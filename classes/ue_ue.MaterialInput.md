[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialInput

# Class: MaterialInput

[ue/ue](../modules/ue_ue.md).MaterialInput

## Hierarchy

- **`MaterialInput`**

  ↳ [`ColorMaterialInput`](ue_ue.ColorMaterialInput.md)

  ↳ [`ScalarMaterialInput`](ue_ue.ScalarMaterialInput.md)

  ↳ [`VectorMaterialInput`](ue_ue.VectorMaterialInput.md)

  ↳ [`Vector2MaterialInput`](ue_ue.Vector2MaterialInput.md)

  ↳ [`ShadingModelMaterialInput`](ue_ue.ShadingModelMaterialInput.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialInput.md#constructor)

### Properties

- [Expression](ue_ue.MaterialInput.md#expression)
- [ExpressionName](ue_ue.MaterialInput.md#expressionname)
- [InputName](ue_ue.MaterialInput.md#inputname)
- [Mask](ue_ue.MaterialInput.md#mask)
- [MaskA](ue_ue.MaterialInput.md#maska)
- [MaskB](ue_ue.MaterialInput.md#maskb)
- [MaskG](ue_ue.MaterialInput.md#maskg)
- [MaskR](ue_ue.MaterialInput.md#maskr)
- [OutputIndex](ue_ue.MaterialInput.md#outputindex)
- [\_\_tid\_MaterialInput\_\_](ue_ue.MaterialInput.md#__tid_materialinput__)

### Methods

- [StaticClass](ue_ue.MaterialInput.md#staticclass)
- [StaticStruct](ue_ue.MaterialInput.md#staticstruct)

## Constructors

### constructor

• **new MaterialInput**()

#### Defined in

[ue/ue.d.ts:1185](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1185)

• **new MaterialInput**(`Expression`, `OutputIndex`, `InputName`, `Mask`, `MaskR`, `MaskG`, `MaskB`, `MaskA`, `ExpressionName`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Expression` | [`MaterialExpression`](ue_ue.MaterialExpression.md) |
| `OutputIndex` | `number` |
| `InputName` | `string` |
| `Mask` | `number` |
| `MaskR` | `number` |
| `MaskG` | `number` |
| `MaskB` | `number` |
| `MaskA` | `number` |
| `ExpressionName` | `string` |

#### Defined in

[ue/ue.d.ts:1186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1186)

## Properties

### Expression

• **Expression**: [`MaterialExpression`](ue_ue.MaterialExpression.md)

#### Defined in

[ue/ue.d.ts:1187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1187)

___

### ExpressionName

• **ExpressionName**: `string`

#### Defined in

[ue/ue.d.ts:1195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1195)

___

### InputName

• **InputName**: `string`

#### Defined in

[ue/ue.d.ts:1189](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1189)

___

### Mask

• **Mask**: `number`

#### Defined in

[ue/ue.d.ts:1190](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1190)

___

### MaskA

• **MaskA**: `number`

#### Defined in

[ue/ue.d.ts:1194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1194)

___

### MaskB

• **MaskB**: `number`

#### Defined in

[ue/ue.d.ts:1193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1193)

___

### MaskG

• **MaskG**: `number`

#### Defined in

[ue/ue.d.ts:1192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1192)

___

### MaskR

• **MaskR**: `number`

#### Defined in

[ue/ue.d.ts:1191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1191)

___

### OutputIndex

• **OutputIndex**: `number`

#### Defined in

[ue/ue.d.ts:1188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1188)

___

### \_\_tid\_MaterialInput\_\_

• `Private` **\_\_tid\_MaterialInput\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:1201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1201)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:1199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1199)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:1200](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1200)
