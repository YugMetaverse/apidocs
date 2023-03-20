[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_LinkedAnimGraph

# Class: AnimNode\_LinkedAnimGraph

[ue/ue](../modules/ue_ue.md).AnimNode_LinkedAnimGraph

## Hierarchy

- [`AnimNode_CustomProperty`](ue_ue.AnimNode_CustomProperty.md)

  ↳ **`AnimNode_LinkedAnimGraph`**

  ↳↳ [`AnimNode_LinkedAnimLayer`](ue_ue.AnimNode_LinkedAnimLayer.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_LinkedAnimGraph.md#constructor)

### Properties

- [DestProperties](ue_ue.AnimNode_LinkedAnimGraph.md#destproperties)
- [DestPropertyNames](ue_ue.AnimNode_LinkedAnimGraph.md#destpropertynames)
- [InputPoseNames](ue_ue.AnimNode_LinkedAnimGraph.md#inputposenames)
- [InputPoses](ue_ue.AnimNode_LinkedAnimGraph.md#inputposes)
- [InstanceClass](ue_ue.AnimNode_LinkedAnimGraph.md#instanceclass)
- [SourceProperties](ue_ue.AnimNode_LinkedAnimGraph.md#sourceproperties)
- [SourcePropertyNames](ue_ue.AnimNode_LinkedAnimGraph.md#sourcepropertynames)
- [Tag](ue_ue.AnimNode_LinkedAnimGraph.md#tag)
- [TargetInstance](ue_ue.AnimNode_LinkedAnimGraph.md#targetinstance)
- [\_\_tid\_AnimNode\_LinkedAnimGraph\_\_](ue_ue.AnimNode_LinkedAnimGraph.md#__tid_animnode_linkedanimgraph__)

### Methods

- [StaticClass](ue_ue.AnimNode_LinkedAnimGraph.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_LinkedAnimGraph.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_LinkedAnimGraph**()

#### Overrides

[AnimNode_CustomProperty](ue_ue.AnimNode_CustomProperty.md).[constructor](ue_ue.AnimNode_CustomProperty.md#constructor)

• **new AnimNode_LinkedAnimGraph**(`InputPoses`, `InputPoseNames`, `InstanceClass`, `Tag`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InputPoses` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseLink`](ue_ue.PoseLink.md)\> |
| `InputPoseNames` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `InstanceClass` | [`Class`](ue_ue.Class.md) |
| `Tag` | `string` |

#### Overrides

[AnimNode_CustomProperty](ue_ue.AnimNode_CustomProperty.md).[constructor](ue_ue.AnimNode_CustomProperty.md#constructor)

## Properties

### DestProperties

• **DestProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Property`](ue_ue.Property.md)\>

#### Inherited from

[AnimNode_CustomProperty](ue_ue.AnimNode_CustomProperty.md).[DestProperties](ue_ue.AnimNode_CustomProperty.md#destproperties)

___

### DestPropertyNames

• **DestPropertyNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AnimNode_CustomProperty](ue_ue.AnimNode_CustomProperty.md).[DestPropertyNames](ue_ue.AnimNode_CustomProperty.md#destpropertynames)

___

### InputPoseNames

• **InputPoseNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### InputPoses

• **InputPoses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseLink`](ue_ue.PoseLink.md)\>

___

### InstanceClass

• **InstanceClass**: [`Class`](ue_ue.Class.md)

___

### SourceProperties

• **SourceProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Property`](ue_ue.Property.md)\>

#### Inherited from

[AnimNode_CustomProperty](ue_ue.AnimNode_CustomProperty.md).[SourceProperties](ue_ue.AnimNode_CustomProperty.md#sourceproperties)

___

### SourcePropertyNames

• **SourcePropertyNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AnimNode_CustomProperty](ue_ue.AnimNode_CustomProperty.md).[SourcePropertyNames](ue_ue.AnimNode_CustomProperty.md#sourcepropertynames)

___

### Tag

• **Tag**: `string`

___

### TargetInstance

• **TargetInstance**: [`Object`](ue_ue.Object.md)

#### Inherited from

[AnimNode_CustomProperty](ue_ue.AnimNode_CustomProperty.md).[TargetInstance](ue_ue.AnimNode_CustomProperty.md#targetinstance)

___

### \_\_tid\_AnimNode\_LinkedAnimGraph\_\_

• `Private` **\_\_tid\_AnimNode\_LinkedAnimGraph\_\_**: `boolean`

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_CustomProperty](ue_ue.AnimNode_CustomProperty.md).[StaticClass](ue_ue.AnimNode_CustomProperty.md#staticclass)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_CustomProperty](ue_ue.AnimNode_CustomProperty.md).[StaticStruct](ue_ue.AnimNode_CustomProperty.md#staticstruct)
