[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EnvQuery

# Class: EnvQuery

[ue/ue](../modules/ue_ue.md).EnvQuery

## Hierarchy

- [`DataAsset`](ue_ue.DataAsset.md)

  ↳ **`EnvQuery`**

## Table of contents

### Constructors

- [constructor](ue_ue.EnvQuery.md#constructor)

### Properties

- [EdGraph](ue_ue.EnvQuery.md#edgraph)
- [NativeClass](ue_ue.EnvQuery.md#nativeclass)
- [Options](ue_ue.EnvQuery.md#options)
- [QueryName](ue_ue.EnvQuery.md#queryname)
- [\_\_tid\_DataAsset\_\_](ue_ue.EnvQuery.md#__tid_dataasset__)
- [\_\_tid\_EnvQuery\_\_](ue_ue.EnvQuery.md#__tid_envquery__)
- [\_\_tid\_Object\_\_](ue_ue.EnvQuery.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EnvQuery.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EnvQuery.md#executeubergraph)
- [GetClass](ue_ue.EnvQuery.md#getclass)
- [GetName](ue_ue.EnvQuery.md#getname)
- [GetOuter](ue_ue.EnvQuery.md#getouter)
- [GetWorld](ue_ue.EnvQuery.md#getworld)
- [Find](ue_ue.EnvQuery.md#find)
- [Load](ue_ue.EnvQuery.md#load)
- [StaticClass](ue_ue.EnvQuery.md#staticclass)

## Constructors

### constructor

• **new EnvQuery**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[constructor](ue_ue.DataAsset.md#constructor)

#### Defined in

[ue/ue.d.ts:15582](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15582)

## Properties

### EdGraph

• **EdGraph**: [`EdGraph`](ue_ue.EdGraph.md)

#### Defined in

[ue/ue.d.ts:15583](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15583)

___

### NativeClass

• **NativeClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[NativeClass](ue_ue.DataAsset.md#nativeclass)

#### Defined in

[ue/ue.d.ts:724](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L724)

___

### Options

• **Options**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EnvQueryOption`](ue_ue.EnvQueryOption.md)\>

#### Defined in

[ue/ue.d.ts:15585](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15585)

___

### QueryName

• **QueryName**: `string`

#### Defined in

[ue/ue.d.ts:15584](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15584)

___

### \_\_tid\_DataAsset\_\_

• **\_\_tid\_DataAsset\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_DataAsset__](ue_ue.DataAsset.md#__tid_dataasset__)

#### Defined in

[ue/ue.d.ts:729](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L729)

___

### \_\_tid\_EnvQuery\_\_

• **\_\_tid\_EnvQuery\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15590](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15590)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_Object__](ue_ue.DataAsset.md#__tid_object__)

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

[DataAsset](ue_ue.DataAsset.md).[CreateDefaultSubobject](ue_ue.DataAsset.md#createdefaultsubobject)

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

[DataAsset](ue_ue.DataAsset.md).[ExecuteUbergraph](ue_ue.DataAsset.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetClass](ue_ue.DataAsset.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetName](ue_ue.DataAsset.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetOuter](ue_ue.DataAsset.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetWorld](ue_ue.DataAsset.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EnvQuery`](ue_ue.EnvQuery.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EnvQuery`](ue_ue.EnvQuery.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[Find](ue_ue.DataAsset.md#find)

#### Defined in

[ue/ue.d.ts:15587](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15587)

___

### Load

▸ `Static` **Load**(`InName`): [`EnvQuery`](ue_ue.EnvQuery.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EnvQuery`](ue_ue.EnvQuery.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[Load](ue_ue.DataAsset.md#load)

#### Defined in

[ue/ue.d.ts:15588](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15588)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[StaticClass](ue_ue.DataAsset.md#staticclass)

#### Defined in

[ue/ue.d.ts:15586](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15586)