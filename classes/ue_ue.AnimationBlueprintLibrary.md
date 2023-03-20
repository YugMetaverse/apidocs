[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimationBlueprintLibrary

# Class: AnimationBlueprintLibrary

[ue/ue](../modules/ue_ue.md).AnimationBlueprintLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`AnimationBlueprintLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimationBlueprintLibrary.md#constructor)

### Properties

- [\_\_tid\_AnimationBlueprintLibrary\_\_](ue_ue.AnimationBlueprintLibrary.md#__tid_animationblueprintlibrary__)
- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.AnimationBlueprintLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.AnimationBlueprintLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimationBlueprintLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimationBlueprintLibrary.md#executeubergraph)
- [GetClass](ue_ue.AnimationBlueprintLibrary.md#getclass)
- [GetName](ue_ue.AnimationBlueprintLibrary.md#getname)
- [GetOuter](ue_ue.AnimationBlueprintLibrary.md#getouter)
- [GetWorld](ue_ue.AnimationBlueprintLibrary.md#getworld)
- [AddAnimationNotifyEvent](ue_ue.AnimationBlueprintLibrary.md#addanimationnotifyevent)
- [AddAnimationNotifyEventObject](ue_ue.AnimationBlueprintLibrary.md#addanimationnotifyeventobject)
- [AddAnimationNotifyStateEvent](ue_ue.AnimationBlueprintLibrary.md#addanimationnotifystateevent)
- [AddAnimationNotifyStateEventObject](ue_ue.AnimationBlueprintLibrary.md#addanimationnotifystateeventobject)
- [AddAnimationNotifyTrack](ue_ue.AnimationBlueprintLibrary.md#addanimationnotifytrack)
- [AddAnimationSyncMarker](ue_ue.AnimationBlueprintLibrary.md#addanimationsyncmarker)
- [AddCurve](ue_ue.AnimationBlueprintLibrary.md#addcurve)
- [AddFloatCurveKey](ue_ue.AnimationBlueprintLibrary.md#addfloatcurvekey)
- [AddFloatCurveKeys](ue_ue.AnimationBlueprintLibrary.md#addfloatcurvekeys)
- [AddMetaData](ue_ue.AnimationBlueprintLibrary.md#addmetadata)
- [AddMetaDataObject](ue_ue.AnimationBlueprintLibrary.md#addmetadataobject)
- [AddTransformationCurveKey](ue_ue.AnimationBlueprintLibrary.md#addtransformationcurvekey)
- [AddTransformationCurveKeys](ue_ue.AnimationBlueprintLibrary.md#addtransformationcurvekeys)
- [AddVectorCurveKey](ue_ue.AnimationBlueprintLibrary.md#addvectorcurvekey)
- [AddVectorCurveKeys](ue_ue.AnimationBlueprintLibrary.md#addvectorcurvekeys)
- [AddVirtualBone](ue_ue.AnimationBlueprintLibrary.md#addvirtualbone)
- [ContainsMetaDataOfClass](ue_ue.AnimationBlueprintLibrary.md#containsmetadataofclass)
- [CopyAnimNotifiesFromSequence](ue_ue.AnimationBlueprintLibrary.md#copyanimnotifiesfromsequence)
- [DoesBoneNameExist](ue_ue.AnimationBlueprintLibrary.md#doesbonenameexist)
- [DoesCurveExist](ue_ue.AnimationBlueprintLibrary.md#doescurveexist)
- [FinalizeBoneAnimation](ue_ue.AnimationBlueprintLibrary.md#finalizeboneanimation)
- [Find](ue_ue.AnimationBlueprintLibrary.md#find)
- [FindBonePathToRoot](ue_ue.AnimationBlueprintLibrary.md#findbonepathtoroot)
- [GetAdditiveAnimationType](ue_ue.AnimationBlueprintLibrary.md#getadditiveanimationtype)
- [GetAdditiveBasePoseType](ue_ue.AnimationBlueprintLibrary.md#getadditivebaseposetype)
- [GetAnimNotifyEventTriggerTime](ue_ue.AnimationBlueprintLibrary.md#getanimnotifyeventtriggertime)
- [GetAnimationInterpolationType](ue_ue.AnimationBlueprintLibrary.md#getanimationinterpolationtype)
- [GetAnimationNotifyEventNames](ue_ue.AnimationBlueprintLibrary.md#getanimationnotifyeventnames)
- [GetAnimationNotifyEvents](ue_ue.AnimationBlueprintLibrary.md#getanimationnotifyevents)
- [GetAnimationNotifyEventsForTrack](ue_ue.AnimationBlueprintLibrary.md#getanimationnotifyeventsfortrack)
- [GetAnimationNotifyTrackNames](ue_ue.AnimationBlueprintLibrary.md#getanimationnotifytracknames)
- [GetAnimationSyncMarkers](ue_ue.AnimationBlueprintLibrary.md#getanimationsyncmarkers)
- [GetAnimationSyncMarkersForTrack](ue_ue.AnimationBlueprintLibrary.md#getanimationsyncmarkersfortrack)
- [GetAnimationTrackNames](ue_ue.AnimationBlueprintLibrary.md#getanimationtracknames)
- [GetBonePoseForFrame](ue_ue.AnimationBlueprintLibrary.md#getboneposeforframe)
- [GetBonePoseForTime](ue_ue.AnimationBlueprintLibrary.md#getboneposefortime)
- [GetBonePosesForFrame](ue_ue.AnimationBlueprintLibrary.md#getboneposesforframe)
- [GetBonePosesForTime](ue_ue.AnimationBlueprintLibrary.md#getboneposesfortime)
- [GetCompressionScheme](ue_ue.AnimationBlueprintLibrary.md#getcompressionscheme)
- [GetFloatKeys](ue_ue.AnimationBlueprintLibrary.md#getfloatkeys)
- [GetFrameAtTime](ue_ue.AnimationBlueprintLibrary.md#getframeattime)
- [GetMetaData](ue_ue.AnimationBlueprintLibrary.md#getmetadata)
- [GetMetaDataOfClass](ue_ue.AnimationBlueprintLibrary.md#getmetadataofclass)
- [GetNumFrames](ue_ue.AnimationBlueprintLibrary.md#getnumframes)
- [GetRateScale](ue_ue.AnimationBlueprintLibrary.md#getratescale)
- [GetRawTrackData](ue_ue.AnimationBlueprintLibrary.md#getrawtrackdata)
- [GetRawTrackPositionData](ue_ue.AnimationBlueprintLibrary.md#getrawtrackpositiondata)
- [GetRawTrackRotationData](ue_ue.AnimationBlueprintLibrary.md#getrawtrackrotationdata)
- [GetRawTrackScaleData](ue_ue.AnimationBlueprintLibrary.md#getrawtrackscaledata)
- [GetRootMotionLockType](ue_ue.AnimationBlueprintLibrary.md#getrootmotionlocktype)
- [GetSequenceLength](ue_ue.AnimationBlueprintLibrary.md#getsequencelength)
- [GetTimeAtFrame](ue_ue.AnimationBlueprintLibrary.md#gettimeatframe)
- [GetTransformationKeys](ue_ue.AnimationBlueprintLibrary.md#gettransformationkeys)
- [GetUniqueMarkerNames](ue_ue.AnimationBlueprintLibrary.md#getuniquemarkernames)
- [GetVectorKeys](ue_ue.AnimationBlueprintLibrary.md#getvectorkeys)
- [IsRootMotionEnabled](ue_ue.AnimationBlueprintLibrary.md#isrootmotionenabled)
- [IsRootMotionLockForced](ue_ue.AnimationBlueprintLibrary.md#isrootmotionlockforced)
- [IsValidAnimNotifyTrackName](ue_ue.AnimationBlueprintLibrary.md#isvalidanimnotifytrackname)
- [IsValidAnimationSyncMarkerName](ue_ue.AnimationBlueprintLibrary.md#isvalidanimationsyncmarkername)
- [IsValidRawAnimationTrackName](ue_ue.AnimationBlueprintLibrary.md#isvalidrawanimationtrackname)
- [IsValidTime](ue_ue.AnimationBlueprintLibrary.md#isvalidtime)
- [Load](ue_ue.AnimationBlueprintLibrary.md#load)
- [RemoveAllAnimationNotifyTracks](ue_ue.AnimationBlueprintLibrary.md#removeallanimationnotifytracks)
- [RemoveAllAnimationSyncMarkers](ue_ue.AnimationBlueprintLibrary.md#removeallanimationsyncmarkers)
- [RemoveAllBoneAnimation](ue_ue.AnimationBlueprintLibrary.md#removeallboneanimation)
- [RemoveAllCurveData](ue_ue.AnimationBlueprintLibrary.md#removeallcurvedata)
- [RemoveAllMetaData](ue_ue.AnimationBlueprintLibrary.md#removeallmetadata)
- [RemoveAllVirtualBones](ue_ue.AnimationBlueprintLibrary.md#removeallvirtualbones)
- [RemoveAnimationNotifyEventsByName](ue_ue.AnimationBlueprintLibrary.md#removeanimationnotifyeventsbyname)
- [RemoveAnimationNotifyEventsByTrack](ue_ue.AnimationBlueprintLibrary.md#removeanimationnotifyeventsbytrack)
- [RemoveAnimationNotifyTrack](ue_ue.AnimationBlueprintLibrary.md#removeanimationnotifytrack)
- [RemoveAnimationSyncMarkersByName](ue_ue.AnimationBlueprintLibrary.md#removeanimationsyncmarkersbyname)
- [RemoveAnimationSyncMarkersByTrack](ue_ue.AnimationBlueprintLibrary.md#removeanimationsyncmarkersbytrack)
- [RemoveBoneAnimation](ue_ue.AnimationBlueprintLibrary.md#removeboneanimation)
- [RemoveCurve](ue_ue.AnimationBlueprintLibrary.md#removecurve)
- [RemoveMetaData](ue_ue.AnimationBlueprintLibrary.md#removemetadata)
- [RemoveMetaDataOfClass](ue_ue.AnimationBlueprintLibrary.md#removemetadataofclass)
- [RemoveVirtualBone](ue_ue.AnimationBlueprintLibrary.md#removevirtualbone)
- [RemoveVirtualBones](ue_ue.AnimationBlueprintLibrary.md#removevirtualbones)
- [ReplaceAnimNotifies](ue_ue.AnimationBlueprintLibrary.md#replaceanimnotifies)
- [ReplaceAnimNotifyStates](ue_ue.AnimationBlueprintLibrary.md#replaceanimnotifystates)
- [SetAdditiveAnimationType](ue_ue.AnimationBlueprintLibrary.md#setadditiveanimationtype)
- [SetAdditiveBasePoseType](ue_ue.AnimationBlueprintLibrary.md#setadditivebaseposetype)
- [SetAnimationInterpolationType](ue_ue.AnimationBlueprintLibrary.md#setanimationinterpolationtype)
- [SetCompressionScheme](ue_ue.AnimationBlueprintLibrary.md#setcompressionscheme)
- [SetIsRootMotionLockForced](ue_ue.AnimationBlueprintLibrary.md#setisrootmotionlockforced)
- [SetRateScale](ue_ue.AnimationBlueprintLibrary.md#setratescale)
- [SetRootMotionEnabled](ue_ue.AnimationBlueprintLibrary.md#setrootmotionenabled)
- [SetRootMotionLockType](ue_ue.AnimationBlueprintLibrary.md#setrootmotionlocktype)
- [StaticClass](ue_ue.AnimationBlueprintLibrary.md#staticclass)

## Constructors

### constructor

• **new AnimationBlueprintLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:16603](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16603)

## Properties

### \_\_tid\_AnimationBlueprintLibrary\_\_

• **\_\_tid\_AnimationBlueprintLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:16695](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16695)

___

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13418)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### AddAnimationNotifyEvent

▸ `Static` **AddAnimationNotifyEvent**(`AnimationSequence`, `NotifyTrackName`, `StartTime`, `NotifyClass`): [`AnimNotify`](ue_ue.AnimNotify.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `NotifyTrackName` | `string` |
| `StartTime` | `number` |
| `NotifyClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`AnimNotify`](ue_ue.AnimNotify.md)

