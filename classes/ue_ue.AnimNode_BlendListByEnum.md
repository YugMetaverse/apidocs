[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_BlendListByEnum

# Class: AnimNode\_BlendListByEnum

[ue/ue](../modules/ue_ue.md).AnimNode_BlendListByEnum

## Hierarchy

- [`AnimNode_BlendListBase`](ue_ue.AnimNode_BlendListBase.md)

  ↳ **`AnimNode_BlendListByEnum`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_BlendListByEnum.md#constructor)

### Properties

- [ActiveEnumValue](ue_ue.AnimNode_BlendListByEnum.md#activeenumvalue)
- [BlendPose](ue_ue.AnimNode_BlendListByEnum.md#blendpose)
- [BlendProfile](ue_ue.AnimNode_BlendListByEnum.md#blendprofile)
- [BlendTime](ue_ue.AnimNode_BlendListByEnum.md#blendtime)
- [BlendType](ue_ue.AnimNode_BlendListByEnum.md#blendtype)
- [CustomBlendCurve](ue_ue.AnimNode_BlendListByEnum.md#customblendcurve)
- [EnumToPoseIndex](ue_ue.AnimNode_BlendListByEnum.md#enumtoposeindex)
- [TransitionType](ue_ue.AnimNode_BlendListByEnum.md#transitiontype)
- [\_\_tid\_AnimNode\_BlendListByEnum\_\_](ue_ue.AnimNode_BlendListByEnum.md#__tid_animnode_blendlistbyenum__)
- [bResetChildOnActivation](ue_ue.AnimNode_BlendListByEnum.md#bresetchildonactivation)

### Methods

- [StaticClass](ue_ue.AnimNode_BlendListByEnum.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_BlendListByEnum.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_BlendListByEnum**()

#### Overrides

[AnimNode_BlendListBase](ue_ue.AnimNode_BlendListBase.md).[constructor](ue_ue.AnimNode_BlendListBase.md#constructor)

• **new AnimNode_BlendListByEnum**(`EnumToPoseIndex`, `ActiveEnumValue`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `EnumToPoseIndex` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `ActiveEnumValue` | `number` |

#### Overrides

[AnimNode_BlendListBase](ue_ue.AnimNode_BlendListBase.md).[constructor](ue_ue.AnimNode_BlendListBase.md#constructor)

## Properties

### ActiveEnumValue

• **ActiveEnumValue**: `number`

___

### BlendPose

• **BlendPose**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseLink`](ue_ue.PoseLink.md)\>

#### Inherited from

[AnimNode_BlendListBase](ue_ue.AnimNode_BlendListBase.md).[BlendPose](ue_ue.AnimNode_BlendListBase.md#blendpose)

___

### BlendProfile

• **BlendProfile**: [`BlendProfile`](ue_ue.BlendProfile.md)

#### Inherited from

[AnimNode_BlendListBase](ue_ue.AnimNode_BlendListBase.md).[BlendProfile](ue_ue.AnimNode_BlendListBase.md#blendprofile)

___

### BlendTime

• **BlendTime**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[AnimNode_BlendListBase](ue_ue.AnimNode_BlendListBase.md).[BlendTime](ue_ue.AnimNode_BlendListBase.md#blendtime)

___

### BlendType

• **BlendType**: [`EAlphaBlendOption`](../enums/ue_ue.EAlphaBlendOption.md)

#### Inherited from

[AnimNode_BlendListBase](ue_ue.AnimNode_BlendListBase.md).[BlendType](ue_ue.AnimNode_BlendListBase.md#blendtype)

___

### CustomBlendCurve

• **CustomBlendCurve**: [`CurveFloat`](ue_ue.CurveFloat.md)

#### Inherited from

[AnimNode_BlendListBase](ue_ue.AnimNode_BlendListBase.md).[CustomBlendCurve](ue_ue.AnimNode_BlendListBase.md#customblendcurve)

___

### EnumToPoseIndex

• **EnumToPoseIndex**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### TransitionType

• **TransitionType**: [`EBlendListTransitionType`](../enums/ue_ue.EBlendListTransitionType.md)

#### Inherited from

[AnimNode_BlendListBase](ue_ue.AnimNode_BlendListBase.md).[TransitionType](ue_ue.AnimNode_BlendListBase.md#transitiontype)

___

### \_\_tid\_AnimNode\_BlendListByEnum\_\_

• `Private` **\_\_tid\_AnimNode\_BlendListByEnum\_\_**: `boolean`

___

### bResetChildOnActivation

• **bResetChildOnActivation**: `boolean`

#### Inherited from

[AnimNode_BlendListBase](ue_ue.AnimNode_BlendListBase.md).[bResetChildOnActivation](ue_ue.AnimNode_BlendListBase.md#bresetchildonactivation)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_BlendListBase](ue_ue.AnimNode_BlendListBase.md).[StaticClass](ue_ue.AnimNode_BlendListBase.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_BlendListBase](ue_ue.AnimNode_BlendListBase.md).[StaticStruct](ue_ue.AnimNode_BlendListBase.md#staticstruct)
