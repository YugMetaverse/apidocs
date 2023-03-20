[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue\_s](../modules/ue_ue_s.md) / Rotator

# Class: Rotator

[ue/ue_s](../modules/ue_ue_s.md).Rotator

## Table of contents

### Constructors

- [constructor](ue_ue_s.Rotator.md#constructor)

### Properties

- [Pitch](ue_ue_s.Rotator.md#pitch)
- [Roll](ue_ue_s.Rotator.md#roll)
- [Yaw](ue_ue_s.Rotator.md#yaw)
- [\_\_tid\_Rotator\_\_](ue_ue_s.Rotator.md#__tid_rotator__)

### Methods

- [Add](ue_ue_s.Rotator.md#add)
- [Clamp](ue_ue_s.Rotator.md#clamp)
- [ContainsNaN](ue_ue_s.Rotator.md#containsnan)
- [DiagnosticCheckNaN](ue_ue_s.Rotator.md#diagnosticchecknan)
- [Equals](ue_ue_s.Rotator.md#equals)
- [Euler](ue_ue_s.Rotator.md#euler)
- [GetComponentForAxis](ue_ue_s.Rotator.md#getcomponentforaxis)
- [GetDenormalized](ue_ue_s.Rotator.md#getdenormalized)
- [GetEquivalentRotator](ue_ue_s.Rotator.md#getequivalentrotator)
- [GetInverse](ue_ue_s.Rotator.md#getinverse)
- [GetManhattanDistance](ue_ue_s.Rotator.md#getmanhattandistance)
- [GetNormalized](ue_ue_s.Rotator.md#getnormalized)
- [GetWindingAndRemainder](ue_ue_s.Rotator.md#getwindingandremainder)
- [GridSnap](ue_ue_s.Rotator.md#gridsnap)
- [InitFromString](ue_ue_s.Rotator.md#initfromstring)
- [IsNearlyZero](ue_ue_s.Rotator.md#isnearlyzero)
- [IsZero](ue_ue_s.Rotator.md#iszero)
- [Normalize](ue_ue_s.Rotator.md#normalize)
- [Quaternion](ue_ue_s.Rotator.md#quaternion)
- [RotateVector](ue_ue_s.Rotator.md#rotatevector)
- [SetClosestToMe](ue_ue_s.Rotator.md#setclosesttome)
- [SetComponentForAxis](ue_ue_s.Rotator.md#setcomponentforaxis)
- [ToCompactString](ue_ue_s.Rotator.md#tocompactstring)
- [ToString](ue_ue_s.Rotator.md#tostring)
- [UnrotateVector](ue_ue_s.Rotator.md#unrotatevector)
- [Vector](ue_ue_s.Rotator.md#vector)
- [op\_Addition](ue_ue_s.Rotator.md#op_addition)
- [op\_Equality](ue_ue_s.Rotator.md#op_equality)
- [op\_Inequality](ue_ue_s.Rotator.md#op_inequality)
- [op\_Multiply](ue_ue_s.Rotator.md#op_multiply)
- [op\_Subtraction](ue_ue_s.Rotator.md#op_subtraction)
- [ClampAxis](ue_ue_s.Rotator.md#clampaxis)
- [CompressAxisToByte](ue_ue_s.Rotator.md#compressaxistobyte)
- [CompressAxisToShort](ue_ue_s.Rotator.md#compressaxistoshort)
- [DecompressAxisFromByte](ue_ue_s.Rotator.md#decompressaxisfrombyte)
- [DecompressAxisFromShort](ue_ue_s.Rotator.md#decompressaxisfromshort)
- [MakeFromEuler](ue_ue_s.Rotator.md#makefromeuler)
- [NormalizeAxis](ue_ue_s.Rotator.md#normalizeaxis)
- [StaticClass](ue_ue_s.Rotator.md#staticclass)
- [StaticStruct](ue_ue_s.Rotator.md#staticstruct)

## Constructors

### constructor

• **new Rotator**()

• **new Rotator**(`InF`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InF` | `number` |

• **new Rotator**(`InPitch`, `InYaw`, `InRoll`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPitch` | `number` |
| `InYaw` | `number` |
| `InRoll` | `number` |

• **new Rotator**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

• **new Rotator**(`Quat`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Quat` | [`Quat`](ue_ue_s.Quat.md) |

## Properties

### Pitch

• **Pitch**: `number`

___

### Roll

• **Roll**: `number`

___

### Yaw

• **Yaw**: `number`

___

### \_\_tid\_Rotator\_\_

• `Private` **\_\_tid\_Rotator\_\_**: `boolean`

## Methods

### Add

▸ **Add**(`DeltaPitch`, `DeltaYaw`, `DeltaRoll`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaPitch` | `number` |
| `DeltaYaw` | `number` |
| `DeltaRoll` | `number` |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### Clamp

▸ **Clamp**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

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

▸ **Equals**(`R`, `Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `R` | [`Rotator`](ue_ue_s.Rotator.md) |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### Euler

▸ **Euler**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetComponentForAxis

▸ **GetComponentForAxis**(`Axis`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Axis` | `number` |

#### Returns

`number`

___

### GetDenormalized

▸ **GetDenormalized**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### GetEquivalentRotator

▸ **GetEquivalentRotator**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### GetInverse

▸ **GetInverse**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### GetManhattanDistance

▸ **GetManhattanDistance**(`Rotator`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Rotator` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`number`

___

### GetNormalized

▸ **GetNormalized**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### GetWindingAndRemainder

▸ **GetWindingAndRemainder**(`Winding`, `Remainder`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Winding` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |
| `Remainder` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |

#### Returns

`void`

___

### GridSnap

▸ **GridSnap**(`RotGrid`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `RotGrid` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

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

▸ **Normalize**(): `void`

#### Returns

`void`

___

### Quaternion

▸ **Quaternion**(): [`Quat`](ue_ue_s.Quat.md)

#### Returns

[`Quat`](ue_ue_s.Quat.md)

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

### SetClosestToMe

▸ **SetClosestToMe**(`MakeClosest`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MakeClosest` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |

#### Returns

`void`

___

### SetComponentForAxis

▸ **SetComponentForAxis**(`Axis`, `Component`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Axis` | `number` |
| `Component` | `number` |

#### Returns

`void`

___

### ToCompactString

▸ **ToCompactString**(): `string`

#### Returns

`string`

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

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

▸ **op_Addition**(`R`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `R` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### op\_Equality

▸ **op_Equality**(`R`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `R` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`boolean`

___

### op\_Inequality

▸ **op_Inequality**(`V`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`boolean`

___

### op\_Multiply

▸ **op_Multiply**(`Scale`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### op\_Subtraction

▸ **op_Subtraction**(`R`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `R` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### ClampAxis

▸ `Static` **ClampAxis**(`Angle`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Angle` | `number` |

#### Returns

`number`

___

### CompressAxisToByte

▸ `Static` **CompressAxisToByte**(`Angle`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Angle` | `number` |

#### Returns

`number`

___

### CompressAxisToShort

▸ `Static` **CompressAxisToShort**(`Angle`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Angle` | `number` |

#### Returns

`number`

___

### DecompressAxisFromByte

▸ `Static` **DecompressAxisFromByte**(`Angle`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Angle` | `number` |

#### Returns

`number`

___

### DecompressAxisFromShort

▸ `Static` **DecompressAxisFromShort**(`Angle`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Angle` | `number` |

#### Returns

`number`

___

### MakeFromEuler

▸ `Static` **MakeFromEuler**(`Euler`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Euler` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### NormalizeAxis

▸ `Static` **NormalizeAxis**(`Angle`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Angle` | `number` |

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
