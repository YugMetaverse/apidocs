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

#### Defined in

[ue/ue.d.ts:17796](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17796)

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

#### Defined in

[ue/ue.d.ts:17797](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17797)

## Properties

### CustomCurve

• **CustomCurve**: [`RuntimeFloatCurve`](ue_ue.RuntimeFloatCurve.md)

#### Defined in

[ue/ue.d.ts:17809](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17809)

___

### EasingType

• **EasingType**: [`EEasingFuncType`](../enums/ue_ue.EEasingFuncType.md)

#### Defined in

[ue/ue.d.ts:17808](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17808)

___

### EasingWeight

• **EasingWeight**: `number`

#### Defined in

[ue/ue.d.ts:17811](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17811)

___

### RotationComponent

• **RotationComponent**: [`ERotationComponent`](../enums/ue_ue.ERotationComponent.md)

#### Defined in

[ue/ue.d.ts:17801](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17801)

___

### Source

• **Source**: [`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:17799](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17799)

___

### SourceMaximum

• **SourceMaximum**: `number`

#### Defined in

[ue/ue.d.ts:17805](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17805)

___

### SourceMinimum

• **SourceMinimum**: `number`

#### Defined in

[ue/ue.d.ts:17804](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17804)

___

### Target

• **Target**: [`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:17800](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17800)

___

### TargetMaximum

• **TargetMaximum**: `number`

#### Defined in

[ue/ue.d.ts:17807](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17807)

___

### TargetMinimum

• **TargetMinimum**: `number`

#### Defined in

[ue/ue.d.ts:17806](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17806)

___

### TwistAxis

• **TwistAxis**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:17802](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17802)

___

### \_\_tid\_RotationRetargetingInfo\_\_

• `Private` **\_\_tid\_RotationRetargetingInfo\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:17818](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17818)

___

### bClamp

• **bClamp**: `boolean`

#### Defined in

[ue/ue.d.ts:17812](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17812)

___

### bEnabled

• **bEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:17798](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17798)

___

### bFlipEasing

• **bFlipEasing**: `boolean`

#### Defined in

[ue/ue.d.ts:17810](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17810)

___

### bUseAbsoluteAngle

• **bUseAbsoluteAngle**: `boolean`

#### Defined in

[ue/ue.d.ts:17803](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17803)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:17816](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17816)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:17817](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17817)
