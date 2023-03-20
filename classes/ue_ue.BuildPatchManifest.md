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

#### Defined in

[ue/ue.d.ts:25543](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25543)

## Properties

### AppID

• **AppID**: `number`

#### Defined in

[ue/ue.d.ts:25546](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25546)

___

### AppName

• **AppName**: `string`

#### Defined in

[ue/ue.d.ts:25547](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25547)

___

### BuildVersion

• **BuildVersion**: `string`

#### Defined in

[ue/ue.d.ts:25548](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25548)

___

### ChunkList

• **ChunkList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ChunkInfoData`](ue_ue.ChunkInfoData.md)\>

#### Defined in

[ue/ue.d.ts:25556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25556)

___

### CustomFields

• **CustomFields**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CustomFieldData`](ue_ue.CustomFieldData.md)\>

#### Defined in

[ue/ue.d.ts:25557](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25557)

___

### FileManifestList

• **FileManifestList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FileManifestData`](ue_ue.FileManifestData.md)\>

#### Defined in

[ue/ue.d.ts:25555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25555)

___

### LaunchCommand

• **LaunchCommand**: `string`

#### Defined in

[ue/ue.d.ts:25550](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25550)

___

### LaunchExe

• **LaunchExe**: `string`

#### Defined in

[ue/ue.d.ts:25549](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25549)

___

### ManifestFileVersion

• **ManifestFileVersion**: `number`

#### Defined in

[ue/ue.d.ts:25544](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25544)

___

### PrereqArgs

• **PrereqArgs**: `string`

#### Defined in

[ue/ue.d.ts:25554](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25554)

___

### PrereqIds

• **PrereqIds**: [`TSet`](../interfaces/ue_puerts.TSet.md)<`string`\>

#### Defined in

[ue/ue.d.ts:25551](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25551)

___

### PrereqName

• **PrereqName**: `string`

#### Defined in

[ue/ue.d.ts:25552](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25552)

___

### PrereqPath

• **PrereqPath**: `string`

#### Defined in

[ue/ue.d.ts:25553](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25553)

___

### \_\_tid\_BuildPatchManifest\_\_

• **\_\_tid\_BuildPatchManifest\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:25562](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25562)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bIsFileData

• **bIsFileData**: `boolean`

#### Defined in

[ue/ue.d.ts:25545](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25545)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:25559](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25559)

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

#### Defined in

[ue/ue.d.ts:25560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25560)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:25558](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25558)
