[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Layer

# Class: Layer

[ue/ue](../modules/ue_ue.md).Layer

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`Layer`**

## Table of contents

### Constructors

- [constructor](ue_ue.Layer.md#constructor)

### Properties

- [ActorStats](ue_ue.Layer.md#actorstats)
- [LayerName](ue_ue.Layer.md#layername)
- [\_\_tid\_Layer\_\_](ue_ue.Layer.md#__tid_layer__)
- [\_\_tid\_Object\_\_](ue_ue.Layer.md#__tid_object__)
- [bIsVisible](ue_ue.Layer.md#bisvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.Layer.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Layer.md#executeubergraph)
- [GetClass](ue_ue.Layer.md#getclass)
- [GetName](ue_ue.Layer.md#getname)
- [GetOuter](ue_ue.Layer.md#getouter)
- [GetWorld](ue_ue.Layer.md#getworld)
- [Find](ue_ue.Layer.md#find)
- [Load](ue_ue.Layer.md#load)
- [StaticClass](ue_ue.Layer.md#staticclass)

## Constructors

### constructor

• **new Layer**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:8511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8511)

## Properties

### ActorStats

• **ActorStats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LayerActorStats`](ue_ue.LayerActorStats.md)\>

#### Defined in

[ue/ue.d.ts:8514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8514)

___

### LayerName

• **LayerName**: `string`

#### Defined in

[ue/ue.d.ts:8512](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8512)

___

### \_\_tid\_Layer\_\_

• **\_\_tid\_Layer\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:8519](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8519)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bIsVisible

• **bIsVisible**: `boolean`

#### Defined in

[ue/ue.d.ts:8513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8513)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Layer`](ue_ue.Layer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Layer`](ue_ue.Layer.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:8516](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8516)

___

### Load

▸ `Static` **Load**(`InName`): [`Layer`](ue_ue.Layer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Layer`](ue_ue.Layer.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:8517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8517)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:8515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8515)
