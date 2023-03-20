[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneSequenceHierarchy

# Class: MovieSceneSequenceHierarchy

[ue/ue](../modules/ue_ue.md).MovieSceneSequenceHierarchy

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneSequenceHierarchy.md#constructor)

### Properties

- [Hierarchy](ue_ue.MovieSceneSequenceHierarchy.md#hierarchy)
- [SubSequences](ue_ue.MovieSceneSequenceHierarchy.md#subsequences)
- [\_\_tid\_MovieSceneSequenceHierarchy\_\_](ue_ue.MovieSceneSequenceHierarchy.md#__tid_moviescenesequencehierarchy__)

### Methods

- [StaticClass](ue_ue.MovieSceneSequenceHierarchy.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneSequenceHierarchy.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneSequenceHierarchy**()

• **new MovieSceneSequenceHierarchy**(`SubSequences`, `Hierarchy`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SubSequences` | [`TMap`](../interfaces/ue_puerts.TMap.md)<[`MovieSceneSequenceID`](ue_ue.MovieSceneSequenceID.md), [`MovieSceneSubSequenceData`](ue_ue.MovieSceneSubSequenceData.md)\> |
| `Hierarchy` | [`TMap`](../interfaces/ue_puerts.TMap.md)<[`MovieSceneSequenceID`](ue_ue.MovieSceneSequenceID.md), [`MovieSceneSequenceHierarchyNode`](ue_ue.MovieSceneSequenceHierarchyNode.md)\> |

## Properties

### Hierarchy

• **Hierarchy**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`MovieSceneSequenceID`](ue_ue.MovieSceneSequenceID.md), [`MovieSceneSequenceHierarchyNode`](ue_ue.MovieSceneSequenceHierarchyNode.md)\>

___

### SubSequences

• **SubSequences**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`MovieSceneSequenceID`](ue_ue.MovieSceneSequenceID.md), [`MovieSceneSubSequenceData`](ue_ue.MovieSceneSubSequenceData.md)\>

___

### \_\_tid\_MovieSceneSequenceHierarchy\_\_

• `Private` **\_\_tid\_MovieSceneSequenceHierarchy\_\_**: `boolean`

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
