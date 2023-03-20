[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MinimalViewInfo

# Class: MinimalViewInfo

[ue/ue](../modules/ue_ue.md).MinimalViewInfo

## Table of contents

### Constructors

- [constructor](ue_ue.MinimalViewInfo.md#constructor)

### Properties

- [AspectRatio](ue_ue.MinimalViewInfo.md#aspectratio)
- [DesiredFOV](ue_ue.MinimalViewInfo.md#desiredfov)
- [FOV](ue_ue.MinimalViewInfo.md#fov)
- [Location](ue_ue.MinimalViewInfo.md#location)
- [OffCenterProjectionOffset](ue_ue.MinimalViewInfo.md#offcenterprojectionoffset)
- [OrthoFarClipPlane](ue_ue.MinimalViewInfo.md#orthofarclipplane)
- [OrthoNearClipPlane](ue_ue.MinimalViewInfo.md#orthonearclipplane)
- [OrthoWidth](ue_ue.MinimalViewInfo.md#orthowidth)
- [PostProcessBlendWeight](ue_ue.MinimalViewInfo.md#postprocessblendweight)
- [PostProcessSettings](ue_ue.MinimalViewInfo.md#postprocesssettings)
- [ProjectionMode](ue_ue.MinimalViewInfo.md#projectionmode)
- [Rotation](ue_ue.MinimalViewInfo.md#rotation)
- [\_\_tid\_MinimalViewInfo\_\_](ue_ue.MinimalViewInfo.md#__tid_minimalviewinfo__)
- [bConstrainAspectRatio](ue_ue.MinimalViewInfo.md#bconstrainaspectratio)
- [bUseFieldOfViewForLOD](ue_ue.MinimalViewInfo.md#busefieldofviewforlod)

### Methods

- [StaticClass](ue_ue.MinimalViewInfo.md#staticclass)
- [StaticStruct](ue_ue.MinimalViewInfo.md#staticstruct)

## Constructors

### constructor

• **new MinimalViewInfo**()

• **new MinimalViewInfo**(`Location`, `Rotation`, `FOV`, `DesiredFOV`, `OrthoWidth`, `OrthoNearClipPlane`, `OrthoFarClipPlane`, `AspectRatio`, `bConstrainAspectRatio`, `bUseFieldOfViewForLOD`, `ProjectionMode`, `PostProcessBlendWeight`, `PostProcessSettings`, `OffCenterProjectionOffset`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `FOV` | `number` |
| `DesiredFOV` | `number` |
| `OrthoWidth` | `number` |
| `OrthoNearClipPlane` | `number` |
| `OrthoFarClipPlane` | `number` |
| `AspectRatio` | `number` |
| `bConstrainAspectRatio` | `boolean` |
| `bUseFieldOfViewForLOD` | `boolean` |
| `ProjectionMode` | [`ECameraProjectionMode`](../enums/ue_ue.ECameraProjectionMode.md) |
| `PostProcessBlendWeight` | `number` |
| `PostProcessSettings` | [`PostProcessSettings`](ue_ue.PostProcessSettings.md) |
| `OffCenterProjectionOffset` | [`Vector2D`](ue_ue_s.Vector2D.md) |

## Properties

### AspectRatio

• **AspectRatio**: `number`

___

### DesiredFOV

• **DesiredFOV**: `number`

___

### FOV

• **FOV**: `number`

___

### Location

• **Location**: [`Vector`](ue_ue_s.Vector.md)

___

### OffCenterProjectionOffset

• **OffCenterProjectionOffset**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### OrthoFarClipPlane

• **OrthoFarClipPlane**: `number`

___

### OrthoNearClipPlane

• **OrthoNearClipPlane**: `number`

___

### OrthoWidth

• **OrthoWidth**: `number`

___

### PostProcessBlendWeight

• **PostProcessBlendWeight**: `number`

___

### PostProcessSettings

• **PostProcessSettings**: [`PostProcessSettings`](ue_ue.PostProcessSettings.md)

___

### ProjectionMode

• **ProjectionMode**: [`ECameraProjectionMode`](../enums/ue_ue.ECameraProjectionMode.md)

___

### Rotation

• **Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### \_\_tid\_MinimalViewInfo\_\_

• `Private` **\_\_tid\_MinimalViewInfo\_\_**: `boolean`

___

### bConstrainAspectRatio

• **bConstrainAspectRatio**: `boolean`

___

### bUseFieldOfViewForLOD

• **bUseFieldOfViewForLOD**: `boolean`

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
