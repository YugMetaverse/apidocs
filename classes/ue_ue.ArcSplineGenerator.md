[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ArcSplineGenerator

# Class: ArcSplineGenerator

[ue/ue](../modules/ue_ue.md).ArcSplineGenerator

## Hierarchy

- [`SplineGeneratorBase`](ue_ue.SplineGeneratorBase.md)

  ↳ **`ArcSplineGenerator`**

## Table of contents

### Constructors

- [constructor](ue_ue.ArcSplineGenerator.md#constructor)

### Properties

- [Degrees](ue_ue.ArcSplineGenerator.md#degrees)
- [NumberOfPoints](ue_ue.ArcSplineGenerator.md#numberofpoints)
- [Radius](ue_ue.ArcSplineGenerator.md#radius)
- [ShapeAddMode](ue_ue.ArcSplineGenerator.md#shapeaddmode)
- [\_\_tid\_ArcSplineGenerator\_\_](ue_ue.ArcSplineGenerator.md#__tid_arcsplinegenerator__)
- [\_\_tid\_Object\_\_](ue_ue.ArcSplineGenerator.md#__tid_object__)
- [\_\_tid\_SplineGeneratorBase\_\_](ue_ue.ArcSplineGenerator.md#__tid_splinegeneratorbase__)
- [bBranchRight](ue_ue.ArcSplineGenerator.md#bbranchright)
- [bKeepFirstKeyTangent](ue_ue.ArcSplineGenerator.md#bkeepfirstkeytangent)
- [bReverseDir](ue_ue.ArcSplineGenerator.md#breversedir)

### Methods

- [CreateDefaultSubobject](ue_ue.ArcSplineGenerator.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ArcSplineGenerator.md#executeubergraph)
- [GetClass](ue_ue.ArcSplineGenerator.md#getclass)
- [GetName](ue_ue.ArcSplineGenerator.md#getname)
- [GetOuter](ue_ue.ArcSplineGenerator.md#getouter)
- [GetWorld](ue_ue.ArcSplineGenerator.md#getworld)
- [Find](ue_ue.ArcSplineGenerator.md#find)
- [Load](ue_ue.ArcSplineGenerator.md#load)
- [StaticClass](ue_ue.ArcSplineGenerator.md#staticclass)

## Constructors

### constructor

• **new ArcSplineGenerator**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[constructor](ue_ue.SplineGeneratorBase.md#constructor)

#### Defined in

[ue/ue.d.ts:21189](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21189)

## Properties

### Degrees

• **Degrees**: `number`

#### Defined in

[ue/ue.d.ts:21192](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21192)

___

### NumberOfPoints

• **NumberOfPoints**: `number`

#### Defined in

[ue/ue.d.ts:21190](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21190)

___

### Radius

• **Radius**: `number`

#### Defined in

[ue/ue.d.ts:21191](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21191)

___

### ShapeAddMode

• **ShapeAddMode**: [`EShapeAddMode`](../enums/ue_ue.EShapeAddMode.md)

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[ShapeAddMode](ue_ue.SplineGeneratorBase.md#shapeaddmode)

#### Defined in

[ue/ue.d.ts:21180](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21180)

___

### \_\_tid\_ArcSplineGenerator\_\_

• **\_\_tid\_ArcSplineGenerator\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:21200](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21200)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[__tid_Object__](ue_ue.SplineGeneratorBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SplineGeneratorBase\_\_

• **\_\_tid\_SplineGeneratorBase\_\_**: `boolean`

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[__tid_SplineGeneratorBase__](ue_ue.SplineGeneratorBase.md#__tid_splinegeneratorbase__)

#### Defined in

[ue/ue.d.ts:21185](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21185)

___

### bBranchRight

• **bBranchRight**: `boolean`

#### Defined in

[ue/ue.d.ts:21195](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21195)

___

### bKeepFirstKeyTangent

• **bKeepFirstKeyTangent**: `boolean`

#### Defined in

[ue/ue.d.ts:21194](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21194)

___

### bReverseDir

• **bReverseDir**: `boolean`

#### Defined in

[ue/ue.d.ts:21193](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21193)

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

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[ExecuteUbergraph](ue_ue.SplineGeneratorBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[GetClass](ue_ue.SplineGeneratorBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[GetName](ue_ue.SplineGeneratorBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[GetOuter](ue_ue.SplineGeneratorBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[GetWorld](ue_ue.SplineGeneratorBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ArcSplineGenerator`](ue_ue.ArcSplineGenerator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ArcSplineGenerator`](ue_ue.ArcSplineGenerator.md)

#### Overrides

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[Find](ue_ue.SplineGeneratorBase.md#find)

#### Defined in

[ue/ue.d.ts:21197](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21197)

___

### Load

▸ `Static` **Load**(`InName`): [`ArcSplineGenerator`](ue_ue.ArcSplineGenerator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ArcSplineGenerator`](ue_ue.ArcSplineGenerator.md)

#### Overrides

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[Load](ue_ue.SplineGeneratorBase.md#load)

#### Defined in

[ue/ue.d.ts:21198](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21198)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[StaticClass](ue_ue.SplineGeneratorBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:21196](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21196)
