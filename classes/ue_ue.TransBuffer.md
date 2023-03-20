[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TransBuffer

# Class: TransBuffer

[ue/ue](../modules/ue_ue.md).TransBuffer

## Hierarchy

- [`Transactor`](ue_ue.Transactor.md)

  ↳ **`TransBuffer`**

## Table of contents

### Constructors

- [constructor](ue_ue.TransBuffer.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.TransBuffer.md#__tid_object__)
- [\_\_tid\_TransBuffer\_\_](ue_ue.TransBuffer.md#__tid_transbuffer__)
- [\_\_tid\_Transactor\_\_](ue_ue.TransBuffer.md#__tid_transactor__)

### Methods

- [CreateDefaultSubobject](ue_ue.TransBuffer.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TransBuffer.md#executeubergraph)
- [GetClass](ue_ue.TransBuffer.md#getclass)
- [GetName](ue_ue.TransBuffer.md#getname)
- [GetOuter](ue_ue.TransBuffer.md#getouter)
- [GetWorld](ue_ue.TransBuffer.md#getworld)
- [Find](ue_ue.TransBuffer.md#find)
- [Load](ue_ue.TransBuffer.md#load)
- [StaticClass](ue_ue.TransBuffer.md#staticclass)

## Constructors

### constructor

• **new TransBuffer**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Transactor](ue_ue.Transactor.md).[constructor](ue_ue.Transactor.md#constructor)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Transactor](ue_ue.Transactor.md).[__tid_Object__](ue_ue.Transactor.md#__tid_object__)

___

### \_\_tid\_TransBuffer\_\_

• **\_\_tid\_TransBuffer\_\_**: `boolean`

___

### \_\_tid\_Transactor\_\_

• **\_\_tid\_Transactor\_\_**: `boolean`

#### Inherited from

[Transactor](ue_ue.Transactor.md).[__tid_Transactor__](ue_ue.Transactor.md#__tid_transactor__)

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

[Transactor](ue_ue.Transactor.md).[CreateDefaultSubobject](ue_ue.Transactor.md#createdefaultsubobject)

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

[Transactor](ue_ue.Transactor.md).[ExecuteUbergraph](ue_ue.Transactor.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Transactor](ue_ue.Transactor.md).[GetClass](ue_ue.Transactor.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Transactor](ue_ue.Transactor.md).[GetName](ue_ue.Transactor.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Transactor](ue_ue.Transactor.md).[GetOuter](ue_ue.Transactor.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Transactor](ue_ue.Transactor.md).[GetWorld](ue_ue.Transactor.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TransBuffer`](ue_ue.TransBuffer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TransBuffer`](ue_ue.TransBuffer.md)

#### Overrides

[Transactor](ue_ue.Transactor.md).[Find](ue_ue.Transactor.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TransBuffer`](ue_ue.TransBuffer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TransBuffer`](ue_ue.TransBuffer.md)

#### Overrides

[Transactor](ue_ue.Transactor.md).[Load](ue_ue.Transactor.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Transactor](ue_ue.Transactor.md).[StaticClass](ue_ue.Transactor.md#staticclass)
