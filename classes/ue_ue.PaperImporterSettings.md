[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PaperImporterSettings

# Class: PaperImporterSettings

[ue/ue](../modules/ue_ue.md).PaperImporterSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PaperImporterSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.PaperImporterSettings.md#constructor)

### Properties

- [BaseMapTextureSuffixes](ue_ue.PaperImporterSettings.md#basemaptexturesuffixes)
- [DefaultPixelsPerUnrealUnit](ue_ue.PaperImporterSettings.md#defaultpixelsperunrealunit)
- [DefaultSpriteTextureCompression](ue_ue.PaperImporterSettings.md#defaultspritetexturecompression)
- [DefaultSpriteTextureGroup](ue_ue.PaperImporterSettings.md#defaultspritetexturegroup)
- [LitDefaultMaskedMaterialName](ue_ue.PaperImporterSettings.md#litdefaultmaskedmaterialname)
- [LitDefaultOpaqueMaterialName](ue_ue.PaperImporterSettings.md#litdefaultopaquematerialname)
- [LitDefaultTranslucentMaterialName](ue_ue.PaperImporterSettings.md#litdefaulttranslucentmaterialname)
- [NormalMapTextureSuffixes](ue_ue.PaperImporterSettings.md#normalmaptexturesuffixes)
- [UnlitDefaultMaskedMaterialName](ue_ue.PaperImporterSettings.md#unlitdefaultmaskedmaterialname)
- [UnlitDefaultOpaqueMaterialName](ue_ue.PaperImporterSettings.md#unlitdefaultopaquematerialname)
- [UnlitDefaultTranslucentMaterialName](ue_ue.PaperImporterSettings.md#unlitdefaulttranslucentmaterialname)
- [\_\_tid\_Object\_\_](ue_ue.PaperImporterSettings.md#__tid_object__)
- [\_\_tid\_PaperImporterSettings\_\_](ue_ue.PaperImporterSettings.md#__tid_paperimportersettings__)
- [bAnalysisCanUseOpaque](ue_ue.PaperImporterSettings.md#banalysiscanuseopaque)
- [bOverrideTextureCompression](ue_ue.PaperImporterSettings.md#boverridetexturecompression)
- [bPickBestMaterialWhenCreatingSprites](ue_ue.PaperImporterSettings.md#bpickbestmaterialwhencreatingsprites)
- [bPickBestMaterialWhenCreatingTileMaps](ue_ue.PaperImporterSettings.md#bpickbestmaterialwhencreatingtilemaps)

### Methods

- [CreateDefaultSubobject](ue_ue.PaperImporterSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PaperImporterSettings.md#executeubergraph)
- [GetClass](ue_ue.PaperImporterSettings.md#getclass)
- [GetName](ue_ue.PaperImporterSettings.md#getname)
- [GetOuter](ue_ue.PaperImporterSettings.md#getouter)
- [GetWorld](ue_ue.PaperImporterSettings.md#getworld)
- [Find](ue_ue.PaperImporterSettings.md#find)
- [Load](ue_ue.PaperImporterSettings.md#load)
- [StaticClass](ue_ue.PaperImporterSettings.md#staticclass)

## Constructors

### constructor

• **new PaperImporterSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### BaseMapTextureSuffixes

• **BaseMapTextureSuffixes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### DefaultPixelsPerUnrealUnit

• **DefaultPixelsPerUnrealUnit**: `number`

___

### DefaultSpriteTextureCompression

• **DefaultSpriteTextureCompression**: [`TextureCompressionSettings`](../enums/ue_ue.TextureCompressionSettings.md)

___

### DefaultSpriteTextureGroup

• **DefaultSpriteTextureGroup**: [`TextureGroup`](../enums/ue_ue.TextureGroup.md)

___

### LitDefaultMaskedMaterialName

• **LitDefaultMaskedMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### LitDefaultOpaqueMaterialName

• **LitDefaultOpaqueMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### LitDefaultTranslucentMaterialName

• **LitDefaultTranslucentMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### NormalMapTextureSuffixes

• **NormalMapTextureSuffixes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### UnlitDefaultMaskedMaterialName

• **UnlitDefaultMaskedMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### UnlitDefaultOpaqueMaterialName

• **UnlitDefaultOpaqueMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### UnlitDefaultTranslucentMaterialName

• **UnlitDefaultTranslucentMaterialName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PaperImporterSettings\_\_

• **\_\_tid\_PaperImporterSettings\_\_**: `boolean`

___

### bAnalysisCanUseOpaque

• **bAnalysisCanUseOpaque**: `boolean`

___

### bOverrideTextureCompression

• **bOverrideTextureCompression**: `boolean`

___

### bPickBestMaterialWhenCreatingSprites

• **bPickBestMaterialWhenCreatingSprites**: `boolean`

___

### bPickBestMaterialWhenCreatingTileMaps

• **bPickBestMaterialWhenCreatingTileMaps**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PaperImporterSettings`](ue_ue.PaperImporterSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PaperImporterSettings`](ue_ue.PaperImporterSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PaperImporterSettings`](ue_ue.PaperImporterSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PaperImporterSettings`](ue_ue.PaperImporterSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
