[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EnvQueryTest\_PathfindingBatch

# Class: EnvQueryTest\_PathfindingBatch

[ue/ue](../modules/ue_ue.md).EnvQueryTest_PathfindingBatch

## Hierarchy

- [`EnvQueryTest_Pathfinding`](ue_ue.EnvQueryTest_Pathfinding.md)

  ↳ **`EnvQueryTest_PathfindingBatch`**

## Table of contents

### Constructors

- [constructor](ue_ue.EnvQueryTest_PathfindingBatch.md#constructor)

### Properties

- [BoolValue](ue_ue.EnvQueryTest_PathfindingBatch.md#boolvalue)
- [ClampMaxType](ue_ue.EnvQueryTest_PathfindingBatch.md#clampmaxtype)
- [ClampMinType](ue_ue.EnvQueryTest_PathfindingBatch.md#clampmintype)
- [Context](ue_ue.EnvQueryTest_PathfindingBatch.md#context)
- [FilterClass](ue_ue.EnvQueryTest_PathfindingBatch.md#filterclass)
- [FilterType](ue_ue.EnvQueryTest_PathfindingBatch.md#filtertype)
- [FloatValueMax](ue_ue.EnvQueryTest_PathfindingBatch.md#floatvaluemax)
- [FloatValueMin](ue_ue.EnvQueryTest_PathfindingBatch.md#floatvaluemin)
- [MultipleContextFilterOp](ue_ue.EnvQueryTest_PathfindingBatch.md#multiplecontextfilterop)
- [MultipleContextScoreOp](ue_ue.EnvQueryTest_PathfindingBatch.md#multiplecontextscoreop)
- [NormalizationType](ue_ue.EnvQueryTest_PathfindingBatch.md#normalizationtype)
- [PathFromContext](ue_ue.EnvQueryTest_PathfindingBatch.md#pathfromcontext)
- [ReferenceValue](ue_ue.EnvQueryTest_PathfindingBatch.md#referencevalue)
- [ScanRangeMultiplier](ue_ue.EnvQueryTest_PathfindingBatch.md#scanrangemultiplier)
- [ScoreClampMax](ue_ue.EnvQueryTest_PathfindingBatch.md#scoreclampmax)
- [ScoreClampMin](ue_ue.EnvQueryTest_PathfindingBatch.md#scoreclampmin)
- [ScoringEquation](ue_ue.EnvQueryTest_PathfindingBatch.md#scoringequation)
- [ScoringFactor](ue_ue.EnvQueryTest_PathfindingBatch.md#scoringfactor)
- [SkipUnreachable](ue_ue.EnvQueryTest_PathfindingBatch.md#skipunreachable)
- [TestComment](ue_ue.EnvQueryTest_PathfindingBatch.md#testcomment)
- [TestMode](ue_ue.EnvQueryTest_PathfindingBatch.md#testmode)
- [TestOrder](ue_ue.EnvQueryTest_PathfindingBatch.md#testorder)
- [TestPurpose](ue_ue.EnvQueryTest_PathfindingBatch.md#testpurpose)
- [VerNum](ue_ue.EnvQueryTest_PathfindingBatch.md#vernum)
- [\_\_tid\_EnvQueryNode\_\_](ue_ue.EnvQueryTest_PathfindingBatch.md#__tid_envquerynode__)
- [\_\_tid\_EnvQueryTest\_PathfindingBatch\_\_](ue_ue.EnvQueryTest_PathfindingBatch.md#__tid_envquerytest_pathfindingbatch__)
- [\_\_tid\_EnvQueryTest\_Pathfinding\_\_](ue_ue.EnvQueryTest_PathfindingBatch.md#__tid_envquerytest_pathfinding__)
- [\_\_tid\_EnvQueryTest\_\_](ue_ue.EnvQueryTest_PathfindingBatch.md#__tid_envquerytest__)
- [\_\_tid\_Object\_\_](ue_ue.EnvQueryTest_PathfindingBatch.md#__tid_object__)
- [bDefineReferenceValue](ue_ue.EnvQueryTest_PathfindingBatch.md#bdefinereferencevalue)
- [bWorkOnFloatValues](ue_ue.EnvQueryTest_PathfindingBatch.md#bworkonfloatvalues)

### Methods

- [CreateDefaultSubobject](ue_ue.EnvQueryTest_PathfindingBatch.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EnvQueryTest_PathfindingBatch.md#executeubergraph)
- [GetClass](ue_ue.EnvQueryTest_PathfindingBatch.md#getclass)
- [GetName](ue_ue.EnvQueryTest_PathfindingBatch.md#getname)
- [GetOuter](ue_ue.EnvQueryTest_PathfindingBatch.md#getouter)
- [GetWorld](ue_ue.EnvQueryTest_PathfindingBatch.md#getworld)
- [Find](ue_ue.EnvQueryTest_PathfindingBatch.md#find)
- [Load](ue_ue.EnvQueryTest_PathfindingBatch.md#load)
- [StaticClass](ue_ue.EnvQueryTest_PathfindingBatch.md#staticclass)

## Constructors

### constructor

• **new EnvQueryTest_PathfindingBatch**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[constructor](ue_ue.EnvQueryTest_Pathfinding.md#constructor)

## Properties

### BoolValue

• **BoolValue**: [`AIDataProviderBoolValue`](ue_ue.AIDataProviderBoolValue.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[BoolValue](ue_ue.EnvQueryTest_Pathfinding.md#boolvalue)

___

### ClampMaxType

• **ClampMaxType**: [`EEnvQueryTestClamping`](../enums/ue_ue.EEnvQueryTestClamping.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[ClampMaxType](ue_ue.EnvQueryTest_Pathfinding.md#clampmaxtype)

___

### ClampMinType

• **ClampMinType**: [`EEnvQueryTestClamping`](../enums/ue_ue.EEnvQueryTestClamping.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[ClampMinType](ue_ue.EnvQueryTest_Pathfinding.md#clampmintype)

___

### Context

• **Context**: [`Class`](ue_ue.Class.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[Context](ue_ue.EnvQueryTest_Pathfinding.md#context)

___

### FilterClass

• **FilterClass**: [`Class`](ue_ue.Class.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[FilterClass](ue_ue.EnvQueryTest_Pathfinding.md#filterclass)

___

### FilterType

• **FilterType**: [`EEnvTestFilterType`](../enums/ue_ue.EEnvTestFilterType.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[FilterType](ue_ue.EnvQueryTest_Pathfinding.md#filtertype)

___

### FloatValueMax

• **FloatValueMax**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[FloatValueMax](ue_ue.EnvQueryTest_Pathfinding.md#floatvaluemax)

___

### FloatValueMin

• **FloatValueMin**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[FloatValueMin](ue_ue.EnvQueryTest_Pathfinding.md#floatvaluemin)

___

### MultipleContextFilterOp

• **MultipleContextFilterOp**: [`EEnvTestFilterOperator`](../enums/ue_ue.EEnvTestFilterOperator.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[MultipleContextFilterOp](ue_ue.EnvQueryTest_Pathfinding.md#multiplecontextfilterop)

___

### MultipleContextScoreOp

• **MultipleContextScoreOp**: [`EEnvTestScoreOperator`](../enums/ue_ue.EEnvTestScoreOperator.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[MultipleContextScoreOp](ue_ue.EnvQueryTest_Pathfinding.md#multiplecontextscoreop)

___

### NormalizationType

• **NormalizationType**: [`EEQSNormalizationType`](../enums/ue_ue.EEQSNormalizationType.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[NormalizationType](ue_ue.EnvQueryTest_Pathfinding.md#normalizationtype)

___

### PathFromContext

• **PathFromContext**: [`AIDataProviderBoolValue`](ue_ue.AIDataProviderBoolValue.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[PathFromContext](ue_ue.EnvQueryTest_Pathfinding.md#pathfromcontext)

___

### ReferenceValue

• **ReferenceValue**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[ReferenceValue](ue_ue.EnvQueryTest_Pathfinding.md#referencevalue)

___

### ScanRangeMultiplier

• **ScanRangeMultiplier**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

___

### ScoreClampMax

• **ScoreClampMax**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[ScoreClampMax](ue_ue.EnvQueryTest_Pathfinding.md#scoreclampmax)

___

### ScoreClampMin

• **ScoreClampMin**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[ScoreClampMin](ue_ue.EnvQueryTest_Pathfinding.md#scoreclampmin)

___

### ScoringEquation

• **ScoringEquation**: [`EEnvTestScoreEquation`](../enums/ue_ue.EEnvTestScoreEquation.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[ScoringEquation](ue_ue.EnvQueryTest_Pathfinding.md#scoringequation)

___

### ScoringFactor

• **ScoringFactor**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[ScoringFactor](ue_ue.EnvQueryTest_Pathfinding.md#scoringfactor)

___

### SkipUnreachable

• **SkipUnreachable**: [`AIDataProviderBoolValue`](ue_ue.AIDataProviderBoolValue.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[SkipUnreachable](ue_ue.EnvQueryTest_Pathfinding.md#skipunreachable)

___

### TestComment

• **TestComment**: `string`

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[TestComment](ue_ue.EnvQueryTest_Pathfinding.md#testcomment)

___

### TestMode

• **TestMode**: [`EEnvTestPathfinding`](../enums/ue_ue.EEnvTestPathfinding.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[TestMode](ue_ue.EnvQueryTest_Pathfinding.md#testmode)

___

### TestOrder

• **TestOrder**: `number`

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[TestOrder](ue_ue.EnvQueryTest_Pathfinding.md#testorder)

___

### TestPurpose

• **TestPurpose**: [`EEnvTestPurpose`](../enums/ue_ue.EEnvTestPurpose.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[TestPurpose](ue_ue.EnvQueryTest_Pathfinding.md#testpurpose)

___

### VerNum

• **VerNum**: `number`

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[VerNum](ue_ue.EnvQueryTest_Pathfinding.md#vernum)

___

### \_\_tid\_EnvQueryNode\_\_

• **\_\_tid\_EnvQueryNode\_\_**: `boolean`

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[__tid_EnvQueryNode__](ue_ue.EnvQueryTest_Pathfinding.md#__tid_envquerynode__)

___

### \_\_tid\_EnvQueryTest\_PathfindingBatch\_\_

• **\_\_tid\_EnvQueryTest\_PathfindingBatch\_\_**: `boolean`

___

### \_\_tid\_EnvQueryTest\_Pathfinding\_\_

• **\_\_tid\_EnvQueryTest\_Pathfinding\_\_**: `boolean`

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[__tid_EnvQueryTest_Pathfinding__](ue_ue.EnvQueryTest_Pathfinding.md#__tid_envquerytest_pathfinding__)

___

### \_\_tid\_EnvQueryTest\_\_

• **\_\_tid\_EnvQueryTest\_\_**: `boolean`

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[__tid_EnvQueryTest__](ue_ue.EnvQueryTest_Pathfinding.md#__tid_envquerytest__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[__tid_Object__](ue_ue.EnvQueryTest_Pathfinding.md#__tid_object__)

___

### bDefineReferenceValue

• **bDefineReferenceValue**: `boolean`

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[bDefineReferenceValue](ue_ue.EnvQueryTest_Pathfinding.md#bdefinereferencevalue)

___

### bWorkOnFloatValues

• **bWorkOnFloatValues**: `boolean`

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[bWorkOnFloatValues](ue_ue.EnvQueryTest_Pathfinding.md#bworkonfloatvalues)

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

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[CreateDefaultSubobject](ue_ue.EnvQueryTest_Pathfinding.md#createdefaultsubobject)

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

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[ExecuteUbergraph](ue_ue.EnvQueryTest_Pathfinding.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[GetClass](ue_ue.EnvQueryTest_Pathfinding.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[GetName](ue_ue.EnvQueryTest_Pathfinding.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[GetOuter](ue_ue.EnvQueryTest_Pathfinding.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[GetWorld](ue_ue.EnvQueryTest_Pathfinding.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EnvQueryTest_PathfindingBatch`](ue_ue.EnvQueryTest_PathfindingBatch.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EnvQueryTest_PathfindingBatch`](ue_ue.EnvQueryTest_PathfindingBatch.md)

#### Overrides

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[Find](ue_ue.EnvQueryTest_Pathfinding.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EnvQueryTest_PathfindingBatch`](ue_ue.EnvQueryTest_PathfindingBatch.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EnvQueryTest_PathfindingBatch`](ue_ue.EnvQueryTest_PathfindingBatch.md)

#### Overrides

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[Load](ue_ue.EnvQueryTest_Pathfinding.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EnvQueryTest_Pathfinding](ue_ue.EnvQueryTest_Pathfinding.md).[StaticClass](ue_ue.EnvQueryTest_Pathfinding.md#staticclass)
