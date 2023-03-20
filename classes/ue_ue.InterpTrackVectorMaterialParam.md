[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / InterpTrackVectorMaterialParam

# Class: InterpTrackVectorMaterialParam

[ue/ue](../modules/ue_ue.md).InterpTrackVectorMaterialParam

## Hierarchy

- [`InterpTrackVectorBase`](ue_ue.InterpTrackVectorBase.md)

  ↳ **`InterpTrackVectorMaterialParam`**

## Table of contents

### Constructors

- [constructor](ue_ue.InterpTrackVectorMaterialParam.md#constructor)

### Properties

- [ActiveCondition](ue_ue.InterpTrackVectorMaterialParam.md#activecondition)
- [CurveTension](ue_ue.InterpTrackVectorMaterialParam.md#curvetension)
- [ParamName](ue_ue.InterpTrackVectorMaterialParam.md#paramname)
- [SubTrackGroups](ue_ue.InterpTrackVectorMaterialParam.md#subtrackgroups)
- [SubTracks](ue_ue.InterpTrackVectorMaterialParam.md#subtracks)
- [SupportedSubTracks](ue_ue.InterpTrackVectorMaterialParam.md#supportedsubtracks)
- [TargetMaterials](ue_ue.InterpTrackVectorMaterialParam.md#targetmaterials)
- [TrackIcon](ue_ue.InterpTrackVectorMaterialParam.md#trackicon)
- [TrackInstClass](ue_ue.InterpTrackVectorMaterialParam.md#trackinstclass)
- [TrackTitle](ue_ue.InterpTrackVectorMaterialParam.md#tracktitle)
- [VectorTrack](ue_ue.InterpTrackVectorMaterialParam.md#vectortrack)
- [\_\_tid\_InterpTrackVectorBase\_\_](ue_ue.InterpTrackVectorMaterialParam.md#__tid_interptrackvectorbase__)
- [\_\_tid\_InterpTrackVectorMaterialParam\_\_](ue_ue.InterpTrackVectorMaterialParam.md#__tid_interptrackvectormaterialparam__)
- [\_\_tid\_InterpTrack\_\_](ue_ue.InterpTrackVectorMaterialParam.md#__tid_interptrack__)
- [\_\_tid\_Object\_\_](ue_ue.InterpTrackVectorMaterialParam.md#__tid_object__)
- [bDirGroupOnly](ue_ue.InterpTrackVectorMaterialParam.md#bdirgrouponly)
- [bDisableTrack](ue_ue.InterpTrackVectorMaterialParam.md#bdisabletrack)
- [bIsAnimControlTrack](ue_ue.InterpTrackVectorMaterialParam.md#bisanimcontroltrack)
- [bIsCollapsed](ue_ue.InterpTrackVectorMaterialParam.md#biscollapsed)
- [bIsRecording](ue_ue.InterpTrackVectorMaterialParam.md#bisrecording)
- [bIsSelected](ue_ue.InterpTrackVectorMaterialParam.md#bisselected)
- [bOnePerGroup](ue_ue.InterpTrackVectorMaterialParam.md#bonepergroup)
- [bSubTrackOnly](ue_ue.InterpTrackVectorMaterialParam.md#bsubtrackonly)
- [bVisible](ue_ue.InterpTrackVectorMaterialParam.md#bvisible)

### Methods

- [CreateDefaultSubobject](ue_ue.InterpTrackVectorMaterialParam.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.InterpTrackVectorMaterialParam.md#executeubergraph)
- [GetClass](ue_ue.InterpTrackVectorMaterialParam.md#getclass)
- [GetName](ue_ue.InterpTrackVectorMaterialParam.md#getname)
- [GetOuter](ue_ue.InterpTrackVectorMaterialParam.md#getouter)
- [GetWorld](ue_ue.InterpTrackVectorMaterialParam.md#getworld)
- [Find](ue_ue.InterpTrackVectorMaterialParam.md#find)
- [Load](ue_ue.InterpTrackVectorMaterialParam.md#load)
- [StaticClass](ue_ue.InterpTrackVectorMaterialParam.md#staticclass)

## Constructors

### constructor

• **new InterpTrackVectorMaterialParam**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### ParamName

• **ParamName**: `string`

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

### TargetMaterials

• **TargetMaterials**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\>

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

### \_\_tid\_InterpTrackVectorBase\_\_

• **\_\_tid\_InterpTrackVectorBase\_\_**: `boolean`

#### Inherited from

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[__tid_InterpTrackVectorBase__](ue_ue.InterpTrackVectorBase.md#__tid_interptrackvectorbase__)

___

### \_\_tid\_InterpTrackVectorMaterialParam\_\_

• **\_\_tid\_InterpTrackVectorMaterialParam\_\_**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`InterpTrackVectorMaterialParam`](ue_ue.InterpTrackVectorMaterialParam.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`InterpTrackVectorMaterialParam`](ue_ue.InterpTrackVectorMaterialParam.md)

#### Overrides

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[Find](ue_ue.InterpTrackVectorBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`InterpTrackVectorMaterialParam`](ue_ue.InterpTrackVectorMaterialParam.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`InterpTrackVectorMaterialParam`](ue_ue.InterpTrackVectorMaterialParam.md)

#### Overrides

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[Load](ue_ue.InterpTrackVectorBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[InterpTrackVectorBase](ue_ue.InterpTrackVectorBase.md).[StaticClass](ue_ue.InterpTrackVectorBase.md#staticclass)
