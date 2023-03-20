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

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

___

### ImportKeyField

• **ImportKeyField**: `string`

___

### ImportPath

• **ImportPath**: `string`

___

### RowStruct

• **RowStruct**: [`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### RowStructName

• **RowStructName**: `string`

___

### RowsSerializedWithTags

• **RowsSerializedWithTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### TemporarilyReferencedObjects

• **TemporarilyReferencedObjects**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`Object`](ue_ue.Object.md)\>

___

### \_\_tid\_DataTable\_\_

• **\_\_tid\_DataTable\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bIgnoreExtraFields

• **bIgnoreExtraFields**: `boolean`

___

### bIgnoreMissingFields

• **bIgnoreMissingFields**: `boolean`

___

### bStripFromClientBuilds

• **bStripFromClientBuilds**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
