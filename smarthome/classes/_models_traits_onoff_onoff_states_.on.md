[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/onoff/onoff_states"](../modules/_models_traits_onoff_onoff_states_.md) › [On](_models_traits_onoff_onoff_states_.on.md)

# Class: On

## Hierarchy

* [State](_models_core_.state.md)

  ↳ **On**

## Implements

* [State](../interfaces/_models_interfaces_i_core_.state.md)
* [State](../interfaces/_models_interfaces_i_core_.state.md)

## Index

### Constructors

* [constructor](_models_traits_onoff_onoff_states_.on.md#constructor)

### Properties

* [name](_models_traits_onoff_onoff_states_.on.md#name)
* [value](_models_traits_onoff_onoff_states_.on.md#value)
* [_name](_models_traits_onoff_onoff_states_.on.md#static-_name)

### Methods

* [getKeyName](_models_traits_onoff_onoff_states_.on.md#getkeyname)
* [getName](_models_traits_onoff_onoff_states_.on.md#getname)
* [getKeyName](_models_traits_onoff_onoff_states_.on.md#static-getkeyname)
* [getName](_models_traits_onoff_onoff_states_.on.md#static-getname)

## Constructors

###  constructor

\+ **new On**(`value`: On["value"]): *[On](_models_traits_onoff_onoff_states_.on.md)*

*Defined in [src/models/traits/onoff/onoff_states.ts:8](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/onoff/onoff_states.ts#L8)*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`value` | On["value"] | Boolean. Whether a device with an on/off switch is on or off.  |

**Returns:** *[On](_models_traits_onoff_onoff_states_.on.md)*

## Properties

###  name

• **name**: *"on"* = On._name

*Implementation of [State](../interfaces/_models_interfaces_i_core_.state.md).[name](../interfaces/_models_interfaces_i_core_.state.md#name)*

*Overrides [State](_models_core_.state.md).[name](_models_core_.state.md#name)*

*Defined in [src/models/traits/onoff/onoff_states.ts:7](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/onoff/onoff_states.ts#L7)*

___

###  value

• **value**: *On["value"]* = true

*Implementation of [State](../interfaces/_models_interfaces_i_core_.state.md).[value](../interfaces/_models_interfaces_i_core_.state.md#value)*

*Overrides [State](_models_core_.state.md).[value](_models_core_.state.md#value)*

*Defined in [src/models/traits/onoff/onoff_states.ts:8](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/onoff/onoff_states.ts#L8)*

___

### `Static` _name

▪ **_name**: *"on"* = "on"

*Overrides [State](_models_core_.state.md).[_name](_models_core_.state.md#static-_name)*

*Defined in [src/models/traits/onoff/onoff_states.ts:6](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/onoff/onoff_states.ts#L6)*

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