#### Defined in

[ue/ue.d.ts:16604](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16604)

___

### AddAnimationNotifyEventObject

▸ `Static` **AddAnimationNotifyEventObject**(`AnimationSequence`, `StartTime`, `Notify`, `NotifyTrackName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `StartTime` | `number` |
| `Notify` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimNotify`](ue_ue.AnimNotify.md)\> |
| `NotifyTrackName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16605](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16605)

___

### AddAnimationNotifyStateEvent

▸ `Static` **AddAnimationNotifyStateEvent**(`AnimationSequence`, `NotifyTrackName`, `StartTime`, `Duration`, `NotifyStateClass`): [`AnimNotifyState`](ue_ue.AnimNotifyState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `NotifyTrackName` | `string` |
| `StartTime` | `number` |
| `Duration` | `number` |
| `NotifyStateClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`AnimNotifyState`](ue_ue.AnimNotifyState.md)

#### Defined in

[ue/ue.d.ts:16606](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16606)

___

### AddAnimationNotifyStateEventObject

▸ `Static` **AddAnimationNotifyStateEventObject**(`AnimationSequence`, `StartTime`, `Duration`, `NotifyState`, `NotifyTrackName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `StartTime` | `number` |
| `Duration` | `number` |
| `NotifyState` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimNotifyState`](ue_ue.AnimNotifyState.md)\> |
| `NotifyTrackName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16607)

___

### AddAnimationNotifyTrack

▸ `Static` **AddAnimationNotifyTrack**(`AnimationSequence`, `NotifyTrackName`, `TrackColor?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `NotifyTrackName` | `string` |
| `TrackColor?` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16608](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16608)

