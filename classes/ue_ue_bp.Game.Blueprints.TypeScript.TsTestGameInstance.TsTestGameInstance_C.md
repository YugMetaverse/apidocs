[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue\_bp](../modules/ue_ue_bp.md) / [Game](../modules/ue_ue_bp.Game.md) / [Blueprints](../modules/ue_ue_bp.Game.Blueprints.md) / [TypeScript](../modules/ue_ue_bp.Game.Blueprints.TypeScript.md) / [TsTestGameInstance](../modules/ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.md) / TsTestGameInstance\_C

# Class: TsTestGameInstance\_C

[TypeScript](../modules/ue_ue_bp.Game.Blueprints.TypeScript.md).[TsTestGameInstance](../modules/ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.md).TsTestGameInstance_C

## Hierarchy

- [`TypeScriptGameInstance`](ue_ue.TypeScriptGameInstance.md)

  ↳ **`TsTestGameInstance_C`**

## Table of contents

### Constructors

- [constructor](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#constructor)

### Properties

- [LocalPlayers](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#localplayers)
- [OnlineSession](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#onlinesession)
- [ReferencedObjects](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#referencedobjects)
- [ShutdownNotify](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#shutdownnotify)
- [StartNotify](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#startnotify)
- [UberGraphFrame](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#ubergraphframe)
- [\_\_tid\_GameInstance\_\_](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#__tid_gameinstance__)
- [\_\_tid\_Object\_\_](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#__tid_object__)
- [\_\_tid\_TsTestGameInstance\_C\_\_](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#__tid_tstestgameinstance_c__)
- [\_\_tid\_TypeScriptGameInstance\_\_](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#__tid_typescriptgameinstance__)

### Methods

- [CreateDefaultSubobject](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#createdefaultsubobject)
- [DebugCreatePlayer](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#debugcreateplayer)
- [DebugRemovePlayer](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#debugremoveplayer)
- [ExecuteUbergraph](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#executeubergraph)
- [ExecuteUbergraph\_TsTestGameInstance](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#executeubergraph_tstestgameinstance)
- [GetClass](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#getclass)
- [GetName](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#getname)
- [GetOuter](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#getouter)
- [GetWorld](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#getworld)
- [HandleNetworkError](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#handlenetworkerror)
- [HandleTravelError](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#handletravelerror)
- [ReceiveInit](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#receiveinit)
- [ReceiveShutdown](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#receiveshutdown)
- [Find](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#find)
- [Load](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#load)
- [StaticClass](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md#staticclass)

## Constructors

### constructor

• **new TsTestGameInstance_C**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[constructor](ue_ue.TypeScriptGameInstance.md#constructor)

#### Defined in

[ue/ue_bp.d.ts:166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_bp.d.ts#L166)

## Properties

### LocalPlayers

• **LocalPlayers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LocalPlayer`](ue_ue.LocalPlayer.md)\>

#### Inherited from

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[LocalPlayers](ue_ue.TypeScriptGameInstance.md#localplayers)

#### Defined in

[ue/ue.d.ts:10190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10190)

___

### OnlineSession

• **OnlineSession**: [`OnlineSession`](ue_ue.OnlineSession.md)

#### Inherited from

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[OnlineSession](ue_ue.TypeScriptGameInstance.md#onlinesession)

#### Defined in

[ue/ue.d.ts:10191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10191)

___

### ReferencedObjects

• **ReferencedObjects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[ReferencedObjects](ue_ue.TypeScriptGameInstance.md#referencedobjects)

#### Defined in

[ue/ue.d.ts:10192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10192)

___

### ShutdownNotify

• **ShutdownNotify**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\>

#### Inherited from

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[ShutdownNotify](ue_ue.TypeScriptGameInstance.md#shutdownnotify)

#### Defined in

[ue/ue.d.ts:64355](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64355)

___

### StartNotify

• **StartNotify**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\>

#### Inherited from

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[StartNotify](ue_ue.TypeScriptGameInstance.md#startnotify)

#### Defined in

[ue/ue.d.ts:64354](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64354)

___

### UberGraphFrame

• **UberGraphFrame**: [`PointerToUberGraphFrame`](ue_ue.PointerToUberGraphFrame.md)

#### Defined in

[ue/ue_bp.d.ts:167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_bp.d.ts#L167)

___

### \_\_tid\_GameInstance\_\_

• **\_\_tid\_GameInstance\_\_**: `boolean`

#### Inherited from

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[__tid_GameInstance__](ue_ue.TypeScriptGameInstance.md#__tid_gameinstance__)

#### Defined in

[ue/ue.d.ts:10203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10203)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[__tid_Object__](ue_ue.TypeScriptGameInstance.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_TsTestGameInstance\_C\_\_

• **\_\_tid\_TsTestGameInstance\_C\_\_**: `boolean`

#### Defined in

[ue/ue_bp.d.ts:174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_bp.d.ts#L174)

___

### \_\_tid\_TypeScriptGameInstance\_\_

• **\_\_tid\_TypeScriptGameInstance\_\_**: `boolean`

#### Inherited from

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[__tid_TypeScriptGameInstance__](ue_ue.TypeScriptGameInstance.md#__tid_typescriptgameinstance__)

#### Defined in

[ue/ue.d.ts:64360](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L64360)

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

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[CreateDefaultSubobject](ue_ue.TypeScriptGameInstance.md#createdefaultsubobject)

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

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[DebugCreatePlayer](ue_ue.TypeScriptGameInstance.md#debugcreateplayer)

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

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[DebugRemovePlayer](ue_ue.TypeScriptGameInstance.md#debugremoveplayer)

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

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[ExecuteUbergraph](ue_ue.TypeScriptGameInstance.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### ExecuteUbergraph\_TsTestGameInstance

▸ **ExecuteUbergraph_TsTestGameInstance**(`EntryPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryPoint` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue_bp.d.ts:168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_bp.d.ts#L168)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[GetClass](ue_ue.TypeScriptGameInstance.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[GetName](ue_ue.TypeScriptGameInstance.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[GetOuter](ue_ue.TypeScriptGameInstance.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[GetWorld](ue_ue.TypeScriptGameInstance.md#getworld)

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

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[HandleNetworkError](ue_ue.TypeScriptGameInstance.md#handlenetworkerror)

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

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[HandleTravelError](ue_ue.TypeScriptGameInstance.md#handletravelerror)

#### Defined in

[ue/ue.d.ts:10196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10196)

___

### ReceiveInit

▸ **ReceiveInit**(): `void`

#### Returns

`void`

#### Overrides

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[ReceiveInit](ue_ue.TypeScriptGameInstance.md#receiveinit)

#### Defined in

[ue/ue_bp.d.ts:169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_bp.d.ts#L169)

___

### ReceiveShutdown

▸ **ReceiveShutdown**(): `void`

#### Returns

`void`

#### Inherited from

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[ReceiveShutdown](ue_ue.TypeScriptGameInstance.md#receiveshutdown)

#### Defined in

[ue/ue.d.ts:10198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L10198)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TsTestGameInstance_C`](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TsTestGameInstance_C`](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md)

#### Overrides

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[Find](ue_ue.TypeScriptGameInstance.md#find)

#### Defined in

[ue/ue_bp.d.ts:171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_bp.d.ts#L171)

___

### Load

▸ `Static` **Load**(`InName`): [`TsTestGameInstance_C`](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TsTestGameInstance_C`](ue_ue_bp.Game.Blueprints.TypeScript.TsTestGameInstance.TsTestGameInstance_C.md)

#### Overrides

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[Load](ue_ue.TypeScriptGameInstance.md#load)

#### Defined in

[ue/ue_bp.d.ts:172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_bp.d.ts#L172)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[TypeScriptGameInstance](ue_ue.TypeScriptGameInstance.md).[StaticClass](ue_ue.TypeScriptGameInstance.md#staticclass)

#### Defined in

[ue/ue_bp.d.ts:170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_bp.d.ts#L170)
