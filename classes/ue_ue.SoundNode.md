[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundNode

# Class: SoundNode

[ue/ue](../modules/ue_ue.md).SoundNode

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SoundNode`**

  ↳↳ [`SoundNodeAssetReferencer`](ue_ue.SoundNodeAssetReferencer.md)

  ↳↳ [`SoundNodeAttenuation`](ue_ue.SoundNodeAttenuation.md)

  ↳↳ [`SoundNodeBranch`](ue_ue.SoundNodeBranch.md)

  ↳↳ [`SoundNodeConcatenator`](ue_ue.SoundNodeConcatenator.md)

  ↳↳ [`SoundNodeDelay`](ue_ue.SoundNodeDelay.md)

  ↳↳ [`SoundNodeDialoguePlayer`](ue_ue.SoundNodeDialoguePlayer.md)

  ↳↳ [`SoundNodeDistanceCrossFade`](ue_ue.SoundNodeDistanceCrossFade.md)

  ↳↳ [`SoundNodeDoppler`](ue_ue.SoundNodeDoppler.md)

  ↳↳ [`SoundNodeEnveloper`](ue_ue.SoundNodeEnveloper.md)

  ↳↳ [`SoundNodeGroupControl`](ue_ue.SoundNodeGroupControl.md)

  ↳↳ [`SoundNodeLooping`](ue_ue.SoundNodeLooping.md)

  ↳↳ [`SoundNodeMature`](ue_ue.SoundNodeMature.md)

  ↳↳ [`SoundNodeMixer`](ue_ue.SoundNodeMixer.md)

  ↳↳ [`SoundNodeModulator`](ue_ue.SoundNodeModulator.md)

  ↳↳ [`SoundNodeModulatorContinuous`](ue_ue.SoundNodeModulatorContinuous.md)

  ↳↳ [`SoundNodeOscillator`](ue_ue.SoundNodeOscillator.md)

  ↳↳ [`SoundNodeQualityLevel`](ue_ue.SoundNodeQualityLevel.md)

  ↳↳ [`SoundNodeRandom`](ue_ue.SoundNodeRandom.md)

  ↳↳ [`SoundNodeSoundClass`](ue_ue.SoundNodeSoundClass.md)

  ↳↳ [`SoundNodeSwitch`](ue_ue.SoundNodeSwitch.md)

  ↳↳ [`SoundNodeWaveParam`](ue_ue.SoundNodeWaveParam.md)

## Table of contents

### Constructors

- [constructor](ue_ue.SoundNode.md#constructor)

### Properties

- [ChildNodes](ue_ue.SoundNode.md#childnodes)
- [GraphNode](ue_ue.SoundNode.md#graphnode)
- [\_\_tid\_Object\_\_](ue_ue.SoundNode.md#__tid_object__)
- [\_\_tid\_SoundNode\_\_](ue_ue.SoundNode.md#__tid_soundnode__)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundNode.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundNode.md#executeubergraph)
- [GetClass](ue_ue.SoundNode.md#getclass)
- [GetName](ue_ue.SoundNode.md#getname)
- [GetOuter](ue_ue.SoundNode.md#getouter)
- [GetWorld](ue_ue.SoundNode.md#getworld)
- [Find](ue_ue.SoundNode.md#find)
- [Load](ue_ue.SoundNode.md#load)
- [StaticClass](ue_ue.SoundNode.md#staticclass)

## Constructors

### constructor

• **new SoundNode**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:22397](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22397)

## Properties

### ChildNodes

• **ChildNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundNode`](ue_ue.SoundNode.md)\>

#### Defined in

[ue/ue.d.ts:22398](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22398)

___

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Defined in

[ue/ue.d.ts:22399](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22399)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SoundNode\_\_

• **\_\_tid\_SoundNode\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:22404](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22404)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundNode`](ue_ue.SoundNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundNode`](ue_ue.SoundNode.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:22401](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22401)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundNode`](ue_ue.SoundNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundNode`](ue_ue.SoundNode.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:22402](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22402)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:22400](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22400)
