[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / K2Node\_GenericCreateObject

# Class: K2Node\_GenericCreateObject

[ue/ue](../modules/ue_ue.md).K2Node_GenericCreateObject

## Hierarchy

- [`K2Node_ConstructObjectFromClass`](ue_ue.K2Node_ConstructObjectFromClass.md)

  ↳ **`K2Node_GenericCreateObject`**

## Table of contents

### Constructors

- [constructor](ue_ue.K2Node_GenericCreateObject.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.K2Node_GenericCreateObject.md#advancedpindisplay)
- [DeprecatedPins](ue_ue.K2Node_GenericCreateObject.md#deprecatedpins)
- [EnabledState](ue_ue.K2Node_GenericCreateObject.md#enabledstate)
- [ErrorMsg](ue_ue.K2Node_GenericCreateObject.md#errormsg)
- [ErrorType](ue_ue.K2Node_GenericCreateObject.md#errortype)
- [NodeComment](ue_ue.K2Node_GenericCreateObject.md#nodecomment)
- [NodeGuid](ue_ue.K2Node_GenericCreateObject.md#nodeguid)
- [NodeHeight](ue_ue.K2Node_GenericCreateObject.md#nodeheight)
- [NodePosX](ue_ue.K2Node_GenericCreateObject.md#nodeposx)
- [NodePosY](ue_ue.K2Node_GenericCreateObject.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.K2Node_GenericCreateObject.md#nodeupgrademessage)
- [NodeWidth](ue_ue.K2Node_GenericCreateObject.md#nodewidth)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.K2Node_GenericCreateObject.md#__tid_edgraphnode__)
- [\_\_tid\_K2Node\_ConstructObjectFromClass\_\_](ue_ue.K2Node_GenericCreateObject.md#__tid_k2node_constructobjectfromclass__)
- [\_\_tid\_K2Node\_GenericCreateObject\_\_](ue_ue.K2Node_GenericCreateObject.md#__tid_k2node_genericcreateobject__)
- [\_\_tid\_K2Node\_\_](ue_ue.K2Node_GenericCreateObject.md#__tid_k2node__)
- [\_\_tid\_Object\_\_](ue_ue.K2Node_GenericCreateObject.md#__tid_object__)
- [bCanRenameNode](ue_ue.K2Node_GenericCreateObject.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.K2Node_GenericCreateObject.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.K2Node_GenericCreateObject.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.K2Node_GenericCreateObject.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.K2Node_GenericCreateObject.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.K2Node_GenericCreateObject.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.K2Node_GenericCreateObject.md#bhascompilermessage)
- [bIsNodeEnabled](ue_ue.K2Node_GenericCreateObject.md#bisnodeenabled)
- [bUserSetEnabledState](ue_ue.K2Node_GenericCreateObject.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.K2Node_GenericCreateObject.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.K2Node_GenericCreateObject.md#executeubergraph)
- [GetClass](ue_ue.K2Node_GenericCreateObject.md#getclass)
- [GetName](ue_ue.K2Node_GenericCreateObject.md#getname)
- [GetOuter](ue_ue.K2Node_GenericCreateObject.md#getouter)
- [GetWorld](ue_ue.K2Node_GenericCreateObject.md#getworld)
- [Find](ue_ue.K2Node_GenericCreateObject.md#find)
- [Load](ue_ue.K2Node_GenericCreateObject.md#load)
- [StaticClass](ue_ue.K2Node_GenericCreateObject.md#staticclass)

## Constructors

### constructor

• **new K2Node_GenericCreateObject**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[constructor](ue_ue.K2Node_ConstructObjectFromClass.md#constructor)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[AdvancedPinDisplay](ue_ue.K2Node_ConstructObjectFromClass.md#advancedpindisplay)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[DeprecatedPins](ue_ue.K2Node_ConstructObjectFromClass.md#deprecatedpins)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[EnabledState](ue_ue.K2Node_ConstructObjectFromClass.md#enabledstate)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[ErrorMsg](ue_ue.K2Node_ConstructObjectFromClass.md#errormsg)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[ErrorType](ue_ue.K2Node_ConstructObjectFromClass.md#errortype)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[NodeComment](ue_ue.K2Node_ConstructObjectFromClass.md#nodecomment)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[NodeGuid](ue_ue.K2Node_ConstructObjectFromClass.md#nodeguid)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[NodeHeight](ue_ue.K2Node_ConstructObjectFromClass.md#nodeheight)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[NodePosX](ue_ue.K2Node_ConstructObjectFromClass.md#nodeposx)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[NodePosY](ue_ue.K2Node_ConstructObjectFromClass.md#nodeposy)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[NodeUpgradeMessage](ue_ue.K2Node_ConstructObjectFromClass.md#nodeupgrademessage)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[NodeWidth](ue_ue.K2Node_ConstructObjectFromClass.md#nodewidth)

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[__tid_EdGraphNode__](ue_ue.K2Node_ConstructObjectFromClass.md#__tid_edgraphnode__)

___

### \_\_tid\_K2Node\_ConstructObjectFromClass\_\_

• **\_\_tid\_K2Node\_ConstructObjectFromClass\_\_**: `boolean`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[__tid_K2Node_ConstructObjectFromClass__](ue_ue.K2Node_ConstructObjectFromClass.md#__tid_k2node_constructobjectfromclass__)

___

### \_\_tid\_K2Node\_GenericCreateObject\_\_

• **\_\_tid\_K2Node\_GenericCreateObject\_\_**: `boolean`

___

### \_\_tid\_K2Node\_\_

• **\_\_tid\_K2Node\_\_**: `boolean`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[__tid_K2Node__](ue_ue.K2Node_ConstructObjectFromClass.md#__tid_k2node__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[__tid_Object__](ue_ue.K2Node_ConstructObjectFromClass.md#__tid_object__)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[bCanRenameNode](ue_ue.K2Node_ConstructObjectFromClass.md#bcanrenamenode)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[bCanResizeNode](ue_ue.K2Node_ConstructObjectFromClass.md#bcanresizenode)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[bCommentBubbleMakeVisible](ue_ue.K2Node_ConstructObjectFromClass.md#bcommentbubblemakevisible)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[bCommentBubblePinned](ue_ue.K2Node_ConstructObjectFromClass.md#bcommentbubblepinned)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[bCommentBubbleVisible](ue_ue.K2Node_ConstructObjectFromClass.md#bcommentbubblevisible)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[bDisplayAsDisabled](ue_ue.K2Node_ConstructObjectFromClass.md#bdisplayasdisabled)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[bHasCompilerMessage](ue_ue.K2Node_ConstructObjectFromClass.md#bhascompilermessage)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[bIsNodeEnabled](ue_ue.K2Node_ConstructObjectFromClass.md#bisnodeenabled)

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[bUserSetEnabledState](ue_ue.K2Node_ConstructObjectFromClass.md#busersetenabledstate)

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

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[CreateDefaultSubobject](ue_ue.K2Node_ConstructObjectFromClass.md#createdefaultsubobject)

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

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[ExecuteUbergraph](ue_ue.K2Node_ConstructObjectFromClass.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[GetClass](ue_ue.K2Node_ConstructObjectFromClass.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[GetName](ue_ue.K2Node_ConstructObjectFromClass.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[GetOuter](ue_ue.K2Node_ConstructObjectFromClass.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[GetWorld](ue_ue.K2Node_ConstructObjectFromClass.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`K2Node_GenericCreateObject`](ue_ue.K2Node_GenericCreateObject.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`K2Node_GenericCreateObject`](ue_ue.K2Node_GenericCreateObject.md)

#### Overrides

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[Find](ue_ue.K2Node_ConstructObjectFromClass.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`K2Node_GenericCreateObject`](ue_ue.K2Node_GenericCreateObject.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`K2Node_GenericCreateObject`](ue_ue.K2Node_GenericCreateObject.md)

#### Overrides

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[Load](ue_ue.K2Node_ConstructObjectFromClass.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[K2Node_ConstructObjectFromClass](ue_ue.K2Node_ConstructObjectFromClass.md).[StaticClass](ue_ue.K2Node_ConstructObjectFromClass.md#staticclass)
