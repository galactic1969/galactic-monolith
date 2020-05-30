[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/volume/volume_attributes"](../modules/_models_traits_volume_volume_attributes_.md) › [LevelStepSize](_models_traits_volume_volume_attributes_.levelstepsize.md)

# Class: LevelStepSize

The default step size for relative volume queries like 'volume up on <device_name>'.

## Hierarchy

* [Attribute](_models_core_.attribute.md)

  ↳ **LevelStepSize**

## Implements

* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)
* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)

## Index

### Constructors

* [constructor](_models_traits_volume_volume_attributes_.levelstepsize.md#constructor)

### Properties

* [name](_models_traits_volume_volume_attributes_.levelstepsize.md#name)
* [value](_models_traits_volume_volume_attributes_.levelstepsize.md#value)
* [_name](_models_traits_volume_volume_attributes_.levelstepsize.md#static-_name)

### Methods

* [getKeyName](_models_traits_volume_volume_attributes_.levelstepsize.md#getkeyname)
* [getName](_models_traits_volume_volume_attributes_.levelstepsize.md#getname)
* [getKeyName](_models_traits_volume_volume_attributes_.levelstepsize.md#static-getkeyname)
* [getName](_models_traits_volume_volume_attributes_.levelstepsize.md#static-getname)

## Constructors

###  constructor

\+ **new LevelStepSize**(`value`: LevelStepSize["value"]): *[LevelStepSize](_models_traits_volume_volume_attributes_.levelstepsize.md)*

*Defined in [src/models/traits/volume/volume_attributes.ts:68](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_attributes.ts#L68)*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`value` | LevelStepSize["value"] | The default step size for relative volume queries like 'volume up on <device_name>'.  |

**Returns:** *[LevelStepSize](_models_traits_volume_volume_attributes_.levelstepsize.md)*

## Properties

###  name

• **name**: *"levelStepSize"* = LevelStepSize._name

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[name](../interfaces/_models_interfaces_i_core_.attribute.md#name)*

*Overrides [Attribute](_models_core_.attribute.md).[name](_models_core_.attribute.md#name)*

*Defined in [src/models/traits/volume/volume_attributes.ts:67](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_attributes.ts#L67)*

___

###  value

• **value**: *LevelStepSize["value"]* = 1

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[value](../interfaces/_models_interfaces_i_core_.attribute.md#value)*

*Overrides [Attribute](_models_core_.attribute.md).[value](_models_core_.attribute.md#value)*

*Defined in [src/models/traits/volume/volume_attributes.ts:68](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_attributes.ts#L68)*

___

### `Static` _name

▪ **_name**: *"levelStepSize"* = "levelStepSize"

*Overrides [Attribute](_models_core_.attribute.md).[_name](_models_core_.attribute.md#static-_name)*

*Defined in [src/models/traits/volume/volume_attributes.ts:66](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_attributes.ts#L66)*

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
