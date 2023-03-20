[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GameSessionSettings

# Class: GameSessionSettings

[ue/ue](../modules/ue_ue.md).GameSessionSettings

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`GameSessionSettings`**

## Table of contents

### Constructors

- [constructor](ue_ue.GameSessionSettings.md#constructor)

### Properties

- [MaxPlayers](ue_ue.GameSessionSettings.md#maxplayers)
- [MaxSpectators](ue_ue.GameSessionSettings.md#maxspectators)
- [\_\_tid\_GameSessionSettings\_\_](ue_ue.GameSessionSettings.md#__tid_gamesessionsettings__)
- [\_\_tid\_Object\_\_](ue_ue.GameSessionSettings.md#__tid_object__)
- [bRequiresPushToTalk](ue_ue.GameSessionSettings.md#brequirespushtotalk)

### Methods

- [CreateDefaultSubobject](ue_ue.GameSessionSettings.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GameSessionSettings.md#executeubergraph)
- [GetClass](ue_ue.GameSessionSettings.md#getclass)
- [GetName](ue_ue.GameSessionSettings.md#getname)
- [GetOuter](ue_ue.GameSessionSettings.md#getouter)
- [GetWorld](ue_ue.GameSessionSettings.md#getworld)
- [Find](ue_ue.GameSessionSettings.md#find)
- [Load](ue_ue.GameSessionSettings.md#load)
- [StaticClass](ue_ue.GameSessionSettings.md#staticclass)

## Constructors

### constructor

• **new GameSessionSettings**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### MaxPlayers

• **MaxPlayers**: `number`

___

### MaxSpectators

• **MaxSpectators**: `number`

___

### \_\_tid\_GameSessionSettings\_\_

• **\_\_tid\_GameSessionSettings\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bRequiresPushToTalk

• **bRequiresPushToTalk**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GameSessionSettings`](ue_ue.GameSessionSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GameSessionSettings`](ue_ue.GameSessionSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`GameSessionSettings`](ue_ue.GameSessionSettings.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GameSessionSettings`](ue_ue.GameSessionSettings.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
