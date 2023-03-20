[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpTrackMove

# Class: InterpTrackMove

[ue/ue](../modules/ue_ue.md).InterpTrackMove

## Hierarchy

- [`InterpTrack`](ue_ue.InterpTrack.md)

  ↳ **`InterpTrackMove`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpTrackMove.md#constructor)

### Properties

- [ActiveCondition](ue_ue.InterpTrackMove.md#activecondition)
- [AngCurveTension](ue_ue.InterpTrackMove.md#angcurvetension)
- [EulerTrack](ue_ue.InterpTrackMove.md#eulertrack)
- [LinCurveTension](ue_ue.InterpTrackMove.md#lincurvetension)
- [LookAtGroupName](ue_ue.InterpTrackMove.md#lookatgroupname)
- [LookupTrack](ue_ue.InterpTrackMove.md#lookuptrack)
- [PosTrack](ue_ue.InterpTrackMove.md#postrack)
- [RotMode](ue_ue.InterpTrackMove.md#rotmode)
- [SubTrackGroups](ue_ue.InterpTrackMove.md#subtrackgroups)
- [SubTracks](ue_ue.InterpTrackMove.md#subtracks)
- [SupportedSubTracks](ue_ue.InterpTrackMove.md#supportedsubtracks)
- [TrackIcon](ue_ue.InterpTrackMove.md#trackicon)
- [TrackInstClass](ue_ue.InterpTrackMove.md#trackinstclass)
- [TrackTitle](ue_ue.InterpTrackMove.md#tracktitle)
- [\_\_tid\_InterpTrackMove\_\_](ue_ue.InterpTrackMove.md#__tid_interptrackmove__)
- [\_\_tid\_InterpTrack\_\_](ue_ue.InterpTrackMove.md#__tid_interptrack__)
- [\_\_tid\_Object\_\_](ue_ue.InterpTrackMove.md#__tid_object__)
- [bDirGroupOnly](ue_ue.InterpTrackMove.md#bdirgrouponly)
- [bDisableMovement](ue_ue.InterpTrackMove.md#bdisablemovement)
- [bDisableTrack](ue_ue.InterpTrackMove.md#bdisabletrack)
- [bHide3DTrack](ue_ue.InterpTrackMove.md#bhide3dtrack)
- [bIsAnimControlTrack](ue_ue.InterpTrackMove.md#bisanimcontroltrack)
- [bIsCollapsed](ue_ue.InterpTrackMove.md#biscollapsed)
- [bIsRecording](ue_ue.InterpTrackMove.md#bisrecording)
- [bIsSelected](ue_ue.InterpTrackMove.md#bisselected)
- [bOnePerGroup](ue_ue.InterpTrackMove.md#bonepergroup)
- [bShowArrowAtKeys](ue_ue.InterpTrackMove.md#bshowarrowatkeys)
- [bShowRotationOnCurveEd](ue_ue.InterpTrackMove.md#bshowrotationoncurveed)
- [bShowTranslationOnCurveEd](ue_ue.InterpTrackMove.md#bshowtranslationoncurveed)
- [bSubTrackOnly](ue_ue.InterpTrackMove.md#bsubtrackonly)
- [bUseQuatInterpolation](ue_ue.InterpTrackMove.md#busequatinterpolation)
- [bVisible](ue_ue.InterpTrackMove.md#bvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpTrackMove.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpTrackMove.md#executeubergraph)
- [GetClass](ue_ue.InterpTrackMove.md#getclass)
- [GetName](ue_ue.InterpTrackMove.md#getname)
- [GetOuter](ue_ue.InterpTrackMove.md#getouter)
- [GetWorld](ue_ue.InterpTrackMove.md#getworld)
- [Find](ue_ue.InterpTrackMove.md#find)
- [Load](ue_ue.InterpTrackMove.md#load)
- [StaticClass](ue_ue.InterpTrackMove.md#staticclass)

## Constructors

### constructor

• **new InterpTrackMove**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### AngCurveTension

• **AngCurveTension**: `number`

___

### EulerTrack

• **EulerTrack**: [`InterpCurveVector`](ue_ue.InterpCurveVector.md)

___

### LinCurveTension

• **LinCurveTension**: `number`

___

### LookAtGroupName

• **LookAtGroupName**: `string`

___

### LookupTrack

• **LookupTrack**: [`InterpLookupTrack`](ue_ue.InterpLookupTrack.md)

___

### PosTrack

• **PosTrack**: [`InterpCurveVector`](ue_ue.InterpCurveVector.md)

___

### RotMode

• **RotMode**: [`EInterpTrackMoveRotMode`](../enums/ue_ue.EInterpTrackMoveRotMode.md)

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

### \_\_tid\_InterpTrackMove\_\_

• **\_\_tid\_InterpTrackMove\_\_**: `boolean`

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

### bDisableMovement

• **bDisableMovement**: `boolean`

___

### bDisableTrack

• **bDisableTrack**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bDisableTrack](ue_ue.InterpTrack.md#bdisabletrack)

___

### bHide3DTrack

• **bHide3DTrack**: `boolean`

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

### bShowArrowAtKeys

• **bShowArrowAtKeys**: `boolean`

___

### bShowRotationOnCurveEd

• **bShowRotationOnCurveEd**: `boolean`

___

### bShowTranslationOnCurveEd

• **bShowTranslationOnCurveEd**: `boolean`

___

### bSubTrackOnly

• **bSubTrackOnly**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bSubTrackOnly](ue_ue.InterpTrack.md#bsubtrackonly)

___

### bUseQuatInterpolation

• **bUseQuatInterpolation**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpTrackMove`](ue_ue.InterpTrackMove.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpTrackMove`](ue_ue.InterpTrackMove.md)

#### Overrides

[InterpTrack](ue_ue.InterpTrack.md).[Find](ue_ue.InterpTrack.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpTrackMove`](ue_ue.InterpTrackMove.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpTrackMove`](ue_ue.InterpTrackMove.md)

#### Overrides

[InterpTrack](ue_ue.InterpTrack.md).[Load](ue_ue.InterpTrack.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpTrack](ue_ue.InterpTrack.md).[StaticClass](ue_ue.InterpTrack.md#staticclass)
