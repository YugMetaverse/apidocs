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

## Properties

### Category

• **Category**: `string`

___

### DefaultValue

• **DefaultValue**: `string`

___

### FriendlyName

• **FriendlyName**: `string`

___

### MetaDataArray

• **MetaDataArray**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`BPVariableMetaDataEntry`](ue_ue.BPVariableMetaDataEntry.md)\>

___

### PropertyFlags

• **PropertyFlags**: `bigint`

___

### RepNotifyFunc

• **RepNotifyFunc**: `string`

___

### ReplicationCondition

• **ReplicationCondition**: [`ELifetimeCondition`](../enums/ue_ue.ELifetimeCondition.md)

___

### VarGuid

• **VarGuid**: [`Guid`](ue_ue_s.Guid.md)

___

### VarName

• **VarName**: `string`

___

### VarType

• **VarType**: [`EdGraphPinType`](ue_ue.EdGraphPinType.md)

___

### \_\_tid\_BPVariableDescription\_\_

• `Private` **\_\_tid\_BPVariableDescription\_\_**: `boolean`

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
