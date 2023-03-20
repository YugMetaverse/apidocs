[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARSaveWorldAsyncTaskBlueprintProxy

# Class: ARSaveWorldAsyncTaskBlueprintProxy

[ue/ue](../modules/ue_ue.md).ARSaveWorldAsyncTaskBlueprintProxy

## Hierarchy

- [`ARBaseAsyncTaskBlueprintProxy`](ue_ue.ARBaseAsyncTaskBlueprintProxy.md)

  ↳ **`ARSaveWorldAsyncTaskBlueprintProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#constructor)

### Properties

- [OnFailed](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#onfailed)
- [OnSuccess](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#onsuccess)
- [\_\_tid\_ARBaseAsyncTaskBlueprintProxy\_\_](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#__tid_arbaseasynctaskblueprintproxy__)
- [\_\_tid\_ARSaveWorldAsyncTaskBlueprintProxy\_\_](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#__tid_arsaveworldasynctaskblueprintproxy__)
- [\_\_tid\_BlueprintAsyncActionBase\_\_](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#__tid_blueprintasyncactionbase__)
- [\_\_tid\_Object\_\_](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#__tid_object__)

### Methods

- [Activate](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#activate)
- [CreateDefaultSubobject](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#executeubergraph)
- [GetClass](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#getclass)
- [GetName](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#getname)
- [GetOuter](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#getouter)
- [GetWorld](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#getworld)
- [ARSaveWorld](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#arsaveworld)
- [Find](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#find)
- [Load](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#load)
- [StaticClass](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md#staticclass)

## Constructors

### constructor

• **new ARSaveWorldAsyncTaskBlueprintProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[constructor](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#constructor)

#### Defined in

[ue/ue.d.ts:21253](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21253)

## Properties

### OnFailed

• **OnFailed**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SavedWorld`: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>) => `void`\>

#### Defined in

[ue/ue.d.ts:21255](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21255)

___

### OnSuccess

• **OnSuccess**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`SavedWorld`: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>) => `void`\>

#### Defined in

[ue/ue.d.ts:21254](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21254)

___

### \_\_tid\_ARBaseAsyncTaskBlueprintProxy\_\_

• **\_\_tid\_ARBaseAsyncTaskBlueprintProxy\_\_**: `boolean`

#### Inherited from

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[__tid_ARBaseAsyncTaskBlueprintProxy__](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#__tid_arbaseasynctaskblueprintproxy__)

#### Defined in

[ue/ue.d.ts:20681](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20681)

___

### \_\_tid\_ARSaveWorldAsyncTaskBlueprintProxy\_\_

• **\_\_tid\_ARSaveWorldAsyncTaskBlueprintProxy\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:21261](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21261)

___

### \_\_tid\_BlueprintAsyncActionBase\_\_

• **\_\_tid\_BlueprintAsyncActionBase\_\_**: `boolean`

#### Inherited from

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[__tid_BlueprintAsyncActionBase__](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#__tid_blueprintasyncactionbase__)

#### Defined in

[ue/ue.d.ts:20672](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20672)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[__tid_Object__](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

#### Inherited from

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[Activate](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#activate)

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

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[CreateDefaultSubobject](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#createdefaultsubobject)

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

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[ExecuteUbergraph](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[GetClass](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[GetName](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[GetOuter](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[GetWorld](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### ARSaveWorld

▸ `Static` **ARSaveWorld**(`WorldContextObject`): [`ARSaveWorldAsyncTaskBlueprintProxy`](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`ARSaveWorldAsyncTaskBlueprintProxy`](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md)

#### Defined in

[ue/ue.d.ts:21256](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21256)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARSaveWorldAsyncTaskBlueprintProxy`](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARSaveWorldAsyncTaskBlueprintProxy`](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md)

#### Overrides

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[Find](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#find)

#### Defined in

[ue/ue.d.ts:21258](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21258)

___

### Load

▸ `Static` **Load**(`InName`): [`ARSaveWorldAsyncTaskBlueprintProxy`](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARSaveWorldAsyncTaskBlueprintProxy`](ue_ue.ARSaveWorldAsyncTaskBlueprintProxy.md)

#### Overrides

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[Load](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#load)

#### Defined in

[ue/ue.d.ts:21259](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21259)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ARBaseAsyncTaskBlueprintProxy](ue_ue.ARBaseAsyncTaskBlueprintProxy.md).[StaticClass](ue_ue.ARBaseAsyncTaskBlueprintProxy.md#staticclass)

#### Defined in

[ue/ue.d.ts:21257](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21257)