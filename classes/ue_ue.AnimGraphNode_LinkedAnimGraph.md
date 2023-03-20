[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimGraphNode\_LinkedAnimGraph

# Class: AnimGraphNode\_LinkedAnimGraph

[ue/ue](../modules/ue_ue.md).AnimGraphNode_LinkedAnimGraph

## Hierarchy

- [`AnimGraphNode_LinkedAnimGraphBase`](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md)

  ↳ **`AnimGraphNode_LinkedAnimGraph`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimGraphNode_LinkedAnimGraph.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.AnimGraphNode_LinkedAnimGraph.md#advancedpindisplay)
- [BlueprintUsage](ue_ue.AnimGraphNode_LinkedAnimGraph.md#blueprintusage)
- [DeprecatedPins](ue_ue.AnimGraphNode_LinkedAnimGraph.md#deprecatedpins)
- [EnabledState](ue_ue.AnimGraphNode_LinkedAnimGraph.md#enabledstate)
- [ErrorMsg](ue_ue.AnimGraphNode_LinkedAnimGraph.md#errormsg)
- [ErrorType](ue_ue.AnimGraphNode_LinkedAnimGraph.md#errortype)
- [ExposedPropertyNames](ue_ue.AnimGraphNode_LinkedAnimGraph.md#exposedpropertynames)
- [KnownExposableProperties](ue_ue.AnimGraphNode_LinkedAnimGraph.md#knownexposableproperties)
- [Node](ue_ue.AnimGraphNode_LinkedAnimGraph.md#node)
- [NodeComment](ue_ue.AnimGraphNode_LinkedAnimGraph.md#nodecomment)
- [NodeGuid](ue_ue.AnimGraphNode_LinkedAnimGraph.md#nodeguid)
- [NodeHeight](ue_ue.AnimGraphNode_LinkedAnimGraph.md#nodeheight)
- [NodePosX](ue_ue.AnimGraphNode_LinkedAnimGraph.md#nodeposx)
- [NodePosY](ue_ue.AnimGraphNode_LinkedAnimGraph.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.AnimGraphNode_LinkedAnimGraph.md#nodeupgrademessage)
- [NodeWidth](ue_ue.AnimGraphNode_LinkedAnimGraph.md#nodewidth)
- [ShowPinForProperties](ue_ue.AnimGraphNode_LinkedAnimGraph.md#showpinforproperties)
- [\_\_tid\_AnimGraphNode\_Base\_\_](ue_ue.AnimGraphNode_LinkedAnimGraph.md#__tid_animgraphnode_base__)
- [\_\_tid\_AnimGraphNode\_CustomProperty\_\_](ue_ue.AnimGraphNode_LinkedAnimGraph.md#__tid_animgraphnode_customproperty__)
- [\_\_tid\_AnimGraphNode\_LinkedAnimGraphBase\_\_](ue_ue.AnimGraphNode_LinkedAnimGraph.md#__tid_animgraphnode_linkedanimgraphbase__)
- [\_\_tid\_AnimGraphNode\_LinkedAnimGraph\_\_](ue_ue.AnimGraphNode_LinkedAnimGraph.md#__tid_animgraphnode_linkedanimgraph__)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.AnimGraphNode_LinkedAnimGraph.md#__tid_edgraphnode__)
- [\_\_tid\_K2Node\_\_](ue_ue.AnimGraphNode_LinkedAnimGraph.md#__tid_k2node__)
- [\_\_tid\_Object\_\_](ue_ue.AnimGraphNode_LinkedAnimGraph.md#__tid_object__)
- [bCanRenameNode](ue_ue.AnimGraphNode_LinkedAnimGraph.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.AnimGraphNode_LinkedAnimGraph.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.AnimGraphNode_LinkedAnimGraph.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.AnimGraphNode_LinkedAnimGraph.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.AnimGraphNode_LinkedAnimGraph.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.AnimGraphNode_LinkedAnimGraph.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.AnimGraphNode_LinkedAnimGraph.md#bhascompilermessage)
- [bIsNodeEnabled](ue_ue.AnimGraphNode_LinkedAnimGraph.md#bisnodeenabled)
- [bUserSetEnabledState](ue_ue.AnimGraphNode_LinkedAnimGraph.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimGraphNode_LinkedAnimGraph.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimGraphNode_LinkedAnimGraph.md#executeubergraph)
- [GetClass](ue_ue.AnimGraphNode_LinkedAnimGraph.md#getclass)
- [GetName](ue_ue.AnimGraphNode_LinkedAnimGraph.md#getname)
- [GetOuter](ue_ue.AnimGraphNode_LinkedAnimGraph.md#getouter)
- [GetWorld](ue_ue.AnimGraphNode_LinkedAnimGraph.md#getworld)
- [Find](ue_ue.AnimGraphNode_LinkedAnimGraph.md#find)
- [Load](ue_ue.AnimGraphNode_LinkedAnimGraph.md#load)
- [StaticClass](ue_ue.AnimGraphNode_LinkedAnimGraph.md#staticclass)

## Constructors

### constructor

• **new AnimGraphNode_LinkedAnimGraph**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[constructor](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#constructor)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[AdvancedPinDisplay](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#advancedpindisplay)

___

### BlueprintUsage

• **BlueprintUsage**: [`EBlueprintUsage`](../enums/ue_ue.EBlueprintUsage.md)

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[BlueprintUsage](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#blueprintusage)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[DeprecatedPins](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#deprecatedpins)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[EnabledState](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#enabledstate)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[ErrorMsg](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#errormsg)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[ErrorType](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#errortype)

___

### ExposedPropertyNames

• **ExposedPropertyNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[ExposedPropertyNames](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#exposedpropertynames)

___

### KnownExposableProperties

• **KnownExposableProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[KnownExposableProperties](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#knownexposableproperties)

___

### Node

• **Node**: [`AnimNode_LinkedAnimGraph`](ue_ue.AnimNode_LinkedAnimGraph.md)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[NodeComment](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#nodecomment)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[NodeGuid](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#nodeguid)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[NodeHeight](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#nodeheight)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[NodePosX](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#nodeposx)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[NodePosY](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#nodeposy)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[NodeUpgradeMessage](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#nodeupgrademessage)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[NodeWidth](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#nodewidth)

___

### ShowPinForProperties

• **ShowPinForProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`OptionalPinFromProperty`](ue_ue.OptionalPinFromProperty.md)\>

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[ShowPinForProperties](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#showpinforproperties)

___

### \_\_tid\_AnimGraphNode\_Base\_\_

• **\_\_tid\_AnimGraphNode\_Base\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[__tid_AnimGraphNode_Base__](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#__tid_animgraphnode_base__)

___

### \_\_tid\_AnimGraphNode\_CustomProperty\_\_

• **\_\_tid\_AnimGraphNode\_CustomProperty\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[__tid_AnimGraphNode_CustomProperty__](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#__tid_animgraphnode_customproperty__)

___

### \_\_tid\_AnimGraphNode\_LinkedAnimGraphBase\_\_

• **\_\_tid\_AnimGraphNode\_LinkedAnimGraphBase\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[__tid_AnimGraphNode_LinkedAnimGraphBase__](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#__tid_animgraphnode_linkedanimgraphbase__)

___

### \_\_tid\_AnimGraphNode\_LinkedAnimGraph\_\_

• **\_\_tid\_AnimGraphNode\_LinkedAnimGraph\_\_**: `boolean`

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[__tid_EdGraphNode__](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#__tid_edgraphnode__)

___

### \_\_tid\_K2Node\_\_

• **\_\_tid\_K2Node\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[__tid_K2Node__](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#__tid_k2node__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[__tid_Object__](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#__tid_object__)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[bCanRenameNode](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#bcanrenamenode)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[bCanResizeNode](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#bcanresizenode)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[bCommentBubbleMakeVisible](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#bcommentbubblemakevisible)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[bCommentBubblePinned](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#bcommentbubblepinned)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[bCommentBubbleVisible](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#bcommentbubblevisible)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[bDisplayAsDisabled](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#bdisplayasdisabled)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[bHasCompilerMessage](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#bhascompilermessage)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[bIsNodeEnabled](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#bisnodeenabled)

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[bUserSetEnabledState](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#busersetenabledstate)

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

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[CreateDefaultSubobject](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#createdefaultsubobject)

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

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[ExecuteUbergraph](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[GetClass](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[GetName](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[GetOuter](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[GetWorld](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimGraphNode_LinkedAnimGraph`](ue_ue.AnimGraphNode_LinkedAnimGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimGraphNode_LinkedAnimGraph`](ue_ue.AnimGraphNode_LinkedAnimGraph.md)

#### Overrides

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[Find](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimGraphNode_LinkedAnimGraph`](ue_ue.AnimGraphNode_LinkedAnimGraph.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimGraphNode_LinkedAnimGraph`](ue_ue.AnimGraphNode_LinkedAnimGraph.md)

#### Overrides

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[Load](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimGraphNode_LinkedAnimGraphBase](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md).[StaticClass](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#staticclass)
