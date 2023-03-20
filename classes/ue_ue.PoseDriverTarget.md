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

#### Defined in

[ue/ue.d.ts:19160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19160)

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

#### Defined in

[ue/ue.d.ts:19161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19161)

## Properties

### BoneTransforms

• **BoneTransforms**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseDriverTransform`](ue_ue.PoseDriverTransform.md)\>

#### Defined in

[ue/ue.d.ts:19162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19162)

___

### CustomCurve

• **CustomCurve**: [`RichCurve`](ue_ue.RichCurve.md)

#### Defined in

[ue/ue.d.ts:19168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19168)

___

### DistanceMethod

• **DistanceMethod**: [`ERBFDistanceMethod`](../enums/ue_ue.ERBFDistanceMethod.md)

#### Defined in

[ue/ue.d.ts:19165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19165)

___

### DrivenName

• **DrivenName**: `string`

#### Defined in

[ue/ue.d.ts:19169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19169)

___

### FunctionType

• **FunctionType**: [`ERBFFunctionType`](../enums/ue_ue.ERBFFunctionType.md)

#### Defined in

[ue/ue.d.ts:19166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19166)

___

### TargetRotation

• **TargetRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:19163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19163)

___

### TargetScale

• **TargetScale**: `number`

#### Defined in

[ue/ue.d.ts:19164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19164)

___

### \_\_tid\_PoseDriverTarget\_\_

• `Private` **\_\_tid\_PoseDriverTarget\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:19176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19176)

___

### bApplyCustomCurve

• **bApplyCustomCurve**: `boolean`

#### Defined in

[ue/ue.d.ts:19167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19167)

___

### bIsHidden

• **bIsHidden**: `boolean`

#### Defined in

[ue/ue.d.ts:19170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19170)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:19174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19174)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:19175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L19175)
