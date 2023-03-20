[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AudioSettings

# Class: AudioSettings

[ue/ue](../modules/ue_ue.md).AudioSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`AudioSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.AudioSettings.md#constructor)

### Properties

- [DefaultBaseSoundMix](ue_ue.AudioSettings.md#defaultbasesoundmix)
- [DefaultMediaSoundClassName](ue_ue.AudioSettings.md#defaultmediasoundclassname)
- [DefaultReverbSendLevel](ue_ue.AudioSettings.md#defaultreverbsendlevel)
- [DefaultSoundClassName](ue_ue.AudioSettings.md#defaultsoundclassname)
- [DefaultSoundConcurrencyName](ue_ue.AudioSettings.md#defaultsoundconcurrencyname)
- [DialogueFilenameFormat](ue_ue.AudioSettings.md#dialoguefilenameformat)
- [GlobalMaxPitchScale](ue_ue.AudioSettings.md#globalmaxpitchscale)
- [GlobalMinPitchScale](ue_ue.AudioSettings.md#globalminpitchscale)
- [MaximumConcurrentStreams](ue_ue.AudioSettings.md#maximumconcurrentstreams)
- [MonoChannelUpmixMethod](ue_ue.AudioSettings.md#monochannelupmixmethod)
- [NumStoppingSources](ue_ue.AudioSettings.md#numstoppingsources)
- [PanningMethod](ue_ue.AudioSettings.md#panningmethod)
- [QualityLevels](ue_ue.AudioSettings.md#qualitylevels)
- [VoiPSampleRate](ue_ue.AudioSettings.md#voipsamplerate)
- [VoiPSoundClass](ue_ue.AudioSettings.md#voipsoundclass)
- [VoipBufferingDelay](ue_ue.AudioSettings.md#voipbufferingdelay)
- [\_\_tid\_AudioSettings\_\_](ue_ue.AudioSettings.md#__tid_audiosettings__)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.AudioSettings.md#__tid_developersettings__)
- [\_\_tid\_Object\_\_](ue_ue.AudioSettings.md#__tid_object__)
- [bAllowCenterChannel3DPanning](ue_ue.AudioSettings.md#ballowcenterchannel3dpanning)
- [bAllowPlayWhenSilent](ue_ue.AudioSettings.md#ballowplaywhensilent)
- [bDisableMasterEQ](ue_ue.AudioSettings.md#bdisablemastereq)
- [bEnableLegacyReverb](ue_ue.AudioSettings.md#benablelegacyreverb)

### Methods

- [CreateDefaultSubobject](ue_ue.AudioSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AudioSettings.md#executeubergraph)
- [GetClass](ue_ue.AudioSettings.md#getclass)
- [GetName](ue_ue.AudioSettings.md#getname)
- [GetOuter](ue_ue.AudioSettings.md#getouter)
- [GetWorld](ue_ue.AudioSettings.md#getworld)
- [Find](ue_ue.AudioSettings.md#find)
- [Load](ue_ue.AudioSettings.md#load)
- [StaticClass](ue_ue.AudioSettings.md#staticclass)

## Constructors

### constructor

• **new AudioSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

## Properties

### DefaultBaseSoundMix

• **DefaultBaseSoundMix**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### DefaultMediaSoundClassName

• **DefaultMediaSoundClassName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### DefaultReverbSendLevel

• **DefaultReverbSendLevel**: `number`

___

### DefaultSoundClassName

• **DefaultSoundClassName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### DefaultSoundConcurrencyName

• **DefaultSoundConcurrencyName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### DialogueFilenameFormat

• **DialogueFilenameFormat**: `string`

___

### GlobalMaxPitchScale

• **GlobalMaxPitchScale**: `number`

___

### GlobalMinPitchScale

• **GlobalMinPitchScale**: `number`

___

### MaximumConcurrentStreams

• **MaximumConcurrentStreams**: `number`

___

### MonoChannelUpmixMethod

• **MonoChannelUpmixMethod**: [`EMonoChannelUpmixMethod`](../enums/ue_ue.EMonoChannelUpmixMethod.md)

___

### NumStoppingSources

• **NumStoppingSources**: `number`

___

### PanningMethod

• **PanningMethod**: [`EPanningMethod`](../enums/ue_ue.EPanningMethod.md)

___

### QualityLevels

• **QualityLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AudioQualitySettings`](ue_ue.AudioQualitySettings.md)\>

___

### VoiPSampleRate

• **VoiPSampleRate**: [`EVoiceSampleRate`](../enums/ue_ue.EVoiceSampleRate.md)

___

### VoiPSoundClass

• **VoiPSoundClass**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### VoipBufferingDelay

• **VoipBufferingDelay**: `number`

___

### \_\_tid\_AudioSettings\_\_

• **\_\_tid\_AudioSettings\_\_**: `boolean`

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

___

### bAllowCenterChannel3DPanning

• **bAllowCenterChannel3DPanning**: `boolean`

___

### bAllowPlayWhenSilent

• **bAllowPlayWhenSilent**: `boolean`

___

### bDisableMasterEQ

• **bDisableMasterEQ**: `boolean`

___

### bEnableLegacyReverb

• **bEnableLegacyReverb**: `boolean`

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[CreateDefaultSubobject](ue_ue.DeveloperSettings.md#createdefaultsubobject)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AudioSettings`](ue_ue.AudioSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AudioSettings`](ue_ue.AudioSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AudioSettings`](ue_ue.AudioSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AudioSettings`](ue_ue.AudioSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
