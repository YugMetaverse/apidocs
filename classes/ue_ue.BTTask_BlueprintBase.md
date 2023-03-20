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

## Properties

### AIOwner

• **AIOwner**: [`AIController`](ue_ue.AIController.md)

___

### ActorOwner

• **ActorOwner**: [`Actor`](ue_ue.Actor.md)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[NodeName](ue_ue.BTTaskNode.md#nodename)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[ParentNode](ue_ue.BTTaskNode.md#parentnode)

___

### Services

• **Services**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BTService`](ue_ue.BTService.md)\>

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[Services](ue_ue.BTTaskNode.md#services)

___

### TickInterval

• **TickInterval**: [`IntervalCountdown`](ue_ue.IntervalCountdown.md)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[TreeAsset](ue_ue.BTTaskNode.md#treeasset)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_BTNode__](ue_ue.BTTaskNode.md#__tid_btnode__)

___

### \_\_tid\_BTTaskNode\_\_

• **\_\_tid\_BTTaskNode\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_BTTaskNode__](ue_ue.BTTaskNode.md#__tid_bttasknode__)

___

### \_\_tid\_BTTask\_BlueprintBase\_\_

• **\_\_tid\_BTTask\_BlueprintBase\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[__tid_Object__](ue_ue.BTTaskNode.md#__tid_object__)

___

### bIgnoreRestartSelf

• **bIgnoreRestartSelf**: `boolean`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[bIgnoreRestartSelf](ue_ue.BTTaskNode.md#bignorerestartself)

___

### bShowPropertyDetails

• **bShowPropertyDetails**: `boolean`

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

___

### FinishAbort

▸ **FinishAbort**(): `void`

#### Returns

`void`

___

### FinishExecute

▸ **FinishExecute**(`bSuccess`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bSuccess` | `boolean` |

#### Returns

`void`

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetClass](ue_ue.BTTaskNode.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetName](ue_ue.BTTaskNode.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetOuter](ue_ue.BTTaskNode.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTTaskNode](ue_ue.BTTaskNode.md).[GetWorld](ue_ue.BTTaskNode.md#getworld)

___

### IsTaskAborting

▸ **IsTaskAborting**(): `boolean`

#### Returns

`boolean`

___

### IsTaskExecuting

▸ **IsTaskExecuting**(): `boolean`

#### Returns

`boolean`

___

### ReceiveAbort

▸ **ReceiveAbort**(`OwnerActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

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

___

### ReceiveExecute

▸ **ReceiveExecute**(`OwnerActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

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

___

### SetFinishOnMessage

▸ **SetFinishOnMessage**(`MessageName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MessageName` | `string` |

#### Returns

`void`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTTaskNode](ue_ue.BTTaskNode.md).[StaticClass](ue_ue.BTTaskNode.md#staticclass)
