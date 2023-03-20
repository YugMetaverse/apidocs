[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ProjectPackagingSettings

# Class: ProjectPackagingSettings

[ue/ue](../modules/ue_ue.md).ProjectPackagingSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ProjectPackagingSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.ProjectPackagingSettings.md#constructor)

### Properties

- [ApplocalPrerequisitesDirectory](ue_ue.ProjectPackagingSettings.md#applocalprerequisitesdirectory)
- [BlueprintNativizationMethod](ue_ue.ProjectPackagingSettings.md#blueprintnativizationmethod)
- [Build](ue_ue.ProjectPackagingSettings.md#build)
- [BuildConfiguration](ue_ue.ProjectPackagingSettings.md#buildconfiguration)
- [BuildTarget](ue_ue.ProjectPackagingSettings.md#buildtarget)
- [CompressedChunkWildcard](ue_ue.ProjectPackagingSettings.md#compressedchunkwildcard)
- [CulturesToStage](ue_ue.ProjectPackagingSettings.md#culturestostage)
- [DirectoriesToAlwaysCook](ue_ue.ProjectPackagingSettings.md#directoriestoalwayscook)
- [DirectoriesToAlwaysStageAsNonUFS](ue_ue.ProjectPackagingSettings.md#directoriestoalwaysstageasnonufs)
- [DirectoriesToAlwaysStageAsNonUFSServer](ue_ue.ProjectPackagingSettings.md#directoriestoalwaysstageasnonufsserver)
- [DirectoriesToAlwaysStageAsUFS](ue_ue.ProjectPackagingSettings.md#directoriestoalwaysstageasufs)
- [DirectoriesToAlwaysStageAsUFSServer](ue_ue.ProjectPackagingSettings.md#directoriestoalwaysstageasufsserver)
- [DirectoriesToNeverCook](ue_ue.ProjectPackagingSettings.md#directoriestonevercook)
- [EarlyDownloaderPakFileFiles](ue_ue.ProjectPackagingSettings.md#earlydownloaderpakfilefiles)
- [ForDistribution](ue_ue.ProjectPackagingSettings.md#fordistribution)
- [FullRebuild](ue_ue.ProjectPackagingSettings.md#fullrebuild)
- [GenerateEarlyDownloaderPakFile](ue_ue.ProjectPackagingSettings.md#generateearlydownloaderpakfile)
- [HttpChunkInstallDataDirectory](ue_ue.ProjectPackagingSettings.md#httpchunkinstalldatadirectory)
- [HttpChunkInstallDataVersion](ue_ue.ProjectPackagingSettings.md#httpchunkinstalldataversion)
- [IncludeAppLocalPrerequisites](ue_ue.ProjectPackagingSettings.md#includeapplocalprerequisites)
- [IncludeCrashReporter](ue_ue.ProjectPackagingSettings.md#includecrashreporter)
- [IncludeDebugFiles](ue_ue.ProjectPackagingSettings.md#includedebugfiles)
- [IncludePrerequisites](ue_ue.ProjectPackagingSettings.md#includeprerequisites)
- [IniKeyBlacklist](ue_ue.ProjectPackagingSettings.md#inikeyblacklist)
- [IniSectionBlacklist](ue_ue.ProjectPackagingSettings.md#inisectionblacklist)
- [InternationalizationPreset](ue_ue.ProjectPackagingSettings.md#internationalizationpreset)
- [MapsToCook](ue_ue.ProjectPackagingSettings.md#mapstocook)
- [MaxChunkSize](ue_ue.ProjectPackagingSettings.md#maxchunksize)
- [NativizeBlueprintAssets](ue_ue.ProjectPackagingSettings.md#nativizeblueprintassets)
- [NonUFSMovies](ue_ue.ProjectPackagingSettings.md#nonufsmovies)
- [PakFileAdditionalCompressionOptions](ue_ue.ProjectPackagingSettings.md#pakfileadditionalcompressionoptions)
- [PakFileCompressionFormats](ue_ue.ProjectPackagingSettings.md#pakfilecompressionformats)
- [StagingDirectory](ue_ue.ProjectPackagingSettings.md#stagingdirectory)
- [UFSMovies](ue_ue.ProjectPackagingSettings.md#ufsmovies)
- [UsePakFile](ue_ue.ProjectPackagingSettings.md#usepakfile)
- [\_\_tid\_Object\_\_](ue_ue.ProjectPackagingSettings.md#__tid_object__)
- [\_\_tid\_ProjectPackagingSettings\_\_](ue_ue.ProjectPackagingSettings.md#__tid_projectpackagingsettings__)
- [bBuildHttpChunkInstallData](ue_ue.ProjectPackagingSettings.md#bbuildhttpchunkinstalldata)
- [bChunkHardReferencesOnly](ue_ue.ProjectPackagingSettings.md#bchunkhardreferencesonly)
- [bCompressed](ue_ue.ProjectPackagingSettings.md#bcompressed)
- [bCookAll](ue_ue.ProjectPackagingSettings.md#bcookall)
- [bCookMapsOnly](ue_ue.ProjectPackagingSettings.md#bcookmapsonly)
- [bEncryptIniFiles](ue_ue.ProjectPackagingSettings.md#bencryptinifiles)
- [bEncryptPakIndex](ue_ue.ProjectPackagingSettings.md#bencryptpakindex)
- [bExcludeMonolithicEngineHeadersInNativizedCode](ue_ue.ProjectPackagingSettings.md#bexcludemonolithicengineheadersinnativizedcode)
- [bForceOneChunkPerFile](ue_ue.ProjectPackagingSettings.md#bforceonechunkperfile)
- [bGenerateChunks](ue_ue.ProjectPackagingSettings.md#bgeneratechunks)
- [bGenerateNoChunks](ue_ue.ProjectPackagingSettings.md#bgeneratenochunks)
- [bIncludeNativizedAssetsInProjectGeneration](ue_ue.ProjectPackagingSettings.md#bincludenativizedassetsinprojectgeneration)
- [bNativizeBlueprintAssets](ue_ue.ProjectPackagingSettings.md#bnativizeblueprintassets)
- [bNativizeOnlySelectedBlueprints](ue_ue.ProjectPackagingSettings.md#bnativizeonlyselectedblueprints)
- [bShareMaterialShaderCode](ue_ue.ProjectPackagingSettings.md#bsharematerialshadercode)
- [bSharedMaterialNativeLibraries](ue_ue.ProjectPackagingSettings.md#bsharedmaterialnativelibraries)
- [bSkipEditorContent](ue_ue.ProjectPackagingSettings.md#bskipeditorcontent)
- [bSkipMovies](ue_ue.ProjectPackagingSettings.md#bskipmovies)

### Methods

- [CreateDefaultSubobject](ue_ue.ProjectPackagingSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ProjectPackagingSettings.md#executeubergraph)
- [GetClass](ue_ue.ProjectPackagingSettings.md#getclass)
- [GetName](ue_ue.ProjectPackagingSettings.md#getname)
- [GetOuter](ue_ue.ProjectPackagingSettings.md#getouter)
- [GetWorld](ue_ue.ProjectPackagingSettings.md#getworld)
- [Find](ue_ue.ProjectPackagingSettings.md#find)
- [Load](ue_ue.ProjectPackagingSettings.md#load)
- [StaticClass](ue_ue.ProjectPackagingSettings.md#staticclass)

## Constructors

### constructor

• **new ProjectPackagingSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ApplocalPrerequisitesDirectory

• **ApplocalPrerequisitesDirectory**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

___

### BlueprintNativizationMethod

• **BlueprintNativizationMethod**: [`EProjectPackagingBlueprintNativizationMethod`](../enums/ue_ue.EProjectPackagingBlueprintNativizationMethod.md)

___

### Build

• **Build**: [`EProjectPackagingBuild`](../enums/ue_ue.EProjectPackagingBuild.md)

___

### BuildConfiguration

• **BuildConfiguration**: [`EProjectPackagingBuildConfigurations`](../enums/ue_ue.EProjectPackagingBuildConfigurations.md)

___

### BuildTarget

• **BuildTarget**: `string`

___

### CompressedChunkWildcard

• **CompressedChunkWildcard**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### CulturesToStage

• **CulturesToStage**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### DirectoriesToAlwaysCook

• **DirectoriesToAlwaysCook**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

___

### DirectoriesToAlwaysStageAsNonUFS

• **DirectoriesToAlwaysStageAsNonUFS**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

___

### DirectoriesToAlwaysStageAsNonUFSServer

• **DirectoriesToAlwaysStageAsNonUFSServer**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

___

### DirectoriesToAlwaysStageAsUFS

• **DirectoriesToAlwaysStageAsUFS**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

___

### DirectoriesToAlwaysStageAsUFSServer

• **DirectoriesToAlwaysStageAsUFSServer**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

___

### DirectoriesToNeverCook

• **DirectoriesToNeverCook**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

___

### EarlyDownloaderPakFileFiles

• **EarlyDownloaderPakFileFiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ForDistribution

• **ForDistribution**: `boolean`

___

### FullRebuild

• **FullRebuild**: `boolean`

___

### GenerateEarlyDownloaderPakFile

• **GenerateEarlyDownloaderPakFile**: `boolean`

___

### HttpChunkInstallDataDirectory

• **HttpChunkInstallDataDirectory**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

___

### HttpChunkInstallDataVersion

• **HttpChunkInstallDataVersion**: `string`

___

### IncludeAppLocalPrerequisites

• **IncludeAppLocalPrerequisites**: `boolean`

___

### IncludeCrashReporter

• **IncludeCrashReporter**: `boolean`

___

### IncludeDebugFiles

• **IncludeDebugFiles**: `boolean`

___

### IncludePrerequisites

• **IncludePrerequisites**: `boolean`

___

### IniKeyBlacklist

• **IniKeyBlacklist**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### IniSectionBlacklist

• **IniSectionBlacklist**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### InternationalizationPreset

• **InternationalizationPreset**: [`EProjectPackagingInternationalizationPresets`](../enums/ue_ue.EProjectPackagingInternationalizationPresets.md)

___

### MapsToCook

• **MapsToCook**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FilePath`](ue_ue.FilePath.md)\>

___

### MaxChunkSize

• **MaxChunkSize**: `bigint`

___

### NativizeBlueprintAssets

• **NativizeBlueprintAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FilePath`](ue_ue.FilePath.md)\>

___

### NonUFSMovies

• **NonUFSMovies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### PakFileAdditionalCompressionOptions

• **PakFileAdditionalCompressionOptions**: `string`

___

### PakFileCompressionFormats

• **PakFileCompressionFormats**: `string`

___

### StagingDirectory

• **StagingDirectory**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

___

### UFSMovies

• **UFSMovies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### UsePakFile

• **UsePakFile**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_ProjectPackagingSettings\_\_

• **\_\_tid\_ProjectPackagingSettings\_\_**: `boolean`

___

### bBuildHttpChunkInstallData

• **bBuildHttpChunkInstallData**: `boolean`

___

### bChunkHardReferencesOnly

• **bChunkHardReferencesOnly**: `boolean`

___

### bCompressed

• **bCompressed**: `boolean`

___

### bCookAll

• **bCookAll**: `boolean`

___

### bCookMapsOnly

• **bCookMapsOnly**: `boolean`

___

### bEncryptIniFiles

• **bEncryptIniFiles**: `boolean`

___

### bEncryptPakIndex

• **bEncryptPakIndex**: `boolean`

___

### bExcludeMonolithicEngineHeadersInNativizedCode

• **bExcludeMonolithicEngineHeadersInNativizedCode**: `boolean`

___

### bForceOneChunkPerFile

• **bForceOneChunkPerFile**: `boolean`

___

### bGenerateChunks

• **bGenerateChunks**: `boolean`

___

### bGenerateNoChunks

• **bGenerateNoChunks**: `boolean`

___

### bIncludeNativizedAssetsInProjectGeneration

• **bIncludeNativizedAssetsInProjectGeneration**: `boolean`

___

### bNativizeBlueprintAssets

• **bNativizeBlueprintAssets**: `boolean`

___

### bNativizeOnlySelectedBlueprints

• **bNativizeOnlySelectedBlueprints**: `boolean`

___

### bShareMaterialShaderCode

• **bShareMaterialShaderCode**: `boolean`

___

### bSharedMaterialNativeLibraries

• **bSharedMaterialNativeLibraries**: `boolean`

___

### bSkipEditorContent

• **bSkipEditorContent**: `boolean`

___

### bSkipMovies

• **bSkipMovies**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ProjectPackagingSettings`](ue_ue.ProjectPackagingSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ProjectPackagingSettings`](ue_ue.ProjectPackagingSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ProjectPackagingSettings`](ue_ue.ProjectPackagingSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ProjectPackagingSettings`](ue_ue.ProjectPackagingSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
