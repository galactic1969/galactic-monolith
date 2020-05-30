[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/inputselector/inputselector_states"](../modules/_models_traits_inputselector_inputselector_states_.md) › [CurrentInput](_models_traits_inputselector_inputselector_states_.currentinput.md)

# Class: CurrentInput <**T**>

## Type parameters

▪ **T**: *string*

## Hierarchy

* [State](_models_core_.state.md)

  ↳ **CurrentInput**

## Implements

* [State](../interfaces/_models_interfaces_i_core_.state.md)
* [State](../interfaces/_models_interfaces_i_core_.state.md)

## Index

### Constructors

* [constructor](_models_traits_inputselector_inputselector_states_.currentinput.md#constructor)

### Properties

* [name](_models_traits_inputselector_inputselector_states_.currentinput.md#name)
* [value](_models_traits_inputselector_inputselector_states_.currentinput.md#value)
* [_name](_models_traits_inputselector_inputselector_states_.currentinput.md#static-_name)

### Methods

* [getKeyName](_models_traits_inputselector_inputselector_states_.currentinput.md#getkeyname)
* [getName](_models_traits_inputselector_inputselector_states_.currentinput.md#getname)
* [getKeyName](_models_traits_inputselector_inputselector_states_.currentinput.md#static-getkeyname)
* [getName](_models_traits_inputselector_inputselector_states_.currentinput.md#static-getname)

## Constructors

###  constructor

\+ **new CurrentInput**(`value`: CurrentInput<T>["value"]): *[CurrentInput](_models_traits_inputselector_inputselector_states_.currentinput.md)*

*Defined in [src/models/traits/inputselector/inputselector_states.ts:8](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/inputselector/inputselector_states.ts#L8)*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`value` | CurrentInput<T>["value"] | Key of the input currently in use.  |

**Returns:** *[CurrentInput](_models_traits_inputselector_inputselector_states_.currentinput.md)*

## Properties

###  name

• **name**: *"currentInput"* = CurrentInput._name

*Implementation of [State](../interfaces/_models_interfaces_i_core_.state.md).[name](../interfaces/_models_interfaces_i_core_.state.md#name)*

*Overrides [State](_models_core_.state.md).[name](_models_core_.state.md#name)*

*Defined in [src/models/traits/inputselector/inputselector_states.ts:7](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/inputselector/inputselector_states.ts#L7)*

___

###  value

• **value**: *CurrentInput<T>["value"]*

*Implementation of [State](../interfaces/_models_interfaces_i_core_.state.md).[value](../interfaces/_models_interfaces_i_core_.state.md#value)*

*Overrides [State](_models_core_.state.md).[value](_models_core_.state.md#value)*

*Defined in [src/models/traits/inputselector/inputselector_states.ts:8](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/inputselector/inputselector_states.ts#L8)*

___

### `Static` _name

▪ **_name**: *"currentInput"* = "currentInput"

*Overrides [State](_models_core_.state.md).[_name](_models_core_.state.md#static-_name)*

*Defined in [src/models/traits/inputselector/inputselector_states.ts:6](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/inputselector/inputselector_states.ts#L6)*

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
