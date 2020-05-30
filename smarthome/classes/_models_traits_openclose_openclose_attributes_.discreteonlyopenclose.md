[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/openclose/openclose_attributes"](../modules/_models_traits_openclose_openclose_attributes_.md) › [DiscreteOnlyOpenClose](_models_traits_openclose_openclose_attributes_.discreteonlyopenclose.md)

# Class: DiscreteOnlyOpenClose

Boolean. Optional. Defaults to false. When set to true, this indicates that the device must either be fully open or fully closed (that is, it does not support values between 0% and 100%). An example of such a device may be a valve.

## Hierarchy

* [Attribute](_models_core_.attribute.md)

  ↳ **DiscreteOnlyOpenClose**

## Implements

* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)
* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)

## Index

### Constructors

* [constructor](_models_traits_openclose_openclose_attributes_.discreteonlyopenclose.md#constructor)

### Properties

* [name](_models_traits_openclose_openclose_attributes_.discreteonlyopenclose.md#name)
* [value](_models_traits_openclose_openclose_attributes_.discreteonlyopenclose.md#value)
* [_name](_models_traits_openclose_openclose_attributes_.discreteonlyopenclose.md#static-_name)

### Methods

* [getKeyName](_models_traits_openclose_openclose_attributes_.discreteonlyopenclose.md#getkeyname)
* [getName](_models_traits_openclose_openclose_attributes_.discreteonlyopenclose.md#getname)
* [getKeyName](_models_traits_openclose_openclose_attributes_.discreteonlyopenclose.md#static-getkeyname)
* [getName](_models_traits_openclose_openclose_attributes_.discreteonlyopenclose.md#static-getname)

## Constructors

###  constructor

\+ **new DiscreteOnlyOpenClose**(`value`: DiscreteOnlyOpenClose["value"]): *[DiscreteOnlyOpenClose](_models_traits_openclose_openclose_attributes_.discreteonlyopenclose.md)*

*Defined in [src/models/traits/openclose/openclose_attributes.ts:11](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_attributes.ts#L11)*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`value` | DiscreteOnlyOpenClose["value"] | boolean  |

**Returns:** *[DiscreteOnlyOpenClose](_models_traits_openclose_openclose_attributes_.discreteonlyopenclose.md)*

## Properties

###  name

• **name**: *"discreteOnlyOpenClose"* = DiscreteOnlyOpenClose._name

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[name](../interfaces/_models_interfaces_i_core_.attribute.md#name)*

*Overrides [Attribute](_models_core_.attribute.md).[name](_models_core_.attribute.md#name)*

*Defined in [src/models/traits/openclose/openclose_attributes.ts:10](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_attributes.ts#L10)*

___

###  value

• **value**: *DiscreteOnlyOpenClose["value"]* = false

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[value](../interfaces/_models_interfaces_i_core_.attribute.md#value)*

*Overrides [Attribute](_models_core_.attribute.md).[value](_models_core_.attribute.md#value)*

*Defined in [src/models/traits/openclose/openclose_attributes.ts:11](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_attributes.ts#L11)*

___

### `Static` _name

▪ **_name**: *"discreteOnlyOpenClose"* = "discreteOnlyOpenClose"

*Overrides [Attribute](_models_core_.attribute.md).[_name](_models_core_.attribute.md#static-_name)*

*Defined in [src/models/traits/openclose/openclose_attributes.ts:9](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/openclose/openclose_attributes.ts#L9)*

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
