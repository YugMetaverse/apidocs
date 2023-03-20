[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Commandlet

# Class: Commandlet

[ue/ue](../modules/ue_ue.md).Commandlet

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`Commandlet`**

  ↳↳ [`AlembicTestCommandlet`](ue_ue.AlembicTestCommandlet.md)

  ↳↳ [`AssetRegUtilCommandlet`](ue_ue.AssetRegUtilCommandlet.md)

  ↳↳ [`AudioMixerCommandlet`](ue_ue.AudioMixerCommandlet.md)

  ↳↳ [`AudioTestCommandlet`](ue_ue.AudioTestCommandlet.md)

  ↳↳ [`CompileAllBlueprintsCommandlet`](ue_ue.CompileAllBlueprintsCommandlet.md)

  ↳↳ [`CompressAnimationsCommandlet`](ue_ue.CompressAnimationsCommandlet.md)

  ↳↳ [`CookCommandlet`](ue_ue.CookCommandlet.md)

  ↳↳ [`CryptoKeysCommandlet`](ue_ue.CryptoKeysCommandlet.md)

  ↳↳ [`DataValidationCommandlet`](ue_ue.DataValidationCommandlet.md)

  ↳↳ [`DDCCleanupCommandlet`](ue_ue.DDCCleanupCommandlet.md)

  ↳↳ [`DerivedDataCacheCommandlet`](ue_ue.DerivedDataCacheCommandlet.md)

  ↳↳ [`DiffAssetRegistriesCommandlet`](ue_ue.DiffAssetRegistriesCommandlet.md)

  ↳↳ [`DiffAssetsCommandlet`](ue_ue.DiffAssetsCommandlet.md)

  ↳↳ [`DiffFilesCommandlet`](ue_ue.DiffFilesCommandlet.md)

  ↳↳ [`DiffPackagesCommandlet`](ue_ue.DiffPackagesCommandlet.md)

  ↳↳ [`DumpBlueprintsInfoCommandlet`](ue_ue.DumpBlueprintsInfoCommandlet.md)

  ↳↳ [`DumpHiddenCategoriesCommandlet`](ue_ue.DumpHiddenCategoriesCommandlet.md)

  ↳↳ [`GatherTextCommandletBase`](ue_ue.GatherTextCommandletBase.md)

  ↳↳ [`ExportPakDependenciesCommandlet`](ue_ue.ExportPakDependenciesCommandlet.md)

  ↳↳ [`FileServerCommandlet`](ue_ue.FileServerCommandlet.md)

  ↳↳ [`FixConflictingLocalizationKeysCommandlet`](ue_ue.FixConflictingLocalizationKeysCommandlet.md)

  ↳↳ [`ResavePackagesCommandlet`](ue_ue.ResavePackagesCommandlet.md)

  ↳↳ [`GenerateAssetManifestCommandlet`](ue_ue.GenerateAssetManifestCommandlet.md)

  ↳↳ [`GenerateBlueprintAPICommandlet`](ue_ue.GenerateBlueprintAPICommandlet.md)

  ↳↳ [`GenerateDistillFileSetsCommandlet`](ue_ue.GenerateDistillFileSetsCommandlet.md)

  ↳↳ [`ImportAssetsCommandlet`](ue_ue.ImportAssetsCommandlet.md)

  ↳↳ [`ListMaterialsUsedWithMeshEmittersCommandlet`](ue_ue.ListMaterialsUsedWithMeshEmittersCommandlet.md)

  ↳↳ [`ListStaticMeshesImportedFromSpeedTreesCommandlet`](ue_ue.ListStaticMeshesImportedFromSpeedTreesCommandlet.md)

  ↳↳ [`LoadPackageCommandlet`](ue_ue.LoadPackageCommandlet.md)

  ↳↳ [`MergeShaderPipelineCachesCommandlet`](ue_ue.MergeShaderPipelineCachesCommandlet.md)

  ↳↳ [`NativeCodeGenCommandlet`](ue_ue.NativeCodeGenCommandlet.md)

  ↳↳ [`ParticleSystemAuditCommandlet`](ue_ue.ParticleSystemAuditCommandlet.md)

  ↳↳ [`PkgInfoCommandlet`](ue_ue.PkgInfoCommandlet.md)

  ↳↳ [`PluginCommandlet`](ue_ue.PluginCommandlet.md)

  ↳↳ [`PopulateDialogueWaveFromCharacterSheetCommandlet`](ue_ue.PopulateDialogueWaveFromCharacterSheetCommandlet.md)

  ↳↳ [`ReplaceActorCommandlet`](ue_ue.ReplaceActorCommandlet.md)

  ↳↳ [`ReplaceAssetsCommandlet`](ue_ue.ReplaceAssetsCommandlet.md)

  ↳↳ [`ScreenshotComparisonCommandlet`](ue_ue.ScreenshotComparisonCommandlet.md)

  ↳↳ [`ShaderCodeLibraryToolsCommandlet`](ue_ue.ShaderCodeLibraryToolsCommandlet.md)

  ↳↳ [`ShaderPipelineCacheToolsCommandlet`](ue_ue.ShaderPipelineCacheToolsCommandlet.md)

  ↳↳ [`SmokeTestCommandlet`](ue_ue.SmokeTestCommandlet.md)

  ↳↳ [`StabilizeLocalizationKeysCommandlet`](ue_ue.StabilizeLocalizationKeysCommandlet.md)

  ↳↳ [`SwapSoundForDialogueInCuesCommandlet`](ue_ue.SwapSoundForDialogueInCuesCommandlet.md)

  ↳↳ [`TextAssetCommandlet`](ue_ue.TextAssetCommandlet.md)

  ↳↳ [`UnitTestCommandlet`](ue_ue.UnitTestCommandlet.md)

  ↳↳ [`UnrealPakCommandlet`](ue_ue.UnrealPakCommandlet.md)

  ↳↳ [`UpdateGameProjectCommandlet`](ue_ue.UpdateGameProjectCommandlet.md)

  ↳↳ [`WrangleContentCommandlet`](ue_ue.WrangleContentCommandlet.md)

## Table of contents

### Constructors

- [constructor](ue_ue.Commandlet.md#constructor)

### Properties

- [HelpDescription](ue_ue.Commandlet.md#helpdescription)
- [HelpParamDescriptions](ue_ue.Commandlet.md#helpparamdescriptions)
- [HelpParamNames](ue_ue.Commandlet.md#helpparamnames)
- [HelpUsage](ue_ue.Commandlet.md#helpusage)
- [HelpWebLink](ue_ue.Commandlet.md#helpweblink)
- [IsClient](ue_ue.Commandlet.md#isclient)
- [IsEditor](ue_ue.Commandlet.md#iseditor)
- [IsServer](ue_ue.Commandlet.md#isserver)
- [LogToConsole](ue_ue.Commandlet.md#logtoconsole)
- [ShowErrorCount](ue_ue.Commandlet.md#showerrorcount)
- [ShowProgress](ue_ue.Commandlet.md#showprogress)
- [\_\_tid\_Commandlet\_\_](ue_ue.Commandlet.md#__tid_commandlet__)
- [\_\_tid\_Object\_\_](ue_ue.Commandlet.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.Commandlet.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Commandlet.md#executeubergraph)
- [GetClass](ue_ue.Commandlet.md#getclass)
- [GetName](ue_ue.Commandlet.md#getname)
- [GetOuter](ue_ue.Commandlet.md#getouter)
- [GetWorld](ue_ue.Commandlet.md#getworld)
- [Find](ue_ue.Commandlet.md#find)
- [Load](ue_ue.Commandlet.md#load)
- [StaticClass](ue_ue.Commandlet.md#staticclass)

## Constructors

### constructor

• **new Commandlet**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:16166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16166)

## Properties

### HelpDescription

• **HelpDescription**: `string`

#### Defined in

[ue/ue.d.ts:16167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16167)

___

### HelpParamDescriptions

• **HelpParamDescriptions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:16171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16171)

___

### HelpParamNames

• **HelpParamNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:16170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16170)

___

### HelpUsage

• **HelpUsage**: `string`

#### Defined in

[ue/ue.d.ts:16168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16168)

___

### HelpWebLink

• **HelpWebLink**: `string`

#### Defined in

[ue/ue.d.ts:16169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16169)

___

### IsClient

• **IsClient**: `boolean`

#### Defined in

[ue/ue.d.ts:16173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16173)

___

### IsEditor

• **IsEditor**: `boolean`

#### Defined in

[ue/ue.d.ts:16174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16174)

___

### IsServer

• **IsServer**: `boolean`

#### Defined in

[ue/ue.d.ts:16172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16172)

___

### LogToConsole

• **LogToConsole**: `boolean`

#### Defined in

[ue/ue.d.ts:16175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16175)

___

### ShowErrorCount

• **ShowErrorCount**: `boolean`

#### Defined in

[ue/ue.d.ts:16176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16176)

___

### ShowProgress

• **ShowProgress**: `boolean`

#### Defined in

[ue/ue.d.ts:16177](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16177)

___

### \_\_tid\_Commandlet\_\_

• **\_\_tid\_Commandlet\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:16182](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16182)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Commandlet`](ue_ue.Commandlet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Commandlet`](ue_ue.Commandlet.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:16179](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16179)

___

### Load

▸ `Static` **Load**(`InName`): [`Commandlet`](ue_ue.Commandlet.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Commandlet`](ue_ue.Commandlet.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:16180](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16180)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:16178](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16178)
