[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EnvQueryContext\_Item

# Class: EnvQueryContext\_Item

[ue/ue](../modules/ue_ue.md).EnvQueryContext_Item

## Hierarchy

- [`EnvQueryContext`](ue_ue.EnvQueryContext.md)

  ↳ **`EnvQueryContext_Item`**

## Table of contents

### Constructors

- [constructor](ue_ue.EnvQueryContext_Item.md#constructor)

### Properties

- [\_\_tid\_EnvQueryContext\_Item\_\_](ue_ue.EnvQueryContext_Item.md#__tid_envquerycontext_item__)
- [\_\_tid\_EnvQueryContext\_\_](ue_ue.EnvQueryContext_Item.md#__tid_envquerycontext__)
- [\_\_tid\_Object\_\_](ue_ue.EnvQueryContext_Item.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EnvQueryContext_Item.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EnvQueryContext_Item.md#executeubergraph)
- [GetClass](ue_ue.EnvQueryContext_Item.md#getclass)
- [GetName](ue_ue.EnvQueryContext_Item.md#getname)
- [GetOuter](ue_ue.EnvQueryContext_Item.md#getouter)
- [GetWorld](ue_ue.EnvQueryContext_Item.md#getworld)
- [Find](ue_ue.EnvQueryContext_Item.md#find)
- [Load](ue_ue.EnvQueryContext_Item.md#load)
- [StaticClass](ue_ue.EnvQueryContext_Item.md#staticclass)

## Constructors

### constructor

• **new EnvQueryContext_Item**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EnvQueryContext](ue_ue.EnvQueryContext.md).[constructor](ue_ue.EnvQueryContext.md#constructor)

## Properties

### \_\_tid\_EnvQueryContext\_Item\_\_

• **\_\_tid\_EnvQueryContext\_Item\_\_**: `boolean`

___

### \_\_tid\_EnvQueryContext\_\_

• **\_\_tid\_EnvQueryContext\_\_**: `boolean`

#### Inherited from

[EnvQueryContext](ue_ue.EnvQueryContext.md).[__tid_EnvQueryContext__](ue_ue.EnvQueryContext.md#__tid_envquerycontext__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EnvQueryContext](ue_ue.EnvQueryContext.md).[__tid_Object__](ue_ue.EnvQueryContext.md#__tid_object__)

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

[EnvQueryContext](ue_ue.EnvQueryContext.md).[CreateDefaultSubobject](ue_ue.EnvQueryContext.md#createdefaultsubobject)

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

[EnvQueryContext](ue_ue.EnvQueryContext.md).[ExecuteUbergraph](ue_ue.EnvQueryContext.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EnvQueryContext](ue_ue.EnvQueryContext.md).[GetClass](ue_ue.EnvQueryContext.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EnvQueryContext](ue_ue.EnvQueryContext.md).[GetName](ue_ue.EnvQueryContext.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EnvQueryContext](ue_ue.EnvQueryContext.md).[GetOuter](ue_ue.EnvQueryContext.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EnvQueryContext](ue_ue.EnvQueryContext.md).[GetWorld](ue_ue.EnvQueryContext.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EnvQueryContext_Item`](ue_ue.EnvQueryContext_Item.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EnvQueryContext_Item`](ue_ue.EnvQueryContext_Item.md)

#### Overrides

[EnvQueryContext](ue_ue.EnvQueryContext.md).[Find](ue_ue.EnvQueryContext.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EnvQueryContext_Item`](ue_ue.EnvQueryContext_Item.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EnvQueryContext_Item`](ue_ue.EnvQueryContext_Item.md)

#### Overrides

[EnvQueryContext](ue_ue.EnvQueryContext.md).[Load](ue_ue.EnvQueryContext.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EnvQueryContext](ue_ue.EnvQueryContext.md).[StaticClass](ue_ue.EnvQueryContext.md#staticclass)
