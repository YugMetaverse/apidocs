[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CSVImportFactory

# Class: CSVImportFactory

[ue/ue](../modules/ue_ue.md).CSVImportFactory

## Hierarchy

- [`Factory`](ue_ue.Factory.md)

  ↳ **`CSVImportFactory`**

  ↳↳ [`ReimportCurveFactory`](ue_ue.ReimportCurveFactory.md)

  ↳↳ [`ReimportCurveTableFactory`](ue_ue.ReimportCurveTableFactory.md)

  ↳↳ [`ReimportDataTableFactory`](ue_ue.ReimportDataTableFactory.md)

## Table of contents

### Constructors

- [constructor](ue_ue.CSVImportFactory.md#constructor)

### Properties

- [AssetImportTask](ue_ue.CSVImportFactory.md#assetimporttask)
- [AutomatedImportData](ue_ue.CSVImportFactory.md#automatedimportdata)
- [AutomatedImportSettings](ue_ue.CSVImportFactory.md#automatedimportsettings)
- [ContextClass](ue_ue.CSVImportFactory.md#contextclass)
- [Formats](ue_ue.CSVImportFactory.md#formats)
- [ImportPriority](ue_ue.CSVImportFactory.md#importpriority)
- [OverwriteYesOrNoToAllState](ue_ue.CSVImportFactory.md#overwriteyesornotoallstate)
- [SupportedClass](ue_ue.CSVImportFactory.md#supportedclass)
- [TempImportDataTable](ue_ue.CSVImportFactory.md#tempimportdatatable)
- [\_\_tid\_CSVImportFactory\_\_](ue_ue.CSVImportFactory.md#__tid_csvimportfactory__)
- [\_\_tid\_Factory\_\_](ue_ue.CSVImportFactory.md#__tid_factory__)
- [\_\_tid\_Object\_\_](ue_ue.CSVImportFactory.md#__tid_object__)
- [bCreateNew](ue_ue.CSVImportFactory.md#bcreatenew)
- [bEditAfterNew](ue_ue.CSVImportFactory.md#beditafternew)
- [bEditorImport](ue_ue.CSVImportFactory.md#beditorimport)
- [bText](ue_ue.CSVImportFactory.md#btext)

### Methods

- [CreateDefaultSubobject](ue_ue.CSVImportFactory.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CSVImportFactory.md#executeubergraph)
- [GetClass](ue_ue.CSVImportFactory.md#getclass)
- [GetName](ue_ue.CSVImportFactory.md#getname)
- [GetOuter](ue_ue.CSVImportFactory.md#getouter)
- [GetWorld](ue_ue.CSVImportFactory.md#getworld)
- [ScriptFactoryCanImport](ue_ue.CSVImportFactory.md#scriptfactorycanimport)
- [ScriptFactoryCreateFile](ue_ue.CSVImportFactory.md#scriptfactorycreatefile)
- [Find](ue_ue.CSVImportFactory.md#find)
- [Load](ue_ue.CSVImportFactory.md#load)
- [StaticClass](ue_ue.CSVImportFactory.md#staticclass)

## Constructors

### constructor

• **new CSVImportFactory**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Factory](ue_ue.Factory.md).[constructor](ue_ue.Factory.md#constructor)

## Properties

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[AssetImportTask](ue_ue.Factory.md#assetimporttask)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[AutomatedImportData](ue_ue.Factory.md#automatedimportdata)

___

### AutomatedImportSettings

• **AutomatedImportSettings**: [`CSVImportSettings`](ue_ue.CSVImportSettings.md)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[ContextClass](ue_ue.Factory.md#contextclass)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Factory](ue_ue.Factory.md).[Formats](ue_ue.Factory.md#formats)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[Factory](ue_ue.Factory.md).[ImportPriority](ue_ue.Factory.md#importpriority)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[Factory](ue_ue.Factory.md).[OverwriteYesOrNoToAllState](ue_ue.Factory.md#overwriteyesornotoallstate)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[SupportedClass](ue_ue.Factory.md#supportedclass)

___

### TempImportDataTable

• **TempImportDataTable**: [`DataTable`](ue_ue.DataTable.md)

___

### \_\_tid\_CSVImportFactory\_\_

• **\_\_tid\_CSVImportFactory\_\_**: `boolean`

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[__tid_Factory__](ue_ue.Factory.md#__tid_factory__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[__tid_Object__](ue_ue.Factory.md#__tid_object__)

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[bCreateNew](ue_ue.Factory.md#bcreatenew)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[bEditAfterNew](ue_ue.Factory.md#beditafternew)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[bEditorImport](ue_ue.Factory.md#beditorimport)

___

### bText

• **bText**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[bText](ue_ue.Factory.md#btext)

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

[Factory](ue_ue.Factory.md).[CreateDefaultSubobject](ue_ue.Factory.md#createdefaultsubobject)

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

[Factory](ue_ue.Factory.md).[ExecuteUbergraph](ue_ue.Factory.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[GetClass](ue_ue.Factory.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Factory](ue_ue.Factory.md).[GetName](ue_ue.Factory.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[GetOuter](ue_ue.Factory.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Factory](ue_ue.Factory.md).[GetWorld](ue_ue.Factory.md#getworld)

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

[Factory](ue_ue.Factory.md).[ScriptFactoryCanImport](ue_ue.Factory.md#scriptfactorycanimport)

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

[Factory](ue_ue.Factory.md).[ScriptFactoryCreateFile](ue_ue.Factory.md#scriptfactorycreatefile)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CSVImportFactory`](ue_ue.CSVImportFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CSVImportFactory`](ue_ue.CSVImportFactory.md)

#### Overrides

[Factory](ue_ue.Factory.md).[Find](ue_ue.Factory.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`CSVImportFactory`](ue_ue.CSVImportFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CSVImportFactory`](ue_ue.CSVImportFactory.md)

#### Overrides

[Factory](ue_ue.Factory.md).[Load](ue_ue.Factory.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Factory](ue_ue.Factory.md).[StaticClass](ue_ue.Factory.md#staticclass)
