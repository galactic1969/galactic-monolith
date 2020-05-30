[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/i_traits"](../modules/_models_traits_i_traits_.md) › [InputSelectorParam](_models_traits_i_traits_.inputselectorparam.md)

# Interface: InputSelectorParam

## Hierarchy

* **InputSelectorParam**

  ↳ [InputSelectorTrait](_models_traits_i_traits_.inputselectortrait.md)

## Index

### Properties

* [Attributes](_models_traits_i_traits_.inputselectorparam.md#attributes)
* [Commands](_models_traits_i_traits_.inputselectorparam.md#commands)
* [States](_models_traits_i_traits_.inputselectorparam.md#states)

## Properties

###  Attributes

• **Attributes**: *object*

*Defined in [src/models/traits/i_traits.ts:24](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/i_traits.ts#L24)*

#### Type declaration:

* **AvailableInputs**? : *Schema.InputSelector.Attribute.AvailableInputs‹string›*

* **OrderedInputs**? : *Schema.InputSelector.Attribute.OrderedInputs*

___

###  Commands

• **Commands**: *object*

*Defined in [src/models/traits/i_traits.ts:28](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/i_traits.ts#L28)*

#### Type declaration:

* **SetInput**? : *Schema.InputSelector.Command.SetInput‹string›*

___

###  States

• **States**: *object*

*Defined in [src/models/traits/i_traits.ts:31](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/i_traits.ts#L31)*

#### Type declaration:

* **CurrentInput**? : *Schema.InputSelector.State.CurrentInput‹string›*
