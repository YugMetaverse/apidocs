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

## Properties

### Bounds

• **Bounds**: [`Box`](ue_ue.Box.md)

#### Inherited from

[VectorField](ue_ue.VectorField.md).[Bounds](ue_ue.VectorField.md#bounds)

___

### ConstructionOp

• **ConstructionOp**: [`EVectorFieldConstructionOp`](../enums/ue_ue.EVectorFieldConstructionOp.md)

___

### FrameCount

• **FrameCount**: `number`

___

### FramesPerSecond

• **FramesPerSecond**: `number`

___

### Intensity

• **Intensity**: `number`

#### Inherited from

[VectorField](ue_ue.VectorField.md).[Intensity](ue_ue.VectorField.md#intensity)

___

### NoiseField

• **NoiseField**: [`VectorFieldStatic`](ue_ue.VectorFieldStatic.md)

___

### NoiseMax

• **NoiseMax**: `number`

___

### NoiseScale

• **NoiseScale**: `number`

___

### SubImagesX

• **SubImagesX**: `number`

___

### SubImagesY

• **SubImagesY**: `number`

___

### Texture

• **Texture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### VolumeSizeX

• **VolumeSizeX**: `number`

___

### VolumeSizeY

• **VolumeSizeY**: `number`

___

### VolumeSizeZ

• **VolumeSizeZ**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[VectorField](ue_ue.VectorField.md).[__tid_Object__](ue_ue.VectorField.md#__tid_object__)

___

### \_\_tid\_VectorFieldAnimated\_\_

• **\_\_tid\_VectorFieldAnimated\_\_**: `boolean`

___

### \_\_tid\_VectorField\_\_

• **\_\_tid\_VectorField\_\_**: `boolean`

#### Inherited from

[VectorField](ue_ue.VectorField.md).[__tid_VectorField__](ue_ue.VectorField.md#__tid_vectorfield__)

___

### bLoop

• **bLoop**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[VectorField](ue_ue.VectorField.md).[GetClass](ue_ue.VectorField.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[VectorField](ue_ue.VectorField.md).[GetName](ue_ue.VectorField.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[VectorField](ue_ue.VectorField.md).[GetOuter](ue_ue.VectorField.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[VectorField](ue_ue.VectorField.md).[GetWorld](ue_ue.VectorField.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[VectorField](ue_ue.VectorField.md).[StaticClass](ue_ue.VectorField.md#staticclass)
