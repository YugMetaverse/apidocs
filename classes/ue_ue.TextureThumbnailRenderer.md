[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TextureThumbnailRenderer

# Class: TextureThumbnailRenderer

[ue/ue](../modules/ue_ue.md).TextureThumbnailRenderer

## Hierarchy

- [`ThumbnailRenderer`](ue_ue.ThumbnailRenderer.md)

  ↳ **`TextureThumbnailRenderer`**

  ↳↳ [`FontThumbnailRenderer`](ue_ue.FontThumbnailRenderer.md)

  ↳↳ [`ParticleSystemThumbnailRenderer`](ue_ue.ParticleSystemThumbnailRenderer.md)

  ↳↳ [`SubsurfaceProfileRenderer`](ue_ue.SubsurfaceProfileRenderer.md)

  ↳↳ [`Texture2DArrayThumbnailRenderer`](ue_ue.Texture2DArrayThumbnailRenderer.md)

  ↳↳ [`TextureCubeThumbnailRenderer`](ue_ue.TextureCubeThumbnailRenderer.md)

## Table of contents

### Constructors

- [constructor](ue_ue.TextureThumbnailRenderer.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.TextureThumbnailRenderer.md#__tid_object__)
- [\_\_tid\_TextureThumbnailRenderer\_\_](ue_ue.TextureThumbnailRenderer.md#__tid_texturethumbnailrenderer__)
- [\_\_tid\_ThumbnailRenderer\_\_](ue_ue.TextureThumbnailRenderer.md#__tid_thumbnailrenderer__)

### Methods

- [CreateDefaultSubobject](ue_ue.TextureThumbnailRenderer.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TextureThumbnailRenderer.md#executeubergraph)
- [GetClass](ue_ue.TextureThumbnailRenderer.md#getclass)
- [GetName](ue_ue.TextureThumbnailRenderer.md#getname)
- [GetOuter](ue_ue.TextureThumbnailRenderer.md#getouter)
- [GetWorld](ue_ue.TextureThumbnailRenderer.md#getworld)
- [Find](ue_ue.TextureThumbnailRenderer.md#find)
- [Load](ue_ue.TextureThumbnailRenderer.md#load)
- [StaticClass](ue_ue.TextureThumbnailRenderer.md#staticclass)

## Constructors

### constructor

• **new TextureThumbnailRenderer**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ThumbnailRenderer](ue_ue.ThumbnailRenderer.md).[constructor](ue_ue.ThumbnailRenderer.md#constructor)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ThumbnailRenderer](ue_ue.ThumbnailRenderer.md).[__tid_Object__](ue_ue.ThumbnailRenderer.md#__tid_object__)

___

### \_\_tid\_TextureThumbnailRenderer\_\_

• **\_\_tid\_TextureThumbnailRenderer\_\_**: `boolean`

___

### \_\_tid\_ThumbnailRenderer\_\_

• **\_\_tid\_ThumbnailRenderer\_\_**: `boolean`

#### Inherited from

[ThumbnailRenderer](ue_ue.ThumbnailRenderer.md).[__tid_ThumbnailRenderer__](ue_ue.ThumbnailRenderer.md#__tid_thumbnailrenderer__)

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

[ThumbnailRenderer](ue_ue.ThumbnailRenderer.md).[CreateDefaultSubobject](ue_ue.ThumbnailRenderer.md#createdefaultsubobject)

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

[ThumbnailRenderer](ue_ue.ThumbnailRenderer.md).[ExecuteUbergraph](ue_ue.ThumbnailRenderer.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ThumbnailRenderer](ue_ue.ThumbnailRenderer.md).[GetClass](ue_ue.ThumbnailRenderer.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ThumbnailRenderer](ue_ue.ThumbnailRenderer.md).[GetName](ue_ue.ThumbnailRenderer.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ThumbnailRenderer](ue_ue.ThumbnailRenderer.md).[GetOuter](ue_ue.ThumbnailRenderer.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ThumbnailRenderer](ue_ue.ThumbnailRenderer.md).[GetWorld](ue_ue.ThumbnailRenderer.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TextureThumbnailRenderer`](ue_ue.TextureThumbnailRenderer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TextureThumbnailRenderer`](ue_ue.TextureThumbnailRenderer.md)

#### Overrides

[ThumbnailRenderer](ue_ue.ThumbnailRenderer.md).[Find](ue_ue.ThumbnailRenderer.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TextureThumbnailRenderer`](ue_ue.TextureThumbnailRenderer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TextureThumbnailRenderer`](ue_ue.TextureThumbnailRenderer.md)

#### Overrides

[ThumbnailRenderer](ue_ue.ThumbnailRenderer.md).[Load](ue_ue.ThumbnailRenderer.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ThumbnailRenderer](ue_ue.ThumbnailRenderer.md).[StaticClass](ue_ue.ThumbnailRenderer.md#staticclass)
