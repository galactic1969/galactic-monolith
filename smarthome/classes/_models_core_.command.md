[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/core"](../modules/_models_core_.md) › [Command](_models_core_.command.md)

# Class: Command

## Hierarchy

* **Command**

  ↳ [ColorAbsolute](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md)

  ↳ [SetInput](_models_traits_inputselector_inputselector_commands_.setinput.md)

  ↳ [OnOff](_models_traits_onoff_onoff_commands_.onoff.md)

  ↳ [OpenClose](_models_traits_openclose_openclose_commands_.openclose.md)

  ↳ [SetModes](_models_traits_modes_modes_commands_.setmodes.md)

  ↳ [ActivateScene](_models_traits_scene_scene_commands_.activatescene.md)

  ↳ [Mute](_models_traits_volume_volume_commands_.mute.md)

  ↳ [SetVolume](_models_traits_volume_volume_commands_.setvolume.md)

  ↳ [VolumeRelative](_models_traits_volume_volume_commands_.volumerelative.md)

  ↳ [TraitDoesNotHaveCommand](_models_core_.traitdoesnothavecommand.md)

## Implements

* [Command](../interfaces/_models_interfaces_i_core_.command.md)

## Index

### Constructors

* [constructor](_models_core_.command.md#constructor)

### Properties

* [name](_models_core_.command.md#name)
* [param](_models_core_.command.md#param)
* [_name](_models_core_.command.md#static-_name)

### Methods

* [askAcknowledgment](_models_core_.command.md#askacknowledgment)
* [askPinCode](_models_core_.command.md#askpincode)
* [checkAcknowledgement](_models_core_.command.md#checkacknowledgement)
* [checkChallenge](_models_core_.command.md#checkchallenge)
* [checkPinCode](_models_core_.command.md#checkpincode)
* [execute](_models_core_.command.md#abstract-execute)
* [getChallengeType](_models_core_.command.md#getchallengetype)
* [getKeyName](_models_core_.command.md#getkeyname)
* [getMaksedParam](_models_core_.command.md#getmaksedparam)
* [getMergedStates](_models_core_.command.md#getmergedstates)
* [getName](_models_core_.command.md#getname)
* [getState](_models_core_.command.md#abstract-getstate)
* [hasChallengeType](_models_core_.command.md#haschallengetype)
* [reportInvalidPinCode](_models_core_.command.md#reportinvalidpincode)
* [setState](_models_core_.command.md#abstract-setstate)
* [getKeyName](_models_core_.command.md#static-getkeyname)
* [getName](_models_core_.command.md#static-getname)

## Constructors

###  constructor

\+ **new Command**(`init`: Command["param"]): *[Command](_models_core_.command.md)*

*Defined in [src/models/core.ts:103](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L103)*

**Parameters:**

Name | Type |
------ | ------ |
`init` | Command["param"] |

**Returns:** *[Command](_models_core_.command.md)*

## Properties

###  name

• **name**: *string* = ""

*Implementation of [Command](../interfaces/_models_interfaces_i_core_.command.md).[name](../interfaces/_models_interfaces_i_core_.command.md#name)*

*Defined in [src/models/core.ts:100](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L100)*

___

###  param

• **param**: *object*

*Implementation of [Command](../interfaces/_models_interfaces_i_core_.command.md).[param](../interfaces/_models_interfaces_i_core_.command.md#param)*

*Defined in [src/models/core.ts:101](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L101)*

#### Type declaration:

* **needChallenge**? : *CoreInterface.NeedChallenge*

___

### `Static` _name

▪ **_name**: *string* = ""

*Defined in [src/models/core.ts:99](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L99)*

## Methods

###  askAcknowledgment

▸ **askAcknowledgment**(`force`: boolean): *[ExecuteResult](_models_intent_.executeresult.md)*

*Defined in [src/models/core.ts:192](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L192)*

return Acknowledgment response if command has 'ack' challenge type or force option is true.

**Parameters:**

Name | Type | Default | Description |
------ | ------ | ------ | ------ |
`force` | boolean | false | default false. set true if command has not 'ack' challenge type  |

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md)*

___

###  askPinCode

▸ **askPinCode**(`force`: boolean): *[ExecuteResult](_models_intent_.executeresult.md)*

*Defined in [src/models/core.ts:211](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L211)*

return pinNeed response if command has 'pin' challenge type.

**Parameters:**

Name | Type | Default | Description |
------ | ------ | ------ | ------ |
`force` | boolean | false | default false. set true if command has not 'pin' challenge type  |

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md)*

___

###  checkAcknowledgement

▸ **checkAcknowledgement**(`execution`: [ExecuteRequestExecution](_models_intent_.executerequestexecution.md)): *boolean*

*Defined in [src/models/core.ts:250](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L250)*

return True if Acknowledgement challenge passed

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`execution` | [ExecuteRequestExecution](_models_intent_.executerequestexecution.md) |   |

**Returns:** *boolean*

___

###  checkChallenge

▸ **checkChallenge**(`execution`: [ExecuteRequestExecution](_models_intent_.executerequestexecution.md)): *boolean*

*Defined in [src/models/core.ts:230](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L230)*

return True if any challenge passed

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`execution` | [ExecuteRequestExecution](_models_intent_.executerequestexecution.md) |   |

**Returns:** *boolean*

___

###  checkPinCode

▸ **checkPinCode**(`execution`: [ExecuteRequestExecution](_models_intent_.executerequestexecution.md)): *boolean*

*Defined in [src/models/core.ts:262](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L262)*

return True if PinCode challenge passed

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`execution` | [ExecuteRequestExecution](_models_intent_.executerequestexecution.md) |   |

**Returns:** *boolean*

___

### `Abstract` execute

▸ **execute**(`trait`: [Trait](_models_core_.trait.md), `params`: any, `options`: IntentInterface.ExecuteRequestExecutionOption): *Promise‹[ExecuteResult](_models_intent_.executeresult.md)›*

*Implementation of [Command](../interfaces/_models_interfaces_i_core_.command.md)*

*Defined in [src/models/core.ts:111](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L111)*

**Parameters:**

Name | Type |
------ | ------ |
`trait` | [Trait](_models_core_.trait.md) |
`params` | any |
`options` | IntentInterface.ExecuteRequestExecutionOption |

**Returns:** *Promise‹[ExecuteResult](_models_intent_.executeresult.md)›*

___

###  getChallengeType

▸ **getChallengeType**(): *CoreInterface.ChallengeType | false*

*Defined in [src/models/core.ts:174](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L174)*

get challenge type of command. return 'ack' or 'pin' or False

**Returns:** *CoreInterface.ChallengeType | false*

___

###  getKeyName

▸ **getKeyName**(): *string*

*Defined in [src/models/core.ts:155](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L155)*

get command name in object. it is same as class name. ex: Hoge

**Returns:** *string*

___

###  getMaksedParam

▸ **getMaksedParam**(): *Command["param"]*

*Defined in [src/models/core.ts:290](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L290)*

return param with masked pincode if command has pin challenge

**Returns:** *Command["param"]*

___

###  getMergedStates

▸ **getMergedStates**(`states`: Trait["States"]): *object*

*Defined in [src/models/core.ts:122](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L122)*

get merged state. for getting states after setState().

**Parameters:**

Name | Type |
------ | ------ |
`states` | Trait["States"] |

**Returns:** *object*

* \[ **index**: *string*\]: any

___

###  getName

▸ **getName**(): *string*

*Defined in [src/models/core.ts:141](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L141)*

get command name. ex: action.devices.commands.Hoge

**Returns:** *string*

___

### `Abstract` getState

▸ **getState**(`trait`: [Trait](_models_core_.trait.md)): *any*

*Defined in [src/models/core.ts:117](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L117)*

**Parameters:**

Name | Type |
------ | ------ |
`trait` | [Trait](_models_core_.trait.md) |

**Returns:** *any*

___

###  hasChallengeType

▸ **hasChallengeType**(`type`: CoreInterface.ChallengeType): *boolean*

*Defined in [src/models/core.ts:163](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L163)*

return true if command has specified challenge type

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`type` | CoreInterface.ChallengeType | string. pin | ack  |

**Returns:** *boolean*

___

###  reportInvalidPinCode

▸ **reportInvalidPinCode**(): *[ExecuteResult](_models_intent_.executeresult.md)*

*Defined in [src/models/core.ts:276](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L276)*

return pin challenge failed response

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md)*

___

### `Abstract` setState

▸ **setState**(`trait`: [Trait](_models_core_.trait.md), `params`: any): *VariableTrait["States"]*

*Implementation of [Command](../interfaces/_models_interfaces_i_core_.command.md)*

*Defined in [src/models/core.ts:116](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L116)*

**Parameters:**

Name | Type |
------ | ------ |
`trait` | [Trait](_models_core_.trait.md) |
`params` | any |

**Returns:** *VariableTrait["States"]*

___

### `Static` getKeyName

▸ **getKeyName**(): *string*

*Defined in [src/models/core.ts:148](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L148)*

get command name in object. it is same as class name. ex: Hoge

**Returns:** *string*

___

### `Static` getName

▸ **getName**(): *string*

*Defined in [src/models/core.ts:134](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L134)*

get command name. ex: action.devices.commands.Hoge

**Returns:** *string*
