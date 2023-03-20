[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TransformGizmoBuilder

# Class: TransformGizmoBuilder

[ue/ue](../modules/ue_ue.md).TransformGizmoBuilder

## Hierarchy

- [`InteractiveGizmoBuilder`](ue_ue.InteractiveGizmoBuilder.md)

  ↳ **`TransformGizmoBuilder`**

## Table of contents

### Constructors

- [constructor](ue_ue.TransformGizmoBuilder.md#constructor)

### Properties

- [\_\_tid\_InteractiveGizmoBuilder\_\_](ue_ue.TransformGizmoBuilder.md#__tid_interactivegizmobuilder__)
- [\_\_tid\_Object\_\_](ue_ue.TransformGizmoBuilder.md#__tid_object__)
- [\_\_tid\_TransformGizmoBuilder\_\_](ue_ue.TransformGizmoBuilder.md#__tid_transformgizmobuilder__)

### Methods

- [CreateDefaultSubobject](ue_ue.TransformGizmoBuilder.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TransformGizmoBuilder.md#executeubergraph)
- [GetClass](ue_ue.TransformGizmoBuilder.md#getclass)
- [GetName](ue_ue.TransformGizmoBuilder.md#getname)
- [GetOuter](ue_ue.TransformGizmoBuilder.md#getouter)
- [GetWorld](ue_ue.TransformGizmoBuilder.md#getworld)
- [Find](ue_ue.TransformGizmoBuilder.md#find)
- [Load](ue_ue.TransformGizmoBuilder.md#load)
- [StaticClass](ue_ue.TransformGizmoBuilder.md#staticclass)

## Constructors

### constructor

• **new TransformGizmoBuilder**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InteractiveGizmoBuilder](ue_ue.InteractiveGizmoBuilder.md).[constructor](ue_ue.InteractiveGizmoBuilder.md#constructor)

## Properties

### \_\_tid\_InteractiveGizmoBuilder\_\_

• **\_\_tid\_InteractiveGizmoBuilder\_\_**: `boolean`

#### Inherited from

[InteractiveGizmoBuilder](ue_ue.InteractiveGizmoBuilder.md).[__tid_InteractiveGizmoBuilder__](ue_ue.InteractiveGizmoBuilder.md#__tid_interactivegizmobuilder__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InteractiveGizmoBuilder](ue_ue.InteractiveGizmoBuilder.md).[__tid_Object__](ue_ue.InteractiveGizmoBuilder.md#__tid_object__)

___

### \_\_tid\_TransformGizmoBuilder\_\_

• **\_\_tid\_TransformGizmoBuilder\_\_**: `boolean`

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

[InteractiveGizmoBuilder](ue_ue.InteractiveGizmoBuilder.md).[CreateDefaultSubobject](ue_ue.InteractiveGizmoBuilder.md#createdefaultsubobject)

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

[InteractiveGizmoBuilder](ue_ue.InteractiveGizmoBuilder.md).[ExecuteUbergraph](ue_ue.InteractiveGizmoBuilder.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InteractiveGizmoBuilder](ue_ue.InteractiveGizmoBuilder.md).[GetClass](ue_ue.InteractiveGizmoBuilder.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InteractiveGizmoBuilder](ue_ue.InteractiveGizmoBuilder.md).[GetName](ue_ue.InteractiveGizmoBuilder.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InteractiveGizmoBuilder](ue_ue.InteractiveGizmoBuilder.md).[GetOuter](ue_ue.InteractiveGizmoBuilder.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InteractiveGizmoBuilder](ue_ue.InteractiveGizmoBuilder.md).[GetWorld](ue_ue.InteractiveGizmoBuilder.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TransformGizmoBuilder`](ue_ue.TransformGizmoBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TransformGizmoBuilder`](ue_ue.TransformGizmoBuilder.md)

#### Overrides

[InteractiveGizmoBuilder](ue_ue.InteractiveGizmoBuilder.md).[Find](ue_ue.InteractiveGizmoBuilder.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TransformGizmoBuilder`](ue_ue.TransformGizmoBuilder.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TransformGizmoBuilder`](ue_ue.TransformGizmoBuilder.md)

#### Overrides

[InteractiveGizmoBuilder](ue_ue.InteractiveGizmoBuilder.md).[Load](ue_ue.InteractiveGizmoBuilder.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InteractiveGizmoBuilder](ue_ue.InteractiveGizmoBuilder.md).[StaticClass](ue_ue.InteractiveGizmoBuilder.md#staticclass)
