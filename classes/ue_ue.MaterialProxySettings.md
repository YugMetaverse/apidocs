[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialProxySettings

# Class: MaterialProxySettings

[ue/ue](../modules/ue_ue.md).MaterialProxySettings

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialProxySettings.md#constructor)

### Properties

- [AmbientOcclusionConstant](ue_ue.MaterialProxySettings.md#ambientocclusionconstant)
- [AmbientOcclusionTextureSize](ue_ue.MaterialProxySettings.md#ambientocclusiontexturesize)
- [BlendMode](ue_ue.MaterialProxySettings.md#blendmode)
- [DiffuseTextureSize](ue_ue.MaterialProxySettings.md#diffusetexturesize)
- [EmissiveTextureSize](ue_ue.MaterialProxySettings.md#emissivetexturesize)
- [GutterSpace](ue_ue.MaterialProxySettings.md#gutterspace)
- [MaterialMergeType](ue_ue.MaterialProxySettings.md#materialmergetype)
- [MetallicConstant](ue_ue.MaterialProxySettings.md#metallicconstant)
- [MetallicTextureSize](ue_ue.MaterialProxySettings.md#metallictexturesize)
- [NormalTextureSize](ue_ue.MaterialProxySettings.md#normaltexturesize)
- [OpacityConstant](ue_ue.MaterialProxySettings.md#opacityconstant)
- [OpacityMaskConstant](ue_ue.MaterialProxySettings.md#opacitymaskconstant)
- [OpacityMaskTextureSize](ue_ue.MaterialProxySettings.md#opacitymasktexturesize)
- [OpacityTextureSize](ue_ue.MaterialProxySettings.md#opacitytexturesize)
- [RoughnessConstant](ue_ue.MaterialProxySettings.md#roughnessconstant)
- [RoughnessTextureSize](ue_ue.MaterialProxySettings.md#roughnesstexturesize)
- [SpecularConstant](ue_ue.MaterialProxySettings.md#specularconstant)
- [SpecularTextureSize](ue_ue.MaterialProxySettings.md#speculartexturesize)
- [TextureSize](ue_ue.MaterialProxySettings.md#texturesize)
- [TextureSizingType](ue_ue.MaterialProxySettings.md#texturesizingtype)
- [\_\_tid\_MaterialProxySettings\_\_](ue_ue.MaterialProxySettings.md#__tid_materialproxysettings__)
- [bAllowTwoSidedMaterial](ue_ue.MaterialProxySettings.md#ballowtwosidedmaterial)
- [bAmbientOcclusionMap](ue_ue.MaterialProxySettings.md#bambientocclusionmap)
- [bEmissiveMap](ue_ue.MaterialProxySettings.md#bemissivemap)
- [bMetallicMap](ue_ue.MaterialProxySettings.md#bmetallicmap)
- [bNormalMap](ue_ue.MaterialProxySettings.md#bnormalmap)
- [bOpacityMap](ue_ue.MaterialProxySettings.md#bopacitymap)
- [bOpacityMaskMap](ue_ue.MaterialProxySettings.md#bopacitymaskmap)
- [bRoughnessMap](ue_ue.MaterialProxySettings.md#broughnessmap)
- [bSpecularMap](ue_ue.MaterialProxySettings.md#bspecularmap)

### Methods

- [StaticClass](ue_ue.MaterialProxySettings.md#staticclass)
- [StaticStruct](ue_ue.MaterialProxySettings.md#staticstruct)

## Constructors

### constructor

• **new MaterialProxySettings**()

#### Defined in

[ue/ue.d.ts:8603](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8603)

• **new MaterialProxySettings**(`TextureSize`, `GutterSpace`, `MetallicConstant`, `RoughnessConstant`, `SpecularConstant`, `OpacityConstant`, `OpacityMaskConstant`, `AmbientOcclusionConstant`, `TextureSizingType`, `MaterialMergeType`, `BlendMode`, `bAllowTwoSidedMaterial`, `bNormalMap`, `bMetallicMap`, `bRoughnessMap`, `bSpecularMap`, `bEmissiveMap`, `bOpacityMap`, `bOpacityMaskMap`, `bAmbientOcclusionMap`, `DiffuseTextureSize`, `NormalTextureSize`, `MetallicTextureSize`, `RoughnessTextureSize`, `SpecularTextureSize`, `EmissiveTextureSize`, `OpacityTextureSize`, `OpacityMaskTextureSize`, `AmbientOcclusionTextureSize`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TextureSize` | [`IntPoint`](ue_ue_s.IntPoint.md) |
| `GutterSpace` | `number` |
| `MetallicConstant` | `number` |
| `RoughnessConstant` | `number` |
| `SpecularConstant` | `number` |
| `OpacityConstant` | `number` |
| `OpacityMaskConstant` | `number` |
| `AmbientOcclusionConstant` | `number` |
| `TextureSizingType` | [`ETextureSizingType`](../enums/ue_ue.ETextureSizingType.md) |
| `MaterialMergeType` | [`EMaterialMergeType`](../enums/ue_ue.EMaterialMergeType.md) |
| `BlendMode` | [`EBlendMode`](../enums/ue_ue.EBlendMode.md) |
| `bAllowTwoSidedMaterial` | `boolean` |
| `bNormalMap` | `boolean` |
| `bMetallicMap` | `boolean` |
| `bRoughnessMap` | `boolean` |
| `bSpecularMap` | `boolean` |
| `bEmissiveMap` | `boolean` |
| `bOpacityMap` | `boolean` |
| `bOpacityMaskMap` | `boolean` |
| `bAmbientOcclusionMap` | `boolean` |
| `DiffuseTextureSize` | [`IntPoint`](ue_ue_s.IntPoint.md) |
| `NormalTextureSize` | [`IntPoint`](ue_ue_s.IntPoint.md) |
| `MetallicTextureSize` | [`IntPoint`](ue_ue_s.IntPoint.md) |
| `RoughnessTextureSize` | [`IntPoint`](ue_ue_s.IntPoint.md) |
| `SpecularTextureSize` | [`IntPoint`](ue_ue_s.IntPoint.md) |
| `EmissiveTextureSize` | [`IntPoint`](ue_ue_s.IntPoint.md) |
| `OpacityTextureSize` | [`IntPoint`](ue_ue_s.IntPoint.md) |
| `OpacityMaskTextureSize` | [`IntPoint`](ue_ue_s.IntPoint.md) |
| `AmbientOcclusionTextureSize` | [`IntPoint`](ue_ue_s.IntPoint.md) |

#### Defined in

[ue/ue.d.ts:8604](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8604)

## Properties

### AmbientOcclusionConstant

• **AmbientOcclusionConstant**: `number`

#### Defined in

[ue/ue.d.ts:8612](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8612)

___

### AmbientOcclusionTextureSize

• **AmbientOcclusionTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:8633](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8633)

___

### BlendMode

• **BlendMode**: [`EBlendMode`](../enums/ue_ue.EBlendMode.md)

#### Defined in

[ue/ue.d.ts:8615](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8615)

___

### DiffuseTextureSize

• **DiffuseTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:8625](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8625)

___

### EmissiveTextureSize

• **EmissiveTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:8630](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8630)

___

### GutterSpace

• **GutterSpace**: `number`

#### Defined in

[ue/ue.d.ts:8606](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8606)

___

### MaterialMergeType

• **MaterialMergeType**: [`EMaterialMergeType`](../enums/ue_ue.EMaterialMergeType.md)

#### Defined in

[ue/ue.d.ts:8614](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8614)

___

### MetallicConstant

• **MetallicConstant**: `number`

#### Defined in

[ue/ue.d.ts:8607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8607)

___

### MetallicTextureSize

• **MetallicTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:8627](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8627)

___

### NormalTextureSize

• **NormalTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:8626](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8626)

___

### OpacityConstant

• **OpacityConstant**: `number`

#### Defined in

[ue/ue.d.ts:8610](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8610)

___

### OpacityMaskConstant

• **OpacityMaskConstant**: `number`

#### Defined in

[ue/ue.d.ts:8611](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8611)

___

### OpacityMaskTextureSize

• **OpacityMaskTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:8632](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8632)

___

### OpacityTextureSize

• **OpacityTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:8631](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8631)

___

### RoughnessConstant

• **RoughnessConstant**: `number`

#### Defined in

[ue/ue.d.ts:8608](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8608)

___

### RoughnessTextureSize

• **RoughnessTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:8628](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8628)

___

### SpecularConstant

• **SpecularConstant**: `number`

#### Defined in

[ue/ue.d.ts:8609](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8609)

___

### SpecularTextureSize

• **SpecularTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:8629](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8629)

___

### TextureSize

• **TextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue.d.ts:8605](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8605)

___

### TextureSizingType

• **TextureSizingType**: [`ETextureSizingType`](../enums/ue_ue.ETextureSizingType.md)

#### Defined in

[ue/ue.d.ts:8613](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8613)

___

### \_\_tid\_MaterialProxySettings\_\_

• `Private` **\_\_tid\_MaterialProxySettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:8639](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8639)

___

### bAllowTwoSidedMaterial

• **bAllowTwoSidedMaterial**: `boolean`

#### Defined in

[ue/ue.d.ts:8616](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8616)

___

### bAmbientOcclusionMap

• **bAmbientOcclusionMap**: `boolean`

#### Defined in

[ue/ue.d.ts:8624](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8624)

___

### bEmissiveMap

• **bEmissiveMap**: `boolean`

#### Defined in

[ue/ue.d.ts:8621](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8621)

___

### bMetallicMap

• **bMetallicMap**: `boolean`

#### Defined in

[ue/ue.d.ts:8618](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8618)

___

### bNormalMap

• **bNormalMap**: `boolean`

#### Defined in

[ue/ue.d.ts:8617](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8617)

___

### bOpacityMap

• **bOpacityMap**: `boolean`

#### Defined in

[ue/ue.d.ts:8622](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8622)

___

### bOpacityMaskMap

• **bOpacityMaskMap**: `boolean`

#### Defined in

[ue/ue.d.ts:8623](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8623)

___

### bRoughnessMap

• **bRoughnessMap**: `boolean`

#### Defined in

[ue/ue.d.ts:8619](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8619)

___

### bSpecularMap

• **bSpecularMap**: `boolean`

#### Defined in

[ue/ue.d.ts:8620](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8620)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:8637](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8637)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:8638](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8638)
