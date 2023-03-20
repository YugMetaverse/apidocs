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

## Properties

### BlendPose

• **BlendPose**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseLink`](ue_ue.PoseLink.md)\>

___

### BlendProfile

• **BlendProfile**: [`BlendProfile`](ue_ue.BlendProfile.md)

___

### BlendTime

• **BlendTime**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### BlendType

• **BlendType**: [`EAlphaBlendOption`](../enums/ue_ue.EAlphaBlendOption.md)

___

### CustomBlendCurve

• **CustomBlendCurve**: [`CurveFloat`](ue_ue.CurveFloat.md)

___

### TransitionType

• **TransitionType**: [`EBlendListTransitionType`](../enums/ue_ue.EBlendListTransitionType.md)

___

### \_\_tid\_AnimNode\_BlendListBase\_\_

• `Private` **\_\_tid\_AnimNode\_BlendListBase\_\_**: `boolean`

___

### bResetChildOnActivation

• **bResetChildOnActivation**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticClass](ue_ue.AnimNode_Base.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)
