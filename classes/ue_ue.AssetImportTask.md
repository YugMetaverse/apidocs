[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AssetImportTask

# Class: AssetImportTask

[ue/ue](../modules/ue_ue.md).AssetImportTask

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AssetImportTask`**

## Table of contents

### Constructors

- [constructor](ue_ue.AssetImportTask.md#constructor)

### Properties

- [DestinationName](ue_ue.AssetImportTask.md#destinationname)
- [DestinationPath](ue_ue.AssetImportTask.md#destinationpath)
- [Factory](ue_ue.AssetImportTask.md#factory)
- [Filename](ue_ue.AssetImportTask.md#filename)
- [ImportedObjectPaths](ue_ue.AssetImportTask.md#importedobjectpaths)
- [Options](ue_ue.AssetImportTask.md#options)
- [Result](ue_ue.AssetImportTask.md#result)
- [\_\_tid\_AssetImportTask\_\_](ue_ue.AssetImportTask.md#__tid_assetimporttask__)
- [\_\_tid\_Object\_\_](ue_ue.AssetImportTask.md#__tid_object__)
- [bAutomated](ue_ue.AssetImportTask.md#bautomated)
- [bReplaceExisting](ue_ue.AssetImportTask.md#breplaceexisting)
- [bSave](ue_ue.AssetImportTask.md#bsave)

### Methods

- [CreateDefaultSubobject](ue_ue.AssetImportTask.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AssetImportTask.md#executeubergraph)
- [GetClass](ue_ue.AssetImportTask.md#getclass)
- [GetName](ue_ue.AssetImportTask.md#getname)
- [GetOuter](ue_ue.AssetImportTask.md#getouter)
- [GetWorld](ue_ue.AssetImportTask.md#getworld)
- [Find](ue_ue.AssetImportTask.md#find)
- [Load](ue_ue.AssetImportTask.md#load)
- [StaticClass](ue_ue.AssetImportTask.md#staticclass)

## Constructors

### constructor

• **new AssetImportTask**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### DestinationName

• **DestinationName**: `string`

___

### DestinationPath

• **DestinationPath**: `string`

___

### Factory

• **Factory**: [`Factory`](ue_ue.Factory.md)

___

### Filename

• **Filename**: `string`

___

### ImportedObjectPaths

• **ImportedObjectPaths**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### Options

• **Options**: [`Object`](ue_ue.Object.md)

___

### Result

• **Result**: [`Object`](ue_ue.Object.md)

___

### \_\_tid\_AssetImportTask\_\_

• **\_\_tid\_AssetImportTask\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bAutomated

• **bAutomated**: `boolean`

___

### bReplaceExisting

• **bReplaceExisting**: `boolean`

___

### bSave

• **bSave**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AssetImportTask`](ue_ue.AssetImportTask.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
