[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimSharingInstance

# Class: AnimSharingInstance

[ue/ue](../modules/ue_ue.md).AnimSharingInstance

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AnimSharingInstance`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimSharingInstance.md#constructor)

### Properties

- [RegisteredActors](ue_ue.AnimSharingInstance.md#registeredactors)
- [SharingActor](ue_ue.AnimSharingInstance.md#sharingactor)
- [StateEnum](ue_ue.AnimSharingInstance.md#stateenum)
- [StateProcessor](ue_ue.AnimSharingInstance.md#stateprocessor)
- [UsedAnimationSequences](ue_ue.AnimSharingInstance.md#usedanimationsequences)
- [\_\_tid\_AnimSharingInstance\_\_](ue_ue.AnimSharingInstance.md#__tid_animsharinginstance__)
- [\_\_tid\_Object\_\_](ue_ue.AnimSharingInstance.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimSharingInstance.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimSharingInstance.md#executeubergraph)
- [GetClass](ue_ue.AnimSharingInstance.md#getclass)
- [GetName](ue_ue.AnimSharingInstance.md#getname)
- [GetOuter](ue_ue.AnimSharingInstance.md#getouter)
- [GetWorld](ue_ue.AnimSharingInstance.md#getworld)
- [Find](ue_ue.AnimSharingInstance.md#find)
- [Load](ue_ue.AnimSharingInstance.md#load)
- [StaticClass](ue_ue.AnimSharingInstance.md#staticclass)

## Constructors

### constructor

• **new AnimSharingInstance**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:17001](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17001)

## Properties

### RegisteredActors

• **RegisteredActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:17002](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17002)

___

### SharingActor

• **SharingActor**: [`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:17006](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17006)

___

### StateEnum

• **StateEnum**: [`Enum`](ue_ue.Enum.md)

#### Defined in

[ue/ue.d.ts:17005](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17005)

___

### StateProcessor

• **StateProcessor**: [`AnimationSharingStateProcessor`](ue_ue.AnimationSharingStateProcessor.md)

#### Defined in

[ue/ue.d.ts:17003](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17003)

___

### UsedAnimationSequences

• **UsedAnimationSequences**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimSequence`](ue_ue.AnimSequence.md)\>

#### Defined in

[ue/ue.d.ts:17004](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17004)

___

### \_\_tid\_AnimSharingInstance\_\_

• **\_\_tid\_AnimSharingInstance\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:17011](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17011)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimSharingInstance`](ue_ue.AnimSharingInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimSharingInstance`](ue_ue.AnimSharingInstance.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:17008](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17008)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimSharingInstance`](ue_ue.AnimSharingInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimSharingInstance`](ue_ue.AnimSharingInstance.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:17009](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17009)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:17007](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17007)
