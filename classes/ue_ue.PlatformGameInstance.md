[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PlatformGameInstance

# Class: PlatformGameInstance

[ue/ue](../modules/ue_ue.md).PlatformGameInstance

## Hierarchy

- [`GameInstance`](ue_ue.GameInstance.md)

  ↳ **`PlatformGameInstance`**

## Table of contents

### Constructors

- [constructor](ue_ue.PlatformGameInstance.md#constructor)

### Properties

- [ApplicationFailedToRegisterForRemoteNotificationsDelegate](ue_ue.PlatformGameInstance.md#applicationfailedtoregisterforremotenotificationsdelegate)
- [ApplicationHasEnteredForegroundDelegate](ue_ue.PlatformGameInstance.md#applicationhasenteredforegrounddelegate)
- [ApplicationHasReactivatedDelegate](ue_ue.PlatformGameInstance.md#applicationhasreactivateddelegate)
- [ApplicationReceivedLocalNotificationDelegate](ue_ue.PlatformGameInstance.md#applicationreceivedlocalnotificationdelegate)
- [ApplicationReceivedRemoteNotificationDelegate](ue_ue.PlatformGameInstance.md#applicationreceivedremotenotificationdelegate)
- [ApplicationReceivedScreenOrientationChangedNotificationDelegate](ue_ue.PlatformGameInstance.md#applicationreceivedscreenorientationchangednotificationdelegate)
- [ApplicationReceivedStartupArgumentsDelegate](ue_ue.PlatformGameInstance.md#applicationreceivedstartupargumentsdelegate)
- [ApplicationRegisteredForRemoteNotificationsDelegate](ue_ue.PlatformGameInstance.md#applicationregisteredforremotenotificationsdelegate)
- [ApplicationRegisteredForUserNotificationsDelegate](ue_ue.PlatformGameInstance.md#applicationregisteredforusernotificationsdelegate)
- [ApplicationShouldUnloadResourcesDelegate](ue_ue.PlatformGameInstance.md#applicationshouldunloadresourcesdelegate)
- [ApplicationWillDeactivateDelegate](ue_ue.PlatformGameInstance.md#applicationwilldeactivatedelegate)
- [ApplicationWillEnterBackgroundDelegate](ue_ue.PlatformGameInstance.md#applicationwillenterbackgrounddelegate)
- [ApplicationWillTerminateDelegate](ue_ue.PlatformGameInstance.md#applicationwillterminatedelegate)
- [LocalPlayers](ue_ue.PlatformGameInstance.md#localplayers)
- [OnlineSession](ue_ue.PlatformGameInstance.md#onlinesession)
- [ReferencedObjects](ue_ue.PlatformGameInstance.md#referencedobjects)
- [\_\_tid\_GameInstance\_\_](ue_ue.PlatformGameInstance.md#__tid_gameinstance__)
- [\_\_tid\_Object\_\_](ue_ue.PlatformGameInstance.md#__tid_object__)
- [\_\_tid\_PlatformGameInstance\_\_](ue_ue.PlatformGameInstance.md#__tid_platformgameinstance__)

### Methods

- [CreateDefaultSubobject](ue_ue.PlatformGameInstance.md#createdefaultsubobject)
- [DebugCreatePlayer](ue_ue.PlatformGameInstance.md#debugcreateplayer)
- [DebugRemovePlayer](ue_ue.PlatformGameInstance.md#debugremoveplayer)
- [ExecuteUbergraph](ue_ue.PlatformGameInstance.md#executeubergraph)
- [GetClass](ue_ue.PlatformGameInstance.md#getclass)
- [GetName](ue_ue.PlatformGameInstance.md#getname)
- [GetOuter](ue_ue.PlatformGameInstance.md#getouter)
- [GetWorld](ue_ue.PlatformGameInstance.md#getworld)
- [HandleNetworkError](ue_ue.PlatformGameInstance.md#handlenetworkerror)
- [HandleTravelError](ue_ue.PlatformGameInstance.md#handletravelerror)
- [PlatformDelegate\_\_DelegateSignature](ue_ue.PlatformGameInstance.md#platformdelegate__delegatesignature)
- [PlatformFailedToRegisterForRemoteNotificationsDelegate\_\_DelegateSignature](ue_ue.PlatformGameInstance.md#platformfailedtoregisterforremotenotificationsdelegate__delegatesignature)
- [PlatformReceivedLocalNotificationDelegate\_\_DelegateSignature](ue_ue.PlatformGameInstance.md#platformreceivedlocalnotificationdelegate__delegatesignature)
- [PlatformReceivedRemoteNotificationDelegate\_\_DelegateSignature](ue_ue.PlatformGameInstance.md#platformreceivedremotenotificationdelegate__delegatesignature)
- [PlatformRegisteredForRemoteNotificationsDelegate\_\_DelegateSignature](ue_ue.PlatformGameInstance.md#platformregisteredforremotenotificationsdelegate__delegatesignature)
- [PlatformRegisteredForUserNotificationsDelegate\_\_DelegateSignature](ue_ue.PlatformGameInstance.md#platformregisteredforusernotificationsdelegate__delegatesignature)
- [PlatformScreenOrientationChangedDelegate\_\_DelegateSignature](ue_ue.PlatformGameInstance.md#platformscreenorientationchangeddelegate__delegatesignature)
- [PlatformStartupArgumentsDelegate\_\_DelegateSignature](ue_ue.PlatformGameInstance.md#platformstartupargumentsdelegate__delegatesignature)
- [ReceiveInit](ue_ue.PlatformGameInstance.md#receiveinit)
- [ReceiveShutdown](ue_ue.PlatformGameInstance.md#receiveshutdown)
- [Find](ue_ue.PlatformGameInstance.md#find)
- [Load](ue_ue.PlatformGameInstance.md#load)
- [StaticClass](ue_ue.PlatformGameInstance.md#staticclass)

## Constructors

### constructor

• **new PlatformGameInstance**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GameInstance](ue_ue.GameInstance.md).[constructor](ue_ue.GameInstance.md#constructor)

#### Defined in

[ue/ue.d.ts:58037](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58037)

## Properties

### ApplicationFailedToRegisterForRemoteNotificationsDelegate

• **ApplicationFailedToRegisterForRemoteNotificationsDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`inString`: `string`) => `void`\>

#### Defined in

[ue/ue.d.ts:58047](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58047)

___

### ApplicationHasEnteredForegroundDelegate

• **ApplicationHasEnteredForegroundDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:58041](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58041)

___

### ApplicationHasReactivatedDelegate

• **ApplicationHasReactivatedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:58039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58039)

___

### ApplicationReceivedLocalNotificationDelegate

• **ApplicationReceivedLocalNotificationDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`inString`: `string`, `inInt`: `number`, `inAppState`: [`EApplicationState`](../enums/ue_ue.EApplicationState.md)) => `void`\>

#### Defined in

[ue/ue.d.ts:58049](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58049)

___

### ApplicationReceivedRemoteNotificationDelegate

• **ApplicationReceivedRemoteNotificationDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`inString`: `string`, `inAppState`: [`EApplicationState`](../enums/ue_ue.EApplicationState.md)) => `void`\>

#### Defined in

[ue/ue.d.ts:58048](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58048)

___

### ApplicationReceivedScreenOrientationChangedNotificationDelegate

• **ApplicationReceivedScreenOrientationChangedNotificationDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`inScreenOrientation`: [`EScreenOrientation`](../enums/ue_ue.EScreenOrientation.md)) => `void`\>

#### Defined in

[ue/ue.d.ts:58050](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58050)

___

### ApplicationReceivedStartupArgumentsDelegate

• **ApplicationReceivedStartupArgumentsDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`StartupArguments`: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>) => `void`\>

#### Defined in

[ue/ue.d.ts:58044](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58044)

___

### ApplicationRegisteredForRemoteNotificationsDelegate

• **ApplicationRegisteredForRemoteNotificationsDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`inArray`: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>) => `void`\>

#### Defined in

[ue/ue.d.ts:58045](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58045)

___

### ApplicationRegisteredForUserNotificationsDelegate

• **ApplicationRegisteredForUserNotificationsDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`inInt`: `number`) => `void`\>

#### Defined in

[ue/ue.d.ts:58046](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58046)

___

### ApplicationShouldUnloadResourcesDelegate

• **ApplicationShouldUnloadResourcesDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:58043](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58043)

___

### ApplicationWillDeactivateDelegate

• **ApplicationWillDeactivateDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:58038](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58038)

___

### ApplicationWillEnterBackgroundDelegate

• **ApplicationWillEnterBackgroundDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:58040](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58040)

___

### ApplicationWillTerminateDelegate

• **ApplicationWillTerminateDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:58042](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58042)

___

### LocalPlayers

• **LocalPlayers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LocalPlayer`](ue_ue.LocalPlayer.md)\>

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[LocalPlayers](ue_ue.GameInstance.md#localplayers)

#### Defined in

[ue/ue.d.ts:10190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10190)

___

### OnlineSession

• **OnlineSession**: [`OnlineSession`](ue_ue.OnlineSession.md)

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[OnlineSession](ue_ue.GameInstance.md#onlinesession)

#### Defined in

[ue/ue.d.ts:10191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10191)

___

### ReferencedObjects

• **ReferencedObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[ReferencedObjects](ue_ue.GameInstance.md#referencedobjects)

#### Defined in

[ue/ue.d.ts:10192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10192)

___

### \_\_tid\_GameInstance\_\_

• **\_\_tid\_GameInstance\_\_**: `boolean`

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[__tid_GameInstance__](ue_ue.GameInstance.md#__tid_gameinstance__)

#### Defined in

[ue/ue.d.ts:10203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10203)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[__tid_Object__](ue_ue.GameInstance.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PlatformGameInstance\_\_

• **\_\_tid\_PlatformGameInstance\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:58063](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58063)

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

[GameInstance](ue_ue.GameInstance.md).[CreateDefaultSubobject](ue_ue.GameInstance.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### DebugCreatePlayer

▸ **DebugCreatePlayer**(`ControllerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ControllerId` | `number` |

#### Returns

`void`

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[DebugCreatePlayer](ue_ue.GameInstance.md#debugcreateplayer)

#### Defined in

[ue/ue.d.ts:10193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10193)

___

### DebugRemovePlayer

▸ **DebugRemovePlayer**(`ControllerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ControllerId` | `number` |

#### Returns

`void`

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[DebugRemovePlayer](ue_ue.GameInstance.md#debugremoveplayer)

#### Defined in

[ue/ue.d.ts:10194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10194)

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

[GameInstance](ue_ue.GameInstance.md).[ExecuteUbergraph](ue_ue.GameInstance.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[GetClass](ue_ue.GameInstance.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[GetName](ue_ue.GameInstance.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[GetOuter](ue_ue.GameInstance.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[GetWorld](ue_ue.GameInstance.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### HandleNetworkError

▸ **HandleNetworkError**(`FailureType`, `bIsServer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FailureType` | [`ENetworkFailure`](../enums/ue_ue.ENetworkFailure.md) |
| `bIsServer` | `boolean` |

#### Returns

`void`

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[HandleNetworkError](ue_ue.GameInstance.md#handlenetworkerror)

#### Defined in

[ue/ue.d.ts:10195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10195)

___

### HandleTravelError

▸ **HandleTravelError**(`FailureType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FailureType` | [`ETravelFailure`](../enums/ue_ue.ETravelFailure.md) |

#### Returns

`void`

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[HandleTravelError](ue_ue.GameInstance.md#handletravelerror)

#### Defined in

[ue/ue.d.ts:10196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10196)

___

### PlatformDelegate\_\_DelegateSignature

▸ **PlatformDelegate__DelegateSignature**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58051](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58051)

___

### PlatformFailedToRegisterForRemoteNotificationsDelegate\_\_DelegateSignature

▸ **PlatformFailedToRegisterForRemoteNotificationsDelegate__DelegateSignature**(`inString`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `inString` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58052](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58052)

___

### PlatformReceivedLocalNotificationDelegate\_\_DelegateSignature

▸ **PlatformReceivedLocalNotificationDelegate__DelegateSignature**(`inString`, `inInt`, `inAppState`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `inString` | `string` |
| `inInt` | `number` |
| `inAppState` | [`EApplicationState`](../enums/ue_ue.EApplicationState.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58053](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58053)

___

### PlatformReceivedRemoteNotificationDelegate\_\_DelegateSignature

▸ **PlatformReceivedRemoteNotificationDelegate__DelegateSignature**(`inString`, `inAppState`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `inString` | `string` |
| `inAppState` | [`EApplicationState`](../enums/ue_ue.EApplicationState.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58054](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58054)

___

### PlatformRegisteredForRemoteNotificationsDelegate\_\_DelegateSignature

▸ **PlatformRegisteredForRemoteNotificationsDelegate__DelegateSignature**(`inArray`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `inArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58055](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58055)

___

### PlatformRegisteredForUserNotificationsDelegate\_\_DelegateSignature

▸ **PlatformRegisteredForUserNotificationsDelegate__DelegateSignature**(`inInt`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `inInt` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58056](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58056)

___

### PlatformScreenOrientationChangedDelegate\_\_DelegateSignature

▸ **PlatformScreenOrientationChangedDelegate__DelegateSignature**(`inScreenOrientation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `inScreenOrientation` | [`EScreenOrientation`](../enums/ue_ue.EScreenOrientation.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58057](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58057)

___

### PlatformStartupArgumentsDelegate\_\_DelegateSignature

▸ **PlatformStartupArgumentsDelegate__DelegateSignature**(`StartupArguments`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StartupArguments` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:58058](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58058)

___

### ReceiveInit

▸ **ReceiveInit**(): `void`

#### Returns

`void`

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[ReceiveInit](ue_ue.GameInstance.md#receiveinit)

#### Defined in

[ue/ue.d.ts:10197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10197)

___

### ReceiveShutdown

▸ **ReceiveShutdown**(): `void`

#### Returns

`void`

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[ReceiveShutdown](ue_ue.GameInstance.md#receiveshutdown)

#### Defined in

[ue/ue.d.ts:10198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10198)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PlatformGameInstance`](ue_ue.PlatformGameInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PlatformGameInstance`](ue_ue.PlatformGameInstance.md)

#### Overrides

[GameInstance](ue_ue.GameInstance.md).[Find](ue_ue.GameInstance.md#find)

#### Defined in

[ue/ue.d.ts:58060](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58060)

___

### Load

▸ `Static` **Load**(`InName`): [`PlatformGameInstance`](ue_ue.PlatformGameInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PlatformGameInstance`](ue_ue.PlatformGameInstance.md)

#### Overrides

[GameInstance](ue_ue.GameInstance.md).[Load](ue_ue.GameInstance.md#load)

#### Defined in

[ue/ue.d.ts:58061](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58061)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameInstance](ue_ue.GameInstance.md).[StaticClass](ue_ue.GameInstance.md#staticclass)

#### Defined in

[ue/ue.d.ts:58059](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58059)
