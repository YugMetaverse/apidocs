[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MobileInstalledContent

# Class: MobileInstalledContent

[ue/ue](../modules/ue_ue.md).MobileInstalledContent

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MobileInstalledContent`**

  ↳↳ [`MobilePendingContent`](ue_ue.MobilePendingContent.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MobileInstalledContent.md#constructor)

### Properties

- [\_\_tid\_MobileInstalledContent\_\_](ue_ue.MobileInstalledContent.md#__tid_mobileinstalledcontent__)
- [\_\_tid\_Object\_\_](ue_ue.MobileInstalledContent.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MobileInstalledContent.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MobileInstalledContent.md#executeubergraph)
- [GetClass](ue_ue.MobileInstalledContent.md#getclass)
- [GetDiskFreeSpace](ue_ue.MobileInstalledContent.md#getdiskfreespace)
- [GetInstalledContentSize](ue_ue.MobileInstalledContent.md#getinstalledcontentsize)
- [GetName](ue_ue.MobileInstalledContent.md#getname)
- [GetOuter](ue_ue.MobileInstalledContent.md#getouter)
- [GetWorld](ue_ue.MobileInstalledContent.md#getworld)
- [Mount](ue_ue.MobileInstalledContent.md#mount)
- [Find](ue_ue.MobileInstalledContent.md#find)
- [Load](ue_ue.MobileInstalledContent.md#load)
- [StaticClass](ue_ue.MobileInstalledContent.md#staticclass)

## Constructors

### constructor

• **new MobileInstalledContent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_MobileInstalledContent\_\_

• **\_\_tid\_MobileInstalledContent\_\_**: `boolean`

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

### GetDiskFreeSpace

▸ **GetDiskFreeSpace**(): `number`

#### Returns

`number`

___

### GetInstalledContentSize

▸ **GetInstalledContentSize**(): `number`

#### Returns

`number`

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

### Mount

▸ **Mount**(`PakOrder`, `MountPoint`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PakOrder` | `number` |
| `MountPoint` | `string` |

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MobileInstalledContent`](ue_ue.MobileInstalledContent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MobileInstalledContent`](ue_ue.MobileInstalledContent.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MobileInstalledContent`](ue_ue.MobileInstalledContent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MobileInstalledContent`](ue_ue.MobileInstalledContent.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
