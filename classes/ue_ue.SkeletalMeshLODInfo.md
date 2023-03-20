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

## Properties

### BakePose

• **BakePose**: [`AnimSequence`](ue_ue.AnimSequence.md)

___

### BakePoseOverride

• **BakePoseOverride**: [`AnimSequence`](ue_ue.AnimSequence.md)

___

### BonesToPrioritize

• **BonesToPrioritize**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneReference`](ue_ue.BoneReference.md)\>

___

### BonesToRemove

• **BonesToRemove**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneReference`](ue_ue.BoneReference.md)\>

___

### BuildSettings

• **BuildSettings**: [`SkeletalMeshBuildSettings`](ue_ue.SkeletalMeshBuildSettings.md)

___

### LODHysteresis

• **LODHysteresis**: `number`

___

### LODMaterialMap

• **LODMaterialMap**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### ReductionSettings

• **ReductionSettings**: [`SkeletalMeshOptimizationSettings`](ue_ue.SkeletalMeshOptimizationSettings.md)

___

### RemovedBones

• **RemovedBones**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ScreenSize

• **ScreenSize**: [`PerPlatformFloat`](ue_ue.PerPlatformFloat.md)

___

### SourceImportFilename

• **SourceImportFilename**: `string`

___

### WeightOfPrioritization

• **WeightOfPrioritization**: `number`

___

### \_\_tid\_SkeletalMeshLODInfo\_\_

• `Private` **\_\_tid\_SkeletalMeshLODInfo\_\_**: `boolean`

___

### bAllowCPUAccess

• **bAllowCPUAccess**: `boolean`

___

### bEnableShadowCasting

• **bEnableShadowCasting**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`boolean`\>

___

### bHasBeenSimplified

• **bHasBeenSimplified**: `boolean`

___

### bHasPerLODVertexColors

• **bHasPerLODVertexColors**: `boolean`

___

### bImportWithBaseMesh

• **bImportWithBaseMesh**: `boolean`

___

### bSupportUniformlyDistributedSampling

• **bSupportUniformlyDistributedSampling**: `boolean`

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
