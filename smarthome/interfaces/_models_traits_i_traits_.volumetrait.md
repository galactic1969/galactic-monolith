[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/i_traits"](../modules/_models_traits_i_traits_.md) › [VolumeTrait](_models_traits_i_traits_.volumetrait.md)

# Interface: VolumeTrait

## Hierarchy

* [VolumeParam](_models_traits_i_traits_.volumeparam.md)

* [BaseTrait](_models_traits_i_traits_.basetrait.md)

  ↳ **VolumeTrait**

## Implemented by

* [Volume](../classes/_models_traits_volume_volume_.volume.md)

## Index

### Properties

* [Attributes](_models_traits_i_traits_.volumetrait.md#attributes)
* [Commands](_models_traits_i_traits_.volumetrait.md#commands)
* [States](_models_traits_i_traits_.volumetrait.md#states)
* [name](_models_traits_i_traits_.volumetrait.md#name)

## Properties

###  Attributes

• **Attributes**: *object*

*Inherited from [VolumeParam](_models_traits_i_traits_.volumeparam.md).[Attributes](_models_traits_i_traits_.volumeparam.md#attributes)*

*Defined in [src/models/traits/i_traits.ts:110](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/i_traits.ts#L110)*

#### Type declaration:

* **CommandOnlyVolume**? : *Schema.Volume.Attribute.CommandOnlyVolume*

* **LevelStepSize**? : *Schema.Volume.Attribute.LevelStepSize*

* **VolumeCanMuteAndUnmute**? : *Schema.Volume.Attribute.VolumeCanMuteAndUnmute*

* **VolumeDefaultPercentage**? : *Schema.Volume.Attribute.VolumeDefaultPercentage*

* **VolumeMaxLevel**? : *Schema.Volume.Attribute.VolumeMaxLevel*

___

###  Commands

• **Commands**: *object*

*Inherited from [VolumeParam](_models_traits_i_traits_.volumeparam.md).[Commands](_models_traits_i_traits_.volumeparam.md#commands)*

*Defined in [src/models/traits/i_traits.ts:117](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/i_traits.ts#L117)*

#### Type declaration:

* **Mute**? : *Schema.Volume.Command.Mute*

* **SetVolume**? : *Schema.Volume.Command.SetVolume*

* **VolumeRelative**? : *Schema.Volume.Command.VolumeRelative*

___

###  States

• **States**: *object*

*Inherited from [VolumeParam](_models_traits_i_traits_.volumeparam.md).[States](_models_traits_i_traits_.volumeparam.md#states)*

*Defined in [src/models/traits/i_traits.ts:122](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/i_traits.ts#L122)*

#### Type declaration:

* **CurrentVolume**? : *Schema.Volume.State.CurrentVolume*

* **IsMuted**? : *Schema.Volume.State.IsMuted*

___

###  name

• **name**: *string*

*Inherited from [BaseTrait](_models_traits_i_traits_.basetrait.md).[name](_models_traits_i_traits_.basetrait.md#name)*

*Defined in [src/models/traits/i_traits.ts:4](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/i_traits.ts#L4)*
