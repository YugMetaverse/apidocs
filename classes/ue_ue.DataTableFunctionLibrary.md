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

#### Defined in

[ue/ue.d.ts:30195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30195)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_DataTableFunctionLibrary\_\_

• **\_\_tid\_DataTableFunctionLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:30210](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30210)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:30196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30196)

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

#### Defined in

[ue/ue.d.ts:30197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30197)

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

#### Defined in

[ue/ue.d.ts:30198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30198)

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

#### Defined in

[ue/ue.d.ts:30199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30199)

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

#### Defined in

[ue/ue.d.ts:30200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30200)

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

#### Defined in

[ue/ue.d.ts:30201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30201)

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

#### Defined in

[ue/ue.d.ts:30207](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30207)

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

#### Defined in

[ue/ue.d.ts:30202](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30202)

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

#### Defined in

[ue/ue.d.ts:30203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30203)

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

#### Defined in

[ue/ue.d.ts:30204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30204)

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

#### Defined in

[ue/ue.d.ts:30205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30205)

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

#### Defined in

[ue/ue.d.ts:30208](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30208)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:30206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30206)
