[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BehaviorTreeGraphNode

# Class: BehaviorTreeGraphNode

[ue/ue](../modules/ue_ue.md).BehaviorTreeGraphNode

## Hierarchy

- [`AIGraphNode`](ue_ue.AIGraphNode.md)

  ↳ **`BehaviorTreeGraphNode`**

  ↳↳ [`BehaviorTreeGraphNode_Composite`](ue_ue.BehaviorTreeGraphNode_Composite.md)

  ↳↳ [`BehaviorTreeGraphNode_CompositeDecorator`](ue_ue.BehaviorTreeGraphNode_CompositeDecorator.md)

  ↳↳ [`BehaviorTreeGraphNode_Decorator`](ue_ue.BehaviorTreeGraphNode_Decorator.md)

  ↳↳ [`BehaviorTreeGraphNode_Root`](ue_ue.BehaviorTreeGraphNode_Root.md)

  ↳↳ [`BehaviorTreeGraphNode_Service`](ue_ue.BehaviorTreeGraphNode_Service.md)

  ↳↳ [`BehaviorTreeGraphNode_Task`](ue_ue.BehaviorTreeGraphNode_Task.md)

## Table of contents

### Constructors

- [constructor](ue_ue.BehaviorTreeGraphNode.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.BehaviorTreeGraphNode.md#advancedpindisplay)
- [ClassData](ue_ue.BehaviorTreeGraphNode.md#classdata)
- [CopySubNodeIndex](ue_ue.BehaviorTreeGraphNode.md#copysubnodeindex)
- [Decorators](ue_ue.BehaviorTreeGraphNode.md#decorators)
- [DeprecatedPins](ue_ue.BehaviorTreeGraphNode.md#deprecatedpins)
- [EnabledState](ue_ue.BehaviorTreeGraphNode.md#enabledstate)
- [ErrorMessage](ue_ue.BehaviorTreeGraphNode.md#errormessage)
- [ErrorMsg](ue_ue.BehaviorTreeGraphNode.md#errormsg)
- [ErrorType](ue_ue.BehaviorTreeGraphNode.md#errortype)
- [NodeComment](ue_ue.BehaviorTreeGraphNode.md#nodecomment)
- [NodeGuid](ue_ue.BehaviorTreeGraphNode.md#nodeguid)
- [NodeHeight](ue_ue.BehaviorTreeGraphNode.md#nodeheight)
- [NodeInstance](ue_ue.BehaviorTreeGraphNode.md#nodeinstance)
- [NodePosX](ue_ue.BehaviorTreeGraphNode.md#nodeposx)
- [NodePosY](ue_ue.BehaviorTreeGraphNode.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.BehaviorTreeGraphNode.md#nodeupgrademessage)
- [NodeWidth](ue_ue.BehaviorTreeGraphNode.md#nodewidth)
- [ParentNode](ue_ue.BehaviorTreeGraphNode.md#parentnode)
- [Services](ue_ue.BehaviorTreeGraphNode.md#services)
- [SubNodes](ue_ue.BehaviorTreeGraphNode.md#subnodes)
- [\_\_tid\_AIGraphNode\_\_](ue_ue.BehaviorTreeGraphNode.md#__tid_aigraphnode__)
- [\_\_tid\_BehaviorTreeGraphNode\_\_](ue_ue.BehaviorTreeGraphNode.md#__tid_behaviortreegraphnode__)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.BehaviorTreeGraphNode.md#__tid_edgraphnode__)
- [\_\_tid\_Object\_\_](ue_ue.BehaviorTreeGraphNode.md#__tid_object__)
- [bCanRenameNode](ue_ue.BehaviorTreeGraphNode.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.BehaviorTreeGraphNode.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.BehaviorTreeGraphNode.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.BehaviorTreeGraphNode.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.BehaviorTreeGraphNode.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.BehaviorTreeGraphNode.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.BehaviorTreeGraphNode.md#bhascompilermessage)
- [bInjectedNode](ue_ue.BehaviorTreeGraphNode.md#binjectednode)
- [bIsNodeEnabled](ue_ue.BehaviorTreeGraphNode.md#bisnodeenabled)
- [bIsReadOnly](ue_ue.BehaviorTreeGraphNode.md#bisreadonly)
- [bIsSubNode](ue_ue.BehaviorTreeGraphNode.md#bissubnode)
- [bUserSetEnabledState](ue_ue.BehaviorTreeGraphNode.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.BehaviorTreeGraphNode.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BehaviorTreeGraphNode.md#executeubergraph)
- [GetClass](ue_ue.BehaviorTreeGraphNode.md#getclass)
- [GetName](ue_ue.BehaviorTreeGraphNode.md#getname)
- [GetOuter](ue_ue.BehaviorTreeGraphNode.md#getouter)
- [GetWorld](ue_ue.BehaviorTreeGraphNode.md#getworld)
- [Find](ue_ue.BehaviorTreeGraphNode.md#find)
- [Load](ue_ue.BehaviorTreeGraphNode.md#load)
- [StaticClass](ue_ue.BehaviorTreeGraphNode.md#staticclass)

## Constructors

### constructor

• **new BehaviorTreeGraphNode**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AIGraphNode](ue_ue.AIGraphNode.md).[constructor](ue_ue.AIGraphNode.md#constructor)

#### Defined in

[ue/ue.d.ts:23662](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23662)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[AdvancedPinDisplay](ue_ue.AIGraphNode.md#advancedpindisplay)

#### Defined in

[ue/ue.d.ts:1067](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1067)

___

### ClassData

• **ClassData**: [`GraphNodeClassData`](ue_ue.GraphNodeClassData.md)

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[ClassData](ue_ue.AIGraphNode.md#classdata)

#### Defined in

[ue/ue.d.ts:15117](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15117)

___

### CopySubNodeIndex

• **CopySubNodeIndex**: `number`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[CopySubNodeIndex](ue_ue.AIGraphNode.md#copysubnodeindex)

#### Defined in

[ue/ue.d.ts:15121](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15121)

___

### Decorators

• **Decorators**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BehaviorTreeGraphNode`](ue_ue.BehaviorTreeGraphNode.md)\>

#### Defined in

[ue/ue.d.ts:23663](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23663)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[DeprecatedPins](ue_ue.AIGraphNode.md#deprecatedpins)

#### Defined in

[ue/ue.d.ts:1062](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1062)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[EnabledState](ue_ue.AIGraphNode.md#enabledstate)

#### Defined in

[ue/ue.d.ts:1068](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1068)

___

### ErrorMessage

• **ErrorMessage**: `string`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[ErrorMessage](ue_ue.AIGraphNode.md#errormessage)

#### Defined in

[ue/ue.d.ts:15124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15124)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[ErrorMsg](ue_ue.AIGraphNode.md#errormsg)

#### Defined in

[ue/ue.d.ts:1081](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1081)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[ErrorType](ue_ue.AIGraphNode.md#errortype)

#### Defined in

[ue/ue.d.ts:1080](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1080)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[NodeComment](ue_ue.AIGraphNode.md#nodecomment)

#### Defined in

[ue/ue.d.ts:1079](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1079)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[NodeGuid](ue_ue.AIGraphNode.md#nodeguid)

#### Defined in

[ue/ue.d.ts:1082](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1082)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[NodeHeight](ue_ue.AIGraphNode.md#nodeheight)

#### Defined in

[ue/ue.d.ts:1066](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1066)

___

### NodeInstance

• **NodeInstance**: [`Object`](ue_ue.Object.md)

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[NodeInstance](ue_ue.AIGraphNode.md#nodeinstance)

#### Defined in

[ue/ue.d.ts:15118](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15118)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[NodePosX](ue_ue.AIGraphNode.md#nodeposx)

#### Defined in

[ue/ue.d.ts:1063](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1063)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[NodePosY](ue_ue.AIGraphNode.md#nodeposy)

#### Defined in

[ue/ue.d.ts:1064](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1064)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[NodeUpgradeMessage](ue_ue.AIGraphNode.md#nodeupgrademessage)

#### Defined in

[ue/ue.d.ts:1078](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1078)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[NodeWidth](ue_ue.AIGraphNode.md#nodewidth)

#### Defined in

[ue/ue.d.ts:1065](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1065)

___

### ParentNode

• **ParentNode**: [`AIGraphNode`](ue_ue.AIGraphNode.md)

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[ParentNode](ue_ue.AIGraphNode.md#parentnode)

#### Defined in

[ue/ue.d.ts:15119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15119)

___

### Services

• **Services**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BehaviorTreeGraphNode`](ue_ue.BehaviorTreeGraphNode.md)\>

#### Defined in

[ue/ue.d.ts:23664](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23664)

___

### SubNodes

• **SubNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AIGraphNode`](ue_ue.AIGraphNode.md)\>

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[SubNodes](ue_ue.AIGraphNode.md#subnodes)

#### Defined in

[ue/ue.d.ts:15120](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15120)

___

### \_\_tid\_AIGraphNode\_\_

• **\_\_tid\_AIGraphNode\_\_**: `boolean`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[__tid_AIGraphNode__](ue_ue.AIGraphNode.md#__tid_aigraphnode__)

#### Defined in

[ue/ue.d.ts:15129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15129)

___

### \_\_tid\_BehaviorTreeGraphNode\_\_

• **\_\_tid\_BehaviorTreeGraphNode\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:23670](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23670)

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[__tid_EdGraphNode__](ue_ue.AIGraphNode.md#__tid_edgraphnode__)

#### Defined in

[ue/ue.d.ts:1087](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1087)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[__tid_Object__](ue_ue.AIGraphNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[bCanRenameNode](ue_ue.AIGraphNode.md#bcanrenamenode)

#### Defined in

[ue/ue.d.ts:1077](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1077)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[bCanResizeNode](ue_ue.AIGraphNode.md#bcanresizenode)

#### Defined in

[ue/ue.d.ts:1072](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1072)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[bCommentBubbleMakeVisible](ue_ue.AIGraphNode.md#bcommentbubblemakevisible)

#### Defined in

[ue/ue.d.ts:1076](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1076)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[bCommentBubblePinned](ue_ue.AIGraphNode.md#bcommentbubblepinned)

#### Defined in

[ue/ue.d.ts:1074](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1074)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[bCommentBubbleVisible](ue_ue.AIGraphNode.md#bcommentbubblevisible)

#### Defined in

[ue/ue.d.ts:1075](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1075)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[bDisplayAsDisabled](ue_ue.AIGraphNode.md#bdisplayasdisabled)

#### Defined in

[ue/ue.d.ts:1069](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1069)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[bHasCompilerMessage](ue_ue.AIGraphNode.md#bhascompilermessage)

#### Defined in

[ue/ue.d.ts:1073](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1073)

___

### bInjectedNode

• **bInjectedNode**: `boolean`

#### Defined in

[ue/ue.d.ts:23665](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23665)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[bIsNodeEnabled](ue_ue.AIGraphNode.md#bisnodeenabled)

#### Defined in

[ue/ue.d.ts:1071](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1071)

___

### bIsReadOnly

• **bIsReadOnly**: `boolean`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[bIsReadOnly](ue_ue.AIGraphNode.md#bisreadonly)

#### Defined in

[ue/ue.d.ts:15122](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15122)

___

### bIsSubNode

• **bIsSubNode**: `boolean`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[bIsSubNode](ue_ue.AIGraphNode.md#bissubnode)

#### Defined in

[ue/ue.d.ts:15123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15123)

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[bUserSetEnabledState](ue_ue.AIGraphNode.md#busersetenabledstate)

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

[AIGraphNode](ue_ue.AIGraphNode.md).[CreateDefaultSubobject](ue_ue.AIGraphNode.md#createdefaultsubobject)

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

[AIGraphNode](ue_ue.AIGraphNode.md).[ExecuteUbergraph](ue_ue.AIGraphNode.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[GetClass](ue_ue.AIGraphNode.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[GetName](ue_ue.AIGraphNode.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[GetOuter](ue_ue.AIGraphNode.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AIGraphNode](ue_ue.AIGraphNode.md).[GetWorld](ue_ue.AIGraphNode.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BehaviorTreeGraphNode`](ue_ue.BehaviorTreeGraphNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BehaviorTreeGraphNode`](ue_ue.BehaviorTreeGraphNode.md)

#### Overrides

[AIGraphNode](ue_ue.AIGraphNode.md).[Find](ue_ue.AIGraphNode.md#find)

#### Defined in

[ue/ue.d.ts:23667](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23667)

___

### Load

▸ `Static` **Load**(`InName`): [`BehaviorTreeGraphNode`](ue_ue.BehaviorTreeGraphNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BehaviorTreeGraphNode`](ue_ue.BehaviorTreeGraphNode.md)

#### Overrides

[AIGraphNode](ue_ue.AIGraphNode.md).[Load](ue_ue.AIGraphNode.md#load)

#### Defined in

[ue/ue.d.ts:23668](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23668)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AIGraphNode](ue_ue.AIGraphNode.md).[StaticClass](ue_ue.AIGraphNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:23666](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L23666)
