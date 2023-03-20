[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialExpressionSceneTexture

# Class: MaterialExpressionSceneTexture

[ue/ue](../modules/ue_ue.md).MaterialExpressionSceneTexture

## Hierarchy

- [`MaterialExpression`](ue_ue.MaterialExpression.md)

  ↳ **`MaterialExpressionSceneTexture`**

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialExpressionSceneTexture.md#constructor)

### Properties

- [Coordinates](ue_ue.MaterialExpressionSceneTexture.md#coordinates)
- [Desc](ue_ue.MaterialExpressionSceneTexture.md#desc)
- [Function](ue_ue.MaterialExpressionSceneTexture.md#function)
- [GraphNode](ue_ue.MaterialExpressionSceneTexture.md#graphnode)
- [Material](ue_ue.MaterialExpressionSceneTexture.md#material)
- [MaterialExpressionEditorX](ue_ue.MaterialExpressionSceneTexture.md#materialexpressioneditorx)
- [MaterialExpressionEditorY](ue_ue.MaterialExpressionSceneTexture.md#materialexpressioneditory)
- [MaterialExpressionGuid](ue_ue.MaterialExpressionSceneTexture.md#materialexpressionguid)
- [MenuCategories](ue_ue.MaterialExpressionSceneTexture.md#menucategories)
- [Outputs](ue_ue.MaterialExpressionSceneTexture.md#outputs)
- [SceneTextureId](ue_ue.MaterialExpressionSceneTexture.md#scenetextureid)
- [\_\_tid\_MaterialExpressionSceneTexture\_\_](ue_ue.MaterialExpressionSceneTexture.md#__tid_materialexpressionscenetexture__)
- [\_\_tid\_MaterialExpression\_\_](ue_ue.MaterialExpressionSceneTexture.md#__tid_materialexpression__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialExpressionSceneTexture.md#__tid_object__)
- [bCollapsed](ue_ue.MaterialExpressionSceneTexture.md#bcollapsed)
- [bCommentBubbleVisible](ue_ue.MaterialExpressionSceneTexture.md#bcommentbubblevisible)
- [bFiltered](ue_ue.MaterialExpressionSceneTexture.md#bfiltered)
- [bHidePreviewWindow](ue_ue.MaterialExpressionSceneTexture.md#bhidepreviewwindow)
- [bIsParameterExpression](ue_ue.MaterialExpressionSceneTexture.md#bisparameterexpression)
- [bNeedToUpdatePreview](ue_ue.MaterialExpressionSceneTexture.md#bneedtoupdatepreview)
- [bRealtimePreview](ue_ue.MaterialExpressionSceneTexture.md#brealtimepreview)
- [bShaderInputData](ue_ue.MaterialExpressionSceneTexture.md#bshaderinputdata)
- [bShowInputs](ue_ue.MaterialExpressionSceneTexture.md#bshowinputs)
- [bShowMaskColorsOnPin](ue_ue.MaterialExpressionSceneTexture.md#bshowmaskcolorsonpin)
- [bShowOutputNameOnPin](ue_ue.MaterialExpressionSceneTexture.md#bshowoutputnameonpin)
- [bShowOutputs](ue_ue.MaterialExpressionSceneTexture.md#bshowoutputs)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialExpressionSceneTexture.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialExpressionSceneTexture.md#executeubergraph)
- [GetClass](ue_ue.MaterialExpressionSceneTexture.md#getclass)
- [GetName](ue_ue.MaterialExpressionSceneTexture.md#getname)
- [GetOuter](ue_ue.MaterialExpressionSceneTexture.md#getouter)
- [GetWorld](ue_ue.MaterialExpressionSceneTexture.md#getworld)
- [Find](ue_ue.MaterialExpressionSceneTexture.md#find)
- [Load](ue_ue.MaterialExpressionSceneTexture.md#load)
- [StaticClass](ue_ue.MaterialExpressionSceneTexture.md#staticclass)

## Constructors

### constructor

• **new MaterialExpressionSceneTexture**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[constructor](ue_ue.MaterialExpression.md#constructor)

## Properties

### Coordinates

• **Coordinates**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

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

### SceneTextureId

• **SceneTextureId**: [`ESceneTextureId`](../enums/ue_ue.ESceneTextureId.md)

___

### \_\_tid\_MaterialExpressionSceneTexture\_\_

• **\_\_tid\_MaterialExpressionSceneTexture\_\_**: `boolean`

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

### bFiltered

• **bFiltered**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialExpressionSceneTexture`](ue_ue.MaterialExpressionSceneTexture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialExpressionSceneTexture`](ue_ue.MaterialExpressionSceneTexture.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[Find](ue_ue.MaterialExpression.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialExpressionSceneTexture`](ue_ue.MaterialExpressionSceneTexture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialExpressionSceneTexture`](ue_ue.MaterialExpressionSceneTexture.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[Load](ue_ue.MaterialExpression.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[StaticClass](ue_ue.MaterialExpression.md#staticclass)
