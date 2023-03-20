[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / NavAgentInterface

# Class: NavAgentInterface

[ue/ue](../modules/ue_ue.md).NavAgentInterface

## Hierarchy

- [`Interface`](ue_ue.Interface.md)

  ↳ **`NavAgentInterface`**

## Table of contents

### Constructors

- [constructor](ue_ue.NavAgentInterface.md#constructor)

### Properties

- [\_\_tid\_Interface\_\_](ue_ue.NavAgentInterface.md#__tid_interface__)
- [\_\_tid\_NavAgentInterface\_\_](ue_ue.NavAgentInterface.md#__tid_navagentinterface__)
- [\_\_tid\_Object\_\_](ue_ue.NavAgentInterface.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.NavAgentInterface.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.NavAgentInterface.md#executeubergraph)
- [GetClass](ue_ue.NavAgentInterface.md#getclass)
- [GetName](ue_ue.NavAgentInterface.md#getname)
- [GetOuter](ue_ue.NavAgentInterface.md#getouter)
- [GetWorld](ue_ue.NavAgentInterface.md#getworld)
- [Find](ue_ue.NavAgentInterface.md#find)
- [Load](ue_ue.NavAgentInterface.md#load)
- [StaticClass](ue_ue.NavAgentInterface.md#staticclass)

## Constructors

### constructor

• **new NavAgentInterface**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Interface](ue_ue.Interface.md).[constructor](ue_ue.Interface.md#constructor)

#### Defined in

[ue/ue.d.ts:52743](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52743)

## Properties

### \_\_tid\_Interface\_\_

• **\_\_tid\_Interface\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Interface__](ue_ue.Interface.md#__tid_interface__)

#### Defined in

[ue/ue.d.ts:8142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8142)

___

### \_\_tid\_NavAgentInterface\_\_

• **\_\_tid\_NavAgentInterface\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:52748](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52748)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Interface](ue_ue.Interface.md).[__tid_Object__](ue_ue.Interface.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

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

[Interface](ue_ue.Interface.md).[CreateDefaultSubobject](ue_ue.Interface.md#createdefaultsubobject)

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

[Interface](ue_ue.Interface.md).[ExecuteUbergraph](ue_ue.Interface.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetClass](ue_ue.Interface.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Interface](ue_ue.Interface.md).[GetName](ue_ue.Interface.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetOuter](ue_ue.Interface.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Interface](ue_ue.Interface.md).[GetWorld](ue_ue.Interface.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`NavAgentInterface`](ue_ue.NavAgentInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`NavAgentInterface`](ue_ue.NavAgentInterface.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Find](ue_ue.Interface.md#find)

#### Defined in

[ue/ue.d.ts:52745](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52745)

___

### Load

▸ `Static` **Load**(`InName`): [`NavAgentInterface`](ue_ue.NavAgentInterface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`NavAgentInterface`](ue_ue.NavAgentInterface.md)

#### Overrides

[Interface](ue_ue.Interface.md).[Load](ue_ue.Interface.md#load)

#### Defined in

[ue/ue.d.ts:52746](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52746)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Interface](ue_ue.Interface.md).[StaticClass](ue_ue.Interface.md#staticclass)

#### Defined in

[ue/ue.d.ts:52744](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L52744)
