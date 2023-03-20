[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue\_s](../modules/ue_ue_s.md) / Color

# Class: Color

[ue/ue_s](../modules/ue_ue_s.md).Color

## Table of contents

### Constructors

- [constructor](ue_ue_s.Color.md#constructor)

### Properties

- [\_\_tid\_Color\_\_](ue_ue_s.Color.md#__tid_color__)

### Methods

- [DWColor](ue_ue_s.Color.md#dwcolor)
- [FromRGBE](ue_ue_s.Color.md#fromrgbe)
- [InitFromString](ue_ue_s.Color.md#initfromstring)
- [ReinterpretAsLinear](ue_ue_s.Color.md#reinterpretaslinear)
- [ToHex](ue_ue_s.Color.md#tohex)
- [ToPackedABGR](ue_ue_s.Color.md#topackedabgr)
- [ToPackedARGB](ue_ue_s.Color.md#topackedargb)
- [ToPackedBGRA](ue_ue_s.Color.md#topackedbgra)
- [ToPackedRGBA](ue_ue_s.Color.md#topackedrgba)
- [ToString](ue_ue_s.Color.md#tostring)
- [WithAlpha](ue_ue_s.Color.md#withalpha)
- [op\_Equality](ue_ue_s.Color.md#op_equality)
- [op\_Inequality](ue_ue_s.Color.md#op_inequality)
- [FromHex](ue_ue_s.Color.md#fromhex)
- [MakeFromColorTemperature](ue_ue_s.Color.md#makefromcolortemperature)
- [MakeRandomColor](ue_ue_s.Color.md#makerandomcolor)
- [MakeRedToGreenColorFromScalar](ue_ue_s.Color.md#makeredtogreencolorfromscalar)
- [StaticClass](ue_ue_s.Color.md#staticclass)
- [StaticStruct](ue_ue_s.Color.md#staticstruct)

## Constructors

### constructor

• **new Color**()

#### Defined in

[ue/ue_s.d.ts:68](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L68)

• **new Color**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

#### Defined in

[ue/ue_s.d.ts:69](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L69)

• **new Color**(`InR`, `InG`, `InB`, `InA`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InR` | `number` |
| `InG` | `number` |
| `InB` | `number` |
| `InA` | `number` |

#### Defined in

[ue/ue_s.d.ts:70](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L70)

• **new Color**(`InColor`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InColor` | `number` |

#### Defined in

[ue/ue_s.d.ts:71](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L71)

## Properties

### \_\_tid\_Color\_\_

• `Private` **\_\_tid\_Color\_\_**: `boolean`

#### Defined in

[ue/ue_s.d.ts:97](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L97)

## Methods

### DWColor

▸ **DWColor**(): [`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

#### Returns

[`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

#### Defined in

[ue/ue_s.d.ts:72](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L72)

▸ **DWColor**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:73](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L73)

___

### FromRGBE

▸ **FromRGBE**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue_s.d.ts:76](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L76)

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

[ue/ue_s.d.ts:85](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L85)

___

### ReinterpretAsLinear

▸ **ReinterpretAsLinear**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue_s.d.ts:82](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L82)

___

### ToHex

▸ **ToHex**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue_s.d.ts:83](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L83)

___

### ToPackedABGR

▸ **ToPackedABGR**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:87](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L87)

___

### ToPackedARGB

▸ **ToPackedARGB**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:86](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L86)

___

### ToPackedBGRA

▸ **ToPackedBGRA**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:89](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L89)

___

### ToPackedRGBA

▸ **ToPackedRGBA**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue_s.d.ts:88](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L88)

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue_s.d.ts:84](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L84)

___

### WithAlpha

▸ **WithAlpha**(`Alpha`): [`Color`](ue_ue_s.Color.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Alpha` | `number` |

#### Returns

[`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue_s.d.ts:81](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L81)

___

### op\_Equality

▸ **op_Equality**(`C`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `C` | [`Color`](ue_ue_s.Color.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:74](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L74)

___

### op\_Inequality

▸ **op_Inequality**(`C`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `C` | [`Color`](ue_ue_s.Color.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue_s.d.ts:75](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L75)

___

### FromHex

▸ `Static` **FromHex**(`HexString`): [`Color`](ue_ue_s.Color.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `HexString` | `string` |

#### Returns

[`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue_s.d.ts:77](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L77)

___

### MakeFromColorTemperature

▸ `Static` **MakeFromColorTemperature**(`Temp`): [`Color`](ue_ue_s.Color.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Temp` | `number` |

#### Returns

[`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue_s.d.ts:80](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L80)

___

### MakeRandomColor

▸ `Static` **MakeRandomColor**(): [`Color`](ue_ue_s.Color.md)

#### Returns

[`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue_s.d.ts:78](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L78)

___

### MakeRedToGreenColorFromScalar

▸ `Static` **MakeRedToGreenColorFromScalar**(`Scalar`): [`Color`](ue_ue_s.Color.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scalar` | `number` |

#### Returns

[`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue_s.d.ts:79](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L79)

___

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:94](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L94)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue_s.d.ts:95](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue_s.d.ts#L95)
