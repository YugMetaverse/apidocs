[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimCompress\_RemoveLinearKeys

# Class: AnimCompress\_RemoveLinearKeys

[ue/ue](../modules/ue_ue.md).AnimCompress_RemoveLinearKeys

## Hierarchy

- [`AnimCompress`](ue_ue.AnimCompress.md)

  ↳ **`AnimCompress_RemoveLinearKeys`**

  ↳↳ [`AnimCompress_PerTrackCompression`](ue_ue.AnimCompress_PerTrackCompression.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimCompress_RemoveLinearKeys.md#constructor)

### Properties

- [Description](ue_ue.AnimCompress_RemoveLinearKeys.md#description)
- [EffectorDiffSocket](ue_ue.AnimCompress_RemoveLinearKeys.md#effectordiffsocket)
- [IdealNumFramesPerSegment](ue_ue.AnimCompress_RemoveLinearKeys.md#idealnumframespersegment)
- [MaxAngleDiff](ue_ue.AnimCompress_RemoveLinearKeys.md#maxanglediff)
- [MaxCurveError](ue_ue.AnimCompress_RemoveLinearKeys.md#maxcurveerror)
- [MaxEffectorDiff](ue_ue.AnimCompress_RemoveLinearKeys.md#maxeffectordiff)
- [MaxNumFramesPerSegment](ue_ue.AnimCompress_RemoveLinearKeys.md#maxnumframespersegment)
- [MaxPosDiff](ue_ue.AnimCompress_RemoveLinearKeys.md#maxposdiff)
- [MaxScaleDiff](ue_ue.AnimCompress_RemoveLinearKeys.md#maxscalediff)
- [MinEffectorDiff](ue_ue.AnimCompress_RemoveLinearKeys.md#mineffectordiff)
- [ParentKeyScale](ue_ue.AnimCompress_RemoveLinearKeys.md#parentkeyscale)
- [RotationCompressionFormat](ue_ue.AnimCompress_RemoveLinearKeys.md#rotationcompressionformat)
- [ScaleCompressionFormat](ue_ue.AnimCompress_RemoveLinearKeys.md#scalecompressionformat)
- [TranslationCompressionFormat](ue_ue.AnimCompress_RemoveLinearKeys.md#translationcompressionformat)
- [\_\_tid\_AnimCompress\_RemoveLinearKeys\_\_](ue_ue.AnimCompress_RemoveLinearKeys.md#__tid_animcompress_removelinearkeys__)
- [\_\_tid\_AnimCompress\_\_](ue_ue.AnimCompress_RemoveLinearKeys.md#__tid_animcompress__)
- [\_\_tid\_Object\_\_](ue_ue.AnimCompress_RemoveLinearKeys.md#__tid_object__)
- [bActuallyFilterLinearKeys](ue_ue.AnimCompress_RemoveLinearKeys.md#bactuallyfilterlinearkeys)
- [bEnableSegmenting](ue_ue.AnimCompress_RemoveLinearKeys.md#benablesegmenting)
- [bNeedsSkeleton](ue_ue.AnimCompress_RemoveLinearKeys.md#bneedsskeleton)
- [bOptimizeForForwardPlayback](ue_ue.AnimCompress_RemoveLinearKeys.md#boptimizeforforwardplayback)
- [bRetarget](ue_ue.AnimCompress_RemoveLinearKeys.md#bretarget)
- [bUseDecompression](ue_ue.AnimCompress_RemoveLinearKeys.md#busedecompression)
- [bUseMultithreading](ue_ue.AnimCompress_RemoveLinearKeys.md#busemultithreading)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimCompress_RemoveLinearKeys.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimCompress_RemoveLinearKeys.md#executeubergraph)
- [GetClass](ue_ue.AnimCompress_RemoveLinearKeys.md#getclass)
- [GetName](ue_ue.AnimCompress_RemoveLinearKeys.md#getname)
- [GetOuter](ue_ue.AnimCompress_RemoveLinearKeys.md#getouter)
- [GetWorld](ue_ue.AnimCompress_RemoveLinearKeys.md#getworld)
- [Find](ue_ue.AnimCompress_RemoveLinearKeys.md#find)
- [Load](ue_ue.AnimCompress_RemoveLinearKeys.md#load)
- [StaticClass](ue_ue.AnimCompress_RemoveLinearKeys.md#staticclass)

## Constructors

### constructor

• **new AnimCompress_RemoveLinearKeys**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimCompress](ue_ue.AnimCompress.md).[constructor](ue_ue.AnimCompress.md#constructor)

## Properties

### Description

• **Description**: `string`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[Description](ue_ue.AnimCompress.md#description)

___

### EffectorDiffSocket

• **EffectorDiffSocket**: `number`

___

### IdealNumFramesPerSegment

• **IdealNumFramesPerSegment**: `number`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[IdealNumFramesPerSegment](ue_ue.AnimCompress.md#idealnumframespersegment)

___

### MaxAngleDiff

• **MaxAngleDiff**: `number`

___

### MaxCurveError

• **MaxCurveError**: `number`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[MaxCurveError](ue_ue.AnimCompress.md#maxcurveerror)

___

### MaxEffectorDiff

• **MaxEffectorDiff**: `number`

___

### MaxNumFramesPerSegment

• **MaxNumFramesPerSegment**: `number`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[MaxNumFramesPerSegment](ue_ue.AnimCompress.md#maxnumframespersegment)

___

### MaxPosDiff

• **MaxPosDiff**: `number`

___

### MaxScaleDiff

• **MaxScaleDiff**: `number`

___

### MinEffectorDiff

• **MinEffectorDiff**: `number`

___

### ParentKeyScale

• **ParentKeyScale**: `number`

___

### RotationCompressionFormat

• **RotationCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[RotationCompressionFormat](ue_ue.AnimCompress.md#rotationcompressionformat)

___

### ScaleCompressionFormat

• **ScaleCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[ScaleCompressionFormat](ue_ue.AnimCompress.md#scalecompressionformat)

___

### TranslationCompressionFormat

• **TranslationCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[TranslationCompressionFormat](ue_ue.AnimCompress.md#translationcompressionformat)

___

### \_\_tid\_AnimCompress\_RemoveLinearKeys\_\_

• **\_\_tid\_AnimCompress\_RemoveLinearKeys\_\_**: `boolean`

___

### \_\_tid\_AnimCompress\_\_

• **\_\_tid\_AnimCompress\_\_**: `boolean`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[__tid_AnimCompress__](ue_ue.AnimCompress.md#__tid_animcompress__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[__tid_Object__](ue_ue.AnimCompress.md#__tid_object__)

___

### bActuallyFilterLinearKeys

• **bActuallyFilterLinearKeys**: `boolean`

___

### bEnableSegmenting

• **bEnableSegmenting**: `boolean`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[bEnableSegmenting](ue_ue.AnimCompress.md#benablesegmenting)

___

### bNeedsSkeleton

• **bNeedsSkeleton**: `boolean`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[bNeedsSkeleton](ue_ue.AnimCompress.md#bneedsskeleton)

___

### bOptimizeForForwardPlayback

• **bOptimizeForForwardPlayback**: `boolean`

___

### bRetarget

• **bRetarget**: `boolean`

___

### bUseDecompression

• **bUseDecompression**: `boolean`

___

### bUseMultithreading

• **bUseMultithreading**: `boolean`

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

[AnimCompress](ue_ue.AnimCompress.md).[CreateDefaultSubobject](ue_ue.AnimCompress.md#createdefaultsubobject)

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

[AnimCompress](ue_ue.AnimCompress.md).[ExecuteUbergraph](ue_ue.AnimCompress.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[GetClass](ue_ue.AnimCompress.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[GetName](ue_ue.AnimCompress.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[GetOuter](ue_ue.AnimCompress.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[GetWorld](ue_ue.AnimCompress.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimCompress_RemoveLinearKeys`](ue_ue.AnimCompress_RemoveLinearKeys.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimCompress_RemoveLinearKeys`](ue_ue.AnimCompress_RemoveLinearKeys.md)

#### Overrides

[AnimCompress](ue_ue.AnimCompress.md).[Find](ue_ue.AnimCompress.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimCompress_RemoveLinearKeys`](ue_ue.AnimCompress_RemoveLinearKeys.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimCompress_RemoveLinearKeys`](ue_ue.AnimCompress_RemoveLinearKeys.md)

#### Overrides

[AnimCompress](ue_ue.AnimCompress.md).[Load](ue_ue.AnimCompress.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimCompress](ue_ue.AnimCompress.md).[StaticClass](ue_ue.AnimCompress.md#staticclass)
