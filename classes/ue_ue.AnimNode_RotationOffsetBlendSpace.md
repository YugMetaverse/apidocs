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

## Properties

### Alpha

• **Alpha**: `number`

___

### AlphaBoolBlend

• **AlphaBoolBlend**: [`InputAlphaBoolBlend`](ue_ue.InputAlphaBoolBlend.md)

___

### AlphaCurveName

• **AlphaCurveName**: `string`

___

### AlphaInputType

• **AlphaInputType**: [`EAnimAlphaInputType`](../enums/ue_ue.EAnimAlphaInputType.md)

___

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

___

### AlphaScaleBiasClamp

• **AlphaScaleBiasClamp**: [`InputScaleBiasClamp`](ue_ue.InputScaleBiasClamp.md)

___

### BasePose

• **BasePose**: [`PoseLink`](ue_ue.PoseLink.md)

___

### BlendSpace

• **BlendSpace**: [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[BlendSpace](ue_ue.AnimNode_BlendSpacePlayer.md#blendspace)

___

### BlendWeight

• **BlendWeight**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[BlendWeight](ue_ue.AnimNode_BlendSpacePlayer.md#blendweight)

___

### GroupIndex

• **GroupIndex**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[GroupIndex](ue_ue.AnimNode_BlendSpacePlayer.md#groupindex)

___

### GroupRole

• **GroupRole**: [`EAnimGroupRole`](../enums/ue_ue.EAnimGroupRole.md)

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[GroupRole](ue_ue.AnimNode_BlendSpacePlayer.md#grouprole)

___

### InternalTimeAccumulator

• **InternalTimeAccumulator**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[InternalTimeAccumulator](ue_ue.AnimNode_BlendSpacePlayer.md#internaltimeaccumulator)

___

### LODThreshold

• **LODThreshold**: `number`

___

### PlayRate

• **PlayRate**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[PlayRate](ue_ue.AnimNode_BlendSpacePlayer.md#playrate)

___

### PreviousBlendSpace

• **PreviousBlendSpace**: [`BlendSpaceBase`](ue_ue.BlendSpaceBase.md)

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[PreviousBlendSpace](ue_ue.AnimNode_BlendSpacePlayer.md#previousblendspace)

___

### StartPosition

• **StartPosition**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[StartPosition](ue_ue.AnimNode_BlendSpacePlayer.md#startposition)

___

### X

• **X**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[X](ue_ue.AnimNode_BlendSpacePlayer.md#x)

___

### Y

• **Y**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[Y](ue_ue.AnimNode_BlendSpacePlayer.md#y)

___

### Z

• **Z**: `number`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[Z](ue_ue.AnimNode_BlendSpacePlayer.md#z)

___

### \_\_tid\_AnimNode\_RotationOffsetBlendSpace\_\_

• `Private` **\_\_tid\_AnimNode\_RotationOffsetBlendSpace\_\_**: `boolean`

___

### bAlphaBoolEnabled

• **bAlphaBoolEnabled**: `boolean`

___

### bIgnoreForRelevancyTest

• **bIgnoreForRelevancyTest**: `boolean`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[bIgnoreForRelevancyTest](ue_ue.AnimNode_BlendSpacePlayer.md#bignoreforrelevancytest)

___

### bLoop

• **bLoop**: `boolean`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[bLoop](ue_ue.AnimNode_BlendSpacePlayer.md#bloop)

___

### bResetPlayTimeWhenBlendSpaceChanges

• **bResetPlayTimeWhenBlendSpaceChanges**: `boolean`

#### Inherited from

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[bResetPlayTimeWhenBlendSpaceChanges](ue_ue.AnimNode_BlendSpacePlayer.md#bresetplaytimewhenblendspacechanges)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[StaticClass](ue_ue.AnimNode_BlendSpacePlayer.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[StaticStruct](ue_ue.AnimNode_BlendSpacePlayer.md#staticstruct)
