[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_CopyBone

# Class: AnimNode\_CopyBone

[ue/ue](../modules/ue_ue.md).AnimNode_CopyBone

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_CopyBone`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_CopyBone.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_CopyBone.md#actualalpha)
- [Alpha](ue_ue.AnimNode_CopyBone.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_CopyBone.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_CopyBone.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_CopyBone.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_CopyBone.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_CopyBone.md#alphascalebiasclamp)
- [ComponentPose](ue_ue.AnimNode_CopyBone.md#componentpose)
- [ControlSpace](ue_ue.AnimNode_CopyBone.md#controlspace)
- [LODThreshold](ue_ue.AnimNode_CopyBone.md#lodthreshold)
- [SourceBone](ue_ue.AnimNode_CopyBone.md#sourcebone)
- [TargetBone](ue_ue.AnimNode_CopyBone.md#targetbone)
- [\_\_tid\_AnimNode\_CopyBone\_\_](ue_ue.AnimNode_CopyBone.md#__tid_animnode_copybone__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_CopyBone.md#balphaboolenabled)
- [bCopyRotation](ue_ue.AnimNode_CopyBone.md#bcopyrotation)
- [bCopyScale](ue_ue.AnimNode_CopyBone.md#bcopyscale)
- [bCopyTranslation](ue_ue.AnimNode_CopyBone.md#bcopytranslation)

### Methods

- [StaticClass](ue_ue.AnimNode_CopyBone.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_CopyBone.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_CopyBone**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:18336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18336)

• **new AnimNode_CopyBone**(`SourceBone`, `TargetBone`, `bCopyTranslation`, `bCopyRotation`, `bCopyScale`, `ControlSpace`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `TargetBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `bCopyTranslation` | `boolean` |
| `bCopyRotation` | `boolean` |
| `bCopyScale` | `boolean` |
| `ControlSpace` | [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md) |

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:18337](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18337)

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

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

#### Defined in

[ue/ue.d.ts:17715](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17715)

___

### ControlSpace

• **ControlSpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

#### Defined in

[ue/ue.d.ts:18343](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18343)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17716)

___

### SourceBone

• **SourceBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18338)

___

### TargetBone

• **TargetBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18339](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18339)

___

### \_\_tid\_AnimNode\_CopyBone\_\_

• `Private` **\_\_tid\_AnimNode\_CopyBone\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:18349](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18349)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17719)

___

### bCopyRotation

• **bCopyRotation**: `boolean`

#### Defined in

[ue/ue.d.ts:18341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18341)

___

### bCopyScale

• **bCopyScale**: `boolean`

#### Defined in

[ue/ue.d.ts:18342](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18342)

___

### bCopyTranslation

• **bCopyTranslation**: `boolean`

#### Defined in

[ue/ue.d.ts:18340](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18340)

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

[ue/ue.d.ts:18347](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18347)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:18348](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18348)
