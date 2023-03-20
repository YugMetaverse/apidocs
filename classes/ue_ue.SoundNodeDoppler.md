[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundNodeDoppler

# Class: SoundNodeDoppler

[ue/ue](../modules/ue_ue.md).SoundNodeDoppler

## Hierarchy

- [`SoundNode`](ue_ue.SoundNode.md)

  ↳ **`SoundNodeDoppler`**

## Table of contents

### Constructors

- [constructor](ue_ue.SoundNodeDoppler.md#constructor)

### Properties

- [ChildNodes](ue_ue.SoundNodeDoppler.md#childnodes)
- [DopplerIntensity](ue_ue.SoundNodeDoppler.md#dopplerintensity)
- [GraphNode](ue_ue.SoundNodeDoppler.md#graphnode)
- [SmoothingInterpSpeed](ue_ue.SoundNodeDoppler.md#smoothinginterpspeed)
- [\_\_tid\_Object\_\_](ue_ue.SoundNodeDoppler.md#__tid_object__)
- [\_\_tid\_SoundNodeDoppler\_\_](ue_ue.SoundNodeDoppler.md#__tid_soundnodedoppler__)
- [\_\_tid\_SoundNode\_\_](ue_ue.SoundNodeDoppler.md#__tid_soundnode__)
- [bUseSmoothing](ue_ue.SoundNodeDoppler.md#busesmoothing)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundNodeDoppler.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundNodeDoppler.md#executeubergraph)
- [GetClass](ue_ue.SoundNodeDoppler.md#getclass)
- [GetName](ue_ue.SoundNodeDoppler.md#getname)
- [GetOuter](ue_ue.SoundNodeDoppler.md#getouter)
- [GetWorld](ue_ue.SoundNodeDoppler.md#getworld)
- [Find](ue_ue.SoundNodeDoppler.md#find)
- [Load](ue_ue.SoundNodeDoppler.md#load)
- [StaticClass](ue_ue.SoundNodeDoppler.md#staticclass)

## Constructors

### constructor

• **new SoundNodeDoppler**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[constructor](ue_ue.SoundNode.md#constructor)

#### Defined in

[ue/ue.d.ts:61387](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61387)

## Properties

### ChildNodes

• **ChildNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundNode`](ue_ue.SoundNode.md)\>

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[ChildNodes](ue_ue.SoundNode.md#childnodes)

#### Defined in

[ue/ue.d.ts:22398](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22398)

___

### DopplerIntensity

• **DopplerIntensity**: `number`

#### Defined in

[ue/ue.d.ts:61388](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61388)

___

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GraphNode](ue_ue.SoundNode.md#graphnode)

#### Defined in

[ue/ue.d.ts:22399](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22399)

___

### SmoothingInterpSpeed

• **SmoothingInterpSpeed**: `number`

#### Defined in

[ue/ue.d.ts:61390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61390)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_Object__](ue_ue.SoundNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_SoundNodeDoppler\_\_

• **\_\_tid\_SoundNodeDoppler\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:61395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61395)

___

### \_\_tid\_SoundNode\_\_

• **\_\_tid\_SoundNode\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_SoundNode__](ue_ue.SoundNode.md#__tid_soundnode__)

#### Defined in

[ue/ue.d.ts:22404](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22404)

___

### bUseSmoothing

• **bUseSmoothing**: `boolean`

#### Defined in

[ue/ue.d.ts:61389](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61389)

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

[SoundNode](ue_ue.SoundNode.md).[CreateDefaultSubobject](ue_ue.SoundNode.md#createdefaultsubobject)

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

[SoundNode](ue_ue.SoundNode.md).[ExecuteUbergraph](ue_ue.SoundNode.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetClass](ue_ue.SoundNode.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetName](ue_ue.SoundNode.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetOuter](ue_ue.SoundNode.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetWorld](ue_ue.SoundNode.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundNodeDoppler`](ue_ue.SoundNodeDoppler.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundNodeDoppler`](ue_ue.SoundNodeDoppler.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[Find](ue_ue.SoundNode.md#find)

#### Defined in

[ue/ue.d.ts:61392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61392)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundNodeDoppler`](ue_ue.SoundNodeDoppler.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundNodeDoppler`](ue_ue.SoundNodeDoppler.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[Load](ue_ue.SoundNode.md#load)

#### Defined in

[ue/ue.d.ts:61393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61393)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[StaticClass](ue_ue.SoundNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:61391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L61391)
