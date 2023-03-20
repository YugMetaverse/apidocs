[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_AimOffsetLookAt

# Class: AnimNode\_AimOffsetLookAt

[ue/ue](../modules/ue_ue.md).AnimNode_AimOffsetLookAt

## Hierarchy

- [`AnimNode_BlendSpacePlayer`](ue_ue.AnimNode_BlendSpacePlayer.md)

  ↳ **`AnimNode_AimOffsetLookAt`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_AimOffsetLookAt.md#constructor)

### Properties

- [Alpha](ue_ue.AnimNode_AimOffsetLookAt.md#alpha)
- [BasePose](ue_ue.AnimNode_AimOffsetLookAt.md#basepose)
- [BlendSpace](ue_ue.AnimNode_AimOffsetLookAt.md#blendspace)
- [BlendWeight](ue_ue.AnimNode_AimOffsetLookAt.md#blendweight)
- [GroupIndex](ue_ue.AnimNode_AimOffsetLookAt.md#groupindex)
- [GroupRole](ue_ue.AnimNode_AimOffsetLookAt.md#grouprole)
- [InternalTimeAccumulator](ue_ue.AnimNode_AimOffsetLookAt.md#internaltimeaccumulator)
- [LODThreshold](ue_ue.AnimNode_AimOffsetLookAt.md#lodthreshold)
- [LookAtLocation](ue_ue.AnimNode_AimOffsetLookAt.md#lookatlocation)
- [PivotSocketName](ue_ue.AnimNode_AimOffsetLookAt.md#pivotsocketname)
- [PlayRate](ue_ue.AnimNode_AimOffsetLookAt.md#playrate)
- [PreviousBlendSpace](ue_ue.AnimNode_AimOffsetLookAt.md#previousblendspace)
- [SocketAxis](ue_ue.AnimNode_AimOffsetLookAt.md#socketaxis)
- [SourceSocketName](ue_ue.AnimNode_AimOffsetLookAt.md#sourcesocketname)
- [StartPosition](ue_ue.AnimNode_AimOffsetLookAt.md#startposition)
- [X](ue_ue.AnimNode_AimOffsetLookAt.md#x)
- [Y](ue_ue.AnimNode_AimOffsetLookAt.md#y)
- [Z](ue_ue.AnimNode_AimOffsetLookAt.md#z)
- [\_\_tid\_AnimNode\_AimOffsetLookAt\_\_](ue_ue.AnimNode_AimOffsetLookAt.md#__tid_animnode_aimoffsetlookat__)
- [bIgnoreForRelevancyTest](ue_ue.AnimNode_AimOffsetLookAt.md#bignoreforrelevancytest)
- [bLoop](ue_ue.AnimNode_AimOffsetLookAt.md#bloop)
- [bResetPlayTimeWhenBlendSpaceChanges](ue_ue.AnimNode_AimOffsetLookAt.md#bresetplaytimewhenblendspacechanges)

### Methods

- [StaticClass](ue_ue.AnimNode_AimOffsetLookAt.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_AimOffsetLookAt.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_AimOffsetLookAt**()

#### Overrides

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[constructor](ue_ue.AnimNode_BlendSpacePlayer.md#constructor)

• **new AnimNode_AimOffsetLookAt**(`BasePose`, `LODThreshold`, `SourceSocketName`, `PivotSocketName`, `LookAtLocation`, `SocketAxis`, `Alpha`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BasePose` | [`PoseLink`](ue_ue.PoseLink.md) |
| `LODThreshold` | `number` |
| `SourceSocketName` | `string` |
| `PivotSocketName` | `string` |
| `LookAtLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `SocketAxis` | [`Vector`](ue_ue_s.Vector.md) |
| `Alpha` | `number` |

#### Overrides

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[constructor](ue_ue.AnimNode_BlendSpacePlayer.md#constructor)

## Properties

### Alpha

• **Alpha**: `number`

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

### LookAtLocation

• **LookAtLocation**: [`Vector`](ue_ue_s.Vector.md)

___

### PivotSocketName

• **PivotSocketName**: `string`

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

### SocketAxis

• **SocketAxis**: [`Vector`](ue_ue_s.Vector.md)

___

### SourceSocketName

• **SourceSocketName**: `string`

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

### \_\_tid\_AnimNode\_AimOffsetLookAt\_\_

• `Private` **\_\_tid\_AnimNode\_AimOffsetLookAt\_\_**: `boolean`

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
