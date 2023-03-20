[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundBase

# Class: SoundBase

[ue/ue](../modules/ue_ue.md).SoundBase

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SoundBase`**

  ↳↳ [`SoundWave`](ue_ue.SoundWave.md)

  ↳↳ [`SoundCue`](ue_ue.SoundCue.md)

  ↳↳ [`DialogueSoundWaveProxy`](ue_ue.DialogueSoundWaveProxy.md)

## Table of contents

### Constructors

- [constructor](ue_ue.SoundBase.md#constructor)

### Properties

- [AttenuationSettings](ue_ue.SoundBase.md#attenuationsettings)
- [BusSends](ue_ue.SoundBase.md#bussends)
- [ConcurrencyOverrides](ue_ue.SoundBase.md#concurrencyoverrides)
- [ConcurrencySet](ue_ue.SoundBase.md#concurrencyset)
- [Duration](ue_ue.SoundBase.md#duration)
- [MaxConcurrentPlayCount](ue_ue.SoundBase.md#maxconcurrentplaycount)
- [MaxConcurrentResolutionRule](ue_ue.SoundBase.md#maxconcurrentresolutionrule)
- [MaxDistance](ue_ue.SoundBase.md#maxdistance)
- [Modulation](ue_ue.SoundBase.md#modulation)
- [PreEffectBusSends](ue_ue.SoundBase.md#preeffectbussends)
- [Priority](ue_ue.SoundBase.md#priority)
- [SoundClassObject](ue_ue.SoundBase.md#soundclassobject)
- [SoundConcurrencySettings](ue_ue.SoundBase.md#soundconcurrencysettings)
- [SoundSubmixObject](ue_ue.SoundBase.md#soundsubmixobject)
- [SoundSubmixSends](ue_ue.SoundBase.md#soundsubmixsends)
- [SourceEffectChain](ue_ue.SoundBase.md#sourceeffectchain)
- [TotalSamples](ue_ue.SoundBase.md#totalsamples)
- [VirtualizationMode](ue_ue.SoundBase.md#virtualizationmode)
- [\_\_tid\_Object\_\_](ue_ue.SoundBase.md#__tid_object__)
- [\_\_tid\_SoundBase\_\_](ue_ue.SoundBase.md#__tid_soundbase__)
- [bBypassVolumeScaleForPriority](ue_ue.SoundBase.md#bbypassvolumescaleforpriority)
- [bDebug](ue_ue.SoundBase.md#bdebug)
- [bHasConcatenatorNode](ue_ue.SoundBase.md#bhasconcatenatornode)
- [bHasDelayNode](ue_ue.SoundBase.md#bhasdelaynode)
- [bHasVirtualizeWhenSilent](ue_ue.SoundBase.md#bhasvirtualizewhensilent)
- [bOutputToBusOnly](ue_ue.SoundBase.md#boutputtobusonly)
- [bOverrideConcurrency](ue_ue.SoundBase.md#boverrideconcurrency)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundBase.md#executeubergraph)
- [GetClass](ue_ue.SoundBase.md#getclass)
- [GetName](ue_ue.SoundBase.md#getname)
- [GetOuter](ue_ue.SoundBase.md#getouter)
- [GetWorld](ue_ue.SoundBase.md#getworld)
- [Find](ue_ue.SoundBase.md#find)
- [Load](ue_ue.SoundBase.md#load)
- [StaticClass](ue_ue.SoundBase.md#staticclass)

## Constructors

### constructor

• **new SoundBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AttenuationSettings

• **AttenuationSettings**: [`SoundAttenuation`](ue_ue.SoundAttenuation.md)

___

### BusSends

• **BusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

___

### ConcurrencyOverrides

• **ConcurrencyOverrides**: [`SoundConcurrencySettings`](ue_ue.SoundConcurrencySettings.md)

___

### ConcurrencySet

• **ConcurrencySet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`SoundConcurrency`](ue_ue.SoundConcurrency.md)\>

___

### Duration

• **Duration**: `number`

___

### MaxConcurrentPlayCount

• **MaxConcurrentPlayCount**: `number`

___

### MaxConcurrentResolutionRule

• **MaxConcurrentResolutionRule**: [`EMaxConcurrentResolutionRule`](../enums/ue_ue.EMaxConcurrentResolutionRule.md)

___

### MaxDistance

• **MaxDistance**: `number`

___

### Modulation

• **Modulation**: [`SoundModulation`](ue_ue.SoundModulation.md)

___

### PreEffectBusSends

• **PreEffectBusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

___

### Priority

• **Priority**: `number`

___

### SoundClassObject

• **SoundClassObject**: [`SoundClass`](ue_ue.SoundClass.md)

___

### SoundConcurrencySettings

• **SoundConcurrencySettings**: [`SoundConcurrency`](ue_ue.SoundConcurrency.md)

___

### SoundSubmixObject

• **SoundSubmixObject**: [`SoundSubmix`](ue_ue.SoundSubmix.md)

___

### SoundSubmixSends

• **SoundSubmixSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSubmixSendInfo`](ue_ue.SoundSubmixSendInfo.md)\>

___

### SourceEffectChain

• **SourceEffectChain**: [`SoundEffectSourcePresetChain`](ue_ue.SoundEffectSourcePresetChain.md)

___

### TotalSamples

• **TotalSamples**: `number`

___

### VirtualizationMode

• **VirtualizationMode**: [`EVirtualizationMode`](../enums/ue_ue.EVirtualizationMode.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_SoundBase\_\_

• **\_\_tid\_SoundBase\_\_**: `boolean`

___

### bBypassVolumeScaleForPriority

• **bBypassVolumeScaleForPriority**: `boolean`

___

### bDebug

• **bDebug**: `boolean`

___

### bHasConcatenatorNode

• **bHasConcatenatorNode**: `boolean`

___

### bHasDelayNode

• **bHasDelayNode**: `boolean`

___

### bHasVirtualizeWhenSilent

• **bHasVirtualizeWhenSilent**: `boolean`

___

### bOutputToBusOnly

• **bOutputToBusOnly**: `boolean`

___

### bOverrideConcurrency

• **bOverrideConcurrency**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundBase`](ue_ue.SoundBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundBase`](ue_ue.SoundBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundBase`](ue_ue.SoundBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundBase`](ue_ue.SoundBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
