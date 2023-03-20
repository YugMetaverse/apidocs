[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AISense\_Prediction

# Class: AISense\_Prediction

[ue/ue](../modules/ue_ue.md).AISense_Prediction

## Hierarchy

- [`AISense`](ue_ue.AISense.md)

  ↳ **`AISense_Prediction`**

## Table of contents

### Constructors

- [constructor](ue_ue.AISense_Prediction.md#constructor)

### Properties

- [DefaultExpirationAge](ue_ue.AISense_Prediction.md#defaultexpirationage)
- [NotifyType](ue_ue.AISense_Prediction.md#notifytype)
- [PerceptionSystemInstance](ue_ue.AISense_Prediction.md#perceptionsysteminstance)
- [RegisteredEvents](ue_ue.AISense_Prediction.md#registeredevents)
- [\_\_tid\_AISense\_Prediction\_\_](ue_ue.AISense_Prediction.md#__tid_aisense_prediction__)
- [\_\_tid\_AISense\_\_](ue_ue.AISense_Prediction.md#__tid_aisense__)
- [\_\_tid\_Object\_\_](ue_ue.AISense_Prediction.md#__tid_object__)
- [bAutoRegisterAllPawnsAsSources](ue_ue.AISense_Prediction.md#bautoregisterallpawnsassources)
- [bWantsNewPawnNotification](ue_ue.AISense_Prediction.md#bwantsnewpawnnotification)

### Methods

- [CreateDefaultSubobject](ue_ue.AISense_Prediction.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AISense_Prediction.md#executeubergraph)
- [GetClass](ue_ue.AISense_Prediction.md#getclass)
- [GetName](ue_ue.AISense_Prediction.md#getname)
- [GetOuter](ue_ue.AISense_Prediction.md#getouter)
- [GetWorld](ue_ue.AISense_Prediction.md#getworld)
- [Find](ue_ue.AISense_Prediction.md#find)
- [Load](ue_ue.AISense_Prediction.md#load)
- [RequestControllerPredictionEvent](ue_ue.AISense_Prediction.md#requestcontrollerpredictionevent)
- [RequestPawnPredictionEvent](ue_ue.AISense_Prediction.md#requestpawnpredictionevent)
- [StaticClass](ue_ue.AISense_Prediction.md#staticclass)

## Constructors

### constructor

• **new AISense_Prediction**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AISense](ue_ue.AISense.md).[constructor](ue_ue.AISense.md#constructor)

## Properties

### DefaultExpirationAge

• **DefaultExpirationAge**: `number`

#### Inherited from

[AISense](ue_ue.AISense.md).[DefaultExpirationAge](ue_ue.AISense.md#defaultexpirationage)

___

### NotifyType

• **NotifyType**: [`EAISenseNotifyType`](../enums/ue_ue.EAISenseNotifyType.md)

#### Inherited from

[AISense](ue_ue.AISense.md).[NotifyType](ue_ue.AISense.md#notifytype)

___

### PerceptionSystemInstance

• **PerceptionSystemInstance**: [`AIPerceptionSystem`](ue_ue.AIPerceptionSystem.md)

#### Inherited from

[AISense](ue_ue.AISense.md).[PerceptionSystemInstance](ue_ue.AISense.md#perceptionsysteminstance)

___

### RegisteredEvents

• **RegisteredEvents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AIPredictionEvent`](ue_ue.AIPredictionEvent.md)\>

___

### \_\_tid\_AISense\_Prediction\_\_

• **\_\_tid\_AISense\_Prediction\_\_**: `boolean`

___

### \_\_tid\_AISense\_\_

• **\_\_tid\_AISense\_\_**: `boolean`

#### Inherited from

[AISense](ue_ue.AISense.md).[__tid_AISense__](ue_ue.AISense.md#__tid_aisense__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AISense](ue_ue.AISense.md).[__tid_Object__](ue_ue.AISense.md#__tid_object__)

___

### bAutoRegisterAllPawnsAsSources

• **bAutoRegisterAllPawnsAsSources**: `boolean`

#### Inherited from

[AISense](ue_ue.AISense.md).[bAutoRegisterAllPawnsAsSources](ue_ue.AISense.md#bautoregisterallpawnsassources)

___

### bWantsNewPawnNotification

• **bWantsNewPawnNotification**: `boolean`

#### Inherited from

[AISense](ue_ue.AISense.md).[bWantsNewPawnNotification](ue_ue.AISense.md#bwantsnewpawnnotification)

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

[AISense](ue_ue.AISense.md).[CreateDefaultSubobject](ue_ue.AISense.md#createdefaultsubobject)

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

[AISense](ue_ue.AISense.md).[ExecuteUbergraph](ue_ue.AISense.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AISense](ue_ue.AISense.md).[GetClass](ue_ue.AISense.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AISense](ue_ue.AISense.md).[GetName](ue_ue.AISense.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AISense](ue_ue.AISense.md).[GetOuter](ue_ue.AISense.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AISense](ue_ue.AISense.md).[GetWorld](ue_ue.AISense.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AISense_Prediction`](ue_ue.AISense_Prediction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AISense_Prediction`](ue_ue.AISense_Prediction.md)

#### Overrides

[AISense](ue_ue.AISense.md).[Find](ue_ue.AISense.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AISense_Prediction`](ue_ue.AISense_Prediction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AISense_Prediction`](ue_ue.AISense_Prediction.md)

#### Overrides

[AISense](ue_ue.AISense.md).[Load](ue_ue.AISense.md#load)

___

### RequestControllerPredictionEvent

▸ `Static` **RequestControllerPredictionEvent**(`Requestor`, `PredictedActor`, `PredictionTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Requestor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AIController`](ue_ue.AIController.md)\> |
| `PredictedActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `PredictionTime` | `number` |

#### Returns

`void`

___

### RequestPawnPredictionEvent

▸ `Static` **RequestPawnPredictionEvent**(`Requestor`, `PredictedActor`, `PredictionTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Requestor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |
| `PredictedActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `PredictionTime` | `number` |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AISense](ue_ue.AISense.md).[StaticClass](ue_ue.AISense.md#staticclass)
