[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TemplateProjectDefs

# Class: TemplateProjectDefs

[ue/ue](../modules/ue_ue.md).TemplateProjectDefs

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`TemplateProjectDefs`**

  ↳↳ [`DefaultTemplateProjectDefs`](ue_ue.DefaultTemplateProjectDefs.md)

## Table of contents

### Constructors

- [constructor](ue_ue.TemplateProjectDefs.md#constructor)

### Properties

- [AssetTypes](ue_ue.TemplateProjectDefs.md#assettypes)
- [Categories](ue_ue.TemplateProjectDefs.md#categories)
- [ClassTypes](ue_ue.TemplateProjectDefs.md#classtypes)
- [EditDetailLevelPreference](ue_ue.TemplateProjectDefs.md#editdetaillevelpreference)
- [FilenameReplacements](ue_ue.TemplateProjectDefs.md#filenamereplacements)
- [FilesToIgnore](ue_ue.TemplateProjectDefs.md#filestoignore)
- [FolderRenames](ue_ue.TemplateProjectDefs.md#folderrenames)
- [FoldersToIgnore](ue_ue.TemplateProjectDefs.md#folderstoignore)
- [HiddenSettings](ue_ue.TemplateProjectDefs.md#hiddensettings)
- [LocalizedDescriptions](ue_ue.TemplateProjectDefs.md#localizeddescriptions)
- [LocalizedDisplayNames](ue_ue.TemplateProjectDefs.md#localizeddisplaynames)
- [PacksToInclude](ue_ue.TemplateProjectDefs.md#packstoinclude)
- [ReplacementsInFiles](ue_ue.TemplateProjectDefs.md#replacementsinfiles)
- [SharedContentPacks](ue_ue.TemplateProjectDefs.md#sharedcontentpacks)
- [SortKey](ue_ue.TemplateProjectDefs.md#sortkey)
- [\_\_tid\_Object\_\_](ue_ue.TemplateProjectDefs.md#__tid_object__)
- [\_\_tid\_TemplateProjectDefs\_\_](ue_ue.TemplateProjectDefs.md#__tid_templateprojectdefs__)
- [bAllowProjectCreation](ue_ue.TemplateProjectDefs.md#ballowprojectcreation)
- [bIsBlank](ue_ue.TemplateProjectDefs.md#bisblank)
- [bIsEnterprise](ue_ue.TemplateProjectDefs.md#bisenterprise)

### Methods

- [CreateDefaultSubobject](ue_ue.TemplateProjectDefs.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TemplateProjectDefs.md#executeubergraph)
- [GetClass](ue_ue.TemplateProjectDefs.md#getclass)
- [GetName](ue_ue.TemplateProjectDefs.md#getname)
- [GetOuter](ue_ue.TemplateProjectDefs.md#getouter)
- [GetWorld](ue_ue.TemplateProjectDefs.md#getworld)
- [Find](ue_ue.TemplateProjectDefs.md#find)
- [Load](ue_ue.TemplateProjectDefs.md#load)
- [StaticClass](ue_ue.TemplateProjectDefs.md#staticclass)

## Constructors

### constructor

• **new TemplateProjectDefs**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AssetTypes

• **AssetTypes**: `string`

___

### Categories

• **Categories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ClassTypes

• **ClassTypes**: `string`

___

### EditDetailLevelPreference

• **EditDetailLevelPreference**: [`EFeaturePackDetailLevel`](../enums/ue_ue.EFeaturePackDetailLevel.md)

___

### FilenameReplacements

• **FilenameReplacements**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TemplateReplacement`](ue_ue.TemplateReplacement.md)\>

___

### FilesToIgnore

• **FilesToIgnore**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### FolderRenames

• **FolderRenames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TemplateFolderRename`](ue_ue.TemplateFolderRename.md)\>

___

### FoldersToIgnore

• **FoldersToIgnore**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### HiddenSettings

• **HiddenSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ETemplateSetting`](../enums/ue_ue.ETemplateSetting.md)\>

___

### LocalizedDescriptions

• **LocalizedDescriptions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LocalizedTemplateString`](ue_ue.LocalizedTemplateString.md)\>

___

### LocalizedDisplayNames

• **LocalizedDisplayNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LocalizedTemplateString`](ue_ue.LocalizedTemplateString.md)\>

___

### PacksToInclude

• **PacksToInclude**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ReplacementsInFiles

• **ReplacementsInFiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TemplateReplacement`](ue_ue.TemplateReplacement.md)\>

___

### SharedContentPacks

• **SharedContentPacks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FeaturePackLevelSet`](ue_ue.FeaturePackLevelSet.md)\>

___

### SortKey

• **SortKey**: `string`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_TemplateProjectDefs\_\_

• **\_\_tid\_TemplateProjectDefs\_\_**: `boolean`

___

### bAllowProjectCreation

• **bAllowProjectCreation**: `boolean`

___

### bIsBlank

• **bIsBlank**: `boolean`

___

### bIsEnterprise

• **bIsEnterprise**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TemplateProjectDefs`](ue_ue.TemplateProjectDefs.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TemplateProjectDefs`](ue_ue.TemplateProjectDefs.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TemplateProjectDefs`](ue_ue.TemplateProjectDefs.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TemplateProjectDefs`](ue_ue.TemplateProjectDefs.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
