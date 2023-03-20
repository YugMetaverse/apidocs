[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundSubmixSendInfo

# Class: SoundSubmixSendInfo

[ue/ue](../modules/ue_ue.md).SoundSubmixSendInfo

## Table of contents

### Constructors

- [constructor](ue_ue.SoundSubmixSendInfo.md#constructor)

### Properties

- [CustomSendLevelCurve](ue_ue.SoundSubmixSendInfo.md#customsendlevelcurve)
- [MaxSendDistance](ue_ue.SoundSubmixSendInfo.md#maxsenddistance)
- [MaxSendLevel](ue_ue.SoundSubmixSendInfo.md#maxsendlevel)
- [MinSendDistance](ue_ue.SoundSubmixSendInfo.md#minsenddistance)
- [MinSendLevel](ue_ue.SoundSubmixSendInfo.md#minsendlevel)
- [SendLevel](ue_ue.SoundSubmixSendInfo.md#sendlevel)
- [SendLevelControlMethod](ue_ue.SoundSubmixSendInfo.md#sendlevelcontrolmethod)
- [SoundSubmix](ue_ue.SoundSubmixSendInfo.md#soundsubmix)
- [\_\_tid\_SoundSubmixSendInfo\_\_](ue_ue.SoundSubmixSendInfo.md#__tid_soundsubmixsendinfo__)

### Methods

- [StaticClass](ue_ue.SoundSubmixSendInfo.md#staticclass)
- [StaticStruct](ue_ue.SoundSubmixSendInfo.md#staticstruct)

## Constructors

### constructor

• **new SoundSubmixSendInfo**()

• **new SoundSubmixSendInfo**(`SendLevelControlMethod`, `SoundSubmix`, `SendLevel`, `MinSendLevel`, `MaxSendLevel`, `MinSendDistance`, `MaxSendDistance`, `CustomSendLevelCurve`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SendLevelControlMethod` | [`ESendLevelControlMethod`](../enums/ue_ue.ESendLevelControlMethod.md) |
| `SoundSubmix` | [`SoundSubmix`](ue_ue.SoundSubmix.md) |
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

### SendLevelControlMethod

• **SendLevelControlMethod**: [`ESendLevelControlMethod`](../enums/ue_ue.ESendLevelControlMethod.md)

___

### SoundSubmix

• **SoundSubmix**: [`SoundSubmix`](ue_ue.SoundSubmix.md)

___

### \_\_tid\_SoundSubmixSendInfo\_\_

• `Private` **\_\_tid\_SoundSubmixSendInfo\_\_**: `boolean`

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
