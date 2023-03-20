[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundWave

# Class: SoundWave

[ue/ue](../modules/ue_ue.md).SoundWave

## Hierarchy

- [`SoundBase`](ue_ue.SoundBase.md)

  ↳ **`SoundWave`**

  ↳↳ [`SoundSourceBus`](ue_ue.SoundSourceBus.md)

  ↳↳ [`SoundWaveProcedural`](ue_ue.SoundWaveProcedural.md)

## Table of contents

### Constructors

- [constructor](ue_ue.SoundWave.md#constructor)

### Properties

- [AssetImportData](ue_ue.SoundWave.md#assetimportdata)
- [AttenuationSettings](ue_ue.SoundWave.md#attenuationsettings)
- [BusSends](ue_ue.SoundWave.md#bussends)
- [ChannelOffsets](ue_ue.SoundWave.md#channeloffsets)
- [ChannelSizes](ue_ue.SoundWave.md#channelsizes)
- [Comment](ue_ue.SoundWave.md#comment)
- [CompressionQuality](ue_ue.SoundWave.md#compressionquality)
- [ConcurrencyOverrides](ue_ue.SoundWave.md#concurrencyoverrides)
- [ConcurrencySet](ue_ue.SoundWave.md#concurrencyset)
- [CookedEnvelopeTimeData](ue_ue.SoundWave.md#cookedenvelopetimedata)
- [CookedSpectralTimeData](ue_ue.SoundWave.md#cookedspectraltimedata)
- [Curves](ue_ue.SoundWave.md#curves)
- [Duration](ue_ue.SoundWave.md#duration)
- [EnvelopeFollowerAttackTime](ue_ue.SoundWave.md#envelopefollowerattacktime)
- [EnvelopeFollowerFrameSize](ue_ue.SoundWave.md#envelopefollowerframesize)
- [EnvelopeFollowerReleaseTime](ue_ue.SoundWave.md#envelopefollowerreleasetime)
- [FFTAnalysisAttackTime](ue_ue.SoundWave.md#fftanalysisattacktime)
- [FFTAnalysisFrameSize](ue_ue.SoundWave.md#fftanalysisframesize)
- [FFTAnalysisReleaseTime](ue_ue.SoundWave.md#fftanalysisreleasetime)
- [FFTSize](ue_ue.SoundWave.md#fftsize)
- [FrequenciesToAnalyze](ue_ue.SoundWave.md#frequenciestoanalyze)
- [InitialChunkSize](ue_ue.SoundWave.md#initialchunksize)
- [InternalCurves](ue_ue.SoundWave.md#internalcurves)
- [LoadingBehavior](ue_ue.SoundWave.md#loadingbehavior)
- [MaxConcurrentPlayCount](ue_ue.SoundWave.md#maxconcurrentplaycount)
- [MaxConcurrentResolutionRule](ue_ue.SoundWave.md#maxconcurrentresolutionrule)
- [MaxDistance](ue_ue.SoundWave.md#maxdistance)
- [Modulation](ue_ue.SoundWave.md#modulation)
- [NumChannels](ue_ue.SoundWave.md#numchannels)
- [OverrideSoundToUseForAnalysis](ue_ue.SoundWave.md#overridesoundtouseforanalysis)
- [Pitch](ue_ue.SoundWave.md#pitch)
- [PreEffectBusSends](ue_ue.SoundWave.md#preeffectbussends)
- [Priority](ue_ue.SoundWave.md#priority)
- [SampleRate](ue_ue.SoundWave.md#samplerate)
- [SampleRateQuality](ue_ue.SoundWave.md#sampleratequality)
- [SoundClassObject](ue_ue.SoundWave.md#soundclassobject)
- [SoundConcurrencySettings](ue_ue.SoundWave.md#soundconcurrencysettings)
- [SoundGroup](ue_ue.SoundWave.md#soundgroup)
- [SoundSubmixObject](ue_ue.SoundWave.md#soundsubmixobject)
- [SoundSubmixSends](ue_ue.SoundWave.md#soundsubmixsends)
- [SourceEffectChain](ue_ue.SoundWave.md#sourceeffectchain)
- [SourceFilePath](ue_ue.SoundWave.md#sourcefilepath)
- [SourceFileTimestamp](ue_ue.SoundWave.md#sourcefiletimestamp)
- [SpokenText](ue_ue.SoundWave.md#spokentext)
- [StreamingPriority](ue_ue.SoundWave.md#streamingpriority)
- [SubtitlePriority](ue_ue.SoundWave.md#subtitlepriority)
- [Subtitles](ue_ue.SoundWave.md#subtitles)
- [TotalSamples](ue_ue.SoundWave.md#totalsamples)
- [TreatFileAsLoopingForAnalysis](ue_ue.SoundWave.md#treatfileasloopingforanalysis)
- [VirtualizationMode](ue_ue.SoundWave.md#virtualizationmode)
- [Volume](ue_ue.SoundWave.md#volume)
- [\_\_tid\_Object\_\_](ue_ue.SoundWave.md#__tid_object__)
- [\_\_tid\_SoundBase\_\_](ue_ue.SoundWave.md#__tid_soundbase__)
- [\_\_tid\_SoundWave\_\_](ue_ue.SoundWave.md#__tid_soundwave__)
- [bBypassVolumeScaleForPriority](ue_ue.SoundWave.md#bbypassvolumescaleforpriority)
- [bDebug](ue_ue.SoundWave.md#bdebug)
- [bEnableAmplitudeEnvelopeAnalysis](ue_ue.SoundWave.md#benableamplitudeenvelopeanalysis)
- [bEnableBakedFFTAnalysis](ue_ue.SoundWave.md#benablebakedfftanalysis)
- [bHasConcatenatorNode](ue_ue.SoundWave.md#bhasconcatenatornode)
- [bHasDelayNode](ue_ue.SoundWave.md#bhasdelaynode)
- [bHasVirtualizeWhenSilent](ue_ue.SoundWave.md#bhasvirtualizewhensilent)
- [bIsAmbisonics](ue_ue.SoundWave.md#bisambisonics)
- [bLooping](ue_ue.SoundWave.md#blooping)
- [bManualWordWrap](ue_ue.SoundWave.md#bmanualwordwrap)
- [bMature](ue_ue.SoundWave.md#bmature)
- [bOutputToBusOnly](ue_ue.SoundWave.md#boutputtobusonly)
- [bOverrideConcurrency](ue_ue.SoundWave.md#boverrideconcurrency)
- [bSeekableStreaming](ue_ue.SoundWave.md#bseekablestreaming)
- [bSingleLine](ue_ue.SoundWave.md#bsingleline)
- [bStreaming](ue_ue.SoundWave.md#bstreaming)
- [bVirtualizeWhenSilent](ue_ue.SoundWave.md#bvirtualizewhensilent)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundWave.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundWave.md#executeubergraph)
- [GetClass](ue_ue.SoundWave.md#getclass)
- [GetName](ue_ue.SoundWave.md#getname)
- [GetOuter](ue_ue.SoundWave.md#getouter)
- [GetWorld](ue_ue.SoundWave.md#getworld)
- [Find](ue_ue.SoundWave.md#find)
- [Load](ue_ue.SoundWave.md#load)
- [StaticClass](ue_ue.SoundWave.md#staticclass)

## Constructors

### constructor

• **new SoundWave**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoundBase](ue_ue.SoundBase.md).[constructor](ue_ue.SoundBase.md#constructor)

#### Defined in

[ue/ue.d.ts:9552](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9552)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Defined in

[ue/ue.d.ts:9593](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9593)

___

### AttenuationSettings

• **AttenuationSettings**: [`SoundAttenuation`](ue_ue.SoundAttenuation.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[AttenuationSettings](ue_ue.SoundBase.md#attenuationsettings)

#### Defined in

[ue/ue.d.ts:9735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9735)

___

### BusSends

• **BusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[BusSends](ue_ue.SoundBase.md#bussends)

#### Defined in

[ue/ue.d.ts:9740](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9740)

___

### ChannelOffsets

• **ChannelOffsets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:9586](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9586)

___

### ChannelSizes

• **ChannelSizes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:9587](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9587)

___

### Comment

• **Comment**: `string`

#### Defined in

[ue/ue.d.ts:9590](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9590)

___

### CompressionQuality

• **CompressionQuality**: `number`

#### Defined in

[ue/ue.d.ts:9553](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9553)

___

### ConcurrencyOverrides

• **ConcurrencyOverrides**: [`SoundConcurrencySettings`](ue_ue.SoundConcurrencySettings.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[ConcurrencyOverrides](ue_ue.SoundBase.md#concurrencyoverrides)

#### Defined in

[ue/ue.d.ts:9729](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9729)

___

### ConcurrencySet

• **ConcurrencySet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`SoundConcurrency`](ue_ue.SoundConcurrency.md)\>

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[ConcurrencySet](ue_ue.SoundBase.md#concurrencyset)

#### Defined in

[ue/ue.d.ts:9728](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9728)

___

### CookedEnvelopeTimeData

• **CookedEnvelopeTimeData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundWaveEnvelopeTimeData`](ue_ue.SoundWaveEnvelopeTimeData.md)\>

#### Defined in

[ue/ue.d.ts:9579](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9579)

___

### CookedSpectralTimeData

• **CookedSpectralTimeData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundWaveSpectralTimeData`](ue_ue.SoundWaveSpectralTimeData.md)\>

#### Defined in

[ue/ue.d.ts:9578](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9578)

___

### Curves

• **Curves**: [`CurveTable`](ue_ue.CurveTable.md)

#### Defined in

[ue/ue.d.ts:9594](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9594)

___

### Duration

• **Duration**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[Duration](ue_ue.SoundBase.md#duration)

#### Defined in

[ue/ue.d.ts:9731](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9731)

___

### EnvelopeFollowerAttackTime

• **EnvelopeFollowerAttackTime**: `number`

#### Defined in

[ue/ue.d.ts:9575](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9575)

___

### EnvelopeFollowerFrameSize

• **EnvelopeFollowerFrameSize**: `number`

#### Defined in

[ue/ue.d.ts:9574](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9574)

___

### EnvelopeFollowerReleaseTime

• **EnvelopeFollowerReleaseTime**: `number`

#### Defined in

[ue/ue.d.ts:9576](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9576)

___

### FFTAnalysisAttackTime

• **FFTAnalysisAttackTime**: `number`

#### Defined in

[ue/ue.d.ts:9572](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9572)

___

### FFTAnalysisFrameSize

• **FFTAnalysisFrameSize**: `number`

#### Defined in

[ue/ue.d.ts:9571](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9571)

___

### FFTAnalysisReleaseTime

• **FFTAnalysisReleaseTime**: `number`

#### Defined in

[ue/ue.d.ts:9573](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9573)

___

### FFTSize

• **FFTSize**: [`ESoundWaveFFTSize`](../enums/ue_ue.ESoundWaveFFTSize.md)

#### Defined in

[ue/ue.d.ts:9570](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9570)

___

### FrequenciesToAnalyze

• **FrequenciesToAnalyze**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:9577](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9577)

___

### InitialChunkSize

• **InitialChunkSize**: `number`

#### Defined in

[ue/ue.d.ts:9580](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9580)

___

### InternalCurves

• **InternalCurves**: [`CurveTable`](ue_ue.CurveTable.md)

#### Defined in

[ue/ue.d.ts:9595](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9595)

___

### LoadingBehavior

• **LoadingBehavior**: [`ESoundWaveLoadingBehavior`](../enums/ue_ue.ESoundWaveLoadingBehavior.md)

#### Defined in

[ue/ue.d.ts:9560](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9560)

___

### MaxConcurrentPlayCount

• **MaxConcurrentPlayCount**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[MaxConcurrentPlayCount](ue_ue.SoundBase.md#maxconcurrentplaycount)

#### Defined in

[ue/ue.d.ts:9730](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9730)

___

### MaxConcurrentResolutionRule

• **MaxConcurrentResolutionRule**: [`EMaxConcurrentResolutionRule`](../enums/ue_ue.EMaxConcurrentResolutionRule.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[MaxConcurrentResolutionRule](ue_ue.SoundBase.md#maxconcurrentresolutionrule)

#### Defined in

[ue/ue.d.ts:9726](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9726)

___

### MaxDistance

• **MaxDistance**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[MaxDistance](ue_ue.SoundBase.md#maxdistance)

#### Defined in

[ue/ue.d.ts:9732](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9732)

___

### Modulation

• **Modulation**: [`SoundModulation`](ue_ue.SoundModulation.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[Modulation](ue_ue.SoundBase.md#modulation)

#### Defined in

[ue/ue.d.ts:9736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9736)

___

### NumChannels

• **NumChannels**: `number`

#### Defined in

[ue/ue.d.ts:9585](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9585)

___

### OverrideSoundToUseForAnalysis

• **OverrideSoundToUseForAnalysis**: [`SoundWave`](ue_ue.SoundWave.md)

#### Defined in

[ue/ue.d.ts:9566](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9566)

___

### Pitch

• **Pitch**: `number`

#### Defined in

[ue/ue.d.ts:9584](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9584)

___

### PreEffectBusSends

• **PreEffectBusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[PreEffectBusSends](ue_ue.SoundBase.md#preeffectbussends)

#### Defined in

[ue/ue.d.ts:9741](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9741)

___

### Priority

• **Priority**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[Priority](ue_ue.SoundBase.md#priority)

#### Defined in

[ue/ue.d.ts:9734](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9734)

___

### SampleRate

• **SampleRate**: `number`

#### Defined in

[ue/ue.d.ts:9588](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9588)

___

### SampleRateQuality

• **SampleRateQuality**: [`ESoundwaveSampleRateSettings`](../enums/ue_ue.ESoundwaveSampleRateSettings.md)

#### Defined in

[ue/ue.d.ts:9555](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9555)

___

### SoundClassObject

• **SoundClassObject**: [`SoundClass`](ue_ue.SoundClass.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SoundClassObject](ue_ue.SoundBase.md#soundclassobject)

#### Defined in

[ue/ue.d.ts:9717](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9717)

___

### SoundConcurrencySettings

• **SoundConcurrencySettings**: [`SoundConcurrency`](ue_ue.SoundConcurrency.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SoundConcurrencySettings](ue_ue.SoundBase.md#soundconcurrencysettings)

#### Defined in

[ue/ue.d.ts:9727](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9727)

___

### SoundGroup

• **SoundGroup**: [`ESoundGroup`](../enums/ue_ue.ESoundGroup.md)

#### Defined in

[ue/ue.d.ts:9556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9556)

___

### SoundSubmixObject

• **SoundSubmixObject**: [`SoundSubmix`](ue_ue.SoundSubmix.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SoundSubmixObject](ue_ue.SoundBase.md#soundsubmixobject)

#### Defined in

[ue/ue.d.ts:9737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9737)

___

### SoundSubmixSends

• **SoundSubmixSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSubmixSendInfo`](ue_ue.SoundSubmixSendInfo.md)\>

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SoundSubmixSends](ue_ue.SoundBase.md#soundsubmixsends)

#### Defined in

[ue/ue.d.ts:9738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9738)

___

### SourceEffectChain

• **SourceEffectChain**: [`SoundEffectSourcePresetChain`](ue_ue.SoundEffectSourcePresetChain.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SourceEffectChain](ue_ue.SoundBase.md#sourceeffectchain)

#### Defined in

[ue/ue.d.ts:9739](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9739)

___

### SourceFilePath

• **SourceFilePath**: `string`

#### Defined in

[ue/ue.d.ts:9591](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9591)

___

### SourceFileTimestamp

• **SourceFileTimestamp**: `string`

#### Defined in

[ue/ue.d.ts:9592](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9592)

___

### SpokenText

• **SpokenText**: `string`

#### Defined in

[ue/ue.d.ts:9581](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9581)

___

### StreamingPriority

• **StreamingPriority**: `number`

#### Defined in

[ue/ue.d.ts:9554](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9554)

___

### SubtitlePriority

• **SubtitlePriority**: `number`

#### Defined in

[ue/ue.d.ts:9582](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9582)

___

### Subtitles

• **Subtitles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SubtitleCue`](ue_ue.SubtitleCue.md)\>

#### Defined in

[ue/ue.d.ts:9589](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9589)

___

### TotalSamples

• **TotalSamples**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[TotalSamples](ue_ue.SoundBase.md#totalsamples)

#### Defined in

[ue/ue.d.ts:9733](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9733)

___

### TreatFileAsLoopingForAnalysis

• **TreatFileAsLoopingForAnalysis**: `boolean`

#### Defined in

[ue/ue.d.ts:9567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9567)

___

### VirtualizationMode

• **VirtualizationMode**: [`EVirtualizationMode`](../enums/ue_ue.EVirtualizationMode.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[VirtualizationMode](ue_ue.SoundBase.md#virtualizationmode)

#### Defined in

[ue/ue.d.ts:9725](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9725)

___

### Volume

• **Volume**: `number`

#### Defined in

[ue/ue.d.ts:9583](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9583)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[__tid_Object__](ue_ue.SoundBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_SoundBase\_\_

• **\_\_tid\_SoundBase\_\_**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[__tid_SoundBase__](ue_ue.SoundBase.md#__tid_soundbase__)

#### Defined in

[ue/ue.d.ts:9746](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9746)

___

### \_\_tid\_SoundWave\_\_

• **\_\_tid\_SoundWave\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:9600](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9600)

___

### bBypassVolumeScaleForPriority

• **bBypassVolumeScaleForPriority**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bBypassVolumeScaleForPriority](ue_ue.SoundBase.md#bbypassvolumescaleforpriority)

#### Defined in

[ue/ue.d.ts:9724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9724)

___

### bDebug

• **bDebug**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bDebug](ue_ue.SoundBase.md#bdebug)

#### Defined in

[ue/ue.d.ts:9718](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9718)

___

### bEnableAmplitudeEnvelopeAnalysis

• **bEnableAmplitudeEnvelopeAnalysis**: `boolean`

#### Defined in

[ue/ue.d.ts:9569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9569)

___

### bEnableBakedFFTAnalysis

• **bEnableBakedFFTAnalysis**: `boolean`

#### Defined in

[ue/ue.d.ts:9568](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9568)

___

### bHasConcatenatorNode

• **bHasConcatenatorNode**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bHasConcatenatorNode](ue_ue.SoundBase.md#bhasconcatenatornode)

#### Defined in

[ue/ue.d.ts:9722](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9722)

___

### bHasDelayNode

• **bHasDelayNode**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bHasDelayNode](ue_ue.SoundBase.md#bhasdelaynode)

#### Defined in

[ue/ue.d.ts:9721](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9721)

___

### bHasVirtualizeWhenSilent

• **bHasVirtualizeWhenSilent**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bHasVirtualizeWhenSilent](ue_ue.SoundBase.md#bhasvirtualizewhensilent)

#### Defined in

[ue/ue.d.ts:9723](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9723)

___

### bIsAmbisonics

• **bIsAmbisonics**: `boolean`

#### Defined in

[ue/ue.d.ts:9565](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9565)

___

### bLooping

• **bLooping**: `boolean`

#### Defined in

[ue/ue.d.ts:9557](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9557)

___

### bManualWordWrap

• **bManualWordWrap**: `boolean`

#### Defined in

[ue/ue.d.ts:9562](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9562)

___

### bMature

• **bMature**: `boolean`

#### Defined in

[ue/ue.d.ts:9561](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9561)

___

### bOutputToBusOnly

• **bOutputToBusOnly**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bOutputToBusOnly](ue_ue.SoundBase.md#boutputtobusonly)

#### Defined in

[ue/ue.d.ts:9720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9720)

___

### bOverrideConcurrency

• **bOverrideConcurrency**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bOverrideConcurrency](ue_ue.SoundBase.md#boverrideconcurrency)

#### Defined in

[ue/ue.d.ts:9719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9719)

___

### bSeekableStreaming

• **bSeekableStreaming**: `boolean`

#### Defined in

[ue/ue.d.ts:9559](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9559)

___

### bSingleLine

• **bSingleLine**: `boolean`

#### Defined in

[ue/ue.d.ts:9563](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9563)

___

### bStreaming

• **bStreaming**: `boolean`

#### Defined in

[ue/ue.d.ts:9558](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9558)

___

### bVirtualizeWhenSilent

• **bVirtualizeWhenSilent**: `boolean`

#### Defined in

[ue/ue.d.ts:9564](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9564)

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

[SoundBase](ue_ue.SoundBase.md).[CreateDefaultSubobject](ue_ue.SoundBase.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[SoundBase](ue_ue.SoundBase.md).[ExecuteUbergraph](ue_ue.SoundBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[GetClass](ue_ue.SoundBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[GetName](ue_ue.SoundBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[GetOuter](ue_ue.SoundBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[GetWorld](ue_ue.SoundBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundWave`](ue_ue.SoundWave.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundWave`](ue_ue.SoundWave.md)

#### Overrides

[SoundBase](ue_ue.SoundBase.md).[Find](ue_ue.SoundBase.md#find)

#### Defined in

[ue/ue.d.ts:9597](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9597)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundWave`](ue_ue.SoundWave.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundWave`](ue_ue.SoundWave.md)

#### Overrides

[SoundBase](ue_ue.SoundBase.md).[Load](ue_ue.SoundBase.md#load)

#### Defined in

[ue/ue.d.ts:9598](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9598)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundBase](ue_ue.SoundBase.md).[StaticClass](ue_ue.SoundBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:9596](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L9596)
