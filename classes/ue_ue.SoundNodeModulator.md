[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundNodeModulator

# Class: SoundNodeModulator

[ue/ue](../modules/ue_ue.md).SoundNodeModulator

## Hierarchy

- [`SoundNode`](ue_ue.SoundNode.md)

  ↳ **`SoundNodeModulator`**

## Table of contents

### Constructors

- [constructor](ue_ue.SoundNodeModulator.md#constructor)

### Properties

- [ChildNodes](ue_ue.SoundNodeModulator.md#childnodes)
- [GraphNode](ue_ue.SoundNodeModulator.md#graphnode)
- [PitchMax](ue_ue.SoundNodeModulator.md#pitchmax)
- [PitchMin](ue_ue.SoundNodeModulator.md#pitchmin)
- [VolumeMax](ue_ue.SoundNodeModulator.md#volumemax)
- [VolumeMin](ue_ue.SoundNodeModulator.md#volumemin)
- [\_\_tid\_Object\_\_](ue_ue.SoundNodeModulator.md#__tid_object__)
- [\_\_tid\_SoundNodeModulator\_\_](ue_ue.SoundNodeModulator.md#__tid_soundnodemodulator__)
- [\_\_tid\_SoundNode\_\_](ue_ue.SoundNodeModulator.md#__tid_soundnode__)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundNodeModulator.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundNodeModulator.md#executeubergraph)
- [GetClass](ue_ue.SoundNodeModulator.md#getclass)
- [GetName](ue_ue.SoundNodeModulator.md#getname)
- [GetOuter](ue_ue.SoundNodeModulator.md#getouter)
- [GetWorld](ue_ue.SoundNodeModulator.md#getworld)
- [Find](ue_ue.SoundNodeModulator.md#find)
- [Load](ue_ue.SoundNodeModulator.md#load)
- [StaticClass](ue_ue.SoundNodeModulator.md#staticclass)

## Constructors

### constructor

• **new SoundNodeModulator**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GraphNode](ue_ue.SoundNode.md#graphnode)

___

### PitchMax

• **PitchMax**: `number`

___

### PitchMin

• **PitchMin**: `number`

___

### VolumeMax

• **VolumeMax**: `number`

___

### VolumeMin

• **VolumeMin**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_Object__](ue_ue.SoundNode.md#__tid_object__)

___

### \_\_tid\_SoundNodeModulator\_\_

• **\_\_tid\_SoundNodeModulator\_\_**: `boolean`

___

### \_\_tid\_SoundNode\_\_

• **\_\_tid\_SoundNode\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_SoundNode__](ue_ue.SoundNode.md#__tid_soundnode__)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundNodeModulator`](ue_ue.SoundNodeModulator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundNodeModulator`](ue_ue.SoundNodeModulator.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[Find](ue_ue.SoundNode.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundNodeModulator`](ue_ue.SoundNodeModulator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundNodeModulator`](ue_ue.SoundNodeModulator.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[Load](ue_ue.SoundNode.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[StaticClass](ue_ue.SoundNode.md#staticclass)
