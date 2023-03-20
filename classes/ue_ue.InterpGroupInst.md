[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpGroupInst

# Class: InterpGroupInst

[ue/ue](../modules/ue_ue.md).InterpGroupInst

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`InterpGroupInst`**

  ↳↳ [`InterpGroupInstCamera`](ue_ue.InterpGroupInstCamera.md)

  ↳↳ [`InterpGroupInstDirector`](ue_ue.InterpGroupInstDirector.md)

## Table of contents

### Constructors

- [constructor](ue_ue.InterpGroupInst.md#constructor)

### Properties

- [Group](ue_ue.InterpGroupInst.md#group)
- [GroupActor](ue_ue.InterpGroupInst.md#groupactor)
- [TrackInst](ue_ue.InterpGroupInst.md#trackinst)
- [\_\_tid\_InterpGroupInst\_\_](ue_ue.InterpGroupInst.md#__tid_interpgroupinst__)
- [\_\_tid\_Object\_\_](ue_ue.InterpGroupInst.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpGroupInst.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpGroupInst.md#executeubergraph)
- [GetClass](ue_ue.InterpGroupInst.md#getclass)
- [GetName](ue_ue.InterpGroupInst.md#getname)
- [GetOuter](ue_ue.InterpGroupInst.md#getouter)
- [GetWorld](ue_ue.InterpGroupInst.md#getworld)
- [Find](ue_ue.InterpGroupInst.md#find)
- [Load](ue_ue.InterpGroupInst.md#load)
- [StaticClass](ue_ue.InterpGroupInst.md#staticclass)

## Constructors

### constructor

• **new InterpGroupInst**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Group

• **Group**: [`InterpGroup`](ue_ue.InterpGroup.md)

___

### GroupActor

• **GroupActor**: [`Actor`](ue_ue.Actor.md)

___

### TrackInst

• **TrackInst**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpTrackInst`](ue_ue.InterpTrackInst.md)\>

___

### \_\_tid\_InterpGroupInst\_\_

• **\_\_tid\_InterpGroupInst\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpGroupInst`](ue_ue.InterpGroupInst.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpGroupInst`](ue_ue.InterpGroupInst.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpGroupInst`](ue_ue.InterpGroupInst.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpGroupInst`](ue_ue.InterpGroupInst.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
