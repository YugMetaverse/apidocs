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

#### Defined in

[ue/ue.d.ts:13352](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13352)

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

#### Defined in

[ue/ue.d.ts:13353](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13353)

## Properties

### AgentHeight

• **AgentHeight**: `number`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[AgentHeight](ue_ue.NavAgentProperties.md#agentheight)

#### Defined in

[ue/ue.d.ts:5453](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5453)

___

### AgentRadius

• **AgentRadius**: `number`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[AgentRadius](ue_ue.NavAgentProperties.md#agentradius)

#### Defined in

[ue/ue.d.ts:5452](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5452)

___

### AgentStepHeight

• **AgentStepHeight**: `number`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[AgentStepHeight](ue_ue.NavAgentProperties.md#agentstepheight)

#### Defined in

[ue/ue.d.ts:5454](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5454)

___

### Color

• **Color**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:13355](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13355)

___

### DefaultQueryExtent

• **DefaultQueryExtent**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:13356](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13356)

___

### Name

• **Name**: `string`

#### Defined in

[ue/ue.d.ts:13354](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13354)

___

### NavDataClass

• **NavDataClass**: [`TSoftClassPtr`](../modules/ue_puerts.md#tsoftclassptr)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:13358](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13358)

___

### NavWalkingSearchHeightScale

• **NavWalkingSearchHeightScale**: `number`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[NavWalkingSearchHeightScale](ue_ue.NavAgentProperties.md#navwalkingsearchheightscale)

#### Defined in

[ue/ue.d.ts:5455](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5455)

___

### NavigationDataClass

• **NavigationDataClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:13357](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13357)

___

### PreferredNavData

• **PreferredNavData**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[PreferredNavData](ue_ue.NavAgentProperties.md#preferrednavdata)

#### Defined in

[ue/ue.d.ts:5456](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5456)

___

### \_\_tid\_NavDataConfig\_\_

• `Private` **\_\_tid\_NavDataConfig\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:13364](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13364)

___

### bCanCrouch

• **bCanCrouch**: `boolean`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[bCanCrouch](ue_ue.NavAgentProperties.md#bcancrouch)

#### Defined in

[ue/ue.d.ts:5436](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5436)

___

### bCanFly

• **bCanFly**: `boolean`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[bCanFly](ue_ue.NavAgentProperties.md#bcanfly)

#### Defined in

[ue/ue.d.ts:5440](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5440)

___

### bCanJump

• **bCanJump**: `boolean`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[bCanJump](ue_ue.NavAgentProperties.md#bcanjump)

#### Defined in

[ue/ue.d.ts:5437](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5437)

___

### bCanSwim

• **bCanSwim**: `boolean`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[bCanSwim](ue_ue.NavAgentProperties.md#bcanswim)

#### Defined in

[ue/ue.d.ts:5439](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5439)

___

### bCanWalk

• **bCanWalk**: `boolean`

#### Inherited from

[NavAgentProperties](ue_ue.NavAgentProperties.md).[bCanWalk](ue_ue.NavAgentProperties.md#bcanwalk)

#### Defined in

[ue/ue.d.ts:5438](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L5438)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[NavAgentProperties](ue_ue.NavAgentProperties.md).[StaticClass](ue_ue.NavAgentProperties.md#staticclass)

#### Defined in

[ue/ue.d.ts:13362](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13362)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[NavAgentProperties](ue_ue.NavAgentProperties.md).[StaticStruct](ue_ue.NavAgentProperties.md#staticstruct)

#### Defined in

[ue/ue.d.ts:13363](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13363)
