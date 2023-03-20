[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialExpressionCustom

# Class: MaterialExpressionCustom

[ue/ue](../modules/ue_ue.md).MaterialExpressionCustom

## Hierarchy

- [`MaterialExpression`](ue_ue.MaterialExpression.md)

  ↳ **`MaterialExpressionCustom`**

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialExpressionCustom.md#constructor)

### Properties

- [Code](ue_ue.MaterialExpressionCustom.md#code)
- [Desc](ue_ue.MaterialExpressionCustom.md#desc)
- [Description](ue_ue.MaterialExpressionCustom.md#description)
- [Function](ue_ue.MaterialExpressionCustom.md#function)
- [GraphNode](ue_ue.MaterialExpressionCustom.md#graphnode)
- [Inputs](ue_ue.MaterialExpressionCustom.md#inputs)
- [Material](ue_ue.MaterialExpressionCustom.md#material)
- [MaterialExpressionEditorX](ue_ue.MaterialExpressionCustom.md#materialexpressioneditorx)
- [MaterialExpressionEditorY](ue_ue.MaterialExpressionCustom.md#materialexpressioneditory)
- [MaterialExpressionGuid](ue_ue.MaterialExpressionCustom.md#materialexpressionguid)
- [MenuCategories](ue_ue.MaterialExpressionCustom.md#menucategories)
- [OutputType](ue_ue.MaterialExpressionCustom.md#outputtype)
- [Outputs](ue_ue.MaterialExpressionCustom.md#outputs)
- [\_\_tid\_MaterialExpressionCustom\_\_](ue_ue.MaterialExpressionCustom.md#__tid_materialexpressioncustom__)
- [\_\_tid\_MaterialExpression\_\_](ue_ue.MaterialExpressionCustom.md#__tid_materialexpression__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialExpressionCustom.md#__tid_object__)
- [bCollapsed](ue_ue.MaterialExpressionCustom.md#bcollapsed)
- [bCommentBubbleVisible](ue_ue.MaterialExpressionCustom.md#bcommentbubblevisible)
- [bHidePreviewWindow](ue_ue.MaterialExpressionCustom.md#bhidepreviewwindow)
- [bIsParameterExpression](ue_ue.MaterialExpressionCustom.md#bisparameterexpression)
- [bNeedToUpdatePreview](ue_ue.MaterialExpressionCustom.md#bneedtoupdatepreview)
- [bRealtimePreview](ue_ue.MaterialExpressionCustom.md#brealtimepreview)
- [bShaderInputData](ue_ue.MaterialExpressionCustom.md#bshaderinputdata)
- [bShowInputs](ue_ue.MaterialExpressionCustom.md#bshowinputs)
- [bShowMaskColorsOnPin](ue_ue.MaterialExpressionCustom.md#bshowmaskcolorsonpin)
- [bShowOutputNameOnPin](ue_ue.MaterialExpressionCustom.md#bshowoutputnameonpin)
- [bShowOutputs](ue_ue.MaterialExpressionCustom.md#bshowoutputs)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialExpressionCustom.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialExpressionCustom.md#executeubergraph)
- [GetClass](ue_ue.MaterialExpressionCustom.md#getclass)
- [GetName](ue_ue.MaterialExpressionCustom.md#getname)
- [GetOuter](ue_ue.MaterialExpressionCustom.md#getouter)
- [GetWorld](ue_ue.MaterialExpressionCustom.md#getworld)
- [Find](ue_ue.MaterialExpressionCustom.md#find)
- [Load](ue_ue.MaterialExpressionCustom.md#load)
- [StaticClass](ue_ue.MaterialExpressionCustom.md#staticclass)

## Constructors

### constructor

• **new MaterialExpressionCustom**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[constructor](ue_ue.MaterialExpression.md#constructor)

## Properties

### Code

• **Code**: `string`

___

### Desc

• **Desc**: `string`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Desc](ue_ue.MaterialExpression.md#desc)

___

### Description

• **Description**: `string`

___

### Function

• **Function**: [`MaterialFunction`](ue_ue.MaterialFunction.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Function](ue_ue.MaterialExpression.md#function)

___

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[GraphNode](ue_ue.MaterialExpression.md#graphnode)

___

### Inputs

• **Inputs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`CustomInput`](ue_ue.CustomInput.md)\>

___

### Material

• **Material**: [`Material`](ue_ue.Material.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Material](ue_ue.MaterialExpression.md#material)

___

### MaterialExpressionEditorX

• **MaterialExpressionEditorX**: `number`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[MaterialExpressionEditorX](ue_ue.MaterialExpression.md#materialexpressioneditorx)

___

### MaterialExpressionEditorY

• **MaterialExpressionEditorY**: `number`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[MaterialExpressionEditorY](ue_ue.MaterialExpression.md#materialexpressioneditory)

___

### MaterialExpressionGuid

• **MaterialExpressionGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[MaterialExpressionGuid](ue_ue.MaterialExpression.md#materialexpressionguid)

___

### MenuCategories

• **MenuCategories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[MenuCategories](ue_ue.MaterialExpression.md#menucategories)

___

### OutputType

• **OutputType**: [`ECustomMaterialOutputType`](../enums/ue_ue.ECustomMaterialOutputType.md)

___

### Outputs

• **Outputs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ExpressionOutput`](ue_ue.ExpressionOutput.md)\>

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Outputs](ue_ue.MaterialExpression.md#outputs)

___

### \_\_tid\_MaterialExpressionCustom\_\_

• **\_\_tid\_MaterialExpressionCustom\_\_**: `boolean`

___

### \_\_tid\_MaterialExpression\_\_

• **\_\_tid\_MaterialExpression\_\_**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[__tid_MaterialExpression__](ue_ue.MaterialExpression.md#__tid_materialexpression__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[__tid_Object__](ue_ue.MaterialExpression.md#__tid_object__)

___

### bCollapsed

• **bCollapsed**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bCollapsed](ue_ue.MaterialExpression.md#bcollapsed)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bCommentBubbleVisible](ue_ue.MaterialExpression.md#bcommentbubblevisible)

___

### bHidePreviewWindow

• **bHidePreviewWindow**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bHidePreviewWindow](ue_ue.MaterialExpression.md#bhidepreviewwindow)

___

### bIsParameterExpression

• **bIsParameterExpression**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bIsParameterExpression](ue_ue.MaterialExpression.md#bisparameterexpression)

___

### bNeedToUpdatePreview

• **bNeedToUpdatePreview**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bNeedToUpdatePreview](ue_ue.MaterialExpression.md#bneedtoupdatepreview)

___

### bRealtimePreview

• **bRealtimePreview**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bRealtimePreview](ue_ue.MaterialExpression.md#brealtimepreview)

___

### bShaderInputData

• **bShaderInputData**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bShaderInputData](ue_ue.MaterialExpression.md#bshaderinputdata)

___

### bShowInputs

• **bShowInputs**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bShowInputs](ue_ue.MaterialExpression.md#bshowinputs)

___

### bShowMaskColorsOnPin

• **bShowMaskColorsOnPin**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bShowMaskColorsOnPin](ue_ue.MaterialExpression.md#bshowmaskcolorsonpin)

___

### bShowOutputNameOnPin

• **bShowOutputNameOnPin**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bShowOutputNameOnPin](ue_ue.MaterialExpression.md#bshowoutputnameonpin)

___

### bShowOutputs

• **bShowOutputs**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bShowOutputs](ue_ue.MaterialExpression.md#bshowoutputs)

## Methods

### CreateDefaultSubobject

▸ **CreateDefaultSubobject**(`p0`, `p1`, `p2`, `p3`, `p4`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `string` |
| `p1` | [`Class`](ue_ue.Class.md) |
| `p2` | [`Class`](ue_ue.Class.md) |
| `p3` | `boolean` |
| `p4` | `boolean` |

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[CreateDefaultSubobject](ue_ue.MaterialExpression.md#createdefaultsubobject)

___

### ExecuteUbergraph

▸ **ExecuteUbergraph**(`EntryPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryPoint` | `number` |

#### Returns

`void`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[ExecuteUbergraph](ue_ue.MaterialExpression.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[GetClass](ue_ue.MaterialExpression.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[GetName](ue_ue.MaterialExpression.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[GetOuter](ue_ue.MaterialExpression.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[GetWorld](ue_ue.MaterialExpression.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialExpressionCustom`](ue_ue.MaterialExpressionCustom.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialExpressionCustom`](ue_ue.MaterialExpressionCustom.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[Find](ue_ue.MaterialExpression.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialExpressionCustom`](ue_ue.MaterialExpressionCustom.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialExpressionCustom`](ue_ue.MaterialExpressionCustom.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[Load](ue_ue.MaterialExpression.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[StaticClass](ue_ue.MaterialExpression.md#staticclass)
