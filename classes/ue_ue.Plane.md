[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Plane

# Class: Plane

[ue/ue](../modules/ue_ue.md).Plane

## Hierarchy

- [`Vector`](ue_ue_s.Vector.md)

  ↳ **`Plane`**

## Table of contents

### Constructors

- [constructor](ue_ue.Plane.md#constructor)

### Properties

- [W](ue_ue.Plane.md#w)
- [X](ue_ue.Plane.md#x)
- [Y](ue_ue.Plane.md#y)
- [Z](ue_ue.Plane.md#z)
- [\_\_tid\_Plane\_\_](ue_ue.Plane.md#__tid_plane__)

### Methods

- [AddBounded](ue_ue.Plane.md#addbounded)
- [AllComponentsEqual](ue_ue.Plane.md#allcomponentsequal)
- [BoundToBox](ue_ue.Plane.md#boundtobox)
- [BoundToCube](ue_ue.Plane.md#boundtocube)
- [Component](ue_ue.Plane.md#component)
- [ComponentMax](ue_ue.Plane.md#componentmax)
- [ComponentMin](ue_ue.Plane.md#componentmin)
- [ContainsNaN](ue_ue.Plane.md#containsnan)
- [CosineAngle2D](ue_ue.Plane.md#cosineangle2d)
- [DiagnosticCheckNaN](ue_ue.Plane.md#diagnosticchecknan)
- [Equals](ue_ue.Plane.md#equals)
- [FindBestAxisVectors](ue_ue.Plane.md#findbestaxisvectors)
- [GetAbs](ue_ue.Plane.md#getabs)
- [GetAbsMax](ue_ue.Plane.md#getabsmax)
- [GetAbsMin](ue_ue.Plane.md#getabsmin)
- [GetClampedToMaxSize](ue_ue.Plane.md#getclampedtomaxsize)
- [GetClampedToMaxSize2D](ue_ue.Plane.md#getclampedtomaxsize2d)
- [GetClampedToSize](ue_ue.Plane.md#getclampedtosize)
- [GetClampedToSize2D](ue_ue.Plane.md#getclampedtosize2d)
- [GetComponentForAxis](ue_ue.Plane.md#getcomponentforaxis)
- [GetMax](ue_ue.Plane.md#getmax)
- [GetMin](ue_ue.Plane.md#getmin)
- [GetSafeNormal](ue_ue.Plane.md#getsafenormal)
- [GetSafeNormal2D](ue_ue.Plane.md#getsafenormal2d)
- [GetSignVector](ue_ue.Plane.md#getsignvector)
- [GetUnsafeNormal](ue_ue.Plane.md#getunsafenormal)
- [GetUnsafeNormal2D](ue_ue.Plane.md#getunsafenormal2d)
- [GridSnap](ue_ue.Plane.md#gridsnap)
- [HeadingAngle](ue_ue.Plane.md#headingangle)
- [InitFromString](ue_ue.Plane.md#initfromstring)
- [IsNearlyZero](ue_ue.Plane.md#isnearlyzero)
- [IsNormalized](ue_ue.Plane.md#isnormalized)
- [IsUniform](ue_ue.Plane.md#isuniform)
- [IsUnit](ue_ue.Plane.md#isunit)
- [IsZero](ue_ue.Plane.md#iszero)
- [MirrorByPlane](ue_ue.Plane.md#mirrorbyplane)
- [MirrorByVector](ue_ue.Plane.md#mirrorbyvector)
- [Normalize](ue_ue.Plane.md#normalize)
- [ProjectOnTo](ue_ue.Plane.md#projectonto)
- [ProjectOnToNormal](ue_ue.Plane.md#projectontonormal)
- [Projection](ue_ue.Plane.md#projection)
- [Reciprocal](ue_ue.Plane.md#reciprocal)
- [RotateAngleAxis](ue_ue.Plane.md#rotateangleaxis)
- [Rotation](ue_ue.Plane.md#rotation)
- [Set](ue_ue.Plane.md#set)
- [SetComponentForAxis](ue_ue.Plane.md#setcomponentforaxis)
- [Size](ue_ue.Plane.md#size)
- [Size2D](ue_ue.Plane.md#size2d)
- [SizeSquared](ue_ue.Plane.md#sizesquared)
- [SizeSquared2D](ue_ue.Plane.md#sizesquared2d)
- [ToCompactString](ue_ue.Plane.md#tocompactstring)
- [ToCompactText](ue_ue.Plane.md#tocompacttext)
- [ToDirectionAndLength](ue_ue.Plane.md#todirectionandlength)
- [ToOrientationQuat](ue_ue.Plane.md#toorientationquat)
- [ToOrientationRotator](ue_ue.Plane.md#toorientationrotator)
- [ToString](ue_ue.Plane.md#tostring)
- [ToText](ue_ue.Plane.md#totext)
- [UnitCartesianToSpherical](ue_ue.Plane.md#unitcartesiantospherical)
- [UnwindEuler](ue_ue.Plane.md#unwindeuler)
- [get\_Item](ue_ue.Plane.md#get_item)
- [op\_Addition](ue_ue.Plane.md#op_addition)
- [op\_BitwiseOr](ue_ue.Plane.md#op_bitwiseor)
- [op\_Division](ue_ue.Plane.md#op_division)
- [op\_Equality](ue_ue.Plane.md#op_equality)
- [op\_ExclusiveOr](ue_ue.Plane.md#op_exclusiveor)
- [op\_Inequality](ue_ue.Plane.md#op_inequality)
- [op\_Multiply](ue_ue.Plane.md#op_multiply)
- [op\_Subtraction](ue_ue.Plane.md#op_subtraction)
- [op\_UnaryNegation](ue_ue.Plane.md#op_unarynegation)
- [set\_Item](ue_ue.Plane.md#set_item)
- [BoxPushOut](ue_ue.Plane.md#boxpushout)
- [Coincident](ue_ue.Plane.md#coincident)
- [Coplanar](ue_ue.Plane.md#coplanar)
- [CreateOrthonormalBasis](ue_ue.Plane.md#createorthonormalbasis)
- [CrossProduct](ue_ue.Plane.md#crossproduct)
- [DegreesToRadians](ue_ue.Plane.md#degreestoradians)
- [Dist](ue_ue.Plane.md#dist)
- [Dist2D](ue_ue.Plane.md#dist2d)
- [DistSquared](ue_ue.Plane.md#distsquared)
- [DistSquared2D](ue_ue.Plane.md#distsquared2d)
- [DistSquaredXY](ue_ue.Plane.md#distsquaredxy)
- [DistXY](ue_ue.Plane.md#distxy)
- [Distance](ue_ue.Plane.md#distance)
- [DotProduct](ue_ue.Plane.md#dotproduct)
- [Orthogonal](ue_ue.Plane.md#orthogonal)
- [Parallel](ue_ue.Plane.md#parallel)
- [PointPlaneDist](ue_ue.Plane.md#pointplanedist)
- [PointPlaneProject](ue_ue.Plane.md#pointplaneproject)
- [PointsAreNear](ue_ue.Plane.md#pointsarenear)
- [PointsAreSame](ue_ue.Plane.md#pointsaresame)
- [RadiansToDegrees](ue_ue.Plane.md#radianstodegrees)
- [StaticClass](ue_ue.Plane.md#staticclass)
- [StaticStruct](ue_ue.Plane.md#staticstruct)
- [Triple](ue_ue.Plane.md#triple)
- [VectorPlaneProject](ue_ue.Plane.md#vectorplaneproject)

## Constructors

### constructor

• **new Plane**()

#### Overrides

[Vector](ue_ue_s.Vector.md).[constructor](ue_ue_s.Vector.md#constructor)

#### Defined in

[ue/ue.d.ts:3384](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3384)

• **new Plane**(`W`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `W` | `number` |

#### Overrides

[Vector](ue_ue_s.Vector.md).[constructor](ue_ue_s.Vector.md#constructor)

#### Defined in

[ue/ue.d.ts:3385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3385)

## Properties

### W

• **W**: `number`

#### Defined in

[ue/ue.d.ts:3386](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3386)

___

### X

• **X**: `number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[X](ue_ue_s.Vector.md#x)

#### Defined in

[ue/ue_s.d.ts:394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L394)

___

### Y

• **Y**: `number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Y](ue_ue_s.Vector.md#y)

#### Defined in

[ue/ue_s.d.ts:395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L395)

___

### Z

• **Z**: `number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Z](ue_ue_s.Vector.md#z)

#### Defined in

[ue/ue_s.d.ts:396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L396)

___

### \_\_tid\_Plane\_\_

• `Private` **\_\_tid\_Plane\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3392)

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

#### Defined in

[ue/ue_s.d.ts:452](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L452)

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

#### Defined in

[ue/ue_s.d.ts:413](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L413)

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

#### Defined in

[ue/ue_s.d.ts:447](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L447)

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

#### Defined in

[ue/ue_s.d.ts:446](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L446)

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

#### Defined in

[ue/ue_s.d.ts:417](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L417)

▸ **Component**(`Index`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Component](ue_ue_s.Vector.md#component)

#### Defined in

[ue/ue_s.d.ts:418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L418)

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

#### Defined in

[ue/ue_s.d.ts:427](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L427)

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

#### Defined in

[ue/ue_s.d.ts:426](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L426)

___

### ContainsNaN

▸ **ContainsNaN**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ContainsNaN](ue_ue_s.Vector.md#containsnan)

#### Defined in

[ue/ue_s.d.ts:466](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L466)

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

#### Defined in

[ue/ue_s.d.ts:458](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L458)

___

### DiagnosticCheckNaN

▸ **DiagnosticCheckNaN**(): `void`

#### Returns

`void`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[DiagnosticCheckNaN](ue_ue_s.Vector.md#diagnosticchecknan)

#### Defined in

[ue/ue_s.d.ts:397](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L397)

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

#### Defined in

[ue/ue_s.d.ts:412](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L412)

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

#### Defined in

[ue/ue_s.d.ts:464](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L464)

___

### GetAbs

▸ **GetAbs**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetAbs](ue_ue_s.Vector.md#getabs)

#### Defined in

[ue/ue_s.d.ts:428](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L428)

___

### GetAbsMax

▸ **GetAbsMax**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetAbsMax](ue_ue_s.Vector.md#getabsmax)

#### Defined in

[ue/ue_s.d.ts:423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L423)

___

### GetAbsMin

▸ **GetAbsMin**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetAbsMin](ue_ue_s.Vector.md#getabsmin)

#### Defined in

[ue/ue_s.d.ts:425](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L425)

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

#### Defined in

[ue/ue_s.d.ts:450](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L450)

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

#### Defined in

[ue/ue_s.d.ts:451](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L451)

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

#### Defined in

[ue/ue_s.d.ts:448](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L448)

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

#### Defined in

[ue/ue_s.d.ts:449](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L449)

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

#### Defined in

[ue/ue_s.d.ts:419](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L419)

___

### GetMax

▸ **GetMax**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetMax](ue_ue_s.Vector.md#getmax)

#### Defined in

[ue/ue_s.d.ts:422](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L422)

___

### GetMin

▸ **GetMin**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetMin](ue_ue_s.Vector.md#getmin)

#### Defined in

[ue/ue_s.d.ts:424](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L424)

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

#### Defined in

[ue/ue_s.d.ts:439](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L439)

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

#### Defined in

[ue/ue_s.d.ts:440](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L440)

___

### GetSignVector

▸ **GetSignVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetSignVector](ue_ue_s.Vector.md#getsignvector)

#### Defined in

[ue/ue_s.d.ts:442](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L442)

___

### GetUnsafeNormal

▸ **GetUnsafeNormal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetUnsafeNormal](ue_ue_s.Vector.md#getunsafenormal)

#### Defined in

[ue/ue_s.d.ts:438](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L438)

___

### GetUnsafeNormal2D

▸ **GetUnsafeNormal2D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[GetUnsafeNormal2D](ue_ue_s.Vector.md#getunsafenormal2d)

#### Defined in

[ue/ue_s.d.ts:444](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L444)

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

#### Defined in

[ue/ue_s.d.ts:445](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L445)

___

### HeadingAngle

▸ **HeadingAngle**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[HeadingAngle](ue_ue_s.Vector.md#headingangle)

#### Defined in

[ue/ue_s.d.ts:473](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L473)

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

#### Defined in

[ue/ue_s.d.ts:471](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L471)

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

#### Defined in

[ue/ue_s.d.ts:433](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L433)

___

### IsNormalized

▸ **IsNormalized**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[IsNormalized](ue_ue_s.Vector.md#isnormalized)

#### Defined in

[ue/ue_s.d.ts:436](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L436)

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

#### Defined in

[ue/ue_s.d.ts:454](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L454)

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

#### Defined in

[ue/ue_s.d.ts:435](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L435)

___

### IsZero

▸ **IsZero**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[IsZero](ue_ue_s.Vector.md#iszero)

#### Defined in

[ue/ue_s.d.ts:434](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L434)

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

#### Defined in

[ue/ue_s.d.ts:456](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L456)

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

#### Defined in

[ue/ue_s.d.ts:455](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L455)

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

#### Defined in

[ue/ue_s.d.ts:437](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L437)

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

#### Defined in

[ue/ue_s.d.ts:459](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L459)

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

#### Defined in

[ue/ue_s.d.ts:460](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L460)

___

### Projection

▸ **Projection**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Projection](ue_ue_s.Vector.md#projection)

#### Defined in

[ue/ue_s.d.ts:443](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L443)

___

### Reciprocal

▸ **Reciprocal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Reciprocal](ue_ue_s.Vector.md#reciprocal)

#### Defined in

[ue/ue_s.d.ts:453](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L453)

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

#### Defined in

[ue/ue_s.d.ts:457](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L457)

___

### Rotation

▸ **Rotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Rotation](ue_ue_s.Vector.md#rotation)

#### Defined in

[ue/ue_s.d.ts:463](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L463)

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

#### Defined in

[ue/ue_s.d.ts:421](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L421)

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

#### Defined in

[ue/ue_s.d.ts:420](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L420)

___

### Size

▸ **Size**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Size](ue_ue_s.Vector.md#size)

#### Defined in

[ue/ue_s.d.ts:429](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L429)

___

### Size2D

▸ **Size2D**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[Size2D](ue_ue_s.Vector.md#size2d)

#### Defined in

[ue/ue_s.d.ts:431](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L431)

___

### SizeSquared

▸ **SizeSquared**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[SizeSquared](ue_ue_s.Vector.md#sizesquared)

#### Defined in

[ue/ue_s.d.ts:430](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L430)

___

### SizeSquared2D

▸ **SizeSquared2D**(): `number`

#### Returns

`number`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[SizeSquared2D](ue_ue_s.Vector.md#sizesquared2d)

#### Defined in

[ue/ue_s.d.ts:432](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L432)

___

### ToCompactString

▸ **ToCompactString**(): `string`

#### Returns

`string`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ToCompactString](ue_ue_s.Vector.md#tocompactstring)

#### Defined in

[ue/ue_s.d.ts:469](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L469)

___

### ToCompactText

▸ **ToCompactText**(): `string`

#### Returns

`string`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ToCompactText](ue_ue_s.Vector.md#tocompacttext)

#### Defined in

[ue/ue_s.d.ts:470](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L470)

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

#### Defined in

[ue/ue_s.d.ts:441](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L441)

___

### ToOrientationQuat

▸ **ToOrientationQuat**(): [`Quat`](ue_ue_s.Quat.md)

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ToOrientationQuat](ue_ue_s.Vector.md#toorientationquat)

#### Defined in

[ue/ue_s.d.ts:462](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L462)

___

### ToOrientationRotator

▸ **ToOrientationRotator**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ToOrientationRotator](ue_ue_s.Vector.md#toorientationrotator)

#### Defined in

[ue/ue_s.d.ts:461](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L461)

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ToString](ue_ue_s.Vector.md#tostring)

#### Defined in

[ue/ue_s.d.ts:467](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L467)

___

### ToText

▸ **ToText**(): `string`

#### Returns

`string`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[ToText](ue_ue_s.Vector.md#totext)

#### Defined in

[ue/ue_s.d.ts:468](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L468)

___

### UnitCartesianToSpherical

▸ **UnitCartesianToSpherical**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[UnitCartesianToSpherical](ue_ue_s.Vector.md#unitcartesiantospherical)

#### Defined in

[ue/ue_s.d.ts:472](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L472)

___

### UnwindEuler

▸ **UnwindEuler**(): `void`

#### Returns

`void`

#### Inherited from

[Vector](ue_ue_s.Vector.md).[UnwindEuler](ue_ue_s.Vector.md#unwindeuler)

#### Defined in

[ue/ue_s.d.ts:465](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L465)

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

#### Defined in

[ue/ue_s.d.ts:416](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L416)

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

#### Defined in

[ue/ue_s.d.ts:402](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L402)

▸ **op_Addition**(`Bias`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Bias` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_Addition](ue_ue_s.Vector.md#op_addition)

#### Defined in

[ue/ue_s.d.ts:403](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L403)

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

#### Defined in

[ue/ue_s.d.ts:400](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L400)

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

#### Defined in

[ue/ue_s.d.ts:408](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L408)

▸ **op_Division**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_Division](ue_ue_s.Vector.md#op_division)

#### Defined in

[ue/ue_s.d.ts:409](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L409)

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

#### Defined in

[ue/ue_s.d.ts:410](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L410)

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

#### Defined in

[ue/ue_s.d.ts:398](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L398)

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

#### Defined in

[ue/ue_s.d.ts:411](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L411)

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

#### Defined in

[ue/ue_s.d.ts:406](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L406)

▸ **op_Multiply**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_Multiply](ue_ue_s.Vector.md#op_multiply)

#### Defined in

[ue/ue_s.d.ts:407](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L407)

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

#### Defined in

[ue/ue_s.d.ts:404](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L404)

▸ **op_Subtraction**(`Bias`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Bias` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_Subtraction](ue_ue_s.Vector.md#op_subtraction)

#### Defined in

[ue/ue_s.d.ts:405](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L405)

___

### op\_UnaryNegation

▸ **op_UnaryNegation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[Vector](ue_ue_s.Vector.md).[op_UnaryNegation](ue_ue_s.Vector.md#op_unarynegation)

#### Defined in

[ue/ue_s.d.ts:414](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L414)

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

#### Defined in

[ue/ue_s.d.ts:415](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L415)

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

#### Defined in

[ue/ue_s.d.ts:489](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L489)

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

#### Defined in

[ue/ue_s.d.ts:491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L491)

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

#### Defined in

[ue/ue_s.d.ts:493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L493)

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

#### Defined in

[ue/ue_s.d.ts:474](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L474)

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

#### Defined in

[ue/ue_s.d.ts:399](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L399)

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

#### Defined in

[ue/ue_s.d.ts:496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L496)

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

#### Defined in

[ue/ue_s.d.ts:482](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L482)

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

#### Defined in

[ue/ue_s.d.ts:485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L485)

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

#### Defined in

[ue/ue_s.d.ts:486](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L486)

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

#### Defined in

[ue/ue_s.d.ts:488](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L488)

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

#### Defined in

[ue/ue_s.d.ts:487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L487)

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

#### Defined in

[ue/ue_s.d.ts:484](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L484)

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

#### Defined in

[ue/ue_s.d.ts:483](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L483)

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

#### Defined in

[ue/ue_s.d.ts:401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L401)

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

#### Defined in

[ue/ue_s.d.ts:492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L492)

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

#### Defined in

[ue/ue_s.d.ts:490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L490)

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

#### Defined in

[ue/ue_s.d.ts:477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L477)

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

#### Defined in

[ue/ue_s.d.ts:478](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L478)

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

#### Defined in

[ue/ue_s.d.ts:479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L479)

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

#### Defined in

[ue/ue_s.d.ts:480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L480)

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

#### Defined in

[ue/ue_s.d.ts:476](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L476)

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

#### Defined in

[ue/ue_s.d.ts:475](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L475)

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

#### Defined in

[ue/ue_s.d.ts:495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L495)

___

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[Vector](ue_ue_s.Vector.md).[StaticClass](ue_ue_s.Vector.md#staticclass)

#### Defined in

[ue/ue.d.ts:3390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3390)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[Vector](ue_ue_s.Vector.md).[StaticStruct](ue_ue_s.Vector.md#staticstruct)

#### Defined in

[ue/ue.d.ts:3391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3391)

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

#### Defined in

[ue/ue_s.d.ts:494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L494)

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

#### Defined in

[ue/ue_s.d.ts:481](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L481)
