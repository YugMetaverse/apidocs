[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PackageMap

# Class: PackageMap

[ue/ue](../modules/ue_ue.md).PackageMap

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PackageMap`**

  ↳↳ [`PackageMapClient`](ue_ue.PackageMapClient.md)

## Table of contents

### Constructors

- [constructor](ue_ue.PackageMap.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.PackageMap.md#__tid_object__)
- [\_\_tid\_PackageMap\_\_](ue_ue.PackageMap.md#__tid_packagemap__)

### Methods

- [CreateDefaultSubobject](ue_ue.PackageMap.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PackageMap.md#executeubergraph)
- [GetClass](ue_ue.PackageMap.md#getclass)
- [GetName](ue_ue.PackageMap.md#getname)
- [GetOuter](ue_ue.PackageMap.md#getouter)
- [GetWorld](ue_ue.PackageMap.md#getworld)
- [Find](ue_ue.PackageMap.md#find)
- [Load](ue_ue.PackageMap.md#load)
- [StaticClass](ue_ue.PackageMap.md#staticclass)

## Constructors

### constructor

• **new PackageMap**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:10427](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10427)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PackageMap\_\_

• **\_\_tid\_PackageMap\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:10432](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10432)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PackageMap`](ue_ue.PackageMap.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PackageMap`](ue_ue.PackageMap.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:10429](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10429)

___

### Load

▸ `Static` **Load**(`InName`): [`PackageMap`](ue_ue.PackageMap.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PackageMap`](ue_ue.PackageMap.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:10430](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10430)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:10428](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L10428)
