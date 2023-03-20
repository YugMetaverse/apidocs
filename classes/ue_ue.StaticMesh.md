[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / StaticMesh

# Class: StaticMesh

[ue/ue](../modules/ue_ue.md).StaticMesh

## Hierarchy

- [`StreamableRenderAsset`](ue_ue.StreamableRenderAsset.md)

  ↳ **`StaticMesh`**

## Table of contents

### Constructors

- [constructor](ue_ue.StaticMesh.md#constructor)

### Properties

- [AssetImportData](ue_ue.StaticMesh.md#assetimportdata)
- [AssetUserData](ue_ue.StaticMesh.md#assetuserdata)
- [BodySetup](ue_ue.StaticMesh.md#bodysetup)
- [CachedCombinedLODBias](ue_ue.StaticMesh.md#cachedcombinedlodbias)
- [CachedNumResidentLODs](ue_ue.StaticMesh.md#cachednumresidentlods)
- [ComplexCollisionMesh](ue_ue.StaticMesh.md#complexcollisionmesh)
- [DistanceFieldSelfShadowBias](ue_ue.StaticMesh.md#distancefieldselfshadowbias)
- [EditableMesh](ue_ue.StaticMesh.md#editablemesh)
- [EditorCameraPosition](ue_ue.StaticMesh.md#editorcameraposition)
- [ElementToIgnoreForTexFactor](ue_ue.StaticMesh.md#elementtoignorefortexfactor)
- [ExtendedBounds](ue_ue.StaticMesh.md#extendedbounds)
- [ForceMipLevelsToBeResidentTimestamp](ue_ue.StaticMesh.md#forcemiplevelstoberesidenttimestamp)
- [ImportVersion](ue_ue.StaticMesh.md#importversion)
- [LODForCollision](ue_ue.StaticMesh.md#lodforcollision)
- [LODForOccluderMesh](ue_ue.StaticMesh.md#lodforoccludermesh)
- [LODGroup](ue_ue.StaticMesh.md#lodgroup)
- [LightMapCoordinateIndex](ue_ue.StaticMesh.md#lightmapcoordinateindex)
- [LightMapResolution](ue_ue.StaticMesh.md#lightmapresolution)
- [LightmapUVDensity](ue_ue.StaticMesh.md#lightmapuvdensity)
- [LightmapUVVersion](ue_ue.StaticMesh.md#lightmapuvversion)
- [LpvBiasMultiplier](ue_ue.StaticMesh.md#lpvbiasmultiplier)
- [MaterialRemapIndexPerImportVersion](ue_ue.StaticMesh.md#materialremapindexperimportversion)
- [Materials](ue_ue.StaticMesh.md#materials)
- [MinLOD](ue_ue.StaticMesh.md#minlod)
- [NavCollision](ue_ue.StaticMesh.md#navcollision)
- [NegativeBoundsExtension](ue_ue.StaticMesh.md#negativeboundsextension)
- [NeverStream](ue_ue.StaticMesh.md#neverstream)
- [NumCinematicMipLevels](ue_ue.StaticMesh.md#numcinematicmiplevels)
- [NumStreamedLODs](ue_ue.StaticMesh.md#numstreamedlods)
- [OriginalSectionInfoMap](ue_ue.StaticMesh.md#originalsectioninfomap)
- [PositiveBoundsExtension](ue_ue.StaticMesh.md#positiveboundsextension)
- [SectionInfoMap](ue_ue.StaticMesh.md#sectioninfomap)
- [Sockets](ue_ue.StaticMesh.md#sockets)
- [SourceFilePath](ue_ue.StaticMesh.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.StaticMesh.md#sourcefiletimestamp)
- [SourceModels](ue_ue.StaticMesh.md#sourcemodels)
- [StaticMaterials](ue_ue.StaticMesh.md#staticmaterials)
- [StreamingIndex](ue_ue.StaticMesh.md#streamingindex)
- [ThumbnailInfo](ue_ue.StaticMesh.md#thumbnailinfo)
- [\_\_tid\_Object\_\_](ue_ue.StaticMesh.md#__tid_object__)
- [\_\_tid\_StaticMesh\_\_](ue_ue.StaticMesh.md#__tid_staticmesh__)
- [\_\_tid\_StreamableRenderAsset\_\_](ue_ue.StaticMesh.md#__tid_streamablerenderasset__)
- [bAllowCPUAccess](ue_ue.StaticMesh.md#ballowcpuaccess)
- [bAutoComputeLODScreenSize](ue_ue.StaticMesh.md#bautocomputelodscreensize)
- [bCachedReadyForStreaming](ue_ue.StaticMesh.md#bcachedreadyforstreaming)
- [bCustomizedCollision](ue_ue.StaticMesh.md#bcustomizedcollision)
- [bForceMiplevelsToBeResident](ue_ue.StaticMesh.md#bforcemiplevelstoberesident)
- [bGenerateMeshDistanceField](ue_ue.StaticMesh.md#bgeneratemeshdistancefield)
- [bGlobalForceMipLevelsToBeResident](ue_ue.StaticMesh.md#bglobalforcemiplevelstoberesident)
- [bHasNavigationData](ue_ue.StaticMesh.md#bhasnavigationdata)
- [bHasStreamingUpdatePending](ue_ue.StaticMesh.md#bhasstreamingupdatepending)
- [bIgnoreStreamingMipBias](ue_ue.StaticMesh.md#bignorestreamingmipbias)
- [bIsBuiltAtRuntime](ue_ue.StaticMesh.md#bisbuiltatruntime)
- [bIsStreamable](ue_ue.StaticMesh.md#bisstreamable)
- [bStripComplexCollisionForConsole](ue_ue.StaticMesh.md#bstripcomplexcollisionforconsole)
- [bSupportGpuUniformlyDistributedSampling](ue_ue.StaticMesh.md#bsupportgpuuniformlydistributedsampling)
- [bSupportUniformlyDistributedSampling](ue_ue.StaticMesh.md#bsupportuniformlydistributedsampling)
- [bUseCinematicMipLevels](ue_ue.StaticMesh.md#busecinematicmiplevels)

### Methods

- [AddMaterial](ue_ue.StaticMesh.md#addmaterial)
- [AddSocket](ue_ue.StaticMesh.md#addsocket)
- [BuildFromStaticMeshDescriptions](ue_ue.StaticMesh.md#buildfromstaticmeshdescriptions)
- [CreateDefaultSubobject](ue_ue.StaticMesh.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.StaticMesh.md#executeubergraph)
- [FindSocket](ue_ue.StaticMesh.md#findsocket)
- [GetBoundingBox](ue_ue.StaticMesh.md#getboundingbox)
- [GetBounds](ue_ue.StaticMesh.md#getbounds)
- [GetClass](ue_ue.StaticMesh.md#getclass)
- [GetMaterial](ue_ue.StaticMesh.md#getmaterial)
- [GetMaterialIndex](ue_ue.StaticMesh.md#getmaterialindex)
- [GetMinimumLODForPlatform](ue_ue.StaticMesh.md#getminimumlodforplatform)
- [GetMinimumLODForPlatforms](ue_ue.StaticMesh.md#getminimumlodforplatforms)
- [GetName](ue_ue.StaticMesh.md#getname)
- [GetNumLODs](ue_ue.StaticMesh.md#getnumlods)
- [GetNumSections](ue_ue.StaticMesh.md#getnumsections)
- [GetOuter](ue_ue.StaticMesh.md#getouter)
- [GetWorld](ue_ue.StaticMesh.md#getworld)
- [RemoveSocket](ue_ue.StaticMesh.md#removesocket)
- [SetMaterial](ue_ue.StaticMesh.md#setmaterial)
- [SetNumSourceModels](ue_ue.StaticMesh.md#setnumsourcemodels)
- [CreateStaticMeshDescription](ue_ue.StaticMesh.md#createstaticmeshdescription)
- [Find](ue_ue.StaticMesh.md#find)
- [Load](ue_ue.StaticMesh.md#load)
- [StaticClass](ue_ue.StaticMesh.md#staticclass)

## Constructors

### constructor

• **new StaticMesh**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[constructor](ue_ue.StreamableRenderAsset.md#constructor)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

___

### BodySetup

• **BodySetup**: [`BodySetup`](ue_ue.BodySetup.md)

___

### CachedCombinedLODBias

• **CachedCombinedLODBias**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[CachedCombinedLODBias](ue_ue.StreamableRenderAsset.md#cachedcombinedlodbias)

___

### CachedNumResidentLODs

• **CachedNumResidentLODs**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[CachedNumResidentLODs](ue_ue.StreamableRenderAsset.md#cachednumresidentlods)

___

### ComplexCollisionMesh

• **ComplexCollisionMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### DistanceFieldSelfShadowBias

• **DistanceFieldSelfShadowBias**: `number`

___

### EditableMesh

• **EditableMesh**: [`Object`](ue_ue.Object.md)

___

### EditorCameraPosition

• **EditorCameraPosition**: [`AssetEditorOrbitCameraPosition`](ue_ue.AssetEditorOrbitCameraPosition.md)

___

### ElementToIgnoreForTexFactor

• **ElementToIgnoreForTexFactor**: `number`

___

### ExtendedBounds

• **ExtendedBounds**: [`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

___

### ForceMipLevelsToBeResidentTimestamp

• **ForceMipLevelsToBeResidentTimestamp**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[ForceMipLevelsToBeResidentTimestamp](ue_ue.StreamableRenderAsset.md#forcemiplevelstoberesidenttimestamp)

___

### ImportVersion

• **ImportVersion**: `number`

___

### LODForCollision

• **LODForCollision**: `number`

___

### LODForOccluderMesh

• **LODForOccluderMesh**: `number`

___

### LODGroup

• **LODGroup**: `string`

___

### LightMapCoordinateIndex

• **LightMapCoordinateIndex**: `number`

___

### LightMapResolution

• **LightMapResolution**: `number`

___

### LightmapUVDensity

• **LightmapUVDensity**: `number`

___

### LightmapUVVersion

• **LightmapUVVersion**: `number`

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

___

### MaterialRemapIndexPerImportVersion

• **MaterialRemapIndexPerImportVersion**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialRemapIndex`](ue_ue.MaterialRemapIndex.md)\>

___

### Materials

• **Materials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

___

### MinLOD

• **MinLOD**: [`PerPlatformInt`](ue_ue.PerPlatformInt.md)

___

### NavCollision

• **NavCollision**: [`NavCollisionBase`](ue_ue.NavCollisionBase.md)

___

### NegativeBoundsExtension

• **NegativeBoundsExtension**: [`Vector`](ue_ue_s.Vector.md)

___

### NeverStream

• **NeverStream**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[NeverStream](ue_ue.StreamableRenderAsset.md#neverstream)

___

### NumCinematicMipLevels

• **NumCinematicMipLevels**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[NumCinematicMipLevels](ue_ue.StreamableRenderAsset.md#numcinematicmiplevels)

___

### NumStreamedLODs

• **NumStreamedLODs**: [`PerPlatformInt`](ue_ue.PerPlatformInt.md)

___

### OriginalSectionInfoMap

• **OriginalSectionInfoMap**: [`MeshSectionInfoMap`](ue_ue.MeshSectionInfoMap.md)

___

### PositiveBoundsExtension

• **PositiveBoundsExtension**: [`Vector`](ue_ue_s.Vector.md)

___

### SectionInfoMap

• **SectionInfoMap**: [`MeshSectionInfoMap`](ue_ue.MeshSectionInfoMap.md)

___

### Sockets

• **Sockets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticMeshSocket`](ue_ue.StaticMeshSocket.md)\>

___

### SourceFilePath

• **SourceFilePath**: `string`

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

___

### SourceModels

• **SourceModels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticMeshSourceModel`](ue_ue.StaticMeshSourceModel.md)\>

___

### StaticMaterials

• **StaticMaterials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticMaterial`](ue_ue.StaticMaterial.md)\>

___

### StreamingIndex

• **StreamingIndex**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[StreamingIndex](ue_ue.StreamableRenderAsset.md#streamingindex)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[__tid_Object__](ue_ue.StreamableRenderAsset.md#__tid_object__)

___

### \_\_tid\_StaticMesh\_\_

• **\_\_tid\_StaticMesh\_\_**: `boolean`

___

### \_\_tid\_StreamableRenderAsset\_\_

• **\_\_tid\_StreamableRenderAsset\_\_**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[__tid_StreamableRenderAsset__](ue_ue.StreamableRenderAsset.md#__tid_streamablerenderasset__)

___

### bAllowCPUAccess

• **bAllowCPUAccess**: `boolean`

___

### bAutoComputeLODScreenSize

• **bAutoComputeLODScreenSize**: `boolean`

___

### bCachedReadyForStreaming

• **bCachedReadyForStreaming**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bCachedReadyForStreaming](ue_ue.StreamableRenderAsset.md#bcachedreadyforstreaming)

___

### bCustomizedCollision

• **bCustomizedCollision**: `boolean`

___

### bForceMiplevelsToBeResident

• **bForceMiplevelsToBeResident**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bForceMiplevelsToBeResident](ue_ue.StreamableRenderAsset.md#bforcemiplevelstoberesident)

___

### bGenerateMeshDistanceField

• **bGenerateMeshDistanceField**: `boolean`

___

### bGlobalForceMipLevelsToBeResident

• **bGlobalForceMipLevelsToBeResident**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bGlobalForceMipLevelsToBeResident](ue_ue.StreamableRenderAsset.md#bglobalforcemiplevelstoberesident)

___

### bHasNavigationData

• **bHasNavigationData**: `boolean`

___

### bHasStreamingUpdatePending

• **bHasStreamingUpdatePending**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bHasStreamingUpdatePending](ue_ue.StreamableRenderAsset.md#bhasstreamingupdatepending)

___

### bIgnoreStreamingMipBias

• **bIgnoreStreamingMipBias**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bIgnoreStreamingMipBias](ue_ue.StreamableRenderAsset.md#bignorestreamingmipbias)

___

### bIsBuiltAtRuntime

• **bIsBuiltAtRuntime**: `boolean`

___

### bIsStreamable

• **bIsStreamable**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bIsStreamable](ue_ue.StreamableRenderAsset.md#bisstreamable)

___

### bStripComplexCollisionForConsole

• **bStripComplexCollisionForConsole**: `boolean`

___

### bSupportGpuUniformlyDistributedSampling

• **bSupportGpuUniformlyDistributedSampling**: `boolean`

___

### bSupportUniformlyDistributedSampling

• **bSupportUniformlyDistributedSampling**: `boolean`

___

### bUseCinematicMipLevels

• **bUseCinematicMipLevels**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bUseCinematicMipLevels](ue_ue.StreamableRenderAsset.md#busecinematicmiplevels)

## Methods

### AddMaterial

▸ **AddMaterial**(`Material`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |

#### Returns

`string`

___

### AddSocket

▸ **AddSocket**(`Socket`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Socket` | [`$Nullable`](../modules/puerts.md#$nullable)<[`StaticMeshSocket`](ue_ue.StaticMeshSocket.md)\> |

#### Returns

`void`

___

### BuildFromStaticMeshDescriptions

▸ **BuildFromStaticMeshDescriptions**(`StaticMeshDescriptions`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StaticMeshDescriptions` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticMeshDescription`](ue_ue.StaticMeshDescription.md)\> |

#### Returns

`void`

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

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[CreateDefaultSubobject](ue_ue.StreamableRenderAsset.md#createdefaultsubobject)

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

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[ExecuteUbergraph](ue_ue.StreamableRenderAsset.md#executeubergraph)

___

### FindSocket

▸ **FindSocket**(`InSocketName`): [`StaticMeshSocket`](ue_ue.StaticMeshSocket.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSocketName` | `string` |

#### Returns

[`StaticMeshSocket`](ue_ue.StaticMeshSocket.md)

___

### GetBoundingBox

▸ **GetBoundingBox**(): [`Box`](ue_ue.Box.md)

#### Returns

[`Box`](ue_ue.Box.md)

___

### GetBounds

▸ **GetBounds**(): [`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

#### Returns

[`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetClass](ue_ue.StreamableRenderAsset.md#getclass)

___

### GetMaterial

▸ **GetMaterial**(`MaterialIndex`): [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialIndex` | `number` |

#### Returns

[`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### GetMaterialIndex

▸ **GetMaterialIndex**(`MaterialSlotName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialSlotName` | `string` |

#### Returns

`number`

___

### GetMinimumLODForPlatform

▸ **GetMinimumLODForPlatform**(`PlatformName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlatformName` | `string` |

#### Returns

`number`

___

### GetMinimumLODForPlatforms

▸ **GetMinimumLODForPlatforms**(`PlatformMinimumLODs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlatformMinimumLODs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `number`\>\> |

#### Returns

`void`

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetName](ue_ue.StreamableRenderAsset.md#getname)

___

### GetNumLODs

▸ **GetNumLODs**(): `number`

#### Returns

`number`

___

### GetNumSections

▸ **GetNumSections**(`InLOD`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLOD` | `number` |

#### Returns

`number`

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetOuter](ue_ue.StreamableRenderAsset.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetWorld](ue_ue.StreamableRenderAsset.md#getworld)

___

### RemoveSocket

▸ **RemoveSocket**(`Socket`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Socket` | [`$Nullable`](../modules/puerts.md#$nullable)<[`StaticMeshSocket`](ue_ue.StaticMeshSocket.md)\> |

#### Returns

`void`

___

### SetMaterial

▸ **SetMaterial**(`MaterialIndex`, `NewMaterial`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialIndex` | `number` |
| `NewMaterial` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |

#### Returns

`void`

___

### SetNumSourceModels

▸ **SetNumSourceModels**(`Num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Num` | `number` |

#### Returns

`void`

___

### CreateStaticMeshDescription

▸ `Static` **CreateStaticMeshDescription**(`Outer?`): [`StaticMeshDescription`](ue_ue.StaticMeshDescription.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`StaticMeshDescription`](ue_ue.StaticMeshDescription.md)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`StaticMesh`](ue_ue.StaticMesh.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`StaticMesh`](ue_ue.StaticMesh.md)

#### Overrides

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[Find](ue_ue.StreamableRenderAsset.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`StaticMesh`](ue_ue.StaticMesh.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`StaticMesh`](ue_ue.StaticMesh.md)

#### Overrides

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[Load](ue_ue.StreamableRenderAsset.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[StaticClass](ue_ue.StreamableRenderAsset.md#staticclass)
