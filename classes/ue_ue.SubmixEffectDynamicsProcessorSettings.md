[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SubmixEffectDynamicsProcessorSettings

# Class: SubmixEffectDynamicsProcessorSettings

[ue/ue](../modules/ue_ue.md).SubmixEffectDynamicsProcessorSettings

## Table of contents

### Constructors

- [constructor](ue_ue.SubmixEffectDynamicsProcessorSettings.md#constructor)

### Properties

- [AttackTimeMsec](ue_ue.SubmixEffectDynamicsProcessorSettings.md#attacktimemsec)
- [DynamicsProcessorType](ue_ue.SubmixEffectDynamicsProcessorSettings.md#dynamicsprocessortype)
- [InputGainDb](ue_ue.SubmixEffectDynamicsProcessorSettings.md#inputgaindb)
- [KneeBandwidthDb](ue_ue.SubmixEffectDynamicsProcessorSettings.md#kneebandwidthdb)
- [LookAheadMsec](ue_ue.SubmixEffectDynamicsProcessorSettings.md#lookaheadmsec)
- [OutputGainDb](ue_ue.SubmixEffectDynamicsProcessorSettings.md#outputgaindb)
- [PeakMode](ue_ue.SubmixEffectDynamicsProcessorSettings.md#peakmode)
- [Ratio](ue_ue.SubmixEffectDynamicsProcessorSettings.md#ratio)
- [ReleaseTimeMsec](ue_ue.SubmixEffectDynamicsProcessorSettings.md#releasetimemsec)
- [ThresholdDb](ue_ue.SubmixEffectDynamicsProcessorSettings.md#thresholddb)
- [\_\_tid\_SubmixEffectDynamicsProcessorSettings\_\_](ue_ue.SubmixEffectDynamicsProcessorSettings.md#__tid_submixeffectdynamicsprocessorsettings__)
- [bAnalogMode](ue_ue.SubmixEffectDynamicsProcessorSettings.md#banalogmode)
- [bChannelLinked](ue_ue.SubmixEffectDynamicsProcessorSettings.md#bchannellinked)

### Methods

- [StaticClass](ue_ue.SubmixEffectDynamicsProcessorSettings.md#staticclass)
- [StaticStruct](ue_ue.SubmixEffectDynamicsProcessorSettings.md#staticstruct)

## Constructors

### constructor

• **new SubmixEffectDynamicsProcessorSettings**()

• **new SubmixEffectDynamicsProcessorSettings**(`DynamicsProcessorType`, `PeakMode`, `LookAheadMsec`, `AttackTimeMsec`, `ReleaseTimeMsec`, `ThresholdDb`, `Ratio`, `KneeBandwidthDb`, `InputGainDb`, `OutputGainDb`, `bChannelLinked`, `bAnalogMode`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `DynamicsProcessorType` | [`ESubmixEffectDynamicsProcessorType`](../enums/ue_ue.ESubmixEffectDynamicsProcessorType.md) |
| `PeakMode` | [`ESubmixEffectDynamicsPeakMode`](../enums/ue_ue.ESubmixEffectDynamicsPeakMode.md) |
| `LookAheadMsec` | `number` |
| `AttackTimeMsec` | `number` |
| `ReleaseTimeMsec` | `number` |
| `ThresholdDb` | `number` |
| `Ratio` | `number` |
| `KneeBandwidthDb` | `number` |
| `InputGainDb` | `number` |
| `OutputGainDb` | `number` |
| `bChannelLinked` | `boolean` |
| `bAnalogMode` | `boolean` |

## Properties

### AttackTimeMsec

• **AttackTimeMsec**: `number`

___

### DynamicsProcessorType

• **DynamicsProcessorType**: [`ESubmixEffectDynamicsProcessorType`](../enums/ue_ue.ESubmixEffectDynamicsProcessorType.md)

___

### InputGainDb

• **InputGainDb**: `number`

___

### KneeBandwidthDb

• **KneeBandwidthDb**: `number`

___

### LookAheadMsec

• **LookAheadMsec**: `number`

___

### OutputGainDb

• **OutputGainDb**: `number`

___

### PeakMode

• **PeakMode**: [`ESubmixEffectDynamicsPeakMode`](../enums/ue_ue.ESubmixEffectDynamicsPeakMode.md)

___

### Ratio

• **Ratio**: `number`

___

### ReleaseTimeMsec

• **ReleaseTimeMsec**: `number`

___

### ThresholdDb

• **ThresholdDb**: `number`

___

### \_\_tid\_SubmixEffectDynamicsProcessorSettings\_\_

• `Private` **\_\_tid\_SubmixEffectDynamicsProcessorSettings\_\_**: `boolean`

___

### bAnalogMode

• **bAnalogMode**: `boolean`

___

### bChannelLinked

• **bChannelLinked**: `boolean`

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
