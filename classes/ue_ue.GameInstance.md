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

#### Defined in

[ue/ue.d.ts:10189](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10189)

## Properties

### LocalPlayers

• **LocalPlayers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LocalPlayer`](ue_ue.LocalPlayer.md)\>

#### Defined in

[ue/ue.d.ts:10190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10190)

___

### OnlineSession

• **OnlineSession**: [`OnlineSession`](ue_ue.OnlineSession.md)

#### Defined in

[ue/ue.d.ts:10191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10191)

___

### ReferencedObjects

• **ReferencedObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:10192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10192)

___

### \_\_tid\_GameInstance\_\_

• **\_\_tid\_GameInstance\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:10203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10203)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

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

#### Defined in

[ue/ue.d.ts:10196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10196)

___

### ReceiveInit

▸ **ReceiveInit**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:10197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10197)

___

### ReceiveShutdown

▸ **ReceiveShutdown**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:10198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10198)

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

#### Defined in

[ue/ue.d.ts:10200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10200)

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

#### Defined in

[ue/ue.d.ts:10201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10201)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:10199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10199)
