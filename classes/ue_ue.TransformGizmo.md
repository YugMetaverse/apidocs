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

#### Defined in

[ue/ue.d.ts:64089](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64089)

## Properties

### ActiveComponents

• **ActiveComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>

#### Defined in

[ue/ue.d.ts:64091](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64091)

___

### ActiveGizmos

• **ActiveGizmos**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InteractiveGizmo`](ue_ue.InteractiveGizmo.md)\>

#### Defined in

[ue/ue.d.ts:64092](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64092)

___

### ActiveTarget

• **ActiveTarget**: [`TransformProxy`](ue_ue.TransformProxy.md)

#### Defined in

[ue/ue.d.ts:64090](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64090)

___

### AxisXSource

• **AxisXSource**: [`GizmoComponentAxisSource`](ue_ue.GizmoComponentAxisSource.md)

#### Defined in

[ue/ue.d.ts:64093](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64093)

___

### AxisYSource

• **AxisYSource**: [`GizmoComponentAxisSource`](ue_ue.GizmoComponentAxisSource.md)

#### Defined in

[ue/ue.d.ts:64094](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64094)

___

### AxisZSource

• **AxisZSource**: [`GizmoComponentAxisSource`](ue_ue.GizmoComponentAxisSource.md)

#### Defined in

[ue/ue.d.ts:64095](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64095)

___

### InputBehaviors

• **InputBehaviors**: [`InputBehaviorSet`](ue_ue.InputBehaviorSet.md)

#### Inherited from

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[InputBehaviors](ue_ue.InteractiveGizmo.md#inputbehaviors)

#### Defined in

[ue/ue.d.ts:23270](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23270)

___

### StateTarget

• **StateTarget**: [`GizmoTransformChangeStateTarget`](ue_ue.GizmoTransformChangeStateTarget.md)

#### Defined in

[ue/ue.d.ts:64096](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64096)

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

### \_\_tid\_TransformGizmo\_\_

• **\_\_tid\_TransformGizmo\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64101](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64101)

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

#### Defined in

[ue/ue.d.ts:64098](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64098)

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

#### Defined in

[ue/ue.d.ts:64099](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64099)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InteractiveGizmo](ue_ue.InteractiveGizmo.md).[StaticClass](ue_ue.InteractiveGizmo.md#staticclass)

#### Defined in

[ue/ue.d.ts:64097](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64097)
