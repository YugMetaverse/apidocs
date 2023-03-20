[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / K2Node\_Composite

# Class: K2Node\_Composite

[ue/ue](../modules/ue_ue.md).K2Node_Composite

## Hierarchy

- [`K2Node_Tunnel`](ue_ue.K2Node_Tunnel.md)

  ↳ **`K2Node_Composite`**

  ↳↳ [`K2Node_MathExpression`](ue_ue.K2Node_MathExpression.md)

## Table of contents

### Constructors

- [constructor](ue_ue.K2Node_Composite.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.K2Node_Composite.md#advancedpindisplay)
- [BoundGraph](ue_ue.K2Node_Composite.md#boundgraph)
- [DeprecatedPins](ue_ue.K2Node_Composite.md#deprecatedpins)
- [EnabledState](ue_ue.K2Node_Composite.md#enabledstate)
- [ErrorMsg](ue_ue.K2Node_Composite.md#errormsg)
- [ErrorType](ue_ue.K2Node_Composite.md#errortype)
- [InputSinkNode](ue_ue.K2Node_Composite.md#inputsinknode)
- [MetaData](ue_ue.K2Node_Composite.md#metadata)
- [NodeComment](ue_ue.K2Node_Composite.md#nodecomment)
- [NodeGuid](ue_ue.K2Node_Composite.md#nodeguid)
- [NodeHeight](ue_ue.K2Node_Composite.md#nodeheight)
- [NodePosX](ue_ue.K2Node_Composite.md#nodeposx)
- [NodePosY](ue_ue.K2Node_Composite.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.K2Node_Composite.md#nodeupgrademessage)
- [NodeWidth](ue_ue.K2Node_Composite.md#nodewidth)
- [OutputSourceNode](ue_ue.K2Node_Composite.md#outputsourcenode)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.K2Node_Composite.md#__tid_edgraphnode__)
- [\_\_tid\_K2Node\_Composite\_\_](ue_ue.K2Node_Composite.md#__tid_k2node_composite__)
- [\_\_tid\_K2Node\_EditablePinBase\_\_](ue_ue.K2Node_Composite.md#__tid_k2node_editablepinbase__)
- [\_\_tid\_K2Node\_Tunnel\_\_](ue_ue.K2Node_Composite.md#__tid_k2node_tunnel__)
- [\_\_tid\_K2Node\_\_](ue_ue.K2Node_Composite.md#__tid_k2node__)
- [\_\_tid\_Object\_\_](ue_ue.K2Node_Composite.md#__tid_object__)
- [bCanHaveInputs](ue_ue.K2Node_Composite.md#bcanhaveinputs)
- [bCanHaveOutputs](ue_ue.K2Node_Composite.md#bcanhaveoutputs)
- [bCanRenameNode](ue_ue.K2Node_Composite.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.K2Node_Composite.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.K2Node_Composite.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.K2Node_Composite.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.K2Node_Composite.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.K2Node_Composite.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.K2Node_Composite.md#bhascompilermessage)
- [bIsEditable](ue_ue.K2Node_Composite.md#biseditable)
- [bIsNodeEnabled](ue_ue.K2Node_Composite.md#bisnodeenabled)
- [bUserSetEnabledState](ue_ue.K2Node_Composite.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.K2Node_Composite.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.K2Node_Composite.md#executeubergraph)
- [GetClass](ue_ue.K2Node_Composite.md#getclass)
- [GetName](ue_ue.K2Node_Composite.md#getname)
- [GetOuter](ue_ue.K2Node_Composite.md#getouter)
- [GetWorld](ue_ue.K2Node_Composite.md#getworld)
- [Find](ue_ue.K2Node_Composite.md#find)
- [Load](ue_ue.K2Node_Composite.md#load)
- [StaticClass](ue_ue.K2Node_Composite.md#staticclass)

## Constructors

### constructor

• **new K2Node_Composite**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[constructor](ue_ue.K2Node_Tunnel.md#constructor)

#### Defined in

[ue/ue.d.ts:41073](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L41073)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[AdvancedPinDisplay](ue_ue.K2Node_Tunnel.md#advancedpindisplay)

#### Defined in

[ue/ue.d.ts:1067](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1067)

___

### BoundGraph

• **BoundGraph**: [`EdGraph`](ue_ue.EdGraph.md)

#### Defined in

[ue/ue.d.ts:41074](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L41074)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[DeprecatedPins](ue_ue.K2Node_Tunnel.md#deprecatedpins)

#### Defined in

[ue/ue.d.ts:1062](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1062)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[EnabledState](ue_ue.K2Node_Tunnel.md#enabledstate)

#### Defined in

[ue/ue.d.ts:1068](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1068)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[ErrorMsg](ue_ue.K2Node_Tunnel.md#errormsg)

#### Defined in

[ue/ue.d.ts:1081](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1081)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[ErrorType](ue_ue.K2Node_Tunnel.md#errortype)

#### Defined in

[ue/ue.d.ts:1080](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1080)

___

### InputSinkNode

• **InputSinkNode**: [`K2Node_Tunnel`](ue_ue.K2Node_Tunnel.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[InputSinkNode](ue_ue.K2Node_Tunnel.md#inputsinknode)

#### Defined in

[ue/ue.d.ts:41061](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L41061)

___

### MetaData

• **MetaData**: [`KismetUserDeclaredFunctionMetadata`](ue_ue.KismetUserDeclaredFunctionMetadata.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[MetaData](ue_ue.K2Node_Tunnel.md#metadata)

#### Defined in

[ue/ue.d.ts:41064](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L41064)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[NodeComment](ue_ue.K2Node_Tunnel.md#nodecomment)

#### Defined in

[ue/ue.d.ts:1079](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1079)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[NodeGuid](ue_ue.K2Node_Tunnel.md#nodeguid)

#### Defined in

[ue/ue.d.ts:1082](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1082)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[NodeHeight](ue_ue.K2Node_Tunnel.md#nodeheight)

#### Defined in

[ue/ue.d.ts:1066](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1066)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[NodePosX](ue_ue.K2Node_Tunnel.md#nodeposx)

#### Defined in

[ue/ue.d.ts:1063](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1063)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[NodePosY](ue_ue.K2Node_Tunnel.md#nodeposy)

#### Defined in

[ue/ue.d.ts:1064](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1064)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[NodeUpgradeMessage](ue_ue.K2Node_Tunnel.md#nodeupgrademessage)

#### Defined in

[ue/ue.d.ts:1078](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1078)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[NodeWidth](ue_ue.K2Node_Tunnel.md#nodewidth)

#### Defined in

[ue/ue.d.ts:1065](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1065)

___

### OutputSourceNode

• **OutputSourceNode**: [`K2Node_Tunnel`](ue_ue.K2Node_Tunnel.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[OutputSourceNode](ue_ue.K2Node_Tunnel.md#outputsourcenode)

#### Defined in

[ue/ue.d.ts:41060](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L41060)

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[__tid_EdGraphNode__](ue_ue.K2Node_Tunnel.md#__tid_edgraphnode__)

#### Defined in

[ue/ue.d.ts:1087](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1087)

___

### \_\_tid\_K2Node\_Composite\_\_

• **\_\_tid\_K2Node\_Composite\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:41079](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L41079)

___

### \_\_tid\_K2Node\_EditablePinBase\_\_

• **\_\_tid\_K2Node\_EditablePinBase\_\_**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[__tid_K2Node_EditablePinBase__](ue_ue.K2Node_Tunnel.md#__tid_k2node_editablepinbase__)

#### Defined in

[ue/ue.d.ts:40713](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40713)

___

### \_\_tid\_K2Node\_Tunnel\_\_

• **\_\_tid\_K2Node\_Tunnel\_\_**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[__tid_K2Node_Tunnel__](ue_ue.K2Node_Tunnel.md#__tid_k2node_tunnel__)

#### Defined in

[ue/ue.d.ts:41069](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L41069)

___

### \_\_tid\_K2Node\_\_

• **\_\_tid\_K2Node\_\_**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[__tid_K2Node__](ue_ue.K2Node_Tunnel.md#__tid_k2node__)

#### Defined in

[ue/ue.d.ts:16749](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16749)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[__tid_Object__](ue_ue.K2Node_Tunnel.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bCanHaveInputs

• **bCanHaveInputs**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bCanHaveInputs](ue_ue.K2Node_Tunnel.md#bcanhaveinputs)

#### Defined in

[ue/ue.d.ts:41062](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L41062)

___

### bCanHaveOutputs

• **bCanHaveOutputs**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bCanHaveOutputs](ue_ue.K2Node_Tunnel.md#bcanhaveoutputs)

#### Defined in

[ue/ue.d.ts:41063](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L41063)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bCanRenameNode](ue_ue.K2Node_Tunnel.md#bcanrenamenode)

#### Defined in

[ue/ue.d.ts:1077](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1077)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bCanResizeNode](ue_ue.K2Node_Tunnel.md#bcanresizenode)

#### Defined in

[ue/ue.d.ts:1072](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1072)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bCommentBubbleMakeVisible](ue_ue.K2Node_Tunnel.md#bcommentbubblemakevisible)

#### Defined in

[ue/ue.d.ts:1076](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1076)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bCommentBubblePinned](ue_ue.K2Node_Tunnel.md#bcommentbubblepinned)

#### Defined in

[ue/ue.d.ts:1074](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1074)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bCommentBubbleVisible](ue_ue.K2Node_Tunnel.md#bcommentbubblevisible)

#### Defined in

[ue/ue.d.ts:1075](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1075)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bDisplayAsDisabled](ue_ue.K2Node_Tunnel.md#bdisplayasdisabled)

#### Defined in

[ue/ue.d.ts:1069](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1069)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bHasCompilerMessage](ue_ue.K2Node_Tunnel.md#bhascompilermessage)

#### Defined in

[ue/ue.d.ts:1073](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1073)

___

### bIsEditable

• **bIsEditable**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bIsEditable](ue_ue.K2Node_Tunnel.md#biseditable)

#### Defined in

[ue/ue.d.ts:40708](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L40708)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bIsNodeEnabled](ue_ue.K2Node_Tunnel.md#bisnodeenabled)

#### Defined in

[ue/ue.d.ts:1071](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1071)

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bUserSetEnabledState](ue_ue.K2Node_Tunnel.md#busersetenabledstate)

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

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[CreateDefaultSubobject](ue_ue.K2Node_Tunnel.md#createdefaultsubobject)

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

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[ExecuteUbergraph](ue_ue.K2Node_Tunnel.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[GetClass](ue_ue.K2Node_Tunnel.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[GetName](ue_ue.K2Node_Tunnel.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[GetOuter](ue_ue.K2Node_Tunnel.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[GetWorld](ue_ue.K2Node_Tunnel.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`K2Node_Composite`](ue_ue.K2Node_Composite.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`K2Node_Composite`](ue_ue.K2Node_Composite.md)

#### Overrides

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[Find](ue_ue.K2Node_Tunnel.md#find)

#### Defined in

[ue/ue.d.ts:41076](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L41076)

___

### Load

▸ `Static` **Load**(`InName`): [`K2Node_Composite`](ue_ue.K2Node_Composite.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`K2Node_Composite`](ue_ue.K2Node_Composite.md)

#### Overrides

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[Load](ue_ue.K2Node_Tunnel.md#load)

#### Defined in

[ue/ue.d.ts:41077](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L41077)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[StaticClass](ue_ue.K2Node_Tunnel.md#staticclass)

#### Defined in

[ue/ue.d.ts:41075](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L41075)
