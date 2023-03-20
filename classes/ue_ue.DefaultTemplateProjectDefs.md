[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DefaultTemplateProjectDefs

# Class: DefaultTemplateProjectDefs

[ue/ue](../modules/ue_ue.md).DefaultTemplateProjectDefs

## Hierarchy

- [`TemplateProjectDefs`](ue_ue.TemplateProjectDefs.md)

  ↳ **`DefaultTemplateProjectDefs`**

## Table of contents

### Constructors

- [constructor](ue_ue.DefaultTemplateProjectDefs.md#constructor)

### Properties

- [AssetTypes](ue_ue.DefaultTemplateProjectDefs.md#assettypes)
- [Categories](ue_ue.DefaultTemplateProjectDefs.md#categories)
- [ClassTypes](ue_ue.DefaultTemplateProjectDefs.md#classtypes)
- [EditDetailLevelPreference](ue_ue.DefaultTemplateProjectDefs.md#editdetaillevelpreference)
- [FilenameReplacements](ue_ue.DefaultTemplateProjectDefs.md#filenamereplacements)
- [FilesToIgnore](ue_ue.DefaultTemplateProjectDefs.md#filestoignore)
- [FolderRenames](ue_ue.DefaultTemplateProjectDefs.md#folderrenames)
- [FoldersToIgnore](ue_ue.DefaultTemplateProjectDefs.md#folderstoignore)
- [HiddenSettings](ue_ue.DefaultTemplateProjectDefs.md#hiddensettings)
- [LocalizedDescriptions](ue_ue.DefaultTemplateProjectDefs.md#localizeddescriptions)
- [LocalizedDisplayNames](ue_ue.DefaultTemplateProjectDefs.md#localizeddisplaynames)
- [PacksToInclude](ue_ue.DefaultTemplateProjectDefs.md#packstoinclude)
- [ReplacementsInFiles](ue_ue.DefaultTemplateProjectDefs.md#replacementsinfiles)
- [SharedContentPacks](ue_ue.DefaultTemplateProjectDefs.md#sharedcontentpacks)
- [SortKey](ue_ue.DefaultTemplateProjectDefs.md#sortkey)
- [\_\_tid\_DefaultTemplateProjectDefs\_\_](ue_ue.DefaultTemplateProjectDefs.md#__tid_defaulttemplateprojectdefs__)
- [\_\_tid\_Object\_\_](ue_ue.DefaultTemplateProjectDefs.md#__tid_object__)
- [\_\_tid\_TemplateProjectDefs\_\_](ue_ue.DefaultTemplateProjectDefs.md#__tid_templateprojectdefs__)
- [bAllowProjectCreation](ue_ue.DefaultTemplateProjectDefs.md#ballowprojectcreation)
- [bIsBlank](ue_ue.DefaultTemplateProjectDefs.md#bisblank)
- [bIsEnterprise](ue_ue.DefaultTemplateProjectDefs.md#bisenterprise)

### Methods

- [CreateDefaultSubobject](ue_ue.DefaultTemplateProjectDefs.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DefaultTemplateProjectDefs.md#executeubergraph)
- [GetClass](ue_ue.DefaultTemplateProjectDefs.md#getclass)
- [GetName](ue_ue.DefaultTemplateProjectDefs.md#getname)
- [GetOuter](ue_ue.DefaultTemplateProjectDefs.md#getouter)
- [GetWorld](ue_ue.DefaultTemplateProjectDefs.md#getworld)
- [Find](ue_ue.DefaultTemplateProjectDefs.md#find)
- [Load](ue_ue.DefaultTemplateProjectDefs.md#load)
- [StaticClass](ue_ue.DefaultTemplateProjectDefs.md#staticclass)

## Constructors

### constructor

• **new DefaultTemplateProjectDefs**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[constructor](ue_ue.TemplateProjectDefs.md#constructor)

#### Defined in

[ue/ue.d.ts:30630](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30630)

## Properties

### AssetTypes

• **AssetTypes**: `string`

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[AssetTypes](ue_ue.TemplateProjectDefs.md#assettypes)

#### Defined in

[ue/ue.d.ts:30614](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30614)

___

### Categories

• **Categories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[Categories](ue_ue.TemplateProjectDefs.md#categories)

#### Defined in

[ue/ue.d.ts:30612](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30612)

___

### ClassTypes

• **ClassTypes**: `string`

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[ClassTypes](ue_ue.TemplateProjectDefs.md#classtypes)

#### Defined in

[ue/ue.d.ts:30613](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30613)

___

### EditDetailLevelPreference

• **EditDetailLevelPreference**: [`EFeaturePackDetailLevel`](../enums/ue_ue.EFeaturePackDetailLevel.md)

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[EditDetailLevelPreference](ue_ue.TemplateProjectDefs.md#editdetaillevelpreference)

#### Defined in

[ue/ue.d.ts:30620](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30620)

___

### FilenameReplacements

• **FilenameReplacements**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TemplateReplacement`](ue_ue.TemplateReplacement.md)\>

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[FilenameReplacements](ue_ue.TemplateProjectDefs.md#filenamereplacements)

#### Defined in

[ue/ue.d.ts:30609](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30609)

___

### FilesToIgnore

• **FilesToIgnore**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[FilesToIgnore](ue_ue.TemplateProjectDefs.md#filestoignore)

#### Defined in

[ue/ue.d.ts:30607](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30607)

___

### FolderRenames

• **FolderRenames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TemplateFolderRename`](ue_ue.TemplateFolderRename.md)\>

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[FolderRenames](ue_ue.TemplateProjectDefs.md#folderrenames)

#### Defined in

[ue/ue.d.ts:30608](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30608)

___

### FoldersToIgnore

• **FoldersToIgnore**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[FoldersToIgnore](ue_ue.TemplateProjectDefs.md#folderstoignore)

#### Defined in

[ue/ue.d.ts:30606](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30606)

___

### HiddenSettings

• **HiddenSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ETemplateSetting`](../enums/ue_ue.ETemplateSetting.md)\>

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[HiddenSettings](ue_ue.TemplateProjectDefs.md#hiddensettings)

#### Defined in

[ue/ue.d.ts:30618](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30618)

___

### LocalizedDescriptions

• **LocalizedDescriptions**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LocalizedTemplateString`](ue_ue.LocalizedTemplateString.md)\>

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[LocalizedDescriptions](ue_ue.TemplateProjectDefs.md#localizeddescriptions)

#### Defined in

[ue/ue.d.ts:30605](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30605)

___

### LocalizedDisplayNames

• **LocalizedDisplayNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LocalizedTemplateString`](ue_ue.LocalizedTemplateString.md)\>

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[LocalizedDisplayNames](ue_ue.TemplateProjectDefs.md#localizeddisplaynames)

#### Defined in

[ue/ue.d.ts:30604](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30604)

___

### PacksToInclude

• **PacksToInclude**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[PacksToInclude](ue_ue.TemplateProjectDefs.md#packstoinclude)

#### Defined in

[ue/ue.d.ts:30619](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30619)

___

### ReplacementsInFiles

• **ReplacementsInFiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TemplateReplacement`](ue_ue.TemplateReplacement.md)\>

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[ReplacementsInFiles](ue_ue.TemplateProjectDefs.md#replacementsinfiles)

#### Defined in

[ue/ue.d.ts:30610](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30610)

___

### SharedContentPacks

• **SharedContentPacks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FeaturePackLevelSet`](ue_ue.FeaturePackLevelSet.md)\>

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[SharedContentPacks](ue_ue.TemplateProjectDefs.md#sharedcontentpacks)

#### Defined in

[ue/ue.d.ts:30621](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30621)

___

### SortKey

• **SortKey**: `string`

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[SortKey](ue_ue.TemplateProjectDefs.md#sortkey)

#### Defined in

[ue/ue.d.ts:30611](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30611)

___

### \_\_tid\_DefaultTemplateProjectDefs\_\_

• **\_\_tid\_DefaultTemplateProjectDefs\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:30635](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30635)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[__tid_Object__](ue_ue.TemplateProjectDefs.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_TemplateProjectDefs\_\_

• **\_\_tid\_TemplateProjectDefs\_\_**: `boolean`

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[__tid_TemplateProjectDefs__](ue_ue.TemplateProjectDefs.md#__tid_templateprojectdefs__)

#### Defined in

[ue/ue.d.ts:30626](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30626)

___

### bAllowProjectCreation

• **bAllowProjectCreation**: `boolean`

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[bAllowProjectCreation](ue_ue.TemplateProjectDefs.md#ballowprojectcreation)

#### Defined in

[ue/ue.d.ts:30615](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30615)

___

### bIsBlank

• **bIsBlank**: `boolean`

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[bIsBlank](ue_ue.TemplateProjectDefs.md#bisblank)

#### Defined in

[ue/ue.d.ts:30617](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30617)

___

### bIsEnterprise

• **bIsEnterprise**: `boolean`

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[bIsEnterprise](ue_ue.TemplateProjectDefs.md#bisenterprise)

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

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[CreateDefaultSubobject](ue_ue.TemplateProjectDefs.md#createdefaultsubobject)

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

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[ExecuteUbergraph](ue_ue.TemplateProjectDefs.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[GetClass](ue_ue.TemplateProjectDefs.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[GetName](ue_ue.TemplateProjectDefs.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[GetOuter](ue_ue.TemplateProjectDefs.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[GetWorld](ue_ue.TemplateProjectDefs.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DefaultTemplateProjectDefs`](ue_ue.DefaultTemplateProjectDefs.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DefaultTemplateProjectDefs`](ue_ue.DefaultTemplateProjectDefs.md)

#### Overrides

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[Find](ue_ue.TemplateProjectDefs.md#find)

#### Defined in

[ue/ue.d.ts:30632](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30632)

___

### Load

▸ `Static` **Load**(`InName`): [`DefaultTemplateProjectDefs`](ue_ue.DefaultTemplateProjectDefs.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DefaultTemplateProjectDefs`](ue_ue.DefaultTemplateProjectDefs.md)

#### Overrides

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[Load](ue_ue.TemplateProjectDefs.md#load)

#### Defined in

[ue/ue.d.ts:30633](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30633)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[TemplateProjectDefs](ue_ue.TemplateProjectDefs.md).[StaticClass](ue_ue.TemplateProjectDefs.md#staticclass)

#### Defined in

[ue/ue.d.ts:30631](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L30631)
