[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ReverbSettings

# Class: ReverbSettings

[ue/ue](../modules/ue_ue.md).ReverbSettings

## Table of contents

### Constructors

- [constructor](ue_ue.ReverbSettings.md#constructor)

### Properties

- [FadeTime](ue_ue.ReverbSettings.md#fadetime)
- [ReverbEffect](ue_ue.ReverbSettings.md#reverbeffect)
- [ReverbPluginEffect](ue_ue.ReverbSettings.md#reverbplugineffect)
- [ReverbType](ue_ue.ReverbSettings.md#reverbtype)
- [Volume](ue_ue.ReverbSettings.md#volume)
- [\_\_tid\_ReverbSettings\_\_](ue_ue.ReverbSettings.md#__tid_reverbsettings__)
- [bApplyReverb](ue_ue.ReverbSettings.md#bapplyreverb)

### Methods

- [StaticClass](ue_ue.ReverbSettings.md#staticclass)
- [StaticStruct](ue_ue.ReverbSettings.md#staticstruct)

## Constructors

### constructor

• **new ReverbSettings**()

• **new ReverbSettings**(`bApplyReverb`, `ReverbType`, `ReverbEffect`, `ReverbPluginEffect`, `Volume`, `FadeTime`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `bApplyReverb` | `boolean` |
| `ReverbType` | [`ReverbPreset`](../enums/ue_ue.ReverbPreset.md) |
| `ReverbEffect` | [`ReverbEffect`](ue_ue.ReverbEffect.md) |
| `ReverbPluginEffect` | [`SoundEffectSubmixPreset`](ue_ue.SoundEffectSubmixPreset.md) |
| `Volume` | `number` |
| `FadeTime` | `number` |

## Properties

### FadeTime

• **FadeTime**: `number`

___

### ReverbEffect

• **ReverbEffect**: [`ReverbEffect`](ue_ue.ReverbEffect.md)

___

### ReverbPluginEffect

• **ReverbPluginEffect**: [`SoundEffectSubmixPreset`](ue_ue.SoundEffectSubmixPreset.md)

___

### ReverbType

• **ReverbType**: [`ReverbPreset`](../enums/ue_ue.ReverbPreset.md)

___

### Volume

• **Volume**: `number`

___

### \_\_tid\_ReverbSettings\_\_

• `Private` **\_\_tid\_ReverbSettings\_\_**: `boolean`

___

### bApplyReverb

• **bApplyReverb**: `boolean`

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
