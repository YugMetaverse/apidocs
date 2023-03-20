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

#### Defined in

[ue/ue.d.ts:46173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46173)

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

#### Defined in

[ue/ue.d.ts:46174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46174)

## Properties

### AdditionalManifestDependencies

• **AdditionalManifestDependencies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FilePath`](ue_ue.FilePath.md)\>

#### Defined in

[ue/ue.d.ts:46179](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46179)

___

### CompileSettings

• **CompileSettings**: [`LocalizationCompilationSettings`](ue_ue.LocalizationCompilationSettings.md)

#### Defined in

[ue/ue.d.ts:46185](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46185)

___

### ConflictStatus

• **ConflictStatus**: [`ELocalizationTargetConflictStatus`](../enums/ue_ue.ELocalizationTargetConflictStatus.md)

#### Defined in

[ue/ue.d.ts:46177](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46177)

___

### ExportSettings

• **ExportSettings**: [`LocalizationExportingSettings`](ue_ue.LocalizationExportingSettings.md)

#### Defined in

[ue/ue.d.ts:46184](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46184)

___

### GatherFromMetaData

• **GatherFromMetaData**: [`GatherTextFromMetaDataConfiguration`](ue_ue.GatherTextFromMetaDataConfiguration.md)

#### Defined in

[ue/ue.d.ts:46183](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46183)

___

### GatherFromPackages

• **GatherFromPackages**: [`GatherTextFromPackagesConfiguration`](ue_ue.GatherTextFromPackagesConfiguration.md)

#### Defined in

[ue/ue.d.ts:46182](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46182)

___

### GatherFromTextFiles

• **GatherFromTextFiles**: [`GatherTextFromTextFilesConfiguration`](ue_ue.GatherTextFromTextFilesConfiguration.md)

#### Defined in

[ue/ue.d.ts:46181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46181)

___

### Guid

• **Guid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:46176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46176)

___

### ImportDialogueSettings

• **ImportDialogueSettings**: [`LocalizationImportDialogueSettings`](ue_ue.LocalizationImportDialogueSettings.md)

#### Defined in

[ue/ue.d.ts:46186](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46186)

___

### Name

• **Name**: `string`

#### Defined in

[ue/ue.d.ts:46175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46175)

___

### NativeCultureIndex

• **NativeCultureIndex**: `number`

#### Defined in

[ue/ue.d.ts:46187](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46187)

___

### RequiredModuleNames

• **RequiredModuleNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:46180](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46180)

___

### SupportedCulturesStatistics

• **SupportedCulturesStatistics**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CultureStatistics`](ue_ue.CultureStatistics.md)\>

#### Defined in

[ue/ue.d.ts:46188](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46188)

___

### TargetDependencies

• **TargetDependencies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

#### Defined in

[ue/ue.d.ts:46178](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46178)

___

### \_\_tid\_LocalizationTargetSettings\_\_

• `Private` **\_\_tid\_LocalizationTargetSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:46194](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46194)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:46192](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46192)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:46193](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L46193)
