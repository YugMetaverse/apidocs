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

#### Defined in

[ue/ue.d.ts:35420](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35420)

## Properties

### AnimSequenceImportData

• **AnimSequenceImportData**: [`FbxAnimSequenceImportData`](ue_ue.FbxAnimSequenceImportData.md)

#### Defined in

[ue/ue.d.ts:35426](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35426)

___

### AssetImportTask

• **AssetImportTask**: [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[AssetImportTask](ue_ue.SceneImportFactory.md#assetimporttask)

#### Defined in

[ue/ue.d.ts:15338](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15338)

___

### AutomatedImportData

• **AutomatedImportData**: [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[AutomatedImportData](ue_ue.SceneImportFactory.md#automatedimportdata)

#### Defined in

[ue/ue.d.ts:15337](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15337)

___

### ContextClass

• **ContextClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[ContextClass](ue_ue.SceneImportFactory.md#contextclass)

#### Defined in

[ue/ue.d.ts:15331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15331)

___

### Formats

• **Formats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[Formats](ue_ue.SceneImportFactory.md#formats)

#### Defined in

[ue/ue.d.ts:15332](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15332)

___

### ImportPriority

• **ImportPriority**: `number`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[ImportPriority](ue_ue.SceneImportFactory.md#importpriority)

#### Defined in

[ue/ue.d.ts:15336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15336)

___

### OverwriteYesOrNoToAllState

• **OverwriteYesOrNoToAllState**: `number`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[OverwriteYesOrNoToAllState](ue_ue.SceneImportFactory.md#overwriteyesornotoallstate)

#### Defined in

[ue/ue.d.ts:15339](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15339)

___

### ReimportData

• **ReimportData**: [`FbxSceneImportData`](ue_ue.FbxSceneImportData.md)

#### Defined in

[ue/ue.d.ts:35428](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35428)

___

### SceneImportOptions

• **SceneImportOptions**: [`FbxSceneImportOptions`](ue_ue.FbxSceneImportOptions.md)

#### Defined in

[ue/ue.d.ts:35421](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35421)

___

### SceneImportOptionsSkeletalMesh

• **SceneImportOptionsSkeletalMesh**: [`FbxSceneImportOptionsSkeletalMesh`](ue_ue.FbxSceneImportOptionsSkeletalMesh.md)

#### Defined in

[ue/ue.d.ts:35423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35423)

___

### SceneImportOptionsStaticMesh

• **SceneImportOptionsStaticMesh**: [`FbxSceneImportOptionsStaticMesh`](ue_ue.FbxSceneImportOptionsStaticMesh.md)

#### Defined in

[ue/ue.d.ts:35422](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35422)

___

### SkeletalMeshImportData

• **SkeletalMeshImportData**: [`FbxSkeletalMeshImportData`](ue_ue.FbxSkeletalMeshImportData.md)

#### Defined in

[ue/ue.d.ts:35425](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35425)

___

### StaticMeshImportData

• **StaticMeshImportData**: [`FbxStaticMeshImportData`](ue_ue.FbxStaticMeshImportData.md)

#### Defined in

[ue/ue.d.ts:35424](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35424)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[SupportedClass](ue_ue.SceneImportFactory.md#supportedclass)

#### Defined in

[ue/ue.d.ts:15330](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15330)

___

### TextureImportData

• **TextureImportData**: [`FbxTextureImportData`](ue_ue.FbxTextureImportData.md)

#### Defined in

[ue/ue.d.ts:35427](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35427)

___

### \_\_tid\_Factory\_\_

• **\_\_tid\_Factory\_\_**: `boolean`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[__tid_Factory__](ue_ue.SceneImportFactory.md#__tid_factory__)

#### Defined in

[ue/ue.d.ts:15346](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15346)

___

### \_\_tid\_FbxSceneImportFactory\_\_

• **\_\_tid\_FbxSceneImportFactory\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:35433](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35433)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[__tid_Object__](ue_ue.SceneImportFactory.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_SceneImportFactory\_\_

• **\_\_tid\_SceneImportFactory\_\_**: `boolean`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[__tid_SceneImportFactory__](ue_ue.SceneImportFactory.md#__tid_sceneimportfactory__)

#### Defined in

[ue/ue.d.ts:35348](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35348)

___

### bCreateNew

• **bCreateNew**: `boolean`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[bCreateNew](ue_ue.SceneImportFactory.md#bcreatenew)

#### Defined in

[ue/ue.d.ts:15329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15329)

___

### bEditAfterNew

• **bEditAfterNew**: `boolean`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[bEditAfterNew](ue_ue.SceneImportFactory.md#beditafternew)

#### Defined in

[ue/ue.d.ts:15333](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15333)

___

### bEditorImport

• **bEditorImport**: `boolean`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[bEditorImport](ue_ue.SceneImportFactory.md#beditorimport)

#### Defined in

[ue/ue.d.ts:15334](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15334)

___

### bText

• **bText**: `boolean`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[bText](ue_ue.SceneImportFactory.md#btext)

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

[SceneImportFactory](ue_ue.SceneImportFactory.md).[CreateDefaultSubobject](ue_ue.SceneImportFactory.md#createdefaultsubobject)

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

[SceneImportFactory](ue_ue.SceneImportFactory.md).[ExecuteUbergraph](ue_ue.SceneImportFactory.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[GetClass](ue_ue.SceneImportFactory.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[GetName](ue_ue.SceneImportFactory.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[GetOuter](ue_ue.SceneImportFactory.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SceneImportFactory](ue_ue.SceneImportFactory.md).[GetWorld](ue_ue.SceneImportFactory.md#getworld)

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

[SceneImportFactory](ue_ue.SceneImportFactory.md).[ScriptFactoryCanImport](ue_ue.SceneImportFactory.md#scriptfactorycanimport)

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

[SceneImportFactory](ue_ue.SceneImportFactory.md).[ScriptFactoryCreateFile](ue_ue.SceneImportFactory.md#scriptfactorycreatefile)

#### Defined in

[ue/ue.d.ts:15341](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15341)

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

#### Defined in

[ue/ue.d.ts:35430](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35430)

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

#### Defined in

[ue/ue.d.ts:35431](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35431)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SceneImportFactory](ue_ue.SceneImportFactory.md).[StaticClass](ue_ue.SceneImportFactory.md#staticclass)

#### Defined in

[ue/ue.d.ts:35429](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L35429)
