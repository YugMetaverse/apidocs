[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PackageMapClient

# Class: PackageMapClient

[ue/ue](../modules/ue_ue.md).PackageMapClient

## Hierarchy

- [`PackageMap`](ue_ue.PackageMap.md)

  ↳ **`PackageMapClient`**

  ↳↳ [`UnitTestPackageMap`](ue_ue.UnitTestPackageMap.md)

## Table of contents

### Constructors

- [constructor](ue_ue.PackageMapClient.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.PackageMapClient.md#__tid_object__)
- [\_\_tid\_PackageMapClient\_\_](ue_ue.PackageMapClient.md#__tid_packagemapclient__)
- [\_\_tid\_PackageMap\_\_](ue_ue.PackageMapClient.md#__tid_packagemap__)

### Methods

- [CreateDefaultSubobject](ue_ue.PackageMapClient.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PackageMapClient.md#executeubergraph)
- [GetClass](ue_ue.PackageMapClient.md#getclass)
- [GetName](ue_ue.PackageMapClient.md#getname)
- [GetOuter](ue_ue.PackageMapClient.md#getouter)
- [GetWorld](ue_ue.PackageMapClient.md#getworld)
- [Find](ue_ue.PackageMapClient.md#find)
- [Load](ue_ue.PackageMapClient.md#load)
- [StaticClass](ue_ue.PackageMapClient.md#staticclass)

## Constructors

### constructor

• **new PackageMapClient**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PackageMap](ue_ue.PackageMap.md).[constructor](ue_ue.PackageMap.md#constructor)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PackageMap](ue_ue.PackageMap.md).[__tid_Object__](ue_ue.PackageMap.md#__tid_object__)

___

### \_\_tid\_PackageMapClient\_\_

• **\_\_tid\_PackageMapClient\_\_**: `boolean`

___

### \_\_tid\_PackageMap\_\_

• **\_\_tid\_PackageMap\_\_**: `boolean`

#### Inherited from

[PackageMap](ue_ue.PackageMap.md).[__tid_PackageMap__](ue_ue.PackageMap.md#__tid_packagemap__)

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

[PackageMap](ue_ue.PackageMap.md).[CreateDefaultSubobject](ue_ue.PackageMap.md#createdefaultsubobject)

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

[PackageMap](ue_ue.PackageMap.md).[ExecuteUbergraph](ue_ue.PackageMap.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PackageMap](ue_ue.PackageMap.md).[GetClass](ue_ue.PackageMap.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PackageMap](ue_ue.PackageMap.md).[GetName](ue_ue.PackageMap.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PackageMap](ue_ue.PackageMap.md).[GetOuter](ue_ue.PackageMap.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PackageMap](ue_ue.PackageMap.md).[GetWorld](ue_ue.PackageMap.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PackageMapClient`](ue_ue.PackageMapClient.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PackageMapClient`](ue_ue.PackageMapClient.md)

#### Overrides

[PackageMap](ue_ue.PackageMap.md).[Find](ue_ue.PackageMap.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PackageMapClient`](ue_ue.PackageMapClient.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PackageMapClient`](ue_ue.PackageMapClient.md)

#### Overrides

[PackageMap](ue_ue.PackageMap.md).[Load](ue_ue.PackageMap.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PackageMap](ue_ue.PackageMap.md).[StaticClass](ue_ue.PackageMap.md#staticclass)
