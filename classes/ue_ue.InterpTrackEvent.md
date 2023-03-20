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

#### Defined in

[ue/ue.d.ts:39903](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39903)

## Properties

### ActiveCondition

• **ActiveCondition**: [`ETrackActiveCondition`](../enums/ue_ue.ETrackActiveCondition.md)

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[ActiveCondition](ue_ue.InterpTrack.md#activecondition)

#### Defined in

[ue/ue.d.ts:7487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7487)

___

### EventTrack

• **EventTrack**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EventTrackKey`](ue_ue.EventTrackKey.md)\>

#### Defined in

[ue/ue.d.ts:39904](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39904)

___

### SubTrackGroups

• **SubTrackGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SubTrackGroup`](ue_ue.SubTrackGroup.md)\>

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[SubTrackGroups](ue_ue.InterpTrack.md#subtrackgroups)

#### Defined in

[ue/ue.d.ts:7484](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7484)

___

### SubTracks

• **SubTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpTrack`](ue_ue.InterpTrack.md)\>

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[SubTracks](ue_ue.InterpTrack.md#subtracks)

#### Defined in

[ue/ue.d.ts:7483](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7483)

___

### SupportedSubTracks

• **SupportedSubTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SupportedSubTrackInfo`](ue_ue.SupportedSubTrackInfo.md)\>

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[SupportedSubTracks](ue_ue.InterpTrack.md#supportedsubtracks)

#### Defined in

[ue/ue.d.ts:7485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7485)

___

### TrackIcon

• **TrackIcon**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[TrackIcon](ue_ue.InterpTrack.md#trackicon)

#### Defined in

[ue/ue.d.ts:7493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7493)

___

### TrackInstClass

• **TrackInstClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[TrackInstClass](ue_ue.InterpTrack.md#trackinstclass)

#### Defined in

[ue/ue.d.ts:7486](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7486)

___

### TrackTitle

• **TrackTitle**: `string`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[TrackTitle](ue_ue.InterpTrack.md#tracktitle)

#### Defined in

[ue/ue.d.ts:7488](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7488)

___

### \_\_tid\_InterpTrackEvent\_\_

• **\_\_tid\_InterpTrackEvent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:39913](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39913)

___

### \_\_tid\_InterpTrack\_\_

• **\_\_tid\_InterpTrack\_\_**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[__tid_InterpTrack__](ue_ue.InterpTrack.md#__tid_interptrack__)

#### Defined in

[ue/ue.d.ts:7503](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7503)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[__tid_Object__](ue_ue.InterpTrack.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bDirGroupOnly

• **bDirGroupOnly**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bDirGroupOnly](ue_ue.InterpTrack.md#bdirgrouponly)

#### Defined in

[ue/ue.d.ts:7490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7490)

___

### bDisableTrack

• **bDisableTrack**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bDisableTrack](ue_ue.InterpTrack.md#bdisabletrack)

#### Defined in

[ue/ue.d.ts:7491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7491)

___

### bFireEventsWhenBackwards

• **bFireEventsWhenBackwards**: `boolean`

#### Defined in

[ue/ue.d.ts:39906](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39906)

___

### bFireEventsWhenForwards

• **bFireEventsWhenForwards**: `boolean`

#### Defined in

[ue/ue.d.ts:39905](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39905)

___

### bFireEventsWhenJumpingForwards

• **bFireEventsWhenJumpingForwards**: `boolean`

#### Defined in

[ue/ue.d.ts:39907](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39907)

___

### bIsAnimControlTrack

• **bIsAnimControlTrack**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bIsAnimControlTrack](ue_ue.InterpTrack.md#bisanimcontroltrack)

#### Defined in

[ue/ue.d.ts:7494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7494)

___

### bIsCollapsed

• **bIsCollapsed**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bIsCollapsed](ue_ue.InterpTrack.md#biscollapsed)

#### Defined in

[ue/ue.d.ts:7498](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7498)

___

### bIsRecording

• **bIsRecording**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bIsRecording](ue_ue.InterpTrack.md#bisrecording)

#### Defined in

[ue/ue.d.ts:7497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7497)

___

### bIsSelected

• **bIsSelected**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bIsSelected](ue_ue.InterpTrack.md#bisselected)

#### Defined in

[ue/ue.d.ts:7492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7492)

___

### bOnePerGroup

• **bOnePerGroup**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bOnePerGroup](ue_ue.InterpTrack.md#bonepergroup)

#### Defined in

[ue/ue.d.ts:7489](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7489)

___

### bSubTrackOnly

• **bSubTrackOnly**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bSubTrackOnly](ue_ue.InterpTrack.md#bsubtrackonly)

#### Defined in

[ue/ue.d.ts:7495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7495)

___

### bUseCustomEventName

• **bUseCustomEventName**: `boolean`

#### Defined in

[ue/ue.d.ts:39908](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39908)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bVisible](ue_ue.InterpTrack.md#bvisible)

#### Defined in

[ue/ue.d.ts:7496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7496)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[GetClass](ue_ue.InterpTrack.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[GetName](ue_ue.InterpTrack.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[GetOuter](ue_ue.InterpTrack.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[GetWorld](ue_ue.InterpTrack.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:39910](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39910)

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

#### Defined in

[ue/ue.d.ts:39911](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39911)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpTrack](ue_ue.InterpTrack.md).[StaticClass](ue_ue.InterpTrack.md#staticclass)

#### Defined in

[ue/ue.d.ts:39909](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39909)
