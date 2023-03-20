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

#### Defined in

[ue/ue.d.ts:7611](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7611)

## Properties

### ActiveCondition

• **ActiveCondition**: [`ETrackActiveCondition`](../enums/ue_ue.ETrackActiveCondition.md)

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[ActiveCondition](ue_ue.InterpTrack.md#activecondition)

#### Defined in

[ue/ue.d.ts:7487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7487)

___

### AngCurveTension

• **AngCurveTension**: `number`

#### Defined in

[ue/ue.d.ts:7617](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7617)

___

### EulerTrack

• **EulerTrack**: [`InterpCurveVector`](ue_ue.InterpCurveVector.md)

#### Defined in

[ue/ue.d.ts:7613](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7613)

___

### LinCurveTension

• **LinCurveTension**: `number`

#### Defined in

[ue/ue.d.ts:7616](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7616)

___

### LookAtGroupName

• **LookAtGroupName**: `string`

#### Defined in

[ue/ue.d.ts:7615](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7615)

___

### LookupTrack

• **LookupTrack**: [`InterpLookupTrack`](ue_ue.InterpLookupTrack.md)

#### Defined in

[ue/ue.d.ts:7614](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7614)

___

### PosTrack

• **PosTrack**: [`InterpCurveVector`](ue_ue.InterpCurveVector.md)

#### Defined in

[ue/ue.d.ts:7612](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7612)

___

### RotMode

• **RotMode**: [`EInterpTrackMoveRotMode`](../enums/ue_ue.EInterpTrackMoveRotMode.md)

#### Defined in

[ue/ue.d.ts:7624](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7624)

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

### \_\_tid\_InterpTrackMove\_\_

• **\_\_tid\_InterpTrackMove\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:7629](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7629)

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

### bDisableMovement

• **bDisableMovement**: `boolean`

#### Defined in

[ue/ue.d.ts:7620](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7620)

___

### bDisableTrack

• **bDisableTrack**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bDisableTrack](ue_ue.InterpTrack.md#bdisabletrack)

#### Defined in

[ue/ue.d.ts:7491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7491)

___

### bHide3DTrack

• **bHide3DTrack**: `boolean`

#### Defined in

[ue/ue.d.ts:7623](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7623)

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

### bShowArrowAtKeys

• **bShowArrowAtKeys**: `boolean`

#### Defined in

[ue/ue.d.ts:7619](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7619)

___

### bShowRotationOnCurveEd

• **bShowRotationOnCurveEd**: `boolean`

#### Defined in

[ue/ue.d.ts:7622](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7622)

___

### bShowTranslationOnCurveEd

• **bShowTranslationOnCurveEd**: `boolean`

#### Defined in

[ue/ue.d.ts:7621](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7621)

___

### bSubTrackOnly

• **bSubTrackOnly**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bSubTrackOnly](ue_ue.InterpTrack.md#bsubtrackonly)

#### Defined in

[ue/ue.d.ts:7495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7495)

___

### bUseQuatInterpolation

• **bUseQuatInterpolation**: `boolean`

#### Defined in

[ue/ue.d.ts:7618](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7618)

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

#### Defined in

[ue/ue.d.ts:7626](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7626)

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

#### Defined in

[ue/ue.d.ts:7627](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7627)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpTrack](ue_ue.InterpTrack.md).[StaticClass](ue_ue.InterpTrack.md#staticclass)

#### Defined in

[ue/ue.d.ts:7625](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7625)
