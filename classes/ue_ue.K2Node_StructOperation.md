[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / K2Node\_StructOperation

# Class: K2Node\_StructOperation

[ue/ue](../modules/ue_ue.md).K2Node_StructOperation

## Hierarchy

- [`K2Node_Variable`](ue_ue.K2Node_Variable.md)

  ↳ **`K2Node_StructOperation`**

  ↳↳ [`K2Node_StructMemberGet`](ue_ue.K2Node_StructMemberGet.md)

  ↳↳ [`K2Node_StructMemberSet`](ue_ue.K2Node_StructMemberSet.md)

## Table of contents

### Constructors

- [constructor](ue_ue.K2Node_StructOperation.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.K2Node_StructOperation.md#advancedpindisplay)
- [DeprecatedPins](ue_ue.K2Node_StructOperation.md#deprecatedpins)
- [EnabledState](ue_ue.K2Node_StructOperation.md#enabledstate)
- [ErrorMsg](ue_ue.K2Node_StructOperation.md#errormsg)
- [ErrorType](ue_ue.K2Node_StructOperation.md#errortype)
- [NodeComment](ue_ue.K2Node_StructOperation.md#nodecomment)
- [NodeGuid](ue_ue.K2Node_StructOperation.md#nodeguid)
- [NodeHeight](ue_ue.K2Node_StructOperation.md#nodeheight)
- [NodePosX](ue_ue.K2Node_StructOperation.md#nodeposx)
- [NodePosY](ue_ue.K2Node_StructOperation.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.K2Node_StructOperation.md#nodeupgrademessage)
- [NodeWidth](ue_ue.K2Node_StructOperation.md#nodewidth)
- [SelfContextInfo](ue_ue.K2Node_StructOperation.md#selfcontextinfo)
- [StructType](ue_ue.K2Node_StructOperation.md#structtype)
- [VariableName](ue_ue.K2Node_StructOperation.md#variablename)
- [VariableReference](ue_ue.K2Node_StructOperation.md#variablereference)
- [VariableSourceClass](ue_ue.K2Node_StructOperation.md#variablesourceclass)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.K2Node_StructOperation.md#__tid_edgraphnode__)
- [\_\_tid\_K2Node\_StructOperation\_\_](ue_ue.K2Node_StructOperation.md#__tid_k2node_structoperation__)
- [\_\_tid\_K2Node\_Variable\_\_](ue_ue.K2Node_StructOperation.md#__tid_k2node_variable__)
- [\_\_tid\_K2Node\_\_](ue_ue.K2Node_StructOperation.md#__tid_k2node__)
- [\_\_tid\_Object\_\_](ue_ue.K2Node_StructOperation.md#__tid_object__)
- [bCanRenameNode](ue_ue.K2Node_StructOperation.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.K2Node_StructOperation.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.K2Node_StructOperation.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.K2Node_StructOperation.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.K2Node_StructOperation.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.K2Node_StructOperation.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.K2Node_StructOperation.md#bhascompilermessage)
- [bIsNodeEnabled](ue_ue.K2Node_StructOperation.md#bisnodeenabled)
- [bSelfContext](ue_ue.K2Node_StructOperation.md#bselfcontext)
- [bUserSetEnabledState](ue_ue.K2Node_StructOperation.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.K2Node_StructOperation.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.K2Node_StructOperation.md#executeubergraph)
- [GetClass](ue_ue.K2Node_StructOperation.md#getclass)
- [GetName](ue_ue.K2Node_StructOperation.md#getname)
- [GetOuter](ue_ue.K2Node_StructOperation.md#getouter)
- [GetWorld](ue_ue.K2Node_StructOperation.md#getworld)
- [Find](ue_ue.K2Node_StructOperation.md#find)
- [Load](ue_ue.K2Node_StructOperation.md#load)
- [StaticClass](ue_ue.K2Node_StructOperation.md#staticclass)

## Constructors

### constructor

• **new K2Node_StructOperation**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[K2Node_Variable](ue_ue.K2Node_Variable.md).[constructor](ue_ue.K2Node_Variable.md#constructor)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[AdvancedPinDisplay](ue_ue.K2Node_Variable.md#advancedpindisplay)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[DeprecatedPins](ue_ue.K2Node_Variable.md#deprecatedpins)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[EnabledState](ue_ue.K2Node_Variable.md#enabledstate)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[ErrorMsg](ue_ue.K2Node_Variable.md#errormsg)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[ErrorType](ue_ue.K2Node_Variable.md#errortype)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[NodeComment](ue_ue.K2Node_Variable.md#nodecomment)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[NodeGuid](ue_ue.K2Node_Variable.md#nodeguid)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[NodeHeight](ue_ue.K2Node_Variable.md#nodeheight)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[NodePosX](ue_ue.K2Node_Variable.md#nodeposx)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[NodePosY](ue_ue.K2Node_Variable.md#nodeposy)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[NodeUpgradeMessage](ue_ue.K2Node_Variable.md#nodeupgrademessage)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[NodeWidth](ue_ue.K2Node_Variable.md#nodewidth)

___

### SelfContextInfo

• **SelfContextInfo**: [`ESelfContextInfo`](../enums/ue_ue.ESelfContextInfo.md)

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[SelfContextInfo](ue_ue.K2Node_Variable.md#selfcontextinfo)

___

### StructType

• **StructType**: [`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### VariableName

• **VariableName**: `string`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[VariableName](ue_ue.K2Node_Variable.md#variablename)

___

### VariableReference

• **VariableReference**: [`MemberReference`](ue_ue.MemberReference.md)

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[VariableReference](ue_ue.K2Node_Variable.md#variablereference)

___

### VariableSourceClass

• **VariableSourceClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[VariableSourceClass](ue_ue.K2Node_Variable.md#variablesourceclass)

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[__tid_EdGraphNode__](ue_ue.K2Node_Variable.md#__tid_edgraphnode__)

___

### \_\_tid\_K2Node\_StructOperation\_\_

• **\_\_tid\_K2Node\_StructOperation\_\_**: `boolean`

___

### \_\_tid\_K2Node\_Variable\_\_

• **\_\_tid\_K2Node\_Variable\_\_**: `boolean`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[__tid_K2Node_Variable__](ue_ue.K2Node_Variable.md#__tid_k2node_variable__)

___

### \_\_tid\_K2Node\_\_

• **\_\_tid\_K2Node\_\_**: `boolean`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[__tid_K2Node__](ue_ue.K2Node_Variable.md#__tid_k2node__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[__tid_Object__](ue_ue.K2Node_Variable.md#__tid_object__)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[bCanRenameNode](ue_ue.K2Node_Variable.md#bcanrenamenode)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[bCanResizeNode](ue_ue.K2Node_Variable.md#bcanresizenode)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[bCommentBubbleMakeVisible](ue_ue.K2Node_Variable.md#bcommentbubblemakevisible)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[bCommentBubblePinned](ue_ue.K2Node_Variable.md#bcommentbubblepinned)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[bCommentBubbleVisible](ue_ue.K2Node_Variable.md#bcommentbubblevisible)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[bDisplayAsDisabled](ue_ue.K2Node_Variable.md#bdisplayasdisabled)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[bHasCompilerMessage](ue_ue.K2Node_Variable.md#bhascompilermessage)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[bIsNodeEnabled](ue_ue.K2Node_Variable.md#bisnodeenabled)

___

### bSelfContext

• **bSelfContext**: `boolean`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[bSelfContext](ue_ue.K2Node_Variable.md#bselfcontext)

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[bUserSetEnabledState](ue_ue.K2Node_Variable.md#busersetenabledstate)

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

[K2Node_Variable](ue_ue.K2Node_Variable.md).[CreateDefaultSubobject](ue_ue.K2Node_Variable.md#createdefaultsubobject)

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

[K2Node_Variable](ue_ue.K2Node_Variable.md).[ExecuteUbergraph](ue_ue.K2Node_Variable.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[GetClass](ue_ue.K2Node_Variable.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[GetName](ue_ue.K2Node_Variable.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[GetOuter](ue_ue.K2Node_Variable.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[K2Node_Variable](ue_ue.K2Node_Variable.md).[GetWorld](ue_ue.K2Node_Variable.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`K2Node_StructOperation`](ue_ue.K2Node_StructOperation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`K2Node_StructOperation`](ue_ue.K2Node_StructOperation.md)

#### Overrides

[K2Node_Variable](ue_ue.K2Node_Variable.md).[Find](ue_ue.K2Node_Variable.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`K2Node_StructOperation`](ue_ue.K2Node_StructOperation.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`K2Node_StructOperation`](ue_ue.K2Node_StructOperation.md)

#### Overrides

[K2Node_Variable](ue_ue.K2Node_Variable.md).[Load](ue_ue.K2Node_Variable.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[K2Node_Variable](ue_ue.K2Node_Variable.md).[StaticClass](ue_ue.K2Node_Variable.md#staticclass)
