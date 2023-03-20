[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimationTransitionBetweenStates

# Class: AnimationTransitionBetweenStates

[ue/ue](../modules/ue_ue.md).AnimationTransitionBetweenStates

## Hierarchy

- [`AnimationStateBase`](ue_ue.AnimationStateBase.md)

  ↳ **`AnimationTransitionBetweenStates`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimationTransitionBetweenStates.md#constructor)

### Properties

- [BlendMode](ue_ue.AnimationTransitionBetweenStates.md#blendmode)
- [BlendProfile](ue_ue.AnimationTransitionBetweenStates.md#blendprofile)
- [CrossfadeDuration](ue_ue.AnimationTransitionBetweenStates.md#crossfadeduration)
- [CustomCurve](ue_ue.AnimationTransitionBetweenStates.md#customcurve)
- [EndNotify](ue_ue.AnimationTransitionBetweenStates.md#endnotify)
- [InterruptNotify](ue_ue.AnimationTransitionBetweenStates.md#interruptnotify)
- [LogicType](ue_ue.AnimationTransitionBetweenStates.md#logictype)
- [NextState](ue_ue.AnimationTransitionBetweenStates.md#nextstate)
- [PreviousState](ue_ue.AnimationTransitionBetweenStates.md#previousstate)
- [StartNotify](ue_ue.AnimationTransitionBetweenStates.md#startnotify)
- [StateName](ue_ue.AnimationTransitionBetweenStates.md#statename)
- [\_\_tid\_AnimationTransitionBetweenStates\_\_](ue_ue.AnimationTransitionBetweenStates.md#__tid_animationtransitionbetweenstates__)

### Methods

- [StaticClass](ue_ue.AnimationTransitionBetweenStates.md#staticclass)
- [StaticStruct](ue_ue.AnimationTransitionBetweenStates.md#staticstruct)

## Constructors

### constructor

• **new AnimationTransitionBetweenStates**()

#### Overrides

[AnimationStateBase](ue_ue.AnimationStateBase.md).[constructor](ue_ue.AnimationStateBase.md#constructor)

• **new AnimationTransitionBetweenStates**(`PreviousState`, `NextState`, `CrossfadeDuration`, `StartNotify`, `EndNotify`, `InterruptNotify`, `BlendMode`, `CustomCurve`, `BlendProfile`, `LogicType`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PreviousState` | `number` |
| `NextState` | `number` |
| `CrossfadeDuration` | `number` |
| `StartNotify` | `number` |
| `EndNotify` | `number` |
| `InterruptNotify` | `number` |
| `BlendMode` | [`EAlphaBlendOption`](../enums/ue_ue.EAlphaBlendOption.md) |
| `CustomCurve` | [`CurveFloat`](ue_ue.CurveFloat.md) |
| `BlendProfile` | [`BlendProfile`](ue_ue.BlendProfile.md) |
| `LogicType` | [`ETransitionLogicType`](../enums/ue_ue.ETransitionLogicType.md) |

#### Overrides

[AnimationStateBase](ue_ue.AnimationStateBase.md).[constructor](ue_ue.AnimationStateBase.md#constructor)

## Properties

### BlendMode

• **BlendMode**: [`EAlphaBlendOption`](../enums/ue_ue.EAlphaBlendOption.md)

___

### BlendProfile

• **BlendProfile**: [`BlendProfile`](ue_ue.BlendProfile.md)

___

### CrossfadeDuration

• **CrossfadeDuration**: `number`

___

### CustomCurve

• **CustomCurve**: [`CurveFloat`](ue_ue.CurveFloat.md)

___

### EndNotify

• **EndNotify**: `number`

___

### InterruptNotify

• **InterruptNotify**: `number`

___

### LogicType

• **LogicType**: [`ETransitionLogicType`](../enums/ue_ue.ETransitionLogicType.md)

___

### NextState

• **NextState**: `number`

___

### PreviousState

• **PreviousState**: `number`

___

### StartNotify

• **StartNotify**: `number`

___

### StateName

• **StateName**: `string`

#### Inherited from

[AnimationStateBase](ue_ue.AnimationStateBase.md).[StateName](ue_ue.AnimationStateBase.md#statename)

___

### \_\_tid\_AnimationTransitionBetweenStates\_\_

• `Private` **\_\_tid\_AnimationTransitionBetweenStates\_\_**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimationStateBase](ue_ue.AnimationStateBase.md).[StaticClass](ue_ue.AnimationStateBase.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimationStateBase](ue_ue.AnimationStateBase.md).[StaticStruct](ue_ue.AnimationStateBase.md#staticstruct)
