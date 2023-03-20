[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpTrackAnimControl

# Class: InterpTrackAnimControl

[ue/ue](../modules/ue_ue.md).InterpTrackAnimControl

## Hierarchy

- [`InterpTrackFloatBase`](ue_ue.InterpTrackFloatBase.md)

  ↳ **`InterpTrackAnimControl`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpTrackAnimControl.md#constructor)

### Properties

- [ActiveCondition](ue_ue.InterpTrackAnimControl.md#activecondition)
- [AnimSeqs](ue_ue.InterpTrackAnimControl.md#animseqs)
- [CurveTension](ue_ue.InterpTrackAnimControl.md#curvetension)
- [FloatTrack](ue_ue.InterpTrackAnimControl.md#floattrack)
- [SlotName](ue_ue.InterpTrackAnimControl.md#slotname)
- [SubTrackGroups](ue_ue.InterpTrackAnimControl.md#subtrackgroups)
- [SubTracks](ue_ue.InterpTrackAnimControl.md#subtracks)
- [SupportedSubTracks](ue_ue.InterpTrackAnimControl.md#supportedsubtracks)
- [TrackIcon](ue_ue.InterpTrackAnimControl.md#trackicon)
- [TrackInstClass](ue_ue.InterpTrackAnimControl.md#trackinstclass)
- [TrackTitle](ue_ue.InterpTrackAnimControl.md#tracktitle)
- [\_\_tid\_InterpTrackAnimControl\_\_](ue_ue.InterpTrackAnimControl.md#__tid_interptrackanimcontrol__)
- [\_\_tid\_InterpTrackFloatBase\_\_](ue_ue.InterpTrackAnimControl.md#__tid_interptrackfloatbase__)
- [\_\_tid\_InterpTrack\_\_](ue_ue.InterpTrackAnimControl.md#__tid_interptrack__)
- [\_\_tid\_Object\_\_](ue_ue.InterpTrackAnimControl.md#__tid_object__)
- [bDirGroupOnly](ue_ue.InterpTrackAnimControl.md#bdirgrouponly)
- [bDisableTrack](ue_ue.InterpTrackAnimControl.md#bdisabletrack)
- [bIsAnimControlTrack](ue_ue.InterpTrackAnimControl.md#bisanimcontroltrack)
- [bIsCollapsed](ue_ue.InterpTrackAnimControl.md#biscollapsed)
- [bIsRecording](ue_ue.InterpTrackAnimControl.md#bisrecording)
- [bIsSelected](ue_ue.InterpTrackAnimControl.md#bisselected)
- [bOnePerGroup](ue_ue.InterpTrackAnimControl.md#bonepergroup)
- [bSkipAnimNotifiers](ue_ue.InterpTrackAnimControl.md#bskipanimnotifiers)
- [bSubTrackOnly](ue_ue.InterpTrackAnimControl.md#bsubtrackonly)
- [bVisible](ue_ue.InterpTrackAnimControl.md#bvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpTrackAnimControl.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpTrackAnimControl.md#executeubergraph)
- [GetClass](ue_ue.InterpTrackAnimControl.md#getclass)
- [GetName](ue_ue.InterpTrackAnimControl.md#getname)
- [GetOuter](ue_ue.InterpTrackAnimControl.md#getouter)
- [GetWorld](ue_ue.InterpTrackAnimControl.md#getworld)
- [Find](ue_ue.InterpTrackAnimControl.md#find)
- [Load](ue_ue.InterpTrackAnimControl.md#load)
- [StaticClass](ue_ue.InterpTrackAnimControl.md#staticclass)

## Constructors

### constructor

• **new InterpTrackAnimControl**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[constructor](ue_ue.InterpTrackFloatBase.md#constructor)

## Properties

### ActiveCondition

• **ActiveCondition**: [`ETrackActiveCondition`](../enums/ue_ue.ETrackActiveCondition.md)

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[ActiveCondition](ue_ue.InterpTrackFloatBase.md#activecondition)

___

### AnimSeqs

• **AnimSeqs**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimControlTrackKey`](ue_ue.AnimControlTrackKey.md)\>

___

### CurveTension

• **CurveTension**: `number`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[CurveTension](ue_ue.InterpTrackFloatBase.md#curvetension)

___

### FloatTrack

• **FloatTrack**: [`InterpCurveFloat`](ue_ue.InterpCurveFloat.md)

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[FloatTrack](ue_ue.InterpTrackFloatBase.md#floattrack)

___

### SlotName

• **SlotName**: `string`

___

### SubTrackGroups

• **SubTrackGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SubTrackGroup`](ue_ue.SubTrackGroup.md)\>

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[SubTrackGroups](ue_ue.InterpTrackFloatBase.md#subtrackgroups)

___

### SubTracks

• **SubTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpTrack`](ue_ue.InterpTrack.md)\>

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[SubTracks](ue_ue.InterpTrackFloatBase.md#subtracks)

___

### SupportedSubTracks

• **SupportedSubTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SupportedSubTrackInfo`](ue_ue.SupportedSubTrackInfo.md)\>

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[SupportedSubTracks](ue_ue.InterpTrackFloatBase.md#supportedsubtracks)

___

### TrackIcon

• **TrackIcon**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[TrackIcon](ue_ue.InterpTrackFloatBase.md#trackicon)

___

### TrackInstClass

• **TrackInstClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[TrackInstClass](ue_ue.InterpTrackFloatBase.md#trackinstclass)

___

### TrackTitle

• **TrackTitle**: `string`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[TrackTitle](ue_ue.InterpTrackFloatBase.md#tracktitle)

___

### \_\_tid\_InterpTrackAnimControl\_\_

• **\_\_tid\_InterpTrackAnimControl\_\_**: `boolean`

___

### \_\_tid\_InterpTrackFloatBase\_\_

• **\_\_tid\_InterpTrackFloatBase\_\_**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[__tid_InterpTrackFloatBase__](ue_ue.InterpTrackFloatBase.md#__tid_interptrackfloatbase__)

___

### \_\_tid\_InterpTrack\_\_

• **\_\_tid\_InterpTrack\_\_**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[__tid_InterpTrack__](ue_ue.InterpTrackFloatBase.md#__tid_interptrack__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[__tid_Object__](ue_ue.InterpTrackFloatBase.md#__tid_object__)

___

### bDirGroupOnly

• **bDirGroupOnly**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bDirGroupOnly](ue_ue.InterpTrackFloatBase.md#bdirgrouponly)

___

### bDisableTrack

• **bDisableTrack**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bDisableTrack](ue_ue.InterpTrackFloatBase.md#bdisabletrack)

___

### bIsAnimControlTrack

• **bIsAnimControlTrack**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bIsAnimControlTrack](ue_ue.InterpTrackFloatBase.md#bisanimcontroltrack)

___

### bIsCollapsed

• **bIsCollapsed**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bIsCollapsed](ue_ue.InterpTrackFloatBase.md#biscollapsed)

___

### bIsRecording

• **bIsRecording**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bIsRecording](ue_ue.InterpTrackFloatBase.md#bisrecording)

___

### bIsSelected

• **bIsSelected**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bIsSelected](ue_ue.InterpTrackFloatBase.md#bisselected)

___

### bOnePerGroup

• **bOnePerGroup**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bOnePerGroup](ue_ue.InterpTrackFloatBase.md#bonepergroup)

___

### bSkipAnimNotifiers

• **bSkipAnimNotifiers**: `boolean`

___

### bSubTrackOnly

• **bSubTrackOnly**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bSubTrackOnly](ue_ue.InterpTrackFloatBase.md#bsubtrackonly)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bVisible](ue_ue.InterpTrackFloatBase.md#bvisible)

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

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[CreateDefaultSubobject](ue_ue.InterpTrackFloatBase.md#createdefaultsubobject)

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

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[ExecuteUbergraph](ue_ue.InterpTrackFloatBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[GetClass](ue_ue.InterpTrackFloatBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[GetName](ue_ue.InterpTrackFloatBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[GetOuter](ue_ue.InterpTrackFloatBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[GetWorld](ue_ue.InterpTrackFloatBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpTrackAnimControl`](ue_ue.InterpTrackAnimControl.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpTrackAnimControl`](ue_ue.InterpTrackAnimControl.md)

#### Overrides

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[Find](ue_ue.InterpTrackFloatBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpTrackAnimControl`](ue_ue.InterpTrackAnimControl.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpTrackAnimControl`](ue_ue.InterpTrackAnimControl.md)

#### Overrides

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[Load](ue_ue.InterpTrackFloatBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[StaticClass](ue_ue.InterpTrackFloatBase.md#staticclass)
