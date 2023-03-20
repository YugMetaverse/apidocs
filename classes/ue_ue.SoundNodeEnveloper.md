[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundNodeEnveloper

# Class: SoundNodeEnveloper

[ue/ue](../modules/ue_ue.md).SoundNodeEnveloper

## Hierarchy

- [`SoundNode`](ue_ue.SoundNode.md)

  ↳ **`SoundNodeEnveloper`**

## Table of contents

### Constructors

- [constructor](ue_ue.SoundNodeEnveloper.md#constructor)

### Properties

- [ChildNodes](ue_ue.SoundNodeEnveloper.md#childnodes)
- [DurationAfterLoop](ue_ue.SoundNodeEnveloper.md#durationafterloop)
- [GraphNode](ue_ue.SoundNodeEnveloper.md#graphnode)
- [LoopCount](ue_ue.SoundNodeEnveloper.md#loopcount)
- [LoopEnd](ue_ue.SoundNodeEnveloper.md#loopend)
- [LoopStart](ue_ue.SoundNodeEnveloper.md#loopstart)
- [PitchCurve](ue_ue.SoundNodeEnveloper.md#pitchcurve)
- [PitchInterpCurve](ue_ue.SoundNodeEnveloper.md#pitchinterpcurve)
- [PitchMax](ue_ue.SoundNodeEnveloper.md#pitchmax)
- [PitchMin](ue_ue.SoundNodeEnveloper.md#pitchmin)
- [VolumeCurve](ue_ue.SoundNodeEnveloper.md#volumecurve)
- [VolumeInterpCurve](ue_ue.SoundNodeEnveloper.md#volumeinterpcurve)
- [VolumeMax](ue_ue.SoundNodeEnveloper.md#volumemax)
- [VolumeMin](ue_ue.SoundNodeEnveloper.md#volumemin)
- [\_\_tid\_Object\_\_](ue_ue.SoundNodeEnveloper.md#__tid_object__)
- [\_\_tid\_SoundNodeEnveloper\_\_](ue_ue.SoundNodeEnveloper.md#__tid_soundnodeenveloper__)
- [\_\_tid\_SoundNode\_\_](ue_ue.SoundNodeEnveloper.md#__tid_soundnode__)
- [bLoop](ue_ue.SoundNodeEnveloper.md#bloop)
- [bLoopIndefinitely](ue_ue.SoundNodeEnveloper.md#bloopindefinitely)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundNodeEnveloper.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundNodeEnveloper.md#executeubergraph)
- [GetClass](ue_ue.SoundNodeEnveloper.md#getclass)
- [GetName](ue_ue.SoundNodeEnveloper.md#getname)
- [GetOuter](ue_ue.SoundNodeEnveloper.md#getouter)
- [GetWorld](ue_ue.SoundNodeEnveloper.md#getworld)
- [Find](ue_ue.SoundNodeEnveloper.md#find)
- [Load](ue_ue.SoundNodeEnveloper.md#load)
- [StaticClass](ue_ue.SoundNodeEnveloper.md#staticclass)

## Constructors

### constructor

• **new SoundNodeEnveloper**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### DurationAfterLoop

• **DurationAfterLoop**: `number`

___

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GraphNode](ue_ue.SoundNode.md#graphnode)

___

### LoopCount

• **LoopCount**: `number`

___

### LoopEnd

• **LoopEnd**: `number`

___

### LoopStart

• **LoopStart**: `number`

___

### PitchCurve

• **PitchCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

___

### PitchInterpCurve

• **PitchInterpCurve**: [`DistributionFloatConstantCurve`](ue_ue.DistributionFloatConstantCurve.md)

___

### PitchMax

• **PitchMax**: `number`

___

### PitchMin

• **PitchMin**: `number`

___

### VolumeCurve

• **VolumeCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

___

### VolumeInterpCurve

• **VolumeInterpCurve**: [`DistributionFloatConstantCurve`](ue_ue.DistributionFloatConstantCurve.md)

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

### \_\_tid\_SoundNodeEnveloper\_\_

• **\_\_tid\_SoundNodeEnveloper\_\_**: `boolean`

___

### \_\_tid\_SoundNode\_\_

• **\_\_tid\_SoundNode\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_SoundNode__](ue_ue.SoundNode.md#__tid_soundnode__)

___

### bLoop

• **bLoop**: `boolean`

___

### bLoopIndefinitely

• **bLoopIndefinitely**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundNodeEnveloper`](ue_ue.SoundNodeEnveloper.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundNodeEnveloper`](ue_ue.SoundNodeEnveloper.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[Find](ue_ue.SoundNode.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundNodeEnveloper`](ue_ue.SoundNodeEnveloper.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundNodeEnveloper`](ue_ue.SoundNodeEnveloper.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[Load](ue_ue.SoundNode.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[StaticClass](ue_ue.SoundNode.md#staticclass)
