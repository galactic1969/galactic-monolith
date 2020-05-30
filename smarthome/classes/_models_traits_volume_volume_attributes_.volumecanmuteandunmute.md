[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/volume/volume_attributes"](../modules/_models_traits_volume_volume_attributes_.md) › [VolumeCanMuteAndUnmute](_models_traits_volume_volume_attributes_.volumecanmuteandunmute.md)

# Class: VolumeCanMuteAndUnmute

Indicates if the device can mute and unmute the volume. Mute is a separate option as the 'mute' behavior takes the volume to 0 while remembering the previous volume, so that unmute restores it. This is reflected in volume state -- if volume is 5, and the user mutes, the volume remains 5 and isMuted is true.

## Hierarchy

* [Attribute](_models_core_.attribute.md)

  ↳ **VolumeCanMuteAndUnmute**

## Implements

* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)
* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)

## Index

### Constructors

* [constructor](_models_traits_volume_volume_attributes_.volumecanmuteandunmute.md#constructor)

### Properties

* [name](_models_traits_volume_volume_attributes_.volumecanmuteandunmute.md#name)
* [value](_models_traits_volume_volume_attributes_.volumecanmuteandunmute.md#value)
* [_name](_models_traits_volume_volume_attributes_.volumecanmuteandunmute.md#static-_name)

### Methods

* [getKeyName](_models_traits_volume_volume_attributes_.volumecanmuteandunmute.md#getkeyname)
* [getName](_models_traits_volume_volume_attributes_.volumecanmuteandunmute.md#getname)
* [getKeyName](_models_traits_volume_volume_attributes_.volumecanmuteandunmute.md#static-getkeyname)
* [getName](_models_traits_volume_volume_attributes_.volumecanmuteandunmute.md#static-getname)

## Constructors

###  constructor

\+ **new VolumeCanMuteAndUnmute**(`value`: VolumeCanMuteAndUnmute["value"]): *[VolumeCanMuteAndUnmute](_models_traits_volume_volume_attributes_.volumecanmuteandunmute.md)*

*Defined in [src/models/traits/volume/volume_attributes.ts:29](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_attributes.ts#L29)*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`value` | VolumeCanMuteAndUnmute["value"] | Indicates if the device can mute and unmute the volume.  |

**Returns:** *[VolumeCanMuteAndUnmute](_models_traits_volume_volume_attributes_.volumecanmuteandunmute.md)*

## Properties

###  name

• **name**: *"volumeCanMuteAndUnmute"* = VolumeCanMuteAndUnmute._name

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[name](../interfaces/_models_interfaces_i_core_.attribute.md#name)*

*Overrides [Attribute](_models_core_.attribute.md).[name](_models_core_.attribute.md#name)*

*Defined in [src/models/traits/volume/volume_attributes.ts:28](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_attributes.ts#L28)*

___

###  value

• **value**: *VolumeCanMuteAndUnmute["value"]* = true

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[value](../interfaces/_models_interfaces_i_core_.attribute.md#value)*

*Overrides [Attribute](_models_core_.attribute.md).[value](_models_core_.attribute.md#value)*

*Defined in [src/models/traits/volume/volume_attributes.ts:29](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_attributes.ts#L29)*

___

### `Static` _name

▪ **_name**: *"volumeCanMuteAndUnmute"* = "volumeCanMuteAndUnmute"

*Overrides [Attribute](_models_core_.attribute.md).[_name](_models_core_.attribute.md#static-_name)*

*Defined in [src/models/traits/volume/volume_attributes.ts:27](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/volume/volume_attributes.ts#L27)*

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
