[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AISense\_Blueprint

# Class: AISense\_Blueprint

[ue/ue](../modules/ue_ue.md).AISense_Blueprint

## Hierarchy

- [`AISense`](ue_ue.AISense.md)

  ↳ **`AISense_Blueprint`**

## Table of contents

### Constructors

- [constructor](ue_ue.AISense_Blueprint.md#constructor)

### Properties

- [DefaultExpirationAge](ue_ue.AISense_Blueprint.md#defaultexpirationage)
- [ListenerContainer](ue_ue.AISense_Blueprint.md#listenercontainer)
- [ListenerDataType](ue_ue.AISense_Blueprint.md#listenerdatatype)
- [NotifyType](ue_ue.AISense_Blueprint.md#notifytype)
- [PerceptionSystemInstance](ue_ue.AISense_Blueprint.md#perceptionsysteminstance)
- [UnprocessedEvents](ue_ue.AISense_Blueprint.md#unprocessedevents)
- [\_\_tid\_AISense\_Blueprint\_\_](ue_ue.AISense_Blueprint.md#__tid_aisense_blueprint__)
- [\_\_tid\_AISense\_\_](ue_ue.AISense_Blueprint.md#__tid_aisense__)
- [\_\_tid\_Object\_\_](ue_ue.AISense_Blueprint.md#__tid_object__)
- [bAutoRegisterAllPawnsAsSources](ue_ue.AISense_Blueprint.md#bautoregisterallpawnsassources)
- [bWantsNewPawnNotification](ue_ue.AISense_Blueprint.md#bwantsnewpawnnotification)

### Methods

- [CreateDefaultSubobject](ue_ue.AISense_Blueprint.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AISense_Blueprint.md#executeubergraph)
- [GetAllListenerActors](ue_ue.AISense_Blueprint.md#getalllisteneractors)
- [GetAllListenerComponents](ue_ue.AISense_Blueprint.md#getalllistenercomponents)
- [GetClass](ue_ue.AISense_Blueprint.md#getclass)
- [GetName](ue_ue.AISense_Blueprint.md#getname)
- [GetOuter](ue_ue.AISense_Blueprint.md#getouter)
- [GetWorld](ue_ue.AISense_Blueprint.md#getworld)
- [K2\_OnNewPawn](ue_ue.AISense_Blueprint.md#k2_onnewpawn)
- [OnListenerRegistered](ue_ue.AISense_Blueprint.md#onlistenerregistered)
- [OnListenerUnregistered](ue_ue.AISense_Blueprint.md#onlistenerunregistered)
- [OnListenerUpdated](ue_ue.AISense_Blueprint.md#onlistenerupdated)
- [OnUpdate](ue_ue.AISense_Blueprint.md#onupdate)
- [Find](ue_ue.AISense_Blueprint.md#find)
- [Load](ue_ue.AISense_Blueprint.md#load)
- [StaticClass](ue_ue.AISense_Blueprint.md#staticclass)

## Constructors

### constructor

• **new AISense_Blueprint**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### ListenerContainer

• **ListenerContainer**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)\>

___

### ListenerDataType

• **ListenerDataType**: [`Class`](ue_ue.Class.md)

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

### UnprocessedEvents

• **UnprocessedEvents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AISenseEvent`](ue_ue.AISenseEvent.md)\>

___

### \_\_tid\_AISense\_Blueprint\_\_

• **\_\_tid\_AISense\_Blueprint\_\_**: `boolean`

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

### GetAllListenerActors

▸ **GetAllListenerActors**(`ListenerActors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ListenerActors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |

#### Returns

`void`

___

### GetAllListenerComponents

▸ **GetAllListenerComponents**(`ListenerComponents`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ListenerComponents` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)\>\> |

#### Returns

`void`

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

### K2\_OnNewPawn

▸ **K2_OnNewPawn**(`NewPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPawn` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Pawn`](ue_ue.Pawn.md)\> |

#### Returns

`void`

___

### OnListenerRegistered

▸ **OnListenerRegistered**(`ActorListener`, `PerceptionComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActorListener` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `PerceptionComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)\> |

#### Returns

`void`

___

### OnListenerUnregistered

▸ **OnListenerUnregistered**(`ActorListener`, `PerceptionComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActorListener` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `PerceptionComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)\> |

#### Returns

`void`

___

### OnListenerUpdated

▸ **OnListenerUpdated**(`ActorListener`, `PerceptionComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActorListener` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `PerceptionComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)\> |

#### Returns

`void`

___

### OnUpdate

▸ **OnUpdate**(`EventsToProcess`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EventsToProcess` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AISenseEvent`](ue_ue.AISenseEvent.md)\> |

#### Returns

`number`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AISense_Blueprint`](ue_ue.AISense_Blueprint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AISense_Blueprint`](ue_ue.AISense_Blueprint.md)

#### Overrides

[AISense](ue_ue.AISense.md).[Find](ue_ue.AISense.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AISense_Blueprint`](ue_ue.AISense_Blueprint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AISense_Blueprint`](ue_ue.AISense_Blueprint.md)

#### Overrides

[AISense](ue_ue.AISense.md).[Load](ue_ue.AISense.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AISense](ue_ue.AISense.md).[StaticClass](ue_ue.AISense.md#staticclass)
