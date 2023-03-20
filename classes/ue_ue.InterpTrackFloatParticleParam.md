[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpTrackFloatParticleParam

# Class: InterpTrackFloatParticleParam

[ue/ue](../modules/ue_ue.md).InterpTrackFloatParticleParam

## Hierarchy

- [`InterpTrackFloatBase`](ue_ue.InterpTrackFloatBase.md)

  ↳ **`InterpTrackFloatParticleParam`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpTrackFloatParticleParam.md#constructor)

### Properties

- [ActiveCondition](ue_ue.InterpTrackFloatParticleParam.md#activecondition)
- [CurveTension](ue_ue.InterpTrackFloatParticleParam.md#curvetension)
- [FloatTrack](ue_ue.InterpTrackFloatParticleParam.md#floattrack)
- [ParamName](ue_ue.InterpTrackFloatParticleParam.md#paramname)
- [SubTrackGroups](ue_ue.InterpTrackFloatParticleParam.md#subtrackgroups)
- [SubTracks](ue_ue.InterpTrackFloatParticleParam.md#subtracks)
- [SupportedSubTracks](ue_ue.InterpTrackFloatParticleParam.md#supportedsubtracks)
- [TrackIcon](ue_ue.InterpTrackFloatParticleParam.md#trackicon)
- [TrackInstClass](ue_ue.InterpTrackFloatParticleParam.md#trackinstclass)
- [TrackTitle](ue_ue.InterpTrackFloatParticleParam.md#tracktitle)
- [\_\_tid\_InterpTrackFloatBase\_\_](ue_ue.InterpTrackFloatParticleParam.md#__tid_interptrackfloatbase__)
- [\_\_tid\_InterpTrackFloatParticleParam\_\_](ue_ue.InterpTrackFloatParticleParam.md#__tid_interptrackfloatparticleparam__)
- [\_\_tid\_InterpTrack\_\_](ue_ue.InterpTrackFloatParticleParam.md#__tid_interptrack__)
- [\_\_tid\_Object\_\_](ue_ue.InterpTrackFloatParticleParam.md#__tid_object__)
- [bDirGroupOnly](ue_ue.InterpTrackFloatParticleParam.md#bdirgrouponly)
- [bDisableTrack](ue_ue.InterpTrackFloatParticleParam.md#bdisabletrack)
- [bIsAnimControlTrack](ue_ue.InterpTrackFloatParticleParam.md#bisanimcontroltrack)
- [bIsCollapsed](ue_ue.InterpTrackFloatParticleParam.md#biscollapsed)
- [bIsRecording](ue_ue.InterpTrackFloatParticleParam.md#bisrecording)
- [bIsSelected](ue_ue.InterpTrackFloatParticleParam.md#bisselected)
- [bOnePerGroup](ue_ue.InterpTrackFloatParticleParam.md#bonepergroup)
- [bSubTrackOnly](ue_ue.InterpTrackFloatParticleParam.md#bsubtrackonly)
- [bVisible](ue_ue.InterpTrackFloatParticleParam.md#bvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpTrackFloatParticleParam.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpTrackFloatParticleParam.md#executeubergraph)
- [GetClass](ue_ue.InterpTrackFloatParticleParam.md#getclass)
- [GetName](ue_ue.InterpTrackFloatParticleParam.md#getname)
- [GetOuter](ue_ue.InterpTrackFloatParticleParam.md#getouter)
- [GetWorld](ue_ue.InterpTrackFloatParticleParam.md#getworld)
- [Find](ue_ue.InterpTrackFloatParticleParam.md#find)
- [Load](ue_ue.InterpTrackFloatParticleParam.md#load)
- [StaticClass](ue_ue.InterpTrackFloatParticleParam.md#staticclass)

## Constructors

### constructor

• **new InterpTrackFloatParticleParam**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[constructor](ue_ue.InterpTrackFloatBase.md#constructor)

#### Defined in

[ue/ue.d.ts:39952](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39952)

## Properties

### ActiveCondition

• **ActiveCondition**: [`ETrackActiveCondition`](../enums/ue_ue.ETrackActiveCondition.md)

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[ActiveCondition](ue_ue.InterpTrackFloatBase.md#activecondition)

#### Defined in

[ue/ue.d.ts:7487](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7487)

___

### CurveTension

• **CurveTension**: `number`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[CurveTension](ue_ue.InterpTrackFloatBase.md#curvetension)

#### Defined in

[ue/ue.d.ts:39761](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39761)

___

### FloatTrack

• **FloatTrack**: [`InterpCurveFloat`](ue_ue.InterpCurveFloat.md)

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[FloatTrack](ue_ue.InterpTrackFloatBase.md#floattrack)

#### Defined in

[ue/ue.d.ts:39760](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39760)

___

### ParamName

• **ParamName**: `string`

#### Defined in

[ue/ue.d.ts:39953](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39953)

___

### SubTrackGroups

• **SubTrackGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SubTrackGroup`](ue_ue.SubTrackGroup.md)\>

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[SubTrackGroups](ue_ue.InterpTrackFloatBase.md#subtrackgroups)

#### Defined in

[ue/ue.d.ts:7484](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7484)

___

### SubTracks

• **SubTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpTrack`](ue_ue.InterpTrack.md)\>

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[SubTracks](ue_ue.InterpTrackFloatBase.md#subtracks)

#### Defined in

[ue/ue.d.ts:7483](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7483)

___

### SupportedSubTracks

• **SupportedSubTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SupportedSubTrackInfo`](ue_ue.SupportedSubTrackInfo.md)\>

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[SupportedSubTracks](ue_ue.InterpTrackFloatBase.md#supportedsubtracks)

#### Defined in

[ue/ue.d.ts:7485](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7485)

___

### TrackIcon

• **TrackIcon**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[TrackIcon](ue_ue.InterpTrackFloatBase.md#trackicon)

#### Defined in

[ue/ue.d.ts:7493](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7493)

___

### TrackInstClass

• **TrackInstClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[TrackInstClass](ue_ue.InterpTrackFloatBase.md#trackinstclass)

#### Defined in

[ue/ue.d.ts:7486](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7486)

___

### TrackTitle

• **TrackTitle**: `string`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[TrackTitle](ue_ue.InterpTrackFloatBase.md#tracktitle)

#### Defined in

[ue/ue.d.ts:7488](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7488)

___

### \_\_tid\_InterpTrackFloatBase\_\_

• **\_\_tid\_InterpTrackFloatBase\_\_**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[__tid_InterpTrackFloatBase__](ue_ue.InterpTrackFloatBase.md#__tid_interptrackfloatbase__)

#### Defined in

[ue/ue.d.ts:39766](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39766)

___

### \_\_tid\_InterpTrackFloatParticleParam\_\_

• **\_\_tid\_InterpTrackFloatParticleParam\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:39958](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39958)

___

### \_\_tid\_InterpTrack\_\_

• **\_\_tid\_InterpTrack\_\_**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[__tid_InterpTrack__](ue_ue.InterpTrackFloatBase.md#__tid_interptrack__)

#### Defined in

[ue/ue.d.ts:7503](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7503)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[__tid_Object__](ue_ue.InterpTrackFloatBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bDirGroupOnly

• **bDirGroupOnly**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bDirGroupOnly](ue_ue.InterpTrackFloatBase.md#bdirgrouponly)

#### Defined in

[ue/ue.d.ts:7490](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7490)

___

### bDisableTrack

• **bDisableTrack**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bDisableTrack](ue_ue.InterpTrackFloatBase.md#bdisabletrack)

#### Defined in

[ue/ue.d.ts:7491](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7491)

___

### bIsAnimControlTrack

• **bIsAnimControlTrack**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bIsAnimControlTrack](ue_ue.InterpTrackFloatBase.md#bisanimcontroltrack)

#### Defined in

[ue/ue.d.ts:7494](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7494)

___

### bIsCollapsed

• **bIsCollapsed**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bIsCollapsed](ue_ue.InterpTrackFloatBase.md#biscollapsed)

#### Defined in

[ue/ue.d.ts:7498](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7498)

___

### bIsRecording

• **bIsRecording**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bIsRecording](ue_ue.InterpTrackFloatBase.md#bisrecording)

#### Defined in

[ue/ue.d.ts:7497](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7497)

___

### bIsSelected

• **bIsSelected**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bIsSelected](ue_ue.InterpTrackFloatBase.md#bisselected)

#### Defined in

[ue/ue.d.ts:7492](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7492)

___

### bOnePerGroup

• **bOnePerGroup**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bOnePerGroup](ue_ue.InterpTrackFloatBase.md#bonepergroup)

#### Defined in

[ue/ue.d.ts:7489](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7489)

___

### bSubTrackOnly

• **bSubTrackOnly**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bSubTrackOnly](ue_ue.InterpTrackFloatBase.md#bsubtrackonly)

#### Defined in

[ue/ue.d.ts:7495](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7495)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[bVisible](ue_ue.InterpTrackFloatBase.md#bvisible)

#### Defined in

[ue/ue.d.ts:7496](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L7496)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[GetClass](ue_ue.InterpTrackFloatBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[GetName](ue_ue.InterpTrackFloatBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[GetOuter](ue_ue.InterpTrackFloatBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[GetWorld](ue_ue.InterpTrackFloatBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpTrackFloatParticleParam`](ue_ue.InterpTrackFloatParticleParam.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpTrackFloatParticleParam`](ue_ue.InterpTrackFloatParticleParam.md)

#### Overrides

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[Find](ue_ue.InterpTrackFloatBase.md#find)

#### Defined in

[ue/ue.d.ts:39955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39955)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpTrackFloatParticleParam`](ue_ue.InterpTrackFloatParticleParam.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpTrackFloatParticleParam`](ue_ue.InterpTrackFloatParticleParam.md)

#### Overrides

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[Load](ue_ue.InterpTrackFloatBase.md#load)

#### Defined in

[ue/ue.d.ts:39956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39956)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpTrackFloatBase](ue_ue.InterpTrackFloatBase.md).[StaticClass](ue_ue.InterpTrackFloatBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:39954](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L39954)