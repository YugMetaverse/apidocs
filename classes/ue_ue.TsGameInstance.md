[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TsGameInstance

# Class: TsGameInstance

[ue/ue](../modules/ue_ue.md).TsGameInstance

## Hierarchy

- [`GameInstance`](ue_ue.GameInstance.md)

  ↳ **`TsGameInstance`**

## Table of contents

### Constructors

- [constructor](ue_ue.TsGameInstance.md#constructor)

### Properties

- [LocalPlayers](ue_ue.TsGameInstance.md#localplayers)
- [OnlineSession](ue_ue.TsGameInstance.md#onlinesession)
- [ReferencedObjects](ue_ue.TsGameInstance.md#referencedobjects)
- [\_\_tid\_GameInstance\_\_](ue_ue.TsGameInstance.md#__tid_gameinstance__)
- [\_\_tid\_Object\_\_](ue_ue.TsGameInstance.md#__tid_object__)
- [\_\_tid\_TsGameInstance\_\_](ue_ue.TsGameInstance.md#__tid_tsgameinstance__)

### Methods

- [CreateDefaultSubobject](ue_ue.TsGameInstance.md#createdefaultsubobject)
- [DebugCreatePlayer](ue_ue.TsGameInstance.md#debugcreateplayer)
- [DebugRemovePlayer](ue_ue.TsGameInstance.md#debugremoveplayer)
- [ExecuteUbergraph](ue_ue.TsGameInstance.md#executeubergraph)
- [GetClass](ue_ue.TsGameInstance.md#getclass)
- [GetName](ue_ue.TsGameInstance.md#getname)
- [GetOuter](ue_ue.TsGameInstance.md#getouter)
- [GetWorld](ue_ue.TsGameInstance.md#getworld)
- [HandleNetworkError](ue_ue.TsGameInstance.md#handlenetworkerror)
- [HandleTravelError](ue_ue.TsGameInstance.md#handletravelerror)
- [ReceiveInit](ue_ue.TsGameInstance.md#receiveinit)
- [ReceiveShutdown](ue_ue.TsGameInstance.md#receiveshutdown)
- [Find](ue_ue.TsGameInstance.md#find)
- [Load](ue_ue.TsGameInstance.md#load)
- [StaticClass](ue_ue.TsGameInstance.md#staticclass)

## Constructors

### constructor

• **new TsGameInstance**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[GameInstance](ue_ue.GameInstance.md).[constructor](ue_ue.GameInstance.md#constructor)

#### Defined in

[ue/ue.d.ts:64270](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64270)

## Properties

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

### \_\_tid\_TsGameInstance\_\_

• **\_\_tid\_TsGameInstance\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64275](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64275)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TsGameInstance`](ue_ue.TsGameInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TsGameInstance`](ue_ue.TsGameInstance.md)

#### Overrides

[GameInstance](ue_ue.GameInstance.md).[Find](ue_ue.GameInstance.md#find)

#### Defined in

[ue/ue.d.ts:64272](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64272)

___

### Load

▸ `Static` **Load**(`InName`): [`TsGameInstance`](ue_ue.TsGameInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TsGameInstance`](ue_ue.TsGameInstance.md)

#### Overrides

[GameInstance](ue_ue.GameInstance.md).[Load](ue_ue.GameInstance.md#load)

#### Defined in

[ue/ue.d.ts:64273](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64273)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[GameInstance](ue_ue.GameInstance.md).[StaticClass](ue_ue.GameInstance.md#staticclass)

#### Defined in

[ue/ue.d.ts:64271](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64271)
