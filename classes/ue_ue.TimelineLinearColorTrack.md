[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TimelineLinearColorTrack

# Class: TimelineLinearColorTrack

[ue/ue](../modules/ue_ue.md).TimelineLinearColorTrack

## Table of contents

### Constructors

- [constructor](ue_ue.TimelineLinearColorTrack.md#constructor)

### Properties

- [InterpFunc](ue_ue.TimelineLinearColorTrack.md#interpfunc)
- [LinearColorCurve](ue_ue.TimelineLinearColorTrack.md#linearcolorcurve)
- [LinearColorProperty](ue_ue.TimelineLinearColorTrack.md#linearcolorproperty)
- [LinearColorPropertyName](ue_ue.TimelineLinearColorTrack.md#linearcolorpropertyname)
- [TrackName](ue_ue.TimelineLinearColorTrack.md#trackname)
- [\_\_tid\_TimelineLinearColorTrack\_\_](ue_ue.TimelineLinearColorTrack.md#__tid_timelinelinearcolortrack__)

### Methods

- [StaticClass](ue_ue.TimelineLinearColorTrack.md#staticclass)
- [StaticStruct](ue_ue.TimelineLinearColorTrack.md#staticstruct)

## Constructors

### constructor

• **new TimelineLinearColorTrack**()

• **new TimelineLinearColorTrack**(`LinearColorCurve`, `InterpFunc`, `TrackName`, `LinearColorPropertyName`, `LinearColorProperty`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `LinearColorCurve` | [`CurveLinearColor`](ue_ue.CurveLinearColor.md) |
| `InterpFunc` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`Output`: [`LinearColor`](ue_ue_s.LinearColor.md)) => `void`\> |
| `TrackName` | `string` |
| `LinearColorPropertyName` | `string` |
| `LinearColorProperty` | [`StructProperty`](ue_ue.StructProperty.md) |

## Properties

### InterpFunc

• **InterpFunc**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`Output`: [`LinearColor`](ue_ue_s.LinearColor.md)) => `void`\>

___

### LinearColorCurve

• **LinearColorCurve**: [`CurveLinearColor`](ue_ue.CurveLinearColor.md)

___

### LinearColorProperty

• **LinearColorProperty**: [`StructProperty`](ue_ue.StructProperty.md)

___

### LinearColorPropertyName

• **LinearColorPropertyName**: `string`

___

### TrackName

• **TrackName**: `string`

___

### \_\_tid\_TimelineLinearColorTrack\_\_

• `Private` **\_\_tid\_TimelineLinearColorTrack\_\_**: `boolean`

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
