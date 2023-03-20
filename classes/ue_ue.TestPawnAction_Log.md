[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TestPawnAction\_Log

# Class: TestPawnAction\_Log

[ue/ue](../modules/ue_ue.md).TestPawnAction_Log

## Hierarchy

- [`PawnAction`](ue_ue.PawnAction.md)

  ↳ **`TestPawnAction_Log`**

  ↳↳ [`TestPawnAction_CallFunction`](ue_ue.TestPawnAction_CallFunction.md)

## Table of contents

### Constructors

- [constructor](ue_ue.TestPawnAction_Log.md#constructor)

### Properties

- [BrainComp](ue_ue.TestPawnAction_Log.md#braincomp)
- [ChildAction](ue_ue.TestPawnAction_Log.md#childaction)
- [Instigator](ue_ue.TestPawnAction_Log.md#instigator)
- [OwnerComponent](ue_ue.TestPawnAction_Log.md#ownercomponent)
- [ParentAction](ue_ue.TestPawnAction_Log.md#parentaction)
- [\_\_tid\_Object\_\_](ue_ue.TestPawnAction_Log.md#__tid_object__)
- [\_\_tid\_PawnAction\_\_](ue_ue.TestPawnAction_Log.md#__tid_pawnaction__)
- [\_\_tid\_TestPawnAction\_Log\_\_](ue_ue.TestPawnAction_Log.md#__tid_testpawnaction_log__)
- [bAllowNewSameClassInstance](ue_ue.TestPawnAction_Log.md#ballownewsameclassinstance)
- [bAlwaysNotifyOnFinished](ue_ue.TestPawnAction_Log.md#balwaysnotifyonfinished)
- [bReplaceActiveSameClassInstance](ue_ue.TestPawnAction_Log.md#breplaceactivesameclassinstance)
- [bShouldPauseMovement](ue_ue.TestPawnAction_Log.md#bshouldpausemovement)

### Methods

- [CreateDefaultSubobject](ue_ue.TestPawnAction_Log.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TestPawnAction_Log.md#executeubergraph)
- [Finish](ue_ue.TestPawnAction_Log.md#finish)
- [GetActionPriority](ue_ue.TestPawnAction_Log.md#getactionpriority)
- [GetClass](ue_ue.TestPawnAction_Log.md#getclass)
- [GetName](ue_ue.TestPawnAction_Log.md#getname)
- [GetOuter](ue_ue.TestPawnAction_Log.md#getouter)
- [GetWorld](ue_ue.TestPawnAction_Log.md#getworld)
- [CreateActionInstance](ue_ue.TestPawnAction_Log.md#createactioninstance)
- [Find](ue_ue.TestPawnAction_Log.md#find)
- [Load](ue_ue.TestPawnAction_Log.md#load)
- [StaticClass](ue_ue.TestPawnAction_Log.md#staticclass)

## Constructors

### constructor

• **new TestPawnAction_Log**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[__tid_Object__](ue_ue.PawnAction.md#__tid_object__)

___

### \_\_tid\_PawnAction\_\_

• **\_\_tid\_PawnAction\_\_**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[__tid_PawnAction__](ue_ue.PawnAction.md#__tid_pawnaction__)

___

### \_\_tid\_TestPawnAction\_Log\_\_

• **\_\_tid\_TestPawnAction\_Log\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TestPawnAction_Log`](ue_ue.TestPawnAction_Log.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TestPawnAction_Log`](ue_ue.TestPawnAction_Log.md)

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[Find](ue_ue.PawnAction.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TestPawnAction_Log`](ue_ue.TestPawnAction_Log.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TestPawnAction_Log`](ue_ue.TestPawnAction_Log.md)

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[Load](ue_ue.PawnAction.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[StaticClass](ue_ue.PawnAction.md#staticclass)
