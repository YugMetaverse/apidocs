[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CloudStorageBase

# Class: CloudStorageBase

[ue/ue](../modules/ue_ue.md).CloudStorageBase

## Hierarchy

- [`PlatformInterfaceBase`](ue_ue.PlatformInterfaceBase.md)

  ↳ **`CloudStorageBase`**

## Table of contents

### Constructors

- [constructor](ue_ue.CloudStorageBase.md#constructor)

### Properties

- [AllDelegates](ue_ue.CloudStorageBase.md#alldelegates)
- [LocalCloudFiles](ue_ue.CloudStorageBase.md#localcloudfiles)
- [\_\_tid\_CloudStorageBase\_\_](ue_ue.CloudStorageBase.md#__tid_cloudstoragebase__)
- [\_\_tid\_Object\_\_](ue_ue.CloudStorageBase.md#__tid_object__)
- [\_\_tid\_PlatformInterfaceBase\_\_](ue_ue.CloudStorageBase.md#__tid_platforminterfacebase__)
- [bSuppressDelegateCalls](ue_ue.CloudStorageBase.md#bsuppressdelegatecalls)

### Methods

- [CreateDefaultSubobject](ue_ue.CloudStorageBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.CloudStorageBase.md#executeubergraph)
- [GetClass](ue_ue.CloudStorageBase.md#getclass)
- [GetName](ue_ue.CloudStorageBase.md#getname)
- [GetOuter](ue_ue.CloudStorageBase.md#getouter)
- [GetWorld](ue_ue.CloudStorageBase.md#getworld)
- [Find](ue_ue.CloudStorageBase.md#find)
- [Load](ue_ue.CloudStorageBase.md#load)
- [StaticClass](ue_ue.CloudStorageBase.md#staticclass)

## Constructors

### constructor

• **new CloudStorageBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[constructor](ue_ue.PlatformInterfaceBase.md#constructor)

## Properties

### AllDelegates

• **AllDelegates**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DelegateArray`](ue_ue.DelegateArray.md)\>

#### Inherited from

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[AllDelegates](ue_ue.PlatformInterfaceBase.md#alldelegates)

___

### LocalCloudFiles

• **LocalCloudFiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### \_\_tid\_CloudStorageBase\_\_

• **\_\_tid\_CloudStorageBase\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[__tid_Object__](ue_ue.PlatformInterfaceBase.md#__tid_object__)

___

### \_\_tid\_PlatformInterfaceBase\_\_

• **\_\_tid\_PlatformInterfaceBase\_\_**: `boolean`

#### Inherited from

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[__tid_PlatformInterfaceBase__](ue_ue.PlatformInterfaceBase.md#__tid_platforminterfacebase__)

___

### bSuppressDelegateCalls

• **bSuppressDelegateCalls**: `boolean`

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

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[CreateDefaultSubobject](ue_ue.PlatformInterfaceBase.md#createdefaultsubobject)

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

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[ExecuteUbergraph](ue_ue.PlatformInterfaceBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[GetClass](ue_ue.PlatformInterfaceBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[GetName](ue_ue.PlatformInterfaceBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[GetOuter](ue_ue.PlatformInterfaceBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[GetWorld](ue_ue.PlatformInterfaceBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CloudStorageBase`](ue_ue.CloudStorageBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CloudStorageBase`](ue_ue.CloudStorageBase.md)

#### Overrides

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[Find](ue_ue.PlatformInterfaceBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`CloudStorageBase`](ue_ue.CloudStorageBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CloudStorageBase`](ue_ue.CloudStorageBase.md)

#### Overrides

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[Load](ue_ue.PlatformInterfaceBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[StaticClass](ue_ue.PlatformInterfaceBase.md#staticclass)