___

### AddAnimationSyncMarker

▸ `Static` **AddAnimationSyncMarker**(`AnimationSequence`, `MarkerName`, `Time`, `NotifyTrackName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `MarkerName` | `string` |
| `Time` | `number` |
| `NotifyTrackName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16609](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16609)

___

### AddCurve

▸ `Static` **AddCurve**(`AnimationSequence`, `CurveName`, `CurveType?`, `bMetaDataCurve?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `CurveName` | `string` |
| `CurveType?` | [`ERawCurveTrackTypes`](../enums/ue_ue.ERawCurveTrackTypes.md) |
| `bMetaDataCurve?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16610](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16610)

___

### AddFloatCurveKey

▸ `Static` **AddFloatCurveKey**(`AnimationSequence`, `CurveName`, `Time`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `CurveName` | `string` |
| `Time` | `number` |
| `Value` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16611](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16611)

___

### AddFloatCurveKeys

▸ `Static` **AddFloatCurveKeys**(`AnimationSequence`, `CurveName`, `Times`, `Values`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `CurveName` | `string` |
| `Times` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `Values` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16612](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16612)

___

### AddMetaData

▸ `Static` **AddMetaData**(`AnimationSequence`, `MetaDataClass`, `MetaDataInstance`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `MetaDataClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `MetaDataInstance` | [`AnimMetaData`](ue_ue.AnimMetaData.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16613](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16613)

___

### AddMetaDataObject

▸ `Static` **AddMetaDataObject**(`AnimationSequence`, `MetaDataObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `MetaDataObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16614](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16614)

___

### AddTransformationCurveKey

▸ `Static` **AddTransformationCurveKey**(`AnimationSequence`, `CurveName`, `Time`, `Transform`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `CurveName` | `string` |
| `Time` | `number` |
| `Transform` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16615](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16615)

___

### AddTransformationCurveKeys

▸ `Static` **AddTransformationCurveKeys**(`AnimationSequence`, `CurveName`, `Times`, `Transforms`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `CurveName` | `string` |
| `Times` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `Transforms` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16616](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16616)

___

### AddVectorCurveKey

▸ `Static` **AddVectorCurveKey**(`AnimationSequence`, `CurveName`, `Time`, `Vector`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `CurveName` | `string` |
| `Time` | `number` |
| `Vector` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16617](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16617)

___

### AddVectorCurveKeys

▸ `Static` **AddVectorCurveKeys**(`AnimationSequence`, `CurveName`, `Times`, `Vectors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `CurveName` | `string` |
| `Times` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `Vectors` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16618](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16618)

