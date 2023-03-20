[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / BPVariableDescription

# Class: BPVariableDescription

[ue/ue](../modules/ue_ue.md).BPVariableDescription

## Table of contents

### Constructors

- [constructor](ue_ue.BPVariableDescription.md#constructor)

### Properties

- [Category](ue_ue.BPVariableDescription.md#category)
- [DefaultValue](ue_ue.BPVariableDescription.md#defaultvalue)
- [FriendlyName](ue_ue.BPVariableDescription.md#friendlyname)
- [MetaDataArray](ue_ue.BPVariableDescription.md#metadataarray)
- [PropertyFlags](ue_ue.BPVariableDescription.md#propertyflags)
- [RepNotifyFunc](ue_ue.BPVariableDescription.md#repnotifyfunc)
- [ReplicationCondition](ue_ue.BPVariableDescription.md#replicationcondition)
- [VarGuid](ue_ue.BPVariableDescription.md#varguid)
- [VarName](ue_ue.BPVariableDescription.md#varname)
- [VarType](ue_ue.BPVariableDescription.md#vartype)
- [\_\_tid\_BPVariableDescription\_\_](ue_ue.BPVariableDescription.md#__tid_bpvariabledescription__)

### Methods

- [StaticClass](ue_ue.BPVariableDescription.md#staticclass)
- [StaticStruct](ue_ue.BPVariableDescription.md#staticstruct)

## Constructors

### constructor

• **new BPVariableDescription**()

#### Defined in

[ue/ue.d.ts:4360](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4360)

• **new BPVariableDescription**(`VarName`, `VarGuid`, `VarType`, `FriendlyName`, `Category`, `PropertyFlags`, `RepNotifyFunc`, `ReplicationCondition`, `MetaDataArray`, `DefaultValue`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `VarName` | `string` |
| `VarGuid` | [`Guid`](ue_ue_s.Guid.md) |
| `VarType` | [`EdGraphPinType`](ue_ue.EdGraphPinType.md) |
| `FriendlyName` | `string` |
| `Category` | `string` |
| `PropertyFlags` | `bigint` |
| `RepNotifyFunc` | `string` |
| `ReplicationCondition` | [`ELifetimeCondition`](../enums/ue_ue.ELifetimeCondition.md) |
| `MetaDataArray` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPVariableMetaDataEntry`](ue_ue.BPVariableMetaDataEntry.md)\> |
| `DefaultValue` | `string` |

#### Defined in

[ue/ue.d.ts:4361](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4361)

## Properties

### Category

• **Category**: `string`

#### Defined in

[ue/ue.d.ts:4366](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4366)

___

### DefaultValue

• **DefaultValue**: `string`

#### Defined in

[ue/ue.d.ts:4371](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4371)

___

### FriendlyName

• **FriendlyName**: `string`

#### Defined in

[ue/ue.d.ts:4365](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4365)

___

### MetaDataArray

• **MetaDataArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPVariableMetaDataEntry`](ue_ue.BPVariableMetaDataEntry.md)\>

#### Defined in

[ue/ue.d.ts:4370](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4370)

___

### PropertyFlags

• **PropertyFlags**: `bigint`

#### Defined in

[ue/ue.d.ts:4367](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4367)

___

### RepNotifyFunc

• **RepNotifyFunc**: `string`

#### Defined in

[ue/ue.d.ts:4368](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4368)

___

### ReplicationCondition

• **ReplicationCondition**: [`ELifetimeCondition`](../enums/ue_ue.ELifetimeCondition.md)

#### Defined in

[ue/ue.d.ts:4369](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4369)

___

### VarGuid

• **VarGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:4363](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4363)

___

### VarName

• **VarName**: `string`

#### Defined in

[ue/ue.d.ts:4362](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4362)

___

### VarType

• **VarType**: [`EdGraphPinType`](ue_ue.EdGraphPinType.md)

#### Defined in

[ue/ue.d.ts:4364](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4364)

___

### \_\_tid\_BPVariableDescription\_\_

• `Private` **\_\_tid\_BPVariableDescription\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:4377](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4377)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:4375](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4375)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:4376](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L4376)
