[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_CCDIK

# Class: AnimNode\_CCDIK

[ue/ue](../modules/ue_ue.md).AnimNode_CCDIK

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_CCDIK`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_CCDIK.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_CCDIK.md#actualalpha)
- [Alpha](ue_ue.AnimNode_CCDIK.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_CCDIK.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_CCDIK.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_CCDIK.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_CCDIK.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_CCDIK.md#alphascalebiasclamp)
- [ComponentPose](ue_ue.AnimNode_CCDIK.md#componentpose)
- [EffectorLocation](ue_ue.AnimNode_CCDIK.md#effectorlocation)
- [EffectorLocationSpace](ue_ue.AnimNode_CCDIK.md#effectorlocationspace)
- [EffectorTarget](ue_ue.AnimNode_CCDIK.md#effectortarget)
- [LODThreshold](ue_ue.AnimNode_CCDIK.md#lodthreshold)
- [MaxIterations](ue_ue.AnimNode_CCDIK.md#maxiterations)
- [Precision](ue_ue.AnimNode_CCDIK.md#precision)
- [RootBone](ue_ue.AnimNode_CCDIK.md#rootbone)
- [RotationLimitPerJoints](ue_ue.AnimNode_CCDIK.md#rotationlimitperjoints)
- [TipBone](ue_ue.AnimNode_CCDIK.md#tipbone)
- [\_\_tid\_AnimNode\_CCDIK\_\_](ue_ue.AnimNode_CCDIK.md#__tid_animnode_ccdik__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_CCDIK.md#balphaboolenabled)
- [bEnableRotationLimit](ue_ue.AnimNode_CCDIK.md#benablerotationlimit)
- [bStartFromTail](ue_ue.AnimNode_CCDIK.md#bstartfromtail)

### Methods

- [StaticClass](ue_ue.AnimNode_CCDIK.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_CCDIK.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_CCDIK**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:18228](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18228)

• **new AnimNode_CCDIK**(`EffectorLocation`, `EffectorLocationSpace`, `EffectorTarget`, `TipBone`, `RootBone`, `Precision`, `MaxIterations`, `bStartFromTail`, `bEnableRotationLimit`, `RotationLimitPerJoints`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `EffectorLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `EffectorLocationSpace` | [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md) |
| `EffectorTarget` | [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md) |
| `TipBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `RootBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `Precision` | `number` |
| `MaxIterations` | `number` |
| `bStartFromTail` | `boolean` |
| `bEnableRotationLimit` | `boolean` |
| `RotationLimitPerJoints` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:18229](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18229)

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

### EffectorLocation

• **EffectorLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:18230](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18230)

___

### EffectorLocationSpace

• **EffectorLocationSpace**: [`EBoneControlSpace`](../enums/ue_ue.EBoneControlSpace.md)

#### Defined in

[ue/ue.d.ts:18231](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18231)

___

### EffectorTarget

• **EffectorTarget**: [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md)

#### Defined in

[ue/ue.d.ts:18232](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18232)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17716)

___

### MaxIterations

• **MaxIterations**: `number`

#### Defined in

[ue/ue.d.ts:18236](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18236)

___

### Precision

• **Precision**: `number`

#### Defined in

[ue/ue.d.ts:18235](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18235)

___

### RootBone

• **RootBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18234](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18234)

___

### RotationLimitPerJoints

• **RotationLimitPerJoints**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:18239](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18239)

___

### TipBone

• **TipBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18233](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18233)

___

### \_\_tid\_AnimNode\_CCDIK\_\_

• `Private` **\_\_tid\_AnimNode\_CCDIK\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:18245](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18245)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17719)

___

### bEnableRotationLimit

• **bEnableRotationLimit**: `boolean`

#### Defined in

[ue/ue.d.ts:18238](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18238)

___

### bStartFromTail

• **bStartFromTail**: `boolean`

#### Defined in

[ue/ue.d.ts:18237](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18237)

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

[ue/ue.d.ts:18243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18243)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:18244](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18244)