___

### AddVirtualBone

▸ `Static` **AddVirtualBone**(`AnimationSequence`, `SourceBoneName`, `TargetBoneName`, `VirtualBoneName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `SourceBoneName` | `string` |
| `TargetBoneName` | `string` |
| `VirtualBoneName` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16619](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16619)

___

### ContainsMetaDataOfClass

▸ `Static` **ContainsMetaDataOfClass**(`AnimationSequence`, `MetaDataClass`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `MetaDataClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:16620](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16620)

___

### CopyAnimNotifiesFromSequence

▸ `Static` **CopyAnimNotifiesFromSequence**(`SrcAnimSequence`, `DestAnimSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SrcAnimSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `DestAnimSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16621](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16621)

___

### DoesBoneNameExist

▸ `Static` **DoesBoneNameExist**(`AnimationSequence`, `BoneName`, `bExists`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `BoneName` | `string` |
| `bExists` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16622](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16622)

___

### DoesCurveExist

▸ `Static` **DoesCurveExist**(`AnimationSequence`, `CurveName`, `CurveType`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `CurveName` | `string` |
| `CurveType` | [`ERawCurveTrackTypes`](../enums/ue_ue.ERawCurveTrackTypes.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:16623](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16623)

___

### FinalizeBoneAnimation

▸ `Static` **FinalizeBoneAnimation**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16624](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16624)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimationBlueprintLibrary`](ue_ue.AnimationBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimationBlueprintLibrary`](ue_ue.AnimationBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:16692](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16692)

