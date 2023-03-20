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

#### Defined in

[ue/ue.d.ts:19851](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19851)

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

#### Defined in

[ue/ue.d.ts:19852](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19852)

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

### BaseJoint

• **BaseJoint**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:19877](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19877)

___

### ChainBoneAxis

• **ChainBoneAxis**: [`EAxis`](../enums/ue_ue.EAxis.md)

#### Defined in

[ue/ue.d.ts:19855](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19855)

___

### ChainLength

• **ChainLength**: `number`

#### Defined in

[ue/ue.d.ts:19854](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19854)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

#### Defined in

[ue/ue.d.ts:17715](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17715)

___

### DebugLifeTime

• **DebugLifeTime**: `number`

#### Defined in

[ue/ue.d.ts:19866](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19866)

___

### FakeVelocity

• **FakeVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:19876](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19876)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17716)

___

### LastBoneRotationAnimAlphaBlend

• **LastBoneRotationAnimAlphaBlend**: `number`

#### Defined in

[ue/ue.d.ts:19879](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19879)

___

### MaxDeltaTime

• **MaxDeltaTime**: `number`

#### Defined in

[ue/ue.d.ts:19868](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19868)

___

### PlanarLimits

• **PlanarLimits**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimPhysPlanarLimit`](ue_ue.AnimPhysPlanarLimit.md)\>

#### Defined in

[ue/ue.d.ts:19874](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19874)

___

### RelaxationSpeedScale

• **RelaxationSpeedScale**: `number`

#### Defined in

[ue/ue.d.ts:19869](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19869)

___

### RelaxationSpeedScaleInputProcessor

• **RelaxationSpeedScaleInputProcessor**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

#### Defined in

[ue/ue.d.ts:19871](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19871)

___

### RotationLimits

• **RotationLimits**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`RotationLimit`](ue_ue.RotationLimit.md)\>

#### Defined in

[ue/ue.d.ts:19872](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19872)

___

### RotationOffsets

• **RotationOffsets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Defined in

[ue/ue.d.ts:19873](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19873)

___

### StretchLimit

• **StretchLimit**: `number`

#### Defined in

[ue/ue.d.ts:19875](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19875)

___

### TrailBone

• **TrailBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:19853](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19853)

___

### TrailBoneRotationBlendAlpha

• **TrailBoneRotationBlendAlpha**: `number`

#### Defined in

[ue/ue.d.ts:19878](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19878)

___

### TrailRelaxation

• **TrailRelaxation**: `number`

#### Defined in

[ue/ue.d.ts:19867](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19867)

___

### TrailRelaxationSpeed

• **TrailRelaxationSpeed**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

#### Defined in

[ue/ue.d.ts:19870](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19870)

___

### \_\_tid\_AnimNode\_Trail\_\_

• `Private` **\_\_tid\_AnimNode\_Trail\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19885](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19885)

___

### bActorSpaceFakeVel

• **bActorSpaceFakeVel**: `boolean`

#### Defined in

[ue/ue.d.ts:19860](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19860)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17719)

___

### bEnableDebug

• **bEnableDebug**: `boolean`

#### Defined in

[ue/ue.d.ts:19862](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19862)

___

### bInvertChainBoneAxis

• **bInvertChainBoneAxis**: `boolean`

#### Defined in

[ue/ue.d.ts:19856](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19856)

___

### bLimitRotation

• **bLimitRotation**: `boolean`

#### Defined in

[ue/ue.d.ts:19858](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19858)

___

### bLimitStretch

• **bLimitStretch**: `boolean`

#### Defined in

[ue/ue.d.ts:19857](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19857)

___

### bReorientParentToChild

• **bReorientParentToChild**: `boolean`

#### Defined in

[ue/ue.d.ts:19861](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19861)

___

### bShowBaseMotion

• **bShowBaseMotion**: `boolean`

#### Defined in

[ue/ue.d.ts:19863](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19863)

___

### bShowLimit

• **bShowLimit**: `boolean`

#### Defined in

[ue/ue.d.ts:19865](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19865)

___

### bShowTrailLocation

• **bShowTrailLocation**: `boolean`

#### Defined in

[ue/ue.d.ts:19864](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19864)

___

### bUsePlanarLimit

• **bUsePlanarLimit**: `boolean`

#### Defined in

[ue/ue.d.ts:19859](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19859)

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

[ue/ue.d.ts:19883](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19883)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19884](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19884)
