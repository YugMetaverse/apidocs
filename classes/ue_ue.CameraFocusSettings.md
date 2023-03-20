[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CameraFocusSettings

# Class: CameraFocusSettings

[ue/ue](../modules/ue_ue.md).CameraFocusSettings

## Table of contents

### Constructors

- [constructor](ue_ue.CameraFocusSettings.md#constructor)

### Properties

- [DebugFocusPlaneColor](ue_ue.CameraFocusSettings.md#debugfocusplanecolor)
- [FocusMethod](ue_ue.CameraFocusSettings.md#focusmethod)
- [FocusOffset](ue_ue.CameraFocusSettings.md#focusoffset)
- [FocusSmoothingInterpSpeed](ue_ue.CameraFocusSettings.md#focussmoothinginterpspeed)
- [ManualFocusDistance](ue_ue.CameraFocusSettings.md#manualfocusdistance)
- [TrackingFocusSettings](ue_ue.CameraFocusSettings.md#trackingfocussettings)
- [\_\_tid\_CameraFocusSettings\_\_](ue_ue.CameraFocusSettings.md#__tid_camerafocussettings__)
- [bDrawDebugFocusPlane](ue_ue.CameraFocusSettings.md#bdrawdebugfocusplane)
- [bSmoothFocusChanges](ue_ue.CameraFocusSettings.md#bsmoothfocuschanges)

### Methods

- [StaticClass](ue_ue.CameraFocusSettings.md#staticclass)
- [StaticStruct](ue_ue.CameraFocusSettings.md#staticstruct)

## Constructors

### constructor

• **new CameraFocusSettings**()

• **new CameraFocusSettings**(`FocusMethod`, `ManualFocusDistance`, `TrackingFocusSettings`, `bDrawDebugFocusPlane`, `DebugFocusPlaneColor`, `bSmoothFocusChanges`, `FocusSmoothingInterpSpeed`, `FocusOffset`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `FocusMethod` | [`ECameraFocusMethod`](../enums/ue_ue.ECameraFocusMethod.md) |
| `ManualFocusDistance` | `number` |
| `TrackingFocusSettings` | [`CameraTrackingFocusSettings`](ue_ue.CameraTrackingFocusSettings.md) |
| `bDrawDebugFocusPlane` | `boolean` |
| `DebugFocusPlaneColor` | [`Color`](ue_ue_s.Color.md) |
| `bSmoothFocusChanges` | `boolean` |
| `FocusSmoothingInterpSpeed` | `number` |
| `FocusOffset` | `number` |

## Properties

### DebugFocusPlaneColor

• **DebugFocusPlaneColor**: [`Color`](ue_ue_s.Color.md)

___

### FocusMethod

• **FocusMethod**: [`ECameraFocusMethod`](../enums/ue_ue.ECameraFocusMethod.md)

___

### FocusOffset

• **FocusOffset**: `number`

___

### FocusSmoothingInterpSpeed

• **FocusSmoothingInterpSpeed**: `number`

___

### ManualFocusDistance

• **ManualFocusDistance**: `number`

___

### TrackingFocusSettings

• **TrackingFocusSettings**: [`CameraTrackingFocusSettings`](ue_ue.CameraTrackingFocusSettings.md)

___

### \_\_tid\_CameraFocusSettings\_\_

• `Private` **\_\_tid\_CameraFocusSettings\_\_**: `boolean`

___

### bDrawDebugFocusPlane

• **bDrawDebugFocusPlane**: `boolean`

___

### bSmoothFocusChanges

• **bSmoothFocusChanges**: `boolean`

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
