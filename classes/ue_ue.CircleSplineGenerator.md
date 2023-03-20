[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CircleSplineGenerator

# Class: CircleSplineGenerator

[ue/ue](../modules/ue_ue.md).CircleSplineGenerator

## Hierarchy

- [`SplineGeneratorBase`](ue_ue.SplineGeneratorBase.md)

  ↳ **`CircleSplineGenerator`**

## Table of contents

### Constructors

- [constructor](ue_ue.CircleSplineGenerator.md#constructor)

### Properties

- [NumberOfPoints](ue_ue.CircleSplineGenerator.md#numberofpoints)
- [Radius](ue_ue.CircleSplineGenerator.md#radius)
- [ShapeAddMode](ue_ue.CircleSplineGenerator.md#shapeaddmode)
- [\_\_tid\_CircleSplineGenerator\_\_](ue_ue.CircleSplineGenerator.md#__tid_circlesplinegenerator__)
- [\_\_tid\_Object\_\_](ue_ue.CircleSplineGenerator.md#__tid_object__)
- [\_\_tid\_SplineGeneratorBase\_\_](ue_ue.CircleSplineGenerator.md#__tid_splinegeneratorbase__)
- [bBranchRight](ue_ue.CircleSplineGenerator.md#bbranchright)
- [bKeepFirstKeyTangent](ue_ue.CircleSplineGenerator.md#bkeepfirstkeytangent)
- [bReverseDir](ue_ue.CircleSplineGenerator.md#breversedir)

### Methods

- [CreateDefaultSubobject](ue_ue.CircleSplineGenerator.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CircleSplineGenerator.md#executeubergraph)
- [GetClass](ue_ue.CircleSplineGenerator.md#getclass)
- [GetName](ue_ue.CircleSplineGenerator.md#getname)
- [GetOuter](ue_ue.CircleSplineGenerator.md#getouter)
- [GetWorld](ue_ue.CircleSplineGenerator.md#getworld)
- [Find](ue_ue.CircleSplineGenerator.md#find)
- [Load](ue_ue.CircleSplineGenerator.md#load)
- [StaticClass](ue_ue.CircleSplineGenerator.md#staticclass)

## Constructors

### constructor

• **new CircleSplineGenerator**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[constructor](ue_ue.SplineGeneratorBase.md#constructor)

## Properties

### NumberOfPoints

• **NumberOfPoints**: `number`

___

### Radius

• **Radius**: `number`

___

### ShapeAddMode

• **ShapeAddMode**: [`EShapeAddMode`](../enums/ue_ue.EShapeAddMode.md)

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[ShapeAddMode](ue_ue.SplineGeneratorBase.md#shapeaddmode)

___

### \_\_tid\_CircleSplineGenerator\_\_

• **\_\_tid\_CircleSplineGenerator\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CircleSplineGenerator`](ue_ue.CircleSplineGenerator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CircleSplineGenerator`](ue_ue.CircleSplineGenerator.md)

#### Overrides

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[Find](ue_ue.SplineGeneratorBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`CircleSplineGenerator`](ue_ue.CircleSplineGenerator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CircleSplineGenerator`](ue_ue.CircleSplineGenerator.md)

#### Overrides

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[Load](ue_ue.SplineGeneratorBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[StaticClass](ue_ue.SplineGeneratorBase.md#staticclass)
