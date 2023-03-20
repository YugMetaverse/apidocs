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

#### Defined in

[ue/ue.d.ts:50755](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50755)

## Properties

### BBComp

• **BBComp**: [`BlackboardComponent`](ue_ue.BlackboardComponent.md)

#### Inherited from

[MockAI](ue_ue.MockAI.md).[BBComp](ue_ue.MockAI.md#bbcomp)

#### Defined in

[ue/ue.d.ts:50743](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50743)

___

### BTComp

• **BTComp**: [`BehaviorTreeComponent`](ue_ue.BehaviorTreeComponent.md)

#### Defined in

[ue/ue.d.ts:50756](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50756)

___

### BrainComp

• **BrainComp**: [`BrainComponent`](ue_ue.BrainComponent.md)

#### Inherited from

[MockAI](ue_ue.MockAI.md).[BrainComp](ue_ue.MockAI.md#braincomp)

#### Defined in

[ue/ue.d.ts:50744](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50744)

___

### PawnActionComp

• **PawnActionComp**: [`PawnActionsComponent`](ue_ue.PawnActionsComponent.md)

#### Inherited from

[MockAI](ue_ue.MockAI.md).[PawnActionComp](ue_ue.MockAI.md#pawnactioncomp)

#### Defined in

[ue/ue.d.ts:50746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50746)

___

### PerceptionComp

• **PerceptionComp**: [`AIPerceptionComponent`](ue_ue.AIPerceptionComponent.md)

#### Inherited from

[MockAI](ue_ue.MockAI.md).[PerceptionComp](ue_ue.MockAI.md#perceptioncomp)

#### Defined in

[ue/ue.d.ts:50745](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50745)

___

### \_\_tid\_MockAI\_BT\_\_

• **\_\_tid\_MockAI\_BT\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:50761](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50761)

___

### \_\_tid\_MockAI\_\_

• **\_\_tid\_MockAI\_\_**: `boolean`

#### Inherited from

[MockAI](ue_ue.MockAI.md).[__tid_MockAI__](ue_ue.MockAI.md#__tid_mockai__)

#### Defined in

[ue/ue.d.ts:50751](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50751)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MockAI](ue_ue.MockAI.md).[__tid_Object__](ue_ue.MockAI.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[MockAI](ue_ue.MockAI.md).[ExecuteUbergraph](ue_ue.MockAI.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MockAI](ue_ue.MockAI.md).[GetClass](ue_ue.MockAI.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MockAI](ue_ue.MockAI.md).[GetName](ue_ue.MockAI.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MockAI](ue_ue.MockAI.md).[GetOuter](ue_ue.MockAI.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MockAI](ue_ue.MockAI.md).[GetWorld](ue_ue.MockAI.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:50758](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50758)

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

#### Defined in

[ue/ue.d.ts:50759](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50759)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MockAI](ue_ue.MockAI.md).[StaticClass](ue_ue.MockAI.md#staticclass)

#### Defined in

[ue/ue.d.ts:50757](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50757)
