[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AIDamageEvent

# Class: AIDamageEvent

[ue/ue](../modules/ue_ue.md).AIDamageEvent

## Table of contents

### Constructors

- [constructor](ue_ue.AIDamageEvent.md#constructor)

### Properties

- [Amount](ue_ue.AIDamageEvent.md#amount)
- [DamagedActor](ue_ue.AIDamageEvent.md#damagedactor)
- [HitLocation](ue_ue.AIDamageEvent.md#hitlocation)
- [Instigator](ue_ue.AIDamageEvent.md#instigator)
- [Location](ue_ue.AIDamageEvent.md#location)
- [\_\_tid\_AIDamageEvent\_\_](ue_ue.AIDamageEvent.md#__tid_aidamageevent__)

### Methods

- [StaticClass](ue_ue.AIDamageEvent.md#staticclass)
- [StaticStruct](ue_ue.AIDamageEvent.md#staticstruct)

## Constructors

### constructor

• **new AIDamageEvent**()

• **new AIDamageEvent**(`Amount`, `Location`, `HitLocation`, `DamagedActor`, `Instigator`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Amount` | `number` |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `HitLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `DamagedActor` | [`Actor`](ue_ue.Actor.md) |
| `Instigator` | [`Actor`](ue_ue.Actor.md) |

## Properties

### Amount

• **Amount**: `number`

___

### DamagedActor

• **DamagedActor**: [`Actor`](ue_ue.Actor.md)

___

### HitLocation

• **HitLocation**: [`Vector`](ue_ue_s.Vector.md)

___

### Instigator

• **Instigator**: [`Actor`](ue_ue.Actor.md)

___

### Location

• **Location**: [`Vector`](ue_ue_s.Vector.md)

___

### \_\_tid\_AIDamageEvent\_\_

• `Private` **\_\_tid\_AIDamageEvent\_\_**: `boolean`

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
