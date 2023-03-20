[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Exporter

# Class: Exporter

[ue/ue](../modules/ue_ue.md).Exporter

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`Exporter`**

  ↳↳ [`ExporterFBX`](ue_ue.ExporterFBX.md)

  ↳↳ [`LevelExporterLOD`](ue_ue.LevelExporterLOD.md)

  ↳↳ [`LevelExporterOBJ`](ue_ue.LevelExporterOBJ.md)

  ↳↳ [`LevelExporterSTL`](ue_ue.LevelExporterSTL.md)

  ↳↳ [`LevelExporterT3D`](ue_ue.LevelExporterT3D.md)

  ↳↳ [`ModelExporterT3D`](ue_ue.ModelExporterT3D.md)

  ↳↳ [`ObjectExporterT3D`](ue_ue.ObjectExporterT3D.md)

  ↳↳ [`PolysExporterOBJ`](ue_ue.PolysExporterOBJ.md)

  ↳↳ [`PolysExporterT3D`](ue_ue.PolysExporterT3D.md)

  ↳↳ [`RenderTargetExporterHDR`](ue_ue.RenderTargetExporterHDR.md)

  ↳↳ [`SequenceExporterT3D`](ue_ue.SequenceExporterT3D.md)

  ↳↳ [`SoundExporterOGG`](ue_ue.SoundExporterOGG.md)

  ↳↳ [`SoundExporterWAV`](ue_ue.SoundExporterWAV.md)

  ↳↳ [`SoundSurroundExporterWAV`](ue_ue.SoundSurroundExporterWAV.md)

  ↳↳ [`StaticMeshExporterOBJ`](ue_ue.StaticMeshExporterOBJ.md)

  ↳↳ [`TextBufferExporterTXT`](ue_ue.TextBufferExporterTXT.md)

  ↳↳ [`TextureCubeExporterHDR`](ue_ue.TextureCubeExporterHDR.md)

  ↳↳ [`TextureExporterBMP`](ue_ue.TextureExporterBMP.md)

  ↳↳ [`TextureExporterHDR`](ue_ue.TextureExporterHDR.md)

  ↳↳ [`TextureExporterPCX`](ue_ue.TextureExporterPCX.md)

  ↳↳ [`TextureExporterTGA`](ue_ue.TextureExporterTGA.md)

## Table of contents

### Constructors

- [constructor](ue_ue.Exporter.md#constructor)

### Properties

- [ExportRootScope](ue_ue.Exporter.md#exportrootscope)
- [ExportTask](ue_ue.Exporter.md#exporttask)
- [FormatDescription](ue_ue.Exporter.md#formatdescription)
- [FormatExtension](ue_ue.Exporter.md#formatextension)
- [PreferredFormatIndex](ue_ue.Exporter.md#preferredformatindex)
- [SupportedClass](ue_ue.Exporter.md#supportedclass)
- [TextIndent](ue_ue.Exporter.md#textindent)
- [\_\_tid\_Exporter\_\_](ue_ue.Exporter.md#__tid_exporter__)
- [\_\_tid\_Object\_\_](ue_ue.Exporter.md#__tid_object__)
- [bForceFileOperations](ue_ue.Exporter.md#bforcefileoperations)
- [bSelectedOnly](ue_ue.Exporter.md#bselectedonly)
- [bText](ue_ue.Exporter.md#btext)

### Methods

- [CreateDefaultSubobject](ue_ue.Exporter.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Exporter.md#executeubergraph)
- [GetClass](ue_ue.Exporter.md#getclass)
- [GetName](ue_ue.Exporter.md#getname)
- [GetOuter](ue_ue.Exporter.md#getouter)
- [GetWorld](ue_ue.Exporter.md#getworld)
- [ScriptRunAssetExportTask](ue_ue.Exporter.md#scriptrunassetexporttask)
- [Find](ue_ue.Exporter.md#find)
- [Load](ue_ue.Exporter.md#load)
- [RunAssetExportTask](ue_ue.Exporter.md#runassetexporttask)
- [RunAssetExportTasks](ue_ue.Exporter.md#runassetexporttasks)
- [StaticClass](ue_ue.Exporter.md#staticclass)

## Constructors

### constructor

• **new Exporter**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:20320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20320)

## Properties

### ExportRootScope

• **ExportRootScope**: [`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:20322](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20322)

___

### ExportTask

• **ExportTask**: [`AssetExportTask`](ue_ue.AssetExportTask.md)

#### Defined in

[ue/ue.d.ts:20330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20330)

___

### FormatDescription

• **FormatDescription**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:20324](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20324)

___

### FormatExtension

• **FormatExtension**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:20323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20323)

___

### PreferredFormatIndex

• **PreferredFormatIndex**: `number`

#### Defined in

[ue/ue.d.ts:20325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20325)

___

### SupportedClass

• **SupportedClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:20321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20321)

___

### TextIndent

• **TextIndent**: `number`

#### Defined in

[ue/ue.d.ts:20326](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20326)

___

### \_\_tid\_Exporter\_\_

• **\_\_tid\_Exporter\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:20338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20338)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bForceFileOperations

• **bForceFileOperations**: `boolean`

#### Defined in

[ue/ue.d.ts:20329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20329)

___

### bSelectedOnly

• **bSelectedOnly**: `boolean`

#### Defined in

[ue/ue.d.ts:20328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20328)

___

### bText

• **bText**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

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

#### Defined in

[ue/ue.d.ts:20331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20331)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Exporter`](ue_ue.Exporter.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Exporter`](ue_ue.Exporter.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:20335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20335)

___

### Load

▸ `Static` **Load**(`InName`): [`Exporter`](ue_ue.Exporter.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Exporter`](ue_ue.Exporter.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:20336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20336)

___

### RunAssetExportTask

▸ `Static` **RunAssetExportTask**(`Task`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Task` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AssetExportTask`](ue_ue.AssetExportTask.md)\> |

#### Returns

`boolean`

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

#### Defined in

[ue/ue.d.ts:20333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20333)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:20334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L20334)
