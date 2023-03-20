[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_BoneDrivenController

# Class: AnimNode\_BoneDrivenController

[ue/ue](../modules/ue_ue.md).AnimNode_BoneDrivenController

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_BoneDrivenController`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_BoneDrivenController.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_BoneDrivenController.md#actualalpha)
- [Alpha](ue_ue.AnimNode_BoneDrivenController.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_BoneDrivenController.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_BoneDrivenController.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_BoneDrivenController.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_BoneDrivenController.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_BoneDrivenController.md#alphascalebiasclamp)
- [ComponentPose](ue_ue.AnimNode_BoneDrivenController.md#componentpose)
- [DestinationMode](ue_ue.AnimNode_BoneDrivenController.md#destinationmode)
- [DrivingCurve](ue_ue.AnimNode_BoneDrivenController.md#drivingcurve)
- [LODThreshold](ue_ue.AnimNode_BoneDrivenController.md#lodthreshold)
- [ModificationMode](ue_ue.AnimNode_BoneDrivenController.md#modificationmode)
- [Multiplier](ue_ue.AnimNode_BoneDrivenController.md#multiplier)
- [ParameterName](ue_ue.AnimNode_BoneDrivenController.md#parametername)
- [RangeMax](ue_ue.AnimNode_BoneDrivenController.md#rangemax)
- [RangeMin](ue_ue.AnimNode_BoneDrivenController.md#rangemin)
- [RemappedMax](ue_ue.AnimNode_BoneDrivenController.md#remappedmax)
- [RemappedMin](ue_ue.AnimNode_BoneDrivenController.md#remappedmin)
- [SourceBone](ue_ue.AnimNode_BoneDrivenController.md#sourcebone)
- [SourceComponent](ue_ue.AnimNode_BoneDrivenController.md#sourcecomponent)
- [TargetBone](ue_ue.AnimNode_BoneDrivenController.md#targetbone)
- [TargetComponent](ue_ue.AnimNode_BoneDrivenController.md#targetcomponent)
- [\_\_tid\_AnimNode\_BoneDrivenController\_\_](ue_ue.AnimNode_BoneDrivenController.md#__tid_animnode_bonedrivencontroller__)
- [bAffectTargetRotationX](ue_ue.AnimNode_BoneDrivenController.md#baffecttargetrotationx)
- [bAffectTargetRotationY](ue_ue.AnimNode_BoneDrivenController.md#baffecttargetrotationy)
- [bAffectTargetRotationZ](ue_ue.AnimNode_BoneDrivenController.md#baffecttargetrotationz)
- [bAffectTargetScaleX](ue_ue.AnimNode_BoneDrivenController.md#baffecttargetscalex)
- [bAffectTargetScaleY](ue_ue.AnimNode_BoneDrivenController.md#baffecttargetscaley)
- [bAffectTargetScaleZ](ue_ue.AnimNode_BoneDrivenController.md#baffecttargetscalez)
- [bAffectTargetTranslationX](ue_ue.AnimNode_BoneDrivenController.md#baffecttargettranslationx)
- [bAffectTargetTranslationY](ue_ue.AnimNode_BoneDrivenController.md#baffecttargettranslationy)
- [bAffectTargetTranslationZ](ue_ue.AnimNode_BoneDrivenController.md#baffecttargettranslationz)
- [bAlphaBoolEnabled](ue_ue.AnimNode_BoneDrivenController.md#balphaboolenabled)
- [bUseRange](ue_ue.AnimNode_BoneDrivenController.md#buserange)

### Methods

- [StaticClass](ue_ue.AnimNode_BoneDrivenController.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_BoneDrivenController.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_BoneDrivenController**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

• **new AnimNode_BoneDrivenController**(`SourceBone`, `DrivingCurve`, `Multiplier`, `RangeMin`, `RangeMax`, `RemappedMin`, `RemappedMax`, `ParameterName`, `TargetBone`, `TargetComponent`, `DestinationMode`, `ModificationMode`, `SourceComponent`, `bUseRange`, `bAffectTargetTranslationX`, `bAffectTargetTranslationY`, `bAffectTargetTranslationZ`, `bAffectTargetRotationX`, `bAffectTargetRotationY`, `bAffectTargetRotationZ`, `bAffectTargetScaleX`, `bAffectTargetScaleY`, `bAffectTargetScaleZ`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `DrivingCurve` | [`CurveFloat`](ue_ue.CurveFloat.md) |
| `Multiplier` | `number` |
| `RangeMin` | `number` |
| `RangeMax` | `number` |
| `RemappedMin` | `number` |
| `RemappedMax` | `number` |
| `ParameterName` | `string` |
| `TargetBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `TargetComponent` | [`EComponentType`](../enums/ue_ue.EComponentType.md) |
| `DestinationMode` | [`EDrivenDestinationMode`](../enums/ue_ue.EDrivenDestinationMode.md) |
| `ModificationMode` | [`EDrivenBoneModificationMode`](../enums/ue_ue.EDrivenBoneModificationMode.md) |
| `SourceComponent` | [`EComponentType`](../enums/ue_ue.EComponentType.md) |
| `bUseRange` | `boolean` |
| `bAffectTargetTranslationX` | `boolean` |
| `bAffectTargetTranslationY` | `boolean` |
| `bAffectTargetTranslationZ` | `boolean` |
| `bAffectTargetRotationX` | `boolean` |
| `bAffectTargetRotationY` | `boolean` |
| `bAffectTargetRotationZ` | `boolean` |
| `bAffectTargetScaleX` | `boolean` |
| `bAffectTargetScaleY` | `boolean` |
| `bAffectTargetScaleZ` | `boolean` |

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

### DestinationMode

• **DestinationMode**: [`EDrivenDestinationMode`](../enums/ue_ue.EDrivenDestinationMode.md)

___

### DrivingCurve

• **DrivingCurve**: [`CurveFloat`](ue_ue.CurveFloat.md)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

___

### ModificationMode

• **ModificationMode**: [`EDrivenBoneModificationMode`](../enums/ue_ue.EDrivenBoneModificationMode.md)

___

### Multiplier

• **Multiplier**: `number`

___

### ParameterName

• **ParameterName**: `string`

___

### RangeMax

• **RangeMax**: `number`

___

### RangeMin

• **RangeMin**: `number`

___

### RemappedMax

• **RemappedMax**: `number`

___

### RemappedMin

• **RemappedMin**: `number`

___

### SourceBone

• **SourceBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### SourceComponent

• **SourceComponent**: [`EComponentType`](../enums/ue_ue.EComponentType.md)

___

### TargetBone

• **TargetBone**: [`BoneReference`](ue_ue.BoneReference.md)

___

### TargetComponent

• **TargetComponent**: [`EComponentType`](../enums/ue_ue.EComponentType.md)

___

### \_\_tid\_AnimNode\_BoneDrivenController\_\_

• `Private` **\_\_tid\_AnimNode\_BoneDrivenController\_\_**: `boolean`

___

### bAffectTargetRotationX

• **bAffectTargetRotationX**: `boolean`

___

### bAffectTargetRotationY

• **bAffectTargetRotationY**: `boolean`

___

### bAffectTargetRotationZ

• **bAffectTargetRotationZ**: `boolean`

___

### bAffectTargetScaleX

• **bAffectTargetScaleX**: `boolean`

___

### bAffectTargetScaleY

• **bAffectTargetScaleY**: `boolean`

___

### bAffectTargetScaleZ

• **bAffectTargetScaleZ**: `boolean`

___

### bAffectTargetTranslationX

• **bAffectTargetTranslationX**: `boolean`

___

### bAffectTargetTranslationY

• **bAffectTargetTranslationY**: `boolean`

___

### bAffectTargetTranslationZ

• **bAffectTargetTranslationZ**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

___

### bUseRange

• **bUseRange**: `boolean`

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
