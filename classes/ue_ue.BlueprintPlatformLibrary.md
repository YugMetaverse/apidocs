[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlueprintPlatformLibrary

# Class: BlueprintPlatformLibrary

[ue/ue](../modules/ue_ue.md).BlueprintPlatformLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`BlueprintPlatformLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.BlueprintPlatformLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.BlueprintPlatformLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_BlueprintPlatformLibrary\_\_](ue_ue.BlueprintPlatformLibrary.md#__tid_blueprintplatformlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.BlueprintPlatformLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.BlueprintPlatformLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BlueprintPlatformLibrary.md#executeubergraph)
- [GetClass](ue_ue.BlueprintPlatformLibrary.md#getclass)
- [GetName](ue_ue.BlueprintPlatformLibrary.md#getname)
- [GetOuter](ue_ue.BlueprintPlatformLibrary.md#getouter)
- [GetWorld](ue_ue.BlueprintPlatformLibrary.md#getworld)
- [CancelLocalNotification](ue_ue.BlueprintPlatformLibrary.md#cancellocalnotification)
- [CancelLocalNotificationById](ue_ue.BlueprintPlatformLibrary.md#cancellocalnotificationbyid)
- [ClearAllLocalNotifications](ue_ue.BlueprintPlatformLibrary.md#clearalllocalnotifications)
- [Find](ue_ue.BlueprintPlatformLibrary.md#find)
- [GetDeviceOrientation](ue_ue.BlueprintPlatformLibrary.md#getdeviceorientation)
- [GetLaunchNotification](ue_ue.BlueprintPlatformLibrary.md#getlaunchnotification)
- [Load](ue_ue.BlueprintPlatformLibrary.md#load)
- [ScheduleLocalNotificationAtTime](ue_ue.BlueprintPlatformLibrary.md#schedulelocalnotificationattime)
- [ScheduleLocalNotificationBadgeAtTime](ue_ue.BlueprintPlatformLibrary.md#schedulelocalnotificationbadgeattime)
- [ScheduleLocalNotificationBadgeFromNow](ue_ue.BlueprintPlatformLibrary.md#schedulelocalnotificationbadgefromnow)
- [ScheduleLocalNotificationFromNow](ue_ue.BlueprintPlatformLibrary.md#schedulelocalnotificationfromnow)
- [StaticClass](ue_ue.BlueprintPlatformLibrary.md#staticclass)

## Constructors

### constructor

• **new BlueprintPlatformLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:24320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24320)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13418)

___

### \_\_tid\_BlueprintPlatformLibrary\_\_

• **\_\_tid\_BlueprintPlatformLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:24334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24334)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### CancelLocalNotification

▸ `Static` **CancelLocalNotification**(`ActivationEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActivationEvent` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:24321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24321)

___

### CancelLocalNotificationById

▸ `Static` **CancelLocalNotificationById**(`NotificationId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NotificationId` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:24322](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24322)

___

### ClearAllLocalNotifications

▸ `Static` **ClearAllLocalNotifications**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:24323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24323)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlueprintPlatformLibrary`](ue_ue.BlueprintPlatformLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlueprintPlatformLibrary`](ue_ue.BlueprintPlatformLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:24331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24331)

___

### GetDeviceOrientation

▸ `Static` **GetDeviceOrientation**(): [`EScreenOrientation`](../enums/ue_ue.EScreenOrientation.md)

#### Returns

[`EScreenOrientation`](../enums/ue_ue.EScreenOrientation.md)

#### Defined in

[ue/ue.d.ts:24324](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24324)

___

### GetLaunchNotification

▸ `Static` **GetLaunchNotification**(`NotificationLaunchedApp`, `ActivationEvent`, `FireDate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NotificationLaunchedApp` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `ActivationEvent` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `FireDate` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:24325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24325)

___

### Load

▸ `Static` **Load**(`InName`): [`BlueprintPlatformLibrary`](ue_ue.BlueprintPlatformLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlueprintPlatformLibrary`](ue_ue.BlueprintPlatformLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:24332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24332)

___

### ScheduleLocalNotificationAtTime

▸ `Static` **ScheduleLocalNotificationAtTime**(`FireDateTime`, `LocalTime`, `Title`, `Body`, `Action`, `ActivationEvent`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FireDateTime` | [`DateTime`](ue_ue.DateTime.md) |
| `LocalTime` | `boolean` |
| `Title` | `string` |
| `Body` | `string` |
| `Action` | `string` |
| `ActivationEvent` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:24326](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24326)

___

### ScheduleLocalNotificationBadgeAtTime

▸ `Static` **ScheduleLocalNotificationBadgeAtTime**(`FireDateTime`, `LocalTime`, `ActivationEvent`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FireDateTime` | [`DateTime`](ue_ue.DateTime.md) |
| `LocalTime` | `boolean` |
| `ActivationEvent` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:24327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24327)

___

### ScheduleLocalNotificationBadgeFromNow

▸ `Static` **ScheduleLocalNotificationBadgeFromNow**(`inSecondsFromNow`, `ActivationEvent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `inSecondsFromNow` | `number` |
| `ActivationEvent` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:24328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24328)

___

### ScheduleLocalNotificationFromNow

▸ `Static` **ScheduleLocalNotificationFromNow**(`inSecondsFromNow`, `Title`, `Body`, `Action`, `ActivationEvent`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `inSecondsFromNow` | `number` |
| `Title` | `string` |
| `Body` | `string` |
| `Action` | `string` |
| `ActivationEvent` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:24329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24329)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:24330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24330)
