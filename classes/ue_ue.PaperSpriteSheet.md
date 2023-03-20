[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PaperSpriteSheet

# Class: PaperSpriteSheet

[ue/ue](../modules/ue_ue.md).PaperSpriteSheet

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PaperSpriteSheet`**

## Table of contents

### Constructors

- [constructor](ue_ue.PaperSpriteSheet.md#constructor)

### Properties

- [AssetImportData](ue_ue.PaperSpriteSheet.md#assetimportdata)
- [NormalMapTexture](ue_ue.PaperSpriteSheet.md#normalmaptexture)
- [NormalMapTextureName](ue_ue.PaperSpriteSheet.md#normalmaptexturename)
- [SpriteNames](ue_ue.PaperSpriteSheet.md#spritenames)
- [Sprites](ue_ue.PaperSpriteSheet.md#sprites)
- [Texture](ue_ue.PaperSpriteSheet.md#texture)
- [TextureName](ue_ue.PaperSpriteSheet.md#texturename)
- [\_\_tid\_Object\_\_](ue_ue.PaperSpriteSheet.md#__tid_object__)
- [\_\_tid\_PaperSpriteSheet\_\_](ue_ue.PaperSpriteSheet.md#__tid_paperspritesheet__)

### Methods

- [CreateDefaultSubobject](ue_ue.PaperSpriteSheet.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PaperSpriteSheet.md#executeubergraph)
- [GetClass](ue_ue.PaperSpriteSheet.md#getclass)
- [GetName](ue_ue.PaperSpriteSheet.md#getname)
- [GetOuter](ue_ue.PaperSpriteSheet.md#getouter)
- [GetWorld](ue_ue.PaperSpriteSheet.md#getworld)
- [Find](ue_ue.PaperSpriteSheet.md#find)
- [Load](ue_ue.PaperSpriteSheet.md#load)
- [StaticClass](ue_ue.PaperSpriteSheet.md#staticclass)

## Constructors

### constructor

• **new PaperSpriteSheet**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

___

### NormalMapTexture

• **NormalMapTexture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### NormalMapTextureName

• **NormalMapTextureName**: `string`

___

### SpriteNames

• **SpriteNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### Sprites

• **Sprites**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`PaperSprite`](ue_ue.PaperSprite.md)\>\>

___

### Texture

• **Texture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### TextureName

• **TextureName**: `string`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PaperSpriteSheet\_\_

• **\_\_tid\_PaperSpriteSheet\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PaperSpriteSheet`](ue_ue.PaperSpriteSheet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PaperSpriteSheet`](ue_ue.PaperSpriteSheet.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PaperSpriteSheet`](ue_ue.PaperSpriteSheet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PaperSpriteSheet`](ue_ue.PaperSpriteSheet.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
