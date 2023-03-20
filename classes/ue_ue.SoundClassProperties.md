[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundClassProperties

# Class: SoundClassProperties

[ue/ue](../modules/ue_ue.md).SoundClassProperties

## Table of contents

### Constructors

- [constructor](ue_ue.SoundClassProperties.md#constructor)

### Properties

- [Default2DReverbSendAmount](ue_ue.SoundClassProperties.md#default2dreverbsendamount)
- [LFEBleed](ue_ue.SoundClassProperties.md#lfebleed)
- [LoadingBehavior](ue_ue.SoundClassProperties.md#loadingbehavior)
- [LowPassFilterFrequency](ue_ue.SoundClassProperties.md#lowpassfilterfrequency)
- [OutputTarget](ue_ue.SoundClassProperties.md#outputtarget)
- [Pitch](ue_ue.SoundClassProperties.md#pitch)
- [RadioFilterVolume](ue_ue.SoundClassProperties.md#radiofiltervolume)
- [RadioFilterVolumeThreshold](ue_ue.SoundClassProperties.md#radiofiltervolumethreshold)
- [StereoBleed](ue_ue.SoundClassProperties.md#stereobleed)
- [VoiceCenterChannelVolume](ue_ue.SoundClassProperties.md#voicecenterchannelvolume)
- [Volume](ue_ue.SoundClassProperties.md#volume)
- [\_\_tid\_SoundClassProperties\_\_](ue_ue.SoundClassProperties.md#__tid_soundclassproperties__)
- [bAlwaysPlay](ue_ue.SoundClassProperties.md#balwaysplay)
- [bApplyAmbientVolumes](ue_ue.SoundClassProperties.md#bapplyambientvolumes)
- [bApplyEffects](ue_ue.SoundClassProperties.md#bapplyeffects)
- [bCenterChannelOnly](ue_ue.SoundClassProperties.md#bcenterchannelonly)
- [bIsMusic](ue_ue.SoundClassProperties.md#bismusic)
- [bIsUISound](ue_ue.SoundClassProperties.md#bisuisound)
- [bReverb](ue_ue.SoundClassProperties.md#breverb)

### Methods

- [StaticClass](ue_ue.SoundClassProperties.md#staticclass)
- [StaticStruct](ue_ue.SoundClassProperties.md#staticstruct)

## Constructors

### constructor

• **new SoundClassProperties**()

• **new SoundClassProperties**(`Volume`, `Pitch`, `LowPassFilterFrequency`, `StereoBleed`, `LFEBleed`, `VoiceCenterChannelVolume`, `RadioFilterVolume`, `RadioFilterVolumeThreshold`, `bApplyEffects`, `bAlwaysPlay`, `bIsUISound`, `bIsMusic`, `bReverb`, `Default2DReverbSendAmount`, `bCenterChannelOnly`, `bApplyAmbientVolumes`, `OutputTarget`, `LoadingBehavior`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Volume` | `number` |
| `Pitch` | `number` |
| `LowPassFilterFrequency` | `number` |
| `StereoBleed` | `number` |
| `LFEBleed` | `number` |
| `VoiceCenterChannelVolume` | `number` |
| `RadioFilterVolume` | `number` |
| `RadioFilterVolumeThreshold` | `number` |
| `bApplyEffects` | `boolean` |
| `bAlwaysPlay` | `boolean` |
| `bIsUISound` | `boolean` |
| `bIsMusic` | `boolean` |
| `bReverb` | `boolean` |
| `Default2DReverbSendAmount` | `number` |
| `bCenterChannelOnly` | `boolean` |
| `bApplyAmbientVolumes` | `boolean` |
| `OutputTarget` | [`EAudioOutputTarget`](../enums/ue_ue.EAudioOutputTarget.md) |
| `LoadingBehavior` | [`ESoundWaveLoadingBehavior`](../enums/ue_ue.ESoundWaveLoadingBehavior.md) |

## Properties

### Default2DReverbSendAmount

• **Default2DReverbSendAmount**: `number`

___

### LFEBleed

• **LFEBleed**: `number`

___

### LoadingBehavior

• **LoadingBehavior**: [`ESoundWaveLoadingBehavior`](../enums/ue_ue.ESoundWaveLoadingBehavior.md)

___

### LowPassFilterFrequency

• **LowPassFilterFrequency**: `number`

___

### OutputTarget

• **OutputTarget**: [`EAudioOutputTarget`](../enums/ue_ue.EAudioOutputTarget.md)

___

### Pitch

• **Pitch**: `number`

___

### RadioFilterVolume

• **RadioFilterVolume**: `number`

___

### RadioFilterVolumeThreshold

• **RadioFilterVolumeThreshold**: `number`

___

### StereoBleed

• **StereoBleed**: `number`

___

### VoiceCenterChannelVolume

• **VoiceCenterChannelVolume**: `number`

___

### Volume

• **Volume**: `number`

___

### \_\_tid\_SoundClassProperties\_\_

• `Private` **\_\_tid\_SoundClassProperties\_\_**: `boolean`

___

### bAlwaysPlay

• **bAlwaysPlay**: `boolean`

___

### bApplyAmbientVolumes

• **bApplyAmbientVolumes**: `boolean`

___

### bApplyEffects

• **bApplyEffects**: `boolean`

___

### bCenterChannelOnly

• **bCenterChannelOnly**: `boolean`

___

### bIsMusic

• **bIsMusic**: `boolean`

___

### bIsUISound

• **bIsUISound**: `boolean`

___

### bReverb

• **bReverb**: `boolean`

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
