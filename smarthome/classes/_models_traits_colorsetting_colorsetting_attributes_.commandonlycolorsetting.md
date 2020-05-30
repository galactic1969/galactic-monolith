[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/colorsetting/colorsetting_attributes"](../modules/_models_traits_colorsetting_colorsetting_attributes_.md) › [CommandOnlyColorSetting](_models_traits_colorsetting_colorsetting_attributes_.commandonlycolorsetting.md)

# Class: CommandOnlyColorSetting

Attribute description

## Hierarchy

* [Attribute](_models_core_.attribute.md)

  ↳ **CommandOnlyColorSetting**

## Implements

* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)
* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)

## Index

### Constructors

* [constructor](_models_traits_colorsetting_colorsetting_attributes_.commandonlycolorsetting.md#constructor)

### Properties

* [name](_models_traits_colorsetting_colorsetting_attributes_.commandonlycolorsetting.md#name)
* [value](_models_traits_colorsetting_colorsetting_attributes_.commandonlycolorsetting.md#value)
* [_name](_models_traits_colorsetting_colorsetting_attributes_.commandonlycolorsetting.md#static-_name)

### Methods

* [getKeyName](_models_traits_colorsetting_colorsetting_attributes_.commandonlycolorsetting.md#getkeyname)
* [getName](_models_traits_colorsetting_colorsetting_attributes_.commandonlycolorsetting.md#getname)
* [getKeyName](_models_traits_colorsetting_colorsetting_attributes_.commandonlycolorsetting.md#static-getkeyname)
* [getName](_models_traits_colorsetting_colorsetting_attributes_.commandonlycolorsetting.md#static-getname)

## Constructors

###  constructor

\+ **new CommandOnlyColorSetting**(`value`: CommandOnlyColorSetting["value"]): *[CommandOnlyColorSetting](_models_traits_colorsetting_colorsetting_attributes_.commandonlycolorsetting.md)*

*Defined in [src/models/traits/colorsetting/colorsetting_attributes.ts:50](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_attributes.ts#L50)*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`value` | CommandOnlyColorSetting["value"] | Boolean. Optional. Defaults to false. Indicates if the device supports using one-way (true) or two-way (false) communication. Set this attribute to true if the device cannot respond to a QUERY intent or Report State for this trait.  |

**Returns:** *[CommandOnlyColorSetting](_models_traits_colorsetting_colorsetting_attributes_.commandonlycolorsetting.md)*

## Properties

###  name

• **name**: *"commandOnlyColorSetting"* = CommandOnlyColorSetting._name

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[name](../interfaces/_models_interfaces_i_core_.attribute.md#name)*

*Overrides [Attribute](_models_core_.attribute.md).[name](_models_core_.attribute.md#name)*

*Defined in [src/models/traits/colorsetting/colorsetting_attributes.ts:49](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_attributes.ts#L49)*

___

###  value

• **value**: *CommandOnlyColorSetting["value"]* = false

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[value](../interfaces/_models_interfaces_i_core_.attribute.md#value)*

*Overrides [Attribute](_models_core_.attribute.md).[value](_models_core_.attribute.md#value)*

*Defined in [src/models/traits/colorsetting/colorsetting_attributes.ts:50](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_attributes.ts#L50)*

___

### `Static` _name

▪ **_name**: *"commandOnlyColorSetting"* = "commandOnlyColorSetting"

*Overrides [Attribute](_models_core_.attribute.md).[_name](_models_core_.attribute.md#static-_name)*

*Defined in [src/models/traits/colorsetting/colorsetting_attributes.ts:48](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_attributes.ts#L48)*

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
