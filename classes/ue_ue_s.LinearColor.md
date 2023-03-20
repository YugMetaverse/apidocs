[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue\_s](../modules/ue_ue_s.md) / LinearColor

# Class: LinearColor

[ue/ue_s](../modules/ue_ue_s.md).LinearColor

## Table of contents

### Constructors

- [constructor](ue_ue_s.LinearColor.md#constructor)

### Properties

- [A](ue_ue_s.LinearColor.md#a)
- [B](ue_ue_s.LinearColor.md#b)
- [G](ue_ue_s.LinearColor.md#g)
- [R](ue_ue_s.LinearColor.md#r)
- [\_\_tid\_LinearColor\_\_](ue_ue_s.LinearColor.md#__tid_linearcolor__)

### Methods

- [Component](ue_ue_s.LinearColor.md#component)
- [ComputeLuminance](ue_ue_s.LinearColor.md#computeluminance)
- [CopyWithNewOpacity](ue_ue_s.LinearColor.md#copywithnewopacity)
- [Desaturate](ue_ue_s.LinearColor.md#desaturate)
- [Equals](ue_ue_s.LinearColor.md#equals)
- [GetClamped](ue_ue_s.LinearColor.md#getclamped)
- [GetLuminance](ue_ue_s.LinearColor.md#getluminance)
- [GetMax](ue_ue_s.LinearColor.md#getmax)
- [GetMin](ue_ue_s.LinearColor.md#getmin)
- [HSVToLinearRGB](ue_ue_s.LinearColor.md#hsvtolinearrgb)
- [InitFromString](ue_ue_s.LinearColor.md#initfromstring)
- [IsAlmostBlack](ue_ue_s.LinearColor.md#isalmostblack)
- [LinearRGBToHSV](ue_ue_s.LinearColor.md#linearrgbtohsv)
- [Quantize](ue_ue_s.LinearColor.md#quantize)
- [QuantizeRound](ue_ue_s.LinearColor.md#quantizeround)
- [ToFColor](ue_ue_s.LinearColor.md#tofcolor)
- [ToRGBE](ue_ue_s.LinearColor.md#torgbe)
- [ToString](ue_ue_s.LinearColor.md#tostring)
- [op\_Addition](ue_ue_s.LinearColor.md#op_addition)
- [op\_Division](ue_ue_s.LinearColor.md#op_division)
- [op\_Equality](ue_ue_s.LinearColor.md#op_equality)
- [op\_Inequality](ue_ue_s.LinearColor.md#op_inequality)
- [op\_Multiply](ue_ue_s.LinearColor.md#op_multiply)
- [op\_Subtraction](ue_ue_s.LinearColor.md#op_subtraction)
- [Dist](ue_ue_s.LinearColor.md#dist)
- [FromPow22Color](ue_ue_s.LinearColor.md#frompow22color)
- [FromSRGBColor](ue_ue_s.LinearColor.md#fromsrgbcolor)
- [LerpUsingHSV](ue_ue_s.LinearColor.md#lerpusinghsv)
- [MakeFromColorTemperature](ue_ue_s.LinearColor.md#makefromcolortemperature)
- [MakeRandomColor](ue_ue_s.LinearColor.md#makerandomcolor)
- [StaticClass](ue_ue_s.LinearColor.md#staticclass)
- [StaticStruct](ue_ue_s.LinearColor.md#staticstruct)

## Constructors

### constructor

• **new LinearColor**()

• **new LinearColor**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

• **new LinearColor**(`InR`, `InG`, `InB`, `InA`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InR` | `number` |
| `InG` | `number` |
| `InB` | `number` |
| `InA` | `number` |

• **new LinearColor**(`Color`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Color` | [`Color`](ue_ue_s.Color.md) |

• **new LinearColor**(`Vector`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Vector` | [`Vector`](ue_ue_s.Vector.md) |

• **new LinearColor**(`Vector`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Vector` | [`Vector4`](ue_ue_s.Vector4.md) |

## Properties

### A

• **A**: `number`

___

### B

• **B**: `number`

___

### G

• **G**: `number`

___

### R

• **R**: `number`

___

### \_\_tid\_LinearColor\_\_

• `Private` **\_\_tid\_LinearColor\_\_**: `boolean`

## Methods

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

### ComputeLuminance

▸ **ComputeLuminance**(): `number`

#### Returns

`number`

___

### CopyWithNewOpacity

▸ **CopyWithNewOpacity**(`NewOpacicty`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewOpacicty` | `number` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

___

### Desaturate

▸ **Desaturate**(`Desaturation`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Desaturation` | `number` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

___

### Equals

▸ **Equals**(`ColorB`, `Tolerance`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ColorB` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `Tolerance` | `number` |

#### Returns

`boolean`

___

### GetClamped

▸ **GetClamped**(`InMin`, `InMax`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InMin` | `number` |
| `InMax` | `number` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

___

### GetLuminance

▸ **GetLuminance**(): `number`

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

### HSVToLinearRGB

▸ **HSVToLinearRGB**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

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

### IsAlmostBlack

▸ **IsAlmostBlack**(): `boolean`

#### Returns

`boolean`

___

### LinearRGBToHSV

▸ **LinearRGBToHSV**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

___

### Quantize

▸ **Quantize**(): [`Color`](ue_ue_s.Color.md)

#### Returns

[`Color`](ue_ue_s.Color.md)

___

### QuantizeRound

▸ **QuantizeRound**(): [`Color`](ue_ue_s.Color.md)

#### Returns

[`Color`](ue_ue_s.Color.md)

___

### ToFColor

▸ **ToFColor**(`bSRGB`): [`Color`](ue_ue_s.Color.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `bSRGB` | `boolean` |

#### Returns

[`Color`](ue_ue_s.Color.md)

___

### ToRGBE

▸ **ToRGBE**(): [`Color`](ue_ue_s.Color.md)

#### Returns

[`Color`](ue_ue_s.Color.md)

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

___

### op\_Addition

▸ **op_Addition**(`ColorB`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ColorB` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

___

### op\_Division

▸ **op_Division**(`ColorB`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ColorB` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

▸ **op_Division**(`Scalar`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scalar` | `number` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

___

### op\_Equality

▸ **op_Equality**(`ColorB`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ColorB` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`boolean`

___

### op\_Inequality

▸ **op_Inequality**(`Other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`boolean`

___

### op\_Multiply

▸ **op_Multiply**(`ColorB`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ColorB` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

▸ **op_Multiply**(`Scalar`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scalar` | `number` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

___

### op\_Subtraction

▸ **op_Subtraction**(`ColorB`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ColorB` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

___

### Dist

▸ `Static` **Dist**(`V1`, `V2`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `V1` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `V2` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`number`

___

### FromPow22Color

▸ `Static` **FromPow22Color**(`Color`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Color` | [`Color`](ue_ue_s.Color.md) |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

___

### FromSRGBColor

▸ `Static` **FromSRGBColor**(`Color`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Color` | [`Color`](ue_ue_s.Color.md) |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

___

### LerpUsingHSV

▸ `Static` **LerpUsingHSV**(`From`, `To`, `Progress`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `From` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `To` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `Progress` | `number` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

___

### MakeFromColorTemperature

▸ `Static` **MakeFromColorTemperature**(`Temp`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Temp` | `number` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

___

### MakeRandomColor

▸ `Static` **MakeRandomColor**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

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
