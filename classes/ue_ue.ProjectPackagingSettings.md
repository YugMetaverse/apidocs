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

#### Defined in

[ue/ue.d.ts:58644](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58644)

## Properties

### ApplocalPrerequisitesDirectory

• **ApplocalPrerequisitesDirectory**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

#### Defined in

[ue/ue.d.ts:58671](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58671)

___

### BlueprintNativizationMethod

• **BlueprintNativizationMethod**: [`EProjectPackagingBlueprintNativizationMethod`](../enums/ue_ue.EProjectPackagingBlueprintNativizationMethod.md)

#### Defined in

[ue/ue.d.ts:58652](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58652)

___

### Build

• **Build**: [`EProjectPackagingBuild`](../enums/ue_ue.EProjectPackagingBuild.md)

#### Defined in

[ue/ue.d.ts:58645](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58645)

___

### BuildConfiguration

• **BuildConfiguration**: [`EProjectPackagingBuildConfigurations`](../enums/ue_ue.EProjectPackagingBuildConfigurations.md)

#### Defined in

[ue/ue.d.ts:58646](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58646)

___

### BuildTarget

• **BuildTarget**: `string`

#### Defined in

[ue/ue.d.ts:58647](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58647)

___

### CompressedChunkWildcard

• **CompressedChunkWildcard**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:58685](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58685)

___

### CulturesToStage

• **CulturesToStage**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:58674](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58674)

___

### DirectoriesToAlwaysCook

• **DirectoriesToAlwaysCook**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

#### Defined in

[ue/ue.d.ts:58690](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58690)

___

### DirectoriesToAlwaysStageAsNonUFS

• **DirectoriesToAlwaysStageAsNonUFS**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

#### Defined in

[ue/ue.d.ts:58693](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58693)

___

### DirectoriesToAlwaysStageAsNonUFSServer

• **DirectoriesToAlwaysStageAsNonUFSServer**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

#### Defined in

[ue/ue.d.ts:58695](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58695)

___

### DirectoriesToAlwaysStageAsUFS

• **DirectoriesToAlwaysStageAsUFS**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

#### Defined in

[ue/ue.d.ts:58692](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58692)

___

### DirectoriesToAlwaysStageAsUFSServer

• **DirectoriesToAlwaysStageAsUFSServer**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

#### Defined in

[ue/ue.d.ts:58694](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58694)

___

### DirectoriesToNeverCook

• **DirectoriesToNeverCook**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryPath`](ue_ue.DirectoryPath.md)\>

#### Defined in

[ue/ue.d.ts:58691](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58691)

___

### EarlyDownloaderPakFileFiles

• **EarlyDownloaderPakFileFiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:58688](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58688)

___

### ForDistribution

• **ForDistribution**: `boolean`

#### Defined in

[ue/ue.d.ts:58650](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58650)

___

### FullRebuild

• **FullRebuild**: `boolean`

#### Defined in

[ue/ue.d.ts:58649](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58649)

___

### GenerateEarlyDownloaderPakFile

• **GenerateEarlyDownloaderPakFile**: `boolean`

#### Defined in

[ue/ue.d.ts:58680](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58680)

___

### HttpChunkInstallDataDirectory

• **HttpChunkInstallDataDirectory**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

#### Defined in

[ue/ue.d.ts:58663](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58663)

___

### HttpChunkInstallDataVersion

• **HttpChunkInstallDataVersion**: `string`

#### Defined in

[ue/ue.d.ts:58666](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58666)

___

### IncludeAppLocalPrerequisites

• **IncludeAppLocalPrerequisites**: `boolean`

#### Defined in

[ue/ue.d.ts:58668](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58668)

___

### IncludeCrashReporter

• **IncludeCrashReporter**: `boolean`

#### Defined in

[ue/ue.d.ts:58672](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58672)

___

### IncludeDebugFiles

• **IncludeDebugFiles**: `boolean`

#### Defined in

[ue/ue.d.ts:58651](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58651)

___

### IncludePrerequisites

• **IncludePrerequisites**: `boolean`

#### Defined in

[ue/ue.d.ts:58667](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58667)

___

### IniKeyBlacklist

• **IniKeyBlacklist**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:58686](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58686)

___

### IniSectionBlacklist

• **IniSectionBlacklist**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:58687](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58687)

___

### InternationalizationPreset

• **InternationalizationPreset**: [`EProjectPackagingInternationalizationPresets`](../enums/ue_ue.EProjectPackagingInternationalizationPresets.md)

#### Defined in

[ue/ue.d.ts:58673](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58673)

___

### MapsToCook

• **MapsToCook**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FilePath`](ue_ue.FilePath.md)\>

