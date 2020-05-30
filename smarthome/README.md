[google-smarthome-models](README.md) › [Globals](globals.md)

# google-smarthome-models

# Google Smarthome Models

## DeviceTypes

All DeviceTypes is supported.

- action.devices.types.AC_UNIT
- action.devices.types.AIRFRESHENER
- action.devices.types.AIRPURIFIER
- action.devices.types.AWNING
- action.devices.types.BATHTUB
- action.devices.types.BED (May 4, 2020)
- action.devices.types.BLENDER (May 4, 2020)
- action.devices.types.BLINDS
- action.devices.types.BOILER
- action.devices.types.CAMERA
- action.devices.types.CARBON_MONOXIDE_DETECTOR (May 4, 2020)
- action.devices.types.CHARGER (May 4, 2020)
- action.devices.types.CLOSET (May 4, 2020)
- action.devices.types.COFFEE_MAKER
- action.devices.types.COOKTOP (May 4, 2020)
- action.devices.types.CURTAIN
- action.devices.types.DEHUMIDIFIER
- action.devices.types.DEHYDRATOR (May 4, 2020)
- action.devices.types.DISHWASHER
- action.devices.types.DOOR
- action.devices.types.DRAWER (May 4, 2020)
- action.devices.types.DRYER
- action.devices.types.FAN
- action.devices.types.FAUCET
- action.devices.types.FIREPLACE
- action.devices.types.FRYER (May 4, 2020)
- action.devices.types.GARAGE
- action.devices.types.GATE
- action.devices.types.GRILL (May 4, 2020)
- action.devices.types.HEATER
- action.devices.types.HOOD
- action.devices.types.HUMIDIFIER
- action.devices.types.KETTLE
- action.devices.types.LIGHT
- action.devices.types.LOCK
- action.devices.types.REMOTECONTROL (May 4, 2020)
- action.devices.types.MOP
- action.devices.types.MOWER (May 4, 2020)
- action.devices.types.MICROWAVE
- action.devices.types.MULTICOOKER (May 4, 2020)
- action.devices.types.NETWORK (May 4, 2020)
- action.devices.types.OUTLET
- action.devices.types.OVEN
- action.devices.types.PERGOLA
- action.devices.types.PETFEEDER (May 4, 2020)
- action.devices.types.PRESSURECOOKER (May 4, 2020)
- action.devices.types.RADIATOR (May 4, 2020)
- action.devices.types.REFRIGERATOR
- action.devices.types.ROUTER (May 4, 2020)
- action.devices.types.SCENE
- action.devices.types.SENSOR (May 4, 2020)
- action.devices.types.SECURITYSYSTEM
- action.devices.types.SETTOP (May 4, 2020)
- action.devices.types.SHUTTER
- action.devices.types.SHOWER
- action.devices.types.SMOKE_DETECTOR (May 4, 2020)
- action.devices.types.SOURSVIDE (May 4, 2020)
- action.devices.types.SPRINKLER
- action.devices.types.SWITCH
- action.devices.types.TV (May 4, 2020)
- action.devices.types.THERMOSTAT
- action.devices.types.VACUUM
- action.devices.types.VALVE
- action.devices.types.WASHER
- action.devices.types.WATERHEATER
- action.devices.types.WATERPURIFIER (May 4, 2020)
- action.devices.types.WARTERSOFTENER (May 4, 2020)
- action.devices.types.WINDOW
- action.devices.types.YOGURTMAKER (May 4, 2020)

## Traits

### Available

- [x] action.devices.traits.ColorSetting
- [x] action.devices.traits.InputSelector (May 4, 2020)
- [x] action.devices.traits.Modes
- [x] action.devices.traits.OnOff
- [x] action.devices.traits.OpenClose
- [x] action.devices.traits.Scene
- [x] action.devices.traits.StatusReport
- [x] action.devices.traits.Volume (May 4, 2020)

### InProgress

- [ ] action.devices.traits.EnergyStorage (May 4, 2020)
- [ ] action.devices.traits.SensorState (May 4, 2020)

### Waiting

- [ ] action.devices.traits.AppSelector (May 4, 2020 english only)
- [ ] action.devices.traits.ArmDisarm
- [ ] action.devices.traits.Brightness
- [ ] action.devices.traits.CameraStream
- [ ] action.devices.traits.Cook
- [ ] action.devices.traits.Dispense
- [ ] action.devices.traits.Dock
- [ ] action.devices.traits.FanSpeed
- [ ] action.devices.traits.Fill
- [ ] action.devices.traits.HumiditySetting
- [ ] action.devices.traits.LightEffects
- [ ] action.devices.traits.Locator
- [ ] action.devices.traits.LockUnlock
- [ ] action.devices.traits.MediaState (May 4, 2020)
- [ ] action.devices.traits.NetworkControl (May 4, 2020)
- [ ] action.devices.traits.Reboot
- [ ] action.devices.traits.Rotation
- [ ] action.devices.traits.RunCycle
- [ ] action.devices.traits.SoftwareUpdate
- [ ] action.devices.traits.StartStop
- [ ] action.devices.traits.TemperatureControl
- [ ] action.devices.traits.TemperatureSetting
- [ ] action.devices.traits.Timer
- [ ] action.devices.traits.Toggles
- [ ] action.devices.traits.TransportControl (May 4, 2020)

### Frozen

Deprecated Traits.

- [ ] action.devices.traits.ColorSpectrum
- [ ] action.devices.traits.ColorTemperature

## Features

### Available

- validate in creation of trait instance

### InProgress

None

### Waiting

- validate in creation of attribute, state, command instance

## How to add new trait

```sh
./scripts/createtrait/create.sh

input trait name in lowercase to create. : [trait name in lowercase]
```
