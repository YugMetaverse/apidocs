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

#### Defined in

[ue/ue.d.ts:4879](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4879)

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

#### Defined in

[ue/ue.d.ts:4880](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4880)

## Properties

### BlendMode

• **BlendMode**: [`EAlphaBlendOption`](../enums/ue_ue.EAlphaBlendOption.md)

#### Defined in

[ue/ue.d.ts:4887](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4887)

___

### BlendProfile

• **BlendProfile**: [`BlendProfile`](ue_ue.BlendProfile.md)

#### Defined in

[ue/ue.d.ts:4889](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4889)

___

### CrossfadeDuration

• **CrossfadeDuration**: `number`

#### Defined in

[ue/ue.d.ts:4883](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4883)

___

### CustomCurve

• **CustomCurve**: [`CurveFloat`](ue_ue.CurveFloat.md)

#### Defined in

[ue/ue.d.ts:4888](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4888)

___

### EndNotify

• **EndNotify**: `number`

#### Defined in

[ue/ue.d.ts:4885](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4885)

___

### InterruptNotify

• **InterruptNotify**: `number`

#### Defined in

[ue/ue.d.ts:4886](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4886)

___

### LogicType

• **LogicType**: [`ETransitionLogicType`](../enums/ue_ue.ETransitionLogicType.md)

#### Defined in

[ue/ue.d.ts:4890](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4890)

___

### NextState

• **NextState**: `number`

#### Defined in

[ue/ue.d.ts:4882](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4882)

___

### PreviousState

• **PreviousState**: `number`

#### Defined in

[ue/ue.d.ts:4881](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4881)

___

### StartNotify

• **StartNotify**: `number`

#### Defined in

[ue/ue.d.ts:4884](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4884)

___

### StateName

• **StateName**: `string`

#### Inherited from

[AnimationStateBase](ue_ue.AnimationStateBase.md).[StateName](ue_ue.AnimationStateBase.md#statename)

#### Defined in

[ue/ue.d.ts:4868](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4868)

___

### \_\_tid\_AnimationTransitionBetweenStates\_\_

• `Private` **\_\_tid\_AnimationTransitionBetweenStates\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:4896](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4896)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimationStateBase](ue_ue.AnimationStateBase.md).[StaticClass](ue_ue.AnimationStateBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:4894](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4894)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimationStateBase](ue_ue.AnimationStateBase.md).[StaticStruct](ue_ue.AnimationStateBase.md#staticstruct)

#### Defined in

[ue/ue.d.ts:4895](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4895)
