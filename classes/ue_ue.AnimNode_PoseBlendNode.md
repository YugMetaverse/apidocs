[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_PoseBlendNode

# Class: AnimNode\_PoseBlendNode

[ue/ue](../modules/ue_ue.md).AnimNode_PoseBlendNode

## Hierarchy

- [`AnimNode_PoseHandler`](ue_ue.AnimNode_PoseHandler.md)

  ↳ **`AnimNode_PoseBlendNode`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_PoseBlendNode.md#constructor)

### Properties

- [BlendOption](ue_ue.AnimNode_PoseBlendNode.md#blendoption)
- [BlendWeight](ue_ue.AnimNode_PoseBlendNode.md#blendweight)
- [CustomCurve](ue_ue.AnimNode_PoseBlendNode.md#customcurve)
- [GroupIndex](ue_ue.AnimNode_PoseBlendNode.md#groupindex)
- [GroupRole](ue_ue.AnimNode_PoseBlendNode.md#grouprole)
- [InternalTimeAccumulator](ue_ue.AnimNode_PoseBlendNode.md#internaltimeaccumulator)
- [PoseAsset](ue_ue.AnimNode_PoseBlendNode.md#poseasset)
- [SourcePose](ue_ue.AnimNode_PoseBlendNode.md#sourcepose)
- [\_\_tid\_AnimNode\_PoseBlendNode\_\_](ue_ue.AnimNode_PoseBlendNode.md#__tid_animnode_poseblendnode__)
- [bIgnoreForRelevancyTest](ue_ue.AnimNode_PoseBlendNode.md#bignoreforrelevancytest)

### Methods

- [StaticClass](ue_ue.AnimNode_PoseBlendNode.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_PoseBlendNode.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_PoseBlendNode**()

#### Overrides

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[constructor](ue_ue.AnimNode_PoseHandler.md#constructor)

• **new AnimNode_PoseBlendNode**(`SourcePose`, `BlendOption`, `CustomCurve`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourcePose` | [`PoseLink`](ue_ue.PoseLink.md) |
| `BlendOption` | [`EAlphaBlendOption`](../enums/ue_ue.EAlphaBlendOption.md) |
| `CustomCurve` | [`CurveFloat`](ue_ue.CurveFloat.md) |

#### Overrides

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[constructor](ue_ue.AnimNode_PoseHandler.md#constructor)

## Properties

### BlendOption

• **BlendOption**: [`EAlphaBlendOption`](../enums/ue_ue.EAlphaBlendOption.md)

___

### BlendWeight

• **BlendWeight**: `number`

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[BlendWeight](ue_ue.AnimNode_PoseHandler.md#blendweight)

___

### CustomCurve

• **CustomCurve**: [`CurveFloat`](ue_ue.CurveFloat.md)

___

### GroupIndex

• **GroupIndex**: `number`

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[GroupIndex](ue_ue.AnimNode_PoseHandler.md#groupindex)

___

### GroupRole

• **GroupRole**: [`EAnimGroupRole`](../enums/ue_ue.EAnimGroupRole.md)

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[GroupRole](ue_ue.AnimNode_PoseHandler.md#grouprole)

___

### InternalTimeAccumulator

• **InternalTimeAccumulator**: `number`

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[InternalTimeAccumulator](ue_ue.AnimNode_PoseHandler.md#internaltimeaccumulator)

___

### PoseAsset

• **PoseAsset**: [`PoseAsset`](ue_ue.PoseAsset.md)

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[PoseAsset](ue_ue.AnimNode_PoseHandler.md#poseasset)

___

### SourcePose

• **SourcePose**: [`PoseLink`](ue_ue.PoseLink.md)

___

### \_\_tid\_AnimNode\_PoseBlendNode\_\_

• `Private` **\_\_tid\_AnimNode\_PoseBlendNode\_\_**: `boolean`

___

### bIgnoreForRelevancyTest

• **bIgnoreForRelevancyTest**: `boolean`

#### Inherited from

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[bIgnoreForRelevancyTest](ue_ue.AnimNode_PoseHandler.md#bignoreforrelevancytest)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[StaticClass](ue_ue.AnimNode_PoseHandler.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_PoseHandler](ue_ue.AnimNode_PoseHandler.md).[StaticStruct](ue_ue.AnimNode_PoseHandler.md#staticstruct)
