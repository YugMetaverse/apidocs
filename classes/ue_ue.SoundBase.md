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

#### Defined in

[ue/ue.d.ts:9716](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9716)

## Properties

### AttenuationSettings

• **AttenuationSettings**: [`SoundAttenuation`](ue_ue.SoundAttenuation.md)

#### Defined in

[ue/ue.d.ts:9735](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9735)

___

### BusSends

• **BusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Defined in

[ue/ue.d.ts:9740](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9740)

___

### ConcurrencyOverrides

• **ConcurrencyOverrides**: [`SoundConcurrencySettings`](ue_ue.SoundConcurrencySettings.md)

#### Defined in

[ue/ue.d.ts:9729](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9729)

___

### ConcurrencySet

• **ConcurrencySet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`SoundConcurrency`](ue_ue.SoundConcurrency.md)\>

#### Defined in

[ue/ue.d.ts:9728](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9728)

___

### Duration

• **Duration**: `number`

#### Defined in

[ue/ue.d.ts:9731](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9731)

___

### MaxConcurrentPlayCount

• **MaxConcurrentPlayCount**: `number`

#### Defined in

[ue/ue.d.ts:9730](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9730)

___

### MaxConcurrentResolutionRule

• **MaxConcurrentResolutionRule**: [`EMaxConcurrentResolutionRule`](../enums/ue_ue.EMaxConcurrentResolutionRule.md)

#### Defined in

[ue/ue.d.ts:9726](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9726)

___

### MaxDistance

• **MaxDistance**: `number`

#### Defined in

[ue/ue.d.ts:9732](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9732)

___

### Modulation

• **Modulation**: [`SoundModulation`](ue_ue.SoundModulation.md)

#### Defined in

[ue/ue.d.ts:9736](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9736)

___

### PreEffectBusSends

• **PreEffectBusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Defined in

[ue/ue.d.ts:9741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9741)

___

### Priority

• **Priority**: `number`

#### Defined in

[ue/ue.d.ts:9734](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9734)

___

### SoundClassObject

• **SoundClassObject**: [`SoundClass`](ue_ue.SoundClass.md)

#### Defined in

[ue/ue.d.ts:9717](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9717)

___

### SoundConcurrencySettings

• **SoundConcurrencySettings**: [`SoundConcurrency`](ue_ue.SoundConcurrency.md)

#### Defined in

[ue/ue.d.ts:9727](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9727)

___

### SoundSubmixObject

• **SoundSubmixObject**: [`SoundSubmix`](ue_ue.SoundSubmix.md)

#### Defined in

[ue/ue.d.ts:9737](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9737)

___

### SoundSubmixSends

• **SoundSubmixSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSubmixSendInfo`](ue_ue.SoundSubmixSendInfo.md)\>

#### Defined in

[ue/ue.d.ts:9738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9738)

___

### SourceEffectChain

• **SourceEffectChain**: [`SoundEffectSourcePresetChain`](ue_ue.SoundEffectSourcePresetChain.md)

#### Defined in

[ue/ue.d.ts:9739](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9739)

___

### TotalSamples

• **TotalSamples**: `number`

#### Defined in

[ue/ue.d.ts:9733](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9733)

___

### VirtualizationMode

• **VirtualizationMode**: [`EVirtualizationMode`](../enums/ue_ue.EVirtualizationMode.md)

#### Defined in

[ue/ue.d.ts:9725](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9725)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SoundBase\_\_

• **\_\_tid\_SoundBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:9746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9746)

___

### bBypassVolumeScaleForPriority

• **bBypassVolumeScaleForPriority**: `boolean`

#### Defined in

[ue/ue.d.ts:9724](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9724)

___

### bDebug

• **bDebug**: `boolean`

#### Defined in

[ue/ue.d.ts:9718](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9718)

___

### bHasConcatenatorNode

• **bHasConcatenatorNode**: `boolean`

#### Defined in

[ue/ue.d.ts:9722](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9722)

___

### bHasDelayNode

• **bHasDelayNode**: `boolean`

#### Defined in

[ue/ue.d.ts:9721](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9721)

___

### bHasVirtualizeWhenSilent

• **bHasVirtualizeWhenSilent**: `boolean`

#### Defined in

[ue/ue.d.ts:9723](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9723)

___

### bOutputToBusOnly

• **bOutputToBusOnly**: `boolean`

#### Defined in

[ue/ue.d.ts:9720](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9720)

___

### bOverrideConcurrency

• **bOverrideConcurrency**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:9743](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9743)

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

#### Defined in

[ue/ue.d.ts:9744](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9744)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:9742](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9742)
