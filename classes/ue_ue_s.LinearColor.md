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

#### Defined in

[ue/ue_s.d.ts:101](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L101)

• **new LinearColor**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

#### Defined in

[ue/ue_s.d.ts:102](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L102)

• **new LinearColor**(`InR`, `InG`, `InB`, `InA`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InR` | `number` |
| `InG` | `number` |
| `InB` | `number` |
| `InA` | `number` |

#### Defined in

[ue/ue_s.d.ts:103](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L103)

• **new LinearColor**(`Color`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Color` | [`Color`](ue_ue_s.Color.md) |

#### Defined in

[ue/ue_s.d.ts:104](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L104)

• **new LinearColor**(`Vector`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Vector` | [`Vector`](ue_ue_s.Vector.md) |

#### Defined in

[ue/ue_s.d.ts:105](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L105)

• **new LinearColor**(`Vector`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Vector` | [`Vector4`](ue_ue_s.Vector4.md) |

#### Defined in

[ue/ue_s.d.ts:106](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L106)

## Properties

### A

• **A**: `number`

#### Defined in

[ue/ue_s.d.ts:110](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L110)

___

### B

• **B**: `number`

#### Defined in

[ue/ue_s.d.ts:109](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L109)

___

### G

• **G**: `number`

#### Defined in

[ue/ue_s.d.ts:108](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L108)

___

### R

• **R**: `number`

#### Defined in

[ue/ue_s.d.ts:107](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L107)

___

### \_\_tid\_LinearColor\_\_

• `Private` **\_\_tid\_LinearColor\_\_**: `boolean`

#### Defined in

[ue/ue_s.d.ts:151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L151)

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

[ue/ue_s.d.ts:114](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L114)

▸ **Component**(`Index`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:115](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L115)

___

### ComputeLuminance

▸ **ComputeLuminance**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:137](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L137)

___

### CopyWithNewOpacity

▸ **CopyWithNewOpacity**(`NewOpacicty`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewOpacicty` | `number` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue_s.d.ts:126](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L126)

___

### Desaturate

▸ **Desaturate**(`Desaturation`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Desaturation` | `number` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue_s.d.ts:136](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L136)

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

#### Defined in

[ue/ue_s.d.ts:125](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L125)

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

#### Defined in

[ue/ue_s.d.ts:122](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L122)

___

### GetLuminance

▸ **GetLuminance**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:141](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L141)

___

### GetMax

▸ **GetMax**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:138](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L138)

___

### GetMin

▸ **GetMin**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:140](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L140)

___

### HSVToLinearRGB

▸ **HSVToLinearRGB**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue_s.d.ts:131](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L131)

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

[ue/ue_s.d.ts:143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L143)

___

### IsAlmostBlack

▸ **IsAlmostBlack**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:139](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L139)

___

### LinearRGBToHSV

▸ **LinearRGBToHSV**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue_s.d.ts:130](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L130)

___

### Quantize

▸ **Quantize**(): [`Color`](ue_ue_s.Color.md)

#### Returns

[`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue_s.d.ts:133](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L133)

___

### QuantizeRound

▸ **QuantizeRound**(): [`Color`](ue_ue_s.Color.md)

#### Returns

[`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue_s.d.ts:134](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L134)

___

### ToFColor

▸ **ToFColor**(`bSRGB`): [`Color`](ue_ue_s.Color.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `bSRGB` | `boolean` |

#### Returns

[`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue_s.d.ts:135](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L135)

___

### ToRGBE

▸ **ToRGBE**(): [`Color`](ue_ue_s.Color.md)

#### Returns

[`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue_s.d.ts:111](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L111)

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue_s.d.ts:142](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L142)

___

### op\_Addition

▸ **op_Addition**(`ColorB`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ColorB` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue_s.d.ts:116](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L116)

___

### op\_Division

▸ **op_Division**(`ColorB`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ColorB` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue_s.d.ts:120](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L120)

▸ **op_Division**(`Scalar`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scalar` | `number` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue_s.d.ts:121](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L121)

___

### op\_Equality

▸ **op_Equality**(`ColorB`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ColorB` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:123](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L123)

___

### op\_Inequality

▸ **op_Inequality**(`Other`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Other` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:124](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L124)

___

### op\_Multiply

▸ **op_Multiply**(`ColorB`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ColorB` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue_s.d.ts:118](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L118)

▸ **op_Multiply**(`Scalar`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scalar` | `number` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue_s.d.ts:119](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L119)

___

### op\_Subtraction

▸ **op_Subtraction**(`ColorB`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ColorB` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue_s.d.ts:117](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L117)

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

#### Defined in

[ue/ue_s.d.ts:129](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L129)

___

### FromPow22Color

▸ `Static` **FromPow22Color**(`Color`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Color` | [`Color`](ue_ue_s.Color.md) |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue_s.d.ts:113](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L113)

___

### FromSRGBColor

▸ `Static` **FromSRGBColor**(`Color`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Color` | [`Color`](ue_ue_s.Color.md) |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue_s.d.ts:112](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L112)

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

#### Defined in

[ue/ue_s.d.ts:132](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L132)

___

### MakeFromColorTemperature

▸ `Static` **MakeFromColorTemperature**(`Temp`): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Temp` | `number` |

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue_s.d.ts:128](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L128)

___

### MakeRandomColor

▸ `Static` **MakeRandomColor**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue_s.d.ts:127](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L127)

___

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:148](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L148)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:149](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L149)
