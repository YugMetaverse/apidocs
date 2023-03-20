[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / K2Node\_InputActionEvent

# Class: K2Node\_InputActionEvent

[ue/ue](../modules/ue_ue.md).K2Node_InputActionEvent

## Hierarchy

- [`K2Node_Event`](ue_ue.K2Node_Event.md)

  ↳ **`K2Node_InputActionEvent`**

## Table of contents

### Constructors

- [constructor](ue_ue.K2Node_InputActionEvent.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.K2Node_InputActionEvent.md#advancedpindisplay)
- [CustomFunctionName](ue_ue.K2Node_InputActionEvent.md#customfunctionname)
- [DeprecatedPins](ue_ue.K2Node_InputActionEvent.md#deprecatedpins)
- [EnabledState](ue_ue.K2Node_InputActionEvent.md#enabledstate)
- [ErrorMsg](ue_ue.K2Node_InputActionEvent.md#errormsg)
- [ErrorType](ue_ue.K2Node_InputActionEvent.md#errortype)
- [EventReference](ue_ue.K2Node_InputActionEvent.md#eventreference)
- [EventSignatureClass](ue_ue.K2Node_InputActionEvent.md#eventsignatureclass)
- [EventSignatureName](ue_ue.K2Node_InputActionEvent.md#eventsignaturename)
- [FunctionFlags](ue_ue.K2Node_InputActionEvent.md#functionflags)
- [InputActionName](ue_ue.K2Node_InputActionEvent.md#inputactionname)
- [InputKeyEvent](ue_ue.K2Node_InputActionEvent.md#inputkeyevent)
- [NodeComment](ue_ue.K2Node_InputActionEvent.md#nodecomment)
- [NodeGuid](ue_ue.K2Node_InputActionEvent.md#nodeguid)
- [NodeHeight](ue_ue.K2Node_InputActionEvent.md#nodeheight)
- [NodePosX](ue_ue.K2Node_InputActionEvent.md#nodeposx)
- [NodePosY](ue_ue.K2Node_InputActionEvent.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.K2Node_InputActionEvent.md#nodeupgrademessage)
- [NodeWidth](ue_ue.K2Node_InputActionEvent.md#nodewidth)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.K2Node_InputActionEvent.md#__tid_edgraphnode__)
- [\_\_tid\_K2Node\_EditablePinBase\_\_](ue_ue.K2Node_InputActionEvent.md#__tid_k2node_editablepinbase__)
- [\_\_tid\_K2Node\_Event\_\_](ue_ue.K2Node_InputActionEvent.md#__tid_k2node_event__)
- [\_\_tid\_K2Node\_InputActionEvent\_\_](ue_ue.K2Node_InputActionEvent.md#__tid_k2node_inputactionevent__)
- [\_\_tid\_K2Node\_\_](ue_ue.K2Node_InputActionEvent.md#__tid_k2node__)
- [\_\_tid\_Object\_\_](ue_ue.K2Node_InputActionEvent.md#__tid_object__)
- [bCanRenameNode](ue_ue.K2Node_InputActionEvent.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.K2Node_InputActionEvent.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.K2Node_InputActionEvent.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.K2Node_InputActionEvent.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.K2Node_InputActionEvent.md#bcommentbubblevisible)
- [bConsumeInput](ue_ue.K2Node_InputActionEvent.md#bconsumeinput)
- [bDisplayAsDisabled](ue_ue.K2Node_InputActionEvent.md#bdisplayasdisabled)
- [bExecuteWhenPaused](ue_ue.K2Node_InputActionEvent.md#bexecutewhenpaused)
- [bHasCompilerMessage](ue_ue.K2Node_InputActionEvent.md#bhascompilermessage)
- [bInternalEvent](ue_ue.K2Node_InputActionEvent.md#binternalevent)
- [bIsEditable](ue_ue.K2Node_InputActionEvent.md#biseditable)
- [bIsNodeEnabled](ue_ue.K2Node_InputActionEvent.md#bisnodeenabled)
- [bOverrideFunction](ue_ue.K2Node_InputActionEvent.md#boverridefunction)
- [bOverrideParentBinding](ue_ue.K2Node_InputActionEvent.md#boverrideparentbinding)
- [bUserSetEnabledState](ue_ue.K2Node_InputActionEvent.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.K2Node_InputActionEvent.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.K2Node_InputActionEvent.md#executeubergraph)
- [GetClass](ue_ue.K2Node_InputActionEvent.md#getclass)
- [GetName](ue_ue.K2Node_InputActionEvent.md#getname)
- [GetOuter](ue_ue.K2Node_InputActionEvent.md#getouter)
- [GetWorld](ue_ue.K2Node_InputActionEvent.md#getworld)
- [Find](ue_ue.K2Node_InputActionEvent.md#find)
- [Load](ue_ue.K2Node_InputActionEvent.md#load)
- [StaticClass](ue_ue.K2Node_InputActionEvent.md#staticclass)

## Constructors

### constructor

• **new K2Node_InputActionEvent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[K2Node_Event](ue_ue.K2Node_Event.md).[constructor](ue_ue.K2Node_Event.md#constructor)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[AdvancedPinDisplay](ue_ue.K2Node_Event.md#advancedpindisplay)

___

### CustomFunctionName

• **CustomFunctionName**: `string`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[CustomFunctionName](ue_ue.K2Node_Event.md#customfunctionname)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[DeprecatedPins](ue_ue.K2Node_Event.md#deprecatedpins)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[EnabledState](ue_ue.K2Node_Event.md#enabledstate)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[ErrorMsg](ue_ue.K2Node_Event.md#errormsg)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[ErrorType](ue_ue.K2Node_Event.md#errortype)

___

### EventReference

• **EventReference**: [`MemberReference`](ue_ue.MemberReference.md)

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[EventReference](ue_ue.K2Node_Event.md#eventreference)

___

### EventSignatureClass

• **EventSignatureClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[EventSignatureClass](ue_ue.K2Node_Event.md#eventsignatureclass)

___

### EventSignatureName

• **EventSignatureName**: `string`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[EventSignatureName](ue_ue.K2Node_Event.md#eventsignaturename)

___

### FunctionFlags

• **FunctionFlags**: `number`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[FunctionFlags](ue_ue.K2Node_Event.md#functionflags)

___

### InputActionName

• **InputActionName**: `string`

___

### InputKeyEvent

• **InputKeyEvent**: [`EInputEvent`](../enums/ue_ue.EInputEvent.md)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[NodeComment](ue_ue.K2Node_Event.md#nodecomment)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[NodeGuid](ue_ue.K2Node_Event.md#nodeguid)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[NodeHeight](ue_ue.K2Node_Event.md#nodeheight)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[NodePosX](ue_ue.K2Node_Event.md#nodeposx)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[NodePosY](ue_ue.K2Node_Event.md#nodeposy)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[NodeUpgradeMessage](ue_ue.K2Node_Event.md#nodeupgrademessage)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[NodeWidth](ue_ue.K2Node_Event.md#nodewidth)

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[__tid_EdGraphNode__](ue_ue.K2Node_Event.md#__tid_edgraphnode__)

___

### \_\_tid\_K2Node\_EditablePinBase\_\_

• **\_\_tid\_K2Node\_EditablePinBase\_\_**: `boolean`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[__tid_K2Node_EditablePinBase__](ue_ue.K2Node_Event.md#__tid_k2node_editablepinbase__)

___

### \_\_tid\_K2Node\_Event\_\_

• **\_\_tid\_K2Node\_Event\_\_**: `boolean`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[__tid_K2Node_Event__](ue_ue.K2Node_Event.md#__tid_k2node_event__)

___

### \_\_tid\_K2Node\_InputActionEvent\_\_

• **\_\_tid\_K2Node\_InputActionEvent\_\_**: `boolean`

___

### \_\_tid\_K2Node\_\_

• **\_\_tid\_K2Node\_\_**: `boolean`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[__tid_K2Node__](ue_ue.K2Node_Event.md#__tid_k2node__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[__tid_Object__](ue_ue.K2Node_Event.md#__tid_object__)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[bCanRenameNode](ue_ue.K2Node_Event.md#bcanrenamenode)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[bCanResizeNode](ue_ue.K2Node_Event.md#bcanresizenode)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[bCommentBubbleMakeVisible](ue_ue.K2Node_Event.md#bcommentbubblemakevisible)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[bCommentBubblePinned](ue_ue.K2Node_Event.md#bcommentbubblepinned)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[bCommentBubbleVisible](ue_ue.K2Node_Event.md#bcommentbubblevisible)

___

### bConsumeInput

• **bConsumeInput**: `boolean`

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[bDisplayAsDisabled](ue_ue.K2Node_Event.md#bdisplayasdisabled)

___

### bExecuteWhenPaused

• **bExecuteWhenPaused**: `boolean`

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[bHasCompilerMessage](ue_ue.K2Node_Event.md#bhascompilermessage)

___

### bInternalEvent

• **bInternalEvent**: `boolean`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[bInternalEvent](ue_ue.K2Node_Event.md#binternalevent)

___

### bIsEditable

• **bIsEditable**: `boolean`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[bIsEditable](ue_ue.K2Node_Event.md#biseditable)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[bIsNodeEnabled](ue_ue.K2Node_Event.md#bisnodeenabled)

___

### bOverrideFunction

• **bOverrideFunction**: `boolean`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[bOverrideFunction](ue_ue.K2Node_Event.md#boverridefunction)

___

### bOverrideParentBinding

• **bOverrideParentBinding**: `boolean`

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[bUserSetEnabledState](ue_ue.K2Node_Event.md#busersetenabledstate)

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

[K2Node_Event](ue_ue.K2Node_Event.md).[CreateDefaultSubobject](ue_ue.K2Node_Event.md#createdefaultsubobject)

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

[K2Node_Event](ue_ue.K2Node_Event.md).[ExecuteUbergraph](ue_ue.K2Node_Event.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[GetClass](ue_ue.K2Node_Event.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[GetName](ue_ue.K2Node_Event.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[GetOuter](ue_ue.K2Node_Event.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[K2Node_Event](ue_ue.K2Node_Event.md).[GetWorld](ue_ue.K2Node_Event.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`K2Node_InputActionEvent`](ue_ue.K2Node_InputActionEvent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`K2Node_InputActionEvent`](ue_ue.K2Node_InputActionEvent.md)

#### Overrides

[K2Node_Event](ue_ue.K2Node_Event.md).[Find](ue_ue.K2Node_Event.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`K2Node_InputActionEvent`](ue_ue.K2Node_InputActionEvent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`K2Node_InputActionEvent`](ue_ue.K2Node_InputActionEvent.md)

#### Overrides

[K2Node_Event](ue_ue.K2Node_Event.md).[Load](ue_ue.K2Node_Event.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[K2Node_Event](ue_ue.K2Node_Event.md).[StaticClass](ue_ue.K2Node_Event.md#staticclass)
