[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/interfaces/i_intent"](../modules/_models_interfaces_i_intent_.md) › [ExecuteRequestExecutionOf](_models_interfaces_i_intent_.executerequestexecutionof.md)

# Interface: ExecuteRequestExecutionOf <**T**>

特定コマンドのExecuteRequest(主にテスト用)

## Type parameters

▪ **T**: *[Command](../classes/_models_core_.command.md)*

## Hierarchy

* [ExecuteRequestExecution](_models_interfaces_i_intent_.executerequestexecution.md)

  ↳ **ExecuteRequestExecutionOf**

## Index

### Properties

* [challenge](_models_interfaces_i_intent_.executerequestexecutionof.md#optional-challenge)
* [command](_models_interfaces_i_intent_.executerequestexecutionof.md#command)
* [params](_models_interfaces_i_intent_.executerequestexecutionof.md#params)

## Properties

### `Optional` challenge

• **challenge**? : *undefined | object*

*Inherited from [ExecuteRequestExecution](_models_interfaces_i_intent_.executerequestexecution.md).[challenge](_models_interfaces_i_intent_.executerequestexecution.md#optional-challenge)*

*Defined in [src/models/interfaces/i_intent.ts:114](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_intent.ts#L114)*

___

###  command

• **command**: *T["name"]*

*Overrides [ExecuteRequestExecution](_models_interfaces_i_intent_.executerequestexecution.md).[command](_models_interfaces_i_intent_.executerequestexecution.md#command)*

*Defined in [src/models/interfaces/i_intent.ts:126](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_intent.ts#L126)*

___

###  params

• **params**: *Parameters<T["execute"]>[1]*

*Overrides [ExecuteRequestExecution](_models_interfaces_i_intent_.executerequestexecution.md).[params](_models_interfaces_i_intent_.executerequestexecution.md#params)*

*Defined in [src/models/interfaces/i_intent.ts:128](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/interfaces/i_intent.ts#L128)*
