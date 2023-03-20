[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpTrackToggle

# Class: InterpTrackToggle

[ue/ue](../modules/ue_ue.md).InterpTrackToggle

## Hierarchy

- [`InterpTrack`](ue_ue.InterpTrack.md)

  ↳ **`InterpTrackToggle`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpTrackToggle.md#constructor)

### Properties

- [ActiveCondition](ue_ue.InterpTrackToggle.md#activecondition)
- [SubTrackGroups](ue_ue.InterpTrackToggle.md#subtrackgroups)
- [SubTracks](ue_ue.InterpTrackToggle.md#subtracks)
- [SupportedSubTracks](ue_ue.InterpTrackToggle.md#supportedsubtracks)
- [ToggleTrack](ue_ue.InterpTrackToggle.md#toggletrack)
- [TrackIcon](ue_ue.InterpTrackToggle.md#trackicon)
- [TrackInstClass](ue_ue.InterpTrackToggle.md#trackinstclass)
- [TrackTitle](ue_ue.InterpTrackToggle.md#tracktitle)
- [\_\_tid\_InterpTrackToggle\_\_](ue_ue.InterpTrackToggle.md#__tid_interptracktoggle__)
- [\_\_tid\_InterpTrack\_\_](ue_ue.InterpTrackToggle.md#__tid_interptrack__)
- [\_\_tid\_Object\_\_](ue_ue.InterpTrackToggle.md#__tid_object__)
- [bActivateSystemEachUpdate](ue_ue.InterpTrackToggle.md#bactivatesystemeachupdate)
- [bActivateWithJustAttachedFlag](ue_ue.InterpTrackToggle.md#bactivatewithjustattachedflag)
- [bDirGroupOnly](ue_ue.InterpTrackToggle.md#bdirgrouponly)
- [bDisableTrack](ue_ue.InterpTrackToggle.md#bdisabletrack)
- [bFireEventsWhenBackwards](ue_ue.InterpTrackToggle.md#bfireeventswhenbackwards)
- [bFireEventsWhenForwards](ue_ue.InterpTrackToggle.md#bfireeventswhenforwards)
- [bFireEventsWhenJumpingForwards](ue_ue.InterpTrackToggle.md#bfireeventswhenjumpingforwards)
- [bIsAnimControlTrack](ue_ue.InterpTrackToggle.md#bisanimcontroltrack)
- [bIsCollapsed](ue_ue.InterpTrackToggle.md#biscollapsed)
- [bIsRecording](ue_ue.InterpTrackToggle.md#bisrecording)
- [bIsSelected](ue_ue.InterpTrackToggle.md#bisselected)
- [bOnePerGroup](ue_ue.InterpTrackToggle.md#bonepergroup)
- [bSubTrackOnly](ue_ue.InterpTrackToggle.md#bsubtrackonly)
- [bVisible](ue_ue.InterpTrackToggle.md#bvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpTrackToggle.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpTrackToggle.md#executeubergraph)
- [GetClass](ue_ue.InterpTrackToggle.md#getclass)
- [GetName](ue_ue.InterpTrackToggle.md#getname)
- [GetOuter](ue_ue.InterpTrackToggle.md#getouter)
- [GetWorld](ue_ue.InterpTrackToggle.md#getworld)
- [Find](ue_ue.InterpTrackToggle.md#find)
- [Load](ue_ue.InterpTrackToggle.md#load)
- [StaticClass](ue_ue.InterpTrackToggle.md#staticclass)

## Constructors

### constructor

• **new InterpTrackToggle**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### ToggleTrack

• **ToggleTrack**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ToggleTrackKey`](ue_ue.ToggleTrackKey.md)\>

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

### \_\_tid\_InterpTrackToggle\_\_

• **\_\_tid\_InterpTrackToggle\_\_**: `boolean`

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

### bActivateSystemEachUpdate

• **bActivateSystemEachUpdate**: `boolean`

___

### bActivateWithJustAttachedFlag

• **bActivateWithJustAttachedFlag**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpTrackToggle`](ue_ue.InterpTrackToggle.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpTrackToggle`](ue_ue.InterpTrackToggle.md)

#### Overrides

[InterpTrack](ue_ue.InterpTrack.md).[Find](ue_ue.InterpTrack.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpTrackToggle`](ue_ue.InterpTrackToggle.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpTrackToggle`](ue_ue.InterpTrackToggle.md)

#### Overrides

[InterpTrack](ue_ue.InterpTrack.md).[Load](ue_ue.InterpTrack.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpTrack](ue_ue.InterpTrack.md).[StaticClass](ue_ue.InterpTrack.md#staticclass)
