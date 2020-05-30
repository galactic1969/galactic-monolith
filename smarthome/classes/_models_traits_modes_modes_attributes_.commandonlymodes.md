[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/modes/modes_attributes"](../modules/_models_traits_modes_modes_attributes_.md) › [CommandOnlyModes](_models_traits_modes_modes_attributes_.commandonlymodes.md)

# Class: CommandOnlyModes

Indicates if the device operates using one-way (true) or two-way (false) communication. For example, if the controller can confirm the new device state after sending the request, this field would be false. If it's not possible to confirm if the request is successfully executed or to get the state of the device, set this field to true.

## Hierarchy

* [Attribute](_models_core_.attribute.md)

  ↳ **CommandOnlyModes**

## Implements

* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)
* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)

## Index

### Constructors

* [constructor](_models_traits_modes_modes_attributes_.commandonlymodes.md#constructor)

### Properties

* [name](_models_traits_modes_modes_attributes_.commandonlymodes.md#name)
* [value](_models_traits_modes_modes_attributes_.commandonlymodes.md#value)
* [_name](_models_traits_modes_modes_attributes_.commandonlymodes.md#static-_name)

### Methods

* [getKeyName](_models_traits_modes_modes_attributes_.commandonlymodes.md#getkeyname)
* [getName](_models_traits_modes_modes_attributes_.commandonlymodes.md#getname)
* [getKeyName](_models_traits_modes_modes_attributes_.commandonlymodes.md#static-getkeyname)
* [getName](_models_traits_modes_modes_attributes_.commandonlymodes.md#static-getname)

## Constructors

###  constructor

\+ **new CommandOnlyModes**(`value`: CommandOnlyModes["value"]): *[CommandOnlyModes](_models_traits_modes_modes_attributes_.commandonlymodes.md)*

*Defined in [src/models/traits/modes/modes_attributes.ts:31](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/modes/modes_attributes.ts#L31)*

Creates an instance of CommandOnlyModes.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`value` | CommandOnlyModes["value"] | Boolean  |

**Returns:** *[CommandOnlyModes](_models_traits_modes_modes_attributes_.commandonlymodes.md)*

## Properties

###  name

• **name**: *"commandOnlyModes"* = CommandOnlyModes._name

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[name](../interfaces/_models_interfaces_i_core_.attribute.md#name)*

*Overrides [Attribute](_models_core_.attribute.md).[name](_models_core_.attribute.md#name)*

*Defined in [src/models/traits/modes/modes_attributes.ts:30](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/modes/modes_attributes.ts#L30)*

___

###  value

• **value**: *CommandOnlyModes["value"]* = false

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[value](../interfaces/_models_interfaces_i_core_.attribute.md#value)*

*Overrides [Attribute](_models_core_.attribute.md).[value](_models_core_.attribute.md#value)*

*Defined in [src/models/traits/modes/modes_attributes.ts:31](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/modes/modes_attributes.ts#L31)*

___

### `Static` _name

▪ **_name**: *"commandOnlyModes"* = "commandOnlyModes"

*Overrides [Attribute](_models_core_.attribute.md).[_name](_models_core_.attribute.md#static-_name)*

*Defined in [src/models/traits/modes/modes_attributes.ts:29](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/modes/modes_attributes.ts#L29)*

## Methods

###  getKeyName

▸ **getKeyName**(): *string*

*Inherited from [ColorModel](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md).[getKeyName](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md#static-getkeyname)*

*Defined in [src/models/core.ts:93](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L93)*

get attribute name in object. it is same as class name. ex: Hoge

**Returns:** *string*

___

###  getName

▸ **getName**(): *string*

*Inherited from [ColorModel](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md).[getName](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md#static-getname)*

*Defined in [src/models/core.ts:79](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L79)*

get attribute name. ex: hoge

**Returns:** *string*

___

### `Static` getKeyName

▸ **getKeyName**(): *string*

*Inherited from [ColorModel](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md).[getKeyName](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md#static-getkeyname)*

*Defined in [src/models/core.ts:86](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L86)*

get attribute name in object. it is same as class name. ex: Hoge

**Returns:** *string*

___

### `Static` getName

▸ **getName**(): *string*

*Inherited from [ColorModel](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md).[getName](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md#static-getname)*

*Defined in [src/models/core.ts:72](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L72)*

get attribute name. ex: hoge

**Returns:** *string*
