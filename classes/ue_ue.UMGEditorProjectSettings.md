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

#### Defined in

[ue/ue.d.ts:64475](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64475)

## Properties

### CategoriesToHide

• **CategoriesToHide**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:64480](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64480)

___

### DebugResolutions

• **DebugResolutions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DebugResolution`](ue_ue.DebugResolution.md)\>

#### Defined in

[ue/ue.d.ts:64484](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64484)

___

### DefaultCompilerOptions

• **DefaultCompilerOptions**: [`WidgetCompilerOptions`](ue_ue.WidgetCompilerOptions.md)

#### Defined in

[ue/ue.d.ts:64476](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64476)

___

### DefaultRootWidget

• **DefaultRootWidget**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:64483](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64483)

___

### DirectoryCompilerOptions

• **DirectoryCompilerOptions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DirectoryWidgetCompilerOptions`](ue_ue.DirectoryWidgetCompilerOptions.md)\>

#### Defined in

[ue/ue.d.ts:64477](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64477)

___

### Version

• **Version**: `number`

#### Defined in

[ue/ue.d.ts:64485](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64485)

___

### WidgetClassesToHide

• **WidgetClassesToHide**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoftClassPath`](ue_ue.SoftClassPath.md)\>

#### Defined in

[ue/ue.d.ts:64481](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64481)

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

#### Defined in

[ue/ue.d.ts:16950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16950)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_UMGEditorProjectSettings\_\_

• **\_\_tid\_UMGEditorProjectSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64492](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64492)

___

### bCookSlowConstructionWidgetTree

• **bCookSlowConstructionWidgetTree**: `boolean`

#### Defined in

[ue/ue.d.ts:64486](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64486)

___

### bShowWidgetsFromDeveloperContent

• **bShowWidgetsFromDeveloperContent**: `boolean`

#### Defined in

[ue/ue.d.ts:64479](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64479)

___

### bShowWidgetsFromEngineContent

• **bShowWidgetsFromEngineContent**: `boolean`

#### Defined in

[ue/ue.d.ts:64478](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64478)

___

### bUseWidgetTemplateSelector

• **bUseWidgetTemplateSelector**: `boolean`

#### Defined in

[ue/ue.d.ts:64482](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64482)

___

### bWidgetSupportsDynamicCreation

• **bWidgetSupportsDynamicCreation**: `boolean`

#### Defined in

[ue/ue.d.ts:64487](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64487)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:64489](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64489)

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

#### Defined in

[ue/ue.d.ts:64490](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64490)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)

#### Defined in

[ue/ue.d.ts:64488](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64488)
