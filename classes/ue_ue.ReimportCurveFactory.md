[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ReimportCurveFactory

# Class: ReimportCurveFactory

[ue/ue](../modules/ue_ue.md).ReimportCurveFactory

## Hierarchy

- [`CSVImportFactory`](ue_ue.CSVImportFactory.md)

  ↳ **`ReimportCurveFactory`**

## Table of contents

### Constructors

- [constructor](ue_ue.ReimportCurveFactory.md#constructor)

### Properties

- [AssetImportTask](ue_ue.ReimportCurveFactory.md#assetimporttask)
- [AutomatedImportData](ue_ue.ReimportCurveFactory.md#automatedimportdata)
- [AutomatedImportSettings](ue_ue.ReimportCurveFactory.md#automatedimportsettings)
- [ContextClass](ue_ue.ReimportCurveFactory.md#contextclass)
- [Formats](ue_ue.ReimportCurveFactory.md#formats)
- [ImportPriority](ue_ue.ReimportCurveFactory.md#importpriority)
- [OverwriteYesOrNoToAllState](ue_ue.ReimportCurveFactory.md#overwriteyesornotoallstate)
- [SupportedClass](ue_ue.ReimportCurveFactory.md#supportedclass)
- [TempImportDataTable](ue_ue.ReimportCurveFactory.md#tempimportdatatable)
- [\_\_tid\_CSVImportFactory\_\_](ue_ue.ReimportCurveFactory.md#__tid_csvimportfactory__)
- [\_\_tid\_Factory\_\_](ue_ue.ReimportCurveFactory.md#__tid_factory__)
- [\_\_tid\_Object\_\_](ue_ue.ReimportCurveFactory.md#__tid_object__)
- [\_\_tid\_ReimportCurveFactory\_\_](ue_ue.ReimportCurveFactory.md#__tid_reimportcurvefactory__)
- [bCreateNew](ue_ue.ReimportCurveFactory.md#bcreatenew)
- [bEditAfterNew](ue_ue.ReimportCurveFactory.md#beditafternew)
- [bEditorImport](ue_ue.ReimportCurveFactory.md#beditorimport)
- [bText](ue_ue.ReimportCurveFactory.md#btext)

### Methods

- [CreateDefaultSubobject](ue_ue.ReimportCurveFactory.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ReimportCurveFactory.md#executeubergraph)
- [GetClass](ue_ue.ReimportCurveFactory.md#getclass)
- [GetName](ue_ue.ReimportCurveFactory.md#getname)
- [GetOuter](ue_ue.ReimportCurveFactory.md#getouter)
- [GetWorld](ue_ue.ReimportCurveFactory.md#getworld)
- [ScriptFactoryCanImport](ue_ue.ReimportCurveFactory.md#scriptfactorycanimport)
- [ScriptFactoryCreateFile](ue_ue.ReimportCurveFactory.md#scriptfactorycreatefile)
- [Find](ue_ue.ReimportCurveFactory.md#find)
- [Load](ue_ue.ReimportCurveFactory.md#load)
- [StaticClass](ue_ue.ReimportCurveFactory.md#staticclass)

## Constructors

### constructor

• **new ReimportCurveFactory**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[CSVImportFactory](ue_ue.CSVImportFactory.md).[constructor](ue_ue.CSVImportFactory.md#constructor)

#### Defined in

[ue/ue.d.ts:59250](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59250)

## Properties

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[AssetImportTask](ue_ue.CSVImportFactory.md#assetimporttask)

#### Defined in

[ue/ue.d.ts:15338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15338)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[AutomatedImportData](ue_ue.CSVImportFactory.md#automatedimportdata)

#### Defined in

[ue/ue.d.ts:15337](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15337)

___

### AutomatedImportSettings

• **AutomatedImportSettings**: [`CSVImportSettings`](ue_ue.CSVImportSettings.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[AutomatedImportSettings](ue_ue.CSVImportFactory.md#automatedimportsettings)

#### Defined in

[ue/ue.d.ts:28985](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28985)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[ContextClass](ue_ue.CSVImportFactory.md#contextclass)

#### Defined in

[ue/ue.d.ts:15331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15331)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[Formats](ue_ue.CSVImportFactory.md#formats)

#### Defined in

[ue/ue.d.ts:15332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15332)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[ImportPriority](ue_ue.CSVImportFactory.md#importpriority)

#### Defined in

[ue/ue.d.ts:15336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15336)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[OverwriteYesOrNoToAllState](ue_ue.CSVImportFactory.md#overwriteyesornotoallstate)

#### Defined in

[ue/ue.d.ts:15339](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15339)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[SupportedClass](ue_ue.CSVImportFactory.md#supportedclass)

#### Defined in

[ue/ue.d.ts:15330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15330)

___

### TempImportDataTable

• **TempImportDataTable**: [`DataTable`](ue_ue.DataTable.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[TempImportDataTable](ue_ue.CSVImportFactory.md#tempimportdatatable)

#### Defined in

[ue/ue.d.ts:28986](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28986)

___

### \_\_tid\_CSVImportFactory\_\_

• **\_\_tid\_CSVImportFactory\_\_**: `boolean`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[__tid_CSVImportFactory__](ue_ue.CSVImportFactory.md#__tid_csvimportfactory__)

#### Defined in

[ue/ue.d.ts:28991](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28991)

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[__tid_Factory__](ue_ue.CSVImportFactory.md#__tid_factory__)

#### Defined in

[ue/ue.d.ts:15346](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15346)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[__tid_Object__](ue_ue.CSVImportFactory.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ReimportCurveFactory\_\_

• **\_\_tid\_ReimportCurveFactory\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:59255](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59255)

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[bCreateNew](ue_ue.CSVImportFactory.md#bcreatenew)

#### Defined in

[ue/ue.d.ts:15329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15329)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[bEditAfterNew](ue_ue.CSVImportFactory.md#beditafternew)

#### Defined in

[ue/ue.d.ts:15333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15333)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[bEditorImport](ue_ue.CSVImportFactory.md#beditorimport)

#### Defined in

[ue/ue.d.ts:15334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15334)

___

### bText

• **bText**: `boolean`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[bText](ue_ue.CSVImportFactory.md#btext)

#### Defined in

[ue/ue.d.ts:15335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15335)

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

[CSVImportFactory](ue_ue.CSVImportFactory.md).[ExecuteUbergraph](ue_ue.CSVImportFactory.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[GetClass](ue_ue.CSVImportFactory.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[GetName](ue_ue.CSVImportFactory.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[GetOuter](ue_ue.CSVImportFactory.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[CSVImportFactory](ue_ue.CSVImportFactory.md).[GetWorld](ue_ue.CSVImportFactory.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:15340](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15340)

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

#### Defined in

[ue/ue.d.ts:15341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15341)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ReimportCurveFactory`](ue_ue.ReimportCurveFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ReimportCurveFactory`](ue_ue.ReimportCurveFactory.md)

#### Overrides

[CSVImportFactory](ue_ue.CSVImportFactory.md).[Find](ue_ue.CSVImportFactory.md#find)

#### Defined in

[ue/ue.d.ts:59252](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59252)

___

### Load

▸ `Static` **Load**(`InName`): [`ReimportCurveFactory`](ue_ue.ReimportCurveFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ReimportCurveFactory`](ue_ue.ReimportCurveFactory.md)

#### Overrides

[CSVImportFactory](ue_ue.CSVImportFactory.md).[Load](ue_ue.CSVImportFactory.md#load)

#### Defined in

[ue/ue.d.ts:59253](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59253)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[CSVImportFactory](ue_ue.CSVImportFactory.md).[StaticClass](ue_ue.CSVImportFactory.md#staticclass)

#### Defined in

[ue/ue.d.ts:59251](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L59251)