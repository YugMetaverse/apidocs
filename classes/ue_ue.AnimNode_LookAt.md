[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_LookAt

# Class: AnimNode\_LookAt

[ue/ue](../modules/ue_ue.md).AnimNode_LookAt

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_LookAt`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_LookAt.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_LookAt.md#actualalpha)
- [Alpha](ue_ue.AnimNode_LookAt.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_LookAt.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_LookAt.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_LookAt.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_LookAt.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_LookAt.md#alphascalebiasclamp)
- [BoneToModify](ue_ue.AnimNode_LookAt.md#bonetomodify)
- [ComponentPose](ue_ue.AnimNode_LookAt.md#componentpose)
- [CustomLookAtAxis](ue_ue.AnimNode_LookAt.md#customlookataxis)
- [CustomLookUpAxis](ue_ue.AnimNode_LookAt.md#customlookupaxis)
- [InterpolationTime](ue_ue.AnimNode_LookAt.md#interpolationtime)
- [InterpolationTriggerThreashold](ue_ue.AnimNode_LookAt.md#interpolationtriggerthreashold)
- [InterpolationType](ue_ue.AnimNode_LookAt.md#interpolationtype)
- [LODThreshold](ue_ue.AnimNode_LookAt.md#lodthreshold)
- [LookAtAxis](ue_ue.AnimNode_LookAt.md#lookataxis)
- [LookAtBone](ue_ue.AnimNode_LookAt.md#lookatbone)
- [LookAtClamp](ue_ue.AnimNode_LookAt.md#lookatclamp)
- [LookAtLocation](ue_ue.AnimNode_LookAt.md#lookatlocation)
- [LookAtSocket](ue_ue.AnimNode_LookAt.md#lookatsocket)
- [LookAtTarget](ue_ue.AnimNode_LookAt.md#lookattarget)
- [LookAt\_Axis](ue_ue.AnimNode_LookAt.md#lookat_axis)
- [LookUpAxis](ue_ue.AnimNode_LookAt.md#lookupaxis)
- [LookUp\_Axis](ue_ue.AnimNode_LookAt.md#lookup_axis)
- [\_\_tid\_AnimNode\_LookAt\_\_](ue_ue.AnimNode_LookAt.md#__tid_animnode_lookat__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_LookAt.md#balphaboolenabled)
- [bUseLookUpAxis](ue_ue.AnimNode_LookAt.md#buselookupaxis)

### Methods

- [StaticClass](ue_ue.AnimNode_LookAt.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_LookAt.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_LookAt**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:18884](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18884)

• **new AnimNode_LookAt**(`BoneToModify`, `LookAtTarget`, `LookAtLocation`, `LookAt_Axis`, `bUseLookUpAxis`, `InterpolationType`, `LookUp_Axis`, `LookAtClamp`, `InterpolationTime`, `InterpolationTriggerThreashold`, `LookAtBone`, `LookAtSocket`, `LookAtAxis`, `CustomLookAtAxis`, `LookUpAxis`, `CustomLookUpAxis`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneToModify` | [`BoneReference`](ue_ue.BoneReference.md) |
| `LookAtTarget` | [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md) |
| `LookAtLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `LookAt_Axis` | [`Axis`](ue_ue.Axis.md) |
| `bUseLookUpAxis` | `boolean` |
| `InterpolationType` | [`EInterpolationBlend`](../enums/ue_ue.EInterpolationBlend.md) |
| `LookUp_Axis` | [`Axis`](ue_ue.Axis.md) |
| `LookAtClamp` | `number` |
| `InterpolationTime` | `number` |
| `InterpolationTriggerThreashold` | `number` |
| `LookAtBone` | [`BoneReference`](ue_ue.BoneReference.md) |
| `LookAtSocket` | `string` |
| `LookAtAxis` | [`EAxisOption`](../enums/ue_ue.EAxisOption.md) |
| `CustomLookAtAxis` | [`Vector`](ue_ue_s.Vector.md) |
| `LookUpAxis` | [`EAxisOption`](../enums/ue_ue.EAxisOption.md) |
| `CustomLookUpAxis` | [`Vector`](ue_ue_s.Vector.md) |

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:18885](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18885)

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

[ue/ue.d.ts:18886](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18886)

___

### ComponentPose

• **ComponentPose**: [`ComponentSpacePoseLink`](ue_ue.ComponentSpacePoseLink.md)

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[ComponentPose](ue_ue.AnimNode_SkeletalControlBase.md#componentpose)

#### Defined in

[ue/ue.d.ts:17715](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17715)

___

### CustomLookAtAxis

• **CustomLookAtAxis**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:18899](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18899)

___

### CustomLookUpAxis

• **CustomLookUpAxis**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:18901](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18901)

___

### InterpolationTime

• **InterpolationTime**: `number`

#### Defined in

[ue/ue.d.ts:18894](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18894)

___

### InterpolationTriggerThreashold

• **InterpolationTriggerThreashold**: `number`

#### Defined in

[ue/ue.d.ts:18895](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18895)

___

### InterpolationType

• **InterpolationType**: [`EInterpolationBlend`](../enums/ue_ue.EInterpolationBlend.md)

#### Defined in

[ue/ue.d.ts:18891](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18891)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17716)

___

### LookAtAxis

• **LookAtAxis**: [`EAxisOption`](../enums/ue_ue.EAxisOption.md)

#### Defined in

[ue/ue.d.ts:18898](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18898)

___

### LookAtBone

• **LookAtBone**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18896](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18896)

___

### LookAtClamp

• **LookAtClamp**: `number`

#### Defined in

[ue/ue.d.ts:18893](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18893)

___

### LookAtLocation

• **LookAtLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:18888](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18888)

___

### LookAtSocket

• **LookAtSocket**: `string`

#### Defined in

[ue/ue.d.ts:18897](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18897)

___

### LookAtTarget

• **LookAtTarget**: [`BoneSocketTarget`](ue_ue.BoneSocketTarget.md)

#### Defined in

[ue/ue.d.ts:18887](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18887)

___

### LookAt\_Axis

• **LookAt\_Axis**: [`Axis`](ue_ue.Axis.md)

#### Defined in

[ue/ue.d.ts:18889](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18889)

___

### LookUpAxis

• **LookUpAxis**: [`EAxisOption`](../enums/ue_ue.EAxisOption.md)

#### Defined in

[ue/ue.d.ts:18900](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18900)

___

### LookUp\_Axis

• **LookUp\_Axis**: [`Axis`](ue_ue.Axis.md)

#### Defined in

[ue/ue.d.ts:18892](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18892)

___

### \_\_tid\_AnimNode\_LookAt\_\_

• `Private` **\_\_tid\_AnimNode\_LookAt\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:18907](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18907)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17719)

___

### bUseLookUpAxis

• **bUseLookUpAxis**: `boolean`

#### Defined in

[ue/ue.d.ts:18890](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18890)

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

[ue/ue.d.ts:18905](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18905)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:18906](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18906)
