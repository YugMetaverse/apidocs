[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MagicLeapPlaneResult

# Class: MagicLeapPlaneResult

[ue/ue](../modules/ue_ue.md).MagicLeapPlaneResult

## Table of contents

### Constructors

- [constructor](ue_ue.MagicLeapPlaneResult.md#constructor)

### Properties

- [ContentOrientation](ue_ue.MagicLeapPlaneResult.md#contentorientation)
- [ID](ue_ue.MagicLeapPlaneResult.md#id)
- [PlaneDimensions](ue_ue.MagicLeapPlaneResult.md#planedimensions)
- [PlaneFlags](ue_ue.MagicLeapPlaneResult.md#planeflags)
- [PlaneOrientation](ue_ue.MagicLeapPlaneResult.md#planeorientation)
- [PlanePosition](ue_ue.MagicLeapPlaneResult.md#planeposition)
- [\_\_tid\_MagicLeapPlaneResult\_\_](ue_ue.MagicLeapPlaneResult.md#__tid_magicleapplaneresult__)

### Methods

- [StaticClass](ue_ue.MagicLeapPlaneResult.md#staticclass)
- [StaticStruct](ue_ue.MagicLeapPlaneResult.md#staticstruct)

## Constructors

### constructor

• **new MagicLeapPlaneResult**()

• **new MagicLeapPlaneResult**(`PlanePosition`, `PlaneOrientation`, `ContentOrientation`, `PlaneDimensions`, `PlaneFlags`, `ID`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PlanePosition` | [`Vector`](ue_ue_s.Vector.md) |
| `PlaneOrientation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `ContentOrientation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `PlaneDimensions` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `PlaneFlags` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EMagicLeapPlaneQueryFlags`](../enums/ue_ue.EMagicLeapPlaneQueryFlags.md)\> |
| `ID` | [`Guid`](ue_ue_s.Guid.md) |

## Properties

### ContentOrientation

• **ContentOrientation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### ID

• **ID**: [`Guid`](ue_ue_s.Guid.md)

___

### PlaneDimensions

• **PlaneDimensions**: [`Vector2D`](ue_ue_s.Vector2D.md)

___

### PlaneFlags

• **PlaneFlags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EMagicLeapPlaneQueryFlags`](../enums/ue_ue.EMagicLeapPlaneQueryFlags.md)\>

___

### PlaneOrientation

• **PlaneOrientation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### PlanePosition

• **PlanePosition**: [`Vector`](ue_ue_s.Vector.md)

___

### \_\_tid\_MagicLeapPlaneResult\_\_

• `Private` **\_\_tid\_MagicLeapPlaneResult\_\_**: `boolean`

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
