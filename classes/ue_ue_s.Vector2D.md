[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue\_s](../modules/ue_ue_s.md) / Vector2D

# Class: Vector2D

[ue/ue_s](../modules/ue_ue_s.md).Vector2D

## Table of contents

### Constructors

- [constructor](ue_ue_s.Vector2D.md#constructor)

### Properties

- [X](ue_ue_s.Vector2D.md#x)
- [Y](ue_ue_s.Vector2D.md#y)
- [\_\_tid\_Vector2D\_\_](ue_ue_s.Vector2D.md#__tid_vector2d__)

### Methods

- [ClampAxes](ue_ue_s.Vector2D.md#clampaxes)
- [Component](ue_ue_s.Vector2D.md#component)
- [ContainsNaN](ue_ue_s.Vector2D.md#containsnan)
- [DiagnosticCheckNaN](ue_ue_s.Vector2D.md#diagnosticchecknan)
- [Equals](ue_ue_s.Vector2D.md#equals)
- [GetAbs](ue_ue_s.Vector2D.md#getabs)
- [GetAbsMax](ue_ue_s.Vector2D.md#getabsmax)
- [GetMax](ue_ue_s.Vector2D.md#getmax)
- [GetMin](ue_ue_s.Vector2D.md#getmin)
- [GetRotated](ue_ue_s.Vector2D.md#getrotated)
- [GetSafeNormal](ue_ue_s.Vector2D.md#getsafenormal)
- [GetSignVector](ue_ue_s.Vector2D.md#getsignvector)
- [InitFromString](ue_ue_s.Vector2D.md#initfromstring)
- [IntPoint](ue_ue_s.Vector2D.md#intpoint)
- [IsNearlyZero](ue_ue_s.Vector2D.md#isnearlyzero)
- [IsZero](ue_ue_s.Vector2D.md#iszero)
- [Normalize](ue_ue_s.Vector2D.md#normalize)
- [RoundToVector](ue_ue_s.Vector2D.md#roundtovector)
- [Set](ue_ue_s.Vector2D.md#set)
- [Size](ue_ue_s.Vector2D.md#size)
- [SizeSquared](ue_ue_s.Vector2D.md#sizesquared)
- [SphericalToUnitCartesian](ue_ue_s.Vector2D.md#sphericaltounitcartesian)
- [ToDirectionAndLength](ue_ue_s.Vector2D.md#todirectionandlength)
- [ToString](ue_ue_s.Vector2D.md#tostring)
- [get\_Item](ue_ue_s.Vector2D.md#get_item)
- [op\_Addition](ue_ue_s.Vector2D.md#op_addition)
- [op\_BitwiseOr](ue_ue_s.Vector2D.md#op_bitwiseor)
- [op\_Division](ue_ue_s.Vector2D.md#op_division)
- [op\_Equality](ue_ue_s.Vector2D.md#op_equality)
- [op\_ExclusiveOr](ue_ue_s.Vector2D.md#op_exclusiveor)
- [op\_Inequality](ue_ue_s.Vector2D.md#op_inequality)
- [op\_Multiply](ue_ue_s.Vector2D.md#op_multiply)
- [op\_Subtraction](ue_ue_s.Vector2D.md#op_subtraction)
- [op\_UnaryNegation](ue_ue_s.Vector2D.md#op_unarynegation)
- [set\_Item](ue_ue_s.Vector2D.md#set_item)
- [CrossProduct](ue_ue_s.Vector2D.md#crossproduct)
- [DistSquared](ue_ue_s.Vector2D.md#distsquared)
- [Distance](ue_ue_s.Vector2D.md#distance)
- [DotProduct](ue_ue_s.Vector2D.md#dotproduct)
- [StaticClass](ue_ue_s.Vector2D.md#staticclass)
- [StaticStruct](ue_ue_s.Vector2D.md#staticstruct)

## Constructors

### constructor

• **new Vector2D**()

• **new Vector2D**(`InX`, `InY`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InX` | `number` |
| `InY` | `number` |

• **new Vector2D**(`InPos`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPos` | [`IntPoint`](ue_ue_s.IntPoint.md) |

• **new Vector2D**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

• **new Vector2D**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

• **new Vector2D**(`V`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

• **new Vector2D**(`V`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

## Properties

### X

• **X**: `number`

___

### Y

• **Y**: `number`

___

### \_\_tid\_Vector2D\_\_

• `Private` **\_\_tid\_Vector2D\_\_**: `boolean`

## Methods

### ClampAxes

▸ **ClampAxes**(`MinAxisVal`, `MaxAxisVal`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MinAxisVal` | `number` |
| `MaxAxisVal` | `number` |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### Component

▸ **Component**(`Index`): [`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

[`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

▸ **Component**(`Index`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`number`

___

### ContainsNaN

▸ **ContainsNaN**(): `boolean`

#### Returns

`boolean`

___

### DiagnosticCheckNaN

▸ **DiagnosticCheckNaN**(): `void`

#### Returns

`void`

___

### Equals

▸ **Equals**(`V`, `Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### GetAbs

▸ **GetAbs**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### GetAbsMax

▸ **GetAbsMax**(): `number`

#### Returns

`number`

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

### GetRotated

▸ **GetRotated**(`AngleDeg`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `AngleDeg` | `number` |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### GetSafeNormal

▸ **GetSafeNormal**(`Tolerance`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### GetSignVector

▸ **GetSignVector**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### InitFromString

▸ **InitFromString**(`InSourceString`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSourceString` | `string` |

#### Returns

`boolean`

___

### IntPoint

▸ **IntPoint**(): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

___

### IsNearlyZero

▸ **IsNearlyZero**(`Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### IsZero

▸ **IsZero**(): `boolean`

#### Returns

`boolean`

___

### Normalize

▸ **Normalize**(`Tolerance`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

`void`

___

### RoundToVector

▸ **RoundToVector**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### Set

▸ **Set**(`InX`, `InY`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InX` | `number` |
| `InY` | `number` |

#### Returns

`void`

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

### SphericalToUnitCartesian

▸ **SphericalToUnitCartesian**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### ToDirectionAndLength

▸ **ToDirectionAndLength**(`OutDir`, `OutLength`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutDir` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\> |
| `OutLength` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

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

▸ **op_Addition**(`V`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

▸ **op_Addition**(`A`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | `number` |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### op\_BitwiseOr

▸ **op_BitwiseOr**(`V`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`number`

___

### op\_Division

▸ **op_Division**(`Scale`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

▸ **op_Division**(`V`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### op\_Equality

▸ **op_Equality**(`V`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`boolean`

___

### op\_ExclusiveOr

▸ **op_ExclusiveOr**(`V`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`number`

___

### op\_Inequality

▸ **op_Inequality**(`V`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`boolean`

___

### op\_Multiply

▸ **op_Multiply**(`Scale`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

▸ **op_Multiply**(`V`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### op\_Subtraction

▸ **op_Subtraction**(`V`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

▸ **op_Subtraction**(`A`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | `number` |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### op\_UnaryNegation

▸ **op_UnaryNegation**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

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

### CrossProduct

▸ `Static` **CrossProduct**(`A`, `B`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `B` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`number`

___

### DistSquared

▸ `Static` **DistSquared**(`V1`, `V2`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V1` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `V2` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`number`

___

### Distance

▸ `Static` **Distance**(`V1`, `V2`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V1` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `V2` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`number`

___

### DotProduct

▸ `Static` **DotProduct**(`A`, `B`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `B` | [`Vector2D`](ue_ue_s.Vector2D.md) |

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
