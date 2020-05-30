[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/colorsetting/colorsetting_states"](../modules/_models_traits_colorsetting_colorsetting_states_.md) › [Color](_models_traits_colorsetting_colorsetting_states_.color.md)

# Class: Color

## Hierarchy

* [State](_models_core_.state.md)

  ↳ **Color**

## Implements

* [State](../interfaces/_models_interfaces_i_core_.state.md)
* [State](../interfaces/_models_interfaces_i_core_.state.md)

## Index

### Constructors

* [constructor](_models_traits_colorsetting_colorsetting_states_.color.md#constructor)

### Properties

* [name](_models_traits_colorsetting_colorsetting_states_.color.md#name)
* [value](_models_traits_colorsetting_colorsetting_states_.color.md#value)
* [_name](_models_traits_colorsetting_colorsetting_states_.color.md#static-_name)

### Methods

* [getKeyName](_models_traits_colorsetting_colorsetting_states_.color.md#getkeyname)
* [getName](_models_traits_colorsetting_colorsetting_states_.color.md#getname)
* [getKeyName](_models_traits_colorsetting_colorsetting_states_.color.md#static-getkeyname)
* [getName](_models_traits_colorsetting_colorsetting_states_.color.md#static-getname)

## Constructors

###  constructor

\+ **new Color**(`value`: Color["value"]): *[Color](_models_traits_colorsetting_colorsetting_states_.color.md)*

*Defined in [src/models/traits/colorsetting/colorsetting_states.ts:9](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_states.ts#L9)*

Object. The current color setting. Must contain exactly one of the following states (whichever is currently being used on the device): @param temperatureK Integer. Value in Kelvin. Used if the device is currently set to a color temperature; for example, "cool white" at 4000 K.

**Parameters:**

Name | Type |
------ | ------ |
`value` | Color["value"] |

**Returns:** *[Color](_models_traits_colorsetting_colorsetting_states_.color.md)*

## Properties

###  name

• **name**: *"color"* = Color._name

*Implementation of [State](../interfaces/_models_interfaces_i_core_.state.md).[name](../interfaces/_models_interfaces_i_core_.state.md#name)*

*Overrides [State](_models_core_.state.md).[name](_models_core_.state.md#name)*

*Defined in [src/models/traits/colorsetting/colorsetting_states.ts:8](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_states.ts#L8)*

___

###  value

• **value**: *Color["value"]*

*Implementation of [State](../interfaces/_models_interfaces_i_core_.state.md).[value](../interfaces/_models_interfaces_i_core_.state.md#value)*

*Overrides [State](_models_core_.state.md).[value](_models_core_.state.md#value)*

*Defined in [src/models/traits/colorsetting/colorsetting_states.ts:9](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_states.ts#L9)*

___

### `Static` _name

▪ **_name**: *"color"* = "color"

*Overrides [State](_models_core_.state.md).[_name](_models_core_.state.md#static-_name)*

*Defined in [src/models/traits/colorsetting/colorsetting_states.ts:6](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_states.ts#L6)*

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
