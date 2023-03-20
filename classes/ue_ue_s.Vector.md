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

#### Defined in

[ue/ue_s.d.ts:385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L385)

• **new Vector**(`InF`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InF` | `number` |

#### Defined in

[ue/ue_s.d.ts:386](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L386)

• **new Vector**(`InX`, `InY`, `InZ`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InX` | `number` |
| `InY` | `number` |
| `InZ` | `number` |

#### Defined in

[ue/ue_s.d.ts:387](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L387)

• **new Vector**(`V`, `InZ`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `InZ` | `number` |

#### Defined in

[ue/ue_s.d.ts:388](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L388)

• **new Vector**(`V`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Defined in

[ue/ue_s.d.ts:389](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L389)

• **new Vector**(`InColor`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Defined in

[ue/ue_s.d.ts:390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L390)

• **new Vector**(`InVector`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVector` | [`IntVector`](ue_ue_s.IntVector.md) |

#### Defined in

[ue/ue_s.d.ts:391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L391)

• **new Vector**(`A`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`IntPoint`](ue_ue_s.IntPoint.md) |

#### Defined in

[ue/ue_s.d.ts:392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L392)

• **new Vector**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

#### Defined in

[ue/ue_s.d.ts:393](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L393)

## Properties

### X

• **X**: `number`

#### Defined in

[ue/ue_s.d.ts:394](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L394)

___

### Y

• **Y**: `number`

#### Defined in

[ue/ue_s.d.ts:395](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L395)

___

### Z

• **Z**: `number`

#### Defined in

[ue/ue_s.d.ts:396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L396)

___

### \_\_tid\_Vector\_\_

• `Private` **\_\_tid\_Vector\_\_**: `boolean`

#### Defined in

[ue/ue_s.d.ts:504](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L504)

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

#### Defined in

[ue/ue_s.d.ts:417](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L417)

▸ **Component**(`Index`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`number`

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

#### Defined in

[ue/ue_s.d.ts:426](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L426)

___

### ContainsNaN

▸ **ContainsNaN**(): `boolean`

#### Returns

`boolean`

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

#### Defined in

[ue/ue_s.d.ts:458](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L458)

___

### DiagnosticCheckNaN

▸ **DiagnosticCheckNaN**(): `void`

#### Returns

`void`

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

#### Defined in

[ue/ue_s.d.ts:464](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L464)

___

### GetAbs

▸ **GetAbs**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:428](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L428)

___

### GetAbsMax

▸ **GetAbsMax**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L423)

___

### GetAbsMin

▸ **GetAbsMin**(): `number`

#### Returns

`number`

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

#### Defined in

[ue/ue_s.d.ts:419](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L419)

___

### GetMax

▸ **GetMax**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:422](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L422)

___

### GetMin

▸ **GetMin**(): `number`

#### Returns

`number`

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

#### Defined in

[ue/ue_s.d.ts:440](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L440)

___

### GetSignVector

▸ **GetSignVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:442](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L442)

___

### GetUnsafeNormal

▸ **GetUnsafeNormal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:438](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L438)

___

### GetUnsafeNormal2D

▸ **GetUnsafeNormal2D**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

#### Defined in

[ue/ue_s.d.ts:445](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L445)

___

### HeadingAngle

▸ **HeadingAngle**(): `number`

#### Returns

`number`

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

#### Defined in

[ue/ue_s.d.ts:433](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L433)

___

### IsNormalized

▸ **IsNormalized**(): `boolean`

#### Returns

`boolean`

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

#### Defined in

[ue/ue_s.d.ts:435](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L435)

___

### IsZero

▸ **IsZero**(): `boolean`

#### Returns

`boolean`

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

#### Defined in

[ue/ue_s.d.ts:460](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L460)

___

### Projection

▸ **Projection**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:443](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L443)

___

### Reciprocal

▸ **Reciprocal**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

#### Defined in

[ue/ue_s.d.ts:457](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L457)

___

### Rotation

▸ **Rotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

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

#### Defined in

[ue/ue_s.d.ts:420](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L420)

___

### Size

▸ **Size**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:429](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L429)

___

### Size2D

▸ **Size2D**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:431](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L431)

___

### SizeSquared

▸ **SizeSquared**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:430](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L430)

___

### SizeSquared2D

▸ **SizeSquared2D**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:432](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L432)

___

### ToCompactString

▸ **ToCompactString**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue_s.d.ts:469](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L469)

___

### ToCompactText

▸ **ToCompactText**(): `string`

#### Returns

`string`

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

#### Defined in

[ue/ue_s.d.ts:441](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L441)

___

### ToOrientationQuat

▸ **ToOrientationQuat**(): [`Quat`](ue_ue_s.Quat.md)

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Defined in

[ue/ue_s.d.ts:462](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L462)

___

### ToOrientationRotator

▸ **ToOrientationRotator**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue_s.d.ts:461](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L461)

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue_s.d.ts:467](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L467)

___

### ToText

▸ **ToText**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue_s.d.ts:468](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L468)

___

### UnitCartesianToSpherical

▸ **UnitCartesianToSpherical**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:472](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L472)

___

### UnwindEuler

▸ **UnwindEuler**(): `void`

#### Returns

`void`

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

#### Defined in

[ue/ue_s.d.ts:402](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L402)

▸ **op_Addition**(`Bias`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Bias` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

#### Defined in

[ue/ue_s.d.ts:408](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L408)

▸ **op_Division**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

#### Defined in

[ue/ue_s.d.ts:406](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L406)

▸ **op_Multiply**(`V`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

#### Defined in

[ue/ue_s.d.ts:404](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L404)

▸ **op_Subtraction**(`Bias`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Bias` | `number` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:405](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L405)

___

### op\_UnaryNegation

▸ **op_UnaryNegation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

#### Defined in

[ue/ue_s.d.ts:495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L495)

___

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:501](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L501)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:502](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L502)

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

#### Defined in

[ue/ue_s.d.ts:481](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L481)
