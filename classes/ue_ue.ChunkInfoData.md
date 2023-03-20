[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ChunkInfoData

# Class: ChunkInfoData

[ue/ue](../modules/ue_ue.md).ChunkInfoData

## Table of contents

### Constructors

- [constructor](ue_ue.ChunkInfoData.md#constructor)

### Properties

- [FileSize](ue_ue.ChunkInfoData.md#filesize)
- [GroupNumber](ue_ue.ChunkInfoData.md#groupnumber)
- [Guid](ue_ue.ChunkInfoData.md#guid)
- [Hash](ue_ue.ChunkInfoData.md#hash)
- [ShaHash](ue_ue.ChunkInfoData.md#shahash)
- [\_\_tid\_ChunkInfoData\_\_](ue_ue.ChunkInfoData.md#__tid_chunkinfodata__)

### Methods

- [StaticClass](ue_ue.ChunkInfoData.md#staticclass)
- [StaticStruct](ue_ue.ChunkInfoData.md#staticstruct)

## Constructors

### constructor

• **new ChunkInfoData**()

• **new ChunkInfoData**(`Guid`, `Hash`, `ShaHash`, `FileSize`, `GroupNumber`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Guid` | [`Guid`](ue_ue_s.Guid.md) |
| `Hash` | `bigint` |
| `ShaHash` | [`SHAHashData`](ue_ue.SHAHashData.md) |
| `FileSize` | `bigint` |
| `GroupNumber` | `number` |

## Properties

### FileSize

• **FileSize**: `bigint`

___

### GroupNumber

• **GroupNumber**: `number`

___

### Guid

• **Guid**: [`Guid`](ue_ue_s.Guid.md)

___

### Hash

• **Hash**: `bigint`

___

### ShaHash

• **ShaHash**: [`SHAHashData`](ue_ue.SHAHashData.md)

___

### \_\_tid\_ChunkInfoData\_\_

• `Private` **\_\_tid\_ChunkInfoData\_\_**: `boolean`

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
