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

#### Defined in

[ue/ue.d.ts:19634](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19634)

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

#### Defined in

[ue/ue.d.ts:19635](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19635)

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

### BoneAxis

• **BoneAxis**: [`ESplineBoneAxis`](../enums/ue_ue.ESplineBoneAxis.md)

#### Defined in

[ue/ue.d.ts:19638](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19638)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

#### Defined in

[ue/ue.d.ts:17715](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17715)

___

### ControlPoints

• **ControlPoints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\>

#### Defined in

[ue/ue.d.ts:19641](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19641)

___

### EndBone

• **EndBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:19637](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19637)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17716)

___

### Offset

• **Offset**: `number`

#### Defined in

[ue/ue.d.ts:19647](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19647)

___

### PointCount

• **PointCount**: `number`

#### Defined in

[ue/ue.d.ts:19640](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19640)

___

### Roll

• **Roll**: `number`

#### Defined in

[ue/ue.d.ts:19642](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19642)

___

### StartBone

• **StartBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:19636](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19636)

___

### Stretch

• **Stretch**: `number`

#### Defined in

[ue/ue.d.ts:19646](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19646)

___

### TwistBlend

• **TwistBlend**: [`AlphaBlend`](ue_ue.AlphaBlend.md)

#### Defined in

[ue/ue.d.ts:19645](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19645)

___

### TwistEnd

• **TwistEnd**: `number`

#### Defined in

[ue/ue.d.ts:19644](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19644)

___

### TwistStart

• **TwistStart**: `number`

#### Defined in

[ue/ue.d.ts:19643](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19643)

___

### \_\_tid\_AnimNode\_SplineIK\_\_

• `Private` **\_\_tid\_AnimNode\_SplineIK\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19653](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19653)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17719)

___

### bAutoCalculateSpline

• **bAutoCalculateSpline**: `boolean`

#### Defined in

[ue/ue.d.ts:19639](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19639)

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

[ue/ue.d.ts:19651](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19651)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19652](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19652)
