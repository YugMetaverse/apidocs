[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AssetMappingTable

# Class: AssetMappingTable

[ue/ue](../modules/ue_ue.md).AssetMappingTable

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AssetMappingTable`**

## Table of contents

### Constructors

- [constructor](ue_ue.AssetMappingTable.md#constructor)

### Properties

- [MappedAssets](ue_ue.AssetMappingTable.md#mappedassets)
- [\_\_tid\_AssetMappingTable\_\_](ue_ue.AssetMappingTable.md#__tid_assetmappingtable__)
- [\_\_tid\_Object\_\_](ue_ue.AssetMappingTable.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AssetMappingTable.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AssetMappingTable.md#executeubergraph)
- [GetClass](ue_ue.AssetMappingTable.md#getclass)
- [GetName](ue_ue.AssetMappingTable.md#getname)
- [GetOuter](ue_ue.AssetMappingTable.md#getouter)
- [GetWorld](ue_ue.AssetMappingTable.md#getworld)
- [Find](ue_ue.AssetMappingTable.md#find)
- [Load](ue_ue.AssetMappingTable.md#load)
- [StaticClass](ue_ue.AssetMappingTable.md#staticclass)

## Constructors

### constructor

• **new AssetMappingTable**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:2679](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2679)

## Properties

### MappedAssets

• **MappedAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetMapping`](ue_ue.AssetMapping.md)\>

#### Defined in

[ue/ue.d.ts:2680](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2680)

___

### \_\_tid\_AssetMappingTable\_\_

• **\_\_tid\_AssetMappingTable\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:2685](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2685)

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AssetMappingTable`](ue_ue.AssetMappingTable.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AssetMappingTable`](ue_ue.AssetMappingTable.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:2682](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2682)

___

### Load

▸ `Static` **Load**(`InName`): [`AssetMappingTable`](ue_ue.AssetMappingTable.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AssetMappingTable`](ue_ue.AssetMappingTable.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:2683](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2683)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:2681](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L2681)
