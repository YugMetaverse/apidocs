[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TimelineVectorTrack

# Class: TimelineVectorTrack

[ue/ue](../modules/ue_ue.md).TimelineVectorTrack

## Table of contents

### Constructors

- [constructor](ue_ue.TimelineVectorTrack.md#constructor)

### Properties

- [InterpFunc](ue_ue.TimelineVectorTrack.md#interpfunc)
- [TrackName](ue_ue.TimelineVectorTrack.md#trackname)
- [VectorCurve](ue_ue.TimelineVectorTrack.md#vectorcurve)
- [VectorProperty](ue_ue.TimelineVectorTrack.md#vectorproperty)
- [VectorPropertyName](ue_ue.TimelineVectorTrack.md#vectorpropertyname)
- [\_\_tid\_TimelineVectorTrack\_\_](ue_ue.TimelineVectorTrack.md#__tid_timelinevectortrack__)

### Methods

- [StaticClass](ue_ue.TimelineVectorTrack.md#staticclass)
- [StaticStruct](ue_ue.TimelineVectorTrack.md#staticstruct)

## Constructors

### constructor

• **new TimelineVectorTrack**()

• **new TimelineVectorTrack**(`VectorCurve`, `InterpFunc`, `TrackName`, `VectorPropertyName`, `VectorProperty`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VectorCurve` | [`CurveVector`](ue_ue.CurveVector.md) |
| `InterpFunc` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`Output`: [`Vector`](ue_ue_s.Vector.md)) => `void`\> |
| `TrackName` | `string` |
| `VectorPropertyName` | `string` |
| `VectorProperty` | [`StructProperty`](ue_ue.StructProperty.md) |

## Properties

### InterpFunc

• **InterpFunc**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`Output`: [`Vector`](ue_ue_s.Vector.md)) => `void`\>

___

### TrackName

• **TrackName**: `string`

___

### VectorCurve

• **VectorCurve**: [`CurveVector`](ue_ue.CurveVector.md)

___

### VectorProperty

• **VectorProperty**: [`StructProperty`](ue_ue.StructProperty.md)

___

### VectorPropertyName

• **VectorPropertyName**: `string`

___

### \_\_tid\_TimelineVectorTrack\_\_

• `Private` **\_\_tid\_TimelineVectorTrack\_\_**: `boolean`

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
