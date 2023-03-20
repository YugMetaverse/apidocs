[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue\_s](../modules/ue_ue_s.md) / Box2D

# Class: Box2D

[ue/ue_s](../modules/ue_ue_s.md).Box2D

## Table of contents

### Constructors

- [constructor](ue_ue_s.Box2D.md#constructor)

### Properties

- [Max](ue_ue_s.Box2D.md#max)
- [Min](ue_ue_s.Box2D.md#min)
- [\_\_tid\_Box2D\_\_](ue_ue_s.Box2D.md#__tid_box2d__)
- [bIsValid](ue_ue_s.Box2D.md#bisvalid)

### Methods

- [ComputeSquaredDistanceToPoint](ue_ue_s.Box2D.md#computesquareddistancetopoint)
- [ExpandBy](ue_ue_s.Box2D.md#expandby)
- [GetArea](ue_ue_s.Box2D.md#getarea)
- [GetCenter](ue_ue_s.Box2D.md#getcenter)
- [GetCenterAndExtents](ue_ue_s.Box2D.md#getcenterandextents)
- [GetClosestPointTo](ue_ue_s.Box2D.md#getclosestpointto)
- [GetExtent](ue_ue_s.Box2D.md#getextent)
- [GetSize](ue_ue_s.Box2D.md#getsize)
- [Init](ue_ue_s.Box2D.md#init)
- [Intersect](ue_ue_s.Box2D.md#intersect)
- [IsInside](ue_ue_s.Box2D.md#isinside)
- [ShiftBy](ue_ue_s.Box2D.md#shiftby)
- [ToString](ue_ue_s.Box2D.md#tostring)
- [op\_Addition](ue_ue_s.Box2D.md#op_addition)
- [op\_Equality](ue_ue_s.Box2D.md#op_equality)
- [op\_Inequality](ue_ue_s.Box2D.md#op_inequality)
- [set\_Item](ue_ue_s.Box2D.md#set_item)
- [StaticClass](ue_ue_s.Box2D.md#staticclass)
- [StaticStruct](ue_ue_s.Box2D.md#staticstruct)

## Constructors

### constructor

• **new Box2D**()

#### Defined in

[ue/ue_s.d.ts:31](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L31)

• **new Box2D**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

#### Defined in

[ue/ue_s.d.ts:32](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L32)

• **new Box2D**(`InMin`, `InMax`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InMin` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `InMax` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Defined in

[ue/ue_s.d.ts:33](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L33)

• **new Box2D**(`Points`, `Count`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Points` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `Count` | `number` |

#### Defined in

[ue/ue_s.d.ts:34](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L34)

## Properties

### Max

• **Max**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:36](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L36)

___

### Min

• **Min**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:35](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L35)

___

### \_\_tid\_Box2D\_\_

• `Private` **\_\_tid\_Box2D\_\_**: `boolean`

#### Defined in

[ue/ue_s.d.ts:64](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L64)

___

### bIsValid

• **bIsValid**: `boolean`

#### Defined in

[ue/ue_s.d.ts:37](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L37)

## Methods

### ComputeSquaredDistanceToPoint

▸ **ComputeSquaredDistanceToPoint**(`Point`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Point` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:43](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L43)

___

### ExpandBy

▸ **ExpandBy**(`W`): [`Box2D`](ue_ue_s.Box2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `W` | `number` |

#### Returns

[`Box2D`](ue_ue_s.Box2D.md)

#### Defined in

[ue/ue_s.d.ts:44](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L44)

___

### GetArea

▸ **GetArea**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:45](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L45)

___

### GetCenter

▸ **GetCenter**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:46](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L46)

___

### GetCenterAndExtents

▸ **GetCenterAndExtents**(`center`, `Extents`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `center` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\> |
| `Extents` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:47](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L47)

___

### GetClosestPointTo

▸ **GetClosestPointTo**(`Point`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Point` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:48](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L48)

___

### GetExtent

▸ **GetExtent**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:49](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L49)

___

### GetSize

▸ **GetSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:50](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L50)

___

### Init

▸ **Init**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:51](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L51)

___

### Intersect

▸ **Intersect**(`other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`Box2D`](ue_ue_s.Box2D.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:52](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L52)

___

### IsInside

▸ **IsInside**(`TestPoint`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TestPoint` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:53](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L53)

▸ **IsInside**(`Other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Box2D`](ue_ue_s.Box2D.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:54](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L54)

___

### ShiftBy

▸ **ShiftBy**(`Offset`): [`Box2D`](ue_ue_s.Box2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Offset` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

[`Box2D`](ue_ue_s.Box2D.md)

#### Defined in

[ue/ue_s.d.ts:55](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L55)

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue_s.d.ts:56](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L56)

___

### op\_Addition

▸ **op_Addition**(`Other`): [`Box2D`](ue_ue_s.Box2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

[`Box2D`](ue_ue_s.Box2D.md)

#### Defined in

[ue/ue_s.d.ts:40](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L40)

▸ **op_Addition**(`Other`): [`Box2D`](ue_ue_s.Box2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Box2D`](ue_ue_s.Box2D.md) |

#### Returns

[`Box2D`](ue_ue_s.Box2D.md)

#### Defined in

[ue/ue_s.d.ts:41](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L41)

___

### op\_Equality

▸ **op_Equality**(`Other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Box2D`](ue_ue_s.Box2D.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:38](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L38)

___

### op\_Inequality

▸ **op_Inequality**(`Other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Box2D`](ue_ue_s.Box2D.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:39](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L39)

___

### set\_Item

▸ **set_Item**(`Index`): [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

[`$Ref`](../interfaces/puerts._Ref.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\>

#### Defined in

[ue/ue_s.d.ts:42](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L42)

___

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:61](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L61)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:62](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L62)
