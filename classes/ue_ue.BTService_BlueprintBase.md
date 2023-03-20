[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BTService\_BlueprintBase

# Class: BTService\_BlueprintBase

[ue/ue](../modules/ue_ue.md).BTService_BlueprintBase

## Hierarchy

- [`BTService`](ue_ue.BTService.md)

  ↳ **`BTService_BlueprintBase`**

## Table of contents

### Constructors

- [constructor](ue_ue.BTService_BlueprintBase.md#constructor)

### Properties

- [AIOwner](ue_ue.BTService_BlueprintBase.md#aiowner)
- [ActorOwner](ue_ue.BTService_BlueprintBase.md#actorowner)
- [Interval](ue_ue.BTService_BlueprintBase.md#interval)
- [NodeName](ue_ue.BTService_BlueprintBase.md#nodename)
- [ParentNode](ue_ue.BTService_BlueprintBase.md#parentnode)
- [RandomDeviation](ue_ue.BTService_BlueprintBase.md#randomdeviation)
- [TreeAsset](ue_ue.BTService_BlueprintBase.md#treeasset)
- [\_\_tid\_BTAuxiliaryNode\_\_](ue_ue.BTService_BlueprintBase.md#__tid_btauxiliarynode__)
- [\_\_tid\_BTNode\_\_](ue_ue.BTService_BlueprintBase.md#__tid_btnode__)
- [\_\_tid\_BTService\_BlueprintBase\_\_](ue_ue.BTService_BlueprintBase.md#__tid_btservice_blueprintbase__)
- [\_\_tid\_BTService\_\_](ue_ue.BTService_BlueprintBase.md#__tid_btservice__)
- [\_\_tid\_Object\_\_](ue_ue.BTService_BlueprintBase.md#__tid_object__)
- [bCallTickOnSearchStart](ue_ue.BTService_BlueprintBase.md#bcalltickonsearchstart)
- [bRestartTimerOnEachActivation](ue_ue.BTService_BlueprintBase.md#brestarttimeroneachactivation)
- [bShowEventDetails](ue_ue.BTService_BlueprintBase.md#bshoweventdetails)
- [bShowPropertyDetails](ue_ue.BTService_BlueprintBase.md#bshowpropertydetails)

### Methods

- [CreateDefaultSubobject](ue_ue.BTService_BlueprintBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BTService_BlueprintBase.md#executeubergraph)
- [GetClass](ue_ue.BTService_BlueprintBase.md#getclass)
- [GetName](ue_ue.BTService_BlueprintBase.md#getname)
- [GetOuter](ue_ue.BTService_BlueprintBase.md#getouter)
- [GetWorld](ue_ue.BTService_BlueprintBase.md#getworld)
- [IsServiceActive](ue_ue.BTService_BlueprintBase.md#isserviceactive)
- [ReceiveActivation](ue_ue.BTService_BlueprintBase.md#receiveactivation)
- [ReceiveActivationAI](ue_ue.BTService_BlueprintBase.md#receiveactivationai)
- [ReceiveDeactivation](ue_ue.BTService_BlueprintBase.md#receivedeactivation)
- [ReceiveDeactivationAI](ue_ue.BTService_BlueprintBase.md#receivedeactivationai)
- [ReceiveSearchStart](ue_ue.BTService_BlueprintBase.md#receivesearchstart)
- [ReceiveSearchStartAI](ue_ue.BTService_BlueprintBase.md#receivesearchstartai)
- [ReceiveTick](ue_ue.BTService_BlueprintBase.md#receivetick)
- [ReceiveTickAI](ue_ue.BTService_BlueprintBase.md#receivetickai)
- [Find](ue_ue.BTService_BlueprintBase.md#find)
- [Load](ue_ue.BTService_BlueprintBase.md#load)
- [StaticClass](ue_ue.BTService_BlueprintBase.md#staticclass)

## Constructors

### constructor

• **new BTService_BlueprintBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BTService](ue_ue.BTService.md).[constructor](ue_ue.BTService.md#constructor)

## Properties

### AIOwner

• **AIOwner**: [`AIController`](ue_ue.AIController.md)

___

### ActorOwner

• **ActorOwner**: [`Actor`](ue_ue.Actor.md)

___

### Interval

• **Interval**: `number`

#### Inherited from

[BTService](ue_ue.BTService.md).[Interval](ue_ue.BTService.md#interval)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTService](ue_ue.BTService.md).[NodeName](ue_ue.BTService.md#nodename)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[ParentNode](ue_ue.BTService.md#parentnode)

___

### RandomDeviation

• **RandomDeviation**: `number`

#### Inherited from

[BTService](ue_ue.BTService.md).[RandomDeviation](ue_ue.BTService.md#randomdeviation)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[TreeAsset](ue_ue.BTService.md#treeasset)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[__tid_BTAuxiliaryNode__](ue_ue.BTService.md#__tid_btauxiliarynode__)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[__tid_BTNode__](ue_ue.BTService.md#__tid_btnode__)

___

### \_\_tid\_BTService\_BlueprintBase\_\_

• **\_\_tid\_BTService\_BlueprintBase\_\_**: `boolean`

___

### \_\_tid\_BTService\_\_

• **\_\_tid\_BTService\_\_**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[__tid_BTService__](ue_ue.BTService.md#__tid_btservice__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[__tid_Object__](ue_ue.BTService.md#__tid_object__)

___

### bCallTickOnSearchStart

• **bCallTickOnSearchStart**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[bCallTickOnSearchStart](ue_ue.BTService.md#bcalltickonsearchstart)

___

### bRestartTimerOnEachActivation

• **bRestartTimerOnEachActivation**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[bRestartTimerOnEachActivation](ue_ue.BTService.md#brestarttimeroneachactivation)

___

### bShowEventDetails

• **bShowEventDetails**: `boolean`

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

[BTService](ue_ue.BTService.md).[CreateDefaultSubobject](ue_ue.BTService.md#createdefaultsubobject)

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

[BTService](ue_ue.BTService.md).[ExecuteUbergraph](ue_ue.BTService.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[GetClass](ue_ue.BTService.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTService](ue_ue.BTService.md).[GetName](ue_ue.BTService.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[GetOuter](ue_ue.BTService.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[GetWorld](ue_ue.BTService.md#getworld)

___

### IsServiceActive

▸ **IsServiceActive**(): `boolean`

#### Returns

`boolean`

___

### ReceiveActivation

▸ **ReceiveActivation**(`OwnerActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### ReceiveActivationAI

▸ **ReceiveActivationAI**(`OwnerController`, `ControlledPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AIController`](ue_ue.AIController.md)\> |
| `ControlledPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

___

### ReceiveDeactivation

▸ **ReceiveDeactivation**(`OwnerActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### ReceiveDeactivationAI

▸ **ReceiveDeactivationAI**(`OwnerController`, `ControlledPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AIController`](ue_ue.AIController.md)\> |
| `ControlledPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

___

### ReceiveSearchStart

▸ **ReceiveSearchStart**(`OwnerActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### ReceiveSearchStartAI

▸ **ReceiveSearchStartAI**(`OwnerController`, `ControlledPawn`): `void`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BTService_BlueprintBase`](ue_ue.BTService_BlueprintBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BTService_BlueprintBase`](ue_ue.BTService_BlueprintBase.md)

#### Overrides

[BTService](ue_ue.BTService.md).[Find](ue_ue.BTService.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`BTService_BlueprintBase`](ue_ue.BTService_BlueprintBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BTService_BlueprintBase`](ue_ue.BTService_BlueprintBase.md)

#### Overrides

[BTService](ue_ue.BTService.md).[Load](ue_ue.BTService.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTService](ue_ue.BTService.md).[StaticClass](ue_ue.BTService.md#staticclass)
