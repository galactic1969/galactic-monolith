[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/interfaces/i_core"](_models_interfaces_i_core_.md)

# External module: "models/interfaces/i_core"

## Index

### Interfaces

* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)
* [Command](../interfaces/_models_interfaces_i_core_.command.md)
* [DesiredExecution](../interfaces/_models_interfaces_i_core_.desiredexecution.md)
* [DeviceInfo](../interfaces/_models_interfaces_i_core_.deviceinfo.md)
* [DeviceName](../interfaces/_models_interfaces_i_core_.devicename.md)
* [NeedChallenge](../interfaces/_models_interfaces_i_core_.needchallenge.md)
* [OtherDeviceId](../interfaces/_models_interfaces_i_core_.otherdeviceid.md)
* [State](../interfaces/_models_interfaces_i_core_.state.md)
* [Trait](../interfaces/_models_interfaces_i_core_.trait.md)
* [TraitImport](../interfaces/_models_interfaces_i_core_.traitimport.md)
* [TraitSchemaImport](../interfaces/_models_interfaces_i_core_.traitschemaimport.md)
* [VariableAttribute](../interfaces/_models_interfaces_i_core_.variableattribute.md)
* [VariableCommand](../interfaces/_models_interfaces_i_core_.variablecommand.md)
* [VariableState](../interfaces/_models_interfaces_i_core_.variablestate.md)
* [VariableTrait](../interfaces/_models_interfaces_i_core_.variabletrait.md)

### Type aliases

* [AttributeClassDefinition](_models_interfaces_i_core_.md#attributeclassdefinition)
* [ChallengeType](_models_interfaces_i_core_.md#challengetype)
* [CommandClassDefinition](_models_interfaces_i_core_.md#commandclassdefinition)
* [ElementClassDefinition](_models_interfaces_i_core_.md#elementclassdefinition)
* [StateClassDefinition](_models_interfaces_i_core_.md#stateclassdefinition)
* [TraitInitParameter](_models_interfaces_i_core_.md#traitinitparameter)
* [VariableTraitInitParameter](_models_interfaces_i_core_.md#variabletraitinitparameter)

## Type aliases

###  AttributeClassDefinition

Ƭ **AttributeClassDefinition**: *object*

*Defined in [src/models/interfaces/i_core.ts:94](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_core.ts#L94)*

#### Type declaration:

* **new __type**(`value`: any): *any*

* **getName**(): *string*

___

###  ChallengeType

Ƭ **ChallengeType**: *"pin" | "ack"*

*Defined in [src/models/interfaces/i_core.ts:70](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_core.ts#L70)*

___

###  CommandClassDefinition

Ƭ **CommandClassDefinition**: *object*

*Defined in [src/models/interfaces/i_core.ts:96](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_core.ts#L96)*

#### Type declaration:

* **new __type**(`init`: any): *any*

* **getName**(): *string*

___

###  ElementClassDefinition

Ƭ **ElementClassDefinition**: *object*

*Defined in [src/models/interfaces/i_core.ts:93](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_core.ts#L93)*

#### Type declaration:

* **new __type**(`value`: any): *any*

* **getName**(): *string*

___

###  StateClassDefinition

Ƭ **StateClassDefinition**: *object*

*Defined in [src/models/interfaces/i_core.ts:95](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_core.ts#L95)*

#### Type declaration:

* **new __type**(`value`: any): *any*

* **getName**(): *string*

___

###  TraitInitParameter

Ƭ **TraitInitParameter**: *Pick‹[Trait](../interfaces/_models_interfaces_i_core_.trait.md), "Attributes" | "Commands" | "States"›*

*Defined in [src/models/interfaces/i_core.ts:38](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_core.ts#L38)*

___

###  VariableTraitInitParameter

Ƭ **VariableTraitInitParameter**: *Omit‹[VariableTrait](../interfaces/_models_interfaces_i_core_.variabletrait.md), "name"›*

*Defined in [src/models/interfaces/i_core.ts:28](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_core.ts#L28)*
