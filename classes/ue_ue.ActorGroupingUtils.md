[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ActorGroupingUtils

# Class: ActorGroupingUtils

[ue/ue](../modules/ue_ue.md).ActorGroupingUtils

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ActorGroupingUtils`**

## Table of contents

### Constructors

- [constructor](ue_ue.ActorGroupingUtils.md#constructor)

### Properties

- [\_\_tid\_ActorGroupingUtils\_\_](ue_ue.ActorGroupingUtils.md#__tid_actorgroupingutils__)
- [\_\_tid\_Object\_\_](ue_ue.ActorGroupingUtils.md#__tid_object__)

### Methods

- [AddSelectedToGroup](ue_ue.ActorGroupingUtils.md#addselectedtogroup)
- [CreateDefaultSubobject](ue_ue.ActorGroupingUtils.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ActorGroupingUtils.md#executeubergraph)
- [GetClass](ue_ue.ActorGroupingUtils.md#getclass)
- [GetName](ue_ue.ActorGroupingUtils.md#getname)
- [GetOuter](ue_ue.ActorGroupingUtils.md#getouter)
- [GetWorld](ue_ue.ActorGroupingUtils.md#getworld)
- [GroupActors](ue_ue.ActorGroupingUtils.md#groupactors)
- [GroupSelected](ue_ue.ActorGroupingUtils.md#groupselected)
- [LockSelectedGroups](ue_ue.ActorGroupingUtils.md#lockselectedgroups)
- [RemoveSelectedFromGroup](ue_ue.ActorGroupingUtils.md#removeselectedfromgroup)
- [UngroupActors](ue_ue.ActorGroupingUtils.md#ungroupactors)
- [UngroupSelected](ue_ue.ActorGroupingUtils.md#ungroupselected)
- [UnlockSelectedGroups](ue_ue.ActorGroupingUtils.md#unlockselectedgroups)
- [Find](ue_ue.ActorGroupingUtils.md#find)
- [Get](ue_ue.ActorGroupingUtils.md#get)
- [IsGroupingActive](ue_ue.ActorGroupingUtils.md#isgroupingactive)
- [Load](ue_ue.ActorGroupingUtils.md#load)
- [SetGroupingActive](ue_ue.ActorGroupingUtils.md#setgroupingactive)
- [StaticClass](ue_ue.ActorGroupingUtils.md#staticclass)

## Constructors

### constructor

• **new ActorGroupingUtils**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_ActorGroupingUtils\_\_

• **\_\_tid\_ActorGroupingUtils\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

## Methods

### AddSelectedToGroup

▸ **AddSelectedToGroup**(): `void`

#### Returns

`void`

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

### GroupActors

▸ **GroupActors**(`ActorsToGroup`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActorsToGroup` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### GroupSelected

▸ **GroupSelected**(): `void`

#### Returns

`void`

___

### LockSelectedGroups

▸ **LockSelectedGroups**(): `void`

#### Returns

`void`

___

### RemoveSelectedFromGroup

▸ **RemoveSelectedFromGroup**(): `void`

#### Returns

`void`

___

### UngroupActors

▸ **UngroupActors**(`ActorsToUngroup`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActorsToUngroup` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### UngroupSelected

▸ **UngroupSelected**(): `void`

#### Returns

`void`

___

### UnlockSelectedGroups

▸ **UnlockSelectedGroups**(): `void`

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ActorGroupingUtils`](ue_ue.ActorGroupingUtils.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ActorGroupingUtils`](ue_ue.ActorGroupingUtils.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Get

▸ `Static` **Get**(): [`ActorGroupingUtils`](ue_ue.ActorGroupingUtils.md)

#### Returns

[`ActorGroupingUtils`](ue_ue.ActorGroupingUtils.md)

___

### IsGroupingActive

▸ `Static` **IsGroupingActive**(): `boolean`

#### Returns

`boolean`

___

### Load

▸ `Static` **Load**(`InName`): [`ActorGroupingUtils`](ue_ue.ActorGroupingUtils.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ActorGroupingUtils`](ue_ue.ActorGroupingUtils.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### SetGroupingActive

▸ `Static` **SetGroupingActive**(`bInGroupingActive`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInGroupingActive` | `boolean` |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
