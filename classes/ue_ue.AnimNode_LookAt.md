[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_LookAt

# Class: AnimNode\_LookAt

[ue/ue](../modules/ue_ue.md).AnimNode_LookAt

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_LookAt`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_LookAt.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_LookAt.md#actualalpha)
- [Alpha](ue_ue.AnimNode_LookAt.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_LookAt.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_LookAt.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_LookAt.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_LookAt.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_LookAt.md#alphascalebiasclamp)
- [BoneToModify](ue_ue.AnimNode_LookAt.md#bonetomodify)
- [ComponentPose](ue_ue.AnimNode_LookAt.md#componentpose)
- [CustomLookAtAxis](ue_ue.AnimNode_LookAt.md#customlookataxis)
- [CustomLookUpAxis](ue_ue.AnimNode_LookAt.md#customlookupaxis)
- [InterpolationTime](ue_ue.AnimNode_LookAt.md#interpolationtime)
- [InterpolationTriggerThreashold](ue_ue.AnimNode_LookAt.md#interpolationtriggerthreashold)
- [InterpolationType](ue_ue.AnimNode_LookAt.md#interpolationtype)
- [LODThreshold](ue_ue.AnimNode_LookAt.md#lodthreshold)
- [LookAtAxis](ue_ue.AnimNode_LookAt.md#lookataxis)
- [LookAtBone](ue_ue.AnimNode_LookAt.md#lookatbone)
- [LookAtClamp](ue_ue.AnimNode_LookAt.md#lookatclamp)
- [LookAtLocation](ue_ue.AnimNode_LookAt.md#lookatlocation)
- [LookAtSocket](ue_ue.AnimNode_LookAt.md#lookatsocket)
- [LookAtTarget](ue_ue.AnimNode_LookAt.md#lookattarget)
- [LookAt\_Axis](ue_ue.AnimNode_LookAt.md#lookat_axis)
- [LookUpAxis](ue_ue.AnimNode_LookAt.md#lookupaxis)
- [LookUp\_Axis](ue_ue.AnimNode_LookAt.md#lookup_axis)
- [\_\_tid\_AnimNode\_LookAt\_\_](ue_ue.AnimNode_LookAt.md#__tid_animnode_lookat__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_LookAt.md#balphaboolenabled)
- [bUseLookUpAxis](ue_ue.AnimNode_LookAt.md#buselookupaxis)

### Methods

- [StaticClass](ue_ue.AnimNode_LookAt.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_LookAt.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_LookAt**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

• **new AnimNode_LookAt**(`BoneToModify`, `LookAtTarget`, `LookAtLocation`, `LookAt_Axis`, `bUseLookUpAxis`, `InterpolationType`, `LookUp_Axis`, `LookAtClamp`, `InterpolationTime`, `InterpolationTriggerThreashold`, `LookAtBone`, `LookAtSocket`, `LookAtAxis`, `CustomLookAtAxis`, `LookUpAxis`, `CustomLookUpAxis`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneToModify` | [`BoneReference`](ue_ue.BoneReference.md) |
| `LookAtTarget` | [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md) |
| `LookAtLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `LookAt_Axis` | [`Axis`](ue_ue.Axis.md) |
| `bUseLookUpAxis` | `boolean` |
| `InterpolationType` | [`EInterpolationBlend`](../enums/ue_ue.EInterpolationBlend.md) |
| `LookUp_Axis` | [`Axis`](ue_ue.Axis.md) |
| `LookAtClamp` | `number` |
| `InterpolationTime` | `number` |
| `InterpolationTriggerThreashold` | `number` |
| `LookAtBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `LookAtSocket` | `string` |
| `LookAtAxis` | [`EAxisOption`](../enums/ue_ue.EAxisOption.md) |
| `CustomLookAtAxis` | [`Vector`](ue_ue_s.Vector.md) |
| `LookUpAxis` | [`EAxisOption`](../enums/ue_ue.EAxisOption.md) |
| `CustomLookUpAxis` | [`Vector`](ue_ue_s.Vector.md) |

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

### BoneToModify

• **BoneToModify**: [`BoneReference`](ue_ue.BoneReference.md)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

___

### CustomLookAtAxis

• **CustomLookAtAxis**: [`Vector`](ue_ue_s.Vector.md)

___

### CustomLookUpAxis

• **CustomLookUpAxis**: [`Vector`](ue_ue_s.Vector.md)

___

### InterpolationTime

• **InterpolationTime**: `number`

___

### InterpolationTriggerThreashold

• **InterpolationTriggerThreashold**: `number`

___

### InterpolationType

• **InterpolationType**: [`EInterpolationBlend`](../enums/ue_ue.EInterpolationBlend.md)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

___

### LookAtAxis

• **LookAtAxis**: [`EAxisOption`](../enums/ue_ue.EAxisOption.md)

___

### LookAtBone

• **LookAtBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### LookAtClamp

• **LookAtClamp**: `number`

___

### LookAtLocation

• **LookAtLocation**: [`Vector`](ue_ue_s.Vector.md)

___

### LookAtSocket

• **LookAtSocket**: `string`

___

### LookAtTarget

• **LookAtTarget**: [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md)

___

### LookAt\_Axis

• **LookAt\_Axis**: [`Axis`](ue_ue.Axis.md)

___

### LookUpAxis

• **LookUpAxis**: [`EAxisOption`](../enums/ue_ue.EAxisOption.md)

___

### LookUp\_Axis

• **LookUp\_Axis**: [`Axis`](ue_ue.Axis.md)

___

### \_\_tid\_AnimNode\_LookAt\_\_

• `Private` **\_\_tid\_AnimNode\_LookAt\_\_**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

___

### bUseLookUpAxis

• **bUseLookUpAxis**: `boolean`

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
