[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/intent"](../modules/_models_intent_.md) › [ExecuteResponseDevice](_models_intent_.executeresponsedevice.md)

# Class: ExecuteResponseDevice

## Hierarchy

  ↳ [IntentResponseDevice](_models_intent_.intentresponsedevice.md)

  ↳ **ExecuteResponseDevice**

## Implements

* [ExecuteResponseDevice](../interfaces/_models_interfaces_i_intent_.executeresponsedevice.md)

## Index

### Constructors

* [constructor](_models_intent_.executeresponsedevice.md#constructor)

### Properties

* [challengeNeeded](_models_intent_.executeresponsedevice.md#optional-challengeneeded)
* [debugString](_models_intent_.executeresponsedevice.md#optional-debugstring)
* [errorCode](_models_intent_.executeresponsedevice.md#optional-errorcode)
* [id](_models_intent_.executeresponsedevice.md#id)
* [states](_models_intent_.executeresponsedevice.md#states)
* [status](_models_intent_.executeresponsedevice.md#status)

### Methods

* [getClassName](_models_intent_.executeresponsedevice.md#getclassname)

## Constructors

###  constructor

\+ **new ExecuteResponseDevice**(`init`: [ExecuteResponseDevice](../interfaces/_models_interfaces_i_intent_.executeresponsedevice.md)): *[ExecuteResponseDevice](_models_intent_.executeresponsedevice.md)*

*Defined in [src/models/intent.ts:306](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L306)*

**Parameters:**

Name | Type |
------ | ------ |
`init` | [ExecuteResponseDevice](../interfaces/_models_interfaces_i_intent_.executeresponsedevice.md) |

**Returns:** *[ExecuteResponseDevice](_models_intent_.executeresponsedevice.md)*

## Properties

### `Optional` challengeNeeded

• **challengeNeeded**? : *ExecuteResult["challengeNeeded"]*

*Implementation of [ExecuteResponseDevice](../interfaces/_models_interfaces_i_intent_.executeresponsedevice.md).[challengeNeeded](../interfaces/_models_interfaces_i_intent_.executeresponsedevice.md#optional-challengeneeded)*

*Defined in [src/models/intent.ts:306](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L306)*

___

### `Optional` debugString

• **debugString**? : *undefined | string*

*Implementation of [ExecuteResponseDevice](../interfaces/_models_interfaces_i_intent_.executeresponsedevice.md).[debugString](../interfaces/_models_interfaces_i_intent_.executeresponsedevice.md#optional-debugstring)*

*Defined in [src/models/intent.ts:305](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L305)*

___

### `Optional` errorCode

• **errorCode**? : *DeviceErrorCode["code"]*

*Implementation of [ExecuteResponseDevice](../interfaces/_models_interfaces_i_intent_.executeresponsedevice.md).[errorCode](../interfaces/_models_interfaces_i_intent_.executeresponsedevice.md#optional-errorcode)*

*Defined in [src/models/intent.ts:304](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L304)*

___

###  id

• **id**: *string* = ""

*Implementation of [ExecuteResponseDevice](../interfaces/_models_interfaces_i_intent_.executeresponsedevice.md).[id](../interfaces/_models_interfaces_i_intent_.executeresponsedevice.md#id)*

*Defined in [src/models/intent.ts:298](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L298)*

___

###  states

• **states**: *object*

*Implementation of [ExecuteResponseDevice](../interfaces/_models_interfaces_i_intent_.executeresponsedevice.md).[states](../interfaces/_models_interfaces_i_intent_.executeresponsedevice.md#states)*

*Defined in [src/models/intent.ts:300](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L300)*

#### Type declaration:

* \[ **index**: *string*\]: any

* **exceptionCode**? : *DeviceStatusCode["code"]*

___

###  status

• **status**: *ExecuteResult["status"]* = "SUCCESS"

*Implementation of [ExecuteResponseDevice](../interfaces/_models_interfaces_i_intent_.executeresponsedevice.md).[status](../interfaces/_models_interfaces_i_intent_.executeresponsedevice.md#status)*

*Defined in [src/models/intent.ts:299](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L299)*

## Methods

###  getClassName

▸ **getClassName**(): *string*

*Inherited from [BaseClass](_models_common_.baseclass.md).[getClassName](_models_common_.baseclass.md#getclassname)*

*Defined in [src/models/common.ts:10](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/common.ts#L10)*

**Returns:** *string*
