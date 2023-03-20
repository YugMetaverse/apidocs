[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TimelineFloatTrack

# Class: TimelineFloatTrack

[ue/ue](../modules/ue_ue.md).TimelineFloatTrack

## Table of contents

### Constructors

- [constructor](ue_ue.TimelineFloatTrack.md#constructor)

### Properties

- [FloatCurve](ue_ue.TimelineFloatTrack.md#floatcurve)
- [FloatProperty](ue_ue.TimelineFloatTrack.md#floatproperty)
- [FloatPropertyName](ue_ue.TimelineFloatTrack.md#floatpropertyname)
- [InterpFunc](ue_ue.TimelineFloatTrack.md#interpfunc)
- [TrackName](ue_ue.TimelineFloatTrack.md#trackname)
- [\_\_tid\_TimelineFloatTrack\_\_](ue_ue.TimelineFloatTrack.md#__tid_timelinefloattrack__)

### Methods

- [StaticClass](ue_ue.TimelineFloatTrack.md#staticclass)
- [StaticStruct](ue_ue.TimelineFloatTrack.md#staticstruct)

## Constructors

### constructor

• **new TimelineFloatTrack**()

• **new TimelineFloatTrack**(`FloatCurve`, `InterpFunc`, `TrackName`, `FloatPropertyName`, `FloatProperty`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `FloatCurve` | [`CurveFloat`](ue_ue.CurveFloat.md) |
| `InterpFunc` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`Output`: `number`) => `void`\> |
| `TrackName` | `string` |
| `FloatPropertyName` | `string` |
| `FloatProperty` | [`FloatProperty`](ue_ue.FloatProperty.md) |

## Properties

### FloatCurve

• **FloatCurve**: [`CurveFloat`](ue_ue.CurveFloat.md)

___

### FloatProperty

• **FloatProperty**: [`FloatProperty`](ue_ue.FloatProperty.md)

___

### FloatPropertyName

• **FloatPropertyName**: `string`

___

### InterpFunc

• **InterpFunc**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`Output`: `number`) => `void`\>

___

### TrackName

• **TrackName**: `string`

___

### \_\_tid\_TimelineFloatTrack\_\_

• `Private` **\_\_tid\_TimelineFloatTrack\_\_**: `boolean`

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
