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

#### Defined in

[ue/ue.d.ts:15474](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15474)

## Properties

### ItemType

• **ItemType**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:15476](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15476)

___

### OptionName

• **OptionName**: `string`

#### Defined in

[ue/ue.d.ts:15475](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15475)

___

### VerNum

• **VerNum**: `number`

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[VerNum](ue_ue.EnvQueryNode.md#vernum)

#### Defined in

[ue/ue.d.ts:15465](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15465)

___

### \_\_tid\_EnvQueryGenerator\_\_

• **\_\_tid\_EnvQueryGenerator\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:15482](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15482)

___

### \_\_tid\_EnvQueryNode\_\_

• **\_\_tid\_EnvQueryNode\_\_**: `boolean`

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[__tid_EnvQueryNode__](ue_ue.EnvQueryNode.md#__tid_envquerynode__)

#### Defined in

[ue/ue.d.ts:15470](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15470)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EnvQueryNode](ue_ue.EnvQueryNode.md).[__tid_Object__](ue_ue.EnvQueryNode.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### bAutoSortTests

• **bAutoSortTests**: `boolean`

#### Defined in

[ue/ue.d.ts:15477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15477)

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

#### Defined in

[ue/ue.d.ts:15479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15479)

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

#### Defined in

[ue/ue.d.ts:15480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15480)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EnvQueryNode](ue_ue.EnvQueryNode.md).[StaticClass](ue_ue.EnvQueryNode.md#staticclass)

#### Defined in

[ue/ue.d.ts:15478](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15478)
