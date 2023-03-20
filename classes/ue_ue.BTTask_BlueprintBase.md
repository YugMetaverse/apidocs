[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTTask\_BlueprintBase

# Class: BTTask\_BlueprintBase

[ue/ue](../modules/ue_ue.md).BTTask_BlueprintBase

## Hierarchy

- [`BTTaskNode`](ue_ue.BTTaskNode.md)

  ↳ **`BTTask_BlueprintBase`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTTask_BlueprintBase.md#constructor)

### Properties

- [AIOwner](ue_ue.BTTask_BlueprintBase.md#aiowner)
- [ActorOwner](ue_ue.BTTask_BlueprintBase.md#actorowner)
- [NodeName](ue_ue.BTTask_BlueprintBase.md#nodename)
- [ParentNode](ue_ue.BTTask_BlueprintBase.md#parentnode)
- [Services](ue_ue.BTTask_BlueprintBase.md#services)
- [TickInterval](ue_ue.BTTask_BlueprintBase.md#tickinterval)
- [TreeAsset](ue_ue.BTTask_BlueprintBase.md#treeasset)
- [\_\_tid\_BTNode\_\_](ue_ue.BTTask_BlueprintBase.md#__tid_btnode__)
- [\_\_tid\_BTTaskNode\_\_](ue_ue.BTTask_BlueprintBase.md#__tid_bttasknode__)
- [\_\_tid\_BTTask\_BlueprintBase\_\_](ue_ue.BTTask_BlueprintBase.md#__tid_bttask_blueprintbase__)
- [\_\_tid\_Object\_\_](ue_ue.BTTask_BlueprintBase.md#__tid_object__)
- [bIgnoreRestartSelf](ue_ue.BTTask_BlueprintBase.md#bignorerestartself)
- [bShowPropertyDetails](ue_ue.BTTask_BlueprintBase.md#bshowpropertydetails)

### Methods

- [CreateDefaultSubobject](ue_ue.BTTask_BlueprintBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTTask_BlueprintBase.md#executeubergraph)
- [FinishAbort](ue_ue.BTTask_BlueprintBase.md#finishabort)
- [FinishExecute](ue_ue.BTTask_BlueprintBase.md#finishexecute)
- [GetClass](ue_ue.BTTask_BlueprintBase.md#getclass)
- [GetName](ue_ue.BTTask_BlueprintBase.md#getname)
- [GetOuter](ue_ue.BTTask_BlueprintBase.md#getouter)
- [GetWorld](ue_ue.BTTask_BlueprintBase.md#getworld)
- [IsTaskAborting](ue_ue.BTTask_BlueprintBase.md#istaskaborting)
- [IsTaskExecuting](ue_ue.BTTask_BlueprintBase.md#istaskexecuting)
- [ReceiveAbort](ue_ue.BTTask_BlueprintBase.md#receiveabort)
- [ReceiveAbortAI](ue_ue.BTTask_BlueprintBase.md#receiveabortai)
- [ReceiveExecute](ue_ue.BTTask_BlueprintBase.md#receiveexecute)
- [ReceiveExecuteAI](ue_ue.BTTask_BlueprintBase.md#receiveexecuteai)
- [ReceiveTick](ue_ue.BTTask_BlueprintBase.md#receivetick)
- [ReceiveTickAI](ue_ue.BTTask_BlueprintBase.md#receivetickai)
- [SetFinishOnMessage](ue_ue.BTTask_BlueprintBase.md#setfinishonmessage)
- [SetFinishOnMessageWithId](ue_ue.BTTask_BlueprintBase.md#setfinishonmessagewithid)
- [Find](ue_ue.BTTask_BlueprintBase.md#find)
- [Load](ue_ue.BTTask_BlueprintBase.md#load)
- [StaticClass](ue_ue.BTTask_BlueprintBase.md#staticclass)

## Constructors

### constructor

• **new BTTask_BlueprintBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[constructor](ue_ue.BTTaskNode.md#constructor)

#### Defined in

[ue/ue.d.ts:25243](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25243)

## Properties

### AIOwner

• **AIOwner**: [`AIController`](ue_ue.AIController.md)

#### Defined in

[ue/ue.d.ts:25244](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25244)

___

### ActorOwner

• **ActorOwner**: [`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:25245](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25245)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[NodeName](ue_ue.BTTaskNode.md#nodename)

#### Defined in

[ue/ue.d.ts:14567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14567)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[ParentNode](ue_ue.BTTaskNode.md#parentnode)

#### Defined in

[ue/ue.d.ts:14569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14569)

___

### Services

• **Services**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTService`](ue_ue.BTService.md)\>

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[Services](ue_ue.BTTaskNode.md#services)

#### Defined in

[ue/ue.d.ts:14601](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14601)

___

### TickInterval

• **TickInterval**: [`IntervalCountdown`](ue_ue.IntervalCountdown.md)

#### Defined in

[ue/ue.d.ts:25246](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25246)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[TreeAsset](ue_ue.BTTaskNode.md#treeasset)

#### Defined in

[ue/ue.d.ts:14568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14568)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_BTNode__](ue_ue.BTTaskNode.md#__tid_btnode__)

#### Defined in

[ue/ue.d.ts:14574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14574)

___

### \_\_tid\_BTTaskNode\_\_

• **\_\_tid\_BTTaskNode\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_BTTaskNode__](ue_ue.BTTaskNode.md#__tid_bttasknode__)

#### Defined in

[ue/ue.d.ts:14607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14607)

___

### \_\_tid\_BTTask\_BlueprintBase\_\_

• **\_\_tid\_BTTask\_BlueprintBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:25264](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25264)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_Object__](ue_ue.BTTaskNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bIgnoreRestartSelf

• **bIgnoreRestartSelf**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[bIgnoreRestartSelf](ue_ue.BTTaskNode.md#bignorerestartself)

#### Defined in

[ue/ue.d.ts:14602](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14602)

___

### bShowPropertyDetails

• **bShowPropertyDetails**: `boolean`

#### Defined in

[ue/ue.d.ts:25247](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25247)

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

[BTTaskNode](ue_ue.BTTaskNode.md).[CreateDefaultSubobject](ue_ue.BTTaskNode.md#createdefaultsubobject)

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

[BTTaskNode](ue_ue.BTTaskNode.md).[ExecuteUbergraph](ue_ue.BTTaskNode.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### FinishAbort

▸ **FinishAbort**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:25248](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25248)

___

### FinishExecute

▸ **FinishExecute**(`bSuccess`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bSuccess` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:25249](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25249)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetClass](ue_ue.BTTaskNode.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetName](ue_ue.BTTaskNode.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetOuter](ue_ue.BTTaskNode.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetWorld](ue_ue.BTTaskNode.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsTaskAborting

▸ **IsTaskAborting**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:25250](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25250)

___

### IsTaskExecuting

▸ **IsTaskExecuting**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:25251](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25251)

___

### ReceiveAbort

▸ **ReceiveAbort**(`OwnerActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:25252](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25252)

___

### ReceiveAbortAI

▸ **ReceiveAbortAI**(`OwnerController`, `ControlledPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AIController`](ue_ue.AIController.md)\> |
| `ControlledPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:25253](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25253)

___

### ReceiveExecute

▸ **ReceiveExecute**(`OwnerActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:25254](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25254)

___

### ReceiveExecuteAI

▸ **ReceiveExecuteAI**(`OwnerController`, `ControlledPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AIController`](ue_ue.AIController.md)\> |
| `ControlledPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:25255](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25255)

___

### ReceiveTick

▸ **ReceiveTick**(`OwnerActor`, `DeltaSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `DeltaSeconds` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:25256](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25256)

___

### ReceiveTickAI

▸ **ReceiveTickAI**(`OwnerController`, `ControlledPawn`, `DeltaSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AIController`](ue_ue.AIController.md)\> |
| `ControlledPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |
| `DeltaSeconds` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:25257](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25257)

___

### SetFinishOnMessage

▸ **SetFinishOnMessage**(`MessageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MessageName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:25258](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25258)

___

### SetFinishOnMessageWithId

▸ **SetFinishOnMessageWithId**(`MessageName`, `RequestID?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MessageName` | `string` |
| `RequestID?` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:25259](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25259)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTTask_BlueprintBase`](ue_ue.BTTask_BlueprintBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTTask_BlueprintBase`](ue_ue.BTTask_BlueprintBase.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[Find](ue_ue.BTTaskNode.md#find)

#### Defined in

[ue/ue.d.ts:25261](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25261)

___

### Load

▸ `Static` **Load**(`InName`): [`BTTask_BlueprintBase`](ue_ue.BTTask_BlueprintBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTTask_BlueprintBase`](ue_ue.BTTask_BlueprintBase.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[Load](ue_ue.BTTaskNode.md#load)

#### Defined in

[ue/ue.d.ts:25262](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25262)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[StaticClass](ue_ue.BTTaskNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:25260](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25260)
