[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BlackboardData

# Class: BlackboardData

[ue/ue](../modules/ue_ue.md).BlackboardData

## Hierarchy

- [`DataAsset`](ue_ue.DataAsset.md)

  ↳ **`BlackboardData`**

## Table of contents

### Constructors

- [constructor](ue_ue.BlackboardData.md#constructor)

### Properties

- [Keys](ue_ue.BlackboardData.md#keys)
- [NativeClass](ue_ue.BlackboardData.md#nativeclass)
- [Parent](ue_ue.BlackboardData.md#parent)
- [ParentKeys](ue_ue.BlackboardData.md#parentkeys)
- [\_\_tid\_BlackboardData\_\_](ue_ue.BlackboardData.md#__tid_blackboarddata__)
- [\_\_tid\_DataAsset\_\_](ue_ue.BlackboardData.md#__tid_dataasset__)
- [\_\_tid\_Object\_\_](ue_ue.BlackboardData.md#__tid_object__)
- [bHasSynchronizedKeys](ue_ue.BlackboardData.md#bhassynchronizedkeys)

### Methods

- [CreateDefaultSubobject](ue_ue.BlackboardData.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.BlackboardData.md#executeubergraph)
- [GetClass](ue_ue.BlackboardData.md#getclass)
- [GetName](ue_ue.BlackboardData.md#getname)
- [GetOuter](ue_ue.BlackboardData.md#getouter)
- [GetWorld](ue_ue.BlackboardData.md#getworld)
- [Find](ue_ue.BlackboardData.md#find)
- [Load](ue_ue.BlackboardData.md#load)
- [StaticClass](ue_ue.BlackboardData.md#staticclass)

## Constructors

### constructor

• **new BlackboardData**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[constructor](ue_ue.DataAsset.md#constructor)

#### Defined in

[ue/ue.d.ts:14688](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14688)

## Properties

### Keys

• **Keys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlackboardEntry`](ue_ue.BlackboardEntry.md)\>

#### Defined in

[ue/ue.d.ts:14691](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14691)

___

### NativeClass

• **NativeClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[NativeClass](ue_ue.DataAsset.md#nativeclass)

#### Defined in

[ue/ue.d.ts:724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L724)

___

### Parent

• **Parent**: [`BlackboardData`](ue_ue.BlackboardData.md)

#### Defined in

[ue/ue.d.ts:14689](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14689)

___

### ParentKeys

• **ParentKeys**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BlackboardEntry`](ue_ue.BlackboardEntry.md)\>

#### Defined in

[ue/ue.d.ts:14690](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14690)

___

### \_\_tid\_BlackboardData\_\_

• **\_\_tid\_BlackboardData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14697](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14697)

___

### \_\_tid\_DataAsset\_\_

• **\_\_tid\_DataAsset\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_DataAsset__](ue_ue.DataAsset.md#__tid_dataasset__)

#### Defined in

[ue/ue.d.ts:729](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L729)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[__tid_Object__](ue_ue.DataAsset.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bHasSynchronizedKeys

• **bHasSynchronizedKeys**: `boolean`

#### Defined in

[ue/ue.d.ts:14692](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14692)

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

[DataAsset](ue_ue.DataAsset.md).[CreateDefaultSubobject](ue_ue.DataAsset.md#createdefaultsubobject)

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

[DataAsset](ue_ue.DataAsset.md).[ExecuteUbergraph](ue_ue.DataAsset.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetClass](ue_ue.DataAsset.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetName](ue_ue.DataAsset.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetOuter](ue_ue.DataAsset.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[GetWorld](ue_ue.DataAsset.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`BlackboardData`](ue_ue.BlackboardData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`BlackboardData`](ue_ue.BlackboardData.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[Find](ue_ue.DataAsset.md#find)

#### Defined in

[ue/ue.d.ts:14694](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14694)

___

### Load

▸ `Static` **Load**(`InName`): [`BlackboardData`](ue_ue.BlackboardData.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`BlackboardData`](ue_ue.BlackboardData.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[Load](ue_ue.DataAsset.md#load)

#### Defined in

[ue/ue.d.ts:14695](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14695)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[StaticClass](ue_ue.DataAsset.md#staticclass)

#### Defined in

[ue/ue.d.ts:14693](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14693)
