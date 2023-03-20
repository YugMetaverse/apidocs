[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlackboardEntry

# Class: BlackboardEntry

[ue/ue](../modules/ue_ue.md).BlackboardEntry

## Table of contents

### Constructors

- [constructor](ue_ue.BlackboardEntry.md#constructor)

### Properties

- [EntryDescription](ue_ue.BlackboardEntry.md#entrydescription)
- [EntryName](ue_ue.BlackboardEntry.md#entryname)
- [KeyType](ue_ue.BlackboardEntry.md#keytype)
- [\_\_tid\_BlackboardEntry\_\_](ue_ue.BlackboardEntry.md#__tid_blackboardentry__)
- [bInstanceSynced](ue_ue.BlackboardEntry.md#binstancesynced)

### Methods

- [StaticClass](ue_ue.BlackboardEntry.md#staticclass)
- [StaticStruct](ue_ue.BlackboardEntry.md#staticstruct)

## Constructors

### constructor

• **new BlackboardEntry**()

• **new BlackboardEntry**(`EntryName`, `EntryDescription`, `KeyType`, `bInstanceSynced`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryName` | `string` |
| `EntryDescription` | `string` |
| `KeyType` | [`BlackboardKeyType`](ue_ue.BlackboardKeyType.md) |
| `bInstanceSynced` | `boolean` |

## Properties

### EntryDescription

• **EntryDescription**: `string`

___

### EntryName

• **EntryName**: `string`

___

### KeyType

• **KeyType**: [`BlackboardKeyType`](ue_ue.BlackboardKeyType.md)

___

### \_\_tid\_BlackboardEntry\_\_

• `Private` **\_\_tid\_BlackboardEntry\_\_**: `boolean`

___

### bInstanceSynced

• **bInstanceSynced**: `boolean`

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
