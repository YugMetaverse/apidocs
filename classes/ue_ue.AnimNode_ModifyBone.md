[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_ModifyBone

# Class: AnimNode\_ModifyBone

[ue/ue](../modules/ue_ue.md).AnimNode_ModifyBone

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_ModifyBone`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_ModifyBone.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_ModifyBone.md#actualalpha)
- [Alpha](ue_ue.AnimNode_ModifyBone.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_ModifyBone.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_ModifyBone.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_ModifyBone.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_ModifyBone.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_ModifyBone.md#alphascalebiasclamp)
- [BoneToModify](ue_ue.AnimNode_ModifyBone.md#bonetomodify)
- [ComponentPose](ue_ue.AnimNode_ModifyBone.md#componentpose)
- [LODThreshold](ue_ue.AnimNode_ModifyBone.md#lodthreshold)
- [Rotation](ue_ue.AnimNode_ModifyBone.md#rotation)
- [RotationMode](ue_ue.AnimNode_ModifyBone.md#rotationmode)
- [RotationSpace](ue_ue.AnimNode_ModifyBone.md#rotationspace)
- [Scale](ue_ue.AnimNode_ModifyBone.md#scale)
- [ScaleMode](ue_ue.AnimNode_ModifyBone.md#scalemode)
- [ScaleSpace](ue_ue.AnimNode_ModifyBone.md#scalespace)
- [Translation](ue_ue.AnimNode_ModifyBone.md#translation)
- [TranslationMode](ue_ue.AnimNode_ModifyBone.md#translationmode)
- [TranslationSpace](ue_ue.AnimNode_ModifyBone.md#translationspace)
- [\_\_tid\_AnimNode\_ModifyBone\_\_](ue_ue.AnimNode_ModifyBone.md#__tid_animnode_modifybone__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_ModifyBone.md#balphaboolenabled)

### Methods

- [StaticClass](ue_ue.AnimNode_ModifyBone.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_ModifyBone.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_ModifyBone**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:18966](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18966)

• **new AnimNode_ModifyBone**(`BoneToModify`, `Translation`, `Rotation`, `Scale`, `TranslationMode`, `RotationMode`, `ScaleMode`, `TranslationSpace`, `RotationSpace`, `ScaleSpace`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneToModify` | [`BoneReference`](ue_ue.BoneReference.md) |
| `Translation` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `Scale` | [`Vector`](ue_ue_s.Vector.md) |
| `TranslationMode` | [`EBoneModificationMode`](../enums/ue_ue.EBoneModificationMode.md) |
| `RotationMode` | [`EBoneModificationMode`](../enums/ue_ue.EBoneModificationMode.md) |
| `ScaleMode` | [`EBoneModificationMode`](../enums/ue_ue.EBoneModificationMode.md) |
| `TranslationSpace` | [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md) |
| `RotationSpace` | [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md) |
| `ScaleSpace` | [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md) |

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:18967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18967)

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

### BoneToModify

• **BoneToModify**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18968](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18968)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

#### Defined in

[ue/ue.d.ts:17715](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17715)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17716)

___

### Rotation

• **Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:18970](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18970)

___

### RotationMode

• **RotationMode**: [`EBoneModificationMode`](../enums/ue_ue.EBoneModificationMode.md)

#### Defined in

[ue/ue.d.ts:18973](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18973)

___

### RotationSpace

• **RotationSpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

#### Defined in

[ue/ue.d.ts:18976](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18976)

___

### Scale

• **Scale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:18971](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18971)

___

### ScaleMode

• **ScaleMode**: [`EBoneModificationMode`](../enums/ue_ue.EBoneModificationMode.md)

#### Defined in

[ue/ue.d.ts:18974](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18974)

___

### ScaleSpace

• **ScaleSpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

#### Defined in

[ue/ue.d.ts:18977](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18977)

___

### Translation

• **Translation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:18969](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18969)

___

### TranslationMode

• **TranslationMode**: [`EBoneModificationMode`](../enums/ue_ue.EBoneModificationMode.md)

#### Defined in

[ue/ue.d.ts:18972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18972)

___

### TranslationSpace

• **TranslationSpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

#### Defined in

[ue/ue.d.ts:18975](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18975)

___

### \_\_tid\_AnimNode\_ModifyBone\_\_

• `Private` **\_\_tid\_AnimNode\_ModifyBone\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:18983](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18983)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17719)

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

[ue/ue.d.ts:18981](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18981)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:18982](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18982)
