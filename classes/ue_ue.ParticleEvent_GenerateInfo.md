[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleEvent\_GenerateInfo

# Class: ParticleEvent\_GenerateInfo

[ue/ue](../modules/ue_ue.md).ParticleEvent_GenerateInfo

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleEvent_GenerateInfo.md#constructor)

### Properties

- [CustomName](ue_ue.ParticleEvent_GenerateInfo.md#customname)
- [FirstTimeOnly](ue_ue.ParticleEvent_GenerateInfo.md#firsttimeonly)
- [Frequency](ue_ue.ParticleEvent_GenerateInfo.md#frequency)
- [LastTimeOnly](ue_ue.ParticleEvent_GenerateInfo.md#lasttimeonly)
- [ParticleFrequency](ue_ue.ParticleEvent_GenerateInfo.md#particlefrequency)
- [ParticleModuleEventsToSendToGame](ue_ue.ParticleEvent_GenerateInfo.md#particlemoduleeventstosendtogame)
- [Type](ue_ue.ParticleEvent_GenerateInfo.md#type)
- [UseReflectedImpactVector](ue_ue.ParticleEvent_GenerateInfo.md#usereflectedimpactvector)
- [\_\_tid\_ParticleEvent\_GenerateInfo\_\_](ue_ue.ParticleEvent_GenerateInfo.md#__tid_particleevent_generateinfo__)
- [bUseOrbitOffset](ue_ue.ParticleEvent_GenerateInfo.md#buseorbitoffset)

### Methods

- [StaticClass](ue_ue.ParticleEvent_GenerateInfo.md#staticclass)
- [StaticStruct](ue_ue.ParticleEvent_GenerateInfo.md#staticstruct)

## Constructors

### constructor

• **new ParticleEvent_GenerateInfo**()

• **new ParticleEvent_GenerateInfo**(`Type`, `Frequency`, `ParticleFrequency`, `FirstTimeOnly`, `LastTimeOnly`, `UseReflectedImpactVector`, `bUseOrbitOffset`, `CustomName`, `ParticleModuleEventsToSendToGame`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Type` | [`EParticleEventType`](../enums/ue_ue.EParticleEventType.md) |
| `Frequency` | `number` |
| `ParticleFrequency` | `number` |
| `FirstTimeOnly` | `boolean` |
| `LastTimeOnly` | `boolean` |
| `UseReflectedImpactVector` | `boolean` |
| `bUseOrbitOffset` | `boolean` |
| `CustomName` | `string` |
| `ParticleModuleEventsToSendToGame` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleModuleEventSendToGame`](ue_ue.ParticleModuleEventSendToGame.md)\> |

## Properties

### CustomName

• **CustomName**: `string`

___

### FirstTimeOnly

• **FirstTimeOnly**: `boolean`

___

### Frequency

• **Frequency**: `number`

___

### LastTimeOnly

• **LastTimeOnly**: `boolean`

___

### ParticleFrequency

• **ParticleFrequency**: `number`

___

### ParticleModuleEventsToSendToGame

• **ParticleModuleEventsToSendToGame**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleModuleEventSendToGame`](ue_ue.ParticleModuleEventSendToGame.md)\>

___

### Type

• **Type**: [`EParticleEventType`](../enums/ue_ue.EParticleEventType.md)

___

### UseReflectedImpactVector

• **UseReflectedImpactVector**: `boolean`

___

### \_\_tid\_ParticleEvent\_GenerateInfo\_\_

• `Private` **\_\_tid\_ParticleEvent\_GenerateInfo\_\_**: `boolean`

___

### bUseOrbitOffset

• **bUseOrbitOffset**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
