[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ReverbEffect

# Class: ReverbEffect

[ue/ue](../modules/ue_ue.md).ReverbEffect

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ReverbEffect`**

## Table of contents

### Constructors

- [constructor](ue_ue.ReverbEffect.md#constructor)

### Properties

- [AirAbsorptionGainHF](ue_ue.ReverbEffect.md#airabsorptiongainhf)
- [DecayHFRatio](ue_ue.ReverbEffect.md#decayhfratio)
- [DecayTime](ue_ue.ReverbEffect.md#decaytime)
- [Density](ue_ue.ReverbEffect.md#density)
- [Diffusion](ue_ue.ReverbEffect.md#diffusion)
- [Gain](ue_ue.ReverbEffect.md#gain)
- [GainHF](ue_ue.ReverbEffect.md#gainhf)
- [LateDelay](ue_ue.ReverbEffect.md#latedelay)
- [LateGain](ue_ue.ReverbEffect.md#lategain)
- [ReflectionsDelay](ue_ue.ReverbEffect.md#reflectionsdelay)
- [ReflectionsGain](ue_ue.ReverbEffect.md#reflectionsgain)
- [RoomRolloffFactor](ue_ue.ReverbEffect.md#roomrollofffactor)
- [\_\_tid\_Object\_\_](ue_ue.ReverbEffect.md#__tid_object__)
- [\_\_tid\_ReverbEffect\_\_](ue_ue.ReverbEffect.md#__tid_reverbeffect__)
- [bChanged](ue_ue.ReverbEffect.md#bchanged)

### Methods

- [CreateDefaultSubobject](ue_ue.ReverbEffect.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ReverbEffect.md#executeubergraph)
- [GetClass](ue_ue.ReverbEffect.md#getclass)
- [GetName](ue_ue.ReverbEffect.md#getname)
- [GetOuter](ue_ue.ReverbEffect.md#getouter)
- [GetWorld](ue_ue.ReverbEffect.md#getworld)
- [Find](ue_ue.ReverbEffect.md#find)
- [Load](ue_ue.ReverbEffect.md#load)
- [StaticClass](ue_ue.ReverbEffect.md#staticclass)

## Constructors

### constructor

• **new ReverbEffect**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AirAbsorptionGainHF

• **AirAbsorptionGainHF**: `number`

___

### DecayHFRatio

• **DecayHFRatio**: `number`

___

### DecayTime

• **DecayTime**: `number`

___

### Density

• **Density**: `number`

___

### Diffusion

• **Diffusion**: `number`

___

### Gain

• **Gain**: `number`

___

### GainHF

• **GainHF**: `number`

___

### LateDelay

• **LateDelay**: `number`

___

### LateGain

• **LateGain**: `number`

___

### ReflectionsDelay

• **ReflectionsDelay**: `number`

___

### ReflectionsGain

• **ReflectionsGain**: `number`

___

### RoomRolloffFactor

• **RoomRolloffFactor**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_ReverbEffect\_\_

• **\_\_tid\_ReverbEffect\_\_**: `boolean`

___

### bChanged

• **bChanged**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ReverbEffect`](ue_ue.ReverbEffect.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ReverbEffect`](ue_ue.ReverbEffect.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ReverbEffect`](ue_ue.ReverbEffect.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ReverbEffect`](ue_ue.ReverbEffect.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
