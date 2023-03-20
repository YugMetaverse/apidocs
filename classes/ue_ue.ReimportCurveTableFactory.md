[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ReimportCurveTableFactory

# Class: ReimportCurveTableFactory

[ue/ue](../modules/ue_ue.md).ReimportCurveTableFactory

## Hierarchy

- [`CSVImportFactory`](ue_ue.CSVImportFactory.md)

  ↳ **`ReimportCurveTableFactory`**

## Table of contents

### Constructors

- [constructor](ue_ue.ReimportCurveTableFactory.md#constructor)

### Properties

- [AssetImportTask](ue_ue.ReimportCurveTableFactory.md#assetimporttask)
- [AutomatedImportData](ue_ue.ReimportCurveTableFactory.md#automatedimportdata)
- [AutomatedImportSettings](ue_ue.ReimportCurveTableFactory.md#automatedimportsettings)
- [ContextClass](ue_ue.ReimportCurveTableFactory.md#contextclass)
- [Formats](ue_ue.ReimportCurveTableFactory.md#formats)
- [ImportPriority](ue_ue.ReimportCurveTableFactory.md#importpriority)
- [OverwriteYesOrNoToAllState](ue_ue.ReimportCurveTableFactory.md#overwriteyesornotoallstate)
- [SupportedClass](ue_ue.ReimportCurveTableFactory.md#supportedclass)
- [TempImportDataTable](ue_ue.ReimportCurveTableFactory.md#tempimportdatatable)
- [\_\_tid\_CSVImportFactory\_\_](ue_ue.ReimportCurveTableFactory.md#__tid_csvimportfactory__)
- [\_\_tid\_Factory\_\_](ue_ue.ReimportCurveTableFactory.md#__tid_factory__)
- [\_\_tid\_Object\_\_](ue_ue.ReimportCurveTableFactory.md#__tid_object__)
- [\_\_tid\_ReimportCurveTableFactory\_\_](ue_ue.ReimportCurveTableFactory.md#__tid_reimportcurvetablefactory__)
- [bCreateNew](ue_ue.ReimportCurveTableFactory.md#bcreatenew)
- [bEditAfterNew](ue_ue.ReimportCurveTableFactory.md#beditafternew)
- [bEditorImport](ue_ue.ReimportCurveTableFactory.md#beditorimport)
- [bText](ue_ue.ReimportCurveTableFactory.md#btext)

### Methods

- [CreateDefaultSubobject](ue_ue.ReimportCurveTableFactory.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ReimportCurveTableFactory.md#executeubergraph)
- [GetClass](ue_ue.ReimportCurveTableFactory.md#getclass)
- [GetName](ue_ue.ReimportCurveTableFactory.md#getname)
- [GetOuter](ue_ue.ReimportCurveTableFactory.md#getouter)
- [GetWorld](ue_ue.ReimportCurveTableFactory.md#getworld)
- [ScriptFactoryCanImport](ue_ue.ReimportCurveTableFactory.md#scriptfactorycanimport)
- [ScriptFactoryCreateFile](ue_ue.ReimportCurveTableFactory.md#scriptfactorycreatefile)
- [Find](ue_ue.ReimportCurveTableFactory.md#find)
- [Load](ue_ue.ReimportCurveTableFactory.md#load)
- [StaticClass](ue_ue.ReimportCurveTableFactory.md#staticclass)

## Constructors

### constructor

• **new ReimportCurveTableFactory**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[CSVImportFactory](ue_ue.CSVImportFactory.md).[constructor](ue_ue.CSVImportFactory.md#constructor)

## Properties

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[AssetImportTask](ue_ue.CSVImportFactory.md#assetimporttask)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[AutomatedImportData](ue_ue.CSVImportFactory.md#automatedimportdata)

___

### AutomatedImportSettings

• **AutomatedImportSettings**: [`CSVImportSettings`](ue_ue.CSVImportSettings.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[AutomatedImportSettings](ue_ue.CSVImportFactory.md#automatedimportsettings)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[ContextClass](ue_ue.CSVImportFactory.md#contextclass)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[Formats](ue_ue.CSVImportFactory.md#formats)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[ImportPriority](ue_ue.CSVImportFactory.md#importpriority)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[OverwriteYesOrNoToAllState](ue_ue.CSVImportFactory.md#overwriteyesornotoallstate)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[SupportedClass](ue_ue.CSVImportFactory.md#supportedclass)

___

### TempImportDataTable

• **TempImportDataTable**: [`DataTable`](ue_ue.DataTable.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[TempImportDataTable](ue_ue.CSVImportFactory.md#tempimportdatatable)

___

### \_\_tid\_CSVImportFactory\_\_

• **\_\_tid\_CSVImportFactory\_\_**: `boolean`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[__tid_CSVImportFactory__](ue_ue.CSVImportFactory.md#__tid_csvimportfactory__)

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[__tid_Factory__](ue_ue.CSVImportFactory.md#__tid_factory__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[__tid_Object__](ue_ue.CSVImportFactory.md#__tid_object__)

___

### \_\_tid\_ReimportCurveTableFactory\_\_

• **\_\_tid\_ReimportCurveTableFactory\_\_**: `boolean`

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[bCreateNew](ue_ue.CSVImportFactory.md#bcreatenew)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[bEditAfterNew](ue_ue.CSVImportFactory.md#beditafternew)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[bEditorImport](ue_ue.CSVImportFactory.md#beditorimport)

___

### bText

• **bText**: `boolean`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[bText](ue_ue.CSVImportFactory.md#btext)

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

[CSVImportFactory](ue_ue.CSVImportFactory.md).[CreateDefaultSubobject](ue_ue.CSVImportFactory.md#createdefaultsubobject)

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

[CSVImportFactory](ue_ue.CSVImportFactory.md).[ExecuteUbergraph](ue_ue.CSVImportFactory.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[GetClass](ue_ue.CSVImportFactory.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[GetName](ue_ue.CSVImportFactory.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[GetOuter](ue_ue.CSVImportFactory.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[GetWorld](ue_ue.CSVImportFactory.md#getworld)

___

### ScriptFactoryCanImport

▸ **ScriptFactoryCanImport**(`Filename`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Filename` | `string` |

#### Returns

`boolean`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[ScriptFactoryCanImport](ue_ue.CSVImportFactory.md#scriptfactorycanimport)

___

### ScriptFactoryCreateFile

▸ **ScriptFactoryCreateFile**(`InTask`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTask` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AssetImportTask`](ue_ue.AssetImportTask.md)\> |

#### Returns

`boolean`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[ScriptFactoryCreateFile](ue_ue.CSVImportFactory.md#scriptfactorycreatefile)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ReimportCurveTableFactory`](ue_ue.ReimportCurveTableFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ReimportCurveTableFactory`](ue_ue.ReimportCurveTableFactory.md)

#### Overrides

[CSVImportFactory](ue_ue.CSVImportFactory.md).[Find](ue_ue.CSVImportFactory.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ReimportCurveTableFactory`](ue_ue.ReimportCurveTableFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ReimportCurveTableFactory`](ue_ue.ReimportCurveTableFactory.md)

#### Overrides

[CSVImportFactory](ue_ue.CSVImportFactory.md).[Load](ue_ue.CSVImportFactory.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[CSVImportFactory](ue_ue.CSVImportFactory.md).[StaticClass](ue_ue.CSVImportFactory.md#staticclass)
