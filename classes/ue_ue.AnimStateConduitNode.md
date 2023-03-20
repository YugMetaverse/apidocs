[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimStateConduitNode

# Class: AnimStateConduitNode

[ue/ue](../modules/ue_ue.md).AnimStateConduitNode

## Hierarchy

- [`AnimStateNodeBase`](ue_ue.AnimStateNodeBase.md)

  ↳ **`AnimStateConduitNode`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimStateConduitNode.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.AnimStateConduitNode.md#advancedpindisplay)
- [BoundGraph](ue_ue.AnimStateConduitNode.md#boundgraph)
- [DeprecatedPins](ue_ue.AnimStateConduitNode.md#deprecatedpins)
- [EnabledState](ue_ue.AnimStateConduitNode.md#enabledstate)
- [ErrorMsg](ue_ue.AnimStateConduitNode.md#errormsg)
- [ErrorType](ue_ue.AnimStateConduitNode.md#errortype)
- [NodeComment](ue_ue.AnimStateConduitNode.md#nodecomment)
- [NodeGuid](ue_ue.AnimStateConduitNode.md#nodeguid)
- [NodeHeight](ue_ue.AnimStateConduitNode.md#nodeheight)
- [NodePosX](ue_ue.AnimStateConduitNode.md#nodeposx)
- [NodePosY](ue_ue.AnimStateConduitNode.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.AnimStateConduitNode.md#nodeupgrademessage)
- [NodeWidth](ue_ue.AnimStateConduitNode.md#nodewidth)
- [\_\_tid\_AnimStateConduitNode\_\_](ue_ue.AnimStateConduitNode.md#__tid_animstateconduitnode__)
- [\_\_tid\_AnimStateNodeBase\_\_](ue_ue.AnimStateConduitNode.md#__tid_animstatenodebase__)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.AnimStateConduitNode.md#__tid_edgraphnode__)
- [\_\_tid\_Object\_\_](ue_ue.AnimStateConduitNode.md#__tid_object__)
- [bCanRenameNode](ue_ue.AnimStateConduitNode.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.AnimStateConduitNode.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.AnimStateConduitNode.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.AnimStateConduitNode.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.AnimStateConduitNode.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.AnimStateConduitNode.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.AnimStateConduitNode.md#bhascompilermessage)
- [bIsNodeEnabled](ue_ue.AnimStateConduitNode.md#bisnodeenabled)
- [bUserSetEnabledState](ue_ue.AnimStateConduitNode.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimStateConduitNode.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimStateConduitNode.md#executeubergraph)
- [GetClass](ue_ue.AnimStateConduitNode.md#getclass)
- [GetName](ue_ue.AnimStateConduitNode.md#getname)
- [GetOuter](ue_ue.AnimStateConduitNode.md#getouter)
- [GetWorld](ue_ue.AnimStateConduitNode.md#getworld)
- [Find](ue_ue.AnimStateConduitNode.md#find)
- [Load](ue_ue.AnimStateConduitNode.md#load)
- [StaticClass](ue_ue.AnimStateConduitNode.md#staticclass)

## Constructors

### constructor

• **new AnimStateConduitNode**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### BoundGraph

• **BoundGraph**: [`EdGraph`](ue_ue.EdGraph.md)

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

### \_\_tid\_AnimStateConduitNode\_\_

• **\_\_tid\_AnimStateConduitNode\_\_**: `boolean`

___

### \_\_tid\_AnimStateNodeBase\_\_

• **\_\_tid\_AnimStateNodeBase\_\_**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[__tid_AnimStateNodeBase__](ue_ue.AnimStateNodeBase.md#__tid_animstatenodebase__)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimStateConduitNode`](ue_ue.AnimStateConduitNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimStateConduitNode`](ue_ue.AnimStateConduitNode.md)

#### Overrides

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[Find](ue_ue.AnimStateNodeBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimStateConduitNode`](ue_ue.AnimStateConduitNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimStateConduitNode`](ue_ue.AnimStateConduitNode.md)

#### Overrides

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[Load](ue_ue.AnimStateNodeBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[StaticClass](ue_ue.AnimStateNodeBase.md#staticclass)
