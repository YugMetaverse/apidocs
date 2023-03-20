[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VectorFieldAnimated

# Class: VectorFieldAnimated

[ue/ue](../modules/ue_ue.md).VectorFieldAnimated

## Hierarchy

- [`VectorField`](ue_ue.VectorField.md)

  ↳ **`VectorFieldAnimated`**

## Table of contents

### Constructors

- [constructor](ue_ue.VectorFieldAnimated.md#constructor)

### Properties

- [Bounds](ue_ue.VectorFieldAnimated.md#bounds)
- [ConstructionOp](ue_ue.VectorFieldAnimated.md#constructionop)
- [FrameCount](ue_ue.VectorFieldAnimated.md#framecount)
- [FramesPerSecond](ue_ue.VectorFieldAnimated.md#framespersecond)
- [Intensity](ue_ue.VectorFieldAnimated.md#intensity)
- [NoiseField](ue_ue.VectorFieldAnimated.md#noisefield)
- [NoiseMax](ue_ue.VectorFieldAnimated.md#noisemax)
- [NoiseScale](ue_ue.VectorFieldAnimated.md#noisescale)
- [SubImagesX](ue_ue.VectorFieldAnimated.md#subimagesx)
- [SubImagesY](ue_ue.VectorFieldAnimated.md#subimagesy)
- [Texture](ue_ue.VectorFieldAnimated.md#texture)
- [VolumeSizeX](ue_ue.VectorFieldAnimated.md#volumesizex)
- [VolumeSizeY](ue_ue.VectorFieldAnimated.md#volumesizey)
- [VolumeSizeZ](ue_ue.VectorFieldAnimated.md#volumesizez)
- [\_\_tid\_Object\_\_](ue_ue.VectorFieldAnimated.md#__tid_object__)
- [\_\_tid\_VectorFieldAnimated\_\_](ue_ue.VectorFieldAnimated.md#__tid_vectorfieldanimated__)
- [\_\_tid\_VectorField\_\_](ue_ue.VectorFieldAnimated.md#__tid_vectorfield__)
- [bLoop](ue_ue.VectorFieldAnimated.md#bloop)

### Methods

- [CreateDefaultSubobject](ue_ue.VectorFieldAnimated.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.VectorFieldAnimated.md#executeubergraph)
- [GetClass](ue_ue.VectorFieldAnimated.md#getclass)
- [GetName](ue_ue.VectorFieldAnimated.md#getname)
- [GetOuter](ue_ue.VectorFieldAnimated.md#getouter)
- [GetWorld](ue_ue.VectorFieldAnimated.md#getworld)
- [Find](ue_ue.VectorFieldAnimated.md#find)
- [Load](ue_ue.VectorFieldAnimated.md#load)
- [StaticClass](ue_ue.VectorFieldAnimated.md#staticclass)

## Constructors

### constructor

• **new VectorFieldAnimated**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[VectorField](ue_ue.VectorField.md).[constructor](ue_ue.VectorField.md#constructor)

#### Defined in

[ue/ue.d.ts:65085](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65085)

## Properties

### Bounds

• **Bounds**: [`Box`](ue_ue.Box.md)

#### Inherited from

[VectorField](ue_ue.VectorField.md).[Bounds](ue_ue.VectorField.md#bounds)

#### Defined in

[ue/ue.d.ts:56432](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56432)

___

### ConstructionOp

• **ConstructionOp**: [`EVectorFieldConstructionOp`](../enums/ue_ue.EVectorFieldConstructionOp.md)

#### Defined in

[ue/ue.d.ts:65087](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65087)

___

### FrameCount

• **FrameCount**: `number`

#### Defined in

[ue/ue.d.ts:65093](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65093)

___

### FramesPerSecond

• **FramesPerSecond**: `number`

#### Defined in

[ue/ue.d.ts:65094](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65094)

___

### Intensity

• **Intensity**: `number`

#### Inherited from

[VectorField](ue_ue.VectorField.md).[Intensity](ue_ue.VectorField.md#intensity)

#### Defined in

[ue/ue.d.ts:56433](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56433)

___

### NoiseField

• **NoiseField**: [`VectorFieldStatic`](ue_ue.VectorFieldStatic.md)

#### Defined in

[ue/ue.d.ts:65096](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65096)

___

### NoiseMax

• **NoiseMax**: `number`

#### Defined in

[ue/ue.d.ts:65098](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65098)

___

### NoiseScale

• **NoiseScale**: `number`

#### Defined in

[ue/ue.d.ts:65097](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65097)

___

### SubImagesX

• **SubImagesX**: `number`

#### Defined in

[ue/ue.d.ts:65091](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65091)

___

### SubImagesY

• **SubImagesY**: `number`

#### Defined in

[ue/ue.d.ts:65092](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65092)

___

### Texture

• **Texture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:65086](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65086)

___

### VolumeSizeX

• **VolumeSizeX**: `number`

#### Defined in

[ue/ue.d.ts:65088](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65088)

___

### VolumeSizeY

• **VolumeSizeY**: `number`

#### Defined in

[ue/ue.d.ts:65089](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65089)

___

### VolumeSizeZ

• **VolumeSizeZ**: `number`

#### Defined in

[ue/ue.d.ts:65090](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65090)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[VectorField](ue_ue.VectorField.md).[__tid_Object__](ue_ue.VectorField.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_VectorFieldAnimated\_\_

• **\_\_tid\_VectorFieldAnimated\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:65103](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65103)

___

### \_\_tid\_VectorField\_\_

• **\_\_tid\_VectorField\_\_**: `boolean`

#### Inherited from

[VectorField](ue_ue.VectorField.md).[__tid_VectorField__](ue_ue.VectorField.md#__tid_vectorfield__)

#### Defined in

[ue/ue.d.ts:56438](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56438)

___

### bLoop

• **bLoop**: `boolean`

#### Defined in

[ue/ue.d.ts:65095](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65095)

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

[VectorField](ue_ue.VectorField.md).[CreateDefaultSubobject](ue_ue.VectorField.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[VectorField](ue_ue.VectorField.md).[ExecuteUbergraph](ue_ue.VectorField.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[VectorField](ue_ue.VectorField.md).[GetClass](ue_ue.VectorField.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[VectorField](ue_ue.VectorField.md).[GetName](ue_ue.VectorField.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[VectorField](ue_ue.VectorField.md).[GetOuter](ue_ue.VectorField.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[VectorField](ue_ue.VectorField.md).[GetWorld](ue_ue.VectorField.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VectorFieldAnimated`](ue_ue.VectorFieldAnimated.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VectorFieldAnimated`](ue_ue.VectorFieldAnimated.md)

#### Overrides

[VectorField](ue_ue.VectorField.md).[Find](ue_ue.VectorField.md#find)

#### Defined in

[ue/ue.d.ts:65100](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65100)

___

### Load

▸ `Static` **Load**(`InName`): [`VectorFieldAnimated`](ue_ue.VectorFieldAnimated.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VectorFieldAnimated`](ue_ue.VectorFieldAnimated.md)

#### Overrides

[VectorField](ue_ue.VectorField.md).[Load](ue_ue.VectorField.md#load)

#### Defined in

[ue/ue.d.ts:65101](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65101)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[VectorField](ue_ue.VectorField.md).[StaticClass](ue_ue.VectorField.md#staticclass)

#### Defined in

[ue/ue.d.ts:65099](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65099)
