[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / K2Node\_Event

# Class: K2Node\_Event

[ue/ue](../modules/ue_ue.md).K2Node_Event

## Hierarchy

- [`K2Node_EditablePinBase`](ue_ue.K2Node_EditablePinBase.md)

  ↳ **`K2Node_Event`**

  ↳↳ [`K2Node_ActorBoundEvent`](ue_ue.K2Node_ActorBoundEvent.md)

  ↳↳ [`K2Node_ComponentBoundEvent`](ue_ue.K2Node_ComponentBoundEvent.md)

  ↳↳ [`K2Node_CustomEvent`](ue_ue.K2Node_CustomEvent.md)

  ↳↳ [`K2Node_InputActionEvent`](ue_ue.K2Node_InputActionEvent.md)

  ↳↳ [`K2Node_InputAxisEvent`](ue_ue.K2Node_InputAxisEvent.md)

  ↳↳ [`K2Node_InputAxisKeyEvent`](ue_ue.K2Node_InputAxisKeyEvent.md)

  ↳↳ [`K2Node_InputKeyEvent`](ue_ue.K2Node_InputKeyEvent.md)

  ↳↳ [`K2Node_InputTouchEvent`](ue_ue.K2Node_InputTouchEvent.md)

  ↳↳ [`K2Node_WidgetAnimationEvent`](ue_ue.K2Node_WidgetAnimationEvent.md)

## Table of contents

### Constructors

- [constructor](ue_ue.K2Node_Event.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.K2Node_Event.md#advancedpindisplay)
- [CustomFunctionName](ue_ue.K2Node_Event.md#customfunctionname)
- [DeprecatedPins](ue_ue.K2Node_Event.md#deprecatedpins)
- [EnabledState](ue_ue.K2Node_Event.md#enabledstate)
- [ErrorMsg](ue_ue.K2Node_Event.md#errormsg)
- [ErrorType](ue_ue.K2Node_Event.md#errortype)
- [EventReference](ue_ue.K2Node_Event.md#eventreference)
- [EventSignatureClass](ue_ue.K2Node_Event.md#eventsignatureclass)
- [EventSignatureName](ue_ue.K2Node_Event.md#eventsignaturename)
- [FunctionFlags](ue_ue.K2Node_Event.md#functionflags)
- [NodeComment](ue_ue.K2Node_Event.md#nodecomment)
- [NodeGuid](ue_ue.K2Node_Event.md#nodeguid)
- [NodeHeight](ue_ue.K2Node_Event.md#nodeheight)
- [NodePosX](ue_ue.K2Node_Event.md#nodeposx)
- [NodePosY](ue_ue.K2Node_Event.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.K2Node_Event.md#nodeupgrademessage)
- [NodeWidth](ue_ue.K2Node_Event.md#nodewidth)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.K2Node_Event.md#__tid_edgraphnode__)
- [\_\_tid\_K2Node\_EditablePinBase\_\_](ue_ue.K2Node_Event.md#__tid_k2node_editablepinbase__)
- [\_\_tid\_K2Node\_Event\_\_](ue_ue.K2Node_Event.md#__tid_k2node_event__)
- [\_\_tid\_K2Node\_\_](ue_ue.K2Node_Event.md#__tid_k2node__)
- [\_\_tid\_Object\_\_](ue_ue.K2Node_Event.md#__tid_object__)
- [bCanRenameNode](ue_ue.K2Node_Event.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.K2Node_Event.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.K2Node_Event.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.K2Node_Event.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.K2Node_Event.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.K2Node_Event.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.K2Node_Event.md#bhascompilermessage)
- [bInternalEvent](ue_ue.K2Node_Event.md#binternalevent)
- [bIsEditable](ue_ue.K2Node_Event.md#biseditable)
- [bIsNodeEnabled](ue_ue.K2Node_Event.md#bisnodeenabled)
- [bOverrideFunction](ue_ue.K2Node_Event.md#boverridefunction)
- [bUserSetEnabledState](ue_ue.K2Node_Event.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.K2Node_Event.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.K2Node_Event.md#executeubergraph)
- [GetClass](ue_ue.K2Node_Event.md#getclass)
- [GetName](ue_ue.K2Node_Event.md#getname)
- [GetOuter](ue_ue.K2Node_Event.md#getouter)
- [GetWorld](ue_ue.K2Node_Event.md#getworld)
- [Find](ue_ue.K2Node_Event.md#find)
- [Load](ue_ue.K2Node_Event.md#load)
- [StaticClass](ue_ue.K2Node_Event.md#staticclass)

## Constructors

### constructor

• **new K2Node_Event**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[constructor](ue_ue.K2Node_EditablePinBase.md#constructor)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[AdvancedPinDisplay](ue_ue.K2Node_EditablePinBase.md#advancedpindisplay)

___

### CustomFunctionName

• **CustomFunctionName**: `string`

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[DeprecatedPins](ue_ue.K2Node_EditablePinBase.md#deprecatedpins)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[EnabledState](ue_ue.K2Node_EditablePinBase.md#enabledstate)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[ErrorMsg](ue_ue.K2Node_EditablePinBase.md#errormsg)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[ErrorType](ue_ue.K2Node_EditablePinBase.md#errortype)

___

### EventReference

• **EventReference**: [`MemberReference`](ue_ue.MemberReference.md)

___

### EventSignatureClass

• **EventSignatureClass**: [`Class`](ue_ue.Class.md)

___

### EventSignatureName

• **EventSignatureName**: `string`

___

### FunctionFlags

• **FunctionFlags**: `number`

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[NodeComment](ue_ue.K2Node_EditablePinBase.md#nodecomment)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[NodeGuid](ue_ue.K2Node_EditablePinBase.md#nodeguid)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[NodeHeight](ue_ue.K2Node_EditablePinBase.md#nodeheight)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[NodePosX](ue_ue.K2Node_EditablePinBase.md#nodeposx)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[NodePosY](ue_ue.K2Node_EditablePinBase.md#nodeposy)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[NodeUpgradeMessage](ue_ue.K2Node_EditablePinBase.md#nodeupgrademessage)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[NodeWidth](ue_ue.K2Node_EditablePinBase.md#nodewidth)

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[__tid_EdGraphNode__](ue_ue.K2Node_EditablePinBase.md#__tid_edgraphnode__)

___

### \_\_tid\_K2Node\_EditablePinBase\_\_

• **\_\_tid\_K2Node\_EditablePinBase\_\_**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[__tid_K2Node_EditablePinBase__](ue_ue.K2Node_EditablePinBase.md#__tid_k2node_editablepinbase__)

___

### \_\_tid\_K2Node\_Event\_\_

• **\_\_tid\_K2Node\_Event\_\_**: `boolean`

___

### \_\_tid\_K2Node\_\_

• **\_\_tid\_K2Node\_\_**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[__tid_K2Node__](ue_ue.K2Node_EditablePinBase.md#__tid_k2node__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[__tid_Object__](ue_ue.K2Node_EditablePinBase.md#__tid_object__)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bCanRenameNode](ue_ue.K2Node_EditablePinBase.md#bcanrenamenode)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bCanResizeNode](ue_ue.K2Node_EditablePinBase.md#bcanresizenode)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bCommentBubbleMakeVisible](ue_ue.K2Node_EditablePinBase.md#bcommentbubblemakevisible)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bCommentBubblePinned](ue_ue.K2Node_EditablePinBase.md#bcommentbubblepinned)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bCommentBubbleVisible](ue_ue.K2Node_EditablePinBase.md#bcommentbubblevisible)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bDisplayAsDisabled](ue_ue.K2Node_EditablePinBase.md#bdisplayasdisabled)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bHasCompilerMessage](ue_ue.K2Node_EditablePinBase.md#bhascompilermessage)

___

### bInternalEvent

• **bInternalEvent**: `boolean`

___

### bIsEditable

• **bIsEditable**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bIsEditable](ue_ue.K2Node_EditablePinBase.md#biseditable)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bIsNodeEnabled](ue_ue.K2Node_EditablePinBase.md#bisnodeenabled)

___

### bOverrideFunction

• **bOverrideFunction**: `boolean`

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bUserSetEnabledState](ue_ue.K2Node_EditablePinBase.md#busersetenabledstate)

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

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[CreateDefaultSubobject](ue_ue.K2Node_EditablePinBase.md#createdefaultsubobject)

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

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[ExecuteUbergraph](ue_ue.K2Node_EditablePinBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[GetClass](ue_ue.K2Node_EditablePinBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[GetName](ue_ue.K2Node_EditablePinBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[GetOuter](ue_ue.K2Node_EditablePinBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[GetWorld](ue_ue.K2Node_EditablePinBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`K2Node_Event`](ue_ue.K2Node_Event.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`K2Node_Event`](ue_ue.K2Node_Event.md)

#### Overrides

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[Find](ue_ue.K2Node_EditablePinBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`K2Node_Event`](ue_ue.K2Node_Event.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`K2Node_Event`](ue_ue.K2Node_Event.md)

#### Overrides

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[Load](ue_ue.K2Node_EditablePinBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[StaticClass](ue_ue.K2Node_EditablePinBase.md#staticclass)
