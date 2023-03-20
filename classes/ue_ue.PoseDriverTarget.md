[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PoseDriverTarget

# Class: PoseDriverTarget

[ue/ue](../modules/ue_ue.md).PoseDriverTarget

## Table of contents

### Constructors

- [constructor](ue_ue.PoseDriverTarget.md#constructor)

### Properties

- [BoneTransforms](ue_ue.PoseDriverTarget.md#bonetransforms)
- [CustomCurve](ue_ue.PoseDriverTarget.md#customcurve)
- [DistanceMethod](ue_ue.PoseDriverTarget.md#distancemethod)
- [DrivenName](ue_ue.PoseDriverTarget.md#drivenname)
- [FunctionType](ue_ue.PoseDriverTarget.md#functiontype)
- [TargetRotation](ue_ue.PoseDriverTarget.md#targetrotation)
- [TargetScale](ue_ue.PoseDriverTarget.md#targetscale)
- [\_\_tid\_PoseDriverTarget\_\_](ue_ue.PoseDriverTarget.md#__tid_posedrivertarget__)
- [bApplyCustomCurve](ue_ue.PoseDriverTarget.md#bapplycustomcurve)
- [bIsHidden](ue_ue.PoseDriverTarget.md#bishidden)

### Methods

- [StaticClass](ue_ue.PoseDriverTarget.md#staticclass)
- [StaticStruct](ue_ue.PoseDriverTarget.md#staticstruct)

## Constructors

### constructor

• **new PoseDriverTarget**()

• **new PoseDriverTarget**(`BoneTransforms`, `TargetRotation`, `TargetScale`, `DistanceMethod`, `FunctionType`, `bApplyCustomCurve`, `CustomCurve`, `DrivenName`, `bIsHidden`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneTransforms` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseDriverTransform`](ue_ue.PoseDriverTransform.md)\> |
| `TargetRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `TargetScale` | `number` |
| `DistanceMethod` | [`ERBFDistanceMethod`](../enums/ue_ue.ERBFDistanceMethod.md) |
| `FunctionType` | [`ERBFFunctionType`](../enums/ue_ue.ERBFFunctionType.md) |
| `bApplyCustomCurve` | `boolean` |
| `CustomCurve` | [`RichCurve`](ue_ue.RichCurve.md) |
| `DrivenName` | `string` |
| `bIsHidden` | `boolean` |

## Properties

### BoneTransforms

• **BoneTransforms**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseDriverTransform`](ue_ue.PoseDriverTransform.md)\>

___

### CustomCurve

• **CustomCurve**: [`RichCurve`](ue_ue.RichCurve.md)

___

### DistanceMethod

• **DistanceMethod**: [`ERBFDistanceMethod`](../enums/ue_ue.ERBFDistanceMethod.md)

___

### DrivenName

• **DrivenName**: `string`

___

### FunctionType

• **FunctionType**: [`ERBFFunctionType`](../enums/ue_ue.ERBFFunctionType.md)

___

### TargetRotation

• **TargetRotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### TargetScale

• **TargetScale**: `number`

___

### \_\_tid\_PoseDriverTarget\_\_

• `Private` **\_\_tid\_PoseDriverTarget\_\_**: `boolean`

___

### bApplyCustomCurve

• **bApplyCustomCurve**: `boolean`

___

### bIsHidden

• **bIsHidden**: `boolean`

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
