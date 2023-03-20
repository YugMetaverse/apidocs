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

## Properties

### BoolValue

• **BoolValue**: [`AIDataProviderBoolValue`](ue_ue.AIDataProviderBoolValue.md)

___

### ClampMaxType

• **ClampMaxType**: [`EEnvQueryTestClamping`](../enums/ue_ue.EEnvQueryTestClamping.md)

___

### ClampMinType

• **ClampMinType**: [`EEnvQueryTestClamping`](../enums/ue_ue.EEnvQueryTestClamping.md)

___

### FilterType

• **FilterType**: [`EEnvTestFilterType`](../enums/ue_ue.EEnvTestFilterType.md)

___

### FloatValueMax

• **FloatValueMax**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

___

### FloatValueMin

• **FloatValueMin**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

___

### MultipleContextFilterOp

• **MultipleContextFilterOp**: [`EEnvTestFilterOperator`](../enums/ue_ue.EEnvTestFilterOperator.md)

___

### MultipleContextScoreOp

• **MultipleContextScoreOp**: [`EEnvTestScoreOperator`](../enums/ue_ue.EEnvTestScoreOperator.md)

___

### NormalizationType

• **NormalizationType**: [`EEQSNormalizationType`](../enums/ue_ue.EEQSNormalizationType.md)

___

### ReferenceValue

• **ReferenceValue**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

___

### ScoreClampMax

• **ScoreClampMax**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

___

### ScoreClampMin

• **ScoreClampMin**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

___

### ScoringEquation

• **ScoringEquation**: [`EEnvTestScoreEquation`](../enums/ue_ue.EEnvTestScoreEquation.md)

___

### ScoringFactor

• **ScoringFactor**: [`AIDataProviderFloatValue`](ue_ue.AIDataProviderFloatValue.md)

___

### TestComment

• **TestComment**: `string`

___

### TestOrder

• **TestOrder**: `number`

___

### TestPurpose

• **TestPurpose**: [`EEnvTestPurpose`](../enums/ue_ue.EEnvTestPurpose.md)

___

### VerNum

• **VerNum**: `number`

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[VerNum](ue_ue.EnvQueryNode.md#vernum)

___

### \_\_tid\_EnvQueryNode\_\_

• **\_\_tid\_EnvQueryNode\_\_**: `boolean`

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[__tid_EnvQueryNode__](ue_ue.EnvQueryNode.md#__tid_envquerynode__)

___

### \_\_tid\_EnvQueryTest\_\_

• **\_\_tid\_EnvQueryTest\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[__tid_Object__](ue_ue.EnvQueryNode.md#__tid_object__)

___

### bDefineReferenceValue

• **bDefineReferenceValue**: `boolean`

___

### bWorkOnFloatValues

• **bWorkOnFloatValues**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[GetClass](ue_ue.EnvQueryNode.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[GetName](ue_ue.EnvQueryNode.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[GetOuter](ue_ue.EnvQueryNode.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[GetWorld](ue_ue.EnvQueryNode.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EnvQueryNode](ue_ue.EnvQueryNode.md).[StaticClass](ue_ue.EnvQueryNode.md#staticclass)
