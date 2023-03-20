[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelSequenceDirector

# Class: LevelSequenceDirector

[ue/ue](../modules/ue_ue.md).LevelSequenceDirector

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`LevelSequenceDirector`**

## Table of contents

### Constructors

- [constructor](ue_ue.LevelSequenceDirector.md#constructor)

### Properties

- [Player](ue_ue.LevelSequenceDirector.md#player)
- [\_\_tid\_LevelSequenceDirector\_\_](ue_ue.LevelSequenceDirector.md#__tid_levelsequencedirector__)
- [\_\_tid\_Object\_\_](ue_ue.LevelSequenceDirector.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.LevelSequenceDirector.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LevelSequenceDirector.md#executeubergraph)
- [GetClass](ue_ue.LevelSequenceDirector.md#getclass)
- [GetName](ue_ue.LevelSequenceDirector.md#getname)
- [GetOuter](ue_ue.LevelSequenceDirector.md#getouter)
- [GetWorld](ue_ue.LevelSequenceDirector.md#getworld)
- [OnCreated](ue_ue.LevelSequenceDirector.md#oncreated)
- [Find](ue_ue.LevelSequenceDirector.md#find)
- [Load](ue_ue.LevelSequenceDirector.md#load)
- [StaticClass](ue_ue.LevelSequenceDirector.md#staticclass)

## Constructors

### constructor

• **new LevelSequenceDirector**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:45175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45175)

## Properties

### Player

• **Player**: [`LevelSequencePlayer`](ue_ue.LevelSequencePlayer.md)

#### Defined in

[ue/ue.d.ts:45176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45176)

___

### \_\_tid\_LevelSequenceDirector\_\_

• **\_\_tid\_LevelSequenceDirector\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:45182](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45182)

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

### OnCreated

▸ **OnCreated**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:45177](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45177)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LevelSequenceDirector`](ue_ue.LevelSequenceDirector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LevelSequenceDirector`](ue_ue.LevelSequenceDirector.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:45179](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45179)

___

### Load

▸ `Static` **Load**(`InName`): [`LevelSequenceDirector`](ue_ue.LevelSequenceDirector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LevelSequenceDirector`](ue_ue.LevelSequenceDirector.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:45180](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45180)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:45178](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45178)
