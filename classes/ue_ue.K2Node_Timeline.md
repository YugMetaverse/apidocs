[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / K2Node\_Timeline

# Class: K2Node\_Timeline

[ue/ue](../modules/ue_ue.md).K2Node_Timeline

## Hierarchy

- [`K2Node`](ue_ue.K2Node.md)

  ↳ **`K2Node_Timeline`**

## Table of contents

### Constructors

- [constructor](ue_ue.K2Node_Timeline.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.K2Node_Timeline.md#advancedpindisplay)
- [DeprecatedPins](ue_ue.K2Node_Timeline.md#deprecatedpins)
- [EnabledState](ue_ue.K2Node_Timeline.md#enabledstate)
- [ErrorMsg](ue_ue.K2Node_Timeline.md#errormsg)
- [ErrorType](ue_ue.K2Node_Timeline.md#errortype)
- [NodeComment](ue_ue.K2Node_Timeline.md#nodecomment)
- [NodeGuid](ue_ue.K2Node_Timeline.md#nodeguid)
- [NodeHeight](ue_ue.K2Node_Timeline.md#nodeheight)
- [NodePosX](ue_ue.K2Node_Timeline.md#nodeposx)
- [NodePosY](ue_ue.K2Node_Timeline.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.K2Node_Timeline.md#nodeupgrademessage)
- [NodeWidth](ue_ue.K2Node_Timeline.md#nodewidth)
- [TimelineGuid](ue_ue.K2Node_Timeline.md#timelineguid)
- [TimelineName](ue_ue.K2Node_Timeline.md#timelinename)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.K2Node_Timeline.md#__tid_edgraphnode__)
- [\_\_tid\_K2Node\_Timeline\_\_](ue_ue.K2Node_Timeline.md#__tid_k2node_timeline__)
- [\_\_tid\_K2Node\_\_](ue_ue.K2Node_Timeline.md#__tid_k2node__)
- [\_\_tid\_Object\_\_](ue_ue.K2Node_Timeline.md#__tid_object__)
- [bAutoPlay](ue_ue.K2Node_Timeline.md#bautoplay)
- [bCanRenameNode](ue_ue.K2Node_Timeline.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.K2Node_Timeline.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.K2Node_Timeline.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.K2Node_Timeline.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.K2Node_Timeline.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.K2Node_Timeline.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.K2Node_Timeline.md#bhascompilermessage)
- [bIgnoreTimeDilation](ue_ue.K2Node_Timeline.md#bignoretimedilation)
- [bIsNodeEnabled](ue_ue.K2Node_Timeline.md#bisnodeenabled)
- [bLoop](ue_ue.K2Node_Timeline.md#bloop)
- [bReplicated](ue_ue.K2Node_Timeline.md#breplicated)
- [bUserSetEnabledState](ue_ue.K2Node_Timeline.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.K2Node_Timeline.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.K2Node_Timeline.md#executeubergraph)
- [GetClass](ue_ue.K2Node_Timeline.md#getclass)
- [GetName](ue_ue.K2Node_Timeline.md#getname)
- [GetOuter](ue_ue.K2Node_Timeline.md#getouter)
- [GetWorld](ue_ue.K2Node_Timeline.md#getworld)
- [Find](ue_ue.K2Node_Timeline.md#find)
- [Load](ue_ue.K2Node_Timeline.md#load)
- [StaticClass](ue_ue.K2Node_Timeline.md#staticclass)

## Constructors

### constructor

• **new K2Node_Timeline**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[K2Node](ue_ue.K2Node.md).[constructor](ue_ue.K2Node.md#constructor)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[K2Node](ue_ue.K2Node.md).[AdvancedPinDisplay](ue_ue.K2Node.md#advancedpindisplay)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[K2Node](ue_ue.K2Node.md).[DeprecatedPins](ue_ue.K2Node.md#deprecatedpins)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[K2Node](ue_ue.K2Node.md).[EnabledState](ue_ue.K2Node.md#enabledstate)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[ErrorMsg](ue_ue.K2Node.md#errormsg)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[ErrorType](ue_ue.K2Node.md#errortype)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[NodeComment](ue_ue.K2Node.md#nodecomment)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[K2Node](ue_ue.K2Node.md).[NodeGuid](ue_ue.K2Node.md#nodeguid)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[NodeHeight](ue_ue.K2Node.md#nodeheight)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[NodePosX](ue_ue.K2Node.md#nodeposx)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[NodePosY](ue_ue.K2Node.md#nodeposy)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[NodeUpgradeMessage](ue_ue.K2Node.md#nodeupgrademessage)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[NodeWidth](ue_ue.K2Node.md#nodewidth)

___

### TimelineGuid

• **TimelineGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### TimelineName

• **TimelineName**: `string`

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[__tid_EdGraphNode__](ue_ue.K2Node.md#__tid_edgraphnode__)

___

### \_\_tid\_K2Node\_Timeline\_\_

• **\_\_tid\_K2Node\_Timeline\_\_**: `boolean`

___

### \_\_tid\_K2Node\_\_

• **\_\_tid\_K2Node\_\_**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[__tid_K2Node__](ue_ue.K2Node.md#__tid_k2node__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[__tid_Object__](ue_ue.K2Node.md#__tid_object__)

___

### bAutoPlay

• **bAutoPlay**: `boolean`

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bCanRenameNode](ue_ue.K2Node.md#bcanrenamenode)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bCanResizeNode](ue_ue.K2Node.md#bcanresizenode)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bCommentBubbleMakeVisible](ue_ue.K2Node.md#bcommentbubblemakevisible)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bCommentBubblePinned](ue_ue.K2Node.md#bcommentbubblepinned)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bCommentBubbleVisible](ue_ue.K2Node.md#bcommentbubblevisible)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bDisplayAsDisabled](ue_ue.K2Node.md#bdisplayasdisabled)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bHasCompilerMessage](ue_ue.K2Node.md#bhascompilermessage)

___

### bIgnoreTimeDilation

• **bIgnoreTimeDilation**: `boolean`

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bIsNodeEnabled](ue_ue.K2Node.md#bisnodeenabled)

___

### bLoop

• **bLoop**: `boolean`

___

### bReplicated

• **bReplicated**: `boolean`

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bUserSetEnabledState](ue_ue.K2Node.md#busersetenabledstate)

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

[K2Node](ue_ue.K2Node.md).[CreateDefaultSubobject](ue_ue.K2Node.md#createdefaultsubobject)

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

[K2Node](ue_ue.K2Node.md).[ExecuteUbergraph](ue_ue.K2Node.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[K2Node](ue_ue.K2Node.md).[GetClass](ue_ue.K2Node.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[GetName](ue_ue.K2Node.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[K2Node](ue_ue.K2Node.md).[GetOuter](ue_ue.K2Node.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[K2Node](ue_ue.K2Node.md).[GetWorld](ue_ue.K2Node.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`K2Node_Timeline`](ue_ue.K2Node_Timeline.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`K2Node_Timeline`](ue_ue.K2Node_Timeline.md)

#### Overrides

[K2Node](ue_ue.K2Node.md).[Find](ue_ue.K2Node.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`K2Node_Timeline`](ue_ue.K2Node_Timeline.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`K2Node_Timeline`](ue_ue.K2Node_Timeline.md)

#### Overrides

[K2Node](ue_ue.K2Node.md).[Load](ue_ue.K2Node.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[K2Node](ue_ue.K2Node.md).[StaticClass](ue_ue.K2Node.md#staticclass)
