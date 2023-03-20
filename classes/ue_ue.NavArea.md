[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NavArea

# Class: NavArea

[ue/ue](../modules/ue_ue.md).NavArea

## Hierarchy

- [`NavAreaBase`](ue_ue.NavAreaBase.md)

  ↳ **`NavArea`**

  ↳↳ [`NavArea_Default`](ue_ue.NavArea_Default.md)

  ↳↳ [`NavArea_LowHeight`](ue_ue.NavArea_LowHeight.md)

  ↳↳ [`NavArea_Null`](ue_ue.NavArea_Null.md)

  ↳↳ [`NavArea_Obstacle`](ue_ue.NavArea_Obstacle.md)

  ↳↳ [`NavAreaMeta`](ue_ue.NavAreaMeta.md)

## Table of contents

### Constructors

- [constructor](ue_ue.NavArea.md#constructor)

### Properties

- [DefaultCost](ue_ue.NavArea.md#defaultcost)
- [DrawColor](ue_ue.NavArea.md#drawcolor)
- [FixedAreaEnteringCost](ue_ue.NavArea.md#fixedareaenteringcost)
- [SupportedAgents](ue_ue.NavArea.md#supportedagents)
- [\_\_tid\_NavAreaBase\_\_](ue_ue.NavArea.md#__tid_navareabase__)
- [\_\_tid\_NavArea\_\_](ue_ue.NavArea.md#__tid_navarea__)
- [\_\_tid\_Object\_\_](ue_ue.NavArea.md#__tid_object__)
- [bSupportsAgent0](ue_ue.NavArea.md#bsupportsagent0)
- [bSupportsAgent1](ue_ue.NavArea.md#bsupportsagent1)
- [bSupportsAgent10](ue_ue.NavArea.md#bsupportsagent10)
- [bSupportsAgent11](ue_ue.NavArea.md#bsupportsagent11)
- [bSupportsAgent12](ue_ue.NavArea.md#bsupportsagent12)
- [bSupportsAgent13](ue_ue.NavArea.md#bsupportsagent13)
- [bSupportsAgent14](ue_ue.NavArea.md#bsupportsagent14)
- [bSupportsAgent15](ue_ue.NavArea.md#bsupportsagent15)
- [bSupportsAgent2](ue_ue.NavArea.md#bsupportsagent2)
- [bSupportsAgent3](ue_ue.NavArea.md#bsupportsagent3)
- [bSupportsAgent4](ue_ue.NavArea.md#bsupportsagent4)
- [bSupportsAgent5](ue_ue.NavArea.md#bsupportsagent5)
- [bSupportsAgent6](ue_ue.NavArea.md#bsupportsagent6)
- [bSupportsAgent7](ue_ue.NavArea.md#bsupportsagent7)
- [bSupportsAgent8](ue_ue.NavArea.md#bsupportsagent8)
- [bSupportsAgent9](ue_ue.NavArea.md#bsupportsagent9)

### Methods

- [CreateDefaultSubobject](ue_ue.NavArea.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.NavArea.md#executeubergraph)
- [GetClass](ue_ue.NavArea.md#getclass)
- [GetName](ue_ue.NavArea.md#getname)
- [GetOuter](ue_ue.NavArea.md#getouter)
- [GetWorld](ue_ue.NavArea.md#getworld)
- [Find](ue_ue.NavArea.md#find)
- [Load](ue_ue.NavArea.md#load)
- [StaticClass](ue_ue.NavArea.md#staticclass)

## Constructors

### constructor

• **new NavArea**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[NavAreaBase](ue_ue.NavAreaBase.md).[constructor](ue_ue.NavAreaBase.md#constructor)

#### Defined in

[ue/ue.d.ts:52761](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52761)

## Properties

### DefaultCost

• **DefaultCost**: `number`

#### Defined in

[ue/ue.d.ts:52762](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52762)

___

### DrawColor

• **DrawColor**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:52764](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52764)

___

### FixedAreaEnteringCost

• **FixedAreaEnteringCost**: `number`

#### Defined in

[ue/ue.d.ts:52763](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52763)

___

### SupportedAgents

• **SupportedAgents**: [`NavAgentSelector`](ue_ue.NavAgentSelector.md)

#### Defined in

[ue/ue.d.ts:52765](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52765)

___

### \_\_tid\_NavAreaBase\_\_

• **\_\_tid\_NavAreaBase\_\_**: `boolean`

#### Inherited from

[NavAreaBase](ue_ue.NavAreaBase.md).[__tid_NavAreaBase__](ue_ue.NavAreaBase.md#__tid_navareabase__)

#### Defined in

[ue/ue.d.ts:52757](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52757)

___

### \_\_tid\_NavArea\_\_

• **\_\_tid\_NavArea\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:52786](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52786)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[NavAreaBase](ue_ue.NavAreaBase.md).[__tid_Object__](ue_ue.NavAreaBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bSupportsAgent0

• **bSupportsAgent0**: `boolean`

#### Defined in

[ue/ue.d.ts:52766](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52766)

___

### bSupportsAgent1

• **bSupportsAgent1**: `boolean`

#### Defined in

[ue/ue.d.ts:52767](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52767)

___

### bSupportsAgent10

• **bSupportsAgent10**: `boolean`

#### Defined in

[ue/ue.d.ts:52776](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52776)

___

### bSupportsAgent11

• **bSupportsAgent11**: `boolean`

#### Defined in

[ue/ue.d.ts:52777](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52777)

___

### bSupportsAgent12

• **bSupportsAgent12**: `boolean`

#### Defined in

[ue/ue.d.ts:52778](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52778)

___

### bSupportsAgent13

• **bSupportsAgent13**: `boolean`

#### Defined in

[ue/ue.d.ts:52779](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52779)

___

### bSupportsAgent14

• **bSupportsAgent14**: `boolean`

#### Defined in

[ue/ue.d.ts:52780](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52780)

___

### bSupportsAgent15

• **bSupportsAgent15**: `boolean`

#### Defined in

[ue/ue.d.ts:52781](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52781)

___

### bSupportsAgent2

• **bSupportsAgent2**: `boolean`

#### Defined in

[ue/ue.d.ts:52768](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52768)

___

### bSupportsAgent3

• **bSupportsAgent3**: `boolean`

#### Defined in

[ue/ue.d.ts:52769](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52769)

___

### bSupportsAgent4

• **bSupportsAgent4**: `boolean`

#### Defined in

[ue/ue.d.ts:52770](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52770)

___

### bSupportsAgent5

• **bSupportsAgent5**: `boolean`

#### Defined in

[ue/ue.d.ts:52771](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52771)

___

### bSupportsAgent6

• **bSupportsAgent6**: `boolean`

#### Defined in

[ue/ue.d.ts:52772](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52772)

___

### bSupportsAgent7

• **bSupportsAgent7**: `boolean`

#### Defined in

[ue/ue.d.ts:52773](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52773)

___

### bSupportsAgent8

• **bSupportsAgent8**: `boolean`

#### Defined in

[ue/ue.d.ts:52774](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52774)

___

### bSupportsAgent9

• **bSupportsAgent9**: `boolean`

#### Defined in

[ue/ue.d.ts:52775](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52775)

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

[NavAreaBase](ue_ue.NavAreaBase.md).[CreateDefaultSubobject](ue_ue.NavAreaBase.md#createdefaultsubobject)

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

[NavAreaBase](ue_ue.NavAreaBase.md).[ExecuteUbergraph](ue_ue.NavAreaBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[NavAreaBase](ue_ue.NavAreaBase.md).[GetClass](ue_ue.NavAreaBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[NavAreaBase](ue_ue.NavAreaBase.md).[GetName](ue_ue.NavAreaBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[NavAreaBase](ue_ue.NavAreaBase.md).[GetOuter](ue_ue.NavAreaBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[NavAreaBase](ue_ue.NavAreaBase.md).[GetWorld](ue_ue.NavAreaBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NavArea`](ue_ue.NavArea.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NavArea`](ue_ue.NavArea.md)

#### Overrides

[NavAreaBase](ue_ue.NavAreaBase.md).[Find](ue_ue.NavAreaBase.md#find)

#### Defined in

[ue/ue.d.ts:52783](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52783)

___

### Load

▸ `Static` **Load**(`InName`): [`NavArea`](ue_ue.NavArea.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NavArea`](ue_ue.NavArea.md)

#### Overrides

[NavAreaBase](ue_ue.NavAreaBase.md).[Load](ue_ue.NavAreaBase.md#load)

#### Defined in

[ue/ue.d.ts:52784](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52784)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[NavAreaBase](ue_ue.NavAreaBase.md).[StaticClass](ue_ue.NavAreaBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:52782](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52782)
