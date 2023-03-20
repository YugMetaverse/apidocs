[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DatasmithAssetUserData

# Class: DatasmithAssetUserData

[ue/ue](../modules/ue_ue.md).DatasmithAssetUserData

## Hierarchy

- [`AssetUserData`](ue_ue.AssetUserData.md)

  ↳ **`DatasmithAssetUserData`**

## Table of contents

### Constructors

- [constructor](ue_ue.DatasmithAssetUserData.md#constructor)

### Properties

- [MetaData](ue_ue.DatasmithAssetUserData.md#metadata)
- [ObjectTemplates](ue_ue.DatasmithAssetUserData.md#objecttemplates)
- [\_\_tid\_AssetUserData\_\_](ue_ue.DatasmithAssetUserData.md#__tid_assetuserdata__)
- [\_\_tid\_DatasmithAssetUserData\_\_](ue_ue.DatasmithAssetUserData.md#__tid_datasmithassetuserdata__)
- [\_\_tid\_Object\_\_](ue_ue.DatasmithAssetUserData.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.DatasmithAssetUserData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DatasmithAssetUserData.md#executeubergraph)
- [GetClass](ue_ue.DatasmithAssetUserData.md#getclass)
- [GetName](ue_ue.DatasmithAssetUserData.md#getname)
- [GetOuter](ue_ue.DatasmithAssetUserData.md#getouter)
- [GetWorld](ue_ue.DatasmithAssetUserData.md#getworld)
- [Find](ue_ue.DatasmithAssetUserData.md#find)
- [Load](ue_ue.DatasmithAssetUserData.md#load)
- [StaticClass](ue_ue.DatasmithAssetUserData.md#staticclass)

## Constructors

### constructor

• **new DatasmithAssetUserData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AssetUserData](ue_ue.AssetUserData.md).[constructor](ue_ue.AssetUserData.md#constructor)

## Properties

### MetaData

• **MetaData**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

___

### ObjectTemplates

• **ObjectTemplates**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Class`](ue_ue.Class.md), [`DatasmithObjectTemplate`](ue_ue.DatasmithObjectTemplate.md)\>

___

### \_\_tid\_AssetUserData\_\_

• **\_\_tid\_AssetUserData\_\_**: `boolean`

#### Inherited from

[AssetUserData](ue_ue.AssetUserData.md).[__tid_AssetUserData__](ue_ue.AssetUserData.md#__tid_assetuserdata__)

___

### \_\_tid\_DatasmithAssetUserData\_\_

• **\_\_tid\_DatasmithAssetUserData\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AssetUserData](ue_ue.AssetUserData.md).[__tid_Object__](ue_ue.AssetUserData.md#__tid_object__)

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

[AssetUserData](ue_ue.AssetUserData.md).[CreateDefaultSubobject](ue_ue.AssetUserData.md#createdefaultsubobject)

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

[AssetUserData](ue_ue.AssetUserData.md).[ExecuteUbergraph](ue_ue.AssetUserData.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AssetUserData](ue_ue.AssetUserData.md).[GetClass](ue_ue.AssetUserData.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AssetUserData](ue_ue.AssetUserData.md).[GetName](ue_ue.AssetUserData.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AssetUserData](ue_ue.AssetUserData.md).[GetOuter](ue_ue.AssetUserData.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AssetUserData](ue_ue.AssetUserData.md).[GetWorld](ue_ue.AssetUserData.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DatasmithAssetUserData`](ue_ue.DatasmithAssetUserData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DatasmithAssetUserData`](ue_ue.DatasmithAssetUserData.md)

#### Overrides

[AssetUserData](ue_ue.AssetUserData.md).[Find](ue_ue.AssetUserData.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DatasmithAssetUserData`](ue_ue.DatasmithAssetUserData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DatasmithAssetUserData`](ue_ue.DatasmithAssetUserData.md)

#### Overrides

[AssetUserData](ue_ue.AssetUserData.md).[Load](ue_ue.AssetUserData.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AssetUserData](ue_ue.AssetUserData.md).[StaticClass](ue_ue.AssetUserData.md#staticclass)
