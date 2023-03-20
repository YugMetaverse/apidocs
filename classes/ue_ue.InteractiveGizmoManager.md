[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InteractiveGizmoManager

# Class: InteractiveGizmoManager

[ue/ue](../modules/ue_ue.md).InteractiveGizmoManager

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`InteractiveGizmoManager`**

## Table of contents

### Constructors

- [constructor](ue_ue.InteractiveGizmoManager.md#constructor)

### Properties

- [ActiveGizmos](ue_ue.InteractiveGizmoManager.md#activegizmos)
- [GizmoBuilders](ue_ue.InteractiveGizmoManager.md#gizmobuilders)
- [\_\_tid\_InteractiveGizmoManager\_\_](ue_ue.InteractiveGizmoManager.md#__tid_interactivegizmomanager__)
- [\_\_tid\_Object\_\_](ue_ue.InteractiveGizmoManager.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.InteractiveGizmoManager.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InteractiveGizmoManager.md#executeubergraph)
- [GetClass](ue_ue.InteractiveGizmoManager.md#getclass)
- [GetName](ue_ue.InteractiveGizmoManager.md#getname)
- [GetOuter](ue_ue.InteractiveGizmoManager.md#getouter)
- [GetWorld](ue_ue.InteractiveGizmoManager.md#getworld)
- [Find](ue_ue.InteractiveGizmoManager.md#find)
- [Load](ue_ue.InteractiveGizmoManager.md#load)
- [StaticClass](ue_ue.InteractiveGizmoManager.md#staticclass)

## Constructors

### constructor

• **new InteractiveGizmoManager**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ActiveGizmos

• **ActiveGizmos**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ActiveGizmo`](ue_ue.ActiveGizmo.md)\>

___

### GizmoBuilders

• **GizmoBuilders**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`InteractiveGizmoBuilder`](ue_ue.InteractiveGizmoBuilder.md)\>

___

### \_\_tid\_InteractiveGizmoManager\_\_

• **\_\_tid\_InteractiveGizmoManager\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InteractiveGizmoManager`](ue_ue.InteractiveGizmoManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InteractiveGizmoManager`](ue_ue.InteractiveGizmoManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InteractiveGizmoManager`](ue_ue.InteractiveGizmoManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InteractiveGizmoManager`](ue_ue.InteractiveGizmoManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
