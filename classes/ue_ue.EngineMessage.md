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

#### Defined in

[ue/ue.d.ts:34155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34155)

## Properties

### EnteredMessage

• **EnteredMessage**: `string`

#### Defined in

[ue/ue.d.ts:34158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34158)

___

### FailedPlaceMessage

• **FailedPlaceMessage**: `string`

#### Defined in

[ue/ue.d.ts:34156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34156)

___

### GlobalNameChange

• **GlobalNameChange**: `string`

#### Defined in

[ue/ue.d.ts:34160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34160)

___

### LeftMessage

• **LeftMessage**: `string`

#### Defined in

[ue/ue.d.ts:34159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34159)

___

### MaxedOutMessage

• **MaxedOutMessage**: `string`

#### Defined in

[ue/ue.d.ts:34157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34157)

___

### NewPlayerMessage

• **NewPlayerMessage**: `string`

#### Defined in

[ue/ue.d.ts:34162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34162)

___

### NewSpecMessage

• **NewSpecMessage**: `string`

#### Defined in

[ue/ue.d.ts:34163](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34163)

___

### SpecEnteredMessage

• **SpecEnteredMessage**: `string`

#### Defined in

[ue/ue.d.ts:34161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34161)

___

### \_\_tid\_EngineMessage\_\_

• **\_\_tid\_EngineMessage\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:34168](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34168)

___

### \_\_tid\_LocalMessage\_\_

• **\_\_tid\_LocalMessage\_\_**: `boolean`

#### Inherited from

[LocalMessage](ue_ue.LocalMessage.md).[__tid_LocalMessage__](ue_ue.LocalMessage.md#__tid_localmessage__)

#### Defined in

[ue/ue.d.ts:34151](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34151)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[LocalMessage](ue_ue.LocalMessage.md).[__tid_Object__](ue_ue.LocalMessage.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

[LocalMessage](ue_ue.LocalMessage.md).[ExecuteUbergraph](ue_ue.LocalMessage.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[LocalMessage](ue_ue.LocalMessage.md).[GetClass](ue_ue.LocalMessage.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[LocalMessage](ue_ue.LocalMessage.md).[GetName](ue_ue.LocalMessage.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[LocalMessage](ue_ue.LocalMessage.md).[GetOuter](ue_ue.LocalMessage.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[LocalMessage](ue_ue.LocalMessage.md).[GetWorld](ue_ue.LocalMessage.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:34165](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34165)

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

#### Defined in

[ue/ue.d.ts:34166](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34166)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[LocalMessage](ue_ue.LocalMessage.md).[StaticClass](ue_ue.LocalMessage.md#staticclass)

#### Defined in

[ue/ue.d.ts:34164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L34164)
