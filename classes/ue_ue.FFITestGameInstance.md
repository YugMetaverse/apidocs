[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FFITestGameInstance

# Class: FFITestGameInstance

[ue/ue](../modules/ue_ue.md).FFITestGameInstance

## Hierarchy

- [`GameInstance`](ue_ue.GameInstance.md)

  ↳ **`FFITestGameInstance`**

## Table of contents

### Constructors

- [constructor](ue_ue.FFITestGameInstance.md#constructor)

### Properties

- [LocalPlayers](ue_ue.FFITestGameInstance.md#localplayers)
- [OnlineSession](ue_ue.FFITestGameInstance.md#onlinesession)
- [ReferencedObjects](ue_ue.FFITestGameInstance.md#referencedobjects)
- [\_\_tid\_FFITestGameInstance\_\_](ue_ue.FFITestGameInstance.md#__tid_ffitestgameinstance__)
- [\_\_tid\_GameInstance\_\_](ue_ue.FFITestGameInstance.md#__tid_gameinstance__)
- [\_\_tid\_Object\_\_](ue_ue.FFITestGameInstance.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.FFITestGameInstance.md#createdefaultsubobject)
- [DebugCreatePlayer](ue_ue.FFITestGameInstance.md#debugcreateplayer)
- [DebugRemovePlayer](ue_ue.FFITestGameInstance.md#debugremoveplayer)
- [ExecuteUbergraph](ue_ue.FFITestGameInstance.md#executeubergraph)
- [GetClass](ue_ue.FFITestGameInstance.md#getclass)
- [GetName](ue_ue.FFITestGameInstance.md#getname)
- [GetOuter](ue_ue.FFITestGameInstance.md#getouter)
- [GetWorld](ue_ue.FFITestGameInstance.md#getworld)
- [HandleNetworkError](ue_ue.FFITestGameInstance.md#handlenetworkerror)
- [HandleTravelError](ue_ue.FFITestGameInstance.md#handletravelerror)
- [ReceiveInit](ue_ue.FFITestGameInstance.md#receiveinit)
- [ReceiveShutdown](ue_ue.FFITestGameInstance.md#receiveshutdown)
- [Find](ue_ue.FFITestGameInstance.md#find)
- [Load](ue_ue.FFITestGameInstance.md#load)
- [StaticClass](ue_ue.FFITestGameInstance.md#staticclass)

## Constructors

### constructor

• **new FFITestGameInstance**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### \_\_tid\_FFITestGameInstance\_\_

• **\_\_tid\_FFITestGameInstance\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FFITestGameInstance`](ue_ue.FFITestGameInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FFITestGameInstance`](ue_ue.FFITestGameInstance.md)

#### Overrides

[GameInstance](ue_ue.GameInstance.md).[Find](ue_ue.GameInstance.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`FFITestGameInstance`](ue_ue.FFITestGameInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FFITestGameInstance`](ue_ue.FFITestGameInstance.md)

#### Overrides

[GameInstance](ue_ue.GameInstance.md).[Load](ue_ue.GameInstance.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameInstance](ue_ue.GameInstance.md).[StaticClass](ue_ue.GameInstance.md#staticclass)
