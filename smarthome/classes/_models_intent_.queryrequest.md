[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/intent"](../modules/_models_intent_.md) › [QueryRequest](_models_intent_.queryrequest.md)

# Class: QueryRequest

## Hierarchy

  ↳ [IntentRequest](_models_intent_.intentrequest.md)

  ↳ **QueryRequest**

## Implements

* [QueryRequest](../interfaces/_models_interfaces_i_intent_.queryrequest.md)

## Index

### Constructors

* [constructor](_models_intent_.queryrequest.md#constructor)

### Properties

* [inputs](_models_intent_.queryrequest.md#inputs)
* [requestId](_models_intent_.queryrequest.md#requestid)

### Methods

* [getClassName](_models_intent_.queryrequest.md#getclassname)
* [getDeviceIds](_models_intent_.queryrequest.md#getdeviceids)

## Constructors

###  constructor

\+ **new QueryRequest**(`init`: [QueryRequest](../interfaces/_models_interfaces_i_intent_.queryrequest.md)): *[QueryRequest](_models_intent_.queryrequest.md)*

*Defined in [src/models/intent.ts:66](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L66)*

**Parameters:**

Name | Type |
------ | ------ |
`init` | [QueryRequest](../interfaces/_models_interfaces_i_intent_.queryrequest.md) |

**Returns:** *[QueryRequest](_models_intent_.queryrequest.md)*

## Properties

###  inputs

• **inputs**: *[object]* = [
    {
      intent: 'action.devices.QUERY',
      payload: {
        devices: []
      }
    }
  ]

*Implementation of [QueryRequest](../interfaces/_models_interfaces_i_intent_.queryrequest.md).[inputs](../interfaces/_models_interfaces_i_intent_.queryrequest.md#inputs)*

*Defined in [src/models/intent.ts:52](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L52)*

___

###  requestId

• **requestId**: *string* = ""

*Implementation of [QueryRequest](../interfaces/_models_interfaces_i_intent_.queryrequest.md).[requestId](../interfaces/_models_interfaces_i_intent_.queryrequest.md#requestid)*

*Defined in [src/models/intent.ts:51](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L51)*

## Methods

###  getClassName

▸ **getClassName**(): *string*

*Inherited from [BaseClass](_models_common_.baseclass.md).[getClassName](_models_common_.baseclass.md#getclassname)*

*Defined in [src/models/common.ts:10](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/common.ts#L10)*

**Returns:** *string*

___

###  getDeviceIds

▸ **getDeviceIds**(): *string[]*

*Defined in [src/models/intent.ts:73](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L73)*

**Returns:** *string[]*
