[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GameInstance

# Class: GameInstance

[ue/ue](../modules/ue_ue.md).GameInstance

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`GameInstance`**

  ↳↳ [`FFITestGameInstance`](ue_ue.FFITestGameInstance.md)

  ↳↳ [`PlatformGameInstance`](ue_ue.PlatformGameInstance.md)

  ↳↳ [`TsGameInstance`](ue_ue.TsGameInstance.md)

  ↳↳ [`TypeScriptGameInstance`](ue_ue.TypeScriptGameInstance.md)

## Table of contents

### Constructors

- [constructor](ue_ue.GameInstance.md#constructor)

### Properties

- [LocalPlayers](ue_ue.GameInstance.md#localplayers)
- [OnlineSession](ue_ue.GameInstance.md#onlinesession)
- [ReferencedObjects](ue_ue.GameInstance.md#referencedobjects)
- [\_\_tid\_GameInstance\_\_](ue_ue.GameInstance.md#__tid_gameinstance__)
- [\_\_tid\_Object\_\_](ue_ue.GameInstance.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.GameInstance.md#createdefaultsubobject)
- [DebugCreatePlayer](ue_ue.GameInstance.md#debugcreateplayer)
- [DebugRemovePlayer](ue_ue.GameInstance.md#debugremoveplayer)
- [ExecuteUbergraph](ue_ue.GameInstance.md#executeubergraph)
- [GetClass](ue_ue.GameInstance.md#getclass)
- [GetName](ue_ue.GameInstance.md#getname)
- [GetOuter](ue_ue.GameInstance.md#getouter)
- [GetWorld](ue_ue.GameInstance.md#getworld)
- [HandleNetworkError](ue_ue.GameInstance.md#handlenetworkerror)
- [HandleTravelError](ue_ue.GameInstance.md#handletravelerror)
- [ReceiveInit](ue_ue.GameInstance.md#receiveinit)
- [ReceiveShutdown](ue_ue.GameInstance.md#receiveshutdown)
- [Find](ue_ue.GameInstance.md#find)
- [Load](ue_ue.GameInstance.md#load)
- [StaticClass](ue_ue.GameInstance.md#staticclass)

## Constructors

### constructor

• **new GameInstance**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### LocalPlayers

• **LocalPlayers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LocalPlayer`](ue_ue.LocalPlayer.md)\>

___

### OnlineSession

• **OnlineSession**: [`OnlineSession`](ue_ue.OnlineSession.md)

___

### ReferencedObjects

• **ReferencedObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

___

### \_\_tid\_GameInstance\_\_

• **\_\_tid\_GameInstance\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

### DebugCreatePlayer

▸ **DebugCreatePlayer**(`ControllerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ControllerId` | `number` |

#### Returns

`void`

___

### DebugRemovePlayer

▸ **DebugRemovePlayer**(`ControllerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ControllerId` | `number` |

#### Returns

`void`

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

### HandleNetworkError

▸ **HandleNetworkError**(`FailureType`, `bIsServer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FailureType` | [`ENetworkFailure`](../enums/ue_ue.ENetworkFailure.md) |
| `bIsServer` | `boolean` |

#### Returns

`void`

___

### HandleTravelError

▸ **HandleTravelError**(`FailureType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FailureType` | [`ETravelFailure`](../enums/ue_ue.ETravelFailure.md) |

#### Returns

`void`

___

### ReceiveInit

▸ **ReceiveInit**(): `void`

#### Returns

`void`

___

### ReceiveShutdown

▸ **ReceiveShutdown**(): `void`

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GameInstance`](ue_ue.GameInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GameInstance`](ue_ue.GameInstance.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GameInstance`](ue_ue.GameInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GameInstance`](ue_ue.GameInstance.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
