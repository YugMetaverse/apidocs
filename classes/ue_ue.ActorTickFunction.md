[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ActorTickFunction

# Class: ActorTickFunction

[ue/ue](../modules/ue_ue.md).ActorTickFunction

## Hierarchy

- [`TickFunction`](ue_ue.TickFunction.md)

  ↳ **`ActorTickFunction`**

## Table of contents

### Constructors

- [constructor](ue_ue.ActorTickFunction.md#constructor)

### Properties

- [EndTickGroup](ue_ue.ActorTickFunction.md#endtickgroup)
- [TickGroup](ue_ue.ActorTickFunction.md#tickgroup)
- [TickInterval](ue_ue.ActorTickFunction.md#tickinterval)
- [\_\_tid\_ActorTickFunction\_\_](ue_ue.ActorTickFunction.md#__tid_actortickfunction__)
- [bAllowTickOnDedicatedServer](ue_ue.ActorTickFunction.md#ballowtickondedicatedserver)
- [bCanEverTick](ue_ue.ActorTickFunction.md#bcanevertick)
- [bStartWithTickEnabled](ue_ue.ActorTickFunction.md#bstartwithtickenabled)
- [bTickEvenWhenPaused](ue_ue.ActorTickFunction.md#btickevenwhenpaused)

### Methods

- [StaticClass](ue_ue.ActorTickFunction.md#staticclass)
- [StaticStruct](ue_ue.ActorTickFunction.md#staticstruct)

## Constructors

### constructor

• **new ActorTickFunction**()

#### Overrides

[TickFunction](ue_ue.TickFunction.md).[constructor](ue_ue.TickFunction.md#constructor)

## Properties

### EndTickGroup

• **EndTickGroup**: [`ETickingGroup`](../enums/ue_ue.ETickingGroup.md)

#### Inherited from

[TickFunction](ue_ue.TickFunction.md).[EndTickGroup](ue_ue.TickFunction.md#endtickgroup)

___

### TickGroup

• **TickGroup**: [`ETickingGroup`](../enums/ue_ue.ETickingGroup.md)

#### Inherited from

[TickFunction](ue_ue.TickFunction.md).[TickGroup](ue_ue.TickFunction.md#tickgroup)

___

### TickInterval

• **TickInterval**: `number`

#### Inherited from

[TickFunction](ue_ue.TickFunction.md).[TickInterval](ue_ue.TickFunction.md#tickinterval)

___

### \_\_tid\_ActorTickFunction\_\_

• `Private` **\_\_tid\_ActorTickFunction\_\_**: `boolean`

___

### bAllowTickOnDedicatedServer

• **bAllowTickOnDedicatedServer**: `boolean`

#### Inherited from

[TickFunction](ue_ue.TickFunction.md).[bAllowTickOnDedicatedServer](ue_ue.TickFunction.md#ballowtickondedicatedserver)

___

### bCanEverTick

• **bCanEverTick**: `boolean`

#### Inherited from

[TickFunction](ue_ue.TickFunction.md).[bCanEverTick](ue_ue.TickFunction.md#bcanevertick)

___

### bStartWithTickEnabled

• **bStartWithTickEnabled**: `boolean`

#### Inherited from

[TickFunction](ue_ue.TickFunction.md).[bStartWithTickEnabled](ue_ue.TickFunction.md#bstartwithtickenabled)

___

### bTickEvenWhenPaused

• **bTickEvenWhenPaused**: `boolean`

#### Inherited from

[TickFunction](ue_ue.TickFunction.md).[bTickEvenWhenPaused](ue_ue.TickFunction.md#btickevenwhenpaused)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[TickFunction](ue_ue.TickFunction.md).[StaticClass](ue_ue.TickFunction.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[TickFunction](ue_ue.TickFunction.md).[StaticStruct](ue_ue.TickFunction.md#staticstruct)
