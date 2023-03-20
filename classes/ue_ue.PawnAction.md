[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PawnAction

# Class: PawnAction

[ue/ue](../modules/ue_ue.md).PawnAction

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PawnAction`**

  ↳↳ [`PawnAction_BlueprintBase`](ue_ue.PawnAction_BlueprintBase.md)

  ↳↳ [`PawnAction_Move`](ue_ue.PawnAction_Move.md)

  ↳↳ [`PawnAction_Repeat`](ue_ue.PawnAction_Repeat.md)

  ↳↳ [`PawnAction_Sequence`](ue_ue.PawnAction_Sequence.md)

  ↳↳ [`PawnAction_Wait`](ue_ue.PawnAction_Wait.md)

  ↳↳ [`TestPawnAction_Log`](ue_ue.TestPawnAction_Log.md)

## Table of contents

### Constructors

- [constructor](ue_ue.PawnAction.md#constructor)

### Properties

- [BrainComp](ue_ue.PawnAction.md#braincomp)
- [ChildAction](ue_ue.PawnAction.md#childaction)
- [Instigator](ue_ue.PawnAction.md#instigator)
- [OwnerComponent](ue_ue.PawnAction.md#ownercomponent)
- [ParentAction](ue_ue.PawnAction.md#parentaction)
- [\_\_tid\_Object\_\_](ue_ue.PawnAction.md#__tid_object__)
- [\_\_tid\_PawnAction\_\_](ue_ue.PawnAction.md#__tid_pawnaction__)
- [bAllowNewSameClassInstance](ue_ue.PawnAction.md#ballownewsameclassinstance)
- [bAlwaysNotifyOnFinished](ue_ue.PawnAction.md#balwaysnotifyonfinished)
- [bReplaceActiveSameClassInstance](ue_ue.PawnAction.md#breplaceactivesameclassinstance)
- [bShouldPauseMovement](ue_ue.PawnAction.md#bshouldpausemovement)

### Methods

- [CreateDefaultSubobject](ue_ue.PawnAction.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PawnAction.md#executeubergraph)
- [Finish](ue_ue.PawnAction.md#finish)
- [GetActionPriority](ue_ue.PawnAction.md#getactionpriority)
- [GetClass](ue_ue.PawnAction.md#getclass)
- [GetName](ue_ue.PawnAction.md#getname)
- [GetOuter](ue_ue.PawnAction.md#getouter)
- [GetWorld](ue_ue.PawnAction.md#getworld)
- [CreateActionInstance](ue_ue.PawnAction.md#createactioninstance)
- [Find](ue_ue.PawnAction.md#find)
- [Load](ue_ue.PawnAction.md#load)
- [StaticClass](ue_ue.PawnAction.md#staticclass)

## Constructors

### constructor

• **new PawnAction**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:14822](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14822)

## Properties

### BrainComp

• **BrainComp**: [`BrainComponent`](ue_ue.BrainComponent.md)

#### Defined in

[ue/ue.d.ts:14827](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14827)

___

### ChildAction

• **ChildAction**: [`PawnAction`](ue_ue.PawnAction.md)

#### Defined in

[ue/ue.d.ts:14823](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14823)

___

### Instigator

• **Instigator**: [`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:14826](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14826)

___

### OwnerComponent

• **OwnerComponent**: [`PawnActionsComponent`](ue_ue.PawnActionsComponent.md)

#### Defined in

[ue/ue.d.ts:14825](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14825)

___

### ParentAction

• **ParentAction**: [`PawnAction`](ue_ue.PawnAction.md)

#### Defined in

[ue/ue.d.ts:14824](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14824)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PawnAction\_\_

• **\_\_tid\_PawnAction\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14839](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14839)

___

### bAllowNewSameClassInstance

• **bAllowNewSameClassInstance**: `boolean`

#### Defined in

[ue/ue.d.ts:14828](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14828)

___

### bAlwaysNotifyOnFinished

• **bAlwaysNotifyOnFinished**: `boolean`

#### Defined in

[ue/ue.d.ts:14831](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14831)

___

### bReplaceActiveSameClassInstance

• **bReplaceActiveSameClassInstance**: `boolean`

#### Defined in

[ue/ue.d.ts:14829](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14829)

___

### bShouldPauseMovement

• **bShouldPauseMovement**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

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

#### Defined in

[ue/ue.d.ts:14832](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14832)

___

### GetActionPriority

▸ **GetActionPriority**(): [`EAIRequestPriority`](../enums/ue_ue.EAIRequestPriority.md)

#### Returns

[`EAIRequestPriority`](../enums/ue_ue.EAIRequestPriority.md)

#### Defined in

[ue/ue.d.ts:14833](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14833)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

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

#### Defined in

[ue/ue.d.ts:14834](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14834)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PawnAction`](ue_ue.PawnAction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PawnAction`](ue_ue.PawnAction.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:14836](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14836)

___

### Load

▸ `Static` **Load**(`InName`): [`PawnAction`](ue_ue.PawnAction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PawnAction`](ue_ue.PawnAction.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:14837](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14837)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:14835](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14835)
