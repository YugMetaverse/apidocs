[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DockableWindowDragOperation

# Class: DockableWindowDragOperation

[ue/ue](../modules/ue_ue.md).DockableWindowDragOperation

## Hierarchy

- [`ViewportDragOperation`](ue_ue.ViewportDragOperation.md)

  ↳ **`DockableWindowDragOperation`**

## Table of contents

### Constructors

- [constructor](ue_ue.DockableWindowDragOperation.md#constructor)

### Properties

- [\_\_tid\_DockableWindowDragOperation\_\_](ue_ue.DockableWindowDragOperation.md#__tid_dockablewindowdragoperation__)
- [\_\_tid\_Object\_\_](ue_ue.DockableWindowDragOperation.md#__tid_object__)
- [\_\_tid\_ViewportDragOperation\_\_](ue_ue.DockableWindowDragOperation.md#__tid_viewportdragoperation__)

### Methods

- [CreateDefaultSubobject](ue_ue.DockableWindowDragOperation.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DockableWindowDragOperation.md#executeubergraph)
- [GetClass](ue_ue.DockableWindowDragOperation.md#getclass)
- [GetName](ue_ue.DockableWindowDragOperation.md#getname)
- [GetOuter](ue_ue.DockableWindowDragOperation.md#getouter)
- [GetWorld](ue_ue.DockableWindowDragOperation.md#getworld)
- [Find](ue_ue.DockableWindowDragOperation.md#find)
- [Load](ue_ue.DockableWindowDragOperation.md#load)
- [StaticClass](ue_ue.DockableWindowDragOperation.md#staticclass)

## Constructors

### constructor

• **new DockableWindowDragOperation**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ViewportDragOperation](ue_ue.ViewportDragOperation.md).[constructor](ue_ue.ViewportDragOperation.md#constructor)

## Properties

### \_\_tid\_DockableWindowDragOperation\_\_

• **\_\_tid\_DockableWindowDragOperation\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ViewportDragOperation](ue_ue.ViewportDragOperation.md).[__tid_Object__](ue_ue.ViewportDragOperation.md#__tid_object__)

___

### \_\_tid\_ViewportDragOperation\_\_

• **\_\_tid\_ViewportDragOperation\_\_**: `boolean`

#### Inherited from

[ViewportDragOperation](ue_ue.ViewportDragOperation.md).[__tid_ViewportDragOperation__](ue_ue.ViewportDragOperation.md#__tid_viewportdragoperation__)

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

[ViewportDragOperation](ue_ue.ViewportDragOperation.md).[CreateDefaultSubobject](ue_ue.ViewportDragOperation.md#createdefaultsubobject)

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

[ViewportDragOperation](ue_ue.ViewportDragOperation.md).[ExecuteUbergraph](ue_ue.ViewportDragOperation.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ViewportDragOperation](ue_ue.ViewportDragOperation.md).[GetClass](ue_ue.ViewportDragOperation.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ViewportDragOperation](ue_ue.ViewportDragOperation.md).[GetName](ue_ue.ViewportDragOperation.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ViewportDragOperation](ue_ue.ViewportDragOperation.md).[GetOuter](ue_ue.ViewportDragOperation.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ViewportDragOperation](ue_ue.ViewportDragOperation.md).[GetWorld](ue_ue.ViewportDragOperation.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DockableWindowDragOperation`](ue_ue.DockableWindowDragOperation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DockableWindowDragOperation`](ue_ue.DockableWindowDragOperation.md)

#### Overrides

[ViewportDragOperation](ue_ue.ViewportDragOperation.md).[Find](ue_ue.ViewportDragOperation.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DockableWindowDragOperation`](ue_ue.DockableWindowDragOperation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DockableWindowDragOperation`](ue_ue.DockableWindowDragOperation.md)

#### Overrides

[ViewportDragOperation](ue_ue.ViewportDragOperation.md).[Load](ue_ue.ViewportDragOperation.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ViewportDragOperation](ue_ue.ViewportDragOperation.md).[StaticClass](ue_ue.ViewportDragOperation.md#staticclass)
