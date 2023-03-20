[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AxisAngleGizmo

# Class: AxisAngleGizmo

[ue/ue](../modules/ue_ue.md).AxisAngleGizmo

## Hierarchy

- [`InteractiveGizmo`](ue_ue.InteractiveGizmo.md)

  ↳ **`AxisAngleGizmo`**

## Table of contents

### Constructors

- [constructor](ue_ue.AxisAngleGizmo.md#constructor)

### Properties

- [AngleSource](ue_ue.AxisAngleGizmo.md#anglesource)
- [AxisSource](ue_ue.AxisAngleGizmo.md#axissource)
- [HitTarget](ue_ue.AxisAngleGizmo.md#hittarget)
- [InputBehaviors](ue_ue.AxisAngleGizmo.md#inputbehaviors)
- [InteractionCurAngle](ue_ue.AxisAngleGizmo.md#interactioncurangle)
- [InteractionCurPoint](ue_ue.AxisAngleGizmo.md#interactioncurpoint)
- [InteractionStartAngle](ue_ue.AxisAngleGizmo.md#interactionstartangle)
- [InteractionStartPoint](ue_ue.AxisAngleGizmo.md#interactionstartpoint)
- [RotationAxis](ue_ue.AxisAngleGizmo.md#rotationaxis)
- [RotationOrigin](ue_ue.AxisAngleGizmo.md#rotationorigin)
- [RotationPlaneX](ue_ue.AxisAngleGizmo.md#rotationplanex)
- [RotationPlaneY](ue_ue.AxisAngleGizmo.md#rotationplaney)
- [StateTarget](ue_ue.AxisAngleGizmo.md#statetarget)
- [\_\_tid\_AxisAngleGizmo\_\_](ue_ue.AxisAngleGizmo.md#__tid_axisanglegizmo__)
- [\_\_tid\_InteractiveGizmo\_\_](ue_ue.AxisAngleGizmo.md#__tid_interactivegizmo__)
- [\_\_tid\_Object\_\_](ue_ue.AxisAngleGizmo.md#__tid_object__)
- [bInInteraction](ue_ue.AxisAngleGizmo.md#bininteraction)

### Methods

- [CreateDefaultSubobject](ue_ue.AxisAngleGizmo.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AxisAngleGizmo.md#executeubergraph)
- [GetClass](ue_ue.AxisAngleGizmo.md#getclass)
- [GetName](ue_ue.AxisAngleGizmo.md#getname)
- [GetOuter](ue_ue.AxisAngleGizmo.md#getouter)
- [GetWorld](ue_ue.AxisAngleGizmo.md#getworld)
- [Find](ue_ue.AxisAngleGizmo.md#find)
- [Load](ue_ue.AxisAngleGizmo.md#load)
- [StaticClass](ue_ue.AxisAngleGizmo.md#staticclass)

## Constructors

### constructor

• **new AxisAngleGizmo**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[constructor](ue_ue.InteractiveGizmo.md#constructor)

## Properties

### AngleSource

• **AngleSource**: [`GizmoFloatParameterSource`](ue_ue.GizmoFloatParameterSource.md)

___

### AxisSource

• **AxisSource**: [`GizmoAxisSource`](ue_ue.GizmoAxisSource.md)

___

### HitTarget

• **HitTarget**: [`GizmoClickTarget`](ue_ue.GizmoClickTarget.md)

___

### InputBehaviors

• **InputBehaviors**: [`InputBehaviorSet`](ue_ue.InputBehaviorSet.md)

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[InputBehaviors](ue_ue.InteractiveGizmo.md#inputbehaviors)

___

### InteractionCurAngle

• **InteractionCurAngle**: `number`

___

### InteractionCurPoint

• **InteractionCurPoint**: [`Vector`](ue_ue_s.Vector.md)

___

### InteractionStartAngle

• **InteractionStartAngle**: `number`

___

### InteractionStartPoint

• **InteractionStartPoint**: [`Vector`](ue_ue_s.Vector.md)

___

### RotationAxis

• **RotationAxis**: [`Vector`](ue_ue_s.Vector.md)

___

### RotationOrigin

• **RotationOrigin**: [`Vector`](ue_ue_s.Vector.md)

___

### RotationPlaneX

• **RotationPlaneX**: [`Vector`](ue_ue_s.Vector.md)

___

### RotationPlaneY

• **RotationPlaneY**: [`Vector`](ue_ue_s.Vector.md)

___

### StateTarget

• **StateTarget**: [`GizmoStateTarget`](ue_ue.GizmoStateTarget.md)

___

### \_\_tid\_AxisAngleGizmo\_\_

• **\_\_tid\_AxisAngleGizmo\_\_**: `boolean`

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

### bInInteraction

• **bInInteraction**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AxisAngleGizmo`](ue_ue.AxisAngleGizmo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AxisAngleGizmo`](ue_ue.AxisAngleGizmo.md)

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[Find](ue_ue.InteractiveGizmo.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AxisAngleGizmo`](ue_ue.AxisAngleGizmo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AxisAngleGizmo`](ue_ue.AxisAngleGizmo.md)

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[Load](ue_ue.InteractiveGizmo.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[StaticClass](ue_ue.InteractiveGizmo.md#staticclass)
