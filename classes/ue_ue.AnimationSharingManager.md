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

## Properties

### PerSkeletonData

• **PerSkeletonData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimSharingInstance`](ue_ue.AnimSharingInstance.md)\>

___

### Skeletons

• **Skeletons**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Skeleton`](ue_ue.Skeleton.md)\>

___

### \_\_tid\_AnimationSharingManager\_\_

• **\_\_tid\_AnimationSharingManager\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

### RegisterActorWithSkeletonBP

▸ **RegisterActorWithSkeletonBP**(`InActor`, `SharingSkeleton`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `SharingSkeleton` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Skeleton`](ue_ue.Skeleton.md)\> |

#### Returns

`void`

___

### AnimationSharingEnabled

▸ `Static` **AnimationSharingEnabled**(): `boolean`

#### Returns

`boolean`

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

___

### GetAnimationSharingManager

▸ `Static` **GetAnimationSharingManager**(`WorldContextObject`): [`AnimationSharingManager`](ue_ue.AnimationSharingManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`AnimationSharingManager`](ue_ue.AnimationSharingManager.md)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
