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

## Properties

### Alpha

• **Alpha**: `number`

___

### ApplyMode

• **ApplyMode**: [`EModifyCurveApplyMode`](../enums/ue_ue.EModifyCurveApplyMode.md)

___

### CurveNames

• **CurveNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### CurveValues

• **CurveValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### SourcePose

• **SourcePose**: [`PoseLink`](ue_ue.PoseLink.md)

___

### \_\_tid\_AnimNode\_ModifyCurve\_\_

• `Private` **\_\_tid\_AnimNode\_ModifyCurve\_\_**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticClass](ue_ue.AnimNode_Base.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)
