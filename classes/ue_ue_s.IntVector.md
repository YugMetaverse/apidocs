[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue\_s](../modules/ue_ue_s.md) / IntVector

# Class: IntVector

[ue/ue_s](../modules/ue_ue_s.md).IntVector

## Table of contents

### Constructors

- [constructor](ue_ue_s.IntVector.md#constructor)

### Properties

- [X](ue_ue_s.IntVector.md#x)
- [Y](ue_ue_s.IntVector.md#y)
- [Z](ue_ue_s.IntVector.md#z)
- [\_\_tid\_IntVector\_\_](ue_ue_s.IntVector.md#__tid_intvector__)

### Methods

- [GetMax](ue_ue_s.IntVector.md#getmax)
- [GetMin](ue_ue_s.IntVector.md#getmin)
- [IsZero](ue_ue_s.IntVector.md#iszero)
- [Size](ue_ue_s.IntVector.md#size)
- [ToString](ue_ue_s.IntVector.md#tostring)
- [get\_Item](ue_ue_s.IntVector.md#get_item)
- [op\_Addition](ue_ue_s.IntVector.md#op_addition)
- [op\_Division](ue_ue_s.IntVector.md#op_division)
- [op\_Equality](ue_ue_s.IntVector.md#op_equality)
- [op\_Inequality](ue_ue_s.IntVector.md#op_inequality)
- [op\_Multiply](ue_ue_s.IntVector.md#op_multiply)
- [op\_Subtraction](ue_ue_s.IntVector.md#op_subtraction)
- [set\_Item](ue_ue_s.IntVector.md#set_item)
- [DivideAndRoundUp](ue_ue_s.IntVector.md#divideandroundup)
- [Num](ue_ue_s.IntVector.md#num)
- [StaticClass](ue_ue_s.IntVector.md#staticclass)
- [StaticStruct](ue_ue_s.IntVector.md#staticstruct)

## Constructors

### constructor

• **new IntVector**()

• **new IntVector**(`InX`, `InY`, `InZ`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InX` | `number` |
| `InY` | `number` |
| `InZ` | `number` |

• **new IntVector**(`InValue`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InValue` | `number` |

• **new IntVector**(`InVector`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVector` | [`Vector`](ue_ue_s.Vector.md) |

• **new IntVector**(`Param1`)

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

### Z

• **Z**: `number`

___

### \_\_tid\_IntVector\_\_

• `Private` **\_\_tid\_IntVector\_\_**: `boolean`

## Methods

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

### IsZero

▸ **IsZero**(): `boolean`

#### Returns

`boolean`

___

### Size

▸ **Size**(): `number`

#### Returns

`number`

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

___

### get\_Item

▸ **get_Item**(`ComponentIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ComponentIndex` | `number` |

#### Returns

`number`

___

### op\_Addition

▸ **op_Addition**(`Other`): [`IntVector`](ue_ue_s.IntVector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`IntVector`](ue_ue_s.IntVector.md) |

#### Returns

[`IntVector`](ue_ue_s.IntVector.md)

___

### op\_Division

▸ **op_Division**(`Divisor`): [`IntVector`](ue_ue_s.IntVector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Divisor` | `number` |

#### Returns

[`IntVector`](ue_ue_s.IntVector.md)

___

### op\_Equality

▸ **op_Equality**(`Other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`IntVector`](ue_ue_s.IntVector.md) |

#### Returns

`boolean`

___

### op\_Inequality

▸ **op_Inequality**(`Other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`IntVector`](ue_ue_s.IntVector.md) |

#### Returns

`boolean`

___

### op\_Multiply

▸ **op_Multiply**(`Scale`): [`IntVector`](ue_ue_s.IntVector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`IntVector`](ue_ue_s.IntVector.md)

___

### op\_Subtraction

▸ **op_Subtraction**(`Other`): [`IntVector`](ue_ue_s.IntVector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`IntVector`](ue_ue_s.IntVector.md) |

#### Returns

[`IntVector`](ue_ue_s.IntVector.md)

___

### set\_Item

▸ **set_Item**(`ComponentIndex`): [`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ComponentIndex` | `number` |

#### Returns

[`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

___

### DivideAndRoundUp

▸ `Static` **DivideAndRoundUp**(`lhs`, `Divisor`): [`IntVector`](ue_ue_s.IntVector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `lhs` | [`IntVector`](ue_ue_s.IntVector.md) |
| `Divisor` | `number` |

#### Returns

[`IntVector`](ue_ue_s.IntVector.md)

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
