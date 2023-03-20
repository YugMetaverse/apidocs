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

## Properties

### DisplayText

• **DisplayText**: `string`

___

### ObjectBindings

• **ObjectBindings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`VariantObjectBinding`](ue_ue.VariantObjectBinding.md)\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_Variant\_\_

• **\_\_tid\_Variant\_\_**: `boolean`

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

### GetActor

▸ **GetActor**(`ActorIndex`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActorIndex` | `number` |

#### Returns

[`Actor`](ue_ue.Actor.md)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetDisplayText

▸ **GetDisplayText**(): `string`

#### Returns

`string`

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetNumActors

▸ **GetNumActors**(): `number`

#### Returns

`number`

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

### SetDisplayText

▸ **SetDisplayText**(`NewDisplayText`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewDisplayText` | `string` |

#### Returns

`void`

___

### SwitchOn

▸ **SwitchOn**(): `void`

#### Returns

`void`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
