[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNode\_CopyPoseFromMesh

# Class: AnimNode\_CopyPoseFromMesh

[ue/ue](../modules/ue_ue.md).AnimNode_CopyPoseFromMesh

## Hierarchy

- [`AnimNode_Base`](ue_ue.AnimNode_Base.md)

  ↳ **`AnimNode_CopyPoseFromMesh`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNode_CopyPoseFromMesh.md#constructor)

### Properties

- [SourceMeshComponent](ue_ue.AnimNode_CopyPoseFromMesh.md#sourcemeshcomponent)
- [\_\_tid\_AnimNode\_CopyPoseFromMesh\_\_](ue_ue.AnimNode_CopyPoseFromMesh.md#__tid_animnode_copyposefrommesh__)
- [bCopyCurves](ue_ue.AnimNode_CopyPoseFromMesh.md#bcopycurves)
- [bUseAttachedParent](ue_ue.AnimNode_CopyPoseFromMesh.md#buseattachedparent)

### Methods

- [StaticClass](ue_ue.AnimNode_CopyPoseFromMesh.md#staticclass)
- [StaticStruct](ue_ue.AnimNode_CopyPoseFromMesh.md#staticstruct)

## Constructors

### constructor

• **new AnimNode_CopyPoseFromMesh**()

#### Overrides

[AnimNode_Base](ue_ue.AnimNode_Base.md).[constructor](ue_ue.AnimNode_Base.md#constructor)

• **new AnimNode_CopyPoseFromMesh**(`SourceMeshComponent`, `bUseAttachedParent`, `bCopyCurves`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceMeshComponent` | [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)\> |
| `bUseAttachedParent` | `boolean` |
| `bCopyCurves` | `boolean` |

#### Overrides

UE.AnimNode\_Base.constructor

## Properties

### SourceMeshComponent

• **SourceMeshComponent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)\>

___

### \_\_tid\_AnimNode\_CopyPoseFromMesh\_\_

• `Private` **\_\_tid\_AnimNode\_CopyPoseFromMesh\_\_**: `boolean`

___

### bCopyCurves

• **bCopyCurves**: `boolean`

___

### bUseAttachedParent

• **bUseAttachedParent**: `boolean`

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
