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

#### Defined in

[ue/ue.d.ts:8070](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8070)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Defined in

[ue/ue.d.ts:8097](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8097)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Defined in

[ue/ue.d.ts:8109](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8109)

___

### BodySetup

• **BodySetup**: [`BodySetup`](ue_ue.BodySetup.md)

#### Defined in

[ue/ue.d.ts:8088](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8088)

___

### CachedCombinedLODBias

• **CachedCombinedLODBias**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[CachedCombinedLODBias](ue_ue.StreamableRenderAsset.md#cachedcombinedlodbias)

#### Defined in

[ue/ue.d.ts:387](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L387)

___

### CachedNumResidentLODs

• **CachedNumResidentLODs**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[CachedNumResidentLODs](ue_ue.StreamableRenderAsset.md#cachednumresidentlods)

#### Defined in

[ue/ue.d.ts:388](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L388)

___

### ComplexCollisionMesh

• **ComplexCollisionMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:8111](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8111)

___

### DistanceFieldSelfShadowBias

• **DistanceFieldSelfShadowBias**: `number`

#### Defined in

[ue/ue.d.ts:8087](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8087)

___

### EditableMesh

• **EditableMesh**: [`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:8110](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8110)

___

### EditorCameraPosition

• **EditorCameraPosition**: [`AssetEditorOrbitCameraPosition`](ue_ue.AssetEditorOrbitCameraPosition.md)

#### Defined in

[ue/ue.d.ts:8101](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8101)

___

### ElementToIgnoreForTexFactor

• **ElementToIgnoreForTexFactor**: `number`

#### Defined in

[ue/ue.d.ts:8108](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8108)

___

### ExtendedBounds

• **ExtendedBounds**: [`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

#### Defined in

[ue/ue.d.ts:8107](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8107)

___

### ForceMipLevelsToBeResidentTimestamp

• **ForceMipLevelsToBeResidentTimestamp**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[ForceMipLevelsToBeResidentTimestamp](ue_ue.StreamableRenderAsset.md#forcemiplevelstoberesidenttimestamp)

#### Defined in

[ue/ue.d.ts:384](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L384)

___

### ImportVersion

• **ImportVersion**: `number`

#### Defined in

[ue/ue.d.ts:8076](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8076)

___

### LODForCollision

• **LODForCollision**: `number`

#### Defined in

[ue/ue.d.ts:8089](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8089)

___

### LODForOccluderMesh

• **LODForOccluderMesh**: `number`

#### Defined in

[ue/ue.d.ts:8103](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8103)

___

### LODGroup

• **LODGroup**: `string`

#### Defined in

[ue/ue.d.ts:8074](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8074)

___

### LightMapCoordinateIndex

• **LightMapCoordinateIndex**: `number`

#### Defined in

[ue/ue.d.ts:8086](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8086)

___

### LightMapResolution

• **LightMapResolution**: `number`

#### Defined in

[ue/ue.d.ts:8085](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8085)

___

### LightmapUVDensity

• **LightmapUVDensity**: `number`

#### Defined in

[ue/ue.d.ts:8084](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8084)

___

### LightmapUVVersion

• **LightmapUVVersion**: `number`

#### Defined in

[ue/ue.d.ts:8078](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8078)

___

### LpvBiasMultiplier

• **LpvBiasMultiplier**: `number`

#### Defined in

[ue/ue.d.ts:8082](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8082)

___

### MaterialRemapIndexPerImportVersion

• **MaterialRemapIndexPerImportVersion**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialRemapIndex`](ue_ue.MaterialRemapIndex.md)\>

#### Defined in

[ue/ue.d.ts:8077](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8077)

___

### Materials

• **Materials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Defined in

[ue/ue.d.ts:8080](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8080)

___

### MinLOD

• **MinLOD**: [`PerPlatformInt`](ue_ue.PerPlatformInt.md)

#### Defined in

[ue/ue.d.ts:8081](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8081)

___

### NavCollision

• **NavCollision**: [`NavCollisionBase`](ue_ue.NavCollisionBase.md)

#### Defined in

[ue/ue.d.ts:8112](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8112)

___

### NegativeBoundsExtension

• **NegativeBoundsExtension**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:8106](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8106)

___

### NeverStream

• **NeverStream**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[NeverStream](ue_ue.StreamableRenderAsset.md#neverstream)

#### Defined in

[ue/ue.d.ts:390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L390)

___

### NumCinematicMipLevels

• **NumCinematicMipLevels**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[NumCinematicMipLevels](ue_ue.StreamableRenderAsset.md#numcinematicmiplevels)

#### Defined in

[ue/ue.d.ts:385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L385)

___

### NumStreamedLODs

• **NumStreamedLODs**: [`PerPlatformInt`](ue_ue.PerPlatformInt.md)

#### Defined in

[ue/ue.d.ts:8075](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8075)

___

### OriginalSectionInfoMap

• **OriginalSectionInfoMap**: [`MeshSectionInfoMap`](ue_ue.MeshSectionInfoMap.md)

#### Defined in

[ue/ue.d.ts:8073](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8073)

___

### PositiveBoundsExtension

• **PositiveBoundsExtension**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:8105](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8105)

___

### SectionInfoMap

• **SectionInfoMap**: [`MeshSectionInfoMap`](ue_ue.MeshSectionInfoMap.md)

#### Defined in

[ue/ue.d.ts:8072](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8072)

___

### Sockets

• **Sockets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticMeshSocket`](ue_ue.StaticMeshSocket.md)\>

#### Defined in

[ue/ue.d.ts:8104](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8104)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Defined in

[ue/ue.d.ts:8098](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8098)

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

#### Defined in

[ue/ue.d.ts:8099](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8099)

___

### SourceModels

• **SourceModels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticMeshSourceModel`](ue_ue.StaticMeshSourceModel.md)\>

#### Defined in

[ue/ue.d.ts:8071](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8071)

___

### StaticMaterials

• **StaticMaterials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticMaterial`](ue_ue.StaticMaterial.md)\>

#### Defined in

[ue/ue.d.ts:8083](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8083)

___

### StreamingIndex

• **StreamingIndex**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[StreamingIndex](ue_ue.StreamableRenderAsset.md#streamingindex)

#### Defined in

[ue/ue.d.ts:386](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L386)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Defined in

[ue/ue.d.ts:8100](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8100)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[__tid_Object__](ue_ue.StreamableRenderAsset.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_StaticMesh\_\_

• **\_\_tid\_StaticMesh\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:8133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8133)

___

### \_\_tid\_StreamableRenderAsset\_\_

• **\_\_tid\_StreamableRenderAsset\_\_**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[__tid_StreamableRenderAsset__](ue_ue.StreamableRenderAsset.md#__tid_streamablerenderasset__)

#### Defined in

[ue/ue.d.ts:401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L401)

___

### bAllowCPUAccess

• **bAllowCPUAccess**: `boolean`

#### Defined in

[ue/ue.d.ts:8095](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8095)

___

### bAutoComputeLODScreenSize

• **bAutoComputeLODScreenSize**: `boolean`

#### Defined in

[ue/ue.d.ts:8079](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8079)

___

### bCachedReadyForStreaming

• **bCachedReadyForStreaming**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bCachedReadyForStreaming](ue_ue.StreamableRenderAsset.md#bcachedreadyforstreaming)

#### Defined in

[ue/ue.d.ts:389](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L389)

___

### bCustomizedCollision

• **bCustomizedCollision**: `boolean`

#### Defined in

[ue/ue.d.ts:8102](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8102)

___

### bForceMiplevelsToBeResident

• **bForceMiplevelsToBeResident**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bForceMiplevelsToBeResident](ue_ue.StreamableRenderAsset.md#bforcemiplevelstoberesident)

#### Defined in

[ue/ue.d.ts:394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L394)

___

### bGenerateMeshDistanceField

• **bGenerateMeshDistanceField**: `boolean`

#### Defined in

[ue/ue.d.ts:8090](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8090)

___

### bGlobalForceMipLevelsToBeResident

• **bGlobalForceMipLevelsToBeResident**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bGlobalForceMipLevelsToBeResident](ue_ue.StreamableRenderAsset.md#bglobalforcemiplevelstoberesident)

#### Defined in

[ue/ue.d.ts:391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L391)

___

### bHasNavigationData

• **bHasNavigationData**: `boolean`

#### Defined in

[ue/ue.d.ts:8092](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8092)

___

### bHasStreamingUpdatePending

• **bHasStreamingUpdatePending**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bHasStreamingUpdatePending](ue_ue.StreamableRenderAsset.md#bhasstreamingupdatepending)

#### Defined in

[ue/ue.d.ts:393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L393)

___

### bIgnoreStreamingMipBias

• **bIgnoreStreamingMipBias**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bIgnoreStreamingMipBias](ue_ue.StreamableRenderAsset.md#bignorestreamingmipbias)

#### Defined in

[ue/ue.d.ts:395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L395)

___

### bIsBuiltAtRuntime

• **bIsBuiltAtRuntime**: `boolean`

#### Defined in

[ue/ue.d.ts:8094](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8094)

___

### bIsStreamable

• **bIsStreamable**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bIsStreamable](ue_ue.StreamableRenderAsset.md#bisstreamable)

#### Defined in

[ue/ue.d.ts:392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L392)

___

### bStripComplexCollisionForConsole

• **bStripComplexCollisionForConsole**: `boolean`

#### Defined in

[ue/ue.d.ts:8091](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8091)

___

### bSupportGpuUniformlyDistributedSampling

• **bSupportGpuUniformlyDistributedSampling**: `boolean`

#### Defined in

[ue/ue.d.ts:8096](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8096)

___

### bSupportUniformlyDistributedSampling

• **bSupportUniformlyDistributedSampling**: `boolean`

#### Defined in

[ue/ue.d.ts:8093](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8093)

___

### bUseCinematicMipLevels

• **bUseCinematicMipLevels**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bUseCinematicMipLevels](ue_ue.StreamableRenderAsset.md#busecinematicmiplevels)

#### Defined in

[ue/ue.d.ts:396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L396)

## Methods

### AddMaterial

▸ **AddMaterial**(`Material`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Material` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:8113](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8113)

___

### AddSocket

▸ **AddSocket**(`Socket`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Socket` | [`$Nullable`](../modules/puerts.md#$nullable)<[`StaticMeshSocket`](ue_ue.StaticMeshSocket.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8114](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8114)

___

### BuildFromStaticMeshDescriptions

▸ **BuildFromStaticMeshDescriptions**(`StaticMeshDescriptions`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StaticMeshDescriptions` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`StaticMeshDescription`](ue_ue.StaticMeshDescription.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8115](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8115)

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

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[ExecuteUbergraph](ue_ue.StreamableRenderAsset.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### FindSocket

▸ **FindSocket**(`InSocketName`): [`StaticMeshSocket`](ue_ue.StaticMeshSocket.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSocketName` | `string` |

#### Returns

[`StaticMeshSocket`](ue_ue.StaticMeshSocket.md)

#### Defined in

[ue/ue.d.ts:8116](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8116)

___

### GetBoundingBox

▸ **GetBoundingBox**(): [`Box`](ue_ue.Box.md)

#### Returns

[`Box`](ue_ue.Box.md)

#### Defined in

[ue/ue.d.ts:8117](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8117)

___

### GetBounds

▸ **GetBounds**(): [`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

#### Returns

[`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

#### Defined in

[ue/ue.d.ts:8118](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8118)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetClass](ue_ue.StreamableRenderAsset.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetMaterial

▸ **GetMaterial**(`MaterialIndex`): [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialIndex` | `number` |

#### Returns

[`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:8119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8119)

___

### GetMaterialIndex

▸ **GetMaterialIndex**(`MaterialSlotName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaterialSlotName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:8120](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8120)

___

### GetMinimumLODForPlatform

▸ **GetMinimumLODForPlatform**(`PlatformName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlatformName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:8121](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8121)

___

### GetMinimumLODForPlatforms

▸ **GetMinimumLODForPlatforms**(`PlatformMinimumLODs`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlatformMinimumLODs` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `number`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8122](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8122)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetName](ue_ue.StreamableRenderAsset.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetNumLODs

▸ **GetNumLODs**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:8123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8123)

___

### GetNumSections

▸ **GetNumSections**(`InLOD`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLOD` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:8124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8124)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetOuter](ue_ue.StreamableRenderAsset.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetWorld](ue_ue.StreamableRenderAsset.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### RemoveSocket

▸ **RemoveSocket**(`Socket`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Socket` | [`$Nullable`](../modules/puerts.md#$nullable)<[`StaticMeshSocket`](ue_ue.StaticMeshSocket.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8125)

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

#### Defined in

[ue/ue.d.ts:8126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8126)

___

### SetNumSourceModels

▸ **SetNumSourceModels**(`Num`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Num` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:8127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8127)

___

### CreateStaticMeshDescription

▸ `Static` **CreateStaticMeshDescription**(`Outer?`): [`StaticMeshDescription`](ue_ue.StaticMeshDescription.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`StaticMeshDescription`](ue_ue.StaticMeshDescription.md)

#### Defined in

[ue/ue.d.ts:8128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8128)

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

#### Defined in

[ue/ue.d.ts:8130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8130)

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

#### Defined in

[ue/ue.d.ts:8131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8131)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[StaticClass](ue_ue.StreamableRenderAsset.md#staticclass)

#### Defined in

[ue/ue.d.ts:8129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8129)
