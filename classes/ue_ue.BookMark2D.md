[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BookMark2D

# Class: BookMark2D

[ue/ue](../modules/ue_ue.md).BookMark2D

## Hierarchy

- [`BookmarkBase`](ue_ue.BookmarkBase.md)

  ↳ **`BookMark2D`**

## Table of contents

### Constructors

- [constructor](ue_ue.BookMark2D.md#constructor)

### Properties

- [Location](ue_ue.BookMark2D.md#location)
- [Zoom2D](ue_ue.BookMark2D.md#zoom2d)
- [\_\_tid\_BookMark2D\_\_](ue_ue.BookMark2D.md#__tid_bookmark2d__)
- [\_\_tid\_BookmarkBase\_\_](ue_ue.BookMark2D.md#__tid_bookmarkbase__)
- [\_\_tid\_Object\_\_](ue_ue.BookMark2D.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.BookMark2D.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BookMark2D.md#executeubergraph)
- [GetClass](ue_ue.BookMark2D.md#getclass)
- [GetName](ue_ue.BookMark2D.md#getname)
- [GetOuter](ue_ue.BookMark2D.md#getouter)
- [GetWorld](ue_ue.BookMark2D.md#getworld)
- [Find](ue_ue.BookMark2D.md#find)
- [Load](ue_ue.BookMark2D.md#load)
- [StaticClass](ue_ue.BookMark2D.md#staticclass)

## Constructors

### constructor

• **new BookMark2D**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BookmarkBase](ue_ue.BookmarkBase.md).[constructor](ue_ue.BookmarkBase.md#constructor)

## Properties

### Location

• **Location**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### Zoom2D

• **Zoom2D**: `number`

___

### \_\_tid\_BookMark2D\_\_

• **\_\_tid\_BookMark2D\_\_**: `boolean`

___

### \_\_tid\_BookmarkBase\_\_

• **\_\_tid\_BookmarkBase\_\_**: `boolean`

#### Inherited from

[BookmarkBase](ue_ue.BookmarkBase.md).[__tid_BookmarkBase__](ue_ue.BookmarkBase.md#__tid_bookmarkbase__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BookmarkBase](ue_ue.BookmarkBase.md).[__tid_Object__](ue_ue.BookmarkBase.md#__tid_object__)

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

[BookmarkBase](ue_ue.BookmarkBase.md).[CreateDefaultSubobject](ue_ue.BookmarkBase.md#createdefaultsubobject)

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

[BookmarkBase](ue_ue.BookmarkBase.md).[ExecuteUbergraph](ue_ue.BookmarkBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BookmarkBase](ue_ue.BookmarkBase.md).[GetClass](ue_ue.BookmarkBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BookmarkBase](ue_ue.BookmarkBase.md).[GetName](ue_ue.BookmarkBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BookmarkBase](ue_ue.BookmarkBase.md).[GetOuter](ue_ue.BookmarkBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BookmarkBase](ue_ue.BookmarkBase.md).[GetWorld](ue_ue.BookmarkBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BookMark2D`](ue_ue.BookMark2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BookMark2D`](ue_ue.BookMark2D.md)

#### Overrides

[BookmarkBase](ue_ue.BookmarkBase.md).[Find](ue_ue.BookmarkBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BookMark2D`](ue_ue.BookMark2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BookMark2D`](ue_ue.BookMark2D.md)

#### Overrides

[BookmarkBase](ue_ue.BookmarkBase.md).[Load](ue_ue.BookmarkBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BookmarkBase](ue_ue.BookmarkBase.md).[StaticClass](ue_ue.BookmarkBase.md#staticclass)
