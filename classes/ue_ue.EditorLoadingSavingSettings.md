[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EditorLoadingSavingSettings

# Class: EditorLoadingSavingSettings

[ue/ue](../modules/ue_ue.md).EditorLoadingSavingSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`EditorLoadingSavingSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.EditorLoadingSavingSettings.md#constructor)

### Properties

- [AutoReimportDirectories](ue_ue.EditorLoadingSavingSettings.md#autoreimportdirectories)
- [AutoReimportDirectorySettings](ue_ue.EditorLoadingSavingSettings.md#autoreimportdirectorysettings)
- [AutoReimportThreshold](ue_ue.EditorLoadingSavingSettings.md#autoreimportthreshold)
- [AutoSaveInteractionDelayInSeconds](ue_ue.EditorLoadingSavingSettings.md#autosaveinteractiondelayinseconds)
- [AutoSaveTimeMinutes](ue_ue.EditorLoadingSavingSettings.md#autosavetimeminutes)
- [AutoSaveWarningInSeconds](ue_ue.EditorLoadingSavingSettings.md#autosavewarninginseconds)
- [LoadLevelAtStartup](ue_ue.EditorLoadingSavingSettings.md#loadlevelatstartup)
- [TextDiffToolPath](ue_ue.EditorLoadingSavingSettings.md#textdifftoolpath)
- [\_\_tid\_EditorLoadingSavingSettings\_\_](ue_ue.EditorLoadingSavingSettings.md#__tid_editorloadingsavingsettings__)
- [\_\_tid\_Object\_\_](ue_ue.EditorLoadingSavingSettings.md#__tid_object__)
- [bAutoCreateAssets](ue_ue.EditorLoadingSavingSettings.md#bautocreateassets)
- [bAutoDeleteAssets](ue_ue.EditorLoadingSavingSettings.md#bautodeleteassets)
- [bAutoReimportCSV](ue_ue.EditorLoadingSavingSettings.md#bautoreimportcsv)
- [bAutoReimportTextures](ue_ue.EditorLoadingSavingSettings.md#bautoreimporttextures)
- [bAutoSaveContent](ue_ue.EditorLoadingSavingSettings.md#bautosavecontent)
- [bAutoSaveEnable](ue_ue.EditorLoadingSavingSettings.md#bautosaveenable)
- [bAutoSaveMaps](ue_ue.EditorLoadingSavingSettings.md#bautosavemaps)
- [bAutomaticallyCheckoutOnAssetModification](ue_ue.EditorLoadingSavingSettings.md#bautomaticallycheckoutonassetmodification)
- [bDeleteSourceFilesWithAssets](ue_ue.EditorLoadingSavingSettings.md#bdeletesourcefileswithassets)
- [bDetectChangesOnStartup](ue_ue.EditorLoadingSavingSettings.md#bdetectchangesonstartup)
- [bDirtyMigratedBlueprints](ue_ue.EditorLoadingSavingSettings.md#bdirtymigratedblueprints)
- [bEnableSourceControlCompatabilityCheck](ue_ue.EditorLoadingSavingSettings.md#benablesourcecontrolcompatabilitycheck)
- [bForceCompilationAtStartup](ue_ue.EditorLoadingSavingSettings.md#bforcecompilationatstartup)
- [bMonitorContentDirectories](ue_ue.EditorLoadingSavingSettings.md#bmonitorcontentdirectories)
- [bPromptBeforeAutoImporting](ue_ue.EditorLoadingSavingSettings.md#bpromptbeforeautoimporting)
- [bPromptForCheckoutOnAssetModification](ue_ue.EditorLoadingSavingSettings.md#bpromptforcheckoutonassetmodification)
- [bRestoreOpenAssetTabsOnRestart](ue_ue.EditorLoadingSavingSettings.md#brestoreopenassettabsonrestart)
- [bSCCAutoAddNewFiles](ue_ue.EditorLoadingSavingSettings.md#bsccautoaddnewfiles)
- [bSCCUseGlobalSettings](ue_ue.EditorLoadingSavingSettings.md#bsccuseglobalsettings)

### Methods

- [CreateDefaultSubobject](ue_ue.EditorLoadingSavingSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EditorLoadingSavingSettings.md#executeubergraph)
- [GetClass](ue_ue.EditorLoadingSavingSettings.md#getclass)
- [GetName](ue_ue.EditorLoadingSavingSettings.md#getname)
- [GetOuter](ue_ue.EditorLoadingSavingSettings.md#getouter)
- [GetWorld](ue_ue.EditorLoadingSavingSettings.md#getworld)
- [Find](ue_ue.EditorLoadingSavingSettings.md#find)
- [Load](ue_ue.EditorLoadingSavingSettings.md#load)
- [StaticClass](ue_ue.EditorLoadingSavingSettings.md#staticclass)

## Constructors

### constructor

• **new EditorLoadingSavingSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AutoReimportDirectories

• **AutoReimportDirectories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### AutoReimportDirectorySettings

• **AutoReimportDirectorySettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AutoReimportDirectoryConfig`](ue_ue.AutoReimportDirectoryConfig.md)\>

