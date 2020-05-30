[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/interfaces/i_core"](../modules/_models_interfaces_i_core_.md) › [Command](_models_interfaces_i_core_.command.md)

# Interface: Command

## Hierarchy

* **Command**

## Implemented by

* [ActivateScene](../classes/_models_traits_scene_scene_commands_.activatescene.md)
* [ActivateScene](../classes/_models_traits_scene_scene_commands_.activatescene.md)
* [ColorAbsolute](../classes/_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md)
* [ColorAbsolute](../classes/_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md)
* [Command](../classes/_models_core_.command.md)
* [Mute](../classes/_models_traits_volume_volume_commands_.mute.md)
* [Mute](../classes/_models_traits_volume_volume_commands_.mute.md)
* [OnOff](../classes/_models_traits_onoff_onoff_commands_.onoff.md)
* [OnOff](../classes/_models_traits_onoff_onoff_commands_.onoff.md)
* [OpenClose](../classes/_models_traits_openclose_openclose_commands_.openclose.md)
* [OpenClose](../classes/_models_traits_openclose_openclose_commands_.openclose.md)
* [SetInput](../classes/_models_traits_inputselector_inputselector_commands_.setinput.md)
* [SetInput](../classes/_models_traits_inputselector_inputselector_commands_.setinput.md)
* [SetModes](../classes/_models_traits_modes_modes_commands_.setmodes.md)
* [SetModes](../classes/_models_traits_modes_modes_commands_.setmodes.md)
* [SetVolume](../classes/_models_traits_volume_volume_commands_.setvolume.md)
* [SetVolume](../classes/_models_traits_volume_volume_commands_.setvolume.md)
* [TraitDoesNotHaveCommand](../classes/_models_core_.traitdoesnothavecommand.md)
* [VolumeRelative](../classes/_models_traits_volume_volume_commands_.volumerelative.md)
* [VolumeRelative](../classes/_models_traits_volume_volume_commands_.volumerelative.md)

## Index

### Properties

* [name](_models_interfaces_i_core_.command.md#name)
* [param](_models_interfaces_i_core_.command.md#param)

### Methods

* [execute](_models_interfaces_i_core_.command.md#execute)
* [setState](_models_interfaces_i_core_.command.md#setstate)

## Properties

###  name

• **name**: *string*

*Defined in [src/models/interfaces/i_core.ts:78](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_core.ts#L78)*

___

###  param

• **param**: *object*

*Defined in [src/models/interfaces/i_core.ts:79](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_core.ts#L79)*

#### Type declaration:

* **needChallenge**? : *[NeedChallenge](_models_interfaces_i_core_.needchallenge.md)*

## Methods

###  execute

▸ **execute**(`trait`: [Trait](../classes/_models_core_.trait.md), `params`: any, `options`: IntentInterface.ExecuteRequestExecutionOption): *any*

*Defined in [src/models/interfaces/i_core.ts:82](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_core.ts#L82)*

**Parameters:**

Name | Type |
------ | ------ |
`trait` | [Trait](../classes/_models_core_.trait.md) |
`params` | any |
`options` | IntentInterface.ExecuteRequestExecutionOption |

**Returns:** *any*

___

###  setState

▸ **setState**(`trait`: [Trait](../classes/_models_core_.trait.md), `params`: any): *VariableTrait["States"]*

*Defined in [src/models/interfaces/i_core.ts:83](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_core.ts#L83)*

**Parameters:**

Name | Type |
------ | ------ |
`trait` | [Trait](../classes/_models_core_.trait.md) |
`params` | any |

**Returns:** *VariableTrait["States"]*
