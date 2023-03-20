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

#### Defined in

[ue/ue.d.ts:63601](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63601)

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

#### Defined in

[ue/ue.d.ts:63602](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63602)

## Properties

### DirectionProperty

• **DirectionProperty**: [`Property`](ue_ue.Property.md)

#### Defined in

[ue/ue.d.ts:63618](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63618)

___

### DirectionPropertyName

• **DirectionPropertyName**: `string`

#### Defined in

[ue/ue.d.ts:63617](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63617)

___

### Events

• **Events**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineEventEntry`](ue_ue.TimelineEventEntry.md)\>

#### Defined in

[ue/ue.d.ts:63610](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63610)

___

### InterpFloats

• **InterpFloats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineFloatTrack`](ue_ue.TimelineFloatTrack.md)\>

#### Defined in

[ue/ue.d.ts:63612](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63612)

___

### InterpLinearColors

• **InterpLinearColors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineLinearColorTrack`](ue_ue.TimelineLinearColorTrack.md)\>

#### Defined in

[ue/ue.d.ts:63613](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63613)

___

### InterpVectors

• **InterpVectors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TimelineVectorTrack`](ue_ue.TimelineVectorTrack.md)\>

#### Defined in

[ue/ue.d.ts:63611](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63611)

___

### Length

• **Length**: `number`

#### Defined in

[ue/ue.d.ts:63607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63607)

___

### LengthMode

• **LengthMode**: [`ETimelineLengthMode`](../enums/ue_ue.ETimelineLengthMode.md)

#### Defined in

[ue/ue.d.ts:63603](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63603)

___

### PlayRate

• **PlayRate**: `number`

#### Defined in

[ue/ue.d.ts:63608](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63608)

___

### Position

• **Position**: `number`

#### Defined in

[ue/ue.d.ts:63609](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63609)

___

### PropertySetObject

• **PropertySetObject**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Object`](ue_ue.Object.md)\>

#### Defined in

[ue/ue.d.ts:63616](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63616)

___

### TimelineFinishedFunc

• **TimelineFinishedFunc**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:63615](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63615)

___

### TimelinePostUpdateFunc

• **TimelinePostUpdateFunc**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:63614](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63614)

___

### \_\_tid\_Timeline\_\_

• `Private` **\_\_tid\_Timeline\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:63624](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63624)

___

### bLooping

• **bLooping**: `boolean`

#### Defined in

[ue/ue.d.ts:63604](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63604)

___

### bPlaying

• **bPlaying**: `boolean`

#### Defined in

[ue/ue.d.ts:63606](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63606)

___

### bReversePlayback

• **bReversePlayback**: `boolean`

#### Defined in

[ue/ue.d.ts:63605](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63605)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:63622](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63622)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:63623](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L63623)
