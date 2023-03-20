[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AISense\_Sight

# Class: AISense\_Sight

[ue/ue](../modules/ue_ue.md).AISense_Sight

## Hierarchy

- [`AISense`](ue_ue.AISense.md)

  ↳ **`AISense_Sight`**

## Table of contents

### Constructors

- [constructor](ue_ue.AISense_Sight.md#constructor)

### Properties

- [DefaultExpirationAge](ue_ue.AISense_Sight.md#defaultexpirationage)
- [HighImportanceQueryDistanceThreshold](ue_ue.AISense_Sight.md#highimportancequerydistancethreshold)
- [MaxQueryImportance](ue_ue.AISense_Sight.md#maxqueryimportance)
- [MaxTimeSlicePerTick](ue_ue.AISense_Sight.md#maxtimeslicepertick)
- [MaxTracesPerTick](ue_ue.AISense_Sight.md#maxtracespertick)
- [MinQueriesPerTimeSliceCheck](ue_ue.AISense_Sight.md#minqueriespertimeslicecheck)
- [NotifyType](ue_ue.AISense_Sight.md#notifytype)
- [PerceptionSystemInstance](ue_ue.AISense_Sight.md#perceptionsysteminstance)
- [SightLimitQueryImportance](ue_ue.AISense_Sight.md#sightlimitqueryimportance)
- [\_\_tid\_AISense\_Sight\_\_](ue_ue.AISense_Sight.md#__tid_aisense_sight__)
- [\_\_tid\_AISense\_\_](ue_ue.AISense_Sight.md#__tid_aisense__)
- [\_\_tid\_Object\_\_](ue_ue.AISense_Sight.md#__tid_object__)
- [bAutoRegisterAllPawnsAsSources](ue_ue.AISense_Sight.md#bautoregisterallpawnsassources)
- [bWantsNewPawnNotification](ue_ue.AISense_Sight.md#bwantsnewpawnnotification)

### Methods

- [CreateDefaultSubobject](ue_ue.AISense_Sight.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AISense_Sight.md#executeubergraph)
- [GetClass](ue_ue.AISense_Sight.md#getclass)
- [GetName](ue_ue.AISense_Sight.md#getname)
- [GetOuter](ue_ue.AISense_Sight.md#getouter)
- [GetWorld](ue_ue.AISense_Sight.md#getworld)
- [Find](ue_ue.AISense_Sight.md#find)
- [Load](ue_ue.AISense_Sight.md#load)
- [StaticClass](ue_ue.AISense_Sight.md#staticclass)

## Constructors

### constructor

• **new AISense_Sight**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### HighImportanceQueryDistanceThreshold

• **HighImportanceQueryDistanceThreshold**: `number`

___

### MaxQueryImportance

• **MaxQueryImportance**: `number`

___

### MaxTimeSlicePerTick

• **MaxTimeSlicePerTick**: `number`

___

### MaxTracesPerTick

• **MaxTracesPerTick**: `number`

___

### MinQueriesPerTimeSliceCheck

• **MinQueriesPerTimeSliceCheck**: `number`

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

### SightLimitQueryImportance

• **SightLimitQueryImportance**: `number`

___

### \_\_tid\_AISense\_Sight\_\_

• **\_\_tid\_AISense\_Sight\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AISense_Sight`](ue_ue.AISense_Sight.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AISense_Sight`](ue_ue.AISense_Sight.md)

#### Overrides

[AISense](ue_ue.AISense.md).[Find](ue_ue.AISense.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AISense_Sight`](ue_ue.AISense_Sight.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AISense_Sight`](ue_ue.AISense_Sight.md)

#### Overrides

[AISense](ue_ue.AISense.md).[Load](ue_ue.AISense.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AISense](ue_ue.AISense.md).[StaticClass](ue_ue.AISense.md#staticclass)
