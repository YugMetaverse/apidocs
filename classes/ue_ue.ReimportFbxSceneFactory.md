[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ReimportFbxSceneFactory

# Class: ReimportFbxSceneFactory

[ue/ue](../modules/ue_ue.md).ReimportFbxSceneFactory

## Hierarchy

- [`FbxSceneImportFactory`](ue_ue.FbxSceneImportFactory.md)

  ↳ **`ReimportFbxSceneFactory`**

## Table of contents

### Constructors

- [constructor](ue_ue.ReimportFbxSceneFactory.md#constructor)

### Properties

- [AnimSequenceImportData](ue_ue.ReimportFbxSceneFactory.md#animsequenceimportdata)
- [AssetImportTask](ue_ue.ReimportFbxSceneFactory.md#assetimporttask)
- [AutomatedImportData](ue_ue.ReimportFbxSceneFactory.md#automatedimportdata)
- [ContextClass](ue_ue.ReimportFbxSceneFactory.md#contextclass)
- [Formats](ue_ue.ReimportFbxSceneFactory.md#formats)
- [ImportPriority](ue_ue.ReimportFbxSceneFactory.md#importpriority)
- [OverwriteYesOrNoToAllState](ue_ue.ReimportFbxSceneFactory.md#overwriteyesornotoallstate)
- [ReimportData](ue_ue.ReimportFbxSceneFactory.md#reimportdata)
- [SceneImportOptions](ue_ue.ReimportFbxSceneFactory.md#sceneimportoptions)
- [SceneImportOptionsSkeletalMesh](ue_ue.ReimportFbxSceneFactory.md#sceneimportoptionsskeletalmesh)
- [SceneImportOptionsStaticMesh](ue_ue.ReimportFbxSceneFactory.md#sceneimportoptionsstaticmesh)
- [SkeletalMeshImportData](ue_ue.ReimportFbxSceneFactory.md#skeletalmeshimportdata)
- [StaticMeshImportData](ue_ue.ReimportFbxSceneFactory.md#staticmeshimportdata)
- [SupportedClass](ue_ue.ReimportFbxSceneFactory.md#supportedclass)
- [TextureImportData](ue_ue.ReimportFbxSceneFactory.md#textureimportdata)
- [\_\_tid\_Factory\_\_](ue_ue.ReimportFbxSceneFactory.md#__tid_factory__)
- [\_\_tid\_FbxSceneImportFactory\_\_](ue_ue.ReimportFbxSceneFactory.md#__tid_fbxsceneimportfactory__)
- [\_\_tid\_Object\_\_](ue_ue.ReimportFbxSceneFactory.md#__tid_object__)
- [\_\_tid\_ReimportFbxSceneFactory\_\_](ue_ue.ReimportFbxSceneFactory.md#__tid_reimportfbxscenefactory__)
- [\_\_tid\_SceneImportFactory\_\_](ue_ue.ReimportFbxSceneFactory.md#__tid_sceneimportfactory__)
- [bCreateNew](ue_ue.ReimportFbxSceneFactory.md#bcreatenew)
- [bEditAfterNew](ue_ue.ReimportFbxSceneFactory.md#beditafternew)
- [bEditorImport](ue_ue.ReimportFbxSceneFactory.md#beditorimport)
- [bText](ue_ue.ReimportFbxSceneFactory.md#btext)

### Methods

- [CreateDefaultSubobject](ue_ue.ReimportFbxSceneFactory.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ReimportFbxSceneFactory.md#executeubergraph)
- [GetClass](ue_ue.ReimportFbxSceneFactory.md#getclass)
- [GetName](ue_ue.ReimportFbxSceneFactory.md#getname)
- [GetOuter](ue_ue.ReimportFbxSceneFactory.md#getouter)
- [GetWorld](ue_ue.ReimportFbxSceneFactory.md#getworld)
- [ScriptFactoryCanImport](ue_ue.ReimportFbxSceneFactory.md#scriptfactorycanimport)
- [ScriptFactoryCreateFile](ue_ue.ReimportFbxSceneFactory.md#scriptfactorycreatefile)
- [Find](ue_ue.ReimportFbxSceneFactory.md#find)
- [Load](ue_ue.ReimportFbxSceneFactory.md#load)
- [StaticClass](ue_ue.ReimportFbxSceneFactory.md#staticclass)

## Constructors

### constructor

• **new ReimportFbxSceneFactory**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[constructor](ue_ue.FbxSceneImportFactory.md#constructor)

## Properties

### AnimSequenceImportData

• **AnimSequenceImportData**: [`FbxAnimSequenceImportData`](ue_ue.FbxAnimSequenceImportData.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[AnimSequenceImportData](ue_ue.FbxSceneImportFactory.md#animsequenceimportdata)

___

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[AssetImportTask](ue_ue.FbxSceneImportFactory.md#assetimporttask)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[AutomatedImportData](ue_ue.FbxSceneImportFactory.md#automatedimportdata)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[ContextClass](ue_ue.FbxSceneImportFactory.md#contextclass)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[Formats](ue_ue.FbxSceneImportFactory.md#formats)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[ImportPriority](ue_ue.FbxSceneImportFactory.md#importpriority)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[OverwriteYesOrNoToAllState](ue_ue.FbxSceneImportFactory.md#overwriteyesornotoallstate)

___

### ReimportData

• **ReimportData**: [`FbxSceneImportData`](ue_ue.FbxSceneImportData.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[ReimportData](ue_ue.FbxSceneImportFactory.md#reimportdata)

___

### SceneImportOptions

• **SceneImportOptions**: [`FbxSceneImportOptions`](ue_ue.FbxSceneImportOptions.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[SceneImportOptions](ue_ue.FbxSceneImportFactory.md#sceneimportoptions)

___

### SceneImportOptionsSkeletalMesh

• **SceneImportOptionsSkeletalMesh**: [`FbxSceneImportOptionsSkeletalMesh`](ue_ue.FbxSceneImportOptionsSkeletalMesh.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[SceneImportOptionsSkeletalMesh](ue_ue.FbxSceneImportFactory.md#sceneimportoptionsskeletalmesh)

___

### SceneImportOptionsStaticMesh

• **SceneImportOptionsStaticMesh**: [`FbxSceneImportOptionsStaticMesh`](ue_ue.FbxSceneImportOptionsStaticMesh.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[SceneImportOptionsStaticMesh](ue_ue.FbxSceneImportFactory.md#sceneimportoptionsstaticmesh)

___

### SkeletalMeshImportData

• **SkeletalMeshImportData**: [`FbxSkeletalMeshImportData`](ue_ue.FbxSkeletalMeshImportData.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[SkeletalMeshImportData](ue_ue.FbxSceneImportFactory.md#skeletalmeshimportdata)

___

### StaticMeshImportData

• **StaticMeshImportData**: [`FbxStaticMeshImportData`](ue_ue.FbxStaticMeshImportData.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[StaticMeshImportData](ue_ue.FbxSceneImportFactory.md#staticmeshimportdata)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[SupportedClass](ue_ue.FbxSceneImportFactory.md#supportedclass)

___

### TextureImportData

• **TextureImportData**: [`FbxTextureImportData`](ue_ue.FbxTextureImportData.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[TextureImportData](ue_ue.FbxSceneImportFactory.md#textureimportdata)

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[__tid_Factory__](ue_ue.FbxSceneImportFactory.md#__tid_factory__)

___

### \_\_tid\_FbxSceneImportFactory\_\_

• **\_\_tid\_FbxSceneImportFactory\_\_**: `boolean`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[__tid_FbxSceneImportFactory__](ue_ue.FbxSceneImportFactory.md#__tid_fbxsceneimportfactory__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[__tid_Object__](ue_ue.FbxSceneImportFactory.md#__tid_object__)

___

### \_\_tid\_ReimportFbxSceneFactory\_\_

• **\_\_tid\_ReimportFbxSceneFactory\_\_**: `boolean`

___

### \_\_tid\_SceneImportFactory\_\_

• **\_\_tid\_SceneImportFactory\_\_**: `boolean`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[__tid_SceneImportFactory__](ue_ue.FbxSceneImportFactory.md#__tid_sceneimportfactory__)

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[bCreateNew](ue_ue.FbxSceneImportFactory.md#bcreatenew)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[bEditAfterNew](ue_ue.FbxSceneImportFactory.md#beditafternew)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[bEditorImport](ue_ue.FbxSceneImportFactory.md#beditorimport)

___

### bText

• **bText**: `boolean`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[bText](ue_ue.FbxSceneImportFactory.md#btext)

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

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[CreateDefaultSubobject](ue_ue.FbxSceneImportFactory.md#createdefaultsubobject)

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

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[ExecuteUbergraph](ue_ue.FbxSceneImportFactory.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[GetClass](ue_ue.FbxSceneImportFactory.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[GetName](ue_ue.FbxSceneImportFactory.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[GetOuter](ue_ue.FbxSceneImportFactory.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[GetWorld](ue_ue.FbxSceneImportFactory.md#getworld)

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

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[ScriptFactoryCanImport](ue_ue.FbxSceneImportFactory.md#scriptfactorycanimport)

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

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[ScriptFactoryCreateFile](ue_ue.FbxSceneImportFactory.md#scriptfactorycreatefile)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ReimportFbxSceneFactory`](ue_ue.ReimportFbxSceneFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ReimportFbxSceneFactory`](ue_ue.ReimportFbxSceneFactory.md)

#### Overrides

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[Find](ue_ue.FbxSceneImportFactory.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ReimportFbxSceneFactory`](ue_ue.ReimportFbxSceneFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ReimportFbxSceneFactory`](ue_ue.ReimportFbxSceneFactory.md)

#### Overrides

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[Load](ue_ue.FbxSceneImportFactory.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[StaticClass](ue_ue.FbxSceneImportFactory.md#staticclass)
