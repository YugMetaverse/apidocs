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

#### Defined in

[ue/ue.d.ts:28094](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28094)

## Properties

### AllDelegates

• **AllDelegates**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DelegateArray`](ue_ue.DelegateArray.md)\>

#### Inherited from

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[AllDelegates](ue_ue.PlatformInterfaceBase.md#alldelegates)

#### Defined in

[ue/ue.d.ts:28085](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28085)

___

### LocalCloudFiles

• **LocalCloudFiles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:28095](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28095)

___

### \_\_tid\_CloudStorageBase\_\_

• **\_\_tid\_CloudStorageBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:28101](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28101)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[__tid_Object__](ue_ue.PlatformInterfaceBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PlatformInterfaceBase\_\_

• **\_\_tid\_PlatformInterfaceBase\_\_**: `boolean`

#### Inherited from

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[__tid_PlatformInterfaceBase__](ue_ue.PlatformInterfaceBase.md#__tid_platforminterfacebase__)

#### Defined in

[ue/ue.d.ts:28090](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28090)

___

### bSuppressDelegateCalls

• **bSuppressDelegateCalls**: `boolean`

#### Defined in

[ue/ue.d.ts:28096](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28096)

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

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[ExecuteUbergraph](ue_ue.PlatformInterfaceBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[GetClass](ue_ue.PlatformInterfaceBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[GetName](ue_ue.PlatformInterfaceBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[GetOuter](ue_ue.PlatformInterfaceBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[GetWorld](ue_ue.PlatformInterfaceBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:28098](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28098)

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

#### Defined in

[ue/ue.d.ts:28099](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28099)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[StaticClass](ue_ue.PlatformInterfaceBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:28097](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28097)
