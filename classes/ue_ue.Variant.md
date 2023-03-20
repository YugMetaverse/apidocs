[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / Variant

# Class: Variant

[ue/ue](../modules/ue_ue.md).Variant

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`Variant`**

## Table of contents

### Constructors

- [constructor](ue_ue.Variant.md#constructor)

### Properties

- [DisplayText](ue_ue.Variant.md#displaytext)
- [ObjectBindings](ue_ue.Variant.md#objectbindings)
- [\_\_tid\_Object\_\_](ue_ue.Variant.md#__tid_object__)
- [\_\_tid\_Variant\_\_](ue_ue.Variant.md#__tid_variant__)

### Methods

- [CreateDefaultSubobject](ue_ue.Variant.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.Variant.md#executeubergraph)
- [GetActor](ue_ue.Variant.md#getactor)
- [GetClass](ue_ue.Variant.md#getclass)
- [GetDisplayText](ue_ue.Variant.md#getdisplaytext)
- [GetName](ue_ue.Variant.md#getname)
- [GetNumActors](ue_ue.Variant.md#getnumactors)
- [GetOuter](ue_ue.Variant.md#getouter)
- [GetWorld](ue_ue.Variant.md#getworld)
- [SetDisplayText](ue_ue.Variant.md#setdisplaytext)
- [SwitchOn](ue_ue.Variant.md#switchon)
- [Find](ue_ue.Variant.md#find)
- [Load](ue_ue.Variant.md#load)
- [StaticClass](ue_ue.Variant.md#staticclass)

## Constructors

### constructor

• **new Variant**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:29903](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29903)

## Properties

### DisplayText

• **DisplayText**: `string`

#### Defined in

[ue/ue.d.ts:29904](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29904)

___

### ObjectBindings

• **ObjectBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VariantObjectBinding`](ue_ue.VariantObjectBinding.md)\>

#### Defined in

[ue/ue.d.ts:29905](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29905)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_Variant\_\_

• **\_\_tid\_Variant\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:29915](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29915)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetActor

▸ **GetActor**(`ActorIndex`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActorIndex` | `number` |

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:29906](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29906)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetDisplayText

▸ **GetDisplayText**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:29907](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29907)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetNumActors

▸ **GetNumActors**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:29908](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29908)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### SetDisplayText

▸ **SetDisplayText**(`NewDisplayText`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewDisplayText` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:29909](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29909)

___

### SwitchOn

▸ **SwitchOn**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:29910](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29910)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`Variant`](ue_ue.Variant.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`Variant`](ue_ue.Variant.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:29912](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29912)

___

### Load

▸ `Static` **Load**(`InName`): [`Variant`](ue_ue.Variant.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`Variant`](ue_ue.Variant.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:29913](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29913)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:29911](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L29911)
