[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ActorComponentTickFunction

# Class: ActorComponentTickFunction

[ue/ue](../modules/ue_ue.md).ActorComponentTickFunction

## Hierarchy

- [`TickFunction`](ue_ue.TickFunction.md)

  ↳ **`ActorComponentTickFunction`**

## Table of contents

### Constructors

- [constructor](ue_ue.ActorComponentTickFunction.md#constructor)

### Properties

- [EndTickGroup](ue_ue.ActorComponentTickFunction.md#endtickgroup)
- [TickGroup](ue_ue.ActorComponentTickFunction.md#tickgroup)
- [TickInterval](ue_ue.ActorComponentTickFunction.md#tickinterval)
- [\_\_tid\_ActorComponentTickFunction\_\_](ue_ue.ActorComponentTickFunction.md#__tid_actorcomponenttickfunction__)
- [bAllowTickOnDedicatedServer](ue_ue.ActorComponentTickFunction.md#ballowtickondedicatedserver)
- [bCanEverTick](ue_ue.ActorComponentTickFunction.md#bcanevertick)
- [bStartWithTickEnabled](ue_ue.ActorComponentTickFunction.md#bstartwithtickenabled)
- [bTickEvenWhenPaused](ue_ue.ActorComponentTickFunction.md#btickevenwhenpaused)

### Methods

- [StaticClass](ue_ue.ActorComponentTickFunction.md#staticclass)
- [StaticStruct](ue_ue.ActorComponentTickFunction.md#staticstruct)

## Constructors

### constructor

• **new ActorComponentTickFunction**()

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

### \_\_tid\_ActorComponentTickFunction\_\_

• `Private` **\_\_tid\_ActorComponentTickFunction\_\_**: `boolean`

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
