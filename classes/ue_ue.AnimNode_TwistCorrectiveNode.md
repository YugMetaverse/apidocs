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

#### Defined in

[ue/ue.d.ts:19950](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19950)

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

#### Defined in

[ue/ue.d.ts:19951](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19951)

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

### BaseFrame

• **BaseFrame**: [`ReferenceBoneFrame`](ue_ue.ReferenceBoneFrame.md)

#### Defined in

[ue/ue.d.ts:19952](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19952)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

#### Defined in

[ue/ue.d.ts:17715](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17715)

___

### Curve

• **Curve**: [`AnimCurveParam`](ue_ue.AnimCurveParam.md)

#### Defined in

[ue/ue.d.ts:19958](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19958)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17716)

___

### RangeMax

• **RangeMax**: `number`

#### Defined in

[ue/ue.d.ts:19955](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19955)

___

### RemappedMax

• **RemappedMax**: `number`

#### Defined in

[ue/ue.d.ts:19957](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19957)

___

### RemappedMin

• **RemappedMin**: `number`

#### Defined in

[ue/ue.d.ts:19956](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19956)

___

### TwistFrame

• **TwistFrame**: [`ReferenceBoneFrame`](ue_ue.ReferenceBoneFrame.md)

#### Defined in

[ue/ue.d.ts:19953](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19953)

___

### TwistPlaneNormalAxis

• **TwistPlaneNormalAxis**: [`Axis`](ue_ue.Axis.md)

#### Defined in

[ue/ue.d.ts:19954](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19954)

___

### \_\_tid\_AnimNode\_TwistCorrectiveNode\_\_

• `Private` **\_\_tid\_AnimNode\_TwistCorrectiveNode\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19964](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19964)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17719)

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

[ue/ue.d.ts:19962](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19962)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19963](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19963)
