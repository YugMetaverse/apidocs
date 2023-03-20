[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpTrackBoolProp

# Class: InterpTrackBoolProp

[ue/ue](../modules/ue_ue.md).InterpTrackBoolProp

## Hierarchy

- [`InterpTrack`](ue_ue.InterpTrack.md)

  ↳ **`InterpTrackBoolProp`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpTrackBoolProp.md#constructor)

### Properties

- [ActiveCondition](ue_ue.InterpTrackBoolProp.md#activecondition)
- [BoolTrack](ue_ue.InterpTrackBoolProp.md#booltrack)
- [PropertyName](ue_ue.InterpTrackBoolProp.md#propertyname)
- [SubTrackGroups](ue_ue.InterpTrackBoolProp.md#subtrackgroups)
- [SubTracks](ue_ue.InterpTrackBoolProp.md#subtracks)
- [SupportedSubTracks](ue_ue.InterpTrackBoolProp.md#supportedsubtracks)
- [TrackIcon](ue_ue.InterpTrackBoolProp.md#trackicon)
- [TrackInstClass](ue_ue.InterpTrackBoolProp.md#trackinstclass)
- [TrackTitle](ue_ue.InterpTrackBoolProp.md#tracktitle)
- [\_\_tid\_InterpTrackBoolProp\_\_](ue_ue.InterpTrackBoolProp.md#__tid_interptrackboolprop__)
- [\_\_tid\_InterpTrack\_\_](ue_ue.InterpTrackBoolProp.md#__tid_interptrack__)
- [\_\_tid\_Object\_\_](ue_ue.InterpTrackBoolProp.md#__tid_object__)
- [bDirGroupOnly](ue_ue.InterpTrackBoolProp.md#bdirgrouponly)
- [bDisableTrack](ue_ue.InterpTrackBoolProp.md#bdisabletrack)
- [bIsAnimControlTrack](ue_ue.InterpTrackBoolProp.md#bisanimcontroltrack)
- [bIsCollapsed](ue_ue.InterpTrackBoolProp.md#biscollapsed)
- [bIsRecording](ue_ue.InterpTrackBoolProp.md#bisrecording)
- [bIsSelected](ue_ue.InterpTrackBoolProp.md#bisselected)
- [bOnePerGroup](ue_ue.InterpTrackBoolProp.md#bonepergroup)
- [bSubTrackOnly](ue_ue.InterpTrackBoolProp.md#bsubtrackonly)
- [bVisible](ue_ue.InterpTrackBoolProp.md#bvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpTrackBoolProp.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpTrackBoolProp.md#executeubergraph)
- [GetClass](ue_ue.InterpTrackBoolProp.md#getclass)
- [GetName](ue_ue.InterpTrackBoolProp.md#getname)
- [GetOuter](ue_ue.InterpTrackBoolProp.md#getouter)
- [GetWorld](ue_ue.InterpTrackBoolProp.md#getworld)
- [Find](ue_ue.InterpTrackBoolProp.md#find)
- [Load](ue_ue.InterpTrackBoolProp.md#load)
- [StaticClass](ue_ue.InterpTrackBoolProp.md#staticclass)

## Constructors

### constructor

• **new InterpTrackBoolProp**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### BoolTrack

• **BoolTrack**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BoolTrackKey`](ue_ue.BoolTrackKey.md)\>

___

### PropertyName

• **PropertyName**: `string`

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

### \_\_tid\_InterpTrackBoolProp\_\_

• **\_\_tid\_InterpTrackBoolProp\_\_**: `boolean`

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

### bDisableTrack

• **bDisableTrack**: `boolean`

#### Inherited from

[InterpTrack](ue_ue.InterpTrack.md).[bDisableTrack](ue_ue.InterpTrack.md#bdisabletrack)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpTrackBoolProp`](ue_ue.InterpTrackBoolProp.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpTrackBoolProp`](ue_ue.InterpTrackBoolProp.md)

#### Overrides

[InterpTrack](ue_ue.InterpTrack.md).[Find](ue_ue.InterpTrack.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpTrackBoolProp`](ue_ue.InterpTrackBoolProp.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpTrackBoolProp`](ue_ue.InterpTrackBoolProp.md)

#### Overrides

[InterpTrack](ue_ue.InterpTrack.md).[Load](ue_ue.InterpTrack.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpTrack](ue_ue.InterpTrack.md).[StaticClass](ue_ue.InterpTrack.md#staticclass)
