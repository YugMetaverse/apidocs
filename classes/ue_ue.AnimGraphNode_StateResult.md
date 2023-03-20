[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimGraphNode\_StateResult

# Class: AnimGraphNode\_StateResult

[ue/ue](../modules/ue_ue.md).AnimGraphNode_StateResult

## Hierarchy

- [`AnimGraphNode_Base`](ue_ue.AnimGraphNode_Base.md)

  ↳ **`AnimGraphNode_StateResult`**

  ↳↳ [`AnimGraphNode_CustomTransitionResult`](ue_ue.AnimGraphNode_CustomTransitionResult.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimGraphNode_StateResult.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.AnimGraphNode_StateResult.md#advancedpindisplay)
- [BlueprintUsage](ue_ue.AnimGraphNode_StateResult.md#blueprintusage)
- [DeprecatedPins](ue_ue.AnimGraphNode_StateResult.md#deprecatedpins)
- [EnabledState](ue_ue.AnimGraphNode_StateResult.md#enabledstate)
- [ErrorMsg](ue_ue.AnimGraphNode_StateResult.md#errormsg)
- [ErrorType](ue_ue.AnimGraphNode_StateResult.md#errortype)
- [Node](ue_ue.AnimGraphNode_StateResult.md#node)
- [NodeComment](ue_ue.AnimGraphNode_StateResult.md#nodecomment)
- [NodeGuid](ue_ue.AnimGraphNode_StateResult.md#nodeguid)
- [NodeHeight](ue_ue.AnimGraphNode_StateResult.md#nodeheight)
- [NodePosX](ue_ue.AnimGraphNode_StateResult.md#nodeposx)
- [NodePosY](ue_ue.AnimGraphNode_StateResult.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.AnimGraphNode_StateResult.md#nodeupgrademessage)
- [NodeWidth](ue_ue.AnimGraphNode_StateResult.md#nodewidth)
- [ShowPinForProperties](ue_ue.AnimGraphNode_StateResult.md#showpinforproperties)
- [\_\_tid\_AnimGraphNode\_Base\_\_](ue_ue.AnimGraphNode_StateResult.md#__tid_animgraphnode_base__)
- [\_\_tid\_AnimGraphNode\_StateResult\_\_](ue_ue.AnimGraphNode_StateResult.md#__tid_animgraphnode_stateresult__)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.AnimGraphNode_StateResult.md#__tid_edgraphnode__)
- [\_\_tid\_K2Node\_\_](ue_ue.AnimGraphNode_StateResult.md#__tid_k2node__)
- [\_\_tid\_Object\_\_](ue_ue.AnimGraphNode_StateResult.md#__tid_object__)
- [bCanRenameNode](ue_ue.AnimGraphNode_StateResult.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.AnimGraphNode_StateResult.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.AnimGraphNode_StateResult.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.AnimGraphNode_StateResult.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.AnimGraphNode_StateResult.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.AnimGraphNode_StateResult.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.AnimGraphNode_StateResult.md#bhascompilermessage)
- [bIsNodeEnabled](ue_ue.AnimGraphNode_StateResult.md#bisnodeenabled)
- [bUserSetEnabledState](ue_ue.AnimGraphNode_StateResult.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimGraphNode_StateResult.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimGraphNode_StateResult.md#executeubergraph)
- [GetClass](ue_ue.AnimGraphNode_StateResult.md#getclass)
- [GetName](ue_ue.AnimGraphNode_StateResult.md#getname)
- [GetOuter](ue_ue.AnimGraphNode_StateResult.md#getouter)
- [GetWorld](ue_ue.AnimGraphNode_StateResult.md#getworld)
- [Find](ue_ue.AnimGraphNode_StateResult.md#find)
- [Load](ue_ue.AnimGraphNode_StateResult.md#load)
- [StaticClass](ue_ue.AnimGraphNode_StateResult.md#staticclass)

## Constructors

### constructor

• **new AnimGraphNode_StateResult**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[constructor](ue_ue.AnimGraphNode_Base.md#constructor)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[AdvancedPinDisplay](ue_ue.AnimGraphNode_Base.md#advancedpindisplay)

___

### BlueprintUsage

• **BlueprintUsage**: [`EBlueprintUsage`](../enums/ue_ue.EBlueprintUsage.md)

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[BlueprintUsage](ue_ue.AnimGraphNode_Base.md#blueprintusage)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[DeprecatedPins](ue_ue.AnimGraphNode_Base.md#deprecatedpins)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[EnabledState](ue_ue.AnimGraphNode_Base.md#enabledstate)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[ErrorMsg](ue_ue.AnimGraphNode_Base.md#errormsg)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[ErrorType](ue_ue.AnimGraphNode_Base.md#errortype)

___

### Node

• **Node**: [`AnimNode_StateResult`](ue_ue.AnimNode_StateResult.md)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[NodeComment](ue_ue.AnimGraphNode_Base.md#nodecomment)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[NodeGuid](ue_ue.AnimGraphNode_Base.md#nodeguid)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[NodeHeight](ue_ue.AnimGraphNode_Base.md#nodeheight)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[NodePosX](ue_ue.AnimGraphNode_Base.md#nodeposx)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[NodePosY](ue_ue.AnimGraphNode_Base.md#nodeposy)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[NodeUpgradeMessage](ue_ue.AnimGraphNode_Base.md#nodeupgrademessage)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[NodeWidth](ue_ue.AnimGraphNode_Base.md#nodewidth)

___

### ShowPinForProperties

• **ShowPinForProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`OptionalPinFromProperty`](ue_ue.OptionalPinFromProperty.md)\>

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[ShowPinForProperties](ue_ue.AnimGraphNode_Base.md#showpinforproperties)

___

### \_\_tid\_AnimGraphNode\_Base\_\_

• **\_\_tid\_AnimGraphNode\_Base\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[__tid_AnimGraphNode_Base__](ue_ue.AnimGraphNode_Base.md#__tid_animgraphnode_base__)

___

### \_\_tid\_AnimGraphNode\_StateResult\_\_

• **\_\_tid\_AnimGraphNode\_StateResult\_\_**: `boolean`

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[__tid_EdGraphNode__](ue_ue.AnimGraphNode_Base.md#__tid_edgraphnode__)

___

### \_\_tid\_K2Node\_\_

• **\_\_tid\_K2Node\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[__tid_K2Node__](ue_ue.AnimGraphNode_Base.md#__tid_k2node__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[__tid_Object__](ue_ue.AnimGraphNode_Base.md#__tid_object__)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[bCanRenameNode](ue_ue.AnimGraphNode_Base.md#bcanrenamenode)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[bCanResizeNode](ue_ue.AnimGraphNode_Base.md#bcanresizenode)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[bCommentBubbleMakeVisible](ue_ue.AnimGraphNode_Base.md#bcommentbubblemakevisible)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[bCommentBubblePinned](ue_ue.AnimGraphNode_Base.md#bcommentbubblepinned)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[bCommentBubbleVisible](ue_ue.AnimGraphNode_Base.md#bcommentbubblevisible)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[bDisplayAsDisabled](ue_ue.AnimGraphNode_Base.md#bdisplayasdisabled)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[bHasCompilerMessage](ue_ue.AnimGraphNode_Base.md#bhascompilermessage)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[bIsNodeEnabled](ue_ue.AnimGraphNode_Base.md#bisnodeenabled)

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[bUserSetEnabledState](ue_ue.AnimGraphNode_Base.md#busersetenabledstate)

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

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[CreateDefaultSubobject](ue_ue.AnimGraphNode_Base.md#createdefaultsubobject)

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

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[ExecuteUbergraph](ue_ue.AnimGraphNode_Base.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[GetClass](ue_ue.AnimGraphNode_Base.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[GetName](ue_ue.AnimGraphNode_Base.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[GetOuter](ue_ue.AnimGraphNode_Base.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[GetWorld](ue_ue.AnimGraphNode_Base.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimGraphNode_StateResult`](ue_ue.AnimGraphNode_StateResult.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimGraphNode_StateResult`](ue_ue.AnimGraphNode_StateResult.md)

#### Overrides

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[Find](ue_ue.AnimGraphNode_Base.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimGraphNode_StateResult`](ue_ue.AnimGraphNode_StateResult.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimGraphNode_StateResult`](ue_ue.AnimGraphNode_StateResult.md)

#### Overrides

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[Load](ue_ue.AnimGraphNode_Base.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimGraphNode_Base](ue_ue.AnimGraphNode_Base.md).[StaticClass](ue_ue.AnimGraphNode_Base.md#staticclass)
