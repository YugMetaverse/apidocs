[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ClothingAssetFactory

# Class: ClothingAssetFactory

[ue/ue](../modules/ue_ue.md).ClothingAssetFactory

## Hierarchy

- [`ClothingAssetFactoryBase`](ue_ue.ClothingAssetFactoryBase.md)

  ↳ **`ClothingAssetFactory`**

## Table of contents

### Constructors

- [constructor](ue_ue.ClothingAssetFactory.md#constructor)

### Properties

- [\_\_tid\_ClothingAssetFactoryBase\_\_](ue_ue.ClothingAssetFactory.md#__tid_clothingassetfactorybase__)
- [\_\_tid\_ClothingAssetFactory\_\_](ue_ue.ClothingAssetFactory.md#__tid_clothingassetfactory__)
- [\_\_tid\_Object\_\_](ue_ue.ClothingAssetFactory.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ClothingAssetFactory.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ClothingAssetFactory.md#executeubergraph)
- [GetClass](ue_ue.ClothingAssetFactory.md#getclass)
- [GetName](ue_ue.ClothingAssetFactory.md#getname)
- [GetOuter](ue_ue.ClothingAssetFactory.md#getouter)
- [GetWorld](ue_ue.ClothingAssetFactory.md#getworld)
- [Find](ue_ue.ClothingAssetFactory.md#find)
- [Load](ue_ue.ClothingAssetFactory.md#load)
- [StaticClass](ue_ue.ClothingAssetFactory.md#staticclass)

## Constructors

### constructor

• **new ClothingAssetFactory**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ClothingAssetFactoryBase](ue_ue.ClothingAssetFactoryBase.md).[constructor](ue_ue.ClothingAssetFactoryBase.md#constructor)

## Properties

### \_\_tid\_ClothingAssetFactoryBase\_\_

• **\_\_tid\_ClothingAssetFactoryBase\_\_**: `boolean`

#### Inherited from

[ClothingAssetFactoryBase](ue_ue.ClothingAssetFactoryBase.md).[__tid_ClothingAssetFactoryBase__](ue_ue.ClothingAssetFactoryBase.md#__tid_clothingassetfactorybase__)

___

### \_\_tid\_ClothingAssetFactory\_\_

• **\_\_tid\_ClothingAssetFactory\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ClothingAssetFactoryBase](ue_ue.ClothingAssetFactoryBase.md).[__tid_Object__](ue_ue.ClothingAssetFactoryBase.md#__tid_object__)

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

[ClothingAssetFactoryBase](ue_ue.ClothingAssetFactoryBase.md).[CreateDefaultSubobject](ue_ue.ClothingAssetFactoryBase.md#createdefaultsubobject)

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

[ClothingAssetFactoryBase](ue_ue.ClothingAssetFactoryBase.md).[ExecuteUbergraph](ue_ue.ClothingAssetFactoryBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ClothingAssetFactoryBase](ue_ue.ClothingAssetFactoryBase.md).[GetClass](ue_ue.ClothingAssetFactoryBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ClothingAssetFactoryBase](ue_ue.ClothingAssetFactoryBase.md).[GetName](ue_ue.ClothingAssetFactoryBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ClothingAssetFactoryBase](ue_ue.ClothingAssetFactoryBase.md).[GetOuter](ue_ue.ClothingAssetFactoryBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ClothingAssetFactoryBase](ue_ue.ClothingAssetFactoryBase.md).[GetWorld](ue_ue.ClothingAssetFactoryBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ClothingAssetFactory`](ue_ue.ClothingAssetFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ClothingAssetFactory`](ue_ue.ClothingAssetFactory.md)

#### Overrides

[ClothingAssetFactoryBase](ue_ue.ClothingAssetFactoryBase.md).[Find](ue_ue.ClothingAssetFactoryBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ClothingAssetFactory`](ue_ue.ClothingAssetFactory.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ClothingAssetFactory`](ue_ue.ClothingAssetFactory.md)

#### Overrides

[ClothingAssetFactoryBase](ue_ue.ClothingAssetFactoryBase.md).[Load](ue_ue.ClothingAssetFactoryBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ClothingAssetFactoryBase](ue_ue.ClothingAssetFactoryBase.md).[StaticClass](ue_ue.ClothingAssetFactoryBase.md#staticclass)
