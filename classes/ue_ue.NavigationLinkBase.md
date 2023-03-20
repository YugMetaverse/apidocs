[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NavigationLinkBase

# Class: NavigationLinkBase

[ue/ue](../modules/ue_ue.md).NavigationLinkBase

## Hierarchy

- **`NavigationLinkBase`**

  ↳ [`NavigationLink`](ue_ue.NavigationLink.md)

  ↳ [`NavigationSegmentLink`](ue_ue.NavigationSegmentLink.md)

## Table of contents

### Constructors

- [constructor](ue_ue.NavigationLinkBase.md#constructor)

### Properties

- [AreaClass](ue_ue.NavigationLinkBase.md#areaclass)
- [Description](ue_ue.NavigationLinkBase.md#description)
- [Direction](ue_ue.NavigationLinkBase.md#direction)
- [LeftProjectHeight](ue_ue.NavigationLinkBase.md#leftprojectheight)
- [MaxFallDownLength](ue_ue.NavigationLinkBase.md#maxfalldownlength)
- [SnapHeight](ue_ue.NavigationLinkBase.md#snapheight)
- [SnapRadius](ue_ue.NavigationLinkBase.md#snapradius)
- [SupportedAgents](ue_ue.NavigationLinkBase.md#supportedagents)
- [\_\_tid\_NavigationLinkBase\_\_](ue_ue.NavigationLinkBase.md#__tid_navigationlinkbase__)
- [bCustomFlag0](ue_ue.NavigationLinkBase.md#bcustomflag0)
- [bCustomFlag1](ue_ue.NavigationLinkBase.md#bcustomflag1)
- [bCustomFlag2](ue_ue.NavigationLinkBase.md#bcustomflag2)
- [bCustomFlag3](ue_ue.NavigationLinkBase.md#bcustomflag3)
- [bCustomFlag4](ue_ue.NavigationLinkBase.md#bcustomflag4)
- [bCustomFlag5](ue_ue.NavigationLinkBase.md#bcustomflag5)
- [bCustomFlag6](ue_ue.NavigationLinkBase.md#bcustomflag6)
- [bCustomFlag7](ue_ue.NavigationLinkBase.md#bcustomflag7)
- [bSnapToCheapestArea](ue_ue.NavigationLinkBase.md#bsnaptocheapestarea)
- [bSupportsAgent0](ue_ue.NavigationLinkBase.md#bsupportsagent0)
- [bSupportsAgent1](ue_ue.NavigationLinkBase.md#bsupportsagent1)
- [bSupportsAgent10](ue_ue.NavigationLinkBase.md#bsupportsagent10)
- [bSupportsAgent11](ue_ue.NavigationLinkBase.md#bsupportsagent11)
- [bSupportsAgent12](ue_ue.NavigationLinkBase.md#bsupportsagent12)
- [bSupportsAgent13](ue_ue.NavigationLinkBase.md#bsupportsagent13)
- [bSupportsAgent14](ue_ue.NavigationLinkBase.md#bsupportsagent14)
- [bSupportsAgent15](ue_ue.NavigationLinkBase.md#bsupportsagent15)
- [bSupportsAgent2](ue_ue.NavigationLinkBase.md#bsupportsagent2)
- [bSupportsAgent3](ue_ue.NavigationLinkBase.md#bsupportsagent3)
- [bSupportsAgent4](ue_ue.NavigationLinkBase.md#bsupportsagent4)
- [bSupportsAgent5](ue_ue.NavigationLinkBase.md#bsupportsagent5)
- [bSupportsAgent6](ue_ue.NavigationLinkBase.md#bsupportsagent6)
- [bSupportsAgent7](ue_ue.NavigationLinkBase.md#bsupportsagent7)
- [bSupportsAgent8](ue_ue.NavigationLinkBase.md#bsupportsagent8)
- [bSupportsAgent9](ue_ue.NavigationLinkBase.md#bsupportsagent9)
- [bUseSnapHeight](ue_ue.NavigationLinkBase.md#busesnapheight)

### Methods

- [StaticClass](ue_ue.NavigationLinkBase.md#staticclass)
- [StaticStruct](ue_ue.NavigationLinkBase.md#staticstruct)

## Constructors

### constructor

• **new NavigationLinkBase**()

#### Defined in

[ue/ue.d.ts:53173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53173)

• **new NavigationLinkBase**(`LeftProjectHeight`, `MaxFallDownLength`, `SnapRadius`, `SnapHeight`, `SupportedAgents`, `bSupportsAgent0`, `bSupportsAgent1`, `bSupportsAgent2`, `bSupportsAgent3`, `bSupportsAgent4`, `bSupportsAgent5`, `bSupportsAgent6`, `bSupportsAgent7`, `bSupportsAgent8`, `bSupportsAgent9`, `bSupportsAgent10`, `bSupportsAgent11`, `bSupportsAgent12`, `bSupportsAgent13`, `bSupportsAgent14`, `bSupportsAgent15`, `Description`, `Direction`, `bUseSnapHeight`, `bSnapToCheapestArea`, `bCustomFlag0`, `bCustomFlag1`, `bCustomFlag2`, `bCustomFlag3`, `bCustomFlag4`, `bCustomFlag5`, `bCustomFlag6`, `bCustomFlag7`, `AreaClass`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `LeftProjectHeight` | `number` |
| `MaxFallDownLength` | `number` |
| `SnapRadius` | `number` |
| `SnapHeight` | `number` |
| `SupportedAgents` | [`NavAgentSelector`](ue_ue.NavAgentSelector.md) |
| `bSupportsAgent0` | `boolean` |
| `bSupportsAgent1` | `boolean` |
| `bSupportsAgent2` | `boolean` |
| `bSupportsAgent3` | `boolean` |
| `bSupportsAgent4` | `boolean` |
| `bSupportsAgent5` | `boolean` |
| `bSupportsAgent6` | `boolean` |
| `bSupportsAgent7` | `boolean` |
| `bSupportsAgent8` | `boolean` |
| `bSupportsAgent9` | `boolean` |
| `bSupportsAgent10` | `boolean` |
| `bSupportsAgent11` | `boolean` |
| `bSupportsAgent12` | `boolean` |
| `bSupportsAgent13` | `boolean` |
| `bSupportsAgent14` | `boolean` |
| `bSupportsAgent15` | `boolean` |
| `Description` | `string` |
| `Direction` | [`ENavLinkDirection`](../enums/ue_ue.ENavLinkDirection.md) |
| `bUseSnapHeight` | `boolean` |
| `bSnapToCheapestArea` | `boolean` |
| `bCustomFlag0` | `boolean` |
| `bCustomFlag1` | `boolean` |
| `bCustomFlag2` | `boolean` |
| `bCustomFlag3` | `boolean` |
| `bCustomFlag4` | `boolean` |
| `bCustomFlag5` | `boolean` |
| `bCustomFlag6` | `boolean` |
| `bCustomFlag7` | `boolean` |
| `AreaClass` | [`Class`](ue_ue.Class.md) |

#### Defined in

[ue/ue.d.ts:53174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53174)

## Properties

### AreaClass

• **AreaClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:53208](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53208)

___

### Description

• **Description**: `string`

#### Defined in

[ue/ue.d.ts:53196](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53196)

___

### Direction

• **Direction**: [`ENavLinkDirection`](../enums/ue_ue.ENavLinkDirection.md)

#### Defined in

[ue/ue.d.ts:53197](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53197)

___

### LeftProjectHeight

• **LeftProjectHeight**: `number`

#### Defined in

[ue/ue.d.ts:53175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53175)

___

### MaxFallDownLength

• **MaxFallDownLength**: `number`

#### Defined in

[ue/ue.d.ts:53176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53176)

___

### SnapHeight

• **SnapHeight**: `number`

#### Defined in

[ue/ue.d.ts:53178](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53178)

___

### SnapRadius

• **SnapRadius**: `number`

#### Defined in

[ue/ue.d.ts:53177](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53177)

___

### SupportedAgents

• **SupportedAgents**: [`NavAgentSelector`](ue_ue.NavAgentSelector.md)

#### Defined in

[ue/ue.d.ts:53179](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53179)

___

### \_\_tid\_NavigationLinkBase\_\_

• `Private` **\_\_tid\_NavigationLinkBase\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:53214](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53214)

___

### bCustomFlag0

• **bCustomFlag0**: `boolean`

#### Defined in

[ue/ue.d.ts:53200](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53200)

___

### bCustomFlag1

• **bCustomFlag1**: `boolean`

#### Defined in

[ue/ue.d.ts:53201](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53201)

___

### bCustomFlag2

• **bCustomFlag2**: `boolean`

#### Defined in

[ue/ue.d.ts:53202](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53202)

___

### bCustomFlag3

• **bCustomFlag3**: `boolean`

#### Defined in

[ue/ue.d.ts:53203](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53203)

___

### bCustomFlag4

• **bCustomFlag4**: `boolean`

#### Defined in

[ue/ue.d.ts:53204](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53204)

___

### bCustomFlag5

• **bCustomFlag5**: `boolean`

#### Defined in

[ue/ue.d.ts:53205](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53205)

___

### bCustomFlag6

• **bCustomFlag6**: `boolean`

#### Defined in

[ue/ue.d.ts:53206](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53206)

___

### bCustomFlag7

• **bCustomFlag7**: `boolean`

#### Defined in

[ue/ue.d.ts:53207](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53207)

___

### bSnapToCheapestArea

• **bSnapToCheapestArea**: `boolean`

#### Defined in

[ue/ue.d.ts:53199](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53199)

___

### bSupportsAgent0

• **bSupportsAgent0**: `boolean`

#### Defined in

[ue/ue.d.ts:53180](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53180)

___

### bSupportsAgent1

• **bSupportsAgent1**: `boolean`

#### Defined in

[ue/ue.d.ts:53181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53181)

___

### bSupportsAgent10

• **bSupportsAgent10**: `boolean`

#### Defined in

[ue/ue.d.ts:53190](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53190)

___

### bSupportsAgent11

• **bSupportsAgent11**: `boolean`

#### Defined in

[ue/ue.d.ts:53191](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53191)

___

### bSupportsAgent12

• **bSupportsAgent12**: `boolean`

#### Defined in

[ue/ue.d.ts:53192](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53192)

___

### bSupportsAgent13

• **bSupportsAgent13**: `boolean`

#### Defined in

[ue/ue.d.ts:53193](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53193)

___

### bSupportsAgent14

• **bSupportsAgent14**: `boolean`

#### Defined in

[ue/ue.d.ts:53194](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53194)

___

### bSupportsAgent15

• **bSupportsAgent15**: `boolean`

#### Defined in

[ue/ue.d.ts:53195](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53195)

___

### bSupportsAgent2

• **bSupportsAgent2**: `boolean`

#### Defined in

[ue/ue.d.ts:53182](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53182)

___

### bSupportsAgent3

• **bSupportsAgent3**: `boolean`

#### Defined in

[ue/ue.d.ts:53183](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53183)

___

### bSupportsAgent4

• **bSupportsAgent4**: `boolean`

#### Defined in

[ue/ue.d.ts:53184](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53184)

___

### bSupportsAgent5

• **bSupportsAgent5**: `boolean`

#### Defined in

[ue/ue.d.ts:53185](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53185)

___

### bSupportsAgent6

• **bSupportsAgent6**: `boolean`

#### Defined in

[ue/ue.d.ts:53186](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53186)

___

### bSupportsAgent7

• **bSupportsAgent7**: `boolean`

#### Defined in

[ue/ue.d.ts:53187](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53187)

___

### bSupportsAgent8

• **bSupportsAgent8**: `boolean`

#### Defined in

[ue/ue.d.ts:53188](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53188)

___

### bSupportsAgent9

• **bSupportsAgent9**: `boolean`

#### Defined in

[ue/ue.d.ts:53189](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53189)

___

### bUseSnapHeight

• **bUseSnapHeight**: `boolean`

#### Defined in

[ue/ue.d.ts:53198](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53198)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:53212](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53212)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:53213](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L53213)
