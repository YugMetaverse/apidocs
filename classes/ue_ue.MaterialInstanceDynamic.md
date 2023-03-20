[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialInstanceDynamic

# Class: MaterialInstanceDynamic

[ue/ue](../modules/ue_ue.md).MaterialInstanceDynamic

## Hierarchy

- [`MaterialInstance`](ue_ue.MaterialInstance.md)

  ↳ **`MaterialInstanceDynamic`**

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialInstanceDynamic.md#constructor)

### Properties

- [AssetImportData](ue_ue.MaterialInstanceDynamic.md#assetimportdata)
- [AssetUserData](ue_ue.MaterialInstanceDynamic.md#assetuserdata)
- [BasePropertyOverrides](ue_ue.MaterialInstanceDynamic.md#basepropertyoverrides)
- [FontParameterValues](ue_ue.MaterialInstanceDynamic.md#fontparametervalues)
- [LayerParameterExpansion](ue_ue.MaterialInstanceDynamic.md#layerparameterexpansion)
- [LightingGuid](ue_ue.MaterialInstanceDynamic.md#lightingguid)
- [LightmassSettings](ue_ue.MaterialInstanceDynamic.md#lightmasssettings)
- [ParameterOverviewExpansion](ue_ue.MaterialInstanceDynamic.md#parameteroverviewexpansion)
- [Parent](ue_ue.MaterialInstanceDynamic.md#parent)
- [PermutationTextureReferences](ue_ue.MaterialInstanceDynamic.md#permutationtexturereferences)
- [PhysMaterial](ue_ue.MaterialInstanceDynamic.md#physmaterial)
- [PreviewMesh](ue_ue.MaterialInstanceDynamic.md#previewmesh)
- [ReferencedTextureGuids](ue_ue.MaterialInstanceDynamic.md#referencedtextureguids)
- [RuntimeVirtualTextureParameterValues](ue_ue.MaterialInstanceDynamic.md#runtimevirtualtextureparametervalues)
- [ScalarParameterValues](ue_ue.MaterialInstanceDynamic.md#scalarparametervalues)
- [StaticParameters](ue_ue.MaterialInstanceDynamic.md#staticparameters)
- [SubsurfaceProfile](ue_ue.MaterialInstanceDynamic.md#subsurfaceprofile)
- [TextureParameterValues](ue_ue.MaterialInstanceDynamic.md#textureparametervalues)
- [TextureStreamingData](ue_ue.MaterialInstanceDynamic.md#texturestreamingdata)
- [TextureStreamingDataMissingEntries](ue_ue.MaterialInstanceDynamic.md#texturestreamingdatamissingentries)
- [TextureStreamingDataVersion](ue_ue.MaterialInstanceDynamic.md#texturestreamingdataversion)
- [ThumbnailInfo](ue_ue.MaterialInstanceDynamic.md#thumbnailinfo)
- [VectorParameterValues](ue_ue.MaterialInstanceDynamic.md#vectorparametervalues)
- [\_\_tid\_MaterialInstanceDynamic\_\_](ue_ue.MaterialInstanceDynamic.md#__tid_materialinstancedynamic__)
- [\_\_tid\_MaterialInstance\_\_](ue_ue.MaterialInstanceDynamic.md#__tid_materialinstance__)
- [\_\_tid\_MaterialInterface\_\_](ue_ue.MaterialInstanceDynamic.md#__tid_materialinterface__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialInstanceDynamic.md#__tid_object__)
- [bHasStaticPermutationResource](ue_ue.MaterialInstanceDynamic.md#bhasstaticpermutationresource)
- [bOverrideBaseProperties](ue_ue.MaterialInstanceDynamic.md#boverridebaseproperties)
- [bOverrideSubsurfaceProfile](ue_ue.MaterialInstanceDynamic.md#boverridesubsurfaceprofile)
- [bTextureStreamingDataSorted](ue_ue.MaterialInstanceDynamic.md#btexturestreamingdatasorted)

### Methods

- [CopyInterpParameters](ue_ue.MaterialInstanceDynamic.md#copyinterpparameters)
- [CopyParameterOverrides](ue_ue.MaterialInstanceDynamic.md#copyparameteroverrides)
- [CreateDefaultSubobject](ue_ue.MaterialInstanceDynamic.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialInstanceDynamic.md#executeubergraph)
- [GetBaseMaterial](ue_ue.MaterialInstanceDynamic.md#getbasematerial)
- [GetClass](ue_ue.MaterialInstanceDynamic.md#getclass)
- [GetName](ue_ue.MaterialInstanceDynamic.md#getname)
- [GetOuter](ue_ue.MaterialInstanceDynamic.md#getouter)
- [GetPhysicalMaterial](ue_ue.MaterialInstanceDynamic.md#getphysicalmaterial)
- [GetWorld](ue_ue.MaterialInstanceDynamic.md#getworld)
- [K2\_CopyMaterialInstanceParameters](ue_ue.MaterialInstanceDynamic.md#k2_copymaterialinstanceparameters)
- [K2\_GetScalarParameterValue](ue_ue.MaterialInstanceDynamic.md#k2_getscalarparametervalue)
- [K2\_GetTextureParameterValue](ue_ue.MaterialInstanceDynamic.md#k2_gettextureparametervalue)
- [K2\_GetVectorParameterValue](ue_ue.MaterialInstanceDynamic.md#k2_getvectorparametervalue)
- [K2\_InterpolateMaterialInstanceParams](ue_ue.MaterialInstanceDynamic.md#k2_interpolatematerialinstanceparams)
- [SetForceMipLevelsToBeResident](ue_ue.MaterialInstanceDynamic.md#setforcemiplevelstoberesident)
- [SetScalarParameterValue](ue_ue.MaterialInstanceDynamic.md#setscalarparametervalue)
- [SetTextureParameterValue](ue_ue.MaterialInstanceDynamic.md#settextureparametervalue)
- [SetVectorParameterValue](ue_ue.MaterialInstanceDynamic.md#setvectorparametervalue)
- [Find](ue_ue.MaterialInstanceDynamic.md#find)
- [Load](ue_ue.MaterialInstanceDynamic.md#load)
- [StaticClass](ue_ue.MaterialInstanceDynamic.md#staticclass)

## Constructors

### constructor

• **new MaterialInstanceDynamic**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MaterialInstance](ue_ue.MaterialInstance.md).[constructor](ue_ue.MaterialInstance.md#constructor)

#### Defined in

[ue/ue.d.ts:2157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2157)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[AssetImportData](ue_ue.MaterialInstance.md#assetimportdata)

#### Defined in

[ue/ue.d.ts:1556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1556)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[AssetUserData](ue_ue.MaterialInstance.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:1550](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1550)

___

### BasePropertyOverrides

• **BasePropertyOverrides**: [`MaterialInstanceBasePropertyOverrides`](ue_ue.MaterialInstanceBasePropertyOverrides.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[BasePropertyOverrides](ue_ue.MaterialInstance.md#basepropertyoverrides)

#### Defined in

[ue/ue.d.ts:2145](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2145)

___

### FontParameterValues

• **FontParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FontParameterValue`](ue_ue.FontParameterValue.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[FontParameterValues](ue_ue.MaterialInstance.md#fontparametervalues)

#### Defined in

[ue/ue.d.ts:2143](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2143)

___

### LayerParameterExpansion

• **LayerParameterExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[LayerParameterExpansion](ue_ue.MaterialInstance.md#layerparameterexpansion)

#### Defined in

[ue/ue.d.ts:1554](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1554)

___

### LightingGuid

• **LightingGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[LightingGuid](ue_ue.MaterialInstance.md#lightingguid)

#### Defined in

[ue/ue.d.ts:1557](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1557)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassMaterialInterfaceSettings`](ue_ue.LightmassMaterialInterfaceSettings.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[LightmassSettings](ue_ue.MaterialInstance.md#lightmasssettings)

#### Defined in

[ue/ue.d.ts:1546](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1546)

___

### ParameterOverviewExpansion

• **ParameterOverviewExpansion**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `boolean`\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[ParameterOverviewExpansion](ue_ue.MaterialInstance.md#parameteroverviewexpansion)

#### Defined in

[ue/ue.d.ts:1555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1555)

___

### Parent

• **Parent**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[Parent](ue_ue.MaterialInstance.md#parent)

#### Defined in

[ue/ue.d.ts:2136](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2136)

___

### PermutationTextureReferences

• **PermutationTextureReferences**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[PermutationTextureReferences](ue_ue.MaterialInstance.md#permutationtexturereferences)

#### Defined in

[ue/ue.d.ts:2146](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2146)

___

### PhysMaterial

• **PhysMaterial**: [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[PhysMaterial](ue_ue.MaterialInstance.md#physmaterial)

#### Defined in

[ue/ue.d.ts:2135](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2135)

___

### PreviewMesh

• **PreviewMesh**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[PreviewMesh](ue_ue.MaterialInstance.md#previewmesh)

#### Defined in

[ue/ue.d.ts:1552](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1552)

___

### ReferencedTextureGuids

• **ReferencedTextureGuids**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[ReferencedTextureGuids](ue_ue.MaterialInstance.md#referencedtextureguids)

#### Defined in

[ue/ue.d.ts:2147](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2147)

___

### RuntimeVirtualTextureParameterValues

• **RuntimeVirtualTextureParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTextureParameterValue`](ue_ue.RuntimeVirtualTextureParameterValue.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[RuntimeVirtualTextureParameterValues](ue_ue.MaterialInstance.md#runtimevirtualtextureparametervalues)

#### Defined in

[ue/ue.d.ts:2142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2142)

___

### ScalarParameterValues

• **ScalarParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ScalarParameterValue`](ue_ue.ScalarParameterValue.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[ScalarParameterValues](ue_ue.MaterialInstance.md#scalarparametervalues)

#### Defined in

[ue/ue.d.ts:2139](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2139)

___

### StaticParameters

• **StaticParameters**: [`StaticParameterSet`](ue_ue.StaticParameterSet.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[StaticParameters](ue_ue.MaterialInstance.md#staticparameters)

#### Defined in

[ue/ue.d.ts:2148](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2148)

___

### SubsurfaceProfile

• **SubsurfaceProfile**: [`SubsurfaceProfile`](ue_ue.SubsurfaceProfile.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[SubsurfaceProfile](ue_ue.MaterialInstance.md#subsurfaceprofile)

#### Defined in

[ue/ue.d.ts:1545](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1545)

___

### TextureParameterValues

• **TextureParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureParameterValue`](ue_ue.TextureParameterValue.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[TextureParameterValues](ue_ue.MaterialInstance.md#textureparametervalues)

#### Defined in

[ue/ue.d.ts:2141](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2141)

___

### TextureStreamingData

• **TextureStreamingData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[TextureStreamingData](ue_ue.MaterialInstance.md#texturestreamingdata)

#### Defined in

[ue/ue.d.ts:1549](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1549)

___

### TextureStreamingDataMissingEntries

• **TextureStreamingDataMissingEntries**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialTextureInfo`](ue_ue.MaterialTextureInfo.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[TextureStreamingDataMissingEntries](ue_ue.MaterialInstance.md#texturestreamingdatamissingentries)

#### Defined in

[ue/ue.d.ts:1551](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1551)

___

### TextureStreamingDataVersion

• **TextureStreamingDataVersion**: `number`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[TextureStreamingDataVersion](ue_ue.MaterialInstance.md#texturestreamingdataversion)

#### Defined in

[ue/ue.d.ts:1548](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1548)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[ThumbnailInfo](ue_ue.MaterialInstance.md#thumbnailinfo)

#### Defined in

[ue/ue.d.ts:1553](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1553)

___

### VectorParameterValues

• **VectorParameterValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VectorParameterValue`](ue_ue.VectorParameterValue.md)\>

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[VectorParameterValues](ue_ue.MaterialInstance.md#vectorparametervalues)

#### Defined in

[ue/ue.d.ts:2140](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2140)

___

### \_\_tid\_MaterialInstanceDynamic\_\_

• **\_\_tid\_MaterialInstanceDynamic\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:2172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2172)

___

### \_\_tid\_MaterialInstance\_\_

• **\_\_tid\_MaterialInstance\_\_**: `boolean`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[__tid_MaterialInstance__](ue_ue.MaterialInstance.md#__tid_materialinstance__)

#### Defined in

[ue/ue.d.ts:2153](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2153)

___

### \_\_tid\_MaterialInterface\_\_

• **\_\_tid\_MaterialInterface\_\_**: `boolean`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[__tid_MaterialInterface__](ue_ue.MaterialInstance.md#__tid_materialinterface__)

#### Defined in

[ue/ue.d.ts:1565](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1565)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[__tid_Object__](ue_ue.MaterialInstance.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bHasStaticPermutationResource

• **bHasStaticPermutationResource**: `boolean`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[bHasStaticPermutationResource](ue_ue.MaterialInstance.md#bhasstaticpermutationresource)

#### Defined in

[ue/ue.d.ts:2137](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2137)

___

### bOverrideBaseProperties

• **bOverrideBaseProperties**: `boolean`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[bOverrideBaseProperties](ue_ue.MaterialInstance.md#boverridebaseproperties)

#### Defined in

[ue/ue.d.ts:2144](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2144)

___

### bOverrideSubsurfaceProfile

• **bOverrideSubsurfaceProfile**: `boolean`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[bOverrideSubsurfaceProfile](ue_ue.MaterialInstance.md#boverridesubsurfaceprofile)

#### Defined in

[ue/ue.d.ts:2138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2138)

___

### bTextureStreamingDataSorted

• **bTextureStreamingDataSorted**: `boolean`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[bTextureStreamingDataSorted](ue_ue.MaterialInstance.md#btexturestreamingdatasorted)

#### Defined in

[ue/ue.d.ts:1547](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1547)

## Methods

### CopyInterpParameters

▸ **CopyInterpParameters**(`Source`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Source` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInstance`](ue_ue.MaterialInstance.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:2158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2158)

___

### CopyParameterOverrides

▸ **CopyParameterOverrides**(`MaterialInstance`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialInstance` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInstance`](ue_ue.MaterialInstance.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:2159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2159)

___

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

[MaterialInstance](ue_ue.MaterialInstance.md).[ExecuteUbergraph](ue_ue.MaterialInstance.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetBaseMaterial

▸ **GetBaseMaterial**(): [`Material`](ue_ue.Material.md)

#### Returns

[`Material`](ue_ue.Material.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[GetBaseMaterial](ue_ue.MaterialInstance.md#getbasematerial)

#### Defined in

[ue/ue.d.ts:1558](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1558)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[GetClass](ue_ue.MaterialInstance.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[GetName](ue_ue.MaterialInstance.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[GetOuter](ue_ue.MaterialInstance.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetPhysicalMaterial

▸ **GetPhysicalMaterial**(): [`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Returns

[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[GetPhysicalMaterial](ue_ue.MaterialInstance.md#getphysicalmaterial)

#### Defined in

[ue/ue.d.ts:1559](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1559)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MaterialInstance](ue_ue.MaterialInstance.md).[GetWorld](ue_ue.MaterialInstance.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### K2\_CopyMaterialInstanceParameters

▸ **K2_CopyMaterialInstanceParameters**(`Source`, `bQuickParametersOnly?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Source` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `bQuickParametersOnly?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:2160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2160)

___

### K2\_GetScalarParameterValue

▸ **K2_GetScalarParameterValue**(`ParameterName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:2161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2161)

___

### K2\_GetTextureParameterValue

▸ **K2_GetTextureParameterValue**(`ParameterName`): [`Texture`](ue_ue.Texture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |

#### Returns

[`Texture`](ue_ue.Texture.md)

#### Defined in

[ue/ue.d.ts:2162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2162)

___

### K2\_GetVectorParameterValue

▸ **K2_GetVectorParameterValue**(`ParameterName`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:2163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2163)

___

### K2\_InterpolateMaterialInstanceParams

▸ **K2_InterpolateMaterialInstanceParams**(`SourceA`, `SourceB`, `Alpha`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceA` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInstance`](ue_ue.MaterialInstance.md)\> |
| `SourceB` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInstance`](ue_ue.MaterialInstance.md)\> |
| `Alpha` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:2164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2164)

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

#### Defined in

[ue/ue.d.ts:1560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1560)

___

### SetScalarParameterValue

▸ **SetScalarParameterValue**(`ParameterName`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `Value` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:2165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2165)

___

### SetTextureParameterValue

▸ **SetTextureParameterValue**(`ParameterName`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `Value` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Texture`](ue_ue.Texture.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:2166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2166)

___

### SetVectorParameterValue

▸ **SetVectorParameterValue**(`ParameterName`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParameterName` | `string` |
| `Value` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:2167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2167)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Overrides

[MaterialInstance](ue_ue.MaterialInstance.md).[Find](ue_ue.MaterialInstance.md#find)

#### Defined in

[ue/ue.d.ts:2169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2169)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Overrides

[MaterialInstance](ue_ue.MaterialInstance.md).[Load](ue_ue.MaterialInstance.md#load)

#### Defined in

[ue/ue.d.ts:2170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2170)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialInstance](ue_ue.MaterialInstance.md).[StaticClass](ue_ue.MaterialInstance.md#staticclass)

#### Defined in

[ue/ue.d.ts:2168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L2168)