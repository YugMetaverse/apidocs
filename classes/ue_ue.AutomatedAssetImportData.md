[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AutomatedAssetImportData

# Class: AutomatedAssetImportData

[ue/ue](../modules/ue_ue.md).AutomatedAssetImportData

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AutomatedAssetImportData`**

## Table of contents

### Constructors

- [constructor](ue_ue.AutomatedAssetImportData.md#constructor)

### Properties

- [DestinationPath](ue_ue.AutomatedAssetImportData.md#destinationpath)
- [Factory](ue_ue.AutomatedAssetImportData.md#factory)
- [FactoryName](ue_ue.AutomatedAssetImportData.md#factoryname)
- [Filenames](ue_ue.AutomatedAssetImportData.md#filenames)
- [GroupName](ue_ue.AutomatedAssetImportData.md#groupname)
- [LevelToLoad](ue_ue.AutomatedAssetImportData.md#leveltoload)
- [\_\_tid\_AutomatedAssetImportData\_\_](ue_ue.AutomatedAssetImportData.md#__tid_automatedassetimportdata__)
- [\_\_tid\_Object\_\_](ue_ue.AutomatedAssetImportData.md#__tid_object__)
- [bReplaceExisting](ue_ue.AutomatedAssetImportData.md#breplaceexisting)
- [bSkipReadOnly](ue_ue.AutomatedAssetImportData.md#bskipreadonly)

### Methods

- [CreateDefaultSubobject](ue_ue.AutomatedAssetImportData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AutomatedAssetImportData.md#executeubergraph)
- [GetClass](ue_ue.AutomatedAssetImportData.md#getclass)
- [GetName](ue_ue.AutomatedAssetImportData.md#getname)
- [GetOuter](ue_ue.AutomatedAssetImportData.md#getouter)
- [GetWorld](ue_ue.AutomatedAssetImportData.md#getworld)
- [Find](ue_ue.AutomatedAssetImportData.md#find)
- [Load](ue_ue.AutomatedAssetImportData.md#load)
- [StaticClass](ue_ue.AutomatedAssetImportData.md#staticclass)

## Constructors

### constructor

• **new AutomatedAssetImportData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### DestinationPath

• **DestinationPath**: `string`

___

### Factory

• **Factory**: [`Factory`](ue_ue.Factory.md)

___

### FactoryName

• **FactoryName**: `string`

___

### Filenames

• **Filenames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### GroupName

• **GroupName**: `string`

___

### LevelToLoad

• **LevelToLoad**: `string`

___

### \_\_tid\_AutomatedAssetImportData\_\_

• **\_\_tid\_AutomatedAssetImportData\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bReplaceExisting

• **bReplaceExisting**: `boolean`

___

### bSkipReadOnly

• **bSkipReadOnly**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AutomatedAssetImportData`](ue_ue.AutomatedAssetImportData.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
