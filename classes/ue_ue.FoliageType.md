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

#### Defined in

[ue/ue.d.ts:35904](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35904)

## Properties

### AlignMaxAngle

• **AlignMaxAngle**: `number`

#### Defined in

[ue/ue.d.ts:35921](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35921)

___

### AlignToNormal

• **AlignToNormal**: `boolean`

#### Defined in

[ue/ue.d.ts:35920](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35920)

___

### AverageSpreadDistance

• **AverageSpreadDistance**: `number`

#### Defined in

[ue/ue.d.ts:35961](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35961)

___

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Defined in

[ue/ue.d.ts:35949](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35949)

___

### CastShadow

• **CastShadow**: `boolean`

#### Defined in

[ue/ue.d.ts:35938](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35938)

___

### ChangeCount

• **ChangeCount**: `number`

#### Defined in

[ue/ue.d.ts:35973](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35973)

___

### CollisionRadius

• **CollisionRadius**: `number`

#### Defined in

[ue/ue.d.ts:35957](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35957)

___

### CollisionScale

• **CollisionScale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:35932](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35932)

___

### CollisionWithWorld

• **CollisionWithWorld**: `boolean`

#### Defined in

[ue/ue.d.ts:35931](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35931)

___

### CullDistance

• **CullDistance**: [`Int32Interval`](ue_ue.Int32Interval.md)

#### Defined in

[ue/ue.d.ts:35936](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35936)

___

### CustomDepthStencilValue

• **CustomDepthStencilValue**: `number`

#### Defined in

[ue/ue.d.ts:35953](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35953)

___

### CustomNavigableGeometry

• **CustomNavigableGeometry**: [`EHasCustomNavigableGeometry`](../enums/ue_ue.EHasCustomNavigableGeometry.md)

#### Defined in

[ue/ue.d.ts:35950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35950)

___

### Density

• **Density**: `number`

#### Defined in

[ue/ue.d.ts:35906](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35906)

___

### DensityAdjustmentFactor

• **DensityAdjustmentFactor**: `number`

#### Defined in

[ue/ue.d.ts:35907](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35907)

___

### DistributionSeed

• **DistributionSeed**: `number`

#### Defined in

[ue/ue.d.ts:35964](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35964)

___

### EndCullDistance

• **EndCullDistance**: `number`

#### Defined in

[ue/ue.d.ts:36004](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36004)

___

### ExclusionLandscapeLayers

• **ExclusionLandscapeLayers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:35928](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35928)

___

### GroundSlope

• **GroundSlope**: `number`

#### Defined in

[ue/ue.d.ts:36009](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36009)

___

### GroundSlopeAngle

• **GroundSlopeAngle**: [`FloatInterval`](ue_ue.FloatInterval.md)

#### Defined in

[ue/ue.d.ts:35924](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35924)

___

### Height

• **Height**: [`FloatInterval`](ue_ue.FloatInterval.md)

#### Defined in

[ue/ue.d.ts:35925](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35925)

___

### HeightMax

• **HeightMax**: `number`

#### Defined in

[ue/ue.d.ts:36000](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36000)

___

### HeightMin

• **HeightMin**: `number`

#### Defined in

[ue/ue.d.ts:35999](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35999)

___

### HiddenEditorViews

• **HiddenEditorViews**: `bigint`

#### Defined in

[ue/ue.d.ts:35955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35955)

___

### InitialSeedDensity

• **InitialSeedDensity**: `number`

#### Defined in

[ue/ue.d.ts:35960](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35960)

___

### IsSelected

• **IsSelected**: `boolean`

#### Defined in

[ue/ue.d.ts:35956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35956)

___

### LandscapeLayer

• **LandscapeLayer**: `string`

#### Defined in

[ue/ue.d.ts:35930](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35930)

___

### LandscapeLayers

• **LandscapeLayers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:35926](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35926)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Defined in

[ue/ue.d.ts:35951](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35951)

___

### LightmapType

