[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PawnAction\_Repeat

# Class: PawnAction\_Repeat

[ue/ue](../modules/ue_ue.md).PawnAction_Repeat

## Hierarchy

- [`PawnAction`](ue_ue.PawnAction.md)

  ↳ **`PawnAction_Repeat`**

## Table of contents

### Constructors

- [constructor](ue_ue.PawnAction_Repeat.md#constructor)

### Properties

- [ActionToRepeat](ue_ue.PawnAction_Repeat.md#actiontorepeat)
- [BrainComp](ue_ue.PawnAction_Repeat.md#braincomp)
- [ChildAction](ue_ue.PawnAction_Repeat.md#childaction)
- [ChildFailureHandlingMode](ue_ue.PawnAction_Repeat.md#childfailurehandlingmode)
- [Instigator](ue_ue.PawnAction_Repeat.md#instigator)
- [OwnerComponent](ue_ue.PawnAction_Repeat.md#ownercomponent)
- [ParentAction](ue_ue.PawnAction_Repeat.md#parentaction)
- [RecentActionCopy](ue_ue.PawnAction_Repeat.md#recentactioncopy)
- [\_\_tid\_Object\_\_](ue_ue.PawnAction_Repeat.md#__tid_object__)
- [\_\_tid\_PawnAction\_Repeat\_\_](ue_ue.PawnAction_Repeat.md#__tid_pawnaction_repeat__)
- [\_\_tid\_PawnAction\_\_](ue_ue.PawnAction_Repeat.md#__tid_pawnaction__)
- [bAllowNewSameClassInstance](ue_ue.PawnAction_Repeat.md#ballownewsameclassinstance)
- [bAlwaysNotifyOnFinished](ue_ue.PawnAction_Repeat.md#balwaysnotifyonfinished)
- [bReplaceActiveSameClassInstance](ue_ue.PawnAction_Repeat.md#breplaceactivesameclassinstance)
- [bShouldPauseMovement](ue_ue.PawnAction_Repeat.md#bshouldpausemovement)

### Methods

- [CreateDefaultSubobject](ue_ue.PawnAction_Repeat.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PawnAction_Repeat.md#executeubergraph)
- [Finish](ue_ue.PawnAction_Repeat.md#finish)
- [GetActionPriority](ue_ue.PawnAction_Repeat.md#getactionpriority)
- [GetClass](ue_ue.PawnAction_Repeat.md#getclass)
- [GetName](ue_ue.PawnAction_Repeat.md#getname)
- [GetOuter](ue_ue.PawnAction_Repeat.md#getouter)
- [GetWorld](ue_ue.PawnAction_Repeat.md#getworld)
- [CreateActionInstance](ue_ue.PawnAction_Repeat.md#createactioninstance)
- [Find](ue_ue.PawnAction_Repeat.md#find)
- [Load](ue_ue.PawnAction_Repeat.md#load)
- [StaticClass](ue_ue.PawnAction_Repeat.md#staticclass)

## Constructors

### constructor

• **new PawnAction_Repeat**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[constructor](ue_ue.PawnAction.md#constructor)

#### Defined in

[ue/ue.d.ts:56964](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56964)

## Properties

### ActionToRepeat

• **ActionToRepeat**: [`PawnAction`](ue_ue.PawnAction.md)

#### Defined in

[ue/ue.d.ts:56965](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56965)

___

### BrainComp

• **BrainComp**: [`BrainComponent`](ue_ue.BrainComponent.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[BrainComp](ue_ue.PawnAction.md#braincomp)

#### Defined in

[ue/ue.d.ts:14827](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14827)

___

### ChildAction

• **ChildAction**: [`PawnAction`](ue_ue.PawnAction.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[ChildAction](ue_ue.PawnAction.md#childaction)

#### Defined in

[ue/ue.d.ts:14823](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14823)

___

### ChildFailureHandlingMode

• **ChildFailureHandlingMode**: [`EPawnActionFailHandling`](../enums/ue_ue.EPawnActionFailHandling.md)

#### Defined in

[ue/ue.d.ts:56967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56967)

___

### Instigator

• **Instigator**: [`Object`](ue_ue.Object.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[Instigator](ue_ue.PawnAction.md#instigator)

#### Defined in

[ue/ue.d.ts:14826](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14826)

___

### OwnerComponent

• **OwnerComponent**: [`PawnActionsComponent`](ue_ue.PawnActionsComponent.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[OwnerComponent](ue_ue.PawnAction.md#ownercomponent)

#### Defined in

[ue/ue.d.ts:14825](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14825)

___

### ParentAction

• **ParentAction**: [`PawnAction`](ue_ue.PawnAction.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[ParentAction](ue_ue.PawnAction.md#parentaction)

#### Defined in

[ue/ue.d.ts:14824](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14824)

___

### RecentActionCopy

• **RecentActionCopy**: [`PawnAction`](ue_ue.PawnAction.md)

#### Defined in

[ue/ue.d.ts:56966](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56966)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[__tid_Object__](ue_ue.PawnAction.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PawnAction\_Repeat\_\_

• **\_\_tid\_PawnAction\_Repeat\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:56972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56972)

___

### \_\_tid\_PawnAction\_\_

• **\_\_tid\_PawnAction\_\_**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[__tid_PawnAction__](ue_ue.PawnAction.md#__tid_pawnaction__)

#### Defined in

[ue/ue.d.ts:14839](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14839)

___

### bAllowNewSameClassInstance

• **bAllowNewSameClassInstance**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[bAllowNewSameClassInstance](ue_ue.PawnAction.md#ballownewsameclassinstance)

#### Defined in

[ue/ue.d.ts:14828](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14828)

___

### bAlwaysNotifyOnFinished

• **bAlwaysNotifyOnFinished**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[bAlwaysNotifyOnFinished](ue_ue.PawnAction.md#balwaysnotifyonfinished)

#### Defined in

[ue/ue.d.ts:14831](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14831)

___

### bReplaceActiveSameClassInstance

• **bReplaceActiveSameClassInstance**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[bReplaceActiveSameClassInstance](ue_ue.PawnAction.md#breplaceactivesameclassinstance)

#### Defined in

[ue/ue.d.ts:14829](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14829)

___

### bShouldPauseMovement

• **bShouldPauseMovement**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[bShouldPauseMovement](ue_ue.PawnAction.md#bshouldpausemovement)

#### Defined in

[ue/ue.d.ts:14830](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14830)

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

[PawnAction](ue_ue.PawnAction.md).[CreateDefaultSubobject](ue_ue.PawnAction.md#createdefaultsubobject)

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

[PawnAction](ue_ue.PawnAction.md).[ExecuteUbergraph](ue_ue.PawnAction.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### Finish

▸ **Finish**(`WithResult`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WithResult` | [`EPawnActionResult`](../enums/ue_ue.EPawnActionResult.md) |

#### Returns

`void`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[Finish](ue_ue.PawnAction.md#finish)

#### Defined in

[ue/ue.d.ts:14832](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14832)

___

### GetActionPriority

▸ **GetActionPriority**(): [`EAIRequestPriority`](../enums/ue_ue.EAIRequestPriority.md)

#### Returns

[`EAIRequestPriority`](../enums/ue_ue.EAIRequestPriority.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[GetActionPriority](ue_ue.PawnAction.md#getactionpriority)

#### Defined in

[ue/ue.d.ts:14833](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14833)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[GetClass](ue_ue.PawnAction.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[GetName](ue_ue.PawnAction.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[GetOuter](ue_ue.PawnAction.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[GetWorld](ue_ue.PawnAction.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### CreateActionInstance

▸ `Static` **CreateActionInstance**(`WorldContextObject`, `ActionClass`): [`PawnAction`](ue_ue.PawnAction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ActionClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`PawnAction`](ue_ue.PawnAction.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[CreateActionInstance](ue_ue.PawnAction.md#createactioninstance)

#### Defined in

[ue/ue.d.ts:14834](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14834)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PawnAction_Repeat`](ue_ue.PawnAction_Repeat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PawnAction_Repeat`](ue_ue.PawnAction_Repeat.md)

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[Find](ue_ue.PawnAction.md#find)

#### Defined in

[ue/ue.d.ts:56969](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56969)

___

### Load

▸ `Static` **Load**(`InName`): [`PawnAction_Repeat`](ue_ue.PawnAction_Repeat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PawnAction_Repeat`](ue_ue.PawnAction_Repeat.md)

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[Load](ue_ue.PawnAction.md#load)

#### Defined in

[ue/ue.d.ts:56970](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56970)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[StaticClass](ue_ue.PawnAction.md#staticclass)

#### Defined in

[ue/ue.d.ts:56968](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L56968)
