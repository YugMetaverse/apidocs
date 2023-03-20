[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PaperSpriteAtlas

# Class: PaperSpriteAtlas

[ue/ue](../modules/ue_ue.md).PaperSpriteAtlas

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PaperSpriteAtlas`**

## Table of contents

### Constructors

- [constructor](ue_ue.PaperSpriteAtlas.md#constructor)

### Properties

- [AtlasDescription](ue_ue.PaperSpriteAtlas.md#atlasdescription)
- [AtlasGUID](ue_ue.PaperSpriteAtlas.md#atlasguid)
- [AtlasSlots](ue_ue.PaperSpriteAtlas.md#atlasslots)
- [BuiltHeight](ue_ue.PaperSpriteAtlas.md#builtheight)
- [BuiltPadding](ue_ue.PaperSpriteAtlas.md#builtpadding)
- [BuiltWidth](ue_ue.PaperSpriteAtlas.md#builtwidth)
- [CompressionSettings](ue_ue.PaperSpriteAtlas.md#compressionsettings)
- [Filter](ue_ue.PaperSpriteAtlas.md#filter)
- [GeneratedTextures](ue_ue.PaperSpriteAtlas.md#generatedtextures)
- [MaxHeight](ue_ue.PaperSpriteAtlas.md#maxheight)
- [MaxWidth](ue_ue.PaperSpriteAtlas.md#maxwidth)
- [MipCount](ue_ue.PaperSpriteAtlas.md#mipcount)
- [NumIncrementalBuilds](ue_ue.PaperSpriteAtlas.md#numincrementalbuilds)
- [Padding](ue_ue.PaperSpriteAtlas.md#padding)
- [PaddingType](ue_ue.PaperSpriteAtlas.md#paddingtype)
- [\_\_tid\_Object\_\_](ue_ue.PaperSpriteAtlas.md#__tid_object__)
- [\_\_tid\_PaperSpriteAtlas\_\_](ue_ue.PaperSpriteAtlas.md#__tid_paperspriteatlas__)
- [bRebuildAtlas](ue_ue.PaperSpriteAtlas.md#brebuildatlas)

### Methods

- [CreateDefaultSubobject](ue_ue.PaperSpriteAtlas.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PaperSpriteAtlas.md#executeubergraph)
- [GetClass](ue_ue.PaperSpriteAtlas.md#getclass)
- [GetName](ue_ue.PaperSpriteAtlas.md#getname)
- [GetOuter](ue_ue.PaperSpriteAtlas.md#getouter)
- [GetWorld](ue_ue.PaperSpriteAtlas.md#getworld)
- [Find](ue_ue.PaperSpriteAtlas.md#find)
- [Load](ue_ue.PaperSpriteAtlas.md#load)
- [StaticClass](ue_ue.PaperSpriteAtlas.md#staticclass)

## Constructors

### constructor

• **new PaperSpriteAtlas**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AtlasDescription

• **AtlasDescription**: `string`

___

### AtlasGUID

• **AtlasGUID**: [`Guid`](ue_ue_s.Guid.md)

___

### AtlasSlots

• **AtlasSlots**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PaperSpriteAtlasSlot`](ue_ue.PaperSpriteAtlasSlot.md)\>

___

### BuiltHeight

• **BuiltHeight**: `number`

___

### BuiltPadding

• **BuiltPadding**: `number`

___

### BuiltWidth

• **BuiltWidth**: `number`

___

### CompressionSettings

• **CompressionSettings**: [`TextureCompressionSettings`](../enums/ue_ue.TextureCompressionSettings.md)

___

### Filter

• **Filter**: [`TextureFilter`](../enums/ue_ue.TextureFilter.md)

___

### GeneratedTextures

• **GeneratedTextures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Texture`](ue_ue.Texture.md)\>

___

### MaxHeight

• **MaxHeight**: `number`

___

### MaxWidth

• **MaxWidth**: `number`

___

### MipCount

• **MipCount**: `number`

___

### NumIncrementalBuilds

• **NumIncrementalBuilds**: `number`

___

### Padding

• **Padding**: `number`

___

### PaddingType

• **PaddingType**: [`EPaperSpriteAtlasPadding`](../enums/ue_ue.EPaperSpriteAtlasPadding.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PaperSpriteAtlas\_\_

• **\_\_tid\_PaperSpriteAtlas\_\_**: `boolean`

___

### bRebuildAtlas

• **bRebuildAtlas**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PaperSpriteAtlas`](ue_ue.PaperSpriteAtlas.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PaperSpriteAtlas`](ue_ue.PaperSpriteAtlas.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PaperSpriteAtlas`](ue_ue.PaperSpriteAtlas.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PaperSpriteAtlas`](ue_ue.PaperSpriteAtlas.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
