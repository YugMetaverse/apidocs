[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_SpringBone

# Class: AnimNode\_SpringBone

[ue/ue](../modules/ue_ue.md).AnimNode_SpringBone

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_SpringBone`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_SpringBone.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_SpringBone.md#actualalpha)
- [Alpha](ue_ue.AnimNode_SpringBone.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_SpringBone.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_SpringBone.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_SpringBone.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_SpringBone.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_SpringBone.md#alphascalebiasclamp)
- [ComponentPose](ue_ue.AnimNode_SpringBone.md#componentpose)
- [ErrorResetThresh](ue_ue.AnimNode_SpringBone.md#errorresetthresh)
- [LODThreshold](ue_ue.AnimNode_SpringBone.md#lodthreshold)
- [MaxDisplacement](ue_ue.AnimNode_SpringBone.md#maxdisplacement)
- [SpringBone](ue_ue.AnimNode_SpringBone.md#springbone)
- [SpringDamping](ue_ue.AnimNode_SpringBone.md#springdamping)
- [SpringStiffness](ue_ue.AnimNode_SpringBone.md#springstiffness)
- [\_\_tid\_AnimNode\_SpringBone\_\_](ue_ue.AnimNode_SpringBone.md#__tid_animnode_springbone__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_SpringBone.md#balphaboolenabled)
- [bLimitDisplacement](ue_ue.AnimNode_SpringBone.md#blimitdisplacement)
- [bNoZSpring](ue_ue.AnimNode_SpringBone.md#bnozspring)
- [bRotateX](ue_ue.AnimNode_SpringBone.md#brotatex)
- [bRotateY](ue_ue.AnimNode_SpringBone.md#brotatey)
- [bRotateZ](ue_ue.AnimNode_SpringBone.md#brotatez)
- [bTranslateX](ue_ue.AnimNode_SpringBone.md#btranslatex)
- [bTranslateY](ue_ue.AnimNode_SpringBone.md#btranslatey)
- [bTranslateZ](ue_ue.AnimNode_SpringBone.md#btranslatez)

### Methods

- [StaticClass](ue_ue.AnimNode_SpringBone.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_SpringBone.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_SpringBone**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:19667](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19667)

• **new AnimNode_SpringBone**(`SpringBone`, `MaxDisplacement`, `SpringStiffness`, `SpringDamping`, `ErrorResetThresh`, `bNoZSpring`, `bLimitDisplacement`, `bTranslateX`, `bTranslateY`, `bTranslateZ`, `bRotateX`, `bRotateY`, `bRotateZ`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SpringBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `MaxDisplacement` | `number` |
| `SpringStiffness` | `number` |
| `SpringDamping` | `number` |
| `ErrorResetThresh` | `number` |
| `bNoZSpring` | `boolean` |
| `bLimitDisplacement` | `boolean` |
| `bTranslateX` | `boolean` |
| `bTranslateY` | `boolean` |
| `bTranslateZ` | `boolean` |
| `bRotateX` | `boolean` |
| `bRotateY` | `boolean` |
| `bRotateZ` | `boolean` |

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:19668](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19668)

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

### ErrorResetThresh

• **ErrorResetThresh**: `number`

#### Defined in

[ue/ue.d.ts:19673](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19673)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17716)

___

### MaxDisplacement

• **MaxDisplacement**: `number`

#### Defined in

[ue/ue.d.ts:19670](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19670)

___

### SpringBone

• **SpringBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:19669](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19669)

___

### SpringDamping

• **SpringDamping**: `number`

#### Defined in

[ue/ue.d.ts:19672](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19672)

___

### SpringStiffness

• **SpringStiffness**: `number`

#### Defined in

[ue/ue.d.ts:19671](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19671)

___

### \_\_tid\_AnimNode\_SpringBone\_\_

• `Private` **\_\_tid\_AnimNode\_SpringBone\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19687](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19687)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17719)

___

### bLimitDisplacement

• **bLimitDisplacement**: `boolean`

#### Defined in

[ue/ue.d.ts:19675](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19675)

___

### bNoZSpring

• **bNoZSpring**: `boolean`

#### Defined in

[ue/ue.d.ts:19674](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19674)

___

### bRotateX

• **bRotateX**: `boolean`

#### Defined in

[ue/ue.d.ts:19679](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19679)

___

### bRotateY

• **bRotateY**: `boolean`

#### Defined in

[ue/ue.d.ts:19680](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19680)

___

### bRotateZ

• **bRotateZ**: `boolean`

#### Defined in

[ue/ue.d.ts:19681](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19681)

___

### bTranslateX

• **bTranslateX**: `boolean`

#### Defined in

[ue/ue.d.ts:19676](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19676)

___

### bTranslateY

• **bTranslateY**: `boolean`

#### Defined in

[ue/ue.d.ts:19677](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19677)

___

### bTranslateZ

• **bTranslateZ**: `boolean`

#### Defined in

[ue/ue.d.ts:19678](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19678)

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

[ue/ue.d.ts:19685](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19685)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19686](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L19686)
