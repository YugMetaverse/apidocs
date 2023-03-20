[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PlanePositionGizmo

# Class: PlanePositionGizmo

[ue/ue](../modules/ue_ue.md).PlanePositionGizmo

## Hierarchy

- [`InteractiveGizmo`](ue_ue.InteractiveGizmo.md)

  ↳ **`PlanePositionGizmo`**

## Table of contents

### Constructors

- [constructor](ue_ue.PlanePositionGizmo.md#constructor)

### Properties

- [AxisSource](ue_ue.PlanePositionGizmo.md#axissource)
- [HitTarget](ue_ue.PlanePositionGizmo.md#hittarget)
- [InputBehaviors](ue_ue.PlanePositionGizmo.md#inputbehaviors)
- [InteractionAxisX](ue_ue.PlanePositionGizmo.md#interactionaxisx)
- [InteractionAxisY](ue_ue.PlanePositionGizmo.md#interactionaxisy)
- [InteractionCurParameter](ue_ue.PlanePositionGizmo.md#interactioncurparameter)
- [InteractionCurPoint](ue_ue.PlanePositionGizmo.md#interactioncurpoint)
- [InteractionNormal](ue_ue.PlanePositionGizmo.md#interactionnormal)
- [InteractionOrigin](ue_ue.PlanePositionGizmo.md#interactionorigin)
- [InteractionStartParameter](ue_ue.PlanePositionGizmo.md#interactionstartparameter)
- [InteractionStartPoint](ue_ue.PlanePositionGizmo.md#interactionstartpoint)
- [ParameterSource](ue_ue.PlanePositionGizmo.md#parametersource)
- [StateTarget](ue_ue.PlanePositionGizmo.md#statetarget)
- [\_\_tid\_InteractiveGizmo\_\_](ue_ue.PlanePositionGizmo.md#__tid_interactivegizmo__)
- [\_\_tid\_Object\_\_](ue_ue.PlanePositionGizmo.md#__tid_object__)
- [\_\_tid\_PlanePositionGizmo\_\_](ue_ue.PlanePositionGizmo.md#__tid_planepositiongizmo__)
- [bInInteraction](ue_ue.PlanePositionGizmo.md#bininteraction)

### Methods

- [CreateDefaultSubobject](ue_ue.PlanePositionGizmo.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PlanePositionGizmo.md#executeubergraph)
- [GetClass](ue_ue.PlanePositionGizmo.md#getclass)
- [GetName](ue_ue.PlanePositionGizmo.md#getname)
- [GetOuter](ue_ue.PlanePositionGizmo.md#getouter)
- [GetWorld](ue_ue.PlanePositionGizmo.md#getworld)
- [Find](ue_ue.PlanePositionGizmo.md#find)
- [Load](ue_ue.PlanePositionGizmo.md#load)
- [StaticClass](ue_ue.PlanePositionGizmo.md#staticclass)

## Constructors

### constructor

• **new PlanePositionGizmo**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[constructor](ue_ue.InteractiveGizmo.md#constructor)

## Properties

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

### InteractionAxisX

• **InteractionAxisX**: [`Vector`](ue_ue_s.Vector.md)

___

### InteractionAxisY

• **InteractionAxisY**: [`Vector`](ue_ue_s.Vector.md)

___

### InteractionCurParameter

• **InteractionCurParameter**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### InteractionCurPoint

• **InteractionCurPoint**: [`Vector`](ue_ue_s.Vector.md)

___

### InteractionNormal

• **InteractionNormal**: [`Vector`](ue_ue_s.Vector.md)

___

### InteractionOrigin

• **InteractionOrigin**: [`Vector`](ue_ue_s.Vector.md)

___

### InteractionStartParameter

• **InteractionStartParameter**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### InteractionStartPoint

• **InteractionStartPoint**: [`Vector`](ue_ue_s.Vector.md)

___

### ParameterSource

• **ParameterSource**: [`GizmoVec2ParameterSource`](ue_ue.GizmoVec2ParameterSource.md)

___

### StateTarget

• **StateTarget**: [`GizmoStateTarget`](ue_ue.GizmoStateTarget.md)

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

### \_\_tid\_PlanePositionGizmo\_\_

• **\_\_tid\_PlanePositionGizmo\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PlanePositionGizmo`](ue_ue.PlanePositionGizmo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PlanePositionGizmo`](ue_ue.PlanePositionGizmo.md)

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[Find](ue_ue.InteractiveGizmo.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PlanePositionGizmo`](ue_ue.PlanePositionGizmo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PlanePositionGizmo`](ue_ue.PlanePositionGizmo.md)

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[Load](ue_ue.InteractiveGizmo.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[StaticClass](ue_ue.InteractiveGizmo.md#staticclass)
