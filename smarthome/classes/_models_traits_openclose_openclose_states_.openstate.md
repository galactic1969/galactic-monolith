[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/openclose/openclose_states"](../modules/_models_traits_openclose_openclose_states_.md) › [OpenState](_models_traits_openclose_openclose_states_.openstate.md)

# Class: OpenState

For having multiple opening directions object

## Hierarchy

* [State](_models_core_.state.md)

  ↳ **OpenState**

## Implements

* [State](../interfaces/_models_interfaces_i_core_.state.md)
* [State](../interfaces/_models_interfaces_i_core_.state.md)

## Index

### Constructors

* [constructor](_models_traits_openclose_openclose_states_.openstate.md#constructor)

### Properties

* [name](_models_traits_openclose_openclose_states_.openstate.md#name)
* [_name](_models_traits_openclose_openclose_states_.openstate.md#static-_name)

### Methods

* [getKeyName](_models_traits_openclose_openclose_states_.openstate.md#getkeyname)
* [getName](_models_traits_openclose_openclose_states_.openstate.md#getname)
* [getKeyName](_models_traits_openclose_openclose_states_.openstate.md#static-getkeyname)
* [getName](_models_traits_openclose_openclose_states_.openstate.md#static-getname)

### Object literals

* [value](_models_traits_openclose_openclose_states_.openstate.md#value)

## Constructors

###  constructor

\+ **new OpenState**(`value`: OpenState["value"]): *[OpenState](_models_traits_openclose_openclose_states_.openstate.md)*

*Defined in [src/models/traits/openclose/openclose_states.ts:14](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_states.ts#L14)*

**Parameters:**

Name | Type |
------ | ------ |
`value` | OpenState["value"] |

**Returns:** *[OpenState](_models_traits_openclose_openclose_states_.openstate.md)*

## Properties

###  name

• **name**: *"openState"* = OpenState._name

*Implementation of [State](../interfaces/_models_interfaces_i_core_.state.md).[name](../interfaces/_models_interfaces_i_core_.state.md#name)*

*Overrides [State](_models_core_.state.md).[name](_models_core_.state.md#name)*

*Defined in [src/models/traits/openclose/openclose_states.ts:10](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_states.ts#L10)*

___

### `Static` _name

▪ **_name**: *"openState"* = "openState"

*Overrides [State](_models_core_.state.md).[_name](_models_core_.state.md#static-_name)*

*Defined in [src/models/traits/openclose/openclose_states.ts:9](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_states.ts#L9)*

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

## Object literals

###  value

### ▪ **value**: *object*

*Implementation of [State](../interfaces/_models_interfaces_i_core_.state.md).[value](../interfaces/_models_interfaces_i_core_.state.md#value)*

*Overrides [State](_models_core_.state.md).[value](_models_core_.state.md#value)*

*Defined in [src/models/traits/openclose/openclose_states.ts:11](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_states.ts#L11)*

###  openDirection

• **openDirection**: *"DOWN"* = "DOWN"

*Defined in [src/models/traits/openclose/openclose_states.ts:13](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_states.ts#L13)*

###  openPercent

• **openPercent**: *number* = 0

*Defined in [src/models/traits/openclose/openclose_states.ts:12](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_states.ts#L12)*
