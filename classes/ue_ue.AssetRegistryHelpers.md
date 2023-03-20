[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AssetRegistryHelpers

# Class: AssetRegistryHelpers

[ue/ue](../modules/ue_ue.md).AssetRegistryHelpers

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AssetRegistryHelpers`**

## Table of contents

### Constructors

- [constructor](ue_ue.AssetRegistryHelpers.md#constructor)

### Properties

- [\_\_tid\_AssetRegistryHelpers\_\_](ue_ue.AssetRegistryHelpers.md#__tid_assetregistryhelpers__)
- [\_\_tid\_Object\_\_](ue_ue.AssetRegistryHelpers.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AssetRegistryHelpers.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AssetRegistryHelpers.md#executeubergraph)
- [GetClass](ue_ue.AssetRegistryHelpers.md#getclass)
- [GetName](ue_ue.AssetRegistryHelpers.md#getname)
- [GetOuter](ue_ue.AssetRegistryHelpers.md#getouter)
- [GetWorld](ue_ue.AssetRegistryHelpers.md#getworld)
- [CreateAssetData](ue_ue.AssetRegistryHelpers.md#createassetdata)
- [Find](ue_ue.AssetRegistryHelpers.md#find)
- [GetAsset](ue_ue.AssetRegistryHelpers.md#getasset)
- [GetAssetRegistry](ue_ue.AssetRegistryHelpers.md#getassetregistry)
- [GetClass](ue_ue.AssetRegistryHelpers.md#getclass-1)
- [GetExportTextName](ue_ue.AssetRegistryHelpers.md#getexporttextname)
- [GetFullName](ue_ue.AssetRegistryHelpers.md#getfullname)
- [GetTagValue](ue_ue.AssetRegistryHelpers.md#gettagvalue)
- [IsAssetLoaded](ue_ue.AssetRegistryHelpers.md#isassetloaded)
- [IsRedirector](ue_ue.AssetRegistryHelpers.md#isredirector)
- [IsUAsset](ue_ue.AssetRegistryHelpers.md#isuasset)
- [IsValid](ue_ue.AssetRegistryHelpers.md#isvalid)
- [Load](ue_ue.AssetRegistryHelpers.md#load)
- [SetFilterTagsAndValues](ue_ue.AssetRegistryHelpers.md#setfiltertagsandvalues)
- [StaticClass](ue_ue.AssetRegistryHelpers.md#staticclass)
- [ToSoftObjectPath](ue_ue.AssetRegistryHelpers.md#tosoftobjectpath)

## Constructors

### constructor

• **new AssetRegistryHelpers**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_AssetRegistryHelpers\_\_

• **\_\_tid\_AssetRegistryHelpers\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

### CreateAssetData

▸ `Static` **CreateAssetData**(`InAsset`, `bAllowBlueprintClass?`): [`AssetData`](ue_ue.AssetData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAsset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `bAllowBlueprintClass?` | `boolean` |

#### Returns

[`AssetData`](ue_ue.AssetData.md)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AssetRegistryHelpers`](ue_ue.AssetRegistryHelpers.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AssetRegistryHelpers`](ue_ue.AssetRegistryHelpers.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### GetAsset

▸ `Static` **GetAsset**(`InAssetData`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAssetData` | [`AssetData`](ue_ue.AssetData.md) |

#### Returns

[`Object`](ue_ue.Object.md)

___

### GetAssetRegistry

▸ `Static` **GetAssetRegistry**(): [`AssetRegistry`](ue_ue.AssetRegistry.md)

#### Returns

[`AssetRegistry`](ue_ue.AssetRegistry.md)

___

### GetClass

▸ `Static` **GetClass**(`InAssetData`): [`Class`](ue_ue.Class.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAssetData` | [`AssetData`](ue_ue.AssetData.md) |

#### Returns

[`Class`](ue_ue.Class.md)

___

### GetExportTextName

▸ `Static` **GetExportTextName**(`InAssetData`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAssetData` | [`AssetData`](ue_ue.AssetData.md) |

#### Returns

`string`

___

### GetFullName

▸ `Static` **GetFullName**(`InAssetData`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAssetData` | [`AssetData`](ue_ue.AssetData.md) |

#### Returns

`string`

___

### GetTagValue

▸ `Static` **GetTagValue**(`InAssetData`, `InTagName`, `OutTagValue`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAssetData` | [`AssetData`](ue_ue.AssetData.md) |
| `InTagName` | `string` |
| `OutTagValue` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`boolean`

___

### IsAssetLoaded

▸ `Static` **IsAssetLoaded**(`InAssetData`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAssetData` | [`AssetData`](ue_ue.AssetData.md) |

#### Returns

`boolean`

___

### IsRedirector

▸ `Static` **IsRedirector**(`InAssetData`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAssetData` | [`AssetData`](ue_ue.AssetData.md) |

#### Returns

`boolean`

___

### IsUAsset

▸ `Static` **IsUAsset**(`InAssetData`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAssetData` | [`AssetData`](ue_ue.AssetData.md) |

#### Returns

`boolean`

___

### IsValid

▸ `Static` **IsValid**(`InAssetData`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAssetData` | [`AssetData`](ue_ue.AssetData.md) |

#### Returns

`boolean`

___

### Load

▸ `Static` **Load**(`InName`): [`AssetRegistryHelpers`](ue_ue.AssetRegistryHelpers.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AssetRegistryHelpers`](ue_ue.AssetRegistryHelpers.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### SetFilterTagsAndValues

▸ `Static` **SetFilterTagsAndValues**(`InFilter`, `InTagsAndValues`): [`ARFilter`](ue_ue.ARFilter.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFilter` | [`ARFilter`](ue_ue.ARFilter.md) |
| `InTagsAndValues` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TagAndValue`](ue_ue.TagAndValue.md)\> |

#### Returns

[`ARFilter`](ue_ue.ARFilter.md)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

___

### ToSoftObjectPath

▸ `Static` **ToSoftObjectPath**(`InAssetData`): [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAssetData` | [`AssetData`](ue_ue.AssetData.md) |

#### Returns

[`SoftObjectPath`](ue_ue.SoftObjectPath.md)
