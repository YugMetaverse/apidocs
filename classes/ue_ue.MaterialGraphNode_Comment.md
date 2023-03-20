[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialGraphNode\_Comment

# Class: MaterialGraphNode\_Comment

[ue/ue](../modules/ue_ue.md).MaterialGraphNode_Comment

## Hierarchy

- [`EdGraphNode_Comment`](ue_ue.EdGraphNode_Comment.md)

  ↳ **`MaterialGraphNode_Comment`**

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialGraphNode_Comment.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.MaterialGraphNode_Comment.md#advancedpindisplay)
- [CommentColor](ue_ue.MaterialGraphNode_Comment.md#commentcolor)
- [CommentDepth](ue_ue.MaterialGraphNode_Comment.md#commentdepth)
- [DeprecatedPins](ue_ue.MaterialGraphNode_Comment.md#deprecatedpins)
- [EnabledState](ue_ue.MaterialGraphNode_Comment.md#enabledstate)
- [ErrorMsg](ue_ue.MaterialGraphNode_Comment.md#errormsg)
- [ErrorType](ue_ue.MaterialGraphNode_Comment.md#errortype)
- [FontSize](ue_ue.MaterialGraphNode_Comment.md#fontsize)
- [MaterialExpressionComment](ue_ue.MaterialGraphNode_Comment.md#materialexpressioncomment)
- [MoveMode](ue_ue.MaterialGraphNode_Comment.md#movemode)
- [NodeComment](ue_ue.MaterialGraphNode_Comment.md#nodecomment)
- [NodeGuid](ue_ue.MaterialGraphNode_Comment.md#nodeguid)
- [NodeHeight](ue_ue.MaterialGraphNode_Comment.md#nodeheight)
- [NodePosX](ue_ue.MaterialGraphNode_Comment.md#nodeposx)
- [NodePosY](ue_ue.MaterialGraphNode_Comment.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.MaterialGraphNode_Comment.md#nodeupgrademessage)
- [NodeWidth](ue_ue.MaterialGraphNode_Comment.md#nodewidth)
- [\_\_tid\_EdGraphNode\_Comment\_\_](ue_ue.MaterialGraphNode_Comment.md#__tid_edgraphnode_comment__)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.MaterialGraphNode_Comment.md#__tid_edgraphnode__)
- [\_\_tid\_MaterialGraphNode\_Comment\_\_](ue_ue.MaterialGraphNode_Comment.md#__tid_materialgraphnode_comment__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialGraphNode_Comment.md#__tid_object__)
- [bCanRenameNode](ue_ue.MaterialGraphNode_Comment.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.MaterialGraphNode_Comment.md#bcanresizenode)
- [bColorCommentBubble](ue_ue.MaterialGraphNode_Comment.md#bcolorcommentbubble)
- [bCommentBubbleMakeVisible](ue_ue.MaterialGraphNode_Comment.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.MaterialGraphNode_Comment.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.MaterialGraphNode_Comment.md#bcommentbubblevisible)
- [bCommentBubbleVisible\_InDetailsPanel](ue_ue.MaterialGraphNode_Comment.md#bcommentbubblevisible_indetailspanel)
- [bDisplayAsDisabled](ue_ue.MaterialGraphNode_Comment.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.MaterialGraphNode_Comment.md#bhascompilermessage)
- [bIsNodeEnabled](ue_ue.MaterialGraphNode_Comment.md#bisnodeenabled)
- [bUserSetEnabledState](ue_ue.MaterialGraphNode_Comment.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialGraphNode_Comment.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialGraphNode_Comment.md#executeubergraph)
- [GetClass](ue_ue.MaterialGraphNode_Comment.md#getclass)
- [GetName](ue_ue.MaterialGraphNode_Comment.md#getname)
- [GetOuter](ue_ue.MaterialGraphNode_Comment.md#getouter)
- [GetWorld](ue_ue.MaterialGraphNode_Comment.md#getworld)
- [Find](ue_ue.MaterialGraphNode_Comment.md#find)
- [Load](ue_ue.MaterialGraphNode_Comment.md#load)
- [StaticClass](ue_ue.MaterialGraphNode_Comment.md#staticclass)

## Constructors

### constructor

• **new MaterialGraphNode_Comment**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[constructor](ue_ue.EdGraphNode_Comment.md#constructor)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[AdvancedPinDisplay](ue_ue.EdGraphNode_Comment.md#advancedpindisplay)

___

### CommentColor

• **CommentColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[CommentColor](ue_ue.EdGraphNode_Comment.md#commentcolor)

___

### CommentDepth

• **CommentDepth**: `number`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[CommentDepth](ue_ue.EdGraphNode_Comment.md#commentdepth)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[DeprecatedPins](ue_ue.EdGraphNode_Comment.md#deprecatedpins)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[EnabledState](ue_ue.EdGraphNode_Comment.md#enabledstate)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[ErrorMsg](ue_ue.EdGraphNode_Comment.md#errormsg)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[ErrorType](ue_ue.EdGraphNode_Comment.md#errortype)

___

### FontSize

• **FontSize**: `number`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[FontSize](ue_ue.EdGraphNode_Comment.md#fontsize)

___

### MaterialExpressionComment

• **MaterialExpressionComment**: [`MaterialExpressionComment`](ue_ue.MaterialExpressionComment.md)

___

### MoveMode

• **MoveMode**: [`ECommentBoxMode`](../enums/ue_ue.ECommentBoxMode.md)

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[MoveMode](ue_ue.EdGraphNode_Comment.md#movemode)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[NodeComment](ue_ue.EdGraphNode_Comment.md#nodecomment)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[NodeGuid](ue_ue.EdGraphNode_Comment.md#nodeguid)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[NodeHeight](ue_ue.EdGraphNode_Comment.md#nodeheight)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[NodePosX](ue_ue.EdGraphNode_Comment.md#nodeposx)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[NodePosY](ue_ue.EdGraphNode_Comment.md#nodeposy)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[NodeUpgradeMessage](ue_ue.EdGraphNode_Comment.md#nodeupgrademessage)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[NodeWidth](ue_ue.EdGraphNode_Comment.md#nodewidth)

___

### \_\_tid\_EdGraphNode\_Comment\_\_

• **\_\_tid\_EdGraphNode\_Comment\_\_**: `boolean`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[__tid_EdGraphNode_Comment__](ue_ue.EdGraphNode_Comment.md#__tid_edgraphnode_comment__)

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[__tid_EdGraphNode__](ue_ue.EdGraphNode_Comment.md#__tid_edgraphnode__)

___

### \_\_tid\_MaterialGraphNode\_Comment\_\_

• **\_\_tid\_MaterialGraphNode\_Comment\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[__tid_Object__](ue_ue.EdGraphNode_Comment.md#__tid_object__)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[bCanRenameNode](ue_ue.EdGraphNode_Comment.md#bcanrenamenode)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[bCanResizeNode](ue_ue.EdGraphNode_Comment.md#bcanresizenode)

___

### bColorCommentBubble

• **bColorCommentBubble**: `boolean`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[bColorCommentBubble](ue_ue.EdGraphNode_Comment.md#bcolorcommentbubble)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[bCommentBubbleMakeVisible](ue_ue.EdGraphNode_Comment.md#bcommentbubblemakevisible)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[bCommentBubblePinned](ue_ue.EdGraphNode_Comment.md#bcommentbubblepinned)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[bCommentBubbleVisible](ue_ue.EdGraphNode_Comment.md#bcommentbubblevisible)

___

### bCommentBubbleVisible\_InDetailsPanel

• **bCommentBubbleVisible\_InDetailsPanel**: `boolean`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[bCommentBubbleVisible_InDetailsPanel](ue_ue.EdGraphNode_Comment.md#bcommentbubblevisible_indetailspanel)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[bDisplayAsDisabled](ue_ue.EdGraphNode_Comment.md#bdisplayasdisabled)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[bHasCompilerMessage](ue_ue.EdGraphNode_Comment.md#bhascompilermessage)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[bIsNodeEnabled](ue_ue.EdGraphNode_Comment.md#bisnodeenabled)

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[bUserSetEnabledState](ue_ue.EdGraphNode_Comment.md#busersetenabledstate)

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

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[CreateDefaultSubobject](ue_ue.EdGraphNode_Comment.md#createdefaultsubobject)

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

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[ExecuteUbergraph](ue_ue.EdGraphNode_Comment.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[GetClass](ue_ue.EdGraphNode_Comment.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[GetName](ue_ue.EdGraphNode_Comment.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[GetOuter](ue_ue.EdGraphNode_Comment.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[GetWorld](ue_ue.EdGraphNode_Comment.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialGraphNode_Comment`](ue_ue.MaterialGraphNode_Comment.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialGraphNode_Comment`](ue_ue.MaterialGraphNode_Comment.md)

#### Overrides

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[Find](ue_ue.EdGraphNode_Comment.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialGraphNode_Comment`](ue_ue.MaterialGraphNode_Comment.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialGraphNode_Comment`](ue_ue.MaterialGraphNode_Comment.md)

#### Overrides

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[Load](ue_ue.EdGraphNode_Comment.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EdGraphNode_Comment](ue_ue.EdGraphNode_Comment.md).[StaticClass](ue_ue.EdGraphNode_Comment.md#staticclass)
