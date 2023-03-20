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

## Properties

### AmbientOcclusionConstant

• **AmbientOcclusionConstant**: `number`

___

### AmbientOcclusionTextureSize

• **AmbientOcclusionTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### BlendMode

• **BlendMode**: [`EBlendMode`](../enums/ue_ue.EBlendMode.md)

___

### DiffuseTextureSize

• **DiffuseTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### EmissiveTextureSize

• **EmissiveTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### GutterSpace

• **GutterSpace**: `number`

___

### MaterialMergeType

• **MaterialMergeType**: [`EMaterialMergeType`](../enums/ue_ue.EMaterialMergeType.md)

___

### MetallicConstant

• **MetallicConstant**: `number`

___

### MetallicTextureSize

• **MetallicTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### NormalTextureSize

• **NormalTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### OpacityConstant

• **OpacityConstant**: `number`

___

### OpacityMaskConstant

• **OpacityMaskConstant**: `number`

___

### OpacityMaskTextureSize

• **OpacityMaskTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### OpacityTextureSize

• **OpacityTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### RoughnessConstant

• **RoughnessConstant**: `number`

___

### RoughnessTextureSize

• **RoughnessTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### SpecularConstant

• **SpecularConstant**: `number`

___

### SpecularTextureSize

• **SpecularTextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### TextureSize

• **TextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### TextureSizingType

• **TextureSizingType**: [`ETextureSizingType`](../enums/ue_ue.ETextureSizingType.md)

___

### \_\_tid\_MaterialProxySettings\_\_

• `Private` **\_\_tid\_MaterialProxySettings\_\_**: `boolean`

___

### bAllowTwoSidedMaterial

• **bAllowTwoSidedMaterial**: `boolean`

___

### bAmbientOcclusionMap

• **bAmbientOcclusionMap**: `boolean`

___

### bEmissiveMap

• **bEmissiveMap**: `boolean`

___

### bMetallicMap

• **bMetallicMap**: `boolean`

___

### bNormalMap

• **bNormalMap**: `boolean`

___

### bOpacityMap

• **bOpacityMap**: `boolean`

___

### bOpacityMaskMap

• **bOpacityMaskMap**: `boolean`

___

### bRoughnessMap

• **bRoughnessMap**: `boolean`

___

### bSpecularMap

• **bSpecularMap**: `boolean`

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
