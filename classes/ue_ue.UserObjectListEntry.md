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

#### Defined in

[ue/ue.d.ts:64990](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64990)

## Properties

### \_\_tid\_Interface\_\_

• **\_\_tid\_Interface\_\_**: `boolean`

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[__tid_Interface__](ue_ue.UserListEntry.md#__tid_interface__)

#### Defined in

[ue/ue.d.ts:8142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8142)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[__tid_Object__](ue_ue.UserListEntry.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_UserListEntry\_\_

• **\_\_tid\_UserListEntry\_\_**: `boolean`

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[__tid_UserListEntry__](ue_ue.UserListEntry.md#__tid_userlistentry__)

#### Defined in

[ue/ue.d.ts:64974](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64974)

___

### \_\_tid\_UserObjectListEntry\_\_

• **\_\_tid\_UserObjectListEntry\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64996](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64996)

## Methods

### BP\_OnEntryReleased

▸ **BP_OnEntryReleased**(): `void`

#### Returns

`void`

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[BP_OnEntryReleased](ue_ue.UserListEntry.md#bp_onentryreleased)

#### Defined in

[ue/ue.d.ts:64967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64967)

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

#### Defined in

[ue/ue.d.ts:64968](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64968)

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

#### Defined in

[ue/ue.d.ts:64969](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64969)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[GetClass](ue_ue.UserListEntry.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[GetName](ue_ue.UserListEntry.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[GetOuter](ue_ue.UserListEntry.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[UserListEntry](ue_ue.UserListEntry.md).[GetWorld](ue_ue.UserListEntry.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### OnListItemObjectSet

▸ **OnListItemObjectSet**(`ListItemObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ListItemObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64991](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64991)

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

#### Defined in

[ue/ue.d.ts:64993](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64993)

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

#### Defined in

[ue/ue.d.ts:64994](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64994)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[UserListEntry](ue_ue.UserListEntry.md).[StaticClass](ue_ue.UserListEntry.md#staticclass)

#### Defined in

[ue/ue.d.ts:64992](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64992)
