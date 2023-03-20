[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SkeletalMeshLODSettings

# Class: SkeletalMeshLODSettings

[ue/ue](../modules/ue_ue.md).SkeletalMeshLODSettings

## Hierarchy

- [`DataAsset`](ue_ue.DataAsset.md)

  ↳ **`SkeletalMeshLODSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.SkeletalMeshLODSettings.md#constructor)

### Properties

- [DisableBelowMinLodStripping](ue_ue.SkeletalMeshLODSettings.md#disablebelowminlodstripping)
- [LODGroups](ue_ue.SkeletalMeshLODSettings.md#lodgroups)
- [MaxNumOptionalLODs](ue_ue.SkeletalMeshLODSettings.md#maxnumoptionallods)
- [MaxNumStreamedLODs](ue_ue.SkeletalMeshLODSettings.md#maxnumstreamedlods)
- [MinLod](ue_ue.SkeletalMeshLODSettings.md#minlod)
- [NativeClass](ue_ue.SkeletalMeshLODSettings.md#nativeclass)
- [\_\_tid\_DataAsset\_\_](ue_ue.SkeletalMeshLODSettings.md#__tid_dataasset__)
- [\_\_tid\_Object\_\_](ue_ue.SkeletalMeshLODSettings.md#__tid_object__)
- [\_\_tid\_SkeletalMeshLODSettings\_\_](ue_ue.SkeletalMeshLODSettings.md#__tid_skeletalmeshlodsettings__)
- [bSupportLODStreaming](ue_ue.SkeletalMeshLODSettings.md#bsupportlodstreaming)

### Methods

- [CreateDefaultSubobject](ue_ue.SkeletalMeshLODSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SkeletalMeshLODSettings.md#executeubergraph)
- [GetClass](ue_ue.SkeletalMeshLODSettings.md#getclass)
- [GetName](ue_ue.SkeletalMeshLODSettings.md#getname)
- [GetOuter](ue_ue.SkeletalMeshLODSettings.md#getouter)
- [GetWorld](ue_ue.SkeletalMeshLODSettings.md#getworld)
- [Find](ue_ue.SkeletalMeshLODSettings.md#find)
- [Load](ue_ue.SkeletalMeshLODSettings.md#load)
- [StaticClass](ue_ue.SkeletalMeshLODSettings.md#staticclass)

## Constructors

### constructor

• **new SkeletalMeshLODSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[constructor](ue_ue.DataAsset.md#constructor)

#### Defined in

[ue/ue.d.ts:3355](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3355)

## Properties

### DisableBelowMinLodStripping

• **DisableBelowMinLodStripping**: [`PerPlatformBool`](ue_ue.PerPlatformBool.md)

#### Defined in

[ue/ue.d.ts:3357](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3357)

___

### LODGroups

• **LODGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SkeletalMeshLODGroupSettings`](ue_ue.SkeletalMeshLODGroupSettings.md)\>

#### Defined in

[ue/ue.d.ts:3361](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3361)

___

### MaxNumOptionalLODs

• **MaxNumOptionalLODs**: [`PerPlatformInt`](ue_ue.PerPlatformInt.md)

#### Defined in

[ue/ue.d.ts:3360](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3360)

___

### MaxNumStreamedLODs

• **MaxNumStreamedLODs**: [`PerPlatformInt`](ue_ue.PerPlatformInt.md)

#### Defined in

[ue/ue.d.ts:3359](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3359)

___

### MinLod

• **MinLod**: [`PerPlatformInt`](ue_ue.PerPlatformInt.md)

#### Defined in

[ue/ue.d.ts:3356](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3356)

___

### NativeClass

• **NativeClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[NativeClass](ue_ue.DataAsset.md#nativeclass)

#### Defined in

[ue/ue.d.ts:724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L724)

___

### \_\_tid\_DataAsset\_\_

• **\_\_tid\_DataAsset\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_DataAsset__](ue_ue.DataAsset.md#__tid_dataasset__)

#### Defined in

[ue/ue.d.ts:729](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L729)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_Object__](ue_ue.DataAsset.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_SkeletalMeshLODSettings\_\_

• **\_\_tid\_SkeletalMeshLODSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3366](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3366)

___

### bSupportLODStreaming

• **bSupportLODStreaming**: [`PerPlatformBool`](ue_ue.PerPlatformBool.md)

#### Defined in

[ue/ue.d.ts:3358](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3358)

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

[DataAsset](ue_ue.DataAsset.md).[CreateDefaultSubobject](ue_ue.DataAsset.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[DataAsset](ue_ue.DataAsset.md).[ExecuteUbergraph](ue_ue.DataAsset.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetClass](ue_ue.DataAsset.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetName](ue_ue.DataAsset.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetOuter](ue_ue.DataAsset.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetWorld](ue_ue.DataAsset.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SkeletalMeshLODSettings`](ue_ue.SkeletalMeshLODSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SkeletalMeshLODSettings`](ue_ue.SkeletalMeshLODSettings.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[Find](ue_ue.DataAsset.md#find)

#### Defined in

[ue/ue.d.ts:3363](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3363)

___

### Load

▸ `Static` **Load**(`InName`): [`SkeletalMeshLODSettings`](ue_ue.SkeletalMeshLODSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SkeletalMeshLODSettings`](ue_ue.SkeletalMeshLODSettings.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[Load](ue_ue.DataAsset.md#load)

#### Defined in

[ue/ue.d.ts:3364](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3364)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[StaticClass](ue_ue.DataAsset.md#staticclass)

#### Defined in

[ue/ue.d.ts:3362](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3362)
