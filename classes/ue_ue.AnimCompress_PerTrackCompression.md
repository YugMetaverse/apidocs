[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimCompress\_PerTrackCompression

# Class: AnimCompress\_PerTrackCompression

[ue/ue](../modules/ue_ue.md).AnimCompress_PerTrackCompression

## Hierarchy

- [`AnimCompress_RemoveLinearKeys`](ue_ue.AnimCompress_RemoveLinearKeys.md)

  ↳ **`AnimCompress_PerTrackCompression`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimCompress_PerTrackCompression.md#constructor)

### Properties

- [AllowedRotationFormats](ue_ue.AnimCompress_PerTrackCompression.md#allowedrotationformats)
- [AllowedScaleFormats](ue_ue.AnimCompress_PerTrackCompression.md#allowedscaleformats)
- [AllowedTranslationFormats](ue_ue.AnimCompress_PerTrackCompression.md#allowedtranslationformats)
- [Description](ue_ue.AnimCompress_PerTrackCompression.md#description)
- [EffectorDiffSocket](ue_ue.AnimCompress_PerTrackCompression.md#effectordiffsocket)
- [IdealNumFramesPerSegment](ue_ue.AnimCompress_PerTrackCompression.md#idealnumframespersegment)
- [MaxAngleDiff](ue_ue.AnimCompress_PerTrackCompression.md#maxanglediff)
- [MaxAngleDiffBitwise](ue_ue.AnimCompress_PerTrackCompression.md#maxanglediffbitwise)
- [MaxCurveError](ue_ue.AnimCompress_PerTrackCompression.md#maxcurveerror)
- [MaxEffectorDiff](ue_ue.AnimCompress_PerTrackCompression.md#maxeffectordiff)
- [MaxErrorPerTrackRatio](ue_ue.AnimCompress_PerTrackCompression.md#maxerrorpertrackratio)
- [MaxNumFramesPerSegment](ue_ue.AnimCompress_PerTrackCompression.md#maxnumframespersegment)
- [MaxPosDiff](ue_ue.AnimCompress_PerTrackCompression.md#maxposdiff)
- [MaxPosDiffBitwise](ue_ue.AnimCompress_PerTrackCompression.md#maxposdiffbitwise)
- [MaxScaleDiff](ue_ue.AnimCompress_PerTrackCompression.md#maxscalediff)
- [MaxScaleDiffBitwise](ue_ue.AnimCompress_PerTrackCompression.md#maxscalediffbitwise)
- [MaxZeroingThreshold](ue_ue.AnimCompress_PerTrackCompression.md#maxzeroingthreshold)
- [MinEffectorDiff](ue_ue.AnimCompress_PerTrackCompression.md#mineffectordiff)
- [MinKeysForResampling](ue_ue.AnimCompress_PerTrackCompression.md#minkeysforresampling)
- [ParentKeyScale](ue_ue.AnimCompress_PerTrackCompression.md#parentkeyscale)
- [ParentingDivisor](ue_ue.AnimCompress_PerTrackCompression.md#parentingdivisor)
- [ParentingDivisorExponent](ue_ue.AnimCompress_PerTrackCompression.md#parentingdivisorexponent)
- [PerturbationProbeSize](ue_ue.AnimCompress_PerTrackCompression.md#perturbationprobesize)
- [ResampledFramerate](ue_ue.AnimCompress_PerTrackCompression.md#resampledframerate)
- [RotationCompressionFormat](ue_ue.AnimCompress_PerTrackCompression.md#rotationcompressionformat)
- [RotationErrorSourceRatio](ue_ue.AnimCompress_PerTrackCompression.md#rotationerrorsourceratio)
- [ScaleCompressionFormat](ue_ue.AnimCompress_PerTrackCompression.md#scalecompressionformat)
- [ScaleErrorSourceRatio](ue_ue.AnimCompress_PerTrackCompression.md#scaleerrorsourceratio)
- [TrackHeightBias](ue_ue.AnimCompress_PerTrackCompression.md#trackheightbias)
- [TranslationCompressionFormat](ue_ue.AnimCompress_PerTrackCompression.md#translationcompressionformat)
- [TranslationErrorSourceRatio](ue_ue.AnimCompress_PerTrackCompression.md#translationerrorsourceratio)
- [\_\_tid\_AnimCompress\_PerTrackCompression\_\_](ue_ue.AnimCompress_PerTrackCompression.md#__tid_animcompress_pertrackcompression__)
- [\_\_tid\_AnimCompress\_RemoveLinearKeys\_\_](ue_ue.AnimCompress_PerTrackCompression.md#__tid_animcompress_removelinearkeys__)
- [\_\_tid\_AnimCompress\_\_](ue_ue.AnimCompress_PerTrackCompression.md#__tid_animcompress__)
- [\_\_tid\_Object\_\_](ue_ue.AnimCompress_PerTrackCompression.md#__tid_object__)
- [bActuallyFilterLinearKeys](ue_ue.AnimCompress_PerTrackCompression.md#bactuallyfilterlinearkeys)
- [bEnableSegmenting](ue_ue.AnimCompress_PerTrackCompression.md#benablesegmenting)
- [bNeedsSkeleton](ue_ue.AnimCompress_PerTrackCompression.md#bneedsskeleton)
- [bOptimizeForForwardPlayback](ue_ue.AnimCompress_PerTrackCompression.md#boptimizeforforwardplayback)
- [bResampleAnimation](ue_ue.AnimCompress_PerTrackCompression.md#bresampleanimation)
- [bRetarget](ue_ue.AnimCompress_PerTrackCompression.md#bretarget)
- [bUseAdaptiveError](ue_ue.AnimCompress_PerTrackCompression.md#buseadaptiveerror)
- [bUseAdaptiveError2](ue_ue.AnimCompress_PerTrackCompression.md#buseadaptiveerror2)
- [bUseDecompression](ue_ue.AnimCompress_PerTrackCompression.md#busedecompression)
- [bUseMultithreading](ue_ue.AnimCompress_PerTrackCompression.md#busemultithreading)
- [bUseOverrideForEndEffectors](ue_ue.AnimCompress_PerTrackCompression.md#buseoverrideforendeffectors)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimCompress_PerTrackCompression.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimCompress_PerTrackCompression.md#executeubergraph)
- [GetClass](ue_ue.AnimCompress_PerTrackCompression.md#getclass)
- [GetName](ue_ue.AnimCompress_PerTrackCompression.md#getname)
- [GetOuter](ue_ue.AnimCompress_PerTrackCompression.md#getouter)
- [GetWorld](ue_ue.AnimCompress_PerTrackCompression.md#getworld)
- [Find](ue_ue.AnimCompress_PerTrackCompression.md#find)
- [Load](ue_ue.AnimCompress_PerTrackCompression.md#load)
- [StaticClass](ue_ue.AnimCompress_PerTrackCompression.md#staticclass)

## Constructors

### constructor

• **new AnimCompress_PerTrackCompression**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[constructor](ue_ue.AnimCompress_RemoveLinearKeys.md#constructor)

## Properties

### AllowedRotationFormats

• **AllowedRotationFormats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)\>

___

### AllowedScaleFormats

• **AllowedScaleFormats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)\>

___

### AllowedTranslationFormats

• **AllowedTranslationFormats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)\>

___

### Description

• **Description**: `string`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[Description](ue_ue.AnimCompress_RemoveLinearKeys.md#description)

___

### EffectorDiffSocket

• **EffectorDiffSocket**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[EffectorDiffSocket](ue_ue.AnimCompress_RemoveLinearKeys.md#effectordiffsocket)

___

### IdealNumFramesPerSegment

• **IdealNumFramesPerSegment**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[IdealNumFramesPerSegment](ue_ue.AnimCompress_RemoveLinearKeys.md#idealnumframespersegment)

___

### MaxAngleDiff

• **MaxAngleDiff**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[MaxAngleDiff](ue_ue.AnimCompress_RemoveLinearKeys.md#maxanglediff)

___

### MaxAngleDiffBitwise

• **MaxAngleDiffBitwise**: `number`

___

### MaxCurveError

• **MaxCurveError**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[MaxCurveError](ue_ue.AnimCompress_RemoveLinearKeys.md#maxcurveerror)

___

### MaxEffectorDiff

• **MaxEffectorDiff**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[MaxEffectorDiff](ue_ue.AnimCompress_RemoveLinearKeys.md#maxeffectordiff)

___

### MaxErrorPerTrackRatio

• **MaxErrorPerTrackRatio**: `number`

___

### MaxNumFramesPerSegment

• **MaxNumFramesPerSegment**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[MaxNumFramesPerSegment](ue_ue.AnimCompress_RemoveLinearKeys.md#maxnumframespersegment)

___

### MaxPosDiff

• **MaxPosDiff**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[MaxPosDiff](ue_ue.AnimCompress_RemoveLinearKeys.md#maxposdiff)

___

### MaxPosDiffBitwise

• **MaxPosDiffBitwise**: `number`

___

### MaxScaleDiff

• **MaxScaleDiff**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[MaxScaleDiff](ue_ue.AnimCompress_RemoveLinearKeys.md#maxscalediff)

___

### MaxScaleDiffBitwise

• **MaxScaleDiffBitwise**: `number`

___

### MaxZeroingThreshold

• **MaxZeroingThreshold**: `number`

___

### MinEffectorDiff

• **MinEffectorDiff**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[MinEffectorDiff](ue_ue.AnimCompress_RemoveLinearKeys.md#mineffectordiff)

___

### MinKeysForResampling

• **MinKeysForResampling**: `number`

___

### ParentKeyScale

• **ParentKeyScale**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[ParentKeyScale](ue_ue.AnimCompress_RemoveLinearKeys.md#parentkeyscale)

___

### ParentingDivisor

• **ParentingDivisor**: `number`

___

### ParentingDivisorExponent

• **ParentingDivisorExponent**: `number`

___

### PerturbationProbeSize

• **PerturbationProbeSize**: `number`

___

### ResampledFramerate

• **ResampledFramerate**: `number`

___

### RotationCompressionFormat

• **RotationCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[RotationCompressionFormat](ue_ue.AnimCompress_RemoveLinearKeys.md#rotationcompressionformat)

___

### RotationErrorSourceRatio

• **RotationErrorSourceRatio**: `number`

___

### ScaleCompressionFormat

• **ScaleCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[ScaleCompressionFormat](ue_ue.AnimCompress_RemoveLinearKeys.md#scalecompressionformat)

___

### ScaleErrorSourceRatio

• **ScaleErrorSourceRatio**: `number`

___

### TrackHeightBias

• **TrackHeightBias**: `number`

___

### TranslationCompressionFormat

• **TranslationCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[TranslationCompressionFormat](ue_ue.AnimCompress_RemoveLinearKeys.md#translationcompressionformat)

___

### TranslationErrorSourceRatio

• **TranslationErrorSourceRatio**: `number`

___

### \_\_tid\_AnimCompress\_PerTrackCompression\_\_

• **\_\_tid\_AnimCompress\_PerTrackCompression\_\_**: `boolean`

___

### \_\_tid\_AnimCompress\_RemoveLinearKeys\_\_

• **\_\_tid\_AnimCompress\_RemoveLinearKeys\_\_**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[__tid_AnimCompress_RemoveLinearKeys__](ue_ue.AnimCompress_RemoveLinearKeys.md#__tid_animcompress_removelinearkeys__)

___

### \_\_tid\_AnimCompress\_\_

• **\_\_tid\_AnimCompress\_\_**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[__tid_AnimCompress__](ue_ue.AnimCompress_RemoveLinearKeys.md#__tid_animcompress__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[__tid_Object__](ue_ue.AnimCompress_RemoveLinearKeys.md#__tid_object__)

___

### bActuallyFilterLinearKeys

• **bActuallyFilterLinearKeys**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[bActuallyFilterLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md#bactuallyfilterlinearkeys)

___

### bEnableSegmenting

• **bEnableSegmenting**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[bEnableSegmenting](ue_ue.AnimCompress_RemoveLinearKeys.md#benablesegmenting)

___

### bNeedsSkeleton

• **bNeedsSkeleton**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[bNeedsSkeleton](ue_ue.AnimCompress_RemoveLinearKeys.md#bneedsskeleton)

___

### bOptimizeForForwardPlayback

• **bOptimizeForForwardPlayback**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[bOptimizeForForwardPlayback](ue_ue.AnimCompress_RemoveLinearKeys.md#boptimizeforforwardplayback)

___

### bResampleAnimation

• **bResampleAnimation**: `boolean`

___

### bRetarget

• **bRetarget**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[bRetarget](ue_ue.AnimCompress_RemoveLinearKeys.md#bretarget)

___

### bUseAdaptiveError

• **bUseAdaptiveError**: `boolean`

___

### bUseAdaptiveError2

• **bUseAdaptiveError2**: `boolean`

___

### bUseDecompression

• **bUseDecompression**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[bUseDecompression](ue_ue.AnimCompress_RemoveLinearKeys.md#busedecompression)

___

### bUseMultithreading

• **bUseMultithreading**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[bUseMultithreading](ue_ue.AnimCompress_RemoveLinearKeys.md#busemultithreading)

___

### bUseOverrideForEndEffectors

• **bUseOverrideForEndEffectors**: `boolean`

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

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[CreateDefaultSubobject](ue_ue.AnimCompress_RemoveLinearKeys.md#createdefaultsubobject)

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

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[ExecuteUbergraph](ue_ue.AnimCompress_RemoveLinearKeys.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[GetClass](ue_ue.AnimCompress_RemoveLinearKeys.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[GetName](ue_ue.AnimCompress_RemoveLinearKeys.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[GetOuter](ue_ue.AnimCompress_RemoveLinearKeys.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[GetWorld](ue_ue.AnimCompress_RemoveLinearKeys.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimCompress_PerTrackCompression`](ue_ue.AnimCompress_PerTrackCompression.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimCompress_PerTrackCompression`](ue_ue.AnimCompress_PerTrackCompression.md)

#### Overrides

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[Find](ue_ue.AnimCompress_RemoveLinearKeys.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimCompress_PerTrackCompression`](ue_ue.AnimCompress_PerTrackCompression.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimCompress_PerTrackCompression`](ue_ue.AnimCompress_PerTrackCompression.md)

#### Overrides

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[Load](ue_ue.AnimCompress_RemoveLinearKeys.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[StaticClass](ue_ue.AnimCompress_RemoveLinearKeys.md#staticclass)
