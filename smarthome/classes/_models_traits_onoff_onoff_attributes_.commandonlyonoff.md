[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/traits/onoff/onoff_attributes"](../modules/_models_traits_onoff_onoff_attributes_.md) › [CommandOnlyOnOff](_models_traits_onoff_onoff_attributes_.commandonlyonoff.md)

# Class: CommandOnlyOnOff

Boolean. Optional. Defaults to false. Indicates if the device operates using one-way (true) or two-way (false) communication. For example, if the controller can confirm the new device state after sending the request, this field would be false. If it's not possible to confirm if the request is successfully executed or to get the state of the device, set this field to true.

## Hierarchy

* [Attribute](_models_core_.attribute.md)

  ↳ **CommandOnlyOnOff**

## Implements

* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)
* [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md)

## Index

### Constructors

* [constructor](_models_traits_onoff_onoff_attributes_.commandonlyonoff.md#constructor)

### Properties

* [name](_models_traits_onoff_onoff_attributes_.commandonlyonoff.md#name)
* [value](_models_traits_onoff_onoff_attributes_.commandonlyonoff.md#value)
* [_name](_models_traits_onoff_onoff_attributes_.commandonlyonoff.md#static-_name)

### Methods

* [getKeyName](_models_traits_onoff_onoff_attributes_.commandonlyonoff.md#getkeyname)
* [getName](_models_traits_onoff_onoff_attributes_.commandonlyonoff.md#getname)
* [getKeyName](_models_traits_onoff_onoff_attributes_.commandonlyonoff.md#static-getkeyname)
* [getName](_models_traits_onoff_onoff_attributes_.commandonlyonoff.md#static-getname)

## Constructors

###  constructor

\+ **new CommandOnlyOnOff**(`value`: CommandOnlyOnOff["value"]): *[CommandOnlyOnOff](_models_traits_onoff_onoff_attributes_.commandonlyonoff.md)*

*Defined in [src/models/traits/onoff/onoff_attributes.ts:11](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/onoff/onoff_attributes.ts#L11)*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`value` | CommandOnlyOnOff["value"] | Boolean. Whether a device with an on/off switch is on or off.  |

**Returns:** *[CommandOnlyOnOff](_models_traits_onoff_onoff_attributes_.commandonlyonoff.md)*

## Properties

###  name

• **name**: *"commandOnlyOnOff"* = CommandOnlyOnOff._name

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[name](../interfaces/_models_interfaces_i_core_.attribute.md#name)*

*Overrides [Attribute](_models_core_.attribute.md).[name](_models_core_.attribute.md#name)*

*Defined in [src/models/traits/onoff/onoff_attributes.ts:10](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/onoff/onoff_attributes.ts#L10)*

___

###  value

• **value**: *CommandOnlyOnOff["value"]* = false

*Implementation of [Attribute](../interfaces/_models_interfaces_i_core_.attribute.md).[value](../interfaces/_models_interfaces_i_core_.attribute.md#value)*

*Overrides [Attribute](_models_core_.attribute.md).[value](_models_core_.attribute.md#value)*

*Defined in [src/models/traits/onoff/onoff_attributes.ts:11](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/onoff/onoff_attributes.ts#L11)*

___

### `Static` _name

▪ **_name**: *"commandOnlyOnOff"* = "commandOnlyOnOff"

*Overrides [Attribute](_models_core_.attribute.md).[_name](_models_core_.attribute.md#static-_name)*

*Defined in [src/models/traits/onoff/onoff_attributes.ts:9](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/traits/onoff/onoff_attributes.ts#L9)*

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
