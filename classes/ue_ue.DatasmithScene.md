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

#### Defined in

[ue/ue.d.ts:29951](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29951)

## Properties

### AssetImportData

• **AssetImportData**: [`DatasmithSceneImportData`](ue_ue.DatasmithSceneImportData.md)

#### Defined in

[ue/ue.d.ts:29952](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29952)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Defined in

[ue/ue.d.ts:29960](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29960)

___

### BulkDataVersion

• **BulkDataVersion**: `number`

#### Defined in

[ue/ue.d.ts:29953](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29953)

___

### LevelSequences

• **LevelSequences**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`LevelSequence`](ue_ue.LevelSequence.md)\>\>

#### Defined in

[ue/ue.d.ts:29958](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29958)

___

### LevelVariantSets

• **LevelVariantSets**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`LevelVariantSets`](ue_ue.LevelVariantSets.md)\>\>

#### Defined in

[ue/ue.d.ts:29959](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29959)

___

### MaterialFunctions

• **MaterialFunctions**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`MaterialFunction`](ue_ue.MaterialFunction.md)\>\>

#### Defined in

[ue/ue.d.ts:29956](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29956)

___

### Materials

• **Materials**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>\>

#### Defined in

[ue/ue.d.ts:29957](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29957)

___

### StaticMeshes

• **StaticMeshes**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`StaticMesh`](ue_ue.StaticMesh.md)\>\>

#### Defined in

[ue/ue.d.ts:29954](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29954)

___

### Textures

• **Textures**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`Texture`](ue_ue.Texture.md)\>\>

#### Defined in

[ue/ue.d.ts:29955](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29955)

___

### \_\_tid\_DatasmithScene\_\_

• **\_\_tid\_DatasmithScene\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:29965](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29965)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:29962](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29962)

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

#### Defined in

[ue/ue.d.ts:29963](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29963)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:29961](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29961)
