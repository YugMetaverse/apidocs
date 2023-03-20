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

## Properties

### Description

• **Description**: `string`

___

### IdealNumFramesPerSegment

• **IdealNumFramesPerSegment**: `number`

___

### MaxCurveError

• **MaxCurveError**: `number`

___

### MaxNumFramesPerSegment

• **MaxNumFramesPerSegment**: `number`

___

### RotationCompressionFormat

• **RotationCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

___

### ScaleCompressionFormat

• **ScaleCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

___

### TranslationCompressionFormat

• **TranslationCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

___

### \_\_tid\_AnimCompress\_\_

• **\_\_tid\_AnimCompress\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bEnableSegmenting

• **bEnableSegmenting**: `boolean`

___

### bNeedsSkeleton

• **bNeedsSkeleton**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
