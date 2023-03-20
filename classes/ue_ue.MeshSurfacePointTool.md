[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MeshSurfacePointTool

# Class: MeshSurfacePointTool

[ue/ue](../modules/ue_ue.md).MeshSurfacePointTool

## Hierarchy

- [`SingleSelectionTool`](ue_ue.SingleSelectionTool.md)

  ↳ **`MeshSurfacePointTool`**

## Table of contents

### Constructors

- [constructor](ue_ue.MeshSurfacePointTool.md#constructor)

### Properties

- [InputBehaviors](ue_ue.MeshSurfacePointTool.md#inputbehaviors)
- [ToolPropertyObjects](ue_ue.MeshSurfacePointTool.md#toolpropertyobjects)
- [\_\_tid\_InteractiveTool\_\_](ue_ue.MeshSurfacePointTool.md#__tid_interactivetool__)
- [\_\_tid\_MeshSurfacePointTool\_\_](ue_ue.MeshSurfacePointTool.md#__tid_meshsurfacepointtool__)
- [\_\_tid\_Object\_\_](ue_ue.MeshSurfacePointTool.md#__tid_object__)
- [\_\_tid\_SingleSelectionTool\_\_](ue_ue.MeshSurfacePointTool.md#__tid_singleselectiontool__)

### Methods

- [CreateDefaultSubobject](ue_ue.MeshSurfacePointTool.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MeshSurfacePointTool.md#executeubergraph)
- [GetClass](ue_ue.MeshSurfacePointTool.md#getclass)
- [GetName](ue_ue.MeshSurfacePointTool.md#getname)
- [GetOuter](ue_ue.MeshSurfacePointTool.md#getouter)
- [GetWorld](ue_ue.MeshSurfacePointTool.md#getworld)
- [Find](ue_ue.MeshSurfacePointTool.md#find)
- [Load](ue_ue.MeshSurfacePointTool.md#load)
- [StaticClass](ue_ue.MeshSurfacePointTool.md#staticclass)

## Constructors

### constructor

• **new MeshSurfacePointTool**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SingleSelectionTool](ue_ue.SingleSelectionTool.md).[constructor](ue_ue.SingleSelectionTool.md#constructor)

#### Defined in

[ue/ue.d.ts:50592](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50592)

## Properties

### InputBehaviors

• **InputBehaviors**: [`InputBehaviorSet`](ue_ue.InputBehaviorSet.md)

#### Inherited from

[SingleSelectionTool](ue_ue.SingleSelectionTool.md).[InputBehaviors](ue_ue.SingleSelectionTool.md#inputbehaviors)

#### Defined in

[ue/ue.d.ts:27481](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27481)

___

### ToolPropertyObjects

• **ToolPropertyObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[SingleSelectionTool](ue_ue.SingleSelectionTool.md).[ToolPropertyObjects](ue_ue.SingleSelectionTool.md#toolpropertyobjects)

#### Defined in

[ue/ue.d.ts:27482](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27482)

___

### \_\_tid\_InteractiveTool\_\_

• **\_\_tid\_InteractiveTool\_\_**: `boolean`

#### Inherited from

[SingleSelectionTool](ue_ue.SingleSelectionTool.md).[__tid_InteractiveTool__](ue_ue.SingleSelectionTool.md#__tid_interactivetool__)

#### Defined in

[ue/ue.d.ts:27487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27487)

___

### \_\_tid\_MeshSurfacePointTool\_\_

• **\_\_tid\_MeshSurfacePointTool\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:50597](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50597)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SingleSelectionTool](ue_ue.SingleSelectionTool.md).[__tid_Object__](ue_ue.SingleSelectionTool.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_SingleSelectionTool\_\_

• **\_\_tid\_SingleSelectionTool\_\_**: `boolean`

#### Inherited from

[SingleSelectionTool](ue_ue.SingleSelectionTool.md).[__tid_SingleSelectionTool__](ue_ue.SingleSelectionTool.md#__tid_singleselectiontool__)

#### Defined in

[ue/ue.d.ts:50588](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50588)

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

[SingleSelectionTool](ue_ue.SingleSelectionTool.md).[CreateDefaultSubobject](ue_ue.SingleSelectionTool.md#createdefaultsubobject)

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

[SingleSelectionTool](ue_ue.SingleSelectionTool.md).[ExecuteUbergraph](ue_ue.SingleSelectionTool.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SingleSelectionTool](ue_ue.SingleSelectionTool.md).[GetClass](ue_ue.SingleSelectionTool.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SingleSelectionTool](ue_ue.SingleSelectionTool.md).[GetName](ue_ue.SingleSelectionTool.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SingleSelectionTool](ue_ue.SingleSelectionTool.md).[GetOuter](ue_ue.SingleSelectionTool.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SingleSelectionTool](ue_ue.SingleSelectionTool.md).[GetWorld](ue_ue.SingleSelectionTool.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MeshSurfacePointTool`](ue_ue.MeshSurfacePointTool.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MeshSurfacePointTool`](ue_ue.MeshSurfacePointTool.md)

#### Overrides

[SingleSelectionTool](ue_ue.SingleSelectionTool.md).[Find](ue_ue.SingleSelectionTool.md#find)

#### Defined in

[ue/ue.d.ts:50594](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50594)

___

### Load

▸ `Static` **Load**(`InName`): [`MeshSurfacePointTool`](ue_ue.MeshSurfacePointTool.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MeshSurfacePointTool`](ue_ue.MeshSurfacePointTool.md)

#### Overrides

[SingleSelectionTool](ue_ue.SingleSelectionTool.md).[Load](ue_ue.SingleSelectionTool.md#load)

#### Defined in

[ue/ue.d.ts:50595](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50595)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SingleSelectionTool](ue_ue.SingleSelectionTool.md).[StaticClass](ue_ue.SingleSelectionTool.md#staticclass)

#### Defined in

[ue/ue.d.ts:50593](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L50593)
