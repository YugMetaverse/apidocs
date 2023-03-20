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

#### Defined in

[ue/ue.d.ts:62096](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62096)

## Properties

### ExportRootScope

• **ExportRootScope**: [`Object`](ue_ue.Object.md)

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[ExportRootScope](ue_ue.ExporterFBX.md#exportrootscope)

#### Defined in

[ue/ue.d.ts:20322](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20322)

___

### ExportTask

• **ExportTask**: [`AssetExportTask`](ue_ue.AssetExportTask.md)

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[ExportTask](ue_ue.ExporterFBX.md#exporttask)

#### Defined in

[ue/ue.d.ts:20330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20330)

___

### FormatDescription

• **FormatDescription**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[FormatDescription](ue_ue.ExporterFBX.md#formatdescription)

#### Defined in

[ue/ue.d.ts:20324](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20324)

___

### FormatExtension

• **FormatExtension**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[FormatExtension](ue_ue.ExporterFBX.md#formatextension)

#### Defined in

[ue/ue.d.ts:20323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20323)

___

### PreferredFormatIndex

• **PreferredFormatIndex**: `number`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[PreferredFormatIndex](ue_ue.ExporterFBX.md#preferredformatindex)

#### Defined in

[ue/ue.d.ts:20325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20325)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[SupportedClass](ue_ue.ExporterFBX.md#supportedclass)

#### Defined in

[ue/ue.d.ts:20321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20321)

___

### TextIndent

• **TextIndent**: `number`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[TextIndent](ue_ue.ExporterFBX.md#textindent)

#### Defined in

[ue/ue.d.ts:20326](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20326)

___

### \_\_tid\_ExporterFBX\_\_

• **\_\_tid\_ExporterFBX\_\_**: `boolean`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[__tid_ExporterFBX__](ue_ue.ExporterFBX.md#__tid_exporterfbx__)

#### Defined in

[ue/ue.d.ts:20347](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20347)

___

### \_\_tid\_Exporter\_\_

• **\_\_tid\_Exporter\_\_**: `boolean`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[__tid_Exporter__](ue_ue.ExporterFBX.md#__tid_exporter__)

#### Defined in

[ue/ue.d.ts:20338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20338)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[__tid_Object__](ue_ue.ExporterFBX.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_StaticMeshExporterFBX\_\_

• **\_\_tid\_StaticMeshExporterFBX\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:62101](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62101)

___

### bForceFileOperations

• **bForceFileOperations**: `boolean`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[bForceFileOperations](ue_ue.ExporterFBX.md#bforcefileoperations)

#### Defined in

[ue/ue.d.ts:20329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20329)

___

### bSelectedOnly

• **bSelectedOnly**: `boolean`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[bSelectedOnly](ue_ue.ExporterFBX.md#bselectedonly)

#### Defined in

[ue/ue.d.ts:20328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20328)

___

### bText

• **bText**: `boolean`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[bText](ue_ue.ExporterFBX.md#btext)

#### Defined in

[ue/ue.d.ts:20327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20327)

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

[ExporterFBX](ue_ue.ExporterFBX.md).[ExecuteUbergraph](ue_ue.ExporterFBX.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[GetClass](ue_ue.ExporterFBX.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[GetName](ue_ue.ExporterFBX.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[GetOuter](ue_ue.ExporterFBX.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ExporterFBX](ue_ue.ExporterFBX.md).[GetWorld](ue_ue.ExporterFBX.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:20331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20331)

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

#### Defined in

[ue/ue.d.ts:62098](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62098)

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

#### Defined in

[ue/ue.d.ts:62099](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62099)

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

#### Defined in

[ue/ue.d.ts:20332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20332)

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

#### Defined in

[ue/ue.d.ts:20333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20333)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ExporterFBX](ue_ue.ExporterFBX.md).[StaticClass](ue_ue.ExporterFBX.md#staticclass)

#### Defined in

[ue/ue.d.ts:62097](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62097)
