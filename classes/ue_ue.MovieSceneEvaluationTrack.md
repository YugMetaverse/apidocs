[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneEvaluationTrack

# Class: MovieSceneEvaluationTrack

[ue/ue](../modules/ue_ue.md).MovieSceneEvaluationTrack

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneEvaluationTrack.md#constructor)

### Properties

- [ChildTemplates](ue_ue.MovieSceneEvaluationTrack.md#childtemplates)
- [EvaluationGroup](ue_ue.MovieSceneEvaluationTrack.md#evaluationgroup)
- [EvaluationMethod](ue_ue.MovieSceneEvaluationTrack.md#evaluationmethod)
- [EvaluationPriority](ue_ue.MovieSceneEvaluationTrack.md#evaluationpriority)
- [EvaluationTree](ue_ue.MovieSceneEvaluationTrack.md#evaluationtree)
- [ObjectBindingID](ue_ue.MovieSceneEvaluationTrack.md#objectbindingid)
- [Segments](ue_ue.MovieSceneEvaluationTrack.md#segments)
- [SourceTrack](ue_ue.MovieSceneEvaluationTrack.md#sourcetrack)
- [TrackTemplate](ue_ue.MovieSceneEvaluationTrack.md#tracktemplate)
- [\_\_tid\_MovieSceneEvaluationTrack\_\_](ue_ue.MovieSceneEvaluationTrack.md#__tid_moviesceneevaluationtrack__)
- [bEvaluateInPostroll](ue_ue.MovieSceneEvaluationTrack.md#bevaluateinpostroll)
- [bEvaluateInPreroll](ue_ue.MovieSceneEvaluationTrack.md#bevaluateinpreroll)
- [bTearDownPriority](ue_ue.MovieSceneEvaluationTrack.md#bteardownpriority)

### Methods

- [StaticClass](ue_ue.MovieSceneEvaluationTrack.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneEvaluationTrack.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneEvaluationTrack**()

• **new MovieSceneEvaluationTrack**(`ObjectBindingID`, `EvaluationPriority`, `EvaluationMethod`, `Segments`, `SourceTrack`, `EvaluationTree`, `ChildTemplates`, `TrackTemplate`, `EvaluationGroup`, `bEvaluateInPreroll`, `bEvaluateInPostroll`, `bTearDownPriority`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ObjectBindingID` | [`Guid`](ue_ue_s.Guid.md) |
| `EvaluationPriority` | `number` |
| `EvaluationMethod` | [`EEvaluationMethod`](../enums/ue_ue.EEvaluationMethod.md) |
| `Segments` | [`MovieSceneEvaluationTrackSegments`](ue_ue.MovieSceneEvaluationTrackSegments.md) |
| `SourceTrack` | [`MovieSceneTrack`](ue_ue.MovieSceneTrack.md) |
| `EvaluationTree` | [`SectionEvaluationDataTree`](ue_ue.SectionEvaluationDataTree.md) |
| `ChildTemplates` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneEvalTemplatePtr`](ue_ue.MovieSceneEvalTemplatePtr.md)\> |
| `TrackTemplate` | [`MovieSceneTrackImplementationPtr`](ue_ue.MovieSceneTrackImplementationPtr.md) |
| `EvaluationGroup` | `string` |
| `bEvaluateInPreroll` | `boolean` |
| `bEvaluateInPostroll` | `boolean` |
| `bTearDownPriority` | `boolean` |

## Properties

### ChildTemplates

• **ChildTemplates**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneEvalTemplatePtr`](ue_ue.MovieSceneEvalTemplatePtr.md)\>

___

### EvaluationGroup

• **EvaluationGroup**: `string`

___

### EvaluationMethod

• **EvaluationMethod**: [`EEvaluationMethod`](../enums/ue_ue.EEvaluationMethod.md)

___

### EvaluationPriority

• **EvaluationPriority**: `number`

___

### EvaluationTree

• **EvaluationTree**: [`SectionEvaluationDataTree`](ue_ue.SectionEvaluationDataTree.md)

___

### ObjectBindingID

• **ObjectBindingID**: [`Guid`](ue_ue_s.Guid.md)

___

### Segments

• **Segments**: [`MovieSceneEvaluationTrackSegments`](ue_ue.MovieSceneEvaluationTrackSegments.md)

___

### SourceTrack

• **SourceTrack**: [`MovieSceneTrack`](ue_ue.MovieSceneTrack.md)

___

### TrackTemplate

• **TrackTemplate**: [`MovieSceneTrackImplementationPtr`](ue_ue.MovieSceneTrackImplementationPtr.md)

___

### \_\_tid\_MovieSceneEvaluationTrack\_\_

• `Private` **\_\_tid\_MovieSceneEvaluationTrack\_\_**: `boolean`

___

### bEvaluateInPostroll

• **bEvaluateInPostroll**: `boolean`

___

### bEvaluateInPreroll

• **bEvaluateInPreroll**: `boolean`

___

### bTearDownPriority

• **bTearDownPriority**: `boolean`

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
