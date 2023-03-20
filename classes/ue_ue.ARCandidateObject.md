[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ARCandidateObject

# Class: ARCandidateObject

[ue/ue](../modules/ue_ue.md).ARCandidateObject

## Hierarchy

- [`DataAsset`](ue_ue.DataAsset.md)

  ↳ **`ARCandidateObject`**

## Table of contents

### Constructors

- [constructor](ue_ue.ARCandidateObject.md#constructor)

### Properties

- [BoundingBox](ue_ue.ARCandidateObject.md#boundingbox)
- [CandidateObjectData](ue_ue.ARCandidateObject.md#candidateobjectdata)
- [FriendlyName](ue_ue.ARCandidateObject.md#friendlyname)
- [NativeClass](ue_ue.ARCandidateObject.md#nativeclass)
- [\_\_tid\_ARCandidateObject\_\_](ue_ue.ARCandidateObject.md#__tid_arcandidateobject__)
- [\_\_tid\_DataAsset\_\_](ue_ue.ARCandidateObject.md#__tid_dataasset__)
- [\_\_tid\_Object\_\_](ue_ue.ARCandidateObject.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.ARCandidateObject.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ARCandidateObject.md#executeubergraph)
- [GetBoundingBox](ue_ue.ARCandidateObject.md#getboundingbox)
- [GetCandidateObjectData](ue_ue.ARCandidateObject.md#getcandidateobjectdata)
- [GetClass](ue_ue.ARCandidateObject.md#getclass)
- [GetFriendlyName](ue_ue.ARCandidateObject.md#getfriendlyname)
- [GetName](ue_ue.ARCandidateObject.md#getname)
- [GetOuter](ue_ue.ARCandidateObject.md#getouter)
- [GetWorld](ue_ue.ARCandidateObject.md#getworld)
- [SetBoundingBox](ue_ue.ARCandidateObject.md#setboundingbox)
- [SetCandidateObjectData](ue_ue.ARCandidateObject.md#setcandidateobjectdata)
- [SetFriendlyName](ue_ue.ARCandidateObject.md#setfriendlyname)
- [Find](ue_ue.ARCandidateObject.md#find)
- [Load](ue_ue.ARCandidateObject.md#load)
- [StaticClass](ue_ue.ARCandidateObject.md#staticclass)

## Constructors

### constructor

• **new ARCandidateObject**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[constructor](ue_ue.DataAsset.md#constructor)

#### Defined in

[ue/ue.d.ts:20735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20735)

## Properties

### BoundingBox

• **BoundingBox**: [`Box`](ue_ue.Box.md)

#### Defined in

[ue/ue.d.ts:20738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20738)

___

### CandidateObjectData

• **CandidateObjectData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:20736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20736)

___

### FriendlyName

• **FriendlyName**: `string`

#### Defined in

[ue/ue.d.ts:20737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20737)

___

### NativeClass

• **NativeClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[DataAsset](ue_ue.DataAsset.md).[NativeClass](ue_ue.DataAsset.md#nativeclass)

#### Defined in

[ue/ue.d.ts:724](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L724)

___

### \_\_tid\_ARCandidateObject\_\_

• **\_\_tid\_ARCandidateObject\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:20749](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20749)

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

### GetBoundingBox

▸ **GetBoundingBox**(): [`Box`](ue_ue.Box.md)

#### Returns

[`Box`](ue_ue.Box.md)

#### Defined in

[ue/ue.d.ts:20739](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20739)

___

### GetCandidateObjectData

▸ **GetCandidateObjectData**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:20740](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20740)

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

### GetFriendlyName

▸ **GetFriendlyName**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:20741](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20741)

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

### SetBoundingBox

▸ **SetBoundingBox**(`InBoundingBox`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBoundingBox` | [`Box`](ue_ue.Box.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:20742](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20742)

___

### SetCandidateObjectData

▸ **SetCandidateObjectData**(`InCandidateObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InCandidateObject` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:20743](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20743)

___

### SetFriendlyName

▸ **SetFriendlyName**(`NewName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:20744](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20744)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ARCandidateObject`](ue_ue.ARCandidateObject.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ARCandidateObject`](ue_ue.ARCandidateObject.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[Find](ue_ue.DataAsset.md#find)

#### Defined in

[ue/ue.d.ts:20746](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20746)

___

### Load

▸ `Static` **Load**(`InName`): [`ARCandidateObject`](ue_ue.ARCandidateObject.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ARCandidateObject`](ue_ue.ARCandidateObject.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[Load](ue_ue.DataAsset.md#load)

#### Defined in

[ue/ue.d.ts:20747](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20747)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DataAsset](ue_ue.DataAsset.md).[StaticClass](ue_ue.DataAsset.md#staticclass)

#### Defined in

[ue/ue.d.ts:20745](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20745)
