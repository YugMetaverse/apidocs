[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialOptions

# Class: MaterialOptions

[ue/ue](../modules/ue_ue.md).MaterialOptions

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MaterialOptions`**

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialOptions.md#constructor)

### Properties

- [LODIndices](ue_ue.MaterialOptions.md#lodindices)
- [Properties](ue_ue.MaterialOptions.md#properties)
- [TextureCoordinateIndex](ue_ue.MaterialOptions.md#texturecoordinateindex)
- [TextureSize](ue_ue.MaterialOptions.md#texturesize)
- [\_\_tid\_MaterialOptions\_\_](ue_ue.MaterialOptions.md#__tid_materialoptions__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialOptions.md#__tid_object__)
- [bUseMeshData](ue_ue.MaterialOptions.md#busemeshdata)
- [bUseSpecificUVIndex](ue_ue.MaterialOptions.md#busespecificuvindex)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialOptions.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialOptions.md#executeubergraph)
- [GetClass](ue_ue.MaterialOptions.md#getclass)
- [GetName](ue_ue.MaterialOptions.md#getname)
- [GetOuter](ue_ue.MaterialOptions.md#getouter)
- [GetWorld](ue_ue.MaterialOptions.md#getworld)
- [Find](ue_ue.MaterialOptions.md#find)
- [Load](ue_ue.MaterialOptions.md#load)
- [StaticClass](ue_ue.MaterialOptions.md#staticclass)

## Constructors

### constructor

• **new MaterialOptions**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### LODIndices

• **LODIndices**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### Properties

• **Properties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PropertyEntry`](ue_ue.PropertyEntry.md)\>

___

### TextureCoordinateIndex

• **TextureCoordinateIndex**: `number`

___

### TextureSize

• **TextureSize**: [`IntPoint`](ue_ue_s.IntPoint.md)

___

### \_\_tid\_MaterialOptions\_\_

• **\_\_tid\_MaterialOptions\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bUseMeshData

• **bUseMeshData**: `boolean`

___

### bUseSpecificUVIndex

• **bUseSpecificUVIndex**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialOptions`](ue_ue.MaterialOptions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialOptions`](ue_ue.MaterialOptions.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialOptions`](ue_ue.MaterialOptions.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialOptions`](ue_ue.MaterialOptions.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
