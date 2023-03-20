[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AISense\_Team

# Class: AISense\_Team

[ue/ue](../modules/ue_ue.md).AISense_Team

## Hierarchy

- [`AISense`](ue_ue.AISense.md)

  ↳ **`AISense_Team`**

## Table of contents

### Constructors

- [constructor](ue_ue.AISense_Team.md#constructor)

### Properties

- [DefaultExpirationAge](ue_ue.AISense_Team.md#defaultexpirationage)
- [NotifyType](ue_ue.AISense_Team.md#notifytype)
- [PerceptionSystemInstance](ue_ue.AISense_Team.md#perceptionsysteminstance)
- [RegisteredEvents](ue_ue.AISense_Team.md#registeredevents)
- [\_\_tid\_AISense\_Team\_\_](ue_ue.AISense_Team.md#__tid_aisense_team__)
- [\_\_tid\_AISense\_\_](ue_ue.AISense_Team.md#__tid_aisense__)
- [\_\_tid\_Object\_\_](ue_ue.AISense_Team.md#__tid_object__)
- [bAutoRegisterAllPawnsAsSources](ue_ue.AISense_Team.md#bautoregisterallpawnsassources)
- [bWantsNewPawnNotification](ue_ue.AISense_Team.md#bwantsnewpawnnotification)

### Methods

- [CreateDefaultSubobject](ue_ue.AISense_Team.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AISense_Team.md#executeubergraph)
- [GetClass](ue_ue.AISense_Team.md#getclass)
- [GetName](ue_ue.AISense_Team.md#getname)
- [GetOuter](ue_ue.AISense_Team.md#getouter)
- [GetWorld](ue_ue.AISense_Team.md#getworld)
- [Find](ue_ue.AISense_Team.md#find)
- [Load](ue_ue.AISense_Team.md#load)
- [StaticClass](ue_ue.AISense_Team.md#staticclass)

## Constructors

### constructor

• **new AISense_Team**(`Outer?`, `Name?`, `ObjectFlags?`)

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

• **RegisteredEvents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AITeamStimulusEvent`](ue_ue.AITeamStimulusEvent.md)\>

___

### \_\_tid\_AISense\_Team\_\_

• **\_\_tid\_AISense\_Team\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AISense_Team`](ue_ue.AISense_Team.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AISense_Team`](ue_ue.AISense_Team.md)

#### Overrides

[AISense](ue_ue.AISense.md).[Find](ue_ue.AISense.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AISense_Team`](ue_ue.AISense_Team.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AISense_Team`](ue_ue.AISense_Team.md)

#### Overrides

[AISense](ue_ue.AISense.md).[Load](ue_ue.AISense.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AISense](ue_ue.AISense.md).[StaticClass](ue_ue.AISense.md#staticclass)