___

### FindBonePathToRoot

▸ `Static` **FindBonePathToRoot**(`AnimationSequence`, `BoneName`, `BonePath`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `BoneName` | `string` |
| `BonePath` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16625](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16625)

___

### GetAdditiveAnimationType

▸ `Static` **GetAdditiveAnimationType**(`AnimationSequence`, `AdditiveAnimationType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `AdditiveAnimationType` | [`$Ref`](../interfaces/puerts._Ref.md)<[`EAdditiveAnimationType`](../enums/ue_ue.EAdditiveAnimationType.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16626](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16626)

___

### GetAdditiveBasePoseType

▸ `Static` **GetAdditiveBasePoseType**(`AnimationSequence`, `AdditiveBasePoseType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `AdditiveBasePoseType` | [`$Ref`](../interfaces/puerts._Ref.md)<[`EAdditiveBasePoseType`](../enums/ue_ue.EAdditiveBasePoseType.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16627](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16627)

___

### GetAnimNotifyEventTriggerTime

▸ `Static` **GetAnimNotifyEventTriggerTime**(`NotifyEvent`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NotifyEvent` | [`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md) |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:16636](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16636)

___

### GetAnimationInterpolationType

▸ `Static` **GetAnimationInterpolationType**(`AnimationSequence`, `InterpolationType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `InterpolationType` | [`$Ref`](../interfaces/puerts._Ref.md)<[`EAnimInterpolationType`](../enums/ue_ue.EAnimInterpolationType.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16628](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16628)

___

### GetAnimationNotifyEventNames

▸ `Static` **GetAnimationNotifyEventNames**(`AnimationSequence`, `EventNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `EventNames` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16629](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16629)

___

### GetAnimationNotifyEvents

▸ `Static` **GetAnimationNotifyEvents**(`AnimationSequence`, `NotifyEvents`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `NotifyEvents` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16630](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16630)

___

### GetAnimationNotifyEventsForTrack

▸ `Static` **GetAnimationNotifyEventsForTrack**(`AnimationSequence`, `NotifyTrackName`, `Events`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `NotifyTrackName` | `string` |
| `Events` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16631](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16631)

___

### GetAnimationNotifyTrackNames

▸ `Static` **GetAnimationNotifyTrackNames**(`AnimationSequence`, `TrackNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `TrackNames` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16632](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16632)

___

### GetAnimationSyncMarkers

▸ `Static` **GetAnimationSyncMarkers**(`AnimationSequence`, `Markers`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `Markers` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimSyncMarker`](ue_ue.AnimSyncMarker.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16633](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16633)

___

### GetAnimationSyncMarkersForTrack

▸ `Static` **GetAnimationSyncMarkersForTrack**(`AnimationSequence`, `NotifyTrackName`, `Markers`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `NotifyTrackName` | `string` |
| `Markers` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimSyncMarker`](ue_ue.AnimSyncMarker.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16634](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16634)

___

### GetAnimationTrackNames

▸ `Static` **GetAnimationTrackNames**(`AnimationSequence`, `TrackNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `TrackNames` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16635](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16635)

___

### GetBonePoseForFrame

