[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InteractiveToolManager

# Class: InteractiveToolManager

[ue/ue](../modules/ue_ue.md).InteractiveToolManager

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`InteractiveToolManager`**

## Table of contents

### Constructors

- [constructor](ue_ue.InteractiveToolManager.md#constructor)

### Properties

- [ActiveLeftTool](ue_ue.InteractiveToolManager.md#activelefttool)
- [ActiveRightTool](ue_ue.InteractiveToolManager.md#activerighttool)
- [ToolBuilders](ue_ue.InteractiveToolManager.md#toolbuilders)
- [\_\_tid\_InteractiveToolManager\_\_](ue_ue.InteractiveToolManager.md#__tid_interactivetoolmanager__)
- [\_\_tid\_Object\_\_](ue_ue.InteractiveToolManager.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.InteractiveToolManager.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InteractiveToolManager.md#executeubergraph)
- [GetClass](ue_ue.InteractiveToolManager.md#getclass)
- [GetName](ue_ue.InteractiveToolManager.md#getname)
- [GetOuter](ue_ue.InteractiveToolManager.md#getouter)
- [GetWorld](ue_ue.InteractiveToolManager.md#getworld)
- [Find](ue_ue.InteractiveToolManager.md#find)
- [Load](ue_ue.InteractiveToolManager.md#load)
- [StaticClass](ue_ue.InteractiveToolManager.md#staticclass)

## Constructors

### constructor

• **new InteractiveToolManager**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:33772](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33772)

## Properties

### ActiveLeftTool

• **ActiveLeftTool**: [`InteractiveTool`](ue_ue.InteractiveTool.md)

#### Defined in

[ue/ue.d.ts:33773](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33773)

___

### ActiveRightTool

• **ActiveRightTool**: [`InteractiveTool`](ue_ue.InteractiveTool.md)

#### Defined in

[ue/ue.d.ts:33774](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33774)

___

### ToolBuilders

• **ToolBuilders**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`InteractiveToolBuilder`](ue_ue.InteractiveToolBuilder.md)\>

#### Defined in

[ue/ue.d.ts:33775](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33775)

___

### \_\_tid\_InteractiveToolManager\_\_

• **\_\_tid\_InteractiveToolManager\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:33780](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33780)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InteractiveToolManager`](ue_ue.InteractiveToolManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InteractiveToolManager`](ue_ue.InteractiveToolManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:33777](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33777)

___

### Load

▸ `Static` **Load**(`InName`): [`InteractiveToolManager`](ue_ue.InteractiveToolManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InteractiveToolManager`](ue_ue.InteractiveToolManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:33778](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33778)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:33776](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L33776)
