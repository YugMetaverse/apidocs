[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundCue

# Class: SoundCue

[ue/ue](../modules/ue_ue.md).SoundCue

## Hierarchy

- [`SoundBase`](ue_ue.SoundBase.md)

  ↳ **`SoundCue`**

  ↳↳ [`SoundCueTemplate`](ue_ue.SoundCueTemplate.md)

## Table of contents

### Constructors

- [constructor](ue_ue.SoundCue.md#constructor)

### Properties

- [AllNodes](ue_ue.SoundCue.md#allnodes)
- [AttenuationOverrides](ue_ue.SoundCue.md#attenuationoverrides)
- [AttenuationSettings](ue_ue.SoundCue.md#attenuationsettings)
- [BusSends](ue_ue.SoundCue.md#bussends)
- [ConcurrencyOverrides](ue_ue.SoundCue.md#concurrencyoverrides)
- [ConcurrencySet](ue_ue.SoundCue.md#concurrencyset)
- [Duration](ue_ue.SoundCue.md#duration)
- [FirstNode](ue_ue.SoundCue.md#firstnode)
- [MaxConcurrentPlayCount](ue_ue.SoundCue.md#maxconcurrentplaycount)
- [MaxConcurrentResolutionRule](ue_ue.SoundCue.md#maxconcurrentresolutionrule)
- [MaxDistance](ue_ue.SoundCue.md#maxdistance)
- [Modulation](ue_ue.SoundCue.md#modulation)
- [PitchMultiplier](ue_ue.SoundCue.md#pitchmultiplier)
- [PreEffectBusSends](ue_ue.SoundCue.md#preeffectbussends)
- [Priority](ue_ue.SoundCue.md#priority)
- [SoundClassObject](ue_ue.SoundCue.md#soundclassobject)
- [SoundConcurrencySettings](ue_ue.SoundCue.md#soundconcurrencysettings)
- [SoundCueGraph](ue_ue.SoundCue.md#soundcuegraph)
- [SoundSubmixObject](ue_ue.SoundCue.md#soundsubmixobject)
- [SoundSubmixSends](ue_ue.SoundCue.md#soundsubmixsends)
- [SourceEffectChain](ue_ue.SoundCue.md#sourceeffectchain)
- [SubtitlePriority](ue_ue.SoundCue.md#subtitlepriority)
- [TotalSamples](ue_ue.SoundCue.md#totalsamples)
- [VirtualizationMode](ue_ue.SoundCue.md#virtualizationmode)
- [VolumeMultiplier](ue_ue.SoundCue.md#volumemultiplier)
- [\_\_tid\_Object\_\_](ue_ue.SoundCue.md#__tid_object__)
- [\_\_tid\_SoundBase\_\_](ue_ue.SoundCue.md#__tid_soundbase__)
- [\_\_tid\_SoundCue\_\_](ue_ue.SoundCue.md#__tid_soundcue__)
- [bBypassVolumeScaleForPriority](ue_ue.SoundCue.md#bbypassvolumescaleforpriority)
- [bDebug](ue_ue.SoundCue.md#bdebug)
- [bExcludeFromRandomNodeBranchCulling](ue_ue.SoundCue.md#bexcludefromrandomnodebranchculling)
- [bHasConcatenatorNode](ue_ue.SoundCue.md#bhasconcatenatornode)
- [bHasDelayNode](ue_ue.SoundCue.md#bhasdelaynode)
- [bHasPlayWhenSilent](ue_ue.SoundCue.md#bhasplaywhensilent)
- [bHasVirtualizeWhenSilent](ue_ue.SoundCue.md#bhasvirtualizewhensilent)
- [bOutputToBusOnly](ue_ue.SoundCue.md#boutputtobusonly)
- [bOverrideAttenuation](ue_ue.SoundCue.md#boverrideattenuation)
- [bOverrideConcurrency](ue_ue.SoundCue.md#boverrideconcurrency)
- [bPrimeOnLoad](ue_ue.SoundCue.md#bprimeonload)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundCue.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundCue.md#executeubergraph)
- [GetClass](ue_ue.SoundCue.md#getclass)
- [GetName](ue_ue.SoundCue.md#getname)
- [GetOuter](ue_ue.SoundCue.md#getouter)
- [GetWorld](ue_ue.SoundCue.md#getworld)
- [Find](ue_ue.SoundCue.md#find)
- [Load](ue_ue.SoundCue.md#load)
- [StaticClass](ue_ue.SoundCue.md#staticclass)

## Constructors

### constructor

• **new SoundCue**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoundBase](ue_ue.SoundBase.md).[constructor](ue_ue.SoundBase.md#constructor)

## Properties

### AllNodes

• **AllNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundNode`](ue_ue.SoundNode.md)\>

___

### AttenuationOverrides

• **AttenuationOverrides**: [`SoundAttenuationSettings`](ue_ue.SoundAttenuationSettings.md)

___

### AttenuationSettings

• **AttenuationSettings**: [`SoundAttenuation`](ue_ue.SoundAttenuation.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[AttenuationSettings](ue_ue.SoundBase.md#attenuationsettings)

___

### BusSends

• **BusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[BusSends](ue_ue.SoundBase.md#bussends)

___

### ConcurrencyOverrides

• **ConcurrencyOverrides**: [`SoundConcurrencySettings`](ue_ue.SoundConcurrencySettings.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[ConcurrencyOverrides](ue_ue.SoundBase.md#concurrencyoverrides)

___

### ConcurrencySet

• **ConcurrencySet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`SoundConcurrency`](ue_ue.SoundConcurrency.md)\>

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[ConcurrencySet](ue_ue.SoundBase.md#concurrencyset)

___

### Duration

• **Duration**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[Duration](ue_ue.SoundBase.md#duration)

___

### FirstNode

• **FirstNode**: [`SoundNode`](ue_ue.SoundNode.md)

___

### MaxConcurrentPlayCount

• **MaxConcurrentPlayCount**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[MaxConcurrentPlayCount](ue_ue.SoundBase.md#maxconcurrentplaycount)

___

### MaxConcurrentResolutionRule

• **MaxConcurrentResolutionRule**: [`EMaxConcurrentResolutionRule`](../enums/ue_ue.EMaxConcurrentResolutionRule.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[MaxConcurrentResolutionRule](ue_ue.SoundBase.md#maxconcurrentresolutionrule)

___

### MaxDistance

• **MaxDistance**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[MaxDistance](ue_ue.SoundBase.md#maxdistance)

___

### Modulation

• **Modulation**: [`SoundModulation`](ue_ue.SoundModulation.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[Modulation](ue_ue.SoundBase.md#modulation)

___

### PitchMultiplier

• **PitchMultiplier**: `number`

___

### PreEffectBusSends

• **PreEffectBusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[PreEffectBusSends](ue_ue.SoundBase.md#preeffectbussends)

___

### Priority

• **Priority**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[Priority](ue_ue.SoundBase.md#priority)

___

### SoundClassObject

• **SoundClassObject**: [`SoundClass`](ue_ue.SoundClass.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SoundClassObject](ue_ue.SoundBase.md#soundclassobject)

___

### SoundConcurrencySettings

• **SoundConcurrencySettings**: [`SoundConcurrency`](ue_ue.SoundConcurrency.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SoundConcurrencySettings](ue_ue.SoundBase.md#soundconcurrencysettings)

___

### SoundCueGraph

• **SoundCueGraph**: [`EdGraph`](ue_ue.EdGraph.md)

___

### SoundSubmixObject

• **SoundSubmixObject**: [`SoundSubmix`](ue_ue.SoundSubmix.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SoundSubmixObject](ue_ue.SoundBase.md#soundsubmixobject)

___

### SoundSubmixSends

• **SoundSubmixSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSubmixSendInfo`](ue_ue.SoundSubmixSendInfo.md)\>

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SoundSubmixSends](ue_ue.SoundBase.md#soundsubmixsends)

___

### SourceEffectChain

• **SourceEffectChain**: [`SoundEffectSourcePresetChain`](ue_ue.SoundEffectSourcePresetChain.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SourceEffectChain](ue_ue.SoundBase.md#sourceeffectchain)

___

### SubtitlePriority

• **SubtitlePriority**: `number`

___

### TotalSamples

• **TotalSamples**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[TotalSamples](ue_ue.SoundBase.md#totalsamples)

___

### VirtualizationMode

• **VirtualizationMode**: [`EVirtualizationMode`](../enums/ue_ue.EVirtualizationMode.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[VirtualizationMode](ue_ue.SoundBase.md#virtualizationmode)

___

### VolumeMultiplier

• **VolumeMultiplier**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[__tid_Object__](ue_ue.SoundBase.md#__tid_object__)

___

### \_\_tid\_SoundBase\_\_

• **\_\_tid\_SoundBase\_\_**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[__tid_SoundBase__](ue_ue.SoundBase.md#__tid_soundbase__)

___

### \_\_tid\_SoundCue\_\_

• **\_\_tid\_SoundCue\_\_**: `boolean`

___

### bBypassVolumeScaleForPriority

• **bBypassVolumeScaleForPriority**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bBypassVolumeScaleForPriority](ue_ue.SoundBase.md#bbypassvolumescaleforpriority)

___

### bDebug

• **bDebug**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bDebug](ue_ue.SoundBase.md#bdebug)

___

### bExcludeFromRandomNodeBranchCulling

• **bExcludeFromRandomNodeBranchCulling**: `boolean`

___

### bHasConcatenatorNode

• **bHasConcatenatorNode**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bHasConcatenatorNode](ue_ue.SoundBase.md#bhasconcatenatornode)

___

### bHasDelayNode

• **bHasDelayNode**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bHasDelayNode](ue_ue.SoundBase.md#bhasdelaynode)

___

### bHasPlayWhenSilent

• **bHasPlayWhenSilent**: `boolean`

___

### bHasVirtualizeWhenSilent

• **bHasVirtualizeWhenSilent**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bHasVirtualizeWhenSilent](ue_ue.SoundBase.md#bhasvirtualizewhensilent)

___

### bOutputToBusOnly

• **bOutputToBusOnly**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bOutputToBusOnly](ue_ue.SoundBase.md#boutputtobusonly)

___

### bOverrideAttenuation

• **bOverrideAttenuation**: `boolean`

___

### bOverrideConcurrency

• **bOverrideConcurrency**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bOverrideConcurrency](ue_ue.SoundBase.md#boverrideconcurrency)

___

### bPrimeOnLoad

• **bPrimeOnLoad**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[GetClass](ue_ue.SoundBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[GetName](ue_ue.SoundBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[GetOuter](ue_ue.SoundBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[GetWorld](ue_ue.SoundBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundCue`](ue_ue.SoundCue.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundCue`](ue_ue.SoundCue.md)

#### Overrides

[SoundBase](ue_ue.SoundBase.md).[Find](ue_ue.SoundBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundCue`](ue_ue.SoundCue.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundCue`](ue_ue.SoundCue.md)

#### Overrides

[SoundBase](ue_ue.SoundBase.md).[Load](ue_ue.SoundBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundBase](ue_ue.SoundBase.md).[StaticClass](ue_ue.SoundBase.md#staticclass)
