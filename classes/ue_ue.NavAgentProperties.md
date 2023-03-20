[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NavAgentProperties

# Class: NavAgentProperties

[ue/ue](../modules/ue_ue.md).NavAgentProperties

## Hierarchy

- [`MovementProperties`](ue_ue.MovementProperties.md)

  ↳ **`NavAgentProperties`**

  ↳↳ [`NavDataConfig`](ue_ue.NavDataConfig.md)

## Table of contents

### Constructors

- [constructor](ue_ue.NavAgentProperties.md#constructor)

### Properties

- [AgentHeight](ue_ue.NavAgentProperties.md#agentheight)
- [AgentRadius](ue_ue.NavAgentProperties.md#agentradius)
- [AgentStepHeight](ue_ue.NavAgentProperties.md#agentstepheight)
- [NavWalkingSearchHeightScale](ue_ue.NavAgentProperties.md#navwalkingsearchheightscale)
- [PreferredNavData](ue_ue.NavAgentProperties.md#preferrednavdata)
- [\_\_tid\_NavAgentProperties\_\_](ue_ue.NavAgentProperties.md#__tid_navagentproperties__)
- [bCanCrouch](ue_ue.NavAgentProperties.md#bcancrouch)
- [bCanFly](ue_ue.NavAgentProperties.md#bcanfly)
- [bCanJump](ue_ue.NavAgentProperties.md#bcanjump)
- [bCanSwim](ue_ue.NavAgentProperties.md#bcanswim)
- [bCanWalk](ue_ue.NavAgentProperties.md#bcanwalk)

### Methods

- [StaticClass](ue_ue.NavAgentProperties.md#staticclass)
- [StaticStruct](ue_ue.NavAgentProperties.md#staticstruct)

## Constructors

### constructor

• **new NavAgentProperties**()

#### Overrides

[MovementProperties](ue_ue.MovementProperties.md).[constructor](ue_ue.MovementProperties.md#constructor)

• **new NavAgentProperties**(`AgentRadius`, `AgentHeight`, `AgentStepHeight`, `NavWalkingSearchHeightScale`, `PreferredNavData`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `AgentRadius` | `number` |
| `AgentHeight` | `number` |
| `AgentStepHeight` | `number` |
| `NavWalkingSearchHeightScale` | `number` |
| `PreferredNavData` | [`SoftClassPath`](ue_ue.SoftClassPath.md) |

#### Overrides

[MovementProperties](ue_ue.MovementProperties.md).[constructor](ue_ue.MovementProperties.md#constructor)

## Properties

### AgentHeight

• **AgentHeight**: `number`

___

### AgentRadius

• **AgentRadius**: `number`

___

### AgentStepHeight

• **AgentStepHeight**: `number`

___

### NavWalkingSearchHeightScale

• **NavWalkingSearchHeightScale**: `number`

___

### PreferredNavData

• **PreferredNavData**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### \_\_tid\_NavAgentProperties\_\_

• `Private` **\_\_tid\_NavAgentProperties\_\_**: `boolean`

___

### bCanCrouch

• **bCanCrouch**: `boolean`

#### Inherited from

[MovementProperties](ue_ue.MovementProperties.md).[bCanCrouch](ue_ue.MovementProperties.md#bcancrouch)

___

### bCanFly

• **bCanFly**: `boolean`

#### Inherited from

[MovementProperties](ue_ue.MovementProperties.md).[bCanFly](ue_ue.MovementProperties.md#bcanfly)

___

### bCanJump

• **bCanJump**: `boolean`

#### Inherited from

[MovementProperties](ue_ue.MovementProperties.md).[bCanJump](ue_ue.MovementProperties.md#bcanjump)

___

### bCanSwim

• **bCanSwim**: `boolean`

#### Inherited from

[MovementProperties](ue_ue.MovementProperties.md).[bCanSwim](ue_ue.MovementProperties.md#bcanswim)

___

### bCanWalk

• **bCanWalk**: `boolean`

#### Inherited from

[MovementProperties](ue_ue.MovementProperties.md).[bCanWalk](ue_ue.MovementProperties.md#bcanwalk)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[MovementProperties](ue_ue.MovementProperties.md).[StaticClass](ue_ue.MovementProperties.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[MovementProperties](ue_ue.MovementProperties.md).[StaticStruct](ue_ue.MovementProperties.md#staticstruct)
