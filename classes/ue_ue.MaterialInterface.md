[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialInterface

# Class: MaterialInterface

[ue/ue](../modules/ue_ue.md).MaterialInterface

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MaterialInterface`**

  ↳↳ [`Material`](ue_ue.Material.md)

  ↳↳ [`MaterialInstance`](ue_ue.MaterialInstance.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialInterface.md#constructor)

### Properties

- [AssetImportData](ue_ue.MaterialInterface.md#assetimportdata)
- [AssetUserData](ue_ue.MaterialInterface.md#assetuserdata)
- [LayerParameterExpansion](ue_ue.MaterialInterface.md#layerparameterexpansion)
- [LightingGuid](ue_ue.MaterialInterface.md#lightingguid)
- [LightmassSettings](ue_ue.MaterialInterface.md#lightmasssettings)
- [ParameterOverviewExpansion](ue_ue.MaterialInterface.md#parameteroverviewexpansion)
- [PreviewMesh](ue_ue.MaterialInterface.md#previewmesh)
- [SubsurfaceProfile](ue_ue.MaterialInterface.md#subsurfaceprofile)
- [TextureStreamingData](ue_ue.MaterialInterface.md#texturestreamingdata)
- [TextureStreamingDataMissingEntries](ue_ue.MaterialInterface.md#texturestreamingdatamissingentries)
- [TextureStreamingDataVersion](ue_ue.MaterialInterface.md#texturestreamingdataversion)
- [ThumbnailInfo](ue_ue.MaterialInterface.md#thumbnailinfo)
- [\_\_tid\_MaterialInterface\_\_](ue_ue.MaterialInterface.md#__tid_materialinterface__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialInterface.md#__tid_object__)
- [bTextureStreamingDataSorted](ue_ue.MaterialInterface.md#btexturestreamingdatasorted)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialInterface.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialInterface.md#executeubergraph)
- [GetBaseMaterial](ue_ue.MaterialInterface.md#getbasematerial)
- [GetClass](ue_ue.MaterialInterface.md#getclass)
- [GetName](ue_ue.MaterialInterface.md#getname)
- [GetOuter](ue_ue.MaterialInterface.md#getouter)
- [GetPhysicalMaterial](ue_ue.MaterialInterface.md#getphysicalmaterial)
- [GetWorld](ue_ue.MaterialInterface.md#getworld)
- [SetForceMipLevelsToBeResident](ue_ue.MaterialInterface.md#setforcemiplevelstoberesident)
- [Find](ue_ue.MaterialInterface.md#find)
- [Load](ue_ue.MaterialInterface.md#load)
- [StaticClass](ue_ue.MaterialInterface.md#staticclass)

## Constructors

### constructor

• **new MaterialInterface**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:1544](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1544)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Defined in

[ue/ue.d.ts:1556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1556)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Defined in

[ue/ue.d.ts:1550](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1550)

___

### LayerParameterExpansion

• **LayerParameterExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

#### Defined in

[ue/ue.d.ts:1554](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1554)

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:1557](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1557)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassMaterialInterfaceSettings`](ue_ue.LightmassMaterialInterfaceSettings.md)

#### Defined in

[ue/ue.d.ts:1546](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1546)

___

### ParameterOverviewExpansion

• **ParameterOverviewExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

#### Defined in

[ue/ue.d.ts:1555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1555)

___

### PreviewMesh

• **PreviewMesh**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:1552](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1552)

___

### SubsurfaceProfile

• **SubsurfaceProfile**: [`SubsurfaceProfile`](ue_ue.SubsurfaceProfile.md)

#### Defined in

[ue/ue.d.ts:1545](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1545)

___

### TextureStreamingData

• **TextureStreamingData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

#### Defined in

[ue/ue.d.ts:1549](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1549)

___

### TextureStreamingDataMissingEntries

• **TextureStreamingDataMissingEntries**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

#### Defined in

[ue/ue.d.ts:1551](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1551)

___

### TextureStreamingDataVersion

• **TextureStreamingDataVersion**: `number`

#### Defined in

[ue/ue.d.ts:1548](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1548)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Defined in

[ue/ue.d.ts:1553](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1553)

___

### \_\_tid\_MaterialInterface\_\_

• **\_\_tid\_MaterialInterface\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:1565](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1565)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bTextureStreamingDataSorted

• **bTextureStreamingDataSorted**: `boolean`

#### Defined in

[ue/ue.d.ts:1547](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1547)

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

### GetBaseMaterial

▸ **GetBaseMaterial**(): [`Material`](ue_ue.Material.md)

#### Returns

[`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:1558](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1558)

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

### GetPhysicalMaterial

▸ **GetPhysicalMaterial**(): [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Returns

[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Defined in

[ue/ue.d.ts:1559](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1559)

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

### SetForceMipLevelsToBeResident

▸ **SetForceMipLevelsToBeResident**(`OverrideForceMiplevelsToBeResident`, `bForceMiplevelsToBeResidentValue`, `ForceDuration`, `CinematicTextureGroups?`, `bFastResponse?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OverrideForceMiplevelsToBeResident` | `boolean` |
| `bForceMiplevelsToBeResidentValue` | `boolean` |
| `ForceDuration` | `number` |
| `CinematicTextureGroups?` | `number` |
| `bFastResponse?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:1560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1560)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:1562](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1562)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:1563](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1563)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:1561](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1561)
