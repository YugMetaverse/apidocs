[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Vector\_NetQuantizeNormal

# Class: Vector\_NetQuantizeNormal

[ue/ue](../modules/ue_ue.md).Vector_NetQuantizeNormal

## Hierarchy

- [`Vector`](ue_ue_s.Vector.md)

  ↳ **`Vector_NetQuantizeNormal`**

## Table of contents

### Constructors

- [constructor](ue_ue.Vector_NetQuantizeNormal.md#constructor)

### Properties

- [X](ue_ue.Vector_NetQuantizeNormal.md#x)
- [Y](ue_ue.Vector_NetQuantizeNormal.md#y)
- [Z](ue_ue.Vector_NetQuantizeNormal.md#z)
- [\_\_tid\_Vector\_NetQuantizeNormal\_\_](ue_ue.Vector_NetQuantizeNormal.md#__tid_vector_netquantizenormal__)

### Methods

- [AddBounded](ue_ue.Vector_NetQuantizeNormal.md#addbounded)
- [AllComponentsEqual](ue_ue.Vector_NetQuantizeNormal.md#allcomponentsequal)
- [BoundToBox](ue_ue.Vector_NetQuantizeNormal.md#boundtobox)
- [BoundToCube](ue_ue.Vector_NetQuantizeNormal.md#boundtocube)
- [Component](ue_ue.Vector_NetQuantizeNormal.md#component)
- [ComponentMax](ue_ue.Vector_NetQuantizeNormal.md#componentmax)
- [ComponentMin](ue_ue.Vector_NetQuantizeNormal.md#componentmin)
- [ContainsNaN](ue_ue.Vector_NetQuantizeNormal.md#containsnan)
- [CosineAngle2D](ue_ue.Vector_NetQuantizeNormal.md#cosineangle2d)
- [DiagnosticCheckNaN](ue_ue.Vector_NetQuantizeNormal.md#diagnosticchecknan)
- [Equals](ue_ue.Vector_NetQuantizeNormal.md#equals)
- [FindBestAxisVectors](ue_ue.Vector_NetQuantizeNormal.md#findbestaxisvectors)
- [GetAbs](ue_ue.Vector_NetQuantizeNormal.md#getabs)
- [GetAbsMax](ue_ue.Vector_NetQuantizeNormal.md#getabsmax)
- [GetAbsMin](ue_ue.Vector_NetQuantizeNormal.md#getabsmin)
- [GetClampedToMaxSize](ue_ue.Vector_NetQuantizeNormal.md#getclampedtomaxsize)
- [GetClampedToMaxSize2D](ue_ue.Vector_NetQuantizeNormal.md#getclampedtomaxsize2d)
- [GetClampedToSize](ue_ue.Vector_NetQuantizeNormal.md#getclampedtosize)
- [GetClampedToSize2D](ue_ue.Vector_NetQuantizeNormal.md#getclampedtosize2d)
- [GetComponentForAxis](ue_ue.Vector_NetQuantizeNormal.md#getcomponentforaxis)
- [GetMax](ue_ue.Vector_NetQuantizeNormal.md#getmax)
- [GetMin](ue_ue.Vector_NetQuantizeNormal.md#getmin)
- [GetSafeNormal](ue_ue.Vector_NetQuantizeNormal.md#getsafenormal)
- [GetSafeNormal2D](ue_ue.Vector_NetQuantizeNormal.md#getsafenormal2d)
- [GetSignVector](ue_ue.Vector_NetQuantizeNormal.md#getsignvector)
- [GetUnsafeNormal](ue_ue.Vector_NetQuantizeNormal.md#getunsafenormal)
- [GetUnsafeNormal2D](ue_ue.Vector_NetQuantizeNormal.md#getunsafenormal2d)
- [GridSnap](ue_ue.Vector_NetQuantizeNormal.md#gridsnap)
- [HeadingAngle](ue_ue.Vector_NetQuantizeNormal.md#headingangle)
- [InitFromString](ue_ue.Vector_NetQuantizeNormal.md#initfromstring)
- [IsNearlyZero](ue_ue.Vector_NetQuantizeNormal.md#isnearlyzero)
- [IsNormalized](ue_ue.Vector_NetQuantizeNormal.md#isnormalized)
- [IsUniform](ue_ue.Vector_NetQuantizeNormal.md#isuniform)
- [IsUnit](ue_ue.Vector_NetQuantizeNormal.md#isunit)
- [IsZero](ue_ue.Vector_NetQuantizeNormal.md#iszero)
- [MirrorByPlane](ue_ue.Vector_NetQuantizeNormal.md#mirrorbyplane)
- [MirrorByVector](ue_ue.Vector_NetQuantizeNormal.md#mirrorbyvector)
- [Normalize](ue_ue.Vector_NetQuantizeNormal.md#normalize)
- [ProjectOnTo](ue_ue.Vector_NetQuantizeNormal.md#projectonto)
- [ProjectOnToNormal](ue_ue.Vector_NetQuantizeNormal.md#projectontonormal)
- [Projection](ue_ue.Vector_NetQuantizeNormal.md#projection)
- [Reciprocal](ue_ue.Vector_NetQuantizeNormal.md#reciprocal)
- [RotateAngleAxis](ue_ue.Vector_NetQuantizeNormal.md#rotateangleaxis)
- [Rotation](ue_ue.Vector_NetQuantizeNormal.md#rotation)
- [Set](ue_ue.Vector_NetQuantizeNormal.md#set)
- [SetComponentForAxis](ue_ue.Vector_NetQuantizeNormal.md#setcomponentforaxis)
- [Size](ue_ue.Vector_NetQuantizeNormal.md#size)
- [Size2D](ue_ue.Vector_NetQuantizeNormal.md#size2d)
- [SizeSquared](ue_ue.Vector_NetQuantizeNormal.md#sizesquared)
- [SizeSquared2D](ue_ue.Vector_NetQuantizeNormal.md#sizesquared2d)
- [ToCompactString](ue_ue.Vector_NetQuantizeNormal.md#tocompactstring)
- [ToCompactText](ue_ue.Vector_NetQuantizeNormal.md#tocompacttext)
- [ToDirectionAndLength](ue_ue.Vector_NetQuantizeNormal.md#todirectionandlength)
- [ToOrientationQuat](ue_ue.Vector_NetQuantizeNormal.md#toorientationquat)
- [ToOrientationRotator](ue_ue.Vector_NetQuantizeNormal.md#toorientationrotator)
- [ToString](ue_ue.Vector_NetQuantizeNormal.md#tostring)
- [ToText](ue_ue.Vector_NetQuantizeNormal.md#totext)
- [UnitCartesianToSpherical](ue_ue.Vector_NetQuantizeNormal.md#unitcartesiantospherical)
- [UnwindEuler](ue_ue.Vector_NetQuantizeNormal.md#unwindeuler)
- [get\_Item](ue_ue.Vector_NetQuantizeNormal.md#get_item)
- [op\_Addition](ue_ue.Vector_NetQuantizeNormal.md#op_addition)
- [op\_BitwiseOr](ue_ue.Vector_NetQuantizeNormal.md#op_bitwiseor)
- [op\_Division](ue_ue.Vector_NetQuantizeNormal.md#op_division)
- [op\_Equality](ue_ue.Vector_NetQuantizeNormal.md#op_equality)
- [op\_ExclusiveOr](ue_ue.Vector_NetQuantizeNormal.md#op_exclusiveor)
- [op\_Inequality](ue_ue.Vector_NetQuantizeNormal.md#op_inequality)
- [op\_Multiply](ue_ue.Vector_NetQuantizeNormal.md#op_multiply)
- [op\_Subtraction](ue_ue.Vector_NetQuantizeNormal.md#op_subtraction)
- [op\_UnaryNegation](ue_ue.Vector_NetQuantizeNormal.md#op_unarynegation)
- [set\_Item](ue_ue.Vector_NetQuantizeNormal.md#set_item)
- [BoxPushOut](ue_ue.Vector_NetQuantizeNormal.md#boxpushout)
- [Coincident](ue_ue.Vector_NetQuantizeNormal.md#coincident)
- [Coplanar](ue_ue.Vector_NetQuantizeNormal.md#coplanar)
- [CreateOrthonormalBasis](ue_ue.Vector_NetQuantizeNormal.md#createorthonormalbasis)
- [CrossProduct](ue_ue.Vector_NetQuantizeNormal.md#crossproduct)
- [DegreesToRadians](ue_ue.Vector_NetQuantizeNormal.md#degreestoradians)
- [Dist](ue_ue.Vector_NetQuantizeNormal.md#dist)
- [Dist2D](ue_ue.Vector_NetQuantizeNormal.md#dist2d)
- [DistSquared](ue_ue.Vector_NetQuantizeNormal.md#distsquared)
- [DistSquared2D](ue_ue.Vector_NetQuantizeNormal.md#distsquared2d)
- [DistSquaredXY](ue_ue.Vector_NetQuantizeNormal.md#distsquaredxy)
- [DistXY](ue_ue.Vector_NetQuantizeNormal.md#distxy)
- [Distance](ue_ue.Vector_NetQuantizeNormal.md#distance)
- [DotProduct](ue_ue.Vector_NetQuantizeNormal.md#dotproduct)
- [Orthogonal](ue_ue.Vector_NetQuantizeNormal.md#orthogonal)
- [Parallel](ue_ue.Vector_NetQuantizeNormal.md#parallel)
- [PointPlaneDist](ue_ue.Vector_NetQuantizeNormal.md#pointplanedist)
- [PointPlaneProject](ue_ue.Vector_NetQuantizeNormal.md#pointplaneproject)
- [PointsAreNear](ue_ue.Vector_NetQuantizeNormal.md#pointsarenear)
- [PointsAreSame](ue_ue.Vector_NetQuantizeNormal.md#pointsaresame)
- [RadiansToDegrees](ue_ue.Vector_NetQuantizeNormal.md#radianstodegrees)
- [StaticClass](ue_ue.Vector_NetQuantizeNormal.md#staticclass)
- [StaticStruct](ue_ue.Vector_NetQuantizeNormal.md#staticstruct)
- [Triple](ue_ue.Vector_NetQuantizeNormal.md#triple)
- [VectorPlaneProject](ue_ue.Vector_NetQuantizeNormal.md#vectorplaneproject)

## Constructors

### constructor

• **new Vector_NetQuantizeNormal**()

#### Overrides

[Vector](ue_ue_s.Vector.md).[constructor](ue_ue_s.Vector.md#constructor)

## Properties

### X

• **X**: `number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[X](ue_ue_s.Vector.md#x)

___

### Y

• **Y**: `number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Y](ue_ue_s.Vector.md#y)

___

### Z

• **Z**: `number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Z](ue_ue_s.Vector.md#z)

___

### \_\_tid\_Vector\_NetQuantizeNormal\_\_

• `Private` **\_\_tid\_Vector\_NetQuantizeNormal\_\_**: `boolean`

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[AddBounded](ue_ue_s.Vector.md#addbounded)

___

### AllComponentsEqual

▸ **AllComponentsEqual**(`Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

`boolean`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[AllComponentsEqual](ue_ue_s.Vector.md#allcomponentsequal)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[BoundToBox](ue_ue_s.Vector.md#boundtobox)

___

### BoundToCube

▸ **BoundToCube**(`Radius`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Radius` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[BoundToCube](ue_ue_s.Vector.md#boundtocube)

___

### Component

▸ **Component**(`Index`): [`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

[`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Component](ue_ue_s.Vector.md#component)

▸ **Component**(`Index`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Component](ue_ue_s.Vector.md#component)

___

### ComponentMax

▸ **ComponentMax**(`Other`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ComponentMax](ue_ue_s.Vector.md#componentmax)

___

### ComponentMin

▸ **ComponentMin**(`Other`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ComponentMin](ue_ue_s.Vector.md#componentmin)

___

### ContainsNaN

▸ **ContainsNaN**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ContainsNaN](ue_ue_s.Vector.md#containsnan)

___

### CosineAngle2D

▸ **CosineAngle2D**(`B`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `B` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[CosineAngle2D](ue_ue_s.Vector.md#cosineangle2d)

___

### DiagnosticCheckNaN

▸ **DiagnosticCheckNaN**(): `void`

#### Returns

`void`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[DiagnosticCheckNaN](ue_ue_s.Vector.md#diagnosticchecknan)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Equals](ue_ue_s.Vector.md#equals)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[FindBestAxisVectors](ue_ue_s.Vector.md#findbestaxisvectors)

___

### GetAbs

▸ **GetAbs**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetAbs](ue_ue_s.Vector.md#getabs)

___

### GetAbsMax

▸ **GetAbsMax**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetAbsMax](ue_ue_s.Vector.md#getabsmax)

___

### GetAbsMin

▸ **GetAbsMin**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetAbsMin](ue_ue_s.Vector.md#getabsmin)

___

### GetClampedToMaxSize

▸ **GetClampedToMaxSize**(`MaxSize`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaxSize` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetClampedToMaxSize](ue_ue_s.Vector.md#getclampedtomaxsize)

___

### GetClampedToMaxSize2D

▸ **GetClampedToMaxSize2D**(`MaxSize`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MaxSize` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetClampedToMaxSize2D](ue_ue_s.Vector.md#getclampedtomaxsize2d)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetClampedToSize](ue_ue_s.Vector.md#getclampedtosize)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetClampedToSize2D](ue_ue_s.Vector.md#getclampedtosize2d)

___

### GetComponentForAxis

▸ **GetComponentForAxis**(`Axis`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Axis` | `number` |

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetComponentForAxis](ue_ue_s.Vector.md#getcomponentforaxis)

___

### GetMax

▸ **GetMax**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetMax](ue_ue_s.Vector.md#getmax)

___

### GetMin

▸ **GetMin**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetMin](ue_ue_s.Vector.md#getmin)

___

### GetSafeNormal

▸ **GetSafeNormal**(`Tolerance`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetSafeNormal](ue_ue_s.Vector.md#getsafenormal)

___

### GetSafeNormal2D

▸ **GetSafeNormal2D**(`Tolerance`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetSafeNormal2D](ue_ue_s.Vector.md#getsafenormal2d)

___

### GetSignVector

▸ **GetSignVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetSignVector](ue_ue_s.Vector.md#getsignvector)

___

### GetUnsafeNormal

▸ **GetUnsafeNormal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetUnsafeNormal](ue_ue_s.Vector.md#getunsafenormal)

___

### GetUnsafeNormal2D

▸ **GetUnsafeNormal2D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetUnsafeNormal2D](ue_ue_s.Vector.md#getunsafenormal2d)

___

### GridSnap

▸ **GridSnap**(`GridSz`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `GridSz` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GridSnap](ue_ue_s.Vector.md#gridsnap)

___

### HeadingAngle

▸ **HeadingAngle**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[HeadingAngle](ue_ue_s.Vector.md#headingangle)

___

### InitFromString

▸ **InitFromString**(`InSourceString`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSourceString` | `string` |

#### Returns

`boolean`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[InitFromString](ue_ue_s.Vector.md#initfromstring)

___

### IsNearlyZero

▸ **IsNearlyZero**(`Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

`boolean`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[IsNearlyZero](ue_ue_s.Vector.md#isnearlyzero)

___

### IsNormalized

▸ **IsNormalized**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[IsNormalized](ue_ue_s.Vector.md#isnormalized)

___

### IsUniform

▸ **IsUniform**(`Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

`boolean`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[IsUniform](ue_ue_s.Vector.md#isuniform)

___

### IsUnit

▸ **IsUnit**(`LengthSquaredTolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LengthSquaredTolerance` | `number` |

#### Returns

`boolean`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[IsUnit](ue_ue_s.Vector.md#isunit)

___

### IsZero

▸ **IsZero**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[IsZero](ue_ue_s.Vector.md#iszero)

___

### MirrorByPlane

▸ **MirrorByPlane**(`Plane`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Plane` | [`FPlane`](ue_ue_s.FPlane.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[MirrorByPlane](ue_ue_s.Vector.md#mirrorbyplane)

___

### MirrorByVector

▸ **MirrorByVector**(`MirrorNormal`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MirrorNormal` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[MirrorByVector](ue_ue_s.Vector.md#mirrorbyvector)

___

### Normalize

▸ **Normalize**(`Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

`boolean`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Normalize](ue_ue_s.Vector.md#normalize)

___

### ProjectOnTo

▸ **ProjectOnTo**(`A`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ProjectOnTo](ue_ue_s.Vector.md#projectonto)

___

### ProjectOnToNormal

▸ **ProjectOnToNormal**(`Normal`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Normal` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ProjectOnToNormal](ue_ue_s.Vector.md#projectontonormal)

___

### Projection

▸ **Projection**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Projection](ue_ue_s.Vector.md#projection)

___

### Reciprocal

▸ **Reciprocal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Reciprocal](ue_ue_s.Vector.md#reciprocal)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[RotateAngleAxis](ue_ue_s.Vector.md#rotateangleaxis)

___

### Rotation

▸ **Rotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Rotation](ue_ue_s.Vector.md#rotation)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Set](ue_ue_s.Vector.md#set)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[SetComponentForAxis](ue_ue_s.Vector.md#setcomponentforaxis)

___

### Size

▸ **Size**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Size](ue_ue_s.Vector.md#size)

___

### Size2D

▸ **Size2D**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Size2D](ue_ue_s.Vector.md#size2d)

___

### SizeSquared

▸ **SizeSquared**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[SizeSquared](ue_ue_s.Vector.md#sizesquared)

___

### SizeSquared2D

▸ **SizeSquared2D**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[SizeSquared2D](ue_ue_s.Vector.md#sizesquared2d)

___

### ToCompactString

▸ **ToCompactString**(): `string`

#### Returns

`string`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ToCompactString](ue_ue_s.Vector.md#tocompactstring)

___

### ToCompactText

▸ **ToCompactText**(): `string`

#### Returns

`string`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ToCompactText](ue_ue_s.Vector.md#tocompacttext)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ToDirectionAndLength](ue_ue_s.Vector.md#todirectionandlength)

___

### ToOrientationQuat

▸ **ToOrientationQuat**(): [`Quat`](ue_ue_s.Quat.md)

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ToOrientationQuat](ue_ue_s.Vector.md#toorientationquat)

___

### ToOrientationRotator

▸ **ToOrientationRotator**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ToOrientationRotator](ue_ue_s.Vector.md#toorientationrotator)

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ToString](ue_ue_s.Vector.md#tostring)

___

### ToText

▸ **ToText**(): `string`

#### Returns

`string`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ToText](ue_ue_s.Vector.md#totext)

___

### UnitCartesianToSpherical

▸ **UnitCartesianToSpherical**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[UnitCartesianToSpherical](ue_ue_s.Vector.md#unitcartesiantospherical)

___

### UnwindEuler

▸ **UnwindEuler**(): `void`

#### Returns

`void`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[UnwindEuler](ue_ue_s.Vector.md#unwindeuler)

___

### get\_Item

▸ **get_Item**(`Index`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[get_Item](ue_ue_s.Vector.md#get_item)

___

### op\_Addition

▸ **op_Addition**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_Addition](ue_ue_s.Vector.md#op_addition)

▸ **op_Addition**(`Bias`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Bias` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_Addition](ue_ue_s.Vector.md#op_addition)

___

### op\_BitwiseOr

▸ **op_BitwiseOr**(`V`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_BitwiseOr](ue_ue_s.Vector.md#op_bitwiseor)

___

### op\_Division

▸ **op_Division**(`Scale`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_Division](ue_ue_s.Vector.md#op_division)

▸ **op_Division**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_Division](ue_ue_s.Vector.md#op_division)

___

### op\_Equality

▸ **op_Equality**(`V`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`boolean`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_Equality](ue_ue_s.Vector.md#op_equality)

___

### op\_ExclusiveOr

▸ **op_ExclusiveOr**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_ExclusiveOr](ue_ue_s.Vector.md#op_exclusiveor)

___

### op\_Inequality

▸ **op_Inequality**(`V`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`boolean`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_Inequality](ue_ue_s.Vector.md#op_inequality)

___

### op\_Multiply

▸ **op_Multiply**(`Scale`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_Multiply](ue_ue_s.Vector.md#op_multiply)

▸ **op_Multiply**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_Multiply](ue_ue_s.Vector.md#op_multiply)

___

### op\_Subtraction

▸ **op_Subtraction**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_Subtraction](ue_ue_s.Vector.md#op_subtraction)

▸ **op_Subtraction**(`Bias`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Bias` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_Subtraction](ue_ue_s.Vector.md#op_subtraction)

___

### op\_UnaryNegation

▸ **op_UnaryNegation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_UnaryNegation](ue_ue_s.Vector.md#op_unarynegation)

___

### set\_Item

▸ **set_Item**(`Index`): [`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

[`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

#### Inherited from

[Vector](ue_ue_s.Vector.md).[set_Item](ue_ue_s.Vector.md#set_item)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[BoxPushOut](ue_ue_s.Vector.md#boxpushout)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Coincident](ue_ue_s.Vector.md#coincident)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Coplanar](ue_ue_s.Vector.md#coplanar)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[CreateOrthonormalBasis](ue_ue_s.Vector.md#createorthonormalbasis)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[CrossProduct](ue_ue_s.Vector.md#crossproduct)

___

### DegreesToRadians

▸ `Static` **DegreesToRadians**(`DegVector`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `DegVector` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[DegreesToRadians](ue_ue_s.Vector.md#degreestoradians)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Dist](ue_ue_s.Vector.md#dist)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Dist2D](ue_ue_s.Vector.md#dist2d)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[DistSquared](ue_ue_s.Vector.md#distsquared)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[DistSquared2D](ue_ue_s.Vector.md#distsquared2d)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[DistSquaredXY](ue_ue_s.Vector.md#distsquaredxy)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[DistXY](ue_ue_s.Vector.md#distxy)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Distance](ue_ue_s.Vector.md#distance)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[DotProduct](ue_ue_s.Vector.md#dotproduct)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Orthogonal](ue_ue_s.Vector.md#orthogonal)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Parallel](ue_ue_s.Vector.md#parallel)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[PointPlaneDist](ue_ue_s.Vector.md#pointplanedist)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[PointPlaneProject](ue_ue_s.Vector.md#pointplaneproject)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[PointPlaneProject](ue_ue_s.Vector.md#pointplaneproject)

▸ `Static` **PointPlaneProject**(`Point`, `PlaneBase`, `PlaneNormal`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Point` | [`Vector`](ue_ue_s.Vector.md) |
| `PlaneBase` | [`Vector`](ue_ue_s.Vector.md) |
| `PlaneNormal` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[PointPlaneProject](ue_ue_s.Vector.md#pointplaneproject)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[PointsAreNear](ue_ue_s.Vector.md#pointsarenear)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[PointsAreSame](ue_ue_s.Vector.md#pointsaresame)

___

### RadiansToDegrees

▸ `Static` **RadiansToDegrees**(`RadVector`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `RadVector` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[RadiansToDegrees](ue_ue_s.Vector.md#radianstodegrees)

___

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[Vector](ue_ue_s.Vector.md).[StaticClass](ue_ue_s.Vector.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[Vector](ue_ue_s.Vector.md).[StaticStruct](ue_ue_s.Vector.md#staticstruct)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Triple](ue_ue_s.Vector.md#triple)

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

#### Inherited from

[Vector](ue_ue_s.Vector.md).[VectorPlaneProject](ue_ue_s.Vector.md#vectorplaneproject)
