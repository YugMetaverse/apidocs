[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialExpressionSpriteTextureSampler

# Class: MaterialExpressionSpriteTextureSampler

[ue/ue](../modules/ue_ue.md).MaterialExpressionSpriteTextureSampler

## Hierarchy

- [`MaterialExpressionTextureSampleParameter2D`](ue_ue.MaterialExpressionTextureSampleParameter2D.md)

  ↳ **`MaterialExpressionSpriteTextureSampler`**

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialExpressionSpriteTextureSampler.md#constructor)

### Properties

- [AdditionalSlotIndex](ue_ue.MaterialExpressionSpriteTextureSampler.md#additionalslotindex)
- [AutomaticViewMipBias](ue_ue.MaterialExpressionSpriteTextureSampler.md#automaticviewmipbias)
- [AutomaticViewMipBiasValue](ue_ue.MaterialExpressionSpriteTextureSampler.md#automaticviewmipbiasvalue)
- [ChannelNames](ue_ue.MaterialExpressionSpriteTextureSampler.md#channelnames)
- [ConstCoordinate](ue_ue.MaterialExpressionSpriteTextureSampler.md#constcoordinate)
- [ConstMipValue](ue_ue.MaterialExpressionSpriteTextureSampler.md#constmipvalue)
- [Coordinates](ue_ue.MaterialExpressionSpriteTextureSampler.md#coordinates)
- [CoordinatesDX](ue_ue.MaterialExpressionSpriteTextureSampler.md#coordinatesdx)
- [CoordinatesDY](ue_ue.MaterialExpressionSpriteTextureSampler.md#coordinatesdy)
- [Desc](ue_ue.MaterialExpressionSpriteTextureSampler.md#desc)
- [ExpressionGUID](ue_ue.MaterialExpressionSpriteTextureSampler.md#expressionguid)
- [Function](ue_ue.MaterialExpressionSpriteTextureSampler.md#function)
- [GraphNode](ue_ue.MaterialExpressionSpriteTextureSampler.md#graphnode)
- [Group](ue_ue.MaterialExpressionSpriteTextureSampler.md#group)
- [IsDefaultMeshpaintTexture](ue_ue.MaterialExpressionSpriteTextureSampler.md#isdefaultmeshpainttexture)
- [Material](ue_ue.MaterialExpressionSpriteTextureSampler.md#material)
- [MaterialExpressionEditorX](ue_ue.MaterialExpressionSpriteTextureSampler.md#materialexpressioneditorx)
- [MaterialExpressionEditorY](ue_ue.MaterialExpressionSpriteTextureSampler.md#materialexpressioneditory)
- [MaterialExpressionGuid](ue_ue.MaterialExpressionSpriteTextureSampler.md#materialexpressionguid)
- [MenuCategories](ue_ue.MaterialExpressionSpriteTextureSampler.md#menucategories)
- [MipValue](ue_ue.MaterialExpressionSpriteTextureSampler.md#mipvalue)
- [MipValueMode](ue_ue.MaterialExpressionSpriteTextureSampler.md#mipvaluemode)
- [Outputs](ue_ue.MaterialExpressionSpriteTextureSampler.md#outputs)
- [ParameterName](ue_ue.MaterialExpressionSpriteTextureSampler.md#parametername)
- [SamplerSource](ue_ue.MaterialExpressionSpriteTextureSampler.md#samplersource)
- [SamplerType](ue_ue.MaterialExpressionSpriteTextureSampler.md#samplertype)
- [SlotDisplayName](ue_ue.MaterialExpressionSpriteTextureSampler.md#slotdisplayname)
- [SortPriority](ue_ue.MaterialExpressionSpriteTextureSampler.md#sortpriority)
- [Texture](ue_ue.MaterialExpressionSpriteTextureSampler.md#texture)
- [TextureObject](ue_ue.MaterialExpressionSpriteTextureSampler.md#textureobject)
- [\_\_tid\_MaterialExpressionSpriteTextureSampler\_\_](ue_ue.MaterialExpressionSpriteTextureSampler.md#__tid_materialexpressionspritetexturesampler__)
- [\_\_tid\_MaterialExpressionTextureBase\_\_](ue_ue.MaterialExpressionSpriteTextureSampler.md#__tid_materialexpressiontexturebase__)
- [\_\_tid\_MaterialExpressionTextureSampleParameter2D\_\_](ue_ue.MaterialExpressionSpriteTextureSampler.md#__tid_materialexpressiontexturesampleparameter2d__)
- [\_\_tid\_MaterialExpressionTextureSampleParameter\_\_](ue_ue.MaterialExpressionSpriteTextureSampler.md#__tid_materialexpressiontexturesampleparameter__)
- [\_\_tid\_MaterialExpressionTextureSample\_\_](ue_ue.MaterialExpressionSpriteTextureSampler.md#__tid_materialexpressiontexturesample__)
- [\_\_tid\_MaterialExpression\_\_](ue_ue.MaterialExpressionSpriteTextureSampler.md#__tid_materialexpression__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialExpressionSpriteTextureSampler.md#__tid_object__)
- [bCollapsed](ue_ue.MaterialExpressionSpriteTextureSampler.md#bcollapsed)
- [bCommentBubbleVisible](ue_ue.MaterialExpressionSpriteTextureSampler.md#bcommentbubblevisible)
- [bHidePreviewWindow](ue_ue.MaterialExpressionSpriteTextureSampler.md#bhidepreviewwindow)
- [bIsParameterExpression](ue_ue.MaterialExpressionSpriteTextureSampler.md#bisparameterexpression)
- [bNeedToUpdatePreview](ue_ue.MaterialExpressionSpriteTextureSampler.md#bneedtoupdatepreview)
- [bRealtimePreview](ue_ue.MaterialExpressionSpriteTextureSampler.md#brealtimepreview)
- [bSampleAdditionalTextures](ue_ue.MaterialExpressionSpriteTextureSampler.md#bsampleadditionaltextures)
- [bShaderInputData](ue_ue.MaterialExpressionSpriteTextureSampler.md#bshaderinputdata)
- [bShowInputs](ue_ue.MaterialExpressionSpriteTextureSampler.md#bshowinputs)
- [bShowMaskColorsOnPin](ue_ue.MaterialExpressionSpriteTextureSampler.md#bshowmaskcolorsonpin)
- [bShowOutputNameOnPin](ue_ue.MaterialExpressionSpriteTextureSampler.md#bshowoutputnameonpin)
- [bShowOutputs](ue_ue.MaterialExpressionSpriteTextureSampler.md#bshowoutputs)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialExpressionSpriteTextureSampler.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialExpressionSpriteTextureSampler.md#executeubergraph)
- [GetClass](ue_ue.MaterialExpressionSpriteTextureSampler.md#getclass)
- [GetName](ue_ue.MaterialExpressionSpriteTextureSampler.md#getname)
- [GetOuter](ue_ue.MaterialExpressionSpriteTextureSampler.md#getouter)
- [GetWorld](ue_ue.MaterialExpressionSpriteTextureSampler.md#getworld)
- [Find](ue_ue.MaterialExpressionSpriteTextureSampler.md#find)
- [Load](ue_ue.MaterialExpressionSpriteTextureSampler.md#load)
- [StaticClass](ue_ue.MaterialExpressionSpriteTextureSampler.md#staticclass)

## Constructors

### constructor

• **new MaterialExpressionSpriteTextureSampler**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[constructor](ue_ue.MaterialExpressionTextureSampleParameter2D.md#constructor)

## Properties

### AdditionalSlotIndex

• **AdditionalSlotIndex**: `number`

___

### AutomaticViewMipBias

• **AutomaticViewMipBias**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[AutomaticViewMipBias](ue_ue.MaterialExpressionTextureSampleParameter2D.md#automaticviewmipbias)

___

### AutomaticViewMipBiasValue

• **AutomaticViewMipBiasValue**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[AutomaticViewMipBiasValue](ue_ue.MaterialExpressionTextureSampleParameter2D.md#automaticviewmipbiasvalue)

___

### ChannelNames

• **ChannelNames**: [`ParameterChannelNames`](ue_ue.ParameterChannelNames.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[ChannelNames](ue_ue.MaterialExpressionTextureSampleParameter2D.md#channelnames)

___

### ConstCoordinate

• **ConstCoordinate**: `number`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[ConstCoordinate](ue_ue.MaterialExpressionTextureSampleParameter2D.md#constcoordinate)

___

### ConstMipValue

• **ConstMipValue**: `number`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[ConstMipValue](ue_ue.MaterialExpressionTextureSampleParameter2D.md#constmipvalue)

___

### Coordinates

• **Coordinates**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[Coordinates](ue_ue.MaterialExpressionTextureSampleParameter2D.md#coordinates)

___

### CoordinatesDX

• **CoordinatesDX**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[CoordinatesDX](ue_ue.MaterialExpressionTextureSampleParameter2D.md#coordinatesdx)

___

### CoordinatesDY

• **CoordinatesDY**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[CoordinatesDY](ue_ue.MaterialExpressionTextureSampleParameter2D.md#coordinatesdy)

___

### Desc

• **Desc**: `string`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[Desc](ue_ue.MaterialExpressionTextureSampleParameter2D.md#desc)

___

### ExpressionGUID

• **ExpressionGUID**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[ExpressionGUID](ue_ue.MaterialExpressionTextureSampleParameter2D.md#expressionguid)

___

### Function

• **Function**: [`MaterialFunction`](ue_ue.MaterialFunction.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[Function](ue_ue.MaterialExpressionTextureSampleParameter2D.md#function)

___

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[GraphNode](ue_ue.MaterialExpressionTextureSampleParameter2D.md#graphnode)

___

### Group

• **Group**: `string`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[Group](ue_ue.MaterialExpressionTextureSampleParameter2D.md#group)

___

### IsDefaultMeshpaintTexture

• **IsDefaultMeshpaintTexture**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[IsDefaultMeshpaintTexture](ue_ue.MaterialExpressionTextureSampleParameter2D.md#isdefaultmeshpainttexture)

___

### Material

• **Material**: [`Material`](ue_ue.Material.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[Material](ue_ue.MaterialExpressionTextureSampleParameter2D.md#material)

___

### MaterialExpressionEditorX

• **MaterialExpressionEditorX**: `number`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[MaterialExpressionEditorX](ue_ue.MaterialExpressionTextureSampleParameter2D.md#materialexpressioneditorx)

___

### MaterialExpressionEditorY

• **MaterialExpressionEditorY**: `number`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[MaterialExpressionEditorY](ue_ue.MaterialExpressionTextureSampleParameter2D.md#materialexpressioneditory)

___

### MaterialExpressionGuid

• **MaterialExpressionGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[MaterialExpressionGuid](ue_ue.MaterialExpressionTextureSampleParameter2D.md#materialexpressionguid)

___

### MenuCategories

• **MenuCategories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[MenuCategories](ue_ue.MaterialExpressionTextureSampleParameter2D.md#menucategories)

___

### MipValue

• **MipValue**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[MipValue](ue_ue.MaterialExpressionTextureSampleParameter2D.md#mipvalue)

___

### MipValueMode

• **MipValueMode**: [`ETextureMipValueMode`](../enums/ue_ue.ETextureMipValueMode.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[MipValueMode](ue_ue.MaterialExpressionTextureSampleParameter2D.md#mipvaluemode)

___

### Outputs

• **Outputs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ExpressionOutput`](ue_ue.ExpressionOutput.md)\>

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[Outputs](ue_ue.MaterialExpressionTextureSampleParameter2D.md#outputs)

___

### ParameterName

• **ParameterName**: `string`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[ParameterName](ue_ue.MaterialExpressionTextureSampleParameter2D.md#parametername)

___

### SamplerSource

• **SamplerSource**: [`ESamplerSourceMode`](../enums/ue_ue.ESamplerSourceMode.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[SamplerSource](ue_ue.MaterialExpressionTextureSampleParameter2D.md#samplersource)

___

### SamplerType

• **SamplerType**: [`EMaterialSamplerType`](../enums/ue_ue.EMaterialSamplerType.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[SamplerType](ue_ue.MaterialExpressionTextureSampleParameter2D.md#samplertype)

___

### SlotDisplayName

• **SlotDisplayName**: `string`

___

### SortPriority

• **SortPriority**: `number`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[SortPriority](ue_ue.MaterialExpressionTextureSampleParameter2D.md#sortpriority)

___

### Texture

• **Texture**: [`Texture`](ue_ue.Texture.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[Texture](ue_ue.MaterialExpressionTextureSampleParameter2D.md#texture)

___

### TextureObject

• **TextureObject**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[TextureObject](ue_ue.MaterialExpressionTextureSampleParameter2D.md#textureobject)

___

### \_\_tid\_MaterialExpressionSpriteTextureSampler\_\_

• **\_\_tid\_MaterialExpressionSpriteTextureSampler\_\_**: `boolean`

___

### \_\_tid\_MaterialExpressionTextureBase\_\_

• **\_\_tid\_MaterialExpressionTextureBase\_\_**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[__tid_MaterialExpressionTextureBase__](ue_ue.MaterialExpressionTextureSampleParameter2D.md#__tid_materialexpressiontexturebase__)

___

### \_\_tid\_MaterialExpressionTextureSampleParameter2D\_\_

• **\_\_tid\_MaterialExpressionTextureSampleParameter2D\_\_**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[__tid_MaterialExpressionTextureSampleParameter2D__](ue_ue.MaterialExpressionTextureSampleParameter2D.md#__tid_materialexpressiontexturesampleparameter2d__)

___

### \_\_tid\_MaterialExpressionTextureSampleParameter\_\_

• **\_\_tid\_MaterialExpressionTextureSampleParameter\_\_**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[__tid_MaterialExpressionTextureSampleParameter__](ue_ue.MaterialExpressionTextureSampleParameter2D.md#__tid_materialexpressiontexturesampleparameter__)

___

### \_\_tid\_MaterialExpressionTextureSample\_\_

• **\_\_tid\_MaterialExpressionTextureSample\_\_**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[__tid_MaterialExpressionTextureSample__](ue_ue.MaterialExpressionTextureSampleParameter2D.md#__tid_materialexpressiontexturesample__)

___

### \_\_tid\_MaterialExpression\_\_

• **\_\_tid\_MaterialExpression\_\_**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[__tid_MaterialExpression__](ue_ue.MaterialExpressionTextureSampleParameter2D.md#__tid_materialexpression__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[__tid_Object__](ue_ue.MaterialExpressionTextureSampleParameter2D.md#__tid_object__)

___

### bCollapsed

• **bCollapsed**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[bCollapsed](ue_ue.MaterialExpressionTextureSampleParameter2D.md#bcollapsed)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[bCommentBubbleVisible](ue_ue.MaterialExpressionTextureSampleParameter2D.md#bcommentbubblevisible)

___

### bHidePreviewWindow

• **bHidePreviewWindow**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[bHidePreviewWindow](ue_ue.MaterialExpressionTextureSampleParameter2D.md#bhidepreviewwindow)

___

### bIsParameterExpression

• **bIsParameterExpression**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[bIsParameterExpression](ue_ue.MaterialExpressionTextureSampleParameter2D.md#bisparameterexpression)

___

### bNeedToUpdatePreview

• **bNeedToUpdatePreview**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[bNeedToUpdatePreview](ue_ue.MaterialExpressionTextureSampleParameter2D.md#bneedtoupdatepreview)

___

### bRealtimePreview

• **bRealtimePreview**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[bRealtimePreview](ue_ue.MaterialExpressionTextureSampleParameter2D.md#brealtimepreview)

___

### bSampleAdditionalTextures

• **bSampleAdditionalTextures**: `boolean`

___

### bShaderInputData

• **bShaderInputData**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[bShaderInputData](ue_ue.MaterialExpressionTextureSampleParameter2D.md#bshaderinputdata)

___

### bShowInputs

• **bShowInputs**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[bShowInputs](ue_ue.MaterialExpressionTextureSampleParameter2D.md#bshowinputs)

___

### bShowMaskColorsOnPin

• **bShowMaskColorsOnPin**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[bShowMaskColorsOnPin](ue_ue.MaterialExpressionTextureSampleParameter2D.md#bshowmaskcolorsonpin)

___

### bShowOutputNameOnPin

• **bShowOutputNameOnPin**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[bShowOutputNameOnPin](ue_ue.MaterialExpressionTextureSampleParameter2D.md#bshowoutputnameonpin)

___

### bShowOutputs

• **bShowOutputs**: `boolean`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[bShowOutputs](ue_ue.MaterialExpressionTextureSampleParameter2D.md#bshowoutputs)

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

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[CreateDefaultSubobject](ue_ue.MaterialExpressionTextureSampleParameter2D.md#createdefaultsubobject)

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

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[ExecuteUbergraph](ue_ue.MaterialExpressionTextureSampleParameter2D.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[GetClass](ue_ue.MaterialExpressionTextureSampleParameter2D.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[GetName](ue_ue.MaterialExpressionTextureSampleParameter2D.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[GetOuter](ue_ue.MaterialExpressionTextureSampleParameter2D.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[GetWorld](ue_ue.MaterialExpressionTextureSampleParameter2D.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialExpressionSpriteTextureSampler`](ue_ue.MaterialExpressionSpriteTextureSampler.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialExpressionSpriteTextureSampler`](ue_ue.MaterialExpressionSpriteTextureSampler.md)

#### Overrides

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[Find](ue_ue.MaterialExpressionTextureSampleParameter2D.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialExpressionSpriteTextureSampler`](ue_ue.MaterialExpressionSpriteTextureSampler.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialExpressionSpriteTextureSampler`](ue_ue.MaterialExpressionSpriteTextureSampler.md)

#### Overrides

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[Load](ue_ue.MaterialExpressionTextureSampleParameter2D.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialExpressionTextureSampleParameter2D](ue_ue.MaterialExpressionTextureSampleParameter2D.md).[StaticClass](ue_ue.MaterialExpressionTextureSampleParameter2D.md#staticclass)
