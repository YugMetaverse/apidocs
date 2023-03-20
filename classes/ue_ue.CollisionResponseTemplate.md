[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CollisionResponseTemplate

# Class: CollisionResponseTemplate

[ue/ue](../modules/ue_ue.md).CollisionResponseTemplate

## Table of contents

### Constructors

- [constructor](ue_ue.CollisionResponseTemplate.md#constructor)

### Properties

- [CollisionEnabled](ue_ue.CollisionResponseTemplate.md#collisionenabled)
- [CustomResponses](ue_ue.CollisionResponseTemplate.md#customresponses)
- [HelpMessage](ue_ue.CollisionResponseTemplate.md#helpmessage)
- [Name](ue_ue.CollisionResponseTemplate.md#name)
- [ObjectTypeName](ue_ue.CollisionResponseTemplate.md#objecttypename)
- [\_\_tid\_CollisionResponseTemplate\_\_](ue_ue.CollisionResponseTemplate.md#__tid_collisionresponsetemplate__)
- [bCanModify](ue_ue.CollisionResponseTemplate.md#bcanmodify)

### Methods

- [StaticClass](ue_ue.CollisionResponseTemplate.md#staticclass)
- [StaticStruct](ue_ue.CollisionResponseTemplate.md#staticstruct)

## Constructors

### constructor

• **new CollisionResponseTemplate**()

• **new CollisionResponseTemplate**(`Name`, `CollisionEnabled`, `bCanModify`, `ObjectTypeName`, `CustomResponses`, `HelpMessage`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Name` | `string` |
| `CollisionEnabled` | [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md) |
| `bCanModify` | `boolean` |
| `ObjectTypeName` | `string` |
| `CustomResponses` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ResponseChannel`](ue_ue.ResponseChannel.md)\> |
| `HelpMessage` | `string` |

## Properties

### CollisionEnabled

• **CollisionEnabled**: [`ECollisionEnabled`](../enums/ue_ue.ECollisionEnabled.md)

___

### CustomResponses

• **CustomResponses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ResponseChannel`](ue_ue.ResponseChannel.md)\>

___

### HelpMessage

• **HelpMessage**: `string`

___

### Name

• **Name**: `string`

___

### ObjectTypeName

• **ObjectTypeName**: `string`

___

### \_\_tid\_CollisionResponseTemplate\_\_

• `Private` **\_\_tid\_CollisionResponseTemplate\_\_**: `boolean`

___

### bCanModify

• **bCanModify**: `boolean`

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
