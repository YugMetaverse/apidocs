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

#### Defined in

[ue/ue.d.ts:43660](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43660)

## Properties

### BodyInstance

• **BodyInstance**: [`BodyInstance`](ue_ue.BodyInstance.md)

#### Defined in

[ue/ue.d.ts:43679](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43679)

___

### Bounds

• **Bounds**: [`Box`](ue_ue.Box.md)

#### Defined in

[ue/ue.d.ts:43684](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43684)

___

### CollisionProfileName

• **CollisionProfileName**: `string`

#### Defined in

[ue/ue.d.ts:43667](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43667)

___

### Connections

• **Connections**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`LandscapeSplineSegmentConnection`](ue_ue.LandscapeSplineSegmentConnection.md)\>

#### Defined in

[ue/ue.d.ts:43661](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43661)

___

### ForeignWorlds

• **ForeignWorlds**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`World`](ue_ue.World.md)\>\>

#### Defined in

[ue/ue.d.ts:43686](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43686)

___

### LDMaxDrawDistance

• **LDMaxDrawDistance**: `number`

#### Defined in

[ue/ue.d.ts:43670](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43670)

___

### LayerName

• **LayerName**: `string`

#### Defined in

[ue/ue.d.ts:43662](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43662)

___

### LocalMeshComponents

• **LocalMeshComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SplineMeshComponent`](ue_ue.SplineMeshComponent.md)\>

#### Defined in

[ue/ue.d.ts:43685](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43685)

___

### ModificationKey

• **ModificationKey**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:43687](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43687)

___

### Points

• **Points**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeSplineInterpPoint`](ue_ue.LandscapeSplineInterpPoint.md)\>

#### Defined in

[ue/ue.d.ts:43683](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43683)

___

### RandomSeed

• **RandomSeed**: `number`

#### Defined in

[ue/ue.d.ts:43669](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43669)

___

### RuntimeVirtualTextures

• **RuntimeVirtualTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)\>

#### Defined in

[ue/ue.d.ts:43674](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43674)

___

### SplineInfo

• **SplineInfo**: [`InterpCurveVector`](ue_ue.InterpCurveVector.md)

#### Defined in

[ue/ue.d.ts:43682](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43682)

___

### SplineMeshes

• **SplineMeshes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeSplineMeshEntry`](ue_ue.LandscapeSplineMeshEntry.md)\>

#### Defined in

[ue/ue.d.ts:43665](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43665)

___

### TranslucencySortPriority

• **TranslucencySortPriority**: `number`

#### Defined in

[ue/ue.d.ts:43671](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43671)

___

### VirtualTextureCullMips

• **VirtualTextureCullMips**: `number`

#### Defined in

[ue/ue.d.ts:43676](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43676)

___

### VirtualTextureLodBias

• **VirtualTextureLodBias**: `number`

#### Defined in

[ue/ue.d.ts:43675](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43675)

___

### VirtualTextureMainPassMaxDrawDistance

• **VirtualTextureMainPassMaxDrawDistance**: `number`

#### Defined in

[ue/ue.d.ts:43677](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43677)

___

### VirtualTextureRenderPassType

• **VirtualTextureRenderPassType**: [`ERuntimeVirtualTextureMainPassType`](../enums/ue_ue.ERuntimeVirtualTextureMainPassType.md)

#### Defined in

[ue/ue.d.ts:43678](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43678)

___

### \_\_tid\_LandscapeSplineSegment\_\_

• **\_\_tid\_LandscapeSplineSegment\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:43692](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43692)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bCastShadow

• **bCastShadow**: `boolean`

#### Defined in

[ue/ue.d.ts:43668](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43668)

___

### bEnableCollision

• **bEnableCollision**: `boolean`

#### Defined in

[ue/ue.d.ts:43666](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43666)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Defined in

[ue/ue.d.ts:43672](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43672)

___

### bLowerTerrain

• **bLowerTerrain**: `boolean`

#### Defined in

[ue/ue.d.ts:43664](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43664)

___

### bNavDirty

• **bNavDirty**: `boolean`

#### Defined in

[ue/ue.d.ts:43681](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43681)

___

### bPlaceSplineMeshesInStreamingLevels

• **bPlaceSplineMeshesInStreamingLevels**: `boolean`

#### Defined in

[ue/ue.d.ts:43673](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43673)

___

### bRaiseTerrain

• **bRaiseTerrain**: `boolean`

#### Defined in

[ue/ue.d.ts:43663](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43663)

___

### bSelected

• **bSelected**: `boolean`

#### Defined in

[ue/ue.d.ts:43680](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43680)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:43689](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43689)

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

#### Defined in

[ue/ue.d.ts:43690](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43690)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:43688](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L43688)
