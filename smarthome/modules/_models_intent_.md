[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/intent"](_models_intent_.md)

# External module: "models/intent"

## Index

### Classes

* [DisconnectRequest](../classes/_models_intent_.disconnectrequest.md)
* [ExecuteRequest](../classes/_models_intent_.executerequest.md)
* [ExecuteRequestDevice](../classes/_models_intent_.executerequestdevice.md)
* [ExecuteRequestExecution](../classes/_models_intent_.executerequestexecution.md)
* [ExecuteResponse](../classes/_models_intent_.executeresponse.md)
* [ExecuteResponseDevice](../classes/_models_intent_.executeresponsedevice.md)
* [ExecuteResponseDeviceGroup](../classes/_models_intent_.executeresponsedevicegroup.md)
* [ExecuteResponseDevices](../classes/_models_intent_.executeresponsedevices.md)
* [ExecuteResult](../classes/_models_intent_.executeresult.md)
* [ExecuteResults](../classes/_models_intent_.executeresults.md)
* [IntentRequest](../classes/_models_intent_.intentrequest.md)
* [IntentRequestDevice](../classes/_models_intent_.intentrequestdevice.md)
* [IntentResponse](../classes/_models_intent_.intentresponse.md)
* [IntentResponseDevice](../classes/_models_intent_.intentresponsedevice.md)
* [QueryRequest](../classes/_models_intent_.queryrequest.md)
* [QueryRequestDevice](../classes/_models_intent_.queryrequestdevice.md)
* [QueryResponse](../classes/_models_intent_.queryresponse.md)
* [QueryResponseDevice](../classes/_models_intent_.queryresponsedevice.md)
* [SyncRequest](../classes/_models_intent_.syncrequest.md)
* [SyncResponse](../classes/_models_intent_.syncresponse.md)
* [SyncResponseDevice](../classes/_models_intent_.syncresponsedevice.md)

### Functions

* [getExecuteRequestExecutionOf](_models_intent_.md#const-getexecuterequestexecutionof)

## Functions

### `Const` getExecuteRequestExecutionOf

▸ **getExecuteRequestExecutionOf**<**T**>(`command`: object, `params`: Parameters<T["execute"]>[1]): *[ExecuteRequestExecutionOf](../interfaces/_models_interfaces_i_intent_.executerequestexecutionof.md)‹T›*

*Defined in [src/models/intent.ts:156](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/intent.ts#L156)*

特定コマンドのExecuteRequest取得(主にテスト用)

**Type parameters:**

▪ **T**: *[Command](../classes/_models_core_.command.md)*

**Parameters:**

▪ **command**: *object*

Name | Type |
------ | ------ |
`constructor` |  |
`getName` |  |

▪ **params**: *Parameters<T["execute"]>[1]*

**Returns:** *[ExecuteRequestExecutionOf](../interfaces/_models_interfaces_i_intent_.executerequestexecutionof.md)‹T›*
