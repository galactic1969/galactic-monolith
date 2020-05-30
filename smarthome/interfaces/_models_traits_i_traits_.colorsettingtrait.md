[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/i_traits"](../modules/_models_traits_i_traits_.md) › [ColorSettingTrait](_models_traits_i_traits_.colorsettingtrait.md)

# Interface: ColorSettingTrait

## Hierarchy

* [ColorSettingParam](_models_traits_i_traits_.colorsettingparam.md)

* [BaseTrait](_models_traits_i_traits_.basetrait.md)

  ↳ **ColorSettingTrait**

## Implemented by

* [ColorSetting](../classes/_models_traits_colorsetting_colorsetting_.colorsetting.md)

## Index

### Properties

* [Attributes](_models_traits_i_traits_.colorsettingtrait.md#attributes)
* [Commands](_models_traits_i_traits_.colorsettingtrait.md#commands)
* [States](_models_traits_i_traits_.colorsettingtrait.md#states)
* [name](_models_traits_i_traits_.colorsettingtrait.md#name)

## Properties

###  Attributes

• **Attributes**: *object*

*Inherited from [ColorSettingParam](_models_traits_i_traits_.colorsettingparam.md).[Attributes](_models_traits_i_traits_.colorsettingparam.md#attributes)*

*Defined in [src/models/traits/i_traits.ts:8](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/i_traits.ts#L8)*

#### Type declaration:

* **ColorModel**? : *Schema.ColorSetting.Attribute.ColorModel*

* **ColorTemperatureRange**? : *Schema.ColorSetting.Attribute.ColorTemperatureRange*

* **CommandOnlyColorSetting**? : *Schema.ColorSetting.Attribute.CommandOnlyColorSetting*

___

###  Commands

• **Commands**: *object*

*Inherited from [ColorSettingParam](_models_traits_i_traits_.colorsettingparam.md).[Commands](_models_traits_i_traits_.colorsettingparam.md#commands)*

*Defined in [src/models/traits/i_traits.ts:13](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/i_traits.ts#L13)*

#### Type declaration:

* **ColorAbsolute**? : *Schema.ColorSetting.Command.ColorAbsolute*

___

###  States

• **States**: *object*

*Inherited from [ColorSettingParam](_models_traits_i_traits_.colorsettingparam.md).[States](_models_traits_i_traits_.colorsettingparam.md#states)*

*Defined in [src/models/traits/i_traits.ts:16](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/i_traits.ts#L16)*

#### Type declaration:

* **Color**? : *Schema.ColorSetting.State.Color*

___

###  name

• **name**: *string*

*Inherited from [BaseTrait](_models_traits_i_traits_.basetrait.md).[name](_models_traits_i_traits_.basetrait.md#name)*

*Defined in [src/models/traits/i_traits.ts:4](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/i_traits.ts#L4)*
