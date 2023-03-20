[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SequencerExportTask

# Class: SequencerExportTask

[ue/ue](../modules/ue_ue.md).SequencerExportTask

## Hierarchy

- [`AssetExportTask`](ue_ue.AssetExportTask.md)

  ↳ **`SequencerExportTask`**

## Table of contents

### Constructors

- [constructor](ue_ue.SequencerExportTask.md#constructor)

### Properties

- [Errors](ue_ue.SequencerExportTask.md#errors)
- [Exporter](ue_ue.SequencerExportTask.md#exporter)
- [Filename](ue_ue.SequencerExportTask.md#filename)
- [IgnoreObjectList](ue_ue.SequencerExportTask.md#ignoreobjectlist)
- [Object](ue_ue.SequencerExportTask.md#object)
- [Options](ue_ue.SequencerExportTask.md#options)
- [SequencerContext](ue_ue.SequencerExportTask.md#sequencercontext)
- [\_\_tid\_AssetExportTask\_\_](ue_ue.SequencerExportTask.md#__tid_assetexporttask__)
- [\_\_tid\_Object\_\_](ue_ue.SequencerExportTask.md#__tid_object__)
- [\_\_tid\_SequencerExportTask\_\_](ue_ue.SequencerExportTask.md#__tid_sequencerexporttask__)
- [bAutomated](ue_ue.SequencerExportTask.md#bautomated)
- [bPrompt](ue_ue.SequencerExportTask.md#bprompt)
- [bReplaceIdentical](ue_ue.SequencerExportTask.md#breplaceidentical)
- [bSelected](ue_ue.SequencerExportTask.md#bselected)
- [bUseFileArchive](ue_ue.SequencerExportTask.md#busefilearchive)
- [bWriteEmptyFiles](ue_ue.SequencerExportTask.md#bwriteemptyfiles)

### Methods

- [CreateDefaultSubobject](ue_ue.SequencerExportTask.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SequencerExportTask.md#executeubergraph)
- [GetClass](ue_ue.SequencerExportTask.md#getclass)
- [GetName](ue_ue.SequencerExportTask.md#getname)
- [GetOuter](ue_ue.SequencerExportTask.md#getouter)
- [GetWorld](ue_ue.SequencerExportTask.md#getworld)
- [Find](ue_ue.SequencerExportTask.md#find)
- [Load](ue_ue.SequencerExportTask.md#load)
- [StaticClass](ue_ue.SequencerExportTask.md#staticclass)

## Constructors

### constructor

• **new SequencerExportTask**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AssetExportTask](ue_ue.AssetExportTask.md).[constructor](ue_ue.AssetExportTask.md#constructor)

## Properties

### Errors

• **Errors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[Errors](ue_ue.AssetExportTask.md#errors)

___

### Exporter

• **Exporter**: [`Exporter`](ue_ue.Exporter.md)

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[Exporter](ue_ue.AssetExportTask.md#exporter)

___

### Filename

• **Filename**: `string`

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[Filename](ue_ue.AssetExportTask.md#filename)

___

### IgnoreObjectList

• **IgnoreObjectList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Object`](ue_ue.Object.md)\>

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[IgnoreObjectList](ue_ue.AssetExportTask.md#ignoreobjectlist)

___

### Object

• **Object**: [`Object`](ue_ue.Object.md)

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[Object](ue_ue.AssetExportTask.md#object)

___

### Options

• **Options**: [`Object`](ue_ue.Object.md)

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[Options](ue_ue.AssetExportTask.md#options)

___

### SequencerContext

• **SequencerContext**: [`Object`](ue_ue.Object.md)

___

### \_\_tid\_AssetExportTask\_\_

• **\_\_tid\_AssetExportTask\_\_**: `boolean`

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[__tid_AssetExportTask__](ue_ue.AssetExportTask.md#__tid_assetexporttask__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[__tid_Object__](ue_ue.AssetExportTask.md#__tid_object__)

___

### \_\_tid\_SequencerExportTask\_\_

• **\_\_tid\_SequencerExportTask\_\_**: `boolean`

___

### bAutomated

• **bAutomated**: `boolean`

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[bAutomated](ue_ue.AssetExportTask.md#bautomated)

___

### bPrompt

• **bPrompt**: `boolean`

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[bPrompt](ue_ue.AssetExportTask.md#bprompt)

___

### bReplaceIdentical

• **bReplaceIdentical**: `boolean`

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[bReplaceIdentical](ue_ue.AssetExportTask.md#breplaceidentical)

___

### bSelected

• **bSelected**: `boolean`

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[bSelected](ue_ue.AssetExportTask.md#bselected)

___

### bUseFileArchive

• **bUseFileArchive**: `boolean`

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[bUseFileArchive](ue_ue.AssetExportTask.md#busefilearchive)

___

### bWriteEmptyFiles

• **bWriteEmptyFiles**: `boolean`

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[bWriteEmptyFiles](ue_ue.AssetExportTask.md#bwriteemptyfiles)

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

[AssetExportTask](ue_ue.AssetExportTask.md).[CreateDefaultSubobject](ue_ue.AssetExportTask.md#createdefaultsubobject)

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

[AssetExportTask](ue_ue.AssetExportTask.md).[ExecuteUbergraph](ue_ue.AssetExportTask.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[GetClass](ue_ue.AssetExportTask.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[GetName](ue_ue.AssetExportTask.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[GetOuter](ue_ue.AssetExportTask.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AssetExportTask](ue_ue.AssetExportTask.md).[GetWorld](ue_ue.AssetExportTask.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SequencerExportTask`](ue_ue.SequencerExportTask.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SequencerExportTask`](ue_ue.SequencerExportTask.md)

#### Overrides

[AssetExportTask](ue_ue.AssetExportTask.md).[Find](ue_ue.AssetExportTask.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SequencerExportTask`](ue_ue.SequencerExportTask.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SequencerExportTask`](ue_ue.SequencerExportTask.md)

#### Overrides

[AssetExportTask](ue_ue.AssetExportTask.md).[Load](ue_ue.AssetExportTask.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AssetExportTask](ue_ue.AssetExportTask.md).[StaticClass](ue_ue.AssetExportTask.md#staticclass)
