[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / UnitTestPackageMap

# Class: UnitTestPackageMap

[ue/ue](../modules/ue_ue.md).UnitTestPackageMap

## Hierarchy

- [`PackageMapClient`](ue_ue.PackageMapClient.md)

  ↳ **`UnitTestPackageMap`**

## Table of contents

### Constructors

- [constructor](ue_ue.UnitTestPackageMap.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.UnitTestPackageMap.md#__tid_object__)
- [\_\_tid\_PackageMapClient\_\_](ue_ue.UnitTestPackageMap.md#__tid_packagemapclient__)
- [\_\_tid\_PackageMap\_\_](ue_ue.UnitTestPackageMap.md#__tid_packagemap__)
- [\_\_tid\_UnitTestPackageMap\_\_](ue_ue.UnitTestPackageMap.md#__tid_unittestpackagemap__)

### Methods

- [CreateDefaultSubobject](ue_ue.UnitTestPackageMap.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.UnitTestPackageMap.md#executeubergraph)
- [GetClass](ue_ue.UnitTestPackageMap.md#getclass)
- [GetName](ue_ue.UnitTestPackageMap.md#getname)
- [GetOuter](ue_ue.UnitTestPackageMap.md#getouter)
- [GetWorld](ue_ue.UnitTestPackageMap.md#getworld)
- [Find](ue_ue.UnitTestPackageMap.md#find)
- [Load](ue_ue.UnitTestPackageMap.md#load)
- [StaticClass](ue_ue.UnitTestPackageMap.md#staticclass)

## Constructors

### constructor

• **new UnitTestPackageMap**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PackageMapClient](ue_ue.PackageMapClient.md).[constructor](ue_ue.PackageMapClient.md#constructor)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PackageMapClient](ue_ue.PackageMapClient.md).[__tid_Object__](ue_ue.PackageMapClient.md#__tid_object__)

___

### \_\_tid\_PackageMapClient\_\_

• **\_\_tid\_PackageMapClient\_\_**: `boolean`

#### Inherited from

[PackageMapClient](ue_ue.PackageMapClient.md).[__tid_PackageMapClient__](ue_ue.PackageMapClient.md#__tid_packagemapclient__)

___

### \_\_tid\_PackageMap\_\_

• **\_\_tid\_PackageMap\_\_**: `boolean`

#### Inherited from

[PackageMapClient](ue_ue.PackageMapClient.md).[__tid_PackageMap__](ue_ue.PackageMapClient.md#__tid_packagemap__)

___

### \_\_tid\_UnitTestPackageMap\_\_

• **\_\_tid\_UnitTestPackageMap\_\_**: `boolean`

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

[PackageMapClient](ue_ue.PackageMapClient.md).[CreateDefaultSubobject](ue_ue.PackageMapClient.md#createdefaultsubobject)

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

[PackageMapClient](ue_ue.PackageMapClient.md).[ExecuteUbergraph](ue_ue.PackageMapClient.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PackageMapClient](ue_ue.PackageMapClient.md).[GetClass](ue_ue.PackageMapClient.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PackageMapClient](ue_ue.PackageMapClient.md).[GetName](ue_ue.PackageMapClient.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PackageMapClient](ue_ue.PackageMapClient.md).[GetOuter](ue_ue.PackageMapClient.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PackageMapClient](ue_ue.PackageMapClient.md).[GetWorld](ue_ue.PackageMapClient.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`UnitTestPackageMap`](ue_ue.UnitTestPackageMap.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`UnitTestPackageMap`](ue_ue.UnitTestPackageMap.md)

#### Overrides

[PackageMapClient](ue_ue.PackageMapClient.md).[Find](ue_ue.PackageMapClient.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`UnitTestPackageMap`](ue_ue.UnitTestPackageMap.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`UnitTestPackageMap`](ue_ue.UnitTestPackageMap.md)

#### Overrides

[PackageMapClient](ue_ue.PackageMapClient.md).[Load](ue_ue.PackageMapClient.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PackageMapClient](ue_ue.PackageMapClient.md).[StaticClass](ue_ue.PackageMapClient.md#staticclass)
