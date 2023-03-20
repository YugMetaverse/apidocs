[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UserListEntryLibrary

# Class: UserListEntryLibrary

[ue/ue](../modules/ue_ue.md).UserListEntryLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`UserListEntryLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.UserListEntryLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.UserListEntryLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.UserListEntryLibrary.md#__tid_object__)
- [\_\_tid\_UserListEntryLibrary\_\_](ue_ue.UserListEntryLibrary.md#__tid_userlistentrylibrary__)

### Methods

- [CreateDefaultSubobject](ue_ue.UserListEntryLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UserListEntryLibrary.md#executeubergraph)
- [GetClass](ue_ue.UserListEntryLibrary.md#getclass)
- [GetName](ue_ue.UserListEntryLibrary.md#getname)
- [GetOuter](ue_ue.UserListEntryLibrary.md#getouter)
- [GetWorld](ue_ue.UserListEntryLibrary.md#getworld)
- [Find](ue_ue.UserListEntryLibrary.md#find)
- [GetOwningListView](ue_ue.UserListEntryLibrary.md#getowninglistview)
- [IsListItemExpanded](ue_ue.UserListEntryLibrary.md#islistitemexpanded)
- [IsListItemSelected](ue_ue.UserListEntryLibrary.md#islistitemselected)
- [Load](ue_ue.UserListEntryLibrary.md#load)
- [StaticClass](ue_ue.UserListEntryLibrary.md#staticclass)

## Constructors

### constructor

• **new UserListEntryLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

___

### \_\_tid\_UserListEntryLibrary\_\_

• **\_\_tid\_UserListEntryLibrary\_\_**: `boolean`

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UserListEntryLibrary`](ue_ue.UserListEntryLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UserListEntryLibrary`](ue_ue.UserListEntryLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetOwningListView

▸ `Static` **GetOwningListView**(`UserListEntry`): [`ListViewBase`](ue_ue.ListViewBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `UserListEntry` | [`UserListEntry`](ue_ue.UserListEntry.md) |

#### Returns

[`ListViewBase`](ue_ue.ListViewBase.md)

___

### IsListItemExpanded

▸ `Static` **IsListItemExpanded**(`UserListEntry`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `UserListEntry` | [`UserListEntry`](ue_ue.UserListEntry.md) |

#### Returns

`boolean`

___

### IsListItemSelected

▸ `Static` **IsListItemSelected**(`UserListEntry`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `UserListEntry` | [`UserListEntry`](ue_ue.UserListEntry.md) |

#### Returns

`boolean`

___

### Load

▸ `Static` **Load**(`InName`): [`UserListEntryLibrary`](ue_ue.UserListEntryLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UserListEntryLibrary`](ue_ue.UserListEntryLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