#### Defined in

[ue/ue.d.ts:58689](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58689)

___

### MaxChunkSize

• **MaxChunkSize**: `bigint`

#### Defined in

[ue/ue.d.ts:58661](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58661)

___

### NativizeBlueprintAssets

• **NativizeBlueprintAssets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FilePath`](ue_ue.FilePath.md)\>

#### Defined in

[ue/ue.d.ts:58653](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58653)

___

### NonUFSMovies

• **NonUFSMovies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:58684](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58684)

___

### PakFileAdditionalCompressionOptions

• **PakFileAdditionalCompressionOptions**: `string`

#### Defined in

[ue/ue.d.ts:58665](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58665)

___

### PakFileCompressionFormats

• **PakFileCompressionFormats**: `string`

#### Defined in

[ue/ue.d.ts:58664](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58664)

___

### StagingDirectory

• **StagingDirectory**: [`DirectoryPath`](ue_ue.DirectoryPath.md)

#### Defined in

[ue/ue.d.ts:58648](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58648)

___

### UFSMovies

• **UFSMovies**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:58683](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58683)

___

### UsePakFile

• **UsePakFile**: `boolean`

#### Defined in

[ue/ue.d.ts:58656](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58656)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ProjectPackagingSettings\_\_

• **\_\_tid\_ProjectPackagingSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:58702](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58702)

___

### bBuildHttpChunkInstallData

• **bBuildHttpChunkInstallData**: `boolean`

#### Defined in

[ue/ue.d.ts:58662](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58662)

___

### bChunkHardReferencesOnly

• **bChunkHardReferencesOnly**: `boolean`

#### Defined in

[ue/ue.d.ts:58659](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58659)

___

### bCompressed

• **bCompressed**: `boolean`

#### Defined in

[ue/ue.d.ts:58677](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58677)

___

### bCookAll

• **bCookAll**: `boolean`

#### Defined in

[ue/ue.d.ts:58675](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58675)

___

### bCookMapsOnly

• **bCookMapsOnly**: `boolean`

#### Defined in

[ue/ue.d.ts:58676](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58676)

___

### bEncryptIniFiles

• **bEncryptIniFiles**: `boolean`

#### Defined in

[ue/ue.d.ts:58678](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58678)

___

### bEncryptPakIndex

• **bEncryptPakIndex**: `boolean`

#### Defined in

[ue/ue.d.ts:58679](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58679)

___

### bExcludeMonolithicEngineHeadersInNativizedCode

• **bExcludeMonolithicEngineHeadersInNativizedCode**: `boolean`

#### Defined in

[ue/ue.d.ts:58655](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58655)

___

### bForceOneChunkPerFile

• **bForceOneChunkPerFile**: `boolean`

#### Defined in

[ue/ue.d.ts:58660](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58660)

___

### bGenerateChunks

• **bGenerateChunks**: `boolean`

#### Defined in

[ue/ue.d.ts:58657](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58657)

___

### bGenerateNoChunks

• **bGenerateNoChunks**: `boolean`

#### Defined in

[ue/ue.d.ts:58658](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58658)

___

### bIncludeNativizedAssetsInProjectGeneration

• **bIncludeNativizedAssetsInProjectGeneration**: `boolean`

#### Defined in

[ue/ue.d.ts:58654](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58654)

___

### bNativizeBlueprintAssets

• **bNativizeBlueprintAssets**: `boolean`

#### Defined in

[ue/ue.d.ts:58696](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58696)

___

### bNativizeOnlySelectedBlueprints

• **bNativizeOnlySelectedBlueprints**: `boolean`

#### Defined in

[ue/ue.d.ts:58697](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58697)

___

### bShareMaterialShaderCode

• **bShareMaterialShaderCode**: `boolean`

#### Defined in

[ue/ue.d.ts:58669](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58669)

___

### bSharedMaterialNativeLibraries

• **bSharedMaterialNativeLibraries**: `boolean`

#### Defined in

[ue/ue.d.ts:58670](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58670)

___

### bSkipEditorContent

• **bSkipEditorContent**: `boolean`

#### Defined in

[ue/ue.d.ts:58681](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58681)

___

### bSkipMovies

• **bSkipMovies**: `boolean`

#### Defined in

[ue/ue.d.ts:58682](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58682)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:58699](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58699)

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

#### Defined in

[ue/ue.d.ts:58700](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58700)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:58698](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58698)
