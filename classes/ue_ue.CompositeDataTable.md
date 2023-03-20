[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CompositeDataTable

# Class: CompositeDataTable

[ue/ue](../modules/ue_ue.md).CompositeDataTable

## Hierarchy

- [`DataTable`](ue_ue.DataTable.md)

  ↳ **`CompositeDataTable`**

## Table of contents

### Constructors

- [constructor](ue_ue.CompositeDataTable.md#constructor)

### Properties

- [AssetImportData](ue_ue.CompositeDataTable.md#assetimportdata)
- [ImportKeyField](ue_ue.CompositeDataTable.md#importkeyfield)
- [ImportPath](ue_ue.CompositeDataTable.md#importpath)
- [OldParentTables](ue_ue.CompositeDataTable.md#oldparenttables)
- [ParentTables](ue_ue.CompositeDataTable.md#parenttables)
- [RowStruct](ue_ue.CompositeDataTable.md#rowstruct)
- [RowStructName](ue_ue.CompositeDataTable.md#rowstructname)
- [RowsSerializedWithTags](ue_ue.CompositeDataTable.md#rowsserializedwithtags)
- [TemporarilyReferencedObjects](ue_ue.CompositeDataTable.md#temporarilyreferencedobjects)
- [\_\_tid\_CompositeDataTable\_\_](ue_ue.CompositeDataTable.md#__tid_compositedatatable__)
- [\_\_tid\_DataTable\_\_](ue_ue.CompositeDataTable.md#__tid_datatable__)
- [\_\_tid\_Object\_\_](ue_ue.CompositeDataTable.md#__tid_object__)
- [bIgnoreExtraFields](ue_ue.CompositeDataTable.md#bignoreextrafields)
- [bIgnoreMissingFields](ue_ue.CompositeDataTable.md#bignoremissingfields)
- [bStripFromClientBuilds](ue_ue.CompositeDataTable.md#bstripfromclientbuilds)

### Methods

- [CreateDefaultSubobject](ue_ue.CompositeDataTable.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CompositeDataTable.md#executeubergraph)
- [GetClass](ue_ue.CompositeDataTable.md#getclass)
- [GetName](ue_ue.CompositeDataTable.md#getname)
- [GetOuter](ue_ue.CompositeDataTable.md#getouter)
- [GetWorld](ue_ue.CompositeDataTable.md#getworld)
- [Find](ue_ue.CompositeDataTable.md#find)
- [Load](ue_ue.CompositeDataTable.md#load)
- [StaticClass](ue_ue.CompositeDataTable.md#staticclass)

## Constructors

### constructor

• **new CompositeDataTable**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DataTable](ue_ue.DataTable.md).[constructor](ue_ue.DataTable.md#constructor)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Inherited from

[DataTable](ue_ue.DataTable.md).[AssetImportData](ue_ue.DataTable.md#assetimportdata)

___

### ImportKeyField

• **ImportKeyField**: `string`

#### Inherited from

[DataTable](ue_ue.DataTable.md).[ImportKeyField](ue_ue.DataTable.md#importkeyfield)

___

### ImportPath

• **ImportPath**: `string`

#### Inherited from

[DataTable](ue_ue.DataTable.md).[ImportPath](ue_ue.DataTable.md#importpath)

___

### OldParentTables

• **OldParentTables**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DataTable`](ue_ue.DataTable.md)\>

___

### ParentTables

• **ParentTables**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DataTable`](ue_ue.DataTable.md)\>

___

### RowStruct

• **RowStruct**: [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Inherited from

[DataTable](ue_ue.DataTable.md).[RowStruct](ue_ue.DataTable.md#rowstruct)

___

### RowStructName

• **RowStructName**: `string`

#### Inherited from

[DataTable](ue_ue.DataTable.md).[RowStructName](ue_ue.DataTable.md#rowstructname)

___

### RowsSerializedWithTags

• **RowsSerializedWithTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Inherited from

[DataTable](ue_ue.DataTable.md).[RowsSerializedWithTags](ue_ue.DataTable.md#rowsserializedwithtags)

___

### TemporarilyReferencedObjects

• **TemporarilyReferencedObjects**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[DataTable](ue_ue.DataTable.md).[TemporarilyReferencedObjects](ue_ue.DataTable.md#temporarilyreferencedobjects)

___

### \_\_tid\_CompositeDataTable\_\_

• **\_\_tid\_CompositeDataTable\_\_**: `boolean`

___

### \_\_tid\_DataTable\_\_

• **\_\_tid\_DataTable\_\_**: `boolean`

#### Inherited from

[DataTable](ue_ue.DataTable.md).[__tid_DataTable__](ue_ue.DataTable.md#__tid_datatable__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DataTable](ue_ue.DataTable.md).[__tid_Object__](ue_ue.DataTable.md#__tid_object__)

___

### bIgnoreExtraFields

• **bIgnoreExtraFields**: `boolean`

#### Inherited from

[DataTable](ue_ue.DataTable.md).[bIgnoreExtraFields](ue_ue.DataTable.md#bignoreextrafields)

___

### bIgnoreMissingFields

• **bIgnoreMissingFields**: `boolean`

#### Inherited from

[DataTable](ue_ue.DataTable.md).[bIgnoreMissingFields](ue_ue.DataTable.md#bignoremissingfields)

___

### bStripFromClientBuilds

• **bStripFromClientBuilds**: `boolean`

#### Inherited from

[DataTable](ue_ue.DataTable.md).[bStripFromClientBuilds](ue_ue.DataTable.md#bstripfromclientbuilds)

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

[DataTable](ue_ue.DataTable.md).[CreateDefaultSubobject](ue_ue.DataTable.md#createdefaultsubobject)

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

[DataTable](ue_ue.DataTable.md).[ExecuteUbergraph](ue_ue.DataTable.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DataTable](ue_ue.DataTable.md).[GetClass](ue_ue.DataTable.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DataTable](ue_ue.DataTable.md).[GetName](ue_ue.DataTable.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DataTable](ue_ue.DataTable.md).[GetOuter](ue_ue.DataTable.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DataTable](ue_ue.DataTable.md).[GetWorld](ue_ue.DataTable.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CompositeDataTable`](ue_ue.CompositeDataTable.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CompositeDataTable`](ue_ue.CompositeDataTable.md)

#### Overrides

[DataTable](ue_ue.DataTable.md).[Find](ue_ue.DataTable.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`CompositeDataTable`](ue_ue.CompositeDataTable.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CompositeDataTable`](ue_ue.CompositeDataTable.md)

#### Overrides

[DataTable](ue_ue.DataTable.md).[Load](ue_ue.DataTable.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DataTable](ue_ue.DataTable.md).[StaticClass](ue_ue.DataTable.md#staticclass)
