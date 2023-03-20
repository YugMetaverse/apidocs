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

#### Defined in

[ue/ue_s.d.ts:155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L155)

• **new Quat**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

#### Defined in

[ue/ue_s.d.ts:156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L156)

• **new Quat**(`InX`, `InY`, `InZ`, `InW`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InX` | `number` |
| `InY` | `number` |
| `InZ` | `number` |
| `InW` | `number` |

#### Defined in

[ue/ue_s.d.ts:157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L157)

• **new Quat**(`R`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `R` | [`Rotator`](ue_ue_s.Rotator.md) |

#### Defined in

[ue/ue_s.d.ts:158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L158)

• **new Quat**(`Axis`, `AngleRad`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Axis` | [`Vector`](ue_ue_s.Vector.md) |
| `AngleRad` | `number` |

#### Defined in

[ue/ue_s.d.ts:159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L159)

## Properties

### W

• **W**: `number`

#### Defined in

[ue/ue_s.d.ts:163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L163)

___

### X

• **X**: `number`

#### Defined in

[ue/ue_s.d.ts:160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L160)

___

### Y

• **Y**: `number`

#### Defined in

[ue/ue_s.d.ts:161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L161)

___

### Z

• **Z**: `number`

#### Defined in

[ue/ue_s.d.ts:162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L162)

___

### \_\_tid\_Quat\_\_

• `Private` **\_\_tid\_Quat\_\_**: `boolean`

#### Defined in

[ue/ue_s.d.ts:226](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L226)

## Methods

### AngularDistance

▸ **AngularDistance**(`Q`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L200)

___

### ContainsNaN

▸ **ContainsNaN**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L201)

___

### DiagnosticCheckNaN

▸ **DiagnosticCheckNaN**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L204)

___

### EnforceShortestArcWith

▸ **EnforceShortestArcWith**(`OtherQuat`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OtherQuat` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L190)

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

#### Defined in

[ue/ue_s.d.ts:166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L166)

___

### Euler

▸ **Euler**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L176)

___

### Exp

▸ **Exp**(): [`Quat`](ue_ue_s.Quat.md)

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue_s.d.ts:188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L188)

___

### GetAngle

▸ **GetAngle**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L182)

___

### GetAxisX

▸ **GetAxisX**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L191)

___

### GetAxisY

▸ **GetAxisY**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L192)

___

### GetAxisZ

▸ **GetAxisZ**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L193)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L194)

___

### GetNormalized

▸ **GetNormalized**(`Tolerance`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue_s.d.ts:178](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L178)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L195)

___

### GetRotationAxis

▸ **GetRotationAxis**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L199)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L196)

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

[ue/ue_s.d.ts:203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L203)

___

### Inverse

▸ **Inverse**(): [`Quat`](ue_ue_s.Quat.md)

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue_s.d.ts:189](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L189)

___

### IsIdentity

▸ **IsIdentity**(`Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L167)

___

### IsNormalized

▸ **IsNormalized**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:179](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L179)

___

### Log

▸ **Log**(): [`Quat`](ue_ue_s.Quat.md)

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue_s.d.ts:187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L187)

___

### Normalize

▸ **Normalize**(`Tolerance`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:177](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L177)

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

[ue/ue_s.d.ts:185](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L185)

___

### Rotator

▸ **Rotator**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue_s.d.ts:198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L198)

___

### Size

▸ **Size**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L180)

___

### SizeSquared

▸ **SizeSquared**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L181)

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

#### Defined in

[ue/ue_s.d.ts:183](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L183)

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue_s.d.ts:202](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L202)

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

#### Defined in

[ue/ue_s.d.ts:184](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L184)

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

[ue/ue_s.d.ts:186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L186)

___

### Vector

▸ **Vector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L197)

___

### op\_Addition

▸ **op_Addition**(`Q`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue_s.d.ts:164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L164)

___

### op\_BitwiseOr

▸ **op_BitwiseOr**(`Q`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L174)

___

### op\_Division

▸ **op_Division**(`Scale`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue_s.d.ts:171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L171)

___

### op\_Equality

▸ **op_Equality**(`Q`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L172)

___

### op\_Inequality

▸ **op_Inequality**(`Q`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L173)

___

### op\_Multiply

▸ **op_Multiply**(`Q`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue_s.d.ts:168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L168)

▸ **op_Multiply**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L169)

▸ **op_Multiply**(`Scale`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue_s.d.ts:170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L170)

___

### op\_Subtraction

▸ **op_Subtraction**(`Q`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Q` | [`Quat`](ue_ue_s.Quat.md) |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue_s.d.ts:165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L165)

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

#### Defined in

[ue/ue_s.d.ts:218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L218)

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

#### Defined in

[ue/ue_s.d.ts:208](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L208)

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

#### Defined in

[ue/ue_s.d.ts:209](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L209)

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

#### Defined in

[ue/ue_s.d.ts:211](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L211)

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

#### Defined in

[ue/ue_s.d.ts:210](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L210)

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

#### Defined in

[ue/ue_s.d.ts:205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L205)

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

#### Defined in

[ue/ue_s.d.ts:206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L206)

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

#### Defined in

[ue/ue_s.d.ts:207](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L207)

___

### MakeFromEuler

▸ `Static` **MakeFromEuler**(`Euler`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Euler` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue_s.d.ts:175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L175)

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

#### Defined in

[ue/ue_s.d.ts:213](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L213)

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

#### Defined in

[ue/ue_s.d.ts:215](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L215)

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

#### Defined in

[ue/ue_s.d.ts:214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L214)

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

#### Defined in

[ue/ue_s.d.ts:212](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L212)

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

#### Defined in

[ue/ue_s.d.ts:216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L216)

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

#### Defined in

[ue/ue_s.d.ts:217](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L217)

___

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:223](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L223)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:224](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L224)
