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

#### Defined in

[ue/ue.d.ts:17428](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17428)

## Properties

### AllowedRotationFormats

• **AllowedRotationFormats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)\>

#### Defined in

[ue/ue.d.ts:17433](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17433)

___

### AllowedScaleFormats

• **AllowedScaleFormats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)\>

#### Defined in

[ue/ue.d.ts:17435](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17435)

___

### AllowedTranslationFormats

• **AllowedTranslationFormats**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)\>

#### Defined in

[ue/ue.d.ts:17434](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17434)

___

### Description

• **Description**: `string`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[Description](ue_ue.AnimCompress_RemoveLinearKeys.md#description)

#### Defined in

[ue/ue.d.ts:3158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3158)

___

### EffectorDiffSocket

• **EffectorDiffSocket**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[EffectorDiffSocket](ue_ue.AnimCompress_RemoveLinearKeys.md#effectordiffsocket)

#### Defined in

[ue/ue.d.ts:17413](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17413)

___

### IdealNumFramesPerSegment

• **IdealNumFramesPerSegment**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[IdealNumFramesPerSegment](ue_ue.AnimCompress_RemoveLinearKeys.md#idealnumframespersegment)

#### Defined in

[ue/ue.d.ts:3161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3161)

___

### MaxAngleDiff

• **MaxAngleDiff**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[MaxAngleDiff](ue_ue.AnimCompress_RemoveLinearKeys.md#maxanglediff)

#### Defined in

[ue/ue.d.ts:17409](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17409)

___

### MaxAngleDiffBitwise

• **MaxAngleDiffBitwise**: `number`

#### Defined in

[ue/ue.d.ts:17431](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17431)

___

### MaxCurveError

• **MaxCurveError**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[MaxCurveError](ue_ue.AnimCompress_RemoveLinearKeys.md#maxcurveerror)

#### Defined in

[ue/ue.d.ts:3166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3166)

___

### MaxEffectorDiff

• **MaxEffectorDiff**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[MaxEffectorDiff](ue_ue.AnimCompress_RemoveLinearKeys.md#maxeffectordiff)

#### Defined in

[ue/ue.d.ts:17411](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17411)

___

### MaxErrorPerTrackRatio

• **MaxErrorPerTrackRatio**: `number`

#### Defined in

[ue/ue.d.ts:17448](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17448)

___

### MaxNumFramesPerSegment

• **MaxNumFramesPerSegment**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[MaxNumFramesPerSegment](ue_ue.AnimCompress_RemoveLinearKeys.md#maxnumframespersegment)

#### Defined in

[ue/ue.d.ts:3162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3162)

___

### MaxPosDiff

• **MaxPosDiff**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[MaxPosDiff](ue_ue.AnimCompress_RemoveLinearKeys.md#maxposdiff)

#### Defined in

[ue/ue.d.ts:17408](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17408)

___

### MaxPosDiffBitwise

• **MaxPosDiffBitwise**: `number`

#### Defined in

[ue/ue.d.ts:17430](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17430)

___

### MaxScaleDiff

• **MaxScaleDiff**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[MaxScaleDiff](ue_ue.AnimCompress_RemoveLinearKeys.md#maxscalediff)

#### Defined in

[ue/ue.d.ts:17410](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17410)

___

### MaxScaleDiffBitwise

• **MaxScaleDiffBitwise**: `number`

#### Defined in

[ue/ue.d.ts:17432](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17432)

___

### MaxZeroingThreshold

• **MaxZeroingThreshold**: `number`

#### Defined in

[ue/ue.d.ts:17429](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17429)

___

### MinEffectorDiff

• **MinEffectorDiff**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[MinEffectorDiff](ue_ue.AnimCompress_RemoveLinearKeys.md#mineffectordiff)

#### Defined in

[ue/ue.d.ts:17412](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17412)

___

### MinKeysForResampling

• **MinKeysForResampling**: `number`

#### Defined in

[ue/ue.d.ts:17438](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17438)

___

### ParentKeyScale

• **ParentKeyScale**: `number`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[ParentKeyScale](ue_ue.AnimCompress_RemoveLinearKeys.md#parentkeyscale)

#### Defined in

[ue/ue.d.ts:17414](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17414)

___

### ParentingDivisor

• **ParentingDivisor**: `number`

#### Defined in

[ue/ue.d.ts:17442](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17442)

___

### ParentingDivisorExponent

• **ParentingDivisorExponent**: `number`

#### Defined in

[ue/ue.d.ts:17443](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17443)

___

### PerturbationProbeSize

• **PerturbationProbeSize**: `number`

#### Defined in

[ue/ue.d.ts:17449](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17449)

___

### ResampledFramerate

• **ResampledFramerate**: `number`

#### Defined in

[ue/ue.d.ts:17437](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17437)

___

### RotationCompressionFormat

• **RotationCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[RotationCompressionFormat](ue_ue.AnimCompress_RemoveLinearKeys.md#rotationcompressionformat)

#### Defined in

[ue/ue.d.ts:3164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3164)

___

### RotationErrorSourceRatio

• **RotationErrorSourceRatio**: `number`

#### Defined in

[ue/ue.d.ts:17445](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17445)

___

### ScaleCompressionFormat

• **ScaleCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[ScaleCompressionFormat](ue_ue.AnimCompress_RemoveLinearKeys.md#scalecompressionformat)

#### Defined in

[ue/ue.d.ts:3165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3165)

___

### ScaleErrorSourceRatio

• **ScaleErrorSourceRatio**: `number`

#### Defined in

[ue/ue.d.ts:17447](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17447)

___

### TrackHeightBias

• **TrackHeightBias**: `number`

#### Defined in

[ue/ue.d.ts:17441](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17441)

___

### TranslationCompressionFormat

• **TranslationCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[TranslationCompressionFormat](ue_ue.AnimCompress_RemoveLinearKeys.md#translationcompressionformat)

#### Defined in

[ue/ue.d.ts:3163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3163)

___

### TranslationErrorSourceRatio

• **TranslationErrorSourceRatio**: `number`

#### Defined in

[ue/ue.d.ts:17446](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17446)

___

### \_\_tid\_AnimCompress\_PerTrackCompression\_\_

• **\_\_tid\_AnimCompress\_PerTrackCompression\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:17454](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17454)

___

### \_\_tid\_AnimCompress\_RemoveLinearKeys\_\_

• **\_\_tid\_AnimCompress\_RemoveLinearKeys\_\_**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[__tid_AnimCompress_RemoveLinearKeys__](ue_ue.AnimCompress_RemoveLinearKeys.md#__tid_animcompress_removelinearkeys__)

#### Defined in

[ue/ue.d.ts:17424](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17424)

___

### \_\_tid\_AnimCompress\_\_

• **\_\_tid\_AnimCompress\_\_**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[__tid_AnimCompress__](ue_ue.AnimCompress_RemoveLinearKeys.md#__tid_animcompress__)

#### Defined in

[ue/ue.d.ts:3171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3171)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[__tid_Object__](ue_ue.AnimCompress_RemoveLinearKeys.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bActuallyFilterLinearKeys

• **bActuallyFilterLinearKeys**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[bActuallyFilterLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md#bactuallyfilterlinearkeys)

#### Defined in

[ue/ue.d.ts:17416](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17416)

___

### bEnableSegmenting

• **bEnableSegmenting**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[bEnableSegmenting](ue_ue.AnimCompress_RemoveLinearKeys.md#benablesegmenting)

#### Defined in

[ue/ue.d.ts:3160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3160)

___

### bNeedsSkeleton

• **bNeedsSkeleton**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[bNeedsSkeleton](ue_ue.AnimCompress_RemoveLinearKeys.md#bneedsskeleton)

#### Defined in

[ue/ue.d.ts:3159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3159)

___

### bOptimizeForForwardPlayback

• **bOptimizeForForwardPlayback**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[bOptimizeForForwardPlayback](ue_ue.AnimCompress_RemoveLinearKeys.md#boptimizeforforwardplayback)

#### Defined in

[ue/ue.d.ts:17417](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17417)

___

### bResampleAnimation

• **bResampleAnimation**: `boolean`

#### Defined in

[ue/ue.d.ts:17436](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17436)

___

### bRetarget

• **bRetarget**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[bRetarget](ue_ue.AnimCompress_RemoveLinearKeys.md#bretarget)

#### Defined in

[ue/ue.d.ts:17415](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17415)

___

### bUseAdaptiveError

• **bUseAdaptiveError**: `boolean`

#### Defined in

[ue/ue.d.ts:17439](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17439)

___

### bUseAdaptiveError2

• **bUseAdaptiveError2**: `boolean`

#### Defined in

[ue/ue.d.ts:17444](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17444)

___

### bUseDecompression

• **bUseDecompression**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[bUseDecompression](ue_ue.AnimCompress_RemoveLinearKeys.md#busedecompression)

#### Defined in

[ue/ue.d.ts:17418](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17418)

___

### bUseMultithreading

• **bUseMultithreading**: `boolean`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[bUseMultithreading](ue_ue.AnimCompress_RemoveLinearKeys.md#busemultithreading)

#### Defined in

[ue/ue.d.ts:17419](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17419)

___

### bUseOverrideForEndEffectors

• **bUseOverrideForEndEffectors**: `boolean`

#### Defined in

[ue/ue.d.ts:17440](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17440)

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

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[ExecuteUbergraph](ue_ue.AnimCompress_RemoveLinearKeys.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[GetClass](ue_ue.AnimCompress_RemoveLinearKeys.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[GetName](ue_ue.AnimCompress_RemoveLinearKeys.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[GetOuter](ue_ue.AnimCompress_RemoveLinearKeys.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[GetWorld](ue_ue.AnimCompress_RemoveLinearKeys.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:17451](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17451)

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

#### Defined in

[ue/ue.d.ts:17452](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17452)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimCompress_RemoveLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md).[StaticClass](ue_ue.AnimCompress_RemoveLinearKeys.md#staticclass)

#### Defined in

[ue/ue.d.ts:17450](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L17450)
