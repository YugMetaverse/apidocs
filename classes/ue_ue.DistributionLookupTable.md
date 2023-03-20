[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DistributionLookupTable

# Class: DistributionLookupTable

[ue/ue](../modules/ue_ue.md).DistributionLookupTable

## Table of contents

### Constructors

- [constructor](ue_ue.DistributionLookupTable.md#constructor)

### Properties

- [EntryCount](ue_ue.DistributionLookupTable.md#entrycount)
- [EntryStride](ue_ue.DistributionLookupTable.md#entrystride)
- [LockFlag](ue_ue.DistributionLookupTable.md#lockflag)
- [Op](ue_ue.DistributionLookupTable.md#op)
- [SubEntryStride](ue_ue.DistributionLookupTable.md#subentrystride)
- [TimeBias](ue_ue.DistributionLookupTable.md#timebias)
- [TimeScale](ue_ue.DistributionLookupTable.md#timescale)
- [Values](ue_ue.DistributionLookupTable.md#values)
- [\_\_tid\_DistributionLookupTable\_\_](ue_ue.DistributionLookupTable.md#__tid_distributionlookuptable__)

### Methods

- [StaticClass](ue_ue.DistributionLookupTable.md#staticclass)
- [StaticStruct](ue_ue.DistributionLookupTable.md#staticstruct)

## Constructors

### constructor

• **new DistributionLookupTable**()

• **new DistributionLookupTable**(`TimeScale`, `TimeBias`, `Values`, `Op`, `EntryCount`, `EntryStride`, `SubEntryStride`, `LockFlag`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TimeScale` | `number` |
| `TimeBias` | `number` |
| `Values` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `Op` | `number` |
| `EntryCount` | `number` |
| `EntryStride` | `number` |
| `SubEntryStride` | `number` |
| `LockFlag` | `number` |

## Properties

### EntryCount

• **EntryCount**: `number`

___

### EntryStride

• **EntryStride**: `number`

___

### LockFlag

• **LockFlag**: `number`

___

### Op

• **Op**: `number`

___

### SubEntryStride

• **SubEntryStride**: `number`

___

### TimeBias

• **TimeBias**: `number`

___

### TimeScale

• **TimeScale**: `number`

___

### Values

• **Values**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### \_\_tid\_DistributionLookupTable\_\_

• `Private` **\_\_tid\_DistributionLookupTable\_\_**: `boolean`

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
