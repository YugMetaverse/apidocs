[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AISense

# Class: AISense

[ue/ue](../modules/ue_ue.md).AISense

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AISense`**

  ↳↳ [`AISense_Blueprint`](ue_ue.AISense_Blueprint.md)

  ↳↳ [`AISense_Damage`](ue_ue.AISense_Damage.md)

  ↳↳ [`AISense_Hearing`](ue_ue.AISense_Hearing.md)

  ↳↳ [`AISense_Prediction`](ue_ue.AISense_Prediction.md)

  ↳↳ [`AISense_Sight`](ue_ue.AISense_Sight.md)

  ↳↳ [`AISense_Team`](ue_ue.AISense_Team.md)

  ↳↳ [`AISense_Touch`](ue_ue.AISense_Touch.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AISense.md#constructor)

### Properties

- [DefaultExpirationAge](ue_ue.AISense.md#defaultexpirationage)
- [NotifyType](ue_ue.AISense.md#notifytype)
- [PerceptionSystemInstance](ue_ue.AISense.md#perceptionsysteminstance)
- [\_\_tid\_AISense\_\_](ue_ue.AISense.md#__tid_aisense__)
- [\_\_tid\_Object\_\_](ue_ue.AISense.md#__tid_object__)
- [bAutoRegisterAllPawnsAsSources](ue_ue.AISense.md#bautoregisterallpawnsassources)
- [bWantsNewPawnNotification](ue_ue.AISense.md#bwantsnewpawnnotification)

### Methods

- [CreateDefaultSubobject](ue_ue.AISense.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AISense.md#executeubergraph)
- [GetClass](ue_ue.AISense.md#getclass)
- [GetName](ue_ue.AISense.md#getname)
- [GetOuter](ue_ue.AISense.md#getouter)
- [GetWorld](ue_ue.AISense.md#getworld)
- [Find](ue_ue.AISense.md#find)
- [Load](ue_ue.AISense.md#load)
- [StaticClass](ue_ue.AISense.md#staticclass)

## Constructors

### constructor

• **new AISense**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### DefaultExpirationAge

• **DefaultExpirationAge**: `number`

___

### NotifyType

• **NotifyType**: [`EAISenseNotifyType`](../enums/ue_ue.EAISenseNotifyType.md)

___

### PerceptionSystemInstance

• **PerceptionSystemInstance**: [`AIPerceptionSystem`](ue_ue.AIPerceptionSystem.md)

___

### \_\_tid\_AISense\_\_

• **\_\_tid\_AISense\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bAutoRegisterAllPawnsAsSources

• **bAutoRegisterAllPawnsAsSources**: `boolean`

___

### bWantsNewPawnNotification

• **bWantsNewPawnNotification**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AISense`](ue_ue.AISense.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AISense`](ue_ue.AISense.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AISense`](ue_ue.AISense.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AISense`](ue_ue.AISense.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
