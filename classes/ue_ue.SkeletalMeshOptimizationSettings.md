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

#### Defined in

[ue/ue.d.ts:3234](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3234)

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

#### Defined in

[ue/ue.d.ts:3235](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3235)

## Properties

### BakePose

• **BakePose**: [`AnimSequence`](ue_ue.AnimSequence.md)

#### Defined in

[ue/ue.d.ts:3257](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3257)

___

### BaseLOD

• **BaseLOD**: `number`

#### Defined in

[ue/ue.d.ts:3255](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3255)

___

### BonesToRemove

• **BonesToRemove**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneReference`](ue_ue.BoneReference.md)\>

#### Defined in

[ue/ue.d.ts:3256](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3256)

___

### MaxBonesPerVertex

• **MaxBonesPerVertex**: `number`

#### Defined in

[ue/ue.d.ts:3251](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3251)

___

### MaxDeviationPercentage

• **MaxDeviationPercentage**: `number`

#### Defined in

[ue/ue.d.ts:3241](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3241)

___

### MaxNumOfTriangles

• **MaxNumOfTriangles**: `number`

#### Defined in

[ue/ue.d.ts:3239](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3239)

___

### MaxNumOfVerts

• **MaxNumOfVerts**: `number`

#### Defined in

[ue/ue.d.ts:3240](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3240)

___

### NormalsThreshold

• **NormalsThreshold**: `number`

#### Defined in

[ue/ue.d.ts:3250](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3250)

___

### NumOfTrianglesPercentage

• **NumOfTrianglesPercentage**: `number`

#### Defined in

[ue/ue.d.ts:3237](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3237)

___

### NumOfVertPercentage

• **NumOfVertPercentage**: `number`

#### Defined in

[ue/ue.d.ts:3238](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3238)

___

### ReductionMethod

• **ReductionMethod**: [`SkeletalMeshOptimizationType`](../enums/ue_ue.SkeletalMeshOptimizationType.md)

#### Defined in

[ue/ue.d.ts:3242](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3242)

___

### ShadingImportance

• **ShadingImportance**: [`SkeletalMeshOptimizationImportance`](../enums/ue_ue.SkeletalMeshOptimizationImportance.md)

#### Defined in

[ue/ue.d.ts:3245](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3245)

___

### SilhouetteImportance

• **SilhouetteImportance**: [`SkeletalMeshOptimizationImportance`](../enums/ue_ue.SkeletalMeshOptimizationImportance.md)

#### Defined in

[ue/ue.d.ts:3243](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3243)

___

### SkinningImportance

• **SkinningImportance**: [`SkeletalMeshOptimizationImportance`](../enums/ue_ue.SkeletalMeshOptimizationImportance.md)

#### Defined in

[ue/ue.d.ts:3246](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3246)

___

### TerminationCriterion

• **TerminationCriterion**: [`SkeletalMeshTerminationCriterion`](../enums/ue_ue.SkeletalMeshTerminationCriterion.md)

#### Defined in

[ue/ue.d.ts:3236](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3236)

___

### TextureImportance

• **TextureImportance**: [`SkeletalMeshOptimizationImportance`](../enums/ue_ue.SkeletalMeshOptimizationImportance.md)

#### Defined in

[ue/ue.d.ts:3244](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3244)

___

### VolumeImportance

• **VolumeImportance**: `number`

#### Defined in

[ue/ue.d.ts:3253](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3253)

___

### WeldingThreshold

• **WeldingThreshold**: `number`

#### Defined in

[ue/ue.d.ts:3249](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3249)

___

### \_\_tid\_SkeletalMeshOptimizationSettings\_\_

• `Private` **\_\_tid\_SkeletalMeshOptimizationSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3263](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3263)

___

### bEnforceBoneBoundaries

• **bEnforceBoneBoundaries**: `boolean`

#### Defined in

[ue/ue.d.ts:3252](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3252)

___

### bLockEdges

• **bLockEdges**: `boolean`

#### Defined in

[ue/ue.d.ts:3254](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3254)

___

### bRecalcNormals

• **bRecalcNormals**: `boolean`

#### Defined in

[ue/ue.d.ts:3248](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3248)

___

### bRemapMorphTargets

• **bRemapMorphTargets**: `boolean`

#### Defined in

[ue/ue.d.ts:3247](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3247)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:3261](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3261)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:3262](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3262)
