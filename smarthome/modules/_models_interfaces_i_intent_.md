[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/interfaces/i_intent"](_models_interfaces_i_intent_.md)

# External module: "models/interfaces/i_intent"

## Index

### Interfaces

* [DisconnectRequest](../interfaces/_models_interfaces_i_intent_.disconnectrequest.md)
* [ExecuteRequest](../interfaces/_models_interfaces_i_intent_.executerequest.md)
* [ExecuteRequestDevice](../interfaces/_models_interfaces_i_intent_.executerequestdevice.md)
* [ExecuteRequestExecution](../interfaces/_models_interfaces_i_intent_.executerequestexecution.md)
* [ExecuteRequestExecutionOf](../interfaces/_models_interfaces_i_intent_.executerequestexecutionof.md)
* [ExecuteResponse](../interfaces/_models_interfaces_i_intent_.executeresponse.md)
* [ExecuteResponseDevice](../interfaces/_models_interfaces_i_intent_.executeresponsedevice.md)
* [ExecuteResponseDeviceGroup](../interfaces/_models_interfaces_i_intent_.executeresponsedevicegroup.md)
* [ExecuteResult](../interfaces/_models_interfaces_i_intent_.executeresult.md)
* [QueryRequest](../interfaces/_models_interfaces_i_intent_.queryrequest.md)
* [QueryRequestAdmin](../interfaces/_models_interfaces_i_intent_.queryrequestadmin.md)
* [QueryRequestDevice](../interfaces/_models_interfaces_i_intent_.queryrequestdevice.md)
* [QueryResponse](../interfaces/_models_interfaces_i_intent_.queryresponse.md)
* [QueryResponseDevice](../interfaces/_models_interfaces_i_intent_.queryresponsedevice.md)
* [ReportExecuteRequest](../interfaces/_models_interfaces_i_intent_.reportexecuterequest.md)
* [ReportStateRequest](../interfaces/_models_interfaces_i_intent_.reportstaterequest.md)
* [RequestSyncRequest](../interfaces/_models_interfaces_i_intent_.requestsyncrequest.md)
* [SyncRequest](../interfaces/_models_interfaces_i_intent_.syncrequest.md)
* [SyncResponse](../interfaces/_models_interfaces_i_intent_.syncresponse.md)
* [SyncResponseDevice](../interfaces/_models_interfaces_i_intent_.syncresponsedevice.md)

### Type aliases

* [ExecuteRequestExecutionOption](_models_interfaces_i_intent_.md#executerequestexecutionoption)
* [ExecuteRequiredChallengeType](_models_interfaces_i_intent_.md#executerequiredchallengetype)
* [ExecuteResultStatus](_models_interfaces_i_intent_.md#executeresultstatus)
* [IntentName](_models_interfaces_i_intent_.md#intentname)
* [ShortenIntentName](_models_interfaces_i_intent_.md#shortenintentname)

## Type aliases

###  ExecuteRequestExecutionOption

Ƭ **ExecuteRequestExecutionOption**: *Pick‹[ExecuteRequestExecution](../interfaces/_models_interfaces_i_intent_.executerequestexecution.md), "challenge"›*

*Defined in [src/models/interfaces/i_intent.ts:120](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_intent.ts#L120)*

___

###  ExecuteRequiredChallengeType

Ƭ **ExecuteRequiredChallengeType**: *"ackNeeded" | "pinNeeded" | "challengeFailedPinNeeded"*

*Defined in [src/models/interfaces/i_intent.ts:144](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_intent.ts#L144)*

___

###  ExecuteResultStatus

Ƭ **ExecuteResultStatus**: *"SUCCESS" | "PENDING" | "ERROR" | "OFFLINE" | "EXCEPTIONS"*

*Defined in [src/models/interfaces/i_intent.ts:145](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_intent.ts#L145)*

___

###  IntentName

Ƭ **IntentName**: *"action.devices.SYNC" | "action.devices.QUERY" | "action.devices.EXECUTE" | "action.devices.DISCONNECT"*

*Defined in [src/models/interfaces/i_intent.ts:7](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_intent.ts#L7)*

___

###  ShortenIntentName

Ƭ **ShortenIntentName**: *"sync" | "query" | "execute" | "disconnect"*

*Defined in [src/models/interfaces/i_intent.ts:13](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_intent.ts#L13)*
