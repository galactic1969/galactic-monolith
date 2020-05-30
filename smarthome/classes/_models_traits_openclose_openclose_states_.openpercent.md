[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/openclose/openclose_states"](../modules/_models_traits_openclose_openclose_states_.md) › [OpenPercent](_models_traits_openclose_openclose_states_.openpercent.md)

# Class: OpenPercent

For having Single opening direction object

## Hierarchy

* [State](_models_core_.state.md)

  ↳ **OpenPercent**

## Implements

* [State](../interfaces/_models_interfaces_i_core_.state.md)
* [State](../interfaces/_models_interfaces_i_core_.state.md)

## Index

### Constructors

* [constructor](_models_traits_openclose_openclose_states_.openpercent.md#constructor)

### Properties

* [name](_models_traits_openclose_openclose_states_.openpercent.md#name)
* [value](_models_traits_openclose_openclose_states_.openpercent.md#value)
* [_name](_models_traits_openclose_openclose_states_.openpercent.md#static-_name)

### Methods

* [getKeyName](_models_traits_openclose_openclose_states_.openpercent.md#getkeyname)
* [getName](_models_traits_openclose_openclose_states_.openpercent.md#getname)
* [getKeyName](_models_traits_openclose_openclose_states_.openpercent.md#static-getkeyname)
* [getName](_models_traits_openclose_openclose_states_.openpercent.md#static-getname)

## Constructors

###  constructor

\+ **new OpenPercent**(`value`: OpenPercent["value"]): *[OpenPercent](_models_traits_openclose_openclose_states_.openpercent.md)*

*Defined in [src/models/traits/openclose/openclose_states.ts:33](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_states.ts#L33)*

**Parameters:**

Name | Type |
------ | ------ |
`value` | OpenPercent["value"] |

**Returns:** *[OpenPercent](_models_traits_openclose_openclose_states_.openpercent.md)*

## Properties

###  name

• **name**: *"openPercent"* = OpenPercent._name

*Implementation of [State](../interfaces/_models_interfaces_i_core_.state.md).[name](../interfaces/_models_interfaces_i_core_.state.md#name)*

*Overrides [State](_models_core_.state.md).[name](_models_core_.state.md#name)*

*Defined in [src/models/traits/openclose/openclose_states.ts:32](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_states.ts#L32)*

___

###  value

• **value**: *OpenPercent["value"]* = 0

*Implementation of [State](../interfaces/_models_interfaces_i_core_.state.md).[value](../interfaces/_models_interfaces_i_core_.state.md#value)*

*Overrides [State](_models_core_.state.md).[value](_models_core_.state.md#value)*

*Defined in [src/models/traits/openclose/openclose_states.ts:33](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_states.ts#L33)*

___

### `Static` _name

▪ **_name**: *"openPercent"* = "openPercent"

*Overrides [State](_models_core_.state.md).[_name](_models_core_.state.md#static-_name)*

*Defined in [src/models/traits/openclose/openclose_states.ts:31](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_states.ts#L31)*

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
