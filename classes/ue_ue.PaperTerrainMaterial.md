[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PaperTerrainMaterial

# Class: PaperTerrainMaterial

[ue/ue](../modules/ue_ue.md).PaperTerrainMaterial

## Hierarchy

- [`DataAsset`](ue_ue.DataAsset.md)

  ↳ **`PaperTerrainMaterial`**

## Table of contents

### Constructors

- [constructor](ue_ue.PaperTerrainMaterial.md#constructor)

### Properties

- [InteriorFill](ue_ue.PaperTerrainMaterial.md#interiorfill)
- [NativeClass](ue_ue.PaperTerrainMaterial.md#nativeclass)
- [Rules](ue_ue.PaperTerrainMaterial.md#rules)
- [\_\_tid\_DataAsset\_\_](ue_ue.PaperTerrainMaterial.md#__tid_dataasset__)
- [\_\_tid\_Object\_\_](ue_ue.PaperTerrainMaterial.md#__tid_object__)
- [\_\_tid\_PaperTerrainMaterial\_\_](ue_ue.PaperTerrainMaterial.md#__tid_paperterrainmaterial__)

### Methods

- [CreateDefaultSubobject](ue_ue.PaperTerrainMaterial.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PaperTerrainMaterial.md#executeubergraph)
- [GetClass](ue_ue.PaperTerrainMaterial.md#getclass)
- [GetName](ue_ue.PaperTerrainMaterial.md#getname)
- [GetOuter](ue_ue.PaperTerrainMaterial.md#getouter)
- [GetWorld](ue_ue.PaperTerrainMaterial.md#getworld)
- [Find](ue_ue.PaperTerrainMaterial.md#find)
- [Load](ue_ue.PaperTerrainMaterial.md#load)
- [StaticClass](ue_ue.PaperTerrainMaterial.md#staticclass)

## Constructors

### constructor

• **new PaperTerrainMaterial**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[constructor](ue_ue.DataAsset.md#constructor)

## Properties

### InteriorFill

• **InteriorFill**: [`PaperSprite`](ue_ue.PaperSprite.md)

___

### NativeClass

• **NativeClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[NativeClass](ue_ue.DataAsset.md#nativeclass)

___

### Rules

• **Rules**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PaperTerrainMaterialRule`](ue_ue.PaperTerrainMaterialRule.md)\>

___

### \_\_tid\_DataAsset\_\_

• **\_\_tid\_DataAsset\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_DataAsset__](ue_ue.DataAsset.md#__tid_dataasset__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_Object__](ue_ue.DataAsset.md#__tid_object__)

___

### \_\_tid\_PaperTerrainMaterial\_\_

• **\_\_tid\_PaperTerrainMaterial\_\_**: `boolean`

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

[DataAsset](ue_ue.DataAsset.md).[CreateDefaultSubobject](ue_ue.DataAsset.md#createdefaultsubobject)

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

[DataAsset](ue_ue.DataAsset.md).[ExecuteUbergraph](ue_ue.DataAsset.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetClass](ue_ue.DataAsset.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetName](ue_ue.DataAsset.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetOuter](ue_ue.DataAsset.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetWorld](ue_ue.DataAsset.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PaperTerrainMaterial`](ue_ue.PaperTerrainMaterial.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PaperTerrainMaterial`](ue_ue.PaperTerrainMaterial.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[Find](ue_ue.DataAsset.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PaperTerrainMaterial`](ue_ue.PaperTerrainMaterial.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PaperTerrainMaterial`](ue_ue.PaperTerrainMaterial.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[Load](ue_ue.DataAsset.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[StaticClass](ue_ue.DataAsset.md#staticclass)
