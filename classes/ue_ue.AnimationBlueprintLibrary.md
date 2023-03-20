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

## Properties

### \_\_tid\_AnimationBlueprintLibrary\_\_

• **\_\_tid\_AnimationBlueprintLibrary\_\_**: `boolean`

___

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

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

___

### FinalizeBoneAnimation

▸ `Static` **FinalizeBoneAnimation**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

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

___

### GetAnimNotifyEventTriggerTime

▸ `Static` **GetAnimNotifyEventTriggerTime**(`NotifyEvent`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NotifyEvent` | [`AnimNotifyEvent`](ue_ue.AnimNotifyEvent.md) |

#### Returns

`number`

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

___

### IsRootMotionEnabled

▸ `Static` **IsRootMotionEnabled**(`AnimationSequence`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`boolean`

___

### IsRootMotionLockForced

▸ `Static` **IsRootMotionLockForced**(`AnimationSequence`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`boolean`

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

___

### RemoveAllAnimationNotifyTracks

▸ `Static` **RemoveAllAnimationNotifyTracks**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

___

### RemoveAllAnimationSyncMarkers

▸ `Static` **RemoveAllAnimationSyncMarkers**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

___

### RemoveAllBoneAnimation

▸ `Static` **RemoveAllBoneAnimation**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

___

### RemoveAllCurveData

▸ `Static` **RemoveAllCurveData**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

___

### RemoveAllMetaData

▸ `Static` **RemoveAllMetaData**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

___

### RemoveAllVirtualBones

▸ `Static` **RemoveAllVirtualBones**(`AnimationSequence`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AnimationSequence` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequence`](ue_ue.AnimSequence.md)\> |

#### Returns

`void`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)
