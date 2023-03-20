[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimStateTransitionNode

# Class: AnimStateTransitionNode

[ue/ue](../modules/ue_ue.md).AnimStateTransitionNode

## Hierarchy

- [`AnimStateNodeBase`](ue_ue.AnimStateNodeBase.md)

  ↳ **`AnimStateTransitionNode`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimStateTransitionNode.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.AnimStateTransitionNode.md#advancedpindisplay)
- [Bidirectional](ue_ue.AnimStateTransitionNode.md#bidirectional)
- [BlendMode](ue_ue.AnimStateTransitionNode.md#blendmode)
- [BlendProfile](ue_ue.AnimStateTransitionNode.md#blendprofile)
- [BoundGraph](ue_ue.AnimStateTransitionNode.md#boundgraph)
- [CrossfadeDuration](ue_ue.AnimStateTransitionNode.md#crossfadeduration)
- [CrossfadeMode](ue_ue.AnimStateTransitionNode.md#crossfademode)
- [CustomBlendCurve](ue_ue.AnimStateTransitionNode.md#customblendcurve)
- [CustomTransitionGraph](ue_ue.AnimStateTransitionNode.md#customtransitiongraph)
- [DeprecatedPins](ue_ue.AnimStateTransitionNode.md#deprecatedpins)
- [EnabledState](ue_ue.AnimStateTransitionNode.md#enabledstate)
- [ErrorMsg](ue_ue.AnimStateTransitionNode.md#errormsg)
- [ErrorType](ue_ue.AnimStateTransitionNode.md#errortype)
- [LogicType](ue_ue.AnimStateTransitionNode.md#logictype)
- [NodeComment](ue_ue.AnimStateTransitionNode.md#nodecomment)
- [NodeGuid](ue_ue.AnimStateTransitionNode.md#nodeguid)
- [NodeHeight](ue_ue.AnimStateTransitionNode.md#nodeheight)
- [NodePosX](ue_ue.AnimStateTransitionNode.md#nodeposx)
- [NodePosY](ue_ue.AnimStateTransitionNode.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.AnimStateTransitionNode.md#nodeupgrademessage)
- [NodeWidth](ue_ue.AnimStateTransitionNode.md#nodewidth)
- [PriorityOrder](ue_ue.AnimStateTransitionNode.md#priorityorder)
- [SharedColor](ue_ue.AnimStateTransitionNode.md#sharedcolor)
- [SharedCrossfadeGuid](ue_ue.AnimStateTransitionNode.md#sharedcrossfadeguid)
- [SharedCrossfadeIdx](ue_ue.AnimStateTransitionNode.md#sharedcrossfadeidx)
- [SharedCrossfadeName](ue_ue.AnimStateTransitionNode.md#sharedcrossfadename)
- [SharedRulesGuid](ue_ue.AnimStateTransitionNode.md#sharedrulesguid)
- [SharedRulesName](ue_ue.AnimStateTransitionNode.md#sharedrulesname)
- [TransitionEnd](ue_ue.AnimStateTransitionNode.md#transitionend)
- [TransitionInterrupt](ue_ue.AnimStateTransitionNode.md#transitioninterrupt)
- [TransitionStart](ue_ue.AnimStateTransitionNode.md#transitionstart)
- [\_\_tid\_AnimStateNodeBase\_\_](ue_ue.AnimStateTransitionNode.md#__tid_animstatenodebase__)
- [\_\_tid\_AnimStateTransitionNode\_\_](ue_ue.AnimStateTransitionNode.md#__tid_animstatetransitionnode__)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.AnimStateTransitionNode.md#__tid_edgraphnode__)
- [\_\_tid\_Object\_\_](ue_ue.AnimStateTransitionNode.md#__tid_object__)
- [bAutomaticRuleBasedOnSequencePlayerInState](ue_ue.AnimStateTransitionNode.md#bautomaticrulebasedonsequenceplayerinstate)
- [bCanRenameNode](ue_ue.AnimStateTransitionNode.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.AnimStateTransitionNode.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.AnimStateTransitionNode.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.AnimStateTransitionNode.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.AnimStateTransitionNode.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.AnimStateTransitionNode.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.AnimStateTransitionNode.md#bhascompilermessage)
- [bIsNodeEnabled](ue_ue.AnimStateTransitionNode.md#bisnodeenabled)
- [bSharedCrossfade](ue_ue.AnimStateTransitionNode.md#bsharedcrossfade)
- [bSharedRules](ue_ue.AnimStateTransitionNode.md#bsharedrules)
- [bUserSetEnabledState](ue_ue.AnimStateTransitionNode.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimStateTransitionNode.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimStateTransitionNode.md#executeubergraph)
- [GetClass](ue_ue.AnimStateTransitionNode.md#getclass)
- [GetName](ue_ue.AnimStateTransitionNode.md#getname)
- [GetOuter](ue_ue.AnimStateTransitionNode.md#getouter)
- [GetWorld](ue_ue.AnimStateTransitionNode.md#getworld)
- [Find](ue_ue.AnimStateTransitionNode.md#find)
- [Load](ue_ue.AnimStateTransitionNode.md#load)
- [StaticClass](ue_ue.AnimStateTransitionNode.md#staticclass)

## Constructors

### constructor

• **new AnimStateTransitionNode**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[constructor](ue_ue.AnimStateNodeBase.md#constructor)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[AdvancedPinDisplay](ue_ue.AnimStateNodeBase.md#advancedpindisplay)

___

### Bidirectional

• **Bidirectional**: `boolean`

___

### BlendMode

• **BlendMode**: [`EAlphaBlendOption`](../enums/ue_ue.EAlphaBlendOption.md)

___

### BlendProfile

• **BlendProfile**: [`BlendProfile`](ue_ue.BlendProfile.md)

___

### BoundGraph

• **BoundGraph**: [`EdGraph`](ue_ue.EdGraph.md)

___

### CrossfadeDuration

• **CrossfadeDuration**: `number`

___

### CrossfadeMode

• **CrossfadeMode**: [`ETransitionBlendMode`](../enums/ue_ue.ETransitionBlendMode.md)

___

### CustomBlendCurve

• **CustomBlendCurve**: [`CurveFloat`](ue_ue.CurveFloat.md)

___

### CustomTransitionGraph

• **CustomTransitionGraph**: [`EdGraph`](ue_ue.EdGraph.md)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[DeprecatedPins](ue_ue.AnimStateNodeBase.md#deprecatedpins)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[EnabledState](ue_ue.AnimStateNodeBase.md#enabledstate)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[ErrorMsg](ue_ue.AnimStateNodeBase.md#errormsg)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[ErrorType](ue_ue.AnimStateNodeBase.md#errortype)

___

### LogicType

• **LogicType**: [`ETransitionLogicType`](../enums/ue_ue.ETransitionLogicType.md)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodeComment](ue_ue.AnimStateNodeBase.md#nodecomment)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodeGuid](ue_ue.AnimStateNodeBase.md#nodeguid)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodeHeight](ue_ue.AnimStateNodeBase.md#nodeheight)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodePosX](ue_ue.AnimStateNodeBase.md#nodeposx)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodePosY](ue_ue.AnimStateNodeBase.md#nodeposy)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodeUpgradeMessage](ue_ue.AnimStateNodeBase.md#nodeupgrademessage)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodeWidth](ue_ue.AnimStateNodeBase.md#nodewidth)

___

### PriorityOrder

• **PriorityOrder**: `number`

___

### SharedColor

• **SharedColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### SharedCrossfadeGuid

• **SharedCrossfadeGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### SharedCrossfadeIdx

• **SharedCrossfadeIdx**: `number`

___

### SharedCrossfadeName

• **SharedCrossfadeName**: `string`

___

### SharedRulesGuid

• **SharedRulesGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### SharedRulesName

• **SharedRulesName**: `string`

___

### TransitionEnd

• **TransitionEnd**: [`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)

___

### TransitionInterrupt

• **TransitionInterrupt**: [`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)

___

### TransitionStart

• **TransitionStart**: [`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)

___

### \_\_tid\_AnimStateNodeBase\_\_

• **\_\_tid\_AnimStateNodeBase\_\_**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[__tid_AnimStateNodeBase__](ue_ue.AnimStateNodeBase.md#__tid_animstatenodebase__)

___

### \_\_tid\_AnimStateTransitionNode\_\_

• **\_\_tid\_AnimStateTransitionNode\_\_**: `boolean`

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[__tid_EdGraphNode__](ue_ue.AnimStateNodeBase.md#__tid_edgraphnode__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[__tid_Object__](ue_ue.AnimStateNodeBase.md#__tid_object__)

___

### bAutomaticRuleBasedOnSequencePlayerInState

• **bAutomaticRuleBasedOnSequencePlayerInState**: `boolean`

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bCanRenameNode](ue_ue.AnimStateNodeBase.md#bcanrenamenode)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bCanResizeNode](ue_ue.AnimStateNodeBase.md#bcanresizenode)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bCommentBubbleMakeVisible](ue_ue.AnimStateNodeBase.md#bcommentbubblemakevisible)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bCommentBubblePinned](ue_ue.AnimStateNodeBase.md#bcommentbubblepinned)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bCommentBubbleVisible](ue_ue.AnimStateNodeBase.md#bcommentbubblevisible)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bDisplayAsDisabled](ue_ue.AnimStateNodeBase.md#bdisplayasdisabled)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bHasCompilerMessage](ue_ue.AnimStateNodeBase.md#bhascompilermessage)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bIsNodeEnabled](ue_ue.AnimStateNodeBase.md#bisnodeenabled)

___

### bSharedCrossfade

• **bSharedCrossfade**: `boolean`

___

### bSharedRules

• **bSharedRules**: `boolean`

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bUserSetEnabledState](ue_ue.AnimStateNodeBase.md#busersetenabledstate)

## Methods

### CreateDefaultSubobject

▸ **CreateDefaultSubobject**(`p0`, `p1`, `p2`, `p3`, `p4`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `string` |
| `p1` | [`Class`](ue_ue.Class.md) |
| `p2` | [`Class`](ue_ue.Class.md) |
| `p3` | `boolean` |
| `p4` | `boolean` |

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[CreateDefaultSubobject](ue_ue.AnimStateNodeBase.md#createdefaultsubobject)

___

### ExecuteUbergraph

▸ **ExecuteUbergraph**(`EntryPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryPoint` | `number` |

#### Returns

`void`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[ExecuteUbergraph](ue_ue.AnimStateNodeBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[GetClass](ue_ue.AnimStateNodeBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[GetName](ue_ue.AnimStateNodeBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[GetOuter](ue_ue.AnimStateNodeBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[GetWorld](ue_ue.AnimStateNodeBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimStateTransitionNode`](ue_ue.AnimStateTransitionNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimStateTransitionNode`](ue_ue.AnimStateTransitionNode.md)

#### Overrides

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[Find](ue_ue.AnimStateNodeBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimStateTransitionNode`](ue_ue.AnimStateTransitionNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimStateTransitionNode`](ue_ue.AnimStateTransitionNode.md)

#### Overrides

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[Load](ue_ue.AnimStateNodeBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[StaticClass](ue_ue.AnimStateNodeBase.md#staticclass)
