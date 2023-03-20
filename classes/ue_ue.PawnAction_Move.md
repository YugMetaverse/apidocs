[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PawnAction\_Move

# Class: PawnAction\_Move

[ue/ue](../modules/ue_ue.md).PawnAction_Move

## Hierarchy

- [`PawnAction`](ue_ue.PawnAction.md)

  ↳ **`PawnAction_Move`**

## Table of contents

### Constructors

- [constructor](ue_ue.PawnAction_Move.md#constructor)

### Properties

- [AcceptableRadius](ue_ue.PawnAction_Move.md#acceptableradius)
- [BrainComp](ue_ue.PawnAction_Move.md#braincomp)
- [ChildAction](ue_ue.PawnAction_Move.md#childaction)
- [FilterClass](ue_ue.PawnAction_Move.md#filterclass)
- [GoalActor](ue_ue.PawnAction_Move.md#goalactor)
- [GoalLocation](ue_ue.PawnAction_Move.md#goallocation)
- [Instigator](ue_ue.PawnAction_Move.md#instigator)
- [OwnerComponent](ue_ue.PawnAction_Move.md#ownercomponent)
- [ParentAction](ue_ue.PawnAction_Move.md#parentaction)
- [\_\_tid\_Object\_\_](ue_ue.PawnAction_Move.md#__tid_object__)
- [\_\_tid\_PawnAction\_Move\_\_](ue_ue.PawnAction_Move.md#__tid_pawnaction_move__)
- [\_\_tid\_PawnAction\_\_](ue_ue.PawnAction_Move.md#__tid_pawnaction__)
- [bAbortChildActionOnPathChange](ue_ue.PawnAction_Move.md#babortchildactiononpathchange)
- [bAllowNewSameClassInstance](ue_ue.PawnAction_Move.md#ballownewsameclassinstance)
- [bAllowPartialPath](ue_ue.PawnAction_Move.md#ballowpartialpath)
- [bAllowStrafe](ue_ue.PawnAction_Move.md#ballowstrafe)
- [bAlwaysNotifyOnFinished](ue_ue.PawnAction_Move.md#balwaysnotifyonfinished)
- [bFinishOnOverlap](ue_ue.PawnAction_Move.md#bfinishonoverlap)
- [bProjectGoalToNavigation](ue_ue.PawnAction_Move.md#bprojectgoaltonavigation)
- [bReplaceActiveSameClassInstance](ue_ue.PawnAction_Move.md#breplaceactivesameclassinstance)
- [bShouldPauseMovement](ue_ue.PawnAction_Move.md#bshouldpausemovement)
- [bUpdatePathToGoal](ue_ue.PawnAction_Move.md#bupdatepathtogoal)
- [bUsePathfinding](ue_ue.PawnAction_Move.md#busepathfinding)

### Methods

- [CreateDefaultSubobject](ue_ue.PawnAction_Move.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PawnAction_Move.md#executeubergraph)
- [Finish](ue_ue.PawnAction_Move.md#finish)
- [GetActionPriority](ue_ue.PawnAction_Move.md#getactionpriority)
- [GetClass](ue_ue.PawnAction_Move.md#getclass)
- [GetName](ue_ue.PawnAction_Move.md#getname)
- [GetOuter](ue_ue.PawnAction_Move.md#getouter)
- [GetWorld](ue_ue.PawnAction_Move.md#getworld)
- [CreateActionInstance](ue_ue.PawnAction_Move.md#createactioninstance)
- [Find](ue_ue.PawnAction_Move.md#find)
- [Load](ue_ue.PawnAction_Move.md#load)
- [StaticClass](ue_ue.PawnAction_Move.md#staticclass)

## Constructors

### constructor

• **new PawnAction_Move**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[constructor](ue_ue.PawnAction.md#constructor)

#### Defined in

[ue/ue.d.ts:56944](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56944)

## Properties

### AcceptableRadius

• **AcceptableRadius**: `number`

#### Defined in

[ue/ue.d.ts:56947](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56947)

___

### BrainComp

• **BrainComp**: [`BrainComponent`](ue_ue.BrainComponent.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[BrainComp](ue_ue.PawnAction.md#braincomp)

#### Defined in

[ue/ue.d.ts:14827](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14827)

___

### ChildAction

• **ChildAction**: [`PawnAction`](ue_ue.PawnAction.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[ChildAction](ue_ue.PawnAction.md#childaction)

#### Defined in

[ue/ue.d.ts:14823](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14823)

___

### FilterClass

• **FilterClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:56948](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56948)

___

### GoalActor

• **GoalActor**: [`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:56945](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56945)

___

### GoalLocation

• **GoalLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:56946](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56946)

___

### Instigator

• **Instigator**: [`Object`](ue_ue.Object.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[Instigator](ue_ue.PawnAction.md#instigator)

#### Defined in

[ue/ue.d.ts:14826](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14826)

___

### OwnerComponent

• **OwnerComponent**: [`PawnActionsComponent`](ue_ue.PawnActionsComponent.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[OwnerComponent](ue_ue.PawnAction.md#ownercomponent)

#### Defined in

[ue/ue.d.ts:14825](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14825)

___

### ParentAction

• **ParentAction**: [`PawnAction`](ue_ue.PawnAction.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[ParentAction](ue_ue.PawnAction.md#parentaction)

#### Defined in

[ue/ue.d.ts:14824](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14824)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[__tid_Object__](ue_ue.PawnAction.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PawnAction\_Move\_\_

• **\_\_tid\_PawnAction\_Move\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:56960](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56960)

___

### \_\_tid\_PawnAction\_\_

• **\_\_tid\_PawnAction\_\_**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[__tid_PawnAction__](ue_ue.PawnAction.md#__tid_pawnaction__)

#### Defined in

[ue/ue.d.ts:14839](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14839)

___

### bAbortChildActionOnPathChange

• **bAbortChildActionOnPathChange**: `boolean`

#### Defined in

[ue/ue.d.ts:56955](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56955)

___

### bAllowNewSameClassInstance

• **bAllowNewSameClassInstance**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[bAllowNewSameClassInstance](ue_ue.PawnAction.md#ballownewsameclassinstance)

#### Defined in

[ue/ue.d.ts:14828](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14828)

___

### bAllowPartialPath

• **bAllowPartialPath**: `boolean`

#### Defined in

[ue/ue.d.ts:56952](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56952)

___

### bAllowStrafe

• **bAllowStrafe**: `boolean`

#### Defined in

[ue/ue.d.ts:56949](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56949)

___

### bAlwaysNotifyOnFinished

• **bAlwaysNotifyOnFinished**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[bAlwaysNotifyOnFinished](ue_ue.PawnAction.md#balwaysnotifyonfinished)

#### Defined in

[ue/ue.d.ts:14831](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14831)

___

### bFinishOnOverlap

• **bFinishOnOverlap**: `boolean`

#### Defined in

[ue/ue.d.ts:56950](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56950)

___

### bProjectGoalToNavigation

• **bProjectGoalToNavigation**: `boolean`

#### Defined in

[ue/ue.d.ts:56953](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56953)

___

### bReplaceActiveSameClassInstance

• **bReplaceActiveSameClassInstance**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[bReplaceActiveSameClassInstance](ue_ue.PawnAction.md#breplaceactivesameclassinstance)

#### Defined in

[ue/ue.d.ts:14829](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14829)

___

### bShouldPauseMovement

• **bShouldPauseMovement**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[bShouldPauseMovement](ue_ue.PawnAction.md#bshouldpausemovement)

#### Defined in

[ue/ue.d.ts:14830](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14830)

___

### bUpdatePathToGoal

• **bUpdatePathToGoal**: `boolean`

#### Defined in

[ue/ue.d.ts:56954](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56954)

___

### bUsePathfinding

• **bUsePathfinding**: `boolean`

#### Defined in

[ue/ue.d.ts:56951](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56951)

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

[PawnAction](ue_ue.PawnAction.md).[ExecuteUbergraph](ue_ue.PawnAction.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

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

[ue/ue.d.ts:14832](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14832)

___

### GetActionPriority

▸ **GetActionPriority**(): [`EAIRequestPriority`](../enums/ue_ue.EAIRequestPriority.md)

#### Returns

[`EAIRequestPriority`](../enums/ue_ue.EAIRequestPriority.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[GetActionPriority](ue_ue.PawnAction.md#getactionpriority)

#### Defined in

[ue/ue.d.ts:14833](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14833)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[GetClass](ue_ue.PawnAction.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[GetName](ue_ue.PawnAction.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[GetOuter](ue_ue.PawnAction.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[GetWorld](ue_ue.PawnAction.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

[ue/ue.d.ts:14834](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14834)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PawnAction_Move`](ue_ue.PawnAction_Move.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PawnAction_Move`](ue_ue.PawnAction_Move.md)

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[Find](ue_ue.PawnAction.md#find)

#### Defined in

[ue/ue.d.ts:56957](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56957)

___

### Load

▸ `Static` **Load**(`InName`): [`PawnAction_Move`](ue_ue.PawnAction_Move.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PawnAction_Move`](ue_ue.PawnAction_Move.md)

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[Load](ue_ue.PawnAction.md#load)

#### Defined in

[ue/ue.d.ts:56958](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56958)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[StaticClass](ue_ue.PawnAction.md#staticclass)

#### Defined in

[ue/ue.d.ts:56956](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56956)
