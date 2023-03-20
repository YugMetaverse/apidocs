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

#### Defined in

[ue/ue.d.ts:17822](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17822)

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

#### Defined in

[ue/ue.d.ts:17823](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17823)

## Properties

### ActualAlpha

• **ActualAlpha**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ActualAlpha](ue_ue.AnimNode_SkeletalControlBase.md#actualalpha)

#### Defined in

[ue/ue.d.ts:17717](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17717)

___

### Alpha

• **Alpha**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[Alpha](ue_ue.AnimNode_SkeletalControlBase.md#alpha)

#### Defined in

[ue/ue.d.ts:17720](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17720)

___

### AlphaBoolBlend

• **AlphaBoolBlend**: [`InputAlphaBoolBlend`](ue_ue.InputAlphaBoolBlend.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaBoolBlend](ue_ue.AnimNode_SkeletalControlBase.md#alphaboolblend)

#### Defined in

[ue/ue.d.ts:17722](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17722)

___

### AlphaCurveName

• **AlphaCurveName**: `string`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaCurveName](ue_ue.AnimNode_SkeletalControlBase.md#alphacurvename)

#### Defined in

[ue/ue.d.ts:17723](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17723)

___

### AlphaInputType

• **AlphaInputType**: [`EAnimAlphaInputType`](../enums/ue_ue.EAnimAlphaInputType.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaInputType](ue_ue.AnimNode_SkeletalControlBase.md#alphainputtype)

#### Defined in

[ue/ue.d.ts:17718](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17718)

___

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaScaleBias](ue_ue.AnimNode_SkeletalControlBase.md#alphascalebias)

#### Defined in

[ue/ue.d.ts:17721](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17721)

___

### AlphaScaleBiasClamp

• **AlphaScaleBiasClamp**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaScaleBiasClamp](ue_ue.AnimNode_SkeletalControlBase.md#alphascalebiasclamp)

#### Defined in

[ue/ue.d.ts:17724](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17724)

___

### AngularBiasOverride

• **AngularBiasOverride**: `number`

#### Defined in

[ue/ue.d.ts:17839](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17839)

___

### AngularDampingOverride

• **AngularDampingOverride**: `number`

#### Defined in

[ue/ue.d.ts:17825](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17825)

___

### AngularSpringConstant

• **AngularSpringConstant**: `number`

#### Defined in

[ue/ue.d.ts:17834](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17834)

___

### BoundBone

• **BoundBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:17827](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17827)

___

### BoxExtents

• **BoxExtents**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:17829](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17829)

___

### ChainEnd

• **ChainEnd**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:17828](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17828)

___

### CollisionType

• **CollisionType**: [`AnimPhysCollisionType`](../enums/ue_ue.AnimPhysCollisionType.md)

#### Defined in

[ue/ue.d.ts:17847](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17847)

___

### ComponentAppliedLinearAccClamp

• **ComponentAppliedLinearAccClamp**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:17838](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17838)

___

### ComponentLinearAccScale

• **ComponentLinearAccScale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:17836](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17836)

___

### ComponentLinearVelScale

• **ComponentLinearVelScale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:17837](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17837)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

#### Defined in

[ue/ue.d.ts:17715](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17715)

___

### ConstraintSetup

• **ConstraintSetup**: [`AnimPhysConstraintSetup`](ue_ue.AnimPhysConstraintSetup.md)

#### Defined in

[ue/ue.d.ts:17842](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17842)

___

### ExternalForce

• **ExternalForce**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:17845](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17845)

___

### GravityOverride

• **GravityOverride**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:17832](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17832)

___

### GravityScale

• **GravityScale**: `number`

#### Defined in

[ue/ue.d.ts:17831](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17831)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17716)

___

### LinearDampingOverride

• **LinearDampingOverride**: `number`

#### Defined in

[ue/ue.d.ts:17824](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17824)

___

### LinearSpringConstant

• **LinearSpringConstant**: `number`

#### Defined in

[ue/ue.d.ts:17833](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17833)

___

### LocalJointOffset

• **LocalJointOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:17830](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17830)

___

### NumSolverIterationsPostUpdate

• **NumSolverIterationsPostUpdate**: `number`

#### Defined in

[ue/ue.d.ts:17841](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17841)

___

### NumSolverIterationsPreUpdate

• **NumSolverIterationsPreUpdate**: `number`

#### Defined in

[ue/ue.d.ts:17840](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17840)

___

### PlanarLimits

• **PlanarLimits**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimPhysPlanarLimit`](ue_ue.AnimPhysPlanarLimit.md)\>

#### Defined in

[ue/ue.d.ts:17846](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17846)

___

### RelativeSpaceBone

• **RelativeSpaceBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:17826](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17826)

___

### RetargetingSettings

• **RetargetingSettings**: [`RotationRetargetingInfo`](ue_ue.RotationRetargetingInfo.md)

#### Defined in

[ue/ue.d.ts:17861](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17861)

___

### SimulationSpace

• **SimulationSpace**: [`AnimPhysSimSpaceType`](../enums/ue_ue.AnimPhysSimSpaceType.md)

#### Defined in

[ue/ue.d.ts:17848](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17848)

___

### SphereCollisionRadius

• **SphereCollisionRadius**: `number`

#### Defined in

[ue/ue.d.ts:17844](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17844)

___

### SphericalLimits

• **SphericalLimits**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimPhysSphericalLimit`](ue_ue.AnimPhysSphericalLimit.md)\>

#### Defined in

[ue/ue.d.ts:17843](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17843)

___

### WindScale

• **WindScale**: `number`

#### Defined in

[ue/ue.d.ts:17835](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17835)

___

### \_\_tid\_AnimNode\_AnimDynamics\_\_

• `Private` **\_\_tid\_AnimNode\_AnimDynamics\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:17867](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17867)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17719)

___

### bAngularSpring

• **bAngularSpring**: `boolean`

#### Defined in

[ue/ue.d.ts:17859](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17859)

___

### bChain

• **bChain**: `boolean`

#### Defined in

[ue/ue.d.ts:17860](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17860)

___

### bDoEval

• **bDoEval**: `boolean`

#### Defined in

[ue/ue.d.ts:17852](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17852)

___

### bDoUpdate

• **bDoUpdate**: `boolean`

#### Defined in

[ue/ue.d.ts:17851](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17851)

___

### bEnableWind

• **bEnableWind**: `boolean`

#### Defined in

[ue/ue.d.ts:17856](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17856)

___

### bLinearSpring

• **bLinearSpring**: `boolean`

#### Defined in

[ue/ue.d.ts:17858](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17858)

___

### bOverrideAngularBias

• **bOverrideAngularBias**: `boolean`

#### Defined in

[ue/ue.d.ts:17854](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17854)

___

### bOverrideAngularDamping

• **bOverrideAngularDamping**: `boolean`

#### Defined in

[ue/ue.d.ts:17855](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17855)

___

### bOverrideLinearDamping

• **bOverrideLinearDamping**: `boolean`

#### Defined in

[ue/ue.d.ts:17853](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17853)

___

### bUseGravityOverride

• **bUseGravityOverride**: `boolean`

#### Defined in

[ue/ue.d.ts:17857](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17857)

___

### bUsePlanarLimit

• **bUsePlanarLimit**: `boolean`

#### Defined in

[ue/ue.d.ts:17850](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17850)

___

### bUseSphericalLimits

• **bUseSphericalLimits**: `boolean`

#### Defined in

[ue/ue.d.ts:17849](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17849)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticClass](ue_ue.AnimNode_SkeletalControlBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:17865](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17865)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:17866](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17866)
