[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/interfaces/i_intent"](../modules/_models_interfaces_i_intent_.md) › [ExecuteResult](_models_interfaces_i_intent_.executeresult.md)

# Interface: ExecuteResult

## Hierarchy

* **ExecuteResult**

  ↳ [ExecuteResponseDeviceGroup](_models_interfaces_i_intent_.executeresponsedevicegroup.md)

  ↳ [ExecuteResponseDevice](_models_interfaces_i_intent_.executeresponsedevice.md)

## Implemented by

* [ExecuteResult](../classes/_models_intent_.executeresult.md)

## Index

### Properties

* [challengeNeeded](_models_interfaces_i_intent_.executeresult.md#optional-challengeneeded)
* [debugString](_models_interfaces_i_intent_.executeresult.md#optional-debugstring)
* [errorCode](_models_interfaces_i_intent_.executeresult.md#optional-errorcode)
* [states](_models_interfaces_i_intent_.executeresult.md#states)
* [status](_models_interfaces_i_intent_.executeresult.md#status)

## Properties

### `Optional` challengeNeeded

• **challengeNeeded**? : *undefined | object*

*Defined in [src/models/interfaces/i_intent.ts:155](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_intent.ts#L155)*

___

### `Optional` debugString

• **debugString**? : *undefined | string*

*Defined in [src/models/interfaces/i_intent.ts:154](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_intent.ts#L154)*

___

### `Optional` errorCode

• **errorCode**? : *DeviceErrorCode["code"]*

*Defined in [src/models/interfaces/i_intent.ts:153](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_intent.ts#L153)*

___

###  states

• **states**: *object*

*Defined in [src/models/interfaces/i_intent.ts:149](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_intent.ts#L149)*

#### Type declaration:

* \[ **index**: *string*\]: any

* **exceptionCode**? : *DeviceStatusCode["code"]*

___

###  status

• **status**: *[ExecuteResultStatus](../modules/_models_interfaces_i_intent_.md#executeresultstatus)*

*Defined in [src/models/interfaces/i_intent.ts:148](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_intent.ts#L148)*
