[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AbcImportSettings

# Class: AbcImportSettings

[ue/ue](../modules/ue_ue.md).AbcImportSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AbcImportSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.AbcImportSettings.md#constructor)

### Properties

- [CompressionSettings](ue_ue.AbcImportSettings.md#compressionsettings)
- [ConversionSettings](ue_ue.AbcImportSettings.md#conversionsettings)
- [GeometryCacheSettings](ue_ue.AbcImportSettings.md#geometrycachesettings)
- [ImportType](ue_ue.AbcImportSettings.md#importtype)
- [MaterialSettings](ue_ue.AbcImportSettings.md#materialsettings)
- [NormalGenerationSettings](ue_ue.AbcImportSettings.md#normalgenerationsettings)
- [SamplingSettings](ue_ue.AbcImportSettings.md#samplingsettings)
- [StaticMeshSettings](ue_ue.AbcImportSettings.md#staticmeshsettings)
- [\_\_tid\_AbcImportSettings\_\_](ue_ue.AbcImportSettings.md#__tid_abcimportsettings__)
- [\_\_tid\_Object\_\_](ue_ue.AbcImportSettings.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AbcImportSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AbcImportSettings.md#executeubergraph)
- [GetClass](ue_ue.AbcImportSettings.md#getclass)
- [GetName](ue_ue.AbcImportSettings.md#getname)
- [GetOuter](ue_ue.AbcImportSettings.md#getouter)
- [GetWorld](ue_ue.AbcImportSettings.md#getworld)
- [Find](ue_ue.AbcImportSettings.md#find)
- [Load](ue_ue.AbcImportSettings.md#load)
- [StaticClass](ue_ue.AbcImportSettings.md#staticclass)

## Constructors

### constructor

• **new AbcImportSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L173)

## Properties

### CompressionSettings

• **CompressionSettings**: [`AbcCompressionSettings`](ue_ue.AbcCompressionSettings.md)

#### Defined in

[ue/ue.d.ts:178](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L178)

___

### ConversionSettings

• **ConversionSettings**: [`AbcConversionSettings`](ue_ue.AbcConversionSettings.md)

#### Defined in

[ue/ue.d.ts:181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L181)

___

### GeometryCacheSettings

• **GeometryCacheSettings**: [`AbcGeometryCacheSettings`](ue_ue.AbcGeometryCacheSettings.md)

#### Defined in

[ue/ue.d.ts:180](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L180)

___

### ImportType

• **ImportType**: [`EAlembicImportType`](../enums/ue_ue.EAlembicImportType.md)

#### Defined in

[ue/ue.d.ts:174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L174)

___

### MaterialSettings

• **MaterialSettings**: [`AbcMaterialSettings`](ue_ue.AbcMaterialSettings.md)

#### Defined in

[ue/ue.d.ts:177](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L177)

___

### NormalGenerationSettings

• **NormalGenerationSettings**: [`AbcNormalGenerationSettings`](ue_ue.AbcNormalGenerationSettings.md)

#### Defined in

[ue/ue.d.ts:176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L176)

___

### SamplingSettings

• **SamplingSettings**: [`AbcSamplingSettings`](ue_ue.AbcSamplingSettings.md)

#### Defined in

[ue/ue.d.ts:175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L175)

___

### StaticMeshSettings

• **StaticMeshSettings**: [`AbcStaticMeshSettings`](ue_ue.AbcStaticMeshSettings.md)

#### Defined in

[ue/ue.d.ts:179](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L179)

___

### \_\_tid\_AbcImportSettings\_\_

• **\_\_tid\_AbcImportSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:186](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L186)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AbcImportSettings`](ue_ue.AbcImportSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AbcImportSettings`](ue_ue.AbcImportSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:183](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L183)

___

### Load

▸ `Static` **Load**(`InName`): [`AbcImportSettings`](ue_ue.AbcImportSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AbcImportSettings`](ue_ue.AbcImportSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:184](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L184)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:182](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L182)
