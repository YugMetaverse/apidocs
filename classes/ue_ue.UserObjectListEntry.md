[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UserObjectListEntry

# Class: UserObjectListEntry

[ue/ue](../modules/ue_ue.md).UserObjectListEntry

## Hierarchy

- [`UserListEntry`](ue_ue.UserListEntry.md)

  ↳ **`UserObjectListEntry`**

## Table of contents

### Constructors

- [constructor](ue_ue.UserObjectListEntry.md#constructor)

### Properties

- [\_\_tid\_Interface\_\_](ue_ue.UserObjectListEntry.md#__tid_interface__)
- [\_\_tid\_Object\_\_](ue_ue.UserObjectListEntry.md#__tid_object__)
- [\_\_tid\_UserListEntry\_\_](ue_ue.UserObjectListEntry.md#__tid_userlistentry__)
- [\_\_tid\_UserObjectListEntry\_\_](ue_ue.UserObjectListEntry.md#__tid_userobjectlistentry__)

### Methods

- [BP\_OnEntryReleased](ue_ue.UserObjectListEntry.md#bp_onentryreleased)
- [BP\_OnItemExpansionChanged](ue_ue.UserObjectListEntry.md#bp_onitemexpansionchanged)
- [BP\_OnItemSelectionChanged](ue_ue.UserObjectListEntry.md#bp_onitemselectionchanged)
- [CreateDefaultSubobject](ue_ue.UserObjectListEntry.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UserObjectListEntry.md#executeubergraph)
- [GetClass](ue_ue.UserObjectListEntry.md#getclass)
- [GetName](ue_ue.UserObjectListEntry.md#getname)
- [GetOuter](ue_ue.UserObjectListEntry.md#getouter)
- [GetWorld](ue_ue.UserObjectListEntry.md#getworld)
- [OnListItemObjectSet](ue_ue.UserObjectListEntry.md#onlistitemobjectset)
- [Find](ue_ue.UserObjectListEntry.md#find)
- [Load](ue_ue.UserObjectListEntry.md#load)
- [StaticClass](ue_ue.UserObjectListEntry.md#staticclass)

## Constructors

### constructor

• **new UserObjectListEntry**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[UserListEntry](ue_ue.UserListEntry.md).[constructor](ue_ue.UserListEntry.md#constructor)

## Properties

### \_\_tid\_Interface\_\_

• **\_\_tid\_Interface\_\_**: `boolean`

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[__tid_Interface__](ue_ue.UserListEntry.md#__tid_interface__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[__tid_Object__](ue_ue.UserListEntry.md#__tid_object__)

___

### \_\_tid\_UserListEntry\_\_

• **\_\_tid\_UserListEntry\_\_**: `boolean`

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[__tid_UserListEntry__](ue_ue.UserListEntry.md#__tid_userlistentry__)

___

### \_\_tid\_UserObjectListEntry\_\_

• **\_\_tid\_UserObjectListEntry\_\_**: `boolean`

## Methods

### BP\_OnEntryReleased

▸ **BP_OnEntryReleased**(): `void`

#### Returns

`void`

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[BP_OnEntryReleased](ue_ue.UserListEntry.md#bp_onentryreleased)

___

### BP\_OnItemExpansionChanged

▸ **BP_OnItemExpansionChanged**(`bIsExpanded`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIsExpanded` | `boolean` |

#### Returns

`void`

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[BP_OnItemExpansionChanged](ue_ue.UserListEntry.md#bp_onitemexpansionchanged)

___

### BP\_OnItemSelectionChanged

▸ **BP_OnItemSelectionChanged**(`bIsSelected`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIsSelected` | `boolean` |

#### Returns

`void`

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[BP_OnItemSelectionChanged](ue_ue.UserListEntry.md#bp_onitemselectionchanged)

___

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

[UserListEntry](ue_ue.UserListEntry.md).[CreateDefaultSubobject](ue_ue.UserListEntry.md#createdefaultsubobject)

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

[UserListEntry](ue_ue.UserListEntry.md).[ExecuteUbergraph](ue_ue.UserListEntry.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[GetClass](ue_ue.UserListEntry.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[GetName](ue_ue.UserListEntry.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[GetOuter](ue_ue.UserListEntry.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[GetWorld](ue_ue.UserListEntry.md#getworld)

___

### OnListItemObjectSet

▸ **OnListItemObjectSet**(`ListItemObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ListItemObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UserObjectListEntry`](ue_ue.UserObjectListEntry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UserObjectListEntry`](ue_ue.UserObjectListEntry.md)

#### Overrides

[UserListEntry](ue_ue.UserListEntry.md).[Find](ue_ue.UserListEntry.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`UserObjectListEntry`](ue_ue.UserObjectListEntry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UserObjectListEntry`](ue_ue.UserObjectListEntry.md)

#### Overrides

[UserListEntry](ue_ue.UserListEntry.md).[Load](ue_ue.UserListEntry.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[UserListEntry](ue_ue.UserListEntry.md).[StaticClass](ue_ue.UserListEntry.md#staticclass)
