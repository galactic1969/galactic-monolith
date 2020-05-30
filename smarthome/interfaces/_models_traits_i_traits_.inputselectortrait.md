[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/i_traits"](../modules/_models_traits_i_traits_.md) › [InputSelectorTrait](_models_traits_i_traits_.inputselectortrait.md)

# Interface: InputSelectorTrait

## Hierarchy

* [InputSelectorParam](_models_traits_i_traits_.inputselectorparam.md)

* [BaseTrait](_models_traits_i_traits_.basetrait.md)

  ↳ **InputSelectorTrait**

## Implemented by

* [InputSelector](../classes/_models_traits_inputselector_inputselector_.inputselector.md)

## Index

### Properties

* [Attributes](_models_traits_i_traits_.inputselectortrait.md#attributes)
* [Commands](_models_traits_i_traits_.inputselectortrait.md#commands)
* [States](_models_traits_i_traits_.inputselectortrait.md#states)
* [name](_models_traits_i_traits_.inputselectortrait.md#name)

## Properties

###  Attributes

• **Attributes**: *object*

*Inherited from [InputSelectorParam](_models_traits_i_traits_.inputselectorparam.md).[Attributes](_models_traits_i_traits_.inputselectorparam.md#attributes)*

*Defined in [src/models/traits/i_traits.ts:24](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/i_traits.ts#L24)*

#### Type declaration:

* **AvailableInputs**? : *Schema.InputSelector.Attribute.AvailableInputs‹string›*

* **OrderedInputs**? : *Schema.InputSelector.Attribute.OrderedInputs*

___

###  Commands

• **Commands**: *object*

*Inherited from [InputSelectorParam](_models_traits_i_traits_.inputselectorparam.md).[Commands](_models_traits_i_traits_.inputselectorparam.md#commands)*

*Defined in [src/models/traits/i_traits.ts:28](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/i_traits.ts#L28)*

#### Type declaration:

* **SetInput**? : *Schema.InputSelector.Command.SetInput‹string›*

___

###  States

• **States**: *object*

*Inherited from [InputSelectorParam](_models_traits_i_traits_.inputselectorparam.md).[States](_models_traits_i_traits_.inputselectorparam.md#states)*

*Defined in [src/models/traits/i_traits.ts:31](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/i_traits.ts#L31)*

#### Type declaration:

* **CurrentInput**? : *Schema.InputSelector.State.CurrentInput‹string›*

___

###  name

• **name**: *string*

*Inherited from [BaseTrait](_models_traits_i_traits_.basetrait.md).[name](_models_traits_i_traits_.basetrait.md#name)*

*Defined in [src/models/traits/i_traits.ts:4](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/i_traits.ts#L4)*
