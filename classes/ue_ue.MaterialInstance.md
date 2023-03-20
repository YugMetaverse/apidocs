[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialInstance

# Class: MaterialInstance

[ue/ue](../modules/ue_ue.md).MaterialInstance

## Hierarchy

- [`MaterialInterface`](ue_ue.MaterialInterface.md)

  ↳ **`MaterialInstance`**

  ↳↳ [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

  ↳↳ [`MaterialInstanceConstant`](ue_ue.MaterialInstanceConstant.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialInstance.md#constructor)

### Properties

- [AssetImportData](ue_ue.MaterialInstance.md#assetimportdata)
- [AssetUserData](ue_ue.MaterialInstance.md#assetuserdata)
- [BasePropertyOverrides](ue_ue.MaterialInstance.md#basepropertyoverrides)
- [FontParameterValues](ue_ue.MaterialInstance.md#fontparametervalues)
- [LayerParameterExpansion](ue_ue.MaterialInstance.md#layerparameterexpansion)
- [LightingGuid](ue_ue.MaterialInstance.md#lightingguid)
- [LightmassSettings](ue_ue.MaterialInstance.md#lightmasssettings)
- [ParameterOverviewExpansion](ue_ue.MaterialInstance.md#parameteroverviewexpansion)
- [Parent](ue_ue.MaterialInstance.md#parent)
- [PermutationTextureReferences](ue_ue.MaterialInstance.md#permutationtexturereferences)
- [PhysMaterial](ue_ue.MaterialInstance.md#physmaterial)
- [PreviewMesh](ue_ue.MaterialInstance.md#previewmesh)
- [ReferencedTextureGuids](ue_ue.MaterialInstance.md#referencedtextureguids)
- [RuntimeVirtualTextureParameterValues](ue_ue.MaterialInstance.md#runtimevirtualtextureparametervalues)
- [ScalarParameterValues](ue_ue.MaterialInstance.md#scalarparametervalues)
- [StaticParameters](ue_ue.MaterialInstance.md#staticparameters)
- [SubsurfaceProfile](ue_ue.MaterialInstance.md#subsurfaceprofile)
- [TextureParameterValues](ue_ue.MaterialInstance.md#textureparametervalues)
- [TextureStreamingData](ue_ue.MaterialInstance.md#texturestreamingdata)
- [TextureStreamingDataMissingEntries](ue_ue.MaterialInstance.md#texturestreamingdatamissingentries)
- [TextureStreamingDataVersion](ue_ue.MaterialInstance.md#texturestreamingdataversion)
- [ThumbnailInfo](ue_ue.MaterialInstance.md#thumbnailinfo)
- [VectorParameterValues](ue_ue.MaterialInstance.md#vectorparametervalues)
- [\_\_tid\_MaterialInstance\_\_](ue_ue.MaterialInstance.md#__tid_materialinstance__)
- [\_\_tid\_MaterialInterface\_\_](ue_ue.MaterialInstance.md#__tid_materialinterface__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialInstance.md#__tid_object__)
- [bHasStaticPermutationResource](ue_ue.MaterialInstance.md#bhasstaticpermutationresource)
- [bOverrideBaseProperties](ue_ue.MaterialInstance.md#boverridebaseproperties)
- [bOverrideSubsurfaceProfile](ue_ue.MaterialInstance.md#boverridesubsurfaceprofile)
- [bTextureStreamingDataSorted](ue_ue.MaterialInstance.md#btexturestreamingdatasorted)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialInstance.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialInstance.md#executeubergraph)
- [GetBaseMaterial](ue_ue.MaterialInstance.md#getbasematerial)
- [GetClass](ue_ue.MaterialInstance.md#getclass)
- [GetName](ue_ue.MaterialInstance.md#getname)
- [GetOuter](ue_ue.MaterialInstance.md#getouter)
- [GetPhysicalMaterial](ue_ue.MaterialInstance.md#getphysicalmaterial)
- [GetWorld](ue_ue.MaterialInstance.md#getworld)
- [SetForceMipLevelsToBeResident](ue_ue.MaterialInstance.md#setforcemiplevelstoberesident)
- [Find](ue_ue.MaterialInstance.md#find)
- [Load](ue_ue.MaterialInstance.md#load)
- [StaticClass](ue_ue.MaterialInstance.md#staticclass)

## Constructors

### constructor

• **new MaterialInstance**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MaterialInterface](ue_ue.MaterialInterface.md).[constructor](ue_ue.MaterialInterface.md#constructor)

#### Defined in

[ue/ue.d.ts:2134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2134)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[AssetImportData](ue_ue.MaterialInterface.md#assetimportdata)

#### Defined in

[ue/ue.d.ts:1556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1556)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[AssetUserData](ue_ue.MaterialInterface.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:1550](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1550)

___

### BasePropertyOverrides

• **BasePropertyOverrides**: [`MaterialInstanceBasePropertyOverrides`](ue_ue.MaterialInstanceBasePropertyOverrides.md)

#### Defined in

[ue/ue.d.ts:2145](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2145)

___

### FontParameterValues

• **FontParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FontParameterValue`](ue_ue.FontParameterValue.md)\>

#### Defined in

[ue/ue.d.ts:2143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2143)

___

### LayerParameterExpansion

• **LayerParameterExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[LayerParameterExpansion](ue_ue.MaterialInterface.md#layerparameterexpansion)

#### Defined in

[ue/ue.d.ts:1554](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1554)

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[LightingGuid](ue_ue.MaterialInterface.md#lightingguid)

#### Defined in

[ue/ue.d.ts:1557](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1557)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassMaterialInterfaceSettings`](ue_ue.LightmassMaterialInterfaceSettings.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[LightmassSettings](ue_ue.MaterialInterface.md#lightmasssettings)

#### Defined in

[ue/ue.d.ts:1546](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1546)

___

### ParameterOverviewExpansion

• **ParameterOverviewExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[ParameterOverviewExpansion](ue_ue.MaterialInterface.md#parameteroverviewexpansion)

#### Defined in

[ue/ue.d.ts:1555](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1555)

___

### Parent

• **Parent**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:2136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2136)

___

### PermutationTextureReferences

• **PermutationTextureReferences**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:2146](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2146)

___

### PhysMaterial

• **PhysMaterial**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Defined in

[ue/ue.d.ts:2135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2135)

___

### PreviewMesh

• **PreviewMesh**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[PreviewMesh](ue_ue.MaterialInterface.md#previewmesh)

#### Defined in

[ue/ue.d.ts:1552](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1552)

___

### ReferencedTextureGuids

• **ReferencedTextureGuids**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

#### Defined in

[ue/ue.d.ts:2147](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2147)

___

### RuntimeVirtualTextureParameterValues

• **RuntimeVirtualTextureParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTextureParameterValue`](ue_ue.RuntimeVirtualTextureParameterValue.md)\>

#### Defined in

[ue/ue.d.ts:2142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2142)

___

### ScalarParameterValues

• **ScalarParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ScalarParameterValue`](ue_ue.ScalarParameterValue.md)\>

#### Defined in

[ue/ue.d.ts:2139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2139)

___

### StaticParameters

• **StaticParameters**: [`StaticParameterSet`](ue_ue.StaticParameterSet.md)

#### Defined in

[ue/ue.d.ts:2148](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2148)

___

### SubsurfaceProfile

• **SubsurfaceProfile**: [`SubsurfaceProfile`](ue_ue.SubsurfaceProfile.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[SubsurfaceProfile](ue_ue.MaterialInterface.md#subsurfaceprofile)

#### Defined in

[ue/ue.d.ts:1545](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1545)

___

### TextureParameterValues

• **TextureParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureParameterValue`](ue_ue.TextureParameterValue.md)\>

#### Defined in

[ue/ue.d.ts:2141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2141)

___

### TextureStreamingData

• **TextureStreamingData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[TextureStreamingData](ue_ue.MaterialInterface.md#texturestreamingdata)

#### Defined in

[ue/ue.d.ts:1549](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1549)

___

### TextureStreamingDataMissingEntries

• **TextureStreamingDataMissingEntries**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[TextureStreamingDataMissingEntries](ue_ue.MaterialInterface.md#texturestreamingdatamissingentries)

#### Defined in

[ue/ue.d.ts:1551](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1551)

___

### TextureStreamingDataVersion

• **TextureStreamingDataVersion**: `number`

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[TextureStreamingDataVersion](ue_ue.MaterialInterface.md#texturestreamingdataversion)

#### Defined in

[ue/ue.d.ts:1548](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1548)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[ThumbnailInfo](ue_ue.MaterialInterface.md#thumbnailinfo)

#### Defined in

[ue/ue.d.ts:1553](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1553)

___

### VectorParameterValues

• **VectorParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VectorParameterValue`](ue_ue.VectorParameterValue.md)\>

#### Defined in

[ue/ue.d.ts:2140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2140)

___

### \_\_tid\_MaterialInstance\_\_

• **\_\_tid\_MaterialInstance\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:2153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2153)

___

### \_\_tid\_MaterialInterface\_\_

• **\_\_tid\_MaterialInterface\_\_**: `boolean`

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[__tid_MaterialInterface__](ue_ue.MaterialInterface.md#__tid_materialinterface__)

#### Defined in

[ue/ue.d.ts:1565](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1565)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[__tid_Object__](ue_ue.MaterialInterface.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bHasStaticPermutationResource

• **bHasStaticPermutationResource**: `boolean`

#### Defined in

[ue/ue.d.ts:2137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2137)

___

### bOverrideBaseProperties

• **bOverrideBaseProperties**: `boolean`

#### Defined in

[ue/ue.d.ts:2144](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2144)

___

### bOverrideSubsurfaceProfile

• **bOverrideSubsurfaceProfile**: `boolean`

#### Defined in

[ue/ue.d.ts:2138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2138)

___

### bTextureStreamingDataSorted

• **bTextureStreamingDataSorted**: `boolean`

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[bTextureStreamingDataSorted](ue_ue.MaterialInterface.md#btexturestreamingdatasorted)

#### Defined in

[ue/ue.d.ts:1547](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1547)

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

[MaterialInterface](ue_ue.MaterialInterface.md).[CreateDefaultSubobject](ue_ue.MaterialInterface.md#createdefaultsubobject)

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

[MaterialInterface](ue_ue.MaterialInterface.md).[ExecuteUbergraph](ue_ue.MaterialInterface.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetBaseMaterial

▸ **GetBaseMaterial**(): [`Material`](ue_ue.Material.md)

#### Returns

[`Material`](ue_ue.Material.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetBaseMaterial](ue_ue.MaterialInterface.md#getbasematerial)

#### Defined in

[ue/ue.d.ts:1558](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1558)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetClass](ue_ue.MaterialInterface.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetName](ue_ue.MaterialInterface.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetOuter](ue_ue.MaterialInterface.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetPhysicalMaterial

▸ **GetPhysicalMaterial**(): [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Returns

[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetPhysicalMaterial](ue_ue.MaterialInterface.md#getphysicalmaterial)

#### Defined in

[ue/ue.d.ts:1559](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1559)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MaterialInterface](ue_ue.MaterialInterface.md).[GetWorld](ue_ue.MaterialInterface.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

[MaterialInterface](ue_ue.MaterialInterface.md).[SetForceMipLevelsToBeResident](ue_ue.MaterialInterface.md#setforcemiplevelstoberesident)

#### Defined in

[ue/ue.d.ts:1560](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1560)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialInstance`](ue_ue.MaterialInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialInstance`](ue_ue.MaterialInstance.md)

#### Overrides

[MaterialInterface](ue_ue.MaterialInterface.md).[Find](ue_ue.MaterialInterface.md#find)

#### Defined in

[ue/ue.d.ts:2150](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2150)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialInstance`](ue_ue.MaterialInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialInstance`](ue_ue.MaterialInstance.md)

#### Overrides

[MaterialInterface](ue_ue.MaterialInterface.md).[Load](ue_ue.MaterialInterface.md#load)

#### Defined in

[ue/ue.d.ts:2151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2151)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialInterface](ue_ue.MaterialInterface.md).[StaticClass](ue_ue.MaterialInterface.md#staticclass)

#### Defined in

[ue/ue.d.ts:2149](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2149)
