[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_HandIKRetargeting

# Class: AnimNode\_HandIKRetargeting

[ue/ue](../modules/ue_ue.md).AnimNode_HandIKRetargeting

## Hierarchy

- [`AnimNode_SkeletalControlBase`](ue_ue.AnimNode_SkeletalControlBase.md)

  ↳ **`AnimNode_HandIKRetargeting`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_HandIKRetargeting.md#constructor)

### Properties

- [ActualAlpha](ue_ue.AnimNode_HandIKRetargeting.md#actualalpha)
- [Alpha](ue_ue.AnimNode_HandIKRetargeting.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_HandIKRetargeting.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_HandIKRetargeting.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_HandIKRetargeting.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_HandIKRetargeting.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_HandIKRetargeting.md#alphascalebiasclamp)
- [ComponentPose](ue_ue.AnimNode_HandIKRetargeting.md#componentpose)
- [HandFKWeight](ue_ue.AnimNode_HandIKRetargeting.md#handfkweight)
- [IKBonesToMove](ue_ue.AnimNode_HandIKRetargeting.md#ikbonestomove)
- [LODThreshold](ue_ue.AnimNode_HandIKRetargeting.md#lodthreshold)
- [LeftHandFK](ue_ue.AnimNode_HandIKRetargeting.md#lefthandfk)
- [LeftHandIK](ue_ue.AnimNode_HandIKRetargeting.md#lefthandik)
- [RightHandFK](ue_ue.AnimNode_HandIKRetargeting.md#righthandfk)
- [RightHandIK](ue_ue.AnimNode_HandIKRetargeting.md#righthandik)
- [\_\_tid\_AnimNode\_HandIKRetargeting\_\_](ue_ue.AnimNode_HandIKRetargeting.md#__tid_animnode_handikretargeting__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_HandIKRetargeting.md#balphaboolenabled)

### Methods

- [StaticClass](ue_ue.AnimNode_HandIKRetargeting.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_HandIKRetargeting.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_HandIKRetargeting**()

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:18511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18511)

• **new AnimNode_HandIKRetargeting**(`RightHandFK`, `LeftHandFK`, `RightHandIK`, `LeftHandIK`, `IKBonesToMove`, `HandFKWeight`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `RightHandFK` | [`BoneReference`](ue_ue.BoneReference.md) |
| `LeftHandFK` | [`BoneReference`](ue_ue.BoneReference.md) |
| `RightHandIK` | [`BoneReference`](ue_ue.BoneReference.md) |
| `LeftHandIK` | [`BoneReference`](ue_ue.BoneReference.md) |
| `IKBonesToMove` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneReference`](ue_ue.BoneReference.md)\> |
| `HandFKWeight` | `number` |

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[constructor](ue_ue.AnimNode_SkeletalControlBase.md#constructor)

#### Defined in

[ue/ue.d.ts:18512](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18512)

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

### HandFKWeight

• **HandFKWeight**: `number`

#### Defined in

[ue/ue.d.ts:18518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18518)

___

### IKBonesToMove

• **IKBonesToMove**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoneReference`](ue_ue.BoneReference.md)\>

#### Defined in

[ue/ue.d.ts:18517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18517)

___

### LODThreshold

• **LODThreshold**: `number`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[LODThreshold](ue_ue.AnimNode_SkeletalControlBase.md#lodthreshold)

#### Defined in

[ue/ue.d.ts:17716](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17716)

___

### LeftHandFK

• **LeftHandFK**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18514)

___

### LeftHandIK

• **LeftHandIK**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18516](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18516)

___

### RightHandFK

• **RightHandFK**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18513)

___

### RightHandIK

• **RightHandIK**: [`BoneReference`](ue_ue.BoneReference.md)

#### Defined in

[ue/ue.d.ts:18515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18515)

___

### \_\_tid\_AnimNode\_HandIKRetargeting\_\_

• `Private` **\_\_tid\_AnimNode\_HandIKRetargeting\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:18524](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18524)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Inherited from

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[bAlphaBoolEnabled](ue_ue.AnimNode_SkeletalControlBase.md#balphaboolenabled)

#### Defined in

[ue/ue.d.ts:17719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17719)

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

[ue/ue.d.ts:18522](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18522)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_SkeletalControlBase](ue_ue.AnimNode_SkeletalControlBase.md).[StaticStruct](ue_ue.AnimNode_SkeletalControlBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:18523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18523)
