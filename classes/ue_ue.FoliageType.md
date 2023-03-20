[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FoliageType

# Class: FoliageType

[ue/ue](../modules/ue_ue.md).FoliageType

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`FoliageType`**

  ↳↳ [`FoliageType_Actor`](ue_ue.FoliageType_Actor.md)

  ↳↳ [`FoliageType_InstancedStaticMesh`](ue_ue.FoliageType_InstancedStaticMesh.md)

## Table of contents

### Constructors

- [constructor](ue_ue.FoliageType.md#constructor)

### Properties

- [AlignMaxAngle](ue_ue.FoliageType.md#alignmaxangle)
- [AlignToNormal](ue_ue.FoliageType.md#aligntonormal)
- [AverageSpreadDistance](ue_ue.FoliageType.md#averagespreaddistance)
- [BodyInstance](ue_ue.FoliageType.md#bodyinstance)
- [CastShadow](ue_ue.FoliageType.md#castshadow)
- [ChangeCount](ue_ue.FoliageType.md#changecount)
- [CollisionRadius](ue_ue.FoliageType.md#collisionradius)
- [CollisionScale](ue_ue.FoliageType.md#collisionscale)
- [CollisionWithWorld](ue_ue.FoliageType.md#collisionwithworld)
- [CullDistance](ue_ue.FoliageType.md#culldistance)
- [CustomDepthStencilValue](ue_ue.FoliageType.md#customdepthstencilvalue)
- [CustomNavigableGeometry](ue_ue.FoliageType.md#customnavigablegeometry)
- [Density](ue_ue.FoliageType.md#density)
- [DensityAdjustmentFactor](ue_ue.FoliageType.md#densityadjustmentfactor)
- [DistributionSeed](ue_ue.FoliageType.md#distributionseed)
- [EndCullDistance](ue_ue.FoliageType.md#endculldistance)
- [ExclusionLandscapeLayers](ue_ue.FoliageType.md#exclusionlandscapelayers)
- [GroundSlope](ue_ue.FoliageType.md#groundslope)
- [GroundSlopeAngle](ue_ue.FoliageType.md#groundslopeangle)
- [Height](ue_ue.FoliageType.md#height)
- [HeightMax](ue_ue.FoliageType.md#heightmax)
- [HeightMin](ue_ue.FoliageType.md#heightmin)
- [HiddenEditorViews](ue_ue.FoliageType.md#hiddeneditorviews)
- [InitialSeedDensity](ue_ue.FoliageType.md#initialseeddensity)
- [IsSelected](ue_ue.FoliageType.md#isselected)
- [LandscapeLayer](ue_ue.FoliageType.md#landscapelayer)
- [LandscapeLayers](ue_ue.FoliageType.md#landscapelayers)
- [LightingChannels](ue_ue.FoliageType.md#lightingchannels)
- [LightmapType](ue_ue.FoliageType.md#lightmaptype)
- [LockScaleX](ue_ue.FoliageType.md#lockscalex)
- [LockScaleY](ue_ue.FoliageType.md#lockscaley)
- [LockScaleZ](ue_ue.FoliageType.md#lockscalez)
- [LowBoundOriginRadius](ue_ue.FoliageType.md#lowboundoriginradius)
- [MaxAge](ue_ue.FoliageType.md#maxage)
- [MaxInitialAge](ue_ue.FoliageType.md#maxinitialage)
- [MaxInitialSeedOffset](ue_ue.FoliageType.md#maxinitialseedoffset)
- [MaxScale](ue_ue.FoliageType.md#maxscale)
- [MeshBounds](ue_ue.FoliageType.md#meshbounds)
- [MinGroundSlope](ue_ue.FoliageType.md#mingroundslope)
- [MinScale](ue_ue.FoliageType.md#minscale)
- [MinimumExclusionLayerWeight](ue_ue.FoliageType.md#minimumexclusionlayerweight)
- [MinimumLayerWeight](ue_ue.FoliageType.md#minimumlayerweight)
- [Mobility](ue_ue.FoliageType.md#mobility)
- [NumSteps](ue_ue.FoliageType.md#numsteps)
- [OverlapPriority](ue_ue.FoliageType.md#overlappriority)
- [OverriddenLightMapRes](ue_ue.FoliageType.md#overriddenlightmapres)
- [ProceduralScale](ue_ue.FoliageType.md#proceduralscale)
- [Radius](ue_ue.FoliageType.md#radius)
- [RandomPitchAngle](ue_ue.FoliageType.md#randompitchangle)
- [RandomYaw](ue_ue.FoliageType.md#randomyaw)
- [ReapplyAlignToNormal](ue_ue.FoliageType.md#reapplyaligntonormal)
- [ReapplyCollisionWithWorld](ue_ue.FoliageType.md#reapplycollisionwithworld)
- [ReapplyDensity](ue_ue.FoliageType.md#reapplydensity)
- [ReapplyGroundSlope](ue_ue.FoliageType.md#reapplygroundslope)
- [ReapplyHeight](ue_ue.FoliageType.md#reapplyheight)
- [ReapplyLandscapeLayers](ue_ue.FoliageType.md#reapplylandscapelayers)
- [ReapplyRadius](ue_ue.FoliageType.md#reapplyradius)
- [ReapplyRandomPitchAngle](ue_ue.FoliageType.md#reapplyrandompitchangle)
- [ReapplyRandomYaw](ue_ue.FoliageType.md#reapplyrandomyaw)
- [ReapplyScaleX](ue_ue.FoliageType.md#reapplyscalex)
- [ReapplyScaleY](ue_ue.FoliageType.md#reapplyscaley)
- [ReapplyScaleZ](ue_ue.FoliageType.md#reapplyscalez)
- [ReapplyScaling](ue_ue.FoliageType.md#reapplyscaling)
- [ReapplyVertexColorMask](ue_ue.FoliageType.md#reapplyvertexcolormask)
- [ReapplyZOffset](ue_ue.FoliageType.md#reapplyzoffset)
- [RuntimeVirtualTextures](ue_ue.FoliageType.md#runtimevirtualtextures)
- [ScaleCurve](ue_ue.FoliageType.md#scalecurve)
- [ScaleMaxX](ue_ue.FoliageType.md#scalemaxx)
- [ScaleMaxY](ue_ue.FoliageType.md#scalemaxy)
- [ScaleMaxZ](ue_ue.FoliageType.md#scalemaxz)
- [ScaleMinX](ue_ue.FoliageType.md#scaleminx)
- [ScaleMinY](ue_ue.FoliageType.md#scaleminy)
- [ScaleMinZ](ue_ue.FoliageType.md#scaleminz)
- [ScaleX](ue_ue.FoliageType.md#scalex)
- [ScaleY](ue_ue.FoliageType.md#scaley)
- [ScaleZ](ue_ue.FoliageType.md#scalez)
- [Scaling](ue_ue.FoliageType.md#scaling)
- [SeedsPerStep](ue_ue.FoliageType.md#seedsperstep)
- [ShadeRadius](ue_ue.FoliageType.md#shaderadius)
- [SingleInstanceModeRadius](ue_ue.FoliageType.md#singleinstancemoderadius)
- [SpreadVariance](ue_ue.FoliageType.md#spreadvariance)
- [StartCullDistance](ue_ue.FoliageType.md#startculldistance)
- [TranslucencySortPriority](ue_ue.FoliageType.md#translucencysortpriority)
- [UniformScale](ue_ue.FoliageType.md#uniformscale)
- [UpdateGuid](ue_ue.FoliageType.md#updateguid)
- [VertexColorMask](ue_ue.FoliageType.md#vertexcolormask)
- [VertexColorMaskByChannel](ue_ue.FoliageType.md#vertexcolormaskbychannel)
- [VertexColorMaskInvert](ue_ue.FoliageType.md#vertexcolormaskinvert)
- [VertexColorMaskThreshold](ue_ue.FoliageType.md#vertexcolormaskthreshold)
- [VirtualTextureCullMips](ue_ue.FoliageType.md#virtualtexturecullmips)
- [VirtualTextureRenderPassType](ue_ue.FoliageType.md#virtualtexturerenderpasstype)
- [ZOffset](ue_ue.FoliageType.md#zoffset)
- [ZOffsetMax](ue_ue.FoliageType.md#zoffsetmax)
- [ZOffsetMin](ue_ue.FoliageType.md#zoffsetmin)
- [\_\_tid\_FoliageType\_\_](ue_ue.FoliageType.md#__tid_foliagetype__)
- [\_\_tid\_Object\_\_](ue_ue.FoliageType.md#__tid_object__)
- [bAffectDistanceFieldLighting](ue_ue.FoliageType.md#baffectdistancefieldlighting)
- [bAffectDynamicIndirectLighting](ue_ue.FoliageType.md#baffectdynamicindirectlighting)
- [bCanGrowInShade](ue_ue.FoliageType.md#bcangrowinshade)
- [bCastDynamicShadow](ue_ue.FoliageType.md#bcastdynamicshadow)
- [bCastShadowAsTwoSided](ue_ue.FoliageType.md#bcastshadowastwosided)
- [bCastStaticShadow](ue_ue.FoliageType.md#bcaststaticshadow)
- [bEnableDensityScaling](ue_ue.FoliageType.md#benabledensityscaling)
- [bEnableStaticLighting](ue_ue.FoliageType.md#benablestaticlighting)
- [bOverrideLightMapRes](ue_ue.FoliageType.md#boverridelightmapres)
- [bReceivesDecals](ue_ue.FoliageType.md#breceivesdecals)
- [bRenderCustomDepth](ue_ue.FoliageType.md#brendercustomdepth)
- [bSingleInstanceModeOverrideRadius](ue_ue.FoliageType.md#bsingleinstancemodeoverrideradius)
- [bSpawnsInShade](ue_ue.FoliageType.md#bspawnsinshade)
- [bUseAsOccluder](ue_ue.FoliageType.md#buseasoccluder)

### Methods

- [CreateDefaultSubobject](ue_ue.FoliageType.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FoliageType.md#executeubergraph)
- [GetClass](ue_ue.FoliageType.md#getclass)
- [GetName](ue_ue.FoliageType.md#getname)
- [GetOuter](ue_ue.FoliageType.md#getouter)
- [GetWorld](ue_ue.FoliageType.md#getworld)
- [Find](ue_ue.FoliageType.md#find)
- [Load](ue_ue.FoliageType.md#load)
- [StaticClass](ue_ue.FoliageType.md#staticclass)

## Constructors

### constructor

• **new FoliageType**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AlignMaxAngle

• **AlignMaxAngle**: `number`

___

### AlignToNormal

• **AlignToNormal**: `boolean`

___

### AverageSpreadDistance

• **AverageSpreadDistance**: `number`

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

___

### CastShadow

• **CastShadow**: `boolean`

___

### ChangeCount

• **ChangeCount**: `number`

___

### CollisionRadius

• **CollisionRadius**: `number`

___

### CollisionScale

• **CollisionScale**: [`Vector`](ue_ue_s.Vector.md)

___

### CollisionWithWorld

• **CollisionWithWorld**: `boolean`

___

### CullDistance

• **CullDistance**: [`Int32Interval`](ue_ue.Int32Interval.md)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

___

### CustomNavigableGeometry

• **CustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

___

### Density

• **Density**: `number`

___

### DensityAdjustmentFactor

• **DensityAdjustmentFactor**: `number`

___

### DistributionSeed

• **DistributionSeed**: `number`

___

### EndCullDistance

• **EndCullDistance**: `number`

___

### ExclusionLandscapeLayers

• **ExclusionLandscapeLayers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### GroundSlope

• **GroundSlope**: `number`

___

### GroundSlopeAngle

• **GroundSlopeAngle**: [`FloatInterval`](ue_ue.FloatInterval.md)

___

### Height

• **Height**: [`FloatInterval`](ue_ue.FloatInterval.md)

___

### HeightMax

• **HeightMax**: `number`

___

### HeightMin

• **HeightMin**: `number`

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

___

### InitialSeedDensity

• **InitialSeedDensity**: `number`

___

### IsSelected

• **IsSelected**: `boolean`

___

### LandscapeLayer

• **LandscapeLayer**: `string`

___

### LandscapeLayers

• **LandscapeLayers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

___

### LockScaleX

• **LockScaleX**: `boolean`

___

### LockScaleY

• **LockScaleY**: `boolean`

___

### LockScaleZ

• **LockScaleZ**: `boolean`

___

### LowBoundOriginRadius

• **LowBoundOriginRadius**: [`Vector`](ue_ue_s.Vector.md)

___

### MaxAge

• **MaxAge**: `number`

___

### MaxInitialAge

• **MaxInitialAge**: `number`

___

### MaxInitialSeedOffset

• **MaxInitialSeedOffset**: `number`

___

### MaxScale

• **MaxScale**: `number`

___

### MeshBounds

• **MeshBounds**: [`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

___

### MinGroundSlope

• **MinGroundSlope**: `number`

___

### MinScale

• **MinScale**: `number`

___

### MinimumExclusionLayerWeight

• **MinimumExclusionLayerWeight**: `number`

___

### MinimumLayerWeight

• **MinimumLayerWeight**: `number`

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

___

### NumSteps

• **NumSteps**: `number`

___

### OverlapPriority

• **OverlapPriority**: `number`

___

### OverriddenLightMapRes

• **OverriddenLightMapRes**: `number`

___

### ProceduralScale

• **ProceduralScale**: [`FloatInterval`](ue_ue.FloatInterval.md)

___

### Radius

• **Radius**: `number`

___

### RandomPitchAngle

• **RandomPitchAngle**: `number`

___

### RandomYaw

• **RandomYaw**: `boolean`

___

### ReapplyAlignToNormal

• **ReapplyAlignToNormal**: `boolean`

___

### ReapplyCollisionWithWorld

• **ReapplyCollisionWithWorld**: `boolean`

___

### ReapplyDensity

• **ReapplyDensity**: `boolean`

___

### ReapplyGroundSlope

• **ReapplyGroundSlope**: `boolean`

___

### ReapplyHeight

• **ReapplyHeight**: `boolean`

___

### ReapplyLandscapeLayers

• **ReapplyLandscapeLayers**: `boolean`

___

### ReapplyRadius

• **ReapplyRadius**: `boolean`

___

### ReapplyRandomPitchAngle

• **ReapplyRandomPitchAngle**: `boolean`

___

### ReapplyRandomYaw

• **ReapplyRandomYaw**: `boolean`

___

### ReapplyScaleX

• **ReapplyScaleX**: `boolean`

___

### ReapplyScaleY

• **ReapplyScaleY**: `boolean`

___

### ReapplyScaleZ

• **ReapplyScaleZ**: `boolean`

___

### ReapplyScaling

• **ReapplyScaling**: `boolean`

___

### ReapplyVertexColorMask

• **ReapplyVertexColorMask**: `boolean`

___

### ReapplyZOffset

• **ReapplyZOffset**: `boolean`

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

___

### ScaleCurve

• **ScaleCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

___

### ScaleMaxX

• **ScaleMaxX**: `number`

___

### ScaleMaxY

• **ScaleMaxY**: `number`

___

### ScaleMaxZ

• **ScaleMaxZ**: `number`

___

### ScaleMinX

• **ScaleMinX**: `number`

___

### ScaleMinY

• **ScaleMinY**: `number`

___

### ScaleMinZ

• **ScaleMinZ**: `number`

___

### ScaleX

• **ScaleX**: [`FloatInterval`](ue_ue.FloatInterval.md)

___

### ScaleY

• **ScaleY**: [`FloatInterval`](ue_ue.FloatInterval.md)

___

### ScaleZ

• **ScaleZ**: [`FloatInterval`](ue_ue.FloatInterval.md)

___

### Scaling

• **Scaling**: [`EFoliageScaling`](../enums/ue_ue.EFoliageScaling.md)

___

### SeedsPerStep

• **SeedsPerStep**: `number`

___

### ShadeRadius

• **ShadeRadius**: `number`

___

### SingleInstanceModeRadius

• **SingleInstanceModeRadius**: `number`

___

### SpreadVariance

• **SpreadVariance**: `number`

___

### StartCullDistance

• **StartCullDistance**: `number`

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

___

### UniformScale

• **UniformScale**: `boolean`

___

### UpdateGuid

• **UpdateGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### VertexColorMask

• **VertexColorMask**: [`FoliageVertexColorMask`](../enums/ue_ue.FoliageVertexColorMask.md)

___

### VertexColorMaskByChannel

• **VertexColorMaskByChannel**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`FoliageVertexColorChannelMask`](ue_ue.FoliageVertexColorChannelMask.md)\>

___

### VertexColorMaskInvert

• **VertexColorMaskInvert**: `boolean`

___

### VertexColorMaskThreshold

• **VertexColorMaskThreshold**: `number`

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

___

### ZOffset

• **ZOffset**: [`FloatInterval`](ue_ue.FloatInterval.md)

___

### ZOffsetMax

• **ZOffsetMax**: `number`

___

### ZOffsetMin

• **ZOffsetMin**: `number`

___

### \_\_tid\_FoliageType\_\_

• **\_\_tid\_FoliageType\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

___

### bCanGrowInShade

• **bCanGrowInShade**: `boolean`

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

___

### bEnableDensityScaling

• **bEnableDensityScaling**: `boolean`

___

### bEnableStaticLighting

• **bEnableStaticLighting**: `boolean`

___

### bOverrideLightMapRes

• **bOverrideLightMapRes**: `boolean`

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

___

### bSingleInstanceModeOverrideRadius

• **bSingleInstanceModeOverrideRadius**: `boolean`

___

### bSpawnsInShade

• **bSpawnsInShade**: `boolean`

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

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

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FoliageType`](ue_ue.FoliageType.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FoliageType`](ue_ue.FoliageType.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`FoliageType`](ue_ue.FoliageType.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FoliageType`](ue_ue.FoliageType.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
