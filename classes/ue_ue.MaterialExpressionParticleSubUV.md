[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialExpressionParticleSubUV

# Class: MaterialExpressionParticleSubUV

[ue/ue](../modules/ue_ue.md).MaterialExpressionParticleSubUV

## Hierarchy

- [`MaterialExpressionTextureSample`](ue_ue.MaterialExpressionTextureSample.md)

  ↳ **`MaterialExpressionParticleSubUV`**

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialExpressionParticleSubUV.md#constructor)

### Properties

- [AutomaticViewMipBias](ue_ue.MaterialExpressionParticleSubUV.md#automaticviewmipbias)
- [AutomaticViewMipBiasValue](ue_ue.MaterialExpressionParticleSubUV.md#automaticviewmipbiasvalue)
- [ConstCoordinate](ue_ue.MaterialExpressionParticleSubUV.md#constcoordinate)
- [ConstMipValue](ue_ue.MaterialExpressionParticleSubUV.md#constmipvalue)
- [Coordinates](ue_ue.MaterialExpressionParticleSubUV.md#coordinates)
- [CoordinatesDX](ue_ue.MaterialExpressionParticleSubUV.md#coordinatesdx)
- [CoordinatesDY](ue_ue.MaterialExpressionParticleSubUV.md#coordinatesdy)
- [Desc](ue_ue.MaterialExpressionParticleSubUV.md#desc)
- [Function](ue_ue.MaterialExpressionParticleSubUV.md#function)
- [GraphNode](ue_ue.MaterialExpressionParticleSubUV.md#graphnode)
- [IsDefaultMeshpaintTexture](ue_ue.MaterialExpressionParticleSubUV.md#isdefaultmeshpainttexture)
- [Material](ue_ue.MaterialExpressionParticleSubUV.md#material)
- [MaterialExpressionEditorX](ue_ue.MaterialExpressionParticleSubUV.md#materialexpressioneditorx)
- [MaterialExpressionEditorY](ue_ue.MaterialExpressionParticleSubUV.md#materialexpressioneditory)
- [MaterialExpressionGuid](ue_ue.MaterialExpressionParticleSubUV.md#materialexpressionguid)
- [MenuCategories](ue_ue.MaterialExpressionParticleSubUV.md#menucategories)
- [MipValue](ue_ue.MaterialExpressionParticleSubUV.md#mipvalue)
- [MipValueMode](ue_ue.MaterialExpressionParticleSubUV.md#mipvaluemode)
- [Outputs](ue_ue.MaterialExpressionParticleSubUV.md#outputs)
- [SamplerSource](ue_ue.MaterialExpressionParticleSubUV.md#samplersource)
- [SamplerType](ue_ue.MaterialExpressionParticleSubUV.md#samplertype)
- [Texture](ue_ue.MaterialExpressionParticleSubUV.md#texture)
- [TextureObject](ue_ue.MaterialExpressionParticleSubUV.md#textureobject)
- [\_\_tid\_MaterialExpressionParticleSubUV\_\_](ue_ue.MaterialExpressionParticleSubUV.md#__tid_materialexpressionparticlesubuv__)
- [\_\_tid\_MaterialExpressionTextureBase\_\_](ue_ue.MaterialExpressionParticleSubUV.md#__tid_materialexpressiontexturebase__)
- [\_\_tid\_MaterialExpressionTextureSample\_\_](ue_ue.MaterialExpressionParticleSubUV.md#__tid_materialexpressiontexturesample__)
- [\_\_tid\_MaterialExpression\_\_](ue_ue.MaterialExpressionParticleSubUV.md#__tid_materialexpression__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialExpressionParticleSubUV.md#__tid_object__)
- [bBlend](ue_ue.MaterialExpressionParticleSubUV.md#bblend)
- [bCollapsed](ue_ue.MaterialExpressionParticleSubUV.md#bcollapsed)
- [bCommentBubbleVisible](ue_ue.MaterialExpressionParticleSubUV.md#bcommentbubblevisible)
- [bHidePreviewWindow](ue_ue.MaterialExpressionParticleSubUV.md#bhidepreviewwindow)
- [bIsParameterExpression](ue_ue.MaterialExpressionParticleSubUV.md#bisparameterexpression)
- [bNeedToUpdatePreview](ue_ue.MaterialExpressionParticleSubUV.md#bneedtoupdatepreview)
- [bRealtimePreview](ue_ue.MaterialExpressionParticleSubUV.md#brealtimepreview)
- [bShaderInputData](ue_ue.MaterialExpressionParticleSubUV.md#bshaderinputdata)
- [bShowInputs](ue_ue.MaterialExpressionParticleSubUV.md#bshowinputs)
- [bShowMaskColorsOnPin](ue_ue.MaterialExpressionParticleSubUV.md#bshowmaskcolorsonpin)
- [bShowOutputNameOnPin](ue_ue.MaterialExpressionParticleSubUV.md#bshowoutputnameonpin)
- [bShowOutputs](ue_ue.MaterialExpressionParticleSubUV.md#bshowoutputs)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialExpressionParticleSubUV.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialExpressionParticleSubUV.md#executeubergraph)
- [GetClass](ue_ue.MaterialExpressionParticleSubUV.md#getclass)
- [GetName](ue_ue.MaterialExpressionParticleSubUV.md#getname)
- [GetOuter](ue_ue.MaterialExpressionParticleSubUV.md#getouter)
- [GetWorld](ue_ue.MaterialExpressionParticleSubUV.md#getworld)
- [Find](ue_ue.MaterialExpressionParticleSubUV.md#find)
- [Load](ue_ue.MaterialExpressionParticleSubUV.md#load)
- [StaticClass](ue_ue.MaterialExpressionParticleSubUV.md#staticclass)

## Constructors

### constructor

• **new MaterialExpressionParticleSubUV**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[constructor](ue_ue.MaterialExpressionTextureSample.md#constructor)

#### Defined in

[ue/ue.d.ts:48885](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48885)

## Properties

### AutomaticViewMipBias

• **AutomaticViewMipBias**: `boolean`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[AutomaticViewMipBias](ue_ue.MaterialExpressionTextureSample.md#automaticviewmipbias)

#### Defined in

[ue/ue.d.ts:47533](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47533)

___

### AutomaticViewMipBiasValue

• **AutomaticViewMipBiasValue**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[AutomaticViewMipBiasValue](ue_ue.MaterialExpressionTextureSample.md#automaticviewmipbiasvalue)

#### Defined in

[ue/ue.d.ts:47530](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47530)

___

### ConstCoordinate

• **ConstCoordinate**: `number`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[ConstCoordinate](ue_ue.MaterialExpressionTextureSample.md#constcoordinate)

#### Defined in

[ue/ue.d.ts:47534](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47534)

___

### ConstMipValue

• **ConstMipValue**: `number`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[ConstMipValue](ue_ue.MaterialExpressionTextureSample.md#constmipvalue)

#### Defined in

[ue/ue.d.ts:47535](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47535)

___

### Coordinates

• **Coordinates**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[Coordinates](ue_ue.MaterialExpressionTextureSample.md#coordinates)

#### Defined in

[ue/ue.d.ts:47525](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47525)

___

### CoordinatesDX

• **CoordinatesDX**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[CoordinatesDX](ue_ue.MaterialExpressionTextureSample.md#coordinatesdx)

#### Defined in

[ue/ue.d.ts:47528](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47528)

___

### CoordinatesDY

• **CoordinatesDY**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[CoordinatesDY](ue_ue.MaterialExpressionTextureSample.md#coordinatesdy)

#### Defined in

[ue/ue.d.ts:47529](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47529)

___

### Desc

• **Desc**: `string`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[Desc](ue_ue.MaterialExpressionTextureSample.md#desc)

#### Defined in

[ue/ue.d.ts:1163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1163)

___

### Function

• **Function**: [`MaterialFunction`](ue_ue.MaterialFunction.md)

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[Function](ue_ue.MaterialExpressionTextureSample.md#function)

#### Defined in

[ue/ue.d.ts:1162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1162)

___

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[GraphNode](ue_ue.MaterialExpressionTextureSample.md#graphnode)

#### Defined in

[ue/ue.d.ts:1159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1159)

___

### IsDefaultMeshpaintTexture

• **IsDefaultMeshpaintTexture**: `boolean`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[IsDefaultMeshpaintTexture](ue_ue.MaterialExpressionTextureSample.md#isdefaultmeshpainttexture)

#### Defined in

[ue/ue.d.ts:47515](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47515)

___

### Material

• **Material**: [`Material`](ue_ue.Material.md)

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[Material](ue_ue.MaterialExpressionTextureSample.md#material)

#### Defined in

[ue/ue.d.ts:1161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1161)

___

### MaterialExpressionEditorX

• **MaterialExpressionEditorX**: `number`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[MaterialExpressionEditorX](ue_ue.MaterialExpressionTextureSample.md#materialexpressioneditorx)

#### Defined in

[ue/ue.d.ts:1157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1157)

___

### MaterialExpressionEditorY

• **MaterialExpressionEditorY**: `number`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[MaterialExpressionEditorY](ue_ue.MaterialExpressionTextureSample.md#materialexpressioneditory)

#### Defined in

[ue/ue.d.ts:1158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1158)

___

### MaterialExpressionGuid

• **MaterialExpressionGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[MaterialExpressionGuid](ue_ue.MaterialExpressionTextureSample.md#materialexpressionguid)

#### Defined in

[ue/ue.d.ts:1160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1160)

___

### MenuCategories

• **MenuCategories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[MenuCategories](ue_ue.MaterialExpressionTextureSample.md#menucategories)

#### Defined in

[ue/ue.d.ts:1175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1175)

___

### MipValue

• **MipValue**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[MipValue](ue_ue.MaterialExpressionTextureSample.md#mipvalue)

#### Defined in

[ue/ue.d.ts:47527](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47527)

___

### MipValueMode

• **MipValueMode**: [`ETextureMipValueMode`](../enums/ue_ue.ETextureMipValueMode.md)

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[MipValueMode](ue_ue.MaterialExpressionTextureSample.md#mipvaluemode)

#### Defined in

[ue/ue.d.ts:47531](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47531)

___

### Outputs

• **Outputs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ExpressionOutput`](ue_ue.ExpressionOutput.md)\>

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[Outputs](ue_ue.MaterialExpressionTextureSample.md#outputs)

#### Defined in

[ue/ue.d.ts:1176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1176)

___

### SamplerSource

• **SamplerSource**: [`ESamplerSourceMode`](../enums/ue_ue.ESamplerSourceMode.md)

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[SamplerSource](ue_ue.MaterialExpressionTextureSample.md#samplersource)

#### Defined in

[ue/ue.d.ts:47532](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47532)

___

### SamplerType

• **SamplerType**: [`EMaterialSamplerType`](../enums/ue_ue.EMaterialSamplerType.md)

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[SamplerType](ue_ue.MaterialExpressionTextureSample.md#samplertype)

#### Defined in

[ue/ue.d.ts:47514](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47514)

___

### Texture

• **Texture**: [`Texture`](ue_ue.Texture.md)

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[Texture](ue_ue.MaterialExpressionTextureSample.md#texture)

#### Defined in

[ue/ue.d.ts:47513](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47513)

___

### TextureObject

• **TextureObject**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[TextureObject](ue_ue.MaterialExpressionTextureSample.md#textureobject)

#### Defined in

[ue/ue.d.ts:47526](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47526)

___

### \_\_tid\_MaterialExpressionParticleSubUV\_\_

• **\_\_tid\_MaterialExpressionParticleSubUV\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:48891](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48891)

___

### \_\_tid\_MaterialExpressionTextureBase\_\_

• **\_\_tid\_MaterialExpressionTextureBase\_\_**: `boolean`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[__tid_MaterialExpressionTextureBase__](ue_ue.MaterialExpressionTextureSample.md#__tid_materialexpressiontexturebase__)

#### Defined in

[ue/ue.d.ts:47520](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47520)

___

### \_\_tid\_MaterialExpressionTextureSample\_\_

• **\_\_tid\_MaterialExpressionTextureSample\_\_**: `boolean`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[__tid_MaterialExpressionTextureSample__](ue_ue.MaterialExpressionTextureSample.md#__tid_materialexpressiontexturesample__)

#### Defined in

[ue/ue.d.ts:47540](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47540)

___

### \_\_tid\_MaterialExpression\_\_

• **\_\_tid\_MaterialExpression\_\_**: `boolean`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[__tid_MaterialExpression__](ue_ue.MaterialExpressionTextureSample.md#__tid_materialexpression__)

#### Defined in

[ue/ue.d.ts:1181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1181)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[__tid_Object__](ue_ue.MaterialExpressionTextureSample.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bBlend

• **bBlend**: `boolean`

#### Defined in

[ue/ue.d.ts:48886](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48886)

___

### bCollapsed

• **bCollapsed**: `boolean`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[bCollapsed](ue_ue.MaterialExpressionTextureSample.md#bcollapsed)

#### Defined in

[ue/ue.d.ts:1171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1171)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[bCommentBubbleVisible](ue_ue.MaterialExpressionTextureSample.md#bcommentbubblevisible)

#### Defined in

[ue/ue.d.ts:1167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1167)

___

### bHidePreviewWindow

• **bHidePreviewWindow**: `boolean`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[bHidePreviewWindow](ue_ue.MaterialExpressionTextureSample.md#bhidepreviewwindow)

#### Defined in

[ue/ue.d.ts:1170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1170)

___

### bIsParameterExpression

• **bIsParameterExpression**: `boolean`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[bIsParameterExpression](ue_ue.MaterialExpressionTextureSample.md#bisparameterexpression)

#### Defined in

[ue/ue.d.ts:1166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1166)

___

### bNeedToUpdatePreview

• **bNeedToUpdatePreview**: `boolean`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[bNeedToUpdatePreview](ue_ue.MaterialExpressionTextureSample.md#bneedtoupdatepreview)

#### Defined in

[ue/ue.d.ts:1165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1165)

___

### bRealtimePreview

• **bRealtimePreview**: `boolean`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[bRealtimePreview](ue_ue.MaterialExpressionTextureSample.md#brealtimepreview)

#### Defined in

[ue/ue.d.ts:1164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1164)

___

### bShaderInputData

• **bShaderInputData**: `boolean`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[bShaderInputData](ue_ue.MaterialExpressionTextureSample.md#bshaderinputdata)

#### Defined in

[ue/ue.d.ts:1172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1172)

___

### bShowInputs

• **bShowInputs**: `boolean`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[bShowInputs](ue_ue.MaterialExpressionTextureSample.md#bshowinputs)

#### Defined in

[ue/ue.d.ts:1173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1173)

___

### bShowMaskColorsOnPin

• **bShowMaskColorsOnPin**: `boolean`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[bShowMaskColorsOnPin](ue_ue.MaterialExpressionTextureSample.md#bshowmaskcolorsonpin)

#### Defined in

[ue/ue.d.ts:1169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1169)

___

### bShowOutputNameOnPin

• **bShowOutputNameOnPin**: `boolean`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[bShowOutputNameOnPin](ue_ue.MaterialExpressionTextureSample.md#bshowoutputnameonpin)

#### Defined in

[ue/ue.d.ts:1168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1168)

___

### bShowOutputs

• **bShowOutputs**: `boolean`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[bShowOutputs](ue_ue.MaterialExpressionTextureSample.md#bshowoutputs)

#### Defined in

[ue/ue.d.ts:1174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1174)

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

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[CreateDefaultSubobject](ue_ue.MaterialExpressionTextureSample.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[ExecuteUbergraph](ue_ue.MaterialExpressionTextureSample.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[GetClass](ue_ue.MaterialExpressionTextureSample.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[GetName](ue_ue.MaterialExpressionTextureSample.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[GetOuter](ue_ue.MaterialExpressionTextureSample.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[GetWorld](ue_ue.MaterialExpressionTextureSample.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialExpressionParticleSubUV`](ue_ue.MaterialExpressionParticleSubUV.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialExpressionParticleSubUV`](ue_ue.MaterialExpressionParticleSubUV.md)

#### Overrides

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[Find](ue_ue.MaterialExpressionTextureSample.md#find)

#### Defined in

[ue/ue.d.ts:48888](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48888)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialExpressionParticleSubUV`](ue_ue.MaterialExpressionParticleSubUV.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialExpressionParticleSubUV`](ue_ue.MaterialExpressionParticleSubUV.md)

#### Overrides

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[Load](ue_ue.MaterialExpressionTextureSample.md#load)

#### Defined in

[ue/ue.d.ts:48889](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48889)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialExpressionTextureSample](ue_ue.MaterialExpressionTextureSample.md).[StaticClass](ue_ue.MaterialExpressionTextureSample.md#staticclass)

#### Defined in

[ue/ue.d.ts:48887](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48887)