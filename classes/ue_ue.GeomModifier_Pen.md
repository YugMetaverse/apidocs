[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GeomModifier\_Pen

# Class: GeomModifier\_Pen

[ue/ue](../modules/ue_ue.md).GeomModifier_Pen

## Hierarchy

- [`GeomModifier_Edit`](ue_ue.GeomModifier_Edit.md)

  ↳ **`GeomModifier_Pen`**

## Table of contents

### Constructors

- [constructor](ue_ue.GeomModifier_Pen.md#constructor)

### Properties

- [CachedPolys](ue_ue.GeomModifier_Pen.md#cachedpolys)
- [Description](ue_ue.GeomModifier_Pen.md#description)
- [ExtrudeDepth](ue_ue.GeomModifier_Pen.md#extrudedepth)
- [MouseWorldSpacePos](ue_ue.GeomModifier_Pen.md#mouseworldspacepos)
- [ShapeVertices](ue_ue.GeomModifier_Pen.md#shapevertices)
- [Tooltip](ue_ue.GeomModifier_Pen.md#tooltip)
- [\_\_tid\_GeomModifier\_Edit\_\_](ue_ue.GeomModifier_Pen.md#__tid_geommodifier_edit__)
- [\_\_tid\_GeomModifier\_Pen\_\_](ue_ue.GeomModifier_Pen.md#__tid_geommodifier_pen__)
- [\_\_tid\_GeomModifier\_\_](ue_ue.GeomModifier_Pen.md#__tid_geommodifier__)
- [\_\_tid\_Object\_\_](ue_ue.GeomModifier_Pen.md#__tid_object__)
- [bAutoExtrude](ue_ue.GeomModifier_Pen.md#bautoextrude)
- [bCreateBrushShape](ue_ue.GeomModifier_Pen.md#bcreatebrushshape)
- [bCreateConvexPolygons](ue_ue.GeomModifier_Pen.md#bcreateconvexpolygons)
- [bInitialized](ue_ue.GeomModifier_Pen.md#binitialized)
- [bPendingPivotOffsetUpdate](ue_ue.GeomModifier_Pen.md#bpendingpivotoffsetupdate)
- [bPushButton](ue_ue.GeomModifier_Pen.md#bpushbutton)

### Methods

- [CreateDefaultSubobject](ue_ue.GeomModifier_Pen.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GeomModifier_Pen.md#executeubergraph)
- [GetClass](ue_ue.GeomModifier_Pen.md#getclass)
- [GetName](ue_ue.GeomModifier_Pen.md#getname)
- [GetOuter](ue_ue.GeomModifier_Pen.md#getouter)
- [GetWorld](ue_ue.GeomModifier_Pen.md#getworld)
- [Find](ue_ue.GeomModifier_Pen.md#find)
- [Load](ue_ue.GeomModifier_Pen.md#load)
- [StaticClass](ue_ue.GeomModifier_Pen.md#staticclass)

## Constructors

### constructor

• **new GeomModifier_Pen**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[constructor](ue_ue.GeomModifier_Edit.md#constructor)

## Properties

### CachedPolys

• **CachedPolys**: [`Polys`](ue_ue.Polys.md)

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[CachedPolys](ue_ue.GeomModifier_Edit.md#cachedpolys)

___

### Description

• **Description**: `string`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[Description](ue_ue.GeomModifier_Edit.md#description)

___

### ExtrudeDepth

• **ExtrudeDepth**: `number`

___

### MouseWorldSpacePos

• **MouseWorldSpacePos**: [`Vector`](ue_ue_s.Vector.md)

___

### ShapeVertices

• **ShapeVertices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

___

### Tooltip

• **Tooltip**: `string`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[Tooltip](ue_ue.GeomModifier_Edit.md#tooltip)

___

### \_\_tid\_GeomModifier\_Edit\_\_

• **\_\_tid\_GeomModifier\_Edit\_\_**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[__tid_GeomModifier_Edit__](ue_ue.GeomModifier_Edit.md#__tid_geommodifier_edit__)

___

### \_\_tid\_GeomModifier\_Pen\_\_

• **\_\_tid\_GeomModifier\_Pen\_\_**: `boolean`

___

### \_\_tid\_GeomModifier\_\_

• **\_\_tid\_GeomModifier\_\_**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[__tid_GeomModifier__](ue_ue.GeomModifier_Edit.md#__tid_geommodifier__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[__tid_Object__](ue_ue.GeomModifier_Edit.md#__tid_object__)

___

### bAutoExtrude

• **bAutoExtrude**: `boolean`

___

### bCreateBrushShape

• **bCreateBrushShape**: `boolean`

___

### bCreateConvexPolygons

• **bCreateConvexPolygons**: `boolean`

___

### bInitialized

• **bInitialized**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[bInitialized](ue_ue.GeomModifier_Edit.md#binitialized)

___

### bPendingPivotOffsetUpdate

• **bPendingPivotOffsetUpdate**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[bPendingPivotOffsetUpdate](ue_ue.GeomModifier_Edit.md#bpendingpivotoffsetupdate)

___

### bPushButton

• **bPushButton**: `boolean`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[bPushButton](ue_ue.GeomModifier_Edit.md#bpushbutton)

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

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[CreateDefaultSubobject](ue_ue.GeomModifier_Edit.md#createdefaultsubobject)

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

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[ExecuteUbergraph](ue_ue.GeomModifier_Edit.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[GetClass](ue_ue.GeomModifier_Edit.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[GetName](ue_ue.GeomModifier_Edit.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[GetOuter](ue_ue.GeomModifier_Edit.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[GetWorld](ue_ue.GeomModifier_Edit.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GeomModifier_Pen`](ue_ue.GeomModifier_Pen.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GeomModifier_Pen`](ue_ue.GeomModifier_Pen.md)

#### Overrides

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[Find](ue_ue.GeomModifier_Edit.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GeomModifier_Pen`](ue_ue.GeomModifier_Pen.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GeomModifier_Pen`](ue_ue.GeomModifier_Pen.md)

#### Overrides

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[Load](ue_ue.GeomModifier_Edit.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GeomModifier_Edit](ue_ue.GeomModifier_Edit.md).[StaticClass](ue_ue.GeomModifier_Edit.md#staticclass)
