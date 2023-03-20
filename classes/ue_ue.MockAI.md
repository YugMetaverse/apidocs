[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MockAI

# Class: MockAI

[ue/ue](../modules/ue_ue.md).MockAI

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MockAI`**

  ↳↳ [`MockAI_BT`](ue_ue.MockAI_BT.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MockAI.md#constructor)

### Properties

- [BBComp](ue_ue.MockAI.md#bbcomp)
- [BrainComp](ue_ue.MockAI.md#braincomp)
- [PawnActionComp](ue_ue.MockAI.md#pawnactioncomp)
- [PerceptionComp](ue_ue.MockAI.md#perceptioncomp)
- [\_\_tid\_MockAI\_\_](ue_ue.MockAI.md#__tid_mockai__)
- [\_\_tid\_Object\_\_](ue_ue.MockAI.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MockAI.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MockAI.md#executeubergraph)
- [GetClass](ue_ue.MockAI.md#getclass)
- [GetName](ue_ue.MockAI.md#getname)
- [GetOuter](ue_ue.MockAI.md#getouter)
- [GetWorld](ue_ue.MockAI.md#getworld)
- [Find](ue_ue.MockAI.md#find)
- [Load](ue_ue.MockAI.md#load)
- [StaticClass](ue_ue.MockAI.md#staticclass)

## Constructors

### constructor

• **new MockAI**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### BBComp

• **BBComp**: [`BlackboardComponent`](ue_ue.BlackboardComponent.md)

___

### BrainComp

• **BrainComp**: [`BrainComponent`](ue_ue.BrainComponent.md)

___

### PawnActionComp

• **PawnActionComp**: [`PawnActionsComponent`](ue_ue.PawnActionsComponent.md)

___

### PerceptionComp

• **PerceptionComp**: [`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)

___

### \_\_tid\_MockAI\_\_

• **\_\_tid\_MockAI\_\_**: `boolean`

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

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MockAI`](ue_ue.MockAI.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MockAI`](ue_ue.MockAI.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MockAI`](ue_ue.MockAI.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MockAI`](ue_ue.MockAI.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
