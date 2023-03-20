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

#### Defined in

[ue/ue.d.ts:18158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18158)

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

#### Defined in

[ue/ue.d.ts:18159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18159)

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

### DestinationMode

• **DestinationMode**: [`EDrivenDestinationMode`](../enums/ue_ue.EDrivenDestinationMode.md)

#### Defined in

[ue/ue.d.ts:18170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18170)

___

### DrivingCurve

• **DrivingCurve**: [`CurveFloat`](ue_ue.CurveFloat.md)

#### Defined in

[ue/ue.d.ts:18161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18161)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17716)

___

### ModificationMode

• **ModificationMode**: [`EDrivenBoneModificationMode`](../enums/ue_ue.EDrivenBoneModificationMode.md)

#### Defined in

[ue/ue.d.ts:18171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18171)

___

### Multiplier

• **Multiplier**: `number`

#### Defined in

[ue/ue.d.ts:18162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18162)

___

### ParameterName

• **ParameterName**: `string`

#### Defined in

[ue/ue.d.ts:18167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18167)

___

### RangeMax

• **RangeMax**: `number`

#### Defined in

[ue/ue.d.ts:18164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18164)

___

### RangeMin

• **RangeMin**: `number`

#### Defined in

[ue/ue.d.ts:18163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18163)

___

### RemappedMax

• **RemappedMax**: `number`

#### Defined in

[ue/ue.d.ts:18166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18166)

___

### RemappedMin

• **RemappedMin**: `number`

#### Defined in

[ue/ue.d.ts:18165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18165)

___

### SourceBone

• **SourceBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18160)

___

### SourceComponent

• **SourceComponent**: [`EComponentType`](../enums/ue_ue.EComponentType.md)

#### Defined in

[ue/ue.d.ts:18172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18172)

___

### TargetBone

• **TargetBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18168)

___

### TargetComponent

• **TargetComponent**: [`EComponentType`](../enums/ue_ue.EComponentType.md)

#### Defined in

[ue/ue.d.ts:18169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18169)

___

### \_\_tid\_AnimNode\_BoneDrivenController\_\_

• `Private` **\_\_tid\_AnimNode\_BoneDrivenController\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:18188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18188)

___

### bAffectTargetRotationX

• **bAffectTargetRotationX**: `boolean`

#### Defined in

[ue/ue.d.ts:18177](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18177)

___

### bAffectTargetRotationY

• **bAffectTargetRotationY**: `boolean`

#### Defined in

[ue/ue.d.ts:18178](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18178)

___

### bAffectTargetRotationZ

• **bAffectTargetRotationZ**: `boolean`

#### Defined in

[ue/ue.d.ts:18179](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18179)

___

### bAffectTargetScaleX

• **bAffectTargetScaleX**: `boolean`

#### Defined in

[ue/ue.d.ts:18180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18180)

___

### bAffectTargetScaleY

• **bAffectTargetScaleY**: `boolean`

#### Defined in

[ue/ue.d.ts:18181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18181)

___

### bAffectTargetScaleZ

• **bAffectTargetScaleZ**: `boolean`

#### Defined in

[ue/ue.d.ts:18182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18182)

___

### bAffectTargetTranslationX

• **bAffectTargetTranslationX**: `boolean`

#### Defined in

[ue/ue.d.ts:18174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18174)

___

### bAffectTargetTranslationY

• **bAffectTargetTranslationY**: `boolean`

#### Defined in

[ue/ue.d.ts:18175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18175)

___

### bAffectTargetTranslationZ

• **bAffectTargetTranslationZ**: `boolean`

#### Defined in

[ue/ue.d.ts:18176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18176)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17719)

___

### bUseRange

• **bUseRange**: `boolean`

#### Defined in

[ue/ue.d.ts:18173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18173)

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

[ue/ue.d.ts:18186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18186)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:18187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18187)
