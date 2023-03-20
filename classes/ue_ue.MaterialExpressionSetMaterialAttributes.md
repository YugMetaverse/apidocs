[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialExpressionSetMaterialAttributes

# Class: MaterialExpressionSetMaterialAttributes

[ue/ue](../modules/ue_ue.md).MaterialExpressionSetMaterialAttributes

## Hierarchy

- [`MaterialExpression`](ue_ue.MaterialExpression.md)

  ↳ **`MaterialExpressionSetMaterialAttributes`**

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialExpressionSetMaterialAttributes.md#constructor)

### Properties

- [AttributeSetTypes](ue_ue.MaterialExpressionSetMaterialAttributes.md#attributesettypes)
- [Desc](ue_ue.MaterialExpressionSetMaterialAttributes.md#desc)
- [Function](ue_ue.MaterialExpressionSetMaterialAttributes.md#function)
- [GraphNode](ue_ue.MaterialExpressionSetMaterialAttributes.md#graphnode)
- [Inputs](ue_ue.MaterialExpressionSetMaterialAttributes.md#inputs)
- [Material](ue_ue.MaterialExpressionSetMaterialAttributes.md#material)
- [MaterialExpressionEditorX](ue_ue.MaterialExpressionSetMaterialAttributes.md#materialexpressioneditorx)
- [MaterialExpressionEditorY](ue_ue.MaterialExpressionSetMaterialAttributes.md#materialexpressioneditory)
- [MaterialExpressionGuid](ue_ue.MaterialExpressionSetMaterialAttributes.md#materialexpressionguid)
- [MenuCategories](ue_ue.MaterialExpressionSetMaterialAttributes.md#menucategories)
- [Outputs](ue_ue.MaterialExpressionSetMaterialAttributes.md#outputs)
- [\_\_tid\_MaterialExpressionSetMaterialAttributes\_\_](ue_ue.MaterialExpressionSetMaterialAttributes.md#__tid_materialexpressionsetmaterialattributes__)
- [\_\_tid\_MaterialExpression\_\_](ue_ue.MaterialExpressionSetMaterialAttributes.md#__tid_materialexpression__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialExpressionSetMaterialAttributes.md#__tid_object__)
- [bCollapsed](ue_ue.MaterialExpressionSetMaterialAttributes.md#bcollapsed)
- [bCommentBubbleVisible](ue_ue.MaterialExpressionSetMaterialAttributes.md#bcommentbubblevisible)
- [bHidePreviewWindow](ue_ue.MaterialExpressionSetMaterialAttributes.md#bhidepreviewwindow)
- [bIsParameterExpression](ue_ue.MaterialExpressionSetMaterialAttributes.md#bisparameterexpression)
- [bNeedToUpdatePreview](ue_ue.MaterialExpressionSetMaterialAttributes.md#bneedtoupdatepreview)
- [bRealtimePreview](ue_ue.MaterialExpressionSetMaterialAttributes.md#brealtimepreview)
- [bShaderInputData](ue_ue.MaterialExpressionSetMaterialAttributes.md#bshaderinputdata)
- [bShowInputs](ue_ue.MaterialExpressionSetMaterialAttributes.md#bshowinputs)
- [bShowMaskColorsOnPin](ue_ue.MaterialExpressionSetMaterialAttributes.md#bshowmaskcolorsonpin)
- [bShowOutputNameOnPin](ue_ue.MaterialExpressionSetMaterialAttributes.md#bshowoutputnameonpin)
- [bShowOutputs](ue_ue.MaterialExpressionSetMaterialAttributes.md#bshowoutputs)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialExpressionSetMaterialAttributes.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialExpressionSetMaterialAttributes.md#executeubergraph)
- [GetClass](ue_ue.MaterialExpressionSetMaterialAttributes.md#getclass)
- [GetName](ue_ue.MaterialExpressionSetMaterialAttributes.md#getname)
- [GetOuter](ue_ue.MaterialExpressionSetMaterialAttributes.md#getouter)
- [GetWorld](ue_ue.MaterialExpressionSetMaterialAttributes.md#getworld)
- [Find](ue_ue.MaterialExpressionSetMaterialAttributes.md#find)
- [Load](ue_ue.MaterialExpressionSetMaterialAttributes.md#load)
- [StaticClass](ue_ue.MaterialExpressionSetMaterialAttributes.md#staticclass)

## Constructors

### constructor

• **new MaterialExpressionSetMaterialAttributes**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[constructor](ue_ue.MaterialExpression.md#constructor)

## Properties

### AttributeSetTypes

• **AttributeSetTypes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Guid`](ue_ue_s.Guid.md)\>

___

### Desc

• **Desc**: `string`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Desc](ue_ue.MaterialExpression.md#desc)

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

• **Inputs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ExpressionInput`](ue_ue.ExpressionInput.md)\>

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

### Outputs

• **Outputs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ExpressionOutput`](ue_ue.ExpressionOutput.md)\>

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Outputs](ue_ue.MaterialExpression.md#outputs)

___

### \_\_tid\_MaterialExpressionSetMaterialAttributes\_\_

• **\_\_tid\_MaterialExpressionSetMaterialAttributes\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialExpressionSetMaterialAttributes`](ue_ue.MaterialExpressionSetMaterialAttributes.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialExpressionSetMaterialAttributes`](ue_ue.MaterialExpressionSetMaterialAttributes.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[Find](ue_ue.MaterialExpression.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialExpressionSetMaterialAttributes`](ue_ue.MaterialExpressionSetMaterialAttributes.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialExpressionSetMaterialAttributes`](ue_ue.MaterialExpressionSetMaterialAttributes.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[Load](ue_ue.MaterialExpression.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[StaticClass](ue_ue.MaterialExpression.md#staticclass)
