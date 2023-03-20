[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CollisionProfile

# Class: CollisionProfile

[ue/ue](../modules/ue_ue.md).CollisionProfile

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`CollisionProfile`**

## Table of contents

### Constructors

- [constructor](ue_ue.CollisionProfile.md#constructor)

### Properties

- [CollisionChannelRedirects](ue_ue.CollisionProfile.md#collisionchannelredirects)
- [DefaultChannelResponses](ue_ue.CollisionProfile.md#defaultchannelresponses)
- [EditProfiles](ue_ue.CollisionProfile.md#editprofiles)
- [ProfileRedirects](ue_ue.CollisionProfile.md#profileredirects)
- [Profiles](ue_ue.CollisionProfile.md#profiles)
- [\_\_tid\_CollisionProfile\_\_](ue_ue.CollisionProfile.md#__tid_collisionprofile__)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.CollisionProfile.md#__tid_developersettings__)
- [\_\_tid\_Object\_\_](ue_ue.CollisionProfile.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.CollisionProfile.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CollisionProfile.md#executeubergraph)
- [GetClass](ue_ue.CollisionProfile.md#getclass)
- [GetName](ue_ue.CollisionProfile.md#getname)
- [GetOuter](ue_ue.CollisionProfile.md#getouter)
- [GetWorld](ue_ue.CollisionProfile.md#getworld)
- [Find](ue_ue.CollisionProfile.md#find)
- [Load](ue_ue.CollisionProfile.md#load)
- [StaticClass](ue_ue.CollisionProfile.md#staticclass)

## Constructors

### constructor

• **new CollisionProfile**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

#### Defined in

[ue/ue.d.ts:28174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28174)

## Properties

### CollisionChannelRedirects

• **CollisionChannelRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Redirector`](ue_ue.Redirector.md)\>

#### Defined in

[ue/ue.d.ts:28179](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28179)

___

### DefaultChannelResponses

• **DefaultChannelResponses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CustomChannelSetup`](ue_ue.CustomChannelSetup.md)\>

#### Defined in

[ue/ue.d.ts:28176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28176)

___

### EditProfiles

• **EditProfiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CustomProfile`](ue_ue.CustomProfile.md)\>

#### Defined in

[ue/ue.d.ts:28177](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28177)

___

### ProfileRedirects

• **ProfileRedirects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Redirector`](ue_ue.Redirector.md)\>

#### Defined in

[ue/ue.d.ts:28178](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28178)

___

### Profiles

• **Profiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CollisionResponseTemplate`](ue_ue.CollisionResponseTemplate.md)\>

#### Defined in

[ue/ue.d.ts:28175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28175)

___

### \_\_tid\_CollisionProfile\_\_

• **\_\_tid\_CollisionProfile\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:28184](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28184)

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

#### Defined in

[ue/ue.d.ts:16950](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16950)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[CreateDefaultSubobject](ue_ue.DeveloperSettings.md#createdefaultsubobject)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CollisionProfile`](ue_ue.CollisionProfile.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CollisionProfile`](ue_ue.CollisionProfile.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

#### Defined in

[ue/ue.d.ts:28181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28181)

___

### Load

▸ `Static` **Load**(`InName`): [`CollisionProfile`](ue_ue.CollisionProfile.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CollisionProfile`](ue_ue.CollisionProfile.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

#### Defined in

[ue/ue.d.ts:28182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28182)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)

#### Defined in

[ue/ue.d.ts:28180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L28180)
