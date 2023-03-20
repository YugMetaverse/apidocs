[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlendProfile

# Class: BlendProfile

[ue/ue](../modules/ue_ue.md).BlendProfile

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`BlendProfile`**

## Table of contents

### Constructors

- [constructor](ue_ue.BlendProfile.md#constructor)

### Properties

- [OwningSkeleton](ue_ue.BlendProfile.md#owningskeleton)
- [ProfileEntries](ue_ue.BlendProfile.md#profileentries)
- [\_\_tid\_BlendProfile\_\_](ue_ue.BlendProfile.md#__tid_blendprofile__)
- [\_\_tid\_Object\_\_](ue_ue.BlendProfile.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.BlendProfile.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BlendProfile.md#executeubergraph)
- [GetClass](ue_ue.BlendProfile.md#getclass)
- [GetName](ue_ue.BlendProfile.md#getname)
- [GetOuter](ue_ue.BlendProfile.md#getouter)
- [GetWorld](ue_ue.BlendProfile.md#getworld)
- [Find](ue_ue.BlendProfile.md#find)
- [Load](ue_ue.BlendProfile.md#load)
- [StaticClass](ue_ue.BlendProfile.md#staticclass)

## Constructors

### constructor

• **new BlendProfile**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### OwningSkeleton

• **OwningSkeleton**: [`Skeleton`](ue_ue.Skeleton.md)

___

### ProfileEntries

• **ProfileEntries**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlendProfileBoneEntry`](ue_ue.BlendProfileBoneEntry.md)\>

___

### \_\_tid\_BlendProfile\_\_

• **\_\_tid\_BlendProfile\_\_**: `boolean`

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlendProfile`](ue_ue.BlendProfile.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlendProfile`](ue_ue.BlendProfile.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BlendProfile`](ue_ue.BlendProfile.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlendProfile`](ue_ue.BlendProfile.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
