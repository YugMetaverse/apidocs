[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpTrackLinearColorProp

# Class: InterpTrackLinearColorProp

[ue/ue](../modules/ue_ue.md).InterpTrackLinearColorProp

## Hierarchy

- [`InterpTrackLinearColorBase`](ue_ue.InterpTrackLinearColorBase.md)

  ↳ **`InterpTrackLinearColorProp`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpTrackLinearColorProp.md#constructor)

### Properties

- [ActiveCondition](ue_ue.InterpTrackLinearColorProp.md#activecondition)
- [CurveTension](ue_ue.InterpTrackLinearColorProp.md#curvetension)
- [LinearColorTrack](ue_ue.InterpTrackLinearColorProp.md#linearcolortrack)
- [PropertyName](ue_ue.InterpTrackLinearColorProp.md#propertyname)
- [SubTrackGroups](ue_ue.InterpTrackLinearColorProp.md#subtrackgroups)
- [SubTracks](ue_ue.InterpTrackLinearColorProp.md#subtracks)
- [SupportedSubTracks](ue_ue.InterpTrackLinearColorProp.md#supportedsubtracks)
- [TrackIcon](ue_ue.InterpTrackLinearColorProp.md#trackicon)
- [TrackInstClass](ue_ue.InterpTrackLinearColorProp.md#trackinstclass)
- [TrackTitle](ue_ue.InterpTrackLinearColorProp.md#tracktitle)
- [\_\_tid\_InterpTrackLinearColorBase\_\_](ue_ue.InterpTrackLinearColorProp.md#__tid_interptracklinearcolorbase__)
- [\_\_tid\_InterpTrackLinearColorProp\_\_](ue_ue.InterpTrackLinearColorProp.md#__tid_interptracklinearcolorprop__)
- [\_\_tid\_InterpTrack\_\_](ue_ue.InterpTrackLinearColorProp.md#__tid_interptrack__)
- [\_\_tid\_Object\_\_](ue_ue.InterpTrackLinearColorProp.md#__tid_object__)
- [bDirGroupOnly](ue_ue.InterpTrackLinearColorProp.md#bdirgrouponly)
- [bDisableTrack](ue_ue.InterpTrackLinearColorProp.md#bdisabletrack)
- [bIsAnimControlTrack](ue_ue.InterpTrackLinearColorProp.md#bisanimcontroltrack)
- [bIsCollapsed](ue_ue.InterpTrackLinearColorProp.md#biscollapsed)
- [bIsRecording](ue_ue.InterpTrackLinearColorProp.md#bisrecording)
- [bIsSelected](ue_ue.InterpTrackLinearColorProp.md#bisselected)
- [bOnePerGroup](ue_ue.InterpTrackLinearColorProp.md#bonepergroup)
- [bSubTrackOnly](ue_ue.InterpTrackLinearColorProp.md#bsubtrackonly)
- [bVisible](ue_ue.InterpTrackLinearColorProp.md#bvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpTrackLinearColorProp.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpTrackLinearColorProp.md#executeubergraph)
- [GetClass](ue_ue.InterpTrackLinearColorProp.md#getclass)
- [GetName](ue_ue.InterpTrackLinearColorProp.md#getname)
- [GetOuter](ue_ue.InterpTrackLinearColorProp.md#getouter)
- [GetWorld](ue_ue.InterpTrackLinearColorProp.md#getworld)
- [Find](ue_ue.InterpTrackLinearColorProp.md#find)
- [Load](ue_ue.InterpTrackLinearColorProp.md#load)
- [StaticClass](ue_ue.InterpTrackLinearColorProp.md#staticclass)

## Constructors

### constructor

• **new InterpTrackLinearColorProp**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[constructor](ue_ue.InterpTrackLinearColorBase.md#constructor)

## Properties

### ActiveCondition

• **ActiveCondition**: [`ETrackActiveCondition`](../enums/ue_ue.ETrackActiveCondition.md)

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[ActiveCondition](ue_ue.InterpTrackLinearColorBase.md#activecondition)

___

### CurveTension

• **CurveTension**: `number`

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[CurveTension](ue_ue.InterpTrackLinearColorBase.md#curvetension)

___

### LinearColorTrack

• **LinearColorTrack**: [`InterpCurveLinearColor`](ue_ue.InterpCurveLinearColor.md)

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[LinearColorTrack](ue_ue.InterpTrackLinearColorBase.md#linearcolortrack)

___

### PropertyName

• **PropertyName**: `string`

___

### SubTrackGroups

• **SubTrackGroups**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SubTrackGroup`](ue_ue.SubTrackGroup.md)\>

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[SubTrackGroups](ue_ue.InterpTrackLinearColorBase.md#subtrackgroups)

___

### SubTracks

• **SubTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`InterpTrack`](ue_ue.InterpTrack.md)\>

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[SubTracks](ue_ue.InterpTrackLinearColorBase.md#subtracks)

___

### SupportedSubTracks

• **SupportedSubTracks**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SupportedSubTrackInfo`](ue_ue.SupportedSubTrackInfo.md)\>

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[SupportedSubTracks](ue_ue.InterpTrackLinearColorBase.md#supportedsubtracks)

___

### TrackIcon

• **TrackIcon**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[TrackIcon](ue_ue.InterpTrackLinearColorBase.md#trackicon)

___

### TrackInstClass

• **TrackInstClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[TrackInstClass](ue_ue.InterpTrackLinearColorBase.md#trackinstclass)

___

### TrackTitle

• **TrackTitle**: `string`

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[TrackTitle](ue_ue.InterpTrackLinearColorBase.md#tracktitle)

___

### \_\_tid\_InterpTrackLinearColorBase\_\_

• **\_\_tid\_InterpTrackLinearColorBase\_\_**: `boolean`

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[__tid_InterpTrackLinearColorBase__](ue_ue.InterpTrackLinearColorBase.md#__tid_interptracklinearcolorbase__)

___

### \_\_tid\_InterpTrackLinearColorProp\_\_

• **\_\_tid\_InterpTrackLinearColorProp\_\_**: `boolean`

___

### \_\_tid\_InterpTrack\_\_

• **\_\_tid\_InterpTrack\_\_**: `boolean`

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[__tid_InterpTrack__](ue_ue.InterpTrackLinearColorBase.md#__tid_interptrack__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[__tid_Object__](ue_ue.InterpTrackLinearColorBase.md#__tid_object__)

___

### bDirGroupOnly

• **bDirGroupOnly**: `boolean`

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[bDirGroupOnly](ue_ue.InterpTrackLinearColorBase.md#bdirgrouponly)

___

### bDisableTrack

• **bDisableTrack**: `boolean`

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[bDisableTrack](ue_ue.InterpTrackLinearColorBase.md#bdisabletrack)

___

### bIsAnimControlTrack

• **bIsAnimControlTrack**: `boolean`

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[bIsAnimControlTrack](ue_ue.InterpTrackLinearColorBase.md#bisanimcontroltrack)

___

### bIsCollapsed

• **bIsCollapsed**: `boolean`

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[bIsCollapsed](ue_ue.InterpTrackLinearColorBase.md#biscollapsed)

___

### bIsRecording

• **bIsRecording**: `boolean`

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[bIsRecording](ue_ue.InterpTrackLinearColorBase.md#bisrecording)

___

### bIsSelected

• **bIsSelected**: `boolean`

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[bIsSelected](ue_ue.InterpTrackLinearColorBase.md#bisselected)

___

### bOnePerGroup

• **bOnePerGroup**: `boolean`

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[bOnePerGroup](ue_ue.InterpTrackLinearColorBase.md#bonepergroup)

___

### bSubTrackOnly

• **bSubTrackOnly**: `boolean`

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[bSubTrackOnly](ue_ue.InterpTrackLinearColorBase.md#bsubtrackonly)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[bVisible](ue_ue.InterpTrackLinearColorBase.md#bvisible)

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

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[CreateDefaultSubobject](ue_ue.InterpTrackLinearColorBase.md#createdefaultsubobject)

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

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[ExecuteUbergraph](ue_ue.InterpTrackLinearColorBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[GetClass](ue_ue.InterpTrackLinearColorBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[GetName](ue_ue.InterpTrackLinearColorBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[GetOuter](ue_ue.InterpTrackLinearColorBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[GetWorld](ue_ue.InterpTrackLinearColorBase.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpTrackLinearColorProp`](ue_ue.InterpTrackLinearColorProp.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpTrackLinearColorProp`](ue_ue.InterpTrackLinearColorProp.md)

#### Overrides

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[Find](ue_ue.InterpTrackLinearColorBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpTrackLinearColorProp`](ue_ue.InterpTrackLinearColorProp.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpTrackLinearColorProp`](ue_ue.InterpTrackLinearColorProp.md)

#### Overrides

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[Load](ue_ue.InterpTrackLinearColorBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpTrackLinearColorBase](ue_ue.InterpTrackLinearColorBase.md).[StaticClass](ue_ue.InterpTrackLinearColorBase.md#staticclass)
