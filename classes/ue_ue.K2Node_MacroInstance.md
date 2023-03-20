[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / K2Node\_MacroInstance

# Class: K2Node\_MacroInstance

[ue/ue](../modules/ue_ue.md).K2Node_MacroInstance

## Hierarchy

- [`K2Node_Tunnel`](ue_ue.K2Node_Tunnel.md)

  ↳ **`K2Node_MacroInstance`**

## Table of contents

### Constructors

- [constructor](ue_ue.K2Node_MacroInstance.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.K2Node_MacroInstance.md#advancedpindisplay)
- [DeprecatedPins](ue_ue.K2Node_MacroInstance.md#deprecatedpins)
- [EnabledState](ue_ue.K2Node_MacroInstance.md#enabledstate)
- [ErrorMsg](ue_ue.K2Node_MacroInstance.md#errormsg)
- [ErrorType](ue_ue.K2Node_MacroInstance.md#errortype)
- [InputSinkNode](ue_ue.K2Node_MacroInstance.md#inputsinknode)
- [MacroGraph](ue_ue.K2Node_MacroInstance.md#macrograph)
- [MacroGraphReference](ue_ue.K2Node_MacroInstance.md#macrographreference)
- [MetaData](ue_ue.K2Node_MacroInstance.md#metadata)
- [NodeComment](ue_ue.K2Node_MacroInstance.md#nodecomment)
- [NodeGuid](ue_ue.K2Node_MacroInstance.md#nodeguid)
- [NodeHeight](ue_ue.K2Node_MacroInstance.md#nodeheight)
- [NodePosX](ue_ue.K2Node_MacroInstance.md#nodeposx)
- [NodePosY](ue_ue.K2Node_MacroInstance.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.K2Node_MacroInstance.md#nodeupgrademessage)
- [NodeWidth](ue_ue.K2Node_MacroInstance.md#nodewidth)
- [OutputSourceNode](ue_ue.K2Node_MacroInstance.md#outputsourcenode)
- [ResolvedWildcardType](ue_ue.K2Node_MacroInstance.md#resolvedwildcardtype)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.K2Node_MacroInstance.md#__tid_edgraphnode__)
- [\_\_tid\_K2Node\_EditablePinBase\_\_](ue_ue.K2Node_MacroInstance.md#__tid_k2node_editablepinbase__)
- [\_\_tid\_K2Node\_MacroInstance\_\_](ue_ue.K2Node_MacroInstance.md#__tid_k2node_macroinstance__)
- [\_\_tid\_K2Node\_Tunnel\_\_](ue_ue.K2Node_MacroInstance.md#__tid_k2node_tunnel__)
- [\_\_tid\_K2Node\_\_](ue_ue.K2Node_MacroInstance.md#__tid_k2node__)
- [\_\_tid\_Object\_\_](ue_ue.K2Node_MacroInstance.md#__tid_object__)
- [bCanHaveInputs](ue_ue.K2Node_MacroInstance.md#bcanhaveinputs)
- [bCanHaveOutputs](ue_ue.K2Node_MacroInstance.md#bcanhaveoutputs)
- [bCanRenameNode](ue_ue.K2Node_MacroInstance.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.K2Node_MacroInstance.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.K2Node_MacroInstance.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.K2Node_MacroInstance.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.K2Node_MacroInstance.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.K2Node_MacroInstance.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.K2Node_MacroInstance.md#bhascompilermessage)
- [bIsEditable](ue_ue.K2Node_MacroInstance.md#biseditable)
- [bIsNodeEnabled](ue_ue.K2Node_MacroInstance.md#bisnodeenabled)
- [bUserSetEnabledState](ue_ue.K2Node_MacroInstance.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.K2Node_MacroInstance.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.K2Node_MacroInstance.md#executeubergraph)
- [GetClass](ue_ue.K2Node_MacroInstance.md#getclass)
- [GetName](ue_ue.K2Node_MacroInstance.md#getname)
- [GetOuter](ue_ue.K2Node_MacroInstance.md#getouter)
- [GetWorld](ue_ue.K2Node_MacroInstance.md#getworld)
- [Find](ue_ue.K2Node_MacroInstance.md#find)
- [Load](ue_ue.K2Node_MacroInstance.md#load)
- [StaticClass](ue_ue.K2Node_MacroInstance.md#staticclass)

## Constructors

### constructor

• **new K2Node_MacroInstance**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[constructor](ue_ue.K2Node_Tunnel.md#constructor)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[AdvancedPinDisplay](ue_ue.K2Node_Tunnel.md#advancedpindisplay)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[DeprecatedPins](ue_ue.K2Node_Tunnel.md#deprecatedpins)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[EnabledState](ue_ue.K2Node_Tunnel.md#enabledstate)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[ErrorMsg](ue_ue.K2Node_Tunnel.md#errormsg)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[ErrorType](ue_ue.K2Node_Tunnel.md#errortype)

___

### InputSinkNode

• **InputSinkNode**: [`K2Node_Tunnel`](ue_ue.K2Node_Tunnel.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[InputSinkNode](ue_ue.K2Node_Tunnel.md#inputsinknode)

___

### MacroGraph

• **MacroGraph**: [`EdGraph`](ue_ue.EdGraph.md)

___

### MacroGraphReference

• **MacroGraphReference**: [`GraphReference`](ue_ue.GraphReference.md)

___

### MetaData

• **MetaData**: [`KismetUserDeclaredFunctionMetadata`](ue_ue.KismetUserDeclaredFunctionMetadata.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[MetaData](ue_ue.K2Node_Tunnel.md#metadata)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[NodeComment](ue_ue.K2Node_Tunnel.md#nodecomment)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[NodeGuid](ue_ue.K2Node_Tunnel.md#nodeguid)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[NodeHeight](ue_ue.K2Node_Tunnel.md#nodeheight)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[NodePosX](ue_ue.K2Node_Tunnel.md#nodeposx)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[NodePosY](ue_ue.K2Node_Tunnel.md#nodeposy)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[NodeUpgradeMessage](ue_ue.K2Node_Tunnel.md#nodeupgrademessage)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[NodeWidth](ue_ue.K2Node_Tunnel.md#nodewidth)

___

### OutputSourceNode

• **OutputSourceNode**: [`K2Node_Tunnel`](ue_ue.K2Node_Tunnel.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[OutputSourceNode](ue_ue.K2Node_Tunnel.md#outputsourcenode)

___

### ResolvedWildcardType

• **ResolvedWildcardType**: [`EdGraphPinType`](ue_ue.EdGraphPinType.md)

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[__tid_EdGraphNode__](ue_ue.K2Node_Tunnel.md#__tid_edgraphnode__)

___

### \_\_tid\_K2Node\_EditablePinBase\_\_

• **\_\_tid\_K2Node\_EditablePinBase\_\_**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[__tid_K2Node_EditablePinBase__](ue_ue.K2Node_Tunnel.md#__tid_k2node_editablepinbase__)

___

### \_\_tid\_K2Node\_MacroInstance\_\_

• **\_\_tid\_K2Node\_MacroInstance\_\_**: `boolean`

___

### \_\_tid\_K2Node\_Tunnel\_\_

• **\_\_tid\_K2Node\_Tunnel\_\_**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[__tid_K2Node_Tunnel__](ue_ue.K2Node_Tunnel.md#__tid_k2node_tunnel__)

___

### \_\_tid\_K2Node\_\_

• **\_\_tid\_K2Node\_\_**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[__tid_K2Node__](ue_ue.K2Node_Tunnel.md#__tid_k2node__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[__tid_Object__](ue_ue.K2Node_Tunnel.md#__tid_object__)

___

### bCanHaveInputs

• **bCanHaveInputs**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bCanHaveInputs](ue_ue.K2Node_Tunnel.md#bcanhaveinputs)

___

### bCanHaveOutputs

• **bCanHaveOutputs**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bCanHaveOutputs](ue_ue.K2Node_Tunnel.md#bcanhaveoutputs)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bCanRenameNode](ue_ue.K2Node_Tunnel.md#bcanrenamenode)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bCanResizeNode](ue_ue.K2Node_Tunnel.md#bcanresizenode)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bCommentBubbleMakeVisible](ue_ue.K2Node_Tunnel.md#bcommentbubblemakevisible)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bCommentBubblePinned](ue_ue.K2Node_Tunnel.md#bcommentbubblepinned)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bCommentBubbleVisible](ue_ue.K2Node_Tunnel.md#bcommentbubblevisible)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bDisplayAsDisabled](ue_ue.K2Node_Tunnel.md#bdisplayasdisabled)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bHasCompilerMessage](ue_ue.K2Node_Tunnel.md#bhascompilermessage)

___

### bIsEditable

• **bIsEditable**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bIsEditable](ue_ue.K2Node_Tunnel.md#biseditable)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bIsNodeEnabled](ue_ue.K2Node_Tunnel.md#bisnodeenabled)

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[bUserSetEnabledState](ue_ue.K2Node_Tunnel.md#busersetenabledstate)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[GetClass](ue_ue.K2Node_Tunnel.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[GetName](ue_ue.K2Node_Tunnel.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[GetOuter](ue_ue.K2Node_Tunnel.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[GetWorld](ue_ue.K2Node_Tunnel.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`K2Node_MacroInstance`](ue_ue.K2Node_MacroInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`K2Node_MacroInstance`](ue_ue.K2Node_MacroInstance.md)

#### Overrides

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[Find](ue_ue.K2Node_Tunnel.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`K2Node_MacroInstance`](ue_ue.K2Node_MacroInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`K2Node_MacroInstance`](ue_ue.K2Node_MacroInstance.md)

#### Overrides

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[Load](ue_ue.K2Node_Tunnel.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[K2Node_Tunnel](ue_ue.K2Node_Tunnel.md).[StaticClass](ue_ue.K2Node_Tunnel.md#staticclass)
