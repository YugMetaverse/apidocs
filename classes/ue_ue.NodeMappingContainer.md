[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NodeMappingContainer

# Class: NodeMappingContainer

[ue/ue](../modules/ue_ue.md).NodeMappingContainer

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`NodeMappingContainer`**

## Table of contents

### Constructors

- [constructor](ue_ue.NodeMappingContainer.md#constructor)

### Properties

- [SourceAsset](ue_ue.NodeMappingContainer.md#sourceasset)
- [SourceItems](ue_ue.NodeMappingContainer.md#sourceitems)
- [SourceToTarget](ue_ue.NodeMappingContainer.md#sourcetotarget)
- [TargetAsset](ue_ue.NodeMappingContainer.md#targetasset)
- [TargetItems](ue_ue.NodeMappingContainer.md#targetitems)
- [\_\_tid\_NodeMappingContainer\_\_](ue_ue.NodeMappingContainer.md#__tid_nodemappingcontainer__)
- [\_\_tid\_Object\_\_](ue_ue.NodeMappingContainer.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.NodeMappingContainer.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.NodeMappingContainer.md#executeubergraph)
- [GetClass](ue_ue.NodeMappingContainer.md#getclass)
- [GetName](ue_ue.NodeMappingContainer.md#getname)
- [GetOuter](ue_ue.NodeMappingContainer.md#getouter)
- [GetWorld](ue_ue.NodeMappingContainer.md#getworld)
- [Find](ue_ue.NodeMappingContainer.md#find)
- [Load](ue_ue.NodeMappingContainer.md#load)
- [StaticClass](ue_ue.NodeMappingContainer.md#staticclass)

## Constructors

### constructor

• **new NodeMappingContainer**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:3889](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3889)

## Properties

### SourceAsset

• **SourceAsset**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:3893](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3893)

___

### SourceItems

• **SourceItems**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`NodeItem`](ue_ue.NodeItem.md)\>

#### Defined in

[ue/ue.d.ts:3890](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3890)

___

### SourceToTarget

• **SourceToTarget**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, `string`\>

#### Defined in

[ue/ue.d.ts:3892](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3892)

___

### TargetAsset

• **TargetAsset**: [`TSoftObjectPtr`](../modules/ue_puerts.md#tsoftobjectptr)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:3894](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3894)

___

### TargetItems

• **TargetItems**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`NodeItem`](ue_ue.NodeItem.md)\>

#### Defined in

[ue/ue.d.ts:3891](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3891)

___

### \_\_tid\_NodeMappingContainer\_\_

• **\_\_tid\_NodeMappingContainer\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3899](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3899)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NodeMappingContainer`](ue_ue.NodeMappingContainer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NodeMappingContainer`](ue_ue.NodeMappingContainer.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:3896](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3896)

___

### Load

▸ `Static` **Load**(`InName`): [`NodeMappingContainer`](ue_ue.NodeMappingContainer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NodeMappingContainer`](ue_ue.NodeMappingContainer.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:3897](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3897)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:3895](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3895)
