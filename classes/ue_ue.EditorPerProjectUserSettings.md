[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorPerProjectUserSettings

# Class: EditorPerProjectUserSettings

[ue/ue](../modules/ue_ue.md).EditorPerProjectUserSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`EditorPerProjectUserSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditorPerProjectUserSettings.md#constructor)

### Properties

- [AssetViewerProfileIndex](ue_ue.EditorPerProjectUserSettings.md#assetviewerprofileindex)
- [AssetViewerProfileName](ue_ue.EditorPerProjectUserSettings.md#assetviewerprofilename)
- [BlueprintFavorites](ue_ue.EditorPerProjectUserSettings.md#blueprintfavorites)
- [DataSourceFolder](ue_ue.EditorPerProjectUserSettings.md#datasourcefolder)
- [MaterialQualityLevel](ue_ue.EditorPerProjectUserSettings.md#materialqualitylevel)
- [PreviewFeatureLevel](ue_ue.EditorPerProjectUserSettings.md#previewfeaturelevel)
- [PreviewShaderFormatName](ue_ue.EditorPerProjectUserSettings.md#previewshaderformatname)
- [PropertyMatrix\_NumberOfPasteOperationsBeforeWarning](ue_ue.EditorPerProjectUserSettings.md#propertymatrix_numberofpasteoperationsbeforewarning)
- [SCSViewportCameraSpeed](ue_ue.EditorPerProjectUserSettings.md#scsviewportcameraspeed)
- [SimplygonServerIP](ue_ue.EditorPerProjectUserSettings.md#simplygonserverip)
- [SimplygonSwarmDelay](ue_ue.EditorPerProjectUserSettings.md#simplygonswarmdelay)
- [SwarmIntermediateFolder](ue_ue.EditorPerProjectUserSettings.md#swarmintermediatefolder)
- [SwarmMaxUploadChunkSizeInMB](ue_ue.EditorPerProjectUserSettings.md#swarmmaxuploadchunksizeinmb)
- [SwarmNumOfConcurrentJobs](ue_ue.EditorPerProjectUserSettings.md#swarmnumofconcurrentjobs)
- [\_\_tid\_EditorPerProjectUserSettings\_\_](ue_ue.EditorPerProjectUserSettings.md#__tid_editorperprojectusersettings__)
- [\_\_tid\_Object\_\_](ue_ue.EditorPerProjectUserSettings.md#__tid_object__)
- [bAllowSelectTranslucent](ue_ue.EditorPerProjectUserSettings.md#ballowselecttranslucent)
- [bAlwaysGatherBehaviorTreeDebuggerData](ue_ue.EditorPerProjectUserSettings.md#balwaysgatherbehaviortreedebuggerdata)
- [bAnimationReimportWarnings](ue_ue.EditorPerProjectUserSettings.md#banimationreimportwarnings)
- [bAutoloadCheckedOutPackages](ue_ue.EditorPerProjectUserSettings.md#bautoloadcheckedoutpackages)
- [bAutomaticallyHotReloadNewClasses](ue_ue.EditorPerProjectUserSettings.md#bautomaticallyhotreloadnewclasses)
- [bDisplayActionListItemRefIds](ue_ue.EditorPerProjectUserSettings.md#bdisplayactionlistitemrefids)
- [bDisplayBlackboardKeysInAlphabeticalOrder](ue_ue.EditorPerProjectUserSettings.md#bdisplayblackboardkeysinalphabeticalorder)
- [bDisplayDocumentationLink](ue_ue.EditorPerProjectUserSettings.md#bdisplaydocumentationlink)
- [bDisplayEngineVersionInBadge](ue_ue.EditorPerProjectUserSettings.md#bdisplayengineversioninbadge)
- [bDisplayUIExtensionPoints](ue_ue.EditorPerProjectUserSettings.md#bdisplayuiextensionpoints)
- [bEnableSwarmDebugging](ue_ue.EditorPerProjectUserSettings.md#benableswarmdebugging)
- [bGetAttentionOnUATCompletion](ue_ue.EditorPerProjectUserSettings.md#bgetattentiononuatcompletion)
- [bKeepAttachHierarchy](ue_ue.EditorPerProjectUserSettings.md#bkeepattachhierarchy)
- [bKeepFbxNamespace](ue_ue.EditorPerProjectUserSettings.md#bkeepfbxnamespace)
- [bPreviewFeatureLevelActive](ue_ue.EditorPerProjectUserSettings.md#bpreviewfeaturelevelactive)
- [bSCSEditorShowFloor](ue_ue.EditorPerProjectUserSettings.md#bscseditorshowfloor)
- [bSCSEditorShowGrid](ue_ue.EditorPerProjectUserSettings.md#bscseditorshowgrid)
- [bShowCompilerLogOnCompileError](ue_ue.EditorPerProjectUserSettings.md#bshowcompilerlogoncompileerror)
- [bShowImportDialogAtReimport](ue_ue.EditorPerProjectUserSettings.md#bshowimportdialogatreimport)
- [bSuppressFullyLoadPrompt](ue_ue.EditorPerProjectUserSettings.md#bsuppressfullyloadprompt)
- [bUseCurvesForDistributions](ue_ue.EditorPerProjectUserSettings.md#busecurvesfordistributions)
- [bUseSimplygonSwarm](ue_ue.EditorPerProjectUserSettings.md#busesimplygonswarm)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorPerProjectUserSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorPerProjectUserSettings.md#executeubergraph)
- [GetClass](ue_ue.EditorPerProjectUserSettings.md#getclass)
- [GetName](ue_ue.EditorPerProjectUserSettings.md#getname)
- [GetOuter](ue_ue.EditorPerProjectUserSettings.md#getouter)
- [GetWorld](ue_ue.EditorPerProjectUserSettings.md#getworld)
- [Find](ue_ue.EditorPerProjectUserSettings.md#find)
- [Load](ue_ue.EditorPerProjectUserSettings.md#load)
- [StaticClass](ue_ue.EditorPerProjectUserSettings.md#staticclass)

## Constructors

### constructor

• **new EditorPerProjectUserSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AssetViewerProfileIndex

• **AssetViewerProfileIndex**: `number`

___

### AssetViewerProfileName

• **AssetViewerProfileName**: `string`

___

### BlueprintFavorites

• **BlueprintFavorites**: [`BlueprintPaletteFavorites`](ue_ue.BlueprintPaletteFavorites.md)

___

### DataSourceFolder

• **DataSourceFolder**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

___

### MaterialQualityLevel

• **MaterialQualityLevel**: `number`

___

### PreviewFeatureLevel

• **PreviewFeatureLevel**: `number`

___

### PreviewShaderFormatName

• **PreviewShaderFormatName**: `string`

___

### PropertyMatrix\_NumberOfPasteOperationsBeforeWarning

• **PropertyMatrix\_NumberOfPasteOperationsBeforeWarning**: `number`

___

### SCSViewportCameraSpeed

• **SCSViewportCameraSpeed**: `number`

___

### SimplygonServerIP

• **SimplygonServerIP**: `string`

___

### SimplygonSwarmDelay

• **SimplygonSwarmDelay**: `number`

___

### SwarmIntermediateFolder

• **SwarmIntermediateFolder**: `string`

___

### SwarmMaxUploadChunkSizeInMB

• **SwarmMaxUploadChunkSizeInMB**: `number`

___

### SwarmNumOfConcurrentJobs

• **SwarmNumOfConcurrentJobs**: `number`

___

### \_\_tid\_EditorPerProjectUserSettings\_\_

• **\_\_tid\_EditorPerProjectUserSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bAllowSelectTranslucent

• **bAllowSelectTranslucent**: `boolean`

___

### bAlwaysGatherBehaviorTreeDebuggerData

• **bAlwaysGatherBehaviorTreeDebuggerData**: `boolean`

___

### bAnimationReimportWarnings

• **bAnimationReimportWarnings**: `boolean`

___

### bAutoloadCheckedOutPackages

• **bAutoloadCheckedOutPackages**: `boolean`

___

### bAutomaticallyHotReloadNewClasses

• **bAutomaticallyHotReloadNewClasses**: `boolean`

___

### bDisplayActionListItemRefIds

• **bDisplayActionListItemRefIds**: `boolean`

___

### bDisplayBlackboardKeysInAlphabeticalOrder

• **bDisplayBlackboardKeysInAlphabeticalOrder**: `boolean`

___

### bDisplayDocumentationLink

• **bDisplayDocumentationLink**: `boolean`

___

### bDisplayEngineVersionInBadge

• **bDisplayEngineVersionInBadge**: `boolean`

___

### bDisplayUIExtensionPoints

• **bDisplayUIExtensionPoints**: `boolean`

___

### bEnableSwarmDebugging

• **bEnableSwarmDebugging**: `boolean`

___

### bGetAttentionOnUATCompletion

• **bGetAttentionOnUATCompletion**: `boolean`

___

### bKeepAttachHierarchy

• **bKeepAttachHierarchy**: `boolean`

___

### bKeepFbxNamespace

• **bKeepFbxNamespace**: `boolean`

___

### bPreviewFeatureLevelActive

• **bPreviewFeatureLevelActive**: `boolean`

___

### bSCSEditorShowFloor

• **bSCSEditorShowFloor**: `boolean`

___

### bSCSEditorShowGrid

• **bSCSEditorShowGrid**: `boolean`

___

### bShowCompilerLogOnCompileError

• **bShowCompilerLogOnCompileError**: `boolean`

___

### bShowImportDialogAtReimport

• **bShowImportDialogAtReimport**: `boolean`

___

### bSuppressFullyLoadPrompt

• **bSuppressFullyLoadPrompt**: `boolean`

___

### bUseCurvesForDistributions

• **bUseCurvesForDistributions**: `boolean`

___

### bUseSimplygonSwarm

• **bUseSimplygonSwarm**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorPerProjectUserSettings`](ue_ue.EditorPerProjectUserSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorPerProjectUserSettings`](ue_ue.EditorPerProjectUserSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorPerProjectUserSettings`](ue_ue.EditorPerProjectUserSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorPerProjectUserSettings`](ue_ue.EditorPerProjectUserSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
