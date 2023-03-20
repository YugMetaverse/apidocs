[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimGraphNode\_LinkedAnimGraphBase

# Class: AnimGraphNode\_LinkedAnimGraphBase

[ue/ue](../modules/ue_ue.md).AnimGraphNode_LinkedAnimGraphBase

## Hierarchy

- [`AnimGraphNode_CustomProperty`](ue_ue.AnimGraphNode_CustomProperty.md)

  ↳ **`AnimGraphNode_LinkedAnimGraphBase`**

  ↳↳ [`AnimGraphNode_LinkedAnimGraph`](ue_ue.AnimGraphNode_LinkedAnimGraph.md)

  ↳↳ [`AnimGraphNode_LinkedAnimLayer`](ue_ue.AnimGraphNode_LinkedAnimLayer.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#advancedpindisplay)
- [BlueprintUsage](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#blueprintusage)
- [DeprecatedPins](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#deprecatedpins)
- [EnabledState](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#enabledstate)
- [ErrorMsg](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#errormsg)
- [ErrorType](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#errortype)
- [ExposedPropertyNames](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#exposedpropertynames)
- [KnownExposableProperties](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#knownexposableproperties)
- [NodeComment](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#nodecomment)
- [NodeGuid](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#nodeguid)
- [NodeHeight](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#nodeheight)
- [NodePosX](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#nodeposx)
- [NodePosY](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#nodeupgrademessage)
- [NodeWidth](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#nodewidth)
- [ShowPinForProperties](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#showpinforproperties)
- [\_\_tid\_AnimGraphNode\_Base\_\_](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#__tid_animgraphnode_base__)
- [\_\_tid\_AnimGraphNode\_CustomProperty\_\_](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#__tid_animgraphnode_customproperty__)
- [\_\_tid\_AnimGraphNode\_LinkedAnimGraphBase\_\_](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#__tid_animgraphnode_linkedanimgraphbase__)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#__tid_edgraphnode__)
- [\_\_tid\_K2Node\_\_](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#__tid_k2node__)
- [\_\_tid\_Object\_\_](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#__tid_object__)
- [bCanRenameNode](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#bhascompilermessage)
- [bIsNodeEnabled](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#bisnodeenabled)
- [bUserSetEnabledState](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#executeubergraph)
- [GetClass](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#getclass)
- [GetName](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#getname)
- [GetOuter](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#getouter)
- [GetWorld](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#getworld)
- [Find](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#find)
- [Load](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#load)
- [StaticClass](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md#staticclass)

## Constructors

### constructor

• **new AnimGraphNode_LinkedAnimGraphBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[constructor](ue_ue.AnimGraphNode_CustomProperty.md#constructor)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[AdvancedPinDisplay](ue_ue.AnimGraphNode_CustomProperty.md#advancedpindisplay)

___

### BlueprintUsage

• **BlueprintUsage**: [`EBlueprintUsage`](../enums/ue_ue.EBlueprintUsage.md)

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[BlueprintUsage](ue_ue.AnimGraphNode_CustomProperty.md#blueprintusage)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[DeprecatedPins](ue_ue.AnimGraphNode_CustomProperty.md#deprecatedpins)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[EnabledState](ue_ue.AnimGraphNode_CustomProperty.md#enabledstate)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[ErrorMsg](ue_ue.AnimGraphNode_CustomProperty.md#errormsg)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[ErrorType](ue_ue.AnimGraphNode_CustomProperty.md#errortype)

___

### ExposedPropertyNames

• **ExposedPropertyNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[ExposedPropertyNames](ue_ue.AnimGraphNode_CustomProperty.md#exposedpropertynames)

___

### KnownExposableProperties

• **KnownExposableProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[KnownExposableProperties](ue_ue.AnimGraphNode_CustomProperty.md#knownexposableproperties)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[NodeComment](ue_ue.AnimGraphNode_CustomProperty.md#nodecomment)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[NodeGuid](ue_ue.AnimGraphNode_CustomProperty.md#nodeguid)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[NodeHeight](ue_ue.AnimGraphNode_CustomProperty.md#nodeheight)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[NodePosX](ue_ue.AnimGraphNode_CustomProperty.md#nodeposx)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[NodePosY](ue_ue.AnimGraphNode_CustomProperty.md#nodeposy)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[NodeUpgradeMessage](ue_ue.AnimGraphNode_CustomProperty.md#nodeupgrademessage)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[NodeWidth](ue_ue.AnimGraphNode_CustomProperty.md#nodewidth)

___

### ShowPinForProperties

• **ShowPinForProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`OptionalPinFromProperty`](ue_ue.OptionalPinFromProperty.md)\>

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[ShowPinForProperties](ue_ue.AnimGraphNode_CustomProperty.md#showpinforproperties)

___

### \_\_tid\_AnimGraphNode\_Base\_\_

• **\_\_tid\_AnimGraphNode\_Base\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[__tid_AnimGraphNode_Base__](ue_ue.AnimGraphNode_CustomProperty.md#__tid_animgraphnode_base__)

___

### \_\_tid\_AnimGraphNode\_CustomProperty\_\_

• **\_\_tid\_AnimGraphNode\_CustomProperty\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[__tid_AnimGraphNode_CustomProperty__](ue_ue.AnimGraphNode_CustomProperty.md#__tid_animgraphnode_customproperty__)

___

### \_\_tid\_AnimGraphNode\_LinkedAnimGraphBase\_\_

• **\_\_tid\_AnimGraphNode\_LinkedAnimGraphBase\_\_**: `boolean`

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[__tid_EdGraphNode__](ue_ue.AnimGraphNode_CustomProperty.md#__tid_edgraphnode__)

___

### \_\_tid\_K2Node\_\_

• **\_\_tid\_K2Node\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[__tid_K2Node__](ue_ue.AnimGraphNode_CustomProperty.md#__tid_k2node__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[__tid_Object__](ue_ue.AnimGraphNode_CustomProperty.md#__tid_object__)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[bCanRenameNode](ue_ue.AnimGraphNode_CustomProperty.md#bcanrenamenode)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[bCanResizeNode](ue_ue.AnimGraphNode_CustomProperty.md#bcanresizenode)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[bCommentBubbleMakeVisible](ue_ue.AnimGraphNode_CustomProperty.md#bcommentbubblemakevisible)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[bCommentBubblePinned](ue_ue.AnimGraphNode_CustomProperty.md#bcommentbubblepinned)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[bCommentBubbleVisible](ue_ue.AnimGraphNode_CustomProperty.md#bcommentbubblevisible)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[bDisplayAsDisabled](ue_ue.AnimGraphNode_CustomProperty.md#bdisplayasdisabled)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[bHasCompilerMessage](ue_ue.AnimGraphNode_CustomProperty.md#bhascompilermessage)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[bIsNodeEnabled](ue_ue.AnimGraphNode_CustomProperty.md#bisnodeenabled)

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[bUserSetEnabledState](ue_ue.AnimGraphNode_CustomProperty.md#busersetenabledstate)

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

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[CreateDefaultSubobject](ue_ue.AnimGraphNode_CustomProperty.md#createdefaultsubobject)

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

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[ExecuteUbergraph](ue_ue.AnimGraphNode_CustomProperty.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[GetClass](ue_ue.AnimGraphNode_CustomProperty.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[GetName](ue_ue.AnimGraphNode_CustomProperty.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[GetOuter](ue_ue.AnimGraphNode_CustomProperty.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[GetWorld](ue_ue.AnimGraphNode_CustomProperty.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimGraphNode_LinkedAnimGraphBase`](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimGraphNode_LinkedAnimGraphBase`](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md)

#### Overrides

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[Find](ue_ue.AnimGraphNode_CustomProperty.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimGraphNode_LinkedAnimGraphBase`](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimGraphNode_LinkedAnimGraphBase`](ue_ue.AnimGraphNode_LinkedAnimGraphBase.md)

#### Overrides

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[Load](ue_ue.AnimGraphNode_CustomProperty.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimGraphNode_CustomProperty](ue_ue.AnimGraphNode_CustomProperty.md).[StaticClass](ue_ue.AnimGraphNode_CustomProperty.md#staticclass)
