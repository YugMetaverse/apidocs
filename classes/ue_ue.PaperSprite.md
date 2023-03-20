[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PaperSprite

# Class: PaperSprite

[ue/ue](../modules/ue_ue.md).PaperSprite

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PaperSprite`**

## Table of contents

### Constructors

- [constructor](ue_ue.PaperSprite.md#constructor)

### Properties

- [AdditionalSourceTextures](ue_ue.PaperSprite.md#additionalsourcetextures)
- [AlternateMaterial](ue_ue.PaperSprite.md#alternatematerial)
- [AlternateMaterialSplitIndex](ue_ue.PaperSprite.md#alternatematerialsplitindex)
- [AtlasGroup](ue_ue.PaperSprite.md#atlasgroup)
- [BakedRenderData](ue_ue.PaperSprite.md#bakedrenderdata)
- [BakedSourceDimension](ue_ue.PaperSprite.md#bakedsourcedimension)
- [BakedSourceTexture](ue_ue.PaperSprite.md#bakedsourcetexture)
- [BakedSourceUV](ue_ue.PaperSprite.md#bakedsourceuv)
- [BodySetup](ue_ue.PaperSprite.md#bodysetup)
- [CollisionGeometry](ue_ue.PaperSprite.md#collisiongeometry)
- [CollisionThickness](ue_ue.PaperSprite.md#collisionthickness)
- [CustomPivotPoint](ue_ue.PaperSprite.md#custompivotpoint)
- [DefaultMaterial](ue_ue.PaperSprite.md#defaultmaterial)
- [OriginInSourceImageBeforeTrimming](ue_ue.PaperSprite.md#origininsourceimagebeforetrimming)
- [PivotMode](ue_ue.PaperSprite.md#pivotmode)
- [PixelsPerUnrealUnit](ue_ue.PaperSprite.md#pixelsperunrealunit)
- [RenderGeometry](ue_ue.PaperSprite.md#rendergeometry)
- [Sockets](ue_ue.PaperSprite.md#sockets)
- [SourceDimension](ue_ue.PaperSprite.md#sourcedimension)
- [SourceImageDimensionBeforeTrimming](ue_ue.PaperSprite.md#sourceimagedimensionbeforetrimming)
- [SourceTexture](ue_ue.PaperSprite.md#sourcetexture)
- [SourceTextureCacheNeverSerialized](ue_ue.PaperSprite.md#sourcetexturecacheneverserialized)
- [SourceTextureDimension](ue_ue.PaperSprite.md#sourcetexturedimension)
- [SourceUV](ue_ue.PaperSprite.md#sourceuv)
- [SpriteCollisionDomain](ue_ue.PaperSprite.md#spritecollisiondomain)
- [\_\_tid\_Object\_\_](ue_ue.PaperSprite.md#__tid_object__)
- [\_\_tid\_PaperSprite\_\_](ue_ue.PaperSprite.md#__tid_papersprite__)
- [bRotatedInSourceImage](ue_ue.PaperSprite.md#brotatedinsourceimage)
- [bSnapPivotToPixelGrid](ue_ue.PaperSprite.md#bsnappivottopixelgrid)
- [bTrimmedInSourceImage](ue_ue.PaperSprite.md#btrimmedinsourceimage)

### Methods

- [CreateDefaultSubobject](ue_ue.PaperSprite.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PaperSprite.md#executeubergraph)
- [GetClass](ue_ue.PaperSprite.md#getclass)
- [GetName](ue_ue.PaperSprite.md#getname)
- [GetOuter](ue_ue.PaperSprite.md#getouter)
- [GetWorld](ue_ue.PaperSprite.md#getworld)
- [Find](ue_ue.PaperSprite.md#find)
- [Load](ue_ue.PaperSprite.md#load)
- [StaticClass](ue_ue.PaperSprite.md#staticclass)

## Constructors

### constructor

• **new PaperSprite**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:54547](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54547)

## Properties

### AdditionalSourceTextures

• **AdditionalSourceTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Texture`](ue_ue.Texture.md)\>

#### Defined in

[ue/ue.d.ts:54557](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54557)

___

### AlternateMaterial

• **AlternateMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:54562](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54562)

___

### AlternateMaterialSplitIndex

