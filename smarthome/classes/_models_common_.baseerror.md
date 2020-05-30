[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/common"](../modules/_models_common_.md) › [BaseError](_models_common_.baseerror.md)

# Class: BaseError

## Hierarchy

* [Error](_models_common_.baseerror.md#static-error)

  ↳ **BaseError**

  ↳ [UnknownIntentFormatType](_models_core_.unknownintentformattype.md)

  ↳ [UnknownIntentName](_models_core_.unknownintentname.md)

  ↳ [IntentQueryError](_models_core_.intentqueryerror.md)

  ↳ [UnknownAttributeError](_models_core_.unknownattributeerror.md)

  ↳ [UnknownStateError](_models_core_.unknownstateerror.md)

  ↳ [UnknownCommandError](_models_core_.unknowncommanderror.md)

  ↳ [UnknownTraitError](_models_core_.unknowntraiterror.md)

  ↳ [UnknownChallngeTypeError](_models_core_.unknownchallngetypeerror.md)

  ↳ [UnexpectedChallngeTypeError](_models_core_.unexpectedchallngetypeerror.md)

  ↳ [UnexpectedParameterError](_models_core_.unexpectedparametererror.md)

  ↳ [TraitDoesNotHaveSpecifiedState](_models_core_.traitdoesnothavespecifiedstate.md)

  ↳ [TraitDoesNotHaveSpecifiedElement](_models_core_.traitdoesnothavespecifiedelement.md)

  ↳ [TraitValidationError](_models_core_.traitvalidationerror.md)

  ↳ [NotImplementedError](_models_core_.notimplementederror.md)

  ↳ [OutOfRangeError](_models_core_.outofrangeerror.md)

## Index

### Constructors

* [constructor](_models_common_.baseerror.md#constructor)

### Properties

* [message](_models_common_.baseerror.md#message)
* [name](_models_common_.baseerror.md#name)
* [stack](_models_common_.baseerror.md#optional-stack)
* [Error](_models_common_.baseerror.md#static-error)

## Constructors

###  constructor

\+ **new BaseError**(`e?`: undefined | string): *[BaseError](_models_common_.baseerror.md)*

*Defined in [src/models/common.ts:1](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/common.ts#L1)*

**Parameters:**

Name | Type |
------ | ------ |
`e?` | undefined &#124; string |

**Returns:** *[BaseError](_models_common_.baseerror.md)*

## Properties

###  message

• **message**: *string*

*Inherited from [BaseError](_models_common_.baseerror.md).[message](_models_common_.baseerror.md#message)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:974

___

###  name

• **name**: *string*

*Inherited from [BaseError](_models_common_.baseerror.md).[name](_models_common_.baseerror.md#name)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:973

___

### `Optional` stack

• **stack**? : *undefined | string*

*Inherited from [BaseError](_models_common_.baseerror.md).[stack](_models_common_.baseerror.md#optional-stack)*

*Overrides [BaseError](_models_common_.baseerror.md).[stack](_models_common_.baseerror.md#optional-stack)*

Defined in node_modules/typescript/lib/lib.es5.d.ts:975

___

### `Static` Error

▪ **Error**: *ErrorConstructor*

Defined in node_modules/typescript/lib/lib.es5.d.ts:984
