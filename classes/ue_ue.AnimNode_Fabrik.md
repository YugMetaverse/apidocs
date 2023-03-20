[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_Fabrik

# Class: AnimNode\_Fabrik

[ue/ue](../modules/ue_ue.md).AnimNode_Fabrik

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_Fabrik`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_Fabrik.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_Fabrik.md#actualalpha)
- [Alpha](ue_ue.AnimNode_Fabrik.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_Fabrik.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_Fabrik.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_Fabrik.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_Fabrik.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_Fabrik.md#alphascalebiasclamp)
- [ComponentPose](ue_ue.AnimNode_Fabrik.md#componentpose)
- [EffectorRotationSource](ue_ue.AnimNode_Fabrik.md#effectorrotationsource)
- [EffectorTarget](ue_ue.AnimNode_Fabrik.md#effectortarget)
- [EffectorTransform](ue_ue.AnimNode_Fabrik.md#effectortransform)
- [EffectorTransformBone](ue_ue.AnimNode_Fabrik.md#effectortransformbone)
- [EffectorTransformSpace](ue_ue.AnimNode_Fabrik.md#effectortransformspace)
- [LODThreshold](ue_ue.AnimNode_Fabrik.md#lodthreshold)
- [MaxIterations](ue_ue.AnimNode_Fabrik.md#maxiterations)
- [Precision](ue_ue.AnimNode_Fabrik.md#precision)
- [RootBone](ue_ue.AnimNode_Fabrik.md#rootbone)
- [TipBone](ue_ue.AnimNode_Fabrik.md#tipbone)
- [\_\_tid\_AnimNode\_Fabrik\_\_](ue_ue.AnimNode_Fabrik.md#__tid_animnode_fabrik__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_Fabrik.md#balphaboolenabled)
- [bEnableDebugDraw](ue_ue.AnimNode_Fabrik.md#benabledebugdraw)

### Methods

- [StaticClass](ue_ue.AnimNode_Fabrik.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_Fabrik.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_Fabrik**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:18480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18480)

• **new AnimNode_Fabrik**(`EffectorTransform`, `EffectorTarget`, `TipBone`, `RootBone`, `Precision`, `MaxIterations`, `EffectorTransformSpace`, `EffectorRotationSource`, `bEnableDebugDraw`, `EffectorTransformBone`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `EffectorTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `EffectorTarget` | [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md) |
| `TipBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `RootBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `Precision` | `number` |
| `MaxIterations` | `number` |
| `EffectorTransformSpace` | [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md) |
| `EffectorRotationSource` | [`EBoneRotationSource`](../enums/ue_ue.EBoneRotationSource.md) |
| `bEnableDebugDraw` | `boolean` |
| `EffectorTransformBone` | [`BoneReference`](ue_ue.BoneReference.md) |

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:18481](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18481)

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

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

#### Defined in

[ue/ue.d.ts:17715](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17715)

___

### EffectorRotationSource

• **EffectorRotationSource**: [`EBoneRotationSource`](../enums/ue_ue.EBoneRotationSource.md)

#### Defined in

[ue/ue.d.ts:18489](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18489)

___

### EffectorTarget

• **EffectorTarget**: [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md)

#### Defined in

[ue/ue.d.ts:18483](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18483)

___

### EffectorTransform

• **EffectorTransform**: [`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:18482](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18482)

___

### EffectorTransformBone

• **EffectorTransformBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18491)

___

### EffectorTransformSpace

• **EffectorTransformSpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

#### Defined in

[ue/ue.d.ts:18488](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18488)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17716)

___

### MaxIterations

• **MaxIterations**: `number`

#### Defined in

[ue/ue.d.ts:18487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18487)

___

### Precision

• **Precision**: `number`

#### Defined in

[ue/ue.d.ts:18486](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18486)

___

### RootBone

• **RootBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18485)

___

### TipBone

• **TipBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18484](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18484)

___

### \_\_tid\_AnimNode\_Fabrik\_\_

• `Private` **\_\_tid\_AnimNode\_Fabrik\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:18497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18497)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17719)

___

### bEnableDebugDraw

• **bEnableDebugDraw**: `boolean`

#### Defined in

[ue/ue.d.ts:18490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18490)

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

[ue/ue.d.ts:18495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18495)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:18496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18496)
