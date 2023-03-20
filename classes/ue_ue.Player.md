[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Player

# Class: Player

[ue/ue](../modules/ue_ue.md).Player

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`Player`**

  ↳↳ [`LocalPlayer`](ue_ue.LocalPlayer.md)

  ↳↳ [`NetConnection`](ue_ue.NetConnection.md)

## Table of contents

### Constructors

- [constructor](ue_ue.Player.md#constructor)

### Properties

- [ConfiguredInternetSpeed](ue_ue.Player.md#configuredinternetspeed)
- [ConfiguredLanSpeed](ue_ue.Player.md#configuredlanspeed)
- [CurrentNetSpeed](ue_ue.Player.md#currentnetspeed)
- [PlayerController](ue_ue.Player.md#playercontroller)
- [\_\_tid\_Object\_\_](ue_ue.Player.md#__tid_object__)
- [\_\_tid\_Player\_\_](ue_ue.Player.md#__tid_player__)

### Methods

- [CreateDefaultSubobject](ue_ue.Player.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Player.md#executeubergraph)
- [GetClass](ue_ue.Player.md#getclass)
- [GetName](ue_ue.Player.md#getname)
- [GetOuter](ue_ue.Player.md#getouter)
- [GetWorld](ue_ue.Player.md#getworld)
- [Find](ue_ue.Player.md#find)
- [Load](ue_ue.Player.md#load)
- [StaticClass](ue_ue.Player.md#staticclass)

## Constructors

### constructor

• **new Player**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:6038](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6038)

## Properties

### ConfiguredInternetSpeed

• **ConfiguredInternetSpeed**: `number`

#### Defined in

[ue/ue.d.ts:6041](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6041)

___

### ConfiguredLanSpeed

• **ConfiguredLanSpeed**: `number`

#### Defined in

[ue/ue.d.ts:6042](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6042)

___

### CurrentNetSpeed

• **CurrentNetSpeed**: `number`

#### Defined in

[ue/ue.d.ts:6040](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6040)

___

### PlayerController

• **PlayerController**: [`PlayerController`](ue_ue.PlayerController.md)

#### Defined in

[ue/ue.d.ts:6039](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6039)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_Player\_\_

• **\_\_tid\_Player\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:6047](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6047)

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Player`](ue_ue.Player.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Player`](ue_ue.Player.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:6044](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6044)

___

### Load

▸ `Static` **Load**(`InName`): [`Player`](ue_ue.Player.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Player`](ue_ue.Player.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:6045](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6045)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:6043](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6043)
