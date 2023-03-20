[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / StaticMeshExporterFBX

# Class: StaticMeshExporterFBX

[ue/ue](../modules/ue_ue.md).StaticMeshExporterFBX

## Hierarchy

- [`ExporterFBX`](ue_ue.ExporterFBX.md)

  ↳ **`StaticMeshExporterFBX`**

## Table of contents

### Constructors

- [constructor](ue_ue.StaticMeshExporterFBX.md#constructor)

### Properties

- [ExportRootScope](ue_ue.StaticMeshExporterFBX.md#exportrootscope)
- [ExportTask](ue_ue.StaticMeshExporterFBX.md#exporttask)
- [FormatDescription](ue_ue.StaticMeshExporterFBX.md#formatdescription)
- [FormatExtension](ue_ue.StaticMeshExporterFBX.md#formatextension)
- [PreferredFormatIndex](ue_ue.StaticMeshExporterFBX.md#preferredformatindex)
- [SupportedClass](ue_ue.StaticMeshExporterFBX.md#supportedclass)
- [TextIndent](ue_ue.StaticMeshExporterFBX.md#textindent)
- [\_\_tid\_ExporterFBX\_\_](ue_ue.StaticMeshExporterFBX.md#__tid_exporterfbx__)
- [\_\_tid\_Exporter\_\_](ue_ue.StaticMeshExporterFBX.md#__tid_exporter__)
- [\_\_tid\_Object\_\_](ue_ue.StaticMeshExporterFBX.md#__tid_object__)
- [\_\_tid\_StaticMeshExporterFBX\_\_](ue_ue.StaticMeshExporterFBX.md#__tid_staticmeshexporterfbx__)
- [bForceFileOperations](ue_ue.StaticMeshExporterFBX.md#bforcefileoperations)
- [bSelectedOnly](ue_ue.StaticMeshExporterFBX.md#bselectedonly)
- [bText](ue_ue.StaticMeshExporterFBX.md#btext)

### Methods

- [CreateDefaultSubobject](ue_ue.StaticMeshExporterFBX.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.StaticMeshExporterFBX.md#executeubergraph)
- [GetClass](ue_ue.StaticMeshExporterFBX.md#getclass)
- [GetName](ue_ue.StaticMeshExporterFBX.md#getname)
- [GetOuter](ue_ue.StaticMeshExporterFBX.md#getouter)
- [GetWorld](ue_ue.StaticMeshExporterFBX.md#getworld)
- [ScriptRunAssetExportTask](ue_ue.StaticMeshExporterFBX.md#scriptrunassetexporttask)
- [Find](ue_ue.StaticMeshExporterFBX.md#find)
- [Load](ue_ue.StaticMeshExporterFBX.md#load)
- [RunAssetExportTask](ue_ue.StaticMeshExporterFBX.md#runassetexporttask)
- [RunAssetExportTasks](ue_ue.StaticMeshExporterFBX.md#runassetexporttasks)
- [StaticClass](ue_ue.StaticMeshExporterFBX.md#staticclass)

## Constructors

### constructor

• **new StaticMeshExporterFBX**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ExporterFBX](ue_ue.ExporterFBX.md).[constructor](ue_ue.ExporterFBX.md#constructor)

## Properties

### ExportRootScope

• **ExportRootScope**: [`Object`](ue_ue.Object.md)

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[ExportRootScope](ue_ue.ExporterFBX.md#exportrootscope)

___

### ExportTask

• **ExportTask**: [`AssetExportTask`](ue_ue.AssetExportTask.md)

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[ExportTask](ue_ue.ExporterFBX.md#exporttask)

___

### FormatDescription

• **FormatDescription**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[FormatDescription](ue_ue.ExporterFBX.md#formatdescription)

___

### FormatExtension

• **FormatExtension**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[FormatExtension](ue_ue.ExporterFBX.md#formatextension)

___

### PreferredFormatIndex

• **PreferredFormatIndex**: `number`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[PreferredFormatIndex](ue_ue.ExporterFBX.md#preferredformatindex)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[SupportedClass](ue_ue.ExporterFBX.md#supportedclass)

___

### TextIndent

• **TextIndent**: `number`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[TextIndent](ue_ue.ExporterFBX.md#textindent)

___

### \_\_tid\_ExporterFBX\_\_

• **\_\_tid\_ExporterFBX\_\_**: `boolean`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[__tid_ExporterFBX__](ue_ue.ExporterFBX.md#__tid_exporterfbx__)

___

### \_\_tid\_Exporter\_\_

• **\_\_tid\_Exporter\_\_**: `boolean`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[__tid_Exporter__](ue_ue.ExporterFBX.md#__tid_exporter__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[__tid_Object__](ue_ue.ExporterFBX.md#__tid_object__)

___

### \_\_tid\_StaticMeshExporterFBX\_\_

• **\_\_tid\_StaticMeshExporterFBX\_\_**: `boolean`

___

### bForceFileOperations

• **bForceFileOperations**: `boolean`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[bForceFileOperations](ue_ue.ExporterFBX.md#bforcefileoperations)

___

### bSelectedOnly

• **bSelectedOnly**: `boolean`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[bSelectedOnly](ue_ue.ExporterFBX.md#bselectedonly)

___

### bText

• **bText**: `boolean`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[bText](ue_ue.ExporterFBX.md#btext)

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

[ExporterFBX](ue_ue.ExporterFBX.md).[CreateDefaultSubobject](ue_ue.ExporterFBX.md#createdefaultsubobject)

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

[ExporterFBX](ue_ue.ExporterFBX.md).[ExecuteUbergraph](ue_ue.ExporterFBX.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[GetClass](ue_ue.ExporterFBX.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[GetName](ue_ue.ExporterFBX.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[GetOuter](ue_ue.ExporterFBX.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[GetWorld](ue_ue.ExporterFBX.md#getworld)

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

[ExporterFBX](ue_ue.ExporterFBX.md).[ScriptRunAssetExportTask](ue_ue.ExporterFBX.md#scriptrunassetexporttask)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`StaticMeshExporterFBX`](ue_ue.StaticMeshExporterFBX.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`StaticMeshExporterFBX`](ue_ue.StaticMeshExporterFBX.md)

#### Overrides

[ExporterFBX](ue_ue.ExporterFBX.md).[Find](ue_ue.ExporterFBX.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`StaticMeshExporterFBX`](ue_ue.StaticMeshExporterFBX.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`StaticMeshExporterFBX`](ue_ue.StaticMeshExporterFBX.md)

#### Overrides

[ExporterFBX](ue_ue.ExporterFBX.md).[Load](ue_ue.ExporterFBX.md#load)

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

[ExporterFBX](ue_ue.ExporterFBX.md).[RunAssetExportTask](ue_ue.ExporterFBX.md#runassetexporttask)

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

[ExporterFBX](ue_ue.ExporterFBX.md).[RunAssetExportTasks](ue_ue.ExporterFBX.md#runassetexporttasks)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ExporterFBX](ue_ue.ExporterFBX.md).[StaticClass](ue_ue.ExporterFBX.md#staticclass)
