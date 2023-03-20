[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimCompress\_Automatic

# Class: AnimCompress\_Automatic

[ue/ue](../modules/ue_ue.md).AnimCompress_Automatic

## Hierarchy

- [`AnimCompress`](ue_ue.AnimCompress.md)

  ↳ **`AnimCompress_Automatic`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimCompress_Automatic.md#constructor)

### Properties

- [Description](ue_ue.AnimCompress_Automatic.md#description)
- [IdealNumFramesPerSegment](ue_ue.AnimCompress_Automatic.md#idealnumframespersegment)
- [MaxCurveError](ue_ue.AnimCompress_Automatic.md#maxcurveerror)
- [MaxEndEffectorError](ue_ue.AnimCompress_Automatic.md#maxendeffectorerror)
- [MaxNumFramesPerSegment](ue_ue.AnimCompress_Automatic.md#maxnumframespersegment)
- [RotationCompressionFormat](ue_ue.AnimCompress_Automatic.md#rotationcompressionformat)
- [ScaleCompressionFormat](ue_ue.AnimCompress_Automatic.md#scalecompressionformat)
- [TranslationCompressionFormat](ue_ue.AnimCompress_Automatic.md#translationcompressionformat)
- [\_\_tid\_AnimCompress\_Automatic\_\_](ue_ue.AnimCompress_Automatic.md#__tid_animcompress_automatic__)
- [\_\_tid\_AnimCompress\_\_](ue_ue.AnimCompress_Automatic.md#__tid_animcompress__)
- [\_\_tid\_Object\_\_](ue_ue.AnimCompress_Automatic.md#__tid_object__)
- [bAutoReplaceIfExistingErrorTooGreat](ue_ue.AnimCompress_Automatic.md#bautoreplaceifexistingerrortoogreat)
- [bEnableSegmenting](ue_ue.AnimCompress_Automatic.md#benablesegmenting)
- [bNeedsSkeleton](ue_ue.AnimCompress_Automatic.md#bneedsskeleton)
- [bRaiseMaxErrorToExisting](ue_ue.AnimCompress_Automatic.md#braisemaxerrortoexisting)
- [bRunCurrentDefaultCompressor](ue_ue.AnimCompress_Automatic.md#bruncurrentdefaultcompressor)
- [bTryExhaustiveSearch](ue_ue.AnimCompress_Automatic.md#btryexhaustivesearch)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimCompress_Automatic.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimCompress_Automatic.md#executeubergraph)
- [GetClass](ue_ue.AnimCompress_Automatic.md#getclass)
- [GetName](ue_ue.AnimCompress_Automatic.md#getname)
- [GetOuter](ue_ue.AnimCompress_Automatic.md#getouter)
- [GetWorld](ue_ue.AnimCompress_Automatic.md#getworld)
- [Find](ue_ue.AnimCompress_Automatic.md#find)
- [Load](ue_ue.AnimCompress_Automatic.md#load)
- [StaticClass](ue_ue.AnimCompress_Automatic.md#staticclass)

## Constructors

### constructor

• **new AnimCompress_Automatic**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimCompress](ue_ue.AnimCompress.md).[constructor](ue_ue.AnimCompress.md#constructor)

#### Defined in

[ue/ue.d.ts:17375](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17375)

## Properties

### Description

• **Description**: `string`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[Description](ue_ue.AnimCompress.md#description)

#### Defined in

[ue/ue.d.ts:3158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3158)

___

### IdealNumFramesPerSegment

• **IdealNumFramesPerSegment**: `number`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[IdealNumFramesPerSegment](ue_ue.AnimCompress.md#idealnumframespersegment)

#### Defined in

[ue/ue.d.ts:3161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3161)

___

### MaxCurveError

• **MaxCurveError**: `number`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[MaxCurveError](ue_ue.AnimCompress.md#maxcurveerror)

#### Defined in

[ue/ue.d.ts:3166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3166)

___

### MaxEndEffectorError

• **MaxEndEffectorError**: `number`

#### Defined in

[ue/ue.d.ts:17376](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17376)

___

### MaxNumFramesPerSegment

• **MaxNumFramesPerSegment**: `number`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[MaxNumFramesPerSegment](ue_ue.AnimCompress.md#maxnumframespersegment)

#### Defined in

[ue/ue.d.ts:3162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3162)

___

### RotationCompressionFormat

• **RotationCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[RotationCompressionFormat](ue_ue.AnimCompress.md#rotationcompressionformat)

#### Defined in

[ue/ue.d.ts:3164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3164)

___

### ScaleCompressionFormat

• **ScaleCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[ScaleCompressionFormat](ue_ue.AnimCompress.md#scalecompressionformat)

#### Defined in

[ue/ue.d.ts:3165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3165)

___

### TranslationCompressionFormat

• **TranslationCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[TranslationCompressionFormat](ue_ue.AnimCompress.md#translationcompressionformat)

#### Defined in

[ue/ue.d.ts:3163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3163)

___

### \_\_tid\_AnimCompress\_Automatic\_\_

• **\_\_tid\_AnimCompress\_Automatic\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:17385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17385)

___

### \_\_tid\_AnimCompress\_\_

• **\_\_tid\_AnimCompress\_\_**: `boolean`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[__tid_AnimCompress__](ue_ue.AnimCompress.md#__tid_animcompress__)

#### Defined in

[ue/ue.d.ts:3171](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3171)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[__tid_Object__](ue_ue.AnimCompress.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAutoReplaceIfExistingErrorTooGreat

• **bAutoReplaceIfExistingErrorTooGreat**: `boolean`

#### Defined in

[ue/ue.d.ts:17378](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17378)

___

### bEnableSegmenting

• **bEnableSegmenting**: `boolean`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[bEnableSegmenting](ue_ue.AnimCompress.md#benablesegmenting)

#### Defined in

[ue/ue.d.ts:3160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3160)

___

### bNeedsSkeleton

• **bNeedsSkeleton**: `boolean`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[bNeedsSkeleton](ue_ue.AnimCompress.md#bneedsskeleton)

#### Defined in

[ue/ue.d.ts:3159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3159)

___

### bRaiseMaxErrorToExisting

• **bRaiseMaxErrorToExisting**: `boolean`

#### Defined in

[ue/ue.d.ts:17379](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17379)

___

### bRunCurrentDefaultCompressor

• **bRunCurrentDefaultCompressor**: `boolean`

#### Defined in

[ue/ue.d.ts:17377](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17377)

___

### bTryExhaustiveSearch

• **bTryExhaustiveSearch**: `boolean`

#### Defined in

[ue/ue.d.ts:17380](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17380)

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

[AnimCompress](ue_ue.AnimCompress.md).[ExecuteUbergraph](ue_ue.AnimCompress.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[GetClass](ue_ue.AnimCompress.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[GetName](ue_ue.AnimCompress.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[GetOuter](ue_ue.AnimCompress.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimCompress](ue_ue.AnimCompress.md).[GetWorld](ue_ue.AnimCompress.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimCompress_Automatic`](ue_ue.AnimCompress_Automatic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimCompress_Automatic`](ue_ue.AnimCompress_Automatic.md)

#### Overrides

[AnimCompress](ue_ue.AnimCompress.md).[Find](ue_ue.AnimCompress.md#find)

#### Defined in

[ue/ue.d.ts:17382](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17382)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimCompress_Automatic`](ue_ue.AnimCompress_Automatic.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimCompress_Automatic`](ue_ue.AnimCompress_Automatic.md)

#### Overrides

[AnimCompress](ue_ue.AnimCompress.md).[Load](ue_ue.AnimCompress.md#load)

#### Defined in

[ue/ue.d.ts:17383](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17383)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimCompress](ue_ue.AnimCompress.md).[StaticClass](ue_ue.AnimCompress.md#staticclass)

#### Defined in

[ue/ue.d.ts:17381](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L17381)
