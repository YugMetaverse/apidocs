[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DatasmithScene

# Class: DatasmithScene

[ue/ue](../modules/ue_ue.md).DatasmithScene

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`DatasmithScene`**

## Table of contents

### Constructors

- [constructor](ue_ue.DatasmithScene.md#constructor)

### Properties

- [AssetImportData](ue_ue.DatasmithScene.md#assetimportdata)
- [AssetUserData](ue_ue.DatasmithScene.md#assetuserdata)
- [BulkDataVersion](ue_ue.DatasmithScene.md#bulkdataversion)
- [LevelSequences](ue_ue.DatasmithScene.md#levelsequences)
- [LevelVariantSets](ue_ue.DatasmithScene.md#levelvariantsets)
- [MaterialFunctions](ue_ue.DatasmithScene.md#materialfunctions)
- [Materials](ue_ue.DatasmithScene.md#materials)
- [StaticMeshes](ue_ue.DatasmithScene.md#staticmeshes)
- [Textures](ue_ue.DatasmithScene.md#textures)
- [\_\_tid\_DatasmithScene\_\_](ue_ue.DatasmithScene.md#__tid_datasmithscene__)
- [\_\_tid\_Object\_\_](ue_ue.DatasmithScene.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.DatasmithScene.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DatasmithScene.md#executeubergraph)
- [GetClass](ue_ue.DatasmithScene.md#getclass)
- [GetName](ue_ue.DatasmithScene.md#getname)
- [GetOuter](ue_ue.DatasmithScene.md#getouter)
- [GetWorld](ue_ue.DatasmithScene.md#getworld)
- [Find](ue_ue.DatasmithScene.md#find)
- [Load](ue_ue.DatasmithScene.md#load)
- [StaticClass](ue_ue.DatasmithScene.md#staticclass)

## Constructors

### constructor

• **new DatasmithScene**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AssetImportData

• **AssetImportData**: [`DatasmithSceneImportData`](ue_ue.DatasmithSceneImportData.md)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

___

### BulkDataVersion

• **BulkDataVersion**: `number`

___

### LevelSequences

• **LevelSequences**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`LevelSequence`](ue_ue.LevelSequence.md)\>\>

___

### LevelVariantSets

• **LevelVariantSets**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`LevelVariantSets`](ue_ue.LevelVariantSets.md)\>\>

___

### MaterialFunctions

• **MaterialFunctions**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`MaterialFunction`](ue_ue.MaterialFunction.md)\>\>

___

### Materials

• **Materials**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>\>

___

### StaticMeshes

• **StaticMeshes**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`StaticMesh`](ue_ue.StaticMesh.md)\>\>

___

### Textures

• **Textures**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`Texture`](ue_ue.Texture.md)\>\>

___

### \_\_tid\_DatasmithScene\_\_

• **\_\_tid\_DatasmithScene\_\_**: `boolean`

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DatasmithScene`](ue_ue.DatasmithScene.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DatasmithScene`](ue_ue.DatasmithScene.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DatasmithScene`](ue_ue.DatasmithScene.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DatasmithScene`](ue_ue.DatasmithScene.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
