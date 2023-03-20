[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimationSettings

# Class: AnimationSettings

[ue/ue](../modules/ue_ue.md).AnimationSettings

## Hierarchy

- [`DeveloperSettings`](ue_ue.DeveloperSettings.md)

  ↳ **`AnimationSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimationSettings.md#constructor)

### Properties

- [AlternativeCompressionThreshold](ue_ue.AnimationSettings.md#alternativecompressionthreshold)
- [CompressCommandletVersion](ue_ue.AnimationSettings.md#compresscommandletversion)
- [DefaultCompressionAlgorithm](ue_ue.AnimationSettings.md#defaultcompressionalgorithm)
- [ForceRecompression](ue_ue.AnimationSettings.md#forcerecompression)
- [KeyEndEffectorsMatchNameArray](ue_ue.AnimationSettings.md#keyendeffectorsmatchnamearray)
- [MaxCurveError](ue_ue.AnimationSettings.md#maxcurveerror)
- [RotationCompressionFormat](ue_ue.AnimationSettings.md#rotationcompressionformat)
- [TranslationCompressionFormat](ue_ue.AnimationSettings.md#translationcompressionformat)
- [\_\_tid\_AnimationSettings\_\_](ue_ue.AnimationSettings.md#__tid_animationsettings__)
- [\_\_tid\_DeveloperSettings\_\_](ue_ue.AnimationSettings.md#__tid_developersettings__)
- [\_\_tid\_Object\_\_](ue_ue.AnimationSettings.md#__tid_object__)
- [bEnablePerformanceLog](ue_ue.AnimationSettings.md#benableperformancelog)
- [bEnableSegmenting](ue_ue.AnimationSettings.md#benablesegmenting)
- [bFirstRecompressUsingCurrentOrDefault](ue_ue.AnimationSettings.md#bfirstrecompressusingcurrentordefault)
- [bForceBelowThreshold](ue_ue.AnimationSettings.md#bforcebelowthreshold)
- [bOnlyCheckForMissingSkeletalMeshes](ue_ue.AnimationSettings.md#bonlycheckformissingskeletalmeshes)
- [bRaiseMaxErrorToExisting](ue_ue.AnimationSettings.md#braisemaxerrortoexisting)
- [bStripAnimationDataOnDedicatedServer](ue_ue.AnimationSettings.md#bstripanimationdataondedicatedserver)
- [bTickAnimationOnSkeletalMeshInit](ue_ue.AnimationSettings.md#btickanimationonskeletalmeshinit)
- [bTryExhaustiveSearch](ue_ue.AnimationSettings.md#btryexhaustivesearch)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimationSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimationSettings.md#executeubergraph)
- [GetClass](ue_ue.AnimationSettings.md#getclass)
- [GetName](ue_ue.AnimationSettings.md#getname)
- [GetOuter](ue_ue.AnimationSettings.md#getouter)
- [GetWorld](ue_ue.AnimationSettings.md#getworld)
- [Find](ue_ue.AnimationSettings.md#find)
- [Load](ue_ue.AnimationSettings.md#load)
- [StaticClass](ue_ue.AnimationSettings.md#staticclass)

## Constructors

### constructor

• **new AnimationSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[constructor](ue_ue.DeveloperSettings.md#constructor)

## Properties

### AlternativeCompressionThreshold

• **AlternativeCompressionThreshold**: `number`

___

### CompressCommandletVersion

• **CompressCommandletVersion**: `number`

___

### DefaultCompressionAlgorithm

• **DefaultCompressionAlgorithm**: [`Class`](ue_ue.Class.md)

___

### ForceRecompression

• **ForceRecompression**: `boolean`

___

### KeyEndEffectorsMatchNameArray

• **KeyEndEffectorsMatchNameArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### MaxCurveError

• **MaxCurveError**: `number`

___

### RotationCompressionFormat

• **RotationCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

___

### TranslationCompressionFormat

• **TranslationCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

___

### \_\_tid\_AnimationSettings\_\_

• **\_\_tid\_AnimationSettings\_\_**: `boolean`

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

___

### bEnablePerformanceLog

• **bEnablePerformanceLog**: `boolean`

___

### bEnableSegmenting

• **bEnableSegmenting**: `boolean`

___

### bFirstRecompressUsingCurrentOrDefault

• **bFirstRecompressUsingCurrentOrDefault**: `boolean`

___

### bForceBelowThreshold

• **bForceBelowThreshold**: `boolean`

___

### bOnlyCheckForMissingSkeletalMeshes

• **bOnlyCheckForMissingSkeletalMeshes**: `boolean`

___

### bRaiseMaxErrorToExisting

• **bRaiseMaxErrorToExisting**: `boolean`

___

### bStripAnimationDataOnDedicatedServer

• **bStripAnimationDataOnDedicatedServer**: `boolean`

___

### bTickAnimationOnSkeletalMeshInit

• **bTickAnimationOnSkeletalMeshInit**: `boolean`

___

### bTryExhaustiveSearch

• **bTryExhaustiveSearch**: `boolean`

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[CreateDefaultSubobject](ue_ue.DeveloperSettings.md#createdefaultsubobject)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimationSettings`](ue_ue.AnimationSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimationSettings`](ue_ue.AnimationSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Find](ue_ue.DeveloperSettings.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimationSettings`](ue_ue.AnimationSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimationSettings`](ue_ue.AnimationSettings.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[Load](ue_ue.DeveloperSettings.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)
