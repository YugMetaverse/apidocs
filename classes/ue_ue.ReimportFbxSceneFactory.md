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

#### Defined in

[ue/ue.d.ts:59286](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59286)

## Properties

### AnimSequenceImportData

• **AnimSequenceImportData**: [`FbxAnimSequenceImportData`](ue_ue.FbxAnimSequenceImportData.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[AnimSequenceImportData](ue_ue.FbxSceneImportFactory.md#animsequenceimportdata)

#### Defined in

[ue/ue.d.ts:35426](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35426)

___

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[AssetImportTask](ue_ue.FbxSceneImportFactory.md#assetimporttask)

#### Defined in

[ue/ue.d.ts:15338](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15338)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[AutomatedImportData](ue_ue.FbxSceneImportFactory.md#automatedimportdata)

#### Defined in

[ue/ue.d.ts:15337](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15337)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[ContextClass](ue_ue.FbxSceneImportFactory.md#contextclass)

#### Defined in

[ue/ue.d.ts:15331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15331)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[Formats](ue_ue.FbxSceneImportFactory.md#formats)

#### Defined in

[ue/ue.d.ts:15332](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15332)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[ImportPriority](ue_ue.FbxSceneImportFactory.md#importpriority)

#### Defined in

[ue/ue.d.ts:15336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15336)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[OverwriteYesOrNoToAllState](ue_ue.FbxSceneImportFactory.md#overwriteyesornotoallstate)

#### Defined in

[ue/ue.d.ts:15339](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15339)

___

### ReimportData

• **ReimportData**: [`FbxSceneImportData`](ue_ue.FbxSceneImportData.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[ReimportData](ue_ue.FbxSceneImportFactory.md#reimportdata)

#### Defined in

[ue/ue.d.ts:35428](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35428)

___

### SceneImportOptions

• **SceneImportOptions**: [`FbxSceneImportOptions`](ue_ue.FbxSceneImportOptions.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[SceneImportOptions](ue_ue.FbxSceneImportFactory.md#sceneimportoptions)

#### Defined in

[ue/ue.d.ts:35421](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35421)

___

### SceneImportOptionsSkeletalMesh

• **SceneImportOptionsSkeletalMesh**: [`FbxSceneImportOptionsSkeletalMesh`](ue_ue.FbxSceneImportOptionsSkeletalMesh.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[SceneImportOptionsSkeletalMesh](ue_ue.FbxSceneImportFactory.md#sceneimportoptionsskeletalmesh)

#### Defined in

[ue/ue.d.ts:35423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35423)

___

### SceneImportOptionsStaticMesh

• **SceneImportOptionsStaticMesh**: [`FbxSceneImportOptionsStaticMesh`](ue_ue.FbxSceneImportOptionsStaticMesh.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[SceneImportOptionsStaticMesh](ue_ue.FbxSceneImportFactory.md#sceneimportoptionsstaticmesh)

#### Defined in

[ue/ue.d.ts:35422](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35422)

___

### SkeletalMeshImportData

• **SkeletalMeshImportData**: [`FbxSkeletalMeshImportData`](ue_ue.FbxSkeletalMeshImportData.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[SkeletalMeshImportData](ue_ue.FbxSceneImportFactory.md#skeletalmeshimportdata)

#### Defined in

[ue/ue.d.ts:35425](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35425)

___

### StaticMeshImportData

• **StaticMeshImportData**: [`FbxStaticMeshImportData`](ue_ue.FbxStaticMeshImportData.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[StaticMeshImportData](ue_ue.FbxSceneImportFactory.md#staticmeshimportdata)

#### Defined in

[ue/ue.d.ts:35424](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35424)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[SupportedClass](ue_ue.FbxSceneImportFactory.md#supportedclass)

#### Defined in

[ue/ue.d.ts:15330](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15330)

___

### TextureImportData

• **TextureImportData**: [`FbxTextureImportData`](ue_ue.FbxTextureImportData.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[TextureImportData](ue_ue.FbxSceneImportFactory.md#textureimportdata)

#### Defined in

[ue/ue.d.ts:35427](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35427)

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[__tid_Factory__](ue_ue.FbxSceneImportFactory.md#__tid_factory__)

#### Defined in

[ue/ue.d.ts:15346](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15346)

___

### \_\_tid\_FbxSceneImportFactory\_\_

• **\_\_tid\_FbxSceneImportFactory\_\_**: `boolean`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[__tid_FbxSceneImportFactory__](ue_ue.FbxSceneImportFactory.md#__tid_fbxsceneimportfactory__)

#### Defined in

[ue/ue.d.ts:35433](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35433)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[__tid_Object__](ue_ue.FbxSceneImportFactory.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_ReimportFbxSceneFactory\_\_

• **\_\_tid\_ReimportFbxSceneFactory\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:59291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59291)

___

### \_\_tid\_SceneImportFactory\_\_

• **\_\_tid\_SceneImportFactory\_\_**: `boolean`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[__tid_SceneImportFactory__](ue_ue.FbxSceneImportFactory.md#__tid_sceneimportfactory__)

#### Defined in

[ue/ue.d.ts:35348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35348)

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[bCreateNew](ue_ue.FbxSceneImportFactory.md#bcreatenew)

#### Defined in

[ue/ue.d.ts:15329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15329)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[bEditAfterNew](ue_ue.FbxSceneImportFactory.md#beditafternew)

#### Defined in

[ue/ue.d.ts:15333](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15333)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[bEditorImport](ue_ue.FbxSceneImportFactory.md#beditorimport)

#### Defined in

[ue/ue.d.ts:15334](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15334)

___

### bText

• **bText**: `boolean`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[bText](ue_ue.FbxSceneImportFactory.md#btext)

#### Defined in

[ue/ue.d.ts:15335](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15335)

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

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[ExecuteUbergraph](ue_ue.FbxSceneImportFactory.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[GetClass](ue_ue.FbxSceneImportFactory.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[GetName](ue_ue.FbxSceneImportFactory.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[GetOuter](ue_ue.FbxSceneImportFactory.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[GetWorld](ue_ue.FbxSceneImportFactory.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:15340](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15340)

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

#### Defined in

[ue/ue.d.ts:15341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15341)

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

#### Defined in

[ue/ue.d.ts:59288](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59288)

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

#### Defined in

[ue/ue.d.ts:59289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59289)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FbxSceneImportFactory](ue_ue.FbxSceneImportFactory.md).[StaticClass](ue_ue.FbxSceneImportFactory.md#staticclass)

#### Defined in

[ue/ue.d.ts:59287](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L59287)
