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

#### Defined in

[ue/ue.d.ts:61399](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61399)

## Properties

### ChildNodes

• **ChildNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundNode`](ue_ue.SoundNode.md)\>

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[ChildNodes](ue_ue.SoundNode.md#childnodes)

#### Defined in

[ue/ue.d.ts:22398](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22398)

___

### DurationAfterLoop

• **DurationAfterLoop**: `number`

#### Defined in

[ue/ue.d.ts:61402](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61402)

___

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GraphNode](ue_ue.SoundNode.md#graphnode)

#### Defined in

[ue/ue.d.ts:22399](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22399)

___

### LoopCount

• **LoopCount**: `number`

#### Defined in

[ue/ue.d.ts:61403](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61403)

___

### LoopEnd

• **LoopEnd**: `number`

#### Defined in

[ue/ue.d.ts:61401](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61401)

___

### LoopStart

• **LoopStart**: `number`

#### Defined in

[ue/ue.d.ts:61400](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61400)

___

### PitchCurve

• **PitchCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

#### Defined in

[ue/ue.d.ts:61409](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61409)

___

### PitchInterpCurve

• **PitchInterpCurve**: [`DistributionFloatConstantCurve`](ue_ue.DistributionFloatConstantCurve.md)

#### Defined in

[ue/ue.d.ts:61407](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61407)

___

### PitchMax

• **PitchMax**: `number`

#### Defined in

[ue/ue.d.ts:61411](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61411)

___

### PitchMin

• **PitchMin**: `number`

#### Defined in

[ue/ue.d.ts:61410](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61410)

___

### VolumeCurve

• **VolumeCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

#### Defined in

[ue/ue.d.ts:61408](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61408)

___

### VolumeInterpCurve

• **VolumeInterpCurve**: [`DistributionFloatConstantCurve`](ue_ue.DistributionFloatConstantCurve.md)

#### Defined in

[ue/ue.d.ts:61406](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61406)

___

### VolumeMax

• **VolumeMax**: `number`

#### Defined in

[ue/ue.d.ts:61413](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61413)

___

### VolumeMin

• **VolumeMin**: `number`

#### Defined in

[ue/ue.d.ts:61412](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61412)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_Object__](ue_ue.SoundNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SoundNodeEnveloper\_\_

• **\_\_tid\_SoundNodeEnveloper\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:61418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61418)

___

### \_\_tid\_SoundNode\_\_

• **\_\_tid\_SoundNode\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_SoundNode__](ue_ue.SoundNode.md#__tid_soundnode__)

#### Defined in

[ue/ue.d.ts:22404](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22404)

___

### bLoop

• **bLoop**: `boolean`

#### Defined in

[ue/ue.d.ts:61405](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61405)

___

### bLoopIndefinitely

• **bLoopIndefinitely**: `boolean`

#### Defined in

[ue/ue.d.ts:61404](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61404)

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

#### Defined in

[ue/ue.d.ts:61415](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61415)

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

#### Defined in

[ue/ue.d.ts:61416](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61416)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[StaticClass](ue_ue.SoundNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:61414](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61414)
