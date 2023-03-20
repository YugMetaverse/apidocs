[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EnvQueryGenerator

# Class: EnvQueryGenerator

[ue/ue](../modules/ue_ue.md).EnvQueryGenerator

## Hierarchy

- [`EnvQueryNode`](ue_ue.EnvQueryNode.md)

  ↳ **`EnvQueryGenerator`**

  ↳↳ [`EnvQueryGenerator_ActorsOfClass`](ue_ue.EnvQueryGenerator_ActorsOfClass.md)

  ↳↳ [`EnvQueryGenerator_BlueprintBase`](ue_ue.EnvQueryGenerator_BlueprintBase.md)

  ↳↳ [`EnvQueryGenerator_Composite`](ue_ue.EnvQueryGenerator_Composite.md)

  ↳↳ [`EnvQueryGenerator_ProjectedPoints`](ue_ue.EnvQueryGenerator_ProjectedPoints.md)

  ↳↳ [`EnvQueryGenerator_CurrentLocation`](ue_ue.EnvQueryGenerator_CurrentLocation.md)

## Table of contents

### Constructors

- [constructor](ue_ue.EnvQueryGenerator.md#constructor)

### Properties

- [ItemType](ue_ue.EnvQueryGenerator.md#itemtype)
- [OptionName](ue_ue.EnvQueryGenerator.md#optionname)
- [VerNum](ue_ue.EnvQueryGenerator.md#vernum)
- [\_\_tid\_EnvQueryGenerator\_\_](ue_ue.EnvQueryGenerator.md#__tid_envquerygenerator__)
- [\_\_tid\_EnvQueryNode\_\_](ue_ue.EnvQueryGenerator.md#__tid_envquerynode__)
- [\_\_tid\_Object\_\_](ue_ue.EnvQueryGenerator.md#__tid_object__)
- [bAutoSortTests](ue_ue.EnvQueryGenerator.md#bautosorttests)

### Methods

- [CreateDefaultSubobject](ue_ue.EnvQueryGenerator.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EnvQueryGenerator.md#executeubergraph)
- [GetClass](ue_ue.EnvQueryGenerator.md#getclass)
- [GetName](ue_ue.EnvQueryGenerator.md#getname)
- [GetOuter](ue_ue.EnvQueryGenerator.md#getouter)
- [GetWorld](ue_ue.EnvQueryGenerator.md#getworld)
- [Find](ue_ue.EnvQueryGenerator.md#find)
- [Load](ue_ue.EnvQueryGenerator.md#load)
- [StaticClass](ue_ue.EnvQueryGenerator.md#staticclass)

## Constructors

### constructor

• **new EnvQueryGenerator**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EnvQueryNode](ue_ue.EnvQueryNode.md).[constructor](ue_ue.EnvQueryNode.md#constructor)

## Properties

### ItemType

• **ItemType**: [`Class`](ue_ue.Class.md)

___

### OptionName

• **OptionName**: `string`

___

### VerNum

• **VerNum**: `number`

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[VerNum](ue_ue.EnvQueryNode.md#vernum)

___

### \_\_tid\_EnvQueryGenerator\_\_

• **\_\_tid\_EnvQueryGenerator\_\_**: `boolean`

___

### \_\_tid\_EnvQueryNode\_\_

• **\_\_tid\_EnvQueryNode\_\_**: `boolean`

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[__tid_EnvQueryNode__](ue_ue.EnvQueryNode.md#__tid_envquerynode__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[__tid_Object__](ue_ue.EnvQueryNode.md#__tid_object__)

___

### bAutoSortTests

• **bAutoSortTests**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EnvQueryGenerator`](ue_ue.EnvQueryGenerator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EnvQueryGenerator`](ue_ue.EnvQueryGenerator.md)

#### Overrides

[EnvQueryNode](ue_ue.EnvQueryNode.md).[Find](ue_ue.EnvQueryNode.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EnvQueryGenerator`](ue_ue.EnvQueryGenerator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EnvQueryGenerator`](ue_ue.EnvQueryGenerator.md)

#### Overrides

[EnvQueryNode](ue_ue.EnvQueryNode.md).[Load](ue_ue.EnvQueryNode.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EnvQueryNode](ue_ue.EnvQueryNode.md).[StaticClass](ue_ue.EnvQueryNode.md#staticclass)
