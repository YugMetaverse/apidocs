[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundGroups

# Class: SoundGroups

[ue/ue](../modules/ue_ue.md).SoundGroups

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SoundGroups`**

## Table of contents

### Constructors

- [constructor](ue_ue.SoundGroups.md#constructor)

### Properties

- [SoundGroupProfiles](ue_ue.SoundGroups.md#soundgroupprofiles)
- [\_\_tid\_Object\_\_](ue_ue.SoundGroups.md#__tid_object__)
- [\_\_tid\_SoundGroups\_\_](ue_ue.SoundGroups.md#__tid_soundgroups__)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundGroups.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundGroups.md#executeubergraph)
- [GetClass](ue_ue.SoundGroups.md#getclass)
- [GetName](ue_ue.SoundGroups.md#getname)
- [GetOuter](ue_ue.SoundGroups.md#getouter)
- [GetWorld](ue_ue.SoundGroups.md#getworld)
- [Find](ue_ue.SoundGroups.md#find)
- [Load](ue_ue.SoundGroups.md#load)
- [StaticClass](ue_ue.SoundGroups.md#staticclass)

## Constructors

### constructor

• **new SoundGroups**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:61266](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61266)

## Properties

### SoundGroupProfiles

• **SoundGroupProfiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundGroup`](ue_ue.SoundGroup.md)\>

#### Defined in

[ue/ue.d.ts:61267](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61267)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SoundGroups\_\_

• **\_\_tid\_SoundGroups\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:61272](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61272)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundGroups`](ue_ue.SoundGroups.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundGroups`](ue_ue.SoundGroups.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:61269](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61269)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundGroups`](ue_ue.SoundGroups.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundGroups`](ue_ue.SoundGroups.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:61270](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61270)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:61268](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61268)
