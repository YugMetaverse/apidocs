[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundSubmixGraphNode

# Class: SoundSubmixGraphNode

[ue/ue](../modules/ue_ue.md).SoundSubmixGraphNode

## Hierarchy

- [`EdGraphNode`](ue_ue.EdGraphNode.md)

  ↳ **`SoundSubmixGraphNode`**

## Table of contents

### Constructors

- [constructor](ue_ue.SoundSubmixGraphNode.md#constructor)

### Properties

- [AdvancedPinDisplay](ue_ue.SoundSubmixGraphNode.md#advancedpindisplay)
- [DeprecatedPins](ue_ue.SoundSubmixGraphNode.md#deprecatedpins)
- [EnabledState](ue_ue.SoundSubmixGraphNode.md#enabledstate)
- [ErrorMsg](ue_ue.SoundSubmixGraphNode.md#errormsg)
- [ErrorType](ue_ue.SoundSubmixGraphNode.md#errortype)
- [NodeComment](ue_ue.SoundSubmixGraphNode.md#nodecomment)
- [NodeGuid](ue_ue.SoundSubmixGraphNode.md#nodeguid)
- [NodeHeight](ue_ue.SoundSubmixGraphNode.md#nodeheight)
- [NodePosX](ue_ue.SoundSubmixGraphNode.md#nodeposx)
- [NodePosY](ue_ue.SoundSubmixGraphNode.md#nodeposy)
- [NodeUpgradeMessage](ue_ue.SoundSubmixGraphNode.md#nodeupgrademessage)
- [NodeWidth](ue_ue.SoundSubmixGraphNode.md#nodewidth)
- [SoundSubmix](ue_ue.SoundSubmixGraphNode.md#soundsubmix)
- [\_\_tid\_EdGraphNode\_\_](ue_ue.SoundSubmixGraphNode.md#__tid_edgraphnode__)
- [\_\_tid\_Object\_\_](ue_ue.SoundSubmixGraphNode.md#__tid_object__)
- [\_\_tid\_SoundSubmixGraphNode\_\_](ue_ue.SoundSubmixGraphNode.md#__tid_soundsubmixgraphnode__)
- [bCanRenameNode](ue_ue.SoundSubmixGraphNode.md#bcanrenamenode)
- [bCanResizeNode](ue_ue.SoundSubmixGraphNode.md#bcanresizenode)
- [bCommentBubbleMakeVisible](ue_ue.SoundSubmixGraphNode.md#bcommentbubblemakevisible)
- [bCommentBubblePinned](ue_ue.SoundSubmixGraphNode.md#bcommentbubblepinned)
- [bCommentBubbleVisible](ue_ue.SoundSubmixGraphNode.md#bcommentbubblevisible)
- [bDisplayAsDisabled](ue_ue.SoundSubmixGraphNode.md#bdisplayasdisabled)
- [bHasCompilerMessage](ue_ue.SoundSubmixGraphNode.md#bhascompilermessage)
- [bIsNodeEnabled](ue_ue.SoundSubmixGraphNode.md#bisnodeenabled)
- [bUserSetEnabledState](ue_ue.SoundSubmixGraphNode.md#busersetenabledstate)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundSubmixGraphNode.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundSubmixGraphNode.md#executeubergraph)
- [GetClass](ue_ue.SoundSubmixGraphNode.md#getclass)
- [GetName](ue_ue.SoundSubmixGraphNode.md#getname)
- [GetOuter](ue_ue.SoundSubmixGraphNode.md#getouter)
- [GetWorld](ue_ue.SoundSubmixGraphNode.md#getworld)
- [Find](ue_ue.SoundSubmixGraphNode.md#find)
- [Load](ue_ue.SoundSubmixGraphNode.md#load)
- [StaticClass](ue_ue.SoundSubmixGraphNode.md#staticclass)

## Constructors

### constructor

• **new SoundSubmixGraphNode**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EdGraphNode](ue_ue.EdGraphNode.md).[constructor](ue_ue.EdGraphNode.md#constructor)

## Properties

### AdvancedPinDisplay

• **AdvancedPinDisplay**: [`ENodeAdvancedPins`](../enums/ue_ue.ENodeAdvancedPins.md)

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[AdvancedPinDisplay](ue_ue.EdGraphNode.md#advancedpindisplay)

___

### DeprecatedPins

• **DeprecatedPins**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EdGraphPin_Deprecated`](ue_ue.EdGraphPin_Deprecated.md)\>

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[DeprecatedPins](ue_ue.EdGraphNode.md#deprecatedpins)

___

### EnabledState

• **EnabledState**: [`ENodeEnabledState`](../enums/ue_ue.ENodeEnabledState.md)

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[EnabledState](ue_ue.EdGraphNode.md#enabledstate)

___

### ErrorMsg

• **ErrorMsg**: `string`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[ErrorMsg](ue_ue.EdGraphNode.md#errormsg)

___

### ErrorType

• **ErrorType**: `number`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[ErrorType](ue_ue.EdGraphNode.md#errortype)

___

### NodeComment

• **NodeComment**: `string`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[NodeComment](ue_ue.EdGraphNode.md#nodecomment)

___

### NodeGuid

• **NodeGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[NodeGuid](ue_ue.EdGraphNode.md#nodeguid)

___

### NodeHeight

• **NodeHeight**: `number`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[NodeHeight](ue_ue.EdGraphNode.md#nodeheight)

___

### NodePosX

• **NodePosX**: `number`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[NodePosX](ue_ue.EdGraphNode.md#nodeposx)

___

### NodePosY

• **NodePosY**: `number`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[NodePosY](ue_ue.EdGraphNode.md#nodeposy)

___

### NodeUpgradeMessage

• **NodeUpgradeMessage**: `string`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[NodeUpgradeMessage](ue_ue.EdGraphNode.md#nodeupgrademessage)

___

### NodeWidth

• **NodeWidth**: `number`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[NodeWidth](ue_ue.EdGraphNode.md#nodewidth)

___

### SoundSubmix

• **SoundSubmix**: [`SoundSubmix`](ue_ue.SoundSubmix.md)

___

### \_\_tid\_EdGraphNode\_\_

• **\_\_tid\_EdGraphNode\_\_**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[__tid_EdGraphNode__](ue_ue.EdGraphNode.md#__tid_edgraphnode__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[__tid_Object__](ue_ue.EdGraphNode.md#__tid_object__)

___

### \_\_tid\_SoundSubmixGraphNode\_\_

• **\_\_tid\_SoundSubmixGraphNode\_\_**: `boolean`

___

### bCanRenameNode

• **bCanRenameNode**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bCanRenameNode](ue_ue.EdGraphNode.md#bcanrenamenode)

___

### bCanResizeNode

• **bCanResizeNode**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bCanResizeNode](ue_ue.EdGraphNode.md#bcanresizenode)

___

### bCommentBubbleMakeVisible

• **bCommentBubbleMakeVisible**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bCommentBubbleMakeVisible](ue_ue.EdGraphNode.md#bcommentbubblemakevisible)

___

### bCommentBubblePinned

• **bCommentBubblePinned**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bCommentBubblePinned](ue_ue.EdGraphNode.md#bcommentbubblepinned)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bCommentBubbleVisible](ue_ue.EdGraphNode.md#bcommentbubblevisible)

___

### bDisplayAsDisabled

• **bDisplayAsDisabled**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bDisplayAsDisabled](ue_ue.EdGraphNode.md#bdisplayasdisabled)

___

### bHasCompilerMessage

• **bHasCompilerMessage**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bHasCompilerMessage](ue_ue.EdGraphNode.md#bhascompilermessage)

___

### bIsNodeEnabled

• **bIsNodeEnabled**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bIsNodeEnabled](ue_ue.EdGraphNode.md#bisnodeenabled)

___

### bUserSetEnabledState

• **bUserSetEnabledState**: `boolean`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[bUserSetEnabledState](ue_ue.EdGraphNode.md#busersetenabledstate)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[GetClass](ue_ue.EdGraphNode.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[GetName](ue_ue.EdGraphNode.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[GetOuter](ue_ue.EdGraphNode.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EdGraphNode](ue_ue.EdGraphNode.md).[GetWorld](ue_ue.EdGraphNode.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundSubmixGraphNode`](ue_ue.SoundSubmixGraphNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundSubmixGraphNode`](ue_ue.SoundSubmixGraphNode.md)

#### Overrides

[EdGraphNode](ue_ue.EdGraphNode.md).[Find](ue_ue.EdGraphNode.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundSubmixGraphNode`](ue_ue.SoundSubmixGraphNode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundSubmixGraphNode`](ue_ue.SoundSubmixGraphNode.md)

#### Overrides

[EdGraphNode](ue_ue.EdGraphNode.md).[Load](ue_ue.EdGraphNode.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EdGraphNode](ue_ue.EdGraphNode.md).[StaticClass](ue_ue.EdGraphNode.md#staticclass)
