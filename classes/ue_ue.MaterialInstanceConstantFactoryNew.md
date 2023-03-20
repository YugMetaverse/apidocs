[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialInstanceConstantFactoryNew

# Class: MaterialInstanceConstantFactoryNew

[ue/ue](../modules/ue_ue.md).MaterialInstanceConstantFactoryNew

## Hierarchy

- [`Factory`](ue_ue.Factory.md)

  ↳ **`MaterialInstanceConstantFactoryNew`**

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialInstanceConstantFactoryNew.md#constructor)

### Properties

- [AssetImportTask](ue_ue.MaterialInstanceConstantFactoryNew.md#assetimporttask)
- [AutomatedImportData](ue_ue.MaterialInstanceConstantFactoryNew.md#automatedimportdata)
- [ContextClass](ue_ue.MaterialInstanceConstantFactoryNew.md#contextclass)
- [Formats](ue_ue.MaterialInstanceConstantFactoryNew.md#formats)
- [ImportPriority](ue_ue.MaterialInstanceConstantFactoryNew.md#importpriority)
- [InitialParent](ue_ue.MaterialInstanceConstantFactoryNew.md#initialparent)
- [OverwriteYesOrNoToAllState](ue_ue.MaterialInstanceConstantFactoryNew.md#overwriteyesornotoallstate)
- [SupportedClass](ue_ue.MaterialInstanceConstantFactoryNew.md#supportedclass)
- [\_\_tid\_Factory\_\_](ue_ue.MaterialInstanceConstantFactoryNew.md#__tid_factory__)
- [\_\_tid\_MaterialInstanceConstantFactoryNew\_\_](ue_ue.MaterialInstanceConstantFactoryNew.md#__tid_materialinstanceconstantfactorynew__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialInstanceConstantFactoryNew.md#__tid_object__)
- [bCreateNew](ue_ue.MaterialInstanceConstantFactoryNew.md#bcreatenew)
- [bEditAfterNew](ue_ue.MaterialInstanceConstantFactoryNew.md#beditafternew)
- [bEditorImport](ue_ue.MaterialInstanceConstantFactoryNew.md#beditorimport)
- [bText](ue_ue.MaterialInstanceConstantFactoryNew.md#btext)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialInstanceConstantFactoryNew.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialInstanceConstantFactoryNew.md#executeubergraph)
- [GetClass](ue_ue.MaterialInstanceConstantFactoryNew.md#getclass)
- [GetName](ue_ue.MaterialInstanceConstantFactoryNew.md#getname)
- [GetOuter](ue_ue.MaterialInstanceConstantFactoryNew.md#getouter)
- [GetWorld](ue_ue.MaterialInstanceConstantFactoryNew.md#getworld)
- [ScriptFactoryCanImport](ue_ue.MaterialInstanceConstantFactoryNew.md#scriptfactorycanimport)
- [ScriptFactoryCreateFile](ue_ue.MaterialInstanceConstantFactoryNew.md#scriptfactorycreatefile)
- [Find](ue_ue.MaterialInstanceConstantFactoryNew.md#find)
- [Load](ue_ue.MaterialInstanceConstantFactoryNew.md#load)
- [StaticClass](ue_ue.MaterialInstanceConstantFactoryNew.md#staticclass)

## Constructors

### constructor

• **new MaterialInstanceConstantFactoryNew**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### InitialParent

• **InitialParent**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

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

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[Factory](ue_ue.Factory.md).[__tid_Factory__](ue_ue.Factory.md#__tid_factory__)

___

### \_\_tid\_MaterialInstanceConstantFactoryNew\_\_

• **\_\_tid\_MaterialInstanceConstantFactoryNew\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialInstanceConstantFactoryNew`](ue_ue.MaterialInstanceConstantFactoryNew.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialInstanceConstantFactoryNew`](ue_ue.MaterialInstanceConstantFactoryNew.md)

#### Overrides

[Factory](ue_ue.Factory.md).[Find](ue_ue.Factory.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialInstanceConstantFactoryNew`](ue_ue.MaterialInstanceConstantFactoryNew.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialInstanceConstantFactoryNew`](ue_ue.MaterialInstanceConstantFactoryNew.md)

#### Overrides

[Factory](ue_ue.Factory.md).[Load](ue_ue.Factory.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Factory](ue_ue.Factory.md).[StaticClass](ue_ue.Factory.md#staticclass)
