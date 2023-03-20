[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PartyReservation

# Class: PartyReservation

[ue/ue](../modules/ue_ue.md).PartyReservation

## Table of contents

### Constructors

- [constructor](ue_ue.PartyReservation.md#constructor)

### Properties

- [PartyLeader](ue_ue.PartyReservation.md#partyleader)
- [PartyMembers](ue_ue.PartyReservation.md#partymembers)
- [RemovedPartyMembers](ue_ue.PartyReservation.md#removedpartymembers)
- [TeamNum](ue_ue.PartyReservation.md#teamnum)
- [\_\_tid\_PartyReservation\_\_](ue_ue.PartyReservation.md#__tid_partyreservation__)

### Methods

- [StaticClass](ue_ue.PartyReservation.md#staticclass)
- [StaticStruct](ue_ue.PartyReservation.md#staticstruct)

## Constructors

### constructor

• **new PartyReservation**()

• **new PartyReservation**(`TeamNum`, `PartyLeader`, `PartyMembers`, `RemovedPartyMembers`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `TeamNum` | `number` |
| `PartyLeader` | [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md) |
| `PartyMembers` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PlayerReservation`](ue_ue.PlayerReservation.md)\> |
| `RemovedPartyMembers` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PlayerReservation`](ue_ue.PlayerReservation.md)\> |

## Properties

### PartyLeader

• **PartyLeader**: [`UniqueNetIdRepl`](ue_ue.UniqueNetIdRepl.md)

___

### PartyMembers

• **PartyMembers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PlayerReservation`](ue_ue.PlayerReservation.md)\>

___

### RemovedPartyMembers

• **RemovedPartyMembers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PlayerReservation`](ue_ue.PlayerReservation.md)\>

___

### TeamNum

• **TeamNum**: `number`

___

### \_\_tid\_PartyReservation\_\_

• `Private` **\_\_tid\_PartyReservation\_\_**: `boolean`

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
