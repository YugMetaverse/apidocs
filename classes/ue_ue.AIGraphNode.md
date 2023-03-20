[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AIGraphNode

# Class: AIGraphNode

[ue/ue](../modules/ue_ue.md).AIGraphNode

## Hierarchy

- [`EdGraphNode`](ue_ue.EdGraphNode.md)

  ↳ **`AIGraphNode`**

  ↳↳ [`BehaviorTreeGraphNode`](ue_ue.BehaviorTreeGraphNode.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AIGraphNode.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.AIGraphNode.md#advancedpindisplay)
- [ClassData](ue_ue.AIGraphNode.md#classdata)
- [CopySubNodeIndex](ue_ue.AIGraphNode.md#copysubnodeindex)
- [DeprecatedPins](ue_ue.AIGraphNode.md#deprecatedpins)
- [EnabledState](ue_ue.AIGraphNode.md#enabledstate)
- [ErrorMessage](ue_ue.AIGraphNode.md#errormessage)
- [ErrorMsg](ue_ue.AIGraphNode.md#errormsg)
- [ErrorType](ue_ue.AIGraphNode.md#errortype)
- [NodeComment](ue_ue.AIGraphNode.md#nodecomment)
- [NodeGuid](ue_ue.AIGraphNode.md#nodeguid)
- [NodeHeight](ue_ue.AIGraphNode.md#nodeheight)
- [NodeInstance](ue_ue.AIGraphNode.md#nodeinstance)
- [NodePosX](ue_ue.AIGraphNode.md#nodeposx)
- [NodePosY](ue_ue.AIGraphNode.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.AIGraphNode.md#nodeupgrademessage)
- [NodeWidth](ue_ue.AIGraphNode.md#nodewidth)
- [ParentNode](ue_ue.AIGraphNode.md#parentnode)
- [SubNodes](ue_ue.AIGraphNode.md#subnodes)
- [\_\_tid\_AIGraphNode\_\_](ue_ue.AIGraphNode.md#__tid_aigraphnode__)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.AIGraphNode.md#__tid_edgraphnode__)
- [\_\_tid\_Object\_\_](ue_ue.AIGraphNode.md#__tid_object__)
- [bCanRenameNode](ue_ue.AIGraphNode.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.AIGraphNode.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.AIGraphNode.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.AIGraphNode.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.AIGraphNode.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.AIGraphNode.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.AIGraphNode.md#bhascompilermessage)
- [bIsNodeEnabled](ue_ue.AIGraphNode.md#bisnodeenabled)
- [bIsReadOnly](ue_ue.AIGraphNode.md#bisreadonly)
- [bIsSubNode](ue_ue.AIGraphNode.md#bissubnode)
- [bUserSetEnabledState](ue_ue.AIGraphNode.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.AIGraphNode.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AIGraphNode.md#executeubergraph)
- [GetClass](ue_ue.AIGraphNode.md#getclass)
- [GetName](ue_ue.AIGraphNode.md#getname)
- [GetOuter](ue_ue.AIGraphNode.md#getouter)
- [GetWorld](ue_ue.AIGraphNode.md#getworld)
- [Find](ue_ue.AIGraphNode.md#find)
- [Load](ue_ue.AIGraphNode.md#load)
- [StaticClass](ue_ue.AIGraphNode.md#staticclass)

## Constructors

### constructor

• **new AIGraphNode**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EdGraphNode](ue_ue.EdGraphNode.md).[constructor](ue_ue.EdGraphNode.md#constructor)

#### Defined in

[ue/ue.d.ts:15116](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15116)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[AdvancedPinDisplay](ue_ue.EdGraphNode.md#advancedpindisplay)

#### Defined in

[ue/ue.d.ts:1067](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1067)

___

### ClassData

• **ClassData**: [`GraphNodeClassData`](ue_ue.GraphNodeClassData.md)

#### Defined in

[ue/ue.d.ts:15117](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15117)

___

### CopySubNodeIndex

• **CopySubNodeIndex**: `number`

#### Defined in

[ue/ue.d.ts:15121](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15121)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[DeprecatedPins](ue_ue.EdGraphNode.md#deprecatedpins)

#### Defined in

[ue/ue.d.ts:1062](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1062)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[EnabledState](ue_ue.EdGraphNode.md#enabledstate)

#### Defined in

[ue/ue.d.ts:1068](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1068)

___

### ErrorMessage

• **ErrorMessage**: `string`

#### Defined in

[ue/ue.d.ts:15124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15124)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[ErrorMsg](ue_ue.EdGraphNode.md#errormsg)

#### Defined in

[ue/ue.d.ts:1081](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1081)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[ErrorType](ue_ue.EdGraphNode.md#errortype)

#### Defined in

[ue/ue.d.ts:1080](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1080)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[NodeComment](ue_ue.EdGraphNode.md#nodecomment)

#### Defined in

[ue/ue.d.ts:1079](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1079)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[NodeGuid](ue_ue.EdGraphNode.md#nodeguid)

#### Defined in

[ue/ue.d.ts:1082](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1082)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[NodeHeight](ue_ue.EdGraphNode.md#nodeheight)

#### Defined in

[ue/ue.d.ts:1066](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1066)

___

### NodeInstance

• **NodeInstance**: [`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:15118](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15118)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[NodePosX](ue_ue.EdGraphNode.md#nodeposx)

#### Defined in

[ue/ue.d.ts:1063](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1063)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[NodePosY](ue_ue.EdGraphNode.md#nodeposy)

#### Defined in

[ue/ue.d.ts:1064](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1064)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[NodeUpgradeMessage](ue_ue.EdGraphNode.md#nodeupgrademessage)

#### Defined in

[ue/ue.d.ts:1078](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1078)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[NodeWidth](ue_ue.EdGraphNode.md#nodewidth)

#### Defined in

[ue/ue.d.ts:1065](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1065)

___

### ParentNode

• **ParentNode**: [`AIGraphNode`](ue_ue.AIGraphNode.md)

#### Defined in

[ue/ue.d.ts:15119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15119)

___

### SubNodes

• **SubNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AIGraphNode`](ue_ue.AIGraphNode.md)\>

#### Defined in

[ue/ue.d.ts:15120](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15120)

___

### \_\_tid\_AIGraphNode\_\_

• **\_\_tid\_AIGraphNode\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15129)

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[__tid_EdGraphNode__](ue_ue.EdGraphNode.md#__tid_edgraphnode__)

#### Defined in

[ue/ue.d.ts:1087](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1087)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[__tid_Object__](ue_ue.EdGraphNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bCanRenameNode](ue_ue.EdGraphNode.md#bcanrenamenode)

#### Defined in

[ue/ue.d.ts:1077](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1077)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bCanResizeNode](ue_ue.EdGraphNode.md#bcanresizenode)

#### Defined in

[ue/ue.d.ts:1072](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1072)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bCommentBubbleMakeVisible](ue_ue.EdGraphNode.md#bcommentbubblemakevisible)

#### Defined in

[ue/ue.d.ts:1076](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1076)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bCommentBubblePinned](ue_ue.EdGraphNode.md#bcommentbubblepinned)

#### Defined in

[ue/ue.d.ts:1074](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1074)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bCommentBubbleVisible](ue_ue.EdGraphNode.md#bcommentbubblevisible)

#### Defined in

[ue/ue.d.ts:1075](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1075)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bDisplayAsDisabled](ue_ue.EdGraphNode.md#bdisplayasdisabled)

#### Defined in

[ue/ue.d.ts:1069](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1069)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bHasCompilerMessage](ue_ue.EdGraphNode.md#bhascompilermessage)

#### Defined in

[ue/ue.d.ts:1073](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1073)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bIsNodeEnabled](ue_ue.EdGraphNode.md#bisnodeenabled)

#### Defined in

[ue/ue.d.ts:1071](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1071)

___

### bIsReadOnly

• **bIsReadOnly**: `boolean`

#### Defined in

[ue/ue.d.ts:15122](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15122)

___

### bIsSubNode

• **bIsSubNode**: `boolean`

#### Defined in

[ue/ue.d.ts:15123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15123)

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bUserSetEnabledState](ue_ue.EdGraphNode.md#busersetenabledstate)

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

[EdGraphNode](ue_ue.EdGraphNode.md).[CreateDefaultSubobject](ue_ue.EdGraphNode.md#createdefaultsubobject)

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

[EdGraphNode](ue_ue.EdGraphNode.md).[ExecuteUbergraph](ue_ue.EdGraphNode.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[GetClass](ue_ue.EdGraphNode.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[GetName](ue_ue.EdGraphNode.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[GetOuter](ue_ue.EdGraphNode.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[GetWorld](ue_ue.EdGraphNode.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AIGraphNode`](ue_ue.AIGraphNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AIGraphNode`](ue_ue.AIGraphNode.md)

#### Overrides

[EdGraphNode](ue_ue.EdGraphNode.md).[Find](ue_ue.EdGraphNode.md#find)

#### Defined in

[ue/ue.d.ts:15126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15126)

___

### Load

▸ `Static` **Load**(`InName`): [`AIGraphNode`](ue_ue.AIGraphNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AIGraphNode`](ue_ue.AIGraphNode.md)

#### Overrides

[EdGraphNode](ue_ue.EdGraphNode.md).[Load](ue_ue.EdGraphNode.md#load)

#### Defined in

[ue/ue.d.ts:15127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15127)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EdGraphNode](ue_ue.EdGraphNode.md).[StaticClass](ue_ue.EdGraphNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:15125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15125)
