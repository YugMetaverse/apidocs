[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_AnimDynamics

# Class: AnimNode\_AnimDynamics

[ue/ue](../modules/ue_ue.md).AnimNode_AnimDynamics

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_AnimDynamics`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_AnimDynamics.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_AnimDynamics.md#actualalpha)
- [Alpha](ue_ue.AnimNode_AnimDynamics.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_AnimDynamics.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_AnimDynamics.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_AnimDynamics.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_AnimDynamics.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_AnimDynamics.md#alphascalebiasclamp)
- [AngularBiasOverride](ue_ue.AnimNode_AnimDynamics.md#angularbiasoverride)
- [AngularDampingOverride](ue_ue.AnimNode_AnimDynamics.md#angulardampingoverride)
- [AngularSpringConstant](ue_ue.AnimNode_AnimDynamics.md#angularspringconstant)
- [BoundBone](ue_ue.AnimNode_AnimDynamics.md#boundbone)
- [BoxExtents](ue_ue.AnimNode_AnimDynamics.md#boxextents)
- [ChainEnd](ue_ue.AnimNode_AnimDynamics.md#chainend)
- [CollisionType](ue_ue.AnimNode_AnimDynamics.md#collisiontype)
- [ComponentAppliedLinearAccClamp](ue_ue.AnimNode_AnimDynamics.md#componentappliedlinearaccclamp)
- [ComponentLinearAccScale](ue_ue.AnimNode_AnimDynamics.md#componentlinearaccscale)
- [ComponentLinearVelScale](ue_ue.AnimNode_AnimDynamics.md#componentlinearvelscale)
- [ComponentPose](ue_ue.AnimNode_AnimDynamics.md#componentpose)
- [ConstraintSetup](ue_ue.AnimNode_AnimDynamics.md#constraintsetup)
- [ExternalForce](ue_ue.AnimNode_AnimDynamics.md#externalforce)
- [GravityOverride](ue_ue.AnimNode_AnimDynamics.md#gravityoverride)
- [GravityScale](ue_ue.AnimNode_AnimDynamics.md#gravityscale)
- [LODThreshold](ue_ue.AnimNode_AnimDynamics.md#lodthreshold)
- [LinearDampingOverride](ue_ue.AnimNode_AnimDynamics.md#lineardampingoverride)
- [LinearSpringConstant](ue_ue.AnimNode_AnimDynamics.md#linearspringconstant)
- [LocalJointOffset](ue_ue.AnimNode_AnimDynamics.md#localjointoffset)
- [NumSolverIterationsPostUpdate](ue_ue.AnimNode_AnimDynamics.md#numsolveriterationspostupdate)
- [NumSolverIterationsPreUpdate](ue_ue.AnimNode_AnimDynamics.md#numsolveriterationspreupdate)
- [PlanarLimits](ue_ue.AnimNode_AnimDynamics.md#planarlimits)
- [RelativeSpaceBone](ue_ue.AnimNode_AnimDynamics.md#relativespacebone)
- [RetargetingSettings](ue_ue.AnimNode_AnimDynamics.md#retargetingsettings)
- [SimulationSpace](ue_ue.AnimNode_AnimDynamics.md#simulationspace)
- [SphereCollisionRadius](ue_ue.AnimNode_AnimDynamics.md#spherecollisionradius)
- [SphericalLimits](ue_ue.AnimNode_AnimDynamics.md#sphericallimits)
- [WindScale](ue_ue.AnimNode_AnimDynamics.md#windscale)
- [\_\_tid\_AnimNode\_AnimDynamics\_\_](ue_ue.AnimNode_AnimDynamics.md#__tid_animnode_animdynamics__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_AnimDynamics.md#balphaboolenabled)
- [bAngularSpring](ue_ue.AnimNode_AnimDynamics.md#bangularspring)
- [bChain](ue_ue.AnimNode_AnimDynamics.md#bchain)
- [bDoEval](ue_ue.AnimNode_AnimDynamics.md#bdoeval)
- [bDoUpdate](ue_ue.AnimNode_AnimDynamics.md#bdoupdate)
- [bEnableWind](ue_ue.AnimNode_AnimDynamics.md#benablewind)
- [bLinearSpring](ue_ue.AnimNode_AnimDynamics.md#blinearspring)
- [bOverrideAngularBias](ue_ue.AnimNode_AnimDynamics.md#boverrideangularbias)
- [bOverrideAngularDamping](ue_ue.AnimNode_AnimDynamics.md#boverrideangulardamping)
- [bOverrideLinearDamping](ue_ue.AnimNode_AnimDynamics.md#boverridelineardamping)
- [bUseGravityOverride](ue_ue.AnimNode_AnimDynamics.md#busegravityoverride)
- [bUsePlanarLimit](ue_ue.AnimNode_AnimDynamics.md#buseplanarlimit)
- [bUseSphericalLimits](ue_ue.AnimNode_AnimDynamics.md#busesphericallimits)

### Methods

- [StaticClass](ue_ue.AnimNode_AnimDynamics.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_AnimDynamics.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_AnimDynamics**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

• **new AnimNode_AnimDynamics**(`LinearDampingOverride`, `AngularDampingOverride`, `RelativeSpaceBone`, `BoundBone`, `ChainEnd`, `BoxExtents`, `LocalJointOffset`, `GravityScale`, `GravityOverride`, `LinearSpringConstant`, `AngularSpringConstant`, `WindScale`, `ComponentLinearAccScale`, `ComponentLinearVelScale`, `ComponentAppliedLinearAccClamp`, `AngularBiasOverride`, `NumSolverIterationsPreUpdate`, `NumSolverIterationsPostUpdate`, `ConstraintSetup`, `SphericalLimits`, `SphereCollisionRadius`, `ExternalForce`, `PlanarLimits`, `CollisionType`, `SimulationSpace`, `bUseSphericalLimits`, `bUsePlanarLimit`, `bDoUpdate`, `bDoEval`, `bOverrideLinearDamping`, `bOverrideAngularBias`, `bOverrideAngularDamping`, `bEnableWind`, `bUseGravityOverride`, `bLinearSpring`, `bAngularSpring`, `bChain`, `RetargetingSettings`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `LinearDampingOverride` | `number` |
| `AngularDampingOverride` | `number` |
| `RelativeSpaceBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `BoundBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `ChainEnd` | [`BoneReference`](ue_ue.BoneReference.md) |
| `BoxExtents` | [`Vector`](ue_ue_s.Vector.md) |
| `LocalJointOffset` | [`Vector`](ue_ue_s.Vector.md) |
| `GravityScale` | `number` |
| `GravityOverride` | [`Vector`](ue_ue_s.Vector.md) |
| `LinearSpringConstant` | `number` |
| `AngularSpringConstant` | `number` |
| `WindScale` | `number` |
| `ComponentLinearAccScale` | [`Vector`](ue_ue_s.Vector.md) |
| `ComponentLinearVelScale` | [`Vector`](ue_ue_s.Vector.md) |
| `ComponentAppliedLinearAccClamp` | [`Vector`](ue_ue_s.Vector.md) |
| `AngularBiasOverride` | `number` |
| `NumSolverIterationsPreUpdate` | `number` |
| `NumSolverIterationsPostUpdate` | `number` |
| `ConstraintSetup` | [`AnimPhysConstraintSetup`](ue_ue.AnimPhysConstraintSetup.md) |
| `SphericalLimits` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimPhysSphericalLimit`](ue_ue.AnimPhysSphericalLimit.md)\> |
| `SphereCollisionRadius` | `number` |
| `ExternalForce` | [`Vector`](ue_ue_s.Vector.md) |
| `PlanarLimits` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimPhysPlanarLimit`](ue_ue.AnimPhysPlanarLimit.md)\> |
| `CollisionType` | [`AnimPhysCollisionType`](../enums/ue_ue.AnimPhysCollisionType.md) |
| `SimulationSpace` | [`AnimPhysSimSpaceType`](../enums/ue_ue.AnimPhysSimSpaceType.md) |
| `bUseSphericalLimits` | `boolean` |
| `bUsePlanarLimit` | `boolean` |
| `bDoUpdate` | `boolean` |
| `bDoEval` | `boolean` |
| `bOverrideLinearDamping` | `boolean` |
| `bOverrideAngularBias` | `boolean` |
| `bOverrideAngularDamping` | `boolean` |
| `bEnableWind` | `boolean` |
| `bUseGravityOverride` | `boolean` |
| `bLinearSpring` | `boolean` |
| `bAngularSpring` | `boolean` |
| `bChain` | `boolean` |
| `RetargetingSettings` | [`RotationRetargetingInfo`](ue_ue.RotationRetargetingInfo.md) |

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

## Properties

### ActualAlpha

• **ActualAlpha**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ActualAlpha](ue_ue.AnimNode_SkeletalControlBase.md#actualalpha)

___

### Alpha

• **Alpha**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[Alpha](ue_ue.AnimNode_SkeletalControlBase.md#alpha)

___

### AlphaBoolBlend

• **AlphaBoolBlend**: [`InputAlphaBoolBlend`](ue_ue.InputAlphaBoolBlend.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaBoolBlend](ue_ue.AnimNode_SkeletalControlBase.md#alphaboolblend)

___

### AlphaCurveName

• **AlphaCurveName**: `string`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaCurveName](ue_ue.AnimNode_SkeletalControlBase.md#alphacurvename)

___

### AlphaInputType

• **AlphaInputType**: [`EAnimAlphaInputType`](../enums/ue_ue.EAnimAlphaInputType.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaInputType](ue_ue.AnimNode_SkeletalControlBase.md#alphainputtype)

___

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaScaleBias](ue_ue.AnimNode_SkeletalControlBase.md#alphascalebias)

___

### AlphaScaleBiasClamp

• **AlphaScaleBiasClamp**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaScaleBiasClamp](ue_ue.AnimNode_SkeletalControlBase.md#alphascalebiasclamp)

___

### AngularBiasOverride

• **AngularBiasOverride**: `number`

___

### AngularDampingOverride

• **AngularDampingOverride**: `number`

___

### AngularSpringConstant

• **AngularSpringConstant**: `number`

___

### BoundBone

• **BoundBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### BoxExtents

• **BoxExtents**: [`Vector`](ue_ue_s.Vector.md)

___

### ChainEnd

• **ChainEnd**: [`BoneReference`](ue_ue.BoneReference.md)

___

### CollisionType

• **CollisionType**: [`AnimPhysCollisionType`](../enums/ue_ue.AnimPhysCollisionType.md)

___

### ComponentAppliedLinearAccClamp

• **ComponentAppliedLinearAccClamp**: [`Vector`](ue_ue_s.Vector.md)

___

### ComponentLinearAccScale

• **ComponentLinearAccScale**: [`Vector`](ue_ue_s.Vector.md)

___

### ComponentLinearVelScale

• **ComponentLinearVelScale**: [`Vector`](ue_ue_s.Vector.md)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

___

### ConstraintSetup

• **ConstraintSetup**: [`AnimPhysConstraintSetup`](ue_ue.AnimPhysConstraintSetup.md)

___

### ExternalForce

• **ExternalForce**: [`Vector`](ue_ue_s.Vector.md)

___

### GravityOverride

• **GravityOverride**: [`Vector`](ue_ue_s.Vector.md)

___

### GravityScale

• **GravityScale**: `number`

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

___

### LinearDampingOverride

• **LinearDampingOverride**: `number`

___

### LinearSpringConstant

• **LinearSpringConstant**: `number`

___

### LocalJointOffset

• **LocalJointOffset**: [`Vector`](ue_ue_s.Vector.md)

___

### NumSolverIterationsPostUpdate

• **NumSolverIterationsPostUpdate**: `number`

___

### NumSolverIterationsPreUpdate

• **NumSolverIterationsPreUpdate**: `number`

___

### PlanarLimits

• **PlanarLimits**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimPhysPlanarLimit`](ue_ue.AnimPhysPlanarLimit.md)\>

