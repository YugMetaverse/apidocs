[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialExpressionMaterialAttributeLayers

# Class: MaterialExpressionMaterialAttributeLayers

[ue/ue](../modules/ue_ue.md).MaterialExpressionMaterialAttributeLayers

## Hierarchy

- [`MaterialExpression`](ue_ue.MaterialExpression.md)

  ↳ **`MaterialExpressionMaterialAttributeLayers`**

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialExpressionMaterialAttributeLayers.md#constructor)

### Properties

- [BlendCallers](ue_ue.MaterialExpressionMaterialAttributeLayers.md#blendcallers)
- [DefaultLayers](ue_ue.MaterialExpressionMaterialAttributeLayers.md#defaultlayers)
- [Desc](ue_ue.MaterialExpressionMaterialAttributeLayers.md#desc)
- [ExpressionGUID](ue_ue.MaterialExpressionMaterialAttributeLayers.md#expressionguid)
- [Function](ue_ue.MaterialExpressionMaterialAttributeLayers.md#function)
- [GraphNode](ue_ue.MaterialExpressionMaterialAttributeLayers.md#graphnode)
- [Input](ue_ue.MaterialExpressionMaterialAttributeLayers.md#input)
- [LayerCallers](ue_ue.MaterialExpressionMaterialAttributeLayers.md#layercallers)
- [Material](ue_ue.MaterialExpressionMaterialAttributeLayers.md#material)
- [MaterialExpressionEditorX](ue_ue.MaterialExpressionMaterialAttributeLayers.md#materialexpressioneditorx)
- [MaterialExpressionEditorY](ue_ue.MaterialExpressionMaterialAttributeLayers.md#materialexpressioneditory)
- [MaterialExpressionGuid](ue_ue.MaterialExpressionMaterialAttributeLayers.md#materialexpressionguid)
- [MenuCategories](ue_ue.MaterialExpressionMaterialAttributeLayers.md#menucategories)
- [NumActiveBlendCallers](ue_ue.MaterialExpressionMaterialAttributeLayers.md#numactiveblendcallers)
- [NumActiveLayerCallers](ue_ue.MaterialExpressionMaterialAttributeLayers.md#numactivelayercallers)
- [Outputs](ue_ue.MaterialExpressionMaterialAttributeLayers.md#outputs)
- [ParameterName](ue_ue.MaterialExpressionMaterialAttributeLayers.md#parametername)
- [\_\_tid\_MaterialExpressionMaterialAttributeLayers\_\_](ue_ue.MaterialExpressionMaterialAttributeLayers.md#__tid_materialexpressionmaterialattributelayers__)
- [\_\_tid\_MaterialExpression\_\_](ue_ue.MaterialExpressionMaterialAttributeLayers.md#__tid_materialexpression__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialExpressionMaterialAttributeLayers.md#__tid_object__)
- [bCollapsed](ue_ue.MaterialExpressionMaterialAttributeLayers.md#bcollapsed)
- [bCommentBubbleVisible](ue_ue.MaterialExpressionMaterialAttributeLayers.md#bcommentbubblevisible)
- [bHidePreviewWindow](ue_ue.MaterialExpressionMaterialAttributeLayers.md#bhidepreviewwindow)
- [bIsLayerGraphBuilt](ue_ue.MaterialExpressionMaterialAttributeLayers.md#bislayergraphbuilt)
- [bIsParameterExpression](ue_ue.MaterialExpressionMaterialAttributeLayers.md#bisparameterexpression)
- [bNeedToUpdatePreview](ue_ue.MaterialExpressionMaterialAttributeLayers.md#bneedtoupdatepreview)
- [bRealtimePreview](ue_ue.MaterialExpressionMaterialAttributeLayers.md#brealtimepreview)
- [bShaderInputData](ue_ue.MaterialExpressionMaterialAttributeLayers.md#bshaderinputdata)
- [bShowInputs](ue_ue.MaterialExpressionMaterialAttributeLayers.md#bshowinputs)
- [bShowMaskColorsOnPin](ue_ue.MaterialExpressionMaterialAttributeLayers.md#bshowmaskcolorsonpin)
- [bShowOutputNameOnPin](ue_ue.MaterialExpressionMaterialAttributeLayers.md#bshowoutputnameonpin)
- [bShowOutputs](ue_ue.MaterialExpressionMaterialAttributeLayers.md#bshowoutputs)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialExpressionMaterialAttributeLayers.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialExpressionMaterialAttributeLayers.md#executeubergraph)
- [GetClass](ue_ue.MaterialExpressionMaterialAttributeLayers.md#getclass)
- [GetName](ue_ue.MaterialExpressionMaterialAttributeLayers.md#getname)
- [GetOuter](ue_ue.MaterialExpressionMaterialAttributeLayers.md#getouter)
- [GetWorld](ue_ue.MaterialExpressionMaterialAttributeLayers.md#getworld)
- [Find](ue_ue.MaterialExpressionMaterialAttributeLayers.md#find)
- [Load](ue_ue.MaterialExpressionMaterialAttributeLayers.md#load)
- [StaticClass](ue_ue.MaterialExpressionMaterialAttributeLayers.md#staticclass)

## Constructors

### constructor

• **new MaterialExpressionMaterialAttributeLayers**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[constructor](ue_ue.MaterialExpression.md#constructor)

#### Defined in

[ue/ue.d.ts:48625](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48625)

## Properties

### BlendCallers

• **BlendCallers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialExpressionMaterialFunctionCall`](ue_ue.MaterialExpressionMaterialFunctionCall.md)\>

#### Defined in

[ue/ue.d.ts:48632](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48632)

___

### DefaultLayers

• **DefaultLayers**: [`MaterialLayersFunctions`](ue_ue.MaterialLayersFunctions.md)

#### Defined in

[ue/ue.d.ts:48629](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48629)

___

### Desc

• **Desc**: `string`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Desc](ue_ue.MaterialExpression.md#desc)

#### Defined in

[ue/ue.d.ts:1163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1163)

___

### ExpressionGUID

• **ExpressionGUID**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:48627](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48627)

___

### Function

• **Function**: [`MaterialFunction`](ue_ue.MaterialFunction.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Function](ue_ue.MaterialExpression.md#function)

#### Defined in

[ue/ue.d.ts:1162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1162)

___

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[GraphNode](ue_ue.MaterialExpression.md#graphnode)

#### Defined in

[ue/ue.d.ts:1159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1159)

___

### Input

• **Input**: [`MaterialAttributesInput`](ue_ue.MaterialAttributesInput.md)

#### Defined in

[ue/ue.d.ts:48628](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48628)

___

### LayerCallers

• **LayerCallers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialExpressionMaterialFunctionCall`](ue_ue.MaterialExpressionMaterialFunctionCall.md)\>

#### Defined in

[ue/ue.d.ts:48630](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48630)

___

### Material

• **Material**: [`Material`](ue_ue.Material.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Material](ue_ue.MaterialExpression.md#material)

#### Defined in

[ue/ue.d.ts:1161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1161)

___

### MaterialExpressionEditorX

• **MaterialExpressionEditorX**: `number`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[MaterialExpressionEditorX](ue_ue.MaterialExpression.md#materialexpressioneditorx)

#### Defined in

[ue/ue.d.ts:1157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1157)

___

### MaterialExpressionEditorY

• **MaterialExpressionEditorY**: `number`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[MaterialExpressionEditorY](ue_ue.MaterialExpression.md#materialexpressioneditory)

#### Defined in

[ue/ue.d.ts:1158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1158)

___

### MaterialExpressionGuid

• **MaterialExpressionGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[MaterialExpressionGuid](ue_ue.MaterialExpression.md#materialexpressionguid)

#### Defined in

[ue/ue.d.ts:1160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1160)

___

### MenuCategories

• **MenuCategories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[MenuCategories](ue_ue.MaterialExpression.md#menucategories)

#### Defined in

[ue/ue.d.ts:1175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1175)

___

### NumActiveBlendCallers

• **NumActiveBlendCallers**: `number`

#### Defined in

[ue/ue.d.ts:48633](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48633)

___

### NumActiveLayerCallers

• **NumActiveLayerCallers**: `number`

#### Defined in

[ue/ue.d.ts:48631](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48631)

___

### Outputs

• **Outputs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ExpressionOutput`](ue_ue.ExpressionOutput.md)\>

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Outputs](ue_ue.MaterialExpression.md#outputs)

#### Defined in

[ue/ue.d.ts:1176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1176)

___

### ParameterName

• **ParameterName**: `string`

#### Defined in

[ue/ue.d.ts:48626](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48626)

___

### \_\_tid\_MaterialExpressionMaterialAttributeLayers\_\_

• **\_\_tid\_MaterialExpressionMaterialAttributeLayers\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:48639](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48639)

___

### \_\_tid\_MaterialExpression\_\_

• **\_\_tid\_MaterialExpression\_\_**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[__tid_MaterialExpression__](ue_ue.MaterialExpression.md#__tid_materialexpression__)

#### Defined in

[ue/ue.d.ts:1181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1181)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[__tid_Object__](ue_ue.MaterialExpression.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bCollapsed

• **bCollapsed**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bCollapsed](ue_ue.MaterialExpression.md#bcollapsed)

#### Defined in

[ue/ue.d.ts:1171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1171)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bCommentBubbleVisible](ue_ue.MaterialExpression.md#bcommentbubblevisible)

#### Defined in

[ue/ue.d.ts:1167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1167)

___

### bHidePreviewWindow

• **bHidePreviewWindow**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bHidePreviewWindow](ue_ue.MaterialExpression.md#bhidepreviewwindow)

#### Defined in

[ue/ue.d.ts:1170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1170)

___

### bIsLayerGraphBuilt

• **bIsLayerGraphBuilt**: `boolean`

#### Defined in

[ue/ue.d.ts:48634](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48634)

___

### bIsParameterExpression

• **bIsParameterExpression**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bIsParameterExpression](ue_ue.MaterialExpression.md#bisparameterexpression)

#### Defined in

[ue/ue.d.ts:1166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1166)

___

### bNeedToUpdatePreview

• **bNeedToUpdatePreview**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bNeedToUpdatePreview](ue_ue.MaterialExpression.md#bneedtoupdatepreview)

#### Defined in

[ue/ue.d.ts:1165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1165)

___

### bRealtimePreview

• **bRealtimePreview**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bRealtimePreview](ue_ue.MaterialExpression.md#brealtimepreview)

#### Defined in

[ue/ue.d.ts:1164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1164)

___

### bShaderInputData

• **bShaderInputData**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bShaderInputData](ue_ue.MaterialExpression.md#bshaderinputdata)

#### Defined in

[ue/ue.d.ts:1172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1172)

___

### bShowInputs

• **bShowInputs**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bShowInputs](ue_ue.MaterialExpression.md#bshowinputs)

#### Defined in

[ue/ue.d.ts:1173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1173)

___

### bShowMaskColorsOnPin

• **bShowMaskColorsOnPin**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bShowMaskColorsOnPin](ue_ue.MaterialExpression.md#bshowmaskcolorsonpin)

#### Defined in

[ue/ue.d.ts:1169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1169)

___

### bShowOutputNameOnPin

• **bShowOutputNameOnPin**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bShowOutputNameOnPin](ue_ue.MaterialExpression.md#bshowoutputnameonpin)

#### Defined in

[ue/ue.d.ts:1168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1168)

___

### bShowOutputs

• **bShowOutputs**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bShowOutputs](ue_ue.MaterialExpression.md#bshowoutputs)

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

[MaterialExpression](ue_ue.MaterialExpression.md).[CreateDefaultSubobject](ue_ue.MaterialExpression.md#createdefaultsubobject)

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

[MaterialExpression](ue_ue.MaterialExpression.md).[ExecuteUbergraph](ue_ue.MaterialExpression.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[GetClass](ue_ue.MaterialExpression.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[GetName](ue_ue.MaterialExpression.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[GetOuter](ue_ue.MaterialExpression.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[GetWorld](ue_ue.MaterialExpression.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialExpressionMaterialAttributeLayers`](ue_ue.MaterialExpressionMaterialAttributeLayers.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialExpressionMaterialAttributeLayers`](ue_ue.MaterialExpressionMaterialAttributeLayers.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[Find](ue_ue.MaterialExpression.md#find)

#### Defined in

[ue/ue.d.ts:48636](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48636)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialExpressionMaterialAttributeLayers`](ue_ue.MaterialExpressionMaterialAttributeLayers.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialExpressionMaterialAttributeLayers`](ue_ue.MaterialExpressionMaterialAttributeLayers.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[Load](ue_ue.MaterialExpression.md#load)

#### Defined in

[ue/ue.d.ts:48637](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48637)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[StaticClass](ue_ue.MaterialExpression.md#staticclass)

#### Defined in

[ue/ue.d.ts:48635](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48635)
