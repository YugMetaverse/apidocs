[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EnvQueryTest

# Class: EnvQueryTest

[ue/ue](../modules/ue_ue.md).EnvQueryTest

## Hierarchy

- [`EnvQueryNode`](ue_ue.EnvQueryNode.md)

  ↳ **`EnvQueryTest`**

  ↳↳ [`EnvQueryTest_Distance`](ue_ue.EnvQueryTest_Distance.md)

  ↳↳ [`EnvQueryTest_Dot`](ue_ue.EnvQueryTest_Dot.md)

  ↳↳ [`EnvQueryTest_GameplayTags`](ue_ue.EnvQueryTest_GameplayTags.md)

  ↳↳ [`EnvQueryTest_Overlap`](ue_ue.EnvQueryTest_Overlap.md)

  ↳↳ [`EnvQueryTest_Pathfinding`](ue_ue.EnvQueryTest_Pathfinding.md)

  ↳↳ [`EnvQueryTest_Project`](ue_ue.EnvQueryTest_Project.md)

  ↳↳ [`EnvQueryTest_Random`](ue_ue.EnvQueryTest_Random.md)

  ↳↳ [`EnvQueryTest_Trace`](ue_ue.EnvQueryTest_Trace.md)

  ↳↳ [`EnvQueryTest_Volume`](ue_ue.EnvQueryTest_Volume.md)

## Table of contents

### Constructors

- [constructor](ue_ue.EnvQueryTest.md#constructor)

### Properties

- [BoolValue](ue_ue.EnvQueryTest.md#boolvalue)
- [ClampMaxType](ue_ue.EnvQueryTest.md#clampmaxtype)
- [ClampMinType](ue_ue.EnvQueryTest.md#clampmintype)
- [FilterType](ue_ue.EnvQueryTest.md#filtertype)
- [FloatValueMax](ue_ue.EnvQueryTest.md#floatvaluemax)
- [FloatValueMin](ue_ue.EnvQueryTest.md#floatvaluemin)
- [MultipleContextFilterOp](ue_ue.EnvQueryTest.md#multiplecontextfilterop)
- [MultipleContextScoreOp](ue_ue.EnvQueryTest.md#multiplecontextscoreop)
- [NormalizationType](ue_ue.EnvQueryTest.md#normalizationtype)
- [ReferenceValue](ue_ue.EnvQueryTest.md#referencevalue)
- [ScoreClampMax](ue_ue.EnvQueryTest.md#scoreclampmax)
- [ScoreClampMin](ue_ue.EnvQueryTest.md#scoreclampmin)
- [ScoringEquation](ue_ue.EnvQueryTest.md#scoringequation)
- [ScoringFactor](ue_ue.EnvQueryTest.md#scoringfactor)
- [TestComment](ue_ue.EnvQueryTest.md#testcomment)
- [TestOrder](ue_ue.EnvQueryTest.md#testorder)
- [TestPurpose](ue_ue.EnvQueryTest.md#testpurpose)
- [VerNum](ue_ue.EnvQueryTest.md#vernum)
- [\_\_tid\_EnvQueryNode\_\_](ue_ue.EnvQueryTest.md#__tid_envquerynode__)
- [\_\_tid\_EnvQueryTest\_\_](ue_ue.EnvQueryTest.md#__tid_envquerytest__)
- [\_\_tid\_Object\_\_](ue_ue.EnvQueryTest.md#__tid_object__)
- [bDefineReferenceValue](ue_ue.EnvQueryTest.md#bdefinereferencevalue)
- [bWorkOnFloatValues](ue_ue.EnvQueryTest.md#bworkonfloatvalues)

### Methods

- [CreateDefaultSubobject](ue_ue.EnvQueryTest.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EnvQueryTest.md#executeubergraph)
- [GetClass](ue_ue.EnvQueryTest.md#getclass)
- [GetName](ue_ue.EnvQueryTest.md#getname)
- [GetOuter](ue_ue.EnvQueryTest.md#getouter)
- [GetWorld](ue_ue.EnvQueryTest.md#getworld)
- [Find](ue_ue.EnvQueryTest.md#find)
- [Load](ue_ue.EnvQueryTest.md#load)
- [StaticClass](ue_ue.EnvQueryTest.md#staticclass)

## Constructors

### constructor

• **new EnvQueryTest**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EnvQueryNode](ue_ue.EnvQueryNode.md).[constructor](ue_ue.EnvQueryNode.md#constructor)

#### Defined in

[ue/ue.d.ts:15543](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15543)

## Properties

### BoolValue

• **BoolValue**: [`AIDataProviderBoolValue`](ue_ue.AIDataProviderBoolValue.md)

#### Defined in

[ue/ue.d.ts:15550](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15550)

___

### ClampMaxType

• **ClampMaxType**: [`EEnvQueryTestClamping`](../enums/ue_ue.EEnvQueryTestClamping.md)

#### Defined in

[ue/ue.d.ts:15555](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15555)

___

### ClampMinType

• **ClampMinType**: [`EEnvQueryTestClamping`](../enums/ue_ue.EEnvQueryTestClamping.md)

#### Defined in

[ue/ue.d.ts:15554](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15554)

___

### FilterType

• **FilterType**: [`EEnvTestFilterType`](../enums/ue_ue.EEnvTestFilterType.md)

#### Defined in

[ue/ue.d.ts:15549](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15549)

___

### FloatValueMax

• **FloatValueMax**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Defined in

[ue/ue.d.ts:15552](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15552)

___

### FloatValueMin

• **FloatValueMin**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Defined in

[ue/ue.d.ts:15551](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15551)

___

### MultipleContextFilterOp

• **MultipleContextFilterOp**: [`EEnvTestFilterOperator`](../enums/ue_ue.EEnvTestFilterOperator.md)

#### Defined in

[ue/ue.d.ts:15547](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15547)

___

### MultipleContextScoreOp

• **MultipleContextScoreOp**: [`EEnvTestScoreOperator`](../enums/ue_ue.EEnvTestScoreOperator.md)

#### Defined in

[ue/ue.d.ts:15548](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15548)

___

### NormalizationType

• **NormalizationType**: [`EEQSNormalizationType`](../enums/ue_ue.EEQSNormalizationType.md)

#### Defined in

[ue/ue.d.ts:15556](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15556)

___

### ReferenceValue

• **ReferenceValue**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Defined in

[ue/ue.d.ts:15560](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15560)

___

### ScoreClampMax

• **ScoreClampMax**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Defined in

[ue/ue.d.ts:15558](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15558)

___

### ScoreClampMin

• **ScoreClampMin**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Defined in

[ue/ue.d.ts:15557](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15557)

___

### ScoringEquation

• **ScoringEquation**: [`EEnvTestScoreEquation`](../enums/ue_ue.EEnvTestScoreEquation.md)

#### Defined in

[ue/ue.d.ts:15553](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15553)

___

### ScoringFactor

• **ScoringFactor**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

#### Defined in

[ue/ue.d.ts:15559](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15559)

___

### TestComment

• **TestComment**: `string`

#### Defined in

[ue/ue.d.ts:15546](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15546)

___

### TestOrder

• **TestOrder**: `number`

#### Defined in

[ue/ue.d.ts:15544](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15544)

___

### TestPurpose

• **TestPurpose**: [`EEnvTestPurpose`](../enums/ue_ue.EEnvTestPurpose.md)

#### Defined in

[ue/ue.d.ts:15545](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15545)

___

### VerNum

• **VerNum**: `number`

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[VerNum](ue_ue.EnvQueryNode.md#vernum)

#### Defined in

[ue/ue.d.ts:15465](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15465)

___

### \_\_tid\_EnvQueryNode\_\_

• **\_\_tid\_EnvQueryNode\_\_**: `boolean`

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[__tid_EnvQueryNode__](ue_ue.EnvQueryNode.md#__tid_envquerynode__)

#### Defined in

[ue/ue.d.ts:15470](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15470)

___

### \_\_tid\_EnvQueryTest\_\_

• **\_\_tid\_EnvQueryTest\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15567](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15567)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[__tid_Object__](ue_ue.EnvQueryNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bDefineReferenceValue

• **bDefineReferenceValue**: `boolean`

#### Defined in

[ue/ue.d.ts:15561](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15561)

___

### bWorkOnFloatValues

• **bWorkOnFloatValues**: `boolean`

#### Defined in

[ue/ue.d.ts:15562](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15562)

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

[EnvQueryNode](ue_ue.EnvQueryNode.md).[CreateDefaultSubobject](ue_ue.EnvQueryNode.md#createdefaultsubobject)

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

[EnvQueryNode](ue_ue.EnvQueryNode.md).[ExecuteUbergraph](ue_ue.EnvQueryNode.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[GetClass](ue_ue.EnvQueryNode.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[GetName](ue_ue.EnvQueryNode.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[GetOuter](ue_ue.EnvQueryNode.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[GetWorld](ue_ue.EnvQueryNode.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EnvQueryTest`](ue_ue.EnvQueryTest.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EnvQueryTest`](ue_ue.EnvQueryTest.md)

#### Overrides

[EnvQueryNode](ue_ue.EnvQueryNode.md).[Find](ue_ue.EnvQueryNode.md#find)

#### Defined in

[ue/ue.d.ts:15564](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15564)

___

### Load

▸ `Static` **Load**(`InName`): [`EnvQueryTest`](ue_ue.EnvQueryTest.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EnvQueryTest`](ue_ue.EnvQueryTest.md)

#### Overrides

[EnvQueryNode](ue_ue.EnvQueryNode.md).[Load](ue_ue.EnvQueryNode.md#load)

#### Defined in

[ue/ue.d.ts:15565](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15565)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EnvQueryNode](ue_ue.EnvQueryNode.md).[StaticClass](ue_ue.EnvQueryNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:15563](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15563)
