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

• **new Color**(`Param1`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Param1` | `number` |

• **new Color**(`InR`, `InG`, `InB`, `InA`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InR` | `number` |
| `InG` | `number` |
| `InB` | `number` |
| `InA` | `number` |

• **new Color**(`InColor`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InColor` | `number` |

## Properties

### \_\_tid\_Color\_\_

• `Private` **\_\_tid\_Color\_\_**: `boolean`

## Methods

### DWColor

▸ **DWColor**(): [`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

#### Returns

[`$Ref`](../interfaces/puerts._Ref.md)<`number`\>

▸ **DWColor**(): `number`

#### Returns

`number`

___

### FromRGBE

▸ **FromRGBE**(): [`LinearColor`](ue_ue_s.LinearColor.md)

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

### ReinterpretAsLinear

▸ **ReinterpretAsLinear**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

___

### ToHex

▸ **ToHex**(): `string`

#### Returns

`string`

___

### ToPackedABGR

▸ **ToPackedABGR**(): `number`

#### Returns

`number`

___

### ToPackedARGB

▸ **ToPackedARGB**(): `number`

#### Returns

`number`

___

### ToPackedBGRA

▸ **ToPackedBGRA**(): `number`

#### Returns

`number`

___

### ToPackedRGBA

▸ **ToPackedRGBA**(): `number`

#### Returns

`number`

___

### ToString

▸ **ToString**(): `string`

#### Returns

`string`

___

### WithAlpha

▸ **WithAlpha**(`Alpha`): [`Color`](ue_ue_s.Color.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Alpha` | `number` |

#### Returns

[`Color`](ue_ue_s.Color.md)

___

### op\_Equality

▸ **op_Equality**(`C`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `C` | [`Color`](ue_ue_s.Color.md) |

#### Returns

`boolean`

___

### op\_Inequality

▸ **op_Inequality**(`C`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `C` | [`Color`](ue_ue_s.Color.md) |

#### Returns

`boolean`

___

### FromHex

▸ `Static` **FromHex**(`HexString`): [`Color`](ue_ue_s.Color.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `HexString` | `string` |

#### Returns

[`Color`](ue_ue_s.Color.md)

___

### MakeFromColorTemperature

▸ `Static` **MakeFromColorTemperature**(`Temp`): [`Color`](ue_ue_s.Color.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Temp` | `number` |

#### Returns

[`Color`](ue_ue_s.Color.md)

___

### MakeRandomColor

▸ `Static` **MakeRandomColor**(): [`Color`](ue_ue_s.Color.md)

#### Returns

[`Color`](ue_ue_s.Color.md)

___

### MakeRedToGreenColorFromScalar

▸ `Static` **MakeRedToGreenColorFromScalar**(`Scalar`): [`Color`](ue_ue_s.Color.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Scalar` | `number` |

#### Returns

[`Color`](ue_ue_s.Color.md)

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
