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

## Properties

### FileChunkParts

• **FileChunkParts**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ChunkPartData`](ue_ue.ChunkPartData.md)\>

___

### FileHash

• **FileHash**: [`SHAHashData`](ue_ue.SHAHashData.md)

___

### Filename

• **Filename**: `string`

___

### InstallTags

• **InstallTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### SymlinkTarget

• **SymlinkTarget**: `string`

___

### \_\_tid\_FileManifestData\_\_

• `Private` **\_\_tid\_FileManifestData\_\_**: `boolean`

___

### bIsCompressed

• **bIsCompressed**: `boolean`

___

### bIsReadOnly

• **bIsReadOnly**: `boolean`

___

### bIsUnixExecutable

• **bIsUnixExecutable**: `boolean`

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
