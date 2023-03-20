[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LandscapeSplineControlPoint

# Class: LandscapeSplineControlPoint

[ue/ue](../modules/ue_ue.md).LandscapeSplineControlPoint

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LandscapeSplineControlPoint`**

## Table of contents

### Constructors

- [constructor](ue_ue.LandscapeSplineControlPoint.md#constructor)

### Properties

- [BodyInstance](ue_ue.LandscapeSplineControlPoint.md#bodyinstance)
- [Bounds](ue_ue.LandscapeSplineControlPoint.md#bounds)
- [CollisionProfileName](ue_ue.LandscapeSplineControlPoint.md#collisionprofilename)
- [ConnectedSegments](ue_ue.LandscapeSplineControlPoint.md#connectedsegments)
- [EndFalloff](ue_ue.LandscapeSplineControlPoint.md#endfalloff)
- [ForeignWorld](ue_ue.LandscapeSplineControlPoint.md#foreignworld)
- [LDMaxDrawDistance](ue_ue.LandscapeSplineControlPoint.md#ldmaxdrawdistance)
- [LayerName](ue_ue.LandscapeSplineControlPoint.md#layername)
- [LayerWidthRatio](ue_ue.LandscapeSplineControlPoint.md#layerwidthratio)
- [LeftSideFalloffFactor](ue_ue.LandscapeSplineControlPoint.md#leftsidefallofffactor)
- [LeftSideLayerFalloffFactor](ue_ue.LandscapeSplineControlPoint.md#leftsidelayerfallofffactor)
- [LocalMeshComponent](ue_ue.LandscapeSplineControlPoint.md#localmeshcomponent)
- [Location](ue_ue.LandscapeSplineControlPoint.md#location)
- [MaterialOverrides](ue_ue.LandscapeSplineControlPoint.md#materialoverrides)
- [Mesh](ue_ue.LandscapeSplineControlPoint.md#mesh)
- [MeshScale](ue_ue.LandscapeSplineControlPoint.md#meshscale)
- [ModificationKey](ue_ue.LandscapeSplineControlPoint.md#modificationkey)
- [Points](ue_ue.LandscapeSplineControlPoint.md#points)
- [RightSideFalloffFactor](ue_ue.LandscapeSplineControlPoint.md#rightsidefallofffactor)
- [RightSideLayerFalloffFactor](ue_ue.LandscapeSplineControlPoint.md#rightsidelayerfallofffactor)
- [Rotation](ue_ue.LandscapeSplineControlPoint.md#rotation)
- [RuntimeVirtualTextures](ue_ue.LandscapeSplineControlPoint.md#runtimevirtualtextures)
- [SegmentMeshOffset](ue_ue.LandscapeSplineControlPoint.md#segmentmeshoffset)
- [SideFalloff](ue_ue.LandscapeSplineControlPoint.md#sidefalloff)
- [TranslucencySortPriority](ue_ue.LandscapeSplineControlPoint.md#translucencysortpriority)
- [VirtualTextureCullMips](ue_ue.LandscapeSplineControlPoint.md#virtualtexturecullmips)
- [VirtualTextureLodBias](ue_ue.LandscapeSplineControlPoint.md#virtualtexturelodbias)
- [VirtualTextureMainPassMaxDrawDistance](ue_ue.LandscapeSplineControlPoint.md#virtualtexturemainpassmaxdrawdistance)
- [VirtualTextureRenderPassType](ue_ue.LandscapeSplineControlPoint.md#virtualtexturerenderpasstype)
- [Width](ue_ue.LandscapeSplineControlPoint.md#width)
- [\_\_tid\_LandscapeSplineControlPoint\_\_](ue_ue.LandscapeSplineControlPoint.md#__tid_landscapesplinecontrolpoint__)
- [\_\_tid\_Object\_\_](ue_ue.LandscapeSplineControlPoint.md#__tid_object__)
- [bCastShadow](ue_ue.LandscapeSplineControlPoint.md#bcastshadow)
- [bEnableCollision](ue_ue.LandscapeSplineControlPoint.md#benablecollision)
- [bHiddenInGame](ue_ue.LandscapeSplineControlPoint.md#bhiddeningame)
- [bLowerTerrain](ue_ue.LandscapeSplineControlPoint.md#blowerterrain)
- [bNavDirty](ue_ue.LandscapeSplineControlPoint.md#bnavdirty)
- [bPlaceSplineMeshesInStreamingLevels](ue_ue.LandscapeSplineControlPoint.md#bplacesplinemeshesinstreaminglevels)
- [bRaiseTerrain](ue_ue.LandscapeSplineControlPoint.md#braiseterrain)
- [bSelected](ue_ue.LandscapeSplineControlPoint.md#bselected)

### Methods

- [CreateDefaultSubobject](ue_ue.LandscapeSplineControlPoint.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LandscapeSplineControlPoint.md#executeubergraph)
- [GetClass](ue_ue.LandscapeSplineControlPoint.md#getclass)
- [GetName](ue_ue.LandscapeSplineControlPoint.md#getname)
- [GetOuter](ue_ue.LandscapeSplineControlPoint.md#getouter)
- [GetWorld](ue_ue.LandscapeSplineControlPoint.md#getworld)
- [Find](ue_ue.LandscapeSplineControlPoint.md#find)
- [Load](ue_ue.LandscapeSplineControlPoint.md#load)
- [StaticClass](ue_ue.LandscapeSplineControlPoint.md#staticclass)

## Constructors

### constructor

• **new LandscapeSplineControlPoint**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

___

### Bounds

• **Bounds**: [`Box`](ue_ue.Box.md)

___

### CollisionProfileName

• **CollisionProfileName**: `string`

___

### ConnectedSegments

• **ConnectedSegments**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeSplineConnection`](ue_ue.LandscapeSplineConnection.md)\>

