[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Timeline

# Class: Timeline

[ue/ue](../modules/ue_ue.md).Timeline

## Table of contents

### Constructors

- [constructor](ue_ue.Timeline.md#constructor)

### Properties

- [DirectionProperty](ue_ue.Timeline.md#directionproperty)
- [DirectionPropertyName](ue_ue.Timeline.md#directionpropertyname)
- [Events](ue_ue.Timeline.md#events)
- [InterpFloats](ue_ue.Timeline.md#interpfloats)
- [InterpLinearColors](ue_ue.Timeline.md#interplinearcolors)
- [InterpVectors](ue_ue.Timeline.md#interpvectors)
- [Length](ue_ue.Timeline.md#length)
- [LengthMode](ue_ue.Timeline.md#lengthmode)
- [PlayRate](ue_ue.Timeline.md#playrate)
- [Position](ue_ue.Timeline.md#position)
- [PropertySetObject](ue_ue.Timeline.md#propertysetobject)
- [TimelineFinishedFunc](ue_ue.Timeline.md#timelinefinishedfunc)
- [TimelinePostUpdateFunc](ue_ue.Timeline.md#timelinepostupdatefunc)
- [\_\_tid\_Timeline\_\_](ue_ue.Timeline.md#__tid_timeline__)
- [bLooping](ue_ue.Timeline.md#blooping)
- [bPlaying](ue_ue.Timeline.md#bplaying)
- [bReversePlayback](ue_ue.Timeline.md#breverseplayback)

### Methods

- [StaticClass](ue_ue.Timeline.md#staticclass)
- [StaticStruct](ue_ue.Timeline.md#staticstruct)

## Constructors

### constructor

• **new Timeline**()

• **new Timeline**(`LengthMode`, `bLooping`, `bReversePlayback`, `bPlaying`, `Length`, `PlayRate`, `Position`, `Events`, `InterpVectors`, `InterpFloats`, `InterpLinearColors`, `TimelinePostUpdateFunc`, `TimelineFinishedFunc`, `PropertySetObject`, `DirectionPropertyName`, `DirectionProperty`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `LengthMode` | [`ETimelineLengthMode`](../enums/ue_ue.ETimelineLengthMode.md) |
| `bLooping` | `boolean` |
| `bReversePlayback` | `boolean` |
| `bPlaying` | `boolean` |
| `Length` | `number` |
| `PlayRate` | `number` |
| `Position` | `number` |
| `Events` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineEventEntry`](ue_ue.TimelineEventEntry.md)\> |
| `InterpVectors` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineVectorTrack`](ue_ue.TimelineVectorTrack.md)\> |
| `InterpFloats` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineFloatTrack`](ue_ue.TimelineFloatTrack.md)\> |
| `InterpLinearColors` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineLinearColorTrack`](ue_ue.TimelineLinearColorTrack.md)\> |
| `TimelinePostUpdateFunc` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\> |
| `TimelineFinishedFunc` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\> |
| `PropertySetObject` | [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\> |
| `DirectionPropertyName` | `string` |
| `DirectionProperty` | [`Property`](ue_ue.Property.md) |

## Properties

### DirectionProperty

• **DirectionProperty**: [`Property`](ue_ue.Property.md)

___

### DirectionPropertyName

• **DirectionPropertyName**: `string`

___

### Events

• **Events**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineEventEntry`](ue_ue.TimelineEventEntry.md)\>

___

### InterpFloats

• **InterpFloats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineFloatTrack`](ue_ue.TimelineFloatTrack.md)\>

___

### InterpLinearColors

• **InterpLinearColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineLinearColorTrack`](ue_ue.TimelineLinearColorTrack.md)\>

___

### InterpVectors

• **InterpVectors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineVectorTrack`](ue_ue.TimelineVectorTrack.md)\>

___

### Length

• **Length**: `number`

___

### LengthMode

• **LengthMode**: [`ETimelineLengthMode`](../enums/ue_ue.ETimelineLengthMode.md)

___

### PlayRate

• **PlayRate**: `number`

___

### Position

• **Position**: `number`

___

### PropertySetObject

• **PropertySetObject**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>

___

### TimelineFinishedFunc

• **TimelineFinishedFunc**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\>

___

### TimelinePostUpdateFunc

• **TimelinePostUpdateFunc**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\>

___

### \_\_tid\_Timeline\_\_

• `Private` **\_\_tid\_Timeline\_\_**: `boolean`

___

### bLooping

• **bLooping**: `boolean`

___

### bPlaying

• **bPlaying**: `boolean`

___

### bReversePlayback

• **bReversePlayback**: `boolean`

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
