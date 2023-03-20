[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AISense\_Damage

# Class: AISense\_Damage

[ue/ue](../modules/ue_ue.md).AISense_Damage

## Hierarchy

- [`AISense`](ue_ue.AISense.md)

  ↳ **`AISense_Damage`**

## Table of contents

### Constructors

- [constructor](ue_ue.AISense_Damage.md#constructor)

### Properties

- [DefaultExpirationAge](ue_ue.AISense_Damage.md#defaultexpirationage)
- [NotifyType](ue_ue.AISense_Damage.md#notifytype)
- [PerceptionSystemInstance](ue_ue.AISense_Damage.md#perceptionsysteminstance)
- [RegisteredEvents](ue_ue.AISense_Damage.md#registeredevents)
- [\_\_tid\_AISense\_Damage\_\_](ue_ue.AISense_Damage.md#__tid_aisense_damage__)
- [\_\_tid\_AISense\_\_](ue_ue.AISense_Damage.md#__tid_aisense__)
- [\_\_tid\_Object\_\_](ue_ue.AISense_Damage.md#__tid_object__)
- [bAutoRegisterAllPawnsAsSources](ue_ue.AISense_Damage.md#bautoregisterallpawnsassources)
- [bWantsNewPawnNotification](ue_ue.AISense_Damage.md#bwantsnewpawnnotification)

### Methods

- [CreateDefaultSubobject](ue_ue.AISense_Damage.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AISense_Damage.md#executeubergraph)
- [GetClass](ue_ue.AISense_Damage.md#getclass)
- [GetName](ue_ue.AISense_Damage.md#getname)
- [GetOuter](ue_ue.AISense_Damage.md#getouter)
- [GetWorld](ue_ue.AISense_Damage.md#getworld)
- [Find](ue_ue.AISense_Damage.md#find)
- [Load](ue_ue.AISense_Damage.md#load)
- [ReportDamageEvent](ue_ue.AISense_Damage.md#reportdamageevent)
- [StaticClass](ue_ue.AISense_Damage.md#staticclass)

## Constructors

### constructor

• **new AISense_Damage**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AISense](ue_ue.AISense.md).[constructor](ue_ue.AISense.md#constructor)

#### Defined in

[ue/ue.d.ts:15823](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15823)

## Properties

### DefaultExpirationAge

• **DefaultExpirationAge**: `number`

#### Inherited from

[AISense](ue_ue.AISense.md).[DefaultExpirationAge](ue_ue.AISense.md#defaultexpirationage)

#### Defined in

[ue/ue.d.ts:15711](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15711)

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

### RegisteredEvents

• **RegisteredEvents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AIDamageEvent`](ue_ue.AIDamageEvent.md)\>

#### Defined in

[ue/ue.d.ts:15824](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15824)

___

### \_\_tid\_AISense\_Damage\_\_

• **\_\_tid\_AISense\_Damage\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15830](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15830)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AISense_Damage`](ue_ue.AISense_Damage.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AISense_Damage`](ue_ue.AISense_Damage.md)

#### Overrides

[AISense](ue_ue.AISense.md).[Find](ue_ue.AISense.md#find)

#### Defined in

[ue/ue.d.ts:15827](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15827)

___

### Load

▸ `Static` **Load**(`InName`): [`AISense_Damage`](ue_ue.AISense_Damage.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AISense_Damage`](ue_ue.AISense_Damage.md)

#### Overrides

[AISense](ue_ue.AISense.md).[Load](ue_ue.AISense.md#load)

#### Defined in

[ue/ue.d.ts:15828](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15828)

___

### ReportDamageEvent

▸ `Static` **ReportDamageEvent**(`WorldContextObject`, `DamagedActor`, `Instigator`, `DamageAmount`, `EventLocation`, `HitLocation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `DamagedActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `Instigator` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `DamageAmount` | `number` |
| `EventLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `HitLocation` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:15825](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15825)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AISense](ue_ue.AISense.md).[StaticClass](ue_ue.AISense.md#staticclass)

#### Defined in

[ue/ue.d.ts:15826](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15826)
