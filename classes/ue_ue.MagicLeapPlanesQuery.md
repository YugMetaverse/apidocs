[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MagicLeapPlanesQuery

# Class: MagicLeapPlanesQuery

[ue/ue](../modules/ue_ue.md).MagicLeapPlanesQuery

## Table of contents

### Constructors

- [constructor](ue_ue.MagicLeapPlanesQuery.md#constructor)

### Properties

- [Flags](ue_ue.MagicLeapPlanesQuery.md#flags)
- [MaxResults](ue_ue.MagicLeapPlanesQuery.md#maxresults)
- [MinHoleLength](ue_ue.MagicLeapPlanesQuery.md#minholelength)
- [MinPlaneArea](ue_ue.MagicLeapPlanesQuery.md#minplanearea)
- [SearchVolume](ue_ue.MagicLeapPlanesQuery.md#searchvolume)
- [SearchVolumeExtents](ue_ue.MagicLeapPlanesQuery.md#searchvolumeextents)
- [SearchVolumeOrientation](ue_ue.MagicLeapPlanesQuery.md#searchvolumeorientation)
- [SearchVolumePosition](ue_ue.MagicLeapPlanesQuery.md#searchvolumeposition)
- [\_\_tid\_MagicLeapPlanesQuery\_\_](ue_ue.MagicLeapPlanesQuery.md#__tid_magicleapplanesquery__)

### Methods

- [StaticClass](ue_ue.MagicLeapPlanesQuery.md#staticclass)
- [StaticStruct](ue_ue.MagicLeapPlanesQuery.md#staticstruct)

## Constructors

### constructor

• **new MagicLeapPlanesQuery**()

• **new MagicLeapPlanesQuery**(`Flags`, `SearchVolume`, `MaxResults`, `MinHoleLength`, `MinPlaneArea`, `SearchVolumePosition`, `SearchVolumeOrientation`, `SearchVolumeExtents`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Flags` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EMagicLeapPlaneQueryFlags`](../enums/ue_ue.EMagicLeapPlaneQueryFlags.md)\> |
| `SearchVolume` | [`BoxComponent`](ue_ue.BoxComponent.md) |
| `MaxResults` | `number` |
| `MinHoleLength` | `number` |
| `MinPlaneArea` | `number` |
| `SearchVolumePosition` | [`Vector`](ue_ue_s.Vector.md) |
| `SearchVolumeOrientation` | [`Quat`](ue_ue_s.Quat.md) |
| `SearchVolumeExtents` | [`Vector`](ue_ue_s.Vector.md) |

## Properties

### Flags

• **Flags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EMagicLeapPlaneQueryFlags`](../enums/ue_ue.EMagicLeapPlaneQueryFlags.md)\>

___

### MaxResults

• **MaxResults**: `number`

___

### MinHoleLength

• **MinHoleLength**: `number`

___

### MinPlaneArea

• **MinPlaneArea**: `number`

___

### SearchVolume

• **SearchVolume**: [`BoxComponent`](ue_ue.BoxComponent.md)

___

### SearchVolumeExtents

• **SearchVolumeExtents**: [`Vector`](ue_ue_s.Vector.md)

___

### SearchVolumeOrientation

• **SearchVolumeOrientation**: [`Quat`](ue_ue_s.Quat.md)

___

### SearchVolumePosition

• **SearchVolumePosition**: [`Vector`](ue_ue_s.Vector.md)

___

### \_\_tid\_MagicLeapPlanesQuery\_\_

• `Private` **\_\_tid\_MagicLeapPlanesQuery\_\_**: `boolean`

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
