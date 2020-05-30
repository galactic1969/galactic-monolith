[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/intent"](../modules/_models_intent_.md) › [ExecuteRequest](_models_intent_.executerequest.md)

# Class: ExecuteRequest

## Hierarchy

  ↳ [IntentRequest](_models_intent_.intentrequest.md)

  ↳ **ExecuteRequest**

## Implements

* [ExecuteRequest](../interfaces/_models_interfaces_i_intent_.executerequest.md)

## Index

### Constructors

* [constructor](_models_intent_.executerequest.md#constructor)

### Properties

* [inputs](_models_intent_.executerequest.md#inputs)
* [requestId](_models_intent_.executerequest.md#requestid)

### Methods

* [getClassName](_models_intent_.executerequest.md#getclassname)

## Constructors

###  constructor

\+ **new ExecuteRequest**(`init`: [ExecuteRequest](../interfaces/_models_interfaces_i_intent_.executerequest.md)): *[ExecuteRequest](_models_intent_.executerequest.md)*

*Defined in [src/models/intent.ts:145](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L145)*

**Parameters:**

Name | Type |
------ | ------ |
`init` | [ExecuteRequest](../interfaces/_models_interfaces_i_intent_.executerequest.md) |

**Returns:** *[ExecuteRequest](_models_intent_.executerequest.md)*

## Properties

###  inputs

• **inputs**: *[object]* = [
    {
      intent: 'action.devices.EXECUTE',
      payload: {
        commands: [
          {
            devices: [],
            execution: []
          }
        ]
      }
    }
  ]

*Implementation of [ExecuteRequest](../interfaces/_models_interfaces_i_intent_.executerequest.md).[inputs](../interfaces/_models_interfaces_i_intent_.executerequest.md#inputs)*

*Defined in [src/models/intent.ts:121](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L121)*

___

###  requestId

• **requestId**: *string* = ""

*Implementation of [ExecuteRequest](../interfaces/_models_interfaces_i_intent_.executerequest.md).[requestId](../interfaces/_models_interfaces_i_intent_.executerequest.md#requestid)*

*Defined in [src/models/intent.ts:120](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L120)*

## Methods

###  getClassName

▸ **getClassName**(): *string*

*Inherited from [BaseClass](_models_common_.baseclass.md).[getClassName](_models_common_.baseclass.md#getclassname)*

*Defined in [src/models/common.ts:10](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/common.ts#L10)*

**Returns:** *string*
