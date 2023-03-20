[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundCueTemplate

# Class: SoundCueTemplate

[ue/ue](../modules/ue_ue.md).SoundCueTemplate

## Hierarchy

- [`SoundCue`](ue_ue.SoundCue.md)

  ↳ **`SoundCueTemplate`**

## Table of contents

### Constructors

- [constructor](ue_ue.SoundCueTemplate.md#constructor)

### Properties

- [AllNodes](ue_ue.SoundCueTemplate.md#allnodes)
- [AttenuationOverrides](ue_ue.SoundCueTemplate.md#attenuationoverrides)
- [AttenuationSettings](ue_ue.SoundCueTemplate.md#attenuationsettings)
- [BusSends](ue_ue.SoundCueTemplate.md#bussends)
- [ConcurrencyOverrides](ue_ue.SoundCueTemplate.md#concurrencyoverrides)
- [ConcurrencySet](ue_ue.SoundCueTemplate.md#concurrencyset)
- [Duration](ue_ue.SoundCueTemplate.md#duration)
- [FirstNode](ue_ue.SoundCueTemplate.md#firstnode)
- [MaxConcurrentPlayCount](ue_ue.SoundCueTemplate.md#maxconcurrentplaycount)
- [MaxConcurrentResolutionRule](ue_ue.SoundCueTemplate.md#maxconcurrentresolutionrule)
- [MaxDistance](ue_ue.SoundCueTemplate.md#maxdistance)
- [Modulation](ue_ue.SoundCueTemplate.md#modulation)
- [PitchMultiplier](ue_ue.SoundCueTemplate.md#pitchmultiplier)
- [PreEffectBusSends](ue_ue.SoundCueTemplate.md#preeffectbussends)
- [Priority](ue_ue.SoundCueTemplate.md#priority)
- [SoundClassObject](ue_ue.SoundCueTemplate.md#soundclassobject)
- [SoundConcurrencySettings](ue_ue.SoundCueTemplate.md#soundconcurrencysettings)
- [SoundCueGraph](ue_ue.SoundCueTemplate.md#soundcuegraph)
- [SoundSubmixObject](ue_ue.SoundCueTemplate.md#soundsubmixobject)
- [SoundSubmixSends](ue_ue.SoundCueTemplate.md#soundsubmixsends)
- [SourceEffectChain](ue_ue.SoundCueTemplate.md#sourceeffectchain)
- [SubtitlePriority](ue_ue.SoundCueTemplate.md#subtitlepriority)
- [TotalSamples](ue_ue.SoundCueTemplate.md#totalsamples)
- [VirtualizationMode](ue_ue.SoundCueTemplate.md#virtualizationmode)
- [VolumeMultiplier](ue_ue.SoundCueTemplate.md#volumemultiplier)
- [\_\_tid\_Object\_\_](ue_ue.SoundCueTemplate.md#__tid_object__)
- [\_\_tid\_SoundBase\_\_](ue_ue.SoundCueTemplate.md#__tid_soundbase__)
- [\_\_tid\_SoundCueTemplate\_\_](ue_ue.SoundCueTemplate.md#__tid_soundcuetemplate__)
- [\_\_tid\_SoundCue\_\_](ue_ue.SoundCueTemplate.md#__tid_soundcue__)
- [bBypassVolumeScaleForPriority](ue_ue.SoundCueTemplate.md#bbypassvolumescaleforpriority)
- [bDebug](ue_ue.SoundCueTemplate.md#bdebug)
- [bExcludeFromRandomNodeBranchCulling](ue_ue.SoundCueTemplate.md#bexcludefromrandomnodebranchculling)
- [bHasConcatenatorNode](ue_ue.SoundCueTemplate.md#bhasconcatenatornode)
- [bHasDelayNode](ue_ue.SoundCueTemplate.md#bhasdelaynode)
- [bHasPlayWhenSilent](ue_ue.SoundCueTemplate.md#bhasplaywhensilent)
- [bHasVirtualizeWhenSilent](ue_ue.SoundCueTemplate.md#bhasvirtualizewhensilent)
- [bOutputToBusOnly](ue_ue.SoundCueTemplate.md#boutputtobusonly)
- [bOverrideAttenuation](ue_ue.SoundCueTemplate.md#boverrideattenuation)
- [bOverrideConcurrency](ue_ue.SoundCueTemplate.md#boverrideconcurrency)
- [bPrimeOnLoad](ue_ue.SoundCueTemplate.md#bprimeonload)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundCueTemplate.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundCueTemplate.md#executeubergraph)
- [GetClass](ue_ue.SoundCueTemplate.md#getclass)
- [GetName](ue_ue.SoundCueTemplate.md#getname)
- [GetOuter](ue_ue.SoundCueTemplate.md#getouter)
- [GetWorld](ue_ue.SoundCueTemplate.md#getworld)
- [Find](ue_ue.SoundCueTemplate.md#find)
- [Load](ue_ue.SoundCueTemplate.md#load)
- [StaticClass](ue_ue.SoundCueTemplate.md#staticclass)

## Constructors

### constructor

• **new SoundCueTemplate**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoundCue](ue_ue.SoundCue.md).[constructor](ue_ue.SoundCue.md#constructor)

#### Defined in

[ue/ue.d.ts:61205](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61205)

## Properties

### AllNodes

• **AllNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundNode`](ue_ue.SoundNode.md)\>

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[AllNodes](ue_ue.SoundCue.md#allnodes)

#### Defined in

[ue/ue.d.ts:22414](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22414)

___

### AttenuationOverrides

• **AttenuationOverrides**: [`SoundAttenuationSettings`](ue_ue.SoundAttenuationSettings.md)

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[AttenuationOverrides](ue_ue.SoundCue.md#attenuationoverrides)

#### Defined in

[ue/ue.d.ts:22413](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22413)

___

### AttenuationSettings

• **AttenuationSettings**: [`SoundAttenuation`](ue_ue.SoundAttenuation.md)

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[AttenuationSettings](ue_ue.SoundCue.md#attenuationsettings)

#### Defined in

[ue/ue.d.ts:9735](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9735)

___

### BusSends

• **BusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[BusSends](ue_ue.SoundCue.md#bussends)

#### Defined in

[ue/ue.d.ts:9740](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9740)

___

### ConcurrencyOverrides

• **ConcurrencyOverrides**: [`SoundConcurrencySettings`](ue_ue.SoundConcurrencySettings.md)

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[ConcurrencyOverrides](ue_ue.SoundCue.md#concurrencyoverrides)

#### Defined in

[ue/ue.d.ts:9729](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9729)

___

### ConcurrencySet

• **ConcurrencySet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`SoundConcurrency`](ue_ue.SoundConcurrency.md)\>

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[ConcurrencySet](ue_ue.SoundCue.md#concurrencyset)

#### Defined in

[ue/ue.d.ts:9728](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9728)

___

### Duration

• **Duration**: `number`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[Duration](ue_ue.SoundCue.md#duration)

#### Defined in

[ue/ue.d.ts:9731](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9731)

___

### FirstNode

• **FirstNode**: [`SoundNode`](ue_ue.SoundNode.md)

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[FirstNode](ue_ue.SoundCue.md#firstnode)

#### Defined in

[ue/ue.d.ts:22410](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22410)

___

### MaxConcurrentPlayCount

• **MaxConcurrentPlayCount**: `number`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[MaxConcurrentPlayCount](ue_ue.SoundCue.md#maxconcurrentplaycount)

#### Defined in

[ue/ue.d.ts:9730](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9730)

___

### MaxConcurrentResolutionRule

• **MaxConcurrentResolutionRule**: [`EMaxConcurrentResolutionRule`](../enums/ue_ue.EMaxConcurrentResolutionRule.md)

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[MaxConcurrentResolutionRule](ue_ue.SoundCue.md#maxconcurrentresolutionrule)

#### Defined in

[ue/ue.d.ts:9726](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9726)

___

### MaxDistance

• **MaxDistance**: `number`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[MaxDistance](ue_ue.SoundCue.md#maxdistance)

#### Defined in

[ue/ue.d.ts:9732](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9732)

___

### Modulation

• **Modulation**: [`SoundModulation`](ue_ue.SoundModulation.md)

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[Modulation](ue_ue.SoundCue.md#modulation)

#### Defined in

[ue/ue.d.ts:9736](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9736)

___

### PitchMultiplier

• **PitchMultiplier**: `number`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[PitchMultiplier](ue_ue.SoundCue.md#pitchmultiplier)

#### Defined in

[ue/ue.d.ts:22412](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22412)

___

### PreEffectBusSends

• **PreEffectBusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[PreEffectBusSends](ue_ue.SoundCue.md#preeffectbussends)

#### Defined in

[ue/ue.d.ts:9741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9741)

___

### Priority

• **Priority**: `number`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[Priority](ue_ue.SoundCue.md#priority)

#### Defined in

[ue/ue.d.ts:9734](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9734)

___

### SoundClassObject

• **SoundClassObject**: [`SoundClass`](ue_ue.SoundClass.md)

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[SoundClassObject](ue_ue.SoundCue.md#soundclassobject)

#### Defined in

[ue/ue.d.ts:9717](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9717)

___

### SoundConcurrencySettings

• **SoundConcurrencySettings**: [`SoundConcurrency`](ue_ue.SoundConcurrency.md)

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[SoundConcurrencySettings](ue_ue.SoundCue.md#soundconcurrencysettings)

#### Defined in

[ue/ue.d.ts:9727](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9727)

___

### SoundCueGraph

• **SoundCueGraph**: [`EdGraph`](ue_ue.EdGraph.md)

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[SoundCueGraph](ue_ue.SoundCue.md#soundcuegraph)

#### Defined in

[ue/ue.d.ts:22415](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22415)

___

### SoundSubmixObject

• **SoundSubmixObject**: [`SoundSubmix`](ue_ue.SoundSubmix.md)

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[SoundSubmixObject](ue_ue.SoundCue.md#soundsubmixobject)

#### Defined in

[ue/ue.d.ts:9737](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9737)

___

### SoundSubmixSends

• **SoundSubmixSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSubmixSendInfo`](ue_ue.SoundSubmixSendInfo.md)\>

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[SoundSubmixSends](ue_ue.SoundCue.md#soundsubmixsends)

#### Defined in

[ue/ue.d.ts:9738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9738)

___

### SourceEffectChain

• **SourceEffectChain**: [`SoundEffectSourcePresetChain`](ue_ue.SoundEffectSourcePresetChain.md)

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[SourceEffectChain](ue_ue.SoundCue.md#sourceeffectchain)

#### Defined in

[ue/ue.d.ts:9739](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9739)

___

### SubtitlePriority

• **SubtitlePriority**: `number`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[SubtitlePriority](ue_ue.SoundCue.md#subtitlepriority)

#### Defined in

[ue/ue.d.ts:22416](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22416)

___

### TotalSamples

• **TotalSamples**: `number`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[TotalSamples](ue_ue.SoundCue.md#totalsamples)

#### Defined in

[ue/ue.d.ts:9733](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9733)

___

### VirtualizationMode

• **VirtualizationMode**: [`EVirtualizationMode`](../enums/ue_ue.EVirtualizationMode.md)

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[VirtualizationMode](ue_ue.SoundCue.md#virtualizationmode)

#### Defined in

[ue/ue.d.ts:9725](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9725)

___

### VolumeMultiplier

• **VolumeMultiplier**: `number`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[VolumeMultiplier](ue_ue.SoundCue.md#volumemultiplier)

#### Defined in

[ue/ue.d.ts:22411](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22411)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[__tid_Object__](ue_ue.SoundCue.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SoundBase\_\_

• **\_\_tid\_SoundBase\_\_**: `boolean`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[__tid_SoundBase__](ue_ue.SoundCue.md#__tid_soundbase__)

#### Defined in

[ue/ue.d.ts:9746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9746)

___

### \_\_tid\_SoundCueTemplate\_\_

• **\_\_tid\_SoundCueTemplate\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:61210](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61210)

___

### \_\_tid\_SoundCue\_\_

• **\_\_tid\_SoundCue\_\_**: `boolean`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[__tid_SoundCue__](ue_ue.SoundCue.md#__tid_soundcue__)

#### Defined in

[ue/ue.d.ts:22424](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22424)

___

### bBypassVolumeScaleForPriority

• **bBypassVolumeScaleForPriority**: `boolean`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[bBypassVolumeScaleForPriority](ue_ue.SoundCue.md#bbypassvolumescaleforpriority)

#### Defined in

[ue/ue.d.ts:9724](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9724)

___

### bDebug

• **bDebug**: `boolean`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[bDebug](ue_ue.SoundCue.md#bdebug)

#### Defined in

[ue/ue.d.ts:9718](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9718)

___

### bExcludeFromRandomNodeBranchCulling

• **bExcludeFromRandomNodeBranchCulling**: `boolean`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[bExcludeFromRandomNodeBranchCulling](ue_ue.SoundCue.md#bexcludefromrandomnodebranchculling)

#### Defined in

[ue/ue.d.ts:22418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22418)

___

### bHasConcatenatorNode

• **bHasConcatenatorNode**: `boolean`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[bHasConcatenatorNode](ue_ue.SoundCue.md#bhasconcatenatornode)

#### Defined in

[ue/ue.d.ts:9722](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9722)

___

### bHasDelayNode

• **bHasDelayNode**: `boolean`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[bHasDelayNode](ue_ue.SoundCue.md#bhasdelaynode)

#### Defined in

[ue/ue.d.ts:9721](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9721)

___

### bHasPlayWhenSilent

• **bHasPlayWhenSilent**: `boolean`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[bHasPlayWhenSilent](ue_ue.SoundCue.md#bhasplaywhensilent)

#### Defined in

[ue/ue.d.ts:22419](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22419)

___

### bHasVirtualizeWhenSilent

• **bHasVirtualizeWhenSilent**: `boolean`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[bHasVirtualizeWhenSilent](ue_ue.SoundCue.md#bhasvirtualizewhensilent)

#### Defined in

[ue/ue.d.ts:9723](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9723)

___

### bOutputToBusOnly

• **bOutputToBusOnly**: `boolean`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[bOutputToBusOnly](ue_ue.SoundCue.md#boutputtobusonly)

#### Defined in

[ue/ue.d.ts:9720](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9720)

___

### bOverrideAttenuation

• **bOverrideAttenuation**: `boolean`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[bOverrideAttenuation](ue_ue.SoundCue.md#boverrideattenuation)

#### Defined in

[ue/ue.d.ts:22417](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22417)

___

### bOverrideConcurrency

• **bOverrideConcurrency**: `boolean`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[bOverrideConcurrency](ue_ue.SoundCue.md#boverrideconcurrency)

#### Defined in

[ue/ue.d.ts:9719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9719)

___

### bPrimeOnLoad

• **bPrimeOnLoad**: `boolean`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[bPrimeOnLoad](ue_ue.SoundCue.md#bprimeonload)

#### Defined in

[ue/ue.d.ts:22409](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22409)

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

[SoundCue](ue_ue.SoundCue.md).[CreateDefaultSubobject](ue_ue.SoundCue.md#createdefaultsubobject)

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

[SoundCue](ue_ue.SoundCue.md).[ExecuteUbergraph](ue_ue.SoundCue.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[GetClass](ue_ue.SoundCue.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[GetName](ue_ue.SoundCue.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[GetOuter](ue_ue.SoundCue.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundCue](ue_ue.SoundCue.md).[GetWorld](ue_ue.SoundCue.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundCueTemplate`](ue_ue.SoundCueTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundCueTemplate`](ue_ue.SoundCueTemplate.md)

#### Overrides

[SoundCue](ue_ue.SoundCue.md).[Find](ue_ue.SoundCue.md#find)

#### Defined in

[ue/ue.d.ts:61207](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61207)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundCueTemplate`](ue_ue.SoundCueTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundCueTemplate`](ue_ue.SoundCueTemplate.md)

#### Overrides

[SoundCue](ue_ue.SoundCue.md).[Load](ue_ue.SoundCue.md#load)

#### Defined in

[ue/ue.d.ts:61208](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61208)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundCue](ue_ue.SoundCue.md).[StaticClass](ue_ue.SoundCue.md#staticclass)

#### Defined in

[ue/ue.d.ts:61206](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L61206)
