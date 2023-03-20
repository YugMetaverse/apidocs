[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UMGEditorProjectSettings

# Class: UMGEditorProjectSettings

[ue/ue](../modules/ue_ue.md).UMGEditorProjectSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`UMGEditorProjectSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.UMGEditorProjectSettings.md#constructor)

### Properties

- [CategoriesToHide](ue_ue.UMGEditorProjectSettings.md#categoriestohide)
- [DebugResolutions](ue_ue.UMGEditorProjectSettings.md#debugresolutions)
- [DefaultCompilerOptions](ue_ue.UMGEditorProjectSettings.md#defaultcompileroptions)
- [DefaultRootWidget](ue_ue.UMGEditorProjectSettings.md#defaultrootwidget)
- [DirectoryCompilerOptions](ue_ue.UMGEditorProjectSettings.md#directorycompileroptions)
- [Version](ue_ue.UMGEditorProjectSettings.md#version)
- [WidgetClassesToHide](ue_ue.UMGEditorProjectSettings.md#widgetclassestohide)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.UMGEditorProjectSettings.md#__tid_developersettings__)
- [\_\_tid\_Object\_\_](ue_ue.UMGEditorProjectSettings.md#__tid_object__)
- [\_\_tid\_UMGEditorProjectSettings\_\_](ue_ue.UMGEditorProjectSettings.md#__tid_umgeditorprojectsettings__)
- [bCookSlowConstructionWidgetTree](ue_ue.UMGEditorProjectSettings.md#bcookslowconstructionwidgettree)
- [bShowWidgetsFromDeveloperContent](ue_ue.UMGEditorProjectSettings.md#bshowwidgetsfromdevelopercontent)
- [bShowWidgetsFromEngineContent](ue_ue.UMGEditorProjectSettings.md#bshowwidgetsfromenginecontent)
- [bUseWidgetTemplateSelector](ue_ue.UMGEditorProjectSettings.md#busewidgettemplateselector)
- [bWidgetSupportsDynamicCreation](ue_ue.UMGEditorProjectSettings.md#bwidgetsupportsdynamiccreation)

### Methods

- [CreateDefaultSubobject](ue_ue.UMGEditorProjectSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UMGEditorProjectSettings.md#executeubergraph)
- [GetClass](ue_ue.UMGEditorProjectSettings.md#getclass)
- [GetName](ue_ue.UMGEditorProjectSettings.md#getname)
- [GetOuter](ue_ue.UMGEditorProjectSettings.md#getouter)
- [GetWorld](ue_ue.UMGEditorProjectSettings.md#getworld)
- [Find](ue_ue.UMGEditorProjectSettings.md#find)
- [Load](ue_ue.UMGEditorProjectSettings.md#load)
- [StaticClass](ue_ue.UMGEditorProjectSettings.md#staticclass)

## Constructors

### constructor

• **new UMGEditorProjectSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

## Properties

### CategoriesToHide

• **CategoriesToHide**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### DebugResolutions

• **DebugResolutions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DebugResolution`](ue_ue.DebugResolution.md)\>

___

### DefaultCompilerOptions

• **DefaultCompilerOptions**: [`WidgetCompilerOptions`](ue_ue.WidgetCompilerOptions.md)

___

### DefaultRootWidget

• **DefaultRootWidget**: [`Class`](ue_ue.Class.md)

___

### DirectoryCompilerOptions

• **DirectoryCompilerOptions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryWidgetCompilerOptions`](ue_ue.DirectoryWidgetCompilerOptions.md)\>

___

### Version

• **Version**: `number`

___

### WidgetClassesToHide

• **WidgetClassesToHide**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoftClassPath`](ue_ue.SoftClassPath.md)\>

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

___

### \_\_tid\_UMGEditorProjectSettings\_\_

• **\_\_tid\_UMGEditorProjectSettings\_\_**: `boolean`

___

### bCookSlowConstructionWidgetTree

• **bCookSlowConstructionWidgetTree**: `boolean`

___

### bShowWidgetsFromDeveloperContent

• **bShowWidgetsFromDeveloperContent**: `boolean`

___

### bShowWidgetsFromEngineContent

• **bShowWidgetsFromEngineContent**: `boolean`

___

### bUseWidgetTemplateSelector

• **bUseWidgetTemplateSelector**: `boolean`

___

### bWidgetSupportsDynamicCreation

• **bWidgetSupportsDynamicCreation**: `boolean`

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[CreateDefaultSubobject](ue_ue.DeveloperSettings.md#createdefaultsubobject)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UMGEditorProjectSettings`](ue_ue.UMGEditorProjectSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UMGEditorProjectSettings`](ue_ue.UMGEditorProjectSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`UMGEditorProjectSettings`](ue_ue.UMGEditorProjectSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UMGEditorProjectSettings`](ue_ue.UMGEditorProjectSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
