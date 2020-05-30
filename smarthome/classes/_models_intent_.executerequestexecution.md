[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/intent"](../modules/_models_intent_.md) › [ExecuteRequestExecution](_models_intent_.executerequestexecution.md)

# Class: ExecuteRequestExecution

## Hierarchy

  ↳ [IntentRequestDevice](_models_intent_.intentrequestdevice.md)

  ↳ **ExecuteRequestExecution**

## Implements

* [ExecuteRequestExecution](../interfaces/_models_interfaces_i_intent_.executerequestexecution.md)

## Index

### Constructors

* [constructor](_models_intent_.executerequestexecution.md#constructor)

### Properties

* [challenge](_models_intent_.executerequestexecution.md#optional-challenge)
* [command](_models_intent_.executerequestexecution.md#command)
* [params](_models_intent_.executerequestexecution.md#params)

### Methods

* [getAcknowledgement](_models_intent_.executerequestexecution.md#getacknowledgement)
* [getChallengeType](_models_intent_.executerequestexecution.md#getchallengetype)
* [getClassName](_models_intent_.executerequestexecution.md#getclassname)
* [getOptions](_models_intent_.executerequestexecution.md#getoptions)
* [getPinCode](_models_intent_.executerequestexecution.md#getpincode)
* [hasChallengeType](_models_intent_.executerequestexecution.md#haschallengetype)

## Constructors

###  constructor

\+ **new ExecuteRequestExecution**(`init`: [ExecuteRequestExecution](../interfaces/_models_interfaces_i_intent_.executerequestexecution.md)): *[ExecuteRequestExecution](_models_intent_.executerequestexecution.md)*

*Defined in [src/models/intent.ts:186](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L186)*

**Parameters:**

Name | Type |
------ | ------ |
`init` | [ExecuteRequestExecution](../interfaces/_models_interfaces_i_intent_.executerequestexecution.md) |

**Returns:** *[ExecuteRequestExecution](_models_intent_.executerequestexecution.md)*

## Properties

### `Optional` challenge

• **challenge**? : *undefined | object*

*Implementation of [ExecuteRequestExecution](../interfaces/_models_interfaces_i_intent_.executerequestexecution.md).[challenge](../interfaces/_models_interfaces_i_intent_.executerequestexecution.md#optional-challenge)*

*Defined in [src/models/intent.ts:183](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L183)*

___

###  command

• **command**: *string* = ""

*Implementation of [ExecuteRequestExecution](../interfaces/_models_interfaces_i_intent_.executerequestexecution.md).[command](../interfaces/_models_interfaces_i_intent_.executerequestexecution.md#command)*

*Defined in [src/models/intent.ts:179](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L179)*

___

###  params

• **params**: *object*

*Implementation of [ExecuteRequestExecution](../interfaces/_models_interfaces_i_intent_.executerequestexecution.md).[params](../interfaces/_models_interfaces_i_intent_.executerequestexecution.md#params)*

*Defined in [src/models/intent.ts:180](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L180)*

#### Type declaration:

* \[ **index**: *string*\]: any

## Methods

###  getAcknowledgement

▸ **getAcknowledgement**(): *boolean*

*Defined in [src/models/intent.ts:218](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L218)*

**Returns:** *boolean*

___

###  getChallengeType

▸ **getChallengeType**(): *"pin" | "ack" | false*

*Defined in [src/models/intent.ts:204](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L204)*

**Returns:** *"pin" | "ack" | false*

___

###  getClassName

▸ **getClassName**(): *string*

*Inherited from [BaseClass](_models_common_.baseclass.md).[getClassName](_models_common_.baseclass.md#getclassname)*

*Defined in [src/models/common.ts:10](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/common.ts#L10)*

**Returns:** *string*

___

###  getOptions

▸ **getOptions**(): *IntentInterface.ExecuteRequestExecutionOption*

*Defined in [src/models/intent.ts:193](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L193)*

**Returns:** *IntentInterface.ExecuteRequestExecutionOption*

___

###  getPinCode

▸ **getPinCode**(): *string*

*Defined in [src/models/intent.ts:227](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L227)*

**Returns:** *string*

___

###  hasChallengeType

▸ **hasChallengeType**(`type`: CoreInterface.ChallengeType): *boolean*

*Defined in [src/models/intent.ts:200](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L200)*

**Parameters:**

Name | Type |
------ | ------ |
`type` | CoreInterface.ChallengeType |

**Returns:** *boolean*
