[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VertexPaintSettings

# Class: VertexPaintSettings

[ue/ue](../modules/ue_ue.md).VertexPaintSettings

## Table of contents

### Constructors

- [constructor](ue_ue.VertexPaintSettings.md#constructor)

### Properties

- [EraseColor](ue_ue.VertexPaintSettings.md#erasecolor)
- [EraseTextureWeightIndex](ue_ue.VertexPaintSettings.md#erasetextureweightindex)
- [LODIndex](ue_ue.VertexPaintSettings.md#lodindex)
- [MeshPaintMode](ue_ue.VertexPaintSettings.md#meshpaintmode)
- [PaintColor](ue_ue.VertexPaintSettings.md#paintcolor)
- [PaintTextureWeightIndex](ue_ue.VertexPaintSettings.md#painttextureweightindex)
- [TextureWeightType](ue_ue.VertexPaintSettings.md#textureweighttype)
- [\_\_tid\_VertexPaintSettings\_\_](ue_ue.VertexPaintSettings.md#__tid_vertexpaintsettings__)
- [bPaintOnSpecificLOD](ue_ue.VertexPaintSettings.md#bpaintonspecificlod)
- [bWriteAlpha](ue_ue.VertexPaintSettings.md#bwritealpha)
- [bWriteBlue](ue_ue.VertexPaintSettings.md#bwriteblue)
- [bWriteGreen](ue_ue.VertexPaintSettings.md#bwritegreen)
- [bWriteRed](ue_ue.VertexPaintSettings.md#bwritered)

### Methods

- [StaticClass](ue_ue.VertexPaintSettings.md#staticclass)
- [StaticStruct](ue_ue.VertexPaintSettings.md#staticstruct)

## Constructors

### constructor

• **new VertexPaintSettings**()

• **new VertexPaintSettings**(`MeshPaintMode`, `PaintColor`, `EraseColor`, `bWriteRed`, `bWriteGreen`, `bWriteBlue`, `bWriteAlpha`, `TextureWeightType`, `PaintTextureWeightIndex`, `EraseTextureWeightIndex`, `bPaintOnSpecificLOD`, `LODIndex`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MeshPaintMode` | [`EMeshPaintMode`](../enums/ue_ue.EMeshPaintMode.md) |
| `PaintColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `EraseColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `bWriteRed` | `boolean` |
| `bWriteGreen` | `boolean` |
| `bWriteBlue` | `boolean` |
| `bWriteAlpha` | `boolean` |
| `TextureWeightType` | [`ETextureWeightTypes`](../enums/ue_ue.ETextureWeightTypes.md) |
| `PaintTextureWeightIndex` | [`ETexturePaintIndex`](../enums/ue_ue.ETexturePaintIndex.md) |
| `EraseTextureWeightIndex` | [`ETexturePaintIndex`](../enums/ue_ue.ETexturePaintIndex.md) |
| `bPaintOnSpecificLOD` | `boolean` |
| `LODIndex` | `number` |

## Properties

### EraseColor

• **EraseColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### EraseTextureWeightIndex

• **EraseTextureWeightIndex**: [`ETexturePaintIndex`](../enums/ue_ue.ETexturePaintIndex.md)

___

### LODIndex

• **LODIndex**: `number`

___

### MeshPaintMode

• **MeshPaintMode**: [`EMeshPaintMode`](../enums/ue_ue.EMeshPaintMode.md)

___

### PaintColor

• **PaintColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### PaintTextureWeightIndex

• **PaintTextureWeightIndex**: [`ETexturePaintIndex`](../enums/ue_ue.ETexturePaintIndex.md)

___

### TextureWeightType

• **TextureWeightType**: [`ETextureWeightTypes`](../enums/ue_ue.ETextureWeightTypes.md)

___

### \_\_tid\_VertexPaintSettings\_\_

• `Private` **\_\_tid\_VertexPaintSettings\_\_**: `boolean`

___

### bPaintOnSpecificLOD

• **bPaintOnSpecificLOD**: `boolean`

___

### bWriteAlpha

• **bWriteAlpha**: `boolean`

___

### bWriteBlue

• **bWriteBlue**: `boolean`

___

### bWriteGreen

• **bWriteGreen**: `boolean`

___

### bWriteRed

• **bWriteRed**: `boolean`

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
