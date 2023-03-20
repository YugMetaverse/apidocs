[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InternationalizationExportSettings

# Class: InternationalizationExportSettings

[ue/ue](../modules/ue_ue.md).InternationalizationExportSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`InternationalizationExportSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.InternationalizationExportSettings.md#constructor)

### Properties

- [ArchiveName](ue_ue.InternationalizationExportSettings.md#archivename)
- [CommandletClass](ue_ue.InternationalizationExportSettings.md#commandletclass)
- [CulturesToGenerate](ue_ue.InternationalizationExportSettings.md#culturestogenerate)
- [DestinationPath](ue_ue.InternationalizationExportSettings.md#destinationpath)
- [ManifestName](ue_ue.InternationalizationExportSettings.md#manifestname)
- [PortableObjectName](ue_ue.InternationalizationExportSettings.md#portableobjectname)
- [SourcePath](ue_ue.InternationalizationExportSettings.md#sourcepath)
- [\_\_tid\_InternationalizationExportSettings\_\_](ue_ue.InternationalizationExportSettings.md#__tid_internationalizationexportsettings__)
- [\_\_tid\_Object\_\_](ue_ue.InternationalizationExportSettings.md#__tid_object__)
- [bExportLoc](ue_ue.InternationalizationExportSettings.md#bexportloc)
- [bImportLoc](ue_ue.InternationalizationExportSettings.md#bimportloc)
- [bUseCultureDirectory](ue_ue.InternationalizationExportSettings.md#buseculturedirectory)

### Methods

- [CreateDefaultSubobject](ue_ue.InternationalizationExportSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InternationalizationExportSettings.md#executeubergraph)
- [GetClass](ue_ue.InternationalizationExportSettings.md#getclass)
- [GetName](ue_ue.InternationalizationExportSettings.md#getname)
- [GetOuter](ue_ue.InternationalizationExportSettings.md#getouter)
- [GetWorld](ue_ue.InternationalizationExportSettings.md#getworld)
- [Find](ue_ue.InternationalizationExportSettings.md#find)
- [Load](ue_ue.InternationalizationExportSettings.md#load)
- [StaticClass](ue_ue.InternationalizationExportSettings.md#staticclass)

## Constructors

### constructor

• **new InternationalizationExportSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ArchiveName

• **ArchiveName**: `string`

___

### CommandletClass

• **CommandletClass**: `string`

___

### CulturesToGenerate

• **CulturesToGenerate**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### DestinationPath

• **DestinationPath**: `string`

___

### ManifestName

• **ManifestName**: `string`

___

### PortableObjectName

• **PortableObjectName**: `string`

___

### SourcePath

• **SourcePath**: `string`

___

### \_\_tid\_InternationalizationExportSettings\_\_

• **\_\_tid\_InternationalizationExportSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bExportLoc

• **bExportLoc**: `boolean`

___

### bImportLoc

• **bImportLoc**: `boolean`

___

### bUseCultureDirectory

• **bUseCultureDirectory**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InternationalizationExportSettings`](ue_ue.InternationalizationExportSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InternationalizationExportSettings`](ue_ue.InternationalizationExportSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InternationalizationExportSettings`](ue_ue.InternationalizationExportSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InternationalizationExportSettings`](ue_ue.InternationalizationExportSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
