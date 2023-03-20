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

## Properties

### ApplicationFailedToRegisterForRemoteNotificationsDelegate

• **ApplicationFailedToRegisterForRemoteNotificationsDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`inString`: `string`) => `void`\>

___

### ApplicationHasEnteredForegroundDelegate

• **ApplicationHasEnteredForegroundDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### ApplicationHasReactivatedDelegate

• **ApplicationHasReactivatedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### ApplicationReceivedLocalNotificationDelegate

• **ApplicationReceivedLocalNotificationDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`inString`: `string`, `inInt`: `number`, `inAppState`: [`EApplicationState`](../enums/ue_ue.EApplicationState.md)) => `void`\>

___

### ApplicationReceivedRemoteNotificationDelegate

• **ApplicationReceivedRemoteNotificationDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`inString`: `string`, `inAppState`: [`EApplicationState`](../enums/ue_ue.EApplicationState.md)) => `void`\>

___

### ApplicationReceivedScreenOrientationChangedNotificationDelegate

• **ApplicationReceivedScreenOrientationChangedNotificationDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`inScreenOrientation`: [`EScreenOrientation`](../enums/ue_ue.EScreenOrientation.md)) => `void`\>

___

### ApplicationReceivedStartupArgumentsDelegate

• **ApplicationReceivedStartupArgumentsDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`StartupArguments`: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>) => `void`\>

___

### ApplicationRegisteredForRemoteNotificationsDelegate

• **ApplicationRegisteredForRemoteNotificationsDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`inArray`: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>) => `void`\>

___

### ApplicationRegisteredForUserNotificationsDelegate

• **ApplicationRegisteredForUserNotificationsDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`inInt`: `number`) => `void`\>

___

### ApplicationShouldUnloadResourcesDelegate

• **ApplicationShouldUnloadResourcesDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### ApplicationWillDeactivateDelegate

• **ApplicationWillDeactivateDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### ApplicationWillEnterBackgroundDelegate

• **ApplicationWillEnterBackgroundDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### ApplicationWillTerminateDelegate

• **ApplicationWillTerminateDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### LocalPlayers

• **LocalPlayers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LocalPlayer`](ue_ue.LocalPlayer.md)\>

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[LocalPlayers](ue_ue.GameInstance.md#localplayers)

___

### OnlineSession

• **OnlineSession**: [`OnlineSession`](ue_ue.OnlineSession.md)

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[OnlineSession](ue_ue.GameInstance.md#onlinesession)

___

### ReferencedObjects

• **ReferencedObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[ReferencedObjects](ue_ue.GameInstance.md#referencedobjects)

___

### \_\_tid\_GameInstance\_\_

• **\_\_tid\_GameInstance\_\_**: `boolean`

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[__tid_GameInstance__](ue_ue.GameInstance.md#__tid_gameinstance__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[__tid_Object__](ue_ue.GameInstance.md#__tid_object__)

___

### \_\_tid\_PlatformGameInstance\_\_

• **\_\_tid\_PlatformGameInstance\_\_**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[GetClass](ue_ue.GameInstance.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[GetName](ue_ue.GameInstance.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[GetOuter](ue_ue.GameInstance.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[GetWorld](ue_ue.GameInstance.md#getworld)

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

___

### PlatformDelegate\_\_DelegateSignature

▸ **PlatformDelegate__DelegateSignature**(): `void`

#### Returns

`void`

___

### PlatformFailedToRegisterForRemoteNotificationsDelegate\_\_DelegateSignature

▸ **PlatformFailedToRegisterForRemoteNotificationsDelegate__DelegateSignature**(`inString`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `inString` | `string` |

#### Returns

`void`

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

___

### PlatformRegisteredForRemoteNotificationsDelegate\_\_DelegateSignature

▸ **PlatformRegisteredForRemoteNotificationsDelegate__DelegateSignature**(`inArray`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `inArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`void`

___

### PlatformRegisteredForUserNotificationsDelegate\_\_DelegateSignature

▸ **PlatformRegisteredForUserNotificationsDelegate__DelegateSignature**(`inInt`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `inInt` | `number` |

#### Returns

`void`

___

### PlatformScreenOrientationChangedDelegate\_\_DelegateSignature

▸ **PlatformScreenOrientationChangedDelegate__DelegateSignature**(`inScreenOrientation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `inScreenOrientation` | [`EScreenOrientation`](../enums/ue_ue.EScreenOrientation.md) |

#### Returns

`void`

___

### PlatformStartupArgumentsDelegate\_\_DelegateSignature

▸ **PlatformStartupArgumentsDelegate__DelegateSignature**(`StartupArguments`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StartupArguments` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`void`

___

### ReceiveInit

▸ **ReceiveInit**(): `void`

#### Returns

`void`

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[ReceiveInit](ue_ue.GameInstance.md#receiveinit)

___

### ReceiveShutdown

▸ **ReceiveShutdown**(): `void`

#### Returns

`void`

#### Inherited from

[GameInstance](ue_ue.GameInstance.md).[ReceiveShutdown](ue_ue.GameInstance.md#receiveshutdown)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameInstance](ue_ue.GameInstance.md).[StaticClass](ue_ue.GameInstance.md#staticclass)
