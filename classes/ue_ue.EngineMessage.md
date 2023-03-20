[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / EngineMessage

# Class: EngineMessage

[ue/ue](../modules/ue_ue.md).EngineMessage

## Hierarchy

- [`LocalMessage`](ue_ue.LocalMessage.md)

  ↳ **`EngineMessage`**

## Table of contents

### Constructors

- [constructor](ue_ue.EngineMessage.md#constructor)

### Properties

- [EnteredMessage](ue_ue.EngineMessage.md#enteredmessage)
- [FailedPlaceMessage](ue_ue.EngineMessage.md#failedplacemessage)
- [GlobalNameChange](ue_ue.EngineMessage.md#globalnamechange)
- [LeftMessage](ue_ue.EngineMessage.md#leftmessage)
- [MaxedOutMessage](ue_ue.EngineMessage.md#maxedoutmessage)
- [NewPlayerMessage](ue_ue.EngineMessage.md#newplayermessage)
- [NewSpecMessage](ue_ue.EngineMessage.md#newspecmessage)
- [SpecEnteredMessage](ue_ue.EngineMessage.md#specenteredmessage)
- [\_\_tid\_EngineMessage\_\_](ue_ue.EngineMessage.md#__tid_enginemessage__)
- [\_\_tid\_LocalMessage\_\_](ue_ue.EngineMessage.md#__tid_localmessage__)
- [\_\_tid\_Object\_\_](ue_ue.EngineMessage.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.EngineMessage.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.EngineMessage.md#executeubergraph)
- [GetClass](ue_ue.EngineMessage.md#getclass)
- [GetName](ue_ue.EngineMessage.md#getname)
- [GetOuter](ue_ue.EngineMessage.md#getouter)
- [GetWorld](ue_ue.EngineMessage.md#getworld)
- [Find](ue_ue.EngineMessage.md#find)
- [Load](ue_ue.EngineMessage.md#load)
- [StaticClass](ue_ue.EngineMessage.md#staticclass)

## Constructors

### constructor

• **new EngineMessage**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[LocalMessage](ue_ue.LocalMessage.md).[constructor](ue_ue.LocalMessage.md#constructor)

## Properties

### EnteredMessage

• **EnteredMessage**: `string`

___

### FailedPlaceMessage

• **FailedPlaceMessage**: `string`

___

### GlobalNameChange

• **GlobalNameChange**: `string`

___

### LeftMessage

• **LeftMessage**: `string`

___

### MaxedOutMessage

• **MaxedOutMessage**: `string`

___

### NewPlayerMessage

• **NewPlayerMessage**: `string`

___

### NewSpecMessage

• **NewSpecMessage**: `string`

___

### SpecEnteredMessage

• **SpecEnteredMessage**: `string`

___

### \_\_tid\_EngineMessage\_\_

• **\_\_tid\_EngineMessage\_\_**: `boolean`

___

### \_\_tid\_LocalMessage\_\_

• **\_\_tid\_LocalMessage\_\_**: `boolean`

#### Inherited from

[LocalMessage](ue_ue.LocalMessage.md).[__tid_LocalMessage__](ue_ue.LocalMessage.md#__tid_localmessage__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[LocalMessage](ue_ue.LocalMessage.md).[__tid_Object__](ue_ue.LocalMessage.md#__tid_object__)

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

[LocalMessage](ue_ue.LocalMessage.md).[CreateDefaultSubobject](ue_ue.LocalMessage.md#createdefaultsubobject)

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

[LocalMessage](ue_ue.LocalMessage.md).[ExecuteUbergraph](ue_ue.LocalMessage.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[LocalMessage](ue_ue.LocalMessage.md).[GetClass](ue_ue.LocalMessage.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[LocalMessage](ue_ue.LocalMessage.md).[GetName](ue_ue.LocalMessage.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[LocalMessage](ue_ue.LocalMessage.md).[GetOuter](ue_ue.LocalMessage.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[LocalMessage](ue_ue.LocalMessage.md).[GetWorld](ue_ue.LocalMessage.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`EngineMessage`](ue_ue.EngineMessage.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`EngineMessage`](ue_ue.EngineMessage.md)

#### Overrides

[LocalMessage](ue_ue.LocalMessage.md).[Find](ue_ue.LocalMessage.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`EngineMessage`](ue_ue.EngineMessage.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`EngineMessage`](ue_ue.EngineMessage.md)

#### Overrides

[LocalMessage](ue_ue.LocalMessage.md).[Load](ue_ue.LocalMessage.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[LocalMessage](ue_ue.LocalMessage.md).[StaticClass](ue_ue.LocalMessage.md#staticclass)
