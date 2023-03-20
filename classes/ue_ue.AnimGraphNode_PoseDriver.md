[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimGraphNode\_PoseDriver

# Class: AnimGraphNode\_PoseDriver

[ue/ue](../modules/ue_ue.md).AnimGraphNode_PoseDriver

## Hierarchy

- [`AnimGraphNode_PoseHandler`](ue_ue.AnimGraphNode_PoseHandler.md)

  ↳ **`AnimGraphNode_PoseDriver`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimGraphNode_PoseDriver.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.AnimGraphNode_PoseDriver.md#advancedpindisplay)
- [AxisLength](ue_ue.AnimGraphNode_PoseDriver.md#axislength)
- [BlueprintUsage](ue_ue.AnimGraphNode_PoseDriver.md#blueprintusage)
- [ConeSubdivision](ue_ue.AnimGraphNode_PoseDriver.md#conesubdivision)
- [DeprecatedPins](ue_ue.AnimGraphNode_PoseDriver.md#deprecatedpins)
- [EnabledState](ue_ue.AnimGraphNode_PoseDriver.md#enabledstate)
- [ErrorMsg](ue_ue.AnimGraphNode_PoseDriver.md#errormsg)
- [ErrorType](ue_ue.AnimGraphNode_PoseDriver.md#errortype)
- [LastPreviewComponent](ue_ue.AnimGraphNode_PoseDriver.md#lastpreviewcomponent)
- [Node](ue_ue.AnimGraphNode_PoseDriver.md#node)
- [NodeComment](ue_ue.AnimGraphNode_PoseDriver.md#nodecomment)
- [NodeGuid](ue_ue.AnimGraphNode_PoseDriver.md#nodeguid)
- [NodeHeight](ue_ue.AnimGraphNode_PoseDriver.md#nodeheight)
- [NodePosX](ue_ue.AnimGraphNode_PoseDriver.md#nodeposx)
- [NodePosY](ue_ue.AnimGraphNode_PoseDriver.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.AnimGraphNode_PoseDriver.md#nodeupgrademessage)
- [NodeWidth](ue_ue.AnimGraphNode_PoseDriver.md#nodewidth)
- [ShowPinForProperties](ue_ue.AnimGraphNode_PoseDriver.md#showpinforproperties)
- [SyncGroup](ue_ue.AnimGraphNode_PoseDriver.md#syncgroup)
- [\_\_tid\_AnimGraphNode\_AssetPlayerBase\_\_](ue_ue.AnimGraphNode_PoseDriver.md#__tid_animgraphnode_assetplayerbase__)
- [\_\_tid\_AnimGraphNode\_Base\_\_](ue_ue.AnimGraphNode_PoseDriver.md#__tid_animgraphnode_base__)
- [\_\_tid\_AnimGraphNode\_PoseDriver\_\_](ue_ue.AnimGraphNode_PoseDriver.md#__tid_animgraphnode_posedriver__)
- [\_\_tid\_AnimGraphNode\_PoseHandler\_\_](ue_ue.AnimGraphNode_PoseDriver.md#__tid_animgraphnode_posehandler__)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.AnimGraphNode_PoseDriver.md#__tid_edgraphnode__)
- [\_\_tid\_K2Node\_\_](ue_ue.AnimGraphNode_PoseDriver.md#__tid_k2node__)
- [\_\_tid\_Object\_\_](ue_ue.AnimGraphNode_PoseDriver.md#__tid_object__)
- [bCanRenameNode](ue_ue.AnimGraphNode_PoseDriver.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.AnimGraphNode_PoseDriver.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.AnimGraphNode_PoseDriver.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.AnimGraphNode_PoseDriver.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.AnimGraphNode_PoseDriver.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.AnimGraphNode_PoseDriver.md#bdisplayasdisabled)
- [bDrawDebugCones](ue_ue.AnimGraphNode_PoseDriver.md#bdrawdebugcones)
- [bHasCompilerMessage](ue_ue.AnimGraphNode_PoseDriver.md#bhascompilermessage)
- [bIsNodeEnabled](ue_ue.AnimGraphNode_PoseDriver.md#bisnodeenabled)
- [bUserSetEnabledState](ue_ue.AnimGraphNode_PoseDriver.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimGraphNode_PoseDriver.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimGraphNode_PoseDriver.md#executeubergraph)
- [GetClass](ue_ue.AnimGraphNode_PoseDriver.md#getclass)
- [GetName](ue_ue.AnimGraphNode_PoseDriver.md#getname)
- [GetOuter](ue_ue.AnimGraphNode_PoseDriver.md#getouter)
- [GetWorld](ue_ue.AnimGraphNode_PoseDriver.md#getworld)
- [Find](ue_ue.AnimGraphNode_PoseDriver.md#find)
- [Load](ue_ue.AnimGraphNode_PoseDriver.md#load)
- [StaticClass](ue_ue.AnimGraphNode_PoseDriver.md#staticclass)

## Constructors

### constructor

• **new AnimGraphNode_PoseDriver**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[constructor](ue_ue.AnimGraphNode_PoseHandler.md#constructor)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[AdvancedPinDisplay](ue_ue.AnimGraphNode_PoseHandler.md#advancedpindisplay)

___

### AxisLength

• **AxisLength**: `number`

___

### BlueprintUsage

• **BlueprintUsage**: [`EBlueprintUsage`](../enums/ue_ue.EBlueprintUsage.md)

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[BlueprintUsage](ue_ue.AnimGraphNode_PoseHandler.md#blueprintusage)

___

### ConeSubdivision

• **ConeSubdivision**: `number`

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[DeprecatedPins](ue_ue.AnimGraphNode_PoseHandler.md#deprecatedpins)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[EnabledState](ue_ue.AnimGraphNode_PoseHandler.md#enabledstate)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[ErrorMsg](ue_ue.AnimGraphNode_PoseHandler.md#errormsg)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[ErrorType](ue_ue.AnimGraphNode_PoseHandler.md#errortype)

___

### LastPreviewComponent

• **LastPreviewComponent**: [`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)

___

### Node

• **Node**: [`AnimNode_PoseDriver`](ue_ue.AnimNode_PoseDriver.md)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[NodeComment](ue_ue.AnimGraphNode_PoseHandler.md#nodecomment)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[NodeGuid](ue_ue.AnimGraphNode_PoseHandler.md#nodeguid)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[NodeHeight](ue_ue.AnimGraphNode_PoseHandler.md#nodeheight)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[NodePosX](ue_ue.AnimGraphNode_PoseHandler.md#nodeposx)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[NodePosY](ue_ue.AnimGraphNode_PoseHandler.md#nodeposy)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[NodeUpgradeMessage](ue_ue.AnimGraphNode_PoseHandler.md#nodeupgrademessage)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[NodeWidth](ue_ue.AnimGraphNode_PoseHandler.md#nodewidth)

___

### ShowPinForProperties

• **ShowPinForProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`OptionalPinFromProperty`](ue_ue.OptionalPinFromProperty.md)\>

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[ShowPinForProperties](ue_ue.AnimGraphNode_PoseHandler.md#showpinforproperties)

___

### SyncGroup

• **SyncGroup**: [`AnimationGroupReference`](ue_ue.AnimationGroupReference.md)

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[SyncGroup](ue_ue.AnimGraphNode_PoseHandler.md#syncgroup)

___

### \_\_tid\_AnimGraphNode\_AssetPlayerBase\_\_

• **\_\_tid\_AnimGraphNode\_AssetPlayerBase\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[__tid_AnimGraphNode_AssetPlayerBase__](ue_ue.AnimGraphNode_PoseHandler.md#__tid_animgraphnode_assetplayerbase__)

___

### \_\_tid\_AnimGraphNode\_Base\_\_

• **\_\_tid\_AnimGraphNode\_Base\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[__tid_AnimGraphNode_Base__](ue_ue.AnimGraphNode_PoseHandler.md#__tid_animgraphnode_base__)

___

### \_\_tid\_AnimGraphNode\_PoseDriver\_\_

• **\_\_tid\_AnimGraphNode\_PoseDriver\_\_**: `boolean`

___

### \_\_tid\_AnimGraphNode\_PoseHandler\_\_

• **\_\_tid\_AnimGraphNode\_PoseHandler\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[__tid_AnimGraphNode_PoseHandler__](ue_ue.AnimGraphNode_PoseHandler.md#__tid_animgraphnode_posehandler__)

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[__tid_EdGraphNode__](ue_ue.AnimGraphNode_PoseHandler.md#__tid_edgraphnode__)

___

### \_\_tid\_K2Node\_\_

• **\_\_tid\_K2Node\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[__tid_K2Node__](ue_ue.AnimGraphNode_PoseHandler.md#__tid_k2node__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[__tid_Object__](ue_ue.AnimGraphNode_PoseHandler.md#__tid_object__)

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[bCanRenameNode](ue_ue.AnimGraphNode_PoseHandler.md#bcanrenamenode)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[bCanResizeNode](ue_ue.AnimGraphNode_PoseHandler.md#bcanresizenode)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[bCommentBubbleMakeVisible](ue_ue.AnimGraphNode_PoseHandler.md#bcommentbubblemakevisible)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[bCommentBubblePinned](ue_ue.AnimGraphNode_PoseHandler.md#bcommentbubblepinned)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[bCommentBubbleVisible](ue_ue.AnimGraphNode_PoseHandler.md#bcommentbubblevisible)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[bDisplayAsDisabled](ue_ue.AnimGraphNode_PoseHandler.md#bdisplayasdisabled)

___

### bDrawDebugCones

• **bDrawDebugCones**: `boolean`

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[bHasCompilerMessage](ue_ue.AnimGraphNode_PoseHandler.md#bhascompilermessage)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[bIsNodeEnabled](ue_ue.AnimGraphNode_PoseHandler.md#bisnodeenabled)

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[bUserSetEnabledState](ue_ue.AnimGraphNode_PoseHandler.md#busersetenabledstate)

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

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[CreateDefaultSubobject](ue_ue.AnimGraphNode_PoseHandler.md#createdefaultsubobject)

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

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[ExecuteUbergraph](ue_ue.AnimGraphNode_PoseHandler.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[GetClass](ue_ue.AnimGraphNode_PoseHandler.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[GetName](ue_ue.AnimGraphNode_PoseHandler.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[GetOuter](ue_ue.AnimGraphNode_PoseHandler.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[GetWorld](ue_ue.AnimGraphNode_PoseHandler.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimGraphNode_PoseDriver`](ue_ue.AnimGraphNode_PoseDriver.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimGraphNode_PoseDriver`](ue_ue.AnimGraphNode_PoseDriver.md)

#### Overrides

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[Find](ue_ue.AnimGraphNode_PoseHandler.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimGraphNode_PoseDriver`](ue_ue.AnimGraphNode_PoseDriver.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimGraphNode_PoseDriver`](ue_ue.AnimGraphNode_PoseDriver.md)

#### Overrides

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[Load](ue_ue.AnimGraphNode_PoseHandler.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimGraphNode_PoseHandler](ue_ue.AnimGraphNode_PoseHandler.md).[StaticClass](ue_ue.AnimGraphNode_PoseHandler.md#staticclass)
