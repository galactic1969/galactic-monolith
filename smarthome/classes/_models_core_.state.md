[google-smarthome-models](../README.md) › [Globals](../globals.md) › ["models/core"](../modules/_models_core_.md) › [State](_models_core_.state.md)

# Class: State

## Hierarchy

* **State**

  ↳ [Color](_models_traits_colorsetting_colorsetting_states_.color.md)

  ↳ [CurrentInput](_models_traits_inputselector_inputselector_states_.currentinput.md)

  ↳ [On](_models_traits_onoff_onoff_states_.on.md)

  ↳ [OpenState](_models_traits_openclose_openclose_states_.openstate.md)

  ↳ [OpenPercent](_models_traits_openclose_openclose_states_.openpercent.md)

  ↳ [OpenDirection](_models_traits_openclose_openclose_states_.opendirection.md)

  ↳ [CurrentModeSettings](_models_traits_modes_modes_states_.currentmodesettings.md)

  ↳ [CurrentStatusReport](_models_traits_statusreport_statusreport_states_.currentstatusreport.md)

  ↳ [CurrentVolume](_models_traits_volume_volume_states_.currentvolume.md)

  ↳ [IsMuted](_models_traits_volume_volume_states_.ismuted.md)

  ↳ [TraitDoesNotHaveState](_models_core_.traitdoesnothavestate.md)

## Implements

* [State](../interfaces/_models_interfaces_i_core_.state.md)

## Index

### Properties

* [name](_models_core_.state.md#name)
* [value](_models_core_.state.md#value)
* [_name](_models_core_.state.md#static-_name)

### Methods

* [getKeyName](_models_core_.state.md#getkeyname)
* [getName](_models_core_.state.md#getname)
* [getKeyName](_models_core_.state.md#static-getkeyname)
* [getName](_models_core_.state.md#static-getname)

## Properties

###  name

• **name**: *string* = ""

*Implementation of [State](../interfaces/_models_interfaces_i_core_.state.md).[name](../interfaces/_models_interfaces_i_core_.state.md#name)*

*Defined in [src/models/core.ts:306](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L306)*

___

###  value

• **value**: *any*

*Implementation of [State](../interfaces/_models_interfaces_i_core_.state.md).[value](../interfaces/_models_interfaces_i_core_.state.md#value)*

*Defined in [src/models/core.ts:307](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L307)*

___

### `Static` _name

▪ **_name**: *string* = ""

*Defined in [src/models/core.ts:305](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L305)*

## Methods

###  getKeyName

▸ **getKeyName**(): *string*

*Defined in [src/models/core.ts:333](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L333)*

get state name in object. it is same as class name. ex: Hoge

**Returns:** *string*

___

###  getName

▸ **getName**(): *string*

*Defined in [src/models/core.ts:319](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L319)*

get command name. ex: action.devices.commands.Hoge

**Returns:** *string*

___

### `Static` getKeyName

▸ **getKeyName**(): *string*

*Defined in [src/models/core.ts:326](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L326)*

get state name in object. it is same as class name. ex: Hoge

**Returns:** *string*

___

### `Static` getName

▸ **getName**(): *string*

*Defined in [src/models/core.ts:312](https://github.com/galactic1969/google-smarthome-models/blob/633871f/src/models/core.ts#L312)*

get command name. ex: action.devices.commands.Hoge

**Returns:** *string*
