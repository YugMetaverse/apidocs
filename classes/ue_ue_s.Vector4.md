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

#### Defined in

[ue/ue_s.d.ts:572](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L572)

• **new Vector4**(`InColor`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Defined in

[ue/ue_s.d.ts:573](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L573)

• **new Vector4**(`InX`, `InY`, `InZ`, `InW`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InX` | `number` |
| `InY` | `number` |
| `InZ` | `number` |
| `InW` | `number` |

#### Defined in

[ue/ue_s.d.ts:574](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L574)

• **new Vector4**(`InXY`, `InZW`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InXY` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `InZW` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Defined in

[ue/ue_s.d.ts:575](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L575)

• **new Vector4**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

#### Defined in

[ue/ue_s.d.ts:576](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L576)

## Properties

### W

• **W**: `number`

#### Defined in

[ue/ue_s.d.ts:580](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L580)

___

### X

• **X**: `number`

#### Defined in

[ue/ue_s.d.ts:577](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L577)

___

### Y

• **Y**: `number`

#### Defined in

[ue/ue_s.d.ts:578](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L578)

___

### Z

• **Z**: `number`

#### Defined in

[ue/ue_s.d.ts:579](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L579)

___

### \_\_tid\_Vector4\_\_

• `Private` **\_\_tid\_Vector4\_\_**: `boolean`

#### Defined in

[ue/ue_s.d.ts:621](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L621)

## Methods

### Component

▸ **Component**(`Index`): [`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

[`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

#### Defined in

[ue/ue_s.d.ts:593](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L593)

▸ **Component**(`Index`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:594](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L594)

___

### ContainsNaN

▸ **ContainsNaN**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:609](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L609)

___

### DiagnosticCheckNaN

▸ **DiagnosticCheckNaN**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:613](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L613)

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

#### Defined in

[ue/ue_s.d.ts:595](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L595)

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

#### Defined in

[ue/ue_s.d.ts:612](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L612)

___

### GetSafeNormal

▸ **GetSafeNormal**(`Tolerance`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue_s.d.ts:599](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L599)

___

### GetUnsafeNormal3

▸ **GetUnsafeNormal3**(): [`Vector4`](ue_ue_s.Vector4.md)

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue_s.d.ts:600](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L600)

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

[ue/ue_s.d.ts:598](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L598)

___

### IsNearlyZero3

▸ **IsNearlyZero3**(`Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:610](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L610)

___

### IsUnit3

▸ **IsUnit3**(`LengthSquaredTolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LengthSquaredTolerance` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:596](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L596)

___

### Reflect3

▸ **Reflect3**(`Normal`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Normal` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue_s.d.ts:611](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L611)

___

### Rotation

▸ **Rotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue_s.d.ts:603](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L603)

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

#### Defined in

[ue/ue_s.d.ts:604](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L604)

___

### Size

▸ **Size**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:607](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L607)

___

### Size3

▸ **Size3**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:605](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L605)

___

### SizeSquared

▸ **SizeSquared**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:608](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L608)

___

### SizeSquared3

▸ **SizeSquared3**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:606](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L606)

___

### ToOrientationQuat

▸ **ToOrientationQuat**(): [`Quat`](ue_ue_s.Quat.md)

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue_s.d.ts:602](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L602)

___

### ToOrientationRotator

▸ **ToOrientationRotator**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue_s.d.ts:601](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L601)

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue_s.d.ts:597](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L597)

___

### get\_Item

▸ **get_Item**(`ComponentIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ComponentIndex` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:582](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L582)

___

### op\_Addition

▸ **op_Addition**(`V`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue_s.d.ts:584](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L584)

___

### op\_Division

▸ **op_Division**(`Scale`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue_s.d.ts:588](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L588)

▸ **op_Division**(`V`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue_s.d.ts:589](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L589)

___

### op\_Equality

▸ **op_Equality**(`V`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:590](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L590)

___

### op\_ExclusiveOr

▸ **op_ExclusiveOr**(`V`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue_s.d.ts:592](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L592)

___

### op\_Inequality

▸ **op_Inequality**(`V`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:591](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L591)

___

### op\_Multiply

▸ **op_Multiply**(`Scale`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue_s.d.ts:586](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L586)

▸ **op_Multiply**(`V`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue_s.d.ts:587](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L587)

___

### op\_Subtraction

▸ **op_Subtraction**(`V`): [`Vector4`](ue_ue_s.Vector4.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue_s.d.ts:585](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L585)

___

### op\_UnaryNegation

▸ **op_UnaryNegation**(): [`Vector4`](ue_ue_s.Vector4.md)

#### Returns

[`Vector4`](ue_ue_s.Vector4.md)

#### Defined in

[ue/ue_s.d.ts:583](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L583)

___

### set\_Item

▸ **set_Item**(`ComponentIndex`): [`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `ComponentIndex` | `number` |

#### Returns

[`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

#### Defined in

[ue/ue_s.d.ts:581](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L581)

___

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:618](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L618)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:619](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L619)
