[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundNodeWavePlayer

# Class: SoundNodeWavePlayer

[ue/ue](../modules/ue_ue.md).SoundNodeWavePlayer

## Hierarchy

- [`SoundNodeAssetReferencer`](ue_ue.SoundNodeAssetReferencer.md)

  ↳ **`SoundNodeWavePlayer`**

## Table of contents

### Constructors

- [constructor](ue_ue.SoundNodeWavePlayer.md#constructor)

### Properties

- [ChildNodes](ue_ue.SoundNodeWavePlayer.md#childnodes)
- [GraphNode](ue_ue.SoundNodeWavePlayer.md#graphnode)
- [SoundWave](ue_ue.SoundNodeWavePlayer.md#soundwave)
- [SoundWaveAssetPtr](ue_ue.SoundNodeWavePlayer.md#soundwaveassetptr)
- [\_\_tid\_Object\_\_](ue_ue.SoundNodeWavePlayer.md#__tid_object__)
- [\_\_tid\_SoundNodeAssetReferencer\_\_](ue_ue.SoundNodeWavePlayer.md#__tid_soundnodeassetreferencer__)
- [\_\_tid\_SoundNodeWavePlayer\_\_](ue_ue.SoundNodeWavePlayer.md#__tid_soundnodewaveplayer__)
- [\_\_tid\_SoundNode\_\_](ue_ue.SoundNodeWavePlayer.md#__tid_soundnode__)
- [bLooping](ue_ue.SoundNodeWavePlayer.md#blooping)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundNodeWavePlayer.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundNodeWavePlayer.md#executeubergraph)
- [GetClass](ue_ue.SoundNodeWavePlayer.md#getclass)
- [GetName](ue_ue.SoundNodeWavePlayer.md#getname)
- [GetOuter](ue_ue.SoundNodeWavePlayer.md#getouter)
- [GetWorld](ue_ue.SoundNodeWavePlayer.md#getworld)
- [Find](ue_ue.SoundNodeWavePlayer.md#find)
- [Load](ue_ue.SoundNodeWavePlayer.md#load)
- [StaticClass](ue_ue.SoundNodeWavePlayer.md#staticclass)

## Constructors

### constructor

• **new SoundNodeWavePlayer**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoundNodeAssetReferencer](ue_ue.SoundNodeAssetReferencer.md).[constructor](ue_ue.SoundNodeAssetReferencer.md#constructor)

#### Defined in

[ue/ue.d.ts:61589](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61589)

## Properties

### ChildNodes

• **ChildNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundNode`](ue_ue.SoundNode.md)\>

#### Inherited from

[SoundNodeAssetReferencer](ue_ue.SoundNodeAssetReferencer.md).[ChildNodes](ue_ue.SoundNodeAssetReferencer.md#childnodes)

#### Defined in

[ue/ue.d.ts:22398](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22398)

___

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Inherited from

[SoundNodeAssetReferencer](ue_ue.SoundNodeAssetReferencer.md).[GraphNode](ue_ue.SoundNodeAssetReferencer.md#graphnode)

#### Defined in

[ue/ue.d.ts:22399](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22399)

___

### SoundWave

• **SoundWave**: [`SoundWave`](ue_ue.SoundWave.md)

#### Defined in

[ue/ue.d.ts:61591](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61591)

___

### SoundWaveAssetPtr

• **SoundWaveAssetPtr**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`SoundWave`](ue_ue.SoundWave.md)\>

#### Defined in

[ue/ue.d.ts:61590](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61590)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundNodeAssetReferencer](ue_ue.SoundNodeAssetReferencer.md).[__tid_Object__](ue_ue.SoundNodeAssetReferencer.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SoundNodeAssetReferencer\_\_

• **\_\_tid\_SoundNodeAssetReferencer\_\_**: `boolean`

#### Inherited from

[SoundNodeAssetReferencer](ue_ue.SoundNodeAssetReferencer.md).[__tid_SoundNodeAssetReferencer__](ue_ue.SoundNodeAssetReferencer.md#__tid_soundnodeassetreferencer__)

#### Defined in

[ue/ue.d.ts:61290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61290)

___

### \_\_tid\_SoundNodeWavePlayer\_\_

• **\_\_tid\_SoundNodeWavePlayer\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:61597](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61597)

___

### \_\_tid\_SoundNode\_\_

• **\_\_tid\_SoundNode\_\_**: `boolean`

#### Inherited from

[SoundNodeAssetReferencer](ue_ue.SoundNodeAssetReferencer.md).[__tid_SoundNode__](ue_ue.SoundNodeAssetReferencer.md#__tid_soundnode__)

#### Defined in

[ue/ue.d.ts:22404](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22404)

___

### bLooping

• **bLooping**: `boolean`

#### Defined in

[ue/ue.d.ts:61592](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61592)

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

[SoundNodeAssetReferencer](ue_ue.SoundNodeAssetReferencer.md).[CreateDefaultSubobject](ue_ue.SoundNodeAssetReferencer.md#createdefaultsubobject)

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

[SoundNodeAssetReferencer](ue_ue.SoundNodeAssetReferencer.md).[ExecuteUbergraph](ue_ue.SoundNodeAssetReferencer.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundNodeAssetReferencer](ue_ue.SoundNodeAssetReferencer.md).[GetClass](ue_ue.SoundNodeAssetReferencer.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundNodeAssetReferencer](ue_ue.SoundNodeAssetReferencer.md).[GetName](ue_ue.SoundNodeAssetReferencer.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundNodeAssetReferencer](ue_ue.SoundNodeAssetReferencer.md).[GetOuter](ue_ue.SoundNodeAssetReferencer.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundNodeAssetReferencer](ue_ue.SoundNodeAssetReferencer.md).[GetWorld](ue_ue.SoundNodeAssetReferencer.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundNodeWavePlayer`](ue_ue.SoundNodeWavePlayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundNodeWavePlayer`](ue_ue.SoundNodeWavePlayer.md)

#### Overrides

[SoundNodeAssetReferencer](ue_ue.SoundNodeAssetReferencer.md).[Find](ue_ue.SoundNodeAssetReferencer.md#find)

#### Defined in

[ue/ue.d.ts:61594](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61594)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundNodeWavePlayer`](ue_ue.SoundNodeWavePlayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundNodeWavePlayer`](ue_ue.SoundNodeWavePlayer.md)

#### Overrides

[SoundNodeAssetReferencer](ue_ue.SoundNodeAssetReferencer.md).[Load](ue_ue.SoundNodeAssetReferencer.md#load)

#### Defined in

[ue/ue.d.ts:61595](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61595)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundNodeAssetReferencer](ue_ue.SoundNodeAssetReferencer.md).[StaticClass](ue_ue.SoundNodeAssetReferencer.md#staticclass)

#### Defined in

[ue/ue.d.ts:61593](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61593)