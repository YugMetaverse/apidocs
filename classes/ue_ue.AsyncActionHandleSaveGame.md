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

## Properties

### Completed

• **Completed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SaveGame`: [`$Nullable`](../modules/puerts.md#$nullable)<[`SaveGame`](ue_ue.SaveGame.md)\>, `bSuccess`: `boolean`) => `void`\>

___

### SaveGameObject

• **SaveGameObject**: [`SaveGame`](ue_ue.SaveGame.md)

___

### \_\_tid\_AsyncActionHandleSaveGame\_\_

• **\_\_tid\_AsyncActionHandleSaveGame\_\_**: `boolean`

___

### \_\_tid\_BlueprintAsyncActionBase\_\_

• **\_\_tid\_BlueprintAsyncActionBase\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_BlueprintAsyncActionBase__](ue_ue.BlueprintAsyncActionBase.md#__tid_blueprintasyncactionbase__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[__tid_Object__](ue_ue.BlueprintAsyncActionBase.md#__tid_object__)

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[Activate](ue_ue.BlueprintAsyncActionBase.md#activate)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetClass](ue_ue.BlueprintAsyncActionBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetName](ue_ue.BlueprintAsyncActionBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetOuter](ue_ue.BlueprintAsyncActionBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[GetWorld](ue_ue.BlueprintAsyncActionBase.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintAsyncActionBase](ue_ue.BlueprintAsyncActionBase.md).[StaticClass](ue_ue.BlueprintAsyncActionBase.md#staticclass)
