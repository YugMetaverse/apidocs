[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GeometryCache

# Class: GeometryCache

[ue/ue](../modules/ue_ue.md).GeometryCache

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`GeometryCache`**

## Table of contents

### Constructors

- [constructor](ue_ue.GeometryCache.md#constructor)

### Properties

- [AssetImportData](ue_ue.GeometryCache.md#assetimportdata)
- [EndFrame](ue_ue.GeometryCache.md#endframe)
- [Materials](ue_ue.GeometryCache.md#materials)
- [StartFrame](ue_ue.GeometryCache.md#startframe)
- [ThumbnailInfo](ue_ue.GeometryCache.md#thumbnailinfo)
- [Tracks](ue_ue.GeometryCache.md#tracks)
- [\_\_tid\_GeometryCache\_\_](ue_ue.GeometryCache.md#__tid_geometrycache__)
- [\_\_tid\_Object\_\_](ue_ue.GeometryCache.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.GeometryCache.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GeometryCache.md#executeubergraph)
- [GetClass](ue_ue.GeometryCache.md#getclass)
- [GetName](ue_ue.GeometryCache.md#getname)
- [GetOuter](ue_ue.GeometryCache.md#getouter)
- [GetWorld](ue_ue.GeometryCache.md#getworld)
- [Find](ue_ue.GeometryCache.md#find)
- [Load](ue_ue.GeometryCache.md#load)
- [StaticClass](ue_ue.GeometryCache.md#staticclass)

## Constructors

### constructor

• **new GeometryCache**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:37555](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37555)

## Properties

### AssetImportData

• **AssetImportData**: [`AssetImportData`](ue_ue.AssetImportData.md)

#### Defined in

[ue/ue.d.ts:37556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37556)

___

### EndFrame

• **EndFrame**: `number`

#### Defined in

[ue/ue.d.ts:37561](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37561)

___

### Materials

• **Materials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

#### Defined in

[ue/ue.d.ts:37558](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37558)

___

### StartFrame

• **StartFrame**: `number`

#### Defined in

[ue/ue.d.ts:37560](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37560)

___

### ThumbnailInfo

• **ThumbnailInfo**: [`ThumbnailInfo`](ue_ue.ThumbnailInfo.md)

#### Defined in

[ue/ue.d.ts:37557](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37557)

___

### Tracks

• **Tracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GeometryCacheTrack`](ue_ue.GeometryCacheTrack.md)\>

#### Defined in

[ue/ue.d.ts:37559](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37559)

___

### \_\_tid\_GeometryCache\_\_

• **\_\_tid\_GeometryCache\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:37566](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37566)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GeometryCache`](ue_ue.GeometryCache.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GeometryCache`](ue_ue.GeometryCache.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:37563](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37563)

___

### Load

▸ `Static` **Load**(`InName`): [`GeometryCache`](ue_ue.GeometryCache.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GeometryCache`](ue_ue.GeometryCache.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:37564](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37564)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:37562](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L37562)
