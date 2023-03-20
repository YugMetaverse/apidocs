[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / HmdUserProfile

# Class: HmdUserProfile

[ue/ue](../modules/ue_ue.md).HmdUserProfile

## Table of contents

### Constructors

- [constructor](ue_ue.HmdUserProfile.md#constructor)

### Properties

- [ExtraFields](ue_ue.HmdUserProfile.md#extrafields)
- [EyeHeight](ue_ue.HmdUserProfile.md#eyeheight)
- [Gender](ue_ue.HmdUserProfile.md#gender)
- [IPD](ue_ue.HmdUserProfile.md#ipd)
- [Name](ue_ue.HmdUserProfile.md#name)
- [NeckToEyeDistance](ue_ue.HmdUserProfile.md#necktoeyedistance)
- [PlayerHeight](ue_ue.HmdUserProfile.md#playerheight)
- [\_\_tid\_HmdUserProfile\_\_](ue_ue.HmdUserProfile.md#__tid_hmduserprofile__)

### Methods

- [StaticClass](ue_ue.HmdUserProfile.md#staticclass)
- [StaticStruct](ue_ue.HmdUserProfile.md#staticstruct)

## Constructors

### constructor

• **new HmdUserProfile**()

• **new HmdUserProfile**(`Name`, `Gender`, `PlayerHeight`, `EyeHeight`, `IPD`, `NeckToEyeDistance`, `ExtraFields`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `Gender` | `string` |
| `PlayerHeight` | `number` |
| `EyeHeight` | `number` |
| `IPD` | `number` |
| `NeckToEyeDistance` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `ExtraFields` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`HmdUserProfileField`](ue_ue.HmdUserProfileField.md)\> |

## Properties

### ExtraFields

• **ExtraFields**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`HmdUserProfileField`](ue_ue.HmdUserProfileField.md)\>

___

### EyeHeight

• **EyeHeight**: `number`

___

### Gender

• **Gender**: `string`

___

### IPD

• **IPD**: `number`

___

### Name

• **Name**: `string`

___

### NeckToEyeDistance

• **NeckToEyeDistance**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### PlayerHeight

• **PlayerHeight**: `number`

___

### \_\_tid\_HmdUserProfile\_\_

• `Private` **\_\_tid\_HmdUserProfile\_\_**: `boolean`

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
