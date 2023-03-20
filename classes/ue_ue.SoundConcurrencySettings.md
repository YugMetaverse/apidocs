[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundConcurrencySettings

# Class: SoundConcurrencySettings

[ue/ue](../modules/ue_ue.md).SoundConcurrencySettings

## Table of contents

### Constructors

- [constructor](ue_ue.SoundConcurrencySettings.md#constructor)

### Properties

- [MaxCount](ue_ue.SoundConcurrencySettings.md#maxcount)
- [ResolutionRule](ue_ue.SoundConcurrencySettings.md#resolutionrule)
- [VoiceStealReleaseTime](ue_ue.SoundConcurrencySettings.md#voicestealreleasetime)
- [VolumeScale](ue_ue.SoundConcurrencySettings.md#volumescale)
- [VolumeScaleAttackTime](ue_ue.SoundConcurrencySettings.md#volumescaleattacktime)
- [VolumeScaleReleaseTime](ue_ue.SoundConcurrencySettings.md#volumescalereleasetime)
- [\_\_tid\_SoundConcurrencySettings\_\_](ue_ue.SoundConcurrencySettings.md#__tid_soundconcurrencysettings__)
- [bLimitToOwner](ue_ue.SoundConcurrencySettings.md#blimittoowner)
- [bVolumeScaleCanRelease](ue_ue.SoundConcurrencySettings.md#bvolumescalecanrelease)

### Methods

- [StaticClass](ue_ue.SoundConcurrencySettings.md#staticclass)
- [StaticStruct](ue_ue.SoundConcurrencySettings.md#staticstruct)

## Constructors

### constructor

• **new SoundConcurrencySettings**()

• **new SoundConcurrencySettings**(`MaxCount`, `bLimitToOwner`, `ResolutionRule`, `VolumeScale`, `VolumeScaleAttackTime`, `bVolumeScaleCanRelease`, `VolumeScaleReleaseTime`, `VoiceStealReleaseTime`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaxCount` | `number` |
| `bLimitToOwner` | `boolean` |
| `ResolutionRule` | [`EMaxConcurrentResolutionRule`](../enums/ue_ue.EMaxConcurrentResolutionRule.md) |
| `VolumeScale` | `number` |
| `VolumeScaleAttackTime` | `number` |
| `bVolumeScaleCanRelease` | `boolean` |
| `VolumeScaleReleaseTime` | `number` |
| `VoiceStealReleaseTime` | `number` |

## Properties

### MaxCount

• **MaxCount**: `number`

___

### ResolutionRule

• **ResolutionRule**: [`EMaxConcurrentResolutionRule`](../enums/ue_ue.EMaxConcurrentResolutionRule.md)

___

### VoiceStealReleaseTime

• **VoiceStealReleaseTime**: `number`

___

### VolumeScale

• **VolumeScale**: `number`

___

### VolumeScaleAttackTime

• **VolumeScaleAttackTime**: `number`

___

### VolumeScaleReleaseTime

• **VolumeScaleReleaseTime**: `number`

___

### \_\_tid\_SoundConcurrencySettings\_\_

• `Private` **\_\_tid\_SoundConcurrencySettings\_\_**: `boolean`

___

### bLimitToOwner

• **bLimitToOwner**: `boolean`

___

### bVolumeScaleCanRelease

• **bVolumeScaleCanRelease**: `boolean`

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
