[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TransformGizmo

# Class: TransformGizmo

[ue/ue](../modules/ue_ue.md).TransformGizmo

## Hierarchy

- [`InteractiveGizmo`](ue_ue.InteractiveGizmo.md)

  ↳ **`TransformGizmo`**

## Table of contents

### Constructors

- [constructor](ue_ue.TransformGizmo.md#constructor)

### Properties

- [ActiveComponents](ue_ue.TransformGizmo.md#activecomponents)
- [ActiveGizmos](ue_ue.TransformGizmo.md#activegizmos)
- [ActiveTarget](ue_ue.TransformGizmo.md#activetarget)
- [AxisXSource](ue_ue.TransformGizmo.md#axisxsource)
- [AxisYSource](ue_ue.TransformGizmo.md#axisysource)
- [AxisZSource](ue_ue.TransformGizmo.md#axiszsource)
- [InputBehaviors](ue_ue.TransformGizmo.md#inputbehaviors)
- [StateTarget](ue_ue.TransformGizmo.md#statetarget)
- [\_\_tid\_InteractiveGizmo\_\_](ue_ue.TransformGizmo.md#__tid_interactivegizmo__)
- [\_\_tid\_Object\_\_](ue_ue.TransformGizmo.md#__tid_object__)
- [\_\_tid\_TransformGizmo\_\_](ue_ue.TransformGizmo.md#__tid_transformgizmo__)

### Methods

- [CreateDefaultSubobject](ue_ue.TransformGizmo.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TransformGizmo.md#executeubergraph)
- [GetClass](ue_ue.TransformGizmo.md#getclass)
- [GetName](ue_ue.TransformGizmo.md#getname)
- [GetOuter](ue_ue.TransformGizmo.md#getouter)
- [GetWorld](ue_ue.TransformGizmo.md#getworld)
- [Find](ue_ue.TransformGizmo.md#find)
- [Load](ue_ue.TransformGizmo.md#load)
- [StaticClass](ue_ue.TransformGizmo.md#staticclass)

## Constructors

### constructor

• **new TransformGizmo**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[constructor](ue_ue.InteractiveGizmo.md#constructor)

## Properties

### ActiveComponents

• **ActiveComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

___

### ActiveGizmos

• **ActiveGizmos**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InteractiveGizmo`](ue_ue.InteractiveGizmo.md)\>

___

### ActiveTarget

• **ActiveTarget**: [`TransformProxy`](ue_ue.TransformProxy.md)

___

### AxisXSource

• **AxisXSource**: [`GizmoComponentAxisSource`](ue_ue.GizmoComponentAxisSource.md)

___

### AxisYSource

• **AxisYSource**: [`GizmoComponentAxisSource`](ue_ue.GizmoComponentAxisSource.md)

___

### AxisZSource

• **AxisZSource**: [`GizmoComponentAxisSource`](ue_ue.GizmoComponentAxisSource.md)

___

### InputBehaviors

• **InputBehaviors**: [`InputBehaviorSet`](ue_ue.InputBehaviorSet.md)

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[InputBehaviors](ue_ue.InteractiveGizmo.md#inputbehaviors)

___

### StateTarget

• **StateTarget**: [`GizmoTransformChangeStateTarget`](ue_ue.GizmoTransformChangeStateTarget.md)

___

### \_\_tid\_InteractiveGizmo\_\_

• **\_\_tid\_InteractiveGizmo\_\_**: `boolean`

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[__tid_InteractiveGizmo__](ue_ue.InteractiveGizmo.md#__tid_interactivegizmo__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[__tid_Object__](ue_ue.InteractiveGizmo.md#__tid_object__)

___

### \_\_tid\_TransformGizmo\_\_

• **\_\_tid\_TransformGizmo\_\_**: `boolean`

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

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[CreateDefaultSubobject](ue_ue.InteractiveGizmo.md#createdefaultsubobject)

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

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[ExecuteUbergraph](ue_ue.InteractiveGizmo.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[GetClass](ue_ue.InteractiveGizmo.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[GetName](ue_ue.InteractiveGizmo.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[GetOuter](ue_ue.InteractiveGizmo.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[GetWorld](ue_ue.InteractiveGizmo.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TransformGizmo`](ue_ue.TransformGizmo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TransformGizmo`](ue_ue.TransformGizmo.md)

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[Find](ue_ue.InteractiveGizmo.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TransformGizmo`](ue_ue.TransformGizmo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TransformGizmo`](ue_ue.TransformGizmo.md)

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[Load](ue_ue.InteractiveGizmo.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[StaticClass](ue_ue.InteractiveGizmo.md#staticclass)
