[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MagicLeapTouchpadGesture

# Class: MagicLeapTouchpadGesture

[ue/ue](../modules/ue_ue.md).MagicLeapTouchpadGesture

## Table of contents

### Constructors

- [constructor](ue_ue.MagicLeapTouchpadGesture.md#constructor)

### Properties

- [Angle](ue_ue.MagicLeapTouchpadGesture.md#angle)
- [Direction](ue_ue.MagicLeapTouchpadGesture.md#direction)
- [Distance](ue_ue.MagicLeapTouchpadGesture.md#distance)
- [FingerGap](ue_ue.MagicLeapTouchpadGesture.md#fingergap)
- [Hand](ue_ue.MagicLeapTouchpadGesture.md#hand)
- [MotionSource](ue_ue.MagicLeapTouchpadGesture.md#motionsource)
- [PositionAndForce](ue_ue.MagicLeapTouchpadGesture.md#positionandforce)
- [Radius](ue_ue.MagicLeapTouchpadGesture.md#radius)
- [Speed](ue_ue.MagicLeapTouchpadGesture.md#speed)
- [Type](ue_ue.MagicLeapTouchpadGesture.md#type)
- [\_\_tid\_MagicLeapTouchpadGesture\_\_](ue_ue.MagicLeapTouchpadGesture.md#__tid_magicleaptouchpadgesture__)

### Methods

- [StaticClass](ue_ue.MagicLeapTouchpadGesture.md#staticclass)
- [StaticStruct](ue_ue.MagicLeapTouchpadGesture.md#staticstruct)

## Constructors

### constructor

• **new MagicLeapTouchpadGesture**()

#### Defined in

[ue/ue.d.ts:47143](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47143)

• **new MagicLeapTouchpadGesture**(`Hand`, `MotionSource`, `Type`, `Direction`, `PositionAndForce`, `Speed`, `Distance`, `FingerGap`, `Radius`, `Angle`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hand` | [`EControllerHand`](../enums/ue_ue.EControllerHand.md) |
| `MotionSource` | `string` |
| `Type` | [`EMagicLeapTouchpadGestureType`](../enums/ue_ue.EMagicLeapTouchpadGestureType.md) |
| `Direction` | [`EMagicLeapTouchpadGestureDirection`](../enums/ue_ue.EMagicLeapTouchpadGestureDirection.md) |
| `PositionAndForce` | [`Vector`](ue_ue_s.Vector.md) |
| `Speed` | `number` |
| `Distance` | `number` |
| `FingerGap` | `number` |
| `Radius` | `number` |
| `Angle` | `number` |

#### Defined in

[ue/ue.d.ts:47144](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47144)

## Properties

### Angle

• **Angle**: `number`

#### Defined in

[ue/ue.d.ts:47154](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47154)

___

### Direction

• **Direction**: [`EMagicLeapTouchpadGestureDirection`](../enums/ue_ue.EMagicLeapTouchpadGestureDirection.md)

#### Defined in

[ue/ue.d.ts:47148](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47148)

___

### Distance

• **Distance**: `number`

#### Defined in

[ue/ue.d.ts:47151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47151)

___

### FingerGap

• **FingerGap**: `number`

#### Defined in

[ue/ue.d.ts:47152](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47152)

___

### Hand

• **Hand**: [`EControllerHand`](../enums/ue_ue.EControllerHand.md)

#### Defined in

[ue/ue.d.ts:47145](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47145)

___

### MotionSource

• **MotionSource**: `string`

#### Defined in

[ue/ue.d.ts:47146](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47146)

___

### PositionAndForce

• **PositionAndForce**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:47149](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47149)

___

### Radius

• **Radius**: `number`

#### Defined in

[ue/ue.d.ts:47153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47153)

___

### Speed

• **Speed**: `number`

#### Defined in

[ue/ue.d.ts:47150](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47150)

___

### Type

• **Type**: [`EMagicLeapTouchpadGestureType`](../enums/ue_ue.EMagicLeapTouchpadGestureType.md)

#### Defined in

[ue/ue.d.ts:47147](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47147)

___

### \_\_tid\_MagicLeapTouchpadGesture\_\_

• `Private` **\_\_tid\_MagicLeapTouchpadGesture\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:47160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47160)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:47158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47158)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:47159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L47159)
