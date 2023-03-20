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

#### Defined in

[ue/ue.d.ts:17600](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17600)

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

#### Defined in

[ue/ue.d.ts:17601](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17601)

## Properties

### Alpha

• **Alpha**: `number`

#### Defined in

[ue/ue.d.ts:17608](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17608)

___

### BasePose

• **BasePose**: [`PoseLink`](ue_ue.PoseLink.md)

#### Defined in

[ue/ue.d.ts:17602](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17602)

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

[ue/ue.d.ts:17603](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17603)

___

### LookAtLocation

• **LookAtLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:17606](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17606)

___

### PivotSocketName

• **PivotSocketName**: `string`

#### Defined in

[ue/ue.d.ts:17605](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17605)

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

### SocketAxis

• **SocketAxis**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:17607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17607)

___

### SourceSocketName

• **SourceSocketName**: `string`

#### Defined in

[ue/ue.d.ts:17604](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17604)

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

### \_\_tid\_AnimNode\_AimOffsetLookAt\_\_

• `Private` **\_\_tid\_AnimNode\_AimOffsetLookAt\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:17614](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17614)

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

[ue/ue.d.ts:17612](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17612)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_BlendSpacePlayer](ue_ue.AnimNode_BlendSpacePlayer.md).[StaticStruct](ue_ue.AnimNode_BlendSpacePlayer.md#staticstruct)

#### Defined in

[ue/ue.d.ts:17613](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17613)
