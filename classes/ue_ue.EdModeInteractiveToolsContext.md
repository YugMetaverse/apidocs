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

## Properties

### GizmoManager

• **GizmoManager**: [`InteractiveGizmoManager`](ue_ue.InteractiveGizmoManager.md)

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[GizmoManager](ue_ue.InteractiveToolsContext.md#gizmomanager)

___

### InputRouter

• **InputRouter**: [`InputRouter`](ue_ue.InputRouter.md)

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[InputRouter](ue_ue.InteractiveToolsContext.md#inputrouter)

___

### StandardVertexColorMaterial

• **StandardVertexColorMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### ToolManager

• **ToolManager**: [`InteractiveToolManager`](ue_ue.InteractiveToolManager.md)

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[ToolManager](ue_ue.InteractiveToolsContext.md#toolmanager)

___

### \_\_tid\_EdModeInteractiveToolsContext\_\_

• **\_\_tid\_EdModeInteractiveToolsContext\_\_**: `boolean`

___

### \_\_tid\_InteractiveToolsContext\_\_

• **\_\_tid\_InteractiveToolsContext\_\_**: `boolean`

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[__tid_InteractiveToolsContext__](ue_ue.InteractiveToolsContext.md#__tid_interactivetoolscontext__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[__tid_Object__](ue_ue.InteractiveToolsContext.md#__tid_object__)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[GetClass](ue_ue.InteractiveToolsContext.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[GetName](ue_ue.InteractiveToolsContext.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[GetOuter](ue_ue.InteractiveToolsContext.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[GetWorld](ue_ue.InteractiveToolsContext.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InteractiveToolsContext](ue_ue.InteractiveToolsContext.md).[StaticClass](ue_ue.InteractiveToolsContext.md#staticclass)
