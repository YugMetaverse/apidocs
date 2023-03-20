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

#### Defined in

[ue/ue.d.ts:22480](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22480)

## Properties

### DefaultBaseSoundMix

• **DefaultBaseSoundMix**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:22484](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22484)

___

### DefaultMediaSoundClassName

• **DefaultMediaSoundClassName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:22482](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22482)

___

### DefaultReverbSendLevel

• **DefaultReverbSendLevel**: `number`

#### Defined in

[ue/ue.d.ts:22488](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22488)

___

### DefaultSoundClassName

• **DefaultSoundClassName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:22481](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22481)

___

### DefaultSoundConcurrencyName

• **DefaultSoundConcurrencyName**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:22483](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22483)

___

### DialogueFilenameFormat

• **DialogueFilenameFormat**: `string`

#### Defined in

[ue/ue.d.ts:22500](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22500)

___

### GlobalMaxPitchScale

• **GlobalMaxPitchScale**: `number`

#### Defined in

[ue/ue.d.ts:22492](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22492)

___

### GlobalMinPitchScale

• **GlobalMinPitchScale**: `number`

#### Defined in

[ue/ue.d.ts:22491](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22491)

___

### MaximumConcurrentStreams

• **MaximumConcurrentStreams**: `number`

#### Defined in

[ue/ue.d.ts:22490](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22490)

___

### MonoChannelUpmixMethod

• **MonoChannelUpmixMethod**: [`EMonoChannelUpmixMethod`](../enums/ue_ue.EMonoChannelUpmixMethod.md)

#### Defined in

[ue/ue.d.ts:22499](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22499)

___

### NumStoppingSources

• **NumStoppingSources**: `number`

#### Defined in

[ue/ue.d.ts:22497](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22497)

___

### PanningMethod

• **PanningMethod**: [`EPanningMethod`](../enums/ue_ue.EPanningMethod.md)

#### Defined in

[ue/ue.d.ts:22498](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22498)

___

### QualityLevels

• **QualityLevels**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AudioQualitySettings`](ue_ue.AudioQualitySettings.md)\>

#### Defined in

[ue/ue.d.ts:22493](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22493)

___

### VoiPSampleRate

• **VoiPSampleRate**: [`EVoiceSampleRate`](../enums/ue_ue.EVoiceSampleRate.md)

#### Defined in

[ue/ue.d.ts:22486](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22486)

___

### VoiPSoundClass

• **VoiPSoundClass**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:22485](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22485)

___

### VoipBufferingDelay

• **VoipBufferingDelay**: `number`

#### Defined in

[ue/ue.d.ts:22487](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22487)

___

### \_\_tid\_AudioSettings\_\_

• **\_\_tid\_AudioSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:22505](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22505)

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

#### Defined in

[ue/ue.d.ts:16950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16950)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bAllowCenterChannel3DPanning

• **bAllowCenterChannel3DPanning**: `boolean`

#### Defined in

[ue/ue.d.ts:22496](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22496)

___

### bAllowPlayWhenSilent

• **bAllowPlayWhenSilent**: `boolean`

#### Defined in

[ue/ue.d.ts:22494](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22494)

___

### bDisableMasterEQ

• **bDisableMasterEQ**: `boolean`

#### Defined in

[ue/ue.d.ts:22495](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22495)

___

### bEnableLegacyReverb

• **bEnableLegacyReverb**: `boolean`

#### Defined in

[ue/ue.d.ts:22489](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22489)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:22502](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22502)

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

#### Defined in

[ue/ue.d.ts:22503](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22503)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)

#### Defined in

[ue/ue.d.ts:22501](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22501)
