[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundSourceBusSendInfo

# Class: SoundSourceBusSendInfo

[ue/ue](../modules/ue_ue.md).SoundSourceBusSendInfo

## Table of contents

### Constructors

- [constructor](ue_ue.SoundSourceBusSendInfo.md#constructor)

### Properties

- [CustomSendLevelCurve](ue_ue.SoundSourceBusSendInfo.md#customsendlevelcurve)
- [MaxSendDistance](ue_ue.SoundSourceBusSendInfo.md#maxsenddistance)
- [MaxSendLevel](ue_ue.SoundSourceBusSendInfo.md#maxsendlevel)
- [MinSendDistance](ue_ue.SoundSourceBusSendInfo.md#minsenddistance)
- [MinSendLevel](ue_ue.SoundSourceBusSendInfo.md#minsendlevel)
- [SendLevel](ue_ue.SoundSourceBusSendInfo.md#sendlevel)
- [SoundSourceBus](ue_ue.SoundSourceBusSendInfo.md#soundsourcebus)
- [SourceBusSendLevelControlMethod](ue_ue.SoundSourceBusSendInfo.md#sourcebussendlevelcontrolmethod)
- [\_\_tid\_SoundSourceBusSendInfo\_\_](ue_ue.SoundSourceBusSendInfo.md#__tid_soundsourcebussendinfo__)

### Methods

- [StaticClass](ue_ue.SoundSourceBusSendInfo.md#staticclass)
- [StaticStruct](ue_ue.SoundSourceBusSendInfo.md#staticstruct)

## Constructors

### constructor

• **new SoundSourceBusSendInfo**()

• **new SoundSourceBusSendInfo**(`SourceBusSendLevelControlMethod`, `SoundSourceBus`, `SendLevel`, `MinSendLevel`, `MaxSendLevel`, `MinSendDistance`, `MaxSendDistance`, `CustomSendLevelCurve`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceBusSendLevelControlMethod` | [`ESourceBusSendLevelControlMethod`](../enums/ue_ue.ESourceBusSendLevelControlMethod.md) |
| `SoundSourceBus` | [`SoundSourceBus`](ue_ue.SoundSourceBus.md) |
| `SendLevel` | `number` |
| `MinSendLevel` | `number` |
| `MaxSendLevel` | `number` |
| `MinSendDistance` | `number` |
| `MaxSendDistance` | `number` |
| `CustomSendLevelCurve` | [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md) |

## Properties

### CustomSendLevelCurve

• **CustomSendLevelCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

___

### MaxSendDistance

• **MaxSendDistance**: `number`

___

### MaxSendLevel

• **MaxSendLevel**: `number`

___

### MinSendDistance

• **MinSendDistance**: `number`

___

### MinSendLevel

• **MinSendLevel**: `number`

___

### SendLevel

• **SendLevel**: `number`

___

### SoundSourceBus

• **SoundSourceBus**: [`SoundSourceBus`](ue_ue.SoundSourceBus.md)

___

### SourceBusSendLevelControlMethod

• **SourceBusSendLevelControlMethod**: [`ESourceBusSendLevelControlMethod`](../enums/ue_ue.ESourceBusSendLevelControlMethod.md)

___

### \_\_tid\_SoundSourceBusSendInfo\_\_

• `Private` **\_\_tid\_SoundSourceBusSendInfo\_\_**: `boolean`

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
