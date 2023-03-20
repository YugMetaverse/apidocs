[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpTrack

# Class: InterpTrack

[ue/ue](../modules/ue_ue.md).InterpTrack

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`InterpTrack`**

  ↳↳ [`InterpTrackMove`](ue_ue.InterpTrackMove.md)

  ↳↳ [`InterpTrackFloatBase`](ue_ue.InterpTrackFloatBase.md)

  ↳↳ [`InterpTrackVectorBase`](ue_ue.InterpTrackVectorBase.md)

  ↳↳ [`InterpTrackBoolProp`](ue_ue.InterpTrackBoolProp.md)

  ↳↳ [`InterpTrackDirector`](ue_ue.InterpTrackDirector.md)

  ↳↳ [`InterpTrackEvent`](ue_ue.InterpTrackEvent.md)

  ↳↳ [`InterpTrackLinearColorBase`](ue_ue.InterpTrackLinearColorBase.md)

  ↳↳ [`InterpTrackParticleReplay`](ue_ue.InterpTrackParticleReplay.md)

  ↳↳ [`InterpTrackToggle`](ue_ue.InterpTrackToggle.md)

  ↳↳ [`InterpTrackVisibility`](ue_ue.InterpTrackVisibility.md)

## Table of contents

### Constructors

- [constructor](ue_ue.InterpTrack.md#constructor)

### Properties

- [ActiveCondition](ue_ue.InterpTrack.md#activecondition)
- [SubTrackGroups](ue_ue.InterpTrack.md#subtrackgroups)
- [SubTracks](ue_ue.InterpTrack.md#subtracks)
- [SupportedSubTracks](ue_ue.InterpTrack.md#supportedsubtracks)
- [TrackIcon](ue_ue.InterpTrack.md#trackicon)
- [TrackInstClass](ue_ue.InterpTrack.md#trackinstclass)
- [TrackTitle](ue_ue.InterpTrack.md#tracktitle)
- [\_\_tid\_InterpTrack\_\_](ue_ue.InterpTrack.md#__tid_interptrack__)
- [\_\_tid\_Object\_\_](ue_ue.InterpTrack.md#__tid_object__)
- [bDirGroupOnly](ue_ue.InterpTrack.md#bdirgrouponly)
- [bDisableTrack](ue_ue.InterpTrack.md#bdisabletrack)
- [bIsAnimControlTrack](ue_ue.InterpTrack.md#bisanimcontroltrack)
- [bIsCollapsed](ue_ue.InterpTrack.md#biscollapsed)
- [bIsRecording](ue_ue.InterpTrack.md#bisrecording)
- [bIsSelected](ue_ue.InterpTrack.md#bisselected)
- [bOnePerGroup](ue_ue.InterpTrack.md#bonepergroup)
- [bSubTrackOnly](ue_ue.InterpTrack.md#bsubtrackonly)
- [bVisible](ue_ue.InterpTrack.md#bvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpTrack.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpTrack.md#executeubergraph)
- [GetClass](ue_ue.InterpTrack.md#getclass)
- [GetName](ue_ue.InterpTrack.md#getname)
- [GetOuter](ue_ue.InterpTrack.md#getouter)
- [GetWorld](ue_ue.InterpTrack.md#getworld)
- [Find](ue_ue.InterpTrack.md#find)
- [Load](ue_ue.InterpTrack.md#load)
- [StaticClass](ue_ue.InterpTrack.md#staticclass)

## Constructors

### constructor

• **new InterpTrack**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ActiveCondition

• **ActiveCondition**: [`ETrackActiveCondition`](../enums/ue_ue.ETrackActiveCondition.md)

___

### SubTrackGroups

• **SubTrackGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SubTrackGroup`](ue_ue.SubTrackGroup.md)\>

___

### SubTracks

• **SubTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpTrack`](ue_ue.InterpTrack.md)\>

___

### SupportedSubTracks

• **SupportedSubTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SupportedSubTrackInfo`](ue_ue.SupportedSubTrackInfo.md)\>

___

### TrackIcon

• **TrackIcon**: [`Texture2D`](ue_ue.Texture2D.md)

___

### TrackInstClass

• **TrackInstClass**: [`Class`](ue_ue.Class.md)

___

### TrackTitle

• **TrackTitle**: `string`

___

### \_\_tid\_InterpTrack\_\_

• **\_\_tid\_InterpTrack\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bDirGroupOnly

• **bDirGroupOnly**: `boolean`

___

### bDisableTrack

• **bDisableTrack**: `boolean`

___

### bIsAnimControlTrack

• **bIsAnimControlTrack**: `boolean`

___

### bIsCollapsed

• **bIsCollapsed**: `boolean`

___

### bIsRecording

• **bIsRecording**: `boolean`

___

### bIsSelected

• **bIsSelected**: `boolean`

___

### bOnePerGroup

• **bOnePerGroup**: `boolean`

___

### bSubTrackOnly

• **bSubTrackOnly**: `boolean`

___

### bVisible

• **bVisible**: `boolean`

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpTrack`](ue_ue.InterpTrack.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpTrack`](ue_ue.InterpTrack.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpTrack`](ue_ue.InterpTrack.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpTrack`](ue_ue.InterpTrack.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
