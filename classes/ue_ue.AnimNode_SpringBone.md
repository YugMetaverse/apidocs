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

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

___

### ErrorResetThresh

• **ErrorResetThresh**: `number`

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

___

### MaxDisplacement

• **MaxDisplacement**: `number`

___

### SpringBone

• **SpringBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### SpringDamping

• **SpringDamping**: `number`

___

### SpringStiffness

• **SpringStiffness**: `number`

___

### \_\_tid\_AnimNode\_SpringBone\_\_

• `Private` **\_\_tid\_AnimNode\_SpringBone\_\_**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

___

### bLimitDisplacement

• **bLimitDisplacement**: `boolean`

___

### bNoZSpring

• **bNoZSpring**: `boolean`

___

### bRotateX

• **bRotateX**: `boolean`

___

### bRotateY

• **bRotateY**: `boolean`

___

### bRotateZ

• **bRotateZ**: `boolean`

___

### bTranslateX

• **bTranslateX**: `boolean`

___

### bTranslateY

• **bTranslateY**: `boolean`

___

### bTranslateZ

• **bTranslateZ**: `boolean`

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
