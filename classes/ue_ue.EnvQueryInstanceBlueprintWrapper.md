[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EnvQueryInstanceBlueprintWrapper

# Class: EnvQueryInstanceBlueprintWrapper

[ue/ue](../modules/ue_ue.md).EnvQueryInstanceBlueprintWrapper

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`EnvQueryInstanceBlueprintWrapper`**

## Table of contents

### Constructors

- [constructor](ue_ue.EnvQueryInstanceBlueprintWrapper.md#constructor)

### Properties

- [ItemType](ue_ue.EnvQueryInstanceBlueprintWrapper.md#itemtype)
- [OnQueryFinishedEvent](ue_ue.EnvQueryInstanceBlueprintWrapper.md#onqueryfinishedevent)
- [OptionIndex](ue_ue.EnvQueryInstanceBlueprintWrapper.md#optionindex)
- [QueryID](ue_ue.EnvQueryInstanceBlueprintWrapper.md#queryid)
- [\_\_tid\_EnvQueryInstanceBlueprintWrapper\_\_](ue_ue.EnvQueryInstanceBlueprintWrapper.md#__tid_envqueryinstanceblueprintwrapper__)
- [\_\_tid\_Object\_\_](ue_ue.EnvQueryInstanceBlueprintWrapper.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EnvQueryInstanceBlueprintWrapper.md#createdefaultsubobject)
- [EQSQueryDoneSignature\_\_DelegateSignature](ue_ue.EnvQueryInstanceBlueprintWrapper.md#eqsquerydonesignature__delegatesignature)
- [ExecuteUbergraph](ue_ue.EnvQueryInstanceBlueprintWrapper.md#executeubergraph)
- [GetClass](ue_ue.EnvQueryInstanceBlueprintWrapper.md#getclass)
- [GetItemScore](ue_ue.EnvQueryInstanceBlueprintWrapper.md#getitemscore)
- [GetName](ue_ue.EnvQueryInstanceBlueprintWrapper.md#getname)
- [GetOuter](ue_ue.EnvQueryInstanceBlueprintWrapper.md#getouter)
- [GetQueryResultsAsActors](ue_ue.EnvQueryInstanceBlueprintWrapper.md#getqueryresultsasactors)
- [GetQueryResultsAsLocations](ue_ue.EnvQueryInstanceBlueprintWrapper.md#getqueryresultsaslocations)
- [GetResultsAsActors](ue_ue.EnvQueryInstanceBlueprintWrapper.md#getresultsasactors)
- [GetResultsAsLocations](ue_ue.EnvQueryInstanceBlueprintWrapper.md#getresultsaslocations)
- [GetWorld](ue_ue.EnvQueryInstanceBlueprintWrapper.md#getworld)
- [SetNamedParam](ue_ue.EnvQueryInstanceBlueprintWrapper.md#setnamedparam)
- [Find](ue_ue.EnvQueryInstanceBlueprintWrapper.md#find)
- [Load](ue_ue.EnvQueryInstanceBlueprintWrapper.md#load)
- [StaticClass](ue_ue.EnvQueryInstanceBlueprintWrapper.md#staticclass)

## Constructors

### constructor

• **new EnvQueryInstanceBlueprintWrapper**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### ItemType

• **ItemType**: [`Class`](ue_ue.Class.md)

___

### OnQueryFinishedEvent

• **OnQueryFinishedEvent**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`QueryInstance`: [`$Nullable`](../modules/puerts.md#$nullable)<[`EnvQueryInstanceBlueprintWrapper`](ue_ue.EnvQueryInstanceBlueprintWrapper.md)\>, `QueryStatus`: [`EEnvQueryStatus`](../enums/ue_ue.EEnvQueryStatus.md)) => `void`\>

___

### OptionIndex

• **OptionIndex**: `number`

___

### QueryID

• **QueryID**: `number`

___

### \_\_tid\_EnvQueryInstanceBlueprintWrapper\_\_

• **\_\_tid\_EnvQueryInstanceBlueprintWrapper\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

### EQSQueryDoneSignature\_\_DelegateSignature

▸ **EQSQueryDoneSignature__DelegateSignature**(`QueryInstance`, `QueryStatus`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `QueryInstance` | [`$Nullable`](../modules/puerts.md#$nullable)<[`EnvQueryInstanceBlueprintWrapper`](ue_ue.EnvQueryInstanceBlueprintWrapper.md)\> |
| `QueryStatus` | [`EEnvQueryStatus`](../enums/ue_ue.EEnvQueryStatus.md) |

#### Returns

`void`

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

### GetItemScore

▸ **GetItemScore**(`ItemIndex`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ItemIndex` | `number` |

#### Returns

`number`

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

### GetQueryResultsAsActors

▸ **GetQueryResultsAsActors**(`ResultActors`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ResultActors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |

#### Returns

`boolean`

___

### GetQueryResultsAsLocations

▸ **GetQueryResultsAsLocations**(`ResultLocations`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ResultLocations` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |

#### Returns

`boolean`

___

### GetResultsAsActors

▸ **GetResultsAsActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

___

### GetResultsAsLocations

▸ **GetResultsAsLocations**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### SetNamedParam

▸ **SetNamedParam**(`ParamName`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ParamName` | `string` |
| `Value` | `number` |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EnvQueryInstanceBlueprintWrapper`](ue_ue.EnvQueryInstanceBlueprintWrapper.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EnvQueryInstanceBlueprintWrapper`](ue_ue.EnvQueryInstanceBlueprintWrapper.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EnvQueryInstanceBlueprintWrapper`](ue_ue.EnvQueryInstanceBlueprintWrapper.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EnvQueryInstanceBlueprintWrapper`](ue_ue.EnvQueryInstanceBlueprintWrapper.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
