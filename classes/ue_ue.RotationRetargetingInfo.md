[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / RotationRetargetingInfo

# Class: RotationRetargetingInfo

[ue/ue](../modules/ue_ue.md).RotationRetargetingInfo

## Table of contents

### Constructors

- [constructor](ue_ue.RotationRetargetingInfo.md#constructor)

### Properties

- [CustomCurve](ue_ue.RotationRetargetingInfo.md#customcurve)
- [EasingType](ue_ue.RotationRetargetingInfo.md#easingtype)
- [EasingWeight](ue_ue.RotationRetargetingInfo.md#easingweight)
- [RotationComponent](ue_ue.RotationRetargetingInfo.md#rotationcomponent)
- [Source](ue_ue.RotationRetargetingInfo.md#source)
- [SourceMaximum](ue_ue.RotationRetargetingInfo.md#sourcemaximum)
- [SourceMinimum](ue_ue.RotationRetargetingInfo.md#sourceminimum)
- [Target](ue_ue.RotationRetargetingInfo.md#target)
- [TargetMaximum](ue_ue.RotationRetargetingInfo.md#targetmaximum)
- [TargetMinimum](ue_ue.RotationRetargetingInfo.md#targetminimum)
- [TwistAxis](ue_ue.RotationRetargetingInfo.md#twistaxis)
- [\_\_tid\_RotationRetargetingInfo\_\_](ue_ue.RotationRetargetingInfo.md#__tid_rotationretargetinginfo__)
- [bClamp](ue_ue.RotationRetargetingInfo.md#bclamp)
- [bEnabled](ue_ue.RotationRetargetingInfo.md#benabled)
- [bFlipEasing](ue_ue.RotationRetargetingInfo.md#bflipeasing)
- [bUseAbsoluteAngle](ue_ue.RotationRetargetingInfo.md#buseabsoluteangle)

### Methods

- [StaticClass](ue_ue.RotationRetargetingInfo.md#staticclass)
- [StaticStruct](ue_ue.RotationRetargetingInfo.md#staticstruct)

## Constructors

### constructor

• **new RotationRetargetingInfo**()

• **new RotationRetargetingInfo**(`bEnabled`, `Source`, `Target`, `RotationComponent`, `TwistAxis`, `bUseAbsoluteAngle`, `SourceMinimum`, `SourceMaximum`, `TargetMinimum`, `TargetMaximum`, `EasingType`, `CustomCurve`, `bFlipEasing`, `EasingWeight`, `bClamp`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnabled` | `boolean` |
| `Source` | [`Transform`](ue_ue_s.Transform.md) |
| `Target` | [`Transform`](ue_ue_s.Transform.md) |
| `RotationComponent` | [`ERotationComponent`](../enums/ue_ue.ERotationComponent.md) |
| `TwistAxis` | [`Vector`](ue_ue_s.Vector.md) |
| `bUseAbsoluteAngle` | `boolean` |
| `SourceMinimum` | `number` |
| `SourceMaximum` | `number` |
| `TargetMinimum` | `number` |
| `TargetMaximum` | `number` |
| `EasingType` | [`EEasingFuncType`](../enums/ue_ue.EEasingFuncType.md) |
| `CustomCurve` | [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md) |
| `bFlipEasing` | `boolean` |
| `EasingWeight` | `number` |
| `bClamp` | `boolean` |

## Properties

### CustomCurve

• **CustomCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

___

### EasingType

• **EasingType**: [`EEasingFuncType`](../enums/ue_ue.EEasingFuncType.md)

___

### EasingWeight

• **EasingWeight**: `number`

___

### RotationComponent

• **RotationComponent**: [`ERotationComponent`](../enums/ue_ue.ERotationComponent.md)

___

### Source

• **Source**: [`Transform`](ue_ue_s.Transform.md)

___

### SourceMaximum

• **SourceMaximum**: `number`

___

### SourceMinimum

• **SourceMinimum**: `number`

___

### Target

• **Target**: [`Transform`](ue_ue_s.Transform.md)

___

### TargetMaximum

• **TargetMaximum**: `number`

___

### TargetMinimum

• **TargetMinimum**: `number`

___

### TwistAxis

• **TwistAxis**: [`Vector`](ue_ue_s.Vector.md)

___

### \_\_tid\_RotationRetargetingInfo\_\_

• `Private` **\_\_tid\_RotationRetargetingInfo\_\_**: `boolean`

___

### bClamp

• **bClamp**: `boolean`

___

### bEnabled

• **bEnabled**: `boolean`

___

### bFlipEasing

• **bFlipEasing**: `boolean`

___

### bUseAbsoluteAngle

• **bUseAbsoluteAngle**: `boolean`

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
