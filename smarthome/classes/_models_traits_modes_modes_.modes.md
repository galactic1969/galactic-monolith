[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/modes/modes"](../modules/_models_traits_modes_modes_.md) › [Modes](_models_traits_modes_modes_.modes.md)

# Class: Modes

This trait covers all available modes and mode-specific settings for a device.

## Hierarchy

* [Trait](_models_core_.trait.md)

  ↳ **Modes**

## Implements

* [Trait](../interfaces/_models_interfaces_i_core_.trait.md)
* [ModesTrait](../interfaces/_models_traits_i_traits_.modestrait.md)

## Index

### Constructors

* [constructor](_models_traits_modes_modes_.modes.md#constructor)

### Properties

* [Attributes](_models_traits_modes_modes_.modes.md#attributes)
* [Commands](_models_traits_modes_modes_.modes.md#commands)
* [States](_models_traits_modes_modes_.modes.md#states)
* [name](_models_traits_modes_modes_.modes.md#name)

### Methods

* [getAttribute](_models_traits_modes_modes_.modes.md#getattribute)
* [getCommand](_models_traits_modes_modes_.modes.md#getcommand)
* [getElement](_models_traits_modes_modes_.modes.md#getelement)
* [getElements](_models_traits_modes_modes_.modes.md#getelements)
* [getKeyName](_models_traits_modes_modes_.modes.md#getkeyname)
* [getMergedAttributes](_models_traits_modes_modes_.modes.md#getmergedattributes)
* [getMergedStates](_models_traits_modes_modes_.modes.md#getmergedstates)
* [getState](_models_traits_modes_modes_.modes.md#getstate)
* [hasAttribute](_models_traits_modes_modes_.modes.md#hasattribute)
* [hasAttributes](_models_traits_modes_modes_.modes.md#hasattributes)
* [hasCommand](_models_traits_modes_modes_.modes.md#hascommand)
* [hasCommands](_models_traits_modes_modes_.modes.md#hascommands)
* [hasElement](_models_traits_modes_modes_.modes.md#haselement)
* [hasState](_models_traits_modes_modes_.modes.md#hasstate)
* [hasStates](_models_traits_modes_modes_.modes.md#hasstates)
* [shouldHaveAttributes](_models_traits_modes_modes_.modes.md#shouldhaveattributes)
* [shouldHaveCommands](_models_traits_modes_modes_.modes.md#shouldhavecommands)
* [shouldHaveElements](_models_traits_modes_modes_.modes.md#shouldhaveelements)
* [shouldHaveStates](_models_traits_modes_modes_.modes.md#shouldhavestates)
* [toJsonObject](_models_traits_modes_modes_.modes.md#tojsonobject)
* [validate](_models_traits_modes_modes_.modes.md#validate)
* [getKeyName](_models_traits_modes_modes_.modes.md#static-getkeyname)
* [getName](_models_traits_modes_modes_.modes.md#static-getname)
* [init](_models_traits_modes_modes_.modes.md#static-init)
* [initWithJson](_models_traits_modes_modes_.modes.md#static-initwithjson)
* [resolveAttributes](_models_traits_modes_modes_.modes.md#static-resolveattributes)
* [resolveCommands](_models_traits_modes_modes_.modes.md#static-resolvecommands)
* [resolveStates](_models_traits_modes_modes_.modes.md#static-resolvestates)

## Constructors

###  constructor

\+ **new Modes**(`param`: [ModesParam](../interfaces/_models_traits_i_traits_.modesparam.md)): *[Modes](_models_traits_modes_modes_.modes.md)*

*Overrides [Trait](_models_core_.trait.md).[constructor](_models_core_.trait.md#constructor)*

*Defined in [src/models/traits/modes/modes.ts:10](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/modes/modes.ts#L10)*

**Parameters:**

Name | Type |
------ | ------ |
`param` | [ModesParam](../interfaces/_models_traits_i_traits_.modesparam.md) |

**Returns:** *[Modes](_models_traits_modes_modes_.modes.md)*

## Properties

###  Attributes

• **Attributes**: *object*

*Implementation of [ModesTrait](../interfaces/_models_traits_i_traits_.modestrait.md).[Attributes](../interfaces/_models_traits_i_traits_.modestrait.md#attributes)*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[Attributes](_models_traits_colorsetting_colorsetting_.colorsetting.md#attributes)*

*Defined in [src/models/core.ts:340](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L340)*

#### Type declaration:

* \[ **index**: *string*\]: [Attribute](_models_core_.attribute.md)

___

###  Commands

• **Commands**: *object*

*Implementation of [ModesTrait](../interfaces/_models_traits_i_traits_.modestrait.md).[Commands](../interfaces/_models_traits_i_traits_.modestrait.md#commands)*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[Commands](_models_traits_colorsetting_colorsetting_.colorsetting.md#commands)*

*Defined in [src/models/core.ts:341](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L341)*

#### Type declaration:

* \[ **index**: *string*\]: [Command](_models_core_.command.md)

___

###  States

• **States**: *object*

*Implementation of [ModesTrait](../interfaces/_models_traits_i_traits_.modestrait.md).[States](../interfaces/_models_traits_i_traits_.modestrait.md#states)*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[States](_models_traits_colorsetting_colorsetting_.colorsetting.md#states)*

*Defined in [src/models/core.ts:342](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L342)*

#### Type declaration:

* \[ **index**: *string*\]: [State](_models_core_.state.md)

___

###  name

• **name**: *"action.devices.traits.Modes"* = "action.devices.traits.Modes"

*Implementation of [ModesTrait](../interfaces/_models_traits_i_traits_.modestrait.md).[name](../interfaces/_models_traits_i_traits_.modestrait.md#name)*

*Overrides [Trait](_models_core_.trait.md).[name](_models_core_.trait.md#name)*

*Defined in [src/models/traits/modes/modes.ts:10](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/modes/modes.ts#L10)*

## Methods

###  getAttribute

▸ **getAttribute**<**T**>(`attribute`: object): *T*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[getAttribute](_models_traits_colorsetting_colorsetting_.colorsetting.md#getattribute)*

*Defined in [src/models/core.ts:572](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L572)*

**Type parameters:**

▪ **T**: *[Attribute](_models_core_.attribute.md)*

**Parameters:**

▪ **attribute**: *object*

Name | Type |
------ | ------ |
`constructor` |  |

**Returns:** *T*

▸ **getAttribute**<**T**>(`attributeName`: string): *T*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[getAttribute](_models_traits_colorsetting_colorsetting_.colorsetting.md#getattribute)*

*Defined in [src/models/core.ts:573](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L573)*

**Type parameters:**

▪ **T**: *[Attribute](_models_core_.attribute.md)*

**Parameters:**

Name | Type |
------ | ------ |
`attributeName` | string |

**Returns:** *T*

___

###  getCommand

▸ **getCommand**<**T**>(`command`: object): *T*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[getCommand](_models_traits_colorsetting_colorsetting_.colorsetting.md#getcommand)*

*Defined in [src/models/core.ts:625](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L625)*

**Type parameters:**

▪ **T**: *[Command](_models_core_.command.md)*

**Parameters:**

▪ **command**: *object*

Name | Type |
------ | ------ |
`constructor` |  |

**Returns:** *T*

▸ **getCommand**<**T**>(`commandName`: string): *T*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[getCommand](_models_traits_colorsetting_colorsetting_.colorsetting.md#getcommand)*

*Defined in [src/models/core.ts:626](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L626)*

**Type parameters:**

▪ **T**: *[Command](_models_core_.command.md)*

**Parameters:**

Name | Type |
------ | ------ |
`commandName` | string |

**Returns:** *T*

___

###  getElement

▸ **getElement**(`name`: string, `elementType`: [TraitElementType](../modules/_models_core_.md#traitelementtype)): *[TraitElementClass](../modules/_models_core_.md#traitelementclass)*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[getElement](_models_traits_colorsetting_colorsetting_.colorsetting.md#getelement)*

*Defined in [src/models/core.ts:409](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L409)*

**Parameters:**

Name | Type |
------ | ------ |
`name` | string |
`elementType` | [TraitElementType](../modules/_models_core_.md#traitelementtype) |

**Returns:** *[TraitElementClass](../modules/_models_core_.md#traitelementclass)*

▸ **getElement**(`elementDefinition`: object, `elementType`: [TraitElementType](../modules/_models_core_.md#traitelementtype)): *[TraitElementClass](../modules/_models_core_.md#traitelementclass)*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[getElement](_models_traits_colorsetting_colorsetting_.colorsetting.md#getelement)*

*Defined in [src/models/core.ts:410](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L410)*

**Parameters:**

▪ **elementDefinition**: *object*

Name | Type |
------ | ------ |
`constructor` |  |
`getName` |  |

▪ **elementType**: *[TraitElementType](../modules/_models_core_.md#traitelementtype)*

**Returns:** *[TraitElementClass](../modules/_models_core_.md#traitelementclass)*

___

###  getElements

▸ **getElements**(`names`: string[], `elementType`: [TraitElementType](../modules/_models_core_.md#traitelementtype)): *[TraitElementClass](../modules/_models_core_.md#traitelementclass)[]*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[getElements](_models_traits_colorsetting_colorsetting_.colorsetting.md#getelements)*

*Defined in [src/models/core.ts:437](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L437)*

**Parameters:**

Name | Type |
------ | ------ |
`names` | string[] |
`elementType` | [TraitElementType](../modules/_models_core_.md#traitelementtype) |

**Returns:** *[TraitElementClass](../modules/_models_core_.md#traitelementclass)[]*

▸ **getElements**(`elementDefinitions`: object[], `elementType`: [TraitElementType](../modules/_models_core_.md#traitelementtype)): *[TraitElementClass](../modules/_models_core_.md#traitelementclass)[]*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[getElements](_models_traits_colorsetting_colorsetting_.colorsetting.md#getelements)*

*Defined in [src/models/core.ts:438](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L438)*

**Parameters:**

Name | Type |
------ | ------ |
`elementDefinitions` | object[] |
`elementType` | [TraitElementType](../modules/_models_core_.md#traitelementtype) |

**Returns:** *[TraitElementClass](../modules/_models_core_.md#traitelementclass)[]*

___

###  getKeyName

▸ **getKeyName**(): *string*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[getKeyName](_models_traits_colorsetting_colorsetting_.colorsetting.md#static-getkeyname)*

*Defined in [src/models/core.ts:376](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L376)*

get object key name of trait

**Returns:** *string*

___

###  getMergedAttributes

▸ **getMergedAttributes**(): *object*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[getMergedAttributes](_models_traits_colorsetting_colorsetting_.colorsetting.md#getmergedattributes)*

*Defined in [src/models/core.ts:382](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L382)*

**Returns:** *object*

* \[ **index**: *string*\]: any

___

###  getMergedStates

▸ **getMergedStates**(): *object*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[getMergedStates](_models_traits_colorsetting_colorsetting_.colorsetting.md#getmergedstates)*

*Defined in [src/models/core.ts:391](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L391)*

**Returns:** *object*

* \[ **index**: *string*\]: any

___

###  getState

▸ **getState**<**T**>(`state`: object): *T*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[getState](_models_traits_colorsetting_colorsetting_.colorsetting.md#getstate)*

*Defined in [src/models/core.ts:599](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L599)*

**Type parameters:**

▪ **T**: *[State](_models_core_.state.md)*

**Parameters:**

▪ **state**: *object*

Name | Type |
------ | ------ |
`constructor` |  |

**Returns:** *T*

▸ **getState**<**T**>(`stateName`: string): *T*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[getState](_models_traits_colorsetting_colorsetting_.colorsetting.md#getstate)*

*Defined in [src/models/core.ts:600](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L600)*

**Type parameters:**

▪ **T**: *[State](_models_core_.state.md)*

**Parameters:**

Name | Type |
------ | ------ |
`stateName` | string |

**Returns:** *T*

___

###  hasAttribute

▸ **hasAttribute**(`attribute`: CoreInterface.AttributeClassDefinition): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[hasAttribute](_models_traits_colorsetting_colorsetting_.colorsetting.md#hasattribute)*

*Defined in [src/models/core.ts:552](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L552)*

**Parameters:**

Name | Type |
------ | ------ |
`attribute` | CoreInterface.AttributeClassDefinition |

**Returns:** *boolean*

▸ **hasAttribute**(`attributeName`: string): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[hasAttribute](_models_traits_colorsetting_colorsetting_.colorsetting.md#hasattribute)*

*Defined in [src/models/core.ts:553](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L553)*

**Parameters:**

Name | Type |
------ | ------ |
`attributeName` | string |

**Returns:** *boolean*

___

###  hasAttributes

▸ **hasAttributes**(`attributeNames`: string[]): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[hasAttributes](_models_traits_colorsetting_colorsetting_.colorsetting.md#hasattributes)*

*Defined in [src/models/core.ts:558](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L558)*

**Parameters:**

Name | Type |
------ | ------ |
`attributeNames` | string[] |

**Returns:** *boolean*

▸ **hasAttributes**(`attributes`: CoreInterface.AttributeClassDefinition[]): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[hasAttributes](_models_traits_colorsetting_colorsetting_.colorsetting.md#hasattributes)*

*Defined in [src/models/core.ts:559](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L559)*

**Parameters:**

Name | Type |
------ | ------ |
`attributes` | CoreInterface.AttributeClassDefinition[] |

**Returns:** *boolean*

___

###  hasCommand

▸ **hasCommand**(`command`: CoreInterface.CommandClassDefinition): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[hasCommand](_models_traits_colorsetting_colorsetting_.colorsetting.md#hascommand)*

*Defined in [src/models/core.ts:605](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L605)*

**Parameters:**

Name | Type |
------ | ------ |
`command` | CoreInterface.CommandClassDefinition |

**Returns:** *boolean*

▸ **hasCommand**(`commandName`: string): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[hasCommand](_models_traits_colorsetting_colorsetting_.colorsetting.md#hascommand)*

*Defined in [src/models/core.ts:606](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L606)*

**Parameters:**

Name | Type |
------ | ------ |
`commandName` | string |

**Returns:** *boolean*

___

###  hasCommands

▸ **hasCommands**(`commandNames`: string[]): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[hasCommands](_models_traits_colorsetting_colorsetting_.colorsetting.md#hascommands)*

*Defined in [src/models/core.ts:611](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L611)*

**Parameters:**

Name | Type |
------ | ------ |
`commandNames` | string[] |

**Returns:** *boolean*

▸ **hasCommands**(`commands`: CoreInterface.CommandClassDefinition[]): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[hasCommands](_models_traits_colorsetting_colorsetting_.colorsetting.md#hascommands)*

*Defined in [src/models/core.ts:612](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L612)*

**Parameters:**

Name | Type |
------ | ------ |
`commands` | CoreInterface.CommandClassDefinition[] |

**Returns:** *boolean*

___

###  hasElement

▸ **hasElement**(`name`: string, `elementType`: [TraitElementType](../modules/_models_core_.md#traitelementtype)): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[hasElement](_models_traits_colorsetting_colorsetting_.colorsetting.md#haselement)*

*Defined in [src/models/core.ts:478](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L478)*

**Parameters:**

Name | Type |
------ | ------ |
`name` | string |
`elementType` | [TraitElementType](../modules/_models_core_.md#traitelementtype) |

**Returns:** *boolean*

▸ **hasElement**(`elementDefinition`: object, `elementType`: [TraitElementType](../modules/_models_core_.md#traitelementtype)): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[hasElement](_models_traits_colorsetting_colorsetting_.colorsetting.md#haselement)*

*Defined in [src/models/core.ts:479](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L479)*

**Parameters:**

▪ **elementDefinition**: *object*

Name | Type |
------ | ------ |
`constructor` |  |
`getName` |  |

▪ **elementType**: *[TraitElementType](../modules/_models_core_.md#traitelementtype)*

**Returns:** *boolean*

___

###  hasState

▸ **hasState**(`state`: CoreInterface.StateClassDefinition): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[hasState](_models_traits_colorsetting_colorsetting_.colorsetting.md#hasstate)*

*Defined in [src/models/core.ts:578](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L578)*

**Parameters:**

Name | Type |
------ | ------ |
`state` | CoreInterface.StateClassDefinition |

**Returns:** *boolean*

▸ **hasState**(`stateName`: string): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[hasState](_models_traits_colorsetting_colorsetting_.colorsetting.md#hasstate)*

*Defined in [src/models/core.ts:579](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L579)*

**Parameters:**

Name | Type |
------ | ------ |
`stateName` | string |

**Returns:** *boolean*

___

###  hasStates

▸ **hasStates**(`stateNames`: string[]): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[hasStates](_models_traits_colorsetting_colorsetting_.colorsetting.md#hasstates)*

*Defined in [src/models/core.ts:584](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L584)*

**Parameters:**

Name | Type |
------ | ------ |
`stateNames` | string[] |

**Returns:** *boolean*

▸ **hasStates**(`states`: CoreInterface.StateClassDefinition[]): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[hasStates](_models_traits_colorsetting_colorsetting_.colorsetting.md#hasstates)*

*Defined in [src/models/core.ts:585](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L585)*

**Parameters:**

Name | Type |
------ | ------ |
`states` | CoreInterface.StateClassDefinition[] |

**Returns:** *boolean*

___

###  shouldHaveAttributes

▸ **shouldHaveAttributes**(`attributeNames`: string[]): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[shouldHaveAttributes](_models_traits_colorsetting_colorsetting_.colorsetting.md#shouldhaveattributes)*

*Defined in [src/models/core.ts:534](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L534)*

**Parameters:**

Name | Type |
------ | ------ |
`attributeNames` | string[] |

**Returns:** *boolean*

▸ **shouldHaveAttributes**(`attributes`: CoreInterface.AttributeClassDefinition[]): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[shouldHaveAttributes](_models_traits_colorsetting_colorsetting_.colorsetting.md#shouldhaveattributes)*

*Defined in [src/models/core.ts:535](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L535)*

**Parameters:**

Name | Type |
------ | ------ |
`attributes` | CoreInterface.AttributeClassDefinition[] |

**Returns:** *boolean*

___

###  shouldHaveCommands

▸ **shouldHaveCommands**(`commandNames`: string[]): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[shouldHaveCommands](_models_traits_colorsetting_colorsetting_.colorsetting.md#shouldhavecommands)*

*Defined in [src/models/core.ts:546](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L546)*

**Parameters:**

Name | Type |
------ | ------ |
`commandNames` | string[] |

**Returns:** *boolean*

▸ **shouldHaveCommands**(`commands`: CoreInterface.CommandClassDefinition[]): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[shouldHaveCommands](_models_traits_colorsetting_colorsetting_.colorsetting.md#shouldhavecommands)*

*Defined in [src/models/core.ts:547](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L547)*

**Parameters:**

Name | Type |
------ | ------ |
`commands` | CoreInterface.CommandClassDefinition[] |

**Returns:** *boolean*

___

###  shouldHaveElements

▸ **shouldHaveElements**(`elementNames`: string[], `elementType`: [TraitElementType](../modules/_models_core_.md#traitelementtype)): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[shouldHaveElements](_models_traits_colorsetting_colorsetting_.colorsetting.md#shouldhaveelements)*

*Defined in [src/models/core.ts:499](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L499)*

**Parameters:**

Name | Type |
------ | ------ |
`elementNames` | string[] |
`elementType` | [TraitElementType](../modules/_models_core_.md#traitelementtype) |

**Returns:** *boolean*

▸ **shouldHaveElements**(`elemnts`: CoreInterface.ElementClassDefinition, `elementType`: [TraitElementType](../modules/_models_core_.md#traitelementtype)): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[shouldHaveElements](_models_traits_colorsetting_colorsetting_.colorsetting.md#shouldhaveelements)*

*Defined in [src/models/core.ts:500](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L500)*

**Parameters:**

Name | Type |
------ | ------ |
`elemnts` | CoreInterface.ElementClassDefinition |
`elementType` | [TraitElementType](../modules/_models_core_.md#traitelementtype) |

**Returns:** *boolean*

___

###  shouldHaveStates

▸ **shouldHaveStates**(`stateNames`: string[]): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[shouldHaveStates](_models_traits_colorsetting_colorsetting_.colorsetting.md#shouldhavestates)*

*Defined in [src/models/core.ts:540](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L540)*

**Parameters:**

Name | Type |
------ | ------ |
`stateNames` | string[] |

**Returns:** *boolean*

▸ **shouldHaveStates**(`states`: CoreInterface.StateClassDefinition[]): *boolean*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[shouldHaveStates](_models_traits_colorsetting_colorsetting_.colorsetting.md#shouldhavestates)*

*Defined in [src/models/core.ts:541](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L541)*

**Parameters:**

Name | Type |
------ | ------ |
`states` | CoreInterface.StateClassDefinition[] |

**Returns:** *boolean*

___

###  toJsonObject

▸ **toJsonObject**(): *[VariableTrait](../interfaces/_models_interfaces_i_core_.variabletrait.md)*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[toJsonObject](_models_traits_colorsetting_colorsetting_.colorsetting.md#tojsonobject)*

*Defined in [src/models/core.ts:729](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L729)*

**Returns:** *[VariableTrait](../interfaces/_models_interfaces_i_core_.variabletrait.md)*

___

###  validate

▸ **validate**(): *boolean*

*Implementation of [Trait](../interfaces/_models_interfaces_i_core_.trait.md)*

*Overrides [Trait](_models_core_.trait.md).[validate](_models_core_.trait.md#abstract-validate)*

*Defined in [src/models/traits/modes/modes.ts:19](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/modes/modes.ts#L19)*

**Returns:** *boolean*

___

### `Static` getKeyName

▸ **getKeyName**(): *string*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[getKeyName](_models_traits_colorsetting_colorsetting_.colorsetting.md#static-getkeyname)*

*Defined in [src/models/core.ts:369](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L369)*

get object key name of trait

**Returns:** *string*

___

### `Static` getName

▸ **getName**(): *string*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[getName](_models_traits_colorsetting_colorsetting_.colorsetting.md#static-getname)*

*Defined in [src/models/core.ts:361](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L361)*

get name of trait. ex: action.devices.traits.Hoge

**Returns:** *string*

___

### `Static` init

▸ **init**(`param`: [VariableTrait](../interfaces/_models_interfaces_i_core_.variabletrait.md)): *[Modes](_models_traits_modes_modes_.modes.md)*

*Overrides [Trait](_models_core_.trait.md).[init](_models_core_.trait.md#static-init)*

*Defined in [src/models/traits/modes/modes.ts:15](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/modes/modes.ts#L15)*

**Parameters:**

Name | Type |
------ | ------ |
`param` | [VariableTrait](../interfaces/_models_interfaces_i_core_.variabletrait.md) |

**Returns:** *[Modes](_models_traits_modes_modes_.modes.md)*

___

### `Static` initWithJson

▸ **initWithJson**<**T**>(`trait`: object, `param`: [VariableTrait](../interfaces/_models_interfaces_i_core_.variabletrait.md), `traitSchemaImport`: [TraitSchemaImport](../interfaces/_models_interfaces_i_core_.traitschemaimport.md)): *T*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[initWithJson](_models_traits_colorsetting_colorsetting_.colorsetting.md#static-initwithjson)*

*Defined in [src/models/core.ts:637](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L637)*

create trait instance from json object.

**Type parameters:**

▪ **T**: *[Trait](_models_core_.trait.md)*

**Parameters:**

▪ **trait**: *object*

TraitClass (class definition. not instance.)

Name | Type |
------ | ------ |
`constructor` |  |

▪ **param**: *[VariableTrait](../interfaces/_models_interfaces_i_core_.variabletrait.md)*

VariableTrait

▪ **traitSchemaImport**: *[TraitSchemaImport](../interfaces/_models_interfaces_i_core_.traitschemaimport.md)*

**Returns:** *T*

___

### `Static` resolveAttributes

▸ **resolveAttributes**(`attributes`: VariableTrait["Attributes"], `traitAttributesImport`: TraitSchemaImport["Attribute"]): *Trait["Attributes"]*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[resolveAttributes](_models_traits_colorsetting_colorsetting_.colorsetting.md#static-resolveattributes)*

*Defined in [src/models/core.ts:659](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L659)*

create attribute instances from json object.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`attributes` | VariableTrait["Attributes"] | - |
`traitAttributesImport` | TraitSchemaImport["Attribute"] |   |

**Returns:** *Trait["Attributes"]*

___

### `Static` resolveCommands

▸ **resolveCommands**(`commands`: VariableTrait["Commands"], `traitCommandsImport`: TraitSchemaImport["Command"]): *Trait["Commands"]*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[resolveCommands](_models_traits_colorsetting_colorsetting_.colorsetting.md#static-resolvecommands)*

*Defined in [src/models/core.ts:709](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L709)*

create command instances from json object.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`commands` | VariableTrait["Commands"] | - |
`traitCommandsImport` | TraitSchemaImport["Command"] |   |

**Returns:** *Trait["Commands"]*

___

### `Static` resolveStates

▸ **resolveStates**(`states`: VariableTrait["States"], `traitStatesImport`: TraitSchemaImport["State"]): *Trait["States"]*

*Inherited from [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md).[resolveStates](_models_traits_colorsetting_colorsetting_.colorsetting.md#static-resolvestates)*

*Defined in [src/models/core.ts:684](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L684)*

create state instances from json object.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`states` | VariableTrait["States"] | - |
`traitStatesImport` | TraitSchemaImport["State"] |   |

**Returns:** *Trait["States"]*
