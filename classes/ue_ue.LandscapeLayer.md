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

## Properties

### BlendMode

• **BlendMode**: [`ELandscapeBlendMode`](../enums/ue_ue.ELandscapeBlendMode.md)

___

### Brushes

• **Brushes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LandscapeLayerBrush`](ue_ue.LandscapeLayerBrush.md)\>

___

### Guid

• **Guid**: [`Guid`](ue_ue_s.Guid.md)

___

### HeightmapAlpha

• **HeightmapAlpha**: `number`

___

### Name

• **Name**: `string`

___

### WeightmapAlpha

• **WeightmapAlpha**: `number`

___

### WeightmapLayerAllocationBlend

• **WeightmapLayerAllocationBlend**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`LandscapeLayerInfoObject`](ue_ue.LandscapeLayerInfoObject.md), `boolean`\>

___

### \_\_tid\_LandscapeLayer\_\_

• `Private` **\_\_tid\_LandscapeLayer\_\_**: `boolean`

___

### bLocked

• **bLocked**: `boolean`

___

### bVisible

• **bVisible**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
