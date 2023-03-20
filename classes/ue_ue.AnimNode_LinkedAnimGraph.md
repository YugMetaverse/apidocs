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

#### Defined in

[ue/ue.d.ts:18732](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18732)

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

#### Defined in

[ue/ue.d.ts:18733](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18733)

## Properties

### DestProperties

• **DestProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Property`](ue_ue.Property.md)\>

#### Inherited from

[AnimNode_CustomProperty](ue_ue.AnimNode_CustomProperty.md).[DestProperties](ue_ue.AnimNode_CustomProperty.md#destproperties)

#### Defined in

[ue/ue.d.ts:18722](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18722)

___

### DestPropertyNames

• **DestPropertyNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AnimNode_CustomProperty](ue_ue.AnimNode_CustomProperty.md).[DestPropertyNames](ue_ue.AnimNode_CustomProperty.md#destpropertynames)

#### Defined in

[ue/ue.d.ts:18719](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18719)

___

### InputPoseNames

• **InputPoseNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:18735](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18735)

___

### InputPoses

• **InputPoses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PoseLink`](ue_ue.PoseLink.md)\>

#### Defined in

[ue/ue.d.ts:18734](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18734)

___

### InstanceClass

• **InstanceClass**: [`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:18736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18736)

___

### SourceProperties

• **SourceProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Property`](ue_ue.Property.md)\>

#### Inherited from

[AnimNode_CustomProperty](ue_ue.AnimNode_CustomProperty.md).[SourceProperties](ue_ue.AnimNode_CustomProperty.md#sourceproperties)

#### Defined in

[ue/ue.d.ts:18721](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18721)

___

### SourcePropertyNames

• **SourcePropertyNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AnimNode_CustomProperty](ue_ue.AnimNode_CustomProperty.md).[SourcePropertyNames](ue_ue.AnimNode_CustomProperty.md#sourcepropertynames)

#### Defined in

[ue/ue.d.ts:18718](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18718)

___

### Tag

• **Tag**: `string`

#### Defined in

[ue/ue.d.ts:18737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18737)

___

### TargetInstance

• **TargetInstance**: [`Object`](ue_ue.Object.md)

#### Inherited from

[AnimNode_CustomProperty](ue_ue.AnimNode_CustomProperty.md).[TargetInstance](ue_ue.AnimNode_CustomProperty.md#targetinstance)

#### Defined in

[ue/ue.d.ts:18720](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18720)

___

### \_\_tid\_AnimNode\_LinkedAnimGraph\_\_

• `Private` **\_\_tid\_AnimNode\_LinkedAnimGraph\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:18743](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18743)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_CustomProperty](ue_ue.AnimNode_CustomProperty.md).[StaticClass](ue_ue.AnimNode_CustomProperty.md#staticclass)

#### Defined in

[ue/ue.d.ts:18741](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18741)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[AnimNode_CustomProperty](ue_ue.AnimNode_CustomProperty.md).[StaticStruct](ue_ue.AnimNode_CustomProperty.md#staticstruct)

#### Defined in

[ue/ue.d.ts:18742](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L18742)
