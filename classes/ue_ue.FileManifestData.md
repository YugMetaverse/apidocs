[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FileManifestData

# Class: FileManifestData

[ue/ue](../modules/ue_ue.md).FileManifestData

## Table of contents

### Constructors

- [constructor](ue_ue.FileManifestData.md#constructor)

### Properties

- [FileChunkParts](ue_ue.FileManifestData.md#filechunkparts)
- [FileHash](ue_ue.FileManifestData.md#filehash)
- [Filename](ue_ue.FileManifestData.md#filename)
- [InstallTags](ue_ue.FileManifestData.md#installtags)
- [SymlinkTarget](ue_ue.FileManifestData.md#symlinktarget)
- [\_\_tid\_FileManifestData\_\_](ue_ue.FileManifestData.md#__tid_filemanifestdata__)
- [bIsCompressed](ue_ue.FileManifestData.md#biscompressed)
- [bIsReadOnly](ue_ue.FileManifestData.md#bisreadonly)
- [bIsUnixExecutable](ue_ue.FileManifestData.md#bisunixexecutable)

### Methods

- [StaticClass](ue_ue.FileManifestData.md#staticclass)
- [StaticStruct](ue_ue.FileManifestData.md#staticstruct)

## Constructors

### constructor

• **new FileManifestData**()

#### Defined in

[ue/ue.d.ts:25495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25495)

• **new FileManifestData**(`Filename`, `FileHash`, `FileChunkParts`, `InstallTags`, `bIsUnixExecutable`, `SymlinkTarget`, `bIsReadOnly`, `bIsCompressed`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Filename` | `string` |
| `FileHash` | [`SHAHashData`](ue_ue.SHAHashData.md) |
| `FileChunkParts` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ChunkPartData`](ue_ue.ChunkPartData.md)\> |
| `InstallTags` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `bIsUnixExecutable` | `boolean` |
| `SymlinkTarget` | `string` |
| `bIsReadOnly` | `boolean` |
| `bIsCompressed` | `boolean` |

#### Defined in

[ue/ue.d.ts:25496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25496)

## Properties

### FileChunkParts

• **FileChunkParts**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ChunkPartData`](ue_ue.ChunkPartData.md)\>

#### Defined in

[ue/ue.d.ts:25499](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25499)

___

### FileHash

• **FileHash**: [`SHAHashData`](ue_ue.SHAHashData.md)

#### Defined in

[ue/ue.d.ts:25498](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25498)

___

### Filename

• **Filename**: `string`

#### Defined in

[ue/ue.d.ts:25497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25497)

___

### InstallTags

• **InstallTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:25500](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25500)

___

### SymlinkTarget

• **SymlinkTarget**: `string`

#### Defined in

[ue/ue.d.ts:25502](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25502)

___

### \_\_tid\_FileManifestData\_\_

• `Private` **\_\_tid\_FileManifestData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:25510](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25510)

___

### bIsCompressed

• **bIsCompressed**: `boolean`

#### Defined in

[ue/ue.d.ts:25504](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25504)

___

### bIsReadOnly

• **bIsReadOnly**: `boolean`

#### Defined in

[ue/ue.d.ts:25503](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25503)

___

### bIsUnixExecutable

• **bIsUnixExecutable**: `boolean`

#### Defined in

[ue/ue.d.ts:25501](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25501)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:25508](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25508)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:25509](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L25509)
