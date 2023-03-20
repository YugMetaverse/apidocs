[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundNodeDialoguePlayer

# Class: SoundNodeDialoguePlayer

[ue/ue](../modules/ue_ue.md).SoundNodeDialoguePlayer

## Hierarchy

- [`SoundNode`](ue_ue.SoundNode.md)

  ↳ **`SoundNodeDialoguePlayer`**

## Table of contents

### Constructors

- [constructor](ue_ue.SoundNodeDialoguePlayer.md#constructor)

### Properties

- [ChildNodes](ue_ue.SoundNodeDialoguePlayer.md#childnodes)
- [DialogueWaveParameter](ue_ue.SoundNodeDialoguePlayer.md#dialoguewaveparameter)
- [GraphNode](ue_ue.SoundNodeDialoguePlayer.md#graphnode)
- [\_\_tid\_Object\_\_](ue_ue.SoundNodeDialoguePlayer.md#__tid_object__)
- [\_\_tid\_SoundNodeDialoguePlayer\_\_](ue_ue.SoundNodeDialoguePlayer.md#__tid_soundnodedialogueplayer__)
- [\_\_tid\_SoundNode\_\_](ue_ue.SoundNodeDialoguePlayer.md#__tid_soundnode__)
- [bLooping](ue_ue.SoundNodeDialoguePlayer.md#blooping)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundNodeDialoguePlayer.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundNodeDialoguePlayer.md#executeubergraph)
- [GetClass](ue_ue.SoundNodeDialoguePlayer.md#getclass)
- [GetName](ue_ue.SoundNodeDialoguePlayer.md#getname)
- [GetOuter](ue_ue.SoundNodeDialoguePlayer.md#getouter)
- [GetWorld](ue_ue.SoundNodeDialoguePlayer.md#getworld)
- [Find](ue_ue.SoundNodeDialoguePlayer.md#find)
- [Load](ue_ue.SoundNodeDialoguePlayer.md#load)
- [StaticClass](ue_ue.SoundNodeDialoguePlayer.md#staticclass)

## Constructors

### constructor

• **new SoundNodeDialoguePlayer**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[constructor](ue_ue.SoundNode.md#constructor)

#### Defined in

[ue/ue.d.ts:61350](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61350)

## Properties

### ChildNodes

• **ChildNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundNode`](ue_ue.SoundNode.md)\>

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[ChildNodes](ue_ue.SoundNode.md#childnodes)

#### Defined in

[ue/ue.d.ts:22398](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22398)

___

### DialogueWaveParameter

• **DialogueWaveParameter**: [`DialogueWaveParameter`](ue_ue.DialogueWaveParameter.md)

#### Defined in

[ue/ue.d.ts:61351](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61351)

___

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GraphNode](ue_ue.SoundNode.md#graphnode)

#### Defined in

[ue/ue.d.ts:22399](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22399)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_Object__](ue_ue.SoundNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SoundNodeDialoguePlayer\_\_

• **\_\_tid\_SoundNodeDialoguePlayer\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:61357](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61357)

___

### \_\_tid\_SoundNode\_\_

• **\_\_tid\_SoundNode\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_SoundNode__](ue_ue.SoundNode.md#__tid_soundnode__)

#### Defined in

[ue/ue.d.ts:22404](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22404)

___

### bLooping

• **bLooping**: `boolean`

#### Defined in

[ue/ue.d.ts:61352](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61352)

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

[SoundNode](ue_ue.SoundNode.md).[ExecuteUbergraph](ue_ue.SoundNode.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetClass](ue_ue.SoundNode.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetName](ue_ue.SoundNode.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetOuter](ue_ue.SoundNode.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetWorld](ue_ue.SoundNode.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundNodeDialoguePlayer`](ue_ue.SoundNodeDialoguePlayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundNodeDialoguePlayer`](ue_ue.SoundNodeDialoguePlayer.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[Find](ue_ue.SoundNode.md#find)

#### Defined in

[ue/ue.d.ts:61354](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61354)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundNodeDialoguePlayer`](ue_ue.SoundNodeDialoguePlayer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundNodeDialoguePlayer`](ue_ue.SoundNodeDialoguePlayer.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[Load](ue_ue.SoundNode.md#load)

#### Defined in

[ue/ue.d.ts:61355](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61355)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[StaticClass](ue_ue.SoundNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:61353](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61353)
