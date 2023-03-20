[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue\_s](../modules/ue_ue_s.md) / IntPoint

# Class: IntPoint

[ue/ue_s](../modules/ue_ue_s.md).IntPoint

## Table of contents

### Constructors

- [constructor](ue_ue_s.IntPoint.md#constructor)

### Properties

- [X](ue_ue_s.IntPoint.md#x)
- [Y](ue_ue_s.IntPoint.md#y)
- [\_\_tid\_IntPoint\_\_](ue_ue_s.IntPoint.md#__tid_intpoint__)

### Methods

- [ComponentMax](ue_ue_s.IntPoint.md#componentmax)
- [ComponentMin](ue_ue_s.IntPoint.md#componentmin)
- [GetMax](ue_ue_s.IntPoint.md#getmax)
- [GetMin](ue_ue_s.IntPoint.md#getmin)
- [Size](ue_ue_s.IntPoint.md#size)
- [SizeSquared](ue_ue_s.IntPoint.md#sizesquared)
- [ToString](ue_ue_s.IntPoint.md#tostring)
- [get\_Item](ue_ue_s.IntPoint.md#get_item)
- [op\_Addition](ue_ue_s.IntPoint.md#op_addition)
- [op\_Division](ue_ue_s.IntPoint.md#op_division)
- [op\_Equality](ue_ue_s.IntPoint.md#op_equality)
- [op\_Inequality](ue_ue_s.IntPoint.md#op_inequality)
- [op\_Multiply](ue_ue_s.IntPoint.md#op_multiply)
- [op\_Subtraction](ue_ue_s.IntPoint.md#op_subtraction)
- [set\_Item](ue_ue_s.IntPoint.md#set_item)
- [DivideAndRoundDown](ue_ue_s.IntPoint.md#divideandrounddown)
- [DivideAndRoundUp](ue_ue_s.IntPoint.md#divideandroundup)
- [Num](ue_ue_s.IntPoint.md#num)
- [StaticClass](ue_ue_s.IntPoint.md#staticclass)
- [StaticStruct](ue_ue_s.IntPoint.md#staticstruct)

## Constructors

### constructor

• **new IntPoint**()

• **new IntPoint**(`InX`, `InY`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InX` | `number` |
| `InY` | `number` |

• **new IntPoint**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

## Properties

### X

• **X**: `number`

___

### Y

• **Y**: `number`

___

### \_\_tid\_IntPoint\_\_

• `Private` **\_\_tid\_IntPoint\_\_**: `boolean`

## Methods

### ComponentMax

▸ **ComponentMax**(`Other`): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`IntPoint`](ue_ue_s.IntPoint.md) |

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

___

### ComponentMin

▸ **ComponentMin**(`Other`): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`IntPoint`](ue_ue_s.IntPoint.md) |

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

___

### GetMax

▸ **GetMax**(): `number`

#### Returns

`number`

___

### GetMin

▸ **GetMin**(): `number`

#### Returns

`number`

___

### Size

▸ **Size**(): `number`

#### Returns

`number`

___

### SizeSquared

▸ **SizeSquared**(): `number`

#### Returns

`number`

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

___

### get\_Item

▸ **get_Item**(`Index`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`number`

___

### op\_Addition

▸ **op_Addition**(`Other`): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`IntPoint`](ue_ue_s.IntPoint.md) |

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

___

### op\_Division

▸ **op_Division**(`Divisor`): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Divisor` | `number` |

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

▸ **op_Division**(`Other`): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`IntPoint`](ue_ue_s.IntPoint.md) |

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

___

### op\_Equality

▸ **op_Equality**(`Other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`IntPoint`](ue_ue_s.IntPoint.md) |

#### Returns

`boolean`

___

### op\_Inequality

▸ **op_Inequality**(`Other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`IntPoint`](ue_ue_s.IntPoint.md) |

#### Returns

`boolean`

___

### op\_Multiply

▸ **op_Multiply**(`Scale`): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

___

### op\_Subtraction

▸ **op_Subtraction**(`Other`): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`IntPoint`](ue_ue_s.IntPoint.md) |

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

___

### set\_Item

▸ **set_Item**(`Index`): [`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

[`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

___

### DivideAndRoundDown

▸ `Static` **DivideAndRoundDown**(`lhs`, `Divisor`): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `lhs` | [`IntPoint`](ue_ue_s.IntPoint.md) |
| `Divisor` | `number` |

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

___

### DivideAndRoundUp

▸ `Static` **DivideAndRoundUp**(`lhs`, `Divisor`): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `lhs` | [`IntPoint`](ue_ue_s.IntPoint.md) |
| `Divisor` | `number` |

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

▸ `Static` **DivideAndRoundUp**(`lhs`, `Divisor`): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `lhs` | [`IntPoint`](ue_ue_s.IntPoint.md) |
| `Divisor` | [`IntPoint`](ue_ue_s.IntPoint.md) |

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

___

### Num

▸ `Static` **Num**(): `number`

#### Returns

`number`

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
