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

#### Defined in

[ue/ue.d.ts:23326](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23326)

## Properties

### AngleSource

• **AngleSource**: [`GizmoFloatParameterSource`](ue_ue.GizmoFloatParameterSource.md)

#### Defined in

[ue/ue.d.ts:23328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23328)

___

### AxisSource

• **AxisSource**: [`GizmoAxisSource`](ue_ue.GizmoAxisSource.md)

#### Defined in

[ue/ue.d.ts:23327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23327)

___

### HitTarget

• **HitTarget**: [`GizmoClickTarget`](ue_ue.GizmoClickTarget.md)

#### Defined in

[ue/ue.d.ts:23329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23329)

___

### InputBehaviors

• **InputBehaviors**: [`InputBehaviorSet`](ue_ue.InputBehaviorSet.md)

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[InputBehaviors](ue_ue.InteractiveGizmo.md#inputbehaviors)

#### Defined in

[ue/ue.d.ts:23270](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23270)

___

### InteractionCurAngle

• **InteractionCurAngle**: `number`

#### Defined in

[ue/ue.d.ts:23339](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23339)

___

### InteractionCurPoint

• **InteractionCurPoint**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:23337](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23337)

___

### InteractionStartAngle

• **InteractionStartAngle**: `number`

#### Defined in

[ue/ue.d.ts:23338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23338)

___

### InteractionStartPoint

• **InteractionStartPoint**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:23336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23336)

___

### RotationAxis

• **RotationAxis**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:23333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23333)

___

### RotationOrigin

• **RotationOrigin**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:23332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23332)

___

### RotationPlaneX

• **RotationPlaneX**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:23334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23334)

___

### RotationPlaneY

• **RotationPlaneY**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:23335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23335)

___

### StateTarget

• **StateTarget**: [`GizmoStateTarget`](ue_ue.GizmoStateTarget.md)

#### Defined in

[ue/ue.d.ts:23330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23330)

___

### \_\_tid\_AxisAngleGizmo\_\_

• **\_\_tid\_AxisAngleGizmo\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:23344](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23344)

___

### \_\_tid\_InteractiveGizmo\_\_

• **\_\_tid\_InteractiveGizmo\_\_**: `boolean`

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[__tid_InteractiveGizmo__](ue_ue.InteractiveGizmo.md#__tid_interactivegizmo__)

#### Defined in

[ue/ue.d.ts:23275](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23275)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[__tid_Object__](ue_ue.InteractiveGizmo.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bInInteraction

• **bInInteraction**: `boolean`

#### Defined in

[ue/ue.d.ts:23331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23331)

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

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[ExecuteUbergraph](ue_ue.InteractiveGizmo.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[GetClass](ue_ue.InteractiveGizmo.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[GetName](ue_ue.InteractiveGizmo.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[GetOuter](ue_ue.InteractiveGizmo.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[GetWorld](ue_ue.InteractiveGizmo.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:23341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23341)

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

#### Defined in

[ue/ue.d.ts:23342](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23342)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[StaticClass](ue_ue.InteractiveGizmo.md#staticclass)

#### Defined in

[ue/ue.d.ts:23340](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L23340)
