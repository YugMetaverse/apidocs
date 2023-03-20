[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AIPerceptionSystem

# Class: AIPerceptionSystem

[ue/ue](../modules/ue_ue.md).AIPerceptionSystem

## Hierarchy

- [`AISubsystem`](ue_ue.AISubsystem.md)

  ↳ **`AIPerceptionSystem`**

## Table of contents

### Constructors

- [constructor](ue_ue.AIPerceptionSystem.md#constructor)

### Properties

- [AISystem](ue_ue.AIPerceptionSystem.md#aisystem)
- [PerceptionAgingRate](ue_ue.AIPerceptionSystem.md#perceptionagingrate)
- [Senses](ue_ue.AIPerceptionSystem.md#senses)
- [\_\_tid\_AIPerceptionSystem\_\_](ue_ue.AIPerceptionSystem.md#__tid_aiperceptionsystem__)
- [\_\_tid\_AISubsystem\_\_](ue_ue.AIPerceptionSystem.md#__tid_aisubsystem__)
- [\_\_tid\_Object\_\_](ue_ue.AIPerceptionSystem.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AIPerceptionSystem.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AIPerceptionSystem.md#executeubergraph)
- [GetClass](ue_ue.AIPerceptionSystem.md#getclass)
- [GetName](ue_ue.AIPerceptionSystem.md#getname)
- [GetOuter](ue_ue.AIPerceptionSystem.md#getouter)
- [GetWorld](ue_ue.AIPerceptionSystem.md#getworld)
- [OnPerceptionStimuliSourceEndPlay](ue_ue.AIPerceptionSystem.md#onperceptionstimulisourceendplay)
- [ReportEvent](ue_ue.AIPerceptionSystem.md#reportevent)
- [Find](ue_ue.AIPerceptionSystem.md#find)
- [GetSenseClassForStimulus](ue_ue.AIPerceptionSystem.md#getsenseclassforstimulus)
- [Load](ue_ue.AIPerceptionSystem.md#load)
- [RegisterPerceptionStimuliSource](ue_ue.AIPerceptionSystem.md#registerperceptionstimulisource)
- [ReportPerceptionEvent](ue_ue.AIPerceptionSystem.md#reportperceptionevent)
- [StaticClass](ue_ue.AIPerceptionSystem.md#staticclass)

## Constructors

### constructor

• **new AIPerceptionSystem**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AISubsystem](ue_ue.AISubsystem.md).[constructor](ue_ue.AISubsystem.md#constructor)

## Properties

### AISystem

• **AISystem**: [`AISystem`](ue_ue.AISystem.md)

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[AISystem](ue_ue.AISubsystem.md#aisystem)

___

### PerceptionAgingRate

• **PerceptionAgingRate**: `number`

___

### Senses

• **Senses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AISense`](ue_ue.AISense.md)\>

___

### \_\_tid\_AIPerceptionSystem\_\_

• **\_\_tid\_AIPerceptionSystem\_\_**: `boolean`

___

### \_\_tid\_AISubsystem\_\_

• **\_\_tid\_AISubsystem\_\_**: `boolean`

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[__tid_AISubsystem__](ue_ue.AISubsystem.md#__tid_aisubsystem__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[__tid_Object__](ue_ue.AISubsystem.md#__tid_object__)

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

[AISubsystem](ue_ue.AISubsystem.md).[CreateDefaultSubobject](ue_ue.AISubsystem.md#createdefaultsubobject)

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

[AISubsystem](ue_ue.AISubsystem.md).[ExecuteUbergraph](ue_ue.AISubsystem.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[GetClass](ue_ue.AISubsystem.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[GetName](ue_ue.AISubsystem.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[GetOuter](ue_ue.AISubsystem.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[GetWorld](ue_ue.AISubsystem.md#getworld)

___

### OnPerceptionStimuliSourceEndPlay

▸ **OnPerceptionStimuliSourceEndPlay**(`Actor`, `EndPlayReason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `EndPlayReason` | [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md) |

#### Returns

`void`

___

### ReportEvent

▸ **ReportEvent**(`PerceptionEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PerceptionEvent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AISenseEvent`](ue_ue.AISenseEvent.md)\> |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AIPerceptionSystem`](ue_ue.AIPerceptionSystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AIPerceptionSystem`](ue_ue.AIPerceptionSystem.md)

#### Overrides

[AISubsystem](ue_ue.AISubsystem.md).[Find](ue_ue.AISubsystem.md#find)

___

### GetSenseClassForStimulus

▸ `Static` **GetSenseClassForStimulus**(`WorldContextObject`, `Stimulus`): [`Class`](ue_ue.Class.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Stimulus` | [`AIStimulus`](ue_ue.AIStimulus.md) |

#### Returns

[`Class`](ue_ue.Class.md)

___

### Load

▸ `Static` **Load**(`InName`): [`AIPerceptionSystem`](ue_ue.AIPerceptionSystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AIPerceptionSystem`](ue_ue.AIPerceptionSystem.md)

#### Overrides

[AISubsystem](ue_ue.AISubsystem.md).[Load](ue_ue.AISubsystem.md#load)

___

### RegisterPerceptionStimuliSource

▸ `Static` **RegisterPerceptionStimuliSource**(`WorldContextObject`, `Sense`, `Target`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Sense` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `Target` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`boolean`

___

### ReportPerceptionEvent

▸ `Static` **ReportPerceptionEvent**(`WorldContextObject`, `PerceptionEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PerceptionEvent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AISenseEvent`](ue_ue.AISenseEvent.md)\> |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AISubsystem](ue_ue.AISubsystem.md).[StaticClass](ue_ue.AISubsystem.md#staticclass)
