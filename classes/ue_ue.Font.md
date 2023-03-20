[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Font

# Class: Font

[ue/ue](../modules/ue_ue.md).Font

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`Font`**

## Table of contents

### Constructors

- [constructor](ue_ue.Font.md#constructor)

### Properties

- [Ascent](ue_ue.Font.md#ascent)
- [Characters](ue_ue.Font.md#characters)
- [CompositeFont](ue_ue.Font.md#compositefont)
- [Descent](ue_ue.Font.md#descent)
- [EmScale](ue_ue.Font.md#emscale)
- [FontCacheType](ue_ue.Font.md#fontcachetype)
- [ImportOptions](ue_ue.Font.md#importoptions)
- [IsRemapped](ue_ue.Font.md#isremapped)
- [Kerning](ue_ue.Font.md#kerning)
- [Leading](ue_ue.Font.md#leading)
- [LegacyFontName](ue_ue.Font.md#legacyfontname)
- [LegacyFontSize](ue_ue.Font.md#legacyfontsize)
- [MaxCharHeight](ue_ue.Font.md#maxcharheight)
- [NumCharacters](ue_ue.Font.md#numcharacters)
- [ScalingFactor](ue_ue.Font.md#scalingfactor)
- [Textures](ue_ue.Font.md#textures)
- [\_\_tid\_Font\_\_](ue_ue.Font.md#__tid_font__)
- [\_\_tid\_Object\_\_](ue_ue.Font.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.Font.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Font.md#executeubergraph)
- [GetClass](ue_ue.Font.md#getclass)
- [GetName](ue_ue.Font.md#getname)
- [GetOuter](ue_ue.Font.md#getouter)
- [GetWorld](ue_ue.Font.md#getworld)
- [Find](ue_ue.Font.md#find)
- [Load](ue_ue.Font.md#load)
- [StaticClass](ue_ue.Font.md#staticclass)

## Constructors

### constructor

• **new Font**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Ascent

• **Ascent**: `number`

___

### Characters

• **Characters**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FontCharacter`](ue_ue.FontCharacter.md)\>

___

### CompositeFont

• **CompositeFont**: [`CompositeFont`](ue_ue.CompositeFont.md)

___

### Descent

• **Descent**: `number`

___

### EmScale

• **EmScale**: `number`

___

### FontCacheType

• **FontCacheType**: [`EFontCacheType`](../enums/ue_ue.EFontCacheType.md)

___

### ImportOptions

• **ImportOptions**: [`FontImportOptionsData`](ue_ue.FontImportOptionsData.md)

___

### IsRemapped

• **IsRemapped**: `number`

___

### Kerning

• **Kerning**: `number`

___

### Leading

• **Leading**: `number`

___

### LegacyFontName

• **LegacyFontName**: `string`

___

### LegacyFontSize

• **LegacyFontSize**: `number`

___

### MaxCharHeight

• **MaxCharHeight**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### NumCharacters

• **NumCharacters**: `number`

___

### ScalingFactor

• **ScalingFactor**: `number`

___

### Textures

• **Textures**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Texture2D`](ue_ue.Texture2D.md)\>

___

### \_\_tid\_Font\_\_

• **\_\_tid\_Font\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Font`](ue_ue.Font.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Font`](ue_ue.Font.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`Font`](ue_ue.Font.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Font`](ue_ue.Font.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
