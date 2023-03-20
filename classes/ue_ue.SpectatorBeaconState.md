[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SpectatorBeaconState

# Class: SpectatorBeaconState

[ue/ue](../modules/ue_ue.md).SpectatorBeaconState

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SpectatorBeaconState`**

## Table of contents

### Constructors

- [constructor](ue_ue.SpectatorBeaconState.md#constructor)

### Properties

- [MaxReservations](ue_ue.SpectatorBeaconState.md#maxreservations)
- [NumConsumedReservations](ue_ue.SpectatorBeaconState.md#numconsumedreservations)
- [Reservations](ue_ue.SpectatorBeaconState.md#reservations)
- [SessionName](ue_ue.SpectatorBeaconState.md#sessionname)
- [\_\_tid\_Object\_\_](ue_ue.SpectatorBeaconState.md#__tid_object__)
- [\_\_tid\_SpectatorBeaconState\_\_](ue_ue.SpectatorBeaconState.md#__tid_spectatorbeaconstate__)
- [bRestrictCrossConsole](ue_ue.SpectatorBeaconState.md#brestrictcrossconsole)

### Methods

- [CreateDefaultSubobject](ue_ue.SpectatorBeaconState.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SpectatorBeaconState.md#executeubergraph)
- [GetClass](ue_ue.SpectatorBeaconState.md#getclass)
- [GetName](ue_ue.SpectatorBeaconState.md#getname)
- [GetOuter](ue_ue.SpectatorBeaconState.md#getouter)
- [GetWorld](ue_ue.SpectatorBeaconState.md#getworld)
- [Find](ue_ue.SpectatorBeaconState.md#find)
- [Load](ue_ue.SpectatorBeaconState.md#load)
- [StaticClass](ue_ue.SpectatorBeaconState.md#staticclass)

## Constructors

### constructor

• **new SpectatorBeaconState**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### MaxReservations

• **MaxReservations**: `number`

___

### NumConsumedReservations

• **NumConsumedReservations**: `number`

___

### Reservations

• **Reservations**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SpectatorReservation`](ue_ue.SpectatorReservation.md)\>

___

### SessionName

• **SessionName**: `string`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_SpectatorBeaconState\_\_

• **\_\_tid\_SpectatorBeaconState\_\_**: `boolean`

___

### bRestrictCrossConsole

• **bRestrictCrossConsole**: `boolean`

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SpectatorBeaconState`](ue_ue.SpectatorBeaconState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SpectatorBeaconState`](ue_ue.SpectatorBeaconState.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SpectatorBeaconState`](ue_ue.SpectatorBeaconState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SpectatorBeaconState`](ue_ue.SpectatorBeaconState.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
