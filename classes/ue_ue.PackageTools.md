[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PackageTools

# Class: PackageTools

[ue/ue](../modules/ue_ue.md).PackageTools

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PackageTools`**

## Table of contents

### Constructors

- [constructor](ue_ue.PackageTools.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.PackageTools.md#__tid_object__)
- [\_\_tid\_PackageTools\_\_](ue_ue.PackageTools.md#__tid_packagetools__)

### Methods

- [CreateDefaultSubobject](ue_ue.PackageTools.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PackageTools.md#executeubergraph)
- [GetClass](ue_ue.PackageTools.md#getclass)
- [GetName](ue_ue.PackageTools.md#getname)
- [GetOuter](ue_ue.PackageTools.md#getouter)
- [GetWorld](ue_ue.PackageTools.md#getworld)
- [Find](ue_ue.PackageTools.md#find)
- [Load](ue_ue.PackageTools.md#load)
- [SanitizePackageName](ue_ue.PackageTools.md#sanitizepackagename)
- [StaticClass](ue_ue.PackageTools.md#staticclass)

## Constructors

### constructor

• **new PackageTools**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:54332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54332)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PackageTools\_\_

• **\_\_tid\_PackageTools\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:54338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54338)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PackageTools`](ue_ue.PackageTools.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PackageTools`](ue_ue.PackageTools.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:54335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54335)

___

### Load

▸ `Static` **Load**(`InName`): [`PackageTools`](ue_ue.PackageTools.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PackageTools`](ue_ue.PackageTools.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:54336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54336)

___

### SanitizePackageName

▸ `Static` **SanitizePackageName**(`InPackageName`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPackageName` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:54333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54333)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:54334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L54334)
