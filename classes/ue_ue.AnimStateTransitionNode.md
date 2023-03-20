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

#### Defined in

[ue/ue.d.ts:20506](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20506)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[AdvancedPinDisplay](ue_ue.AnimStateNodeBase.md#advancedpindisplay)

#### Defined in

[ue/ue.d.ts:1067](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1067)

___

### Bidirectional

• **Bidirectional**: `boolean`

#### Defined in

[ue/ue.d.ts:20520](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20520)

___

### BlendMode

• **BlendMode**: [`EAlphaBlendOption`](../enums/ue_ue.EAlphaBlendOption.md)

#### Defined in

[ue/ue.d.ts:20512](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20512)

___

### BlendProfile

• **BlendProfile**: [`BlendProfile`](ue_ue.BlendProfile.md)

#### Defined in

[ue/ue.d.ts:20514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20514)

___

### BoundGraph

• **BoundGraph**: [`EdGraph`](ue_ue.EdGraph.md)

#### Defined in

[ue/ue.d.ts:20507](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20507)

___

### CrossfadeDuration

• **CrossfadeDuration**: `number`

#### Defined in

[ue/ue.d.ts:20510](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20510)

___

### CrossfadeMode

• **CrossfadeMode**: [`ETransitionBlendMode`](../enums/ue_ue.ETransitionBlendMode.md)

#### Defined in

[ue/ue.d.ts:20511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20511)

___

### CustomBlendCurve

• **CustomBlendCurve**: [`CurveFloat`](ue_ue.CurveFloat.md)

#### Defined in

[ue/ue.d.ts:20513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20513)

___

### CustomTransitionGraph

• **CustomTransitionGraph**: [`EdGraph`](ue_ue.EdGraph.md)

#### Defined in

[ue/ue.d.ts:20508](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20508)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[DeprecatedPins](ue_ue.AnimStateNodeBase.md#deprecatedpins)

#### Defined in

[ue/ue.d.ts:1062](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1062)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[EnabledState](ue_ue.AnimStateNodeBase.md#enabledstate)

#### Defined in

[ue/ue.d.ts:1068](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1068)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[ErrorMsg](ue_ue.AnimStateNodeBase.md#errormsg)

#### Defined in

[ue/ue.d.ts:1081](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1081)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[ErrorType](ue_ue.AnimStateNodeBase.md#errortype)

#### Defined in

[ue/ue.d.ts:1080](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1080)

___

### LogicType

• **LogicType**: [`ETransitionLogicType`](../enums/ue_ue.ETransitionLogicType.md)

#### Defined in

[ue/ue.d.ts:20516](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20516)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodeComment](ue_ue.AnimStateNodeBase.md#nodecomment)

#### Defined in

[ue/ue.d.ts:1079](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1079)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodeGuid](ue_ue.AnimStateNodeBase.md#nodeguid)

#### Defined in

[ue/ue.d.ts:1082](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1082)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodeHeight](ue_ue.AnimStateNodeBase.md#nodeheight)

#### Defined in

[ue/ue.d.ts:1066](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1066)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodePosX](ue_ue.AnimStateNodeBase.md#nodeposx)

#### Defined in

[ue/ue.d.ts:1063](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1063)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodePosY](ue_ue.AnimStateNodeBase.md#nodeposy)

#### Defined in

[ue/ue.d.ts:1064](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1064)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodeUpgradeMessage](ue_ue.AnimStateNodeBase.md#nodeupgrademessage)

#### Defined in

[ue/ue.d.ts:1078](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1078)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodeWidth](ue_ue.AnimStateNodeBase.md#nodewidth)

#### Defined in

[ue/ue.d.ts:1065](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1065)

___

### PriorityOrder

• **PriorityOrder**: `number`

#### Defined in

[ue/ue.d.ts:20509](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20509)

___

### SharedColor

• **SharedColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:20525](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20525)

___

### SharedCrossfadeGuid

• **SharedCrossfadeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:20527](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20527)

___

### SharedCrossfadeIdx

• **SharedCrossfadeIdx**: `number`

#### Defined in

[ue/ue.d.ts:20528](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20528)

___

### SharedCrossfadeName

• **SharedCrossfadeName**: `string`

#### Defined in

[ue/ue.d.ts:20526](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20526)

___

### SharedRulesGuid

• **SharedRulesGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:20524](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20524)

___

### SharedRulesName

• **SharedRulesName**: `string`

#### Defined in

[ue/ue.d.ts:20523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20523)

___

### TransitionEnd

• **TransitionEnd**: [`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)

#### Defined in

[ue/ue.d.ts:20518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20518)

___

### TransitionInterrupt

• **TransitionInterrupt**: [`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)

#### Defined in

[ue/ue.d.ts:20519](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20519)

___

### TransitionStart

• **TransitionStart**: [`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)

#### Defined in

[ue/ue.d.ts:20517](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20517)

___

### \_\_tid\_AnimStateNodeBase\_\_

• **\_\_tid\_AnimStateNodeBase\_\_**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[__tid_AnimStateNodeBase__](ue_ue.AnimStateNodeBase.md#__tid_animstatenodebase__)

#### Defined in

[ue/ue.d.ts:20466](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20466)

___

### \_\_tid\_AnimStateTransitionNode\_\_

• **\_\_tid\_AnimStateTransitionNode\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:20533](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20533)

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[__tid_EdGraphNode__](ue_ue.AnimStateNodeBase.md#__tid_edgraphnode__)

#### Defined in

[ue/ue.d.ts:1087](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1087)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[__tid_Object__](ue_ue.AnimStateNodeBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAutomaticRuleBasedOnSequencePlayerInState

• **bAutomaticRuleBasedOnSequencePlayerInState**: `boolean`

#### Defined in

[ue/ue.d.ts:20515](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20515)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bCanRenameNode](ue_ue.AnimStateNodeBase.md#bcanrenamenode)

#### Defined in

[ue/ue.d.ts:1077](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1077)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bCanResizeNode](ue_ue.AnimStateNodeBase.md#bcanresizenode)

#### Defined in

[ue/ue.d.ts:1072](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1072)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bCommentBubbleMakeVisible](ue_ue.AnimStateNodeBase.md#bcommentbubblemakevisible)

#### Defined in

[ue/ue.d.ts:1076](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1076)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bCommentBubblePinned](ue_ue.AnimStateNodeBase.md#bcommentbubblepinned)

#### Defined in

[ue/ue.d.ts:1074](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1074)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bCommentBubbleVisible](ue_ue.AnimStateNodeBase.md#bcommentbubblevisible)

#### Defined in

[ue/ue.d.ts:1075](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1075)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bDisplayAsDisabled](ue_ue.AnimStateNodeBase.md#bdisplayasdisabled)

#### Defined in

[ue/ue.d.ts:1069](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1069)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bHasCompilerMessage](ue_ue.AnimStateNodeBase.md#bhascompilermessage)

#### Defined in

[ue/ue.d.ts:1073](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1073)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bIsNodeEnabled](ue_ue.AnimStateNodeBase.md#bisnodeenabled)

#### Defined in

[ue/ue.d.ts:1071](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1071)

___

### bSharedCrossfade

• **bSharedCrossfade**: `boolean`

#### Defined in

[ue/ue.d.ts:20522](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20522)

___

### bSharedRules

• **bSharedRules**: `boolean`

#### Defined in

[ue/ue.d.ts:20521](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20521)

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bUserSetEnabledState](ue_ue.AnimStateNodeBase.md#busersetenabledstate)

#### Defined in

[ue/ue.d.ts:1070](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1070)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[GetClass](ue_ue.AnimStateNodeBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[GetName](ue_ue.AnimStateNodeBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[GetOuter](ue_ue.AnimStateNodeBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[GetWorld](ue_ue.AnimStateNodeBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:20530](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20530)

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

#### Defined in

[ue/ue.d.ts:20531](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20531)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[StaticClass](ue_ue.AnimStateNodeBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:20529](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20529)