▸ `Static` **GetBonePoseForFrame**(`AnimationSequence`, `BoneName`, `Frame`, `bExtractRootMotion`, `Pose`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `BoneName` | `string` |
| `Frame` | `number` |
| `bExtractRootMotion` | `boolean` |
| `Pose` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Transform`](ue_ue_s.Transform.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16637](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16637)

___

### GetBonePoseForTime

▸ `Static` **GetBonePoseForTime**(`AnimationSequence`, `BoneName`, `Time`, `bExtractRootMotion`, `Pose`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `BoneName` | `string` |
| `Time` | `number` |
| `bExtractRootMotion` | `boolean` |
| `Pose` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Transform`](ue_ue_s.Transform.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16638](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16638)

___

### GetBonePosesForFrame

▸ `Static` **GetBonePosesForFrame**(`AnimationSequence`, `BoneNames`, `Frame`, `bExtractRootMotion`, `Poses`, `PreviewMesh?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `BoneNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `Frame` | `number` |
| `bExtractRootMotion` | `boolean` |
| `Poses` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\>\> |
| `PreviewMesh?` | [`SkeletalMesh`](ue_ue.SkeletalMesh.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16639](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16639)

___

### GetBonePosesForTime

▸ `Static` **GetBonePosesForTime**(`AnimationSequence`, `BoneNames`, `Time`, `bExtractRootMotion`, `Poses`, `PreviewMesh?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `BoneNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `Time` | `number` |
| `bExtractRootMotion` | `boolean` |
| `Poses` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\>\> |
| `PreviewMesh?` | [`SkeletalMesh`](ue_ue.SkeletalMesh.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16640](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16640)

___

### GetCompressionScheme

▸ `Static` **GetCompressionScheme**(`AnimationSequence`, `CompressionScheme`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `CompressionScheme` | [`$Ref`](../interfaces/puerts._Ref.md)<[`AnimCompress`](ue_ue.AnimCompress.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16641](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16641)

___

### GetFloatKeys

▸ `Static` **GetFloatKeys**(`AnimationSequence`, `CurveName`, `Times`, `Values`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `CurveName` | `string` |
| `Times` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>\> |
| `Values` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16642](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16642)

___

### GetFrameAtTime

▸ `Static` **GetFrameAtTime**(`AnimationSequence`, `Time`, `Frame`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `Time` | `number` |
| `Frame` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16643](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16643)

___

### GetMetaData

▸ `Static` **GetMetaData**(`AnimationSequence`, `MetaData`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `MetaData` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16644](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16644)

___

### GetMetaDataOfClass

▸ `Static` **GetMetaDataOfClass**(`AnimationSequence`, `MetaDataClass`, `MetaDataOfClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `MetaDataClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `MetaDataOfClass` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16645](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16645)

___

### GetNumFrames

▸ `Static` **GetNumFrames**(`AnimationSequence`, `NumFrames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `NumFrames` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16646](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16646)

___

### GetRateScale

▸ `Static` **GetRateScale**(`AnimationSequence`, `RateScale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `RateScale` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16647](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16647)

___

### GetRawTrackData

▸ `Static` **GetRawTrackData**(`AnimationSequence`, `TrackName`, `PositionKeys`, `RotationKeys`, `ScalingKeys`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `TrackName` | `string` |
| `PositionKeys` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |
| `RotationKeys` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Quat`](ue_ue_s.Quat.md)\>\> |
| `ScalingKeys` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16648](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16648)

___

### GetRawTrackPositionData

▸ `Static` **GetRawTrackPositionData**(`AnimationSequence`, `TrackName`, `PositionData`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `TrackName` | `string` |
| `PositionData` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16649](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16649)

___

### GetRawTrackRotationData

▸ `Static` **GetRawTrackRotationData**(`AnimationSequence`, `TrackName`, `RotationData`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `TrackName` | `string` |
| `RotationData` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Quat`](ue_ue_s.Quat.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16650](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16650)

___

### GetRawTrackScaleData

▸ `Static` **GetRawTrackScaleData**(`AnimationSequence`, `TrackName`, `ScaleData`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `TrackName` | `string` |
| `ScaleData` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16651](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16651)

___

### GetRootMotionLockType

▸ `Static` **GetRootMotionLockType**(`AnimationSequence`, `LockType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `LockType` | [`$Ref`](../interfaces/puerts._Ref.md)<[`ERootMotionRootLock`](../enums/ue_ue.ERootMotionRootLock.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16652](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16652)

___

### GetSequenceLength

▸ `Static` **GetSequenceLength**(`AnimationSequence`, `Length`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `Length` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16653](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16653)

___

### GetTimeAtFrame

▸ `Static` **GetTimeAtFrame**(`AnimationSequence`, `Frame`, `Time`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `Frame` | `number` |
| `Time` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16654](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16654)

___

### GetTransformationKeys

▸ `Static` **GetTransformationKeys**(`AnimationSequence`, `CurveName`, `Times`, `Values`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `CurveName` | `string` |
| `Times` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>\> |
| `Values` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Transform`](ue_ue_s.Transform.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16655](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16655)

___

### GetUniqueMarkerNames

▸ `Static` **GetUniqueMarkerNames**(`AnimationSequence`, `MarkerNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `MarkerNames` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16656](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16656)

___

### GetVectorKeys

▸ `Static` **GetVectorKeys**(`AnimationSequence`, `CurveName`, `Times`, `Values`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `CurveName` | `string` |
| `Times` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>\> |
| `Values` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16657](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16657)

___

### IsRootMotionEnabled

▸ `Static` **IsRootMotionEnabled**(`AnimationSequence`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:16658](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16658)

___

### IsRootMotionLockForced

▸ `Static` **IsRootMotionLockForced**(`AnimationSequence`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:16659](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16659)

___

### IsValidAnimNotifyTrackName

▸ `Static` **IsValidAnimNotifyTrackName**(`AnimationSequence`, `NotifyTrackName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `NotifyTrackName` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:16661](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16661)

___

### IsValidAnimationSyncMarkerName

▸ `Static` **IsValidAnimationSyncMarkerName**(`AnimationSequence`, `MarkerName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `MarkerName` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:16660](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16660)

___

### IsValidRawAnimationTrackName

▸ `Static` **IsValidRawAnimationTrackName**(`AnimationSequence`, `TrackName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `TrackName` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:16662](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16662)

___

### IsValidTime

▸ `Static` **IsValidTime**(`AnimationSequence`, `Time`, `IsValid`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `Time` | `number` |
| `IsValid` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16663](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16663)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimationBlueprintLibrary`](ue_ue.AnimationBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimationBlueprintLibrary`](ue_ue.AnimationBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:16693](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16693)

___

### RemoveAllAnimationNotifyTracks

▸ `Static` **RemoveAllAnimationNotifyTracks**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16664](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16664)

___

### RemoveAllAnimationSyncMarkers

▸ `Static` **RemoveAllAnimationSyncMarkers**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16665](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16665)

