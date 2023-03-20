[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MaterialExpressionPanner

# Class: MaterialExpressionPanner

[ue/ue](../modules/ue_ue.md).MaterialExpressionPanner

## Hierarchy

- [`MaterialExpression`](ue_ue.MaterialExpression.md)

  ↳ **`MaterialExpressionPanner`**

## Table of contents

### Constructors

- [constructor](ue_ue.MaterialExpressionPanner.md#constructor)

### Properties

- [ConstCoordinate](ue_ue.MaterialExpressionPanner.md#constcoordinate)
- [Coordinate](ue_ue.MaterialExpressionPanner.md#coordinate)
- [Desc](ue_ue.MaterialExpressionPanner.md#desc)
- [Function](ue_ue.MaterialExpressionPanner.md#function)
- [GraphNode](ue_ue.MaterialExpressionPanner.md#graphnode)
- [Material](ue_ue.MaterialExpressionPanner.md#material)
- [MaterialExpressionEditorX](ue_ue.MaterialExpressionPanner.md#materialexpressioneditorx)
- [MaterialExpressionEditorY](ue_ue.MaterialExpressionPanner.md#materialexpressioneditory)
- [MaterialExpressionGuid](ue_ue.MaterialExpressionPanner.md#materialexpressionguid)
- [MenuCategories](ue_ue.MaterialExpressionPanner.md#menucategories)
- [Outputs](ue_ue.MaterialExpressionPanner.md#outputs)
- [Speed](ue_ue.MaterialExpressionPanner.md#speed)
- [SpeedX](ue_ue.MaterialExpressionPanner.md#speedx)
- [SpeedY](ue_ue.MaterialExpressionPanner.md#speedy)
- [Time](ue_ue.MaterialExpressionPanner.md#time)
- [\_\_tid\_MaterialExpressionPanner\_\_](ue_ue.MaterialExpressionPanner.md#__tid_materialexpressionpanner__)
- [\_\_tid\_MaterialExpression\_\_](ue_ue.MaterialExpressionPanner.md#__tid_materialexpression__)
- [\_\_tid\_Object\_\_](ue_ue.MaterialExpressionPanner.md#__tid_object__)
- [bCollapsed](ue_ue.MaterialExpressionPanner.md#bcollapsed)
- [bCommentBubbleVisible](ue_ue.MaterialExpressionPanner.md#bcommentbubblevisible)
- [bFractionalPart](ue_ue.MaterialExpressionPanner.md#bfractionalpart)
- [bHidePreviewWindow](ue_ue.MaterialExpressionPanner.md#bhidepreviewwindow)
- [bIsParameterExpression](ue_ue.MaterialExpressionPanner.md#bisparameterexpression)
- [bNeedToUpdatePreview](ue_ue.MaterialExpressionPanner.md#bneedtoupdatepreview)
- [bRealtimePreview](ue_ue.MaterialExpressionPanner.md#brealtimepreview)
- [bShaderInputData](ue_ue.MaterialExpressionPanner.md#bshaderinputdata)
- [bShowInputs](ue_ue.MaterialExpressionPanner.md#bshowinputs)
- [bShowMaskColorsOnPin](ue_ue.MaterialExpressionPanner.md#bshowmaskcolorsonpin)
- [bShowOutputNameOnPin](ue_ue.MaterialExpressionPanner.md#bshowoutputnameonpin)
- [bShowOutputs](ue_ue.MaterialExpressionPanner.md#bshowoutputs)

### Methods

- [CreateDefaultSubobject](ue_ue.MaterialExpressionPanner.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MaterialExpressionPanner.md#executeubergraph)
- [GetClass](ue_ue.MaterialExpressionPanner.md#getclass)
- [GetName](ue_ue.MaterialExpressionPanner.md#getname)
- [GetOuter](ue_ue.MaterialExpressionPanner.md#getouter)
- [GetWorld](ue_ue.MaterialExpressionPanner.md#getworld)
- [Find](ue_ue.MaterialExpressionPanner.md#find)
- [Load](ue_ue.MaterialExpressionPanner.md#load)
- [StaticClass](ue_ue.MaterialExpressionPanner.md#staticclass)

## Constructors

### constructor

• **new MaterialExpressionPanner**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[constructor](ue_ue.MaterialExpression.md#constructor)

#### Defined in

[ue/ue.d.ts:48779](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48779)

## Properties

### ConstCoordinate

• **ConstCoordinate**: `number`

#### Defined in

[ue/ue.d.ts:48785](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48785)

___

### Coordinate

• **Coordinate**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48780](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48780)

___

### Desc

• **Desc**: `string`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Desc](ue_ue.MaterialExpression.md#desc)

#### Defined in

[ue/ue.d.ts:1163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1163)

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

### Outputs

• **Outputs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ExpressionOutput`](ue_ue.ExpressionOutput.md)\>

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[Outputs](ue_ue.MaterialExpression.md#outputs)

#### Defined in

[ue/ue.d.ts:1176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1176)

___

### Speed

• **Speed**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48782](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48782)

___

### SpeedX

• **SpeedX**: `number`

#### Defined in

[ue/ue.d.ts:48783](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48783)

___

### SpeedY

• **SpeedY**: `number`

#### Defined in

[ue/ue.d.ts:48784](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48784)

___

### Time

• **Time**: [`ExpressionInput`](ue_ue.ExpressionInput.md)

#### Defined in

[ue/ue.d.ts:48781](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48781)

___

### \_\_tid\_MaterialExpressionPanner\_\_

• **\_\_tid\_MaterialExpressionPanner\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:48791](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48791)

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

### bFractionalPart

• **bFractionalPart**: `boolean`

#### Defined in

[ue/ue.d.ts:48786](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48786)

___

### bHidePreviewWindow

• **bHidePreviewWindow**: `boolean`

#### Inherited from

[MaterialExpression](ue_ue.MaterialExpression.md).[bHidePreviewWindow](ue_ue.MaterialExpression.md#bhidepreviewwindow)

#### Defined in

[ue/ue.d.ts:1170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L1170)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MaterialExpressionPanner`](ue_ue.MaterialExpressionPanner.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MaterialExpressionPanner`](ue_ue.MaterialExpressionPanner.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[Find](ue_ue.MaterialExpression.md#find)

#### Defined in

[ue/ue.d.ts:48788](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48788)

___

### Load

▸ `Static` **Load**(`InName`): [`MaterialExpressionPanner`](ue_ue.MaterialExpressionPanner.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MaterialExpressionPanner`](ue_ue.MaterialExpressionPanner.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[Load](ue_ue.MaterialExpression.md#load)

#### Defined in

[ue/ue.d.ts:48789](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48789)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MaterialExpression](ue_ue.MaterialExpression.md).[StaticClass](ue_ue.MaterialExpression.md#staticclass)

#### Defined in

[ue/ue.d.ts:48787](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L48787)
