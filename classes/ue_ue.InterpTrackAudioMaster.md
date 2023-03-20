[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpTrackAudioMaster

# Class: InterpTrackAudioMaster

[ue/ue](../modules/ue_ue.md).InterpTrackAudioMaster

## Hierarchy

- [`InterpTrackVectorBase`](ue_ue.InterpTrackVectorBase.md)

  ↳ **`InterpTrackAudioMaster`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpTrackAudioMaster.md#constructor)

### Properties

- [ActiveCondition](ue_ue.InterpTrackAudioMaster.md#activecondition)
- [CurveTension](ue_ue.InterpTrackAudioMaster.md#curvetension)
- [SubTrackGroups](ue_ue.InterpTrackAudioMaster.md#subtrackgroups)
- [SubTracks](ue_ue.InterpTrackAudioMaster.md#subtracks)
- [SupportedSubTracks](ue_ue.InterpTrackAudioMaster.md#supportedsubtracks)
- [TrackIcon](ue_ue.InterpTrackAudioMaster.md#trackicon)
- [TrackInstClass](ue_ue.InterpTrackAudioMaster.md#trackinstclass)
- [TrackTitle](ue_ue.InterpTrackAudioMaster.md#tracktitle)
- [VectorTrack](ue_ue.InterpTrackAudioMaster.md#vectortrack)
- [\_\_tid\_InterpTrackAudioMaster\_\_](ue_ue.InterpTrackAudioMaster.md#__tid_interptrackaudiomaster__)
- [\_\_tid\_InterpTrackVectorBase\_\_](ue_ue.InterpTrackAudioMaster.md#__tid_interptrackvectorbase__)
- [\_\_tid\_InterpTrack\_\_](ue_ue.InterpTrackAudioMaster.md#__tid_interptrack__)
- [\_\_tid\_Object\_\_](ue_ue.InterpTrackAudioMaster.md#__tid_object__)
- [bDirGroupOnly](ue_ue.InterpTrackAudioMaster.md#bdirgrouponly)
- [bDisableTrack](ue_ue.InterpTrackAudioMaster.md#bdisabletrack)
- [bIsAnimControlTrack](ue_ue.InterpTrackAudioMaster.md#bisanimcontroltrack)
- [bIsCollapsed](ue_ue.InterpTrackAudioMaster.md#biscollapsed)
- [bIsRecording](ue_ue.InterpTrackAudioMaster.md#bisrecording)
- [bIsSelected](ue_ue.InterpTrackAudioMaster.md#bisselected)
- [bOnePerGroup](ue_ue.InterpTrackAudioMaster.md#bonepergroup)
- [bSubTrackOnly](ue_ue.InterpTrackAudioMaster.md#bsubtrackonly)
- [bVisible](ue_ue.InterpTrackAudioMaster.md#bvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpTrackAudioMaster.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpTrackAudioMaster.md#executeubergraph)
- [GetClass](ue_ue.InterpTrackAudioMaster.md#getclass)
- [GetName](ue_ue.InterpTrackAudioMaster.md#getname)
- [GetOuter](ue_ue.InterpTrackAudioMaster.md#getouter)
- [GetWorld](ue_ue.InterpTrackAudioMaster.md#getworld)
- [Find](ue_ue.InterpTrackAudioMaster.md#find)
- [Load](ue_ue.InterpTrackAudioMaster.md#load)
- [StaticClass](ue_ue.InterpTrackAudioMaster.md#staticclass)

## Constructors

### constructor

• **new InterpTrackAudioMaster**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[constructor](ue_ue.InterpTrackVectorBase.md#constructor)

## Properties

### ActiveCondition

• **ActiveCondition**: [`ETrackActiveCondition`](../enums/ue_ue.ETrackActiveCondition.md)

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[ActiveCondition](ue_ue.InterpTrackVectorBase.md#activecondition)

___

### CurveTension

• **CurveTension**: `number`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[CurveTension](ue_ue.InterpTrackVectorBase.md#curvetension)

___

### SubTrackGroups

• **SubTrackGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SubTrackGroup`](ue_ue.SubTrackGroup.md)\>

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[SubTrackGroups](ue_ue.InterpTrackVectorBase.md#subtrackgroups)

___

### SubTracks

• **SubTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpTrack`](ue_ue.InterpTrack.md)\>

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[SubTracks](ue_ue.InterpTrackVectorBase.md#subtracks)

___

### SupportedSubTracks

• **SupportedSubTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SupportedSubTrackInfo`](ue_ue.SupportedSubTrackInfo.md)\>

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[SupportedSubTracks](ue_ue.InterpTrackVectorBase.md#supportedsubtracks)

___

### TrackIcon

• **TrackIcon**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[TrackIcon](ue_ue.InterpTrackVectorBase.md#trackicon)

___

### TrackInstClass

• **TrackInstClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[TrackInstClass](ue_ue.InterpTrackVectorBase.md#trackinstclass)

___

### TrackTitle

• **TrackTitle**: `string`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[TrackTitle](ue_ue.InterpTrackVectorBase.md#tracktitle)

___

### VectorTrack

• **VectorTrack**: [`InterpCurveVector`](ue_ue.InterpCurveVector.md)

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[VectorTrack](ue_ue.InterpTrackVectorBase.md#vectortrack)

___

### \_\_tid\_InterpTrackAudioMaster\_\_

• **\_\_tid\_InterpTrackAudioMaster\_\_**: `boolean`

___

### \_\_tid\_InterpTrackVectorBase\_\_

• **\_\_tid\_InterpTrackVectorBase\_\_**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[__tid_InterpTrackVectorBase__](ue_ue.InterpTrackVectorBase.md#__tid_interptrackvectorbase__)

___

### \_\_tid\_InterpTrack\_\_

• **\_\_tid\_InterpTrack\_\_**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[__tid_InterpTrack__](ue_ue.InterpTrackVectorBase.md#__tid_interptrack__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[__tid_Object__](ue_ue.InterpTrackVectorBase.md#__tid_object__)

___

### bDirGroupOnly

• **bDirGroupOnly**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bDirGroupOnly](ue_ue.InterpTrackVectorBase.md#bdirgrouponly)

___

### bDisableTrack

• **bDisableTrack**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bDisableTrack](ue_ue.InterpTrackVectorBase.md#bdisabletrack)

___

### bIsAnimControlTrack

• **bIsAnimControlTrack**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bIsAnimControlTrack](ue_ue.InterpTrackVectorBase.md#bisanimcontroltrack)

___

### bIsCollapsed

• **bIsCollapsed**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bIsCollapsed](ue_ue.InterpTrackVectorBase.md#biscollapsed)

___

### bIsRecording

• **bIsRecording**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bIsRecording](ue_ue.InterpTrackVectorBase.md#bisrecording)

___

### bIsSelected

• **bIsSelected**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bIsSelected](ue_ue.InterpTrackVectorBase.md#bisselected)

___

### bOnePerGroup

• **bOnePerGroup**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bOnePerGroup](ue_ue.InterpTrackVectorBase.md#bonepergroup)

___

### bSubTrackOnly

• **bSubTrackOnly**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bSubTrackOnly](ue_ue.InterpTrackVectorBase.md#bsubtrackonly)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bVisible](ue_ue.InterpTrackVectorBase.md#bvisible)

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

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[CreateDefaultSubobject](ue_ue.InterpTrackVectorBase.md#createdefaultsubobject)

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

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[ExecuteUbergraph](ue_ue.InterpTrackVectorBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[GetClass](ue_ue.InterpTrackVectorBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[GetName](ue_ue.InterpTrackVectorBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[GetOuter](ue_ue.InterpTrackVectorBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[GetWorld](ue_ue.InterpTrackVectorBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpTrackAudioMaster`](ue_ue.InterpTrackAudioMaster.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpTrackAudioMaster`](ue_ue.InterpTrackAudioMaster.md)

#### Overrides

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[Find](ue_ue.InterpTrackVectorBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpTrackAudioMaster`](ue_ue.InterpTrackAudioMaster.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpTrackAudioMaster`](ue_ue.InterpTrackAudioMaster.md)

#### Overrides

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[Load](ue_ue.InterpTrackVectorBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[StaticClass](ue_ue.InterpTrackVectorBase.md#staticclass)