___

### AutoReimportThreshold

• **AutoReimportThreshold**: `number`

___

### AutoSaveInteractionDelayInSeconds

• **AutoSaveInteractionDelayInSeconds**: `number`

___

### AutoSaveTimeMinutes

• **AutoSaveTimeMinutes**: `number`

___

### AutoSaveWarningInSeconds

• **AutoSaveWarningInSeconds**: `number`

___

### LoadLevelAtStartup

• **LoadLevelAtStartup**: [`ELoadLevelAtStartup`](../enums/ue_ue.ELoadLevelAtStartup.md)

___

### TextDiffToolPath

• **TextDiffToolPath**: [`FilePath`](ue_ue.FilePath.md)

___

### \_\_tid\_EditorLoadingSavingSettings\_\_

• **\_\_tid\_EditorLoadingSavingSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bAutoCreateAssets

• **bAutoCreateAssets**: `boolean`

___

### bAutoDeleteAssets

• **bAutoDeleteAssets**: `boolean`

___

### bAutoReimportCSV

• **bAutoReimportCSV**: `boolean`

___

### bAutoReimportTextures

• **bAutoReimportTextures**: `boolean`

___

### bAutoSaveContent

• **bAutoSaveContent**: `boolean`

___

### bAutoSaveEnable

• **bAutoSaveEnable**: `boolean`

___

### bAutoSaveMaps

• **bAutoSaveMaps**: `boolean`

___

### bAutomaticallyCheckoutOnAssetModification

• **bAutomaticallyCheckoutOnAssetModification**: `boolean`

___

### bDeleteSourceFilesWithAssets

• **bDeleteSourceFilesWithAssets**: `boolean`

___

### bDetectChangesOnStartup

• **bDetectChangesOnStartup**: `boolean`

___

### bDirtyMigratedBlueprints

• **bDirtyMigratedBlueprints**: `boolean`

___

### bEnableSourceControlCompatabilityCheck

• **bEnableSourceControlCompatabilityCheck**: `boolean`

___

### bForceCompilationAtStartup

• **bForceCompilationAtStartup**: `boolean`

___

### bMonitorContentDirectories

• **bMonitorContentDirectories**: `boolean`

___

### bPromptBeforeAutoImporting

• **bPromptBeforeAutoImporting**: `boolean`

___

### bPromptForCheckoutOnAssetModification

• **bPromptForCheckoutOnAssetModification**: `boolean`

___

### bRestoreOpenAssetTabsOnRestart

• **bRestoreOpenAssetTabsOnRestart**: `boolean`

___

### bSCCAutoAddNewFiles

• **bSCCAutoAddNewFiles**: `boolean`

___

### bSCCUseGlobalSettings

• **bSCCUseGlobalSettings**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EditorLoadingSavingSettings`](ue_ue.EditorLoadingSavingSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EditorLoadingSavingSettings`](ue_ue.EditorLoadingSavingSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EditorLoadingSavingSettings`](ue_ue.EditorLoadingSavingSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EditorLoadingSavingSettings`](ue_ue.EditorLoadingSavingSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
