[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CustomizedToolMenu

# Class: CustomizedToolMenu

[ue/ue](../modules/ue_ue.md).CustomizedToolMenu

## Table of contents

### Constructors

- [constructor](ue_ue.CustomizedToolMenu.md#constructor)

### Properties

- [Entries](ue_ue.CustomizedToolMenu.md#entries)
- [EntryOrder](ue_ue.CustomizedToolMenu.md#entryorder)
- [Name](ue_ue.CustomizedToolMenu.md#name)
- [SectionOrder](ue_ue.CustomizedToolMenu.md#sectionorder)
- [Sections](ue_ue.CustomizedToolMenu.md#sections)
- [\_\_tid\_CustomizedToolMenu\_\_](ue_ue.CustomizedToolMenu.md#__tid_customizedtoolmenu__)

### Methods

- [StaticClass](ue_ue.CustomizedToolMenu.md#staticclass)
- [StaticStruct](ue_ue.CustomizedToolMenu.md#staticstruct)

## Constructors

### constructor

• **new CustomizedToolMenu**()

• **new CustomizedToolMenu**(`Name`, `Entries`, `Sections`, `EntryOrder`, `SectionOrder`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `Entries` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`CustomizedToolMenuEntry`](ue_ue.CustomizedToolMenuEntry.md)\> |
| `Sections` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`CustomizedToolMenuSection`](ue_ue.CustomizedToolMenuSection.md)\> |
| `EntryOrder` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`CustomizedToolMenuNameArray`](ue_ue.CustomizedToolMenuNameArray.md)\> |
| `SectionOrder` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

## Properties

### Entries

• **Entries**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`CustomizedToolMenuEntry`](ue_ue.CustomizedToolMenuEntry.md)\>

___

### EntryOrder

• **EntryOrder**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`CustomizedToolMenuNameArray`](ue_ue.CustomizedToolMenuNameArray.md)\>

___

### Name

• **Name**: `string`

___

### SectionOrder

• **SectionOrder**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### Sections

• **Sections**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`CustomizedToolMenuSection`](ue_ue.CustomizedToolMenuSection.md)\>

___

### \_\_tid\_CustomizedToolMenu\_\_

• `Private` **\_\_tid\_CustomizedToolMenu\_\_**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
