[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/colorsetting/colorsetting_attributes"](../modules/_models_traits_colorsetting_colorsetting_attributes_.md) › [ColorTemperatureRange](_models_traits_colorsetting_colorsetting_attributes_.colortemperaturerange.md)

# Class: ColorTemperatureRange

Attribute description

## Hierarchy

* [Attribute](_models_core_.attribute.md)

  ↳ **ColorTemperatureRange**

## Implements

* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)
* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)

## Index

### Constructors

* [constructor](_models_traits_colorsetting_colorsetting_attributes_.colortemperaturerange.md#constructor)

### Properties

* [name](_models_traits_colorsetting_colorsetting_attributes_.colortemperaturerange.md#name)
* [_name](_models_traits_colorsetting_colorsetting_attributes_.colortemperaturerange.md#static-_name)

### Methods

* [getKeyName](_models_traits_colorsetting_colorsetting_attributes_.colortemperaturerange.md#getkeyname)
* [getName](_models_traits_colorsetting_colorsetting_attributes_.colortemperaturerange.md#getname)
* [getKeyName](_models_traits_colorsetting_colorsetting_attributes_.colortemperaturerange.md#static-getkeyname)
* [getName](_models_traits_colorsetting_colorsetting_attributes_.colortemperaturerange.md#static-getname)

### Object literals

* [value](_models_traits_colorsetting_colorsetting_attributes_.colortemperaturerange.md#value)

## Constructors

###  constructor

\+ **new ColorTemperatureRange**(`value`: ColorTemperatureRange["value"]): *[ColorTemperatureRange](_models_traits_colorsetting_colorsetting_attributes_.colortemperaturerange.md)*

*Defined in [src/models/traits/colorsetting/colorsetting_attributes.ts:32](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_attributes.ts#L32)*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`value` | ColorTemperatureRange["value"] | Object. Required if the device supports color temperature set by Kelvin. Required if the colorModel attribute is not set. Contains the minimum and maximum values in Kelvin supported by the device. Note that colorTemperatureRange may exist when colorModel is rgb or hsv if the device supports both temperature and a full spectrum color model.  |

**Returns:** *[ColorTemperatureRange](_models_traits_colorsetting_colorsetting_attributes_.colortemperaturerange.md)*

## Properties

###  name

• **name**: *"colorTemperatureRange"* = ColorTemperatureRange._name

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[name](../interfaces/_models_interfaces_i_core_.attribute.md#name)*

*Overrides [Attribute](_models_core_.attribute.md).[name](_models_core_.attribute.md#name)*

*Defined in [src/models/traits/colorsetting/colorsetting_attributes.ts:28](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_attributes.ts#L28)*

___

### `Static` _name

▪ **_name**: *"colorTemperatureRange"* = "colorTemperatureRange"

*Overrides [Attribute](_models_core_.attribute.md).[_name](_models_core_.attribute.md#static-_name)*

*Defined in [src/models/traits/colorsetting/colorsetting_attributes.ts:27](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_attributes.ts#L27)*

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

## Object literals

###  value

### ▪ **value**: *object*

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[value](../interfaces/_models_interfaces_i_core_.attribute.md#value)*

*Overrides [Attribute](_models_core_.attribute.md).[value](_models_core_.attribute.md#value)*

*Defined in [src/models/traits/colorsetting/colorsetting_attributes.ts:29](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_attributes.ts#L29)*

###  temperatureMaxK

• **temperatureMaxK**: *number* = 255

*Defined in [src/models/traits/colorsetting/colorsetting_attributes.ts:30](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_attributes.ts#L30)*

###  temperatureMinK

• **temperatureMinK**: *number* = 0

*Defined in [src/models/traits/colorsetting/colorsetting_attributes.ts:31](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_attributes.ts#L31)*
