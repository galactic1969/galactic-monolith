[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["lib/topic"](../modules/_lib_topic_.md) › [TopicBuilder](_lib_topic_.topicbuilder.md)

# Class: TopicBuilder

## Hierarchy

* **TopicBuilder**

## Index

### Methods

* [buildIntentTopic](_lib_topic_.topicbuilder.md#static-buildintenttopic)
* [buildReportExecuteTopic](_lib_topic_.topicbuilder.md#static-buildreportexecutetopic)
* [buildReportstateTopic](_lib_topic_.topicbuilder.md#static-buildreportstatetopic)
* [buildRequestSyncTopic](_lib_topic_.topicbuilder.md#static-buildrequestsynctopic)
* [initCommonOption](_lib_topic_.topicbuilder.md#static-initcommonoption)

## Methods

### `Static` buildIntentTopic

▸ **buildIntentTopic**(`topicPattern`: string, `intentName`: IntentInterface.IntentName, `userId`: string, `deviceId`: string, `requestId`: string, `options?`: [CommonOption](../interfaces/_lib_topic_.commonoption.md)): *string*

*Defined in [src/lib/topic.ts:28](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/lib/topic.ts#L28)*

**Parameters:**

Name | Type |
------ | ------ |
`topicPattern` | string |
`intentName` | IntentInterface.IntentName |
`userId` | string |
`deviceId` | string |
`requestId` | string |
`options?` | [CommonOption](../interfaces/_lib_topic_.commonoption.md) |

**Returns:** *string*

___

### `Static` buildReportExecuteTopic

▸ **buildReportExecuteTopic**(`topicPattern`: string, `userId`: string, `deviceId`: string, `requestId`: string, `options?`: [CommonOption](../interfaces/_lib_topic_.commonoption.md)): *string*

*Defined in [src/lib/topic.ts:69](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/lib/topic.ts#L69)*

**Parameters:**

Name | Type |
------ | ------ |
`topicPattern` | string |
`userId` | string |
`deviceId` | string |
`requestId` | string |
`options?` | [CommonOption](../interfaces/_lib_topic_.commonoption.md) |

**Returns:** *string*

___

### `Static` buildReportstateTopic

▸ **buildReportstateTopic**(`topicPattern`: string, `userId`: string, `deviceId`: string, `requestId`: string, `options?`: [CommonOption](../interfaces/_lib_topic_.commonoption.md)): *string*

*Defined in [src/lib/topic.ts:50](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/lib/topic.ts#L50)*

**Parameters:**

Name | Type |
------ | ------ |
`topicPattern` | string |
`userId` | string |
`deviceId` | string |
`requestId` | string |
`options?` | [CommonOption](../interfaces/_lib_topic_.commonoption.md) |

**Returns:** *string*

___

### `Static` buildRequestSyncTopic

▸ **buildRequestSyncTopic**(`topicPattern`: string, `userId`: string, `requestId`: string, `options`: [CommonOption](../interfaces/_lib_topic_.commonoption.md)): *string*

*Defined in [src/lib/topic.ts:88](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/lib/topic.ts#L88)*

**Parameters:**

Name | Type |
------ | ------ |
`topicPattern` | string |
`userId` | string |
`requestId` | string |
`options` | [CommonOption](../interfaces/_lib_topic_.commonoption.md) |

**Returns:** *string*

___

### `Static` initCommonOption

▸ **initCommonOption**(`options`: [CommonOption](../interfaces/_lib_topic_.commonoption.md) | undefined): *[InitializedCommonOption](../interfaces/_lib_topic_.initializedcommonoption.md)*

*Defined in [src/lib/topic.ts:17](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/lib/topic.ts#L17)*

**Parameters:**

Name | Type |
------ | ------ |
`options` | [CommonOption](../interfaces/_lib_topic_.commonoption.md) &#124; undefined |

**Returns:** *[InitializedCommonOption](../interfaces/_lib_topic_.initializedcommonoption.md)*
