[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialExpressionVectorParameter

# Class: MaterialExpressionVectorParameter

[ue/ue](../modules/ue_ue.md).MaterialExpressionVectorParameter

## Hierarchy

- [`MaterialExpressionParameter`](ue_ue.MaterialExpressionParameter.md)

  ↳ **`MaterialExpressionVectorParameter`**

  ↳↳ [`MaterialExpressionChannelMaskParameter`](ue_ue.MaterialExpressionChannelMaskParameter.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialExpressionVectorParameter.md#constructor)

### Properties

- [ChannelNames](ue_ue.MaterialExpressionVectorParameter.md#channelnames)
- [DefaultValue](ue_ue.MaterialExpressionVectorParameter.md#defaultvalue)
- [Desc](ue_ue.MaterialExpressionVectorParameter.md#desc)
- [ExpressionGUID](ue_ue.MaterialExpressionVectorParameter.md#expressionguid)
- [Function](ue_ue.MaterialExpressionVectorParameter.md#function)
- [GraphNode](ue_ue.MaterialExpressionVectorParameter.md#graphnode)
- [Group](ue_ue.MaterialExpressionVectorParameter.md#group)
- [Material](ue_ue.MaterialExpressionVectorParameter.md#material)
- [MaterialExpressionEditorX](ue_ue.MaterialExpressionVectorParameter.md#materialexpressioneditorx)
- [MaterialExpressionEditorY](ue_ue.MaterialExpressionVectorParameter.md#materialexpressioneditory)
- [MaterialExpressionGuid](ue_ue.MaterialExpressionVectorParameter.md#materialexpressionguid)
- [MenuCategories](ue_ue.MaterialExpressionVectorParameter.md#menucategories)
- [Outputs](ue_ue.MaterialExpressionVectorParameter.md#outputs)
- [ParameterName](ue_ue.MaterialExpressionVectorParameter.md#parametername)
- [PrimitiveDataIndex](ue_ue.MaterialExpressionVectorParameter.md#primitivedataindex)
- [SortPriority](ue_ue.MaterialExpressionVectorParameter.md#sortpriority)
- [\_\_tid\_MaterialExpressionParameter\_\_](ue_ue.MaterialExpressionVectorParameter.md#__tid_materialexpressionparameter__)
- [\_\_tid\_MaterialExpressionVectorParameter\_\_](ue_ue.MaterialExpressionVectorParameter.md#__tid_materialexpressionvectorparameter__)
- [\_\_tid\_MaterialExpression\_\_](ue_ue.MaterialExpressionVectorParameter.md#__tid_materialexpression__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialExpressionVectorParameter.md#__tid_object__)
- [bCollapsed](ue_ue.MaterialExpressionVectorParameter.md#bcollapsed)
- [bCommentBubbleVisible](ue_ue.MaterialExpressionVectorParameter.md#bcommentbubblevisible)
- [bHidePreviewWindow](ue_ue.MaterialExpressionVectorParameter.md#bhidepreviewwindow)
- [bIsParameterExpression](ue_ue.MaterialExpressionVectorParameter.md#bisparameterexpression)
- [bNeedToUpdatePreview](ue_ue.MaterialExpressionVectorParameter.md#bneedtoupdatepreview)
- [bRealtimePreview](ue_ue.MaterialExpressionVectorParameter.md#brealtimepreview)
- [bShaderInputData](ue_ue.MaterialExpressionVectorParameter.md#bshaderinputdata)
- [bShowInputs](ue_ue.MaterialExpressionVectorParameter.md#bshowinputs)
- [bShowMaskColorsOnPin](ue_ue.MaterialExpressionVectorParameter.md#bshowmaskcolorsonpin)
- [bShowOutputNameOnPin](ue_ue.MaterialExpressionVectorParameter.md#bshowoutputnameonpin)
- [bShowOutputs](ue_ue.MaterialExpressionVectorParameter.md#bshowoutputs)
- [bUseCustomPrimitiveData](ue_ue.MaterialExpressionVectorParameter.md#busecustomprimitivedata)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialExpressionVectorParameter.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialExpressionVectorParameter.md#executeubergraph)
- [GetClass](ue_ue.MaterialExpressionVectorParameter.md#getclass)
- [GetName](ue_ue.MaterialExpressionVectorParameter.md#getname)
- [GetOuter](ue_ue.MaterialExpressionVectorParameter.md#getouter)
- [GetWorld](ue_ue.MaterialExpressionVectorParameter.md#getworld)
- [Find](ue_ue.MaterialExpressionVectorParameter.md#find)
- [Load](ue_ue.MaterialExpressionVectorParameter.md#load)
- [StaticClass](ue_ue.MaterialExpressionVectorParameter.md#staticclass)

## Constructors

### constructor

• **new MaterialExpressionVectorParameter**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[constructor](ue_ue.MaterialExpressionParameter.md#constructor)

#### Defined in

[ue/ue.d.ts:47808](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47808)

## Properties

### ChannelNames

• **ChannelNames**: [`ParameterChannelNames`](ue_ue.ParameterChannelNames.md)

#### Defined in

[ue/ue.d.ts:47812](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47812)

___

### DefaultValue

• **DefaultValue**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:47809](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47809)

___

### Desc

• **Desc**: `string`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[Desc](ue_ue.MaterialExpressionParameter.md#desc)

#### Defined in

[ue/ue.d.ts:1163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1163)

___

### ExpressionGUID

• **ExpressionGUID**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[ExpressionGUID](ue_ue.MaterialExpressionParameter.md#expressionguid)

#### Defined in

[ue/ue.d.ts:47797](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47797)

___

### Function

• **Function**: [`MaterialFunction`](ue_ue.MaterialFunction.md)

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[Function](ue_ue.MaterialExpressionParameter.md#function)

#### Defined in

[ue/ue.d.ts:1162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1162)

___

### GraphNode

• **GraphNode**: [`EdGraphNode`](ue_ue.EdGraphNode.md)

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[GraphNode](ue_ue.MaterialExpressionParameter.md#graphnode)

#### Defined in

[ue/ue.d.ts:1159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1159)

___

### Group

• **Group**: `string`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[Group](ue_ue.MaterialExpressionParameter.md#group)

#### Defined in

[ue/ue.d.ts:47798](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47798)

___

### Material

• **Material**: [`Material`](ue_ue.Material.md)

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[Material](ue_ue.MaterialExpressionParameter.md#material)

#### Defined in

[ue/ue.d.ts:1161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1161)

___

### MaterialExpressionEditorX

• **MaterialExpressionEditorX**: `number`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[MaterialExpressionEditorX](ue_ue.MaterialExpressionParameter.md#materialexpressioneditorx)

#### Defined in

[ue/ue.d.ts:1157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1157)

___

### MaterialExpressionEditorY

• **MaterialExpressionEditorY**: `number`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[MaterialExpressionEditorY](ue_ue.MaterialExpressionParameter.md#materialexpressioneditory)

#### Defined in

[ue/ue.d.ts:1158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1158)

___

### MaterialExpressionGuid

• **MaterialExpressionGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[MaterialExpressionGuid](ue_ue.MaterialExpressionParameter.md#materialexpressionguid)

#### Defined in

[ue/ue.d.ts:1160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1160)

___

### MenuCategories

• **MenuCategories**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[MenuCategories](ue_ue.MaterialExpressionParameter.md#menucategories)

#### Defined in

[ue/ue.d.ts:1175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1175)

___

### Outputs

• **Outputs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ExpressionOutput`](ue_ue.ExpressionOutput.md)\>

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[Outputs](ue_ue.MaterialExpressionParameter.md#outputs)

#### Defined in

[ue/ue.d.ts:1176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1176)

___

### ParameterName

• **ParameterName**: `string`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[ParameterName](ue_ue.MaterialExpressionParameter.md#parametername)

#### Defined in

[ue/ue.d.ts:47796](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47796)

___

### PrimitiveDataIndex

• **PrimitiveDataIndex**: `number`

#### Defined in

[ue/ue.d.ts:47811](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47811)

___

### SortPriority

• **SortPriority**: `number`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[SortPriority](ue_ue.MaterialExpressionParameter.md#sortpriority)

#### Defined in

[ue/ue.d.ts:47799](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47799)

___

### \_\_tid\_MaterialExpressionParameter\_\_

• **\_\_tid\_MaterialExpressionParameter\_\_**: `boolean`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[__tid_MaterialExpressionParameter__](ue_ue.MaterialExpressionParameter.md#__tid_materialexpressionparameter__)

#### Defined in

[ue/ue.d.ts:47804](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47804)

___

### \_\_tid\_MaterialExpressionVectorParameter\_\_

• **\_\_tid\_MaterialExpressionVectorParameter\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:47817](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47817)

___

### \_\_tid\_MaterialExpression\_\_

• **\_\_tid\_MaterialExpression\_\_**: `boolean`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[__tid_MaterialExpression__](ue_ue.MaterialExpressionParameter.md#__tid_materialexpression__)

#### Defined in

[ue/ue.d.ts:1181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1181)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[__tid_Object__](ue_ue.MaterialExpressionParameter.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bCollapsed

• **bCollapsed**: `boolean`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[bCollapsed](ue_ue.MaterialExpressionParameter.md#bcollapsed)

#### Defined in

[ue/ue.d.ts:1171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1171)

___

### bCommentBubbleVisible

• **bCommentBubbleVisible**: `boolean`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[bCommentBubbleVisible](ue_ue.MaterialExpressionParameter.md#bcommentbubblevisible)

#### Defined in

[ue/ue.d.ts:1167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1167)

___

### bHidePreviewWindow

• **bHidePreviewWindow**: `boolean`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[bHidePreviewWindow](ue_ue.MaterialExpressionParameter.md#bhidepreviewwindow)

#### Defined in

[ue/ue.d.ts:1170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1170)

___

### bIsParameterExpression

• **bIsParameterExpression**: `boolean`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[bIsParameterExpression](ue_ue.MaterialExpressionParameter.md#bisparameterexpression)

#### Defined in

[ue/ue.d.ts:1166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1166)

___

### bNeedToUpdatePreview

• **bNeedToUpdatePreview**: `boolean`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[bNeedToUpdatePreview](ue_ue.MaterialExpressionParameter.md#bneedtoupdatepreview)

#### Defined in

[ue/ue.d.ts:1165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1165)

___

### bRealtimePreview

• **bRealtimePreview**: `boolean`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[bRealtimePreview](ue_ue.MaterialExpressionParameter.md#brealtimepreview)

#### Defined in

[ue/ue.d.ts:1164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1164)

___

### bShaderInputData

• **bShaderInputData**: `boolean`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[bShaderInputData](ue_ue.MaterialExpressionParameter.md#bshaderinputdata)

#### Defined in

[ue/ue.d.ts:1172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1172)

___

### bShowInputs

• **bShowInputs**: `boolean`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[bShowInputs](ue_ue.MaterialExpressionParameter.md#bshowinputs)

#### Defined in

[ue/ue.d.ts:1173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1173)

___

### bShowMaskColorsOnPin

• **bShowMaskColorsOnPin**: `boolean`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[bShowMaskColorsOnPin](ue_ue.MaterialExpressionParameter.md#bshowmaskcolorsonpin)

#### Defined in

[ue/ue.d.ts:1169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1169)

___

### bShowOutputNameOnPin

• **bShowOutputNameOnPin**: `boolean`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[bShowOutputNameOnPin](ue_ue.MaterialExpressionParameter.md#bshowoutputnameonpin)

#### Defined in

[ue/ue.d.ts:1168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1168)

___

### bShowOutputs

• **bShowOutputs**: `boolean`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[bShowOutputs](ue_ue.MaterialExpressionParameter.md#bshowoutputs)

#### Defined in

[ue/ue.d.ts:1174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1174)

___

### bUseCustomPrimitiveData

• **bUseCustomPrimitiveData**: `boolean`

#### Defined in

[ue/ue.d.ts:47810](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47810)

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

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[CreateDefaultSubobject](ue_ue.MaterialExpressionParameter.md#createdefaultsubobject)

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

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[ExecuteUbergraph](ue_ue.MaterialExpressionParameter.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[GetClass](ue_ue.MaterialExpressionParameter.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[GetName](ue_ue.MaterialExpressionParameter.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[GetOuter](ue_ue.MaterialExpressionParameter.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[GetWorld](ue_ue.MaterialExpressionParameter.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialExpressionVectorParameter`](ue_ue.MaterialExpressionVectorParameter.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialExpressionVectorParameter`](ue_ue.MaterialExpressionVectorParameter.md)

#### Overrides

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[Find](ue_ue.MaterialExpressionParameter.md#find)

#### Defined in

[ue/ue.d.ts:47814](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47814)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialExpressionVectorParameter`](ue_ue.MaterialExpressionVectorParameter.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialExpressionVectorParameter`](ue_ue.MaterialExpressionVectorParameter.md)

#### Overrides

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[Load](ue_ue.MaterialExpressionParameter.md#load)

#### Defined in

[ue/ue.d.ts:47815](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47815)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialExpressionParameter](ue_ue.MaterialExpressionParameter.md).[StaticClass](ue_ue.MaterialExpressionParameter.md#staticclass)

#### Defined in

[ue/ue.d.ts:47813](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L47813)
