[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AsyncActionHandleSaveGame

# Class: AsyncActionHandleSaveGame

[ue/ue](../modules/ue_ue.md).AsyncActionHandleSaveGame

## Hierarchy

- [`BlueprintAsyncActionBase`](ue_ue.BlueprintAsyncActionBase.md)

  ↳ **`AsyncActionHandleSaveGame`**

## Table of contents

### Constructors

- [constructor](ue_ue.AsyncActionHandleSaveGame.md#constructor)

### Properties

- [Completed](ue_ue.AsyncActionHandleSaveGame.md#completed)
- [SaveGameObject](ue_ue.AsyncActionHandleSaveGame.md#savegameobject)
- [\_\_tid\_AsyncActionHandleSaveGame\_\_](ue_ue.AsyncActionHandleSaveGame.md#__tid_asyncactionhandlesavegame__)
- [\_\_tid\_BlueprintAsyncActionBase\_\_](ue_ue.AsyncActionHandleSaveGame.md#__tid_blueprintasyncactionbase__)
- [\_\_tid\_Object\_\_](ue_ue.AsyncActionHandleSaveGame.md#__tid_object__)

### Methods

- [Activate](ue_ue.AsyncActionHandleSaveGame.md#activate)
- [CreateDefaultSubobject](ue_ue.AsyncActionHandleSaveGame.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AsyncActionHandleSaveGame.md#executeubergraph)
- [GetClass](ue_ue.AsyncActionHandleSaveGame.md#getclass)
- [GetName](ue_ue.AsyncActionHandleSaveGame.md#getname)
- [GetOuter](ue_ue.AsyncActionHandleSaveGame.md#getouter)
- [GetWorld](ue_ue.AsyncActionHandleSaveGame.md#getworld)
- [AsyncLoadGameFromSlot](ue_ue.AsyncActionHandleSaveGame.md#asyncloadgamefromslot)
- [AsyncSaveGameToSlot](ue_ue.AsyncActionHandleSaveGame.md#asyncsavegametoslot)
- [Find](ue_ue.AsyncActionHandleSaveGame.md#find)
- [Load](ue_ue.AsyncActionHandleSaveGame.md#load)
- [StaticClass](ue_ue.AsyncActionHandleSaveGame.md#staticclass)

## Constructors

### constructor

• **new AsyncActionHandleSaveGame**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[constructor](ue_ue.BlueprintAsyncActionBase.md#constructor)

#### Defined in

[ue/ue.d.ts:22079](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22079)

## Properties

### Completed

• **Completed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SaveGame`: [`$Nullable`](../modules/puerts.md#$nullable)<[`SaveGame`](ue_ue.SaveGame.md)\>, `bSuccess`: `boolean`) => `void`\>

#### Defined in

[ue/ue.d.ts:22080](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22080)

___

### SaveGameObject

• **SaveGameObject**: [`SaveGame`](ue_ue.SaveGame.md)

#### Defined in

[ue/ue.d.ts:22081](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22081)

___

### \_\_tid\_AsyncActionHandleSaveGame\_\_

• **\_\_tid\_AsyncActionHandleSaveGame\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:22088](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22088)

___

### \_\_tid\_BlueprintAsyncActionBase\_\_

• **\_\_tid\_BlueprintAsyncActionBase\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_BlueprintAsyncActionBase__](ue_ue.BlueprintAsyncActionBase.md#__tid_blueprintasyncactionbase__)

#### Defined in

[ue/ue.d.ts:20672](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20672)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_Object__](ue_ue.BlueprintAsyncActionBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Activate](ue_ue.BlueprintAsyncActionBase.md#activate)

#### Defined in

[ue/ue.d.ts:20667](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20667)

___

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

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[CreateDefaultSubobject](ue_ue.BlueprintAsyncActionBase.md#createdefaultsubobject)

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

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[ExecuteUbergraph](ue_ue.BlueprintAsyncActionBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetClass](ue_ue.BlueprintAsyncActionBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetName](ue_ue.BlueprintAsyncActionBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetOuter](ue_ue.BlueprintAsyncActionBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetWorld](ue_ue.BlueprintAsyncActionBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### AsyncLoadGameFromSlot

▸ `Static` **AsyncLoadGameFromSlot**(`WorldContextObject`, `SlotName`, `UserIndex`): [`AsyncActionHandleSaveGame`](ue_ue.AsyncActionHandleSaveGame.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `SlotName` | `string` |
| `UserIndex` | `number` |

#### Returns

[`AsyncActionHandleSaveGame`](ue_ue.AsyncActionHandleSaveGame.md)

#### Defined in

[ue/ue.d.ts:22082](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22082)

___

### AsyncSaveGameToSlot

▸ `Static` **AsyncSaveGameToSlot**(`WorldContextObject`, `SaveGameObject`, `SlotName`, `UserIndex`): [`AsyncActionHandleSaveGame`](ue_ue.AsyncActionHandleSaveGame.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `SaveGameObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SaveGame`](ue_ue.SaveGame.md)\> |
| `SlotName` | `string` |
| `UserIndex` | `number` |

#### Returns

[`AsyncActionHandleSaveGame`](ue_ue.AsyncActionHandleSaveGame.md)

#### Defined in

[ue/ue.d.ts:22083](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22083)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AsyncActionHandleSaveGame`](ue_ue.AsyncActionHandleSaveGame.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AsyncActionHandleSaveGame`](ue_ue.AsyncActionHandleSaveGame.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Find](ue_ue.BlueprintAsyncActionBase.md#find)

#### Defined in

[ue/ue.d.ts:22085](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22085)

___

### Load

▸ `Static` **Load**(`InName`): [`AsyncActionHandleSaveGame`](ue_ue.AsyncActionHandleSaveGame.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AsyncActionHandleSaveGame`](ue_ue.AsyncActionHandleSaveGame.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Load](ue_ue.BlueprintAsyncActionBase.md#load)

#### Defined in

[ue/ue.d.ts:22086](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22086)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[StaticClass](ue_ue.BlueprintAsyncActionBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:22084](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22084)
