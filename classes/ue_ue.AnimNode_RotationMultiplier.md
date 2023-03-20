[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_RotationMultiplier

# Class: AnimNode\_RotationMultiplier

[ue/ue](../modules/ue_ue.md).AnimNode_RotationMultiplier

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_RotationMultiplier`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_RotationMultiplier.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_RotationMultiplier.md#actualalpha)
- [Alpha](ue_ue.AnimNode_RotationMultiplier.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_RotationMultiplier.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_RotationMultiplier.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_RotationMultiplier.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_RotationMultiplier.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_RotationMultiplier.md#alphascalebiasclamp)
- [ComponentPose](ue_ue.AnimNode_RotationMultiplier.md#componentpose)
- [LODThreshold](ue_ue.AnimNode_RotationMultiplier.md#lodthreshold)
- [Multiplier](ue_ue.AnimNode_RotationMultiplier.md#multiplier)
- [RotationAxisToRefer](ue_ue.AnimNode_RotationMultiplier.md#rotationaxistorefer)
- [SourceBone](ue_ue.AnimNode_RotationMultiplier.md#sourcebone)
- [TargetBone](ue_ue.AnimNode_RotationMultiplier.md#targetbone)
- [\_\_tid\_AnimNode\_RotationMultiplier\_\_](ue_ue.AnimNode_RotationMultiplier.md#__tid_animnode_rotationmultiplier__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_RotationMultiplier.md#balphaboolenabled)
- [bIsAdditive](ue_ue.AnimNode_RotationMultiplier.md#bisadditive)

### Methods

- [StaticClass](ue_ue.AnimNode_RotationMultiplier.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_RotationMultiplier.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_RotationMultiplier**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:19444](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19444)

• **new AnimNode_RotationMultiplier**(`TargetBone`, `SourceBone`, `Multiplier`, `RotationAxisToRefer`, `bIsAdditive`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `SourceBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `Multiplier` | `number` |
| `RotationAxisToRefer` | [`EBoneAxis`](../enums/ue_ue.EBoneAxis.md) |
| `bIsAdditive` | `boolean` |

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:19445](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19445)

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

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17716)

___

### Multiplier

• **Multiplier**: `number`

#### Defined in

[ue/ue.d.ts:19448](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19448)

___

### RotationAxisToRefer

• **RotationAxisToRefer**: [`EBoneAxis`](../enums/ue_ue.EBoneAxis.md)

#### Defined in

[ue/ue.d.ts:19449](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19449)

___

### SourceBone

• **SourceBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:19447](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19447)

___

### TargetBone

• **TargetBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:19446](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19446)

___

### \_\_tid\_AnimNode\_RotationMultiplier\_\_

• `Private` **\_\_tid\_AnimNode\_RotationMultiplier\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19456](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19456)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17719)

___

### bIsAdditive

• **bIsAdditive**: `boolean`

#### Defined in

[ue/ue.d.ts:19450](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19450)

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

[ue/ue.d.ts:19454](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19454)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19455](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19455)
