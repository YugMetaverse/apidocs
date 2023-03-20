[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PawnAction\_BlueprintBase

# Class: PawnAction\_BlueprintBase

[ue/ue](../modules/ue_ue.md).PawnAction_BlueprintBase

## Hierarchy

- [`PawnAction`](ue_ue.PawnAction.md)

  ↳ **`PawnAction_BlueprintBase`**

## Table of contents

### Constructors

- [constructor](ue_ue.PawnAction_BlueprintBase.md#constructor)

### Properties

- [BrainComp](ue_ue.PawnAction_BlueprintBase.md#braincomp)
- [ChildAction](ue_ue.PawnAction_BlueprintBase.md#childaction)
- [Instigator](ue_ue.PawnAction_BlueprintBase.md#instigator)
- [OwnerComponent](ue_ue.PawnAction_BlueprintBase.md#ownercomponent)
- [ParentAction](ue_ue.PawnAction_BlueprintBase.md#parentaction)
- [\_\_tid\_Object\_\_](ue_ue.PawnAction_BlueprintBase.md#__tid_object__)
- [\_\_tid\_PawnAction\_BlueprintBase\_\_](ue_ue.PawnAction_BlueprintBase.md#__tid_pawnaction_blueprintbase__)
- [\_\_tid\_PawnAction\_\_](ue_ue.PawnAction_BlueprintBase.md#__tid_pawnaction__)
- [bAllowNewSameClassInstance](ue_ue.PawnAction_BlueprintBase.md#ballownewsameclassinstance)
- [bAlwaysNotifyOnFinished](ue_ue.PawnAction_BlueprintBase.md#balwaysnotifyonfinished)
- [bReplaceActiveSameClassInstance](ue_ue.PawnAction_BlueprintBase.md#breplaceactivesameclassinstance)
- [bShouldPauseMovement](ue_ue.PawnAction_BlueprintBase.md#bshouldpausemovement)

### Methods

- [ActionFinished](ue_ue.PawnAction_BlueprintBase.md#actionfinished)
- [ActionPause](ue_ue.PawnAction_BlueprintBase.md#actionpause)
- [ActionResume](ue_ue.PawnAction_BlueprintBase.md#actionresume)
- [ActionStart](ue_ue.PawnAction_BlueprintBase.md#actionstart)
- [ActionTick](ue_ue.PawnAction_BlueprintBase.md#actiontick)
- [CreateDefaultSubobject](ue_ue.PawnAction_BlueprintBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PawnAction_BlueprintBase.md#executeubergraph)
- [Finish](ue_ue.PawnAction_BlueprintBase.md#finish)
- [GetActionPriority](ue_ue.PawnAction_BlueprintBase.md#getactionpriority)
- [GetClass](ue_ue.PawnAction_BlueprintBase.md#getclass)
- [GetName](ue_ue.PawnAction_BlueprintBase.md#getname)
- [GetOuter](ue_ue.PawnAction_BlueprintBase.md#getouter)
- [GetWorld](ue_ue.PawnAction_BlueprintBase.md#getworld)
- [CreateActionInstance](ue_ue.PawnAction_BlueprintBase.md#createactioninstance)
- [Find](ue_ue.PawnAction_BlueprintBase.md#find)
- [Load](ue_ue.PawnAction_BlueprintBase.md#load)
- [StaticClass](ue_ue.PawnAction_BlueprintBase.md#staticclass)

## Constructors

### constructor

• **new PawnAction_BlueprintBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[constructor](ue_ue.PawnAction.md#constructor)

#### Defined in

[ue/ue.d.ts:56930](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56930)

## Properties

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

### \_\_tid\_PawnAction\_BlueprintBase\_\_

• **\_\_tid\_PawnAction\_BlueprintBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:56940](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56940)

___

### \_\_tid\_PawnAction\_\_

• **\_\_tid\_PawnAction\_\_**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[__tid_PawnAction__](ue_ue.PawnAction.md#__tid_pawnaction__)

#### Defined in

[ue/ue.d.ts:14839](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14839)

___

### bAllowNewSameClassInstance

• **bAllowNewSameClassInstance**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[bAllowNewSameClassInstance](ue_ue.PawnAction.md#ballownewsameclassinstance)

#### Defined in

[ue/ue.d.ts:14828](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14828)

___

### bAlwaysNotifyOnFinished

• **bAlwaysNotifyOnFinished**: `boolean`

#### Inherited from

[PawnAction](ue_ue.PawnAction.md).[bAlwaysNotifyOnFinished](ue_ue.PawnAction.md#balwaysnotifyonfinished)

#### Defined in

[ue/ue.d.ts:14831](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14831)

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

## Methods

### ActionFinished

▸ **ActionFinished**(`ControlledPawn`, `WithResult`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ControlledPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |
| `WithResult` | [`EPawnActionResult`](../enums/ue_ue.EPawnActionResult.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:56931](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56931)

___

### ActionPause

▸ **ActionPause**(`ControlledPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ControlledPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:56932](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56932)

___

### ActionResume

▸ **ActionResume**(`ControlledPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ControlledPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:56933](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56933)

___

### ActionStart

▸ **ActionStart**(`ControlledPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ControlledPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:56934](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56934)

___

### ActionTick

▸ **ActionTick**(`ControlledPawn`, `DeltaSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ControlledPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |
| `DeltaSeconds` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:56935](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56935)

___

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PawnAction_BlueprintBase`](ue_ue.PawnAction_BlueprintBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PawnAction_BlueprintBase`](ue_ue.PawnAction_BlueprintBase.md)

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[Find](ue_ue.PawnAction.md#find)

#### Defined in

[ue/ue.d.ts:56937](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56937)

___

### Load

▸ `Static` **Load**(`InName`): [`PawnAction_BlueprintBase`](ue_ue.PawnAction_BlueprintBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PawnAction_BlueprintBase`](ue_ue.PawnAction_BlueprintBase.md)

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[Load](ue_ue.PawnAction.md#load)

#### Defined in

[ue/ue.d.ts:56938](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56938)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PawnAction](ue_ue.PawnAction.md).[StaticClass](ue_ue.PawnAction.md#staticclass)

#### Defined in

[ue/ue.d.ts:56936](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L56936)
