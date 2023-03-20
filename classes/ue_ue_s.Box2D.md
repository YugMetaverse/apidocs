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

• **new Box2D**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

• **new Box2D**(`InMin`, `InMax`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InMin` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `InMax` | [`Vector2D`](ue_ue_s.Vector2D.md) |

• **new Box2D**(`Points`, `Count`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Points` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `Count` | `number` |

## Properties

### Max

• **Max**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### Min

• **Min**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### \_\_tid\_Box2D\_\_

• `Private` **\_\_tid\_Box2D\_\_**: `boolean`

___

### bIsValid

• **bIsValid**: `boolean`

## Methods

### ComputeSquaredDistanceToPoint

▸ **ComputeSquaredDistanceToPoint**(`Point`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Point` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`number`

___

### ExpandBy

▸ **ExpandBy**(`W`): [`Box2D`](ue_ue_s.Box2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `W` | `number` |

#### Returns

[`Box2D`](ue_ue_s.Box2D.md)

___

### GetArea

▸ **GetArea**(): `number`

#### Returns

`number`

___

### GetCenter

▸ **GetCenter**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

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

___

### GetClosestPointTo

▸ **GetClosestPointTo**(`Point`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Point` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### GetExtent

▸ **GetExtent**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### GetSize

▸ **GetSize**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### Init

▸ **Init**(): `void`

#### Returns

`void`

___

### Intersect

▸ **Intersect**(`other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `other` | [`Box2D`](ue_ue_s.Box2D.md) |

#### Returns

`boolean`

___

### IsInside

▸ **IsInside**(`TestPoint`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TestPoint` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`boolean`

▸ **IsInside**(`Other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Box2D`](ue_ue_s.Box2D.md) |

#### Returns

`boolean`

___

### ShiftBy

▸ **ShiftBy**(`Offset`): [`Box2D`](ue_ue_s.Box2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Offset` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

[`Box2D`](ue_ue_s.Box2D.md)

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

___

### op\_Addition

▸ **op_Addition**(`Other`): [`Box2D`](ue_ue_s.Box2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

[`Box2D`](ue_ue_s.Box2D.md)

▸ **op_Addition**(`Other`): [`Box2D`](ue_ue_s.Box2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Box2D`](ue_ue_s.Box2D.md) |

#### Returns

[`Box2D`](ue_ue_s.Box2D.md)

___

### op\_Equality

▸ **op_Equality**(`Other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Box2D`](ue_ue_s.Box2D.md) |

#### Returns

`boolean`

___

### op\_Inequality

▸ **op_Inequality**(`Other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Box2D`](ue_ue_s.Box2D.md) |

#### Returns

`boolean`

___

### set\_Item

▸ **set_Item**(`Index`): [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

[`$Ref`](../interfaces/puerts._Ref.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\>

___

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
