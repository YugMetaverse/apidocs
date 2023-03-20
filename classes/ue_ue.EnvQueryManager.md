[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EnvQueryManager

# Class: EnvQueryManager

[ue/ue](../modules/ue_ue.md).EnvQueryManager

## Hierarchy

- [`AISubsystem`](ue_ue.AISubsystem.md)

  ↳ **`EnvQueryManager`**

## Table of contents

### Constructors

- [constructor](ue_ue.EnvQueryManager.md#constructor)

### Properties

- [AISystem](ue_ue.EnvQueryManager.md#aisystem)
- [GCShieldedWrappers](ue_ue.EnvQueryManager.md#gcshieldedwrappers)
- [InstanceCache](ue_ue.EnvQueryManager.md#instancecache)
- [LocalContexts](ue_ue.EnvQueryManager.md#localcontexts)
- [MaxAllowedTestingTime](ue_ue.EnvQueryManager.md#maxallowedtestingtime)
- [QueryCountWarningInterval](ue_ue.EnvQueryManager.md#querycountwarninginterval)
- [QueryCountWarningThreshold](ue_ue.EnvQueryManager.md#querycountwarningthreshold)
- [\_\_tid\_AISubsystem\_\_](ue_ue.EnvQueryManager.md#__tid_aisubsystem__)
- [\_\_tid\_EnvQueryManager\_\_](ue_ue.EnvQueryManager.md#__tid_envquerymanager__)
- [\_\_tid\_Object\_\_](ue_ue.EnvQueryManager.md#__tid_object__)
- [bTestQueriesUsingBreadth](ue_ue.EnvQueryManager.md#btestqueriesusingbreadth)

### Methods

- [CreateDefaultSubobject](ue_ue.EnvQueryManager.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EnvQueryManager.md#executeubergraph)
- [GetClass](ue_ue.EnvQueryManager.md#getclass)
- [GetName](ue_ue.EnvQueryManager.md#getname)
- [GetOuter](ue_ue.EnvQueryManager.md#getouter)
- [GetWorld](ue_ue.EnvQueryManager.md#getworld)
- [Find](ue_ue.EnvQueryManager.md#find)
- [Load](ue_ue.EnvQueryManager.md#load)
- [RunEQSQuery](ue_ue.EnvQueryManager.md#runeqsquery)
- [StaticClass](ue_ue.EnvQueryManager.md#staticclass)

## Constructors

### constructor

• **new EnvQueryManager**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AISubsystem](ue_ue.AISubsystem.md).[constructor](ue_ue.AISubsystem.md#constructor)

## Properties

### AISystem

• **AISystem**: [`AISystem`](ue_ue.AISystem.md)

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[AISystem](ue_ue.AISubsystem.md#aisystem)

___

### GCShieldedWrappers

• **GCShieldedWrappers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EnvQueryInstanceBlueprintWrapper`](ue_ue.EnvQueryInstanceBlueprintWrapper.md)\>

___

### InstanceCache

• **InstanceCache**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EnvQueryInstanceCache`](ue_ue.EnvQueryInstanceCache.md)\>

___

### LocalContexts

• **LocalContexts**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EnvQueryContext`](ue_ue.EnvQueryContext.md)\>

___

### MaxAllowedTestingTime

• **MaxAllowedTestingTime**: `number`

___

### QueryCountWarningInterval

• **QueryCountWarningInterval**: `number`

___

### QueryCountWarningThreshold

• **QueryCountWarningThreshold**: `number`

___

### \_\_tid\_AISubsystem\_\_

• **\_\_tid\_AISubsystem\_\_**: `boolean`

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[__tid_AISubsystem__](ue_ue.AISubsystem.md#__tid_aisubsystem__)

___

### \_\_tid\_EnvQueryManager\_\_

• **\_\_tid\_EnvQueryManager\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[__tid_Object__](ue_ue.AISubsystem.md#__tid_object__)

___

### bTestQueriesUsingBreadth

• **bTestQueriesUsingBreadth**: `boolean`

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

[AISubsystem](ue_ue.AISubsystem.md).[CreateDefaultSubobject](ue_ue.AISubsystem.md#createdefaultsubobject)

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

[AISubsystem](ue_ue.AISubsystem.md).[ExecuteUbergraph](ue_ue.AISubsystem.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[GetClass](ue_ue.AISubsystem.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[GetName](ue_ue.AISubsystem.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[GetOuter](ue_ue.AISubsystem.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AISubsystem](ue_ue.AISubsystem.md).[GetWorld](ue_ue.AISubsystem.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EnvQueryManager`](ue_ue.EnvQueryManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EnvQueryManager`](ue_ue.EnvQueryManager.md)

#### Overrides

[AISubsystem](ue_ue.AISubsystem.md).[Find](ue_ue.AISubsystem.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EnvQueryManager`](ue_ue.EnvQueryManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EnvQueryManager`](ue_ue.EnvQueryManager.md)

#### Overrides

[AISubsystem](ue_ue.AISubsystem.md).[Load](ue_ue.AISubsystem.md#load)

___

### RunEQSQuery

▸ `Static` **RunEQSQuery**(`WorldContextObject`, `QueryTemplate`, `Querier`, `RunMode`, `WrapperClass`): [`EnvQueryInstanceBlueprintWrapper`](ue_ue.EnvQueryInstanceBlueprintWrapper.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `QueryTemplate` | [`$Nullable`](../modules/puerts.md#$nullable)<[`EnvQuery`](ue_ue.EnvQuery.md)\> |
| `Querier` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `RunMode` | [`EEnvQueryRunMode`](../enums/ue_ue.EEnvQueryRunMode.md) |
| `WrapperClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`EnvQueryInstanceBlueprintWrapper`](ue_ue.EnvQueryInstanceBlueprintWrapper.md)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AISubsystem](ue_ue.AISubsystem.md).[StaticClass](ue_ue.AISubsystem.md#staticclass)
