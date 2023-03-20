[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_MultiWayBlend

# Class: AnimNode\_MultiWayBlend

[ue/ue](../modules/ue_ue.md).AnimNode_MultiWayBlend

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_MultiWayBlend`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_MultiWayBlend.md#constructor)

### Properties

- [AlphaScaleBias](ue_ue.AnimNode_MultiWayBlend.md#alphascalebias)
- [DesiredAlphas](ue_ue.AnimNode_MultiWayBlend.md#desiredalphas)
- [Poses](ue_ue.AnimNode_MultiWayBlend.md#poses)
- [\_\_tid\_AnimNode\_MultiWayBlend\_\_](ue_ue.AnimNode_MultiWayBlend.md#__tid_animnode_multiwayblend__)
- [bAdditiveNode](ue_ue.AnimNode_MultiWayBlend.md#badditivenode)
- [bNormalizeAlpha](ue_ue.AnimNode_MultiWayBlend.md#bnormalizealpha)

### Methods

- [StaticClass](ue_ue.AnimNode_MultiWayBlend.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_MultiWayBlend.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_MultiWayBlend**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

• **new AnimNode_MultiWayBlend**(`Poses`, `DesiredAlphas`, `AlphaScaleBias`, `bAdditiveNode`, `bNormalizeAlpha`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Poses` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseLink`](ue_ue.PoseLink.md)\> |
| `DesiredAlphas` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `AlphaScaleBias` | [`InputScaleBias`](ue_ue.InputScaleBias.md) |
| `bAdditiveNode` | `boolean` |
| `bNormalizeAlpha` | `boolean` |

#### Overrides

UE.AnimNode\_Base.constructor

## Properties

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

___

### DesiredAlphas

• **DesiredAlphas**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### Poses

• **Poses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseLink`](ue_ue.PoseLink.md)\>

___

### \_\_tid\_AnimNode\_MultiWayBlend\_\_

• `Private` **\_\_tid\_AnimNode\_MultiWayBlend\_\_**: `boolean`

___

### bAdditiveNode

• **bAdditiveNode**: `boolean`

___

### bNormalizeAlpha

• **bNormalizeAlpha**: `boolean`

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
