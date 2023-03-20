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

#### Defined in

[ue/ue.d.ts:19024](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19024)

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

#### Defined in

[ue/ue.d.ts:19025](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19025)

## Properties

### AlphaScaleBias

• **AlphaScaleBias**: [`InputScaleBias`](ue_ue.InputScaleBias.md)

#### Defined in

[ue/ue.d.ts:19028](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19028)

___

### DesiredAlphas

• **DesiredAlphas**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:19027](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19027)

___

### Poses

• **Poses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseLink`](ue_ue.PoseLink.md)\>

#### Defined in

[ue/ue.d.ts:19026](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19026)

___

### \_\_tid\_AnimNode\_MultiWayBlend\_\_

• `Private` **\_\_tid\_AnimNode\_MultiWayBlend\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19036](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19036)

___

### bAdditiveNode

• **bAdditiveNode**: `boolean`

#### Defined in

[ue/ue.d.ts:19029](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19029)

___

### bNormalizeAlpha

• **bNormalizeAlpha**: `boolean`

#### Defined in

[ue/ue.d.ts:19030](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19030)

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

[ue/ue.d.ts:19034](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19034)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)

#### Defined in

[ue/ue.d.ts:19035](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19035)
