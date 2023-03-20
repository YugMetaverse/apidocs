[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_RigidBody

# Class: AnimNode\_RigidBody

[ue/ue](../modules/ue_ue.md).AnimNode_RigidBody

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_RigidBody`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_RigidBody.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_RigidBody.md#actualalpha)
- [Alpha](ue_ue.AnimNode_RigidBody.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_RigidBody.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_RigidBody.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_RigidBody.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_RigidBody.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_RigidBody.md#alphascalebiasclamp)
- [BaseBoneRef](ue_ue.AnimNode_RigidBody.md#baseboneref)
- [CachedBoundsScale](ue_ue.AnimNode_RigidBody.md#cachedboundsscale)
- [ComponentAppliedLinearAccClamp](ue_ue.AnimNode_RigidBody.md#componentappliedlinearaccclamp)
- [ComponentLinearAccScale](ue_ue.AnimNode_RigidBody.md#componentlinearaccscale)
- [ComponentLinearVelScale](ue_ue.AnimNode_RigidBody.md#componentlinearvelscale)
- [ComponentPose](ue_ue.AnimNode_RigidBody.md#componentpose)
- [ExternalForce](ue_ue.AnimNode_RigidBody.md#externalforce)
- [LODThreshold](ue_ue.AnimNode_RigidBody.md#lodthreshold)
- [OverlapChannel](ue_ue.AnimNode_RigidBody.md#overlapchannel)
- [OverridePhysicsAsset](ue_ue.AnimNode_RigidBody.md#overridephysicsasset)
- [OverrideWorldGravity](ue_ue.AnimNode_RigidBody.md#overrideworldgravity)
- [SimulationSpace](ue_ue.AnimNode_RigidBody.md#simulationspace)
- [\_\_tid\_AnimNode\_RigidBody\_\_](ue_ue.AnimNode_RigidBody.md#__tid_animnode_rigidbody__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_RigidBody.md#balphaboolenabled)
- [bClampLinearTranslationLimitToRefPose](ue_ue.AnimNode_RigidBody.md#bclamplineartranslationlimittorefpose)
- [bComponentSpaceSimulation](ue_ue.AnimNode_RigidBody.md#bcomponentspacesimulation)
- [bEnableWorldGeometry](ue_ue.AnimNode_RigidBody.md#benableworldgeometry)
- [bForceDisableCollisionBetweenConstraintBodies](ue_ue.AnimNode_RigidBody.md#bforcedisablecollisionbetweenconstraintbodies)
- [bFreezeIncomingPoseOnStart](ue_ue.AnimNode_RigidBody.md#bfreezeincomingposeonstart)
- [bOverrideWorldGravity](ue_ue.AnimNode_RigidBody.md#boverrideworldgravity)
- [bTransferBoneVelocities](ue_ue.AnimNode_RigidBody.md#btransferbonevelocities)

### Methods

- [StaticClass](ue_ue.AnimNode_RigidBody.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_RigidBody.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_RigidBody**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

• **new AnimNode_RigidBody**(`OverridePhysicsAsset`, `OverrideWorldGravity`, `ExternalForce`, `ComponentLinearAccScale`, `ComponentLinearVelScale`, `ComponentAppliedLinearAccClamp`, `CachedBoundsScale`, `BaseBoneRef`, `OverlapChannel`, `SimulationSpace`, `bForceDisableCollisionBetweenConstraintBodies`, `bEnableWorldGeometry`, `bOverrideWorldGravity`, `bTransferBoneVelocities`, `bFreezeIncomingPoseOnStart`, `bClampLinearTranslationLimitToRefPose`, `bComponentSpaceSimulation`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OverridePhysicsAsset` | [`PhysicsAsset`](ue_ue.PhysicsAsset.md) |
| `OverrideWorldGravity` | [`Vector`](ue_ue_s.Vector.md) |
| `ExternalForce` | [`Vector`](ue_ue_s.Vector.md) |
| `ComponentLinearAccScale` | [`Vector`](ue_ue_s.Vector.md) |
| `ComponentLinearVelScale` | [`Vector`](ue_ue_s.Vector.md) |
| `ComponentAppliedLinearAccClamp` | [`Vector`](ue_ue_s.Vector.md) |
| `CachedBoundsScale` | `number` |
| `BaseBoneRef` | [`BoneReference`](ue_ue.BoneReference.md) |
| `OverlapChannel` | [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md) |
| `SimulationSpace` | [`ESimulationSpace`](../enums/ue_ue.ESimulationSpace.md) |
| `bForceDisableCollisionBetweenConstraintBodies` | `boolean` |
| `bEnableWorldGeometry` | `boolean` |
| `bOverrideWorldGravity` | `boolean` |
| `bTransferBoneVelocities` | `boolean` |
| `bFreezeIncomingPoseOnStart` | `boolean` |
| `bClampLinearTranslationLimitToRefPose` | `boolean` |
| `bComponentSpaceSimulation` | `boolean` |

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

### BaseBoneRef

• **BaseBoneRef**: [`BoneReference`](ue_ue.BoneReference.md)

___

### CachedBoundsScale

• **CachedBoundsScale**: `number`

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

### ExternalForce

• **ExternalForce**: [`Vector`](ue_ue_s.Vector.md)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

___

### OverlapChannel

• **OverlapChannel**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

___

### OverridePhysicsAsset

• **OverridePhysicsAsset**: [`PhysicsAsset`](ue_ue.PhysicsAsset.md)

___

### OverrideWorldGravity

• **OverrideWorldGravity**: [`Vector`](ue_ue_s.Vector.md)

___

### SimulationSpace

• **SimulationSpace**: [`ESimulationSpace`](../enums/ue_ue.ESimulationSpace.md)

___

### \_\_tid\_AnimNode\_RigidBody\_\_

• `Private` **\_\_tid\_AnimNode\_RigidBody\_\_**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

___

### bClampLinearTranslationLimitToRefPose

• **bClampLinearTranslationLimitToRefPose**: `boolean`

___

### bComponentSpaceSimulation

• **bComponentSpaceSimulation**: `boolean`

___

### bEnableWorldGeometry

• **bEnableWorldGeometry**: `boolean`

___

### bForceDisableCollisionBetweenConstraintBodies

• **bForceDisableCollisionBetweenConstraintBodies**: `boolean`

___

### bFreezeIncomingPoseOnStart

• **bFreezeIncomingPoseOnStart**: `boolean`

___

### bOverrideWorldGravity

• **bOverrideWorldGravity**: `boolean`

___

### bTransferBoneVelocities

• **bTransferBoneVelocities**: `boolean`

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
