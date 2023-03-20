[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EdGraphSchema

# Class: EdGraphSchema

[ue/ue](../modules/ue_ue.md).EdGraphSchema

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`EdGraphSchema`**

  ↳↳ [`AIGraphSchema`](ue_ue.AIGraphSchema.md)

  ↳↳ [`EdGraphSchema_K2`](ue_ue.EdGraphSchema_K2.md)

  ↳↳ [`AnimationStateMachineSchema`](ue_ue.AnimationStateMachineSchema.md)

  ↳↳ [`EdGraphSchema_BehaviorTreeDecorator`](ue_ue.EdGraphSchema_BehaviorTreeDecorator.md)

  ↳↳ [`MaterialGraphSchema`](ue_ue.MaterialGraphSchema.md)

  ↳↳ [`ReferenceViewerSchema`](ue_ue.ReferenceViewerSchema.md)

  ↳↳ [`SoundClassGraphSchema`](ue_ue.SoundClassGraphSchema.md)

  ↳↳ [`SoundCueGraphSchema`](ue_ue.SoundCueGraphSchema.md)

  ↳↳ [`SoundSubmixGraphSchema`](ue_ue.SoundSubmixGraphSchema.md)

## Table of contents

### Constructors

- [constructor](ue_ue.EdGraphSchema.md#constructor)

### Properties

- [\_\_tid\_EdGraphSchema\_\_](ue_ue.EdGraphSchema.md#__tid_edgraphschema__)
- [\_\_tid\_Object\_\_](ue_ue.EdGraphSchema.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EdGraphSchema.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EdGraphSchema.md#executeubergraph)
- [GetClass](ue_ue.EdGraphSchema.md#getclass)
- [GetName](ue_ue.EdGraphSchema.md#getname)
- [GetOuter](ue_ue.EdGraphSchema.md#getouter)
- [GetWorld](ue_ue.EdGraphSchema.md#getworld)
- [Find](ue_ue.EdGraphSchema.md#find)
- [Load](ue_ue.EdGraphSchema.md#load)
- [StaticClass](ue_ue.EdGraphSchema.md#staticclass)

## Constructors

### constructor

• **new EdGraphSchema**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:15133](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15133)

## Properties

### \_\_tid\_EdGraphSchema\_\_

• **\_\_tid\_EdGraphSchema\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15138)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EdGraphSchema`](ue_ue.EdGraphSchema.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EdGraphSchema`](ue_ue.EdGraphSchema.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:15135](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15135)

___

### Load

▸ `Static` **Load**(`InName`): [`EdGraphSchema`](ue_ue.EdGraphSchema.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EdGraphSchema`](ue_ue.EdGraphSchema.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:15136](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15136)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:15134](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15134)
