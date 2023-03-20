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

#### Defined in

[ue/ue.d.ts:11379](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11379)

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

#### Defined in

[ue/ue.d.ts:11380](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11380)

## Properties

### DeterministicSequenceID

• **DeterministicSequenceID**: [`MovieSceneSequenceID`](ue_ue.MovieSceneSequenceID.md)

#### Defined in

[ue/ue.d.ts:11384](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11384)

___

### HierarchicalBias

• **HierarchicalBias**: `number`

#### Defined in

[ue/ue.d.ts:11388](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11388)

___

### InstanceData

• **InstanceData**: [`MovieSceneSequenceInstanceDataPtr`](ue_ue.MovieSceneSequenceInstanceDataPtr.md)

#### Defined in

[ue/ue.d.ts:11389](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11389)

___

### OuterToInnerTransform

• **OuterToInnerTransform**: [`MovieSceneSequenceTransform`](ue_ue.MovieSceneSequenceTransform.md)

#### Defined in

[ue/ue.d.ts:11392](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11392)

___

### PlayRange

• **PlayRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

#### Defined in

[ue/ue.d.ts:11385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11385)

___

### PostRollRange

• **PostRollRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

#### Defined in

[ue/ue.d.ts:11387](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11387)

___

### PreRollRange

• **PreRollRange**: [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)

#### Defined in

[ue/ue.d.ts:11386](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11386)

___

### RootToSequenceTransform

• **RootToSequenceTransform**: [`MovieSceneSequenceTransform`](ue_ue.MovieSceneSequenceTransform.md)

#### Defined in

[ue/ue.d.ts:11382](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11382)

___

### SectionPath

• **SectionPath**: `string`

#### Defined in

[ue/ue.d.ts:11390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11390)

___

### Sequence

• **Sequence**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

#### Defined in

[ue/ue.d.ts:11381](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11381)

___

### SubSectionSignature

• **SubSectionSignature**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:11391](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11391)

___

### TickResolution

• **TickResolution**: [`FrameRate`](ue_ue.FrameRate.md)

#### Defined in

[ue/ue.d.ts:11383](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11383)

___

### \_\_tid\_MovieSceneSubSequenceData\_\_

• `Private` **\_\_tid\_MovieSceneSubSequenceData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:11398](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11398)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:11396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11396)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:11397](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11397)
