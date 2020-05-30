[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/i_traits"](../modules/_models_traits_i_traits_.md) › [VolumeParam](_models_traits_i_traits_.volumeparam.md)

# Interface: VolumeParam

## Hierarchy

* **VolumeParam**

  ↳ [VolumeTrait](_models_traits_i_traits_.volumetrait.md)

## Index

### Properties

* [Attributes](_models_traits_i_traits_.volumeparam.md#attributes)
* [Commands](_models_traits_i_traits_.volumeparam.md#commands)
* [States](_models_traits_i_traits_.volumeparam.md#states)

## Properties

###  Attributes

• **Attributes**: *object*

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

*Defined in [src/models/traits/i_traits.ts:117](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/i_traits.ts#L117)*

#### Type declaration:

* **Mute**? : *Schema.Volume.Command.Mute*

* **SetVolume**? : *Schema.Volume.Command.SetVolume*

* **VolumeRelative**? : *Schema.Volume.Command.VolumeRelative*

___

###  States

• **States**: *object*

*Defined in [src/models/traits/i_traits.ts:122](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/i_traits.ts#L122)*

#### Type declaration:

* **CurrentVolume**? : *Schema.Volume.State.CurrentVolume*

* **IsMuted**? : *Schema.Volume.State.IsMuted*
