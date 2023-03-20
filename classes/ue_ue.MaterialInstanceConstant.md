[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialInstanceConstant

# Class: MaterialInstanceConstant

[ue/ue](../modules/ue_ue.md).MaterialInstanceConstant

## Hierarchy

- [`MaterialInstance`](ue_ue.MaterialInstance.md)

  ↳ **`MaterialInstanceConstant`**

  ↳↳ [`LandscapeMaterialInstanceConstant`](ue_ue.LandscapeMaterialInstanceConstant.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialInstanceConstant.md#constructor)

### Properties

- [AssetImportData](ue_ue.MaterialInstanceConstant.md#assetimportdata)
- [AssetUserData](ue_ue.MaterialInstanceConstant.md#assetuserdata)
- [BasePropertyOverrides](ue_ue.MaterialInstanceConstant.md#basepropertyoverrides)
- [FontParameterValues](ue_ue.MaterialInstanceConstant.md#fontparametervalues)
- [LayerParameterExpansion](ue_ue.MaterialInstanceConstant.md#layerparameterexpansion)
- [LightingGuid](ue_ue.MaterialInstanceConstant.md#lightingguid)
- [LightmassSettings](ue_ue.MaterialInstanceConstant.md#lightmasssettings)
- [ParameterOverviewExpansion](ue_ue.MaterialInstanceConstant.md#parameteroverviewexpansion)
- [ParameterStateId](ue_ue.MaterialInstanceConstant.md#parameterstateid)
- [Parent](ue_ue.MaterialInstanceConstant.md#parent)
- [PermutationTextureReferences](ue_ue.MaterialInstanceConstant.md#permutationtexturereferences)
- [PhysMaterial](ue_ue.MaterialInstanceConstant.md#physmaterial)
- [PreviewMesh](ue_ue.MaterialInstanceConstant.md#previewmesh)
- [ReferencedTextureGuids](ue_ue.MaterialInstanceConstant.md#referencedtextureguids)
- [RuntimeVirtualTextureParameterValues](ue_ue.MaterialInstanceConstant.md#runtimevirtualtextureparametervalues)
- [ScalarParameterValues](ue_ue.MaterialInstanceConstant.md#scalarparametervalues)
- [StaticParameters](ue_ue.MaterialInstanceConstant.md#staticparameters)
- [SubsurfaceProfile](ue_ue.MaterialInstanceConstant.md#subsurfaceprofile)
- [TextureParameterValues](ue_ue.MaterialInstanceConstant.md#textureparametervalues)
- [TextureStreamingData](ue_ue.MaterialInstanceConstant.md#texturestreamingdata)
- [TextureStreamingDataMissingEntries](ue_ue.MaterialInstanceConstant.md#texturestreamingdatamissingentries)
- [TextureStreamingDataVersion](ue_ue.MaterialInstanceConstant.md#texturestreamingdataversion)
- [ThumbnailInfo](ue_ue.MaterialInstanceConstant.md#thumbnailinfo)
- [VectorParameterValues](ue_ue.MaterialInstanceConstant.md#vectorparametervalues)
- [\_\_tid\_MaterialInstanceConstant\_\_](ue_ue.MaterialInstanceConstant.md#__tid_materialinstanceconstant__)
- [\_\_tid\_MaterialInstance\_\_](ue_ue.MaterialInstanceConstant.md#__tid_materialinstance__)
- [\_\_tid\_MaterialInterface\_\_](ue_ue.MaterialInstanceConstant.md#__tid_materialinterface__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialInstanceConstant.md#__tid_object__)
- [bHasStaticPermutationResource](ue_ue.MaterialInstanceConstant.md#bhasstaticpermutationresource)
- [bOverrideBaseProperties](ue_ue.MaterialInstanceConstant.md#boverridebaseproperties)
- [bOverrideSubsurfaceProfile](ue_ue.MaterialInstanceConstant.md#boverridesubsurfaceprofile)
- [bTextureStreamingDataSorted](ue_ue.MaterialInstanceConstant.md#btexturestreamingdatasorted)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialInstanceConstant.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialInstanceConstant.md#executeubergraph)
- [GetBaseMaterial](ue_ue.MaterialInstanceConstant.md#getbasematerial)
- [GetClass](ue_ue.MaterialInstanceConstant.md#getclass)
- [GetName](ue_ue.MaterialInstanceConstant.md#getname)
- [GetOuter](ue_ue.MaterialInstanceConstant.md#getouter)
- [GetPhysicalMaterial](ue_ue.MaterialInstanceConstant.md#getphysicalmaterial)
- [GetWorld](ue_ue.MaterialInstanceConstant.md#getworld)
- [K2\_GetScalarParameterValue](ue_ue.MaterialInstanceConstant.md#k2_getscalarparametervalue)
- [K2\_GetTextureParameterValue](ue_ue.MaterialInstanceConstant.md#k2_gettextureparametervalue)
- [K2\_GetVectorParameterValue](ue_ue.MaterialInstanceConstant.md#k2_getvectorparametervalue)
- [SetForceMipLevelsToBeResident](ue_ue.MaterialInstanceConstant.md#setforcemiplevelstoberesident)
- [Find](ue_ue.MaterialInstanceConstant.md#find)
- [Load](ue_ue.MaterialInstanceConstant.md#load)
- [StaticClass](ue_ue.MaterialInstanceConstant.md#staticclass)

## Constructors

### constructor

• **new MaterialInstanceConstant**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MaterialInstance](ue_ue.MaterialInstance.md).[constructor](ue_ue.MaterialInstance.md#constructor)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[AssetImportData](ue_ue.MaterialInstance.md#assetimportdata)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[AssetUserData](ue_ue.MaterialInstance.md#assetuserdata)

___

### BasePropertyOverrides

• **BasePropertyOverrides**: [`MaterialInstanceBasePropertyOverrides`](ue_ue.MaterialInstanceBasePropertyOverrides.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[BasePropertyOverrides](ue_ue.MaterialInstance.md#basepropertyoverrides)

___

### FontParameterValues

• **FontParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FontParameterValue`](ue_ue.FontParameterValue.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[FontParameterValues](ue_ue.MaterialInstance.md#fontparametervalues)

___

### LayerParameterExpansion

• **LayerParameterExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[LayerParameterExpansion](ue_ue.MaterialInstance.md#layerparameterexpansion)

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[LightingGuid](ue_ue.MaterialInstance.md#lightingguid)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassMaterialInterfaceSettings`](ue_ue.LightmassMaterialInterfaceSettings.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[LightmassSettings](ue_ue.MaterialInstance.md#lightmasssettings)

___

### ParameterOverviewExpansion

• **ParameterOverviewExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[ParameterOverviewExpansion](ue_ue.MaterialInstance.md#parameteroverviewexpansion)

___

### ParameterStateId

• **ParameterStateId**: [`Guid`](ue_ue_s.Guid.md)

___

### Parent

• **Parent**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[Parent](ue_ue.MaterialInstance.md#parent)

___

### PermutationTextureReferences

• **PermutationTextureReferences**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[PermutationTextureReferences](ue_ue.MaterialInstance.md#permutationtexturereferences)

___

### PhysMaterial

• **PhysMaterial**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[PhysMaterial](ue_ue.MaterialInstance.md#physmaterial)

___

### PreviewMesh

• **PreviewMesh**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[PreviewMesh](ue_ue.MaterialInstance.md#previewmesh)

___

### ReferencedTextureGuids

• **ReferencedTextureGuids**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[ReferencedTextureGuids](ue_ue.MaterialInstance.md#referencedtextureguids)

___

### RuntimeVirtualTextureParameterValues

• **RuntimeVirtualTextureParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTextureParameterValue`](ue_ue.RuntimeVirtualTextureParameterValue.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[RuntimeVirtualTextureParameterValues](ue_ue.MaterialInstance.md#runtimevirtualtextureparametervalues)

___

### ScalarParameterValues

• **ScalarParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ScalarParameterValue`](ue_ue.ScalarParameterValue.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[ScalarParameterValues](ue_ue.MaterialInstance.md#scalarparametervalues)

___

### StaticParameters

• **StaticParameters**: [`StaticParameterSet`](ue_ue.StaticParameterSet.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[StaticParameters](ue_ue.MaterialInstance.md#staticparameters)

___

### SubsurfaceProfile

• **SubsurfaceProfile**: [`SubsurfaceProfile`](ue_ue.SubsurfaceProfile.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[SubsurfaceProfile](ue_ue.MaterialInstance.md#subsurfaceprofile)

___

### TextureParameterValues

• **TextureParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureParameterValue`](ue_ue.TextureParameterValue.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[TextureParameterValues](ue_ue.MaterialInstance.md#textureparametervalues)

___

### TextureStreamingData

• **TextureStreamingData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[TextureStreamingData](ue_ue.MaterialInstance.md#texturestreamingdata)

___

### TextureStreamingDataMissingEntries

• **TextureStreamingDataMissingEntries**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[TextureStreamingDataMissingEntries](ue_ue.MaterialInstance.md#texturestreamingdatamissingentries)

___

### TextureStreamingDataVersion

• **TextureStreamingDataVersion**: `number`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[TextureStreamingDataVersion](ue_ue.MaterialInstance.md#texturestreamingdataversion)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[ThumbnailInfo](ue_ue.MaterialInstance.md#thumbnailinfo)

___

### VectorParameterValues

• **VectorParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VectorParameterValue`](ue_ue.VectorParameterValue.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[VectorParameterValues](ue_ue.MaterialInstance.md#vectorparametervalues)

___

### \_\_tid\_MaterialInstanceConstant\_\_

• **\_\_tid\_MaterialInstanceConstant\_\_**: `boolean`

___

### \_\_tid\_MaterialInstance\_\_

• **\_\_tid\_MaterialInstance\_\_**: `boolean`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[__tid_MaterialInstance__](ue_ue.MaterialInstance.md#__tid_materialinstance__)

___

### \_\_tid\_MaterialInterface\_\_

• **\_\_tid\_MaterialInterface\_\_**: `boolean`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[__tid_MaterialInterface__](ue_ue.MaterialInstance.md#__tid_materialinterface__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[__tid_Object__](ue_ue.MaterialInstance.md#__tid_object__)

___

### bHasStaticPermutationResource

• **bHasStaticPermutationResource**: `boolean`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[bHasStaticPermutationResource](ue_ue.MaterialInstance.md#bhasstaticpermutationresource)

___

### bOverrideBaseProperties

• **bOverrideBaseProperties**: `boolean`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[bOverrideBaseProperties](ue_ue.MaterialInstance.md#boverridebaseproperties)

___

### bOverrideSubsurfaceProfile

• **bOverrideSubsurfaceProfile**: `boolean`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[bOverrideSubsurfaceProfile](ue_ue.MaterialInstance.md#boverridesubsurfaceprofile)

___

### bTextureStreamingDataSorted

• **bTextureStreamingDataSorted**: `boolean`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[bTextureStreamingDataSorted](ue_ue.MaterialInstance.md#btexturestreamingdatasorted)

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

[MaterialInstance](ue_ue.MaterialInstance.md).[CreateDefaultSubobject](ue_ue.MaterialInstance.md#createdefaultsubobject)

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

[MaterialInstance](ue_ue.MaterialInstance.md).[ExecuteUbergraph](ue_ue.MaterialInstance.md#executeubergraph)

___

### GetBaseMaterial

▸ **GetBaseMaterial**(): [`Material`](ue_ue.Material.md)

#### Returns

[`Material`](ue_ue.Material.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[GetBaseMaterial](ue_ue.MaterialInstance.md#getbasematerial)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[GetClass](ue_ue.MaterialInstance.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[GetName](ue_ue.MaterialInstance.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[GetOuter](ue_ue.MaterialInstance.md#getouter)

___

### GetPhysicalMaterial

▸ **GetPhysicalMaterial**(): [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Returns

[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[GetPhysicalMaterial](ue_ue.MaterialInstance.md#getphysicalmaterial)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[GetWorld](ue_ue.MaterialInstance.md#getworld)

___

### K2\_GetScalarParameterValue

▸ **K2_GetScalarParameterValue**(`ParameterName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |

#### Returns

`number`

___

### K2\_GetTextureParameterValue

▸ **K2_GetTextureParameterValue**(`ParameterName`): [`Texture`](ue_ue.Texture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |

#### Returns

[`Texture`](ue_ue.Texture.md)

___

### K2\_GetVectorParameterValue

▸ **K2_GetVectorParameterValue**(`ParameterName`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

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

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[SetForceMipLevelsToBeResident](ue_ue.MaterialInstance.md#setforcemiplevelstoberesident)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)

#### Overrides

[MaterialInstance](ue_ue.MaterialInstance.md).[Find](ue_ue.MaterialInstance.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)

#### Overrides

[MaterialInstance](ue_ue.MaterialInstance.md).[Load](ue_ue.MaterialInstance.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialInstance](ue_ue.MaterialInstance.md).[StaticClass](ue_ue.MaterialInstance.md#staticclass)
