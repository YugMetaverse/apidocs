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

## Properties

### ChildNodes

• **ChildNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundNode`](ue_ue.SoundNode.md)\>

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[ChildNodes](ue_ue.SoundNode.md#childnodes)

___

### DialogueWaveParameter

• **DialogueWaveParameter**: [`DialogueWaveParameter`](ue_ue.DialogueWaveParameter.md)

___

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GraphNode](ue_ue.SoundNode.md#graphnode)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_Object__](ue_ue.SoundNode.md#__tid_object__)

___

### \_\_tid\_SoundNodeDialoguePlayer\_\_

• **\_\_tid\_SoundNodeDialoguePlayer\_\_**: `boolean`

___

### \_\_tid\_SoundNode\_\_

• **\_\_tid\_SoundNode\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_SoundNode__](ue_ue.SoundNode.md#__tid_soundnode__)

___

### bLooping

• **bLooping**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetClass](ue_ue.SoundNode.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetName](ue_ue.SoundNode.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetOuter](ue_ue.SoundNode.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GetWorld](ue_ue.SoundNode.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[StaticClass](ue_ue.SoundNode.md#staticclass)
