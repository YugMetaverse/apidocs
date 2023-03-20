[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InteractiveTool

# Class: InteractiveTool

[ue/ue](../modules/ue_ue.md).InteractiveTool

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`InteractiveTool`**

  ↳↳ [`ClickDragTool`](ue_ue.ClickDragTool.md)

  ↳↳ [`SingleSelectionTool`](ue_ue.SingleSelectionTool.md)

  ↳↳ [`MultiSelectionTool`](ue_ue.MultiSelectionTool.md)

  ↳↳ [`SingleClickTool`](ue_ue.SingleClickTool.md)

## Table of contents

### Constructors

- [constructor](ue_ue.InteractiveTool.md#constructor)

### Properties

- [InputBehaviors](ue_ue.InteractiveTool.md#inputbehaviors)
- [ToolPropertyObjects](ue_ue.InteractiveTool.md#toolpropertyobjects)
- [\_\_tid\_InteractiveTool\_\_](ue_ue.InteractiveTool.md#__tid_interactivetool__)
- [\_\_tid\_Object\_\_](ue_ue.InteractiveTool.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.InteractiveTool.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InteractiveTool.md#executeubergraph)
- [GetClass](ue_ue.InteractiveTool.md#getclass)
- [GetName](ue_ue.InteractiveTool.md#getname)
- [GetOuter](ue_ue.InteractiveTool.md#getouter)
- [GetWorld](ue_ue.InteractiveTool.md#getworld)
- [Find](ue_ue.InteractiveTool.md#find)
- [Load](ue_ue.InteractiveTool.md#load)
- [StaticClass](ue_ue.InteractiveTool.md#staticclass)

## Constructors

### constructor

• **new InteractiveTool**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:27480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27480)

## Properties

### InputBehaviors

• **InputBehaviors**: [`InputBehaviorSet`](ue_ue.InputBehaviorSet.md)

#### Defined in

[ue/ue.d.ts:27481](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27481)

___

### ToolPropertyObjects

• **ToolPropertyObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:27482](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27482)

___

### \_\_tid\_InteractiveTool\_\_

• **\_\_tid\_InteractiveTool\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:27487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27487)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InteractiveTool`](ue_ue.InteractiveTool.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InteractiveTool`](ue_ue.InteractiveTool.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:27484](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27484)

___

### Load

▸ `Static` **Load**(`InName`): [`InteractiveTool`](ue_ue.InteractiveTool.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InteractiveTool`](ue_ue.InteractiveTool.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:27485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27485)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:27483](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27483)
