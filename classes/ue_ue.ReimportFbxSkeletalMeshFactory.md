[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ReimportFbxSkeletalMeshFactory

# Class: ReimportFbxSkeletalMeshFactory

[ue/ue](../modules/ue_ue.md).ReimportFbxSkeletalMeshFactory

## Hierarchy

- [`FbxFactory`](ue_ue.FbxFactory.md)

  ↳ **`ReimportFbxSkeletalMeshFactory`**

## Table of contents

### Constructors

- [constructor](ue_ue.ReimportFbxSkeletalMeshFactory.md#constructor)

### Properties

- [AssetImportTask](ue_ue.ReimportFbxSkeletalMeshFactory.md#assetimporttask)
- [AutomatedImportData](ue_ue.ReimportFbxSkeletalMeshFactory.md#automatedimportdata)
- [ContextClass](ue_ue.ReimportFbxSkeletalMeshFactory.md#contextclass)
- [Formats](ue_ue.ReimportFbxSkeletalMeshFactory.md#formats)
- [ImportPriority](ue_ue.ReimportFbxSkeletalMeshFactory.md#importpriority)
- [ImportUI](ue_ue.ReimportFbxSkeletalMeshFactory.md#importui)
- [OriginalImportUI](ue_ue.ReimportFbxSkeletalMeshFactory.md#originalimportui)
- [OverwriteYesOrNoToAllState](ue_ue.ReimportFbxSkeletalMeshFactory.md#overwriteyesornotoallstate)
- [SupportedClass](ue_ue.ReimportFbxSkeletalMeshFactory.md#supportedclass)
- [\_\_tid\_Factory\_\_](ue_ue.ReimportFbxSkeletalMeshFactory.md#__tid_factory__)
- [\_\_tid\_FbxFactory\_\_](ue_ue.ReimportFbxSkeletalMeshFactory.md#__tid_fbxfactory__)
- [\_\_tid\_Object\_\_](ue_ue.ReimportFbxSkeletalMeshFactory.md#__tid_object__)
- [\_\_tid\_ReimportFbxSkeletalMeshFactory\_\_](ue_ue.ReimportFbxSkeletalMeshFactory.md#__tid_reimportfbxskeletalmeshfactory__)
- [bCreateNew](ue_ue.ReimportFbxSkeletalMeshFactory.md#bcreatenew)
- [bEditAfterNew](ue_ue.ReimportFbxSkeletalMeshFactory.md#beditafternew)
- [bEditorImport](ue_ue.ReimportFbxSkeletalMeshFactory.md#beditorimport)
- [bText](ue_ue.ReimportFbxSkeletalMeshFactory.md#btext)

### Methods

- [CreateDefaultSubobject](ue_ue.ReimportFbxSkeletalMeshFactory.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ReimportFbxSkeletalMeshFactory.md#executeubergraph)
- [GetClass](ue_ue.ReimportFbxSkeletalMeshFactory.md#getclass)
- [GetName](ue_ue.ReimportFbxSkeletalMeshFactory.md#getname)
- [GetOuter](ue_ue.ReimportFbxSkeletalMeshFactory.md#getouter)
- [GetWorld](ue_ue.ReimportFbxSkeletalMeshFactory.md#getworld)
- [ScriptFactoryCanImport](ue_ue.ReimportFbxSkeletalMeshFactory.md#scriptfactorycanimport)
- [ScriptFactoryCreateFile](ue_ue.ReimportFbxSkeletalMeshFactory.md#scriptfactorycreatefile)
- [Find](ue_ue.ReimportFbxSkeletalMeshFactory.md#find)
- [Load](ue_ue.ReimportFbxSkeletalMeshFactory.md#load)
- [StaticClass](ue_ue.ReimportFbxSkeletalMeshFactory.md#staticclass)

## Constructors

### constructor

• **new ReimportFbxSkeletalMeshFactory**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FbxFactory](ue_ue.FbxFactory.md).[constructor](ue_ue.FbxFactory.md#constructor)

## Properties

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[AssetImportTask](ue_ue.FbxFactory.md#assetimporttask)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[AutomatedImportData](ue_ue.FbxFactory.md#automatedimportdata)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[ContextClass](ue_ue.FbxFactory.md#contextclass)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[Formats](ue_ue.FbxFactory.md#formats)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[ImportPriority](ue_ue.FbxFactory.md#importpriority)

___

### ImportUI

• **ImportUI**: [`FbxImportUI`](ue_ue.FbxImportUI.md)

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[ImportUI](ue_ue.FbxFactory.md#importui)

___

### OriginalImportUI

• **OriginalImportUI**: [`FbxImportUI`](ue_ue.FbxImportUI.md)

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[OriginalImportUI](ue_ue.FbxFactory.md#originalimportui)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[OverwriteYesOrNoToAllState](ue_ue.FbxFactory.md#overwriteyesornotoallstate)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[SupportedClass](ue_ue.FbxFactory.md#supportedclass)

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[__tid_Factory__](ue_ue.FbxFactory.md#__tid_factory__)

___

### \_\_tid\_FbxFactory\_\_

• **\_\_tid\_FbxFactory\_\_**: `boolean`

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[__tid_FbxFactory__](ue_ue.FbxFactory.md#__tid_fbxfactory__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[__tid_Object__](ue_ue.FbxFactory.md#__tid_object__)

___

### \_\_tid\_ReimportFbxSkeletalMeshFactory\_\_

• **\_\_tid\_ReimportFbxSkeletalMeshFactory\_\_**: `boolean`

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[bCreateNew](ue_ue.FbxFactory.md#bcreatenew)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[bEditAfterNew](ue_ue.FbxFactory.md#beditafternew)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[bEditorImport](ue_ue.FbxFactory.md#beditorimport)

___

### bText

• **bText**: `boolean`

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[bText](ue_ue.FbxFactory.md#btext)

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

[FbxFactory](ue_ue.FbxFactory.md).[CreateDefaultSubobject](ue_ue.FbxFactory.md#createdefaultsubobject)

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

[FbxFactory](ue_ue.FbxFactory.md).[ExecuteUbergraph](ue_ue.FbxFactory.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[GetClass](ue_ue.FbxFactory.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[GetName](ue_ue.FbxFactory.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[GetOuter](ue_ue.FbxFactory.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FbxFactory](ue_ue.FbxFactory.md).[GetWorld](ue_ue.FbxFactory.md#getworld)

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

[FbxFactory](ue_ue.FbxFactory.md).[ScriptFactoryCanImport](ue_ue.FbxFactory.md#scriptfactorycanimport)

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

[FbxFactory](ue_ue.FbxFactory.md).[ScriptFactoryCreateFile](ue_ue.FbxFactory.md#scriptfactorycreatefile)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ReimportFbxSkeletalMeshFactory`](ue_ue.ReimportFbxSkeletalMeshFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ReimportFbxSkeletalMeshFactory`](ue_ue.ReimportFbxSkeletalMeshFactory.md)

#### Overrides

[FbxFactory](ue_ue.FbxFactory.md).[Find](ue_ue.FbxFactory.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ReimportFbxSkeletalMeshFactory`](ue_ue.ReimportFbxSkeletalMeshFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ReimportFbxSkeletalMeshFactory`](ue_ue.ReimportFbxSkeletalMeshFactory.md)

#### Overrides

[FbxFactory](ue_ue.FbxFactory.md).[Load](ue_ue.FbxFactory.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FbxFactory](ue_ue.FbxFactory.md).[StaticClass](ue_ue.FbxFactory.md#staticclass)
