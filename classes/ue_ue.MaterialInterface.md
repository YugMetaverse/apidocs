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

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

___

### LayerParameterExpansion

• **LayerParameterExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassMaterialInterfaceSettings`](ue_ue.LightmassMaterialInterfaceSettings.md)

___

### ParameterOverviewExpansion

• **ParameterOverviewExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

___

### PreviewMesh

• **PreviewMesh**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### SubsurfaceProfile

• **SubsurfaceProfile**: [`SubsurfaceProfile`](ue_ue.SubsurfaceProfile.md)

___

### TextureStreamingData

• **TextureStreamingData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

___

### TextureStreamingDataMissingEntries

• **TextureStreamingDataMissingEntries**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

___

### TextureStreamingDataVersion

• **TextureStreamingDataVersion**: `number`

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

___

### \_\_tid\_MaterialInterface\_\_

• **\_\_tid\_MaterialInterface\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bTextureStreamingDataSorted

• **bTextureStreamingDataSorted**: `boolean`

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

### GetBaseMaterial

▸ **GetBaseMaterial**(): [`Material`](ue_ue.Material.md)

#### Returns

[`Material`](ue_ue.Material.md)

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

### GetPhysicalMaterial

▸ **GetPhysicalMaterial**(): [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Returns

[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
