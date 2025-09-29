# Home Assistant Blueprints

Smart blueprints for Home Assistant automation.

## Blueprints

### Smart HVAC Control with Energy Price & Solar

Controls HVAC systems based on:
- Room temperature
- Electricity price
- Solar energy surplus
- Smart fan control with boost mode

#### Features
- ✅ Heat/Off mode control
- ✅ Electricity price optimization
- ✅ Solar energy utilization
- ✅ Smart fan boost for quick heating
- ✅ Configurable thresholds

#### Required Sensors
- Temperature sensor
- HVAC climate entity
- Solar energy surplus sensor (W)
- Electricity price sensor with `current_price` attribute

#### Installation
1. In Home Assistant, go to **Settings** → **Automations** → **Create Automation**
2. Click **Use blueprint** → **URL**
3. Paste: `https://github.com/ditt-användarnamn/home-assistant-blueprints/blob/main/climate/smart_hvac_temperature_energy_price_control.yaml`

#### Configuration
- Set your temperature thresholds
- Configure energy and price thresholds
- Choose fan modes for normal and boost operation
