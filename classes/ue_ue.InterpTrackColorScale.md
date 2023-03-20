[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpTrackColorScale

# Class: InterpTrackColorScale

[ue/ue](../modules/ue_ue.md).InterpTrackColorScale

## Hierarchy

- [`InterpTrackVectorBase`](ue_ue.InterpTrackVectorBase.md)

  ↳ **`InterpTrackColorScale`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpTrackColorScale.md#constructor)

### Properties

- [ActiveCondition](ue_ue.InterpTrackColorScale.md#activecondition)
- [CurveTension](ue_ue.InterpTrackColorScale.md#curvetension)
- [SubTrackGroups](ue_ue.InterpTrackColorScale.md#subtrackgroups)
- [SubTracks](ue_ue.InterpTrackColorScale.md#subtracks)
- [SupportedSubTracks](ue_ue.InterpTrackColorScale.md#supportedsubtracks)
- [TrackIcon](ue_ue.InterpTrackColorScale.md#trackicon)
- [TrackInstClass](ue_ue.InterpTrackColorScale.md#trackinstclass)
- [TrackTitle](ue_ue.InterpTrackColorScale.md#tracktitle)
- [VectorTrack](ue_ue.InterpTrackColorScale.md#vectortrack)
- [\_\_tid\_InterpTrackColorScale\_\_](ue_ue.InterpTrackColorScale.md#__tid_interptrackcolorscale__)
- [\_\_tid\_InterpTrackVectorBase\_\_](ue_ue.InterpTrackColorScale.md#__tid_interptrackvectorbase__)
- [\_\_tid\_InterpTrack\_\_](ue_ue.InterpTrackColorScale.md#__tid_interptrack__)
- [\_\_tid\_Object\_\_](ue_ue.InterpTrackColorScale.md#__tid_object__)
- [bDirGroupOnly](ue_ue.InterpTrackColorScale.md#bdirgrouponly)
- [bDisableTrack](ue_ue.InterpTrackColorScale.md#bdisabletrack)
- [bIsAnimControlTrack](ue_ue.InterpTrackColorScale.md#bisanimcontroltrack)
- [bIsCollapsed](ue_ue.InterpTrackColorScale.md#biscollapsed)
- [bIsRecording](ue_ue.InterpTrackColorScale.md#bisrecording)
- [bIsSelected](ue_ue.InterpTrackColorScale.md#bisselected)
- [bOnePerGroup](ue_ue.InterpTrackColorScale.md#bonepergroup)
- [bSubTrackOnly](ue_ue.InterpTrackColorScale.md#bsubtrackonly)
- [bVisible](ue_ue.InterpTrackColorScale.md#bvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpTrackColorScale.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpTrackColorScale.md#executeubergraph)
- [GetClass](ue_ue.InterpTrackColorScale.md#getclass)
- [GetName](ue_ue.InterpTrackColorScale.md#getname)
- [GetOuter](ue_ue.InterpTrackColorScale.md#getouter)
- [GetWorld](ue_ue.InterpTrackColorScale.md#getworld)
- [Find](ue_ue.InterpTrackColorScale.md#find)
- [Load](ue_ue.InterpTrackColorScale.md#load)
- [StaticClass](ue_ue.InterpTrackColorScale.md#staticclass)

## Constructors

### constructor

• **new InterpTrackColorScale**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[constructor](ue_ue.InterpTrackVectorBase.md#constructor)

#### Defined in

[ue/ue.d.ts:39854](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39854)

## Properties

### ActiveCondition

• **ActiveCondition**: [`ETrackActiveCondition`](../enums/ue_ue.ETrackActiveCondition.md)

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[ActiveCondition](ue_ue.InterpTrackVectorBase.md#activecondition)

#### Defined in

[ue/ue.d.ts:7487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7487)

___

### CurveTension

• **CurveTension**: `number`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[CurveTension](ue_ue.InterpTrackVectorBase.md#curvetension)

#### Defined in

[ue/ue.d.ts:39802](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39802)

___

### SubTrackGroups

• **SubTrackGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SubTrackGroup`](ue_ue.SubTrackGroup.md)\>

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[SubTrackGroups](ue_ue.InterpTrackVectorBase.md#subtrackgroups)

#### Defined in

[ue/ue.d.ts:7484](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7484)

___

### SubTracks

• **SubTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpTrack`](ue_ue.InterpTrack.md)\>

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[SubTracks](ue_ue.InterpTrackVectorBase.md#subtracks)

#### Defined in

[ue/ue.d.ts:7483](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7483)

___

### SupportedSubTracks

• **SupportedSubTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SupportedSubTrackInfo`](ue_ue.SupportedSubTrackInfo.md)\>

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[SupportedSubTracks](ue_ue.InterpTrackVectorBase.md#supportedsubtracks)

#### Defined in

[ue/ue.d.ts:7485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7485)

___

### TrackIcon

• **TrackIcon**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[TrackIcon](ue_ue.InterpTrackVectorBase.md#trackicon)

#### Defined in

[ue/ue.d.ts:7493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7493)

___

### TrackInstClass

• **TrackInstClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[TrackInstClass](ue_ue.InterpTrackVectorBase.md#trackinstclass)

#### Defined in

[ue/ue.d.ts:7486](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7486)

___

### TrackTitle

• **TrackTitle**: `string`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[TrackTitle](ue_ue.InterpTrackVectorBase.md#tracktitle)

#### Defined in

[ue/ue.d.ts:7488](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7488)

___

### VectorTrack

• **VectorTrack**: [`InterpCurveVector`](ue_ue.InterpCurveVector.md)

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[VectorTrack](ue_ue.InterpTrackVectorBase.md#vectortrack)

#### Defined in

[ue/ue.d.ts:39801](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39801)

___

### \_\_tid\_InterpTrackColorScale\_\_

• **\_\_tid\_InterpTrackColorScale\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:39859](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39859)

___

### \_\_tid\_InterpTrackVectorBase\_\_

• **\_\_tid\_InterpTrackVectorBase\_\_**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[__tid_InterpTrackVectorBase__](ue_ue.InterpTrackVectorBase.md#__tid_interptrackvectorbase__)

#### Defined in

[ue/ue.d.ts:39807](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39807)

___

### \_\_tid\_InterpTrack\_\_

• **\_\_tid\_InterpTrack\_\_**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[__tid_InterpTrack__](ue_ue.InterpTrackVectorBase.md#__tid_interptrack__)

#### Defined in

[ue/ue.d.ts:7503](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7503)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[__tid_Object__](ue_ue.InterpTrackVectorBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bDirGroupOnly

• **bDirGroupOnly**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bDirGroupOnly](ue_ue.InterpTrackVectorBase.md#bdirgrouponly)

#### Defined in

[ue/ue.d.ts:7490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7490)

___

### bDisableTrack

• **bDisableTrack**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bDisableTrack](ue_ue.InterpTrackVectorBase.md#bdisabletrack)

#### Defined in

[ue/ue.d.ts:7491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7491)

___

### bIsAnimControlTrack

• **bIsAnimControlTrack**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bIsAnimControlTrack](ue_ue.InterpTrackVectorBase.md#bisanimcontroltrack)

#### Defined in

[ue/ue.d.ts:7494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7494)

___

### bIsCollapsed

• **bIsCollapsed**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bIsCollapsed](ue_ue.InterpTrackVectorBase.md#biscollapsed)

#### Defined in

[ue/ue.d.ts:7498](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7498)

___

### bIsRecording

• **bIsRecording**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bIsRecording](ue_ue.InterpTrackVectorBase.md#bisrecording)

#### Defined in

[ue/ue.d.ts:7497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7497)

___

### bIsSelected

• **bIsSelected**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bIsSelected](ue_ue.InterpTrackVectorBase.md#bisselected)

#### Defined in

[ue/ue.d.ts:7492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7492)

___

### bOnePerGroup

• **bOnePerGroup**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bOnePerGroup](ue_ue.InterpTrackVectorBase.md#bonepergroup)

#### Defined in

[ue/ue.d.ts:7489](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7489)

___

### bSubTrackOnly

• **bSubTrackOnly**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bSubTrackOnly](ue_ue.InterpTrackVectorBase.md#bsubtrackonly)

#### Defined in

[ue/ue.d.ts:7495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7495)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[bVisible](ue_ue.InterpTrackVectorBase.md#bvisible)

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

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[CreateDefaultSubobject](ue_ue.InterpTrackVectorBase.md#createdefaultsubobject)

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

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[ExecuteUbergraph](ue_ue.InterpTrackVectorBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[GetClass](ue_ue.InterpTrackVectorBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[GetName](ue_ue.InterpTrackVectorBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[GetOuter](ue_ue.InterpTrackVectorBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[GetWorld](ue_ue.InterpTrackVectorBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpTrackColorScale`](ue_ue.InterpTrackColorScale.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpTrackColorScale`](ue_ue.InterpTrackColorScale.md)

#### Overrides

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[Find](ue_ue.InterpTrackVectorBase.md#find)

#### Defined in

[ue/ue.d.ts:39856](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39856)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpTrackColorScale`](ue_ue.InterpTrackColorScale.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpTrackColorScale`](ue_ue.InterpTrackColorScale.md)

#### Overrides

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[Load](ue_ue.InterpTrackVectorBase.md#load)

#### Defined in

[ue/ue.d.ts:39857](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39857)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[StaticClass](ue_ue.InterpTrackVectorBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:39855](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L39855)
