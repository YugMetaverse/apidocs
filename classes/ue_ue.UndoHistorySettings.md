[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UndoHistorySettings

# Class: UndoHistorySettings

[ue/ue](../modules/ue_ue.md).UndoHistorySettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`UndoHistorySettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.UndoHistorySettings.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.UndoHistorySettings.md#__tid_object__)
- [\_\_tid\_UndoHistorySettings\_\_](ue_ue.UndoHistorySettings.md#__tid_undohistorysettings__)
- [bShowTransactionDetails](ue_ue.UndoHistorySettings.md#bshowtransactiondetails)

### Methods

- [CreateDefaultSubobject](ue_ue.UndoHistorySettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UndoHistorySettings.md#executeubergraph)
- [GetClass](ue_ue.UndoHistorySettings.md#getclass)
- [GetName](ue_ue.UndoHistorySettings.md#getname)
- [GetOuter](ue_ue.UndoHistorySettings.md#getouter)
- [GetWorld](ue_ue.UndoHistorySettings.md#getworld)
- [Find](ue_ue.UndoHistorySettings.md#find)
- [Load](ue_ue.UndoHistorySettings.md#load)
- [StaticClass](ue_ue.UndoHistorySettings.md#staticclass)

## Constructors

### constructor

• **new UndoHistorySettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_UndoHistorySettings\_\_

• **\_\_tid\_UndoHistorySettings\_\_**: `boolean`

___

### bShowTransactionDetails

• **bShowTransactionDetails**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UndoHistorySettings`](ue_ue.UndoHistorySettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UndoHistorySettings`](ue_ue.UndoHistorySettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`UndoHistorySettings`](ue_ue.UndoHistorySettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UndoHistorySettings`](ue_ue.UndoHistorySettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
