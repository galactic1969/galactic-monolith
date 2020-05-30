[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/devicetypes/index"](../modules/_models_devicetypes_index_.md) › [Pressurecooker](_models_devicetypes_index_.pressurecooker.md)

# Class: Pressurecooker

## Hierarchy

  ↳ [DeviceType](_models_device_.devicetype.md)

  ↳ **Pressurecooker**

## Implements

* [DeviceType](../interfaces/_models_interfaces_i_device_.devicetype.md)
* [DeviceType](../interfaces/_models_interfaces_i_device_.devicetype.md)

## Index

### Constructors

* [constructor](_models_devicetypes_index_.pressurecooker.md#constructor)

### Properties

* [id](_models_devicetypes_index_.pressurecooker.md#id)
* [name](_models_devicetypes_index_.pressurecooker.md#name)
* [traits](_models_devicetypes_index_.pressurecooker.md#traits)
* [typeName](_models_devicetypes_index_.pressurecooker.md#typename)
* [willReportState](_models_devicetypes_index_.pressurecooker.md#willreportstate)

### Methods

* [[util.inspect.custom]](_models_devicetypes_index_.pressurecooker.md#[util.inspect.custom])
* [createId](_models_devicetypes_index_.pressurecooker.md#createid)
* [getCommand](_models_devicetypes_index_.pressurecooker.md#getcommand)
* [getMergedAttributes](_models_devicetypes_index_.pressurecooker.md#getmergedattributes)
* [getMergedStates](_models_devicetypes_index_.pressurecooker.md#getmergedstates)
* [getTraitHavingSpecificCommand](_models_devicetypes_index_.pressurecooker.md#gettraithavingspecificcommand)
* [getTraitNames](_models_devicetypes_index_.pressurecooker.md#gettraitnames)

### Object literals

* [format](_models_devicetypes_index_.pressurecooker.md#format)

## Constructors

###  constructor

\+ **new Pressurecooker**(`param?`: undefined | object): *[Pressurecooker](_models_devicetypes_index_.pressurecooker.md)*

*Inherited from [DeviceType](_models_device_.devicetype.md).[constructor](_models_device_.devicetype.md#constructor)*

*Defined in [src/models/device.ts:207](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L207)*

**Parameters:**

Name | Type |
------ | ------ |
`param?` | undefined &#124; object |

**Returns:** *[Pressurecooker](_models_devicetypes_index_.pressurecooker.md)*

## Properties

###  id

• **id**: *string* = ""

*Implementation of [DeviceType](../interfaces/_models_interfaces_i_device_.devicetype.md).[id](../interfaces/_models_interfaces_i_device_.devicetype.md#id)*

*Inherited from [BaseDevice](_models_device_.basedevice.md).[id](_models_device_.basedevice.md#id)*

*Defined in [src/models/device.ts:29](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L29)*

___

###  name

• **name**: *[DeviceName](_models_core_.devicename.md)* = new Core.DeviceName({ defaultNames: [], name: '', nicknames: [] })

*Implementation of [DeviceType](../interfaces/_models_interfaces_i_device_.devicetype.md).[name](../interfaces/_models_interfaces_i_device_.devicetype.md#name)*

*Inherited from [BaseDevice](_models_device_.basedevice.md).[name](_models_device_.basedevice.md#name)*

*Defined in [src/models/device.ts:30](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L30)*

___

###  traits

• **traits**: *[Traits](../interfaces/_models_interfaces_i_device_.traits.md)*

*Implementation of [DeviceType](../interfaces/_models_interfaces_i_device_.devicetype.md).[traits](../interfaces/_models_interfaces_i_device_.devicetype.md#traits)*

*Inherited from [BaseDevice](_models_device_.basedevice.md).[traits](_models_device_.basedevice.md#traits)*

*Defined in [src/models/device.ts:31](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L31)*

___

###  typeName

• **typeName**: *"action.devices.types.PRESSURECOOKER"* = "action.devices.types.PRESSURECOOKER"

*Implementation of [DeviceType](../interfaces/_models_interfaces_i_device_.devicetype.md).[typeName](../interfaces/_models_interfaces_i_device_.devicetype.md#typename)*

*Overrides [BaseDevice](_models_device_.basedevice.md).[typeName](_models_device_.basedevice.md#typename)*

*Defined in [src/models/devicetypes/index.ts:184](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/devicetypes/index.ts#L184)*

___

###  willReportState

• **willReportState**: *boolean* = true

*Implementation of [DeviceType](../interfaces/_models_interfaces_i_device_.devicetype.md).[willReportState](../interfaces/_models_interfaces_i_device_.devicetype.md#willreportstate)*

*Inherited from [BaseDevice](_models_device_.basedevice.md).[willReportState](_models_device_.basedevice.md#willreportstate)*

*Defined in [src/models/device.ts:32](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L32)*

## Methods

###  [util.inspect.custom]

▸ **[util.inspect.custom]**(): *[DeviceJson](../interfaces/_models_interfaces_i_device_.devicejson.md)*

*Inherited from [BaseDevice](_models_device_.basedevice.md).[[util.inspect.custom]](_models_device_.basedevice.md#[util.inspect.custom])*

*Defined in [src/models/device.ts:131](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L131)*

**Returns:** *[DeviceJson](../interfaces/_models_interfaces_i_device_.devicejson.md)*

___

###  createId

▸ **createId**(): *string*

*Inherited from [DeviceType](_models_device_.devicetype.md).[createId](_models_device_.devicetype.md#createid)*

*Defined in [src/models/device.ts:233](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L233)*

create unique id.

**Returns:** *string*

___

###  getCommand

▸ **getCommand**(`commandName`: string): *[Command](_models_core_.command.md)*

*Inherited from [BaseDevice](_models_device_.basedevice.md).[getCommand](_models_device_.basedevice.md#getcommand)*

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

*Inherited from [BaseDevice](_models_device_.basedevice.md).[getMergedAttributes](_models_device_.basedevice.md#getmergedattributes)*

*Defined in [src/models/device.ts:145](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L145)*

get merged attributes in trait.

**Returns:** *object*

* \[ **index**: *string*\]: any

___

###  getMergedStates

▸ **getMergedStates**(): *object*

*Inherited from [BaseDevice](_models_device_.basedevice.md).[getMergedStates](_models_device_.basedevice.md#getmergedstates)*

*Defined in [src/models/device.ts:157](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L157)*

get merged states in trait.

**Returns:** *object*

* \[ **index**: *string*\]: any

___

###  getTraitHavingSpecificCommand

▸ **getTraitHavingSpecificCommand**(`commandName`: string): *[Trait](_models_core_.trait.md)*

*Inherited from [BaseDevice](_models_device_.basedevice.md).[getTraitHavingSpecificCommand](_models_device_.basedevice.md#gettraithavingspecificcommand)*

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

*Inherited from [BaseDevice](_models_device_.basedevice.md).[getTraitNames](_models_device_.basedevice.md#gettraitnames)*

*Defined in [src/models/device.ts:138](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/device.ts#L138)*

get Trait names

**Returns:** *string[]*

## Object literals

###  format

### ▪ **format**: *object*

*Inherited from [BaseDevice](_models_device_.basedevice.md).[format](_models_device_.basedevice.md#format)*

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
