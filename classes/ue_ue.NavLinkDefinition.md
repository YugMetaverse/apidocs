[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NavLinkDefinition

# Class: NavLinkDefinition

[ue/ue](../modules/ue_ue.md).NavLinkDefinition

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`NavLinkDefinition`**

  ↳↳ [`NavLinkTrivial`](ue_ue.NavLinkTrivial.md)

## Table of contents

### Constructors

- [constructor](ue_ue.NavLinkDefinition.md#constructor)

### Properties

- [Links](ue_ue.NavLinkDefinition.md#links)
- [SegmentLinks](ue_ue.NavLinkDefinition.md#segmentlinks)
- [\_\_tid\_NavLinkDefinition\_\_](ue_ue.NavLinkDefinition.md#__tid_navlinkdefinition__)
- [\_\_tid\_Object\_\_](ue_ue.NavLinkDefinition.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.NavLinkDefinition.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.NavLinkDefinition.md#executeubergraph)
- [GetClass](ue_ue.NavLinkDefinition.md#getclass)
- [GetName](ue_ue.NavLinkDefinition.md#getname)
- [GetOuter](ue_ue.NavLinkDefinition.md#getouter)
- [GetWorld](ue_ue.NavLinkDefinition.md#getworld)
- [Find](ue_ue.NavLinkDefinition.md#find)
- [Load](ue_ue.NavLinkDefinition.md#load)
- [StaticClass](ue_ue.NavLinkDefinition.md#staticclass)

## Constructors

### constructor

• **new NavLinkDefinition**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:53303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53303)

## Properties

### Links

• **Links**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NavigationLink`](ue_ue.NavigationLink.md)\>

#### Defined in

[ue/ue.d.ts:53304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53304)

___

### SegmentLinks

• **SegmentLinks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NavigationSegmentLink`](ue_ue.NavigationSegmentLink.md)\>

#### Defined in

[ue/ue.d.ts:53305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53305)

___

### \_\_tid\_NavLinkDefinition\_\_

• **\_\_tid\_NavLinkDefinition\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:53310](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53310)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NavLinkDefinition`](ue_ue.NavLinkDefinition.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NavLinkDefinition`](ue_ue.NavLinkDefinition.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:53307](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53307)

___

### Load

▸ `Static` **Load**(`InName`): [`NavLinkDefinition`](ue_ue.NavLinkDefinition.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NavLinkDefinition`](ue_ue.NavLinkDefinition.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:53308](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53308)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:53306](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53306)
