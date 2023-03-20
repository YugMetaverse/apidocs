[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundNodeOscillator

# Class: SoundNodeOscillator

[ue/ue](../modules/ue_ue.md).SoundNodeOscillator

## Hierarchy

- [`SoundNode`](ue_ue.SoundNode.md)

  ↳ **`SoundNodeOscillator`**

## Table of contents

### Constructors

- [constructor](ue_ue.SoundNodeOscillator.md#constructor)

### Properties

- [AmplitudeMax](ue_ue.SoundNodeOscillator.md#amplitudemax)
- [AmplitudeMin](ue_ue.SoundNodeOscillator.md#amplitudemin)
- [CenterMax](ue_ue.SoundNodeOscillator.md#centermax)
- [CenterMin](ue_ue.SoundNodeOscillator.md#centermin)
- [ChildNodes](ue_ue.SoundNodeOscillator.md#childnodes)
- [FrequencyMax](ue_ue.SoundNodeOscillator.md#frequencymax)
- [FrequencyMin](ue_ue.SoundNodeOscillator.md#frequencymin)
- [GraphNode](ue_ue.SoundNodeOscillator.md#graphnode)
- [OffsetMax](ue_ue.SoundNodeOscillator.md#offsetmax)
- [OffsetMin](ue_ue.SoundNodeOscillator.md#offsetmin)
- [\_\_tid\_Object\_\_](ue_ue.SoundNodeOscillator.md#__tid_object__)
- [\_\_tid\_SoundNodeOscillator\_\_](ue_ue.SoundNodeOscillator.md#__tid_soundnodeoscillator__)
- [\_\_tid\_SoundNode\_\_](ue_ue.SoundNodeOscillator.md#__tid_soundnode__)
- [bModulatePitch](ue_ue.SoundNodeOscillator.md#bmodulatepitch)
- [bModulateVolume](ue_ue.SoundNodeOscillator.md#bmodulatevolume)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundNodeOscillator.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundNodeOscillator.md#executeubergraph)
- [GetClass](ue_ue.SoundNodeOscillator.md#getclass)
- [GetName](ue_ue.SoundNodeOscillator.md#getname)
- [GetOuter](ue_ue.SoundNodeOscillator.md#getouter)
- [GetWorld](ue_ue.SoundNodeOscillator.md#getworld)
- [Find](ue_ue.SoundNodeOscillator.md#find)
- [Load](ue_ue.SoundNodeOscillator.md#load)
- [StaticClass](ue_ue.SoundNodeOscillator.md#staticclass)

## Constructors

### constructor

• **new SoundNodeOscillator**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[constructor](ue_ue.SoundNode.md#constructor)

## Properties

### AmplitudeMax

• **AmplitudeMax**: `number`

___

### AmplitudeMin

• **AmplitudeMin**: `number`

___

### CenterMax

• **CenterMax**: `number`

___

### CenterMin

• **CenterMin**: `number`

___

### ChildNodes

• **ChildNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundNode`](ue_ue.SoundNode.md)\>

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[ChildNodes](ue_ue.SoundNode.md#childnodes)

___

### FrequencyMax

• **FrequencyMax**: `number`

___

### FrequencyMin

• **FrequencyMin**: `number`

___

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GraphNode](ue_ue.SoundNode.md#graphnode)

___

### OffsetMax

• **OffsetMax**: `number`

___

### OffsetMin

• **OffsetMin**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_Object__](ue_ue.SoundNode.md#__tid_object__)

___

### \_\_tid\_SoundNodeOscillator\_\_

• **\_\_tid\_SoundNodeOscillator\_\_**: `boolean`

___

### \_\_tid\_SoundNode\_\_

• **\_\_tid\_SoundNode\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_SoundNode__](ue_ue.SoundNode.md#__tid_soundnode__)

___

### bModulatePitch

• **bModulatePitch**: `boolean`

___

### bModulateVolume

• **bModulateVolume**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundNodeOscillator`](ue_ue.SoundNodeOscillator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundNodeOscillator`](ue_ue.SoundNodeOscillator.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[Find](ue_ue.SoundNode.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundNodeOscillator`](ue_ue.SoundNodeOscillator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundNodeOscillator`](ue_ue.SoundNodeOscillator.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[Load](ue_ue.SoundNode.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[StaticClass](ue_ue.SoundNode.md#staticclass)