___

### EndFalloff

• **EndFalloff**: `number`

___

### ForeignWorld

• **ForeignWorld**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`World`](ue_ue.World.md)\>

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

___

### LayerName

• **LayerName**: `string`

___

### LayerWidthRatio

• **LayerWidthRatio**: `number`

___

### LeftSideFalloffFactor

• **LeftSideFalloffFactor**: `number`

___

### LeftSideLayerFalloffFactor

• **LeftSideLayerFalloffFactor**: `number`

___

### LocalMeshComponent

• **LocalMeshComponent**: [`ControlPointMeshComponent`](ue_ue.ControlPointMeshComponent.md)

___

### Location

• **Location**: [`Vector`](ue_ue_s.Vector.md)

___

### MaterialOverrides

• **MaterialOverrides**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

___

### Mesh

• **Mesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### MeshScale

• **MeshScale**: [`Vector`](ue_ue_s.Vector.md)

___

### ModificationKey

• **ModificationKey**: [`Guid`](ue_ue_s.Guid.md)

___

### Points

• **Points**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeSplineInterpPoint`](ue_ue.LandscapeSplineInterpPoint.md)\>

___

### RightSideFalloffFactor

• **RightSideFalloffFactor**: `number`

___

### RightSideLayerFalloffFactor

• **RightSideLayerFalloffFactor**: `number`

___

### Rotation

• **Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

___

### SegmentMeshOffset

• **SegmentMeshOffset**: `number`

___

### SideFalloff

• **SideFalloff**: `number`

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

___

### VirtualTextureMainPassMaxDrawDistance

• **VirtualTextureMainPassMaxDrawDistance**: `number`

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

___

### Width

• **Width**: `number`

___

### \_\_tid\_LandscapeSplineControlPoint\_\_

• **\_\_tid\_LandscapeSplineControlPoint\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bCastShadow

• **bCastShadow**: `boolean`

___

### bEnableCollision

• **bEnableCollision**: `boolean`

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

___

### bLowerTerrain

• **bLowerTerrain**: `boolean`

___

### bNavDirty

• **bNavDirty**: `boolean`

___

### bPlaceSplineMeshesInStreamingLevels

• **bPlaceSplineMeshesInStreamingLevels**: `boolean`

___

### bRaiseTerrain

• **bRaiseTerrain**: `boolean`

___

### bSelected

• **bSelected**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LandscapeSplineControlPoint`](ue_ue.LandscapeSplineControlPoint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LandscapeSplineControlPoint`](ue_ue.LandscapeSplineControlPoint.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LandscapeSplineControlPoint`](ue_ue.LandscapeSplineControlPoint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LandscapeSplineControlPoint`](ue_ue.LandscapeSplineControlPoint.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
