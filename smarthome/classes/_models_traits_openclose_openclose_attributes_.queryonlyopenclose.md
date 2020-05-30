[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/openclose/openclose_attributes"](../modules/_models_traits_openclose_openclose_attributes_.md) › [QueryOnlyOpenClose](_models_traits_openclose_openclose_attributes_.queryonlyopenclose.md)

# Class: QueryOnlyOpenClose

Boolean. Optional. Indicates if the device can only be queried for state information and cannot be controlled. Sensors that can only report open state should set this field to true.

## Hierarchy

* [Attribute](_models_core_.attribute.md)

  ↳ **QueryOnlyOpenClose**

## Implements

* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)
* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)

## Index

### Constructors

* [constructor](_models_traits_openclose_openclose_attributes_.queryonlyopenclose.md#constructor)

### Properties

* [name](_models_traits_openclose_openclose_attributes_.queryonlyopenclose.md#name)
* [value](_models_traits_openclose_openclose_attributes_.queryonlyopenclose.md#value)
* [_name](_models_traits_openclose_openclose_attributes_.queryonlyopenclose.md#static-_name)

### Methods

* [getKeyName](_models_traits_openclose_openclose_attributes_.queryonlyopenclose.md#getkeyname)
* [getName](_models_traits_openclose_openclose_attributes_.queryonlyopenclose.md#getname)
* [getKeyName](_models_traits_openclose_openclose_attributes_.queryonlyopenclose.md#static-getkeyname)
* [getName](_models_traits_openclose_openclose_attributes_.queryonlyopenclose.md#static-getname)

## Constructors

###  constructor

\+ **new QueryOnlyOpenClose**(`value`: QueryOnlyOpenClose["value"]): *[QueryOnlyOpenClose](_models_traits_openclose_openclose_attributes_.queryonlyopenclose.md)*

*Defined in [src/models/traits/openclose/openclose_attributes.ts:47](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_attributes.ts#L47)*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`value` | QueryOnlyOpenClose["value"] | boolean  |

**Returns:** *[QueryOnlyOpenClose](_models_traits_openclose_openclose_attributes_.queryonlyopenclose.md)*

## Properties

###  name

• **name**: *"queryOnlyOpenClose"* = QueryOnlyOpenClose._name

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[name](../interfaces/_models_interfaces_i_core_.attribute.md#name)*

*Overrides [Attribute](_models_core_.attribute.md).[name](_models_core_.attribute.md#name)*

*Defined in [src/models/traits/openclose/openclose_attributes.ts:46](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_attributes.ts#L46)*

___

###  value

• **value**: *QueryOnlyOpenClose["value"]* = false

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[value](../interfaces/_models_interfaces_i_core_.attribute.md#value)*

*Overrides [Attribute](_models_core_.attribute.md).[value](_models_core_.attribute.md#value)*

*Defined in [src/models/traits/openclose/openclose_attributes.ts:47](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_attributes.ts#L47)*

___

### `Static` _name

▪ **_name**: *"queryOnlyOpenClose"* = "queryOnlyOpenClose"

*Overrides [Attribute](_models_core_.attribute.md).[_name](_models_core_.attribute.md#static-_name)*

*Defined in [src/models/traits/openclose/openclose_attributes.ts:45](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_attributes.ts#L45)*

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
