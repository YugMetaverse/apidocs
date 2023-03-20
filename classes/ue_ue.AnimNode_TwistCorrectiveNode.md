[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_TwistCorrectiveNode

# Class: AnimNode\_TwistCorrectiveNode

[ue/ue](../modules/ue_ue.md).AnimNode_TwistCorrectiveNode

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_TwistCorrectiveNode`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_TwistCorrectiveNode.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_TwistCorrectiveNode.md#actualalpha)
- [Alpha](ue_ue.AnimNode_TwistCorrectiveNode.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_TwistCorrectiveNode.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_TwistCorrectiveNode.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_TwistCorrectiveNode.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_TwistCorrectiveNode.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_TwistCorrectiveNode.md#alphascalebiasclamp)
- [BaseFrame](ue_ue.AnimNode_TwistCorrectiveNode.md#baseframe)
- [ComponentPose](ue_ue.AnimNode_TwistCorrectiveNode.md#componentpose)
- [Curve](ue_ue.AnimNode_TwistCorrectiveNode.md#curve)
- [LODThreshold](ue_ue.AnimNode_TwistCorrectiveNode.md#lodthreshold)
- [RangeMax](ue_ue.AnimNode_TwistCorrectiveNode.md#rangemax)
- [RemappedMax](ue_ue.AnimNode_TwistCorrectiveNode.md#remappedmax)
- [RemappedMin](ue_ue.AnimNode_TwistCorrectiveNode.md#remappedmin)
- [TwistFrame](ue_ue.AnimNode_TwistCorrectiveNode.md#twistframe)
- [TwistPlaneNormalAxis](ue_ue.AnimNode_TwistCorrectiveNode.md#twistplanenormalaxis)
- [\_\_tid\_AnimNode\_TwistCorrectiveNode\_\_](ue_ue.AnimNode_TwistCorrectiveNode.md#__tid_animnode_twistcorrectivenode__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_TwistCorrectiveNode.md#balphaboolenabled)

### Methods

- [StaticClass](ue_ue.AnimNode_TwistCorrectiveNode.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_TwistCorrectiveNode.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_TwistCorrectiveNode**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

• **new AnimNode_TwistCorrectiveNode**(`BaseFrame`, `TwistFrame`, `TwistPlaneNormalAxis`, `RangeMax`, `RemappedMin`, `RemappedMax`, `Curve`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BaseFrame` | [`ReferenceBoneFrame`](ue_ue.ReferenceBoneFrame.md) |
| `TwistFrame` | [`ReferenceBoneFrame`](ue_ue.ReferenceBoneFrame.md) |
| `TwistPlaneNormalAxis` | [`Axis`](ue_ue.Axis.md) |
| `RangeMax` | `number` |
| `RemappedMin` | `number` |
| `RemappedMax` | `number` |
| `Curve` | [`AnimCurveParam`](ue_ue.AnimCurveParam.md) |

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

### BaseFrame

• **BaseFrame**: [`ReferenceBoneFrame`](ue_ue.ReferenceBoneFrame.md)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

___

### Curve

• **Curve**: [`AnimCurveParam`](ue_ue.AnimCurveParam.md)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

___

### RangeMax

• **RangeMax**: `number`

___

### RemappedMax

• **RemappedMax**: `number`

___

### RemappedMin

• **RemappedMin**: `number`

___

### TwistFrame

• **TwistFrame**: [`ReferenceBoneFrame`](ue_ue.ReferenceBoneFrame.md)

___

### TwistPlaneNormalAxis

• **TwistPlaneNormalAxis**: [`Axis`](ue_ue.Axis.md)

___

### \_\_tid\_AnimNode\_TwistCorrectiveNode\_\_

• `Private` **\_\_tid\_AnimNode\_TwistCorrectiveNode\_\_**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

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
