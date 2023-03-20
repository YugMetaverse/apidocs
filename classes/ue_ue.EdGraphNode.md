[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EdGraphNode

# Class: EdGraphNode

[ue/ue](../modules/ue_ue.md).EdGraphNode

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`EdGraphNode`**

  ↳↳ [`AIGraphNode`](ue_ue.AIGraphNode.md)

  ↳↳ [`K2Node`](ue_ue.K2Node.md)

  ↳↳ [`AnimStateEntryNode`](ue_ue.AnimStateEntryNode.md)

  ↳↳ [`AnimStateNodeBase`](ue_ue.AnimStateNodeBase.md)

  ↳↳ [`BehaviorTreeDecoratorGraphNode`](ue_ue.BehaviorTreeDecoratorGraphNode.md)

  ↳↳ [`EdGraphNode_Comment`](ue_ue.EdGraphNode_Comment.md)

  ↳↳ [`EdGraphNode_Documentation`](ue_ue.EdGraphNode_Documentation.md)

  ↳↳ [`EdGraphNode_Reference`](ue_ue.EdGraphNode_Reference.md)

  ↳↳ [`MaterialGraphNode_Base`](ue_ue.MaterialGraphNode_Base.md)

  ↳↳ [`SoundClassGraphNode`](ue_ue.SoundClassGraphNode.md)

  ↳↳ [`SoundCueGraphNode_Base`](ue_ue.SoundCueGraphNode_Base.md)

  ↳↳ [`SoundSubmixGraphNode`](ue_ue.SoundSubmixGraphNode.md)

## Table of contents

### Constructors

- [constructor](ue_ue.EdGraphNode.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.EdGraphNode.md#advancedpindisplay)
- [DeprecatedPins](ue_ue.EdGraphNode.md#deprecatedpins)
- [EnabledState](ue_ue.EdGraphNode.md#enabledstate)
- [ErrorMsg](ue_ue.EdGraphNode.md#errormsg)
- [ErrorType](ue_ue.EdGraphNode.md#errortype)
- [NodeComment](ue_ue.EdGraphNode.md#nodecomment)
- [NodeGuid](ue_ue.EdGraphNode.md#nodeguid)
- [NodeHeight](ue_ue.EdGraphNode.md#nodeheight)
- [NodePosX](ue_ue.EdGraphNode.md#nodeposx)
- [NodePosY](ue_ue.EdGraphNode.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.EdGraphNode.md#nodeupgrademessage)
- [NodeWidth](ue_ue.EdGraphNode.md#nodewidth)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.EdGraphNode.md#__tid_edgraphnode__)
- [\_\_tid\_Object\_\_](ue_ue.EdGraphNode.md#__tid_object__)
- [bCanRenameNode](ue_ue.EdGraphNode.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.EdGraphNode.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.EdGraphNode.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.EdGraphNode.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.EdGraphNode.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.EdGraphNode.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.EdGraphNode.md#bhascompilermessage)
- [bIsNodeEnabled](ue_ue.EdGraphNode.md#bisnodeenabled)
- [bUserSetEnabledState](ue_ue.EdGraphNode.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.EdGraphNode.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EdGraphNode.md#executeubergraph)
- [GetClass](ue_ue.EdGraphNode.md#getclass)
- [GetName](ue_ue.EdGraphNode.md#getname)
- [GetOuter](ue_ue.EdGraphNode.md#getouter)
- [GetWorld](ue_ue.EdGraphNode.md#getworld)
- [Find](ue_ue.EdGraphNode.md#find)
- [Load](ue_ue.EdGraphNode.md#load)
- [StaticClass](ue_ue.EdGraphNode.md#staticclass)

## Constructors

### constructor

• **new EdGraphNode**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

___

### ErrorMsg

• **ErrorMsg**: `string`

___

### ErrorType

• **ErrorType**: `number`

___

### NodeComment

• **NodeComment**: `string`

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### NodeHeight

• **NodeHeight**: `number`

___

### NodePosX

• **NodePosX**: `number`

___

### NodePosY

• **NodePosY**: `number`

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

___

### NodeWidth

• **NodeWidth**: `number`

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
