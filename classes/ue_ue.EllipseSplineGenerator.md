[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EllipseSplineGenerator

# Class: EllipseSplineGenerator

[ue/ue](../modules/ue_ue.md).EllipseSplineGenerator

## Hierarchy

- [`SplineGeneratorBase`](ue_ue.SplineGeneratorBase.md)

  ↳ **`EllipseSplineGenerator`**

## Table of contents

### Constructors

- [constructor](ue_ue.EllipseSplineGenerator.md#constructor)

### Properties

- [Length](ue_ue.EllipseSplineGenerator.md#length)
- [NumberOfPoints](ue_ue.EllipseSplineGenerator.md#numberofpoints)
- [ShapeAddMode](ue_ue.EllipseSplineGenerator.md#shapeaddmode)
- [Width](ue_ue.EllipseSplineGenerator.md#width)
- [\_\_tid\_EllipseSplineGenerator\_\_](ue_ue.EllipseSplineGenerator.md#__tid_ellipsesplinegenerator__)
- [\_\_tid\_Object\_\_](ue_ue.EllipseSplineGenerator.md#__tid_object__)
- [\_\_tid\_SplineGeneratorBase\_\_](ue_ue.EllipseSplineGenerator.md#__tid_splinegeneratorbase__)
- [bBranchRight](ue_ue.EllipseSplineGenerator.md#bbranchright)
- [bKeepFirstKeyTangent](ue_ue.EllipseSplineGenerator.md#bkeepfirstkeytangent)
- [bReverseDir](ue_ue.EllipseSplineGenerator.md#breversedir)

### Methods

- [CreateDefaultSubobject](ue_ue.EllipseSplineGenerator.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EllipseSplineGenerator.md#executeubergraph)
- [GetClass](ue_ue.EllipseSplineGenerator.md#getclass)
- [GetName](ue_ue.EllipseSplineGenerator.md#getname)
- [GetOuter](ue_ue.EllipseSplineGenerator.md#getouter)
- [GetWorld](ue_ue.EllipseSplineGenerator.md#getworld)
- [Find](ue_ue.EllipseSplineGenerator.md#find)
- [Load](ue_ue.EllipseSplineGenerator.md#load)
- [StaticClass](ue_ue.EllipseSplineGenerator.md#staticclass)

## Constructors

### constructor

• **new EllipseSplineGenerator**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[constructor](ue_ue.SplineGeneratorBase.md#constructor)

## Properties

### Length

• **Length**: `number`

___

### NumberOfPoints

• **NumberOfPoints**: `number`

___

### ShapeAddMode

• **ShapeAddMode**: [`EShapeAddMode`](../enums/ue_ue.EShapeAddMode.md)

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[ShapeAddMode](ue_ue.SplineGeneratorBase.md#shapeaddmode)

___

### Width

• **Width**: `number`

___

### \_\_tid\_EllipseSplineGenerator\_\_

• **\_\_tid\_EllipseSplineGenerator\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[__tid_Object__](ue_ue.SplineGeneratorBase.md#__tid_object__)

___

### \_\_tid\_SplineGeneratorBase\_\_

• **\_\_tid\_SplineGeneratorBase\_\_**: `boolean`

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[__tid_SplineGeneratorBase__](ue_ue.SplineGeneratorBase.md#__tid_splinegeneratorbase__)

___

### bBranchRight

• **bBranchRight**: `boolean`

___

### bKeepFirstKeyTangent

• **bKeepFirstKeyTangent**: `boolean`

___

### bReverseDir

• **bReverseDir**: `boolean`

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

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[CreateDefaultSubobject](ue_ue.SplineGeneratorBase.md#createdefaultsubobject)

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

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[ExecuteUbergraph](ue_ue.SplineGeneratorBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[GetClass](ue_ue.SplineGeneratorBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[GetName](ue_ue.SplineGeneratorBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[GetOuter](ue_ue.SplineGeneratorBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[GetWorld](ue_ue.SplineGeneratorBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EllipseSplineGenerator`](ue_ue.EllipseSplineGenerator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EllipseSplineGenerator`](ue_ue.EllipseSplineGenerator.md)

#### Overrides

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[Find](ue_ue.SplineGeneratorBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EllipseSplineGenerator`](ue_ue.EllipseSplineGenerator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EllipseSplineGenerator`](ue_ue.EllipseSplineGenerator.md)

#### Overrides

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[Load](ue_ue.SplineGeneratorBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[StaticClass](ue_ue.SplineGeneratorBase.md#staticclass)
