[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UserListEntry

# Class: UserListEntry

[ue/ue](../modules/ue_ue.md).UserListEntry

## Hierarchy

- [`Interface`](ue_ue.Interface.md)

  ↳ **`UserListEntry`**

  ↳↳ [`UserObjectListEntry`](ue_ue.UserObjectListEntry.md)

## Table of contents

### Constructors

- [constructor](ue_ue.UserListEntry.md#constructor)

### Properties

- [\_\_tid\_Interface\_\_](ue_ue.UserListEntry.md#__tid_interface__)
- [\_\_tid\_Object\_\_](ue_ue.UserListEntry.md#__tid_object__)
- [\_\_tid\_UserListEntry\_\_](ue_ue.UserListEntry.md#__tid_userlistentry__)

### Methods

- [BP\_OnEntryReleased](ue_ue.UserListEntry.md#bp_onentryreleased)
- [BP\_OnItemExpansionChanged](ue_ue.UserListEntry.md#bp_onitemexpansionchanged)
- [BP\_OnItemSelectionChanged](ue_ue.UserListEntry.md#bp_onitemselectionchanged)
- [CreateDefaultSubobject](ue_ue.UserListEntry.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UserListEntry.md#executeubergraph)
- [GetClass](ue_ue.UserListEntry.md#getclass)
- [GetName](ue_ue.UserListEntry.md#getname)
- [GetOuter](ue_ue.UserListEntry.md#getouter)
- [GetWorld](ue_ue.UserListEntry.md#getworld)
- [Find](ue_ue.UserListEntry.md#find)
- [Load](ue_ue.UserListEntry.md#load)
- [StaticClass](ue_ue.UserListEntry.md#staticclass)

## Constructors

### constructor

• **new UserListEntry**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Interface](ue_ue.Interface.md).[constructor](ue_ue.Interface.md#constructor)

#### Defined in

[ue/ue.d.ts:64966](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64966)

## Properties

### \_\_tid\_Interface\_\_

• **\_\_tid\_Interface\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Interface__](ue_ue.Interface.md#__tid_interface__)

#### Defined in

[ue/ue.d.ts:8142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8142)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Object__](ue_ue.Interface.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_UserListEntry\_\_

• **\_\_tid\_UserListEntry\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64974](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64974)

## Methods

### BP\_OnEntryReleased

▸ **BP_OnEntryReleased**(): `void`

#### Returns

`void`

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

[Interface](ue_ue.Interface.md).[CreateDefaultSubobject](ue_ue.Interface.md#createdefaultsubobject)

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

[Interface](ue_ue.Interface.md).[ExecuteUbergraph](ue_ue.Interface.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetClass](ue_ue.Interface.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Interface](ue_ue.Interface.md).[GetName](ue_ue.Interface.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetOuter](ue_ue.Interface.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetWorld](ue_ue.Interface.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UserListEntry`](ue_ue.UserListEntry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UserListEntry`](ue_ue.UserListEntry.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Find](ue_ue.Interface.md#find)

#### Defined in

[ue/ue.d.ts:64971](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64971)

___

### Load

▸ `Static` **Load**(`InName`): [`UserListEntry`](ue_ue.UserListEntry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UserListEntry`](ue_ue.UserListEntry.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Load](ue_ue.Interface.md#load)

#### Defined in

[ue/ue.d.ts:64972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64972)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Interface](ue_ue.Interface.md).[StaticClass](ue_ue.Interface.md#staticclass)

#### Defined in

[ue/ue.d.ts:64970](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64970)
