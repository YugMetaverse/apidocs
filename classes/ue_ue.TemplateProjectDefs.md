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

#### Defined in

[ue/ue.d.ts:30603](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30603)

## Properties

### AssetTypes

• **AssetTypes**: `string`

#### Defined in

[ue/ue.d.ts:30614](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30614)

___

### Categories

• **Categories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:30612](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30612)

___

### ClassTypes

• **ClassTypes**: `string`

#### Defined in

[ue/ue.d.ts:30613](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30613)

___

### EditDetailLevelPreference

• **EditDetailLevelPreference**: [`EFeaturePackDetailLevel`](../enums/ue_ue.EFeaturePackDetailLevel.md)

#### Defined in

[ue/ue.d.ts:30620](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30620)

___

### FilenameReplacements

• **FilenameReplacements**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TemplateReplacement`](ue_ue.TemplateReplacement.md)\>

#### Defined in

[ue/ue.d.ts:30609](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30609)

___

### FilesToIgnore

• **FilesToIgnore**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:30607](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30607)

___

### FolderRenames

• **FolderRenames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TemplateFolderRename`](ue_ue.TemplateFolderRename.md)\>

#### Defined in

[ue/ue.d.ts:30608](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30608)

___

### FoldersToIgnore

• **FoldersToIgnore**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:30606](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30606)

___

### HiddenSettings

• **HiddenSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ETemplateSetting`](../enums/ue_ue.ETemplateSetting.md)\>

#### Defined in

[ue/ue.d.ts:30618](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30618)

___

### LocalizedDescriptions

• **LocalizedDescriptions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LocalizedTemplateString`](ue_ue.LocalizedTemplateString.md)\>

#### Defined in

[ue/ue.d.ts:30605](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30605)

___

### LocalizedDisplayNames

• **LocalizedDisplayNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LocalizedTemplateString`](ue_ue.LocalizedTemplateString.md)\>

#### Defined in

[ue/ue.d.ts:30604](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30604)

___

### PacksToInclude

• **PacksToInclude**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:30619](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30619)

___

### ReplacementsInFiles

• **ReplacementsInFiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TemplateReplacement`](ue_ue.TemplateReplacement.md)\>

#### Defined in

[ue/ue.d.ts:30610](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30610)

___

### SharedContentPacks

• **SharedContentPacks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FeaturePackLevelSet`](ue_ue.FeaturePackLevelSet.md)\>

#### Defined in

[ue/ue.d.ts:30621](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30621)

___

### SortKey

• **SortKey**: `string`

#### Defined in

[ue/ue.d.ts:30611](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30611)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_TemplateProjectDefs\_\_

• **\_\_tid\_TemplateProjectDefs\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:30626](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30626)

___

### bAllowProjectCreation

• **bAllowProjectCreation**: `boolean`

#### Defined in

[ue/ue.d.ts:30615](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30615)

___

### bIsBlank

• **bIsBlank**: `boolean`

#### Defined in

[ue/ue.d.ts:30617](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30617)

___

### bIsEnterprise

• **bIsEnterprise**: `boolean`

#### Defined in

[ue/ue.d.ts:30616](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30616)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:30623](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30623)

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

#### Defined in

[ue/ue.d.ts:30624](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30624)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:30622](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30622)
