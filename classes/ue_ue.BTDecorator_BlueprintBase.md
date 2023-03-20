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

#### Defined in

[ue/ue.d.ts:24893](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24893)

## Properties

### AIOwner

• **AIOwner**: [`AIController`](ue_ue.AIController.md)

#### Defined in

[ue/ue.d.ts:24894](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24894)

___

### ActorOwner

• **ActorOwner**: [`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:24895](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24895)

___

### FlowAbortMode

• **FlowAbortMode**: [`EBTFlowAbortMode`](../enums/ue_ue.EBTFlowAbortMode.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[FlowAbortMode](ue_ue.BTDecorator.md#flowabortmode)

#### Defined in

[ue/ue.d.ts:14614](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14614)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[NodeName](ue_ue.BTDecorator.md#nodename)

#### Defined in

[ue/ue.d.ts:14567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14567)

___

### ObservedKeyNames

• **ObservedKeyNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:24896](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24896)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[ParentNode](ue_ue.BTDecorator.md#parentnode)

#### Defined in

[ue/ue.d.ts:14569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14569)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[TreeAsset](ue_ue.BTDecorator.md#treeasset)

#### Defined in

[ue/ue.d.ts:14568](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14568)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[__tid_BTAuxiliaryNode__](ue_ue.BTDecorator.md#__tid_btauxiliarynode__)

#### Defined in

[ue/ue.d.ts:14583](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14583)

___

### \_\_tid\_BTDecorator\_BlueprintBase\_\_

• **\_\_tid\_BTDecorator\_BlueprintBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:24918](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24918)

___

### \_\_tid\_BTDecorator\_\_

• **\_\_tid\_BTDecorator\_\_**: `boolean`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[__tid_BTDecorator__](ue_ue.BTDecorator.md#__tid_btdecorator__)

#### Defined in

[ue/ue.d.ts:14619](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14619)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[__tid_BTNode__](ue_ue.BTDecorator.md#__tid_btnode__)

#### Defined in

[ue/ue.d.ts:14574](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14574)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[__tid_Object__](ue_ue.BTDecorator.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bCheckConditionOnlyBlackBoardChanges

• **bCheckConditionOnlyBlackBoardChanges**: `boolean`

#### Defined in

[ue/ue.d.ts:24898](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24898)

___

### bInverseCondition

• **bInverseCondition**: `boolean`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[bInverseCondition](ue_ue.BTDecorator.md#binversecondition)

#### Defined in

[ue/ue.d.ts:14613](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14613)

___

### bIsObservingBB

• **bIsObservingBB**: `boolean`

#### Defined in

[ue/ue.d.ts:24899](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24899)

___

### bShowPropertyDetails

• **bShowPropertyDetails**: `boolean`

#### Defined in

[ue/ue.d.ts:24897](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24897)

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

[BTDecorator](ue_ue.BTDecorator.md).[ExecuteUbergraph](ue_ue.BTDecorator.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[GetClass](ue_ue.BTDecorator.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[GetName](ue_ue.BTDecorator.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[GetOuter](ue_ue.BTDecorator.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTDecorator](ue_ue.BTDecorator.md).[GetWorld](ue_ue.BTDecorator.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsDecoratorExecutionActive

▸ **IsDecoratorExecutionActive**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:24900](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24900)

___

### IsDecoratorObserverActive

▸ **IsDecoratorObserverActive**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:24901](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24901)

___

### PerformConditionCheck

▸ **PerformConditionCheck**(`OwnerActor`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:24902](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24902)

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

#### Defined in

[ue/ue.d.ts:24903](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24903)

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

#### Defined in

[ue/ue.d.ts:24904](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24904)

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

#### Defined in

[ue/ue.d.ts:24905](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24905)

___

### ReceiveExecutionStart

▸ **ReceiveExecutionStart**(`OwnerActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:24906](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24906)

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

#### Defined in

[ue/ue.d.ts:24907](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24907)

___

### ReceiveObserverActivated

▸ **ReceiveObserverActivated**(`OwnerActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:24908](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24908)

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

#### Defined in

[ue/ue.d.ts:24909](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24909)

___

### ReceiveObserverDeactivated

▸ **ReceiveObserverDeactivated**(`OwnerActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:24910](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24910)

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

#### Defined in

[ue/ue.d.ts:24911](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24911)

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

[ue/ue.d.ts:24912](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24912)

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

[ue/ue.d.ts:24913](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24913)

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

#### Defined in

[ue/ue.d.ts:24915](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24915)

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

#### Defined in

[ue/ue.d.ts:24916](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24916)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTDecorator](ue_ue.BTDecorator.md).[StaticClass](ue_ue.BTDecorator.md#staticclass)

#### Defined in

[ue/ue.d.ts:24914](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24914)
