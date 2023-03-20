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

#### Defined in

[ue/ue.d.ts:15733](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15733)

## Properties

### AISystem

• **AISystem**: [`AISystem`](ue_ue.AISystem.md)

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[AISystem](ue_ue.AISubsystem.md#aisystem)

#### Defined in

[ue/ue.d.ts:15700](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15700)

___

### PerceptionAgingRate

• **PerceptionAgingRate**: `number`

#### Defined in

[ue/ue.d.ts:15735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15735)

___

### Senses

• **Senses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AISense`](ue_ue.AISense.md)\>

#### Defined in

[ue/ue.d.ts:15734](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15734)

___

### \_\_tid\_AIPerceptionSystem\_\_

• **\_\_tid\_AIPerceptionSystem\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15745](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15745)

___

### \_\_tid\_AISubsystem\_\_

• **\_\_tid\_AISubsystem\_\_**: `boolean`

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[__tid_AISubsystem__](ue_ue.AISubsystem.md#__tid_aisubsystem__)

#### Defined in

[ue/ue.d.ts:15705](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15705)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[__tid_Object__](ue_ue.AISubsystem.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

[AISubsystem](ue_ue.AISubsystem.md).[ExecuteUbergraph](ue_ue.AISubsystem.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[GetClass](ue_ue.AISubsystem.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[GetName](ue_ue.AISubsystem.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[GetOuter](ue_ue.AISubsystem.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[GetWorld](ue_ue.AISubsystem.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:15736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15736)

___

### ReportEvent

▸ **ReportEvent**(`PerceptionEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PerceptionEvent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AISenseEvent`](ue_ue.AISenseEvent.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:15737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15737)

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

#### Defined in

[ue/ue.d.ts:15742](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15742)

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

#### Defined in

[ue/ue.d.ts:15738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15738)

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

#### Defined in

[ue/ue.d.ts:15743](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15743)

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

#### Defined in

[ue/ue.d.ts:15739](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15739)

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

#### Defined in

[ue/ue.d.ts:15740](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15740)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AISubsystem](ue_ue.AISubsystem.md).[StaticClass](ue_ue.AISubsystem.md#staticclass)

#### Defined in

[ue/ue.d.ts:15741](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15741)
