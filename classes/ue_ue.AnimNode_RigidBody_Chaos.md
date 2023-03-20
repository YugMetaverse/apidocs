[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_RigidBody\_Chaos

# Class: AnimNode\_RigidBody\_Chaos

[ue/ue](../modules/ue_ue.md).AnimNode_RigidBody_Chaos

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_RigidBody_Chaos`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_RigidBody_Chaos.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_RigidBody_Chaos.md#actualalpha)
- [Alpha](ue_ue.AnimNode_RigidBody_Chaos.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_RigidBody_Chaos.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_RigidBody_Chaos.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_RigidBody_Chaos.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_RigidBody_Chaos.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_RigidBody_Chaos.md#alphascalebiasclamp)
- [BaseBoneRef](ue_ue.AnimNode_RigidBody_Chaos.md#baseboneref)
- [CachedBoundsScale](ue_ue.AnimNode_RigidBody_Chaos.md#cachedboundsscale)
- [ComponentAppliedLinearAccClamp](ue_ue.AnimNode_RigidBody_Chaos.md#componentappliedlinearaccclamp)
- [ComponentLinearAccScale](ue_ue.AnimNode_RigidBody_Chaos.md#componentlinearaccscale)
- [ComponentLinearVelScale](ue_ue.AnimNode_RigidBody_Chaos.md#componentlinearvelscale)
- [ComponentPose](ue_ue.AnimNode_RigidBody_Chaos.md#componentpose)
- [ExternalForce](ue_ue.AnimNode_RigidBody_Chaos.md#externalforce)
- [LODThreshold](ue_ue.AnimNode_RigidBody_Chaos.md#lodthreshold)
- [OverlapChannel](ue_ue.AnimNode_RigidBody_Chaos.md#overlapchannel)
- [OverridePhysicsAsset](ue_ue.AnimNode_RigidBody_Chaos.md#overridephysicsasset)
- [OverrideWorldGravity](ue_ue.AnimNode_RigidBody_Chaos.md#overrideworldgravity)
- [SimulationSpace](ue_ue.AnimNode_RigidBody_Chaos.md#simulationspace)
- [\_\_tid\_AnimNode\_RigidBody\_Chaos\_\_](ue_ue.AnimNode_RigidBody_Chaos.md#__tid_animnode_rigidbody_chaos__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_RigidBody_Chaos.md#balphaboolenabled)
- [bClampLinearTranslationLimitToRefPose](ue_ue.AnimNode_RigidBody_Chaos.md#bclamplineartranslationlimittorefpose)
- [bComponentSpaceSimulation](ue_ue.AnimNode_RigidBody_Chaos.md#bcomponentspacesimulation)
- [bEnableWorldGeometry](ue_ue.AnimNode_RigidBody_Chaos.md#benableworldgeometry)
- [bForceDisableCollisionBetweenConstraintBodies](ue_ue.AnimNode_RigidBody_Chaos.md#bforcedisablecollisionbetweenconstraintbodies)
- [bFreezeIncomingPoseOnStart](ue_ue.AnimNode_RigidBody_Chaos.md#bfreezeincomingposeonstart)
- [bOverrideWorldGravity](ue_ue.AnimNode_RigidBody_Chaos.md#boverrideworldgravity)
- [bTransferBoneVelocities](ue_ue.AnimNode_RigidBody_Chaos.md#btransferbonevelocities)

### Methods

- [StaticClass](ue_ue.AnimNode_RigidBody_Chaos.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_RigidBody_Chaos.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_RigidBody_Chaos**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:19369](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19369)

• **new AnimNode_RigidBody_Chaos**(`OverridePhysicsAsset`, `OverrideWorldGravity`, `ExternalForce`, `ComponentLinearAccScale`, `ComponentLinearVelScale`, `ComponentAppliedLinearAccClamp`, `CachedBoundsScale`, `BaseBoneRef`, `OverlapChannel`, `SimulationSpace`, `bForceDisableCollisionBetweenConstraintBodies`, `bEnableWorldGeometry`, `bOverrideWorldGravity`, `bTransferBoneVelocities`, `bFreezeIncomingPoseOnStart`, `bClampLinearTranslationLimitToRefPose`, `bComponentSpaceSimulation`)

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

[ue/ue.d.ts:19370](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19370)

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

### BaseBoneRef

• **BaseBoneRef**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:19378](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19378)

___

### CachedBoundsScale

• **CachedBoundsScale**: `number`

#### Defined in

[ue/ue.d.ts:19377](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19377)

___

### ComponentAppliedLinearAccClamp

• **ComponentAppliedLinearAccClamp**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:19376](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19376)

___

### ComponentLinearAccScale

• **ComponentLinearAccScale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:19374](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19374)

___

### ComponentLinearVelScale

• **ComponentLinearVelScale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:19375](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19375)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

#### Defined in

[ue/ue.d.ts:17715](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17715)

___

### ExternalForce

• **ExternalForce**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:19373](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19373)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17716)

___

### OverlapChannel

• **OverlapChannel**: [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md)

#### Defined in

[ue/ue.d.ts:19379](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19379)

___

### OverridePhysicsAsset

• **OverridePhysicsAsset**: [`PhysicsAsset`](ue_ue.PhysicsAsset.md)

#### Defined in

[ue/ue.d.ts:19371](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19371)

___

### OverrideWorldGravity

• **OverrideWorldGravity**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:19372](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19372)

___

### SimulationSpace

• **SimulationSpace**: [`ESimulationSpace`](../enums/ue_ue.ESimulationSpace.md)

#### Defined in

[ue/ue.d.ts:19380](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19380)

___

### \_\_tid\_AnimNode\_RigidBody\_Chaos\_\_

• `Private` **\_\_tid\_AnimNode\_RigidBody\_Chaos\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19393](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19393)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17719)

___

### bClampLinearTranslationLimitToRefPose

• **bClampLinearTranslationLimitToRefPose**: `boolean`

#### Defined in

[ue/ue.d.ts:19386](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19386)

___

### bComponentSpaceSimulation

• **bComponentSpaceSimulation**: `boolean`

#### Defined in

[ue/ue.d.ts:19387](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19387)

___

### bEnableWorldGeometry

• **bEnableWorldGeometry**: `boolean`

#### Defined in

[ue/ue.d.ts:19382](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19382)

___

### bForceDisableCollisionBetweenConstraintBodies

• **bForceDisableCollisionBetweenConstraintBodies**: `boolean`

#### Defined in

[ue/ue.d.ts:19381](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19381)

___

### bFreezeIncomingPoseOnStart

• **bFreezeIncomingPoseOnStart**: `boolean`

#### Defined in

[ue/ue.d.ts:19385](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19385)

___

### bOverrideWorldGravity

• **bOverrideWorldGravity**: `boolean`

#### Defined in

[ue/ue.d.ts:19383](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19383)

___

### bTransferBoneVelocities

• **bTransferBoneVelocities**: `boolean`

#### Defined in

[ue/ue.d.ts:19384](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19384)

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

[ue/ue.d.ts:19391](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19391)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19392](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19392)
