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

#### Defined in

[ue/ue.d.ts:61504](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61504)

## Properties

### AmplitudeMax

• **AmplitudeMax**: `number`

#### Defined in

[ue/ue.d.ts:61508](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61508)

___

### AmplitudeMin

• **AmplitudeMin**: `number`

#### Defined in

[ue/ue.d.ts:61507](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61507)

___

### CenterMax

• **CenterMax**: `number`

#### Defined in

[ue/ue.d.ts:61514](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61514)

___

### CenterMin

• **CenterMin**: `number`

#### Defined in

[ue/ue.d.ts:61513](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61513)

___

### ChildNodes

• **ChildNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundNode`](ue_ue.SoundNode.md)\>

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[ChildNodes](ue_ue.SoundNode.md#childnodes)

#### Defined in

[ue/ue.d.ts:22398](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22398)

___

### FrequencyMax

• **FrequencyMax**: `number`

#### Defined in

[ue/ue.d.ts:61510](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61510)

___

### FrequencyMin

• **FrequencyMin**: `number`

#### Defined in

[ue/ue.d.ts:61509](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61509)

___

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[GraphNode](ue_ue.SoundNode.md#graphnode)

#### Defined in

[ue/ue.d.ts:22399](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22399)

___

### OffsetMax

• **OffsetMax**: `number`

#### Defined in

[ue/ue.d.ts:61512](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61512)

___

### OffsetMin

• **OffsetMin**: `number`

#### Defined in

[ue/ue.d.ts:61511](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61511)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_Object__](ue_ue.SoundNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SoundNodeOscillator\_\_

• **\_\_tid\_SoundNodeOscillator\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:61519](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61519)

___

### \_\_tid\_SoundNode\_\_

• **\_\_tid\_SoundNode\_\_**: `boolean`

#### Inherited from

[SoundNode](ue_ue.SoundNode.md).[__tid_SoundNode__](ue_ue.SoundNode.md#__tid_soundnode__)

#### Defined in

[ue/ue.d.ts:22404](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22404)

___

### bModulatePitch

• **bModulatePitch**: `boolean`

#### Defined in

[ue/ue.d.ts:61506](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61506)

___

### bModulateVolume

• **bModulateVolume**: `boolean`

#### Defined in

[ue/ue.d.ts:61505](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61505)

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

#### Defined in

[ue/ue.d.ts:61516](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61516)

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

#### Defined in

[ue/ue.d.ts:61517](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61517)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundNode](ue_ue.SoundNode.md).[StaticClass](ue_ue.SoundNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:61515](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61515)
