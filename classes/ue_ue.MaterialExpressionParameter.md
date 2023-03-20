[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialExpressionParameter

# Class: MaterialExpressionParameter

[ue/ue](../modules/ue_ue.md).MaterialExpressionParameter

## Hierarchy

- [`MaterialExpression`](ue_ue.MaterialExpression.md)

  ↳ **`MaterialExpressionParameter`**

  ↳↳ [`MaterialExpressionVectorParameter`](ue_ue.MaterialExpressionVectorParameter.md)

  ↳↳ [`MaterialExpressionScalarParameter`](ue_ue.MaterialExpressionScalarParameter.md)

  ↳↳ [`MaterialExpressionStaticBoolParameter`](ue_ue.MaterialExpressionStaticBoolParameter.md)

  ↳↳ [`MaterialExpressionStaticComponentMaskParameter`](ue_ue.MaterialExpressionStaticComponentMaskParameter.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialExpressionParameter.md#constructor)

### Properties

- [Desc](ue_ue.MaterialExpressionParameter.md#desc)
- [ExpressionGUID](ue_ue.MaterialExpressionParameter.md#expressionguid)
- [Function](ue_ue.MaterialExpressionParameter.md#function)
- [GraphNode](ue_ue.MaterialExpressionParameter.md#graphnode)
- [Group](ue_ue.MaterialExpressionParameter.md#group)
- [Material](ue_ue.MaterialExpressionParameter.md#material)
- [MaterialExpressionEditorX](ue_ue.MaterialExpressionParameter.md#materialexpressioneditorx)
- [MaterialExpressionEditorY](ue_ue.MaterialExpressionParameter.md#materialexpressioneditory)
- [MaterialExpressionGuid](ue_ue.MaterialExpressionParameter.md#materialexpressionguid)
- [MenuCategories](ue_ue.MaterialExpressionParameter.md#menucategories)
- [Outputs](ue_ue.MaterialExpressionParameter.md#outputs)
- [ParameterName](ue_ue.MaterialExpressionParameter.md#parametername)
- [SortPriority](ue_ue.MaterialExpressionParameter.md#sortpriority)
- [\_\_tid\_MaterialExpressionParameter\_\_](ue_ue.MaterialExpressionParameter.md#__tid_materialexpressionparameter__)
- [\_\_tid\_MaterialExpression\_\_](ue_ue.MaterialExpressionParameter.md#__tid_materialexpression__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialExpressionParameter.md#__tid_object__)
- [bCollapsed](ue_ue.MaterialExpressionParameter.md#bcollapsed)
- [bCommentBubbleVisible](ue_ue.MaterialExpressionParameter.md#bcommentbubblevisible)
- [bHidePreviewWindow](ue_ue.MaterialExpressionParameter.md#bhidepreviewwindow)
- [bIsParameterExpression](ue_ue.MaterialExpressionParameter.md#bisparameterexpression)
- [bNeedToUpdatePreview](ue_ue.MaterialExpressionParameter.md#bneedtoupdatepreview)
- [bRealtimePreview](ue_ue.MaterialExpressionParameter.md#brealtimepreview)
- [bShaderInputData](ue_ue.MaterialExpressionParameter.md#bshaderinputdata)
- [bShowInputs](ue_ue.MaterialExpressionParameter.md#bshowinputs)
- [bShowMaskColorsOnPin](ue_ue.MaterialExpressionParameter.md#bshowmaskcolorsonpin)
- [bShowOutputNameOnPin](ue_ue.MaterialExpressionParameter.md#bshowoutputnameonpin)
- [bShowOutputs](ue_ue.MaterialExpressionParameter.md#bshowoutputs)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialExpressionParameter.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialExpressionParameter.md#executeubergraph)
- [GetClass](ue_ue.MaterialExpressionParameter.md#getclass)
- [GetName](ue_ue.MaterialExpressionParameter.md#getname)
- [GetOuter](ue_ue.MaterialExpressionParameter.md#getouter)
- [GetWorld](ue_ue.MaterialExpressionParameter.md#getworld)
- [Find](ue_ue.MaterialExpressionParameter.md#find)
- [Load](ue_ue.MaterialExpressionParameter.md#load)
- [StaticClass](ue_ue.MaterialExpressionParameter.md#staticclass)

## Constructors

### constructor

• **new MaterialExpressionParameter**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[constructor](ue_ue.MaterialExpression.md#constructor)

#### Defined in

[ue/ue.d.ts:47795](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47795)

## Properties

### Desc

• **Desc**: `string`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Desc](ue_ue.MaterialExpression.md#desc)

#### Defined in

[ue/ue.d.ts:1163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1163)

___

### ExpressionGUID

• **ExpressionGUID**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:47797](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47797)

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

### Group

• **Group**: `string`

#### Defined in

[ue/ue.d.ts:47798](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47798)

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

### Outputs

• **Outputs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ExpressionOutput`](ue_ue.ExpressionOutput.md)\>

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Outputs](ue_ue.MaterialExpression.md#outputs)

#### Defined in

[ue/ue.d.ts:1176](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L1176)

___

### ParameterName

• **ParameterName**: `string`

#### Defined in

[ue/ue.d.ts:47796](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47796)

___

### SortPriority

• **SortPriority**: `number`

#### Defined in

[ue/ue.d.ts:47799](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47799)

___

### \_\_tid\_MaterialExpressionParameter\_\_

• **\_\_tid\_MaterialExpressionParameter\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:47804](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47804)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialExpressionParameter`](ue_ue.MaterialExpressionParameter.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialExpressionParameter`](ue_ue.MaterialExpressionParameter.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[Find](ue_ue.MaterialExpression.md#find)

#### Defined in

[ue/ue.d.ts:47801](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47801)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialExpressionParameter`](ue_ue.MaterialExpressionParameter.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialExpressionParameter`](ue_ue.MaterialExpressionParameter.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[Load](ue_ue.MaterialExpression.md#load)

#### Defined in

[ue/ue.d.ts:47802](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47802)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[StaticClass](ue_ue.MaterialExpression.md#staticclass)

#### Defined in

[ue/ue.d.ts:47800](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47800)
