[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimCompress

# Class: AnimCompress

[ue/ue](../modules/ue_ue.md).AnimCompress

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AnimCompress`**

  ↳↳ [`AnimCompress_Automatic`](ue_ue.AnimCompress_Automatic.md)

  ↳↳ [`AnimCompress_BitwiseCompressOnly`](ue_ue.AnimCompress_BitwiseCompressOnly.md)

  ↳↳ [`AnimCompress_LeastDestructive`](ue_ue.AnimCompress_LeastDestructive.md)

  ↳↳ [`AnimCompress_RemoveLinearKeys`](ue_ue.AnimCompress_RemoveLinearKeys.md)

  ↳↳ [`AnimCompress_RemoveEverySecondKey`](ue_ue.AnimCompress_RemoveEverySecondKey.md)

  ↳↳ [`AnimCompress_RemoveTrivialKeys`](ue_ue.AnimCompress_RemoveTrivialKeys.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimCompress.md#constructor)

### Properties

- [Description](ue_ue.AnimCompress.md#description)
- [IdealNumFramesPerSegment](ue_ue.AnimCompress.md#idealnumframespersegment)
- [MaxCurveError](ue_ue.AnimCompress.md#maxcurveerror)
- [MaxNumFramesPerSegment](ue_ue.AnimCompress.md#maxnumframespersegment)
- [RotationCompressionFormat](ue_ue.AnimCompress.md#rotationcompressionformat)
- [ScaleCompressionFormat](ue_ue.AnimCompress.md#scalecompressionformat)
- [TranslationCompressionFormat](ue_ue.AnimCompress.md#translationcompressionformat)
- [\_\_tid\_AnimCompress\_\_](ue_ue.AnimCompress.md#__tid_animcompress__)
- [\_\_tid\_Object\_\_](ue_ue.AnimCompress.md#__tid_object__)
- [bEnableSegmenting](ue_ue.AnimCompress.md#benablesegmenting)
- [bNeedsSkeleton](ue_ue.AnimCompress.md#bneedsskeleton)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimCompress.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimCompress.md#executeubergraph)
- [GetClass](ue_ue.AnimCompress.md#getclass)
- [GetName](ue_ue.AnimCompress.md#getname)
- [GetOuter](ue_ue.AnimCompress.md#getouter)
- [GetWorld](ue_ue.AnimCompress.md#getworld)
- [Find](ue_ue.AnimCompress.md#find)
- [Load](ue_ue.AnimCompress.md#load)
- [StaticClass](ue_ue.AnimCompress.md#staticclass)

## Constructors

### constructor

• **new AnimCompress**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:3157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3157)

## Properties

### Description

• **Description**: `string`

#### Defined in

[ue/ue.d.ts:3158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3158)

___

### IdealNumFramesPerSegment

• **IdealNumFramesPerSegment**: `number`

#### Defined in

[ue/ue.d.ts:3161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3161)

___

### MaxCurveError

• **MaxCurveError**: `number`

#### Defined in

[ue/ue.d.ts:3166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3166)

___

### MaxNumFramesPerSegment

• **MaxNumFramesPerSegment**: `number`

#### Defined in

[ue/ue.d.ts:3162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3162)

___

### RotationCompressionFormat

• **RotationCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

#### Defined in

[ue/ue.d.ts:3164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3164)

___

### ScaleCompressionFormat

• **ScaleCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

#### Defined in

[ue/ue.d.ts:3165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3165)

___

### TranslationCompressionFormat

• **TranslationCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

#### Defined in

[ue/ue.d.ts:3163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3163)

___

### \_\_tid\_AnimCompress\_\_

• **\_\_tid\_AnimCompress\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3171)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bEnableSegmenting

• **bEnableSegmenting**: `boolean`

#### Defined in

[ue/ue.d.ts:3160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3160)

___

### bNeedsSkeleton

• **bNeedsSkeleton**: `boolean`

#### Defined in

[ue/ue.d.ts:3159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3159)

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimCompress`](ue_ue.AnimCompress.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimCompress`](ue_ue.AnimCompress.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:3168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3168)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimCompress`](ue_ue.AnimCompress.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimCompress`](ue_ue.AnimCompress.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:3169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3169)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:3167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L3167)
