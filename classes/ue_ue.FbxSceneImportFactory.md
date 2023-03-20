[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / FbxSceneImportFactory

# Class: FbxSceneImportFactory

[ue/ue](../modules/ue_ue.md).FbxSceneImportFactory

## Hierarchy

- [`SceneImportFactory`](ue_ue.SceneImportFactory.md)

  ↳ **`FbxSceneImportFactory`**

  ↳↳ [`ReimportFbxSceneFactory`](ue_ue.ReimportFbxSceneFactory.md)

## Table of contents

### Constructors

- [constructor](ue_ue.FbxSceneImportFactory.md#constructor)

### Properties

- [AnimSequenceImportData](ue_ue.FbxSceneImportFactory.md#animsequenceimportdata)
- [AssetImportTask](ue_ue.FbxSceneImportFactory.md#assetimporttask)
- [AutomatedImportData](ue_ue.FbxSceneImportFactory.md#automatedimportdata)
- [ContextClass](ue_ue.FbxSceneImportFactory.md#contextclass)
- [Formats](ue_ue.FbxSceneImportFactory.md#formats)
- [ImportPriority](ue_ue.FbxSceneImportFactory.md#importpriority)
- [OverwriteYesOrNoToAllState](ue_ue.FbxSceneImportFactory.md#overwriteyesornotoallstate)
- [ReimportData](ue_ue.FbxSceneImportFactory.md#reimportdata)
- [SceneImportOptions](ue_ue.FbxSceneImportFactory.md#sceneimportoptions)
- [SceneImportOptionsSkeletalMesh](ue_ue.FbxSceneImportFactory.md#sceneimportoptionsskeletalmesh)
- [SceneImportOptionsStaticMesh](ue_ue.FbxSceneImportFactory.md#sceneimportoptionsstaticmesh)
- [SkeletalMeshImportData](ue_ue.FbxSceneImportFactory.md#skeletalmeshimportdata)
- [StaticMeshImportData](ue_ue.FbxSceneImportFactory.md#staticmeshimportdata)
- [SupportedClass](ue_ue.FbxSceneImportFactory.md#supportedclass)
- [TextureImportData](ue_ue.FbxSceneImportFactory.md#textureimportdata)
- [\_\_tid\_Factory\_\_](ue_ue.FbxSceneImportFactory.md#__tid_factory__)
- [\_\_tid\_FbxSceneImportFactory\_\_](ue_ue.FbxSceneImportFactory.md#__tid_fbxsceneimportfactory__)
- [\_\_tid\_Object\_\_](ue_ue.FbxSceneImportFactory.md#__tid_object__)
- [\_\_tid\_SceneImportFactory\_\_](ue_ue.FbxSceneImportFactory.md#__tid_sceneimportfactory__)
- [bCreateNew](ue_ue.FbxSceneImportFactory.md#bcreatenew)
- [bEditAfterNew](ue_ue.FbxSceneImportFactory.md#beditafternew)
- [bEditorImport](ue_ue.FbxSceneImportFactory.md#beditorimport)
- [bText](ue_ue.FbxSceneImportFactory.md#btext)

### Methods

- [CreateDefaultSubobject](ue_ue.FbxSceneImportFactory.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.FbxSceneImportFactory.md#executeubergraph)
- [GetClass](ue_ue.FbxSceneImportFactory.md#getclass)
- [GetName](ue_ue.FbxSceneImportFactory.md#getname)
- [GetOuter](ue_ue.FbxSceneImportFactory.md#getouter)
- [GetWorld](ue_ue.FbxSceneImportFactory.md#getworld)
- [ScriptFactoryCanImport](ue_ue.FbxSceneImportFactory.md#scriptfactorycanimport)
- [ScriptFactoryCreateFile](ue_ue.FbxSceneImportFactory.md#scriptfactorycreatefile)
- [Find](ue_ue.FbxSceneImportFactory.md#find)
- [Load](ue_ue.FbxSceneImportFactory.md#load)
- [StaticClass](ue_ue.FbxSceneImportFactory.md#staticclass)

## Constructors

### constructor

• **new FbxSceneImportFactory**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SceneImportFactory](ue_ue.SceneImportFactory.md).[constructor](ue_ue.SceneImportFactory.md#constructor)

## Properties

### AnimSequenceImportData

• **AnimSequenceImportData**: [`FbxAnimSequenceImportData`](ue_ue.FbxAnimSequenceImportData.md)

___

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[AssetImportTask](ue_ue.SceneImportFactory.md#assetimporttask)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[AutomatedImportData](ue_ue.SceneImportFactory.md#automatedimportdata)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[ContextClass](ue_ue.SceneImportFactory.md#contextclass)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[Formats](ue_ue.SceneImportFactory.md#formats)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[ImportPriority](ue_ue.SceneImportFactory.md#importpriority)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[OverwriteYesOrNoToAllState](ue_ue.SceneImportFactory.md#overwriteyesornotoallstate)

___

### ReimportData

• **ReimportData**: [`FbxSceneImportData`](ue_ue.FbxSceneImportData.md)

___

### SceneImportOptions

• **SceneImportOptions**: [`FbxSceneImportOptions`](ue_ue.FbxSceneImportOptions.md)

___

### SceneImportOptionsSkeletalMesh

• **SceneImportOptionsSkeletalMesh**: [`FbxSceneImportOptionsSkeletalMesh`](ue_ue.FbxSceneImportOptionsSkeletalMesh.md)

___

### SceneImportOptionsStaticMesh

• **SceneImportOptionsStaticMesh**: [`FbxSceneImportOptionsStaticMesh`](ue_ue.FbxSceneImportOptionsStaticMesh.md)

___

### SkeletalMeshImportData

• **SkeletalMeshImportData**: [`FbxSkeletalMeshImportData`](ue_ue.FbxSkeletalMeshImportData.md)

___

### StaticMeshImportData

• **StaticMeshImportData**: [`FbxStaticMeshImportData`](ue_ue.FbxStaticMeshImportData.md)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[SupportedClass](ue_ue.SceneImportFactory.md#supportedclass)

___

### TextureImportData

• **TextureImportData**: [`FbxTextureImportData`](ue_ue.FbxTextureImportData.md)

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[__tid_Factory__](ue_ue.SceneImportFactory.md#__tid_factory__)

___

### \_\_tid\_FbxSceneImportFactory\_\_

• **\_\_tid\_FbxSceneImportFactory\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[__tid_Object__](ue_ue.SceneImportFactory.md#__tid_object__)

___

### \_\_tid\_SceneImportFactory\_\_

• **\_\_tid\_SceneImportFactory\_\_**: `boolean`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[__tid_SceneImportFactory__](ue_ue.SceneImportFactory.md#__tid_sceneimportfactory__)

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[bCreateNew](ue_ue.SceneImportFactory.md#bcreatenew)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[bEditAfterNew](ue_ue.SceneImportFactory.md#beditafternew)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[bEditorImport](ue_ue.SceneImportFactory.md#beditorimport)

___

### bText

• **bText**: `boolean`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[bText](ue_ue.SceneImportFactory.md#btext)

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

[SceneImportFactory](ue_ue.SceneImportFactory.md).[CreateDefaultSubobject](ue_ue.SceneImportFactory.md#createdefaultsubobject)

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

[SceneImportFactory](ue_ue.SceneImportFactory.md).[ExecuteUbergraph](ue_ue.SceneImportFactory.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[GetClass](ue_ue.SceneImportFactory.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[GetName](ue_ue.SceneImportFactory.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[GetOuter](ue_ue.SceneImportFactory.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[GetWorld](ue_ue.SceneImportFactory.md#getworld)

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

[SceneImportFactory](ue_ue.SceneImportFactory.md).[ScriptFactoryCanImport](ue_ue.SceneImportFactory.md#scriptfactorycanimport)

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

[SceneImportFactory](ue_ue.SceneImportFactory.md).[ScriptFactoryCreateFile](ue_ue.SceneImportFactory.md#scriptfactorycreatefile)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`FbxSceneImportFactory`](ue_ue.FbxSceneImportFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`FbxSceneImportFactory`](ue_ue.FbxSceneImportFactory.md)

#### Overrides

[SceneImportFactory](ue_ue.SceneImportFactory.md).[Find](ue_ue.SceneImportFactory.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`FbxSceneImportFactory`](ue_ue.FbxSceneImportFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`FbxSceneImportFactory`](ue_ue.FbxSceneImportFactory.md)

#### Overrides

[SceneImportFactory](ue_ue.SceneImportFactory.md).[Load](ue_ue.SceneImportFactory.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SceneImportFactory](ue_ue.SceneImportFactory.md).[StaticClass](ue_ue.SceneImportFactory.md#staticclass)
