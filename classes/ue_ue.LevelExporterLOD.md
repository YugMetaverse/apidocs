[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelExporterLOD

# Class: LevelExporterLOD

[ue/ue](../modules/ue_ue.md).LevelExporterLOD

## Hierarchy

- [`Exporter`](ue_ue.Exporter.md)

  ↳ **`LevelExporterLOD`**

## Table of contents

### Constructors

- [constructor](ue_ue.LevelExporterLOD.md#constructor)

### Properties

- [ExportRootScope](ue_ue.LevelExporterLOD.md#exportrootscope)
- [ExportTask](ue_ue.LevelExporterLOD.md#exporttask)
- [FormatDescription](ue_ue.LevelExporterLOD.md#formatdescription)
- [FormatExtension](ue_ue.LevelExporterLOD.md#formatextension)
- [PreferredFormatIndex](ue_ue.LevelExporterLOD.md#preferredformatindex)
- [SupportedClass](ue_ue.LevelExporterLOD.md#supportedclass)
- [TextIndent](ue_ue.LevelExporterLOD.md#textindent)
- [\_\_tid\_Exporter\_\_](ue_ue.LevelExporterLOD.md#__tid_exporter__)
- [\_\_tid\_LevelExporterLOD\_\_](ue_ue.LevelExporterLOD.md#__tid_levelexporterlod__)
- [\_\_tid\_Object\_\_](ue_ue.LevelExporterLOD.md#__tid_object__)
- [bForceFileOperations](ue_ue.LevelExporterLOD.md#bforcefileoperations)
- [bSelectedOnly](ue_ue.LevelExporterLOD.md#bselectedonly)
- [bText](ue_ue.LevelExporterLOD.md#btext)

### Methods

- [CreateDefaultSubobject](ue_ue.LevelExporterLOD.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LevelExporterLOD.md#executeubergraph)
- [GetClass](ue_ue.LevelExporterLOD.md#getclass)
- [GetName](ue_ue.LevelExporterLOD.md#getname)
- [GetOuter](ue_ue.LevelExporterLOD.md#getouter)
- [GetWorld](ue_ue.LevelExporterLOD.md#getworld)
- [ScriptRunAssetExportTask](ue_ue.LevelExporterLOD.md#scriptrunassetexporttask)
- [Find](ue_ue.LevelExporterLOD.md#find)
- [Load](ue_ue.LevelExporterLOD.md#load)
- [RunAssetExportTask](ue_ue.LevelExporterLOD.md#runassetexporttask)
- [RunAssetExportTasks](ue_ue.LevelExporterLOD.md#runassetexporttasks)
- [StaticClass](ue_ue.LevelExporterLOD.md#staticclass)

## Constructors

### constructor

• **new LevelExporterLOD**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Exporter](ue_ue.Exporter.md).[constructor](ue_ue.Exporter.md#constructor)

#### Defined in

[ue/ue.d.ts:45130](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45130)

## Properties

### ExportRootScope

• **ExportRootScope**: [`Object`](ue_ue.Object.md)

#### Inherited from

[Exporter](ue_ue.Exporter.md).[ExportRootScope](ue_ue.Exporter.md#exportrootscope)

#### Defined in

[ue/ue.d.ts:20322](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20322)

___

### ExportTask

• **ExportTask**: [`AssetExportTask`](ue_ue.AssetExportTask.md)

#### Inherited from

[Exporter](ue_ue.Exporter.md).[ExportTask](ue_ue.Exporter.md#exporttask)

#### Defined in

[ue/ue.d.ts:20330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20330)

___

### FormatDescription

• **FormatDescription**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Exporter](ue_ue.Exporter.md).[FormatDescription](ue_ue.Exporter.md#formatdescription)

#### Defined in

[ue/ue.d.ts:20324](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20324)

___

### FormatExtension

• **FormatExtension**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[Exporter](ue_ue.Exporter.md).[FormatExtension](ue_ue.Exporter.md#formatextension)

#### Defined in

[ue/ue.d.ts:20323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20323)

___

### PreferredFormatIndex

• **PreferredFormatIndex**: `number`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[PreferredFormatIndex](ue_ue.Exporter.md#preferredformatindex)

#### Defined in

[ue/ue.d.ts:20325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20325)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[Exporter](ue_ue.Exporter.md).[SupportedClass](ue_ue.Exporter.md#supportedclass)

#### Defined in

[ue/ue.d.ts:20321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20321)

___

### TextIndent

• **TextIndent**: `number`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[TextIndent](ue_ue.Exporter.md#textindent)

#### Defined in

[ue/ue.d.ts:20326](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20326)

___

### \_\_tid\_Exporter\_\_

• **\_\_tid\_Exporter\_\_**: `boolean`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[__tid_Exporter__](ue_ue.Exporter.md#__tid_exporter__)

#### Defined in

[ue/ue.d.ts:20338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20338)

___

### \_\_tid\_LevelExporterLOD\_\_

• **\_\_tid\_LevelExporterLOD\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:45135](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45135)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[__tid_Object__](ue_ue.Exporter.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bForceFileOperations

• **bForceFileOperations**: `boolean`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[bForceFileOperations](ue_ue.Exporter.md#bforcefileoperations)

#### Defined in

[ue/ue.d.ts:20329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20329)

___

### bSelectedOnly

• **bSelectedOnly**: `boolean`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[bSelectedOnly](ue_ue.Exporter.md#bselectedonly)

#### Defined in

[ue/ue.d.ts:20328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20328)

___

### bText

• **bText**: `boolean`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[bText](ue_ue.Exporter.md#btext)

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

[Exporter](ue_ue.Exporter.md).[CreateDefaultSubobject](ue_ue.Exporter.md#createdefaultsubobject)

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

[Exporter](ue_ue.Exporter.md).[ExecuteUbergraph](ue_ue.Exporter.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Exporter](ue_ue.Exporter.md).[GetClass](ue_ue.Exporter.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Exporter](ue_ue.Exporter.md).[GetName](ue_ue.Exporter.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Exporter](ue_ue.Exporter.md).[GetOuter](ue_ue.Exporter.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Exporter](ue_ue.Exporter.md).[GetWorld](ue_ue.Exporter.md#getworld)

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

[Exporter](ue_ue.Exporter.md).[ScriptRunAssetExportTask](ue_ue.Exporter.md#scriptrunassetexporttask)

#### Defined in

[ue/ue.d.ts:20331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20331)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LevelExporterLOD`](ue_ue.LevelExporterLOD.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LevelExporterLOD`](ue_ue.LevelExporterLOD.md)

#### Overrides

[Exporter](ue_ue.Exporter.md).[Find](ue_ue.Exporter.md#find)

#### Defined in

[ue/ue.d.ts:45132](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45132)

___

### Load

▸ `Static` **Load**(`InName`): [`LevelExporterLOD`](ue_ue.LevelExporterLOD.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LevelExporterLOD`](ue_ue.LevelExporterLOD.md)

#### Overrides

[Exporter](ue_ue.Exporter.md).[Load](ue_ue.Exporter.md#load)

#### Defined in

[ue/ue.d.ts:45133](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45133)

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

[Exporter](ue_ue.Exporter.md).[RunAssetExportTasks](ue_ue.Exporter.md#runassetexporttasks)

#### Defined in

[ue/ue.d.ts:20333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20333)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Exporter](ue_ue.Exporter.md).[StaticClass](ue_ue.Exporter.md#staticclass)

#### Defined in

[ue/ue.d.ts:45131](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L45131)