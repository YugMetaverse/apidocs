[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PawnAction\_Wait

# Class: PawnAction\_Wait

[ue/ue](../modules/ue_ue.md).PawnAction_Wait

## Hierarchy

- [`PawnAction`](ue_ue.PawnAction.md)

  ↳ **`PawnAction_Wait`**

## Table of contents

### Constructors

- [constructor](ue_ue.PawnAction_Wait.md#constructor)

### Properties

- [BrainComp](ue_ue.PawnAction_Wait.md#braincomp)
- [ChildAction](ue_ue.PawnAction_Wait.md#childaction)
- [Instigator](ue_ue.PawnAction_Wait.md#instigator)
- [OwnerComponent](ue_ue.PawnAction_Wait.md#ownercomponent)
- [ParentAction](ue_ue.PawnAction_Wait.md#parentaction)
- [TimeToWait](ue_ue.PawnAction_Wait.md#timetowait)
- [\_\_tid\_Object\_\_](ue_ue.PawnAction_Wait.md#__tid_object__)
- [\_\_tid\_PawnAction\_Wait\_\_](ue_ue.PawnAction_Wait.md#__tid_pawnaction_wait__)
- [\_\_tid\_PawnAction\_\_](ue_ue.PawnAction_Wait.md#__tid_pawnaction__)
- [bAllowNewSameClassInstance](ue_ue.PawnAction_Wait.md#ballownewsameclassinstance)
- [bAlwaysNotifyOnFinished](ue_ue.PawnAction_Wait.md#balwaysnotifyonfinished)
- [bReplaceActiveSameClassInstance](ue_ue.PawnAction_Wait.md#breplaceactivesameclassinstance)
- [bShouldPauseMovement](ue_ue.PawnAction_Wait.md#bshouldpausemovement)

### Methods

- [CreateDefaultSubobject](ue_ue.PawnAction_Wait.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PawnAction_Wait.md#executeubergraph)
- [Finish](ue_ue.PawnAction_Wait.md#finish)
- [GetActionPriority](ue_ue.PawnAction_Wait.md#getactionpriority)
- [GetClass](ue_ue.PawnAction_Wait.md#getclass)
- [GetName](ue_ue.PawnAction_Wait.md#getname)
- [GetOuter](ue_ue.PawnAction_Wait.md#getouter)
- [GetWorld](ue_ue.PawnAction_Wait.md#getworld)
- [CreateActionInstance](ue_ue.PawnAction_Wait.md#createactioninstance)
- [Find](ue_ue.PawnAction_Wait.md#find)
- [Load](ue_ue.PawnAction_Wait.md#load)
- [StaticClass](ue_ue.PawnAction_Wait.md#staticclass)

## Constructors

### constructor

• **new PawnAction_Wait**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[constructor](ue_ue.PawnAction.md#constructor)

## Properties

### BrainComp

• **BrainComp**: [`BrainComponent`](ue_ue.BrainComponent.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[BrainComp](ue_ue.PawnAction.md#braincomp)

___

### ChildAction

• **ChildAction**: [`PawnAction`](ue_ue.PawnAction.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[ChildAction](ue_ue.PawnAction.md#childaction)

___

### Instigator

• **Instigator**: [`Object`](ue_ue.Object.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[Instigator](ue_ue.PawnAction.md#instigator)

___

### OwnerComponent

• **OwnerComponent**: [`PawnActionsComponent`](ue_ue.PawnActionsComponent.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[OwnerComponent](ue_ue.PawnAction.md#ownercomponent)

___

### ParentAction

• **ParentAction**: [`PawnAction`](ue_ue.PawnAction.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[ParentAction](ue_ue.PawnAction.md#parentaction)

___

### TimeToWait

• **TimeToWait**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[__tid_Object__](ue_ue.PawnAction.md#__tid_object__)

___

### \_\_tid\_PawnAction\_Wait\_\_

• **\_\_tid\_PawnAction\_Wait\_\_**: `boolean`

___

### \_\_tid\_PawnAction\_\_

• **\_\_tid\_PawnAction\_\_**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[__tid_PawnAction__](ue_ue.PawnAction.md#__tid_pawnaction__)

___

### bAllowNewSameClassInstance

• **bAllowNewSameClassInstance**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[bAllowNewSameClassInstance](ue_ue.PawnAction.md#ballownewsameclassinstance)

___

### bAlwaysNotifyOnFinished

• **bAlwaysNotifyOnFinished**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[bAlwaysNotifyOnFinished](ue_ue.PawnAction.md#balwaysnotifyonfinished)

___

### bReplaceActiveSameClassInstance

• **bReplaceActiveSameClassInstance**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[bReplaceActiveSameClassInstance](ue_ue.PawnAction.md#breplaceactivesameclassinstance)

___

### bShouldPauseMovement

• **bShouldPauseMovement**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[bShouldPauseMovement](ue_ue.PawnAction.md#bshouldpausemovement)

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

___

### GetActionPriority

▸ **GetActionPriority**(): [`EAIRequestPriority`](../enums/ue_ue.EAIRequestPriority.md)

#### Returns

[`EAIRequestPriority`](../enums/ue_ue.EAIRequestPriority.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[GetActionPriority](ue_ue.PawnAction.md#getactionpriority)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[GetClass](ue_ue.PawnAction.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[GetName](ue_ue.PawnAction.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[GetOuter](ue_ue.PawnAction.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[GetWorld](ue_ue.PawnAction.md#getworld)

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

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PawnAction_Wait`](ue_ue.PawnAction_Wait.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PawnAction_Wait`](ue_ue.PawnAction_Wait.md)

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[Find](ue_ue.PawnAction.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PawnAction_Wait`](ue_ue.PawnAction_Wait.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PawnAction_Wait`](ue_ue.PawnAction_Wait.md)

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[Load](ue_ue.PawnAction.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[StaticClass](ue_ue.PawnAction.md#staticclass)
