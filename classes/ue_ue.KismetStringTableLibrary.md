[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / KismetStringTableLibrary

# Class: KismetStringTableLibrary

[ue/ue](../modules/ue_ue.md).KismetStringTableLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`KismetStringTableLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.KismetStringTableLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.KismetStringTableLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_KismetStringTableLibrary\_\_](ue_ue.KismetStringTableLibrary.md#__tid_kismetstringtablelibrary__)
- [\_\_tid\_Object\_\_](ue_ue.KismetStringTableLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.KismetStringTableLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.KismetStringTableLibrary.md#executeubergraph)
- [GetClass](ue_ue.KismetStringTableLibrary.md#getclass)
- [GetName](ue_ue.KismetStringTableLibrary.md#getname)
- [GetOuter](ue_ue.KismetStringTableLibrary.md#getouter)
- [GetWorld](ue_ue.KismetStringTableLibrary.md#getworld)
- [Find](ue_ue.KismetStringTableLibrary.md#find)
- [GetKeysFromStringTable](ue_ue.KismetStringTableLibrary.md#getkeysfromstringtable)
- [GetMetaDataIdsFromStringTableEntry](ue_ue.KismetStringTableLibrary.md#getmetadataidsfromstringtableentry)
- [GetRegisteredStringTables](ue_ue.KismetStringTableLibrary.md#getregisteredstringtables)
- [GetTableEntryMetaData](ue_ue.KismetStringTableLibrary.md#gettableentrymetadata)
- [GetTableEntrySourceString](ue_ue.KismetStringTableLibrary.md#gettableentrysourcestring)
- [GetTableNamespace](ue_ue.KismetStringTableLibrary.md#gettablenamespace)
- [IsRegisteredTableEntry](ue_ue.KismetStringTableLibrary.md#isregisteredtableentry)
- [IsRegisteredTableId](ue_ue.KismetStringTableLibrary.md#isregisteredtableid)
- [Load](ue_ue.KismetStringTableLibrary.md#load)
- [StaticClass](ue_ue.KismetStringTableLibrary.md#staticclass)

## Constructors

### constructor

• **new KismetStringTableLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_KismetStringTableLibrary\_\_

• **\_\_tid\_KismetStringTableLibrary\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`KismetStringTableLibrary`](ue_ue.KismetStringTableLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`KismetStringTableLibrary`](ue_ue.KismetStringTableLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetKeysFromStringTable

▸ `Static` **GetKeysFromStringTable**(`TableId`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `TableId` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### GetMetaDataIdsFromStringTableEntry

▸ `Static` **GetMetaDataIdsFromStringTableEntry**(`TableId`, `Key`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `TableId` | `string` |
| `Key` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### GetRegisteredStringTables

▸ `Static` **GetRegisteredStringTables**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### GetTableEntryMetaData

▸ `Static` **GetTableEntryMetaData**(`TableId`, `Key`, `MetaDataId`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TableId` | `string` |
| `Key` | `string` |
| `MetaDataId` | `string` |

#### Returns

`string`

___

### GetTableEntrySourceString

▸ `Static` **GetTableEntrySourceString**(`TableId`, `Key`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TableId` | `string` |
| `Key` | `string` |

#### Returns

`string`

___

### GetTableNamespace

▸ `Static` **GetTableNamespace**(`TableId`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TableId` | `string` |

#### Returns

`string`

___

### IsRegisteredTableEntry

▸ `Static` **IsRegisteredTableEntry**(`TableId`, `Key`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TableId` | `string` |
| `Key` | `string` |

#### Returns

`boolean`

___

### IsRegisteredTableId

▸ `Static` **IsRegisteredTableId**(`TableId`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TableId` | `string` |

#### Returns

`boolean`

___

### Load

▸ `Static` **Load**(`InName`): [`KismetStringTableLibrary`](ue_ue.KismetStringTableLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`KismetStringTableLibrary`](ue_ue.KismetStringTableLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
