[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/colorsetting/colorsetting_attributes"](../modules/_models_traits_colorsetting_colorsetting_attributes_.md) › [ColorModel](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md)

# Class: ColorModel

Attribute description

## Hierarchy

* [Attribute](_models_core_.attribute.md)

  ↳ **ColorModel**

## Implements

* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)
* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)

## Index

### Constructors

* [constructor](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md#constructor)

### Properties

* [name](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md#name)
* [value](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md#value)
* [_name](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md#static-_name)

### Methods

* [getKeyName](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md#getkeyname)
* [getName](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md#getname)
* [getKeyName](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md#static-getkeyname)
* [getName](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md#static-getname)

## Constructors

###  constructor

\+ **new ColorModel**(`value`: ColorModel["value"]): *[ColorModel](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md)*

*Defined in [src/models/traits/colorsetting/colorsetting_attributes.ts:11](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_attributes.ts#L11)*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`value` | ColorModel["value"] | String. Required if the device supports the full spectrum color model. Required if the colorTemperatureRange attribute is not set. Must be set to exactly one of the following values:  |

**Returns:** *[ColorModel](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md)*

## Properties

###  name

• **name**: *"colorModel"* = ColorModel._name

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[name](../interfaces/_models_interfaces_i_core_.attribute.md#name)*

*Overrides [Attribute](_models_core_.attribute.md).[name](_models_core_.attribute.md#name)*

*Defined in [src/models/traits/colorsetting/colorsetting_attributes.ts:10](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_attributes.ts#L10)*

___

###  value

• **value**: *ColorModel["value"]* = "rgb"

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[value](../interfaces/_models_interfaces_i_core_.attribute.md#value)*

*Overrides [Attribute](_models_core_.attribute.md).[value](_models_core_.attribute.md#value)*

*Defined in [src/models/traits/colorsetting/colorsetting_attributes.ts:11](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_attributes.ts#L11)*

___

### `Static` _name

▪ **_name**: *"colorModel"* = "colorModel"

*Overrides [Attribute](_models_core_.attribute.md).[_name](_models_core_.attribute.md#static-_name)*

*Defined in [src/models/traits/colorsetting/colorsetting_attributes.ts:9](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/colorsetting/colorsetting_attributes.ts#L9)*

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
