[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TwitterIntegrationBase

# Class: TwitterIntegrationBase

[ue/ue](../modules/ue_ue.md).TwitterIntegrationBase

## Hierarchy

- [`PlatformInterfaceBase`](ue_ue.PlatformInterfaceBase.md)

  ↳ **`TwitterIntegrationBase`**

## Table of contents

### Constructors

- [constructor](ue_ue.TwitterIntegrationBase.md#constructor)

### Properties

- [AllDelegates](ue_ue.TwitterIntegrationBase.md#alldelegates)
- [\_\_tid\_Object\_\_](ue_ue.TwitterIntegrationBase.md#__tid_object__)
- [\_\_tid\_PlatformInterfaceBase\_\_](ue_ue.TwitterIntegrationBase.md#__tid_platforminterfacebase__)
- [\_\_tid\_TwitterIntegrationBase\_\_](ue_ue.TwitterIntegrationBase.md#__tid_twitterintegrationbase__)

### Methods

- [AuthorizeAccounts](ue_ue.TwitterIntegrationBase.md#authorizeaccounts)
- [CanShowTweetUI](ue_ue.TwitterIntegrationBase.md#canshowtweetui)
- [CreateDefaultSubobject](ue_ue.TwitterIntegrationBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TwitterIntegrationBase.md#executeubergraph)
- [GetAccountName](ue_ue.TwitterIntegrationBase.md#getaccountname)
- [GetClass](ue_ue.TwitterIntegrationBase.md#getclass)
- [GetName](ue_ue.TwitterIntegrationBase.md#getname)
- [GetNumAccounts](ue_ue.TwitterIntegrationBase.md#getnumaccounts)
- [GetOuter](ue_ue.TwitterIntegrationBase.md#getouter)
- [GetWorld](ue_ue.TwitterIntegrationBase.md#getworld)
- [Init](ue_ue.TwitterIntegrationBase.md#init)
- [ShowTweetUI](ue_ue.TwitterIntegrationBase.md#showtweetui)
- [TwitterRequest](ue_ue.TwitterIntegrationBase.md#twitterrequest)
- [Find](ue_ue.TwitterIntegrationBase.md#find)
- [Load](ue_ue.TwitterIntegrationBase.md#load)
- [StaticClass](ue_ue.TwitterIntegrationBase.md#staticclass)

## Constructors

### constructor

• **new TwitterIntegrationBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[constructor](ue_ue.PlatformInterfaceBase.md#constructor)

#### Defined in

[ue/ue.d.ts:64328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64328)

## Properties

### AllDelegates

• **AllDelegates**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`DelegateArray`](ue_ue.DelegateArray.md)\>

#### Inherited from

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[AllDelegates](ue_ue.PlatformInterfaceBase.md#alldelegates)

#### Defined in

[ue/ue.d.ts:28085](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L28085)

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

### \_\_tid\_TwitterIntegrationBase\_\_

• **\_\_tid\_TwitterIntegrationBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:64340](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64340)

## Methods

### AuthorizeAccounts

▸ **AuthorizeAccounts**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:64329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64329)

___

### CanShowTweetUI

▸ **CanShowTweetUI**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:64330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64330)

___

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

### GetAccountName

▸ **GetAccountName**(`AccountIndex`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AccountIndex` | `number` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:64331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64331)

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

### GetNumAccounts

▸ **GetNumAccounts**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:64332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64332)

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

### Init

▸ **Init**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:64333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64333)

___

### ShowTweetUI

▸ **ShowTweetUI**(`InitialMessage`, `URL`, `Picture`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InitialMessage` | `string` |
| `URL` | `string` |
| `Picture` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:64334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64334)

___

### TwitterRequest

▸ **TwitterRequest**(`URL`, `ParamKeysAndValues`, `RequestMethod`, `AccountIndex`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `URL` | `string` |
| `ParamKeysAndValues` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `RequestMethod` | [`ETwitterRequestMethod`](../enums/ue_ue.ETwitterRequestMethod.md) |
| `AccountIndex` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:64335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64335)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TwitterIntegrationBase`](ue_ue.TwitterIntegrationBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TwitterIntegrationBase`](ue_ue.TwitterIntegrationBase.md)

#### Overrides

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[Find](ue_ue.PlatformInterfaceBase.md#find)

#### Defined in

[ue/ue.d.ts:64337](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64337)

___

### Load

▸ `Static` **Load**(`InName`): [`TwitterIntegrationBase`](ue_ue.TwitterIntegrationBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TwitterIntegrationBase`](ue_ue.TwitterIntegrationBase.md)

#### Overrides

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[Load](ue_ue.PlatformInterfaceBase.md#load)

#### Defined in

[ue/ue.d.ts:64338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64338)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PlatformInterfaceBase](ue_ue.PlatformInterfaceBase.md).[StaticClass](ue_ue.PlatformInterfaceBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:64336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L64336)
