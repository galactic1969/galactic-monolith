[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/volume/volume_attributes"](../modules/_models_traits_volume_volume_attributes_.md) › [VolumeDefaultPercentage](_models_traits_volume_volume_attributes_.volumedefaultpercentage.md)

# Class: VolumeDefaultPercentage

The volume (in percentage) for the default volume as defined by the user or manufacturer. The scale must be 0-100.

## Hierarchy

* [Attribute](_models_core_.attribute.md)

  ↳ **VolumeDefaultPercentage**

## Implements

* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)
* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)

## Index

### Constructors

* [constructor](_models_traits_volume_volume_attributes_.volumedefaultpercentage.md#constructor)

### Properties

* [name](_models_traits_volume_volume_attributes_.volumedefaultpercentage.md#name)
* [value](_models_traits_volume_volume_attributes_.volumedefaultpercentage.md#value)
* [_name](_models_traits_volume_volume_attributes_.volumedefaultpercentage.md#static-_name)

### Methods

* [getKeyName](_models_traits_volume_volume_attributes_.volumedefaultpercentage.md#getkeyname)
* [getName](_models_traits_volume_volume_attributes_.volumedefaultpercentage.md#getname)
* [getKeyName](_models_traits_volume_volume_attributes_.volumedefaultpercentage.md#static-getkeyname)
* [getName](_models_traits_volume_volume_attributes_.volumedefaultpercentage.md#static-getname)

## Constructors

###  constructor

\+ **new VolumeDefaultPercentage**(`value`: VolumeDefaultPercentage["value"]): *[VolumeDefaultPercentage](_models_traits_volume_volume_attributes_.volumedefaultpercentage.md)*

*Defined in [src/models/traits/volume/volume_attributes.ts:47](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_attributes.ts#L47)*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`value` | VolumeDefaultPercentage["value"] | The volume (in percentage) for the default volume as defined by the user or manufacturer. The scale must be 0-100.  |

**Returns:** *[VolumeDefaultPercentage](_models_traits_volume_volume_attributes_.volumedefaultpercentage.md)*

## Properties

###  name

• **name**: *"volumeDefaultPercentage"* = VolumeDefaultPercentage._name

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[name](../interfaces/_models_interfaces_i_core_.attribute.md#name)*

*Overrides [Attribute](_models_core_.attribute.md).[name](_models_core_.attribute.md#name)*

*Defined in [src/models/traits/volume/volume_attributes.ts:46](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_attributes.ts#L46)*

___

###  value

• **value**: *VolumeDefaultPercentage["value"]* = 30

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[value](../interfaces/_models_interfaces_i_core_.attribute.md#value)*

*Overrides [Attribute](_models_core_.attribute.md).[value](_models_core_.attribute.md#value)*

*Defined in [src/models/traits/volume/volume_attributes.ts:47](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_attributes.ts#L47)*

___

### `Static` _name

▪ **_name**: *"volumeDefaultPercentage"* = "volumeDefaultPercentage"

*Overrides [Attribute](_models_core_.attribute.md).[_name](_models_core_.attribute.md#static-_name)*

*Defined in [src/models/traits/volume/volume_attributes.ts:45](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_attributes.ts#L45)*

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