• **AlternateMaterialSplitIndex**: `number`

#### Defined in

[ue/ue.d.ts:54574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54574)

___

### AtlasGroup

• **AtlasGroup**: [`PaperSpriteAtlas`](ue_ue.PaperSpriteAtlas.md)

#### Defined in

[ue/ue.d.ts:54573](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54573)

___

### BakedRenderData

• **BakedRenderData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector4`](ue_ue_s.Vector4.md)\>

#### Defined in

[ue/ue.d.ts:54575](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54575)

___

### BakedSourceDimension

• **BakedSourceDimension**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:54559](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54559)

___

### BakedSourceTexture

• **BakedSourceTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:54560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54560)

___

### BakedSourceUV

• **BakedSourceUV**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:54558](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54558)

___

### BodySetup

• **BodySetup**: [`BodySetup`](ue_ue.BodySetup.md)

#### Defined in

[ue/ue.d.ts:54566](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54566)

___

### CollisionGeometry

• **CollisionGeometry**: [`SpriteGeometryCollection`](ue_ue.SpriteGeometryCollection.md)

#### Defined in

[ue/ue.d.ts:54570](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54570)

___

### CollisionThickness

• **CollisionThickness**: `number`

#### Defined in

[ue/ue.d.ts:54571](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54571)

___

### CustomPivotPoint

• **CustomPivotPoint**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:54568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54568)

___

### DefaultMaterial

• **DefaultMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:54561](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54561)

___

### OriginInSourceImageBeforeTrimming

• **OriginInSourceImageBeforeTrimming**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:54548](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54548)

___

### PivotMode

• **PivotMode**: [`ESpritePivotMode`](../enums/ue_ue.ESpritePivotMode.md)

#### Defined in

[ue/ue.d.ts:54567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54567)

___

### PixelsPerUnrealUnit

• **PixelsPerUnrealUnit**: `number`

#### Defined in

[ue/ue.d.ts:54565](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54565)

___

### RenderGeometry

• **RenderGeometry**: [`SpriteGeometryCollection`](ue_ue.SpriteGeometryCollection.md)

#### Defined in

[ue/ue.d.ts:54572](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54572)

___

### Sockets

• **Sockets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PaperSpriteSocket`](ue_ue.PaperSpriteSocket.md)\>

#### Defined in

[ue/ue.d.ts:54563](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54563)

___

### SourceDimension

• **SourceDimension**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:54554](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54554)

___

### SourceImageDimensionBeforeTrimming

• **SourceImageDimensionBeforeTrimming**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:54549](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54549)

___

### SourceTexture

• **SourceTexture**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`Texture2D`](ue_ue.Texture2D.md)\>

#### Defined in

[ue/ue.d.ts:54555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54555)

___

### SourceTextureCacheNeverSerialized

• **SourceTextureCacheNeverSerialized**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:54556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54556)

___

### SourceTextureDimension

• **SourceTextureDimension**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:54552](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54552)

___

### SourceUV

• **SourceUV**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:54553](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54553)

___

### SpriteCollisionDomain

• **SpriteCollisionDomain**: [`ESpriteCollisionMode`](../enums/ue_ue.ESpriteCollisionMode.md)

#### Defined in

[ue/ue.d.ts:54564](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54564)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PaperSprite\_\_

• **\_\_tid\_PaperSprite\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:54580](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54580)

___

### bRotatedInSourceImage

• **bRotatedInSourceImage**: `boolean`

#### Defined in

[ue/ue.d.ts:54551](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54551)

___

### bSnapPivotToPixelGrid

• **bSnapPivotToPixelGrid**: `boolean`

#### Defined in

[ue/ue.d.ts:54569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54569)

___

### bTrimmedInSourceImage

• **bTrimmedInSourceImage**: `boolean`

#### Defined in

[ue/ue.d.ts:54550](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54550)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PaperSprite`](ue_ue.PaperSprite.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PaperSprite`](ue_ue.PaperSprite.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:54577](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54577)

___

### Load

▸ `Static` **Load**(`InName`): [`PaperSprite`](ue_ue.PaperSprite.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PaperSprite`](ue_ue.PaperSprite.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:54578](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54578)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:54576](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54576)
