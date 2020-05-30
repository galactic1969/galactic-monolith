[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/volume/volume_states"](../modules/_models_traits_volume_volume_states_.md) › [IsMuted](_models_traits_volume_volume_states_.ismuted.md)

# Class: IsMuted

## Hierarchy

* [State](_models_core_.state.md)

  ↳ **IsMuted**

## Implements

* [State](../interfaces/_models_interfaces_i_core_.state.md)
* [State](../interfaces/_models_interfaces_i_core_.state.md)

## Index

### Constructors

* [constructor](_models_traits_volume_volume_states_.ismuted.md#constructor)

### Properties

* [name](_models_traits_volume_volume_states_.ismuted.md#name)
* [value](_models_traits_volume_volume_states_.ismuted.md#value)
* [_name](_models_traits_volume_volume_states_.ismuted.md#static-_name)

### Methods

* [getKeyName](_models_traits_volume_volume_states_.ismuted.md#getkeyname)
* [getName](_models_traits_volume_volume_states_.ismuted.md#getname)
* [getKeyName](_models_traits_volume_volume_states_.ismuted.md#static-getkeyname)
* [getName](_models_traits_volume_volume_states_.ismuted.md#static-getname)

## Constructors

###  constructor

\+ **new IsMuted**(`value`: IsMuted["value"]): *[IsMuted](_models_traits_volume_volume_states_.ismuted.md)*

*Defined in [src/models/traits/volume/volume_states.ts:23](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_states.ts#L23)*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`value` | IsMuted["value"] | Required if volumeCanMuteAndUnmute attribute is set to true. True if the device is muted; false otherwise. If isMuted is true, the device still returns currentVolume for the remembered point.  |

**Returns:** *[IsMuted](_models_traits_volume_volume_states_.ismuted.md)*

## Properties

###  name

• **name**: *"isMuted"* = IsMuted._name

*Implementation of [State](../interfaces/_models_interfaces_i_core_.state.md).[name](../interfaces/_models_interfaces_i_core_.state.md#name)*

*Overrides [State](_models_core_.state.md).[name](_models_core_.state.md#name)*

*Defined in [src/models/traits/volume/volume_states.ts:22](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_states.ts#L22)*

___

###  value

• **value**: *IsMuted["value"]* = false

*Implementation of [State](../interfaces/_models_interfaces_i_core_.state.md).[value](../interfaces/_models_interfaces_i_core_.state.md#value)*

*Overrides [State](_models_core_.state.md).[value](_models_core_.state.md#value)*

*Defined in [src/models/traits/volume/volume_states.ts:23](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_states.ts#L23)*

___

### `Static` _name

▪ **_name**: *"isMuted"* = "isMuted"

*Overrides [State](_models_core_.state.md).[_name](_models_core_.state.md#static-_name)*

*Defined in [src/models/traits/volume/volume_states.ts:21](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_states.ts#L21)*

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
