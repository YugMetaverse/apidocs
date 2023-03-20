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

#### Defined in

[ue/ue.d.ts:423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L423)

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

#### Defined in

[ue/ue.d.ts:424](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L424)

## Properties

### BaseBlockX

• **BaseBlockX**: `number`

#### Defined in

[ue/ue.d.ts:426](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L426)

___

### BaseBlockY

• **BaseBlockY**: `number`

#### Defined in

[ue/ue.d.ts:427](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L427)

___

### Blocks

• **Blocks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TextureSourceBlock`](ue_ue.TextureSourceBlock.md)\>

#### Defined in

[ue/ue.d.ts:437](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L437)

___

### Format

• **Format**: [`ETextureSourceFormat`](../enums/ue_ue.ETextureSourceFormat.md)

#### Defined in

[ue/ue.d.ts:435](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L435)

___

### Id

• **Id**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:425](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L425)

___

### LayerFormat

• **LayerFormat**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ETextureSourceFormat`](../enums/ue_ue.ETextureSourceFormat.md)\>

#### Defined in

[ue/ue.d.ts:436](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L436)

___

### NumLayers

• **NumLayers**: `number`

#### Defined in

[ue/ue.d.ts:432](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L432)

___

### NumMips

• **NumMips**: `number`

#### Defined in

[ue/ue.d.ts:431](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L431)

___

### NumSlices

• **NumSlices**: `number`

#### Defined in

[ue/ue.d.ts:430](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L430)

___

### SizeX

• **SizeX**: `number`

#### Defined in

[ue/ue.d.ts:428](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L428)

___

### SizeY

• **SizeY**: `number`

#### Defined in

[ue/ue.d.ts:429](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L429)

___

### \_\_tid\_TextureSource\_\_

• `Private` **\_\_tid\_TextureSource\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:443](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L443)

___

### bGuidIsHash

• **bGuidIsHash**: `boolean`

#### Defined in

[ue/ue.d.ts:434](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L434)

___

### bPNGCompressed

• **bPNGCompressed**: `boolean`

#### Defined in

[ue/ue.d.ts:433](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L433)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:441](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L441)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:442](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L442)
