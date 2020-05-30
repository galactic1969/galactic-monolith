[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/inputselector/inputselector_attributes"](../modules/_models_traits_inputselector_inputselector_attributes_.md) › [OrderedInputs](_models_traits_inputselector_inputselector_attributes_.orderedinputs.md)

# Class: OrderedInputs

True if the list of output is ordered. This also indicates that the 'next' and 'previous' functionality is available.

## Hierarchy

* [Attribute](_models_core_.attribute.md)

  ↳ **OrderedInputs**

## Implements

* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)
* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)

## Index

### Constructors

* [constructor](_models_traits_inputselector_inputselector_attributes_.orderedinputs.md#constructor)

### Properties

* [name](_models_traits_inputselector_inputselector_attributes_.orderedinputs.md#name)
* [value](_models_traits_inputselector_inputselector_attributes_.orderedinputs.md#value)
* [_name](_models_traits_inputselector_inputselector_attributes_.orderedinputs.md#static-_name)

### Methods

* [getKeyName](_models_traits_inputselector_inputselector_attributes_.orderedinputs.md#getkeyname)
* [getName](_models_traits_inputselector_inputselector_attributes_.orderedinputs.md#getname)
* [getKeyName](_models_traits_inputselector_inputselector_attributes_.orderedinputs.md#static-getkeyname)
* [getName](_models_traits_inputselector_inputselector_attributes_.orderedinputs.md#static-getname)

## Constructors

###  constructor

\+ **new OrderedInputs**(`value`: OrderedInputs["value"]): *[OrderedInputs](_models_traits_inputselector_inputselector_attributes_.orderedinputs.md)*

*Defined in [src/models/traits/inputselector/inputselector_attributes.ts:29](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/inputselector/inputselector_attributes.ts#L29)*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`value` | OrderedInputs["value"] | True if the list of output is ordered. This also indicates that the 'next' and 'previous' functionality is available.  |

**Returns:** *[OrderedInputs](_models_traits_inputselector_inputselector_attributes_.orderedinputs.md)*

## Properties

###  name

• **name**: *"orderedInputs"* = OrderedInputs._name

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[name](../interfaces/_models_interfaces_i_core_.attribute.md#name)*

*Overrides [Attribute](_models_core_.attribute.md).[name](_models_core_.attribute.md#name)*

*Defined in [src/models/traits/inputselector/inputselector_attributes.ts:28](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/inputselector/inputselector_attributes.ts#L28)*

___

###  value

• **value**: *OrderedInputs["value"]* = false

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[value](../interfaces/_models_interfaces_i_core_.attribute.md#value)*

*Overrides [Attribute](_models_core_.attribute.md).[value](_models_core_.attribute.md#value)*

*Defined in [src/models/traits/inputselector/inputselector_attributes.ts:29](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/inputselector/inputselector_attributes.ts#L29)*

___

### `Static` _name

▪ **_name**: *"orderedInputs"* = "orderedInputs"

*Overrides [Attribute](_models_core_.attribute.md).[_name](_models_core_.attribute.md#static-_name)*

*Defined in [src/models/traits/inputselector/inputselector_attributes.ts:27](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/inputselector/inputselector_attributes.ts#L27)*

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
