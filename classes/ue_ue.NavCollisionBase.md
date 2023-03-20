[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NavCollisionBase

# Class: NavCollisionBase

[ue/ue](../modules/ue_ue.md).NavCollisionBase

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`NavCollisionBase`**

  ↳↳ [`NavCollision`](ue_ue.NavCollision.md)

## Table of contents

### Constructors

- [constructor](ue_ue.NavCollisionBase.md#constructor)

### Properties

- [\_\_tid\_NavCollisionBase\_\_](ue_ue.NavCollisionBase.md#__tid_navcollisionbase__)
- [\_\_tid\_Object\_\_](ue_ue.NavCollisionBase.md#__tid_object__)
- [bIsDynamicObstacle](ue_ue.NavCollisionBase.md#bisdynamicobstacle)

### Methods

- [CreateDefaultSubobject](ue_ue.NavCollisionBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.NavCollisionBase.md#executeubergraph)
- [GetClass](ue_ue.NavCollisionBase.md#getclass)
- [GetName](ue_ue.NavCollisionBase.md#getname)
- [GetOuter](ue_ue.NavCollisionBase.md#getouter)
- [GetWorld](ue_ue.NavCollisionBase.md#getworld)
- [Find](ue_ue.NavCollisionBase.md#find)
- [Load](ue_ue.NavCollisionBase.md#load)
- [StaticClass](ue_ue.NavCollisionBase.md#staticclass)

## Constructors

### constructor

• **new NavCollisionBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:7881](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7881)

## Properties

### \_\_tid\_NavCollisionBase\_\_

• **\_\_tid\_NavCollisionBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:7887](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7887)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bIsDynamicObstacle

• **bIsDynamicObstacle**: `boolean`

#### Defined in

[ue/ue.d.ts:7882](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7882)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NavCollisionBase`](ue_ue.NavCollisionBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NavCollisionBase`](ue_ue.NavCollisionBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:7884](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7884)

___

### Load

▸ `Static` **Load**(`InName`): [`NavCollisionBase`](ue_ue.NavCollisionBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NavCollisionBase`](ue_ue.NavCollisionBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:7885](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7885)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:7883](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7883)
