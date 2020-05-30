[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/intent"](../modules/_models_intent_.md) › [ExecuteResult](_models_intent_.executeresult.md)

# Class: ExecuteResult

1デバイスにおけるExecutionの結果

## Hierarchy

* **ExecuteResult**

## Implements

* [ExecuteResult](../interfaces/_models_interfaces_i_intent_.executeresult.md)

## Index

### Constructors

* [constructor](_models_intent_.executeresult.md#constructor)

### Properties

* [challengeNeeded](_models_intent_.executeresult.md#optional-challengeneeded)
* [debugString](_models_intent_.executeresult.md#optional-debugstring)
* [errorCode](_models_intent_.executeresult.md#optional-errorcode)
* [states](_models_intent_.executeresult.md#states)
* [status](_models_intent_.executeresult.md#status)

## Constructors

###  constructor

\+ **new ExecuteResult**(`init`: [ExecuteResult](../interfaces/_models_interfaces_i_intent_.executeresult.md)): *[ExecuteResult](_models_intent_.executeresult.md)*

*Defined in [src/models/intent.ts:261](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L261)*

**Parameters:**

Name | Type |
------ | ------ |
`init` | [ExecuteResult](../interfaces/_models_interfaces_i_intent_.executeresult.md) |

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md)*

## Properties

### `Optional` challengeNeeded

• **challengeNeeded**? : *ExecuteResult["challengeNeeded"]*

*Implementation of [ExecuteResult](../interfaces/_models_interfaces_i_intent_.executeresult.md).[challengeNeeded](../interfaces/_models_interfaces_i_intent_.executeresult.md#optional-challengeneeded)*

*Defined in [src/models/intent.ts:261](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L261)*

___

### `Optional` debugString

• **debugString**? : *undefined | string*

*Implementation of [ExecuteResult](../interfaces/_models_interfaces_i_intent_.executeresult.md).[debugString](../interfaces/_models_interfaces_i_intent_.executeresult.md#optional-debugstring)*

*Defined in [src/models/intent.ts:260](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L260)*

___

### `Optional` errorCode

• **errorCode**? : *DeviceErrorCode["code"]*

*Implementation of [ExecuteResult](../interfaces/_models_interfaces_i_intent_.executeresult.md).[errorCode](../interfaces/_models_interfaces_i_intent_.executeresult.md#optional-errorcode)*

*Defined in [src/models/intent.ts:259](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L259)*

___

###  states

• **states**: *object*

*Implementation of [ExecuteResult](../interfaces/_models_interfaces_i_intent_.executeresult.md).[states](../interfaces/_models_interfaces_i_intent_.executeresult.md#states)*

*Defined in [src/models/intent.ts:255](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L255)*

#### Type declaration:

* \[ **index**: *string*\]: any

* **exceptionCode**? : *DeviceStatusCode["code"]*

___

###  status

• **status**: *ExecuteResult["status"]* = "SUCCESS"

*Implementation of [ExecuteResult](../interfaces/_models_interfaces_i_intent_.executeresult.md).[status](../interfaces/_models_interfaces_i_intent_.executeresult.md#status)*

*Defined in [src/models/intent.ts:254](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L254)*
