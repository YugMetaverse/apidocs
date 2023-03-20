[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AISense\_Hearing

# Class: AISense\_Hearing

[ue/ue](../modules/ue_ue.md).AISense_Hearing

## Hierarchy

- [`AISense`](ue_ue.AISense.md)

  ↳ **`AISense_Hearing`**

## Table of contents

### Constructors

- [constructor](ue_ue.AISense_Hearing.md#constructor)

### Properties

- [DefaultExpirationAge](ue_ue.AISense_Hearing.md#defaultexpirationage)
- [NoiseEvents](ue_ue.AISense_Hearing.md#noiseevents)
- [NotifyType](ue_ue.AISense_Hearing.md#notifytype)
- [PerceptionSystemInstance](ue_ue.AISense_Hearing.md#perceptionsysteminstance)
- [SpeedOfSoundSq](ue_ue.AISense_Hearing.md#speedofsoundsq)
- [\_\_tid\_AISense\_Hearing\_\_](ue_ue.AISense_Hearing.md#__tid_aisense_hearing__)
- [\_\_tid\_AISense\_\_](ue_ue.AISense_Hearing.md#__tid_aisense__)
- [\_\_tid\_Object\_\_](ue_ue.AISense_Hearing.md#__tid_object__)
- [bAutoRegisterAllPawnsAsSources](ue_ue.AISense_Hearing.md#bautoregisterallpawnsassources)
- [bWantsNewPawnNotification](ue_ue.AISense_Hearing.md#bwantsnewpawnnotification)

### Methods

- [CreateDefaultSubobject](ue_ue.AISense_Hearing.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AISense_Hearing.md#executeubergraph)
- [GetClass](ue_ue.AISense_Hearing.md#getclass)
- [GetName](ue_ue.AISense_Hearing.md#getname)
- [GetOuter](ue_ue.AISense_Hearing.md#getouter)
- [GetWorld](ue_ue.AISense_Hearing.md#getworld)
- [Find](ue_ue.AISense_Hearing.md#find)
- [Load](ue_ue.AISense_Hearing.md#load)
- [ReportNoiseEvent](ue_ue.AISense_Hearing.md#reportnoiseevent)
- [StaticClass](ue_ue.AISense_Hearing.md#staticclass)

## Constructors

### constructor

• **new AISense_Hearing**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AISense](ue_ue.AISense.md).[constructor](ue_ue.AISense.md#constructor)

#### Defined in

[ue/ue.d.ts:15850](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15850)

## Properties

### DefaultExpirationAge

• **DefaultExpirationAge**: `number`

#### Inherited from

[AISense](ue_ue.AISense.md).[DefaultExpirationAge](ue_ue.AISense.md#defaultexpirationage)

#### Defined in

[ue/ue.d.ts:15711](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15711)

___

### NoiseEvents

• **NoiseEvents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AINoiseEvent`](ue_ue.AINoiseEvent.md)\>

#### Defined in

[ue/ue.d.ts:15851](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15851)

___

### NotifyType

• **NotifyType**: [`EAISenseNotifyType`](../enums/ue_ue.EAISenseNotifyType.md)

#### Inherited from

[AISense](ue_ue.AISense.md).[NotifyType](ue_ue.AISense.md#notifytype)

#### Defined in

[ue/ue.d.ts:15712](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15712)

___

### PerceptionSystemInstance

• **PerceptionSystemInstance**: [`AIPerceptionSystem`](ue_ue.AIPerceptionSystem.md)

#### Inherited from

[AISense](ue_ue.AISense.md).[PerceptionSystemInstance](ue_ue.AISense.md#perceptionsysteminstance)

#### Defined in

[ue/ue.d.ts:15715](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15715)

___

### SpeedOfSoundSq

• **SpeedOfSoundSq**: `number`

#### Defined in

[ue/ue.d.ts:15852](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15852)

___

### \_\_tid\_AISense\_Hearing\_\_

• **\_\_tid\_AISense\_Hearing\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15858](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15858)

___

### \_\_tid\_AISense\_\_

• **\_\_tid\_AISense\_\_**: `boolean`

#### Inherited from

[AISense](ue_ue.AISense.md).[__tid_AISense__](ue_ue.AISense.md#__tid_aisense__)

#### Defined in

[ue/ue.d.ts:15720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15720)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AISense](ue_ue.AISense.md).[__tid_Object__](ue_ue.AISense.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAutoRegisterAllPawnsAsSources

• **bAutoRegisterAllPawnsAsSources**: `boolean`

#### Inherited from

[AISense](ue_ue.AISense.md).[bAutoRegisterAllPawnsAsSources](ue_ue.AISense.md#bautoregisterallpawnsassources)

#### Defined in

[ue/ue.d.ts:15714](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15714)

___

### bWantsNewPawnNotification

• **bWantsNewPawnNotification**: `boolean`

#### Inherited from

[AISense](ue_ue.AISense.md).[bWantsNewPawnNotification](ue_ue.AISense.md#bwantsnewpawnnotification)

#### Defined in

[ue/ue.d.ts:15713](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15713)

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

[AISense](ue_ue.AISense.md).[ExecuteUbergraph](ue_ue.AISense.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AISense](ue_ue.AISense.md).[GetClass](ue_ue.AISense.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AISense](ue_ue.AISense.md).[GetName](ue_ue.AISense.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AISense](ue_ue.AISense.md).[GetOuter](ue_ue.AISense.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AISense](ue_ue.AISense.md).[GetWorld](ue_ue.AISense.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AISense_Hearing`](ue_ue.AISense_Hearing.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AISense_Hearing`](ue_ue.AISense_Hearing.md)

#### Overrides

[AISense](ue_ue.AISense.md).[Find](ue_ue.AISense.md#find)

#### Defined in

[ue/ue.d.ts:15855](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15855)

___

### Load

▸ `Static` **Load**(`InName`): [`AISense_Hearing`](ue_ue.AISense_Hearing.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AISense_Hearing`](ue_ue.AISense_Hearing.md)

#### Overrides

[AISense](ue_ue.AISense.md).[Load](ue_ue.AISense.md#load)

#### Defined in

[ue/ue.d.ts:15856](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15856)

___

### ReportNoiseEvent

▸ `Static` **ReportNoiseEvent**(`WorldContextObject`, `NoiseLocation`, `Loudness?`, `Instigator?`, `MaxRange?`, `Tag?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `NoiseLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `Loudness?` | `number` |
| `Instigator?` | [`Actor`](ue_ue.Actor.md) |
| `MaxRange?` | `number` |
| `Tag?` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:15853](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15853)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AISense](ue_ue.AISense.md).[StaticClass](ue_ue.AISense.md#staticclass)

#### Defined in

[ue/ue.d.ts:15854](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15854)
