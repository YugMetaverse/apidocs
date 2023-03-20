[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TrackedCamera

# Class: TrackedCamera

[ue/ue](../modules/ue_ue.md).TrackedCamera

## Table of contents

### Constructors

- [constructor](ue_ue.TrackedCamera.md#constructor)

### Properties

- [AttachedTrackedDevice](ue_ue.TrackedCamera.md#attachedtrackeddevice)
- [CalibratedOffset](ue_ue.TrackedCamera.md#calibratedoffset)
- [CalibratedRotation](ue_ue.TrackedCamera.md#calibratedrotation)
- [FieldOfView](ue_ue.TrackedCamera.md#fieldofview)
- [Index](ue_ue.TrackedCamera.md#index)
- [Name](ue_ue.TrackedCamera.md#name)
- [RawOffset](ue_ue.TrackedCamera.md#rawoffset)
- [RawRotation](ue_ue.TrackedCamera.md#rawrotation)
- [SizeX](ue_ue.TrackedCamera.md#sizex)
- [SizeY](ue_ue.TrackedCamera.md#sizey)
- [UserOffset](ue_ue.TrackedCamera.md#useroffset)
- [UserRotation](ue_ue.TrackedCamera.md#userrotation)
- [\_\_tid\_TrackedCamera\_\_](ue_ue.TrackedCamera.md#__tid_trackedcamera__)

### Methods

- [StaticClass](ue_ue.TrackedCamera.md#staticclass)
- [StaticStruct](ue_ue.TrackedCamera.md#staticstruct)

## Constructors

### constructor

• **new TrackedCamera**()

• **new TrackedCamera**(`Index`, `Name`, `FieldOfView`, `SizeX`, `SizeY`, `AttachedTrackedDevice`, `CalibratedRotation`, `CalibratedOffset`, `UserRotation`, `UserOffset`, `RawRotation`, `RawOffset`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Index` | `number` |
| `Name` | `string` |
| `FieldOfView` | `number` |
| `SizeX` | `number` |
| `SizeY` | `number` |
| `AttachedTrackedDevice` | [`ETrackedDeviceType`](../enums/ue_ue.ETrackedDeviceType.md) |
| `CalibratedRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `CalibratedOffset` | [`Vector`](ue_ue_s.Vector.md) |
| `UserRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `UserOffset` | [`Vector`](ue_ue_s.Vector.md) |
| `RawRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `RawOffset` | [`Vector`](ue_ue_s.Vector.md) |

## Properties

### AttachedTrackedDevice

• **AttachedTrackedDevice**: [`ETrackedDeviceType`](../enums/ue_ue.ETrackedDeviceType.md)

___

### CalibratedOffset

• **CalibratedOffset**: [`Vector`](ue_ue_s.Vector.md)

___

### CalibratedRotation

• **CalibratedRotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### FieldOfView

• **FieldOfView**: `number`

___

### Index

• **Index**: `number`

___

### Name

• **Name**: `string`

___

### RawOffset

• **RawOffset**: [`Vector`](ue_ue_s.Vector.md)

___

### RawRotation

• **RawRotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### SizeX

• **SizeX**: `number`

___

### SizeY

• **SizeY**: `number`

___

### UserOffset

• **UserOffset**: [`Vector`](ue_ue_s.Vector.md)

___

### UserRotation

• **UserRotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### \_\_tid\_TrackedCamera\_\_

• `Private` **\_\_tid\_TrackedCamera\_\_**: `boolean`

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
