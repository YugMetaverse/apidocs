[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BookMark

# Class: BookMark

[ue/ue](../modules/ue_ue.md).BookMark

## Hierarchy

- [`BookmarkBase`](ue_ue.BookmarkBase.md)

  ↳ **`BookMark`**

## Table of contents

### Constructors

- [constructor](ue_ue.BookMark.md#constructor)

### Properties

- [HiddenLevels](ue_ue.BookMark.md#hiddenlevels)
- [Location](ue_ue.BookMark.md#location)
- [Rotation](ue_ue.BookMark.md#rotation)
- [\_\_tid\_BookMark\_\_](ue_ue.BookMark.md#__tid_bookmark__)
- [\_\_tid\_BookmarkBase\_\_](ue_ue.BookMark.md#__tid_bookmarkbase__)
- [\_\_tid\_Object\_\_](ue_ue.BookMark.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.BookMark.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BookMark.md#executeubergraph)
- [GetClass](ue_ue.BookMark.md#getclass)
- [GetName](ue_ue.BookMark.md#getname)
- [GetOuter](ue_ue.BookMark.md#getouter)
- [GetWorld](ue_ue.BookMark.md#getworld)
- [Find](ue_ue.BookMark.md#find)
- [Load](ue_ue.BookMark.md#load)
- [StaticClass](ue_ue.BookMark.md#staticclass)

## Constructors

### constructor

• **new BookMark**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BookmarkBase](ue_ue.BookmarkBase.md).[constructor](ue_ue.BookmarkBase.md#constructor)

#### Defined in

[ue/ue.d.ts:9079](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9079)

## Properties

### HiddenLevels

• **HiddenLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:9082](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9082)

___

### Location

• **Location**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:9080](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9080)

___

### Rotation

• **Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:9081](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9081)

___

### \_\_tid\_BookMark\_\_

• **\_\_tid\_BookMark\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:9087](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9087)

___

### \_\_tid\_BookmarkBase\_\_

• **\_\_tid\_BookmarkBase\_\_**: `boolean`

#### Inherited from

[BookmarkBase](ue_ue.BookmarkBase.md).[__tid_BookmarkBase__](ue_ue.BookmarkBase.md#__tid_bookmarkbase__)

#### Defined in

[ue/ue.d.ts:9075](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9075)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BookmarkBase](ue_ue.BookmarkBase.md).[__tid_Object__](ue_ue.BookmarkBase.md#__tid_object__)

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

[BookmarkBase](ue_ue.BookmarkBase.md).[CreateDefaultSubobject](ue_ue.BookmarkBase.md#createdefaultsubobject)

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

[BookmarkBase](ue_ue.BookmarkBase.md).[ExecuteUbergraph](ue_ue.BookmarkBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BookmarkBase](ue_ue.BookmarkBase.md).[GetClass](ue_ue.BookmarkBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BookmarkBase](ue_ue.BookmarkBase.md).[GetName](ue_ue.BookmarkBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BookmarkBase](ue_ue.BookmarkBase.md).[GetOuter](ue_ue.BookmarkBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BookmarkBase](ue_ue.BookmarkBase.md).[GetWorld](ue_ue.BookmarkBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BookMark`](ue_ue.BookMark.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BookMark`](ue_ue.BookMark.md)

#### Overrides

[BookmarkBase](ue_ue.BookmarkBase.md).[Find](ue_ue.BookmarkBase.md#find)

#### Defined in

[ue/ue.d.ts:9084](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9084)

___

### Load

▸ `Static` **Load**(`InName`): [`BookMark`](ue_ue.BookMark.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BookMark`](ue_ue.BookMark.md)

#### Overrides

[BookmarkBase](ue_ue.BookmarkBase.md).[Load](ue_ue.BookmarkBase.md#load)

#### Defined in

[ue/ue.d.ts:9085](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9085)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BookmarkBase](ue_ue.BookmarkBase.md).[StaticClass](ue_ue.BookmarkBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:9083](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9083)
