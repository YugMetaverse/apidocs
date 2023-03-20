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

## Properties

### AdditionalSourceTextures

• **AdditionalSourceTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Texture`](ue_ue.Texture.md)\>

___

### AlternateMaterial

• **AlternateMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### AlternateMaterialSplitIndex

• **AlternateMaterialSplitIndex**: `number`

___

### AtlasGroup

• **AtlasGroup**: [`PaperSpriteAtlas`](ue_ue.PaperSpriteAtlas.md)

___

### BakedRenderData

• **BakedRenderData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector4`](ue_ue_s.Vector4.md)\>

___

### BakedSourceDimension

• **BakedSourceDimension**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### BakedSourceTexture

• **BakedSourceTexture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### BakedSourceUV

• **BakedSourceUV**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### BodySetup

• **BodySetup**: [`BodySetup`](ue_ue.BodySetup.md)

___

### CollisionGeometry

• **CollisionGeometry**: [`SpriteGeometryCollection`](ue_ue.SpriteGeometryCollection.md)

___

### CollisionThickness

• **CollisionThickness**: `number`

___

### CustomPivotPoint

• **CustomPivotPoint**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### DefaultMaterial

• **DefaultMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### OriginInSourceImageBeforeTrimming

• **OriginInSourceImageBeforeTrimming**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### PivotMode

• **PivotMode**: [`ESpritePivotMode`](../enums/ue_ue.ESpritePivotMode.md)

___

### PixelsPerUnrealUnit

• **PixelsPerUnrealUnit**: `number`

___

### RenderGeometry

• **RenderGeometry**: [`SpriteGeometryCollection`](ue_ue.SpriteGeometryCollection.md)

___

### Sockets

• **Sockets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PaperSpriteSocket`](ue_ue.PaperSpriteSocket.md)\>

___

### SourceDimension

• **SourceDimension**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### SourceImageDimensionBeforeTrimming

• **SourceImageDimensionBeforeTrimming**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### SourceTexture

• **SourceTexture**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`Texture2D`](ue_ue.Texture2D.md)\>

___

### SourceTextureCacheNeverSerialized

• **SourceTextureCacheNeverSerialized**: [`Texture2D`](ue_ue.Texture2D.md)

___

### SourceTextureDimension

• **SourceTextureDimension**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### SourceUV

• **SourceUV**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### SpriteCollisionDomain

• **SpriteCollisionDomain**: [`ESpriteCollisionMode`](../enums/ue_ue.ESpriteCollisionMode.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PaperSprite\_\_

• **\_\_tid\_PaperSprite\_\_**: `boolean`

___

### bRotatedInSourceImage

• **bRotatedInSourceImage**: `boolean`

___

### bSnapPivotToPixelGrid

• **bSnapPivotToPixelGrid**: `boolean`

___

### bTrimmedInSourceImage

• **bTrimmedInSourceImage**: `boolean`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
