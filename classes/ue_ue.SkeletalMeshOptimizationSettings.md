[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SkeletalMeshOptimizationSettings

# Class: SkeletalMeshOptimizationSettings

[ue/ue](../modules/ue_ue.md).SkeletalMeshOptimizationSettings

## Table of contents

### Constructors

- [constructor](ue_ue.SkeletalMeshOptimizationSettings.md#constructor)

### Properties

- [BakePose](ue_ue.SkeletalMeshOptimizationSettings.md#bakepose)
- [BaseLOD](ue_ue.SkeletalMeshOptimizationSettings.md#baselod)
- [BonesToRemove](ue_ue.SkeletalMeshOptimizationSettings.md#bonestoremove)
- [MaxBonesPerVertex](ue_ue.SkeletalMeshOptimizationSettings.md#maxbonespervertex)
- [MaxDeviationPercentage](ue_ue.SkeletalMeshOptimizationSettings.md#maxdeviationpercentage)
- [MaxNumOfTriangles](ue_ue.SkeletalMeshOptimizationSettings.md#maxnumoftriangles)
- [MaxNumOfVerts](ue_ue.SkeletalMeshOptimizationSettings.md#maxnumofverts)
- [NormalsThreshold](ue_ue.SkeletalMeshOptimizationSettings.md#normalsthreshold)
- [NumOfTrianglesPercentage](ue_ue.SkeletalMeshOptimizationSettings.md#numoftrianglespercentage)
- [NumOfVertPercentage](ue_ue.SkeletalMeshOptimizationSettings.md#numofvertpercentage)
- [ReductionMethod](ue_ue.SkeletalMeshOptimizationSettings.md#reductionmethod)
- [ShadingImportance](ue_ue.SkeletalMeshOptimizationSettings.md#shadingimportance)
- [SilhouetteImportance](ue_ue.SkeletalMeshOptimizationSettings.md#silhouetteimportance)
- [SkinningImportance](ue_ue.SkeletalMeshOptimizationSettings.md#skinningimportance)
- [TerminationCriterion](ue_ue.SkeletalMeshOptimizationSettings.md#terminationcriterion)
- [TextureImportance](ue_ue.SkeletalMeshOptimizationSettings.md#textureimportance)
- [VolumeImportance](ue_ue.SkeletalMeshOptimizationSettings.md#volumeimportance)
- [WeldingThreshold](ue_ue.SkeletalMeshOptimizationSettings.md#weldingthreshold)
- [\_\_tid\_SkeletalMeshOptimizationSettings\_\_](ue_ue.SkeletalMeshOptimizationSettings.md#__tid_skeletalmeshoptimizationsettings__)
- [bEnforceBoneBoundaries](ue_ue.SkeletalMeshOptimizationSettings.md#benforceboneboundaries)
- [bLockEdges](ue_ue.SkeletalMeshOptimizationSettings.md#blockedges)
- [bRecalcNormals](ue_ue.SkeletalMeshOptimizationSettings.md#brecalcnormals)
- [bRemapMorphTargets](ue_ue.SkeletalMeshOptimizationSettings.md#bremapmorphtargets)

### Methods

- [StaticClass](ue_ue.SkeletalMeshOptimizationSettings.md#staticclass)
- [StaticStruct](ue_ue.SkeletalMeshOptimizationSettings.md#staticstruct)

## Constructors

### constructor

• **new SkeletalMeshOptimizationSettings**()

• **new SkeletalMeshOptimizationSettings**(`TerminationCriterion`, `NumOfTrianglesPercentage`, `NumOfVertPercentage`, `MaxNumOfTriangles`, `MaxNumOfVerts`, `MaxDeviationPercentage`, `ReductionMethod`, `SilhouetteImportance`, `TextureImportance`, `ShadingImportance`, `SkinningImportance`, `bRemapMorphTargets`, `bRecalcNormals`, `WeldingThreshold`, `NormalsThreshold`, `MaxBonesPerVertex`, `bEnforceBoneBoundaries`, `VolumeImportance`, `bLockEdges`, `BaseLOD`, `BonesToRemove`, `BakePose`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TerminationCriterion` | [`SkeletalMeshTerminationCriterion`](../enums/ue_ue.SkeletalMeshTerminationCriterion.md) |
| `NumOfTrianglesPercentage` | `number` |
| `NumOfVertPercentage` | `number` |
| `MaxNumOfTriangles` | `number` |
| `MaxNumOfVerts` | `number` |
| `MaxDeviationPercentage` | `number` |
| `ReductionMethod` | [`SkeletalMeshOptimizationType`](../enums/ue_ue.SkeletalMeshOptimizationType.md) |
| `SilhouetteImportance` | [`SkeletalMeshOptimizationImportance`](../enums/ue_ue.SkeletalMeshOptimizationImportance.md) |
| `TextureImportance` | [`SkeletalMeshOptimizationImportance`](../enums/ue_ue.SkeletalMeshOptimizationImportance.md) |
| `ShadingImportance` | [`SkeletalMeshOptimizationImportance`](../enums/ue_ue.SkeletalMeshOptimizationImportance.md) |
| `SkinningImportance` | [`SkeletalMeshOptimizationImportance`](../enums/ue_ue.SkeletalMeshOptimizationImportance.md) |
| `bRemapMorphTargets` | `boolean` |
| `bRecalcNormals` | `boolean` |
| `WeldingThreshold` | `number` |
| `NormalsThreshold` | `number` |
| `MaxBonesPerVertex` | `number` |
| `bEnforceBoneBoundaries` | `boolean` |
| `VolumeImportance` | `number` |
| `bLockEdges` | `boolean` |
| `BaseLOD` | `number` |
| `BonesToRemove` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneReference`](ue_ue.BoneReference.md)\> |
| `BakePose` | [`AnimSequence`](ue_ue.AnimSequence.md) |

## Properties

### BakePose

• **BakePose**: [`AnimSequence`](ue_ue.AnimSequence.md)

___

### BaseLOD

• **BaseLOD**: `number`

___

### BonesToRemove

• **BonesToRemove**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneReference`](ue_ue.BoneReference.md)\>

___

### MaxBonesPerVertex

• **MaxBonesPerVertex**: `number`

___

### MaxDeviationPercentage

• **MaxDeviationPercentage**: `number`

___

### MaxNumOfTriangles

• **MaxNumOfTriangles**: `number`

___

### MaxNumOfVerts

• **MaxNumOfVerts**: `number`

___

### NormalsThreshold

• **NormalsThreshold**: `number`

___

### NumOfTrianglesPercentage

• **NumOfTrianglesPercentage**: `number`

___

### NumOfVertPercentage

• **NumOfVertPercentage**: `number`

___

### ReductionMethod

• **ReductionMethod**: [`SkeletalMeshOptimizationType`](../enums/ue_ue.SkeletalMeshOptimizationType.md)

___

### ShadingImportance

• **ShadingImportance**: [`SkeletalMeshOptimizationImportance`](../enums/ue_ue.SkeletalMeshOptimizationImportance.md)

___

### SilhouetteImportance

• **SilhouetteImportance**: [`SkeletalMeshOptimizationImportance`](../enums/ue_ue.SkeletalMeshOptimizationImportance.md)

___

### SkinningImportance

• **SkinningImportance**: [`SkeletalMeshOptimizationImportance`](../enums/ue_ue.SkeletalMeshOptimizationImportance.md)

___

### TerminationCriterion

• **TerminationCriterion**: [`SkeletalMeshTerminationCriterion`](../enums/ue_ue.SkeletalMeshTerminationCriterion.md)

___

### TextureImportance

• **TextureImportance**: [`SkeletalMeshOptimizationImportance`](../enums/ue_ue.SkeletalMeshOptimizationImportance.md)

___

### VolumeImportance

• **VolumeImportance**: `number`

___

### WeldingThreshold

• **WeldingThreshold**: `number`

___

### \_\_tid\_SkeletalMeshOptimizationSettings\_\_

• `Private` **\_\_tid\_SkeletalMeshOptimizationSettings\_\_**: `boolean`

___

### bEnforceBoneBoundaries

• **bEnforceBoneBoundaries**: `boolean`

___

### bLockEdges

• **bLockEdges**: `boolean`

___

### bRecalcNormals

• **bRecalcNormals**: `boolean`

___

### bRemapMorphTargets

• **bRemapMorphTargets**: `boolean`

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
