[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SlateVectorArtData

# Class: SlateVectorArtData

[ue/ue](../modules/ue_ue.md).SlateVectorArtData

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SlateVectorArtData`**

## Table of contents

### Constructors

- [constructor](ue_ue.SlateVectorArtData.md#constructor)

### Properties

- [ExtentMax](ue_ue.SlateVectorArtData.md#extentmax)
- [ExtentMin](ue_ue.SlateVectorArtData.md#extentmin)
- [IndexData](ue_ue.SlateVectorArtData.md#indexdata)
- [Material](ue_ue.SlateVectorArtData.md#material)
- [MeshAsset](ue_ue.SlateVectorArtData.md#meshasset)
- [SourceMaterial](ue_ue.SlateVectorArtData.md#sourcematerial)
- [VertexData](ue_ue.SlateVectorArtData.md#vertexdata)
- [\_\_tid\_Object\_\_](ue_ue.SlateVectorArtData.md#__tid_object__)
- [\_\_tid\_SlateVectorArtData\_\_](ue_ue.SlateVectorArtData.md#__tid_slatevectorartdata__)

### Methods

- [CreateDefaultSubobject](ue_ue.SlateVectorArtData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SlateVectorArtData.md#executeubergraph)
- [GetClass](ue_ue.SlateVectorArtData.md#getclass)
- [GetName](ue_ue.SlateVectorArtData.md#getname)
- [GetOuter](ue_ue.SlateVectorArtData.md#getouter)
- [GetWorld](ue_ue.SlateVectorArtData.md#getworld)
- [Find](ue_ue.SlateVectorArtData.md#find)
- [Load](ue_ue.SlateVectorArtData.md#load)
- [StaticClass](ue_ue.SlateVectorArtData.md#staticclass)

## Constructors

### constructor

• **new SlateVectorArtData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:60966](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60966)

## Properties

### ExtentMax

• **ExtentMax**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:60973](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60973)

___

### ExtentMin

• **ExtentMin**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:60972](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60972)

___

### IndexData

• **IndexData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:60970](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60970)

___

### Material

• **Material**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:60971](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60971)

___

### MeshAsset

• **MeshAsset**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:60967](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60967)

___

### SourceMaterial

• **SourceMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:60968](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60968)

___

### VertexData

• **VertexData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SlateMeshVertex`](ue_ue.SlateMeshVertex.md)\>

#### Defined in

[ue/ue.d.ts:60969](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60969)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_SlateVectorArtData\_\_

• **\_\_tid\_SlateVectorArtData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:60978](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60978)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SlateVectorArtData`](ue_ue.SlateVectorArtData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SlateVectorArtData`](ue_ue.SlateVectorArtData.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:60975](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60975)

___

### Load

▸ `Static` **Load**(`InName`): [`SlateVectorArtData`](ue_ue.SlateVectorArtData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SlateVectorArtData`](ue_ue.SlateVectorArtData.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:60976](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60976)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:60974](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L60974)
