[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlueprintMapLibrary

# Class: BlueprintMapLibrary

[ue/ue](../modules/ue_ue.md).BlueprintMapLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`BlueprintMapLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.BlueprintMapLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.BlueprintMapLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_BlueprintMapLibrary\_\_](ue_ue.BlueprintMapLibrary.md#__tid_blueprintmaplibrary__)
- [\_\_tid\_Object\_\_](ue_ue.BlueprintMapLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.BlueprintMapLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BlueprintMapLibrary.md#executeubergraph)
- [GetClass](ue_ue.BlueprintMapLibrary.md#getclass)
- [GetName](ue_ue.BlueprintMapLibrary.md#getname)
- [GetOuter](ue_ue.BlueprintMapLibrary.md#getouter)
- [GetWorld](ue_ue.BlueprintMapLibrary.md#getworld)
- [Find](ue_ue.BlueprintMapLibrary.md#find)
- [Load](ue_ue.BlueprintMapLibrary.md#load)
- [Map\_Add](ue_ue.BlueprintMapLibrary.md#map_add)
- [Map\_Clear](ue_ue.BlueprintMapLibrary.md#map_clear)
- [Map\_Contains](ue_ue.BlueprintMapLibrary.md#map_contains)
- [Map\_Find](ue_ue.BlueprintMapLibrary.md#map_find)
- [Map\_Keys](ue_ue.BlueprintMapLibrary.md#map_keys)
- [Map\_Length](ue_ue.BlueprintMapLibrary.md#map_length)
- [Map\_Remove](ue_ue.BlueprintMapLibrary.md#map_remove)
- [Map\_Values](ue_ue.BlueprintMapLibrary.md#map_values)
- [SetMapPropertyByName](ue_ue.BlueprintMapLibrary.md#setmappropertybyname)
- [StaticClass](ue_ue.BlueprintMapLibrary.md#staticclass)

## Constructors

### constructor

• **new BlueprintMapLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:24178](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24178)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13418)

___

### \_\_tid\_BlueprintMapLibrary\_\_

• **\_\_tid\_BlueprintMapLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:24192](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24192)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlueprintMapLibrary`](ue_ue.BlueprintMapLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlueprintMapLibrary`](ue_ue.BlueprintMapLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:24189](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24189)

___

### Load

▸ `Static` **Load**(`InName`): [`BlueprintMapLibrary`](ue_ue.BlueprintMapLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlueprintMapLibrary`](ue_ue.BlueprintMapLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:24190](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24190)

___

### Map\_Add

▸ `Static` **Map_Add**(`TargetMap`, `Key`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetMap` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, `number`\> |
| `Key` | `number` |
| `Value` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:24179](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24179)

___

### Map\_Clear

▸ `Static` **Map_Clear**(`TargetMap`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetMap` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, `number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:24180](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24180)

___

### Map\_Contains

▸ `Static` **Map_Contains**(`TargetMap`, `Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetMap` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, `number`\> |
| `Key` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:24181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24181)

___

### Map\_Find

▸ `Static` **Map_Find**(`TargetMap`, `Key`, `Value`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetMap` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, `number`\> |
| `Key` | `number` |
| `Value` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:24182](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24182)

___

### Map\_Keys

▸ `Static` **Map_Keys**(`TargetMap`, `Keys`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetMap` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, `number`\> |
| `Keys` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:24183](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24183)

___

### Map\_Length

▸ `Static` **Map_Length**(`TargetMap`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetMap` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, `number`\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:24184](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24184)

___

### Map\_Remove

▸ `Static` **Map_Remove**(`TargetMap`, `Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetMap` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, `number`\> |
| `Key` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:24185](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24185)

___

### Map\_Values

▸ `Static` **Map_Values**(`TargetMap`, `Values`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TargetMap` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, `number`\> |
| `Values` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:24186](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24186)

___

### SetMapPropertyByName

▸ `Static` **SetMapPropertyByName**(`Object`, `PropertyName`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Object` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PropertyName` | `string` |
| `Value` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`number`, `number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:24187](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24187)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:24188](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24188)
