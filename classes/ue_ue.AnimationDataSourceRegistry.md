[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimationDataSourceRegistry

# Class: AnimationDataSourceRegistry

[ue/ue](../modules/ue_ue.md).AnimationDataSourceRegistry

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AnimationDataSourceRegistry`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimationDataSourceRegistry.md#constructor)

### Properties

- [DataSources](ue_ue.AnimationDataSourceRegistry.md#datasources)
- [\_\_tid\_AnimationDataSourceRegistry\_\_](ue_ue.AnimationDataSourceRegistry.md#__tid_animationdatasourceregistry__)
- [\_\_tid\_Object\_\_](ue_ue.AnimationDataSourceRegistry.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimationDataSourceRegistry.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimationDataSourceRegistry.md#executeubergraph)
- [GetClass](ue_ue.AnimationDataSourceRegistry.md#getclass)
- [GetName](ue_ue.AnimationDataSourceRegistry.md#getname)
- [GetOuter](ue_ue.AnimationDataSourceRegistry.md#getouter)
- [GetWorld](ue_ue.AnimationDataSourceRegistry.md#getworld)
- [Find](ue_ue.AnimationDataSourceRegistry.md#find)
- [Load](ue_ue.AnimationDataSourceRegistry.md#load)
- [StaticClass](ue_ue.AnimationDataSourceRegistry.md#staticclass)

## Constructors

### constructor

• **new AnimationDataSourceRegistry**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### DataSources

• **DataSources**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`Object`](ue_ue.Object.md)\>

___

### \_\_tid\_AnimationDataSourceRegistry\_\_

• **\_\_tid\_AnimationDataSourceRegistry\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimationDataSourceRegistry`](ue_ue.AnimationDataSourceRegistry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimationDataSourceRegistry`](ue_ue.AnimationDataSourceRegistry.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimationDataSourceRegistry`](ue_ue.AnimationDataSourceRegistry.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimationDataSourceRegistry`](ue_ue.AnimationDataSourceRegistry.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
