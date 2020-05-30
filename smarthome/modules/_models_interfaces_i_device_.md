[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/interfaces/i_device"](_models_interfaces_i_device_.md)

# External module: "models/interfaces/i_device"

## Index

### Interfaces

* [DeviceJson](../interfaces/_models_interfaces_i_device_.devicejson.md)
* [DeviceType](../interfaces/_models_interfaces_i_device_.devicetype.md)
* [Traits](../interfaces/_models_interfaces_i_device_.traits.md)

### Type aliases

* [AnonymousTrait](_models_interfaces_i_device_.md#anonymoustrait)
* [SpecificTrait](_models_interfaces_i_device_.md#specifictrait)
* [TraitKey](_models_interfaces_i_device_.md#traitkey)
* [VariableTrait](_models_interfaces_i_device_.md#variabletrait)
* [VariableTraits](_models_interfaces_i_device_.md#variabletraits)

## Type aliases

###  AnonymousTrait

Ƭ **AnonymousTrait**: *object*

*Defined in [src/models/interfaces/i_device.ts:26](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_device.ts#L26)*

#### Type declaration:

* **Attributes**(): *object*

* **Commands**(): *object*

* **States**(): *object*

* **name**: *string*

___

###  SpecificTrait

Ƭ **SpecificTrait**: *Exclude‹Traits[TraitKey], undefined›*

*Defined in [src/models/interfaces/i_device.ts:17](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_device.ts#L17)*

___

###  TraitKey

Ƭ **TraitKey**: *keyof Traits*

*Defined in [src/models/interfaces/i_device.ts:16](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_device.ts#L16)*

___

###  VariableTrait

Ƭ **VariableTrait**: *object*

*Defined in [src/models/interfaces/i_device.ts:19](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_device.ts#L19)*

#### Type declaration:

* **Attributes**: *T extends undefined ? object : object[keyof T]*

* **Commands**: *T extends undefined ? object : object[keyof T]*

* **States**: *T extends undefined ? object : object[keyof T]*

* **name**: *string*

___

###  VariableTraits

Ƭ **VariableTraits**: *object*

*Defined in [src/models/interfaces/i_device.ts:33](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_device.ts#L33)*

#### Type declaration:
