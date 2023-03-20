[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NavDataConfig

# Class: NavDataConfig

[ue/ue](../modules/ue_ue.md).NavDataConfig

## Hierarchy

- [`NavAgentProperties`](ue_ue.NavAgentProperties.md)

  ↳ **`NavDataConfig`**

## Table of contents

### Constructors

- [constructor](ue_ue.NavDataConfig.md#constructor)

### Properties

- [AgentHeight](ue_ue.NavDataConfig.md#agentheight)
- [AgentRadius](ue_ue.NavDataConfig.md#agentradius)
- [AgentStepHeight](ue_ue.NavDataConfig.md#agentstepheight)
- [Color](ue_ue.NavDataConfig.md#color)
- [DefaultQueryExtent](ue_ue.NavDataConfig.md#defaultqueryextent)
- [Name](ue_ue.NavDataConfig.md#name)
- [NavDataClass](ue_ue.NavDataConfig.md#navdataclass)
- [NavWalkingSearchHeightScale](ue_ue.NavDataConfig.md#navwalkingsearchheightscale)
- [NavigationDataClass](ue_ue.NavDataConfig.md#navigationdataclass)
- [PreferredNavData](ue_ue.NavDataConfig.md#preferrednavdata)
- [\_\_tid\_NavDataConfig\_\_](ue_ue.NavDataConfig.md#__tid_navdataconfig__)
- [bCanCrouch](ue_ue.NavDataConfig.md#bcancrouch)
- [bCanFly](ue_ue.NavDataConfig.md#bcanfly)
- [bCanJump](ue_ue.NavDataConfig.md#bcanjump)
- [bCanSwim](ue_ue.NavDataConfig.md#bcanswim)
- [bCanWalk](ue_ue.NavDataConfig.md#bcanwalk)

### Methods

- [StaticClass](ue_ue.NavDataConfig.md#staticclass)
- [StaticStruct](ue_ue.NavDataConfig.md#staticstruct)

## Constructors

### constructor

• **new NavDataConfig**()

#### Overrides

[NavAgentProperties](ue_ue.NavAgentProperties.md).[constructor](ue_ue.NavAgentProperties.md#constructor)

• **new NavDataConfig**(`Name`, `Color`, `DefaultQueryExtent`, `NavigationDataClass`, `NavDataClass`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `Color` | [`Color`](ue_ue_s.Color.md) |
| `DefaultQueryExtent` | [`Vector`](ue_ue_s.Vector.md) |
| `NavigationDataClass` | [`Class`](ue_ue.Class.md) |
| `NavDataClass` | [`TSoftClassPtr`](../modules/ue_puerts.md#tsoftclassptr)<[`Actor`](ue_ue.Actor.md)\> |

#### Overrides

[NavAgentProperties](ue_ue.NavAgentProperties.md).[constructor](ue_ue.NavAgentProperties.md#constructor)

## Properties

### AgentHeight

• **AgentHeight**: `number`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[AgentHeight](ue_ue.NavAgentProperties.md#agentheight)

___

### AgentRadius

• **AgentRadius**: `number`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[AgentRadius](ue_ue.NavAgentProperties.md#agentradius)

___

### AgentStepHeight

• **AgentStepHeight**: `number`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[AgentStepHeight](ue_ue.NavAgentProperties.md#agentstepheight)

___

### Color

• **Color**: [`Color`](ue_ue_s.Color.md)

___

### DefaultQueryExtent

• **DefaultQueryExtent**: [`Vector`](ue_ue_s.Vector.md)

___

### Name

• **Name**: `string`

___

### NavDataClass

• **NavDataClass**: [`TSoftClassPtr`](../modules/ue_puerts.md#tsoftclassptr)<[`Actor`](ue_ue.Actor.md)\>

___

### NavWalkingSearchHeightScale

• **NavWalkingSearchHeightScale**: `number`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[NavWalkingSearchHeightScale](ue_ue.NavAgentProperties.md#navwalkingsearchheightscale)

___

### NavigationDataClass

• **NavigationDataClass**: [`Class`](ue_ue.Class.md)

___

### PreferredNavData

• **PreferredNavData**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[PreferredNavData](ue_ue.NavAgentProperties.md#preferrednavdata)

___

### \_\_tid\_NavDataConfig\_\_

• `Private` **\_\_tid\_NavDataConfig\_\_**: `boolean`

___

### bCanCrouch

• **bCanCrouch**: `boolean`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[bCanCrouch](ue_ue.NavAgentProperties.md#bcancrouch)

___

### bCanFly

• **bCanFly**: `boolean`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[bCanFly](ue_ue.NavAgentProperties.md#bcanfly)

___

### bCanJump

• **bCanJump**: `boolean`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[bCanJump](ue_ue.NavAgentProperties.md#bcanjump)

___

### bCanSwim

• **bCanSwim**: `boolean`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[bCanSwim](ue_ue.NavAgentProperties.md#bcanswim)

___

### bCanWalk

• **bCanWalk**: `boolean`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[bCanWalk](ue_ue.NavAgentProperties.md#bcanwalk)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[NavAgentProperties](ue_ue.NavAgentProperties.md).[StaticClass](ue_ue.NavAgentProperties.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[NavAgentProperties](ue_ue.NavAgentProperties.md).[StaticStruct](ue_ue.NavAgentProperties.md#staticstruct)