___

### RemoveAllBoneAnimation

▸ `Static` **RemoveAllBoneAnimation**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16666](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16666)

___

### RemoveAllCurveData

▸ `Static` **RemoveAllCurveData**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16667](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16667)

___

### RemoveAllMetaData

▸ `Static` **RemoveAllMetaData**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16668](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16668)

___

### RemoveAllVirtualBones

▸ `Static` **RemoveAllVirtualBones**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16669](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16669)

___

### RemoveAnimationNotifyEventsByName

▸ `Static` **RemoveAnimationNotifyEventsByName**(`AnimationSequence`, `NotifyName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `NotifyName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:16670](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16670)

___

### RemoveAnimationNotifyEventsByTrack

▸ `Static` **RemoveAnimationNotifyEventsByTrack**(`AnimationSequence`, `NotifyTrackName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `NotifyTrackName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:16671](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16671)

___

### RemoveAnimationNotifyTrack

▸ `Static` **RemoveAnimationNotifyTrack**(`AnimationSequence`, `NotifyTrackName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `NotifyTrackName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16672](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16672)

___

### RemoveAnimationSyncMarkersByName

▸ `Static` **RemoveAnimationSyncMarkersByName**(`AnimationSequence`, `MarkerName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `MarkerName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:16673](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16673)

___

### RemoveAnimationSyncMarkersByTrack

▸ `Static` **RemoveAnimationSyncMarkersByTrack**(`AnimationSequence`, `NotifyTrackName`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `NotifyTrackName` | `string` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:16674](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16674)

___

### RemoveBoneAnimation

