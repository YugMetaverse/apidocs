[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SynthSound

# Class: SynthSound

[ue/ue](../modules/ue_ue.md).SynthSound

## Hierarchy

- [`SoundWaveProcedural`](ue_ue.SoundWaveProcedural.md)

  ↳ **`SynthSound`**

## Table of contents

### Constructors

- [constructor](ue_ue.SynthSound.md#constructor)

### Properties

- [AssetImportData](ue_ue.SynthSound.md#assetimportdata)
- [AttenuationSettings](ue_ue.SynthSound.md#attenuationsettings)
- [BusSends](ue_ue.SynthSound.md#bussends)
- [ChannelOffsets](ue_ue.SynthSound.md#channeloffsets)
- [ChannelSizes](ue_ue.SynthSound.md#channelsizes)
- [Comment](ue_ue.SynthSound.md#comment)
- [CompressionQuality](ue_ue.SynthSound.md#compressionquality)
- [ConcurrencyOverrides](ue_ue.SynthSound.md#concurrencyoverrides)
- [ConcurrencySet](ue_ue.SynthSound.md#concurrencyset)
- [CookedEnvelopeTimeData](ue_ue.SynthSound.md#cookedenvelopetimedata)
- [CookedSpectralTimeData](ue_ue.SynthSound.md#cookedspectraltimedata)
- [Curves](ue_ue.SynthSound.md#curves)
- [Duration](ue_ue.SynthSound.md#duration)
- [EnvelopeFollowerAttackTime](ue_ue.SynthSound.md#envelopefollowerattacktime)
- [EnvelopeFollowerFrameSize](ue_ue.SynthSound.md#envelopefollowerframesize)
- [EnvelopeFollowerReleaseTime](ue_ue.SynthSound.md#envelopefollowerreleasetime)
- [FFTAnalysisAttackTime](ue_ue.SynthSound.md#fftanalysisattacktime)
- [FFTAnalysisFrameSize](ue_ue.SynthSound.md#fftanalysisframesize)
- [FFTAnalysisReleaseTime](ue_ue.SynthSound.md#fftanalysisreleasetime)
- [FFTSize](ue_ue.SynthSound.md#fftsize)
- [FrequenciesToAnalyze](ue_ue.SynthSound.md#frequenciestoanalyze)
- [InitialChunkSize](ue_ue.SynthSound.md#initialchunksize)
- [InternalCurves](ue_ue.SynthSound.md#internalcurves)
- [LoadingBehavior](ue_ue.SynthSound.md#loadingbehavior)
- [MaxConcurrentPlayCount](ue_ue.SynthSound.md#maxconcurrentplaycount)
- [MaxConcurrentResolutionRule](ue_ue.SynthSound.md#maxconcurrentresolutionrule)
- [MaxDistance](ue_ue.SynthSound.md#maxdistance)
- [Modulation](ue_ue.SynthSound.md#modulation)
- [NumChannels](ue_ue.SynthSound.md#numchannels)
- [OverrideSoundToUseForAnalysis](ue_ue.SynthSound.md#overridesoundtouseforanalysis)
- [OwningSynthComponent](ue_ue.SynthSound.md#owningsynthcomponent)
- [Pitch](ue_ue.SynthSound.md#pitch)
- [PreEffectBusSends](ue_ue.SynthSound.md#preeffectbussends)
- [Priority](ue_ue.SynthSound.md#priority)
- [SampleRate](ue_ue.SynthSound.md#samplerate)
- [SampleRateQuality](ue_ue.SynthSound.md#sampleratequality)
- [SoundClassObject](ue_ue.SynthSound.md#soundclassobject)
- [SoundConcurrencySettings](ue_ue.SynthSound.md#soundconcurrencysettings)
- [SoundGroup](ue_ue.SynthSound.md#soundgroup)
- [SoundSubmixObject](ue_ue.SynthSound.md#soundsubmixobject)
- [SoundSubmixSends](ue_ue.SynthSound.md#soundsubmixsends)
- [SourceEffectChain](ue_ue.SynthSound.md#sourceeffectchain)
- [SourceFilePath](ue_ue.SynthSound.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.SynthSound.md#sourcefiletimestamp)
- [SpokenText](ue_ue.SynthSound.md#spokentext)
- [StreamingPriority](ue_ue.SynthSound.md#streamingpriority)
- [SubtitlePriority](ue_ue.SynthSound.md#subtitlepriority)
- [Subtitles](ue_ue.SynthSound.md#subtitles)
- [TotalSamples](ue_ue.SynthSound.md#totalsamples)
- [TreatFileAsLoopingForAnalysis](ue_ue.SynthSound.md#treatfileasloopingforanalysis)
- [VirtualizationMode](ue_ue.SynthSound.md#virtualizationmode)
- [Volume](ue_ue.SynthSound.md#volume)
- [\_\_tid\_Object\_\_](ue_ue.SynthSound.md#__tid_object__)
- [\_\_tid\_SoundBase\_\_](ue_ue.SynthSound.md#__tid_soundbase__)
- [\_\_tid\_SoundWaveProcedural\_\_](ue_ue.SynthSound.md#__tid_soundwaveprocedural__)
- [\_\_tid\_SoundWave\_\_](ue_ue.SynthSound.md#__tid_soundwave__)
- [\_\_tid\_SynthSound\_\_](ue_ue.SynthSound.md#__tid_synthsound__)
- [bBypassVolumeScaleForPriority](ue_ue.SynthSound.md#bbypassvolumescaleforpriority)
- [bDebug](ue_ue.SynthSound.md#bdebug)
- [bEnableAmplitudeEnvelopeAnalysis](ue_ue.SynthSound.md#benableamplitudeenvelopeanalysis)
- [bEnableBakedFFTAnalysis](ue_ue.SynthSound.md#benablebakedfftanalysis)
- [bHasConcatenatorNode](ue_ue.SynthSound.md#bhasconcatenatornode)
- [bHasDelayNode](ue_ue.SynthSound.md#bhasdelaynode)
- [bHasVirtualizeWhenSilent](ue_ue.SynthSound.md#bhasvirtualizewhensilent)
- [bIsAmbisonics](ue_ue.SynthSound.md#bisambisonics)
- [bLooping](ue_ue.SynthSound.md#blooping)
- [bManualWordWrap](ue_ue.SynthSound.md#bmanualwordwrap)
- [bMature](ue_ue.SynthSound.md#bmature)
- [bOutputToBusOnly](ue_ue.SynthSound.md#boutputtobusonly)
- [bOverrideConcurrency](ue_ue.SynthSound.md#boverrideconcurrency)
- [bSeekableStreaming](ue_ue.SynthSound.md#bseekablestreaming)
- [bSingleLine](ue_ue.SynthSound.md#bsingleline)
- [bStreaming](ue_ue.SynthSound.md#bstreaming)
- [bVirtualizeWhenSilent](ue_ue.SynthSound.md#bvirtualizewhensilent)

### Methods

- [CreateDefaultSubobject](ue_ue.SynthSound.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SynthSound.md#executeubergraph)
- [GetClass](ue_ue.SynthSound.md#getclass)
- [GetName](ue_ue.SynthSound.md#getname)
- [GetOuter](ue_ue.SynthSound.md#getouter)
- [GetWorld](ue_ue.SynthSound.md#getworld)
- [Find](ue_ue.SynthSound.md#find)
- [Load](ue_ue.SynthSound.md#load)
- [StaticClass](ue_ue.SynthSound.md#staticclass)

## Constructors

### constructor

• **new SynthSound**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[constructor](ue_ue.SoundWaveProcedural.md#constructor)

#### Defined in

[ue/ue.d.ts:22316](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22316)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[AssetImportData](ue_ue.SoundWaveProcedural.md#assetimportdata)

#### Defined in

[ue/ue.d.ts:9593](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9593)

___

### AttenuationSettings

• **AttenuationSettings**: [`SoundAttenuation`](ue_ue.SoundAttenuation.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[AttenuationSettings](ue_ue.SoundWaveProcedural.md#attenuationsettings)

#### Defined in

[ue/ue.d.ts:9735](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9735)

___

### BusSends

• **BusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[BusSends](ue_ue.SoundWaveProcedural.md#bussends)

#### Defined in

[ue/ue.d.ts:9740](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9740)

___

### ChannelOffsets

• **ChannelOffsets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[ChannelOffsets](ue_ue.SoundWaveProcedural.md#channeloffsets)

#### Defined in

[ue/ue.d.ts:9586](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9586)

___

### ChannelSizes

• **ChannelSizes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[ChannelSizes](ue_ue.SoundWaveProcedural.md#channelsizes)

#### Defined in

[ue/ue.d.ts:9587](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9587)

___

### Comment

• **Comment**: `string`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Comment](ue_ue.SoundWaveProcedural.md#comment)

#### Defined in

[ue/ue.d.ts:9590](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9590)

___

### CompressionQuality

• **CompressionQuality**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[CompressionQuality](ue_ue.SoundWaveProcedural.md#compressionquality)

#### Defined in

[ue/ue.d.ts:9553](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9553)

___

### ConcurrencyOverrides

• **ConcurrencyOverrides**: [`SoundConcurrencySettings`](ue_ue.SoundConcurrencySettings.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[ConcurrencyOverrides](ue_ue.SoundWaveProcedural.md#concurrencyoverrides)

#### Defined in

[ue/ue.d.ts:9729](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9729)

___

### ConcurrencySet

• **ConcurrencySet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`SoundConcurrency`](ue_ue.SoundConcurrency.md)\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[ConcurrencySet](ue_ue.SoundWaveProcedural.md#concurrencyset)

#### Defined in

[ue/ue.d.ts:9728](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9728)

___

### CookedEnvelopeTimeData

• **CookedEnvelopeTimeData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundWaveEnvelopeTimeData`](ue_ue.SoundWaveEnvelopeTimeData.md)\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[CookedEnvelopeTimeData](ue_ue.SoundWaveProcedural.md#cookedenvelopetimedata)

#### Defined in

[ue/ue.d.ts:9579](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9579)

___

### CookedSpectralTimeData

• **CookedSpectralTimeData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundWaveSpectralTimeData`](ue_ue.SoundWaveSpectralTimeData.md)\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[CookedSpectralTimeData](ue_ue.SoundWaveProcedural.md#cookedspectraltimedata)

#### Defined in

[ue/ue.d.ts:9578](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9578)

___

### Curves

• **Curves**: [`CurveTable`](ue_ue.CurveTable.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Curves](ue_ue.SoundWaveProcedural.md#curves)

#### Defined in

[ue/ue.d.ts:9594](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9594)

___

### Duration

• **Duration**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Duration](ue_ue.SoundWaveProcedural.md#duration)

#### Defined in

[ue/ue.d.ts:9731](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9731)

___

### EnvelopeFollowerAttackTime

• **EnvelopeFollowerAttackTime**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[EnvelopeFollowerAttackTime](ue_ue.SoundWaveProcedural.md#envelopefollowerattacktime)

#### Defined in

[ue/ue.d.ts:9575](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9575)

___

### EnvelopeFollowerFrameSize

• **EnvelopeFollowerFrameSize**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[EnvelopeFollowerFrameSize](ue_ue.SoundWaveProcedural.md#envelopefollowerframesize)

#### Defined in

[ue/ue.d.ts:9574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9574)

___

### EnvelopeFollowerReleaseTime

• **EnvelopeFollowerReleaseTime**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[EnvelopeFollowerReleaseTime](ue_ue.SoundWaveProcedural.md#envelopefollowerreleasetime)

#### Defined in

[ue/ue.d.ts:9576](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9576)

___

### FFTAnalysisAttackTime

• **FFTAnalysisAttackTime**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[FFTAnalysisAttackTime](ue_ue.SoundWaveProcedural.md#fftanalysisattacktime)

#### Defined in

[ue/ue.d.ts:9572](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9572)

___

### FFTAnalysisFrameSize

• **FFTAnalysisFrameSize**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[FFTAnalysisFrameSize](ue_ue.SoundWaveProcedural.md#fftanalysisframesize)

#### Defined in

[ue/ue.d.ts:9571](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9571)

___

### FFTAnalysisReleaseTime

• **FFTAnalysisReleaseTime**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[FFTAnalysisReleaseTime](ue_ue.SoundWaveProcedural.md#fftanalysisreleasetime)

#### Defined in

[ue/ue.d.ts:9573](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9573)

___

### FFTSize

• **FFTSize**: [`ESoundWaveFFTSize`](../enums/ue_ue.ESoundWaveFFTSize.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[FFTSize](ue_ue.SoundWaveProcedural.md#fftsize)

#### Defined in

[ue/ue.d.ts:9570](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9570)

___

### FrequenciesToAnalyze

• **FrequenciesToAnalyze**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[FrequenciesToAnalyze](ue_ue.SoundWaveProcedural.md#frequenciestoanalyze)

#### Defined in

[ue/ue.d.ts:9577](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9577)

___

### InitialChunkSize

• **InitialChunkSize**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[InitialChunkSize](ue_ue.SoundWaveProcedural.md#initialchunksize)

#### Defined in

[ue/ue.d.ts:9580](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9580)

___

### InternalCurves

• **InternalCurves**: [`CurveTable`](ue_ue.CurveTable.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[InternalCurves](ue_ue.SoundWaveProcedural.md#internalcurves)

#### Defined in

[ue/ue.d.ts:9595](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9595)

___

### LoadingBehavior

• **LoadingBehavior**: [`ESoundWaveLoadingBehavior`](../enums/ue_ue.ESoundWaveLoadingBehavior.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[LoadingBehavior](ue_ue.SoundWaveProcedural.md#loadingbehavior)

#### Defined in

[ue/ue.d.ts:9560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9560)

___

### MaxConcurrentPlayCount

• **MaxConcurrentPlayCount**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[MaxConcurrentPlayCount](ue_ue.SoundWaveProcedural.md#maxconcurrentplaycount)

#### Defined in

[ue/ue.d.ts:9730](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9730)

___

### MaxConcurrentResolutionRule

• **MaxConcurrentResolutionRule**: [`EMaxConcurrentResolutionRule`](../enums/ue_ue.EMaxConcurrentResolutionRule.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[MaxConcurrentResolutionRule](ue_ue.SoundWaveProcedural.md#maxconcurrentresolutionrule)

#### Defined in

[ue/ue.d.ts:9726](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9726)

___

### MaxDistance

• **MaxDistance**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[MaxDistance](ue_ue.SoundWaveProcedural.md#maxdistance)

#### Defined in

[ue/ue.d.ts:9732](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9732)

___

### Modulation

• **Modulation**: [`SoundModulation`](ue_ue.SoundModulation.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Modulation](ue_ue.SoundWaveProcedural.md#modulation)

#### Defined in

[ue/ue.d.ts:9736](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9736)

___

### NumChannels

• **NumChannels**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[NumChannels](ue_ue.SoundWaveProcedural.md#numchannels)

#### Defined in

[ue/ue.d.ts:9585](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9585)

___

### OverrideSoundToUseForAnalysis

• **OverrideSoundToUseForAnalysis**: [`SoundWave`](ue_ue.SoundWave.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[OverrideSoundToUseForAnalysis](ue_ue.SoundWaveProcedural.md#overridesoundtouseforanalysis)

#### Defined in

[ue/ue.d.ts:9566](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9566)

___

### OwningSynthComponent

• **OwningSynthComponent**: [`SynthComponent`](ue_ue.SynthComponent.md)

#### Defined in

[ue/ue.d.ts:22317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22317)

___

### Pitch

• **Pitch**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Pitch](ue_ue.SoundWaveProcedural.md#pitch)

#### Defined in

[ue/ue.d.ts:9584](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9584)

___

### PreEffectBusSends

• **PreEffectBusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[PreEffectBusSends](ue_ue.SoundWaveProcedural.md#preeffectbussends)

#### Defined in

[ue/ue.d.ts:9741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9741)

___

### Priority

• **Priority**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Priority](ue_ue.SoundWaveProcedural.md#priority)

#### Defined in

[ue/ue.d.ts:9734](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9734)

___

### SampleRate

• **SampleRate**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SampleRate](ue_ue.SoundWaveProcedural.md#samplerate)

#### Defined in

[ue/ue.d.ts:9588](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9588)

___

### SampleRateQuality

• **SampleRateQuality**: [`ESoundwaveSampleRateSettings`](../enums/ue_ue.ESoundwaveSampleRateSettings.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SampleRateQuality](ue_ue.SoundWaveProcedural.md#sampleratequality)

#### Defined in

[ue/ue.d.ts:9555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9555)

___

### SoundClassObject

• **SoundClassObject**: [`SoundClass`](ue_ue.SoundClass.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SoundClassObject](ue_ue.SoundWaveProcedural.md#soundclassobject)

#### Defined in

[ue/ue.d.ts:9717](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9717)

___

### SoundConcurrencySettings

• **SoundConcurrencySettings**: [`SoundConcurrency`](ue_ue.SoundConcurrency.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SoundConcurrencySettings](ue_ue.SoundWaveProcedural.md#soundconcurrencysettings)

#### Defined in

[ue/ue.d.ts:9727](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9727)

___

### SoundGroup

• **SoundGroup**: [`ESoundGroup`](../enums/ue_ue.ESoundGroup.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SoundGroup](ue_ue.SoundWaveProcedural.md#soundgroup)

#### Defined in

[ue/ue.d.ts:9556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9556)

___

### SoundSubmixObject

• **SoundSubmixObject**: [`SoundSubmix`](ue_ue.SoundSubmix.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SoundSubmixObject](ue_ue.SoundWaveProcedural.md#soundsubmixobject)

#### Defined in

[ue/ue.d.ts:9737](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9737)

___

### SoundSubmixSends

• **SoundSubmixSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSubmixSendInfo`](ue_ue.SoundSubmixSendInfo.md)\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SoundSubmixSends](ue_ue.SoundWaveProcedural.md#soundsubmixsends)

#### Defined in

[ue/ue.d.ts:9738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9738)

___

### SourceEffectChain

• **SourceEffectChain**: [`SoundEffectSourcePresetChain`](ue_ue.SoundEffectSourcePresetChain.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SourceEffectChain](ue_ue.SoundWaveProcedural.md#sourceeffectchain)

#### Defined in

[ue/ue.d.ts:9739](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9739)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SourceFilePath](ue_ue.SoundWaveProcedural.md#sourcefilepath)

#### Defined in

[ue/ue.d.ts:9591](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9591)

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SourceFileTimestamp](ue_ue.SoundWaveProcedural.md#sourcefiletimestamp)

#### Defined in

[ue/ue.d.ts:9592](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9592)

___

### SpokenText

• **SpokenText**: `string`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SpokenText](ue_ue.SoundWaveProcedural.md#spokentext)

#### Defined in

[ue/ue.d.ts:9581](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9581)

___

### StreamingPriority

• **StreamingPriority**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[StreamingPriority](ue_ue.SoundWaveProcedural.md#streamingpriority)

#### Defined in

[ue/ue.d.ts:9554](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9554)

___

### SubtitlePriority

• **SubtitlePriority**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[SubtitlePriority](ue_ue.SoundWaveProcedural.md#subtitlepriority)

#### Defined in

[ue/ue.d.ts:9582](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9582)

___

### Subtitles

• **Subtitles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SubtitleCue`](ue_ue.SubtitleCue.md)\>

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Subtitles](ue_ue.SoundWaveProcedural.md#subtitles)

#### Defined in

[ue/ue.d.ts:9589](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9589)

___

### TotalSamples

• **TotalSamples**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[TotalSamples](ue_ue.SoundWaveProcedural.md#totalsamples)

#### Defined in

[ue/ue.d.ts:9733](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9733)

___

### TreatFileAsLoopingForAnalysis

• **TreatFileAsLoopingForAnalysis**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[TreatFileAsLoopingForAnalysis](ue_ue.SoundWaveProcedural.md#treatfileasloopingforanalysis)

#### Defined in

[ue/ue.d.ts:9567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9567)

___

### VirtualizationMode

• **VirtualizationMode**: [`EVirtualizationMode`](../enums/ue_ue.EVirtualizationMode.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[VirtualizationMode](ue_ue.SoundWaveProcedural.md#virtualizationmode)

#### Defined in

[ue/ue.d.ts:9725](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9725)

___

### Volume

• **Volume**: `number`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Volume](ue_ue.SoundWaveProcedural.md#volume)

#### Defined in

[ue/ue.d.ts:9583](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9583)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[__tid_Object__](ue_ue.SoundWaveProcedural.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SoundBase\_\_

• **\_\_tid\_SoundBase\_\_**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[__tid_SoundBase__](ue_ue.SoundWaveProcedural.md#__tid_soundbase__)

#### Defined in

[ue/ue.d.ts:9746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9746)

___

### \_\_tid\_SoundWaveProcedural\_\_

• **\_\_tid\_SoundWaveProcedural\_\_**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[__tid_SoundWaveProcedural__](ue_ue.SoundWaveProcedural.md#__tid_soundwaveprocedural__)

#### Defined in

[ue/ue.d.ts:22312](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22312)

___

### \_\_tid\_SoundWave\_\_

• **\_\_tid\_SoundWave\_\_**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[__tid_SoundWave__](ue_ue.SoundWaveProcedural.md#__tid_soundwave__)

#### Defined in

[ue/ue.d.ts:9600](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9600)

___

### \_\_tid\_SynthSound\_\_

• **\_\_tid\_SynthSound\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:22322](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22322)

___

### bBypassVolumeScaleForPriority

• **bBypassVolumeScaleForPriority**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bBypassVolumeScaleForPriority](ue_ue.SoundWaveProcedural.md#bbypassvolumescaleforpriority)

#### Defined in

[ue/ue.d.ts:9724](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9724)

___

### bDebug

• **bDebug**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bDebug](ue_ue.SoundWaveProcedural.md#bdebug)

#### Defined in

[ue/ue.d.ts:9718](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9718)

___

### bEnableAmplitudeEnvelopeAnalysis

• **bEnableAmplitudeEnvelopeAnalysis**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bEnableAmplitudeEnvelopeAnalysis](ue_ue.SoundWaveProcedural.md#benableamplitudeenvelopeanalysis)

#### Defined in

[ue/ue.d.ts:9569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9569)

___

### bEnableBakedFFTAnalysis

• **bEnableBakedFFTAnalysis**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bEnableBakedFFTAnalysis](ue_ue.SoundWaveProcedural.md#benablebakedfftanalysis)

#### Defined in

[ue/ue.d.ts:9568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9568)

___

### bHasConcatenatorNode

• **bHasConcatenatorNode**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bHasConcatenatorNode](ue_ue.SoundWaveProcedural.md#bhasconcatenatornode)

#### Defined in

[ue/ue.d.ts:9722](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9722)

___

### bHasDelayNode

• **bHasDelayNode**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bHasDelayNode](ue_ue.SoundWaveProcedural.md#bhasdelaynode)

#### Defined in

[ue/ue.d.ts:9721](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9721)

___

### bHasVirtualizeWhenSilent

• **bHasVirtualizeWhenSilent**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bHasVirtualizeWhenSilent](ue_ue.SoundWaveProcedural.md#bhasvirtualizewhensilent)

#### Defined in

[ue/ue.d.ts:9723](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9723)

___

### bIsAmbisonics

• **bIsAmbisonics**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bIsAmbisonics](ue_ue.SoundWaveProcedural.md#bisambisonics)

#### Defined in

[ue/ue.d.ts:9565](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9565)

___

### bLooping

• **bLooping**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bLooping](ue_ue.SoundWaveProcedural.md#blooping)

#### Defined in

[ue/ue.d.ts:9557](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9557)

___

### bManualWordWrap

• **bManualWordWrap**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bManualWordWrap](ue_ue.SoundWaveProcedural.md#bmanualwordwrap)

#### Defined in

[ue/ue.d.ts:9562](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9562)

___

### bMature

• **bMature**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bMature](ue_ue.SoundWaveProcedural.md#bmature)

#### Defined in

[ue/ue.d.ts:9561](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9561)

___

### bOutputToBusOnly

• **bOutputToBusOnly**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bOutputToBusOnly](ue_ue.SoundWaveProcedural.md#boutputtobusonly)

#### Defined in

[ue/ue.d.ts:9720](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9720)

___

### bOverrideConcurrency

• **bOverrideConcurrency**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bOverrideConcurrency](ue_ue.SoundWaveProcedural.md#boverrideconcurrency)

#### Defined in

[ue/ue.d.ts:9719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9719)

___

### bSeekableStreaming

• **bSeekableStreaming**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bSeekableStreaming](ue_ue.SoundWaveProcedural.md#bseekablestreaming)

#### Defined in

[ue/ue.d.ts:9559](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9559)

___

### bSingleLine

• **bSingleLine**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bSingleLine](ue_ue.SoundWaveProcedural.md#bsingleline)

#### Defined in

[ue/ue.d.ts:9563](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9563)

___

### bStreaming

• **bStreaming**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bStreaming](ue_ue.SoundWaveProcedural.md#bstreaming)

#### Defined in

[ue/ue.d.ts:9558](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9558)

___

### bVirtualizeWhenSilent

• **bVirtualizeWhenSilent**: `boolean`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[bVirtualizeWhenSilent](ue_ue.SoundWaveProcedural.md#bvirtualizewhensilent)

#### Defined in

[ue/ue.d.ts:9564](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9564)

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

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[CreateDefaultSubobject](ue_ue.SoundWaveProcedural.md#createdefaultsubobject)

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

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[ExecuteUbergraph](ue_ue.SoundWaveProcedural.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[GetClass](ue_ue.SoundWaveProcedural.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[GetName](ue_ue.SoundWaveProcedural.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[GetOuter](ue_ue.SoundWaveProcedural.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[GetWorld](ue_ue.SoundWaveProcedural.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SynthSound`](ue_ue.SynthSound.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SynthSound`](ue_ue.SynthSound.md)

#### Overrides

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Find](ue_ue.SoundWaveProcedural.md#find)

#### Defined in

[ue/ue.d.ts:22319](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22319)

___

### Load

▸ `Static` **Load**(`InName`): [`SynthSound`](ue_ue.SynthSound.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SynthSound`](ue_ue.SynthSound.md)

#### Overrides

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[Load](ue_ue.SoundWaveProcedural.md#load)

#### Defined in

[ue/ue.d.ts:22320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22320)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundWaveProcedural](ue_ue.SoundWaveProcedural.md).[StaticClass](ue_ue.SoundWaveProcedural.md#staticclass)

#### Defined in

[ue/ue.d.ts:22318](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22318)
