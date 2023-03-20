[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_CustomProperty

# Class: AnimNode\_CustomProperty

[ue/ue](../modules/ue_ue.md).AnimNode_CustomProperty

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_CustomProperty`**

  ↳↳ [`AnimNode_LinkedAnimGraph`](ue_ue.AnimNode_LinkedAnimGraph.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_CustomProperty.md#constructor)

### Properties

- [DestProperties](ue_ue.AnimNode_CustomProperty.md#destproperties)
- [DestPropertyNames](ue_ue.AnimNode_CustomProperty.md#destpropertynames)
- [SourceProperties](ue_ue.AnimNode_CustomProperty.md#sourceproperties)
- [SourcePropertyNames](ue_ue.AnimNode_CustomProperty.md#sourcepropertynames)
- [TargetInstance](ue_ue.AnimNode_CustomProperty.md#targetinstance)
- [\_\_tid\_AnimNode\_CustomProperty\_\_](ue_ue.AnimNode_CustomProperty.md#__tid_animnode_customproperty__)

### Methods

- [StaticClass](ue_ue.AnimNode_CustomProperty.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_CustomProperty.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_CustomProperty**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

• **new AnimNode_CustomProperty**(`SourcePropertyNames`, `DestPropertyNames`, `TargetInstance`, `SourceProperties`, `DestProperties`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourcePropertyNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `DestPropertyNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `TargetInstance` | [`Object`](ue_ue.Object.md) |
| `SourceProperties` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Property`](ue_ue.Property.md)\> |
| `DestProperties` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Property`](ue_ue.Property.md)\> |

#### Overrides

UE.AnimNode\_Base.constructor

## Properties

### DestProperties

• **DestProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Property`](ue_ue.Property.md)\>

___

### DestPropertyNames

• **DestPropertyNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### SourceProperties

• **SourceProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Property`](ue_ue.Property.md)\>

___

### SourcePropertyNames

• **SourcePropertyNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### TargetInstance

• **TargetInstance**: [`Object`](ue_ue.Object.md)

___

### \_\_tid\_AnimNode\_CustomProperty\_\_

• `Private` **\_\_tid\_AnimNode\_CustomProperty\_\_**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticClass](ue_ue.AnimNode_Base.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[StaticStruct](ue_ue.AnimNode_Base.md#staticstruct)
