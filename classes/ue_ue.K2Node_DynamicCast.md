[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / K2Node\_DynamicCast

# Class: K2Node\_DynamicCast

[ue/ue](../modules/ue_ue.md).K2Node_DynamicCast

## Hierarchy

- [`K2Node`](ue_ue.K2Node.md)

  ↳ **`K2Node_DynamicCast`**

  ↳↳ [`K2Node_ClassDynamicCast`](ue_ue.K2Node_ClassDynamicCast.md)

## Table of contents

### Constructors

- [constructor](ue_ue.K2Node_DynamicCast.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.K2Node_DynamicCast.md#advancedpindisplay)
- [DeprecatedPins](ue_ue.K2Node_DynamicCast.md#deprecatedpins)
- [EnabledState](ue_ue.K2Node_DynamicCast.md#enabledstate)
- [ErrorMsg](ue_ue.K2Node_DynamicCast.md#errormsg)
- [ErrorType](ue_ue.K2Node_DynamicCast.md#errortype)
- [NodeComment](ue_ue.K2Node_DynamicCast.md#nodecomment)
- [NodeGuid](ue_ue.K2Node_DynamicCast.md#nodeguid)
- [NodeHeight](ue_ue.K2Node_DynamicCast.md#nodeheight)
- [NodePosX](ue_ue.K2Node_DynamicCast.md#nodeposx)
- [NodePosY](ue_ue.K2Node_DynamicCast.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.K2Node_DynamicCast.md#nodeupgrademessage)
- [NodeWidth](ue_ue.K2Node_DynamicCast.md#nodewidth)
- [TargetType](ue_ue.K2Node_DynamicCast.md#targettype)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.K2Node_DynamicCast.md#__tid_edgraphnode__)
- [\_\_tid\_K2Node\_DynamicCast\_\_](ue_ue.K2Node_DynamicCast.md#__tid_k2node_dynamiccast__)
- [\_\_tid\_K2Node\_\_](ue_ue.K2Node_DynamicCast.md#__tid_k2node__)
- [\_\_tid\_Object\_\_](ue_ue.K2Node_DynamicCast.md#__tid_object__)
- [bCanRenameNode](ue_ue.K2Node_DynamicCast.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.K2Node_DynamicCast.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.K2Node_DynamicCast.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.K2Node_DynamicCast.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.K2Node_DynamicCast.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.K2Node_DynamicCast.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.K2Node_DynamicCast.md#bhascompilermessage)
- [bIsNodeEnabled](ue_ue.K2Node_DynamicCast.md#bisnodeenabled)
- [bIsPureCast](ue_ue.K2Node_DynamicCast.md#bispurecast)
- [bUserSetEnabledState](ue_ue.K2Node_DynamicCast.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.K2Node_DynamicCast.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.K2Node_DynamicCast.md#executeubergraph)
- [GetClass](ue_ue.K2Node_DynamicCast.md#getclass)
- [GetName](ue_ue.K2Node_DynamicCast.md#getname)
- [GetOuter](ue_ue.K2Node_DynamicCast.md#getouter)
- [GetWorld](ue_ue.K2Node_DynamicCast.md#getworld)
- [Find](ue_ue.K2Node_DynamicCast.md#find)
- [Load](ue_ue.K2Node_DynamicCast.md#load)
- [StaticClass](ue_ue.K2Node_DynamicCast.md#staticclass)

## Constructors

### constructor

• **new K2Node_DynamicCast**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[K2Node](ue_ue.K2Node.md).[constructor](ue_ue.K2Node.md#constructor)

#### Defined in

[ue/ue.d.ts:40987](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L40987)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[K2Node](ue_ue.K2Node.md).[AdvancedPinDisplay](ue_ue.K2Node.md#advancedpindisplay)

#### Defined in

[ue/ue.d.ts:1067](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1067)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[K2Node](ue_ue.K2Node.md).[DeprecatedPins](ue_ue.K2Node.md#deprecatedpins)

#### Defined in

[ue/ue.d.ts:1062](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1062)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[K2Node](ue_ue.K2Node.md).[EnabledState](ue_ue.K2Node.md#enabledstate)

#### Defined in

[ue/ue.d.ts:1068](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1068)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[ErrorMsg](ue_ue.K2Node.md#errormsg)

#### Defined in

[ue/ue.d.ts:1081](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1081)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[ErrorType](ue_ue.K2Node.md#errortype)

#### Defined in

[ue/ue.d.ts:1080](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1080)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[NodeComment](ue_ue.K2Node.md#nodecomment)

#### Defined in

[ue/ue.d.ts:1079](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1079)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[K2Node](ue_ue.K2Node.md).[NodeGuid](ue_ue.K2Node.md#nodeguid)

#### Defined in

[ue/ue.d.ts:1082](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1082)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[NodeHeight](ue_ue.K2Node.md#nodeheight)

#### Defined in

[ue/ue.d.ts:1066](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1066)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[NodePosX](ue_ue.K2Node.md#nodeposx)

#### Defined in

[ue/ue.d.ts:1063](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1063)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[NodePosY](ue_ue.K2Node.md#nodeposy)

#### Defined in

[ue/ue.d.ts:1064](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1064)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[NodeUpgradeMessage](ue_ue.K2Node.md#nodeupgrademessage)

#### Defined in

[ue/ue.d.ts:1078](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1078)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[NodeWidth](ue_ue.K2Node.md#nodewidth)

#### Defined in

[ue/ue.d.ts:1065](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1065)

___

### TargetType

• **TargetType**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:40988](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L40988)

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[__tid_EdGraphNode__](ue_ue.K2Node.md#__tid_edgraphnode__)

#### Defined in

[ue/ue.d.ts:1087](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1087)

___

### \_\_tid\_K2Node\_DynamicCast\_\_

• **\_\_tid\_K2Node\_DynamicCast\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:40994](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L40994)

___

### \_\_tid\_K2Node\_\_

• **\_\_tid\_K2Node\_\_**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[__tid_K2Node__](ue_ue.K2Node.md#__tid_k2node__)

#### Defined in

[ue/ue.d.ts:16749](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16749)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[__tid_Object__](ue_ue.K2Node.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bCanRenameNode](ue_ue.K2Node.md#bcanrenamenode)

#### Defined in

[ue/ue.d.ts:1077](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1077)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bCanResizeNode](ue_ue.K2Node.md#bcanresizenode)

#### Defined in

[ue/ue.d.ts:1072](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1072)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bCommentBubbleMakeVisible](ue_ue.K2Node.md#bcommentbubblemakevisible)

#### Defined in

[ue/ue.d.ts:1076](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1076)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bCommentBubblePinned](ue_ue.K2Node.md#bcommentbubblepinned)

#### Defined in

[ue/ue.d.ts:1074](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1074)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bCommentBubbleVisible](ue_ue.K2Node.md#bcommentbubblevisible)

#### Defined in

[ue/ue.d.ts:1075](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1075)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bDisplayAsDisabled](ue_ue.K2Node.md#bdisplayasdisabled)

#### Defined in

[ue/ue.d.ts:1069](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1069)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bHasCompilerMessage](ue_ue.K2Node.md#bhascompilermessage)

#### Defined in

[ue/ue.d.ts:1073](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1073)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bIsNodeEnabled](ue_ue.K2Node.md#bisnodeenabled)

#### Defined in

[ue/ue.d.ts:1071](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1071)

___

### bIsPureCast

• **bIsPureCast**: `boolean`

#### Defined in

[ue/ue.d.ts:40989](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L40989)

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[bUserSetEnabledState](ue_ue.K2Node.md#busersetenabledstate)

#### Defined in

[ue/ue.d.ts:1070](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1070)

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

[K2Node](ue_ue.K2Node.md).[CreateDefaultSubobject](ue_ue.K2Node.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[K2Node](ue_ue.K2Node.md).[ExecuteUbergraph](ue_ue.K2Node.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[K2Node](ue_ue.K2Node.md).[GetClass](ue_ue.K2Node.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[K2Node](ue_ue.K2Node.md).[GetName](ue_ue.K2Node.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[K2Node](ue_ue.K2Node.md).[GetOuter](ue_ue.K2Node.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[K2Node](ue_ue.K2Node.md).[GetWorld](ue_ue.K2Node.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`K2Node_DynamicCast`](ue_ue.K2Node_DynamicCast.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`K2Node_DynamicCast`](ue_ue.K2Node_DynamicCast.md)

#### Overrides

[K2Node](ue_ue.K2Node.md).[Find](ue_ue.K2Node.md#find)

#### Defined in

[ue/ue.d.ts:40991](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L40991)

___

### Load

▸ `Static` **Load**(`InName`): [`K2Node_DynamicCast`](ue_ue.K2Node_DynamicCast.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`K2Node_DynamicCast`](ue_ue.K2Node_DynamicCast.md)

#### Overrides

[K2Node](ue_ue.K2Node.md).[Load](ue_ue.K2Node.md#load)

#### Defined in

[ue/ue.d.ts:40992](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L40992)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[K2Node](ue_ue.K2Node.md).[StaticClass](ue_ue.K2Node.md#staticclass)

#### Defined in

[ue/ue.d.ts:40990](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L40990)
