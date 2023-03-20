[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PaperTileSet

# Class: PaperTileSet

[ue/ue](../modules/ue_ue.md).PaperTileSet

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PaperTileSet`**

## Table of contents

### Constructors

- [constructor](ue_ue.PaperTileSet.md#constructor)

### Properties

- [AdditionalSourceTextures](ue_ue.PaperTileSet.md#additionalsourcetextures)
- [AllocatedHeight](ue_ue.PaperTileSet.md#allocatedheight)
- [AllocatedWidth](ue_ue.PaperTileSet.md#allocatedwidth)
- [BackgroundColor](ue_ue.PaperTileSet.md#backgroundcolor)
- [BorderMargin](ue_ue.PaperTileSet.md#bordermargin)
- [DrawingOffset](ue_ue.PaperTileSet.md#drawingoffset)
- [HeightInTiles](ue_ue.PaperTileSet.md#heightintiles)
- [Margin](ue_ue.PaperTileSet.md#margin)
- [PerTileData](ue_ue.PaperTileSet.md#pertiledata)
- [PerTileSpacing](ue_ue.PaperTileSet.md#pertilespacing)
- [Spacing](ue_ue.PaperTileSet.md#spacing)
- [Terrains](ue_ue.PaperTileSet.md#terrains)
- [TileHeight](ue_ue.PaperTileSet.md#tileheight)
- [TileSheet](ue_ue.PaperTileSet.md#tilesheet)
- [TileSize](ue_ue.PaperTileSet.md#tilesize)
- [TileWidth](ue_ue.PaperTileSet.md#tilewidth)
- [WidthInTiles](ue_ue.PaperTileSet.md#widthintiles)
- [\_\_tid\_Object\_\_](ue_ue.PaperTileSet.md#__tid_object__)
- [\_\_tid\_PaperTileSet\_\_](ue_ue.PaperTileSet.md#__tid_papertileset__)

### Methods

- [CreateDefaultSubobject](ue_ue.PaperTileSet.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PaperTileSet.md#executeubergraph)
- [GetClass](ue_ue.PaperTileSet.md#getclass)
- [GetName](ue_ue.PaperTileSet.md#getname)
- [GetOuter](ue_ue.PaperTileSet.md#getouter)
- [GetWorld](ue_ue.PaperTileSet.md#getworld)
- [Find](ue_ue.PaperTileSet.md#find)
- [Load](ue_ue.PaperTileSet.md#load)
- [StaticClass](ue_ue.PaperTileSet.md#staticclass)

## Constructors

### constructor

• **new PaperTileSet**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### AllocatedHeight

• **AllocatedHeight**: `number`

___

### AllocatedWidth

• **AllocatedWidth**: `number`

___

### BackgroundColor

• **BackgroundColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### BorderMargin

• **BorderMargin**: [`IntMargin`](ue_ue.IntMargin.md)

___

### DrawingOffset

• **DrawingOffset**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### HeightInTiles

• **HeightInTiles**: `number`

___

### Margin

• **Margin**: `number`

___

### PerTileData

• **PerTileData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PaperTileMetadata`](ue_ue.PaperTileMetadata.md)\>

___

### PerTileSpacing

• **PerTileSpacing**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### Spacing

• **Spacing**: `number`

___

### Terrains

• **Terrains**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PaperTileSetTerrain`](ue_ue.PaperTileSetTerrain.md)\>

___

### TileHeight

• **TileHeight**: `number`

___

### TileSheet

• **TileSheet**: [`Texture2D`](ue_ue.Texture2D.md)

___

### TileSize

• **TileSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### TileWidth

• **TileWidth**: `number`

___

### WidthInTiles

• **WidthInTiles**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PaperTileSet\_\_

• **\_\_tid\_PaperTileSet\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PaperTileSet`](ue_ue.PaperTileSet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PaperTileSet`](ue_ue.PaperTileSet.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PaperTileSet`](ue_ue.PaperTileSet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PaperTileSet`](ue_ue.PaperTileSet.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
