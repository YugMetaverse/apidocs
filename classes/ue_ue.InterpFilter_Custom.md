[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpFilter\_Custom

# Class: InterpFilter\_Custom

[ue/ue](../modules/ue_ue.md).InterpFilter_Custom

## Hierarchy

- [`InterpFilter`](ue_ue.InterpFilter.md)

  ↳ **`InterpFilter_Custom`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpFilter_Custom.md#constructor)

### Properties

- [Caption](ue_ue.InterpFilter_Custom.md#caption)
- [GroupsToInclude](ue_ue.InterpFilter_Custom.md#groupstoinclude)
- [\_\_tid\_InterpFilter\_Custom\_\_](ue_ue.InterpFilter_Custom.md#__tid_interpfilter_custom__)
- [\_\_tid\_InterpFilter\_\_](ue_ue.InterpFilter_Custom.md#__tid_interpfilter__)
- [\_\_tid\_Object\_\_](ue_ue.InterpFilter_Custom.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpFilter_Custom.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpFilter_Custom.md#executeubergraph)
- [GetClass](ue_ue.InterpFilter_Custom.md#getclass)
- [GetName](ue_ue.InterpFilter_Custom.md#getname)
- [GetOuter](ue_ue.InterpFilter_Custom.md#getouter)
- [GetWorld](ue_ue.InterpFilter_Custom.md#getworld)
- [Find](ue_ue.InterpFilter_Custom.md#find)
- [Load](ue_ue.InterpFilter_Custom.md#load)
- [StaticClass](ue_ue.InterpFilter_Custom.md#staticclass)

## Constructors

### constructor

• **new InterpFilter_Custom**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InterpFilter](ue_ue.InterpFilter.md).[constructor](ue_ue.InterpFilter.md#constructor)

## Properties

### Caption

• **Caption**: `string`

#### Inherited from

[InterpFilter](ue_ue.InterpFilter.md).[Caption](ue_ue.InterpFilter.md#caption)

___

### GroupsToInclude

• **GroupsToInclude**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpGroup`](ue_ue.InterpGroup.md)\>

___

### \_\_tid\_InterpFilter\_Custom\_\_

• **\_\_tid\_InterpFilter\_Custom\_\_**: `boolean`

___

### \_\_tid\_InterpFilter\_\_

• **\_\_tid\_InterpFilter\_\_**: `boolean`

#### Inherited from

[InterpFilter](ue_ue.InterpFilter.md).[__tid_InterpFilter__](ue_ue.InterpFilter.md#__tid_interpfilter__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InterpFilter](ue_ue.InterpFilter.md).[__tid_Object__](ue_ue.InterpFilter.md#__tid_object__)

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

[InterpFilter](ue_ue.InterpFilter.md).[CreateDefaultSubobject](ue_ue.InterpFilter.md#createdefaultsubobject)

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

[InterpFilter](ue_ue.InterpFilter.md).[ExecuteUbergraph](ue_ue.InterpFilter.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InterpFilter](ue_ue.InterpFilter.md).[GetClass](ue_ue.InterpFilter.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InterpFilter](ue_ue.InterpFilter.md).[GetName](ue_ue.InterpFilter.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InterpFilter](ue_ue.InterpFilter.md).[GetOuter](ue_ue.InterpFilter.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InterpFilter](ue_ue.InterpFilter.md).[GetWorld](ue_ue.InterpFilter.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpFilter_Custom`](ue_ue.InterpFilter_Custom.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpFilter_Custom`](ue_ue.InterpFilter_Custom.md)

#### Overrides

[InterpFilter](ue_ue.InterpFilter.md).[Find](ue_ue.InterpFilter.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpFilter_Custom`](ue_ue.InterpFilter_Custom.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpFilter_Custom`](ue_ue.InterpFilter_Custom.md)

#### Overrides

[InterpFilter](ue_ue.InterpFilter.md).[Load](ue_ue.InterpFilter.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpFilter](ue_ue.InterpFilter.md).[StaticClass](ue_ue.InterpFilter.md#staticclass)
