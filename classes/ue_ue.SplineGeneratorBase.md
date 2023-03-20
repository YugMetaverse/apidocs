[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SplineGeneratorBase

# Class: SplineGeneratorBase

[ue/ue](../modules/ue_ue.md).SplineGeneratorBase

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SplineGeneratorBase`**

  ↳↳ [`ArcSplineGenerator`](ue_ue.ArcSplineGenerator.md)

  ↳↳ [`CircleSplineGenerator`](ue_ue.CircleSplineGenerator.md)

  ↳↳ [`EllipseSplineGenerator`](ue_ue.EllipseSplineGenerator.md)

  ↳↳ [`LineSplineGenerator`](ue_ue.LineSplineGenerator.md)

  ↳↳ [`RectangleSplineGenerator`](ue_ue.RectangleSplineGenerator.md)

  ↳↳ [`SquareSplineGenerator`](ue_ue.SquareSplineGenerator.md)

## Table of contents

### Constructors

- [constructor](ue_ue.SplineGeneratorBase.md#constructor)

### Properties

- [ShapeAddMode](ue_ue.SplineGeneratorBase.md#shapeaddmode)
- [\_\_tid\_Object\_\_](ue_ue.SplineGeneratorBase.md#__tid_object__)
- [\_\_tid\_SplineGeneratorBase\_\_](ue_ue.SplineGeneratorBase.md#__tid_splinegeneratorbase__)

### Methods

- [CreateDefaultSubobject](ue_ue.SplineGeneratorBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SplineGeneratorBase.md#executeubergraph)
- [GetClass](ue_ue.SplineGeneratorBase.md#getclass)
- [GetName](ue_ue.SplineGeneratorBase.md#getname)
- [GetOuter](ue_ue.SplineGeneratorBase.md#getouter)
- [GetWorld](ue_ue.SplineGeneratorBase.md#getworld)
- [Find](ue_ue.SplineGeneratorBase.md#find)
- [Load](ue_ue.SplineGeneratorBase.md#load)
- [StaticClass](ue_ue.SplineGeneratorBase.md#staticclass)

## Constructors

### constructor

• **new SplineGeneratorBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ShapeAddMode

• **ShapeAddMode**: [`EShapeAddMode`](../enums/ue_ue.EShapeAddMode.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_SplineGeneratorBase\_\_

• **\_\_tid\_SplineGeneratorBase\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SplineGeneratorBase`](ue_ue.SplineGeneratorBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SplineGeneratorBase`](ue_ue.SplineGeneratorBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SplineGeneratorBase`](ue_ue.SplineGeneratorBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SplineGeneratorBase`](ue_ue.SplineGeneratorBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