▸ `Static` **RemoveBoneAnimation**(`AnimationSequence`, `BoneName`, `bIncludeChildren?`, `bFinalize?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `BoneName` | `string` |
| `bIncludeChildren?` | `boolean` |
| `bFinalize?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16675](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16675)

___

### RemoveCurve

▸ `Static` **RemoveCurve**(`AnimationSequence`, `CurveName`, `bRemoveNameFromSkeleton?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `CurveName` | `string` |
| `bRemoveNameFromSkeleton?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16676](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16676)

___

### RemoveMetaData

▸ `Static` **RemoveMetaData**(`AnimationSequence`, `MetaDataObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `MetaDataObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMetaData`](ue_ue.AnimMetaData.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16677](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16677)

___

### RemoveMetaDataOfClass

▸ `Static` **RemoveMetaDataOfClass**(`AnimationSequence`, `MetaDataClass`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `MetaDataClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16678](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16678)

___

### RemoveVirtualBone

▸ `Static` **RemoveVirtualBone**(`AnimationSequence`, `VirtualBoneName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `VirtualBoneName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16679](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16679)

___

### RemoveVirtualBones

▸ `Static` **RemoveVirtualBones**(`AnimationSequence`, `VirtualBoneNames`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `VirtualBoneNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16680](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16680)

___

### ReplaceAnimNotifies

▸ `Static` **ReplaceAnimNotifies**(`AnimationSequence`, `OldNotifyClass`, `NewNotifyClass`, `OnNotifyReplaced`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)\> |
| `OldNotifyClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `NewNotifyClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `OnNotifyReplaced` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`OldNotify`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimNotify`](ue_ue.AnimNotify.md)\>, `NewNotify`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimNotify`](ue_ue.AnimNotify.md)\>) => `void`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16681](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16681)

___

### ReplaceAnimNotifyStates

▸ `Static` **ReplaceAnimNotifyStates**(`AnimationSequence`, `OldNotifyClass`, `NewNotifyClass`, `OnNotifyStateReplaced`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)\> |
| `OldNotifyClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `NewNotifyClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `OnNotifyStateReplaced` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`OldNotifyState`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimNotifyState`](ue_ue.AnimNotifyState.md)\>, `NewNotifyState`: [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimNotifyState`](ue_ue.AnimNotifyState.md)\>) => `void`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16682](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16682)

___

### SetAdditiveAnimationType

▸ `Static` **SetAdditiveAnimationType**(`AnimationSequence`, `AdditiveAnimationType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `AdditiveAnimationType` | [`EAdditiveAnimationType`](../enums/ue_ue.EAdditiveAnimationType.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16683](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16683)

___

### SetAdditiveBasePoseType

▸ `Static` **SetAdditiveBasePoseType**(`AnimationSequence`, `AdditiveBasePoseType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `AdditiveBasePoseType` | [`EAdditiveBasePoseType`](../enums/ue_ue.EAdditiveBasePoseType.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16684](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16684)

___

### SetAnimationInterpolationType

▸ `Static` **SetAnimationInterpolationType**(`AnimationSequence`, `InterpolationType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `InterpolationType` | [`EAnimInterpolationType`](../enums/ue_ue.EAnimInterpolationType.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16685](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16685)

___

### SetCompressionScheme

▸ `Static` **SetCompressionScheme**(`AnimationSequence`, `CompressionScheme`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `CompressionScheme` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimCompress`](ue_ue.AnimCompress.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16686](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16686)

___

### SetIsRootMotionLockForced

▸ `Static` **SetIsRootMotionLockForced**(`AnimationSequence`, `bForced`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `bForced` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16687](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16687)

___

### SetRateScale

▸ `Static` **SetRateScale**(`AnimationSequence`, `RateScale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `RateScale` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16688](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16688)

___

### SetRootMotionEnabled

▸ `Static` **SetRootMotionEnabled**(`AnimationSequence`, `bEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `bEnabled` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16689](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16689)

___

### SetRootMotionLockType

▸ `Static` **SetRootMotionLockType**(`AnimationSequence`, `RootMotionLockType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |
| `RootMotionLockType` | [`ERootMotionRootLock`](../enums/ue_ue.ERootMotionRootLock.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:16690](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16690)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:16691](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16691)
