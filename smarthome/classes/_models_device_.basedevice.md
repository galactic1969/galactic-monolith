[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/device"](../modules/_models_device_.md) › [BaseDevice](_models_device_.basedevice.md)

# Class: BaseDevice

## Hierarchy

* **BaseDevice**

  ↳ [DeviceType](_models_device_.devicetype.md)

  ↳ [VariableDevice](_models_device_.variabledevice.md)

## Implements

* [DeviceType](../interfaces/_models_interfaces_i_device_.devicetype.md)

## Index

### Properties

* [id](_models_device_.basedevice.md#id)
* [name](_models_device_.basedevice.md#name)
* [traits](_models_device_.basedevice.md#traits)
* [typeName](_models_device_.basedevice.md#typename)
* [willReportState](_models_device_.basedevice.md#willreportstate)

### Methods

* [[util.inspect.custom]](_models_device_.basedevice.md#[util.inspect.custom])
* [getCommand](_models_device_.basedevice.md#getcommand)
* [getMergedAttributes](_models_device_.basedevice.md#getmergedattributes)
* [getMergedStates](_models_device_.basedevice.md#getmergedstates)
* [getTraitHavingSpecificCommand](_models_device_.basedevice.md#gettraithavingspecificcommand)
* [getTraitNames](_models_device_.basedevice.md#gettraitnames)

### Object literals

* [format](_models_device_.basedevice.md#format)

## Properties

###  id

• **id**: *string* = ""

*Implementation of [DeviceType](../interfaces/_models_interfaces_i_device_.devicetype.md).[id](../interfaces/_models_interfaces_i_device_.devicetype.md#id)*

*Defined in [src/models/device.ts:29](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L29)*

___

###  name

• **name**: *[DeviceName](_models_core_.devicename.md)* = new Core.DeviceName({ defaultNames: [], name: '', nicknames: [] })

*Implementation of [DeviceType](../interfaces/_models_interfaces_i_device_.devicetype.md).[name](../interfaces/_models_interfaces_i_device_.devicetype.md#name)*

*Defined in [src/models/device.ts:30](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L30)*

___

###  traits

• **traits**: *[Traits](../interfaces/_models_interfaces_i_device_.traits.md)*

*Implementation of [DeviceType](../interfaces/_models_interfaces_i_device_.devicetype.md).[traits](../interfaces/_models_interfaces_i_device_.devicetype.md#traits)*

*Defined in [src/models/device.ts:31](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L31)*

___

###  typeName

• **typeName**: *string* = ""

*Implementation of [DeviceType](../interfaces/_models_interfaces_i_device_.devicetype.md).[typeName](../interfaces/_models_interfaces_i_device_.devicetype.md#typename)*

*Defined in [src/models/device.ts:28](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L28)*

___

###  willReportState

• **willReportState**: *boolean* = true

*Implementation of [DeviceType](../interfaces/_models_interfaces_i_device_.devicetype.md).[willReportState](../interfaces/_models_interfaces_i_device_.devicetype.md#willreportstate)*

*Defined in [src/models/device.ts:32](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L32)*

## Methods

###  [util.inspect.custom]

▸ **[util.inspect.custom]**(): *[DeviceJson](../interfaces/_models_interfaces_i_device_.devicejson.md)*

*Defined in [src/models/device.ts:131](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L131)*

**Returns:** *[DeviceJson](../interfaces/_models_interfaces_i_device_.devicejson.md)*

___

###  getCommand

▸ **getCommand**(`commandName`: string): *[Command](_models_core_.command.md)*

*Defined in [src/models/device.ts:189](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L189)*

get specific command instance

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`commandName` | string | string  |

**Returns:** *[Command](_models_core_.command.md)*

___

###  getMergedAttributes

▸ **getMergedAttributes**(): *object*

*Defined in [src/models/device.ts:145](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L145)*

get merged attributes in trait.

**Returns:** *object*

* \[ **index**: *string*\]: any

___

###  getMergedStates

▸ **getMergedStates**(): *object*

*Defined in [src/models/device.ts:157](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L157)*

get merged states in trait.

**Returns:** *object*

* \[ **index**: *string*\]: any

___

###  getTraitHavingSpecificCommand

▸ **getTraitHavingSpecificCommand**(`commandName`: string): *[Trait](_models_core_.trait.md)*

*Defined in [src/models/device.ts:170](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L170)*

get trait instance having specific command

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`commandName` | string | string name of command  |

**Returns:** *[Trait](_models_core_.trait.md)*

___

###  getTraitNames

▸ **getTraitNames**(): *string[]*

*Defined in [src/models/device.ts:138](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L138)*

get Trait names

**Returns:** *string[]*

## Object literals

###  format

### ▪ **format**: *object*

*Defined in [src/models/device.ts:34](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L34)*

###  toExecuteRequest

▸ **toExecuteRequest**(): *[ExecuteRequestDevice](_models_intent_.executerequestdevice.md)*

*Defined in [src/models/device.ts:71](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L71)*

format to execute request

**Returns:** *[ExecuteRequestDevice](_models_intent_.executerequestdevice.md)*

###  toJson

▸ **toJson**(`indent?`: undefined | number): *string*

*Defined in [src/models/device.ts:118](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L118)*

format to json (string)

**Parameters:**

Name | Type |
------ | ------ |
`indent?` | undefined &#124; number |

**Returns:** *string*

###  toJsonObject

▸ **toJsonObject**(): *[DeviceJson](../interfaces/_models_interfaces_i_device_.devicejson.md)*

*Defined in [src/models/device.ts:96](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L96)*

format to json object

**Returns:** *[DeviceJson](../interfaces/_models_interfaces_i_device_.devicejson.md)*

###  toQueryRequest

▸ **toQueryRequest**(): *[QueryRequestDevice](_models_intent_.queryrequestdevice.md)*

*Defined in [src/models/device.ts:53](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L53)*

format to query request

**Returns:** *[QueryRequestDevice](_models_intent_.queryrequestdevice.md)*

###  toQueryResponse

▸ **toQueryResponse**(): *[QueryResponseDevice](_models_intent_.queryresponsedevice.md)*

*Defined in [src/models/device.ts:62](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L62)*

format to query response

**Returns:** *[QueryResponseDevice](_models_intent_.queryresponsedevice.md)*

###  toReportStateRequest

▸ **toReportStateRequest**(`userId`: string): *[ReportStateRequest](_models_homegraph_.reportstaterequest.md)*

*Defined in [src/models/device.ts:80](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L80)*

format to reportstate request

**Parameters:**

Name | Type |
------ | ------ |
`userId` | string |

**Returns:** *[ReportStateRequest](_models_homegraph_.reportstaterequest.md)*

###  toSyncResponse

▸ **toSyncResponse**(): *[SyncResponseDevice](_models_intent_.syncresponsedevice.md)*

*Defined in [src/models/device.ts:38](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L38)*

format to sync response

**Returns:** *[SyncResponseDevice](_models_intent_.syncresponsedevice.md)*
