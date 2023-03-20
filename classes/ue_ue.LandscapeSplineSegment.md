[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LandscapeSplineSegment

# Class: LandscapeSplineSegment

[ue/ue](../modules/ue_ue.md).LandscapeSplineSegment

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LandscapeSplineSegment`**

## Table of contents

### Constructors

- [constructor](ue_ue.LandscapeSplineSegment.md#constructor)

### Properties

- [BodyInstance](ue_ue.LandscapeSplineSegment.md#bodyinstance)
- [Bounds](ue_ue.LandscapeSplineSegment.md#bounds)
- [CollisionProfileName](ue_ue.LandscapeSplineSegment.md#collisionprofilename)
- [Connections](ue_ue.LandscapeSplineSegment.md#connections)
- [ForeignWorlds](ue_ue.LandscapeSplineSegment.md#foreignworlds)
- [LDMaxDrawDistance](ue_ue.LandscapeSplineSegment.md#ldmaxdrawdistance)
- [LayerName](ue_ue.LandscapeSplineSegment.md#layername)
- [LocalMeshComponents](ue_ue.LandscapeSplineSegment.md#localmeshcomponents)
- [ModificationKey](ue_ue.LandscapeSplineSegment.md#modificationkey)
- [Points](ue_ue.LandscapeSplineSegment.md#points)
- [RandomSeed](ue_ue.LandscapeSplineSegment.md#randomseed)
- [RuntimeVirtualTextures](ue_ue.LandscapeSplineSegment.md#runtimevirtualtextures)
- [SplineInfo](ue_ue.LandscapeSplineSegment.md#splineinfo)
- [SplineMeshes](ue_ue.LandscapeSplineSegment.md#splinemeshes)
- [TranslucencySortPriority](ue_ue.LandscapeSplineSegment.md#translucencysortpriority)
- [VirtualTextureCullMips](ue_ue.LandscapeSplineSegment.md#virtualtexturecullmips)
- [VirtualTextureLodBias](ue_ue.LandscapeSplineSegment.md#virtualtexturelodbias)
- [VirtualTextureMainPassMaxDrawDistance](ue_ue.LandscapeSplineSegment.md#virtualtexturemainpassmaxdrawdistance)
- [VirtualTextureRenderPassType](ue_ue.LandscapeSplineSegment.md#virtualtexturerenderpasstype)
- [\_\_tid\_LandscapeSplineSegment\_\_](ue_ue.LandscapeSplineSegment.md#__tid_landscapesplinesegment__)
- [\_\_tid\_Object\_\_](ue_ue.LandscapeSplineSegment.md#__tid_object__)
- [bCastShadow](ue_ue.LandscapeSplineSegment.md#bcastshadow)
- [bEnableCollision](ue_ue.LandscapeSplineSegment.md#benablecollision)
- [bHiddenInGame](ue_ue.LandscapeSplineSegment.md#bhiddeningame)
- [bLowerTerrain](ue_ue.LandscapeSplineSegment.md#blowerterrain)
- [bNavDirty](ue_ue.LandscapeSplineSegment.md#bnavdirty)
- [bPlaceSplineMeshesInStreamingLevels](ue_ue.LandscapeSplineSegment.md#bplacesplinemeshesinstreaminglevels)
- [bRaiseTerrain](ue_ue.LandscapeSplineSegment.md#braiseterrain)
- [bSelected](ue_ue.LandscapeSplineSegment.md#bselected)

### Methods

- [CreateDefaultSubobject](ue_ue.LandscapeSplineSegment.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LandscapeSplineSegment.md#executeubergraph)
- [GetClass](ue_ue.LandscapeSplineSegment.md#getclass)
- [GetName](ue_ue.LandscapeSplineSegment.md#getname)
- [GetOuter](ue_ue.LandscapeSplineSegment.md#getouter)
- [GetWorld](ue_ue.LandscapeSplineSegment.md#getworld)
- [Find](ue_ue.LandscapeSplineSegment.md#find)
- [Load](ue_ue.LandscapeSplineSegment.md#load)
- [StaticClass](ue_ue.LandscapeSplineSegment.md#staticclass)

## Constructors

### constructor

• **new LandscapeSplineSegment**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### Connections

• **Connections**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`LandscapeSplineSegmentConnection`](ue_ue.LandscapeSplineSegmentConnection.md)\>

___

### ForeignWorlds

• **ForeignWorlds**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`World`](ue_ue.World.md)\>\>

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

___

### LayerName

• **LayerName**: `string`

___

### LocalMeshComponents

• **LocalMeshComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SplineMeshComponent`](ue_ue.SplineMeshComponent.md)\>

___

### ModificationKey

• **ModificationKey**: [`Guid`](ue_ue_s.Guid.md)

___

### Points

• **Points**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeSplineInterpPoint`](ue_ue.LandscapeSplineInterpPoint.md)\>

___

### RandomSeed

• **RandomSeed**: `number`

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

___

### SplineInfo

• **SplineInfo**: [`InterpCurveVector`](ue_ue.InterpCurveVector.md)

___

### SplineMeshes

• **SplineMeshes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeSplineMeshEntry`](ue_ue.LandscapeSplineMeshEntry.md)\>

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

### \_\_tid\_LandscapeSplineSegment\_\_

• **\_\_tid\_LandscapeSplineSegment\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LandscapeSplineSegment`](ue_ue.LandscapeSplineSegment.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LandscapeSplineSegment`](ue_ue.LandscapeSplineSegment.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LandscapeSplineSegment`](ue_ue.LandscapeSplineSegment.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LandscapeSplineSegment`](ue_ue.LandscapeSplineSegment.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
