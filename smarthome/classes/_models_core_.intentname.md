[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/core"](../modules/_models_core_.md) › [IntentName](_models_core_.intentname.md)

# Class: IntentName

## Hierarchy

* **IntentName**

## Index

### Methods

* [shorten](_models_core_.intentname.md#static-shorten)

## Methods

### `Static` shorten

▸ **shorten**(`intentName`: IntentInterface.IntentName): *IntentInterface.ShortenIntentName*

*Defined in [src/models/core.ts:31](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L31)*

shorten intent name. ex) input: action.devices.SYNC, output: sync

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`intentName` | IntentInterface.IntentName | string. IntentName ex: action.devices.SYNC  |

**Returns:** *IntentInterface.ShortenIntentName*
