[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimationSharingManager

# Class: AnimationSharingManager

[ue/ue](../modules/ue_ue.md).AnimationSharingManager

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AnimationSharingManager`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimationSharingManager.md#constructor)

### Properties

- [PerSkeletonData](ue_ue.AnimationSharingManager.md#perskeletondata)
- [Skeletons](ue_ue.AnimationSharingManager.md#skeletons)
- [\_\_tid\_AnimationSharingManager\_\_](ue_ue.AnimationSharingManager.md#__tid_animationsharingmanager__)
- [\_\_tid\_Object\_\_](ue_ue.AnimationSharingManager.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimationSharingManager.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimationSharingManager.md#executeubergraph)
- [GetClass](ue_ue.AnimationSharingManager.md#getclass)
- [GetName](ue_ue.AnimationSharingManager.md#getname)
- [GetOuter](ue_ue.AnimationSharingManager.md#getouter)
- [GetWorld](ue_ue.AnimationSharingManager.md#getworld)
- [RegisterActorWithSkeletonBP](ue_ue.AnimationSharingManager.md#registeractorwithskeletonbp)
- [AnimationSharingEnabled](ue_ue.AnimationSharingManager.md#animationsharingenabled)
- [CreateAnimationSharingManager](ue_ue.AnimationSharingManager.md#createanimationsharingmanager)
- [Find](ue_ue.AnimationSharingManager.md#find)
- [GetAnimationSharingManager](ue_ue.AnimationSharingManager.md#getanimationsharingmanager)
- [Load](ue_ue.AnimationSharingManager.md#load)
- [StaticClass](ue_ue.AnimationSharingManager.md#staticclass)

## Constructors

### constructor

• **new AnimationSharingManager**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:17095](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17095)

## Properties

### PerSkeletonData

• **PerSkeletonData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimSharingInstance`](ue_ue.AnimSharingInstance.md)\>

#### Defined in

[ue/ue.d.ts:17097](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17097)

___

### Skeletons

• **Skeletons**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Skeleton`](ue_ue.Skeleton.md)\>

#### Defined in

[ue/ue.d.ts:17096](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17096)

___

### \_\_tid\_AnimationSharingManager\_\_

• **\_\_tid\_AnimationSharingManager\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:17106](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17106)

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

### RegisterActorWithSkeletonBP

▸ **RegisterActorWithSkeletonBP**(`InActor`, `SharingSkeleton`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `SharingSkeleton` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Skeleton`](ue_ue.Skeleton.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:17098](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17098)

___

### AnimationSharingEnabled

▸ `Static` **AnimationSharingEnabled**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:17099](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17099)

___

### CreateAnimationSharingManager

▸ `Static` **CreateAnimationSharingManager**(`WorldContextObject`, `Setup`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Setup` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimationSharingSetup`](ue_ue.AnimationSharingSetup.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:17100](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17100)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimationSharingManager`](ue_ue.AnimationSharingManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimationSharingManager`](ue_ue.AnimationSharingManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:17103](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17103)

___

### GetAnimationSharingManager

▸ `Static` **GetAnimationSharingManager**(`WorldContextObject`): [`AnimationSharingManager`](ue_ue.AnimationSharingManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`AnimationSharingManager`](ue_ue.AnimationSharingManager.md)

#### Defined in

[ue/ue.d.ts:17101](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17101)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimationSharingManager`](ue_ue.AnimationSharingManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimationSharingManager`](ue_ue.AnimationSharingManager.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:17104](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17104)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:17102](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17102)
