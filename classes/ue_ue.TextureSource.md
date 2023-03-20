[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TextureSource

# Class: TextureSource

[ue/ue](../modules/ue_ue.md).TextureSource

## Table of contents

### Constructors

- [constructor](ue_ue.TextureSource.md#constructor)

### Properties

- [BaseBlockX](ue_ue.TextureSource.md#baseblockx)
- [BaseBlockY](ue_ue.TextureSource.md#baseblocky)
- [Blocks](ue_ue.TextureSource.md#blocks)
- [Format](ue_ue.TextureSource.md#format)
- [Id](ue_ue.TextureSource.md#id)
- [LayerFormat](ue_ue.TextureSource.md#layerformat)
- [NumLayers](ue_ue.TextureSource.md#numlayers)
- [NumMips](ue_ue.TextureSource.md#nummips)
- [NumSlices](ue_ue.TextureSource.md#numslices)
- [SizeX](ue_ue.TextureSource.md#sizex)
- [SizeY](ue_ue.TextureSource.md#sizey)
- [\_\_tid\_TextureSource\_\_](ue_ue.TextureSource.md#__tid_texturesource__)
- [bGuidIsHash](ue_ue.TextureSource.md#bguidishash)
- [bPNGCompressed](ue_ue.TextureSource.md#bpngcompressed)

### Methods

- [StaticClass](ue_ue.TextureSource.md#staticclass)
- [StaticStruct](ue_ue.TextureSource.md#staticstruct)

## Constructors

### constructor

• **new TextureSource**()

• **new TextureSource**(`Id`, `BaseBlockX`, `BaseBlockY`, `SizeX`, `SizeY`, `NumSlices`, `NumMips`, `NumLayers`, `bPNGCompressed`, `bGuidIsHash`, `Format`, `LayerFormat`, `Blocks`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Id` | [`Guid`](ue_ue_s.Guid.md) |
| `BaseBlockX` | `number` |
| `BaseBlockY` | `number` |
| `SizeX` | `number` |
| `SizeY` | `number` |
| `NumSlices` | `number` |
| `NumMips` | `number` |
| `NumLayers` | `number` |
| `bPNGCompressed` | `boolean` |
| `bGuidIsHash` | `boolean` |
| `Format` | [`ETextureSourceFormat`](../enums/ue_ue.ETextureSourceFormat.md) |
| `LayerFormat` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ETextureSourceFormat`](../enums/ue_ue.ETextureSourceFormat.md)\> |
| `Blocks` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureSourceBlock`](ue_ue.TextureSourceBlock.md)\> |

## Properties

### BaseBlockX

• **BaseBlockX**: `number`

___

### BaseBlockY

• **BaseBlockY**: `number`

___

### Blocks

• **Blocks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureSourceBlock`](ue_ue.TextureSourceBlock.md)\>

___

### Format

• **Format**: [`ETextureSourceFormat`](../enums/ue_ue.ETextureSourceFormat.md)

___

### Id

• **Id**: [`Guid`](ue_ue_s.Guid.md)

___

### LayerFormat

• **LayerFormat**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ETextureSourceFormat`](../enums/ue_ue.ETextureSourceFormat.md)\>

___

### NumLayers

• **NumLayers**: `number`

___

### NumMips

• **NumMips**: `number`

___

### NumSlices

• **NumSlices**: `number`

___

### SizeX

• **SizeX**: `number`

___

### SizeY

• **SizeY**: `number`

___

### \_\_tid\_TextureSource\_\_

• `Private` **\_\_tid\_TextureSource\_\_**: `boolean`

___

### bGuidIsHash

• **bGuidIsHash**: `boolean`

___

### bPNGCompressed

• **bPNGCompressed**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
