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

#### Defined in

[ue/ue.d.ts:3336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3336)

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

#### Defined in

[ue/ue.d.ts:3337](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3337)

## Properties

### BakePose

• **BakePose**: [`AnimSequence`](ue_ue.AnimSequence.md)

#### Defined in

[ue/ue.d.ts:3344](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3344)

___

### BoneFilterActionOption

• **BoneFilterActionOption**: [`EBoneFilterActionOption`](../enums/ue_ue.EBoneFilterActionOption.md)

#### Defined in

[ue/ue.d.ts:3340](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3340)

___

### BoneList

• **BoneList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneFilter`](ue_ue.BoneFilter.md)\>

#### Defined in

[ue/ue.d.ts:3341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3341)

___

### BonesToPrioritize

• **BonesToPrioritize**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:3342](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3342)

___

### LODHysteresis

• **LODHysteresis**: `number`

#### Defined in

[ue/ue.d.ts:3339](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3339)

___

### ReductionSettings

• **ReductionSettings**: [`SkeletalMeshOptimizationSettings`](ue_ue.SkeletalMeshOptimizationSettings.md)

#### Defined in

[ue/ue.d.ts:3345](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3345)

___

### ScreenSize

• **ScreenSize**: [`PerPlatformFloat`](ue_ue.PerPlatformFloat.md)

#### Defined in

[ue/ue.d.ts:3338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3338)

___

### WeightOfPrioritization

• **WeightOfPrioritization**: `number`

#### Defined in

[ue/ue.d.ts:3343](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3343)

___

### \_\_tid\_SkeletalMeshLODGroupSettings\_\_

• `Private` **\_\_tid\_SkeletalMeshLODGroupSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3351](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3351)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:3349](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3349)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:3350](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3350)
