[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpTrackEvent

# Class: InterpTrackEvent

[ue/ue](../modules/ue_ue.md).InterpTrackEvent

## Hierarchy

- [`InterpTrack`](ue_ue.InterpTrack.md)

  ↳ **`InterpTrackEvent`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpTrackEvent.md#constructor)

### Properties

- [ActiveCondition](ue_ue.InterpTrackEvent.md#activecondition)
- [EventTrack](ue_ue.InterpTrackEvent.md#eventtrack)
- [SubTrackGroups](ue_ue.InterpTrackEvent.md#subtrackgroups)
- [SubTracks](ue_ue.InterpTrackEvent.md#subtracks)
- [SupportedSubTracks](ue_ue.InterpTrackEvent.md#supportedsubtracks)
- [TrackIcon](ue_ue.InterpTrackEvent.md#trackicon)
- [TrackInstClass](ue_ue.InterpTrackEvent.md#trackinstclass)
- [TrackTitle](ue_ue.InterpTrackEvent.md#tracktitle)
- [\_\_tid\_InterpTrackEvent\_\_](ue_ue.InterpTrackEvent.md#__tid_interptrackevent__)
- [\_\_tid\_InterpTrack\_\_](ue_ue.InterpTrackEvent.md#__tid_interptrack__)
- [\_\_tid\_Object\_\_](ue_ue.InterpTrackEvent.md#__tid_object__)
- [bDirGroupOnly](ue_ue.InterpTrackEvent.md#bdirgrouponly)
- [bDisableTrack](ue_ue.InterpTrackEvent.md#bdisabletrack)
- [bFireEventsWhenBackwards](ue_ue.InterpTrackEvent.md#bfireeventswhenbackwards)
- [bFireEventsWhenForwards](ue_ue.InterpTrackEvent.md#bfireeventswhenforwards)
- [bFireEventsWhenJumpingForwards](ue_ue.InterpTrackEvent.md#bfireeventswhenjumpingforwards)
- [bIsAnimControlTrack](ue_ue.InterpTrackEvent.md#bisanimcontroltrack)
- [bIsCollapsed](ue_ue.InterpTrackEvent.md#biscollapsed)
- [bIsRecording](ue_ue.InterpTrackEvent.md#bisrecording)
- [bIsSelected](ue_ue.InterpTrackEvent.md#bisselected)
- [bOnePerGroup](ue_ue.InterpTrackEvent.md#bonepergroup)
- [bSubTrackOnly](ue_ue.InterpTrackEvent.md#bsubtrackonly)
- [bUseCustomEventName](ue_ue.InterpTrackEvent.md#busecustomeventname)
- [bVisible](ue_ue.InterpTrackEvent.md#bvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpTrackEvent.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpTrackEvent.md#executeubergraph)
- [GetClass](ue_ue.InterpTrackEvent.md#getclass)
- [GetName](ue_ue.InterpTrackEvent.md#getname)
- [GetOuter](ue_ue.InterpTrackEvent.md#getouter)
- [GetWorld](ue_ue.InterpTrackEvent.md#getworld)
- [Find](ue_ue.InterpTrackEvent.md#find)
- [Load](ue_ue.InterpTrackEvent.md#load)
- [StaticClass](ue_ue.InterpTrackEvent.md#staticclass)

## Constructors

### constructor

• **new InterpTrackEvent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InterpTrack](ue_ue.InterpTrack.md).[constructor](ue_ue.InterpTrack.md#constructor)

## Properties

### ActiveCondition

• **ActiveCondition**: [`ETrackActiveCondition`](../enums/ue_ue.ETrackActiveCondition.md)

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[ActiveCondition](ue_ue.InterpTrack.md#activecondition)

___

### EventTrack

• **EventTrack**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EventTrackKey`](ue_ue.EventTrackKey.md)\>

___

### SubTrackGroups

• **SubTrackGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SubTrackGroup`](ue_ue.SubTrackGroup.md)\>

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[SubTrackGroups](ue_ue.InterpTrack.md#subtrackgroups)

___

### SubTracks

• **SubTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpTrack`](ue_ue.InterpTrack.md)\>

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[SubTracks](ue_ue.InterpTrack.md#subtracks)

___

### SupportedSubTracks

• **SupportedSubTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SupportedSubTrackInfo`](ue_ue.SupportedSubTrackInfo.md)\>

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[SupportedSubTracks](ue_ue.InterpTrack.md#supportedsubtracks)

___

### TrackIcon

• **TrackIcon**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[TrackIcon](ue_ue.InterpTrack.md#trackicon)

___

### TrackInstClass

• **TrackInstClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[TrackInstClass](ue_ue.InterpTrack.md#trackinstclass)

___

### TrackTitle

• **TrackTitle**: `string`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[TrackTitle](ue_ue.InterpTrack.md#tracktitle)

___

### \_\_tid\_InterpTrackEvent\_\_

• **\_\_tid\_InterpTrackEvent\_\_**: `boolean`

___

### \_\_tid\_InterpTrack\_\_

• **\_\_tid\_InterpTrack\_\_**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[__tid_InterpTrack__](ue_ue.InterpTrack.md#__tid_interptrack__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[__tid_Object__](ue_ue.InterpTrack.md#__tid_object__)

___

### bDirGroupOnly

• **bDirGroupOnly**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bDirGroupOnly](ue_ue.InterpTrack.md#bdirgrouponly)

___

### bDisableTrack

• **bDisableTrack**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bDisableTrack](ue_ue.InterpTrack.md#bdisabletrack)

___

### bFireEventsWhenBackwards

• **bFireEventsWhenBackwards**: `boolean`

___

### bFireEventsWhenForwards

• **bFireEventsWhenForwards**: `boolean`

___

### bFireEventsWhenJumpingForwards

• **bFireEventsWhenJumpingForwards**: `boolean`

___

### bIsAnimControlTrack

• **bIsAnimControlTrack**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bIsAnimControlTrack](ue_ue.InterpTrack.md#bisanimcontroltrack)

___

### bIsCollapsed

• **bIsCollapsed**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bIsCollapsed](ue_ue.InterpTrack.md#biscollapsed)

___

### bIsRecording

• **bIsRecording**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bIsRecording](ue_ue.InterpTrack.md#bisrecording)

___

### bIsSelected

• **bIsSelected**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bIsSelected](ue_ue.InterpTrack.md#bisselected)

___

### bOnePerGroup

• **bOnePerGroup**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bOnePerGroup](ue_ue.InterpTrack.md#bonepergroup)

___

### bSubTrackOnly

• **bSubTrackOnly**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bSubTrackOnly](ue_ue.InterpTrack.md#bsubtrackonly)

___

### bUseCustomEventName

• **bUseCustomEventName**: `boolean`

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bVisible](ue_ue.InterpTrack.md#bvisible)

## Methods

### CreateDefaultSubobject

▸ **CreateDefaultSubobject**(`p0`, `p1`, `p2`, `p3`, `p4`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `string` |
| `p1` | [`Class`](ue_ue.Class.md) |
| `p2` | [`Class`](ue_ue.Class.md) |
| `p3` | `boolean` |
| `p4` | `boolean` |

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[CreateDefaultSubobject](ue_ue.InterpTrack.md#createdefaultsubobject)

___

### ExecuteUbergraph

▸ **ExecuteUbergraph**(`EntryPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryPoint` | `number` |

#### Returns

`void`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[ExecuteUbergraph](ue_ue.InterpTrack.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[GetClass](ue_ue.InterpTrack.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[GetName](ue_ue.InterpTrack.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[GetOuter](ue_ue.InterpTrack.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[GetWorld](ue_ue.InterpTrack.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpTrackEvent`](ue_ue.InterpTrackEvent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpTrackEvent`](ue_ue.InterpTrackEvent.md)

#### Overrides

[InterpTrack](ue_ue.InterpTrack.md).[Find](ue_ue.InterpTrack.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpTrackEvent`](ue_ue.InterpTrackEvent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpTrackEvent`](ue_ue.InterpTrackEvent.md)

#### Overrides

[InterpTrack](ue_ue.InterpTrack.md).[Load](ue_ue.InterpTrack.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpTrack](ue_ue.InterpTrack.md).[StaticClass](ue_ue.InterpTrack.md#staticclass)
