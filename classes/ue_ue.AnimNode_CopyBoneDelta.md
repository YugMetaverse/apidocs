[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_CopyBoneDelta

# Class: AnimNode\_CopyBoneDelta

[ue/ue](../modules/ue_ue.md).AnimNode_CopyBoneDelta

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_CopyBoneDelta`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_CopyBoneDelta.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_CopyBoneDelta.md#actualalpha)
- [Alpha](ue_ue.AnimNode_CopyBoneDelta.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_CopyBoneDelta.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_CopyBoneDelta.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_CopyBoneDelta.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_CopyBoneDelta.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_CopyBoneDelta.md#alphascalebiasclamp)
- [ComponentPose](ue_ue.AnimNode_CopyBoneDelta.md#componentpose)
- [CopyMode](ue_ue.AnimNode_CopyBoneDelta.md#copymode)
- [LODThreshold](ue_ue.AnimNode_CopyBoneDelta.md#lodthreshold)
- [RotationMultiplier](ue_ue.AnimNode_CopyBoneDelta.md#rotationmultiplier)
- [ScaleMultiplier](ue_ue.AnimNode_CopyBoneDelta.md#scalemultiplier)
- [SourceBone](ue_ue.AnimNode_CopyBoneDelta.md#sourcebone)
- [TargetBone](ue_ue.AnimNode_CopyBoneDelta.md#targetbone)
- [TranslationMultiplier](ue_ue.AnimNode_CopyBoneDelta.md#translationmultiplier)
- [\_\_tid\_AnimNode\_CopyBoneDelta\_\_](ue_ue.AnimNode_CopyBoneDelta.md#__tid_animnode_copybonedelta__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_CopyBoneDelta.md#balphaboolenabled)
- [bCopyRotation](ue_ue.AnimNode_CopyBoneDelta.md#bcopyrotation)
- [bCopyScale](ue_ue.AnimNode_CopyBoneDelta.md#bcopyscale)
- [bCopyTranslation](ue_ue.AnimNode_CopyBoneDelta.md#bcopytranslation)

### Methods

- [StaticClass](ue_ue.AnimNode_CopyBoneDelta.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_CopyBoneDelta.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_CopyBoneDelta**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:18364](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18364)

• **new AnimNode_CopyBoneDelta**(`SourceBone`, `TargetBone`, `bCopyTranslation`, `bCopyRotation`, `bCopyScale`, `CopyMode`, `TranslationMultiplier`, `RotationMultiplier`, `ScaleMultiplier`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `TargetBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `bCopyTranslation` | `boolean` |
| `bCopyRotation` | `boolean` |
| `bCopyScale` | `boolean` |
| `CopyMode` | [`CopyBoneDeltaMode`](../enums/ue_ue.CopyBoneDeltaMode.md) |
| `TranslationMultiplier` | `number` |
| `RotationMultiplier` | `number` |
| `ScaleMultiplier` | `number` |

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:18365](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18365)

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

### CopyMode

• **CopyMode**: [`CopyBoneDeltaMode`](../enums/ue_ue.CopyBoneDeltaMode.md)

#### Defined in

[ue/ue.d.ts:18371](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18371)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17716)

___

### RotationMultiplier

• **RotationMultiplier**: `number`

#### Defined in

[ue/ue.d.ts:18373](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18373)

___

### ScaleMultiplier

• **ScaleMultiplier**: `number`

#### Defined in

[ue/ue.d.ts:18374](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18374)

___

### SourceBone

• **SourceBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18366](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18366)

___

### TargetBone

• **TargetBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18367](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18367)

___

### TranslationMultiplier

• **TranslationMultiplier**: `number`

#### Defined in

[ue/ue.d.ts:18372](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18372)

___

### \_\_tid\_AnimNode\_CopyBoneDelta\_\_

• `Private` **\_\_tid\_AnimNode\_CopyBoneDelta\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:18380](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18380)

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

[ue/ue.d.ts:18369](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18369)

___

### bCopyScale

• **bCopyScale**: `boolean`

#### Defined in

[ue/ue.d.ts:18370](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18370)

___

### bCopyTranslation

• **bCopyTranslation**: `boolean`

#### Defined in

[ue/ue.d.ts:18368](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18368)

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

[ue/ue.d.ts:18378](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18378)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:18379](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18379)
