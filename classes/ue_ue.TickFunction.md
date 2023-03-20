[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TickFunction

# Class: TickFunction

[ue/ue](../modules/ue_ue.md).TickFunction

## Hierarchy

- **`TickFunction`**

  ↳ [`ActorTickFunction`](ue_ue.ActorTickFunction.md)

  ↳ [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

  ↳ [`CharacterMovementComponentPostPhysicsTickFunction`](ue_ue.CharacterMovementComponentPostPhysicsTickFunction.md)

## Table of contents

### Constructors

- [constructor](ue_ue.TickFunction.md#constructor)

### Properties

- [EndTickGroup](ue_ue.TickFunction.md#endtickgroup)
- [TickGroup](ue_ue.TickFunction.md#tickgroup)
- [TickInterval](ue_ue.TickFunction.md#tickinterval)
- [\_\_tid\_TickFunction\_\_](ue_ue.TickFunction.md#__tid_tickfunction__)
- [bAllowTickOnDedicatedServer](ue_ue.TickFunction.md#ballowtickondedicatedserver)
- [bCanEverTick](ue_ue.TickFunction.md#bcanevertick)
- [bStartWithTickEnabled](ue_ue.TickFunction.md#bstartwithtickenabled)
- [bTickEvenWhenPaused](ue_ue.TickFunction.md#btickevenwhenpaused)

### Methods

- [StaticClass](ue_ue.TickFunction.md#staticclass)
- [StaticStruct](ue_ue.TickFunction.md#staticstruct)

## Constructors

### constructor

• **new TickFunction**()

#### Defined in

[ue/ue.d.ts:191](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L191)

• **new TickFunction**(`TickGroup`, `EndTickGroup`, `bTickEvenWhenPaused`, `bCanEverTick`, `bStartWithTickEnabled`, `bAllowTickOnDedicatedServer`, `TickInterval`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TickGroup` | [`ETickingGroup`](../enums/ue_ue.ETickingGroup.md) |
| `EndTickGroup` | [`ETickingGroup`](../enums/ue_ue.ETickingGroup.md) |
| `bTickEvenWhenPaused` | `boolean` |
| `bCanEverTick` | `boolean` |
| `bStartWithTickEnabled` | `boolean` |
| `bAllowTickOnDedicatedServer` | `boolean` |
| `TickInterval` | `number` |

#### Defined in

[ue/ue.d.ts:192](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L192)

## Properties

### EndTickGroup

• **EndTickGroup**: [`ETickingGroup`](../enums/ue_ue.ETickingGroup.md)

#### Defined in

[ue/ue.d.ts:194](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L194)

___

### TickGroup

• **TickGroup**: [`ETickingGroup`](../enums/ue_ue.ETickingGroup.md)

#### Defined in

[ue/ue.d.ts:193](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L193)

___

### TickInterval

• **TickInterval**: `number`

#### Defined in

[ue/ue.d.ts:199](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L199)

___

### \_\_tid\_TickFunction\_\_

• `Private` **\_\_tid\_TickFunction\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L205)

___

### bAllowTickOnDedicatedServer

• **bAllowTickOnDedicatedServer**: `boolean`

#### Defined in

[ue/ue.d.ts:198](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L198)

___

### bCanEverTick

• **bCanEverTick**: `boolean`

#### Defined in

[ue/ue.d.ts:196](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L196)

___

### bStartWithTickEnabled

• **bStartWithTickEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:197](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L197)

___

### bTickEvenWhenPaused

• **bTickEvenWhenPaused**: `boolean`

#### Defined in

[ue/ue.d.ts:195](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L195)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L203)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L204)
