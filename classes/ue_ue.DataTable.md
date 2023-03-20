[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DataTable

# Class: DataTable

[ue/ue](../modules/ue_ue.md).DataTable

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`DataTable`**

  ↳↳ [`CompositeDataTable`](ue_ue.CompositeDataTable.md)

## Table of contents

### Constructors

- [constructor](ue_ue.DataTable.md#constructor)

### Properties

- [AssetImportData](ue_ue.DataTable.md#assetimportdata)
- [ImportKeyField](ue_ue.DataTable.md#importkeyfield)
- [ImportPath](ue_ue.DataTable.md#importpath)
- [RowStruct](ue_ue.DataTable.md#rowstruct)
- [RowStructName](ue_ue.DataTable.md#rowstructname)
- [RowsSerializedWithTags](ue_ue.DataTable.md#rowsserializedwithtags)
- [TemporarilyReferencedObjects](ue_ue.DataTable.md#temporarilyreferencedobjects)
- [\_\_tid\_DataTable\_\_](ue_ue.DataTable.md#__tid_datatable__)
- [\_\_tid\_Object\_\_](ue_ue.DataTable.md#__tid_object__)
- [bIgnoreExtraFields](ue_ue.DataTable.md#bignoreextrafields)
- [bIgnoreMissingFields](ue_ue.DataTable.md#bignoremissingfields)
- [bStripFromClientBuilds](ue_ue.DataTable.md#bstripfromclientbuilds)

### Methods

- [CreateDefaultSubobject](ue_ue.DataTable.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DataTable.md#executeubergraph)
- [GetClass](ue_ue.DataTable.md#getclass)
- [GetName](ue_ue.DataTable.md#getname)
- [GetOuter](ue_ue.DataTable.md#getouter)
- [GetWorld](ue_ue.DataTable.md#getworld)
- [Find](ue_ue.DataTable.md#find)
- [Load](ue_ue.DataTable.md#load)
- [StaticClass](ue_ue.DataTable.md#staticclass)

## Constructors

### constructor

• **new DataTable**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:28415](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28415)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Defined in

[ue/ue.d.ts:28421](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28421)

___

### ImportKeyField

• **ImportKeyField**: `string`

#### Defined in

[ue/ue.d.ts:28420](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28420)

___

### ImportPath

• **ImportPath**: `string`

#### Defined in

[ue/ue.d.ts:28422](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28422)

___

### RowStruct

• **RowStruct**: [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:28416](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28416)

___

### RowStructName

• **RowStructName**: `string`

#### Defined in

[ue/ue.d.ts:28423](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28423)

___

### RowsSerializedWithTags

• **RowsSerializedWithTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:28424](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28424)

___

### TemporarilyReferencedObjects

• **TemporarilyReferencedObjects**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:28425](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28425)

___

### \_\_tid\_DataTable\_\_

• **\_\_tid\_DataTable\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:28430](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28430)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bIgnoreExtraFields

• **bIgnoreExtraFields**: `boolean`

#### Defined in

[ue/ue.d.ts:28418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28418)

___

### bIgnoreMissingFields

• **bIgnoreMissingFields**: `boolean`

#### Defined in

[ue/ue.d.ts:28419](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28419)

___

### bStripFromClientBuilds

• **bStripFromClientBuilds**: `boolean`

#### Defined in

[ue/ue.d.ts:28417](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28417)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DataTable`](ue_ue.DataTable.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DataTable`](ue_ue.DataTable.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:28427](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28427)

___

### Load

▸ `Static` **Load**(`InName`): [`DataTable`](ue_ue.DataTable.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DataTable`](ue_ue.DataTable.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:28428](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28428)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:28426](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28426)
