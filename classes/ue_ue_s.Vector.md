[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue\_s](../modules/ue_ue_s.md) / Vector

# Class: Vector

[ue/ue_s](../modules/ue_ue_s.md).Vector

## Hierarchy

- **`Vector`**

  ↳ [`Vector_NetQuantize100`](ue_ue.Vector_NetQuantize100.md)

  ↳ [`Vector_NetQuantize`](ue_ue.Vector_NetQuantize.md)

  ↳ [`Vector_NetQuantizeNormal`](ue_ue.Vector_NetQuantizeNormal.md)

  ↳ [`Plane`](ue_ue.Plane.md)

  ↳ [`Vector_NetQuantize10`](ue_ue.Vector_NetQuantize10.md)

## Table of contents

### Constructors

- [constructor](ue_ue_s.Vector.md#constructor)

### Properties

- [X](ue_ue_s.Vector.md#x)
- [Y](ue_ue_s.Vector.md#y)
- [Z](ue_ue_s.Vector.md#z)
- [\_\_tid\_Vector\_\_](ue_ue_s.Vector.md#__tid_vector__)

### Methods

- [AddBounded](ue_ue_s.Vector.md#addbounded)
- [AllComponentsEqual](ue_ue_s.Vector.md#allcomponentsequal)
- [BoundToBox](ue_ue_s.Vector.md#boundtobox)
- [BoundToCube](ue_ue_s.Vector.md#boundtocube)
- [Component](ue_ue_s.Vector.md#component)
- [ComponentMax](ue_ue_s.Vector.md#componentmax)
- [ComponentMin](ue_ue_s.Vector.md#componentmin)
- [ContainsNaN](ue_ue_s.Vector.md#containsnan)
- [CosineAngle2D](ue_ue_s.Vector.md#cosineangle2d)
- [DiagnosticCheckNaN](ue_ue_s.Vector.md#diagnosticchecknan)
- [Equals](ue_ue_s.Vector.md#equals)
- [FindBestAxisVectors](ue_ue_s.Vector.md#findbestaxisvectors)
- [GetAbs](ue_ue_s.Vector.md#getabs)
- [GetAbsMax](ue_ue_s.Vector.md#getabsmax)
- [GetAbsMin](ue_ue_s.Vector.md#getabsmin)
- [GetClampedToMaxSize](ue_ue_s.Vector.md#getclampedtomaxsize)
- [GetClampedToMaxSize2D](ue_ue_s.Vector.md#getclampedtomaxsize2d)
- [GetClampedToSize](ue_ue_s.Vector.md#getclampedtosize)
- [GetClampedToSize2D](ue_ue_s.Vector.md#getclampedtosize2d)
- [GetComponentForAxis](ue_ue_s.Vector.md#getcomponentforaxis)
- [GetMax](ue_ue_s.Vector.md#getmax)
- [GetMin](ue_ue_s.Vector.md#getmin)
- [GetSafeNormal](ue_ue_s.Vector.md#getsafenormal)
- [GetSafeNormal2D](ue_ue_s.Vector.md#getsafenormal2d)
- [GetSignVector](ue_ue_s.Vector.md#getsignvector)
- [GetUnsafeNormal](ue_ue_s.Vector.md#getunsafenormal)
- [GetUnsafeNormal2D](ue_ue_s.Vector.md#getunsafenormal2d)
- [GridSnap](ue_ue_s.Vector.md#gridsnap)
- [HeadingAngle](ue_ue_s.Vector.md#headingangle)
- [InitFromString](ue_ue_s.Vector.md#initfromstring)
- [IsNearlyZero](ue_ue_s.Vector.md#isnearlyzero)
- [IsNormalized](ue_ue_s.Vector.md#isnormalized)
- [IsUniform](ue_ue_s.Vector.md#isuniform)
- [IsUnit](ue_ue_s.Vector.md#isunit)
- [IsZero](ue_ue_s.Vector.md#iszero)
- [MirrorByPlane](ue_ue_s.Vector.md#mirrorbyplane)
- [MirrorByVector](ue_ue_s.Vector.md#mirrorbyvector)
- [Normalize](ue_ue_s.Vector.md#normalize)
- [ProjectOnTo](ue_ue_s.Vector.md#projectonto)
- [ProjectOnToNormal](ue_ue_s.Vector.md#projectontonormal)
- [Projection](ue_ue_s.Vector.md#projection)
- [Reciprocal](ue_ue_s.Vector.md#reciprocal)
- [RotateAngleAxis](ue_ue_s.Vector.md#rotateangleaxis)
- [Rotation](ue_ue_s.Vector.md#rotation)
- [Set](ue_ue_s.Vector.md#set)
- [SetComponentForAxis](ue_ue_s.Vector.md#setcomponentforaxis)
- [Size](ue_ue_s.Vector.md#size)
- [Size2D](ue_ue_s.Vector.md#size2d)
- [SizeSquared](ue_ue_s.Vector.md#sizesquared)
- [SizeSquared2D](ue_ue_s.Vector.md#sizesquared2d)
- [ToCompactString](ue_ue_s.Vector.md#tocompactstring)
- [ToCompactText](ue_ue_s.Vector.md#tocompacttext)
- [ToDirectionAndLength](ue_ue_s.Vector.md#todirectionandlength)
- [ToOrientationQuat](ue_ue_s.Vector.md#toorientationquat)
- [ToOrientationRotator](ue_ue_s.Vector.md#toorientationrotator)
- [ToString](ue_ue_s.Vector.md#tostring)
- [ToText](ue_ue_s.Vector.md#totext)
- [UnitCartesianToSpherical](ue_ue_s.Vector.md#unitcartesiantospherical)
- [UnwindEuler](ue_ue_s.Vector.md#unwindeuler)
- [get\_Item](ue_ue_s.Vector.md#get_item)
- [op\_Addition](ue_ue_s.Vector.md#op_addition)
- [op\_BitwiseOr](ue_ue_s.Vector.md#op_bitwiseor)
- [op\_Division](ue_ue_s.Vector.md#op_division)
- [op\_Equality](ue_ue_s.Vector.md#op_equality)
- [op\_ExclusiveOr](ue_ue_s.Vector.md#op_exclusiveor)
- [op\_Inequality](ue_ue_s.Vector.md#op_inequality)
- [op\_Multiply](ue_ue_s.Vector.md#op_multiply)
- [op\_Subtraction](ue_ue_s.Vector.md#op_subtraction)
- [op\_UnaryNegation](ue_ue_s.Vector.md#op_unarynegation)
- [set\_Item](ue_ue_s.Vector.md#set_item)
- [BoxPushOut](ue_ue_s.Vector.md#boxpushout)
- [Coincident](ue_ue_s.Vector.md#coincident)
- [Coplanar](ue_ue_s.Vector.md#coplanar)
- [CreateOrthonormalBasis](ue_ue_s.Vector.md#createorthonormalbasis)
- [CrossProduct](ue_ue_s.Vector.md#crossproduct)
- [DegreesToRadians](ue_ue_s.Vector.md#degreestoradians)
- [Dist](ue_ue_s.Vector.md#dist)
- [Dist2D](ue_ue_s.Vector.md#dist2d)
- [DistSquared](ue_ue_s.Vector.md#distsquared)
- [DistSquared2D](ue_ue_s.Vector.md#distsquared2d)
- [DistSquaredXY](ue_ue_s.Vector.md#distsquaredxy)
- [DistXY](ue_ue_s.Vector.md#distxy)
- [Distance](ue_ue_s.Vector.md#distance)
- [DotProduct](ue_ue_s.Vector.md#dotproduct)
- [Orthogonal](ue_ue_s.Vector.md#orthogonal)
- [Parallel](ue_ue_s.Vector.md#parallel)
- [PointPlaneDist](ue_ue_s.Vector.md#pointplanedist)
- [PointPlaneProject](ue_ue_s.Vector.md#pointplaneproject)
- [PointsAreNear](ue_ue_s.Vector.md#pointsarenear)
- [PointsAreSame](ue_ue_s.Vector.md#pointsaresame)
- [RadiansToDegrees](ue_ue_s.Vector.md#radianstodegrees)
- [StaticClass](ue_ue_s.Vector.md#staticclass)
- [StaticStruct](ue_ue_s.Vector.md#staticstruct)
- [Triple](ue_ue_s.Vector.md#triple)
- [VectorPlaneProject](ue_ue_s.Vector.md#vectorplaneproject)

## Constructors

### constructor

• **new Vector**()

• **new Vector**(`InF`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InF` | `number` |

• **new Vector**(`InX`, `InY`, `InZ`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InX` | `number` |
| `InY` | `number` |
| `InZ` | `number` |

• **new Vector**(`V`, `InZ`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `InZ` | `number` |

• **new Vector**(`V`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

• **new Vector**(`InColor`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |

• **new Vector**(`InVector`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVector` | [`IntVector`](ue_ue_s.IntVector.md) |

• **new Vector**(`A`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`IntPoint`](ue_ue_s.IntPoint.md) |

• **new Vector**(`Param1`)

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

### \_\_tid\_Vector\_\_

• `Private` **\_\_tid\_Vector\_\_**: `boolean`

## Methods

### AddBounded

▸ **AddBounded**(`V`, `Radius`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |
| `Radius` | `number` |

#### Returns

`void`

___

### AllComponentsEqual

▸ **AllComponentsEqual**(`Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### BoundToBox

▸ **BoundToBox**(`Min`, `Max`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Min` | [`Vector`](ue_ue_s.Vector.md) |
| `Max` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### BoundToCube

▸ **BoundToCube**(`Radius`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Radius` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

### ComponentMax

▸ **ComponentMax**(`Other`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### ComponentMin

▸ **ComponentMin**(`Other`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### ContainsNaN

▸ **ContainsNaN**(): `boolean`

#### Returns

`boolean`

___

### CosineAngle2D

▸ **CosineAngle2D**(`B`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `B` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`number`

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
| `V` | [`Vector`](ue_ue_s.Vector.md) |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### FindBestAxisVectors

▸ **FindBestAxisVectors**(`Axis1`, `Axis2`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Axis1` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `Axis2` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

___

### GetAbs

▸ **GetAbs**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetAbsMax

▸ **GetAbsMax**(): `number`

#### Returns

`number`

___

### GetAbsMin

▸ **GetAbsMin**(): `number`

#### Returns

`number`

___

### GetClampedToMaxSize

▸ **GetClampedToMaxSize**(`MaxSize`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaxSize` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetClampedToMaxSize2D

▸ **GetClampedToMaxSize2D**(`MaxSize`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaxSize` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetClampedToSize

▸ **GetClampedToSize**(`Min`, `Max`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Min` | `number` |
| `Max` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetClampedToSize2D

▸ **GetClampedToSize2D**(`Min`, `Max`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Min` | `number` |
| `Max` | `number` |

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

### GetSafeNormal

▸ **GetSafeNormal**(`Tolerance`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetSafeNormal2D

▸ **GetSafeNormal2D**(`Tolerance`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetSignVector

▸ **GetSignVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetUnsafeNormal

▸ **GetUnsafeNormal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GetUnsafeNormal2D

▸ **GetUnsafeNormal2D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### GridSnap

▸ **GridSnap**(`GridSz`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `GridSz` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### HeadingAngle

▸ **HeadingAngle**(): `number`

#### Returns

`number`

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

### IsNormalized

▸ **IsNormalized**(): `boolean`

#### Returns

`boolean`

___

### IsUniform

▸ **IsUniform**(`Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### IsUnit

▸ **IsUnit**(`LengthSquaredTolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LengthSquaredTolerance` | `number` |

#### Returns

`boolean`

___

### IsZero

▸ **IsZero**(): `boolean`

#### Returns

`boolean`

___

### MirrorByPlane

▸ **MirrorByPlane**(`Plane`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Plane` | [`FPlane`](ue_ue_s.FPlane.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### MirrorByVector

▸ **MirrorByVector**(`MirrorNormal`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MirrorNormal` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### Normalize

▸ **Normalize**(`Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### ProjectOnTo

▸ **ProjectOnTo**(`A`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### ProjectOnToNormal

▸ **ProjectOnToNormal**(`Normal`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Normal` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### Projection

▸ **Projection**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### Reciprocal

▸ **Reciprocal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### RotateAngleAxis

▸ **RotateAngleAxis**(`AngleDeg`, `Axis`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `AngleDeg` | `number` |
| `Axis` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### Rotation

▸ **Rotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

___

### Set

▸ **Set**(`InX`, `InY`, `InZ`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InX` | `number` |
| `InY` | `number` |
| `InZ` | `number` |

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

### Size

▸ **Size**(): `number`

#### Returns

`number`

___

### Size2D

▸ **Size2D**(): `number`

#### Returns

`number`

___

### SizeSquared

▸ **SizeSquared**(): `number`

#### Returns

`number`

___

### SizeSquared2D

▸ **SizeSquared2D**(): `number`

#### Returns

`number`

___

### ToCompactString

▸ **ToCompactString**(): `string`

#### Returns

`string`

___

### ToCompactText

▸ **ToCompactText**(): `string`

#### Returns

`string`

___

### ToDirectionAndLength

▸ **ToDirectionAndLength**(`OutDir`, `OutLength`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutDir` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `OutLength` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

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

### ToText

▸ **ToText**(): `string`

#### Returns

`string`

___

### UnitCartesianToSpherical

▸ **UnitCartesianToSpherical**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

___

### UnwindEuler

▸ **UnwindEuler**(): `void`

#### Returns

`void`

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

▸ **op_Addition**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

▸ **op_Addition**(`Bias`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Bias` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### op\_BitwiseOr

▸ **op_BitwiseOr**(`V`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`number`

___

### op\_Division

▸ **op_Division**(`Scale`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

▸ **op_Division**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### op\_Equality

▸ **op_Equality**(`V`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`boolean`

___

### op\_ExclusiveOr

▸ **op_ExclusiveOr**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### op\_Inequality

▸ **op_Inequality**(`V`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`boolean`

___

### op\_Multiply

▸ **op_Multiply**(`Scale`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

▸ **op_Multiply**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### op\_Subtraction

▸ **op_Subtraction**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

▸ **op_Subtraction**(`Bias`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Bias` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### op\_UnaryNegation

▸ **op_UnaryNegation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

### BoxPushOut

▸ `Static` **BoxPushOut**(`Normal`, `Size`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Normal` | [`Vector`](ue_ue_s.Vector.md) |
| `Size` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`number`

___

### Coincident

▸ `Static` **Coincident**(`Normal1`, `Normal2`, `ParallelCosineThreshold`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Normal1` | [`Vector`](ue_ue_s.Vector.md) |
| `Normal2` | [`Vector`](ue_ue_s.Vector.md) |
| `ParallelCosineThreshold` | `number` |

#### Returns

`boolean`

___

### Coplanar

▸ `Static` **Coplanar**(`Base1`, `Normal1`, `Base2`, `Normal2`, `ParallelCosineThreshold`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Base1` | [`Vector`](ue_ue_s.Vector.md) |
| `Normal1` | [`Vector`](ue_ue_s.Vector.md) |
| `Base2` | [`Vector`](ue_ue_s.Vector.md) |
| `Normal2` | [`Vector`](ue_ue_s.Vector.md) |
| `ParallelCosineThreshold` | `number` |

#### Returns

`boolean`

___

### CreateOrthonormalBasis

▸ `Static` **CreateOrthonormalBasis**(`XAxis`, `YAxis`, `ZAxis`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `XAxis` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `YAxis` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `ZAxis` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

___

### CrossProduct

▸ `Static` **CrossProduct**(`A`, `B`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Vector`](ue_ue_s.Vector.md) |
| `B` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### DegreesToRadians

▸ `Static` **DegreesToRadians**(`DegVector`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `DegVector` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### Dist

▸ `Static` **Dist**(`V1`, `V2`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V1` | [`Vector`](ue_ue_s.Vector.md) |
| `V2` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`number`

___

### Dist2D

▸ `Static` **Dist2D**(`V1`, `V2`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V1` | [`Vector`](ue_ue_s.Vector.md) |
| `V2` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`number`

___

### DistSquared

▸ `Static` **DistSquared**(`V1`, `V2`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V1` | [`Vector`](ue_ue_s.Vector.md) |
| `V2` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`number`

___

### DistSquared2D

▸ `Static` **DistSquared2D**(`V1`, `V2`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V1` | [`Vector`](ue_ue_s.Vector.md) |
| `V2` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`number`

___

### DistSquaredXY

▸ `Static` **DistSquaredXY**(`V1`, `V2`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V1` | [`Vector`](ue_ue_s.Vector.md) |
| `V2` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`number`

___

### DistXY

▸ `Static` **DistXY**(`V1`, `V2`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V1` | [`Vector`](ue_ue_s.Vector.md) |
| `V2` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`number`

___

### Distance

▸ `Static` **Distance**(`V1`, `V2`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V1` | [`Vector`](ue_ue_s.Vector.md) |
| `V2` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`number`

___

### DotProduct

▸ `Static` **DotProduct**(`A`, `B`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Vector`](ue_ue_s.Vector.md) |
| `B` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`number`

___

### Orthogonal

▸ `Static` **Orthogonal**(`Normal1`, `Normal2`, `OrthogonalCosineThreshold`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Normal1` | [`Vector`](ue_ue_s.Vector.md) |
| `Normal2` | [`Vector`](ue_ue_s.Vector.md) |
| `OrthogonalCosineThreshold` | `number` |

#### Returns

`boolean`

___

### Parallel

▸ `Static` **Parallel**(`Normal1`, `Normal2`, `ParallelCosineThreshold`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Normal1` | [`Vector`](ue_ue_s.Vector.md) |
| `Normal2` | [`Vector`](ue_ue_s.Vector.md) |
| `ParallelCosineThreshold` | `number` |

#### Returns

`boolean`

___

### PointPlaneDist

▸ `Static` **PointPlaneDist**(`Point`, `PlaneBase`, `PlaneNormal`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Point` | [`Vector`](ue_ue_s.Vector.md) |
| `PlaneBase` | [`Vector`](ue_ue_s.Vector.md) |
| `PlaneNormal` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`number`

___

### PointPlaneProject

▸ `Static` **PointPlaneProject**(`Point`, `Plane`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Point` | [`Vector`](ue_ue_s.Vector.md) |
| `Plane` | [`FPlane`](ue_ue_s.FPlane.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

▸ `Static` **PointPlaneProject**(`Point`, `A`, `B`, `C`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Point` | [`Vector`](ue_ue_s.Vector.md) |
| `A` | [`Vector`](ue_ue_s.Vector.md) |
| `B` | [`Vector`](ue_ue_s.Vector.md) |
| `C` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

▸ `Static` **PointPlaneProject**(`Point`, `PlaneBase`, `PlaneNormal`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Point` | [`Vector`](ue_ue_s.Vector.md) |
| `PlaneBase` | [`Vector`](ue_ue_s.Vector.md) |
| `PlaneNormal` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

___

### PointsAreNear

▸ `Static` **PointsAreNear**(`Point1`, `Point2`, `Dist`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Point1` | [`Vector`](ue_ue_s.Vector.md) |
| `Point2` | [`Vector`](ue_ue_s.Vector.md) |
| `Dist` | `number` |

#### Returns

`boolean`

___

### PointsAreSame

▸ `Static` **PointsAreSame**(`P`, `Q`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `P` | [`Vector`](ue_ue_s.Vector.md) |
| `Q` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`boolean`

___

### RadiansToDegrees

▸ `Static` **RadiansToDegrees**(`RadVector`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `RadVector` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

___

### Triple

▸ `Static` **Triple**(`X`, `Y`, `Z`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `X` | [`Vector`](ue_ue_s.Vector.md) |
| `Y` | [`Vector`](ue_ue_s.Vector.md) |
| `Z` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`number`

___

### VectorPlaneProject

▸ `Static` **VectorPlaneProject**(`V`, `PlaneNormal`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |
| `PlaneNormal` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)
