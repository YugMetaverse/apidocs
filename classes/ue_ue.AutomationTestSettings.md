[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AutomationTestSettings

# Class: AutomationTestSettings

[ue/ue](../modules/ue_ue.md).AutomationTestSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AutomationTestSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.AutomationTestSettings.md#constructor)

### Properties

- [AssetsToOpen](ue_ue.AutomationTestSettings.md#assetstoopen)
- [AutomationTestmap](ue_ue.AutomationTestSettings.md#automationtestmap)
- [BlueprintEditorPromotionTest](ue_ue.AutomationTestSettings.md#blueprinteditorpromotiontest)
- [BuildPromotionTest](ue_ue.AutomationTestSettings.md#buildpromotiontest)
- [DefaultScreenshotResolution](ue_ue.AutomationTestSettings.md#defaultscreenshotresolution)
- [EditorPerformanceTestMaps](ue_ue.AutomationTestSettings.md#editorperformancetestmaps)
- [EditorTestModules](ue_ue.AutomationTestSettings.md#editortestmodules)
- [EngineTestModules](ue_ue.AutomationTestSettings.md#enginetestmodules)
- [ExternalTools](ue_ue.AutomationTestSettings.md#externaltools)
- [ImportExportTestDefinitions](ue_ue.AutomationTestSettings.md#importexporttestdefinitions)
- [LaunchOnSettings](ue_ue.AutomationTestSettings.md#launchonsettings)
- [MaterialEditorPromotionTest](ue_ue.AutomationTestSettings.md#materialeditorpromotiontest)
- [ParticleEditorPromotionTest](ue_ue.AutomationTestSettings.md#particleeditorpromotiontest)
- [TestLevelFolders](ue_ue.AutomationTestSettings.md#testlevelfolders)
- [\_\_tid\_AutomationTestSettings\_\_](ue_ue.AutomationTestSettings.md#__tid_automationtestsettings__)
- [\_\_tid\_Object\_\_](ue_ue.AutomationTestSettings.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AutomationTestSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AutomationTestSettings.md#executeubergraph)
- [GetClass](ue_ue.AutomationTestSettings.md#getclass)
- [GetName](ue_ue.AutomationTestSettings.md#getname)
- [GetOuter](ue_ue.AutomationTestSettings.md#getouter)
- [GetWorld](ue_ue.AutomationTestSettings.md#getworld)
- [Find](ue_ue.AutomationTestSettings.md#find)
- [Load](ue_ue.AutomationTestSettings.md#load)
- [StaticClass](ue_ue.AutomationTestSettings.md#staticclass)

## Constructors

### constructor

• **new AutomationTestSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AssetsToOpen

• **AssetsToOpen**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoftObjectPath`](ue_ue.SoftObjectPath.md)\>

___

### AutomationTestmap

• **AutomationTestmap**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### BlueprintEditorPromotionTest

• **BlueprintEditorPromotionTest**: [`BlueprintEditorPromotionSettings`](ue_ue.BlueprintEditorPromotionSettings.md)

___

### BuildPromotionTest

• **BuildPromotionTest**: [`BuildPromotionTestSettings`](ue_ue.BuildPromotionTestSettings.md)

___

### DefaultScreenshotResolution

• **DefaultScreenshotResolution**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### EditorPerformanceTestMaps

• **EditorPerformanceTestMaps**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditorMapPerformanceTestDefinition`](ue_ue.EditorMapPerformanceTestDefinition.md)\>

___

### EditorTestModules

• **EditorTestModules**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### EngineTestModules

• **EngineTestModules**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ExternalTools

• **ExternalTools**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ExternalToolDefinition`](ue_ue.ExternalToolDefinition.md)\>

___

### ImportExportTestDefinitions

• **ImportExportTestDefinitions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditorImportExportTestDefinition`](ue_ue.EditorImportExportTestDefinition.md)\>

___

### LaunchOnSettings

• **LaunchOnSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LaunchOnTestSettings`](ue_ue.LaunchOnTestSettings.md)\>

___

### MaterialEditorPromotionTest

• **MaterialEditorPromotionTest**: [`MaterialEditorPromotionSettings`](ue_ue.MaterialEditorPromotionSettings.md)

___

### ParticleEditorPromotionTest

• **ParticleEditorPromotionTest**: [`ParticleEditorPromotionSettings`](ue_ue.ParticleEditorPromotionSettings.md)

___

### TestLevelFolders

• **TestLevelFolders**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### \_\_tid\_AutomationTestSettings\_\_

• **\_\_tid\_AutomationTestSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AutomationTestSettings`](ue_ue.AutomationTestSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AutomationTestSettings`](ue_ue.AutomationTestSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AutomationTestSettings`](ue_ue.AutomationTestSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AutomationTestSettings`](ue_ue.AutomationTestSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
