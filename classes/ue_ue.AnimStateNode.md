[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimStateNode

# Class: AnimStateNode

[ue/ue](../modules/ue_ue.md).AnimStateNode

## Hierarchy

- [`AnimStateNodeBase`](ue_ue.AnimStateNodeBase.md)

  ↳ **`AnimStateNode`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimStateNode.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.AnimStateNode.md#advancedpindisplay)
- [BoundGraph](ue_ue.AnimStateNode.md#boundgraph)
- [DeprecatedPins](ue_ue.AnimStateNode.md#deprecatedpins)
- [EnabledState](ue_ue.AnimStateNode.md#enabledstate)
- [ErrorMsg](ue_ue.AnimStateNode.md#errormsg)
- [ErrorType](ue_ue.AnimStateNode.md#errortype)
- [NodeComment](ue_ue.AnimStateNode.md#nodecomment)
- [NodeGuid](ue_ue.AnimStateNode.md#nodeguid)
- [NodeHeight](ue_ue.AnimStateNode.md#nodeheight)
- [NodePosX](ue_ue.AnimStateNode.md#nodeposx)
- [NodePosY](ue_ue.AnimStateNode.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.AnimStateNode.md#nodeupgrademessage)
- [NodeWidth](ue_ue.AnimStateNode.md#nodewidth)
- [StateEntered](ue_ue.AnimStateNode.md#stateentered)
- [StateFullyBlended](ue_ue.AnimStateNode.md#statefullyblended)
- [StateLeft](ue_ue.AnimStateNode.md#stateleft)
- [StateType](ue_ue.AnimStateNode.md#statetype)
- [\_\_tid\_AnimStateNodeBase\_\_](ue_ue.AnimStateNode.md#__tid_animstatenodebase__)
- [\_\_tid\_AnimStateNode\_\_](ue_ue.AnimStateNode.md#__tid_animstatenode__)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.AnimStateNode.md#__tid_edgraphnode__)
- [\_\_tid\_Object\_\_](ue_ue.AnimStateNode.md#__tid_object__)
- [bAlwaysResetOnEntry](ue_ue.AnimStateNode.md#balwaysresetonentry)
- [bCanRenameNode](ue_ue.AnimStateNode.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.AnimStateNode.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.AnimStateNode.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.AnimStateNode.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.AnimStateNode.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.AnimStateNode.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.AnimStateNode.md#bhascompilermessage)
- [bIsNodeEnabled](ue_ue.AnimStateNode.md#bisnodeenabled)
- [bUserSetEnabledState](ue_ue.AnimStateNode.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimStateNode.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimStateNode.md#executeubergraph)
- [GetClass](ue_ue.AnimStateNode.md#getclass)
- [GetName](ue_ue.AnimStateNode.md#getname)
- [GetOuter](ue_ue.AnimStateNode.md#getouter)
- [GetWorld](ue_ue.AnimStateNode.md#getworld)
- [Find](ue_ue.AnimStateNode.md#find)
- [Load](ue_ue.AnimStateNode.md#load)
- [StaticClass](ue_ue.AnimStateNode.md#staticclass)

## Constructors

### constructor

• **new AnimStateNode**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[constructor](ue_ue.AnimStateNodeBase.md#constructor)

#### Defined in

[ue/ue.d.ts:20490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20490)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[AdvancedPinDisplay](ue_ue.AnimStateNodeBase.md#advancedpindisplay)

#### Defined in

[ue/ue.d.ts:1067](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1067)

___

### BoundGraph

• **BoundGraph**: [`EdGraph`](ue_ue.EdGraph.md)

#### Defined in

[ue/ue.d.ts:20491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20491)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[DeprecatedPins](ue_ue.AnimStateNodeBase.md#deprecatedpins)

#### Defined in

[ue/ue.d.ts:1062](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1062)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[EnabledState](ue_ue.AnimStateNodeBase.md#enabledstate)

#### Defined in

[ue/ue.d.ts:1068](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1068)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[ErrorMsg](ue_ue.AnimStateNodeBase.md#errormsg)

#### Defined in

[ue/ue.d.ts:1081](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1081)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[ErrorType](ue_ue.AnimStateNodeBase.md#errortype)

#### Defined in

[ue/ue.d.ts:1080](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1080)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodeComment](ue_ue.AnimStateNodeBase.md#nodecomment)

#### Defined in

[ue/ue.d.ts:1079](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1079)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodeGuid](ue_ue.AnimStateNodeBase.md#nodeguid)

#### Defined in

[ue/ue.d.ts:1082](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1082)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodeHeight](ue_ue.AnimStateNodeBase.md#nodeheight)

#### Defined in

[ue/ue.d.ts:1066](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1066)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodePosX](ue_ue.AnimStateNodeBase.md#nodeposx)

#### Defined in

[ue/ue.d.ts:1063](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1063)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodePosY](ue_ue.AnimStateNodeBase.md#nodeposy)

#### Defined in

[ue/ue.d.ts:1064](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1064)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodeUpgradeMessage](ue_ue.AnimStateNodeBase.md#nodeupgrademessage)

#### Defined in

[ue/ue.d.ts:1078](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1078)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[NodeWidth](ue_ue.AnimStateNodeBase.md#nodewidth)

#### Defined in

[ue/ue.d.ts:1065](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1065)

___

### StateEntered

• **StateEntered**: [`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)

#### Defined in

[ue/ue.d.ts:20493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20493)

___

### StateFullyBlended

• **StateFullyBlended**: [`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)

#### Defined in

[ue/ue.d.ts:20495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20495)

___

### StateLeft

• **StateLeft**: [`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)

#### Defined in

[ue/ue.d.ts:20494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20494)

___

### StateType

• **StateType**: [`EAnimStateType`](../enums/ue_ue.EAnimStateType.md)

#### Defined in

[ue/ue.d.ts:20492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20492)

___

### \_\_tid\_AnimStateNodeBase\_\_

• **\_\_tid\_AnimStateNodeBase\_\_**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[__tid_AnimStateNodeBase__](ue_ue.AnimStateNodeBase.md#__tid_animstatenodebase__)

#### Defined in

[ue/ue.d.ts:20466](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20466)

___

### \_\_tid\_AnimStateNode\_\_

• **\_\_tid\_AnimStateNode\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:20501](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20501)

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[__tid_EdGraphNode__](ue_ue.AnimStateNodeBase.md#__tid_edgraphnode__)

#### Defined in

[ue/ue.d.ts:1087](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1087)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[__tid_Object__](ue_ue.AnimStateNodeBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAlwaysResetOnEntry

• **bAlwaysResetOnEntry**: `boolean`

#### Defined in

[ue/ue.d.ts:20496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20496)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bCanRenameNode](ue_ue.AnimStateNodeBase.md#bcanrenamenode)

#### Defined in

[ue/ue.d.ts:1077](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1077)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bCanResizeNode](ue_ue.AnimStateNodeBase.md#bcanresizenode)

#### Defined in

[ue/ue.d.ts:1072](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1072)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bCommentBubbleMakeVisible](ue_ue.AnimStateNodeBase.md#bcommentbubblemakevisible)

#### Defined in

[ue/ue.d.ts:1076](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1076)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bCommentBubblePinned](ue_ue.AnimStateNodeBase.md#bcommentbubblepinned)

#### Defined in

[ue/ue.d.ts:1074](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1074)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bCommentBubbleVisible](ue_ue.AnimStateNodeBase.md#bcommentbubblevisible)

#### Defined in

[ue/ue.d.ts:1075](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1075)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bDisplayAsDisabled](ue_ue.AnimStateNodeBase.md#bdisplayasdisabled)

#### Defined in

[ue/ue.d.ts:1069](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1069)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bHasCompilerMessage](ue_ue.AnimStateNodeBase.md#bhascompilermessage)

#### Defined in

[ue/ue.d.ts:1073](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1073)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bIsNodeEnabled](ue_ue.AnimStateNodeBase.md#bisnodeenabled)

#### Defined in

[ue/ue.d.ts:1071](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1071)

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[bUserSetEnabledState](ue_ue.AnimStateNodeBase.md#busersetenabledstate)

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

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[CreateDefaultSubobject](ue_ue.AnimStateNodeBase.md#createdefaultsubobject)

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

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[ExecuteUbergraph](ue_ue.AnimStateNodeBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[GetClass](ue_ue.AnimStateNodeBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[GetName](ue_ue.AnimStateNodeBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[GetOuter](ue_ue.AnimStateNodeBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[GetWorld](ue_ue.AnimStateNodeBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimStateNode`](ue_ue.AnimStateNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimStateNode`](ue_ue.AnimStateNode.md)

#### Overrides

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[Find](ue_ue.AnimStateNodeBase.md#find)

#### Defined in

[ue/ue.d.ts:20498](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20498)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimStateNode`](ue_ue.AnimStateNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimStateNode`](ue_ue.AnimStateNode.md)

#### Overrides

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[Load](ue_ue.AnimStateNodeBase.md#load)

#### Defined in

[ue/ue.d.ts:20499](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20499)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimStateNodeBase](ue_ue.AnimStateNodeBase.md).[StaticClass](ue_ue.AnimStateNodeBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:20497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20497)
