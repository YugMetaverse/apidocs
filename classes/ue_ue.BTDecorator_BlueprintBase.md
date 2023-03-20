[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTDecorator\_BlueprintBase

# Class: BTDecorator\_BlueprintBase

[ue/ue](../modules/ue_ue.md).BTDecorator_BlueprintBase

## Hierarchy

- [`BTDecorator`](ue_ue.BTDecorator.md)

  ↳ **`BTDecorator_BlueprintBase`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTDecorator_BlueprintBase.md#constructor)

### Properties

- [AIOwner](ue_ue.BTDecorator_BlueprintBase.md#aiowner)
- [ActorOwner](ue_ue.BTDecorator_BlueprintBase.md#actorowner)
- [FlowAbortMode](ue_ue.BTDecorator_BlueprintBase.md#flowabortmode)
- [NodeName](ue_ue.BTDecorator_BlueprintBase.md#nodename)
- [ObservedKeyNames](ue_ue.BTDecorator_BlueprintBase.md#observedkeynames)
- [ParentNode](ue_ue.BTDecorator_BlueprintBase.md#parentnode)
- [TreeAsset](ue_ue.BTDecorator_BlueprintBase.md#treeasset)
- [\_\_tid\_BTAuxiliaryNode\_\_](ue_ue.BTDecorator_BlueprintBase.md#__tid_btauxiliarynode__)
- [\_\_tid\_BTDecorator\_BlueprintBase\_\_](ue_ue.BTDecorator_BlueprintBase.md#__tid_btdecorator_blueprintbase__)
- [\_\_tid\_BTDecorator\_\_](ue_ue.BTDecorator_BlueprintBase.md#__tid_btdecorator__)
- [\_\_tid\_BTNode\_\_](ue_ue.BTDecorator_BlueprintBase.md#__tid_btnode__)
- [\_\_tid\_Object\_\_](ue_ue.BTDecorator_BlueprintBase.md#__tid_object__)
- [bCheckConditionOnlyBlackBoardChanges](ue_ue.BTDecorator_BlueprintBase.md#bcheckconditiononlyblackboardchanges)
- [bInverseCondition](ue_ue.BTDecorator_BlueprintBase.md#binversecondition)
- [bIsObservingBB](ue_ue.BTDecorator_BlueprintBase.md#bisobservingbb)
- [bShowPropertyDetails](ue_ue.BTDecorator_BlueprintBase.md#bshowpropertydetails)

### Methods

- [CreateDefaultSubobject](ue_ue.BTDecorator_BlueprintBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTDecorator_BlueprintBase.md#executeubergraph)
- [GetClass](ue_ue.BTDecorator_BlueprintBase.md#getclass)
- [GetName](ue_ue.BTDecorator_BlueprintBase.md#getname)
- [GetOuter](ue_ue.BTDecorator_BlueprintBase.md#getouter)
- [GetWorld](ue_ue.BTDecorator_BlueprintBase.md#getworld)
- [IsDecoratorExecutionActive](ue_ue.BTDecorator_BlueprintBase.md#isdecoratorexecutionactive)
- [IsDecoratorObserverActive](ue_ue.BTDecorator_BlueprintBase.md#isdecoratorobserveractive)
- [PerformConditionCheck](ue_ue.BTDecorator_BlueprintBase.md#performconditioncheck)
- [PerformConditionCheckAI](ue_ue.BTDecorator_BlueprintBase.md#performconditioncheckai)
- [ReceiveExecutionFinish](ue_ue.BTDecorator_BlueprintBase.md#receiveexecutionfinish)
- [ReceiveExecutionFinishAI](ue_ue.BTDecorator_BlueprintBase.md#receiveexecutionfinishai)
- [ReceiveExecutionStart](ue_ue.BTDecorator_BlueprintBase.md#receiveexecutionstart)
- [ReceiveExecutionStartAI](ue_ue.BTDecorator_BlueprintBase.md#receiveexecutionstartai)
- [ReceiveObserverActivated](ue_ue.BTDecorator_BlueprintBase.md#receiveobserveractivated)
- [ReceiveObserverActivatedAI](ue_ue.BTDecorator_BlueprintBase.md#receiveobserveractivatedai)
- [ReceiveObserverDeactivated](ue_ue.BTDecorator_BlueprintBase.md#receiveobserverdeactivated)
- [ReceiveObserverDeactivatedAI](ue_ue.BTDecorator_BlueprintBase.md#receiveobserverdeactivatedai)
- [ReceiveTick](ue_ue.BTDecorator_BlueprintBase.md#receivetick)
- [ReceiveTickAI](ue_ue.BTDecorator_BlueprintBase.md#receivetickai)
- [Find](ue_ue.BTDecorator_BlueprintBase.md#find)
- [Load](ue_ue.BTDecorator_BlueprintBase.md#load)
- [StaticClass](ue_ue.BTDecorator_BlueprintBase.md#staticclass)

## Constructors

### constructor

• **new BTDecorator_BlueprintBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTDecorator](ue_ue.BTDecorator.md).[constructor](ue_ue.BTDecorator.md#constructor)

## Properties

### AIOwner

• **AIOwner**: [`AIController`](ue_ue.AIController.md)

___

### ActorOwner

• **ActorOwner**: [`Actor`](ue_ue.Actor.md)

___

### FlowAbortMode

• **FlowAbortMode**: [`EBTFlowAbortMode`](../enums/ue_ue.EBTFlowAbortMode.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[FlowAbortMode](ue_ue.BTDecorator.md#flowabortmode)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[NodeName](ue_ue.BTDecorator.md#nodename)

___

### ObservedKeyNames

• **ObservedKeyNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[ParentNode](ue_ue.BTDecorator.md#parentnode)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[TreeAsset](ue_ue.BTDecorator.md#treeasset)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[__tid_BTAuxiliaryNode__](ue_ue.BTDecorator.md#__tid_btauxiliarynode__)

___

### \_\_tid\_BTDecorator\_BlueprintBase\_\_

• **\_\_tid\_BTDecorator\_BlueprintBase\_\_**: `boolean`

___

### \_\_tid\_BTDecorator\_\_

• **\_\_tid\_BTDecorator\_\_**: `boolean`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[__tid_BTDecorator__](ue_ue.BTDecorator.md#__tid_btdecorator__)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[__tid_BTNode__](ue_ue.BTDecorator.md#__tid_btnode__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[__tid_Object__](ue_ue.BTDecorator.md#__tid_object__)

___

### bCheckConditionOnlyBlackBoardChanges

• **bCheckConditionOnlyBlackBoardChanges**: `boolean`

___

### bInverseCondition

• **bInverseCondition**: `boolean`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[bInverseCondition](ue_ue.BTDecorator.md#binversecondition)

___

### bIsObservingBB

• **bIsObservingBB**: `boolean`

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

[BTDecorator](ue_ue.BTDecorator.md).[CreateDefaultSubobject](ue_ue.BTDecorator.md#createdefaultsubobject)

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

[BTDecorator](ue_ue.BTDecorator.md).[ExecuteUbergraph](ue_ue.BTDecorator.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[GetClass](ue_ue.BTDecorator.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[GetName](ue_ue.BTDecorator.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[GetOuter](ue_ue.BTDecorator.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[GetWorld](ue_ue.BTDecorator.md#getworld)

___

### IsDecoratorExecutionActive

▸ **IsDecoratorExecutionActive**(): `boolean`

#### Returns

`boolean`

___

### IsDecoratorObserverActive

▸ **IsDecoratorObserverActive**(): `boolean`

#### Returns

`boolean`

___

### PerformConditionCheck

▸ **PerformConditionCheck**(`OwnerActor`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`boolean`

___

### PerformConditionCheckAI

▸ **PerformConditionCheckAI**(`OwnerController`, `ControlledPawn`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AIController`](ue_ue.AIController.md)\> |
| `ControlledPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`boolean`

___

### ReceiveExecutionFinish

▸ **ReceiveExecutionFinish**(`OwnerActor`, `NodeResult`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `NodeResult` | [`EBTNodeResult`](../enums/ue_ue.EBTNodeResult.md) |

#### Returns

`void`

___

### ReceiveExecutionFinishAI

▸ **ReceiveExecutionFinishAI**(`OwnerController`, `ControlledPawn`, `NodeResult`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AIController`](ue_ue.AIController.md)\> |
| `ControlledPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |
| `NodeResult` | [`EBTNodeResult`](../enums/ue_ue.EBTNodeResult.md) |

#### Returns

`void`

___

### ReceiveExecutionStart

▸ **ReceiveExecutionStart**(`OwnerActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### ReceiveExecutionStartAI

▸ **ReceiveExecutionStartAI**(`OwnerController`, `ControlledPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AIController`](ue_ue.AIController.md)\> |
| `ControlledPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

___

### ReceiveObserverActivated

▸ **ReceiveObserverActivated**(`OwnerActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### ReceiveObserverActivatedAI

▸ **ReceiveObserverActivatedAI**(`OwnerController`, `ControlledPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AIController`](ue_ue.AIController.md)\> |
| `ControlledPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

___

### ReceiveObserverDeactivated

▸ **ReceiveObserverDeactivated**(`OwnerActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### ReceiveObserverDeactivatedAI

▸ **ReceiveObserverDeactivatedAI**(`OwnerController`, `ControlledPawn`): `void`

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTDecorator_BlueprintBase`](ue_ue.BTDecorator_BlueprintBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTDecorator_BlueprintBase`](ue_ue.BTDecorator_BlueprintBase.md)

#### Overrides

[BTDecorator](ue_ue.BTDecorator.md).[Find](ue_ue.BTDecorator.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BTDecorator_BlueprintBase`](ue_ue.BTDecorator_BlueprintBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTDecorator_BlueprintBase`](ue_ue.BTDecorator_BlueprintBase.md)

#### Overrides

[BTDecorator](ue_ue.BTDecorator.md).[Load](ue_ue.BTDecorator.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTDecorator](ue_ue.BTDecorator.md).[StaticClass](ue_ue.BTDecorator.md#staticclass)
