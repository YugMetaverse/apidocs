[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_Trail

# Class: AnimNode\_Trail

[ue/ue](../modules/ue_ue.md).AnimNode_Trail

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_Trail`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_Trail.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_Trail.md#actualalpha)
- [Alpha](ue_ue.AnimNode_Trail.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_Trail.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_Trail.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_Trail.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_Trail.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_Trail.md#alphascalebiasclamp)
- [BaseJoint](ue_ue.AnimNode_Trail.md#basejoint)
- [ChainBoneAxis](ue_ue.AnimNode_Trail.md#chainboneaxis)
- [ChainLength](ue_ue.AnimNode_Trail.md#chainlength)
- [ComponentPose](ue_ue.AnimNode_Trail.md#componentpose)
- [DebugLifeTime](ue_ue.AnimNode_Trail.md#debuglifetime)
- [FakeVelocity](ue_ue.AnimNode_Trail.md#fakevelocity)
- [LODThreshold](ue_ue.AnimNode_Trail.md#lodthreshold)
- [LastBoneRotationAnimAlphaBlend](ue_ue.AnimNode_Trail.md#lastbonerotationanimalphablend)
- [MaxDeltaTime](ue_ue.AnimNode_Trail.md#maxdeltatime)
- [PlanarLimits](ue_ue.AnimNode_Trail.md#planarlimits)
- [RelaxationSpeedScale](ue_ue.AnimNode_Trail.md#relaxationspeedscale)
- [RelaxationSpeedScaleInputProcessor](ue_ue.AnimNode_Trail.md#relaxationspeedscaleinputprocessor)
- [RotationLimits](ue_ue.AnimNode_Trail.md#rotationlimits)
- [RotationOffsets](ue_ue.AnimNode_Trail.md#rotationoffsets)
- [StretchLimit](ue_ue.AnimNode_Trail.md#stretchlimit)
- [TrailBone](ue_ue.AnimNode_Trail.md#trailbone)
- [TrailBoneRotationBlendAlpha](ue_ue.AnimNode_Trail.md#trailbonerotationblendalpha)
- [TrailRelaxation](ue_ue.AnimNode_Trail.md#trailrelaxation)
- [TrailRelaxationSpeed](ue_ue.AnimNode_Trail.md#trailrelaxationspeed)
- [\_\_tid\_AnimNode\_Trail\_\_](ue_ue.AnimNode_Trail.md#__tid_animnode_trail__)
- [bActorSpaceFakeVel](ue_ue.AnimNode_Trail.md#bactorspacefakevel)
- [bAlphaBoolEnabled](ue_ue.AnimNode_Trail.md#balphaboolenabled)
- [bEnableDebug](ue_ue.AnimNode_Trail.md#benabledebug)
- [bInvertChainBoneAxis](ue_ue.AnimNode_Trail.md#binvertchainboneaxis)
- [bLimitRotation](ue_ue.AnimNode_Trail.md#blimitrotation)
- [bLimitStretch](ue_ue.AnimNode_Trail.md#blimitstretch)
- [bReorientParentToChild](ue_ue.AnimNode_Trail.md#breorientparenttochild)
- [bShowBaseMotion](ue_ue.AnimNode_Trail.md#bshowbasemotion)
- [bShowLimit](ue_ue.AnimNode_Trail.md#bshowlimit)
- [bShowTrailLocation](ue_ue.AnimNode_Trail.md#bshowtraillocation)
- [bUsePlanarLimit](ue_ue.AnimNode_Trail.md#buseplanarlimit)

### Methods

- [StaticClass](ue_ue.AnimNode_Trail.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_Trail.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_Trail**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

• **new AnimNode_Trail**(`TrailBone`, `ChainLength`, `ChainBoneAxis`, `bInvertChainBoneAxis`, `bLimitStretch`, `bLimitRotation`, `bUsePlanarLimit`, `bActorSpaceFakeVel`, `bReorientParentToChild`, `bEnableDebug`, `bShowBaseMotion`, `bShowTrailLocation`, `bShowLimit`, `DebugLifeTime`, `TrailRelaxation`, `MaxDeltaTime`, `RelaxationSpeedScale`, `TrailRelaxationSpeed`, `RelaxationSpeedScaleInputProcessor`, `RotationLimits`, `RotationOffsets`, `PlanarLimits`, `StretchLimit`, `FakeVelocity`, `BaseJoint`, `TrailBoneRotationBlendAlpha`, `LastBoneRotationAnimAlphaBlend`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TrailBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `ChainLength` | `number` |
| `ChainBoneAxis` | [`EAxis`](../enums/ue_ue.EAxis.md) |
| `bInvertChainBoneAxis` | `boolean` |
| `bLimitStretch` | `boolean` |
| `bLimitRotation` | `boolean` |
| `bUsePlanarLimit` | `boolean` |
| `bActorSpaceFakeVel` | `boolean` |
| `bReorientParentToChild` | `boolean` |
| `bEnableDebug` | `boolean` |
| `bShowBaseMotion` | `boolean` |
| `bShowTrailLocation` | `boolean` |
| `bShowLimit` | `boolean` |
| `DebugLifeTime` | `number` |
| `TrailRelaxation` | `number` |
| `MaxDeltaTime` | `number` |
| `RelaxationSpeedScale` | `number` |
| `TrailRelaxationSpeed` | [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md) |
| `RelaxationSpeedScaleInputProcessor` | [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md) |
| `RotationLimits` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RotationLimit`](ue_ue.RotationLimit.md)\> |
| `RotationOffsets` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `PlanarLimits` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimPhysPlanarLimit`](ue_ue.AnimPhysPlanarLimit.md)\> |
| `StretchLimit` | `number` |
| `FakeVelocity` | [`Vector`](ue_ue_s.Vector.md) |
| `BaseJoint` | [`BoneReference`](ue_ue.BoneReference.md) |
| `TrailBoneRotationBlendAlpha` | `number` |
| `LastBoneRotationAnimAlphaBlend` | `number` |

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

### BaseJoint

• **BaseJoint**: [`BoneReference`](ue_ue.BoneReference.md)

___

### ChainBoneAxis

• **ChainBoneAxis**: [`EAxis`](../enums/ue_ue.EAxis.md)

___

### ChainLength

• **ChainLength**: `number`

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

___

### DebugLifeTime

• **DebugLifeTime**: `number`

___

### FakeVelocity

• **FakeVelocity**: [`Vector`](ue_ue_s.Vector.md)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

___

### LastBoneRotationAnimAlphaBlend

• **LastBoneRotationAnimAlphaBlend**: `number`

___

### MaxDeltaTime

• **MaxDeltaTime**: `number`

___

### PlanarLimits

• **PlanarLimits**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimPhysPlanarLimit`](ue_ue.AnimPhysPlanarLimit.md)\>

