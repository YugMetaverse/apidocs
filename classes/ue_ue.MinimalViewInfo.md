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

#### Defined in

[ue/ue.d.ts:6629](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6629)

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

#### Defined in

[ue/ue.d.ts:6630](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6630)

## Properties

### AspectRatio

• **AspectRatio**: `number`

#### Defined in

[ue/ue.d.ts:6638](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6638)

___

### DesiredFOV

• **DesiredFOV**: `number`

#### Defined in

[ue/ue.d.ts:6634](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6634)

___

### FOV

• **FOV**: `number`

#### Defined in

[ue/ue.d.ts:6633](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6633)

___

### Location

• **Location**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:6631](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6631)

___

### OffCenterProjectionOffset

• **OffCenterProjectionOffset**: [`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:6644](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6644)

___

### OrthoFarClipPlane

• **OrthoFarClipPlane**: `number`

#### Defined in

[ue/ue.d.ts:6637](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6637)

___

### OrthoNearClipPlane

• **OrthoNearClipPlane**: `number`

#### Defined in

[ue/ue.d.ts:6636](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6636)

___

### OrthoWidth

• **OrthoWidth**: `number`

#### Defined in

[ue/ue.d.ts:6635](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6635)

___

### PostProcessBlendWeight

• **PostProcessBlendWeight**: `number`

#### Defined in

[ue/ue.d.ts:6642](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6642)

___

### PostProcessSettings

• **PostProcessSettings**: [`PostProcessSettings`](ue_ue.PostProcessSettings.md)

#### Defined in

[ue/ue.d.ts:6643](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6643)

___

### ProjectionMode

• **ProjectionMode**: [`ECameraProjectionMode`](../enums/ue_ue.ECameraProjectionMode.md)

#### Defined in

[ue/ue.d.ts:6641](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6641)

___

### Rotation

• **Rotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:6632](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6632)

___

### \_\_tid\_MinimalViewInfo\_\_

• `Private` **\_\_tid\_MinimalViewInfo\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:6650](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6650)

___

### bConstrainAspectRatio

• **bConstrainAspectRatio**: `boolean`

#### Defined in

[ue/ue.d.ts:6639](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6639)

___

### bUseFieldOfViewForLOD

• **bUseFieldOfViewForLOD**: `boolean`

#### Defined in

[ue/ue.d.ts:6640](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6640)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:6648](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6648)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:6649](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L6649)
