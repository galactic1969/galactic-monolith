[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/core"](../modules/_models_core_.md) › [Trait](_models_core_.trait.md)

# Class: Trait

## Hierarchy

* **Trait**

  ↳ [ColorSetting](_models_traits_colorsetting_colorsetting_.colorsetting.md)

  ↳ [InputSelector](_models_traits_inputselector_inputselector_.inputselector.md)

  ↳ [OnOff](_models_traits_onoff_onoff_.onoff.md)

  ↳ [OpenClose](_models_traits_openclose_openclose_.openclose.md)

  ↳ [Modes](_models_traits_modes_modes_.modes.md)

  ↳ [Scene](_models_traits_scene_scene_.scene.md)

  ↳ [StatusReport](_models_traits_statusreport_statusreport_.statusreport.md)

  ↳ [Volume](_models_traits_volume_volume_.volume.md)

## Implements

* [Trait](../interfaces/_models_interfaces_i_core_.trait.md)

## Index

### Constructors

* [constructor](_models_core_.trait.md#constructor)

### Properties

* [Attributes](_models_core_.trait.md#attributes)
* [Commands](_models_core_.trait.md#commands)
* [States](_models_core_.trait.md#states)
* [name](_models_core_.trait.md#name)

### Methods

* [getAttribute](_models_core_.trait.md#getattribute)
* [getCommand](_models_core_.trait.md#getcommand)
* [getElement](_models_core_.trait.md#getelement)
* [getElements](_models_core_.trait.md#getelements)
* [getKeyName](_models_core_.trait.md#getkeyname)
* [getMergedAttributes](_models_core_.trait.md#getmergedattributes)
* [getMergedStates](_models_core_.trait.md#getmergedstates)
* [getState](_models_core_.trait.md#getstate)
* [hasAttribute](_models_core_.trait.md#hasattribute)
* [hasAttributes](_models_core_.trait.md#hasattributes)
* [hasCommand](_models_core_.trait.md#hascommand)
* [hasCommands](_models_core_.trait.md#hascommands)
* [hasElement](_models_core_.trait.md#haselement)
* [hasState](_models_core_.trait.md#hasstate)
* [hasStates](_models_core_.trait.md#hasstates)
* [isElementDefinitionArray](_models_core_.trait.md#private-iselementdefinitionarray)
* [isStringArrray](_models_core_.trait.md#private-isstringarrray)
* [shouldHaveAttributes](_models_core_.trait.md#shouldhaveattributes)
* [shouldHaveCommands](_models_core_.trait.md#shouldhavecommands)
* [shouldHaveElements](_models_core_.trait.md#shouldhaveelements)
* [shouldHaveStates](_models_core_.trait.md#shouldhavestates)
* [toJsonObject](_models_core_.trait.md#tojsonobject)
* [validate](_models_core_.trait.md#abstract-validate)
* [getKeyName](_models_core_.trait.md#static-getkeyname)
* [getName](_models_core_.trait.md#static-getname)
* [init](_models_core_.trait.md#static-init)
* [initWithJson](_models_core_.trait.md#static-initwithjson)
* [resolveAttributes](_models_core_.trait.md#static-resolveattributes)
* [resolveCommands](_models_core_.trait.md#static-resolvecommands)
* [resolveStates](_models_core_.trait.md#static-resolvestates)

## Constructors

###  constructor

\+ **new Trait**(`param`: object): *[Trait](_models_core_.trait.md)*

*Defined in [src/models/core.ts:342](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L342)*

**Parameters:**

▪ **param**: *object*

Name | Type |
------ | ------ |
`Attributes` | object |
`Commands` | object |
`States` | object |

**Returns:** *[Trait](_models_core_.trait.md)*

## Properties

###  Attributes

• **Attributes**: *object*

*Implementation of [Trait](../interfaces/_models_interfaces_i_core_.trait.md).[Attributes](../interfaces/_models_interfaces_i_core_.trait.md#attributes)*

*Defined in [src/models/core.ts:340](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L340)*

#### Type declaration:

* \[ **index**: *string*\]: [Attribute](_models_core_.attribute.md)

___

###  Commands

• **Commands**: *object*

*Implementation of [Trait](../interfaces/_models_interfaces_i_core_.trait.md).[Commands](../interfaces/_models_interfaces_i_core_.trait.md#commands)*

*Defined in [src/models/core.ts:341](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L341)*

#### Type declaration:

* \[ **index**: *string*\]: [Command](_models_core_.command.md)

___

###  States

• **States**: *object*

*Implementation of [Trait](../interfaces/_models_interfaces_i_core_.trait.md).[States](../interfaces/_models_interfaces_i_core_.trait.md#states)*

*Defined in [src/models/core.ts:342](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L342)*

#### Type declaration:

* \[ **index**: *string*\]: [State](_models_core_.state.md)

___

###  name

• **name**: *string* = ""

*Implementation of [Trait](../interfaces/_models_interfaces_i_core_.trait.md).[name](../interfaces/_models_interfaces_i_core_.trait.md#name)*

*Defined in [src/models/core.ts:339](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L339)*

## Methods

###  getAttribute

▸ **getAttribute**<**T**>(`attribute`: object): *T*

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

*Defined in [src/models/core.ts:409](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L409)*

**Parameters:**

Name | Type |
------ | ------ |
`name` | string |
`elementType` | [TraitElementType](../modules/_models_core_.md#traitelementtype) |

**Returns:** *[TraitElementClass](../modules/_models_core_.md#traitelementclass)*

▸ **getElement**(`elementDefinition`: object, `elementType`: [TraitElementType](../modules/_models_core_.md#traitelementtype)): *[TraitElementClass](../modules/_models_core_.md#traitelementclass)*

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

*Defined in [src/models/core.ts:437](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L437)*

**Parameters:**

Name | Type |
------ | ------ |
`names` | string[] |
`elementType` | [TraitElementType](../modules/_models_core_.md#traitelementtype) |

**Returns:** *[TraitElementClass](../modules/_models_core_.md#traitelementclass)[]*

▸ **getElements**(`elementDefinitions`: object[], `elementType`: [TraitElementType](../modules/_models_core_.md#traitelementtype)): *[TraitElementClass](../modules/_models_core_.md#traitelementclass)[]*

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

*Defined in [src/models/core.ts:376](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L376)*

get object key name of trait

**Returns:** *string*

___

###  getMergedAttributes

▸ **getMergedAttributes**(): *object*

*Defined in [src/models/core.ts:382](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L382)*

**Returns:** *object*

* \[ **index**: *string*\]: any

___

###  getMergedStates

▸ **getMergedStates**(): *object*

*Defined in [src/models/core.ts:391](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L391)*

**Returns:** *object*

* \[ **index**: *string*\]: any

___

###  getState

▸ **getState**<**T**>(`state`: object): *T*

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

*Defined in [src/models/core.ts:552](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L552)*

**Parameters:**

Name | Type |
------ | ------ |
`attribute` | CoreInterface.AttributeClassDefinition |

**Returns:** *boolean*

▸ **hasAttribute**(`attributeName`: string): *boolean*

*Defined in [src/models/core.ts:553](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L553)*

**Parameters:**

Name | Type |
------ | ------ |
`attributeName` | string |

**Returns:** *boolean*

___

###  hasAttributes

▸ **hasAttributes**(`attributeNames`: string[]): *boolean*

*Defined in [src/models/core.ts:558](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L558)*

**Parameters:**

Name | Type |
------ | ------ |
`attributeNames` | string[] |

**Returns:** *boolean*

▸ **hasAttributes**(`attributes`: CoreInterface.AttributeClassDefinition[]): *boolean*

*Defined in [src/models/core.ts:559](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L559)*

**Parameters:**

Name | Type |
------ | ------ |
`attributes` | CoreInterface.AttributeClassDefinition[] |

**Returns:** *boolean*

___

###  hasCommand

▸ **hasCommand**(`command`: CoreInterface.CommandClassDefinition): *boolean*

*Defined in [src/models/core.ts:605](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L605)*

**Parameters:**

Name | Type |
------ | ------ |
`command` | CoreInterface.CommandClassDefinition |

**Returns:** *boolean*

▸ **hasCommand**(`commandName`: string): *boolean*

*Defined in [src/models/core.ts:606](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L606)*

**Parameters:**

Name | Type |
------ | ------ |
`commandName` | string |

**Returns:** *boolean*

___

###  hasCommands

▸ **hasCommands**(`commandNames`: string[]): *boolean*

*Defined in [src/models/core.ts:611](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L611)*

**Parameters:**

Name | Type |
------ | ------ |
`commandNames` | string[] |

**Returns:** *boolean*

▸ **hasCommands**(`commands`: CoreInterface.CommandClassDefinition[]): *boolean*

*Defined in [src/models/core.ts:612](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L612)*

**Parameters:**

Name | Type |
------ | ------ |
`commands` | CoreInterface.CommandClassDefinition[] |

**Returns:** *boolean*

___

###  hasElement

▸ **hasElement**(`name`: string, `elementType`: [TraitElementType](../modules/_models_core_.md#traitelementtype)): *boolean*

*Defined in [src/models/core.ts:478](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L478)*

**Parameters:**

Name | Type |
------ | ------ |
`name` | string |
`elementType` | [TraitElementType](../modules/_models_core_.md#traitelementtype) |

**Returns:** *boolean*

▸ **hasElement**(`elementDefinition`: object, `elementType`: [TraitElementType](../modules/_models_core_.md#traitelementtype)): *boolean*

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

*Defined in [src/models/core.ts:578](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L578)*

**Parameters:**

Name | Type |
------ | ------ |
`state` | CoreInterface.StateClassDefinition |

**Returns:** *boolean*

▸ **hasState**(`stateName`: string): *boolean*

*Defined in [src/models/core.ts:579](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L579)*

**Parameters:**

Name | Type |
------ | ------ |
`stateName` | string |

**Returns:** *boolean*

___

###  hasStates

▸ **hasStates**(`stateNames`: string[]): *boolean*

*Defined in [src/models/core.ts:584](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L584)*

**Parameters:**

Name | Type |
------ | ------ |
`stateNames` | string[] |

**Returns:** *boolean*

▸ **hasStates**(`states`: CoreInterface.StateClassDefinition[]): *boolean*

*Defined in [src/models/core.ts:585](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L585)*

**Parameters:**

Name | Type |
------ | ------ |
`states` | CoreInterface.StateClassDefinition[] |

**Returns:** *boolean*

___

### `Private` isElementDefinitionArray

▸ **isElementDefinitionArray**(`arg`: any): *arg is CoreInterface.ElementClassDefinition[]*

*Defined in [src/models/core.ts:405](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L405)*

**Parameters:**

Name | Type |
------ | ------ |
`arg` | any |

**Returns:** *arg is CoreInterface.ElementClassDefinition[]*

___

### `Private` isStringArrray

▸ **isStringArrray**(`arg`: any): *arg is string[]*

*Defined in [src/models/core.ts:401](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L401)*

**Parameters:**

Name | Type |
------ | ------ |
`arg` | any |

**Returns:** *arg is string[]*

___

###  shouldHaveAttributes

▸ **shouldHaveAttributes**(`attributeNames`: string[]): *boolean*

*Defined in [src/models/core.ts:534](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L534)*

**Parameters:**

Name | Type |
------ | ------ |
`attributeNames` | string[] |

**Returns:** *boolean*

▸ **shouldHaveAttributes**(`attributes`: CoreInterface.AttributeClassDefinition[]): *boolean*

*Defined in [src/models/core.ts:535](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L535)*

**Parameters:**

Name | Type |
------ | ------ |
`attributes` | CoreInterface.AttributeClassDefinition[] |

**Returns:** *boolean*

___

###  shouldHaveCommands

▸ **shouldHaveCommands**(`commandNames`: string[]): *boolean*

*Defined in [src/models/core.ts:546](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L546)*

**Parameters:**

Name | Type |
------ | ------ |
`commandNames` | string[] |

**Returns:** *boolean*

▸ **shouldHaveCommands**(`commands`: CoreInterface.CommandClassDefinition[]): *boolean*

*Defined in [src/models/core.ts:547](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L547)*

**Parameters:**

Name | Type |
------ | ------ |
`commands` | CoreInterface.CommandClassDefinition[] |

**Returns:** *boolean*

___

###  shouldHaveElements

▸ **shouldHaveElements**(`elementNames`: string[], `elementType`: [TraitElementType](../modules/_models_core_.md#traitelementtype)): *boolean*

*Defined in [src/models/core.ts:499](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L499)*

**Parameters:**

Name | Type |
------ | ------ |
`elementNames` | string[] |
`elementType` | [TraitElementType](../modules/_models_core_.md#traitelementtype) |

**Returns:** *boolean*

▸ **shouldHaveElements**(`elemnts`: CoreInterface.ElementClassDefinition, `elementType`: [TraitElementType](../modules/_models_core_.md#traitelementtype)): *boolean*

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

*Defined in [src/models/core.ts:540](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L540)*

**Parameters:**

Name | Type |
------ | ------ |
`stateNames` | string[] |

**Returns:** *boolean*

▸ **shouldHaveStates**(`states`: CoreInterface.StateClassDefinition[]): *boolean*

*Defined in [src/models/core.ts:541](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L541)*

**Parameters:**

Name | Type |
------ | ------ |
`states` | CoreInterface.StateClassDefinition[] |

**Returns:** *boolean*

___

###  toJsonObject

▸ **toJsonObject**(): *[VariableTrait](../interfaces/_models_interfaces_i_core_.variabletrait.md)*

*Defined in [src/models/core.ts:729](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L729)*

**Returns:** *[VariableTrait](../interfaces/_models_interfaces_i_core_.variabletrait.md)*

___

### `Abstract` validate

▸ **validate**(): *boolean*

*Implementation of [Trait](../interfaces/_models_interfaces_i_core_.trait.md)*

*Defined in [src/models/core.ts:380](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L380)*

**Returns:** *boolean*

___

### `Static` getKeyName

▸ **getKeyName**(): *string*

*Defined in [src/models/core.ts:369](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L369)*

get object key name of trait

**Returns:** *string*

___

### `Static` getName

▸ **getName**(): *string*

*Defined in [src/models/core.ts:361](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L361)*

get name of trait. ex: action.devices.traits.Hoge

**Returns:** *string*

___

### `Static` init

▸ **init**(`param`: any): *any*

*Defined in [src/models/core.ts:650](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L650)*

**Parameters:**

Name | Type |
------ | ------ |
`param` | any |

**Returns:** *any*

___

### `Static` initWithJson

▸ **initWithJson**<**T**>(`trait`: object, `param`: [VariableTrait](../interfaces/_models_interfaces_i_core_.variabletrait.md), `traitSchemaImport`: [TraitSchemaImport](../interfaces/_models_interfaces_i_core_.traitschemaimport.md)): *T*

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

*Defined in [src/models/core.ts:684](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L684)*

create state instances from json object.

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`states` | VariableTrait["States"] | - |
`traitStatesImport` | TraitSchemaImport["State"] |   |

**Returns:** *Trait["States"]*
