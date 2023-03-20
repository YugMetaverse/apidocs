[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EnvQueryTest\_Pathfinding

# Class: EnvQueryTest\_Pathfinding

[ue/ue](../modules/ue_ue.md).EnvQueryTest_Pathfinding

## Hierarchy

- [`EnvQueryTest`](ue_ue.EnvQueryTest.md)

  ↳ **`EnvQueryTest_Pathfinding`**

  ↳↳ [`EnvQueryTest_PathfindingBatch`](ue_ue.EnvQueryTest_PathfindingBatch.md)

## Table of contents

### Constructors

- [constructor](ue_ue.EnvQueryTest_Pathfinding.md#constructor)

### Properties

- [BoolValue](ue_ue.EnvQueryTest_Pathfinding.md#boolvalue)
- [ClampMaxType](ue_ue.EnvQueryTest_Pathfinding.md#clampmaxtype)
- [ClampMinType](ue_ue.EnvQueryTest_Pathfinding.md#clampmintype)
- [Context](ue_ue.EnvQueryTest_Pathfinding.md#context)
- [FilterClass](ue_ue.EnvQueryTest_Pathfinding.md#filterclass)
- [FilterType](ue_ue.EnvQueryTest_Pathfinding.md#filtertype)
- [FloatValueMax](ue_ue.EnvQueryTest_Pathfinding.md#floatvaluemax)
- [FloatValueMin](ue_ue.EnvQueryTest_Pathfinding.md#floatvaluemin)
- [MultipleContextFilterOp](ue_ue.EnvQueryTest_Pathfinding.md#multiplecontextfilterop)
- [MultipleContextScoreOp](ue_ue.EnvQueryTest_Pathfinding.md#multiplecontextscoreop)
- [NormalizationType](ue_ue.EnvQueryTest_Pathfinding.md#normalizationtype)
- [PathFromContext](ue_ue.EnvQueryTest_Pathfinding.md#pathfromcontext)
- [ReferenceValue](ue_ue.EnvQueryTest_Pathfinding.md#referencevalue)
- [ScoreClampMax](ue_ue.EnvQueryTest_Pathfinding.md#scoreclampmax)
- [ScoreClampMin](ue_ue.EnvQueryTest_Pathfinding.md#scoreclampmin)
- [ScoringEquation](ue_ue.EnvQueryTest_Pathfinding.md#scoringequation)
- [ScoringFactor](ue_ue.EnvQueryTest_Pathfinding.md#scoringfactor)
- [SkipUnreachable](ue_ue.EnvQueryTest_Pathfinding.md#skipunreachable)
- [TestComment](ue_ue.EnvQueryTest_Pathfinding.md#testcomment)
- [TestMode](ue_ue.EnvQueryTest_Pathfinding.md#testmode)
- [TestOrder](ue_ue.EnvQueryTest_Pathfinding.md#testorder)
- [TestPurpose](ue_ue.EnvQueryTest_Pathfinding.md#testpurpose)
- [VerNum](ue_ue.EnvQueryTest_Pathfinding.md#vernum)
- [\_\_tid\_EnvQueryNode\_\_](ue_ue.EnvQueryTest_Pathfinding.md#__tid_envquerynode__)
- [\_\_tid\_EnvQueryTest\_Pathfinding\_\_](ue_ue.EnvQueryTest_Pathfinding.md#__tid_envquerytest_pathfinding__)
- [\_\_tid\_EnvQueryTest\_\_](ue_ue.EnvQueryTest_Pathfinding.md#__tid_envquerytest__)
- [\_\_tid\_Object\_\_](ue_ue.EnvQueryTest_Pathfinding.md#__tid_object__)
- [bDefineReferenceValue](ue_ue.EnvQueryTest_Pathfinding.md#bdefinereferencevalue)
- [bWorkOnFloatValues](ue_ue.EnvQueryTest_Pathfinding.md#bworkonfloatvalues)

### Methods

- [CreateDefaultSubobject](ue_ue.EnvQueryTest_Pathfinding.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EnvQueryTest_Pathfinding.md#executeubergraph)
- [GetClass](ue_ue.EnvQueryTest_Pathfinding.md#getclass)
- [GetName](ue_ue.EnvQueryTest_Pathfinding.md#getname)
- [GetOuter](ue_ue.EnvQueryTest_Pathfinding.md#getouter)
- [GetWorld](ue_ue.EnvQueryTest_Pathfinding.md#getworld)
- [Find](ue_ue.EnvQueryTest_Pathfinding.md#find)
- [Load](ue_ue.EnvQueryTest_Pathfinding.md#load)
- [StaticClass](ue_ue.EnvQueryTest_Pathfinding.md#staticclass)

## Constructors

### constructor

• **new EnvQueryTest_Pathfinding**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EnvQueryTest](ue_ue.EnvQueryTest.md).[constructor](ue_ue.EnvQueryTest.md#constructor)

#### Defined in

[ue/ue.d.ts:34560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L34560)

## Properties

### BoolValue

• **BoolValue**: [`AIDataProviderBoolValue`](ue_ue.AIDataProviderBoolValue.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[BoolValue](ue_ue.EnvQueryTest.md#boolvalue)

#### Defined in

[ue/ue.d.ts:15550](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15550)

___

### ClampMaxType

• **ClampMaxType**: [`EEnvQueryTestClamping`](../enums/ue_ue.EEnvQueryTestClamping.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[ClampMaxType](ue_ue.EnvQueryTest.md#clampmaxtype)

#### Defined in

[ue/ue.d.ts:15555](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15555)

___

### ClampMinType

• **ClampMinType**: [`EEnvQueryTestClamping`](../enums/ue_ue.EEnvQueryTestClamping.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[ClampMinType](ue_ue.EnvQueryTest.md#clampmintype)

#### Defined in

[ue/ue.d.ts:15554](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15554)

___

### Context

• **Context**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:34562](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L34562)

___

### FilterClass

• **FilterClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:34565](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L34565)

___

### FilterType

• **FilterType**: [`EEnvTestFilterType`](../enums/ue_ue.EEnvTestFilterType.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[FilterType](ue_ue.EnvQueryTest.md#filtertype)

#### Defined in

[ue/ue.d.ts:15549](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15549)

___

### FloatValueMax

• **FloatValueMax**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[FloatValueMax](ue_ue.EnvQueryTest.md#floatvaluemax)

#### Defined in

[ue/ue.d.ts:15552](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15552)

___

### FloatValueMin

• **FloatValueMin**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[FloatValueMin](ue_ue.EnvQueryTest.md#floatvaluemin)

#### Defined in

[ue/ue.d.ts:15551](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15551)

___

### MultipleContextFilterOp

• **MultipleContextFilterOp**: [`EEnvTestFilterOperator`](../enums/ue_ue.EEnvTestFilterOperator.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[MultipleContextFilterOp](ue_ue.EnvQueryTest.md#multiplecontextfilterop)

#### Defined in

[ue/ue.d.ts:15547](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15547)

___

### MultipleContextScoreOp

• **MultipleContextScoreOp**: [`EEnvTestScoreOperator`](../enums/ue_ue.EEnvTestScoreOperator.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[MultipleContextScoreOp](ue_ue.EnvQueryTest.md#multiplecontextscoreop)

#### Defined in

[ue/ue.d.ts:15548](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15548)

___

### NormalizationType

• **NormalizationType**: [`EEQSNormalizationType`](../enums/ue_ue.EEQSNormalizationType.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[NormalizationType](ue_ue.EnvQueryTest.md#normalizationtype)

#### Defined in

[ue/ue.d.ts:15556](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15556)

___

### PathFromContext

• **PathFromContext**: [`AIDataProviderBoolValue`](ue_ue.AIDataProviderBoolValue.md)

#### Defined in

[ue/ue.d.ts:34563](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L34563)

___

### ReferenceValue

• **ReferenceValue**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[ReferenceValue](ue_ue.EnvQueryTest.md#referencevalue)

#### Defined in

[ue/ue.d.ts:15560](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15560)

___

### ScoreClampMax

• **ScoreClampMax**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[ScoreClampMax](ue_ue.EnvQueryTest.md#scoreclampmax)

#### Defined in

[ue/ue.d.ts:15558](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15558)

___

### ScoreClampMin

• **ScoreClampMin**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[ScoreClampMin](ue_ue.EnvQueryTest.md#scoreclampmin)

#### Defined in

[ue/ue.d.ts:15557](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15557)

___

### ScoringEquation

• **ScoringEquation**: [`EEnvTestScoreEquation`](../enums/ue_ue.EEnvTestScoreEquation.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[ScoringEquation](ue_ue.EnvQueryTest.md#scoringequation)

#### Defined in

[ue/ue.d.ts:15553](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15553)

___

### ScoringFactor

• **ScoringFactor**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[ScoringFactor](ue_ue.EnvQueryTest.md#scoringfactor)

#### Defined in

[ue/ue.d.ts:15559](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15559)

___

### SkipUnreachable

• **SkipUnreachable**: [`AIDataProviderBoolValue`](ue_ue.AIDataProviderBoolValue.md)

#### Defined in

[ue/ue.d.ts:34564](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L34564)

___

### TestComment

• **TestComment**: `string`

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[TestComment](ue_ue.EnvQueryTest.md#testcomment)

#### Defined in

[ue/ue.d.ts:15546](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15546)

___

### TestMode

• **TestMode**: [`EEnvTestPathfinding`](../enums/ue_ue.EEnvTestPathfinding.md)

#### Defined in

[ue/ue.d.ts:34561](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L34561)

___

### TestOrder

• **TestOrder**: `number`

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[TestOrder](ue_ue.EnvQueryTest.md#testorder)

#### Defined in

[ue/ue.d.ts:15544](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15544)

___

### TestPurpose

• **TestPurpose**: [`EEnvTestPurpose`](../enums/ue_ue.EEnvTestPurpose.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[TestPurpose](ue_ue.EnvQueryTest.md#testpurpose)

#### Defined in

[ue/ue.d.ts:15545](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15545)

___

### VerNum

• **VerNum**: `number`

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[VerNum](ue_ue.EnvQueryTest.md#vernum)

#### Defined in

[ue/ue.d.ts:15465](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15465)

___

### \_\_tid\_EnvQueryNode\_\_

• **\_\_tid\_EnvQueryNode\_\_**: `boolean`

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[__tid_EnvQueryNode__](ue_ue.EnvQueryTest.md#__tid_envquerynode__)

#### Defined in

[ue/ue.d.ts:15470](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15470)

___

### \_\_tid\_EnvQueryTest\_Pathfinding\_\_

• **\_\_tid\_EnvQueryTest\_Pathfinding\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:34570](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L34570)

___

### \_\_tid\_EnvQueryTest\_\_

• **\_\_tid\_EnvQueryTest\_\_**: `boolean`

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[__tid_EnvQueryTest__](ue_ue.EnvQueryTest.md#__tid_envquerytest__)

#### Defined in

[ue/ue.d.ts:15567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15567)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[__tid_Object__](ue_ue.EnvQueryTest.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bDefineReferenceValue

• **bDefineReferenceValue**: `boolean`

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[bDefineReferenceValue](ue_ue.EnvQueryTest.md#bdefinereferencevalue)

#### Defined in

[ue/ue.d.ts:15561](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15561)

___

### bWorkOnFloatValues

• **bWorkOnFloatValues**: `boolean`

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[bWorkOnFloatValues](ue_ue.EnvQueryTest.md#bworkonfloatvalues)

#### Defined in

[ue/ue.d.ts:15562](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15562)

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

[EnvQueryTest](ue_ue.EnvQueryTest.md).[CreateDefaultSubobject](ue_ue.EnvQueryTest.md#createdefaultsubobject)

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

[EnvQueryTest](ue_ue.EnvQueryTest.md).[ExecuteUbergraph](ue_ue.EnvQueryTest.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[GetClass](ue_ue.EnvQueryTest.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[GetName](ue_ue.EnvQueryTest.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[GetOuter](ue_ue.EnvQueryTest.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EnvQueryTest](ue_ue.EnvQueryTest.md).[GetWorld](ue_ue.EnvQueryTest.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EnvQueryTest_Pathfinding`](ue_ue.EnvQueryTest_Pathfinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EnvQueryTest_Pathfinding`](ue_ue.EnvQueryTest_Pathfinding.md)

#### Overrides

[EnvQueryTest](ue_ue.EnvQueryTest.md).[Find](ue_ue.EnvQueryTest.md#find)

#### Defined in

[ue/ue.d.ts:34567](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L34567)

___

### Load

▸ `Static` **Load**(`InName`): [`EnvQueryTest_Pathfinding`](ue_ue.EnvQueryTest_Pathfinding.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EnvQueryTest_Pathfinding`](ue_ue.EnvQueryTest_Pathfinding.md)

#### Overrides

[EnvQueryTest](ue_ue.EnvQueryTest.md).[Load](ue_ue.EnvQueryTest.md#load)

#### Defined in

[ue/ue.d.ts:34568](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L34568)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EnvQueryTest](ue_ue.EnvQueryTest.md).[StaticClass](ue_ue.EnvQueryTest.md#staticclass)

#### Defined in

[ue/ue.d.ts:34566](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L34566)