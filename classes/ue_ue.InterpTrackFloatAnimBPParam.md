[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpTrackFloatAnimBPParam

# Class: InterpTrackFloatAnimBPParam

[ue/ue](../modules/ue_ue.md).InterpTrackFloatAnimBPParam

## Hierarchy

- [`InterpTrackFloatBase`](ue_ue.InterpTrackFloatBase.md)

  ↳ **`InterpTrackFloatAnimBPParam`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpTrackFloatAnimBPParam.md#constructor)

### Properties

- [ActiveCondition](ue_ue.InterpTrackFloatAnimBPParam.md#activecondition)
- [AnimBlueprintClass](ue_ue.InterpTrackFloatAnimBPParam.md#animblueprintclass)
- [AnimClass](ue_ue.InterpTrackFloatAnimBPParam.md#animclass)
- [CurveTension](ue_ue.InterpTrackFloatAnimBPParam.md#curvetension)
- [FloatTrack](ue_ue.InterpTrackFloatAnimBPParam.md#floattrack)
- [ParamName](ue_ue.InterpTrackFloatAnimBPParam.md#paramname)
- [SubTrackGroups](ue_ue.InterpTrackFloatAnimBPParam.md#subtrackgroups)
- [SubTracks](ue_ue.InterpTrackFloatAnimBPParam.md#subtracks)
- [SupportedSubTracks](ue_ue.InterpTrackFloatAnimBPParam.md#supportedsubtracks)
- [TrackIcon](ue_ue.InterpTrackFloatAnimBPParam.md#trackicon)
- [TrackInstClass](ue_ue.InterpTrackFloatAnimBPParam.md#trackinstclass)
- [TrackTitle](ue_ue.InterpTrackFloatAnimBPParam.md#tracktitle)
- [\_\_tid\_InterpTrackFloatAnimBPParam\_\_](ue_ue.InterpTrackFloatAnimBPParam.md#__tid_interptrackfloatanimbpparam__)
- [\_\_tid\_InterpTrackFloatBase\_\_](ue_ue.InterpTrackFloatAnimBPParam.md#__tid_interptrackfloatbase__)
- [\_\_tid\_InterpTrack\_\_](ue_ue.InterpTrackFloatAnimBPParam.md#__tid_interptrack__)
- [\_\_tid\_Object\_\_](ue_ue.InterpTrackFloatAnimBPParam.md#__tid_object__)
- [bDirGroupOnly](ue_ue.InterpTrackFloatAnimBPParam.md#bdirgrouponly)
- [bDisableTrack](ue_ue.InterpTrackFloatAnimBPParam.md#bdisabletrack)
- [bIsAnimControlTrack](ue_ue.InterpTrackFloatAnimBPParam.md#bisanimcontroltrack)
- [bIsCollapsed](ue_ue.InterpTrackFloatAnimBPParam.md#biscollapsed)
- [bIsRecording](ue_ue.InterpTrackFloatAnimBPParam.md#bisrecording)
- [bIsSelected](ue_ue.InterpTrackFloatAnimBPParam.md#bisselected)
- [bOnePerGroup](ue_ue.InterpTrackFloatAnimBPParam.md#bonepergroup)
- [bSubTrackOnly](ue_ue.InterpTrackFloatAnimBPParam.md#bsubtrackonly)
- [bVisible](ue_ue.InterpTrackFloatAnimBPParam.md#bvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpTrackFloatAnimBPParam.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpTrackFloatAnimBPParam.md#executeubergraph)
- [GetClass](ue_ue.InterpTrackFloatAnimBPParam.md#getclass)
- [GetName](ue_ue.InterpTrackFloatAnimBPParam.md#getname)
- [GetOuter](ue_ue.InterpTrackFloatAnimBPParam.md#getouter)
- [GetWorld](ue_ue.InterpTrackFloatAnimBPParam.md#getworld)
- [Find](ue_ue.InterpTrackFloatAnimBPParam.md#find)
- [Load](ue_ue.InterpTrackFloatAnimBPParam.md#load)
- [StaticClass](ue_ue.InterpTrackFloatAnimBPParam.md#staticclass)

## Constructors

### constructor

• **new InterpTrackFloatAnimBPParam**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### AnimBlueprintClass

• **AnimBlueprintClass**: [`AnimBlueprintGeneratedClass`](ue_ue.AnimBlueprintGeneratedClass.md)

___

### AnimClass

• **AnimClass**: [`Class`](ue_ue.Class.md)

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

### ParamName

• **ParamName**: `string`

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

### \_\_tid\_InterpTrackFloatAnimBPParam\_\_

• **\_\_tid\_InterpTrackFloatAnimBPParam\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpTrackFloatAnimBPParam`](ue_ue.InterpTrackFloatAnimBPParam.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpTrackFloatAnimBPParam`](ue_ue.InterpTrackFloatAnimBPParam.md)

#### Overrides

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[Find](ue_ue.InterpTrackFloatBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpTrackFloatAnimBPParam`](ue_ue.InterpTrackFloatAnimBPParam.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpTrackFloatAnimBPParam`](ue_ue.InterpTrackFloatAnimBPParam.md)

#### Overrides

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[Load](ue_ue.InterpTrackFloatBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[StaticClass](ue_ue.InterpTrackFloatBase.md#staticclass)
