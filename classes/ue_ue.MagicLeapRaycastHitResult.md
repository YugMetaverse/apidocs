[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MagicLeapRaycastHitResult

# Class: MagicLeapRaycastHitResult

[ue/ue](../modules/ue_ue.md).MagicLeapRaycastHitResult

## Table of contents

### Constructors

- [constructor](ue_ue.MagicLeapRaycastHitResult.md#constructor)

### Properties

- [Confidence](ue_ue.MagicLeapRaycastHitResult.md#confidence)
- [HitPoint](ue_ue.MagicLeapRaycastHitResult.md#hitpoint)
- [HitState](ue_ue.MagicLeapRaycastHitResult.md#hitstate)
- [Normal](ue_ue.MagicLeapRaycastHitResult.md#normal)
- [UserData](ue_ue.MagicLeapRaycastHitResult.md#userdata)
- [\_\_tid\_MagicLeapRaycastHitResult\_\_](ue_ue.MagicLeapRaycastHitResult.md#__tid_magicleapraycasthitresult__)

### Methods

- [StaticClass](ue_ue.MagicLeapRaycastHitResult.md#staticclass)
- [StaticStruct](ue_ue.MagicLeapRaycastHitResult.md#staticstruct)

## Constructors

### constructor

• **new MagicLeapRaycastHitResult**()

• **new MagicLeapRaycastHitResult**(`HitState`, `HitPoint`, `Normal`, `Confidence`, `UserData`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `HitState` | [`EMagicLeapRaycastResultState`](../enums/ue_ue.EMagicLeapRaycastResultState.md) |
| `HitPoint` | [`Vector`](ue_ue_s.Vector.md) |
| `Normal` | [`Vector`](ue_ue_s.Vector.md) |
| `Confidence` | `number` |
| `UserData` | `number` |

## Properties

### Confidence

• **Confidence**: `number`

___

### HitPoint

• **HitPoint**: [`Vector`](ue_ue_s.Vector.md)

___

### HitState

• **HitState**: [`EMagicLeapRaycastResultState`](../enums/ue_ue.EMagicLeapRaycastResultState.md)

___

### Normal

• **Normal**: [`Vector`](ue_ue_s.Vector.md)

___

### UserData

• **UserData**: `number`

___

### \_\_tid\_MagicLeapRaycastHitResult\_\_

• `Private` **\_\_tid\_MagicLeapRaycastHitResult\_\_**: `boolean`

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
