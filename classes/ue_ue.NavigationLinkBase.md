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

## Properties

### AreaClass

• **AreaClass**: [`Class`](ue_ue.Class.md)

___

### Description

• **Description**: `string`

___

### Direction

• **Direction**: [`ENavLinkDirection`](../enums/ue_ue.ENavLinkDirection.md)

___

### LeftProjectHeight

• **LeftProjectHeight**: `number`

___

### MaxFallDownLength

• **MaxFallDownLength**: `number`

___

### SnapHeight

• **SnapHeight**: `number`

___

### SnapRadius

• **SnapRadius**: `number`

___

### SupportedAgents

• **SupportedAgents**: [`NavAgentSelector`](ue_ue.NavAgentSelector.md)

___

### \_\_tid\_NavigationLinkBase\_\_

• `Private` **\_\_tid\_NavigationLinkBase\_\_**: `boolean`

___

### bCustomFlag0

• **bCustomFlag0**: `boolean`

___

### bCustomFlag1

• **bCustomFlag1**: `boolean`

___

### bCustomFlag2

• **bCustomFlag2**: `boolean`

___

### bCustomFlag3

• **bCustomFlag3**: `boolean`

___

### bCustomFlag4

• **bCustomFlag4**: `boolean`

___

### bCustomFlag5

• **bCustomFlag5**: `boolean`

___

### bCustomFlag6

• **bCustomFlag6**: `boolean`

___

### bCustomFlag7

• **bCustomFlag7**: `boolean`

___

### bSnapToCheapestArea

• **bSnapToCheapestArea**: `boolean`

___

### bSupportsAgent0

• **bSupportsAgent0**: `boolean`

___

### bSupportsAgent1

• **bSupportsAgent1**: `boolean`

___

### bSupportsAgent10

• **bSupportsAgent10**: `boolean`

___

### bSupportsAgent11

• **bSupportsAgent11**: `boolean`

___

### bSupportsAgent12

• **bSupportsAgent12**: `boolean`

___

### bSupportsAgent13

• **bSupportsAgent13**: `boolean`

___

### bSupportsAgent14

• **bSupportsAgent14**: `boolean`

___

### bSupportsAgent15

• **bSupportsAgent15**: `boolean`

___

### bSupportsAgent2

• **bSupportsAgent2**: `boolean`

___

### bSupportsAgent3

• **bSupportsAgent3**: `boolean`

___

### bSupportsAgent4

• **bSupportsAgent4**: `boolean`

___

### bSupportsAgent5

• **bSupportsAgent5**: `boolean`

___

### bSupportsAgent6

• **bSupportsAgent6**: `boolean`

___

### bSupportsAgent7

• **bSupportsAgent7**: `boolean`

___

### bSupportsAgent8

• **bSupportsAgent8**: `boolean`

___

### bSupportsAgent9

• **bSupportsAgent9**: `boolean`

___

### bUseSnapHeight

• **bUseSnapHeight**: `boolean`

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