• **LightmapType**: [`ELightmapType`](../enums/ue_ue.ELightmapType.md)

#### Defined in

[ue/ue.d.ts:35947](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35947)

___

### LockScaleX

• **LockScaleX**: `boolean`

#### Defined in

[ue/ue.d.ts:36006](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36006)

___

### LockScaleY

• **LockScaleY**: `boolean`

#### Defined in

[ue/ue.d.ts:36007](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36007)

___

### LockScaleZ

• **LockScaleZ**: `boolean`

#### Defined in

[ue/ue.d.ts:36008](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36008)

___

### LowBoundOriginRadius

• **LowBoundOriginRadius**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:35934](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35934)

___

### MaxAge

• **MaxAge**: `number`

#### Defined in

[ue/ue.d.ts:35969](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35969)

___

### MaxInitialAge

• **MaxInitialAge**: `number`

#### Defined in

[ue/ue.d.ts:35968](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35968)

___

### MaxInitialSeedOffset

• **MaxInitialSeedOffset**: `number`

#### Defined in

[ue/ue.d.ts:35965](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35965)

___

### MaxScale

• **MaxScale**: `number`

#### Defined in

[ue/ue.d.ts:36012](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36012)

___

### MeshBounds

• **MeshBounds**: [`BoxSphereBounds`](ue_ue.BoxSphereBounds.md)

#### Defined in

[ue/ue.d.ts:35933](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35933)

___

### MinGroundSlope

• **MinGroundSlope**: `number`

#### Defined in

[ue/ue.d.ts:36010](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36010)

___

### MinScale

• **MinScale**: `number`

#### Defined in

[ue/ue.d.ts:36011](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36011)

___

### MinimumExclusionLayerWeight

• **MinimumExclusionLayerWeight**: `number`

#### Defined in

[ue/ue.d.ts:35929](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35929)

___

### MinimumLayerWeight

• **MinimumLayerWeight**: `number`

#### Defined in

[ue/ue.d.ts:35927](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35927)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Defined in

[ue/ue.d.ts:35935](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35935)

___

### NumSteps

• **NumSteps**: `number`

#### Defined in

[ue/ue.d.ts:35959](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35959)

___

### OverlapPriority

• **OverlapPriority**: `number`

#### Defined in

[ue/ue.d.ts:35970](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35970)

___

### OverriddenLightMapRes

• **OverriddenLightMapRes**: `number`

#### Defined in

[ue/ue.d.ts:35946](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35946)

___

### ProceduralScale

• **ProceduralScale**: [`FloatInterval`](ue_ue.FloatInterval.md)

#### Defined in

[ue/ue.d.ts:35971](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35971)

___

### Radius

• **Radius**: `number`

#### Defined in

[ue/ue.d.ts:35908](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35908)

___

### RandomPitchAngle

• **RandomPitchAngle**: `number`

#### Defined in

[ue/ue.d.ts:35923](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35923)

___

### RandomYaw

• **RandomYaw**: `boolean`

#### Defined in

[ue/ue.d.ts:35922](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35922)

___

### ReapplyAlignToNormal

• **ReapplyAlignToNormal**: `boolean`

#### Defined in

[ue/ue.d.ts:35976](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35976)

___

### ReapplyCollisionWithWorld

• **ReapplyCollisionWithWorld**: `boolean`

#### Defined in

[ue/ue.d.ts:35987](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35987)

___

### ReapplyDensity

• **ReapplyDensity**: `boolean`

#### Defined in

[ue/ue.d.ts:35974](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35974)

___

### ReapplyGroundSlope

• **ReapplyGroundSlope**: `boolean`

#### Defined in

[ue/ue.d.ts:35983](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35983)

___

### ReapplyHeight

• **ReapplyHeight**: `boolean`

#### Defined in

[ue/ue.d.ts:35984](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35984)

___

### ReapplyLandscapeLayers

• **ReapplyLandscapeLayers**: `boolean`

#### Defined in

