[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/modes/modes_commands"](../modules/_models_traits_modes_modes_commands_.md) › [SetModes](_models_traits_modes_modes_commands_.setmodes.md)

# Class: SetModes

## Hierarchy

* [Command](_models_core_.command.md)

  ↳ **SetModes**

## Implements

* [Command](../interfaces/_models_interfaces_i_core_.command.md)
* [Command](../interfaces/_models_interfaces_i_core_.command.md)

## Index

### Constructors

* [constructor](_models_traits_modes_modes_commands_.setmodes.md#constructor)

### Properties

* [name](_models_traits_modes_modes_commands_.setmodes.md#name)
* [param](_models_traits_modes_modes_commands_.setmodes.md#param)
* [_name](_models_traits_modes_modes_commands_.setmodes.md#static-_name)

### Methods

* [askAcknowledgment](_models_traits_modes_modes_commands_.setmodes.md#askacknowledgment)
* [askPinCode](_models_traits_modes_modes_commands_.setmodes.md#askpincode)
* [checkAcknowledgement](_models_traits_modes_modes_commands_.setmodes.md#checkacknowledgement)
* [checkChallenge](_models_traits_modes_modes_commands_.setmodes.md#checkchallenge)
* [checkPinCode](_models_traits_modes_modes_commands_.setmodes.md#checkpincode)
* [execute](_models_traits_modes_modes_commands_.setmodes.md#execute)
* [getChallengeType](_models_traits_modes_modes_commands_.setmodes.md#getchallengetype)
* [getKeyName](_models_traits_modes_modes_commands_.setmodes.md#getkeyname)
* [getMaksedParam](_models_traits_modes_modes_commands_.setmodes.md#getmaksedparam)
* [getMergedStates](_models_traits_modes_modes_commands_.setmodes.md#getmergedstates)
* [getName](_models_traits_modes_modes_commands_.setmodes.md#getname)
* [getState](_models_traits_modes_modes_commands_.setmodes.md#getstate)
* [hasChallengeType](_models_traits_modes_modes_commands_.setmodes.md#haschallengetype)
* [reportInvalidPinCode](_models_traits_modes_modes_commands_.setmodes.md#reportinvalidpincode)
* [setState](_models_traits_modes_modes_commands_.setmodes.md#setstate)
* [getKeyName](_models_traits_modes_modes_commands_.setmodes.md#static-getkeyname)
* [getName](_models_traits_modes_modes_commands_.setmodes.md#static-getname)

## Constructors

###  constructor

\+ **new SetModes**(`init`: Command["param"]): *[SetModes](_models_traits_modes_modes_commands_.setmodes.md)*

*Inherited from [ColorAbsolute](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md).[constructor](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md#constructor)*

*Defined in [src/models/core.ts:103](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L103)*

**Parameters:**

Name | Type |
------ | ------ |
`init` | Command["param"] |

**Returns:** *[SetModes](_models_traits_modes_modes_commands_.setmodes.md)*

## Properties

###  name

• **name**: *"action.devices.commands.SetModes"* = SetModes._name

*Implementation of [Command](../interfaces/_models_interfaces_i_core_.command.md).[name](../interfaces/_models_interfaces_i_core_.command.md#name)*

*Overrides [Command](_models_core_.command.md).[name](_models_core_.command.md#name)*

*Defined in [src/models/traits/modes/modes_commands.ts:10](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/modes/modes_commands.ts#L10)*

___

###  param

• **param**: *object*

*Implementation of [Command](../interfaces/_models_interfaces_i_core_.command.md).[param](../interfaces/_models_interfaces_i_core_.command.md#param)*

*Inherited from [ColorAbsolute](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md).[param](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md#param)*

*Defined in [src/models/core.ts:101](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L101)*

#### Type declaration:

* **needChallenge**? : *CoreInterface.NeedChallenge*

___

### `Static` _name

▪ **_name**: *"action.devices.commands.SetModes"* = "action.devices.commands.SetModes"

*Overrides [Command](_models_core_.command.md).[_name](_models_core_.command.md#static-_name)*

*Defined in [src/models/traits/modes/modes_commands.ts:9](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/modes/modes_commands.ts#L9)*

## Methods

###  askAcknowledgment

▸ **askAcknowledgment**(`force`: boolean): *[ExecuteResult](_models_intent_.executeresult.md)*

*Inherited from [ColorAbsolute](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md).[askAcknowledgment](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md#askacknowledgment)*

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

*Inherited from [ColorAbsolute](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md).[askPinCode](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md#askpincode)*

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

*Inherited from [ColorAbsolute](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md).[checkAcknowledgement](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md#checkacknowledgement)*

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

*Inherited from [ColorAbsolute](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md).[checkChallenge](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md#checkchallenge)*

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

*Inherited from [ColorAbsolute](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md).[checkPinCode](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md#checkpincode)*

*Defined in [src/models/core.ts:262](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L262)*

return True if PinCode challenge passed

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`execution` | [ExecuteRequestExecution](_models_intent_.executerequestexecution.md) |   |

**Returns:** *boolean*

___

###  execute

▸ **execute**(`trait`: [Trait](_models_core_.trait.md), `params`: [SetModes](../interfaces/_models_traits_i_commands_.setmodes.md), `options`: IntentInterface.ExecuteRequestExecutionOption): *Promise‹[ExecuteResult](_models_intent_.executeresult.md)›*

*Overrides [Command](_models_core_.command.md).[execute](_models_core_.command.md#abstract-execute)*

*Defined in [src/models/traits/modes/modes_commands.ts:15](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/modes/modes_commands.ts#L15)*

execute

**Parameters:**

Name | Type |
------ | ------ |
`trait` | [Trait](_models_core_.trait.md) |
`params` | [SetModes](../interfaces/_models_traits_i_commands_.setmodes.md) |
`options` | IntentInterface.ExecuteRequestExecutionOption |

**Returns:** *Promise‹[ExecuteResult](_models_intent_.executeresult.md)›*

___

###  getChallengeType

▸ **getChallengeType**(): *CoreInterface.ChallengeType | false*

*Inherited from [ColorAbsolute](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md).[getChallengeType](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md#getchallengetype)*

*Defined in [src/models/core.ts:174](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L174)*

get challenge type of command. return 'ack' or 'pin' or False

**Returns:** *CoreInterface.ChallengeType | false*

___

###  getKeyName

▸ **getKeyName**(): *string*

*Inherited from [ColorAbsolute](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md).[getKeyName](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md#static-getkeyname)*

*Defined in [src/models/core.ts:155](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L155)*

get command name in object. it is same as class name. ex: Hoge

**Returns:** *string*

___

###  getMaksedParam

▸ **getMaksedParam**(): *Command["param"]*

*Inherited from [ColorAbsolute](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md).[getMaksedParam](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md#getmaksedparam)*

*Defined in [src/models/core.ts:290](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L290)*

return param with masked pincode if command has pin challenge

**Returns:** *Command["param"]*

___

###  getMergedStates

▸ **getMergedStates**(`states`: Trait["States"]): *object*

*Inherited from [ColorAbsolute](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md).[getMergedStates](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md#getmergedstates)*

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

*Inherited from [ColorAbsolute](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md).[getName](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md#static-getname)*

*Defined in [src/models/core.ts:141](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L141)*

get command name. ex: action.devices.commands.Hoge

**Returns:** *string*

___

###  getState

▸ **getState**(`trait`: [Trait](_models_core_.trait.md)): *[CurrentModeSettings](_models_traits_modes_modes_states_.currentmodesettings.md)*

*Overrides [Command](_models_core_.command.md).[getState](_models_core_.command.md#abstract-getstate)*

*Defined in [src/models/traits/modes/modes_commands.ts:25](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/modes/modes_commands.ts#L25)*

**Parameters:**

Name | Type |
------ | ------ |
`trait` | [Trait](_models_core_.trait.md) |

**Returns:** *[CurrentModeSettings](_models_traits_modes_modes_states_.currentmodesettings.md)*

___

###  hasChallengeType

▸ **hasChallengeType**(`type`: CoreInterface.ChallengeType): *boolean*

*Inherited from [ColorAbsolute](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md).[hasChallengeType](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md#haschallengetype)*

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

*Inherited from [ColorAbsolute](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md).[reportInvalidPinCode](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md#reportinvalidpincode)*

*Defined in [src/models/core.ts:276](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L276)*

return pin challenge failed response

**Returns:** *[ExecuteResult](_models_intent_.executeresult.md)*

___

###  setState

▸ **setState**(`trait`: [Trait](_models_core_.trait.md), `params`: [SetModes](../interfaces/_models_traits_i_commands_.setmodes.md)): *VariableTrait["States"]*

*Overrides [Command](_models_core_.command.md).[setState](_models_core_.command.md#abstract-setstate)*

*Defined in [src/models/traits/modes/modes_commands.ts:29](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/modes/modes_commands.ts#L29)*

**Parameters:**

Name | Type |
------ | ------ |
`trait` | [Trait](_models_core_.trait.md) |
`params` | [SetModes](../interfaces/_models_traits_i_commands_.setmodes.md) |

**Returns:** *VariableTrait["States"]*

___

### `Static` getKeyName

▸ **getKeyName**(): *string*

*Inherited from [ColorAbsolute](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md).[getKeyName](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md#static-getkeyname)*

*Defined in [src/models/core.ts:148](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L148)*

get command name in object. it is same as class name. ex: Hoge

**Returns:** *string*

___

### `Static` getName

▸ **getName**(): *string*

*Inherited from [ColorAbsolute](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md).[getName](_models_traits_colorsetting_colorsetting_commands_.colorabsolute.md#static-getname)*

*Defined in [src/models/core.ts:134](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L134)*

get command name. ex: action.devices.commands.Hoge

**Returns:** *string*
