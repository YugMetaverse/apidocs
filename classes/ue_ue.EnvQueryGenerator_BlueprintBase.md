[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EnvQueryGenerator\_BlueprintBase

# Class: EnvQueryGenerator\_BlueprintBase

[ue/ue](../modules/ue_ue.md).EnvQueryGenerator_BlueprintBase

## Hierarchy

- [`EnvQueryGenerator`](ue_ue.EnvQueryGenerator.md)

  ↳ **`EnvQueryGenerator_BlueprintBase`**

## Table of contents

### Constructors

- [constructor](ue_ue.EnvQueryGenerator_BlueprintBase.md#constructor)

### Properties

- [Context](ue_ue.EnvQueryGenerator_BlueprintBase.md#context)
- [GeneratedItemType](ue_ue.EnvQueryGenerator_BlueprintBase.md#generateditemtype)
- [GeneratorsActionDescription](ue_ue.EnvQueryGenerator_BlueprintBase.md#generatorsactiondescription)
- [ItemType](ue_ue.EnvQueryGenerator_BlueprintBase.md#itemtype)
- [OptionName](ue_ue.EnvQueryGenerator_BlueprintBase.md#optionname)
- [VerNum](ue_ue.EnvQueryGenerator_BlueprintBase.md#vernum)
- [\_\_tid\_EnvQueryGenerator\_BlueprintBase\_\_](ue_ue.EnvQueryGenerator_BlueprintBase.md#__tid_envquerygenerator_blueprintbase__)
- [\_\_tid\_EnvQueryGenerator\_\_](ue_ue.EnvQueryGenerator_BlueprintBase.md#__tid_envquerygenerator__)
- [\_\_tid\_EnvQueryNode\_\_](ue_ue.EnvQueryGenerator_BlueprintBase.md#__tid_envquerynode__)
- [\_\_tid\_Object\_\_](ue_ue.EnvQueryGenerator_BlueprintBase.md#__tid_object__)
- [bAutoSortTests](ue_ue.EnvQueryGenerator_BlueprintBase.md#bautosorttests)

### Methods

- [AddGeneratedActor](ue_ue.EnvQueryGenerator_BlueprintBase.md#addgeneratedactor)
- [AddGeneratedVector](ue_ue.EnvQueryGenerator_BlueprintBase.md#addgeneratedvector)
- [CreateDefaultSubobject](ue_ue.EnvQueryGenerator_BlueprintBase.md#createdefaultsubobject)
- [DoItemGeneration](ue_ue.EnvQueryGenerator_BlueprintBase.md#doitemgeneration)
- [ExecuteUbergraph](ue_ue.EnvQueryGenerator_BlueprintBase.md#executeubergraph)
- [GetClass](ue_ue.EnvQueryGenerator_BlueprintBase.md#getclass)
- [GetName](ue_ue.EnvQueryGenerator_BlueprintBase.md#getname)
- [GetOuter](ue_ue.EnvQueryGenerator_BlueprintBase.md#getouter)
- [GetQuerier](ue_ue.EnvQueryGenerator_BlueprintBase.md#getquerier)
- [GetWorld](ue_ue.EnvQueryGenerator_BlueprintBase.md#getworld)
- [Find](ue_ue.EnvQueryGenerator_BlueprintBase.md#find)
- [Load](ue_ue.EnvQueryGenerator_BlueprintBase.md#load)
- [StaticClass](ue_ue.EnvQueryGenerator_BlueprintBase.md#staticclass)

## Constructors

### constructor

• **new EnvQueryGenerator_BlueprintBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EnvQueryGenerator](ue_ue.EnvQueryGenerator.md).[constructor](ue_ue.EnvQueryGenerator.md#constructor)

## Properties

### Context

• **Context**: [`Class`](ue_ue.Class.md)

___

### GeneratedItemType

• **GeneratedItemType**: [`Class`](ue_ue.Class.md)

___

### GeneratorsActionDescription

• **GeneratorsActionDescription**: `string`

___

### ItemType

• **ItemType**: [`Class`](ue_ue.Class.md)

#### Inherited from

[EnvQueryGenerator](ue_ue.EnvQueryGenerator.md).[ItemType](ue_ue.EnvQueryGenerator.md#itemtype)

___

### OptionName

• **OptionName**: `string`

#### Inherited from

[EnvQueryGenerator](ue_ue.EnvQueryGenerator.md).[OptionName](ue_ue.EnvQueryGenerator.md#optionname)

___

### VerNum

• **VerNum**: `number`

#### Inherited from

[EnvQueryGenerator](ue_ue.EnvQueryGenerator.md).[VerNum](ue_ue.EnvQueryGenerator.md#vernum)

___

### \_\_tid\_EnvQueryGenerator\_BlueprintBase\_\_

• **\_\_tid\_EnvQueryGenerator\_BlueprintBase\_\_**: `boolean`

___

### \_\_tid\_EnvQueryGenerator\_\_

• **\_\_tid\_EnvQueryGenerator\_\_**: `boolean`

#### Inherited from

[EnvQueryGenerator](ue_ue.EnvQueryGenerator.md).[__tid_EnvQueryGenerator__](ue_ue.EnvQueryGenerator.md#__tid_envquerygenerator__)

___

### \_\_tid\_EnvQueryNode\_\_

• **\_\_tid\_EnvQueryNode\_\_**: `boolean`

#### Inherited from

[EnvQueryGenerator](ue_ue.EnvQueryGenerator.md).[__tid_EnvQueryNode__](ue_ue.EnvQueryGenerator.md#__tid_envquerynode__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EnvQueryGenerator](ue_ue.EnvQueryGenerator.md).[__tid_Object__](ue_ue.EnvQueryGenerator.md#__tid_object__)

___

### bAutoSortTests

• **bAutoSortTests**: `boolean`

#### Inherited from

[EnvQueryGenerator](ue_ue.EnvQueryGenerator.md).[bAutoSortTests](ue_ue.EnvQueryGenerator.md#bautosorttests)

## Methods

### AddGeneratedActor

▸ **AddGeneratedActor**(`GeneratedActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GeneratedActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

___

### AddGeneratedVector

▸ **AddGeneratedVector**(`GeneratedVector`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `GeneratedVector` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

___

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

[EnvQueryGenerator](ue_ue.EnvQueryGenerator.md).[CreateDefaultSubobject](ue_ue.EnvQueryGenerator.md#createdefaultsubobject)

___

### DoItemGeneration

▸ **DoItemGeneration**(`ContextLocations`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ContextLocations` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\> |

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

[EnvQueryGenerator](ue_ue.EnvQueryGenerator.md).[ExecuteUbergraph](ue_ue.EnvQueryGenerator.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EnvQueryGenerator](ue_ue.EnvQueryGenerator.md).[GetClass](ue_ue.EnvQueryGenerator.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EnvQueryGenerator](ue_ue.EnvQueryGenerator.md).[GetName](ue_ue.EnvQueryGenerator.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EnvQueryGenerator](ue_ue.EnvQueryGenerator.md).[GetOuter](ue_ue.EnvQueryGenerator.md#getouter)

___

### GetQuerier

▸ **GetQuerier**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EnvQueryGenerator](ue_ue.EnvQueryGenerator.md).[GetWorld](ue_ue.EnvQueryGenerator.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EnvQueryGenerator_BlueprintBase`](ue_ue.EnvQueryGenerator_BlueprintBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EnvQueryGenerator_BlueprintBase`](ue_ue.EnvQueryGenerator_BlueprintBase.md)

#### Overrides

[EnvQueryGenerator](ue_ue.EnvQueryGenerator.md).[Find](ue_ue.EnvQueryGenerator.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EnvQueryGenerator_BlueprintBase`](ue_ue.EnvQueryGenerator_BlueprintBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EnvQueryGenerator_BlueprintBase`](ue_ue.EnvQueryGenerator_BlueprintBase.md)

#### Overrides

[EnvQueryGenerator](ue_ue.EnvQueryGenerator.md).[Load](ue_ue.EnvQueryGenerator.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EnvQueryGenerator](ue_ue.EnvQueryGenerator.md).[StaticClass](ue_ue.EnvQueryGenerator.md#staticclass)
