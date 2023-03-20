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

## Properties

### Expression

• **Expression**: [`MaterialExpression`](ue_ue.MaterialExpression.md)

___

### ExpressionName

• **ExpressionName**: `string`

___

### InputName

• **InputName**: `string`

___

### Mask

• **Mask**: `number`

___

### MaskA

• **MaskA**: `number`

___

### MaskB

• **MaskB**: `number`

___

### MaskG

• **MaskG**: `number`

___

### MaskR

• **MaskR**: `number`

___

### OutputIndex

• **OutputIndex**: `number`

___

### \_\_tid\_MaterialInput\_\_

• `Private` **\_\_tid\_MaterialInput\_\_**: `boolean`

## Methods

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
