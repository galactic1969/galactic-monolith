[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/volume/volume_states"](../modules/_models_traits_volume_volume_states_.md) › [CurrentVolume](_models_traits_volume_volume_states_.currentvolume.md)

# Class: CurrentVolume

## Hierarchy

* [State](_models_core_.state.md)

  ↳ **CurrentVolume**

## Implements

* [State](../interfaces/_models_interfaces_i_core_.state.md)
* [State](../interfaces/_models_interfaces_i_core_.state.md)

## Index

### Constructors

* [constructor](_models_traits_volume_volume_states_.currentvolume.md#constructor)

### Properties

* [name](_models_traits_volume_volume_states_.currentvolume.md#name)
* [value](_models_traits_volume_volume_states_.currentvolume.md#value)
* [_name](_models_traits_volume_volume_states_.currentvolume.md#static-_name)

### Methods

* [getKeyName](_models_traits_volume_volume_states_.currentvolume.md#getkeyname)
* [getName](_models_traits_volume_volume_states_.currentvolume.md#getname)
* [getKeyName](_models_traits_volume_volume_states_.currentvolume.md#static-getkeyname)
* [getName](_models_traits_volume_volume_states_.currentvolume.md#static-getname)

## Constructors

###  constructor

\+ **new CurrentVolume**(`value`: CurrentVolume["value"]): *[CurrentVolume](_models_traits_volume_volume_states_.currentvolume.md)*

*Defined in [src/models/traits/volume/volume_states.ts:8](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_states.ts#L8)*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`value` | CurrentVolume["value"] | The current volume percentage. It must be [0, volumeMaxLevel].  |

**Returns:** *[CurrentVolume](_models_traits_volume_volume_states_.currentvolume.md)*

## Properties

###  name

• **name**: *"currentVolume"* = CurrentVolume._name

*Implementation of [State](../interfaces/_models_interfaces_i_core_.state.md).[name](../interfaces/_models_interfaces_i_core_.state.md#name)*

*Overrides [State](_models_core_.state.md).[name](_models_core_.state.md#name)*

*Defined in [src/models/traits/volume/volume_states.ts:7](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_states.ts#L7)*

___

###  value

• **value**: *CurrentVolume["value"]* = 30

*Implementation of [State](../interfaces/_models_interfaces_i_core_.state.md).[value](../interfaces/_models_interfaces_i_core_.state.md#value)*

*Overrides [State](_models_core_.state.md).[value](_models_core_.state.md#value)*

*Defined in [src/models/traits/volume/volume_states.ts:8](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_states.ts#L8)*

___

### `Static` _name

▪ **_name**: *"currentVolume"* = "currentVolume"

*Overrides [State](_models_core_.state.md).[_name](_models_core_.state.md#static-_name)*

*Defined in [src/models/traits/volume/volume_states.ts:6](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_states.ts#L6)*

## Methods

###  getKeyName

▸ **getKeyName**(): *string*

*Inherited from [Color](_models_traits_colorsetting_colorsetting_states_.color.md).[getKeyName](_models_traits_colorsetting_colorsetting_states_.color.md#static-getkeyname)*

*Defined in [src/models/core.ts:333](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L333)*

get state name in object. it is same as class name. ex: Hoge

**Returns:** *string*

___

###  getName

▸ **getName**(): *string*

*Inherited from [Color](_models_traits_colorsetting_colorsetting_states_.color.md).[getName](_models_traits_colorsetting_colorsetting_states_.color.md#static-getname)*

*Defined in [src/models/core.ts:319](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L319)*

get command name. ex: action.devices.commands.Hoge

**Returns:** *string*

___

### `Static` getKeyName

▸ **getKeyName**(): *string*

*Inherited from [Color](_models_traits_colorsetting_colorsetting_states_.color.md).[getKeyName](_models_traits_colorsetting_colorsetting_states_.color.md#static-getkeyname)*

*Defined in [src/models/core.ts:326](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L326)*

get state name in object. it is same as class name. ex: Hoge

**Returns:** *string*

___

### `Static` getName

▸ **getName**(): *string*

*Inherited from [Color](_models_traits_colorsetting_colorsetting_states_.color.md).[getName](_models_traits_colorsetting_colorsetting_states_.color.md#static-getname)*

*Defined in [src/models/core.ts:312](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L312)*

get command name. ex: action.devices.commands.Hoge

**Returns:** *string*
