[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialExpressionMakeMaterialAttributes

# Class: MaterialExpressionMakeMaterialAttributes

[ue/ue](../modules/ue_ue.md).MaterialExpressionMakeMaterialAttributes

## Hierarchy

- [`MaterialExpression`](ue_ue.MaterialExpression.md)

  ↳ **`MaterialExpressionMakeMaterialAttributes`**

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialExpressionMakeMaterialAttributes.md#constructor)

### Properties

- [AmbientOcclusion](ue_ue.MaterialExpressionMakeMaterialAttributes.md#ambientocclusion)
- [BaseColor](ue_ue.MaterialExpressionMakeMaterialAttributes.md#basecolor)
- [ClearCoat](ue_ue.MaterialExpressionMakeMaterialAttributes.md#clearcoat)
- [ClearCoatRoughness](ue_ue.MaterialExpressionMakeMaterialAttributes.md#clearcoatroughness)
- [CustomizedUVs](ue_ue.MaterialExpressionMakeMaterialAttributes.md#customizeduvs)
- [Desc](ue_ue.MaterialExpressionMakeMaterialAttributes.md#desc)
- [EmissiveColor](ue_ue.MaterialExpressionMakeMaterialAttributes.md#emissivecolor)
- [Function](ue_ue.MaterialExpressionMakeMaterialAttributes.md#function)
- [GraphNode](ue_ue.MaterialExpressionMakeMaterialAttributes.md#graphnode)
- [Material](ue_ue.MaterialExpressionMakeMaterialAttributes.md#material)
- [MaterialExpressionEditorX](ue_ue.MaterialExpressionMakeMaterialAttributes.md#materialexpressioneditorx)
- [MaterialExpressionEditorY](ue_ue.MaterialExpressionMakeMaterialAttributes.md#materialexpressioneditory)
- [MaterialExpressionGuid](ue_ue.MaterialExpressionMakeMaterialAttributes.md#materialexpressionguid)
- [MenuCategories](ue_ue.MaterialExpressionMakeMaterialAttributes.md#menucategories)
- [Metallic](ue_ue.MaterialExpressionMakeMaterialAttributes.md#metallic)
- [Normal](ue_ue.MaterialExpressionMakeMaterialAttributes.md#normal)
- [Opacity](ue_ue.MaterialExpressionMakeMaterialAttributes.md#opacity)
- [OpacityMask](ue_ue.MaterialExpressionMakeMaterialAttributes.md#opacitymask)
- [Outputs](ue_ue.MaterialExpressionMakeMaterialAttributes.md#outputs)
- [PixelDepthOffset](ue_ue.MaterialExpressionMakeMaterialAttributes.md#pixeldepthoffset)
- [Refraction](ue_ue.MaterialExpressionMakeMaterialAttributes.md#refraction)
- [Roughness](ue_ue.MaterialExpressionMakeMaterialAttributes.md#roughness)
- [ShadingModel](ue_ue.MaterialExpressionMakeMaterialAttributes.md#shadingmodel)
- [Specular](ue_ue.MaterialExpressionMakeMaterialAttributes.md#specular)
- [SubsurfaceColor](ue_ue.MaterialExpressionMakeMaterialAttributes.md#subsurfacecolor)
- [TessellationMultiplier](ue_ue.MaterialExpressionMakeMaterialAttributes.md#tessellationmultiplier)
- [WorldDisplacement](ue_ue.MaterialExpressionMakeMaterialAttributes.md#worlddisplacement)
- [WorldPositionOffset](ue_ue.MaterialExpressionMakeMaterialAttributes.md#worldpositionoffset)
- [\_\_tid\_MaterialExpressionMakeMaterialAttributes\_\_](ue_ue.MaterialExpressionMakeMaterialAttributes.md#__tid_materialexpressionmakematerialattributes__)
- [\_\_tid\_MaterialExpression\_\_](ue_ue.MaterialExpressionMakeMaterialAttributes.md#__tid_materialexpression__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialExpressionMakeMaterialAttributes.md#__tid_object__)
- [bCollapsed](ue_ue.MaterialExpressionMakeMaterialAttributes.md#bcollapsed)
- [bCommentBubbleVisible](ue_ue.MaterialExpressionMakeMaterialAttributes.md#bcommentbubblevisible)
- [bHidePreviewWindow](ue_ue.MaterialExpressionMakeMaterialAttributes.md#bhidepreviewwindow)
- [bIsParameterExpression](ue_ue.MaterialExpressionMakeMaterialAttributes.md#bisparameterexpression)
- [bNeedToUpdatePreview](ue_ue.MaterialExpressionMakeMaterialAttributes.md#bneedtoupdatepreview)
- [bRealtimePreview](ue_ue.MaterialExpressionMakeMaterialAttributes.md#brealtimepreview)
- [bShaderInputData](ue_ue.MaterialExpressionMakeMaterialAttributes.md#bshaderinputdata)
- [bShowInputs](ue_ue.MaterialExpressionMakeMaterialAttributes.md#bshowinputs)
- [bShowMaskColorsOnPin](ue_ue.MaterialExpressionMakeMaterialAttributes.md#bshowmaskcolorsonpin)
- [bShowOutputNameOnPin](ue_ue.MaterialExpressionMakeMaterialAttributes.md#bshowoutputnameonpin)
- [bShowOutputs](ue_ue.MaterialExpressionMakeMaterialAttributes.md#bshowoutputs)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialExpressionMakeMaterialAttributes.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialExpressionMakeMaterialAttributes.md#executeubergraph)
- [GetClass](ue_ue.MaterialExpressionMakeMaterialAttributes.md#getclass)
- [GetName](ue_ue.MaterialExpressionMakeMaterialAttributes.md#getname)
- [GetOuter](ue_ue.MaterialExpressionMakeMaterialAttributes.md#getouter)
- [GetWorld](ue_ue.MaterialExpressionMakeMaterialAttributes.md#getworld)
- [Find](ue_ue.MaterialExpressionMakeMaterialAttributes.md#find)
- [Load](ue_ue.MaterialExpressionMakeMaterialAttributes.md#load)
- [StaticClass](ue_ue.MaterialExpressionMakeMaterialAttributes.md#staticclass)

## Constructors

### constructor

• **new MaterialExpressionMakeMaterialAttributes**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[constructor](ue_ue.MaterialExpression.md#constructor)

#### Defined in

[ue/ue.d.ts:48545](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48545)

## Properties

### AmbientOcclusion

• **AmbientOcclusion**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48560](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48560)

___

### BaseColor

• **BaseColor**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48546](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48546)

___

### ClearCoat

• **ClearCoat**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48558](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48558)

___

### ClearCoatRoughness

• **ClearCoatRoughness**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48559](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48559)

___

### CustomizedUVs

• **CustomizedUVs**: [`FixSizeArray`](../interfaces/ue_puerts.FixSizeArray.md)<[`ExpressionInput`](ue_ue.ExpressionInput.md)\>

#### Defined in

[ue/ue.d.ts:48562](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48562)

___

### Desc

• **Desc**: `string`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Desc](ue_ue.MaterialExpression.md#desc)

#### Defined in

[ue/ue.d.ts:1163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1163)

___

### EmissiveColor

• **EmissiveColor**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48550](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48550)

___

### Function

• **Function**: [`MaterialFunction`](ue_ue.MaterialFunction.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Function](ue_ue.MaterialExpression.md#function)

#### Defined in

[ue/ue.d.ts:1162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1162)

___

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[GraphNode](ue_ue.MaterialExpression.md#graphnode)

#### Defined in

[ue/ue.d.ts:1159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1159)

___

### Material

• **Material**: [`Material`](ue_ue.Material.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Material](ue_ue.MaterialExpression.md#material)

#### Defined in

[ue/ue.d.ts:1161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1161)

___

### MaterialExpressionEditorX

• **MaterialExpressionEditorX**: `number`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[MaterialExpressionEditorX](ue_ue.MaterialExpression.md#materialexpressioneditorx)

#### Defined in

[ue/ue.d.ts:1157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1157)

___

### MaterialExpressionEditorY

• **MaterialExpressionEditorY**: `number`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[MaterialExpressionEditorY](ue_ue.MaterialExpression.md#materialexpressioneditory)

#### Defined in

[ue/ue.d.ts:1158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1158)

___

### MaterialExpressionGuid

• **MaterialExpressionGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[MaterialExpressionGuid](ue_ue.MaterialExpression.md#materialexpressionguid)

#### Defined in

[ue/ue.d.ts:1160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1160)

___

### MenuCategories

• **MenuCategories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[MenuCategories](ue_ue.MaterialExpression.md#menucategories)

#### Defined in

[ue/ue.d.ts:1175](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1175)

___

### Metallic

• **Metallic**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48547](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48547)

___

### Normal

• **Normal**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48553](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48553)

___

### Opacity

• **Opacity**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48551](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48551)

___

### OpacityMask

• **OpacityMask**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48552](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48552)

___

### Outputs

• **Outputs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ExpressionOutput`](ue_ue.ExpressionOutput.md)\>

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Outputs](ue_ue.MaterialExpression.md#outputs)

#### Defined in

[ue/ue.d.ts:1176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1176)

___

### PixelDepthOffset

• **PixelDepthOffset**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48563](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48563)

___

### Refraction

• **Refraction**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48561](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48561)

___

### Roughness

• **Roughness**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48549](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48549)

___

### ShadingModel

• **ShadingModel**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48564](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48564)

___

### Specular

• **Specular**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48548](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48548)

___

### SubsurfaceColor

• **SubsurfaceColor**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48557](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48557)

___

### TessellationMultiplier

• **TessellationMultiplier**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48556)

___

### WorldDisplacement

• **WorldDisplacement**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48555](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48555)

___

### WorldPositionOffset

• **WorldPositionOffset**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48554](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48554)

___

### \_\_tid\_MaterialExpressionMakeMaterialAttributes\_\_

• **\_\_tid\_MaterialExpressionMakeMaterialAttributes\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:48569](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48569)

___

### \_\_tid\_MaterialExpression\_\_

• **\_\_tid\_MaterialExpression\_\_**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[__tid_MaterialExpression__](ue_ue.MaterialExpression.md#__tid_materialexpression__)

#### Defined in

[ue/ue.d.ts:1181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1181)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[__tid_Object__](ue_ue.MaterialExpression.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bCollapsed

• **bCollapsed**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bCollapsed](ue_ue.MaterialExpression.md#bcollapsed)

#### Defined in

[ue/ue.d.ts:1171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1171)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bCommentBubbleVisible](ue_ue.MaterialExpression.md#bcommentbubblevisible)

#### Defined in

[ue/ue.d.ts:1167](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1167)

___

### bHidePreviewWindow

• **bHidePreviewWindow**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bHidePreviewWindow](ue_ue.MaterialExpression.md#bhidepreviewwindow)

#### Defined in

[ue/ue.d.ts:1170](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1170)

___

### bIsParameterExpression

• **bIsParameterExpression**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bIsParameterExpression](ue_ue.MaterialExpression.md#bisparameterexpression)

#### Defined in

[ue/ue.d.ts:1166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1166)

___

### bNeedToUpdatePreview

• **bNeedToUpdatePreview**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bNeedToUpdatePreview](ue_ue.MaterialExpression.md#bneedtoupdatepreview)

#### Defined in

[ue/ue.d.ts:1165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1165)

___

### bRealtimePreview

• **bRealtimePreview**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bRealtimePreview](ue_ue.MaterialExpression.md#brealtimepreview)

#### Defined in

[ue/ue.d.ts:1164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1164)

___

### bShaderInputData

• **bShaderInputData**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bShaderInputData](ue_ue.MaterialExpression.md#bshaderinputdata)

#### Defined in

[ue/ue.d.ts:1172](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1172)

___

### bShowInputs

• **bShowInputs**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bShowInputs](ue_ue.MaterialExpression.md#bshowinputs)

#### Defined in

[ue/ue.d.ts:1173](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1173)

___

### bShowMaskColorsOnPin

• **bShowMaskColorsOnPin**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bShowMaskColorsOnPin](ue_ue.MaterialExpression.md#bshowmaskcolorsonpin)

#### Defined in

[ue/ue.d.ts:1169](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1169)

___

### bShowOutputNameOnPin

• **bShowOutputNameOnPin**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bShowOutputNameOnPin](ue_ue.MaterialExpression.md#bshowoutputnameonpin)

#### Defined in

[ue/ue.d.ts:1168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1168)

___

### bShowOutputs

• **bShowOutputs**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bShowOutputs](ue_ue.MaterialExpression.md#bshowoutputs)

#### Defined in

[ue/ue.d.ts:1174](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1174)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[GetClass](ue_ue.MaterialExpression.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[GetName](ue_ue.MaterialExpression.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[GetOuter](ue_ue.MaterialExpression.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[GetWorld](ue_ue.MaterialExpression.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialExpressionMakeMaterialAttributes`](ue_ue.MaterialExpressionMakeMaterialAttributes.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialExpressionMakeMaterialAttributes`](ue_ue.MaterialExpressionMakeMaterialAttributes.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[Find](ue_ue.MaterialExpression.md#find)

#### Defined in

[ue/ue.d.ts:48566](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48566)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialExpressionMakeMaterialAttributes`](ue_ue.MaterialExpressionMakeMaterialAttributes.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialExpressionMakeMaterialAttributes`](ue_ue.MaterialExpressionMakeMaterialAttributes.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[Load](ue_ue.MaterialExpression.md#load)

#### Defined in

[ue/ue.d.ts:48567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48567)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[StaticClass](ue_ue.MaterialExpression.md#staticclass)

#### Defined in

[ue/ue.d.ts:48565](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L48565)
