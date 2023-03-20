[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DatasmithMaterialInstanceTemplate

# Class: DatasmithMaterialInstanceTemplate

[ue/ue](../modules/ue_ue.md).DatasmithMaterialInstanceTemplate

## Hierarchy

- [`DatasmithObjectTemplate`](ue_ue.DatasmithObjectTemplate.md)

  ↳ **`DatasmithMaterialInstanceTemplate`**

## Table of contents

### Constructors

- [constructor](ue_ue.DatasmithMaterialInstanceTemplate.md#constructor)

### Properties

- [ScalarParameterValues](ue_ue.DatasmithMaterialInstanceTemplate.md#scalarparametervalues)
- [StaticParameters](ue_ue.DatasmithMaterialInstanceTemplate.md#staticparameters)
- [TextureParameterValues](ue_ue.DatasmithMaterialInstanceTemplate.md#textureparametervalues)
- [VectorParameterValues](ue_ue.DatasmithMaterialInstanceTemplate.md#vectorparametervalues)
- [\_\_tid\_DatasmithMaterialInstanceTemplate\_\_](ue_ue.DatasmithMaterialInstanceTemplate.md#__tid_datasmithmaterialinstancetemplate__)
- [\_\_tid\_DatasmithObjectTemplate\_\_](ue_ue.DatasmithMaterialInstanceTemplate.md#__tid_datasmithobjecttemplate__)
- [\_\_tid\_Object\_\_](ue_ue.DatasmithMaterialInstanceTemplate.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.DatasmithMaterialInstanceTemplate.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.DatasmithMaterialInstanceTemplate.md#executeubergraph)
- [GetClass](ue_ue.DatasmithMaterialInstanceTemplate.md#getclass)
- [GetName](ue_ue.DatasmithMaterialInstanceTemplate.md#getname)
- [GetOuter](ue_ue.DatasmithMaterialInstanceTemplate.md#getouter)
- [GetWorld](ue_ue.DatasmithMaterialInstanceTemplate.md#getworld)
- [Find](ue_ue.DatasmithMaterialInstanceTemplate.md#find)
- [Load](ue_ue.DatasmithMaterialInstanceTemplate.md#load)
- [StaticClass](ue_ue.DatasmithMaterialInstanceTemplate.md#staticclass)

## Constructors

### constructor

• **new DatasmithMaterialInstanceTemplate**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[constructor](ue_ue.DatasmithObjectTemplate.md#constructor)

#### Defined in

[ue/ue.d.ts:29793](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29793)

## Properties

### ScalarParameterValues

• **ScalarParameterValues**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `number`\>

#### Defined in

[ue/ue.d.ts:29794](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29794)

___

### StaticParameters

• **StaticParameters**: [`DatasmithStaticParameterSetTemplate`](ue_ue.DatasmithStaticParameterSetTemplate.md)

#### Defined in

[ue/ue.d.ts:29797](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29797)

___

### TextureParameterValues

• **TextureParameterValues**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`Texture`](ue_ue.Texture.md)\>\>

#### Defined in

[ue/ue.d.ts:29796](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29796)

___

### VectorParameterValues

• **VectorParameterValues**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`LinearColor`](ue_ue_s.LinearColor.md)\>

#### Defined in

[ue/ue.d.ts:29795](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29795)

___

### \_\_tid\_DatasmithMaterialInstanceTemplate\_\_

• **\_\_tid\_DatasmithMaterialInstanceTemplate\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:29802](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29802)

___

### \_\_tid\_DatasmithObjectTemplate\_\_

• **\_\_tid\_DatasmithObjectTemplate\_\_**: `boolean`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[__tid_DatasmithObjectTemplate__](ue_ue.DatasmithObjectTemplate.md#__tid_datasmithobjecttemplate__)

#### Defined in

[ue/ue.d.ts:29319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29319)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[__tid_Object__](ue_ue.DatasmithObjectTemplate.md#__tid_object__)

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

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[CreateDefaultSubobject](ue_ue.DatasmithObjectTemplate.md#createdefaultsubobject)

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

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[ExecuteUbergraph](ue_ue.DatasmithObjectTemplate.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetClass](ue_ue.DatasmithObjectTemplate.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetName](ue_ue.DatasmithObjectTemplate.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetOuter](ue_ue.DatasmithObjectTemplate.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[GetWorld](ue_ue.DatasmithObjectTemplate.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DatasmithMaterialInstanceTemplate`](ue_ue.DatasmithMaterialInstanceTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DatasmithMaterialInstanceTemplate`](ue_ue.DatasmithMaterialInstanceTemplate.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[Find](ue_ue.DatasmithObjectTemplate.md#find)

#### Defined in

[ue/ue.d.ts:29799](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29799)

___

### Load

▸ `Static` **Load**(`InName`): [`DatasmithMaterialInstanceTemplate`](ue_ue.DatasmithMaterialInstanceTemplate.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DatasmithMaterialInstanceTemplate`](ue_ue.DatasmithMaterialInstanceTemplate.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[Load](ue_ue.DatasmithObjectTemplate.md#load)

#### Defined in

[ue/ue.d.ts:29800](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29800)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DatasmithObjectTemplate](ue_ue.DatasmithObjectTemplate.md).[StaticClass](ue_ue.DatasmithObjectTemplate.md#staticclass)

#### Defined in

[ue/ue.d.ts:29798](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L29798)
