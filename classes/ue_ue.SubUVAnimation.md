[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SubUVAnimation

# Class: SubUVAnimation

[ue/ue](../modules/ue_ue.md).SubUVAnimation

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SubUVAnimation`**

## Table of contents

### Constructors

- [constructor](ue_ue.SubUVAnimation.md#constructor)

### Properties

- [AlphaThreshold](ue_ue.SubUVAnimation.md#alphathreshold)
- [BoundingMode](ue_ue.SubUVAnimation.md#boundingmode)
- [OpacitySourceMode](ue_ue.SubUVAnimation.md#opacitysourcemode)
- [SubImages\_Horizontal](ue_ue.SubUVAnimation.md#subimages_horizontal)
- [SubImages\_Vertical](ue_ue.SubUVAnimation.md#subimages_vertical)
- [SubUVTexture](ue_ue.SubUVAnimation.md#subuvtexture)
- [\_\_tid\_Object\_\_](ue_ue.SubUVAnimation.md#__tid_object__)
- [\_\_tid\_SubUVAnimation\_\_](ue_ue.SubUVAnimation.md#__tid_subuvanimation__)

### Methods

- [CreateDefaultSubobject](ue_ue.SubUVAnimation.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SubUVAnimation.md#executeubergraph)
- [GetClass](ue_ue.SubUVAnimation.md#getclass)
- [GetName](ue_ue.SubUVAnimation.md#getname)
- [GetOuter](ue_ue.SubUVAnimation.md#getouter)
- [GetWorld](ue_ue.SubUVAnimation.md#getworld)
- [Find](ue_ue.SubUVAnimation.md#find)
- [Load](ue_ue.SubUVAnimation.md#load)
- [StaticClass](ue_ue.SubUVAnimation.md#staticclass)

## Constructors

### constructor

• **new SubUVAnimation**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AlphaThreshold

• **AlphaThreshold**: `number`

___

### BoundingMode

• **BoundingMode**: [`ESubUVBoundingVertexCount`](../enums/ue_ue.ESubUVBoundingVertexCount.md)

___

### OpacitySourceMode

• **OpacitySourceMode**: [`EOpacitySourceMode`](../enums/ue_ue.EOpacitySourceMode.md)

___

### SubImages\_Horizontal

• **SubImages\_Horizontal**: `number`

___

### SubImages\_Vertical

• **SubImages\_Vertical**: `number`

___

### SubUVTexture

• **SubUVTexture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_SubUVAnimation\_\_

• **\_\_tid\_SubUVAnimation\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SubUVAnimation`](ue_ue.SubUVAnimation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SubUVAnimation`](ue_ue.SubUVAnimation.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SubUVAnimation`](ue_ue.SubUVAnimation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SubUVAnimation`](ue_ue.SubUVAnimation.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
