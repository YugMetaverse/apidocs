[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EdModeInteractiveToolsContext

# Class: EdModeInteractiveToolsContext

[ue/ue](../modules/ue_ue.md).EdModeInteractiveToolsContext

## Hierarchy

- [`InteractiveToolsContext`](ue_ue.InteractiveToolsContext.md)

  ↳ **`EdModeInteractiveToolsContext`**

## Table of contents

### Constructors

- [constructor](ue_ue.EdModeInteractiveToolsContext.md#constructor)

### Properties

- [GizmoManager](ue_ue.EdModeInteractiveToolsContext.md#gizmomanager)
- [InputRouter](ue_ue.EdModeInteractiveToolsContext.md#inputrouter)
- [StandardVertexColorMaterial](ue_ue.EdModeInteractiveToolsContext.md#standardvertexcolormaterial)
- [ToolManager](ue_ue.EdModeInteractiveToolsContext.md#toolmanager)
- [\_\_tid\_EdModeInteractiveToolsContext\_\_](ue_ue.EdModeInteractiveToolsContext.md#__tid_edmodeinteractivetoolscontext__)
- [\_\_tid\_InteractiveToolsContext\_\_](ue_ue.EdModeInteractiveToolsContext.md#__tid_interactivetoolscontext__)
- [\_\_tid\_Object\_\_](ue_ue.EdModeInteractiveToolsContext.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EdModeInteractiveToolsContext.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EdModeInteractiveToolsContext.md#executeubergraph)
- [GetClass](ue_ue.EdModeInteractiveToolsContext.md#getclass)
- [GetName](ue_ue.EdModeInteractiveToolsContext.md#getname)
- [GetOuter](ue_ue.EdModeInteractiveToolsContext.md#getouter)
- [GetWorld](ue_ue.EdModeInteractiveToolsContext.md#getworld)
- [Find](ue_ue.EdModeInteractiveToolsContext.md#find)
- [Load](ue_ue.EdModeInteractiveToolsContext.md#load)
- [StaticClass](ue_ue.EdModeInteractiveToolsContext.md#staticclass)

## Constructors

### constructor

• **new EdModeInteractiveToolsContext**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[constructor](ue_ue.InteractiveToolsContext.md#constructor)

#### Defined in

[ue/ue.d.ts:33817](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33817)

## Properties

### GizmoManager

• **GizmoManager**: [`InteractiveGizmoManager`](ue_ue.InteractiveGizmoManager.md)

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[GizmoManager](ue_ue.InteractiveToolsContext.md#gizmomanager)

#### Defined in

[ue/ue.d.ts:33808](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33808)

___

### InputRouter

• **InputRouter**: [`InputRouter`](ue_ue.InputRouter.md)

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[InputRouter](ue_ue.InteractiveToolsContext.md#inputrouter)

#### Defined in

[ue/ue.d.ts:33806](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33806)

___

### StandardVertexColorMaterial

• **StandardVertexColorMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:33818](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33818)

___

### ToolManager

• **ToolManager**: [`InteractiveToolManager`](ue_ue.InteractiveToolManager.md)

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[ToolManager](ue_ue.InteractiveToolsContext.md#toolmanager)

#### Defined in

[ue/ue.d.ts:33807](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33807)

___

### \_\_tid\_EdModeInteractiveToolsContext\_\_

• **\_\_tid\_EdModeInteractiveToolsContext\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:33823](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33823)

___

### \_\_tid\_InteractiveToolsContext\_\_

• **\_\_tid\_InteractiveToolsContext\_\_**: `boolean`

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[__tid_InteractiveToolsContext__](ue_ue.InteractiveToolsContext.md#__tid_interactivetoolscontext__)

#### Defined in

[ue/ue.d.ts:33813](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33813)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[__tid_Object__](ue_ue.InteractiveToolsContext.md#__tid_object__)

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

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[CreateDefaultSubobject](ue_ue.InteractiveToolsContext.md#createdefaultsubobject)

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

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[ExecuteUbergraph](ue_ue.InteractiveToolsContext.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[GetClass](ue_ue.InteractiveToolsContext.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[GetName](ue_ue.InteractiveToolsContext.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[GetOuter](ue_ue.InteractiveToolsContext.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[GetWorld](ue_ue.InteractiveToolsContext.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EdModeInteractiveToolsContext`](ue_ue.EdModeInteractiveToolsContext.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EdModeInteractiveToolsContext`](ue_ue.EdModeInteractiveToolsContext.md)

#### Overrides

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[Find](ue_ue.InteractiveToolsContext.md#find)

#### Defined in

[ue/ue.d.ts:33820](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33820)

___

### Load

▸ `Static` **Load**(`InName`): [`EdModeInteractiveToolsContext`](ue_ue.EdModeInteractiveToolsContext.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EdModeInteractiveToolsContext`](ue_ue.EdModeInteractiveToolsContext.md)

#### Overrides

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[Load](ue_ue.InteractiveToolsContext.md#load)

#### Defined in

[ue/ue.d.ts:33821](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33821)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[StaticClass](ue_ue.InteractiveToolsContext.md#staticclass)

#### Defined in

[ue/ue.d.ts:33819](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L33819)
