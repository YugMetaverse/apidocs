[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AxisPositionGizmo

# Class: AxisPositionGizmo

[ue/ue](../modules/ue_ue.md).AxisPositionGizmo

## Hierarchy

- [`InteractiveGizmo`](ue_ue.InteractiveGizmo.md)

  ↳ **`AxisPositionGizmo`**

## Table of contents

### Constructors

- [constructor](ue_ue.AxisPositionGizmo.md#constructor)

### Properties

- [AxisSource](ue_ue.AxisPositionGizmo.md#axissource)
- [HitTarget](ue_ue.AxisPositionGizmo.md#hittarget)
- [InputBehaviors](ue_ue.AxisPositionGizmo.md#inputbehaviors)
- [InteractionAxis](ue_ue.AxisPositionGizmo.md#interactionaxis)
- [InteractionCurParameter](ue_ue.AxisPositionGizmo.md#interactioncurparameter)
- [InteractionCurPoint](ue_ue.AxisPositionGizmo.md#interactioncurpoint)
- [InteractionOrigin](ue_ue.AxisPositionGizmo.md#interactionorigin)
- [InteractionStartParameter](ue_ue.AxisPositionGizmo.md#interactionstartparameter)
- [InteractionStartPoint](ue_ue.AxisPositionGizmo.md#interactionstartpoint)
- [ParameterSource](ue_ue.AxisPositionGizmo.md#parametersource)
- [StateTarget](ue_ue.AxisPositionGizmo.md#statetarget)
- [\_\_tid\_AxisPositionGizmo\_\_](ue_ue.AxisPositionGizmo.md#__tid_axispositiongizmo__)
- [\_\_tid\_InteractiveGizmo\_\_](ue_ue.AxisPositionGizmo.md#__tid_interactivegizmo__)
- [\_\_tid\_Object\_\_](ue_ue.AxisPositionGizmo.md#__tid_object__)
- [bInInteraction](ue_ue.AxisPositionGizmo.md#bininteraction)

### Methods

- [CreateDefaultSubobject](ue_ue.AxisPositionGizmo.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AxisPositionGizmo.md#executeubergraph)
- [GetClass](ue_ue.AxisPositionGizmo.md#getclass)
- [GetName](ue_ue.AxisPositionGizmo.md#getname)
- [GetOuter](ue_ue.AxisPositionGizmo.md#getouter)
- [GetWorld](ue_ue.AxisPositionGizmo.md#getworld)
- [Find](ue_ue.AxisPositionGizmo.md#find)
- [Load](ue_ue.AxisPositionGizmo.md#load)
- [StaticClass](ue_ue.AxisPositionGizmo.md#staticclass)

## Constructors

### constructor

• **new AxisPositionGizmo**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[constructor](ue_ue.InteractiveGizmo.md#constructor)

#### Defined in

[ue/ue.d.ts:23375](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23375)

## Properties

### AxisSource

• **AxisSource**: [`GizmoAxisSource`](ue_ue.GizmoAxisSource.md)

#### Defined in

[ue/ue.d.ts:23376](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23376)

___

### HitTarget

• **HitTarget**: [`GizmoClickTarget`](ue_ue.GizmoClickTarget.md)

#### Defined in

[ue/ue.d.ts:23378](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23378)

___

### InputBehaviors

• **InputBehaviors**: [`InputBehaviorSet`](ue_ue.InputBehaviorSet.md)

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[InputBehaviors](ue_ue.InteractiveGizmo.md#inputbehaviors)

#### Defined in

[ue/ue.d.ts:23270](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23270)

___

### InteractionAxis

• **InteractionAxis**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:23382](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23382)

___

### InteractionCurParameter

• **InteractionCurParameter**: `number`

#### Defined in

[ue/ue.d.ts:23386](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23386)

___

### InteractionCurPoint

• **InteractionCurPoint**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:23384](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23384)

___

### InteractionOrigin

• **InteractionOrigin**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:23381](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23381)

___

### InteractionStartParameter

• **InteractionStartParameter**: `number`

#### Defined in

[ue/ue.d.ts:23385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23385)

___

### InteractionStartPoint

• **InteractionStartPoint**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:23383](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23383)

___

### ParameterSource

• **ParameterSource**: [`GizmoFloatParameterSource`](ue_ue.GizmoFloatParameterSource.md)

#### Defined in

[ue/ue.d.ts:23377](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23377)

___

### StateTarget

• **StateTarget**: [`GizmoStateTarget`](ue_ue.GizmoStateTarget.md)

#### Defined in

[ue/ue.d.ts:23379](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23379)

___

### \_\_tid\_AxisPositionGizmo\_\_

• **\_\_tid\_AxisPositionGizmo\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:23391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23391)

___

### \_\_tid\_InteractiveGizmo\_\_

• **\_\_tid\_InteractiveGizmo\_\_**: `boolean`

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[__tid_InteractiveGizmo__](ue_ue.InteractiveGizmo.md#__tid_interactivegizmo__)

#### Defined in

[ue/ue.d.ts:23275](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23275)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[__tid_Object__](ue_ue.InteractiveGizmo.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bInInteraction

• **bInInteraction**: `boolean`

#### Defined in

[ue/ue.d.ts:23380](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23380)

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

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[ExecuteUbergraph](ue_ue.InteractiveGizmo.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[GetClass](ue_ue.InteractiveGizmo.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[GetName](ue_ue.InteractiveGizmo.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[GetOuter](ue_ue.InteractiveGizmo.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[GetWorld](ue_ue.InteractiveGizmo.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AxisPositionGizmo`](ue_ue.AxisPositionGizmo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AxisPositionGizmo`](ue_ue.AxisPositionGizmo.md)

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[Find](ue_ue.InteractiveGizmo.md#find)

#### Defined in

[ue/ue.d.ts:23388](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23388)

___

### Load

▸ `Static` **Load**(`InName`): [`AxisPositionGizmo`](ue_ue.AxisPositionGizmo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AxisPositionGizmo`](ue_ue.AxisPositionGizmo.md)

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[Load](ue_ue.InteractiveGizmo.md#load)

#### Defined in

[ue/ue.d.ts:23389](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23389)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[StaticClass](ue_ue.InteractiveGizmo.md#staticclass)

#### Defined in

[ue/ue.d.ts:23387](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23387)
