[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_ModifyCurve

# Class: AnimNode\_ModifyCurve

[ue/ue](../modules/ue_ue.md).AnimNode_ModifyCurve

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_ModifyCurve`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_ModifyCurve.md#constructor)

### Properties

- [Alpha](ue_ue.AnimNode_ModifyCurve.md#alpha)
- [ApplyMode](ue_ue.AnimNode_ModifyCurve.md#applymode)
- [CurveNames](ue_ue.AnimNode_ModifyCurve.md#curvenames)
- [CurveValues](ue_ue.AnimNode_ModifyCurve.md#curvevalues)
- [SourcePose](ue_ue.AnimNode_ModifyCurve.md#sourcepose)
- [\_\_tid\_AnimNode\_ModifyCurve\_\_](ue_ue.AnimNode_ModifyCurve.md#__tid_animnode_modifycurve__)

### Methods

- [StaticClass](ue_ue.AnimNode_ModifyCurve.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_ModifyCurve.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_ModifyCurve**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

#### Defined in

[ue/ue.d.ts:18998](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18998)

• **new AnimNode_ModifyCurve**(`SourcePose`, `CurveValues`, `CurveNames`, `Alpha`, `ApplyMode`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourcePose` | [`PoseLink`](ue_ue.PoseLink.md) |
| `CurveValues` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `CurveNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `Alpha` | `number` |
| `ApplyMode` | [`EModifyCurveApplyMode`](../enums/ue_ue.EModifyCurveApplyMode.md) |

#### Overrides

UE.AnimNode\_Base.constructor

#### Defined in

[ue/ue.d.ts:18999](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L18999)

## Properties

### Alpha

• **Alpha**: `number`

#### Defined in

[ue/ue.d.ts:19003](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19003)

___

### ApplyMode

• **ApplyMode**: [`EModifyCurveApplyMode`](../enums/ue_ue.EModifyCurveApplyMode.md)

#### Defined in

[ue/ue.d.ts:19004](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19004)

___

### CurveNames

• **CurveNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:19002](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19002)

___

### CurveValues

• **CurveValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:19001](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19001)

___

### SourcePose

• **SourcePose**: [`PoseLink`](ue_ue.PoseLink.md)

#### Defined in

[ue/ue.d.ts:19000](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19000)

___

### \_\_tid\_AnimNode\_ModifyCurve\_\_

• `Private` **\_\_tid\_AnimNode\_ModifyCurve\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19010](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19010)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticClass](ue_ue.AnimNode_Base.md#staticclass)

#### Defined in

[ue/ue.d.ts:19008](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19008)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19009](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19009)