___

### RelaxationSpeedScale

• **RelaxationSpeedScale**: `number`

___

### RelaxationSpeedScaleInputProcessor

• **RelaxationSpeedScaleInputProcessor**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

___

### RotationLimits

• **RotationLimits**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RotationLimit`](ue_ue.RotationLimit.md)\>

___

### RotationOffsets

• **RotationOffsets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

___

### StretchLimit

• **StretchLimit**: `number`

___

### TrailBone

• **TrailBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### TrailBoneRotationBlendAlpha

• **TrailBoneRotationBlendAlpha**: `number`

___

### TrailRelaxation

• **TrailRelaxation**: `number`

___

### TrailRelaxationSpeed

• **TrailRelaxationSpeed**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

___

### \_\_tid\_AnimNode\_Trail\_\_

• `Private` **\_\_tid\_AnimNode\_Trail\_\_**: `boolean`

___

### bActorSpaceFakeVel

• **bActorSpaceFakeVel**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

___

### bEnableDebug

• **bEnableDebug**: `boolean`

___

### bInvertChainBoneAxis

• **bInvertChainBoneAxis**: `boolean`

___

### bLimitRotation

• **bLimitRotation**: `boolean`

___

### bLimitStretch

• **bLimitStretch**: `boolean`

___

### bReorientParentToChild

• **bReorientParentToChild**: `boolean`

___

### bShowBaseMotion

• **bShowBaseMotion**: `boolean`

___

### bShowLimit

• **bShowLimit**: `boolean`

___

### bShowTrailLocation

• **bShowTrailLocation**: `boolean`

___

### bUsePlanarLimit

• **bUsePlanarLimit**: `boolean`

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
