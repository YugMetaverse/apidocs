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

## Properties

### DisableBelowMinLodStripping

• **DisableBelowMinLodStripping**: [`PerPlatformBool`](ue_ue.PerPlatformBool.md)

___

### LODGroups

• **LODGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SkeletalMeshLODGroupSettings`](ue_ue.SkeletalMeshLODGroupSettings.md)\>

___

### MaxNumOptionalLODs

• **MaxNumOptionalLODs**: [`PerPlatformInt`](ue_ue.PerPlatformInt.md)

___

### MaxNumStreamedLODs

• **MaxNumStreamedLODs**: [`PerPlatformInt`](ue_ue.PerPlatformInt.md)

___

### MinLod

• **MinLod**: [`PerPlatformInt`](ue_ue.PerPlatformInt.md)

___

### NativeClass

• **NativeClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[NativeClass](ue_ue.DataAsset.md#nativeclass)

___

### \_\_tid\_DataAsset\_\_

• **\_\_tid\_DataAsset\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_DataAsset__](ue_ue.DataAsset.md#__tid_dataasset__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_Object__](ue_ue.DataAsset.md#__tid_object__)

___

### \_\_tid\_SkeletalMeshLODSettings\_\_

• **\_\_tid\_SkeletalMeshLODSettings\_\_**: `boolean`

___

### bSupportLODStreaming

• **bSupportLODStreaming**: [`PerPlatformBool`](ue_ue.PerPlatformBool.md)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetClass](ue_ue.DataAsset.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetName](ue_ue.DataAsset.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetOuter](ue_ue.DataAsset.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetWorld](ue_ue.DataAsset.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[StaticClass](ue_ue.DataAsset.md#staticclass)
