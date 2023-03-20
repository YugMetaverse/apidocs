[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpGroupInstDirector

# Class: InterpGroupInstDirector

[ue/ue](../modules/ue_ue.md).InterpGroupInstDirector

## Hierarchy

- [`InterpGroupInst`](ue_ue.InterpGroupInst.md)

  ↳ **`InterpGroupInstDirector`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpGroupInstDirector.md#constructor)

### Properties

- [Group](ue_ue.InterpGroupInstDirector.md#group)
- [GroupActor](ue_ue.InterpGroupInstDirector.md#groupactor)
- [TrackInst](ue_ue.InterpGroupInstDirector.md#trackinst)
- [\_\_tid\_InterpGroupInstDirector\_\_](ue_ue.InterpGroupInstDirector.md#__tid_interpgroupinstdirector__)
- [\_\_tid\_InterpGroupInst\_\_](ue_ue.InterpGroupInstDirector.md#__tid_interpgroupinst__)
- [\_\_tid\_Object\_\_](ue_ue.InterpGroupInstDirector.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpGroupInstDirector.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpGroupInstDirector.md#executeubergraph)
- [GetClass](ue_ue.InterpGroupInstDirector.md#getclass)
- [GetName](ue_ue.InterpGroupInstDirector.md#getname)
- [GetOuter](ue_ue.InterpGroupInstDirector.md#getouter)
- [GetWorld](ue_ue.InterpGroupInstDirector.md#getworld)
- [Find](ue_ue.InterpGroupInstDirector.md#find)
- [Load](ue_ue.InterpGroupInstDirector.md#load)
- [StaticClass](ue_ue.InterpGroupInstDirector.md#staticclass)

## Constructors

### constructor

• **new InterpGroupInstDirector**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InterpGroupInst](ue_ue.InterpGroupInst.md).[constructor](ue_ue.InterpGroupInst.md#constructor)

#### Defined in

[ue/ue.d.ts:39705](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39705)

## Properties

### Group

• **Group**: [`InterpGroup`](ue_ue.InterpGroup.md)

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[Group](ue_ue.InterpGroupInst.md#group)

#### Defined in

[ue/ue.d.ts:7543](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7543)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[GroupActor](ue_ue.InterpGroupInst.md#groupactor)

#### Defined in

[ue/ue.d.ts:7544](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7544)

___

### TrackInst

• **TrackInst**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpTrackInst`](ue_ue.InterpTrackInst.md)\>

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[TrackInst](ue_ue.InterpGroupInst.md#trackinst)

#### Defined in

[ue/ue.d.ts:7545](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7545)

___

### \_\_tid\_InterpGroupInstDirector\_\_

• **\_\_tid\_InterpGroupInstDirector\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:39710](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39710)

___

### \_\_tid\_InterpGroupInst\_\_

• **\_\_tid\_InterpGroupInst\_\_**: `boolean`

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[__tid_InterpGroupInst__](ue_ue.InterpGroupInst.md#__tid_interpgroupinst__)

#### Defined in

[ue/ue.d.ts:7550](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7550)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[__tid_Object__](ue_ue.InterpGroupInst.md#__tid_object__)

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

[InterpGroupInst](ue_ue.InterpGroupInst.md).[CreateDefaultSubobject](ue_ue.InterpGroupInst.md#createdefaultsubobject)

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

[InterpGroupInst](ue_ue.InterpGroupInst.md).[ExecuteUbergraph](ue_ue.InterpGroupInst.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[GetClass](ue_ue.InterpGroupInst.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[GetName](ue_ue.InterpGroupInst.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[GetOuter](ue_ue.InterpGroupInst.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[GetWorld](ue_ue.InterpGroupInst.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpGroupInstDirector`](ue_ue.InterpGroupInstDirector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpGroupInstDirector`](ue_ue.InterpGroupInstDirector.md)

#### Overrides

[InterpGroupInst](ue_ue.InterpGroupInst.md).[Find](ue_ue.InterpGroupInst.md#find)

#### Defined in

[ue/ue.d.ts:39707](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39707)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpGroupInstDirector`](ue_ue.InterpGroupInstDirector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpGroupInstDirector`](ue_ue.InterpGroupInstDirector.md)

#### Overrides

[InterpGroupInst](ue_ue.InterpGroupInst.md).[Load](ue_ue.InterpGroupInst.md#load)

#### Defined in

[ue/ue.d.ts:39708](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39708)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpGroupInst](ue_ue.InterpGroupInst.md).[StaticClass](ue_ue.InterpGroupInst.md#staticclass)

#### Defined in

[ue/ue.d.ts:39706](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39706)