___

### RelativeSpaceBone

• **RelativeSpaceBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### RetargetingSettings

• **RetargetingSettings**: [`RotationRetargetingInfo`](ue_ue.RotationRetargetingInfo.md)

___

### SimulationSpace

• **SimulationSpace**: [`AnimPhysSimSpaceType`](../enums/ue_ue.AnimPhysSimSpaceType.md)

___

### SphereCollisionRadius

• **SphereCollisionRadius**: `number`

___

### SphericalLimits

• **SphericalLimits**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimPhysSphericalLimit`](ue_ue.AnimPhysSphericalLimit.md)\>

___

### WindScale

• **WindScale**: `number`

___

### \_\_tid\_AnimNode\_AnimDynamics\_\_

• `Private` **\_\_tid\_AnimNode\_AnimDynamics\_\_**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

___

### bAngularSpring

• **bAngularSpring**: `boolean`

___

### bChain

• **bChain**: `boolean`

___

### bDoEval

• **bDoEval**: `boolean`

___

### bDoUpdate

• **bDoUpdate**: `boolean`

___

### bEnableWind

• **bEnableWind**: `boolean`

___

### bLinearSpring

• **bLinearSpring**: `boolean`

___

### bOverrideAngularBias

• **bOverrideAngularBias**: `boolean`

___

### bOverrideAngularDamping

• **bOverrideAngularDamping**: `boolean`

___

### bOverrideLinearDamping

• **bOverrideLinearDamping**: `boolean`

___

### bUseGravityOverride

• **bUseGravityOverride**: `boolean`

___

### bUsePlanarLimit

• **bUsePlanarLimit**: `boolean`

___

### bUseSphericalLimits

• **bUseSphericalLimits**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticClass](ue_ue.AnimNode_SkeletalControlBase.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)
