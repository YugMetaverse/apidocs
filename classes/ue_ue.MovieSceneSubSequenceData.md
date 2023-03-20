[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneSubSequenceData

# Class: MovieSceneSubSequenceData

[ue/ue](../modules/ue_ue.md).MovieSceneSubSequenceData

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneSubSequenceData.md#constructor)

### Properties

- [DeterministicSequenceID](ue_ue.MovieSceneSubSequenceData.md#deterministicsequenceid)
- [HierarchicalBias](ue_ue.MovieSceneSubSequenceData.md#hierarchicalbias)
- [InstanceData](ue_ue.MovieSceneSubSequenceData.md#instancedata)
- [OuterToInnerTransform](ue_ue.MovieSceneSubSequenceData.md#outertoinnertransform)
- [PlayRange](ue_ue.MovieSceneSubSequenceData.md#playrange)
- [PostRollRange](ue_ue.MovieSceneSubSequenceData.md#postrollrange)
- [PreRollRange](ue_ue.MovieSceneSubSequenceData.md#prerollrange)
- [RootToSequenceTransform](ue_ue.MovieSceneSubSequenceData.md#roottosequencetransform)
- [SectionPath](ue_ue.MovieSceneSubSequenceData.md#sectionpath)
- [Sequence](ue_ue.MovieSceneSubSequenceData.md#sequence)
- [SubSectionSignature](ue_ue.MovieSceneSubSequenceData.md#subsectionsignature)
- [TickResolution](ue_ue.MovieSceneSubSequenceData.md#tickresolution)
- [\_\_tid\_MovieSceneSubSequenceData\_\_](ue_ue.MovieSceneSubSequenceData.md#__tid_moviescenesubsequencedata__)

### Methods

- [StaticClass](ue_ue.MovieSceneSubSequenceData.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneSubSequenceData.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneSubSequenceData**()

• **new MovieSceneSubSequenceData**(`Sequence`, `RootToSequenceTransform`, `TickResolution`, `DeterministicSequenceID`, `PlayRange`, `PreRollRange`, `PostRollRange`, `HierarchicalBias`, `InstanceData`, `SectionPath`, `SubSectionSignature`, `OuterToInnerTransform`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Sequence` | [`SoftObjectPath`](ue_ue.SoftObjectPath.md) |
| `RootToSequenceTransform` | [`MovieSceneSequenceTransform`](ue_ue.MovieSceneSequenceTransform.md) |
| `TickResolution` | [`FrameRate`](ue_ue.FrameRate.md) |
| `DeterministicSequenceID` | [`MovieSceneSequenceID`](ue_ue.MovieSceneSequenceID.md) |
| `PlayRange` | [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md) |
| `PreRollRange` | [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md) |
| `PostRollRange` | [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md) |
| `HierarchicalBias` | `number` |
| `InstanceData` | [`MovieSceneSequenceInstanceDataPtr`](ue_ue.MovieSceneSequenceInstanceDataPtr.md) |
| `SectionPath` | `string` |
| `SubSectionSignature` | [`Guid`](ue_ue_s.Guid.md) |
| `OuterToInnerTransform` | [`MovieSceneSequenceTransform`](ue_ue.MovieSceneSequenceTransform.md) |

## Properties

### DeterministicSequenceID

• **DeterministicSequenceID**: [`MovieSceneSequenceID`](ue_ue.MovieSceneSequenceID.md)

___

### HierarchicalBias

• **HierarchicalBias**: `number`

___

### InstanceData

• **InstanceData**: [`MovieSceneSequenceInstanceDataPtr`](ue_ue.MovieSceneSequenceInstanceDataPtr.md)

___

### OuterToInnerTransform

• **OuterToInnerTransform**: [`MovieSceneSequenceTransform`](ue_ue.MovieSceneSequenceTransform.md)

___

### PlayRange

• **PlayRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

___

### PostRollRange

• **PostRollRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

___

### PreRollRange

• **PreRollRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

___

### RootToSequenceTransform

• **RootToSequenceTransform**: [`MovieSceneSequenceTransform`](ue_ue.MovieSceneSequenceTransform.md)

___

### SectionPath

• **SectionPath**: `string`

___

### Sequence

• **Sequence**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### SubSectionSignature

• **SubSectionSignature**: [`Guid`](ue_ue_s.Guid.md)

___

### TickResolution

• **TickResolution**: [`FrameRate`](ue_ue.FrameRate.md)

___

### \_\_tid\_MovieSceneSubSequenceData\_\_

• `Private` **\_\_tid\_MovieSceneSubSequenceData\_\_**: `boolean`

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
