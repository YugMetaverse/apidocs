[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UnitTestBase

# Class: UnitTestBase

[ue/ue](../modules/ue_ue.md).UnitTestBase

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`UnitTestBase`**

  ↳↳ [`UnitTest`](ue_ue.UnitTest.md)

## Table of contents

### Constructors

- [constructor](ue_ue.UnitTestBase.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.UnitTestBase.md#__tid_object__)
- [\_\_tid\_UnitTestBase\_\_](ue_ue.UnitTestBase.md#__tid_unittestbase__)

### Methods

- [CreateDefaultSubobject](ue_ue.UnitTestBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UnitTestBase.md#executeubergraph)
- [GetClass](ue_ue.UnitTestBase.md#getclass)
- [GetName](ue_ue.UnitTestBase.md#getname)
- [GetOuter](ue_ue.UnitTestBase.md#getouter)
- [GetWorld](ue_ue.UnitTestBase.md#getworld)
- [Find](ue_ue.UnitTestBase.md#find)
- [Load](ue_ue.UnitTestBase.md#load)
- [StaticClass](ue_ue.UnitTestBase.md#staticclass)

## Constructors

### constructor

• **new UnitTestBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:27518](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27518)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_UnitTestBase\_\_

• **\_\_tid\_UnitTestBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:27523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27523)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UnitTestBase`](ue_ue.UnitTestBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UnitTestBase`](ue_ue.UnitTestBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:27520](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27520)

___

### Load

▸ `Static` **Load**(`InName`): [`UnitTestBase`](ue_ue.UnitTestBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UnitTestBase`](ue_ue.UnitTestBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:27521](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27521)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:27519](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L27519)
