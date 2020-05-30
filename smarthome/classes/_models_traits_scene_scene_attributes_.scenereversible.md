[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/scene/scene_attributes"](../modules/_models_traits_scene_scene_attributes_.md) › [SceneReversible](_models_traits_scene_scene_attributes_.scenereversible.md)

# Class: SceneReversible

Boolean, indicating that this scene may be reversed. This is only relevant for scenes that modify state and remember previous state. Obviously, scenes that fire specific actions may not be reversible — the bell cannot be unrung. If true, Deactivate Party Mode will function as expected.

## Hierarchy

* [Attribute](_models_core_.attribute.md)

  ↳ **SceneReversible**

## Implements

* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)
* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)

## Index

### Constructors

* [constructor](_models_traits_scene_scene_attributes_.scenereversible.md#constructor)

### Properties

* [name](_models_traits_scene_scene_attributes_.scenereversible.md#name)
* [value](_models_traits_scene_scene_attributes_.scenereversible.md#value)
* [_name](_models_traits_scene_scene_attributes_.scenereversible.md#static-_name)

### Methods

* [getKeyName](_models_traits_scene_scene_attributes_.scenereversible.md#getkeyname)
* [getName](_models_traits_scene_scene_attributes_.scenereversible.md#getname)
* [getKeyName](_models_traits_scene_scene_attributes_.scenereversible.md#static-getkeyname)
* [getName](_models_traits_scene_scene_attributes_.scenereversible.md#static-getname)

## Constructors

###  constructor

\+ **new SceneReversible**(`value`: SceneReversible["value"]): *[SceneReversible](_models_traits_scene_scene_attributes_.scenereversible.md)*

*Defined in [src/models/traits/scene/scene_attributes.ts:11](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/scene/scene_attributes.ts#L11)*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`value` | SceneReversible["value"] | boolean. indicating that this scene may be reversed. This is only relevant for scenes that modify state and remember previous state. Obviously, scenes that fire specific actions may not be reversible — the bell cannot be unrung. If true, Deactivate Party Mode will function as expected.  |

**Returns:** *[SceneReversible](_models_traits_scene_scene_attributes_.scenereversible.md)*

## Properties

###  name

• **name**: *"sceneReversible"* = SceneReversible._name

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[name](../interfaces/_models_interfaces_i_core_.attribute.md#name)*

*Overrides [Attribute](_models_core_.attribute.md).[name](_models_core_.attribute.md#name)*

*Defined in [src/models/traits/scene/scene_attributes.ts:10](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/scene/scene_attributes.ts#L10)*

___

###  value

• **value**: *SceneReversible["value"]* = false

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[value](../interfaces/_models_interfaces_i_core_.attribute.md#value)*

*Overrides [Attribute](_models_core_.attribute.md).[value](_models_core_.attribute.md#value)*

*Defined in [src/models/traits/scene/scene_attributes.ts:11](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/scene/scene_attributes.ts#L11)*

___

### `Static` _name

▪ **_name**: *"sceneReversible"* = "sceneReversible"

*Overrides [Attribute](_models_core_.attribute.md).[_name](_models_core_.attribute.md#static-_name)*

*Defined in [src/models/traits/scene/scene_attributes.ts:9](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/scene/scene_attributes.ts#L9)*

## Methods

###  getKeyName

▸ **getKeyName**(): *string*

*Inherited from [ColorModel](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md).[getKeyName](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md#static-getkeyname)*

*Defined in [src/models/core.ts:93](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L93)*

get attribute name in object. it is same as class name. ex: Hoge

**Returns:** *string*

___

###  getName

▸ **getName**(): *string*

*Inherited from [ColorModel](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md).[getName](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md#static-getname)*

*Defined in [src/models/core.ts:79](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L79)*

get attribute name. ex: hoge

**Returns:** *string*

___

### `Static` getKeyName

▸ **getKeyName**(): *string*

*Inherited from [ColorModel](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md).[getKeyName](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md#static-getkeyname)*

*Defined in [src/models/core.ts:86](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L86)*

get attribute name in object. it is same as class name. ex: Hoge

**Returns:** *string*

___

### `Static` getName

▸ **getName**(): *string*

*Inherited from [ColorModel](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md).[getName](_models_traits_colorsetting_colorsetting_attributes_.colormodel.md#static-getname)*

*Defined in [src/models/core.ts:72](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L72)*

get attribute name. ex: hoge

**Returns:** *string*