[ue/ue.d.ts:35985](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35985)

___

### ReapplyRadius

• **ReapplyRadius**: `boolean`

#### Defined in

[ue/ue.d.ts:35975](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35975)

___

### ReapplyRandomPitchAngle

• **ReapplyRandomPitchAngle**: `boolean`

#### Defined in

[ue/ue.d.ts:35982](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35982)

___

### ReapplyRandomYaw

• **ReapplyRandomYaw**: `boolean`

#### Defined in

[ue/ue.d.ts:35977](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35977)

___

### ReapplyScaleX

• **ReapplyScaleX**: `boolean`

#### Defined in

[ue/ue.d.ts:35979](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35979)

___

### ReapplyScaleY

• **ReapplyScaleY**: `boolean`

#### Defined in

[ue/ue.d.ts:35980](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35980)

___

### ReapplyScaleZ

• **ReapplyScaleZ**: `boolean`

#### Defined in

[ue/ue.d.ts:35981](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35981)

___

### ReapplyScaling

• **ReapplyScaling**: `boolean`

#### Defined in

[ue/ue.d.ts:35978](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35978)

___

### ReapplyVertexColorMask

• **ReapplyVertexColorMask**: `boolean`

#### Defined in

[ue/ue.d.ts:35988](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35988)

___

### ReapplyZOffset

• **ReapplyZOffset**: `boolean`

#### Defined in

[ue/ue.d.ts:35986](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35986)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Defined in

[ue/ue.d.ts:35990](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35990)

___

### ScaleCurve

• **ScaleCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

#### Defined in

[ue/ue.d.ts:35972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35972)

___

### ScaleMaxX

• **ScaleMaxX**: `number`

#### Defined in

[ue/ue.d.ts:35996](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35996)

___

### ScaleMaxY

• **ScaleMaxY**: `number`

#### Defined in

[ue/ue.d.ts:35997](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35997)

___

### ScaleMaxZ

• **ScaleMaxZ**: `number`

#### Defined in

[ue/ue.d.ts:35998](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35998)

___

### ScaleMinX

• **ScaleMinX**: `number`

#### Defined in

[ue/ue.d.ts:35993](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35993)

___

### ScaleMinY

• **ScaleMinY**: `number`

#### Defined in

[ue/ue.d.ts:35994](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35994)

___

### ScaleMinZ

• **ScaleMinZ**: `number`

#### Defined in

[ue/ue.d.ts:35995](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35995)

___

### ScaleX

• **ScaleX**: [`FloatInterval`](ue_ue.FloatInterval.md)

#### Defined in

[ue/ue.d.ts:35912](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35912)

___

### ScaleY

• **ScaleY**: [`FloatInterval`](ue_ue.FloatInterval.md)

#### Defined in

[ue/ue.d.ts:35913](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35913)

___

### ScaleZ

• **ScaleZ**: [`FloatInterval`](ue_ue.FloatInterval.md)

#### Defined in

[ue/ue.d.ts:35914](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35914)

___

### Scaling

• **Scaling**: [`EFoliageScaling`](../enums/ue_ue.EFoliageScaling.md)

#### Defined in

[ue/ue.d.ts:35911](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35911)

___

### SeedsPerStep

• **SeedsPerStep**: `number`

#### Defined in

[ue/ue.d.ts:35963](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35963)

___

### ShadeRadius

• **ShadeRadius**: `number`

#### Defined in

[ue/ue.d.ts:35958](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35958)

___

### SingleInstanceModeRadius

• **SingleInstanceModeRadius**: `number`

#### Defined in

[ue/ue.d.ts:35910](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35910)

___

### SpreadVariance

• **SpreadVariance**: `number`

#### Defined in

[ue/ue.d.ts:35962](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35962)

___

### StartCullDistance

• **StartCullDistance**: `number`

#### Defined in

[ue/ue.d.ts:36003](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36003)

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Defined in

[ue/ue.d.ts:35954](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35954)

