[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DataTableFunctionLibrary

# Class: DataTableFunctionLibrary

[ue/ue](../modules/ue_ue.md).DataTableFunctionLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`DataTableFunctionLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.DataTableFunctionLibrary.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.DataTableFunctionLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_DataTableFunctionLibrary\_\_](ue_ue.DataTableFunctionLibrary.md#__tid_datatablefunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.DataTableFunctionLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.DataTableFunctionLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DataTableFunctionLibrary.md#executeubergraph)
- [GetClass](ue_ue.DataTableFunctionLibrary.md#getclass)
- [GetName](ue_ue.DataTableFunctionLibrary.md#getname)
- [GetOuter](ue_ue.DataTableFunctionLibrary.md#getouter)
- [GetWorld](ue_ue.DataTableFunctionLibrary.md#getworld)
- [DoesDataTableRowExist](ue_ue.DataTableFunctionLibrary.md#doesdatatablerowexist)
- [EvaluateCurveTableRow](ue_ue.DataTableFunctionLibrary.md#evaluatecurvetablerow)
- [FillDataTableFromCSVFile](ue_ue.DataTableFunctionLibrary.md#filldatatablefromcsvfile)
- [FillDataTableFromCSVString](ue_ue.DataTableFunctionLibrary.md#filldatatablefromcsvstring)
- [FillDataTableFromJSONFile](ue_ue.DataTableFunctionLibrary.md#filldatatablefromjsonfile)
- [FillDataTableFromJSONString](ue_ue.DataTableFunctionLibrary.md#filldatatablefromjsonstring)
- [Find](ue_ue.DataTableFunctionLibrary.md#find)
- [Generic\_GetDataTableRowFromName](ue_ue.DataTableFunctionLibrary.md#generic_getdatatablerowfromname)
- [GetDataTableColumnAsString](ue_ue.DataTableFunctionLibrary.md#getdatatablecolumnasstring)
- [GetDataTableRowFromName](ue_ue.DataTableFunctionLibrary.md#getdatatablerowfromname)
- [GetDataTableRowNames](ue_ue.DataTableFunctionLibrary.md#getdatatablerownames)
- [Load](ue_ue.DataTableFunctionLibrary.md#load)
- [StaticClass](ue_ue.DataTableFunctionLibrary.md#staticclass)

## Constructors

### constructor

• **new DataTableFunctionLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### \_\_tid\_DataTableFunctionLibrary\_\_

• **\_\_tid\_DataTableFunctionLibrary\_\_**: `boolean`

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

### DoesDataTableRowExist

▸ `Static` **DoesDataTableRowExist**(`Table`, `RowName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Table` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DataTable`](ue_ue.DataTable.md)\> |
| `RowName` | `string` |

#### Returns

`boolean`

___

### EvaluateCurveTableRow

▸ `Static` **EvaluateCurveTableRow**(`CurveTable`, `RowName`, `InXY`, `OutResult`, `OutXY`, `ContextString`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `CurveTable` | [`$Nullable`](../modules/puerts.md#$nullable)<[`CurveTable`](ue_ue.CurveTable.md)\> |
| `RowName` | `string` |
| `InXY` | `number` |
| `OutResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`EEvaluateCurveTableResult`](../enums/ue_ue.EEvaluateCurveTableResult.md)\> |
| `OutXY` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `ContextString` | `string` |

#### Returns

`void`

___

### FillDataTableFromCSVFile

▸ `Static` **FillDataTableFromCSVFile**(`DataTable`, `CSVFilePath`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DataTable` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DataTable`](ue_ue.DataTable.md)\> |
| `CSVFilePath` | `string` |

#### Returns

`boolean`

___

### FillDataTableFromCSVString

▸ `Static` **FillDataTableFromCSVString**(`DataTable`, `CSVString`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DataTable` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DataTable`](ue_ue.DataTable.md)\> |
| `CSVString` | `string` |

#### Returns

`boolean`

___

### FillDataTableFromJSONFile

▸ `Static` **FillDataTableFromJSONFile**(`DataTable`, `JSONFilePath`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DataTable` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DataTable`](ue_ue.DataTable.md)\> |
| `JSONFilePath` | `string` |

#### Returns

`boolean`

___

### FillDataTableFromJSONString

▸ `Static` **FillDataTableFromJSONString**(`DataTable`, `JSONString`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DataTable` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DataTable`](ue_ue.DataTable.md)\> |
| `JSONString` | `string` |

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DataTableFunctionLibrary`](ue_ue.DataTableFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DataTableFunctionLibrary`](ue_ue.DataTableFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### Generic\_GetDataTableRowFromName

▸ `Static` **Generic_GetDataTableRowFromName**(`p0`, `p1`, `p2`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`DataTable`](ue_ue.DataTable.md) |
| `p1` | `string` |
| `p2` | `any` |

#### Returns

`boolean`

___

### GetDataTableColumnAsString

▸ `Static` **GetDataTableColumnAsString**(`DataTable`, `PropertyName`): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `DataTable` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DataTable`](ue_ue.DataTable.md)\> |
| `PropertyName` | `string` |

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### GetDataTableRowFromName

▸ `Static` **GetDataTableRowFromName**(`Table`, `RowName`, `OutRow`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Table` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DataTable`](ue_ue.DataTable.md)\> |
| `RowName` | `string` |
| `OutRow` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TableRowBase`](ue_ue.TableRowBase.md)\> |

#### Returns

`boolean`

___

### GetDataTableRowNames

▸ `Static` **GetDataTableRowNames**(`Table`, `OutRowNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Table` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DataTable`](ue_ue.DataTable.md)\> |
| `OutRowNames` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

___

### Load

▸ `Static` **Load**(`InName`): [`DataTableFunctionLibrary`](ue_ue.DataTableFunctionLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DataTableFunctionLibrary`](ue_ue.DataTableFunctionLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
