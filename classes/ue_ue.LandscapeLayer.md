[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LandscapeLayer

# Class: LandscapeLayer

[ue/ue](../modules/ue_ue.md).LandscapeLayer

## Table of contents

### Constructors

- [constructor](ue_ue.LandscapeLayer.md#constructor)

### Properties

- [BlendMode](ue_ue.LandscapeLayer.md#blendmode)
- [Brushes](ue_ue.LandscapeLayer.md#brushes)
- [Guid](ue_ue.LandscapeLayer.md#guid)
- [HeightmapAlpha](ue_ue.LandscapeLayer.md#heightmapalpha)
- [Name](ue_ue.LandscapeLayer.md#name)
- [WeightmapAlpha](ue_ue.LandscapeLayer.md#weightmapalpha)
- [WeightmapLayerAllocationBlend](ue_ue.LandscapeLayer.md#weightmaplayerallocationblend)
- [\_\_tid\_LandscapeLayer\_\_](ue_ue.LandscapeLayer.md#__tid_landscapelayer__)
- [bLocked](ue_ue.LandscapeLayer.md#blocked)
- [bVisible](ue_ue.LandscapeLayer.md#bvisible)

### Methods

- [StaticClass](ue_ue.LandscapeLayer.md#staticclass)
- [StaticStruct](ue_ue.LandscapeLayer.md#staticstruct)

## Constructors

### constructor

• **new LandscapeLayer**()

#### Defined in

[ue/ue.d.ts:44178](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44178)

• **new LandscapeLayer**(`Guid`, `Name`, `bVisible`, `bLocked`, `HeightmapAlpha`, `WeightmapAlpha`, `BlendMode`, `Brushes`, `WeightmapLayerAllocationBlend`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Guid` | [`Guid`](ue_ue_s.Guid.md) |
| `Name` | `string` |
| `bVisible` | `boolean` |
| `bLocked` | `boolean` |
| `HeightmapAlpha` | `number` |
| `WeightmapAlpha` | `number` |
| `BlendMode` | [`ELandscapeBlendMode`](../enums/ue_ue.ELandscapeBlendMode.md) |
| `Brushes` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeLayerBrush`](ue_ue.LandscapeLayerBrush.md)\> |
| `WeightmapLayerAllocationBlend` | [`TMap`](../interfaces/ue_puerts.TMap.md)<[`LandscapeLayerInfoObject`](ue_ue.LandscapeLayerInfoObject.md), `boolean`\> |

#### Defined in

[ue/ue.d.ts:44179](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44179)

## Properties

### BlendMode

• **BlendMode**: [`ELandscapeBlendMode`](../enums/ue_ue.ELandscapeBlendMode.md)

#### Defined in

[ue/ue.d.ts:44186](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44186)

___

### Brushes

• **Brushes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeLayerBrush`](ue_ue.LandscapeLayerBrush.md)\>

#### Defined in

[ue/ue.d.ts:44187](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44187)

___

### Guid

• **Guid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:44180](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44180)

___

### HeightmapAlpha

• **HeightmapAlpha**: `number`

#### Defined in

[ue/ue.d.ts:44184](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44184)

___

### Name

• **Name**: `string`

#### Defined in

[ue/ue.d.ts:44181](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44181)

___

### WeightmapAlpha

• **WeightmapAlpha**: `number`

#### Defined in

[ue/ue.d.ts:44185](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44185)

___

### WeightmapLayerAllocationBlend

• **WeightmapLayerAllocationBlend**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`LandscapeLayerInfoObject`](ue_ue.LandscapeLayerInfoObject.md), `boolean`\>

#### Defined in

[ue/ue.d.ts:44188](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44188)

___

### \_\_tid\_LandscapeLayer\_\_

• `Private` **\_\_tid\_LandscapeLayer\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:44194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44194)

___

### bLocked

• **bLocked**: `boolean`

#### Defined in

[ue/ue.d.ts:44183](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44183)

___

### bVisible

• **bVisible**: `boolean`

#### Defined in

[ue/ue.d.ts:44182](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44182)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:44192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44192)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:44193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L44193)
