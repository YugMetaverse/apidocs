[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SkeletalMeshLODInfo

# Class: SkeletalMeshLODInfo

[ue/ue](../modules/ue_ue.md).SkeletalMeshLODInfo

## Table of contents

### Constructors

- [constructor](ue_ue.SkeletalMeshLODInfo.md#constructor)

### Properties

- [BakePose](ue_ue.SkeletalMeshLODInfo.md#bakepose)
- [BakePoseOverride](ue_ue.SkeletalMeshLODInfo.md#bakeposeoverride)
- [BonesToPrioritize](ue_ue.SkeletalMeshLODInfo.md#bonestoprioritize)
- [BonesToRemove](ue_ue.SkeletalMeshLODInfo.md#bonestoremove)
- [BuildSettings](ue_ue.SkeletalMeshLODInfo.md#buildsettings)
- [LODHysteresis](ue_ue.SkeletalMeshLODInfo.md#lodhysteresis)
- [LODMaterialMap](ue_ue.SkeletalMeshLODInfo.md#lodmaterialmap)
- [ReductionSettings](ue_ue.SkeletalMeshLODInfo.md#reductionsettings)
- [RemovedBones](ue_ue.SkeletalMeshLODInfo.md#removedbones)
- [ScreenSize](ue_ue.SkeletalMeshLODInfo.md#screensize)
- [SourceImportFilename](ue_ue.SkeletalMeshLODInfo.md#sourceimportfilename)
- [WeightOfPrioritization](ue_ue.SkeletalMeshLODInfo.md#weightofprioritization)
- [\_\_tid\_SkeletalMeshLODInfo\_\_](ue_ue.SkeletalMeshLODInfo.md#__tid_skeletalmeshlodinfo__)
- [bAllowCPUAccess](ue_ue.SkeletalMeshLODInfo.md#ballowcpuaccess)
- [bEnableShadowCasting](ue_ue.SkeletalMeshLODInfo.md#benableshadowcasting)
- [bHasBeenSimplified](ue_ue.SkeletalMeshLODInfo.md#bhasbeensimplified)
- [bHasPerLODVertexColors](ue_ue.SkeletalMeshLODInfo.md#bhasperlodvertexcolors)
- [bImportWithBaseMesh](ue_ue.SkeletalMeshLODInfo.md#bimportwithbasemesh)
- [bSupportUniformlyDistributedSampling](ue_ue.SkeletalMeshLODInfo.md#bsupportuniformlydistributedsampling)

### Methods

- [StaticClass](ue_ue.SkeletalMeshLODInfo.md#staticclass)
- [StaticStruct](ue_ue.SkeletalMeshLODInfo.md#staticstruct)

## Constructors

### constructor

• **new SkeletalMeshLODInfo**()

#### Defined in

[ue/ue.d.ts:3267](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3267)

• **new SkeletalMeshLODInfo**(`ScreenSize`, `LODHysteresis`, `LODMaterialMap`, `bEnableShadowCasting`, `RemovedBones`, `BuildSettings`, `ReductionSettings`, `BonesToRemove`, `BonesToPrioritize`, `WeightOfPrioritization`, `BakePose`, `BakePoseOverride`, `SourceImportFilename`, `bHasBeenSimplified`, `bHasPerLODVertexColors`, `bAllowCPUAccess`, `bSupportUniformlyDistributedSampling`, `bImportWithBaseMesh`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ScreenSize` | [`PerPlatformFloat`](ue_ue.PerPlatformFloat.md) |
| `LODHysteresis` | `number` |
| `LODMaterialMap` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `bEnableShadowCasting` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\> |
| `RemovedBones` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `BuildSettings` | [`SkeletalMeshBuildSettings`](ue_ue.SkeletalMeshBuildSettings.md) |
| `ReductionSettings` | [`SkeletalMeshOptimizationSettings`](ue_ue.SkeletalMeshOptimizationSettings.md) |
| `BonesToRemove` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneReference`](ue_ue.BoneReference.md)\> |
| `BonesToPrioritize` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneReference`](ue_ue.BoneReference.md)\> |
| `WeightOfPrioritization` | `number` |
| `BakePose` | [`AnimSequence`](ue_ue.AnimSequence.md) |
| `BakePoseOverride` | [`AnimSequence`](ue_ue.AnimSequence.md) |
| `SourceImportFilename` | `string` |
| `bHasBeenSimplified` | `boolean` |
| `bHasPerLODVertexColors` | `boolean` |
| `bAllowCPUAccess` | `boolean` |
| `bSupportUniformlyDistributedSampling` | `boolean` |
| `bImportWithBaseMesh` | `boolean` |

#### Defined in

[ue/ue.d.ts:3268](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3268)

## Properties

### BakePose

• **BakePose**: [`AnimSequence`](ue_ue.AnimSequence.md)

#### Defined in

[ue/ue.d.ts:3279](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3279)

___

### BakePoseOverride

• **BakePoseOverride**: [`AnimSequence`](ue_ue.AnimSequence.md)

#### Defined in

[ue/ue.d.ts:3280](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3280)

___

### BonesToPrioritize

• **BonesToPrioritize**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneReference`](ue_ue.BoneReference.md)\>

#### Defined in

[ue/ue.d.ts:3277](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3277)

___

### BonesToRemove

• **BonesToRemove**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneReference`](ue_ue.BoneReference.md)\>

#### Defined in

[ue/ue.d.ts:3276](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3276)

___

### BuildSettings

• **BuildSettings**: [`SkeletalMeshBuildSettings`](ue_ue.SkeletalMeshBuildSettings.md)

#### Defined in

[ue/ue.d.ts:3274](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3274)

___

### LODHysteresis

• **LODHysteresis**: `number`

#### Defined in

[ue/ue.d.ts:3270](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3270)

___

### LODMaterialMap

• **LODMaterialMap**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:3271](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3271)

___

### ReductionSettings

• **ReductionSettings**: [`SkeletalMeshOptimizationSettings`](ue_ue.SkeletalMeshOptimizationSettings.md)

#### Defined in

[ue/ue.d.ts:3275](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3275)

___

### RemovedBones

• **RemovedBones**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:3273](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3273)

___

### ScreenSize

• **ScreenSize**: [`PerPlatformFloat`](ue_ue.PerPlatformFloat.md)

#### Defined in

[ue/ue.d.ts:3269](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3269)

___

### SourceImportFilename

• **SourceImportFilename**: `string`

#### Defined in

[ue/ue.d.ts:3281](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3281)

___

### WeightOfPrioritization

• **WeightOfPrioritization**: `number`

#### Defined in

[ue/ue.d.ts:3278](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3278)

___

### \_\_tid\_SkeletalMeshLODInfo\_\_

• `Private` **\_\_tid\_SkeletalMeshLODInfo\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3292)

___

### bAllowCPUAccess

• **bAllowCPUAccess**: `boolean`

#### Defined in

[ue/ue.d.ts:3284](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3284)

___

### bEnableShadowCasting

• **bEnableShadowCasting**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\>

#### Defined in

[ue/ue.d.ts:3272](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3272)

___

### bHasBeenSimplified

• **bHasBeenSimplified**: `boolean`

#### Defined in

[ue/ue.d.ts:3282](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3282)

___

### bHasPerLODVertexColors

• **bHasPerLODVertexColors**: `boolean`

#### Defined in

[ue/ue.d.ts:3283](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3283)

___

### bImportWithBaseMesh

• **bImportWithBaseMesh**: `boolean`

#### Defined in

[ue/ue.d.ts:3286](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3286)

___

### bSupportUniformlyDistributedSampling

• **bSupportUniformlyDistributedSampling**: `boolean`

#### Defined in

[ue/ue.d.ts:3285](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3285)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:3290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3290)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:3291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3291)
