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

#### Defined in

[ue/ue.d.ts:25147](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25147)

## Properties

### AIOwner

• **AIOwner**: [`AIController`](ue_ue.AIController.md)

#### Defined in

[ue/ue.d.ts:25148](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25148)

___

### ActorOwner

• **ActorOwner**: [`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:25149](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25149)

___

### Interval

• **Interval**: `number`

#### Inherited from

[BTService](ue_ue.BTService.md).[Interval](ue_ue.BTService.md#interval)

#### Defined in

[ue/ue.d.ts:14588](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14588)

___

### NodeName

• **NodeName**: `string`

#### Inherited from

[BTService](ue_ue.BTService.md).[NodeName](ue_ue.BTService.md#nodename)

#### Defined in

[ue/ue.d.ts:14567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14567)

___

### ParentNode

• **ParentNode**: [`BTCompositeNode`](ue_ue.BTCompositeNode.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[ParentNode](ue_ue.BTService.md#parentnode)

#### Defined in

[ue/ue.d.ts:14569](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14569)

___

### RandomDeviation

• **RandomDeviation**: `number`

#### Inherited from

[BTService](ue_ue.BTService.md).[RandomDeviation](ue_ue.BTService.md#randomdeviation)

#### Defined in

[ue/ue.d.ts:14589](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14589)

___

### TreeAsset

• **TreeAsset**: [`BehaviorTree`](ue_ue.BehaviorTree.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[TreeAsset](ue_ue.BTService.md#treeasset)

#### Defined in

[ue/ue.d.ts:14568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14568)

___

### \_\_tid\_BTAuxiliaryNode\_\_

• **\_\_tid\_BTAuxiliaryNode\_\_**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[__tid_BTAuxiliaryNode__](ue_ue.BTService.md#__tid_btauxiliarynode__)

#### Defined in

[ue/ue.d.ts:14583](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14583)

___

### \_\_tid\_BTNode\_\_

• **\_\_tid\_BTNode\_\_**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[__tid_BTNode__](ue_ue.BTService.md#__tid_btnode__)

#### Defined in

[ue/ue.d.ts:14574](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14574)

___

### \_\_tid\_BTService\_BlueprintBase\_\_

• **\_\_tid\_BTService\_BlueprintBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:25165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25165)

___

### \_\_tid\_BTService\_\_

• **\_\_tid\_BTService\_\_**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[__tid_BTService__](ue_ue.BTService.md#__tid_btservice__)

#### Defined in

[ue/ue.d.ts:14596](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14596)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[__tid_Object__](ue_ue.BTService.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bCallTickOnSearchStart

• **bCallTickOnSearchStart**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[bCallTickOnSearchStart](ue_ue.BTService.md#bcalltickonsearchstart)

#### Defined in

[ue/ue.d.ts:14590](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14590)

___

### bRestartTimerOnEachActivation

• **bRestartTimerOnEachActivation**: `boolean`

#### Inherited from

[BTService](ue_ue.BTService.md).[bRestartTimerOnEachActivation](ue_ue.BTService.md#brestarttimeroneachactivation)

#### Defined in

[ue/ue.d.ts:14591](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14591)

___

### bShowEventDetails

• **bShowEventDetails**: `boolean`

#### Defined in

[ue/ue.d.ts:25151](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25151)

___

### bShowPropertyDetails

• **bShowPropertyDetails**: `boolean`

#### Defined in

[ue/ue.d.ts:25150](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25150)

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

[BTService](ue_ue.BTService.md).[ExecuteUbergraph](ue_ue.BTService.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[GetClass](ue_ue.BTService.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BTService](ue_ue.BTService.md).[GetName](ue_ue.BTService.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[GetOuter](ue_ue.BTService.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BTService](ue_ue.BTService.md).[GetWorld](ue_ue.BTService.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsServiceActive

▸ **IsServiceActive**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:25152](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25152)

___

### ReceiveActivation

▸ **ReceiveActivation**(`OwnerActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:25153](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25153)

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

#### Defined in

[ue/ue.d.ts:25154](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25154)

___

### ReceiveDeactivation

▸ **ReceiveDeactivation**(`OwnerActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:25155](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25155)

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

#### Defined in

[ue/ue.d.ts:25156](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25156)

___

### ReceiveSearchStart

▸ **ReceiveSearchStart**(`OwnerActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwnerActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:25157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25157)

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

#### Defined in

[ue/ue.d.ts:25158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25158)

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

[ue/ue.d.ts:25159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25159)

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

[ue/ue.d.ts:25160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25160)

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

#### Defined in

[ue/ue.d.ts:25162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25162)

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

#### Defined in

[ue/ue.d.ts:25163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25163)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BTService](ue_ue.BTService.md).[StaticClass](ue_ue.BTService.md#staticclass)

#### Defined in

[ue/ue.d.ts:25161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L25161)
