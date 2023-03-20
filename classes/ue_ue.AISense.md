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

#### Defined in

[ue/ue.d.ts:15710](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15710)

## Properties

### DefaultExpirationAge

• **DefaultExpirationAge**: `number`

#### Defined in

[ue/ue.d.ts:15711](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15711)

___

### NotifyType

• **NotifyType**: [`EAISenseNotifyType`](../enums/ue_ue.EAISenseNotifyType.md)

#### Defined in

[ue/ue.d.ts:15712](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15712)

___

### PerceptionSystemInstance

• **PerceptionSystemInstance**: [`AIPerceptionSystem`](ue_ue.AIPerceptionSystem.md)

#### Defined in

[ue/ue.d.ts:15715](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15715)

___

### \_\_tid\_AISense\_\_

• **\_\_tid\_AISense\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15720](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15720)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bAutoRegisterAllPawnsAsSources

• **bAutoRegisterAllPawnsAsSources**: `boolean`

#### Defined in

[ue/ue.d.ts:15714](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15714)

___

### bWantsNewPawnNotification

• **bWantsNewPawnNotification**: `boolean`

#### Defined in

[ue/ue.d.ts:15713](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15713)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:15717](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15717)

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

#### Defined in

[ue/ue.d.ts:15718](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15718)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:15716](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15716)
