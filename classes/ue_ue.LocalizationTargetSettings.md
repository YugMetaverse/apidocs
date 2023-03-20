[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LocalizationTargetSettings

# Class: LocalizationTargetSettings

[ue/ue](../modules/ue_ue.md).LocalizationTargetSettings

## Table of contents

### Constructors

- [constructor](ue_ue.LocalizationTargetSettings.md#constructor)

### Properties

- [AdditionalManifestDependencies](ue_ue.LocalizationTargetSettings.md#additionalmanifestdependencies)
- [CompileSettings](ue_ue.LocalizationTargetSettings.md#compilesettings)
- [ConflictStatus](ue_ue.LocalizationTargetSettings.md#conflictstatus)
- [ExportSettings](ue_ue.LocalizationTargetSettings.md#exportsettings)
- [GatherFromMetaData](ue_ue.LocalizationTargetSettings.md#gatherfrommetadata)
- [GatherFromPackages](ue_ue.LocalizationTargetSettings.md#gatherfrompackages)
- [GatherFromTextFiles](ue_ue.LocalizationTargetSettings.md#gatherfromtextfiles)
- [Guid](ue_ue.LocalizationTargetSettings.md#guid)
- [ImportDialogueSettings](ue_ue.LocalizationTargetSettings.md#importdialoguesettings)
- [Name](ue_ue.LocalizationTargetSettings.md#name)
- [NativeCultureIndex](ue_ue.LocalizationTargetSettings.md#nativecultureindex)
- [RequiredModuleNames](ue_ue.LocalizationTargetSettings.md#requiredmodulenames)
- [SupportedCulturesStatistics](ue_ue.LocalizationTargetSettings.md#supportedculturesstatistics)
- [TargetDependencies](ue_ue.LocalizationTargetSettings.md#targetdependencies)
- [\_\_tid\_LocalizationTargetSettings\_\_](ue_ue.LocalizationTargetSettings.md#__tid_localizationtargetsettings__)

### Methods

- [StaticClass](ue_ue.LocalizationTargetSettings.md#staticclass)
- [StaticStruct](ue_ue.LocalizationTargetSettings.md#staticstruct)

## Constructors

### constructor

• **new LocalizationTargetSettings**()

• **new LocalizationTargetSettings**(`Name`, `Guid`, `ConflictStatus`, `TargetDependencies`, `AdditionalManifestDependencies`, `RequiredModuleNames`, `GatherFromTextFiles`, `GatherFromPackages`, `GatherFromMetaData`, `ExportSettings`, `CompileSettings`, `ImportDialogueSettings`, `NativeCultureIndex`, `SupportedCulturesStatistics`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `Guid` | [`Guid`](ue_ue_s.Guid.md) |
| `ConflictStatus` | [`ELocalizationTargetConflictStatus`](../enums/ue_ue.ELocalizationTargetConflictStatus.md) |
| `TargetDependencies` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\> |
| `AdditionalManifestDependencies` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FilePath`](ue_ue.FilePath.md)\> |
| `RequiredModuleNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `GatherFromTextFiles` | [`GatherTextFromTextFilesConfiguration`](ue_ue.GatherTextFromTextFilesConfiguration.md) |
| `GatherFromPackages` | [`GatherTextFromPackagesConfiguration`](ue_ue.GatherTextFromPackagesConfiguration.md) |
| `GatherFromMetaData` | [`GatherTextFromMetaDataConfiguration`](ue_ue.GatherTextFromMetaDataConfiguration.md) |
| `ExportSettings` | [`LocalizationExportingSettings`](ue_ue.LocalizationExportingSettings.md) |
| `CompileSettings` | [`LocalizationCompilationSettings`](ue_ue.LocalizationCompilationSettings.md) |
| `ImportDialogueSettings` | [`LocalizationImportDialogueSettings`](ue_ue.LocalizationImportDialogueSettings.md) |
| `NativeCultureIndex` | `number` |
| `SupportedCulturesStatistics` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CultureStatistics`](ue_ue.CultureStatistics.md)\> |

## Properties

### AdditionalManifestDependencies

• **AdditionalManifestDependencies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FilePath`](ue_ue.FilePath.md)\>

___

### CompileSettings

• **CompileSettings**: [`LocalizationCompilationSettings`](ue_ue.LocalizationCompilationSettings.md)

___

### ConflictStatus

• **ConflictStatus**: [`ELocalizationTargetConflictStatus`](../enums/ue_ue.ELocalizationTargetConflictStatus.md)

___

### ExportSettings

• **ExportSettings**: [`LocalizationExportingSettings`](ue_ue.LocalizationExportingSettings.md)

___

### GatherFromMetaData

• **GatherFromMetaData**: [`GatherTextFromMetaDataConfiguration`](ue_ue.GatherTextFromMetaDataConfiguration.md)

___

### GatherFromPackages

• **GatherFromPackages**: [`GatherTextFromPackagesConfiguration`](ue_ue.GatherTextFromPackagesConfiguration.md)

___

### GatherFromTextFiles

• **GatherFromTextFiles**: [`GatherTextFromTextFilesConfiguration`](ue_ue.GatherTextFromTextFilesConfiguration.md)

___

### Guid

• **Guid**: [`Guid`](ue_ue_s.Guid.md)

___

### ImportDialogueSettings

• **ImportDialogueSettings**: [`LocalizationImportDialogueSettings`](ue_ue.LocalizationImportDialogueSettings.md)

___

### Name

• **Name**: `string`

___

### NativeCultureIndex

• **NativeCultureIndex**: `number`

___

### RequiredModuleNames

• **RequiredModuleNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### SupportedCulturesStatistics

• **SupportedCulturesStatistics**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CultureStatistics`](ue_ue.CultureStatistics.md)\>

___

### TargetDependencies

• **TargetDependencies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

___

### \_\_tid\_LocalizationTargetSettings\_\_

• `Private` **\_\_tid\_LocalizationTargetSettings\_\_**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
