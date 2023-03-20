[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialExpressionNoise

# Class: MaterialExpressionNoise

[ue/ue](../modules/ue_ue.md).MaterialExpressionNoise

## Hierarchy

- [`MaterialExpression`](ue_ue.MaterialExpression.md)

  ↳ **`MaterialExpressionNoise`**

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialExpressionNoise.md#constructor)

### Properties

- [Desc](ue_ue.MaterialExpressionNoise.md#desc)
- [FilterWidth](ue_ue.MaterialExpressionNoise.md#filterwidth)
- [Function](ue_ue.MaterialExpressionNoise.md#function)
- [GraphNode](ue_ue.MaterialExpressionNoise.md#graphnode)
- [LevelScale](ue_ue.MaterialExpressionNoise.md#levelscale)
- [Levels](ue_ue.MaterialExpressionNoise.md#levels)
- [Material](ue_ue.MaterialExpressionNoise.md#material)
- [MaterialExpressionEditorX](ue_ue.MaterialExpressionNoise.md#materialexpressioneditorx)
- [MaterialExpressionEditorY](ue_ue.MaterialExpressionNoise.md#materialexpressioneditory)
- [MaterialExpressionGuid](ue_ue.MaterialExpressionNoise.md#materialexpressionguid)
- [MenuCategories](ue_ue.MaterialExpressionNoise.md#menucategories)
- [NoiseFunction](ue_ue.MaterialExpressionNoise.md#noisefunction)
- [OutputMax](ue_ue.MaterialExpressionNoise.md#outputmax)
- [OutputMin](ue_ue.MaterialExpressionNoise.md#outputmin)
- [Outputs](ue_ue.MaterialExpressionNoise.md#outputs)
- [Position](ue_ue.MaterialExpressionNoise.md#position)
- [Quality](ue_ue.MaterialExpressionNoise.md#quality)
- [RepeatSize](ue_ue.MaterialExpressionNoise.md#repeatsize)
- [Scale](ue_ue.MaterialExpressionNoise.md#scale)
- [\_\_tid\_MaterialExpressionNoise\_\_](ue_ue.MaterialExpressionNoise.md#__tid_materialexpressionnoise__)
- [\_\_tid\_MaterialExpression\_\_](ue_ue.MaterialExpressionNoise.md#__tid_materialexpression__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialExpressionNoise.md#__tid_object__)
- [bCollapsed](ue_ue.MaterialExpressionNoise.md#bcollapsed)
- [bCommentBubbleVisible](ue_ue.MaterialExpressionNoise.md#bcommentbubblevisible)
- [bHidePreviewWindow](ue_ue.MaterialExpressionNoise.md#bhidepreviewwindow)
- [bIsParameterExpression](ue_ue.MaterialExpressionNoise.md#bisparameterexpression)
- [bNeedToUpdatePreview](ue_ue.MaterialExpressionNoise.md#bneedtoupdatepreview)
- [bRealtimePreview](ue_ue.MaterialExpressionNoise.md#brealtimepreview)
- [bShaderInputData](ue_ue.MaterialExpressionNoise.md#bshaderinputdata)
- [bShowInputs](ue_ue.MaterialExpressionNoise.md#bshowinputs)
- [bShowMaskColorsOnPin](ue_ue.MaterialExpressionNoise.md#bshowmaskcolorsonpin)
- [bShowOutputNameOnPin](ue_ue.MaterialExpressionNoise.md#bshowoutputnameonpin)
- [bShowOutputs](ue_ue.MaterialExpressionNoise.md#bshowoutputs)
- [bTiling](ue_ue.MaterialExpressionNoise.md#btiling)
- [bTurbulence](ue_ue.MaterialExpressionNoise.md#bturbulence)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialExpressionNoise.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialExpressionNoise.md#executeubergraph)
- [GetClass](ue_ue.MaterialExpressionNoise.md#getclass)
- [GetName](ue_ue.MaterialExpressionNoise.md#getname)
- [GetOuter](ue_ue.MaterialExpressionNoise.md#getouter)
- [GetWorld](ue_ue.MaterialExpressionNoise.md#getworld)
- [Find](ue_ue.MaterialExpressionNoise.md#find)
- [Load](ue_ue.MaterialExpressionNoise.md#load)
- [StaticClass](ue_ue.MaterialExpressionNoise.md#staticclass)

## Constructors

### constructor

• **new MaterialExpressionNoise**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[constructor](ue_ue.MaterialExpression.md#constructor)

## Properties

### Desc

• **Desc**: `string`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Desc](ue_ue.MaterialExpression.md#desc)

___

### FilterWidth

• **FilterWidth**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

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

### LevelScale

• **LevelScale**: `number`

___

### Levels

• **Levels**: `number`

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

### NoiseFunction

• **NoiseFunction**: [`ENoiseFunction`](../enums/ue_ue.ENoiseFunction.md)

___

### OutputMax

• **OutputMax**: `number`

___

### OutputMin

• **OutputMin**: `number`

___

### Outputs

• **Outputs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ExpressionOutput`](ue_ue.ExpressionOutput.md)\>

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Outputs](ue_ue.MaterialExpression.md#outputs)

___

### Position

• **Position**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

___

### Quality

• **Quality**: `number`

___

### RepeatSize

• **RepeatSize**: `number`

___

### Scale

• **Scale**: `number`

___

### \_\_tid\_MaterialExpressionNoise\_\_

• **\_\_tid\_MaterialExpressionNoise\_\_**: `boolean`

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

___

### bTiling

• **bTiling**: `boolean`

___

### bTurbulence

• **bTurbulence**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialExpressionNoise`](ue_ue.MaterialExpressionNoise.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialExpressionNoise`](ue_ue.MaterialExpressionNoise.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[Find](ue_ue.MaterialExpression.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialExpressionNoise`](ue_ue.MaterialExpressionNoise.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialExpressionNoise`](ue_ue.MaterialExpressionNoise.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[Load](ue_ue.MaterialExpression.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[StaticClass](ue_ue.MaterialExpression.md#staticclass)
