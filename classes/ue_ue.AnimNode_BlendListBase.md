[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_BlendListBase

# Class: AnimNode\_BlendListBase

[ue/ue](../modules/ue_ue.md).AnimNode_BlendListBase

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_BlendListBase`**

  ↳↳ [`AnimNode_BlendListByBool`](ue_ue.AnimNode_BlendListByBool.md)

  ↳↳ [`AnimNode_BlendListByEnum`](ue_ue.AnimNode_BlendListByEnum.md)

  ↳↳ [`AnimNode_BlendListByInt`](ue_ue.AnimNode_BlendListByInt.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_BlendListBase.md#constructor)

### Properties

- [BlendPose](ue_ue.AnimNode_BlendListBase.md#blendpose)
- [BlendProfile](ue_ue.AnimNode_BlendListBase.md#blendprofile)
- [BlendTime](ue_ue.AnimNode_BlendListBase.md#blendtime)
- [BlendType](ue_ue.AnimNode_BlendListBase.md#blendtype)
- [CustomBlendCurve](ue_ue.AnimNode_BlendListBase.md#customblendcurve)
- [TransitionType](ue_ue.AnimNode_BlendListBase.md#transitiontype)
- [\_\_tid\_AnimNode\_BlendListBase\_\_](ue_ue.AnimNode_BlendListBase.md#__tid_animnode_blendlistbase__)
- [bResetChildOnActivation](ue_ue.AnimNode_BlendListBase.md#bresetchildonactivation)

### Methods

- [StaticClass](ue_ue.AnimNode_BlendListBase.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_BlendListBase.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_BlendListBase**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

#### Defined in

[ue/ue.d.ts:18036](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18036)

• **new AnimNode_BlendListBase**(`BlendPose`, `BlendTime`, `TransitionType`, `BlendType`, `bResetChildOnActivation`, `CustomBlendCurve`, `BlendProfile`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BlendPose` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseLink`](ue_ue.PoseLink.md)\> |
| `BlendTime` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `TransitionType` | [`EBlendListTransitionType`](../enums/ue_ue.EBlendListTransitionType.md) |
| `BlendType` | [`EAlphaBlendOption`](../enums/ue_ue.EAlphaBlendOption.md) |
| `bResetChildOnActivation` | `boolean` |
| `CustomBlendCurve` | [`CurveFloat`](ue_ue.CurveFloat.md) |
| `BlendProfile` | [`BlendProfile`](ue_ue.BlendProfile.md) |

#### Overrides

UE.AnimNode\_Base.constructor

#### Defined in

[ue/ue.d.ts:18037](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18037)

## Properties

### BlendPose

• **BlendPose**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseLink`](ue_ue.PoseLink.md)\>

#### Defined in

[ue/ue.d.ts:18038](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18038)

___

### BlendProfile

• **BlendProfile**: [`BlendProfile`](ue_ue.BlendProfile.md)

#### Defined in

[ue/ue.d.ts:18044](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18044)

___

### BlendTime

• **BlendTime**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:18039](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18039)

___

### BlendType

• **BlendType**: [`EAlphaBlendOption`](../enums/ue_ue.EAlphaBlendOption.md)

#### Defined in

[ue/ue.d.ts:18041](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18041)

___

### CustomBlendCurve

• **CustomBlendCurve**: [`CurveFloat`](ue_ue.CurveFloat.md)

#### Defined in

[ue/ue.d.ts:18043](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18043)

___

### TransitionType

• **TransitionType**: [`EBlendListTransitionType`](../enums/ue_ue.EBlendListTransitionType.md)

#### Defined in

[ue/ue.d.ts:18040](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18040)

___

### \_\_tid\_AnimNode\_BlendListBase\_\_

• `Private` **\_\_tid\_AnimNode\_BlendListBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:18050](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18050)

___

### bResetChildOnActivation

• **bResetChildOnActivation**: `boolean`

#### Defined in

[ue/ue.d.ts:18042](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18042)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticClass](ue_ue.AnimNode_Base.md#staticclass)

#### Defined in

[ue/ue.d.ts:18048](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18048)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)

#### Defined in

[ue/ue.d.ts:18049](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18049)
