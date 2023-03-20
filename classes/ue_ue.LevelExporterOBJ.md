[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelExporterOBJ

# Class: LevelExporterOBJ

[ue/ue](../modules/ue_ue.md).LevelExporterOBJ

## Hierarchy

- [`Exporter`](ue_ue.Exporter.md)

  ↳ **`LevelExporterOBJ`**

## Table of contents

### Constructors

- [constructor](ue_ue.LevelExporterOBJ.md#constructor)

### Properties

- [ExportRootScope](ue_ue.LevelExporterOBJ.md#exportrootscope)
- [ExportTask](ue_ue.LevelExporterOBJ.md#exporttask)
- [FormatDescription](ue_ue.LevelExporterOBJ.md#formatdescription)
- [FormatExtension](ue_ue.LevelExporterOBJ.md#formatextension)
- [PreferredFormatIndex](ue_ue.LevelExporterOBJ.md#preferredformatindex)
- [SupportedClass](ue_ue.LevelExporterOBJ.md#supportedclass)
- [TextIndent](ue_ue.LevelExporterOBJ.md#textindent)
- [\_\_tid\_Exporter\_\_](ue_ue.LevelExporterOBJ.md#__tid_exporter__)
- [\_\_tid\_LevelExporterOBJ\_\_](ue_ue.LevelExporterOBJ.md#__tid_levelexporterobj__)
- [\_\_tid\_Object\_\_](ue_ue.LevelExporterOBJ.md#__tid_object__)
- [bForceFileOperations](ue_ue.LevelExporterOBJ.md#bforcefileoperations)
- [bSelectedOnly](ue_ue.LevelExporterOBJ.md#bselectedonly)
- [bText](ue_ue.LevelExporterOBJ.md#btext)

### Methods

- [CreateDefaultSubobject](ue_ue.LevelExporterOBJ.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LevelExporterOBJ.md#executeubergraph)
- [GetClass](ue_ue.LevelExporterOBJ.md#getclass)
- [GetName](ue_ue.LevelExporterOBJ.md#getname)
- [GetOuter](ue_ue.LevelExporterOBJ.md#getouter)
- [GetWorld](ue_ue.LevelExporterOBJ.md#getworld)
- [ScriptRunAssetExportTask](ue_ue.LevelExporterOBJ.md#scriptrunassetexporttask)
- [Find](ue_ue.LevelExporterOBJ.md#find)
- [Load](ue_ue.LevelExporterOBJ.md#load)
- [RunAssetExportTask](ue_ue.LevelExporterOBJ.md#runassetexporttask)
- [RunAssetExportTasks](ue_ue.LevelExporterOBJ.md#runassetexporttasks)
- [StaticClass](ue_ue.LevelExporterOBJ.md#staticclass)

## Constructors

### constructor

• **new LevelExporterOBJ**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Exporter](ue_ue.Exporter.md).[constructor](ue_ue.Exporter.md#constructor)

## Properties

### ExportRootScope

• **ExportRootScope**: [`Object`](ue_ue.Object.md)

#### Inherited from

[Exporter](ue_ue.Exporter.md).[ExportRootScope](ue_ue.Exporter.md#exportrootscope)

___

### ExportTask

• **ExportTask**: [`AssetExportTask`](ue_ue.AssetExportTask.md)

#### Inherited from

[Exporter](ue_ue.Exporter.md).[ExportTask](ue_ue.Exporter.md#exporttask)

___

### FormatDescription

• **FormatDescription**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Exporter](ue_ue.Exporter.md).[FormatDescription](ue_ue.Exporter.md#formatdescription)

___

### FormatExtension

• **FormatExtension**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Exporter](ue_ue.Exporter.md).[FormatExtension](ue_ue.Exporter.md#formatextension)

___

### PreferredFormatIndex

• **PreferredFormatIndex**: `number`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[PreferredFormatIndex](ue_ue.Exporter.md#preferredformatindex)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Exporter](ue_ue.Exporter.md).[SupportedClass](ue_ue.Exporter.md#supportedclass)

___

### TextIndent

• **TextIndent**: `number`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[TextIndent](ue_ue.Exporter.md#textindent)

___

### \_\_tid\_Exporter\_\_

• **\_\_tid\_Exporter\_\_**: `boolean`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[__tid_Exporter__](ue_ue.Exporter.md#__tid_exporter__)

___

### \_\_tid\_LevelExporterOBJ\_\_

• **\_\_tid\_LevelExporterOBJ\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[__tid_Object__](ue_ue.Exporter.md#__tid_object__)

___

### bForceFileOperations

• **bForceFileOperations**: `boolean`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[bForceFileOperations](ue_ue.Exporter.md#bforcefileoperations)

___

### bSelectedOnly

• **bSelectedOnly**: `boolean`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[bSelectedOnly](ue_ue.Exporter.md#bselectedonly)

___

### bText

• **bText**: `boolean`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[bText](ue_ue.Exporter.md#btext)

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

[Exporter](ue_ue.Exporter.md).[CreateDefaultSubobject](ue_ue.Exporter.md#createdefaultsubobject)

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

[Exporter](ue_ue.Exporter.md).[ExecuteUbergraph](ue_ue.Exporter.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Exporter](ue_ue.Exporter.md).[GetClass](ue_ue.Exporter.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[GetName](ue_ue.Exporter.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Exporter](ue_ue.Exporter.md).[GetOuter](ue_ue.Exporter.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Exporter](ue_ue.Exporter.md).[GetWorld](ue_ue.Exporter.md#getworld)

___

### ScriptRunAssetExportTask

▸ **ScriptRunAssetExportTask**(`Task`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Task` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AssetExportTask`](ue_ue.AssetExportTask.md)\> |

#### Returns

`boolean`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[ScriptRunAssetExportTask](ue_ue.Exporter.md#scriptrunassetexporttask)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LevelExporterOBJ`](ue_ue.LevelExporterOBJ.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LevelExporterOBJ`](ue_ue.LevelExporterOBJ.md)

#### Overrides

[Exporter](ue_ue.Exporter.md).[Find](ue_ue.Exporter.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`LevelExporterOBJ`](ue_ue.LevelExporterOBJ.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LevelExporterOBJ`](ue_ue.LevelExporterOBJ.md)

#### Overrides

[Exporter](ue_ue.Exporter.md).[Load](ue_ue.Exporter.md#load)

___

### RunAssetExportTask

▸ `Static` **RunAssetExportTask**(`Task`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Task` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AssetExportTask`](ue_ue.AssetExportTask.md)\> |

#### Returns

`boolean`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[RunAssetExportTask](ue_ue.Exporter.md#runassetexporttask)

___

### RunAssetExportTasks

▸ `Static` **RunAssetExportTasks**(`ExportTasks`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ExportTasks` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetExportTask`](ue_ue.AssetExportTask.md)\> |

#### Returns

`boolean`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[RunAssetExportTasks](ue_ue.Exporter.md#runassetexporttasks)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Exporter](ue_ue.Exporter.md).[StaticClass](ue_ue.Exporter.md#staticclass)
