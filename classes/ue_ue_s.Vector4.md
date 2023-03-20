[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue\_s](../modules/ue_ue_s.md) / Vector4

# Class: Vector4

[ue/ue_s](../modules/ue_ue_s.md).Vector4

## Table of contents

### Constructors

- [constructor](ue_ue_s.Vector4.md#constructor)

### Properties

- [W](ue_ue_s.Vector4.md#w)
- [X](ue_ue_s.Vector4.md#x)
- [Y](ue_ue_s.Vector4.md#y)
- [Z](ue_ue_s.Vector4.md#z)
- [\_\_tid\_Vector4\_\_](ue_ue_s.Vector4.md#__tid_vector4__)

### Methods

- [Component](ue_ue_s.Vector4.md#component)
- [ContainsNaN](ue_ue_s.Vector4.md#containsnan)
- [DiagnosticCheckNaN](ue_ue_s.Vector4.md#diagnosticchecknan)
- [Equals](ue_ue_s.Vector4.md#equals)
- [FindBestAxisVectors3](ue_ue_s.Vector4.md#findbestaxisvectors3)
- [GetSafeNormal](ue_ue_s.Vector4.md#getsafenormal)
- [GetUnsafeNormal3](ue_ue_s.Vector4.md#getunsafenormal3)
- [InitFromString](ue_ue_s.Vector4.md#initfromstring)
- [IsNearlyZero3](ue_ue_s.Vector4.md#isnearlyzero3)
- [IsUnit3](ue_ue_s.Vector4.md#isunit3)
- [Reflect3](ue_ue_s.Vector4.md#reflect3)
- [Rotation](ue_ue_s.Vector4.md#rotation)
- [Set](ue_ue_s.Vector4.md#set)
- [Size](ue_ue_s.Vector4.md#size)
- [Size3](ue_ue_s.Vector4.md#size3)
- [SizeSquared](ue_ue_s.Vector4.md#sizesquared)
- [SizeSquared3](ue_ue_s.Vector4.md#sizesquared3)
- [ToOrientationQuat](ue_ue_s.Vector4.md#toorientationquat)
- [ToOrientationRotator](ue_ue_s.Vector4.md#toorientationrotator)
- [ToString](ue_ue_s.Vector4.md#tostring)
- [get\_Item](ue_ue_s.Vector4.md#get_item)
- [op\_Addition](ue_ue_s.Vector4.md#op_addition)
- [op\_Division](ue_ue_s.Vector4.md#op_division)
- [op\_Equality](ue_ue_s.Vector4.md#op_equality)
- [op\_ExclusiveOr](ue_ue_s.Vector4.md#op_exclusiveor)
- [op\_Inequality](ue_ue_s.Vector4.md#op_inequality)
- [op\_Multiply](ue_ue_s.Vector4.md#op_multiply)
- [op\_Subtraction](ue_ue_s.Vector4.md#op_subtraction)
- [op\_UnaryNegation](ue_ue_s.Vector4.md#op_unarynegation)
- [set\_Item](ue_ue_s.Vector4.md#set_item)
- [StaticClass](ue_ue_s.Vector4.md#staticclass)
- [StaticStruct](ue_ue_s.Vector4.md#staticstruct)

## Constructors

### constructor

• **new Vector4**(`InVector`, `InW`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVector` | [`Vector`](ue_ue_s.Vector.md) |
| `InW` | `number` |

• **new Vector4**(`InColor`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |

• **new Vector4**(`InX`, `InY`, `InZ`, `InW`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InX` | `number` |
| `InY` | `number` |
| `InZ` | `number` |
| `InW` | `number` |

• **new Vector4**(`InXY`, `InZW`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InXY` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `InZW` | [`Vector2D`](ue_ue_s.Vector2D.md) |

• **new Vector4**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

## Properties

### W

• **W**: `number`

___

### X

• **X**: `number`

___

### Y

• **Y**: `number`

___

### Z

• **Z**: `number`

___

### \_\_tid\_Vector4\_\_

• `Private` **\_\_tid\_Vector4\_\_**: `boolean`

## Methods

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
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### FindBestAxisVectors3

▸ **FindBestAxisVectors3**(`Axis1`, `Axis2`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Axis1` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector4`](ue_ue_s.Vector4.md)\> |
| `Axis2` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector4`](ue_ue_s.Vector4.md)\> |

#### Returns

`void`

___

### GetSafeNormal

▸ **GetSafeNormal**(`Tolerance`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

___

### GetUnsafeNormal3

▸ **GetUnsafeNormal3**(): [`Vector4`](ue_ue_s.Vector4.md)

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

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

### IsNearlyZero3

▸ **IsNearlyZero3**(`Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### IsUnit3

▸ **IsUnit3**(`LengthSquaredTolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LengthSquaredTolerance` | `number` |

#### Returns

`boolean`

___

### Reflect3

▸ **Reflect3**(`Normal`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Normal` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

___

### Rotation

▸ **Rotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### Set

▸ **Set**(`InX`, `InY`, `InZ`, `InW`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InX` | `number` |
| `InY` | `number` |
| `InZ` | `number` |
| `InW` | `number` |

#### Returns

`void`

___

### Size

▸ **Size**(): `number`

#### Returns

`number`

___

### Size3

▸ **Size3**(): `number`

#### Returns

`number`

___

### SizeSquared

▸ **SizeSquared**(): `number`

#### Returns

`number`

___

### SizeSquared3

▸ **SizeSquared3**(): `number`

#### Returns

`number`

___

### ToOrientationQuat

▸ **ToOrientationQuat**(): [`Quat`](ue_ue_s.Quat.md)

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### ToOrientationRotator

▸ **ToOrientationRotator**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

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

▸ **op_Addition**(`V`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

___

### op\_Division

▸ **op_Division**(`Scale`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

▸ **op_Division**(`V`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

___

### op\_Equality

▸ **op_Equality**(`V`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

`boolean`

___

### op\_ExclusiveOr

▸ **op_ExclusiveOr**(`V`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

___

### op\_Inequality

▸ **op_Inequality**(`V`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

`boolean`

___

### op\_Multiply

▸ **op_Multiply**(`Scale`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

▸ **op_Multiply**(`V`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

___

### op\_Subtraction

▸ **op_Subtraction**(`V`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

___

### op\_UnaryNegation

▸ **op_UnaryNegation**(): [`Vector4`](ue_ue_s.Vector4.md)

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

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
