[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_RotationOffsetBlendSpace

# Class: AnimNode\_RotationOffsetBlendSpace

[ue/ue](../modules/ue_ue.md).AnimNode_RotationOffsetBlendSpace

## Hierarchy

- [`AnimNode_BlendSpacePlayer`](ue_ue.AnimNode_BlendSpacePlayer.md)

  ↳ **`AnimNode_RotationOffsetBlendSpace`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_RotationOffsetBlendSpace.md#constructor)

### Properties

- [Alpha](ue_ue.AnimNode_RotationOffsetBlendSpace.md#alpha)
- [AlphaBoolBlend](ue_ue.AnimNode_RotationOffsetBlendSpace.md#alphaboolblend)
- [AlphaCurveName](ue_ue.AnimNode_RotationOffsetBlendSpace.md#alphacurvename)
- [AlphaInputType](ue_ue.AnimNode_RotationOffsetBlendSpace.md#alphainputtype)
- [AlphaScaleBias](ue_ue.AnimNode_RotationOffsetBlendSpace.md#alphascalebias)
- [AlphaScaleBiasClamp](ue_ue.AnimNode_RotationOffsetBlendSpace.md#alphascalebiasclamp)
- [BasePose](ue_ue.AnimNode_RotationOffsetBlendSpace.md#basepose)
- [BlendSpace](ue_ue.AnimNode_RotationOffsetBlendSpace.md#blendspace)
- [BlendWeight](ue_ue.AnimNode_RotationOffsetBlendSpace.md#blendweight)
- [GroupIndex](ue_ue.AnimNode_RotationOffsetBlendSpace.md#groupindex)
- [GroupRole](ue_ue.AnimNode_RotationOffsetBlendSpace.md#grouprole)
- [InternalTimeAccumulator](ue_ue.AnimNode_RotationOffsetBlendSpace.md#internaltimeaccumulator)
- [LODThreshold](ue_ue.AnimNode_RotationOffsetBlendSpace.md#lodthreshold)
- [PlayRate](ue_ue.AnimNode_RotationOffsetBlendSpace.md#playrate)
- [PreviousBlendSpace](ue_ue.AnimNode_RotationOffsetBlendSpace.md#previousblendspace)
- [StartPosition](ue_ue.AnimNode_RotationOffsetBlendSpace.md#startposition)
- [X](ue_ue.AnimNode_RotationOffsetBlendSpace.md#x)
- [Y](ue_ue.AnimNode_RotationOffsetBlendSpace.md#y)
- [Z](ue_ue.AnimNode_RotationOffsetBlendSpace.md#z)
- [\_\_tid\_AnimNode\_RotationOffsetBlendSpace\_\_](ue_ue.AnimNode_RotationOffsetBlendSpace.md#__tid_animnode_rotationoffsetblendspace__)
- [bAlphaBoolEnabled](ue_ue.AnimNode_RotationOffsetBlendSpace.md#balphaboolenabled)
- [bIgnoreForRelevancyTest](ue_ue.AnimNode_RotationOffsetBlendSpace.md#bignoreforrelevancytest)
- [bLoop](ue_ue.AnimNode_RotationOffsetBlendSpace.md#bloop)
- [bResetPlayTimeWhenBlendSpaceChanges](ue_ue.AnimNode_RotationOffsetBlendSpace.md#bresetplaytimewhenblendspacechanges)

### Methods

- [StaticClass](ue_ue.AnimNode_RotationOffsetBlendSpace.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_RotationOffsetBlendSpace.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_RotationOffsetBlendSpace**()

#### Overrides

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[constructor](ue_ue.AnimNode_BlendSpacePlayer.md#constructor)

#### Defined in

[ue/ue.d.ts:19470](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19470)

• **new AnimNode_RotationOffsetBlendSpace**(`BasePose`, `LODThreshold`, `Alpha`, `AlphaScaleBias`, `AlphaBoolBlend`, `AlphaCurveName`, `AlphaScaleBiasClamp`, `AlphaInputType`, `bAlphaBoolEnabled`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BasePose` | [`PoseLink`](ue_ue.PoseLink.md) |
| `LODThreshold` | `number` |
| `Alpha` | `number` |
| `AlphaScaleBias` | [`InputScaleBias`](ue_ue.InputScaleBias.md) |
| `AlphaBoolBlend` | [`InputAlphaBoolBlend`](ue_ue.InputAlphaBoolBlend.md) |
| `AlphaCurveName` | `string` |
| `AlphaScaleBiasClamp` | [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md) |
| `AlphaInputType` | [`EAnimAlphaInputType`](../enums/ue_ue.EAnimAlphaInputType.md) |
| `bAlphaBoolEnabled` | `boolean` |

#### Overrides

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[constructor](ue_ue.AnimNode_BlendSpacePlayer.md#constructor)

#### Defined in

[ue/ue.d.ts:19471](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19471)

## Properties

### Alpha

• **Alpha**: `number`

#### Defined in

[ue/ue.d.ts:19474](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19474)

___

### AlphaBoolBlend

• **AlphaBoolBlend**: [`InputAlphaBoolBlend`](ue_ue.InputAlphaBoolBlend.md)

#### Defined in

[ue/ue.d.ts:19476](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19476)

___

### AlphaCurveName

• **AlphaCurveName**: `string`

#### Defined in

[ue/ue.d.ts:19477](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19477)

___

### AlphaInputType

• **AlphaInputType**: [`EAnimAlphaInputType`](../enums/ue_ue.EAnimAlphaInputType.md)

#### Defined in

[ue/ue.d.ts:19479](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19479)

___

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

#### Defined in

[ue/ue.d.ts:19475](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19475)

___

### AlphaScaleBiasClamp

• **AlphaScaleBiasClamp**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

#### Defined in

[ue/ue.d.ts:19478](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19478)

___

### BasePose

• **BasePose**: [`PoseLink`](ue_ue.PoseLink.md)

#### Defined in

[ue/ue.d.ts:19472](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19472)

___

### BlendSpace

• **BlendSpace**: [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[BlendSpace](ue_ue.AnimNode_BlendSpacePlayer.md#blendspace)

#### Defined in

[ue/ue.d.ts:17589](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17589)

___

### BlendWeight

• **BlendWeight**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[BlendWeight](ue_ue.AnimNode_BlendSpacePlayer.md#blendweight)

#### Defined in

[ue/ue.d.ts:17569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17569)

___

### GroupIndex

• **GroupIndex**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[GroupIndex](ue_ue.AnimNode_BlendSpacePlayer.md#groupindex)

#### Defined in

[ue/ue.d.ts:17566](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17566)

___

### GroupRole

• **GroupRole**: [`EAnimGroupRole`](../enums/ue_ue.EAnimGroupRole.md)

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[GroupRole](ue_ue.AnimNode_BlendSpacePlayer.md#grouprole)

#### Defined in

[ue/ue.d.ts:17567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17567)

___

### InternalTimeAccumulator

• **InternalTimeAccumulator**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[InternalTimeAccumulator](ue_ue.AnimNode_BlendSpacePlayer.md#internaltimeaccumulator)

#### Defined in

[ue/ue.d.ts:17570](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17570)

___

### LODThreshold

• **LODThreshold**: `number`

#### Defined in

[ue/ue.d.ts:19473](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19473)

___

### PlayRate

• **PlayRate**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[PlayRate](ue_ue.AnimNode_BlendSpacePlayer.md#playrate)

#### Defined in

[ue/ue.d.ts:17585](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17585)

___

### PreviousBlendSpace

• **PreviousBlendSpace**: [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[PreviousBlendSpace](ue_ue.AnimNode_BlendSpacePlayer.md#previousblendspace)

#### Defined in

[ue/ue.d.ts:17590](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17590)

___

### StartPosition

• **StartPosition**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[StartPosition](ue_ue.AnimNode_BlendSpacePlayer.md#startposition)

#### Defined in

[ue/ue.d.ts:17588](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17588)

___

### X

• **X**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[X](ue_ue.AnimNode_BlendSpacePlayer.md#x)

#### Defined in

[ue/ue.d.ts:17582](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17582)

___

### Y

• **Y**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[Y](ue_ue.AnimNode_BlendSpacePlayer.md#y)

#### Defined in

[ue/ue.d.ts:17583](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17583)

___

### Z

• **Z**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[Z](ue_ue.AnimNode_BlendSpacePlayer.md#z)

#### Defined in

[ue/ue.d.ts:17584](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17584)

___

### \_\_tid\_AnimNode\_RotationOffsetBlendSpace\_\_

• `Private` **\_\_tid\_AnimNode\_RotationOffsetBlendSpace\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19486](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19486)

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:19480](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19480)

___

### bIgnoreForRelevancyTest

• **bIgnoreForRelevancyTest**: `boolean`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[bIgnoreForRelevancyTest](ue_ue.AnimNode_BlendSpacePlayer.md#bignoreforrelevancytest)

#### Defined in

[ue/ue.d.ts:17568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17568)

___

### bLoop

• **bLoop**: `boolean`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[bLoop](ue_ue.AnimNode_BlendSpacePlayer.md#bloop)

#### Defined in

[ue/ue.d.ts:17586](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17586)

___

### bResetPlayTimeWhenBlendSpaceChanges

• **bResetPlayTimeWhenBlendSpaceChanges**: `boolean`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[bResetPlayTimeWhenBlendSpaceChanges](ue_ue.AnimNode_BlendSpacePlayer.md#bresetplaytimewhenblendspacechanges)

#### Defined in

[ue/ue.d.ts:17587](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17587)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[StaticClass](ue_ue.AnimNode_BlendSpacePlayer.md#staticclass)

#### Defined in

[ue/ue.d.ts:19484](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19484)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[StaticStruct](ue_ue.AnimNode_BlendSpacePlayer.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19485](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19485)
