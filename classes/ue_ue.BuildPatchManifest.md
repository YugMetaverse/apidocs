[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BuildPatchManifest

# Class: BuildPatchManifest

[ue/ue](../modules/ue_ue.md).BuildPatchManifest

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`BuildPatchManifest`**

## Table of contents

### Constructors

- [constructor](ue_ue.BuildPatchManifest.md#constructor)

### Properties

- [AppID](ue_ue.BuildPatchManifest.md#appid)
- [AppName](ue_ue.BuildPatchManifest.md#appname)
- [BuildVersion](ue_ue.BuildPatchManifest.md#buildversion)
- [ChunkList](ue_ue.BuildPatchManifest.md#chunklist)
- [CustomFields](ue_ue.BuildPatchManifest.md#customfields)
- [FileManifestList](ue_ue.BuildPatchManifest.md#filemanifestlist)
- [LaunchCommand](ue_ue.BuildPatchManifest.md#launchcommand)
- [LaunchExe](ue_ue.BuildPatchManifest.md#launchexe)
- [ManifestFileVersion](ue_ue.BuildPatchManifest.md#manifestfileversion)
- [PrereqArgs](ue_ue.BuildPatchManifest.md#prereqargs)
- [PrereqIds](ue_ue.BuildPatchManifest.md#prereqids)
- [PrereqName](ue_ue.BuildPatchManifest.md#prereqname)
- [PrereqPath](ue_ue.BuildPatchManifest.md#prereqpath)
- [\_\_tid\_BuildPatchManifest\_\_](ue_ue.BuildPatchManifest.md#__tid_buildpatchmanifest__)
- [\_\_tid\_Object\_\_](ue_ue.BuildPatchManifest.md#__tid_object__)
- [bIsFileData](ue_ue.BuildPatchManifest.md#bisfiledata)

### Methods

- [CreateDefaultSubobject](ue_ue.BuildPatchManifest.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BuildPatchManifest.md#executeubergraph)
- [GetClass](ue_ue.BuildPatchManifest.md#getclass)
- [GetName](ue_ue.BuildPatchManifest.md#getname)
- [GetOuter](ue_ue.BuildPatchManifest.md#getouter)
- [GetWorld](ue_ue.BuildPatchManifest.md#getworld)
- [Find](ue_ue.BuildPatchManifest.md#find)
- [Load](ue_ue.BuildPatchManifest.md#load)
- [StaticClass](ue_ue.BuildPatchManifest.md#staticclass)

## Constructors

### constructor

• **new BuildPatchManifest**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AppID

• **AppID**: `number`

___

### AppName

• **AppName**: `string`

___

### BuildVersion

• **BuildVersion**: `string`

___

### ChunkList

• **ChunkList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ChunkInfoData`](ue_ue.ChunkInfoData.md)\>

___

### CustomFields

• **CustomFields**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CustomFieldData`](ue_ue.CustomFieldData.md)\>

___

### FileManifestList

• **FileManifestList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FileManifestData`](ue_ue.FileManifestData.md)\>

___

### LaunchCommand

• **LaunchCommand**: `string`

___

### LaunchExe

• **LaunchExe**: `string`

___

### ManifestFileVersion

• **ManifestFileVersion**: `number`

___

### PrereqArgs

• **PrereqArgs**: `string`

___

### PrereqIds

• **PrereqIds**: [`TSet`](../interfaces/ue_puerts.TSet.md)<`string`\>

___

### PrereqName

• **PrereqName**: `string`

___

### PrereqPath

• **PrereqPath**: `string`

___

### \_\_tid\_BuildPatchManifest\_\_

• **\_\_tid\_BuildPatchManifest\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bIsFileData

• **bIsFileData**: `boolean`

## Methods

### CreateDefaultSubobject

▸ **CreateDefaultSubobject**(`p0`, `p1`, `p2`, `p3`, `p4`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `string` |
| `p1` | [`Class`](ue_ue.Class.md) |
| `p2` | [`Class`](ue_ue.Class.md) |
| `p3` | `boolean` |
| `p4` | `boolean` |

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

___

### ExecuteUbergraph

▸ **ExecuteUbergraph**(`EntryPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryPoint` | `number` |

#### Returns

`void`

#### Inherited from

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BuildPatchManifest`](ue_ue.BuildPatchManifest.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BuildPatchManifest`](ue_ue.BuildPatchManifest.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BuildPatchManifest`](ue_ue.BuildPatchManifest.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BuildPatchManifest`](ue_ue.BuildPatchManifest.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
