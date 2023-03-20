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

#### Defined in

[ue/ue.d.ts:19331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19331)

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

#### Defined in

[ue/ue.d.ts:19332](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19332)

## Properties

### ActualAlpha

• **ActualAlpha**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ActualAlpha](ue_ue.AnimNode_SkeletalControlBase.md#actualalpha)

#### Defined in

[ue/ue.d.ts:17717](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17717)

___

### Alpha

• **Alpha**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[Alpha](ue_ue.AnimNode_SkeletalControlBase.md#alpha)

#### Defined in

[ue/ue.d.ts:17720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17720)

___

### AlphaBoolBlend

• **AlphaBoolBlend**: [`InputAlphaBoolBlend`](ue_ue.InputAlphaBoolBlend.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaBoolBlend](ue_ue.AnimNode_SkeletalControlBase.md#alphaboolblend)

#### Defined in

[ue/ue.d.ts:17722](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17722)

___

### AlphaCurveName

• **AlphaCurveName**: `string`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaCurveName](ue_ue.AnimNode_SkeletalControlBase.md#alphacurvename)

#### Defined in

[ue/ue.d.ts:17723](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17723)

___

### AlphaInputType

• **AlphaInputType**: [`EAnimAlphaInputType`](../enums/ue_ue.EAnimAlphaInputType.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaInputType](ue_ue.AnimNode_SkeletalControlBase.md#alphainputtype)

#### Defined in

[ue/ue.d.ts:17718](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17718)

___

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaScaleBias](ue_ue.AnimNode_SkeletalControlBase.md#alphascalebias)

#### Defined in

[ue/ue.d.ts:17721](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17721)

___

### AlphaScaleBiasClamp

• **AlphaScaleBiasClamp**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[AlphaScaleBiasClamp](ue_ue.AnimNode_SkeletalControlBase.md#alphascalebiasclamp)

#### Defined in

[ue/ue.d.ts:17724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17724)

___

### BaseBoneRef

• **BaseBoneRef**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:19340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19340)

___

### CachedBoundsScale

• **CachedBoundsScale**: `number`

#### Defined in

[ue/ue.d.ts:19339](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19339)

___

### ComponentAppliedLinearAccClamp

• **ComponentAppliedLinearAccClamp**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:19338](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19338)

___

### ComponentLinearAccScale

• **ComponentLinearAccScale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:19336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19336)

___

### ComponentLinearVelScale

• **ComponentLinearVelScale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:19337](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19337)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

#### Defined in

[ue/ue.d.ts:17715](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17715)

___

### ExternalForce

• **ExternalForce**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:19335](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19335)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17716)

___

### OverlapChannel

• **OverlapChannel**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Defined in

[ue/ue.d.ts:19341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19341)

___

### OverridePhysicsAsset

• **OverridePhysicsAsset**: [`PhysicsAsset`](ue_ue.PhysicsAsset.md)

#### Defined in

[ue/ue.d.ts:19333](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19333)

___

### OverrideWorldGravity

• **OverrideWorldGravity**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:19334](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19334)

___

### SimulationSpace

• **SimulationSpace**: [`ESimulationSpace`](../enums/ue_ue.ESimulationSpace.md)

#### Defined in

[ue/ue.d.ts:19342](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19342)

___

### \_\_tid\_AnimNode\_RigidBody\_\_

• `Private` **\_\_tid\_AnimNode\_RigidBody\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19355](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19355)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17719)

___

### bClampLinearTranslationLimitToRefPose

• **bClampLinearTranslationLimitToRefPose**: `boolean`

#### Defined in

[ue/ue.d.ts:19348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19348)

___

### bComponentSpaceSimulation

• **bComponentSpaceSimulation**: `boolean`

#### Defined in

[ue/ue.d.ts:19349](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19349)

___

### bEnableWorldGeometry

• **bEnableWorldGeometry**: `boolean`

#### Defined in

[ue/ue.d.ts:19344](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19344)

___

### bForceDisableCollisionBetweenConstraintBodies

• **bForceDisableCollisionBetweenConstraintBodies**: `boolean`

#### Defined in

[ue/ue.d.ts:19343](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19343)

___

### bFreezeIncomingPoseOnStart

• **bFreezeIncomingPoseOnStart**: `boolean`

#### Defined in

[ue/ue.d.ts:19347](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19347)

___

### bOverrideWorldGravity

• **bOverrideWorldGravity**: `boolean`

#### Defined in

[ue/ue.d.ts:19345](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19345)

___

### bTransferBoneVelocities

• **bTransferBoneVelocities**: `boolean`

#### Defined in

[ue/ue.d.ts:19346](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19346)

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

[ue/ue.d.ts:19353](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19353)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19354](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19354)
