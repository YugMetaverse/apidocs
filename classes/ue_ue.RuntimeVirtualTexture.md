[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / RuntimeVirtualTexture

# Class: RuntimeVirtualTexture

[ue/ue](../modules/ue_ue.md).RuntimeVirtualTexture

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`RuntimeVirtualTexture`**

## Table of contents

### Constructors

- [constructor](ue_ue.RuntimeVirtualTexture.md#constructor)

### Properties

- [MaterialType](ue_ue.RuntimeVirtualTexture.md#materialtype)
- [RemoveLowMips](ue_ue.RuntimeVirtualTexture.md#removelowmips)
- [Size](ue_ue.RuntimeVirtualTexture.md#size)
- [StreamLowMips](ue_ue.RuntimeVirtualTexture.md#streamlowmips)
- [StreamingTexture](ue_ue.RuntimeVirtualTexture.md#streamingtexture)
- [TileBorderSize](ue_ue.RuntimeVirtualTexture.md#tilebordersize)
- [TileCount](ue_ue.RuntimeVirtualTexture.md#tilecount)
- [TileSize](ue_ue.RuntimeVirtualTexture.md#tilesize)
- [\_\_tid\_Object\_\_](ue_ue.RuntimeVirtualTexture.md#__tid_object__)
- [\_\_tid\_RuntimeVirtualTexture\_\_](ue_ue.RuntimeVirtualTexture.md#__tid_runtimevirtualtexture__)
- [bClearTextures](ue_ue.RuntimeVirtualTexture.md#bcleartextures)
- [bCompressTextures](ue_ue.RuntimeVirtualTexture.md#bcompresstextures)
- [bEnable](ue_ue.RuntimeVirtualTexture.md#benable)
- [bEnableScalability](ue_ue.RuntimeVirtualTexture.md#benablescalability)
- [bPrivateSpace](ue_ue.RuntimeVirtualTexture.md#bprivatespace)
- [bSinglePhysicalSpace](ue_ue.RuntimeVirtualTexture.md#bsinglephysicalspace)

### Methods

- [CreateDefaultSubobject](ue_ue.RuntimeVirtualTexture.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.RuntimeVirtualTexture.md#executeubergraph)
- [GetClass](ue_ue.RuntimeVirtualTexture.md#getclass)
- [GetName](ue_ue.RuntimeVirtualTexture.md#getname)
- [GetOuter](ue_ue.RuntimeVirtualTexture.md#getouter)
- [GetWorld](ue_ue.RuntimeVirtualTexture.md#getworld)
- [Find](ue_ue.RuntimeVirtualTexture.md#find)
- [Load](ue_ue.RuntimeVirtualTexture.md#load)
- [StaticClass](ue_ue.RuntimeVirtualTexture.md#staticclass)

## Constructors

### constructor

• **new RuntimeVirtualTexture**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### MaterialType

• **MaterialType**: [`ERuntimeVirtualTextureMaterialType`](../enums/ue_ue.ERuntimeVirtualTextureMaterialType.md)

___

### RemoveLowMips

• **RemoveLowMips**: `number`

___

### Size

• **Size**: `number`

___

### StreamLowMips

• **StreamLowMips**: `number`

___

### StreamingTexture

• **StreamingTexture**: [`RuntimeVirtualTextureStreamingProxy`](ue_ue.RuntimeVirtualTextureStreamingProxy.md)

___

### TileBorderSize

• **TileBorderSize**: `number`

___

### TileCount

• **TileCount**: `number`

___

### TileSize

• **TileSize**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_RuntimeVirtualTexture\_\_

• **\_\_tid\_RuntimeVirtualTexture\_\_**: `boolean`

___

### bClearTextures

• **bClearTextures**: `boolean`

___

### bCompressTextures

• **bCompressTextures**: `boolean`

___

### bEnable

• **bEnable**: `boolean`

___

### bEnableScalability

• **bEnableScalability**: `boolean`

___

### bPrivateSpace

• **bPrivateSpace**: `boolean`

___

### bSinglePhysicalSpace

• **bSinglePhysicalSpace**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`RuntimeVirtualTexture`](ue_ue.RuntimeVirtualTexture.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
