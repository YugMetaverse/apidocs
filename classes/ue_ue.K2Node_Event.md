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

#### Defined in

[ue/ue.d.ts:40717](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40717)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[AdvancedPinDisplay](ue_ue.K2Node_EditablePinBase.md#advancedpindisplay)

#### Defined in

[ue/ue.d.ts:1067](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1067)

___

### CustomFunctionName

• **CustomFunctionName**: `string`

#### Defined in

[ue/ue.d.ts:40723](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40723)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[DeprecatedPins](ue_ue.K2Node_EditablePinBase.md#deprecatedpins)

#### Defined in

[ue/ue.d.ts:1062](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1062)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[EnabledState](ue_ue.K2Node_EditablePinBase.md#enabledstate)

#### Defined in

[ue/ue.d.ts:1068](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1068)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[ErrorMsg](ue_ue.K2Node_EditablePinBase.md#errormsg)

#### Defined in

[ue/ue.d.ts:1081](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1081)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[ErrorType](ue_ue.K2Node_EditablePinBase.md#errortype)

#### Defined in

[ue/ue.d.ts:1080](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1080)

___

### EventReference

• **EventReference**: [`MemberReference`](ue_ue.MemberReference.md)

#### Defined in

[ue/ue.d.ts:40720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40720)

___

### EventSignatureClass

• **EventSignatureClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:40719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40719)

___

### EventSignatureName

• **EventSignatureName**: `string`

#### Defined in

[ue/ue.d.ts:40718](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40718)

___

### FunctionFlags

• **FunctionFlags**: `number`

#### Defined in

[ue/ue.d.ts:40724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40724)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[NodeComment](ue_ue.K2Node_EditablePinBase.md#nodecomment)

#### Defined in

[ue/ue.d.ts:1079](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1079)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[NodeGuid](ue_ue.K2Node_EditablePinBase.md#nodeguid)

#### Defined in

[ue/ue.d.ts:1082](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1082)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[NodeHeight](ue_ue.K2Node_EditablePinBase.md#nodeheight)

#### Defined in

[ue/ue.d.ts:1066](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1066)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[NodePosX](ue_ue.K2Node_EditablePinBase.md#nodeposx)

#### Defined in

[ue/ue.d.ts:1063](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1063)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[NodePosY](ue_ue.K2Node_EditablePinBase.md#nodeposy)

#### Defined in

[ue/ue.d.ts:1064](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1064)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[NodeUpgradeMessage](ue_ue.K2Node_EditablePinBase.md#nodeupgrademessage)

#### Defined in

[ue/ue.d.ts:1078](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1078)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[NodeWidth](ue_ue.K2Node_EditablePinBase.md#nodewidth)

#### Defined in

[ue/ue.d.ts:1065](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1065)

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[__tid_EdGraphNode__](ue_ue.K2Node_EditablePinBase.md#__tid_edgraphnode__)

#### Defined in

[ue/ue.d.ts:1087](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1087)

___

### \_\_tid\_K2Node\_EditablePinBase\_\_

• **\_\_tid\_K2Node\_EditablePinBase\_\_**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[__tid_K2Node_EditablePinBase__](ue_ue.K2Node_EditablePinBase.md#__tid_k2node_editablepinbase__)

#### Defined in

[ue/ue.d.ts:40713](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40713)

___

### \_\_tid\_K2Node\_Event\_\_

• **\_\_tid\_K2Node\_Event\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:40729](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40729)

___

### \_\_tid\_K2Node\_\_

• **\_\_tid\_K2Node\_\_**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[__tid_K2Node__](ue_ue.K2Node_EditablePinBase.md#__tid_k2node__)

#### Defined in

[ue/ue.d.ts:16749](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16749)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[__tid_Object__](ue_ue.K2Node_EditablePinBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bCanRenameNode](ue_ue.K2Node_EditablePinBase.md#bcanrenamenode)

#### Defined in

[ue/ue.d.ts:1077](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1077)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bCanResizeNode](ue_ue.K2Node_EditablePinBase.md#bcanresizenode)

#### Defined in

[ue/ue.d.ts:1072](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1072)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bCommentBubbleMakeVisible](ue_ue.K2Node_EditablePinBase.md#bcommentbubblemakevisible)

#### Defined in

[ue/ue.d.ts:1076](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1076)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bCommentBubblePinned](ue_ue.K2Node_EditablePinBase.md#bcommentbubblepinned)

#### Defined in

[ue/ue.d.ts:1074](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1074)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bCommentBubbleVisible](ue_ue.K2Node_EditablePinBase.md#bcommentbubblevisible)

#### Defined in

[ue/ue.d.ts:1075](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1075)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bDisplayAsDisabled](ue_ue.K2Node_EditablePinBase.md#bdisplayasdisabled)

#### Defined in

[ue/ue.d.ts:1069](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1069)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bHasCompilerMessage](ue_ue.K2Node_EditablePinBase.md#bhascompilermessage)

#### Defined in

[ue/ue.d.ts:1073](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1073)

___

### bInternalEvent

• **bInternalEvent**: `boolean`

#### Defined in

[ue/ue.d.ts:40722](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40722)

___

### bIsEditable

• **bIsEditable**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bIsEditable](ue_ue.K2Node_EditablePinBase.md#biseditable)

#### Defined in

[ue/ue.d.ts:40708](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40708)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bIsNodeEnabled](ue_ue.K2Node_EditablePinBase.md#bisnodeenabled)

#### Defined in

[ue/ue.d.ts:1071](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1071)

___

### bOverrideFunction

• **bOverrideFunction**: `boolean`

#### Defined in

[ue/ue.d.ts:40721](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40721)

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[bUserSetEnabledState](ue_ue.K2Node_EditablePinBase.md#busersetenabledstate)

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

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[CreateDefaultSubobject](ue_ue.K2Node_EditablePinBase.md#createdefaultsubobject)

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

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[ExecuteUbergraph](ue_ue.K2Node_EditablePinBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[GetClass](ue_ue.K2Node_EditablePinBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[GetName](ue_ue.K2Node_EditablePinBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[GetOuter](ue_ue.K2Node_EditablePinBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[GetWorld](ue_ue.K2Node_EditablePinBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:40726](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40726)

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

#### Defined in

[ue/ue.d.ts:40727](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40727)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[K2Node_EditablePinBase](ue_ue.K2Node_EditablePinBase.md).[StaticClass](ue_ue.K2Node_EditablePinBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:40725](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40725)
