[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DialogueSoundWaveProxy

# Class: DialogueSoundWaveProxy

[ue/ue](../modules/ue_ue.md).DialogueSoundWaveProxy

## Hierarchy

- [`SoundBase`](ue_ue.SoundBase.md)

  ↳ **`DialogueSoundWaveProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.DialogueSoundWaveProxy.md#constructor)

### Properties

- [AttenuationSettings](ue_ue.DialogueSoundWaveProxy.md#attenuationsettings)
- [BusSends](ue_ue.DialogueSoundWaveProxy.md#bussends)
- [ConcurrencyOverrides](ue_ue.DialogueSoundWaveProxy.md#concurrencyoverrides)
- [ConcurrencySet](ue_ue.DialogueSoundWaveProxy.md#concurrencyset)
- [Duration](ue_ue.DialogueSoundWaveProxy.md#duration)
- [MaxConcurrentPlayCount](ue_ue.DialogueSoundWaveProxy.md#maxconcurrentplaycount)
- [MaxConcurrentResolutionRule](ue_ue.DialogueSoundWaveProxy.md#maxconcurrentresolutionrule)
- [MaxDistance](ue_ue.DialogueSoundWaveProxy.md#maxdistance)
- [Modulation](ue_ue.DialogueSoundWaveProxy.md#modulation)
- [PreEffectBusSends](ue_ue.DialogueSoundWaveProxy.md#preeffectbussends)
- [Priority](ue_ue.DialogueSoundWaveProxy.md#priority)
- [SoundClassObject](ue_ue.DialogueSoundWaveProxy.md#soundclassobject)
- [SoundConcurrencySettings](ue_ue.DialogueSoundWaveProxy.md#soundconcurrencysettings)
- [SoundSubmixObject](ue_ue.DialogueSoundWaveProxy.md#soundsubmixobject)
- [SoundSubmixSends](ue_ue.DialogueSoundWaveProxy.md#soundsubmixsends)
- [SourceEffectChain](ue_ue.DialogueSoundWaveProxy.md#sourceeffectchain)
- [TotalSamples](ue_ue.DialogueSoundWaveProxy.md#totalsamples)
- [VirtualizationMode](ue_ue.DialogueSoundWaveProxy.md#virtualizationmode)
- [\_\_tid\_DialogueSoundWaveProxy\_\_](ue_ue.DialogueSoundWaveProxy.md#__tid_dialoguesoundwaveproxy__)
- [\_\_tid\_Object\_\_](ue_ue.DialogueSoundWaveProxy.md#__tid_object__)
- [\_\_tid\_SoundBase\_\_](ue_ue.DialogueSoundWaveProxy.md#__tid_soundbase__)
- [bBypassVolumeScaleForPriority](ue_ue.DialogueSoundWaveProxy.md#bbypassvolumescaleforpriority)
- [bDebug](ue_ue.DialogueSoundWaveProxy.md#bdebug)
- [bHasConcatenatorNode](ue_ue.DialogueSoundWaveProxy.md#bhasconcatenatornode)
- [bHasDelayNode](ue_ue.DialogueSoundWaveProxy.md#bhasdelaynode)
- [bHasVirtualizeWhenSilent](ue_ue.DialogueSoundWaveProxy.md#bhasvirtualizewhensilent)
- [bOutputToBusOnly](ue_ue.DialogueSoundWaveProxy.md#boutputtobusonly)
- [bOverrideConcurrency](ue_ue.DialogueSoundWaveProxy.md#boverrideconcurrency)

### Methods

- [CreateDefaultSubobject](ue_ue.DialogueSoundWaveProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DialogueSoundWaveProxy.md#executeubergraph)
- [GetClass](ue_ue.DialogueSoundWaveProxy.md#getclass)
- [GetName](ue_ue.DialogueSoundWaveProxy.md#getname)
- [GetOuter](ue_ue.DialogueSoundWaveProxy.md#getouter)
- [GetWorld](ue_ue.DialogueSoundWaveProxy.md#getworld)
- [Find](ue_ue.DialogueSoundWaveProxy.md#find)
- [Load](ue_ue.DialogueSoundWaveProxy.md#load)
- [StaticClass](ue_ue.DialogueSoundWaveProxy.md#staticclass)

## Constructors

### constructor

• **new DialogueSoundWaveProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoundBase](ue_ue.SoundBase.md).[constructor](ue_ue.SoundBase.md#constructor)

#### Defined in

[ue/ue.d.ts:30821](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30821)

## Properties

### AttenuationSettings

• **AttenuationSettings**: [`SoundAttenuation`](ue_ue.SoundAttenuation.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[AttenuationSettings](ue_ue.SoundBase.md#attenuationsettings)

#### Defined in

[ue/ue.d.ts:9735](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9735)

___

### BusSends

• **BusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[BusSends](ue_ue.SoundBase.md#bussends)

#### Defined in

[ue/ue.d.ts:9740](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9740)

___

### ConcurrencyOverrides

• **ConcurrencyOverrides**: [`SoundConcurrencySettings`](ue_ue.SoundConcurrencySettings.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[ConcurrencyOverrides](ue_ue.SoundBase.md#concurrencyoverrides)

#### Defined in

[ue/ue.d.ts:9729](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9729)

___

### ConcurrencySet

• **ConcurrencySet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`SoundConcurrency`](ue_ue.SoundConcurrency.md)\>

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[ConcurrencySet](ue_ue.SoundBase.md#concurrencyset)

#### Defined in

[ue/ue.d.ts:9728](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9728)

___

### Duration

• **Duration**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[Duration](ue_ue.SoundBase.md#duration)

#### Defined in

[ue/ue.d.ts:9731](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9731)

___

### MaxConcurrentPlayCount

• **MaxConcurrentPlayCount**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[MaxConcurrentPlayCount](ue_ue.SoundBase.md#maxconcurrentplaycount)

#### Defined in

[ue/ue.d.ts:9730](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9730)

___

### MaxConcurrentResolutionRule

• **MaxConcurrentResolutionRule**: [`EMaxConcurrentResolutionRule`](../enums/ue_ue.EMaxConcurrentResolutionRule.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[MaxConcurrentResolutionRule](ue_ue.SoundBase.md#maxconcurrentresolutionrule)

#### Defined in

[ue/ue.d.ts:9726](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9726)

___

### MaxDistance

• **MaxDistance**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[MaxDistance](ue_ue.SoundBase.md#maxdistance)

#### Defined in

[ue/ue.d.ts:9732](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9732)

___

### Modulation

• **Modulation**: [`SoundModulation`](ue_ue.SoundModulation.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[Modulation](ue_ue.SoundBase.md#modulation)

#### Defined in

[ue/ue.d.ts:9736](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9736)

___

### PreEffectBusSends

• **PreEffectBusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[PreEffectBusSends](ue_ue.SoundBase.md#preeffectbussends)

#### Defined in

[ue/ue.d.ts:9741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9741)

___

### Priority

• **Priority**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[Priority](ue_ue.SoundBase.md#priority)

#### Defined in

[ue/ue.d.ts:9734](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9734)

___

### SoundClassObject

• **SoundClassObject**: [`SoundClass`](ue_ue.SoundClass.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SoundClassObject](ue_ue.SoundBase.md#soundclassobject)

#### Defined in

[ue/ue.d.ts:9717](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9717)

___

### SoundConcurrencySettings

• **SoundConcurrencySettings**: [`SoundConcurrency`](ue_ue.SoundConcurrency.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SoundConcurrencySettings](ue_ue.SoundBase.md#soundconcurrencysettings)

#### Defined in

[ue/ue.d.ts:9727](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9727)

___

### SoundSubmixObject

• **SoundSubmixObject**: [`SoundSubmix`](ue_ue.SoundSubmix.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SoundSubmixObject](ue_ue.SoundBase.md#soundsubmixobject)

#### Defined in

[ue/ue.d.ts:9737](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9737)

___

### SoundSubmixSends

• **SoundSubmixSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSubmixSendInfo`](ue_ue.SoundSubmixSendInfo.md)\>

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SoundSubmixSends](ue_ue.SoundBase.md#soundsubmixsends)

#### Defined in

[ue/ue.d.ts:9738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9738)

___

### SourceEffectChain

• **SourceEffectChain**: [`SoundEffectSourcePresetChain`](ue_ue.SoundEffectSourcePresetChain.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[SourceEffectChain](ue_ue.SoundBase.md#sourceeffectchain)

#### Defined in

[ue/ue.d.ts:9739](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9739)

___

### TotalSamples

• **TotalSamples**: `number`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[TotalSamples](ue_ue.SoundBase.md#totalsamples)

#### Defined in

[ue/ue.d.ts:9733](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9733)

___

### VirtualizationMode

• **VirtualizationMode**: [`EVirtualizationMode`](../enums/ue_ue.EVirtualizationMode.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[VirtualizationMode](ue_ue.SoundBase.md#virtualizationmode)

#### Defined in

[ue/ue.d.ts:9725](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9725)

___

### \_\_tid\_DialogueSoundWaveProxy\_\_

• **\_\_tid\_DialogueSoundWaveProxy\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:30826](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30826)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[__tid_Object__](ue_ue.SoundBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SoundBase\_\_

• **\_\_tid\_SoundBase\_\_**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[__tid_SoundBase__](ue_ue.SoundBase.md#__tid_soundbase__)

#### Defined in

[ue/ue.d.ts:9746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9746)

___

### bBypassVolumeScaleForPriority

• **bBypassVolumeScaleForPriority**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bBypassVolumeScaleForPriority](ue_ue.SoundBase.md#bbypassvolumescaleforpriority)

#### Defined in

[ue/ue.d.ts:9724](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9724)

___

### bDebug

• **bDebug**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bDebug](ue_ue.SoundBase.md#bdebug)

#### Defined in

[ue/ue.d.ts:9718](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9718)

___

### bHasConcatenatorNode

• **bHasConcatenatorNode**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bHasConcatenatorNode](ue_ue.SoundBase.md#bhasconcatenatornode)

#### Defined in

[ue/ue.d.ts:9722](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9722)

___

### bHasDelayNode

• **bHasDelayNode**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bHasDelayNode](ue_ue.SoundBase.md#bhasdelaynode)

#### Defined in

[ue/ue.d.ts:9721](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9721)

___

### bHasVirtualizeWhenSilent

• **bHasVirtualizeWhenSilent**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bHasVirtualizeWhenSilent](ue_ue.SoundBase.md#bhasvirtualizewhensilent)

#### Defined in

[ue/ue.d.ts:9723](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9723)

___

### bOutputToBusOnly

• **bOutputToBusOnly**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bOutputToBusOnly](ue_ue.SoundBase.md#boutputtobusonly)

#### Defined in

[ue/ue.d.ts:9720](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9720)

___

### bOverrideConcurrency

• **bOverrideConcurrency**: `boolean`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[bOverrideConcurrency](ue_ue.SoundBase.md#boverrideconcurrency)

#### Defined in

[ue/ue.d.ts:9719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9719)

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

[SoundBase](ue_ue.SoundBase.md).[ExecuteUbergraph](ue_ue.SoundBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[GetClass](ue_ue.SoundBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[GetName](ue_ue.SoundBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[GetOuter](ue_ue.SoundBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundBase](ue_ue.SoundBase.md).[GetWorld](ue_ue.SoundBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DialogueSoundWaveProxy`](ue_ue.DialogueSoundWaveProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DialogueSoundWaveProxy`](ue_ue.DialogueSoundWaveProxy.md)

#### Overrides

[SoundBase](ue_ue.SoundBase.md).[Find](ue_ue.SoundBase.md#find)

#### Defined in

[ue/ue.d.ts:30823](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30823)

___

### Load

▸ `Static` **Load**(`InName`): [`DialogueSoundWaveProxy`](ue_ue.DialogueSoundWaveProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DialogueSoundWaveProxy`](ue_ue.DialogueSoundWaveProxy.md)

#### Overrides

[SoundBase](ue_ue.SoundBase.md).[Load](ue_ue.SoundBase.md#load)

#### Defined in

[ue/ue.d.ts:30824](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30824)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundBase](ue_ue.SoundBase.md).[StaticClass](ue_ue.SoundBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:30822](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L30822)
