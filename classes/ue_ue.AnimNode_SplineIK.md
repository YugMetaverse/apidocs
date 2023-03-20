[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_SplineIK

# Class: AnimNode\_SplineIK

[ue/ue](../modules/ue_ue.md).AnimNode_SplineIK

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_SplineIK`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_SplineIK.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_SplineIK.md#actualalpha)
- [Alpha](ue_ue.AnimNode_SplineIK.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_SplineIK.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_SplineIK.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_SplineIK.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_SplineIK.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_SplineIK.md#alphascalebiasclamp)
- [BoneAxis](ue_ue.AnimNode_SplineIK.md#boneaxis)
- [ComponentPose](ue_ue.AnimNode_SplineIK.md#componentpose)
- [ControlPoints](ue_ue.AnimNode_SplineIK.md#controlpoints)
- [EndBone](ue_ue.AnimNode_SplineIK.md#endbone)
- [LODThreshold](ue_ue.AnimNode_SplineIK.md#lodthreshold)
- [Offset](ue_ue.AnimNode_SplineIK.md#offset)
- [PointCount](ue_ue.AnimNode_SplineIK.md#pointcount)
- [Roll](ue_ue.AnimNode_SplineIK.md#roll)
- [StartBone](ue_ue.AnimNode_SplineIK.md#startbone)
- [Stretch](ue_ue.AnimNode_SplineIK.md#stretch)
- [TwistBlend](ue_ue.AnimNode_SplineIK.md#twistblend)
- [TwistEnd](ue_ue.AnimNode_SplineIK.md#twistend)
- [TwistStart](ue_ue.AnimNode_SplineIK.md#twiststart)
- [\_\_tid\_AnimNode\_SplineIK\_\_](ue_ue.AnimNode_SplineIK.md#__tid_animnode_splineik__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_SplineIK.md#balphaboolenabled)
- [bAutoCalculateSpline](ue_ue.AnimNode_SplineIK.md#bautocalculatespline)

### Methods

- [StaticClass](ue_ue.AnimNode_SplineIK.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_SplineIK.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_SplineIK**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

• **new AnimNode_SplineIK**(`StartBone`, `EndBone`, `BoneAxis`, `bAutoCalculateSpline`, `PointCount`, `ControlPoints`, `Roll`, `TwistStart`, `TwistEnd`, `TwistBlend`, `Stretch`, `Offset`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `StartBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `EndBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `BoneAxis` | [`ESplineBoneAxis`](../enums/ue_ue.ESplineBoneAxis.md) |
| `bAutoCalculateSpline` | `boolean` |
| `PointCount` | `number` |
| `ControlPoints` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\> |
| `Roll` | `number` |
| `TwistStart` | `number` |
| `TwistEnd` | `number` |
| `TwistBlend` | [`AlphaBlend`](ue_ue.AlphaBlend.md) |
| `Stretch` | `number` |
| `Offset` | `number` |

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

### BoneAxis

• **BoneAxis**: [`ESplineBoneAxis`](../enums/ue_ue.ESplineBoneAxis.md)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

___

### ControlPoints

• **ControlPoints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\>

___

### EndBone

• **EndBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

___

### Offset

• **Offset**: `number`

___

### PointCount

• **PointCount**: `number`

___

### Roll

• **Roll**: `number`

___

### StartBone

• **StartBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### Stretch

• **Stretch**: `number`

___

### TwistBlend

• **TwistBlend**: [`AlphaBlend`](ue_ue.AlphaBlend.md)

___

### TwistEnd

• **TwistEnd**: `number`

___

### TwistStart

• **TwistStart**: `number`

___

### \_\_tid\_AnimNode\_SplineIK\_\_

• `Private` **\_\_tid\_AnimNode\_SplineIK\_\_**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

___

### bAutoCalculateSpline

• **bAutoCalculateSpline**: `boolean`

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