___

### UniformScale

• **UniformScale**: `boolean`

#### Defined in

[ue/ue.d.ts:36005](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36005)

___

### UpdateGuid

• **UpdateGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:35905](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35905)

___

### VertexColorMask

• **VertexColorMask**: [`FoliageVertexColorMask`](../enums/ue_ue.FoliageVertexColorMask.md)

#### Defined in

[ue/ue.d.ts:35916](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35916)

___

### VertexColorMaskByChannel

• **VertexColorMaskByChannel**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`FoliageVertexColorChannelMask`](ue_ue.FoliageVertexColorChannelMask.md)\>

#### Defined in

[ue/ue.d.ts:35915](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35915)

___

### VertexColorMaskInvert

• **VertexColorMaskInvert**: `boolean`

#### Defined in

[ue/ue.d.ts:35918](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35918)

___

### VertexColorMaskThreshold

• **VertexColorMaskThreshold**: `number`

#### Defined in

[ue/ue.d.ts:35917](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35917)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Defined in

[ue/ue.d.ts:35991](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35991)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Defined in

[ue/ue.d.ts:35992](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35992)

___

### ZOffset

• **ZOffset**: [`FloatInterval`](ue_ue.FloatInterval.md)

#### Defined in

[ue/ue.d.ts:35919](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35919)

___

### ZOffsetMax

• **ZOffsetMax**: `number`

#### Defined in

[ue/ue.d.ts:36002](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36002)

___

### ZOffsetMin

• **ZOffsetMin**: `number`

#### Defined in

[ue/ue.d.ts:36001](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36001)

___

### \_\_tid\_FoliageType\_\_

• **\_\_tid\_FoliageType\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:36017](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36017)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bAffectDistanceFieldLighting

• **bAffectDistanceFieldLighting**: `boolean`

#### Defined in

[ue/ue.d.ts:35940](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35940)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Defined in

[ue/ue.d.ts:35939](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35939)

___

### bCanGrowInShade

• **bCanGrowInShade**: `boolean`

#### Defined in

[ue/ue.d.ts:35966](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35966)

___

### bCastDynamicShadow

• **bCastDynamicShadow**: `boolean`

#### Defined in

[ue/ue.d.ts:35941](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35941)

___

### bCastShadowAsTwoSided

• **bCastShadowAsTwoSided**: `boolean`

#### Defined in

[ue/ue.d.ts:35943](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35943)

___

### bCastStaticShadow

• **bCastStaticShadow**: `boolean`

#### Defined in

[ue/ue.d.ts:35942](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35942)

___

### bEnableDensityScaling

• **bEnableDensityScaling**: `boolean`

#### Defined in

[ue/ue.d.ts:35989](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35989)

___

### bEnableStaticLighting

• **bEnableStaticLighting**: `boolean`

#### Defined in

[ue/ue.d.ts:35937](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35937)

___

### bOverrideLightMapRes

• **bOverrideLightMapRes**: `boolean`

#### Defined in

[ue/ue.d.ts:35945](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35945)

___

### bReceivesDecals

• **bReceivesDecals**: `boolean`

#### Defined in

[ue/ue.d.ts:35944](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35944)

___

### bRenderCustomDepth

• **bRenderCustomDepth**: `boolean`

#### Defined in

[ue/ue.d.ts:35952](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35952)

___

### bSingleInstanceModeOverrideRadius

• **bSingleInstanceModeOverrideRadius**: `boolean`

#### Defined in

[ue/ue.d.ts:35909](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35909)

___

### bSpawnsInShade

• **bSpawnsInShade**: `boolean`

#### Defined in

[ue/ue.d.ts:35967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35967)

___

### bUseAsOccluder

• **bUseAsOccluder**: `boolean`

#### Defined in

[ue/ue.d.ts:35948](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L35948)

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

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:36014](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36014)

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

#### Defined in

[ue/ue.d.ts:36015](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36015)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:36013](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L36013)
