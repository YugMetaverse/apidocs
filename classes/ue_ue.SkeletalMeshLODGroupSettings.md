[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SkeletalMeshLODGroupSettings

# Class: SkeletalMeshLODGroupSettings

[ue/ue](../modules/ue_ue.md).SkeletalMeshLODGroupSettings

## Table of contents

### Constructors

- [constructor](ue_ue.SkeletalMeshLODGroupSettings.md#constructor)

### Properties

- [BakePose](ue_ue.SkeletalMeshLODGroupSettings.md#bakepose)
- [BoneFilterActionOption](ue_ue.SkeletalMeshLODGroupSettings.md#bonefilteractionoption)
- [BoneList](ue_ue.SkeletalMeshLODGroupSettings.md#bonelist)
- [BonesToPrioritize](ue_ue.SkeletalMeshLODGroupSettings.md#bonestoprioritize)
- [LODHysteresis](ue_ue.SkeletalMeshLODGroupSettings.md#lodhysteresis)
- [ReductionSettings](ue_ue.SkeletalMeshLODGroupSettings.md#reductionsettings)
- [ScreenSize](ue_ue.SkeletalMeshLODGroupSettings.md#screensize)
- [WeightOfPrioritization](ue_ue.SkeletalMeshLODGroupSettings.md#weightofprioritization)
- [\_\_tid\_SkeletalMeshLODGroupSettings\_\_](ue_ue.SkeletalMeshLODGroupSettings.md#__tid_skeletalmeshlodgroupsettings__)

### Methods

- [StaticClass](ue_ue.SkeletalMeshLODGroupSettings.md#staticclass)
- [StaticStruct](ue_ue.SkeletalMeshLODGroupSettings.md#staticstruct)

## Constructors

### constructor

• **new SkeletalMeshLODGroupSettings**()

• **new SkeletalMeshLODGroupSettings**(`ScreenSize`, `LODHysteresis`, `BoneFilterActionOption`, `BoneList`, `BonesToPrioritize`, `WeightOfPrioritization`, `BakePose`, `ReductionSettings`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ScreenSize` | [`PerPlatformFloat`](ue_ue.PerPlatformFloat.md) |
| `LODHysteresis` | `number` |
| `BoneFilterActionOption` | [`EBoneFilterActionOption`](../enums/ue_ue.EBoneFilterActionOption.md) |
| `BoneList` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneFilter`](ue_ue.BoneFilter.md)\> |
| `BonesToPrioritize` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `WeightOfPrioritization` | `number` |
| `BakePose` | [`AnimSequence`](ue_ue.AnimSequence.md) |
| `ReductionSettings` | [`SkeletalMeshOptimizationSettings`](ue_ue.SkeletalMeshOptimizationSettings.md) |

## Properties

### BakePose

• **BakePose**: [`AnimSequence`](ue_ue.AnimSequence.md)

___

### BoneFilterActionOption

• **BoneFilterActionOption**: [`EBoneFilterActionOption`](../enums/ue_ue.EBoneFilterActionOption.md)

___

### BoneList

• **BoneList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneFilter`](ue_ue.BoneFilter.md)\>

___

### BonesToPrioritize

• **BonesToPrioritize**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### LODHysteresis

• **LODHysteresis**: `number`

___

### ReductionSettings

• **ReductionSettings**: [`SkeletalMeshOptimizationSettings`](ue_ue.SkeletalMeshOptimizationSettings.md)

___

### ScreenSize

• **ScreenSize**: [`PerPlatformFloat`](ue_ue.PerPlatformFloat.md)

___

### WeightOfPrioritization

• **WeightOfPrioritization**: `number`

___

### \_\_tid\_SkeletalMeshLODGroupSettings\_\_

• `Private` **\_\_tid\_SkeletalMeshLODGroupSettings\_\_**: `boolean`

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
