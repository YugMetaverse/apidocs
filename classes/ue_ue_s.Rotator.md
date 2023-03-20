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

#### Defined in

[ue/ue_s.d.ts:230](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L230)

• **new Rotator**(`InF`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InF` | `number` |

#### Defined in

[ue/ue_s.d.ts:231](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L231)

• **new Rotator**(`InPitch`, `InYaw`, `InRoll`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPitch` | `number` |
| `InYaw` | `number` |
| `InRoll` | `number` |

#### Defined in

[ue/ue_s.d.ts:232](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L232)

• **new Rotator**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

#### Defined in

[ue/ue_s.d.ts:233](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L233)

• **new Rotator**(`Quat`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Quat` | [`Quat`](ue_ue_s.Quat.md) |

#### Defined in

[ue/ue_s.d.ts:234](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L234)

## Properties

### Pitch

• **Pitch**: `number`

#### Defined in

[ue/ue_s.d.ts:235](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L235)

___

### Roll

• **Roll**: `number`

#### Defined in

[ue/ue_s.d.ts:237](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L237)

___

### Yaw

• **Yaw**: `number`

#### Defined in

[ue/ue_s.d.ts:236](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L236)

___

### \_\_tid\_Rotator\_\_

• `Private` **\_\_tid\_Rotator\_\_**: `boolean`

#### Defined in

[ue/ue_s.d.ts:283](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L283)

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

#### Defined in

[ue/ue_s.d.ts:247](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L247)

___

### Clamp

▸ **Clamp**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue_s.d.ts:255](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L255)

___

### ContainsNaN

▸ **ContainsNaN**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:268](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L268)

___

### DiagnosticCheckNaN

▸ **DiagnosticCheckNaN**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:238](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L238)

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

#### Defined in

[ue/ue_s.d.ts:246](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L246)

___

### Euler

▸ **Euler**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:252](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L252)

___

### GetComponentForAxis

▸ **GetComponentForAxis**(`Axis`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Axis` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:258](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L258)

___

### GetDenormalized

▸ **GetDenormalized**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue_s.d.ts:257](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L257)

___

### GetEquivalentRotator

▸ **GetEquivalentRotator**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue_s.d.ts:263](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L263)

___

### GetInverse

▸ **GetInverse**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue_s.d.ts:248](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L248)

___

### GetManhattanDistance

▸ **GetManhattanDistance**(`Rotator`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Rotator` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:262](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L262)

___

### GetNormalized

▸ **GetNormalized**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue_s.d.ts:256](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L256)

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

#### Defined in

[ue/ue_s.d.ts:261](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L261)

___

### GridSnap

▸ **GridSnap**(`RotGrid`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `RotGrid` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue_s.d.ts:249](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L249)

___

### InitFromString

▸ **InitFromString**(`InSourceString`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSourceString` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:267](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L267)

___

### IsNearlyZero

▸ **IsNearlyZero**(`Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:244](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L244)

___

### IsZero

▸ **IsZero**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:245](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L245)

___

### Normalize

▸ **Normalize**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:260](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L260)

___

### Quaternion

▸ **Quaternion**(): [`Quat`](ue_ue_s.Quat.md)

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue_s.d.ts:251](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L251)

___

### RotateVector

▸ **RotateVector**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:253](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L253)

___

### SetClosestToMe

▸ **SetClosestToMe**(`MakeClosest`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MakeClosest` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Rotator`](ue_ue_s.Rotator.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:264](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L264)

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

#### Defined in

[ue/ue_s.d.ts:259](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L259)

___

### ToCompactString

▸ **ToCompactString**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue_s.d.ts:266](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L266)

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue_s.d.ts:265](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L265)

___

### UnrotateVector

▸ **UnrotateVector**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:254](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L254)

___

### Vector

▸ **Vector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:250](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L250)

___

### op\_Addition

▸ **op_Addition**(`R`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `R` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue_s.d.ts:239](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L239)

___

### op\_Equality

▸ **op_Equality**(`R`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `R` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:242](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L242)

___

### op\_Inequality

▸ **op_Inequality**(`V`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:243](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L243)

___

### op\_Multiply

▸ **op_Multiply**(`Scale`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue_s.d.ts:241](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L241)

___

### op\_Subtraction

▸ **op_Subtraction**(`R`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `R` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue_s.d.ts:240](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L240)

___

### ClampAxis

▸ `Static` **ClampAxis**(`Angle`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Angle` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:269](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L269)

___

### CompressAxisToByte

▸ `Static` **CompressAxisToByte**(`Angle`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Angle` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:271](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L271)

___

### CompressAxisToShort

▸ `Static` **CompressAxisToShort**(`Angle`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Angle` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:273](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L273)

___

### DecompressAxisFromByte

▸ `Static` **DecompressAxisFromByte**(`Angle`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Angle` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:272](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L272)

___

### DecompressAxisFromShort

▸ `Static` **DecompressAxisFromShort**(`Angle`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Angle` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:274](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L274)

___

### MakeFromEuler

▸ `Static` **MakeFromEuler**(`Euler`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Euler` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue_s.d.ts:275](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L275)

___

### NormalizeAxis

▸ `Static` **NormalizeAxis**(`Angle`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Angle` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:270](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L270)

___

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:280](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L280)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:281](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L281)
