[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue\_s](../modules/ue_ue_s.md) / Vector2D

# Class: Vector2D

[ue/ue_s](../modules/ue_ue_s.md).Vector2D

## Table of contents

### Constructors

- [constructor](ue_ue_s.Vector2D.md#constructor)

### Properties

- [X](ue_ue_s.Vector2D.md#x)
- [Y](ue_ue_s.Vector2D.md#y)
- [\_\_tid\_Vector2D\_\_](ue_ue_s.Vector2D.md#__tid_vector2d__)

### Methods

- [ClampAxes](ue_ue_s.Vector2D.md#clampaxes)
- [Component](ue_ue_s.Vector2D.md#component)
- [ContainsNaN](ue_ue_s.Vector2D.md#containsnan)
- [DiagnosticCheckNaN](ue_ue_s.Vector2D.md#diagnosticchecknan)
- [Equals](ue_ue_s.Vector2D.md#equals)
- [GetAbs](ue_ue_s.Vector2D.md#getabs)
- [GetAbsMax](ue_ue_s.Vector2D.md#getabsmax)
- [GetMax](ue_ue_s.Vector2D.md#getmax)
- [GetMin](ue_ue_s.Vector2D.md#getmin)
- [GetRotated](ue_ue_s.Vector2D.md#getrotated)
- [GetSafeNormal](ue_ue_s.Vector2D.md#getsafenormal)
- [GetSignVector](ue_ue_s.Vector2D.md#getsignvector)
- [InitFromString](ue_ue_s.Vector2D.md#initfromstring)
- [IntPoint](ue_ue_s.Vector2D.md#intpoint)
- [IsNearlyZero](ue_ue_s.Vector2D.md#isnearlyzero)
- [IsZero](ue_ue_s.Vector2D.md#iszero)
- [Normalize](ue_ue_s.Vector2D.md#normalize)
- [RoundToVector](ue_ue_s.Vector2D.md#roundtovector)
- [Set](ue_ue_s.Vector2D.md#set)
- [Size](ue_ue_s.Vector2D.md#size)
- [SizeSquared](ue_ue_s.Vector2D.md#sizesquared)
- [SphericalToUnitCartesian](ue_ue_s.Vector2D.md#sphericaltounitcartesian)
- [ToDirectionAndLength](ue_ue_s.Vector2D.md#todirectionandlength)
- [ToString](ue_ue_s.Vector2D.md#tostring)
- [get\_Item](ue_ue_s.Vector2D.md#get_item)
- [op\_Addition](ue_ue_s.Vector2D.md#op_addition)
- [op\_BitwiseOr](ue_ue_s.Vector2D.md#op_bitwiseor)
- [op\_Division](ue_ue_s.Vector2D.md#op_division)
- [op\_Equality](ue_ue_s.Vector2D.md#op_equality)
- [op\_ExclusiveOr](ue_ue_s.Vector2D.md#op_exclusiveor)
- [op\_Inequality](ue_ue_s.Vector2D.md#op_inequality)
- [op\_Multiply](ue_ue_s.Vector2D.md#op_multiply)
- [op\_Subtraction](ue_ue_s.Vector2D.md#op_subtraction)
- [op\_UnaryNegation](ue_ue_s.Vector2D.md#op_unarynegation)
- [set\_Item](ue_ue_s.Vector2D.md#set_item)
- [CrossProduct](ue_ue_s.Vector2D.md#crossproduct)
- [DistSquared](ue_ue_s.Vector2D.md#distsquared)
- [Distance](ue_ue_s.Vector2D.md#distance)
- [DotProduct](ue_ue_s.Vector2D.md#dotproduct)
- [StaticClass](ue_ue_s.Vector2D.md#staticclass)
- [StaticStruct](ue_ue_s.Vector2D.md#staticstruct)

## Constructors

### constructor

• **new Vector2D**()

#### Defined in

[ue/ue_s.d.ts:508](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L508)

• **new Vector2D**(`InX`, `InY`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InX` | `number` |
| `InY` | `number` |

#### Defined in

[ue/ue_s.d.ts:509](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L509)

• **new Vector2D**(`InPos`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPos` | [`IntPoint`](ue_ue_s.IntPoint.md) |

#### Defined in

[ue/ue_s.d.ts:510](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L510)

• **new Vector2D**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

#### Defined in

[ue/ue_s.d.ts:511](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L511)

• **new Vector2D**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

#### Defined in

[ue/ue_s.d.ts:512](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L512)

• **new Vector2D**(`V`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector`](ue_ue_s.Vector.md) |

#### Defined in

[ue/ue_s.d.ts:513](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L513)

• **new Vector2D**(`V`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Defined in

[ue/ue_s.d.ts:514](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L514)

## Properties

### X

• **X**: `number`

#### Defined in

[ue/ue_s.d.ts:515](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L515)

___

### Y

• **Y**: `number`

#### Defined in

[ue/ue_s.d.ts:516](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L516)

___

### \_\_tid\_Vector2D\_\_

• `Private` **\_\_tid\_Vector2D\_\_**: `boolean`

#### Defined in

[ue/ue_s.d.ts:568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L568)

## Methods

### ClampAxes

▸ **ClampAxes**(`MinAxisVal`, `MaxAxisVal`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `MinAxisVal` | `number` |
| `MaxAxisVal` | `number` |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:553](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L553)

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

[ue/ue_s.d.ts:532](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L532)

▸ **Component**(`Index`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:533](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L533)

___

### ContainsNaN

▸ **ContainsNaN**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:559](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L559)

___

### DiagnosticCheckNaN

▸ **DiagnosticCheckNaN**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:558](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L558)

___

### Equals

▸ **Equals**(`V`, `Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `Tolerance` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:538](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L538)

___

### GetAbs

▸ **GetAbs**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L555)

___

### GetAbsMax

▸ **GetAbsMax**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:541](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L541)

___

### GetMax

▸ **GetMax**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:540](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L540)

___

### GetMin

▸ **GetMin**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:542](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L542)

___

### GetRotated

▸ **GetRotated**(`AngleDeg`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `AngleDeg` | `number` |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:545](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L545)

___

### GetSafeNormal

▸ **GetSafeNormal**(`Tolerance`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tolerance` | `number` |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:546](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L546)

___

### GetSignVector

▸ **GetSignVector**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:554](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L554)

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

[ue/ue_s.d.ts:557](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L557)

___

### IntPoint

▸ **IntPoint**(): [`IntPoint`](ue_ue_s.IntPoint.md)

#### Returns

[`IntPoint`](ue_ue_s.IntPoint.md)

#### Defined in

[ue/ue_s.d.ts:551](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L551)

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

[ue/ue_s.d.ts:548](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L548)

___

### IsZero

▸ **IsZero**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:550](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L550)

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

[ue/ue_s.d.ts:547](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L547)

___

### RoundToVector

▸ **RoundToVector**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:552](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L552)

___

### Set

▸ **Set**(`InX`, `InY`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InX` | `number` |
| `InY` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:539](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L539)

___

### Size

▸ **Size**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:543](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L543)

___

### SizeSquared

▸ **SizeSquared**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:544](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L544)

___

### SphericalToUnitCartesian

▸ **SphericalToUnitCartesian**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue_s.d.ts:560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L560)

___

### ToDirectionAndLength

▸ **ToDirectionAndLength**(`OutDir`, `OutLength`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutDir` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\> |
| `OutLength` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue_s.d.ts:549](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L549)

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue_s.d.ts:556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L556)

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

[ue/ue_s.d.ts:531](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L531)

___

### op\_Addition

▸ **op_Addition**(`V`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:517](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L517)

▸ **op_Addition**(`A`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | `number` |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:518](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L518)

___

### op\_BitwiseOr

▸ **op_BitwiseOr**(`V`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:525](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L525)

___

### op\_Division

▸ **op_Division**(`Scale`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:523](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L523)

▸ **op_Division**(`V`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:524](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L524)

___

### op\_Equality

▸ **op_Equality**(`V`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:527](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L527)

___

### op\_ExclusiveOr

▸ **op_ExclusiveOr**(`V`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:526](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L526)

___

### op\_Inequality

▸ **op_Inequality**(`V`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:528](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L528)

___

### op\_Multiply

▸ **op_Multiply**(`Scale`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scale` | `number` |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:521](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L521)

▸ **op_Multiply**(`V`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:522](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L522)

___

### op\_Subtraction

▸ **op_Subtraction**(`V`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `V` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:519](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L519)

▸ **op_Subtraction**(`A`): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | `number` |

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:520](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L520)

___

### op\_UnaryNegation

▸ **op_UnaryNegation**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue_s.d.ts:529](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L529)

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

[ue/ue_s.d.ts:530](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L530)

___

### CrossProduct

▸ `Static` **CrossProduct**(`A`, `B`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `B` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:537](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L537)

___

### DistSquared

▸ `Static` **DistSquared**(`V1`, `V2`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V1` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `V2` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:535](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L535)

___

### Distance

▸ `Static` **Distance**(`V1`, `V2`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V1` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `V2` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:536](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L536)

___

### DotProduct

▸ `Static` **DotProduct**(`A`, `B`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `A` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `B` | [`Vector2D`](ue_ue_s.Vector2D.md) |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:534](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L534)

___

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:565](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L565)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:566](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue_s.d.ts#L566)
