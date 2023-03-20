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

## Properties

### EndTickGroup

• **EndTickGroup**: [`ETickingGroup`](../enums/ue_ue.ETickingGroup.md)

___

### TickGroup

• **TickGroup**: [`ETickingGroup`](../enums/ue_ue.ETickingGroup.md)

___

### TickInterval

• **TickInterval**: `number`

___

### \_\_tid\_TickFunction\_\_

• `Private` **\_\_tid\_TickFunction\_\_**: `boolean`

___

### bAllowTickOnDedicatedServer

• **bAllowTickOnDedicatedServer**: `boolean`

___

### bCanEverTick

• **bCanEverTick**: `boolean`

___

### bStartWithTickEnabled

• **bStartWithTickEnabled**: `boolean`

___

### bTickEvenWhenPaused

• **bTickEvenWhenPaused**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)
