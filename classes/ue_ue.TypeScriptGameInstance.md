[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TypeScriptGameInstance

# Class: TypeScriptGameInstance

[ue/ue](../modules/ue_ue.md).TypeScriptGameInstance

## Hierarchy

- [`GameInstance`](ue_ue.GameInstance.md)

  ↳ **`TypeScriptGameInstance`**

  ↳↳ [`TsTestGameInstance_C`](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md)

## Table of contents

### Constructors

- [constructor](ue_ue.TypeScriptGameInstance.md#constructor)

### Properties

- [LocalPlayers](ue_ue.TypeScriptGameInstance.md#localplayers)
- [OnlineSession](ue_ue.TypeScriptGameInstance.md#onlinesession)
- [ReferencedObjects](ue_ue.TypeScriptGameInstance.md#referencedobjects)
- [ShutdownNotify](ue_ue.TypeScriptGameInstance.md#shutdownnotify)
- [StartNotify](ue_ue.TypeScriptGameInstance.md#startnotify)
- [\_\_tid\_GameInstance\_\_](ue_ue.TypeScriptGameInstance.md#__tid_gameinstance__)
- [\_\_tid\_Object\_\_](ue_ue.TypeScriptGameInstance.md#__tid_object__)
- [\_\_tid\_TypeScriptGameInstance\_\_](ue_ue.TypeScriptGameInstance.md#__tid_typescriptgameinstance__)

### Methods

- [CreateDefaultSubobject](ue_ue.TypeScriptGameInstance.md#createdefaultsubobject)
- [DebugCreatePlayer](ue_ue.TypeScriptGameInstance.md#debugcreateplayer)
- [DebugRemovePlayer](ue_ue.TypeScriptGameInstance.md#debugremoveplayer)
- [ExecuteUbergraph](ue_ue.TypeScriptGameInstance.md#executeubergraph)
- [GetClass](ue_ue.TypeScriptGameInstance.md#getclass)
- [GetName](ue_ue.TypeScriptGameInstance.md#getname)
- [GetOuter](ue_ue.TypeScriptGameInstance.md#getouter)
- [GetWorld](ue_ue.TypeScriptGameInstance.md#getworld)
- [HandleNetworkError](ue_ue.TypeScriptGameInstance.md#handlenetworkerror)
- [HandleTravelError](ue_ue.TypeScriptGameInstance.md#handletravelerror)
- [ReceiveInit](ue_ue.TypeScriptGameInstance.md#receiveinit)
- [ReceiveShutdown](ue_ue.TypeScriptGameInstance.md#receiveshutdown)
- [Find](ue_ue.TypeScriptGameInstance.md#find)
- [Load](ue_ue.TypeScriptGameInstance.md#load)
- [StaticClass](ue_ue.TypeScriptGameInstance.md#staticclass)

## Constructors

### constructor

• **new TypeScriptGameInstance**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GameInstance](ue_ue.GameInstance.md).[constructor](ue_ue.GameInstance.md#constructor)

## Properties

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

### ShutdownNotify

• **ShutdownNotify**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\>

___

### StartNotify

• **StartNotify**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\>

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

### \_\_tid\_TypeScriptGameInstance\_\_

• **\_\_tid\_TypeScriptGameInstance\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TypeScriptGameInstance`](ue_ue.TypeScriptGameInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TypeScriptGameInstance`](ue_ue.TypeScriptGameInstance.md)

#### Overrides

[GameInstance](ue_ue.GameInstance.md).[Find](ue_ue.GameInstance.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TypeScriptGameInstance`](ue_ue.TypeScriptGameInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TypeScriptGameInstance`](ue_ue.TypeScriptGameInstance.md)

#### Overrides

[GameInstance](ue_ue.GameInstance.md).[Load](ue_ue.GameInstance.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameInstance](ue_ue.GameInstance.md).[StaticClass](ue_ue.GameInstance.md#staticclass)
