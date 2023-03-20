[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LineSplineGenerator

# Class: LineSplineGenerator

[ue/ue](../modules/ue_ue.md).LineSplineGenerator

## Hierarchy

- [`SplineGeneratorBase`](ue_ue.SplineGeneratorBase.md)

  ↳ **`LineSplineGenerator`**

## Table of contents

### Constructors

- [constructor](ue_ue.LineSplineGenerator.md#constructor)

### Properties

- [Length](ue_ue.LineSplineGenerator.md#length)
- [NumberOfPoints](ue_ue.LineSplineGenerator.md#numberofpoints)
- [ShapeAddMode](ue_ue.LineSplineGenerator.md#shapeaddmode)
- [\_\_tid\_LineSplineGenerator\_\_](ue_ue.LineSplineGenerator.md#__tid_linesplinegenerator__)
- [\_\_tid\_Object\_\_](ue_ue.LineSplineGenerator.md#__tid_object__)
- [\_\_tid\_SplineGeneratorBase\_\_](ue_ue.LineSplineGenerator.md#__tid_splinegeneratorbase__)
- [bEnableUpToNextPoint](ue_ue.LineSplineGenerator.md#benableuptonextpoint)
- [bUpToNextPoint](ue_ue.LineSplineGenerator.md#buptonextpoint)

### Methods

- [CreateDefaultSubobject](ue_ue.LineSplineGenerator.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LineSplineGenerator.md#executeubergraph)
- [GetClass](ue_ue.LineSplineGenerator.md#getclass)
- [GetName](ue_ue.LineSplineGenerator.md#getname)
- [GetOuter](ue_ue.LineSplineGenerator.md#getouter)
- [GetWorld](ue_ue.LineSplineGenerator.md#getworld)
- [Find](ue_ue.LineSplineGenerator.md#find)
- [Load](ue_ue.LineSplineGenerator.md#load)
- [StaticClass](ue_ue.LineSplineGenerator.md#staticclass)

## Constructors

### constructor

• **new LineSplineGenerator**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[constructor](ue_ue.SplineGeneratorBase.md#constructor)

#### Defined in

[ue/ue.d.ts:45590](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45590)

## Properties

### Length

• **Length**: `number`

#### Defined in

[ue/ue.d.ts:45592](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45592)

___

### NumberOfPoints

• **NumberOfPoints**: `number`

#### Defined in

[ue/ue.d.ts:45591](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45591)

___

### ShapeAddMode

• **ShapeAddMode**: [`EShapeAddMode`](../enums/ue_ue.EShapeAddMode.md)

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[ShapeAddMode](ue_ue.SplineGeneratorBase.md#shapeaddmode)

#### Defined in

[ue/ue.d.ts:21180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21180)

___

### \_\_tid\_LineSplineGenerator\_\_

• **\_\_tid\_LineSplineGenerator\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:45599](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45599)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[__tid_Object__](ue_ue.SplineGeneratorBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_SplineGeneratorBase\_\_

• **\_\_tid\_SplineGeneratorBase\_\_**: `boolean`

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[__tid_SplineGeneratorBase__](ue_ue.SplineGeneratorBase.md#__tid_splinegeneratorbase__)

#### Defined in

[ue/ue.d.ts:21185](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21185)

___

### bEnableUpToNextPoint

• **bEnableUpToNextPoint**: `boolean`

#### Defined in

[ue/ue.d.ts:45593](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45593)

___

### bUpToNextPoint

• **bUpToNextPoint**: `boolean`

#### Defined in

[ue/ue.d.ts:45594](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45594)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[GetClass](ue_ue.SplineGeneratorBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[GetName](ue_ue.SplineGeneratorBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[GetOuter](ue_ue.SplineGeneratorBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[GetWorld](ue_ue.SplineGeneratorBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LineSplineGenerator`](ue_ue.LineSplineGenerator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LineSplineGenerator`](ue_ue.LineSplineGenerator.md)

#### Overrides

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[Find](ue_ue.SplineGeneratorBase.md#find)

#### Defined in

[ue/ue.d.ts:45596](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45596)

___

### Load

▸ `Static` **Load**(`InName`): [`LineSplineGenerator`](ue_ue.LineSplineGenerator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LineSplineGenerator`](ue_ue.LineSplineGenerator.md)

#### Overrides

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[Load](ue_ue.SplineGeneratorBase.md#load)

#### Defined in

[ue/ue.d.ts:45597](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45597)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SplineGeneratorBase](ue_ue.SplineGeneratorBase.md).[StaticClass](ue_ue.SplineGeneratorBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:45595](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L45595)
