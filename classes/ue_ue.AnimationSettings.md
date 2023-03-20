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

#### Defined in

[ue/ue.d.ts:16954](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16954)

## Properties

### AlternativeCompressionThreshold

• **AlternativeCompressionThreshold**: `number`

#### Defined in

[ue/ue.d.ts:16961](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16961)

___

### CompressCommandletVersion

• **CompressCommandletVersion**: `number`

#### Defined in

[ue/ue.d.ts:16955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16955)

___

### DefaultCompressionAlgorithm

• **DefaultCompressionAlgorithm**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:16957](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16957)

___

### ForceRecompression

• **ForceRecompression**: `boolean`

#### Defined in

[ue/ue.d.ts:16962](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16962)

___

### KeyEndEffectorsMatchNameArray

• **KeyEndEffectorsMatchNameArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:16956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16956)

___

### MaxCurveError

• **MaxCurveError**: `number`

#### Defined in

[ue/ue.d.ts:16960](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16960)

___

### RotationCompressionFormat

• **RotationCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

#### Defined in

[ue/ue.d.ts:16958](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16958)

___

### TranslationCompressionFormat

• **TranslationCompressionFormat**: [`AnimationCompressionFormat`](../enums/ue_ue.AnimationCompressionFormat.md)

#### Defined in

[ue/ue.d.ts:16959](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16959)

___

### \_\_tid\_AnimationSettings\_\_

• **\_\_tid\_AnimationSettings\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:16976](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16976)

___

### \_\_tid\_DeveloperSettings\_\_

• **\_\_tid\_DeveloperSettings\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_DeveloperSettings__](ue_ue.DeveloperSettings.md#__tid_developersettings__)

#### Defined in

[ue/ue.d.ts:16950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16950)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[__tid_Object__](ue_ue.DeveloperSettings.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bEnablePerformanceLog

• **bEnablePerformanceLog**: `boolean`

#### Defined in

[ue/ue.d.ts:16969](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16969)

___

### bEnableSegmenting

• **bEnableSegmenting**: `boolean`

#### Defined in

[ue/ue.d.ts:16968](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16968)

___

### bFirstRecompressUsingCurrentOrDefault

• **bFirstRecompressUsingCurrentOrDefault**: `boolean`

#### Defined in

[ue/ue.d.ts:16965](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16965)

___

### bForceBelowThreshold

• **bForceBelowThreshold**: `boolean`

#### Defined in

[ue/ue.d.ts:16964](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16964)

___

### bOnlyCheckForMissingSkeletalMeshes

• **bOnlyCheckForMissingSkeletalMeshes**: `boolean`

#### Defined in

[ue/ue.d.ts:16963](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16963)

___

### bRaiseMaxErrorToExisting

• **bRaiseMaxErrorToExisting**: `boolean`

#### Defined in

[ue/ue.d.ts:16966](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16966)

___

### bStripAnimationDataOnDedicatedServer

• **bStripAnimationDataOnDedicatedServer**: `boolean`

#### Defined in

[ue/ue.d.ts:16970](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16970)

___

### bTickAnimationOnSkeletalMeshInit

• **bTickAnimationOnSkeletalMeshInit**: `boolean`

#### Defined in

[ue/ue.d.ts:16971](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16971)

___

### bTryExhaustiveSearch

• **bTryExhaustiveSearch**: `boolean`

#### Defined in

[ue/ue.d.ts:16967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16967)

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

[DeveloperSettings](ue_ue.DeveloperSettings.md).[ExecuteUbergraph](ue_ue.DeveloperSettings.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetClass](ue_ue.DeveloperSettings.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetName](ue_ue.DeveloperSettings.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetOuter](ue_ue.DeveloperSettings.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[DeveloperSettings](ue_ue.DeveloperSettings.md).[GetWorld](ue_ue.DeveloperSettings.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:16973](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16973)

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

#### Defined in

[ue/ue.d.ts:16974](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16974)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[DeveloperSettings](ue_ue.DeveloperSettings.md).[StaticClass](ue_ue.DeveloperSettings.md#staticclass)

#### Defined in

[ue/ue.d.ts:16972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16972)
