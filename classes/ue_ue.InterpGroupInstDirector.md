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

## Properties

### Group

• **Group**: [`InterpGroup`](ue_ue.InterpGroup.md)

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[Group](ue_ue.InterpGroupInst.md#group)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[GroupActor](ue_ue.InterpGroupInst.md#groupactor)

___

### TrackInst

• **TrackInst**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpTrackInst`](ue_ue.InterpTrackInst.md)\>

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[TrackInst](ue_ue.InterpGroupInst.md#trackinst)

___

### \_\_tid\_InterpGroupInstDirector\_\_

• **\_\_tid\_InterpGroupInstDirector\_\_**: `boolean`

___

### \_\_tid\_InterpGroupInst\_\_

• **\_\_tid\_InterpGroupInst\_\_**: `boolean`

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[__tid_InterpGroupInst__](ue_ue.InterpGroupInst.md#__tid_interpgroupinst__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[__tid_Object__](ue_ue.InterpGroupInst.md#__tid_object__)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[GetClass](ue_ue.InterpGroupInst.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[GetName](ue_ue.InterpGroupInst.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[GetOuter](ue_ue.InterpGroupInst.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InterpGroupInst](ue_ue.InterpGroupInst.md).[GetWorld](ue_ue.InterpGroupInst.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpGroupInst](ue_ue.InterpGroupInst.md).[StaticClass](ue_ue.InterpGroupInst.md#staticclass)
