[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MockAI\_BT

# Class: MockAI\_BT

[ue/ue](../modules/ue_ue.md).MockAI_BT

## Hierarchy

- [`MockAI`](ue_ue.MockAI.md)

  ↳ **`MockAI_BT`**

## Table of contents

### Constructors

- [constructor](ue_ue.MockAI_BT.md#constructor)

### Properties

- [BBComp](ue_ue.MockAI_BT.md#bbcomp)
- [BTComp](ue_ue.MockAI_BT.md#btcomp)
- [BrainComp](ue_ue.MockAI_BT.md#braincomp)
- [PawnActionComp](ue_ue.MockAI_BT.md#pawnactioncomp)
- [PerceptionComp](ue_ue.MockAI_BT.md#perceptioncomp)
- [\_\_tid\_MockAI\_BT\_\_](ue_ue.MockAI_BT.md#__tid_mockai_bt__)
- [\_\_tid\_MockAI\_\_](ue_ue.MockAI_BT.md#__tid_mockai__)
- [\_\_tid\_Object\_\_](ue_ue.MockAI_BT.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MockAI_BT.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MockAI_BT.md#executeubergraph)
- [GetClass](ue_ue.MockAI_BT.md#getclass)
- [GetName](ue_ue.MockAI_BT.md#getname)
- [GetOuter](ue_ue.MockAI_BT.md#getouter)
- [GetWorld](ue_ue.MockAI_BT.md#getworld)
- [Find](ue_ue.MockAI_BT.md#find)
- [Load](ue_ue.MockAI_BT.md#load)
- [StaticClass](ue_ue.MockAI_BT.md#staticclass)

## Constructors

### constructor

• **new MockAI_BT**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MockAI](ue_ue.MockAI.md).[constructor](ue_ue.MockAI.md#constructor)

## Properties

### BBComp

• **BBComp**: [`BlackboardComponent`](ue_ue.BlackboardComponent.md)

#### Inherited from

[MockAI](ue_ue.MockAI.md).[BBComp](ue_ue.MockAI.md#bbcomp)

___

### BTComp

• **BTComp**: [`BehaviorTreeComponent`](ue_ue.BehaviorTreeComponent.md)

___

### BrainComp

• **BrainComp**: [`BrainComponent`](ue_ue.BrainComponent.md)

#### Inherited from

[MockAI](ue_ue.MockAI.md).[BrainComp](ue_ue.MockAI.md#braincomp)

___

### PawnActionComp

• **PawnActionComp**: [`PawnActionsComponent`](ue_ue.PawnActionsComponent.md)

#### Inherited from

[MockAI](ue_ue.MockAI.md).[PawnActionComp](ue_ue.MockAI.md#pawnactioncomp)

___

### PerceptionComp

• **PerceptionComp**: [`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)

#### Inherited from

[MockAI](ue_ue.MockAI.md).[PerceptionComp](ue_ue.MockAI.md#perceptioncomp)

___

### \_\_tid\_MockAI\_BT\_\_

• **\_\_tid\_MockAI\_BT\_\_**: `boolean`

___

### \_\_tid\_MockAI\_\_

• **\_\_tid\_MockAI\_\_**: `boolean`

#### Inherited from

[MockAI](ue_ue.MockAI.md).[__tid_MockAI__](ue_ue.MockAI.md#__tid_mockai__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MockAI](ue_ue.MockAI.md).[__tid_Object__](ue_ue.MockAI.md#__tid_object__)

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

[MockAI](ue_ue.MockAI.md).[CreateDefaultSubobject](ue_ue.MockAI.md#createdefaultsubobject)

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

[MockAI](ue_ue.MockAI.md).[ExecuteUbergraph](ue_ue.MockAI.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MockAI](ue_ue.MockAI.md).[GetClass](ue_ue.MockAI.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MockAI](ue_ue.MockAI.md).[GetName](ue_ue.MockAI.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MockAI](ue_ue.MockAI.md).[GetOuter](ue_ue.MockAI.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MockAI](ue_ue.MockAI.md).[GetWorld](ue_ue.MockAI.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MockAI_BT`](ue_ue.MockAI_BT.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MockAI_BT`](ue_ue.MockAI_BT.md)

#### Overrides

[MockAI](ue_ue.MockAI.md).[Find](ue_ue.MockAI.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MockAI_BT`](ue_ue.MockAI_BT.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MockAI_BT`](ue_ue.MockAI_BT.md)

#### Overrides

[MockAI](ue_ue.MockAI.md).[Load](ue_ue.MockAI.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MockAI](ue_ue.MockAI.md).[StaticClass](ue_ue.MockAI.md#staticclass)
