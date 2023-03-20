[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SkeletalMesh

# Class: SkeletalMesh

[ue/ue](../modules/ue_ue.md).SkeletalMesh

## Hierarchy

- [`StreamableRenderAsset`](ue_ue.StreamableRenderAsset.md)

  ↳ **`SkeletalMesh`**

## Table of contents

### Constructors

- [constructor](ue_ue.SkeletalMesh.md#constructor)

### Properties

- [AssetImportData](ue_ue.SkeletalMesh.md#assetimportdata)
- [AssetUserData](ue_ue.SkeletalMesh.md#assetuserdata)
- [BodySetup](ue_ue.SkeletalMesh.md#bodysetup)
- [CachedCombinedLODBias](ue_ue.SkeletalMesh.md#cachedcombinedlodbias)
- [CachedNumResidentLODs](ue_ue.SkeletalMesh.md#cachednumresidentlods)
- [ClothingAssets](ue_ue.SkeletalMesh.md#clothingassets)
- [DefaultEditorCameraLocation](ue_ue.SkeletalMesh.md#defaulteditorcameralocation)
- [DefaultEditorCameraLookAt](ue_ue.SkeletalMesh.md#defaulteditorcameralookat)
- [DefaultEditorCameraOrthoZoom](ue_ue.SkeletalMesh.md#defaulteditorcameraorthozoom)
- [DefaultEditorCameraRotation](ue_ue.SkeletalMesh.md#defaulteditorcamerarotation)
- [DisableBelowMinLodStripping](ue_ue.SkeletalMesh.md#disablebelowminlodstripping)
- [ExtendedBounds](ue_ue.SkeletalMesh.md#extendedbounds)
- [FloorOffset](ue_ue.SkeletalMesh.md#flooroffset)
- [ForceMipLevelsToBeResidentTimestamp](ue_ue.SkeletalMesh.md#forcemiplevelstoberesidenttimestamp)
- [ImportedBounds](ue_ue.SkeletalMesh.md#importedbounds)
- [LODInfo](ue_ue.SkeletalMesh.md#lodinfo)
- [LODSettings](ue_ue.SkeletalMesh.md#lodsettings)
- [Materials](ue_ue.SkeletalMesh.md#materials)
- [MaxNumOptionalLODs](ue_ue.SkeletalMesh.md#maxnumoptionallods)
- [MaxNumStreamedLODs](ue_ue.SkeletalMesh.md#maxnumstreamedlods)
- [MeshClothingAssets](ue_ue.SkeletalMesh.md#meshclothingassets)
- [MinLod](ue_ue.SkeletalMesh.md#minlod)
- [MorphTargets](ue_ue.SkeletalMesh.md#morphtargets)
- [NegativeBoundsExtension](ue_ue.SkeletalMesh.md#negativeboundsextension)
- [NeverStream](ue_ue.SkeletalMesh.md#neverstream)
- [NodeMappingData](ue_ue.SkeletalMesh.md#nodemappingdata)
- [NumCinematicMipLevels](ue_ue.SkeletalMesh.md#numcinematicmiplevels)
- [PhysicsAsset](ue_ue.SkeletalMesh.md#physicsasset)
- [PositiveBoundsExtension](ue_ue.SkeletalMesh.md#positiveboundsextension)
- [PostProcessAnimBlueprint](ue_ue.SkeletalMesh.md#postprocessanimblueprint)
- [PreviewAttachedAssetContainer](ue_ue.SkeletalMesh.md#previewattachedassetcontainer)
- [RetargetBasePose](ue_ue.SkeletalMesh.md#retargetbasepose)
- [SamplingInfo](ue_ue.SkeletalMesh.md#samplinginfo)
- [ShadowPhysicsAsset](ue_ue.SkeletalMesh.md#shadowphysicsasset)
- [SkelMirrorAxis](ue_ue.SkeletalMesh.md#skelmirroraxis)
- [SkelMirrorFlipAxis](ue_ue.SkeletalMesh.md#skelmirrorflipaxis)
- [SkelMirrorTable](ue_ue.SkeletalMesh.md#skelmirrortable)
- [Skeleton](ue_ue.SkeletalMesh.md#skeleton)
- [SkinWeightProfiles](ue_ue.SkeletalMesh.md#skinweightprofiles)
- [Sockets](ue_ue.SkeletalMesh.md#sockets)
- [SourceFilePath](ue_ue.SkeletalMesh.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.SkeletalMesh.md#sourcefiletimestamp)
- [StreamingIndex](ue_ue.SkeletalMesh.md#streamingindex)
- [ThumbnailInfo](ue_ue.SkeletalMesh.md#thumbnailinfo)
- [VertexColorGuid](ue_ue.SkeletalMesh.md#vertexcolorguid)
- [\_\_tid\_Object\_\_](ue_ue.SkeletalMesh.md#__tid_object__)
- [\_\_tid\_SkeletalMesh\_\_](ue_ue.SkeletalMesh.md#__tid_skeletalmesh__)
- [\_\_tid\_StreamableRenderAsset\_\_](ue_ue.SkeletalMesh.md#__tid_streamablerenderasset__)
- [bCachedReadyForStreaming](ue_ue.SkeletalMesh.md#bcachedreadyforstreaming)
- [bEnablePerPolyCollision](ue_ue.SkeletalMesh.md#benableperpolycollision)
- [bForceMiplevelsToBeResident](ue_ue.SkeletalMesh.md#bforcemiplevelstoberesident)
- [bGlobalForceMipLevelsToBeResident](ue_ue.SkeletalMesh.md#bglobalforcemiplevelstoberesident)
- [bHasBeenSimplified](ue_ue.SkeletalMesh.md#bhasbeensimplified)
- [bHasCustomDefaultEditorCamera](ue_ue.SkeletalMesh.md#bhascustomdefaulteditorcamera)
- [bHasStreamingUpdatePending](ue_ue.SkeletalMesh.md#bhasstreamingupdatepending)
- [bHasVertexColors](ue_ue.SkeletalMesh.md#bhasvertexcolors)
- [bIgnoreStreamingMipBias](ue_ue.SkeletalMesh.md#bignorestreamingmipbias)
- [bIsStreamable](ue_ue.SkeletalMesh.md#bisstreamable)
- [bSupportLODStreaming](ue_ue.SkeletalMesh.md#bsupportlodstreaming)
- [bUseCinematicMipLevels](ue_ue.SkeletalMesh.md#busecinematicmiplevels)
- [bUseFullPrecisionUVs](ue_ue.SkeletalMesh.md#busefullprecisionuvs)
- [bUseHighPrecisionTangentBasis](ue_ue.SkeletalMesh.md#busehighprecisiontangentbasis)

### Methods

- [CreateDefaultSubobject](ue_ue.SkeletalMesh.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SkeletalMesh.md#executeubergraph)
- [FindSocket](ue_ue.SkeletalMesh.md#findsocket)
- [FindSocketAndIndex](ue_ue.SkeletalMesh.md#findsocketandindex)
- [FindSocketInfo](ue_ue.SkeletalMesh.md#findsocketinfo)
- [GetBounds](ue_ue.SkeletalMesh.md#getbounds)
- [GetClass](ue_ue.SkeletalMesh.md#getclass)
- [GetImportedBounds](ue_ue.SkeletalMesh.md#getimportedbounds)
- [GetName](ue_ue.SkeletalMesh.md#getname)
- [GetNodeMappingContainer](ue_ue.SkeletalMesh.md#getnodemappingcontainer)
- [GetOuter](ue_ue.SkeletalMesh.md#getouter)
- [GetSocketByIndex](ue_ue.SkeletalMesh.md#getsocketbyindex)
- [GetWorld](ue_ue.SkeletalMesh.md#getworld)
- [IsSectionUsingCloth](ue_ue.SkeletalMesh.md#issectionusingcloth)
- [K2\_GetAllMorphTargetNames](ue_ue.SkeletalMesh.md#k2_getallmorphtargetnames)
- [NumSockets](ue_ue.SkeletalMesh.md#numsockets)
- [SetLODSettings](ue_ue.SkeletalMesh.md#setlodsettings)
- [Find](ue_ue.SkeletalMesh.md#find)
- [Load](ue_ue.SkeletalMesh.md#load)
- [StaticClass](ue_ue.SkeletalMesh.md#staticclass)

## Constructors

### constructor

• **new SkeletalMesh**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[constructor](ue_ue.StreamableRenderAsset.md#constructor)

#### Defined in

[ue/ue.d.ts:4522](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4522)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Defined in

[ue/ue.d.ts:4549](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4549)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Defined in

[ue/ue.d.ts:4566](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4566)

___

### BodySetup

• **BodySetup**: [`BodySetup`](ue_ue.BodySetup.md)

#### Defined in

[ue/ue.d.ts:4545](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4545)

___

### CachedCombinedLODBias

• **CachedCombinedLODBias**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[CachedCombinedLODBias](ue_ue.StreamableRenderAsset.md#cachedcombinedlodbias)

#### Defined in

[ue/ue.d.ts:387](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L387)

___

### CachedNumResidentLODs

• **CachedNumResidentLODs**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[CachedNumResidentLODs](ue_ue.StreamableRenderAsset.md#cachednumresidentlods)

#### Defined in

[ue/ue.d.ts:388](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L388)

___

### ClothingAssets

• **ClothingAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothingAssetData_Legacy`](ue_ue.ClothingAssetData_Legacy.md)\>

#### Defined in

[ue/ue.d.ts:4562](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4562)

___

### DefaultEditorCameraLocation

• **DefaultEditorCameraLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:4554](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4554)

___

### DefaultEditorCameraLookAt

• **DefaultEditorCameraLookAt**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:4556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4556)

___

### DefaultEditorCameraOrthoZoom

• **DefaultEditorCameraOrthoZoom**: `number`

#### Defined in

[ue/ue.d.ts:4557](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4557)

___

### DefaultEditorCameraRotation

• **DefaultEditorCameraRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:4555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4555)

___

### DisableBelowMinLodStripping

• **DisableBelowMinLodStripping**: [`PerPlatformBool`](ue_ue.PerPlatformBool.md)

#### Defined in

[ue/ue.d.ts:4532](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4532)

___

### ExtendedBounds

• **ExtendedBounds**: [`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

#### Defined in

[ue/ue.d.ts:4525](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4525)

___

### FloorOffset

• **FloorOffset**: `number`

#### Defined in

[ue/ue.d.ts:4560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4560)

___

### ForceMipLevelsToBeResidentTimestamp

• **ForceMipLevelsToBeResidentTimestamp**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[ForceMipLevelsToBeResidentTimestamp](ue_ue.StreamableRenderAsset.md#forcemiplevelstoberesidenttimestamp)

#### Defined in

[ue/ue.d.ts:384](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L384)

___

### ImportedBounds

• **ImportedBounds**: [`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

#### Defined in

[ue/ue.d.ts:4524](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4524)

___

### LODInfo

• **LODInfo**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SkeletalMeshLODInfo`](ue_ue.SkeletalMeshLODInfo.md)\>

#### Defined in

[ue/ue.d.ts:4530](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4530)

___

### LODSettings

• **LODSettings**: [`SkeletalMeshLODSettings`](ue_ue.SkeletalMeshLODSettings.md)

#### Defined in

[ue/ue.d.ts:4536](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4536)

___

### Materials

• **Materials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SkeletalMaterial`](ue_ue.SkeletalMaterial.md)\>

#### Defined in

[ue/ue.d.ts:4528](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4528)

___

### MaxNumOptionalLODs

• **MaxNumOptionalLODs**: [`PerPlatformInt`](ue_ue.PerPlatformInt.md)

#### Defined in

[ue/ue.d.ts:4535](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4535)

___

### MaxNumStreamedLODs

• **MaxNumStreamedLODs**: [`PerPlatformInt`](ue_ue.PerPlatformInt.md)

#### Defined in

[ue/ue.d.ts:4534](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4534)

___

### MeshClothingAssets

• **MeshClothingAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ClothingAssetBase`](ue_ue.ClothingAssetBase.md)\>

#### Defined in

[ue/ue.d.ts:4564](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4564)

___

### MinLod

• **MinLod**: [`PerPlatformInt`](ue_ue.PerPlatformInt.md)

#### Defined in

[ue/ue.d.ts:4531](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4531)

___

### MorphTargets

• **MorphTargets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MorphTarget`](ue_ue.MorphTarget.md)\>

#### Defined in

[ue/ue.d.ts:4559](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4559)

___

### NegativeBoundsExtension

• **NegativeBoundsExtension**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:4527](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4527)

___

### NeverStream

• **NeverStream**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[NeverStream](ue_ue.StreamableRenderAsset.md#neverstream)

#### Defined in

[ue/ue.d.ts:390](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L390)

___

### NodeMappingData

• **NodeMappingData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NodeMappingContainer`](ue_ue.NodeMappingContainer.md)\>

#### Defined in

[ue/ue.d.ts:4548](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4548)

___

### NumCinematicMipLevels

• **NumCinematicMipLevels**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[NumCinematicMipLevels](ue_ue.StreamableRenderAsset.md#numcinematicmiplevels)

#### Defined in

[ue/ue.d.ts:385](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L385)

___

### PhysicsAsset

• **PhysicsAsset**: [`PhysicsAsset`](ue_ue.PhysicsAsset.md)

#### Defined in

[ue/ue.d.ts:4546](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4546)

___

### PositiveBoundsExtension

• **PositiveBoundsExtension**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:4526](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4526)

___

### PostProcessAnimBlueprint

• **PostProcessAnimBlueprint**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:4563](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4563)

___

### PreviewAttachedAssetContainer

• **PreviewAttachedAssetContainer**: [`PreviewAssetAttachContainer`](ue_ue.PreviewAssetAttachContainer.md)

#### Defined in

[ue/ue.d.ts:4558](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4558)

___

### RetargetBasePose

• **RetargetBasePose**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\>

#### Defined in

[ue/ue.d.ts:4561](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4561)

___

### SamplingInfo

• **SamplingInfo**: [`SkeletalMeshSamplingInfo`](ue_ue.SkeletalMeshSamplingInfo.md)

#### Defined in

[ue/ue.d.ts:4565](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4565)

___

### ShadowPhysicsAsset

• **ShadowPhysicsAsset**: [`PhysicsAsset`](ue_ue.PhysicsAsset.md)

#### Defined in

[ue/ue.d.ts:4547](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4547)

___

### SkelMirrorAxis

• **SkelMirrorAxis**: [`EAxis`](../enums/ue_ue.EAxis.md)

#### Defined in

[ue/ue.d.ts:4537](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4537)

___

### SkelMirrorFlipAxis

• **SkelMirrorFlipAxis**: [`EAxis`](../enums/ue_ue.EAxis.md)

#### Defined in

[ue/ue.d.ts:4538](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4538)

___

### SkelMirrorTable

• **SkelMirrorTable**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneMirrorInfo`](ue_ue.BoneMirrorInfo.md)\>

#### Defined in

[ue/ue.d.ts:4529](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4529)

___

### Skeleton

• **Skeleton**: [`Skeleton`](ue_ue.Skeleton.md)

#### Defined in

[ue/ue.d.ts:4523](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4523)

___

### SkinWeightProfiles

• **SkinWeightProfiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SkinWeightProfileInfo`](ue_ue.SkinWeightProfileInfo.md)\>

#### Defined in

[ue/ue.d.ts:4568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4568)

___

### Sockets

• **Sockets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SkeletalMeshSocket`](ue_ue.SkeletalMeshSocket.md)\>

#### Defined in

[ue/ue.d.ts:4567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4567)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Defined in

[ue/ue.d.ts:4550](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4550)

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

#### Defined in

[ue/ue.d.ts:4551](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4551)

___

### StreamingIndex

• **StreamingIndex**: `number`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[StreamingIndex](ue_ue.StreamableRenderAsset.md#streamingindex)

#### Defined in

[ue/ue.d.ts:386](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L386)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Defined in

[ue/ue.d.ts:4552](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4552)

___

### VertexColorGuid

• **VertexColorGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:4544](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4544)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[__tid_Object__](ue_ue.StreamableRenderAsset.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SkeletalMesh\_\_

• **\_\_tid\_SkeletalMesh\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:4584](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4584)

___

### \_\_tid\_StreamableRenderAsset\_\_

• **\_\_tid\_StreamableRenderAsset\_\_**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[__tid_StreamableRenderAsset__](ue_ue.StreamableRenderAsset.md#__tid_streamablerenderasset__)

#### Defined in

[ue/ue.d.ts:401](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L401)

___

### bCachedReadyForStreaming

• **bCachedReadyForStreaming**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bCachedReadyForStreaming](ue_ue.StreamableRenderAsset.md#bcachedreadyforstreaming)

#### Defined in

[ue/ue.d.ts:389](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L389)

___

### bEnablePerPolyCollision

• **bEnablePerPolyCollision**: `boolean`

#### Defined in

[ue/ue.d.ts:4543](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4543)

___

### bForceMiplevelsToBeResident

• **bForceMiplevelsToBeResident**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bForceMiplevelsToBeResident](ue_ue.StreamableRenderAsset.md#bforcemiplevelstoberesident)

#### Defined in

[ue/ue.d.ts:394](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L394)

___

### bGlobalForceMipLevelsToBeResident

• **bGlobalForceMipLevelsToBeResident**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bGlobalForceMipLevelsToBeResident](ue_ue.StreamableRenderAsset.md#bglobalforcemiplevelstoberesident)

#### Defined in

[ue/ue.d.ts:391](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L391)

___

### bHasBeenSimplified

• **bHasBeenSimplified**: `boolean`

#### Defined in

[ue/ue.d.ts:4541](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4541)

___

### bHasCustomDefaultEditorCamera

• **bHasCustomDefaultEditorCamera**: `boolean`

#### Defined in

[ue/ue.d.ts:4553](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4553)

___

### bHasStreamingUpdatePending

• **bHasStreamingUpdatePending**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bHasStreamingUpdatePending](ue_ue.StreamableRenderAsset.md#bhasstreamingupdatepending)

#### Defined in

[ue/ue.d.ts:393](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L393)

___

### bHasVertexColors

• **bHasVertexColors**: `boolean`

#### Defined in

[ue/ue.d.ts:4542](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4542)

___

### bIgnoreStreamingMipBias

• **bIgnoreStreamingMipBias**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bIgnoreStreamingMipBias](ue_ue.StreamableRenderAsset.md#bignorestreamingmipbias)

#### Defined in

[ue/ue.d.ts:395](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L395)

___

### bIsStreamable

• **bIsStreamable**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bIsStreamable](ue_ue.StreamableRenderAsset.md#bisstreamable)

#### Defined in

[ue/ue.d.ts:392](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L392)

___

### bSupportLODStreaming

• **bSupportLODStreaming**: [`PerPlatformBool`](ue_ue.PerPlatformBool.md)

#### Defined in

[ue/ue.d.ts:4533](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4533)

___

### bUseCinematicMipLevels

• **bUseCinematicMipLevels**: `boolean`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[bUseCinematicMipLevels](ue_ue.StreamableRenderAsset.md#busecinematicmiplevels)

#### Defined in

[ue/ue.d.ts:396](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L396)

___

### bUseFullPrecisionUVs

• **bUseFullPrecisionUVs**: `boolean`

#### Defined in

[ue/ue.d.ts:4539](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4539)

___

### bUseHighPrecisionTangentBasis

• **bUseHighPrecisionTangentBasis**: `boolean`

#### Defined in

[ue/ue.d.ts:4540](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4540)

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

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[CreateDefaultSubobject](ue_ue.StreamableRenderAsset.md#createdefaultsubobject)

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

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[ExecuteUbergraph](ue_ue.StreamableRenderAsset.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### FindSocket

▸ **FindSocket**(`InSocketName`): [`SkeletalMeshSocket`](ue_ue.SkeletalMeshSocket.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSocketName` | `string` |

#### Returns

[`SkeletalMeshSocket`](ue_ue.SkeletalMeshSocket.md)

#### Defined in

[ue/ue.d.ts:4569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4569)

___

### FindSocketAndIndex

▸ **FindSocketAndIndex**(`InSocketName`, `OutIndex`): [`SkeletalMeshSocket`](ue_ue.SkeletalMeshSocket.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSocketName` | `string` |
| `OutIndex` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

[`SkeletalMeshSocket`](ue_ue.SkeletalMeshSocket.md)

#### Defined in

[ue/ue.d.ts:4570](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4570)

___

### FindSocketInfo

▸ **FindSocketInfo**(`InSocketName`, `OutTransform`, `OutBoneIndex`, `OutIndex`): [`SkeletalMeshSocket`](ue_ue.SkeletalMeshSocket.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSocketName` | `string` |
| `OutTransform` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Transform`](ue_ue_s.Transform.md)\> |
| `OutBoneIndex` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `OutIndex` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

[`SkeletalMeshSocket`](ue_ue.SkeletalMeshSocket.md)

#### Defined in

[ue/ue.d.ts:4571](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4571)

___

### GetBounds

▸ **GetBounds**(): [`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

#### Returns

[`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

#### Defined in

[ue/ue.d.ts:4572](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4572)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetClass](ue_ue.StreamableRenderAsset.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetImportedBounds

▸ **GetImportedBounds**(): [`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

#### Returns

[`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

#### Defined in

[ue/ue.d.ts:4573](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4573)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetName](ue_ue.StreamableRenderAsset.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetNodeMappingContainer

▸ **GetNodeMappingContainer**(`SourceAsset`): [`NodeMappingContainer`](ue_ue.NodeMappingContainer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceAsset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Blueprint`](ue_ue.Blueprint.md)\> |

#### Returns

[`NodeMappingContainer`](ue_ue.NodeMappingContainer.md)

#### Defined in

[ue/ue.d.ts:4574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4574)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetOuter](ue_ue.StreamableRenderAsset.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetSocketByIndex

▸ **GetSocketByIndex**(`Index`): [`SkeletalMeshSocket`](ue_ue.SkeletalMeshSocket.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

[`SkeletalMeshSocket`](ue_ue.SkeletalMeshSocket.md)

#### Defined in

[ue/ue.d.ts:4575](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4575)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[GetWorld](ue_ue.StreamableRenderAsset.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsSectionUsingCloth

▸ **IsSectionUsingCloth**(`InSectionIndex`, `bCheckCorrespondingSections?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSectionIndex` | `number` |
| `bCheckCorrespondingSections?` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:4576](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4576)

___

### K2\_GetAllMorphTargetNames

▸ **K2_GetAllMorphTargetNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:4577](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4577)

___

### NumSockets

▸ **NumSockets**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:4578](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4578)

___

### SetLODSettings

▸ **SetLODSettings**(`InLODSettings`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLODSettings` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SkeletalMeshLODSettings`](ue_ue.SkeletalMeshLODSettings.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:4579](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4579)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SkeletalMesh`](ue_ue.SkeletalMesh.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SkeletalMesh`](ue_ue.SkeletalMesh.md)

#### Overrides

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[Find](ue_ue.StreamableRenderAsset.md#find)

#### Defined in

[ue/ue.d.ts:4581](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4581)

___

### Load

▸ `Static` **Load**(`InName`): [`SkeletalMesh`](ue_ue.SkeletalMesh.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SkeletalMesh`](ue_ue.SkeletalMesh.md)

#### Overrides

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[Load](ue_ue.StreamableRenderAsset.md#load)

#### Defined in

[ue/ue.d.ts:4582](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4582)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[StreamableRenderAsset](ue_ue.StreamableRenderAsset.md).[StaticClass](ue_ue.StreamableRenderAsset.md#staticclass)

#### Defined in

[ue/ue.d.ts:4580](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4580)
