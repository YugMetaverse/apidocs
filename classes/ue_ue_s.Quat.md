[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue\_s](../modules/ue_ue_s.md) / Quat

# Class: Quat

[ue/ue_s](../modules/ue_ue_s.md).Quat

## Table of contents

### Constructors

- [constructor](ue_ue_s.Quat.md#constructor)

### Properties

- [W](ue_ue_s.Quat.md#w)
- [X](ue_ue_s.Quat.md#x)
- [Y](ue_ue_s.Quat.md#y)
- [Z](ue_ue_s.Quat.md#z)
- [\_\_tid\_Quat\_\_](ue_ue_s.Quat.md#__tid_quat__)

### Methods

- [AngularDistance](ue_ue_s.Quat.md#angulardistance)
- [ContainsNaN](ue_ue_s.Quat.md#containsnan)
- [DiagnosticCheckNaN](ue_ue_s.Quat.md#diagnosticchecknan)
- [EnforceShortestArcWith](ue_ue_s.Quat.md#enforceshortestarcwith)
- [Equals](ue_ue_s.Quat.md#equals)
- [Euler](ue_ue_s.Quat.md#euler)
- [Exp](ue_ue_s.Quat.md#exp)
- [GetAngle](ue_ue_s.Quat.md#getangle)
- [GetAxisX](ue_ue_s.Quat.md#getaxisx)
- [GetAxisY](ue_ue_s.Quat.md#getaxisy)
- [GetAxisZ](ue_ue_s.Quat.md#getaxisz)
- [GetForwardVector](ue_ue_s.Quat.md#getforwardvector)
- [GetNormalized](ue_ue_s.Quat.md#getnormalized)
- [GetRightVector](ue_ue_s.Quat.md#getrightvector)
- [GetRotationAxis](ue_ue_s.Quat.md#getrotationaxis)
- [GetUpVector](ue_ue_s.Quat.md#getupvector)
- [InitFromString](ue_ue_s.Quat.md#initfromstring)
- [Inverse](ue_ue_s.Quat.md#inverse)
- [IsIdentity](ue_ue_s.Quat.md#isidentity)
- [IsNormalized](ue_ue_s.Quat.md#isnormalized)
- [Log](ue_ue_s.Quat.md#log)
- [Normalize](ue_ue_s.Quat.md#normalize)
- [RotateVector](ue_ue_s.Quat.md#rotatevector)
- [Rotator](ue_ue_s.Quat.md#rotator)
- [Size](ue_ue_s.Quat.md#size)
- [SizeSquared](ue_ue_s.Quat.md#sizesquared)
- [ToAxisAndAngle](ue_ue_s.Quat.md#toaxisandangle)
- [ToString](ue_ue_s.Quat.md#tostring)
- [ToSwingTwist](ue_ue_s.Quat.md#toswingtwist)
- [UnrotateVector](ue_ue_s.Quat.md#unrotatevector)
- [Vector](ue_ue_s.Quat.md#vector)
- [op\_Addition](ue_ue_s.Quat.md#op_addition)
- [op\_BitwiseOr](ue_ue_s.Quat.md#op_bitwiseor)
- [op\_Division](ue_ue_s.Quat.md#op_division)
- [op\_Equality](ue_ue_s.Quat.md#op_equality)
- [op\_Inequality](ue_ue_s.Quat.md#op_inequality)
- [op\_Multiply](ue_ue_s.Quat.md#op_multiply)
- [op\_Subtraction](ue_ue_s.Quat.md#op_subtraction)
- [CalcTangents](ue_ue_s.Quat.md#calctangents)
- [Error](ue_ue_s.Quat.md#error)
- [ErrorAutoNormalize](ue_ue_s.Quat.md#errorautonormalize)
- [FastBilerp](ue_ue_s.Quat.md#fastbilerp)
- [FastLerp](ue_ue_s.Quat.md#fastlerp)
- [FindBetween](ue_ue_s.Quat.md#findbetween)
- [FindBetweenNormals](ue_ue_s.Quat.md#findbetweennormals)
- [FindBetweenVectors](ue_ue_s.Quat.md#findbetweenvectors)
- [MakeFromEuler](ue_ue_s.Quat.md#makefromeuler)
- [Slerp](ue_ue_s.Quat.md#slerp)
- [SlerpFullPath](ue_ue_s.Quat.md#slerpfullpath)
- [SlerpFullPath\_NotNormalized](ue_ue_s.Quat.md#slerpfullpath_notnormalized)
- [Slerp\_NotNormalized](ue_ue_s.Quat.md#slerp_notnormalized)
- [Squad](ue_ue_s.Quat.md#squad)
- [SquadFullPath](ue_ue_s.Quat.md#squadfullpath)
- [StaticClass](ue_ue_s.Quat.md#staticclass)
- [StaticStruct](ue_ue_s.Quat.md#staticstruct)

## Constructors

### constructor

• **new Quat**()

• **new Quat**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

• **new Quat**(`InX`, `InY`, `InZ`, `InW`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InX` | `number` |
| `InY` | `number` |
| `InZ` | `number` |
| `InW` | `number` |

• **new Quat**(`R`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `R` | [`Rotator`](ue_ue_s.Rotator.md) |

• **new Quat**(`Axis`, `AngleRad`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Axis` | [`Vector`](ue_ue_s.Vector.md) |
| `AngleRad` | `number` |

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

### \_\_tid\_Quat\_\_

• `Private` **\_\_tid\_Quat\_\_**: `boolean`

## Methods

### AngularDistance

▸ **AngularDistance**(`Q`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

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

### EnforceShortestArcWith

▸ **EnforceShortestArcWith**(`OtherQuat`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherQuat` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

`void`

___

### Equals

▸ **Equals**(`Q`, `Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### Euler

▸ **Euler**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### Exp

▸ **Exp**(): [`Quat`](ue_ue_s.Quat.md)

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### GetAngle

▸ **GetAngle**(): `number`

#### Returns

`number`

___

### GetAxisX

▸ **GetAxisX**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetAxisY

▸ **GetAxisY**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetAxisZ

▸ **GetAxisZ**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetNormalized

▸ **GetNormalized**(`Tolerance`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetRotationAxis

▸ **GetRotationAxis**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

### Inverse

▸ **Inverse**(): [`Quat`](ue_ue_s.Quat.md)

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### IsIdentity

▸ **IsIdentity**(`Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### IsNormalized

▸ **IsNormalized**(): `boolean`

#### Returns

`boolean`

___

### Log

▸ **Log**(): [`Quat`](ue_ue_s.Quat.md)

#### Returns

[`Quat`](ue_ue_s.Quat.md)

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

### RotateVector

▸ **RotateVector**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### Rotator

▸ **Rotator**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

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

### ToAxisAndAngle

▸ **ToAxisAndAngle**(`Axis`, `Angle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Axis` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `Angle` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

___

### ToSwingTwist

▸ **ToSwingTwist**(`InTwistAxis`, `OutSwing`, `OutTwist`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTwistAxis` | [`Vector`](ue_ue_s.Vector.md) |
| `OutSwing` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Quat`](ue_ue_s.Quat.md)\> |
| `OutTwist` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Quat`](ue_ue_s.Quat.md)\> |

#### Returns

`void`

___

### UnrotateVector

▸ **UnrotateVector**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### Vector

▸ **Vector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### op\_Addition

▸ **op_Addition**(`Q`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### op\_BitwiseOr

▸ **op_BitwiseOr**(`Q`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

`number`

___

### op\_Division

▸ **op_Division**(`Scale`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### op\_Equality

▸ **op_Equality**(`Q`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

`boolean`

___

### op\_Inequality

▸ **op_Inequality**(`Q`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

`boolean`

___

### op\_Multiply

▸ **op_Multiply**(`Q`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

▸ **op_Multiply**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

▸ **op_Multiply**(`Scale`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### op\_Subtraction

▸ **op_Subtraction**(`Q`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### CalcTangents

▸ `Static` **CalcTangents**(`PrevP`, `P`, `NextP`, `Tension`, `OutTan`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrevP` | [`Quat`](ue_ue_s.Quat.md) |
| `P` | [`Quat`](ue_ue_s.Quat.md) |
| `NextP` | [`Quat`](ue_ue_s.Quat.md) |
| `Tension` | `number` |
| `OutTan` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Quat`](ue_ue_s.Quat.md)\> |

#### Returns

`void`

___

### Error

▸ `Static` **Error**(`Q1`, `Q2`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q1` | [`Quat`](ue_ue_s.Quat.md) |
| `Q2` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

`number`

___

### ErrorAutoNormalize

▸ `Static` **ErrorAutoNormalize**(`A`, `B`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Quat`](ue_ue_s.Quat.md) |
| `B` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

`number`

___

### FastBilerp

▸ `Static` **FastBilerp**(`P00`, `P10`, `P01`, `P11`, `FracX`, `FracY`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `P00` | [`Quat`](ue_ue_s.Quat.md) |
| `P10` | [`Quat`](ue_ue_s.Quat.md) |
| `P01` | [`Quat`](ue_ue_s.Quat.md) |
| `P11` | [`Quat`](ue_ue_s.Quat.md) |
| `FracX` | `number` |
| `FracY` | `number` |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### FastLerp

▸ `Static` **FastLerp**(`A`, `B`, `Alpha`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Quat`](ue_ue_s.Quat.md) |
| `B` | [`Quat`](ue_ue_s.Quat.md) |
| `Alpha` | `number` |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### FindBetween

▸ `Static` **FindBetween**(`Vector1`, `Vector2`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Vector1` | [`Vector`](ue_ue_s.Vector.md) |
| `Vector2` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### FindBetweenNormals

▸ `Static` **FindBetweenNormals**(`Normal1`, `Normal2`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Normal1` | [`Vector`](ue_ue_s.Vector.md) |
| `Normal2` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### FindBetweenVectors

▸ `Static` **FindBetweenVectors**(`Vector1`, `Vector2`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Vector1` | [`Vector`](ue_ue_s.Vector.md) |
| `Vector2` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### MakeFromEuler

▸ `Static` **MakeFromEuler**(`Euler`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Euler` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### Slerp

▸ `Static` **Slerp**(`Quat1`, `Quat2`, `Slerp`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Quat1` | [`Quat`](ue_ue_s.Quat.md) |
| `Quat2` | [`Quat`](ue_ue_s.Quat.md) |
| `Slerp` | `number` |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### SlerpFullPath

▸ `Static` **SlerpFullPath**(`quat1`, `quat2`, `Alpha`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `quat1` | [`Quat`](ue_ue_s.Quat.md) |
| `quat2` | [`Quat`](ue_ue_s.Quat.md) |
| `Alpha` | `number` |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### SlerpFullPath\_NotNormalized

▸ `Static` **SlerpFullPath_NotNormalized**(`quat1`, `quat2`, `Alpha`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `quat1` | [`Quat`](ue_ue_s.Quat.md) |
| `quat2` | [`Quat`](ue_ue_s.Quat.md) |
| `Alpha` | `number` |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### Slerp\_NotNormalized

▸ `Static` **Slerp_NotNormalized**(`Quat1`, `Quat2`, `Slerp`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Quat1` | [`Quat`](ue_ue_s.Quat.md) |
| `Quat2` | [`Quat`](ue_ue_s.Quat.md) |
| `Slerp` | `number` |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### Squad

▸ `Static` **Squad**(`quat1`, `tang1`, `quat2`, `tang2`, `Alpha`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `quat1` | [`Quat`](ue_ue_s.Quat.md) |
| `tang1` | [`Quat`](ue_ue_s.Quat.md) |
| `quat2` | [`Quat`](ue_ue_s.Quat.md) |
| `tang2` | [`Quat`](ue_ue_s.Quat.md) |
| `Alpha` | `number` |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

___

### SquadFullPath

▸ `Static` **SquadFullPath**(`quat1`, `tang1`, `quat2`, `tang2`, `Alpha`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `quat1` | [`Quat`](ue_ue_s.Quat.md) |
| `tang1` | [`Quat`](ue_ue_s.Quat.md) |
| `quat2` | [`Quat`](ue_ue_s.Quat.md) |
| `tang2` | [`Quat`](ue_ue_s.Quat.md) |
| `Alpha` | `number` |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

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
