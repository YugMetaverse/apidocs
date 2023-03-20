[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SingleSelectionTool

# Class: SingleSelectionTool

[ue/ue](../modules/ue_ue.md).SingleSelectionTool

## Hierarchy

- [`InteractiveTool`](ue_ue.InteractiveTool.md)

  ↳ **`SingleSelectionTool`**

  ↳↳ [`MeshSurfacePointTool`](ue_ue.MeshSurfacePointTool.md)

## Table of contents

### Constructors

- [constructor](ue_ue.SingleSelectionTool.md#constructor)

### Properties

- [InputBehaviors](ue_ue.SingleSelectionTool.md#inputbehaviors)
- [ToolPropertyObjects](ue_ue.SingleSelectionTool.md#toolpropertyobjects)
- [\_\_tid\_InteractiveTool\_\_](ue_ue.SingleSelectionTool.md#__tid_interactivetool__)
- [\_\_tid\_Object\_\_](ue_ue.SingleSelectionTool.md#__tid_object__)
- [\_\_tid\_SingleSelectionTool\_\_](ue_ue.SingleSelectionTool.md#__tid_singleselectiontool__)

### Methods

- [CreateDefaultSubobject](ue_ue.SingleSelectionTool.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SingleSelectionTool.md#executeubergraph)
- [GetClass](ue_ue.SingleSelectionTool.md#getclass)
- [GetName](ue_ue.SingleSelectionTool.md#getname)
- [GetOuter](ue_ue.SingleSelectionTool.md#getouter)
- [GetWorld](ue_ue.SingleSelectionTool.md#getworld)
- [Find](ue_ue.SingleSelectionTool.md#find)
- [Load](ue_ue.SingleSelectionTool.md#load)
- [StaticClass](ue_ue.SingleSelectionTool.md#staticclass)

## Constructors

### constructor

• **new SingleSelectionTool**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InteractiveTool](ue_ue.InteractiveTool.md).[constructor](ue_ue.InteractiveTool.md#constructor)

#### Defined in

[ue/ue.d.ts:50583](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50583)

## Properties

### InputBehaviors

• **InputBehaviors**: [`InputBehaviorSet`](ue_ue.InputBehaviorSet.md)

#### Inherited from

[InteractiveTool](ue_ue.InteractiveTool.md).[InputBehaviors](ue_ue.InteractiveTool.md#inputbehaviors)

#### Defined in

[ue/ue.d.ts:27481](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27481)

___

### ToolPropertyObjects

• **ToolPropertyObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[InteractiveTool](ue_ue.InteractiveTool.md).[ToolPropertyObjects](ue_ue.InteractiveTool.md#toolpropertyobjects)

#### Defined in

[ue/ue.d.ts:27482](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27482)

___

### \_\_tid\_InteractiveTool\_\_

• **\_\_tid\_InteractiveTool\_\_**: `boolean`

#### Inherited from

[InteractiveTool](ue_ue.InteractiveTool.md).[__tid_InteractiveTool__](ue_ue.InteractiveTool.md#__tid_interactivetool__)

#### Defined in

[ue/ue.d.ts:27487](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27487)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InteractiveTool](ue_ue.InteractiveTool.md).[__tid_Object__](ue_ue.InteractiveTool.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SingleSelectionTool\_\_

• **\_\_tid\_SingleSelectionTool\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:50588](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50588)

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

[InteractiveTool](ue_ue.InteractiveTool.md).[CreateDefaultSubobject](ue_ue.InteractiveTool.md#createdefaultsubobject)

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

[InteractiveTool](ue_ue.InteractiveTool.md).[ExecuteUbergraph](ue_ue.InteractiveTool.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InteractiveTool](ue_ue.InteractiveTool.md).[GetClass](ue_ue.InteractiveTool.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InteractiveTool](ue_ue.InteractiveTool.md).[GetName](ue_ue.InteractiveTool.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InteractiveTool](ue_ue.InteractiveTool.md).[GetOuter](ue_ue.InteractiveTool.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InteractiveTool](ue_ue.InteractiveTool.md).[GetWorld](ue_ue.InteractiveTool.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SingleSelectionTool`](ue_ue.SingleSelectionTool.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SingleSelectionTool`](ue_ue.SingleSelectionTool.md)

#### Overrides

[InteractiveTool](ue_ue.InteractiveTool.md).[Find](ue_ue.InteractiveTool.md#find)

#### Defined in

[ue/ue.d.ts:50585](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50585)

___

### Load

▸ `Static` **Load**(`InName`): [`SingleSelectionTool`](ue_ue.SingleSelectionTool.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SingleSelectionTool`](ue_ue.SingleSelectionTool.md)

#### Overrides

[InteractiveTool](ue_ue.InteractiveTool.md).[Load](ue_ue.InteractiveTool.md#load)

#### Defined in

[ue/ue.d.ts:50586](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50586)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InteractiveTool](ue_ue.InteractiveTool.md).[StaticClass](ue_ue.InteractiveTool.md#staticclass)

#### Defined in

[ue/ue.d.ts:50584](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50584)