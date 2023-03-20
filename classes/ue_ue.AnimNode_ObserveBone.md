[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_ObserveBone

# Class: AnimNode\_ObserveBone

[ue/ue](../modules/ue_ue.md).AnimNode_ObserveBone

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_ObserveBone`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_ObserveBone.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_ObserveBone.md#actualalpha)
- [Alpha](ue_ue.AnimNode_ObserveBone.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_ObserveBone.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_ObserveBone.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_ObserveBone.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_ObserveBone.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_ObserveBone.md#alphascalebiasclamp)
- [BoneToObserve](ue_ue.AnimNode_ObserveBone.md#bonetoobserve)
- [ComponentPose](ue_ue.AnimNode_ObserveBone.md#componentpose)
- [DisplaySpace](ue_ue.AnimNode_ObserveBone.md#displayspace)
- [LODThreshold](ue_ue.AnimNode_ObserveBone.md#lodthreshold)
- [Rotation](ue_ue.AnimNode_ObserveBone.md#rotation)
- [Scale](ue_ue.AnimNode_ObserveBone.md#scale)
- [Translation](ue_ue.AnimNode_ObserveBone.md#translation)
- [\_\_tid\_AnimNode\_ObserveBone\_\_](ue_ue.AnimNode_ObserveBone.md#__tid_animnode_observebone__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_ObserveBone.md#balphaboolenabled)
- [bRelativeToRefPose](ue_ue.AnimNode_ObserveBone.md#brelativetorefpose)

### Methods

- [StaticClass](ue_ue.AnimNode_ObserveBone.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_ObserveBone.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_ObserveBone**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:19050](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19050)

• **new AnimNode_ObserveBone**(`BoneToObserve`, `DisplaySpace`, `bRelativeToRefPose`, `Translation`, `Rotation`, `Scale`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneToObserve` | [`BoneReference`](ue_ue.BoneReference.md) |
| `DisplaySpace` | [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md) |
| `bRelativeToRefPose` | `boolean` |
| `Translation` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `Scale` | [`Vector`](ue_ue_s.Vector.md) |

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:19051](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19051)

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

### BoneToObserve

• **BoneToObserve**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:19052](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19052)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

#### Defined in

[ue/ue.d.ts:17715](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17715)

___

### DisplaySpace

• **DisplaySpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

#### Defined in

[ue/ue.d.ts:19053](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19053)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17716)

___

### Rotation

• **Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:19056](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19056)

___

### Scale

• **Scale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:19057](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19057)

___

### Translation

• **Translation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:19055](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19055)

___

### \_\_tid\_AnimNode\_ObserveBone\_\_

• `Private` **\_\_tid\_AnimNode\_ObserveBone\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19063](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19063)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17719)

___

### bRelativeToRefPose

• **bRelativeToRefPose**: `boolean`

#### Defined in

[ue/ue.d.ts:19054](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19054)

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

[ue/ue.d.ts:19061](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19061)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19062](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19062)
