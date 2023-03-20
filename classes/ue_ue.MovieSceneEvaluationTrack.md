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

#### Defined in

[ue/ue.d.ts:11152](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11152)

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

#### Defined in

[ue/ue.d.ts:11153](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11153)

## Properties

### ChildTemplates

• **ChildTemplates**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneEvalTemplatePtr`](ue_ue.MovieSceneEvalTemplatePtr.md)\>

#### Defined in

[ue/ue.d.ts:11160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11160)

___

### EvaluationGroup

• **EvaluationGroup**: `string`

#### Defined in

[ue/ue.d.ts:11162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11162)

___

### EvaluationMethod

• **EvaluationMethod**: [`EEvaluationMethod`](../enums/ue_ue.EEvaluationMethod.md)

#### Defined in

[ue/ue.d.ts:11156](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11156)

___

### EvaluationPriority

• **EvaluationPriority**: `number`

#### Defined in

[ue/ue.d.ts:11155](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11155)

___

### EvaluationTree

• **EvaluationTree**: [`SectionEvaluationDataTree`](ue_ue.SectionEvaluationDataTree.md)

#### Defined in

[ue/ue.d.ts:11159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11159)

___

### ObjectBindingID

• **ObjectBindingID**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:11154](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11154)

___

### Segments

• **Segments**: [`MovieSceneEvaluationTrackSegments`](ue_ue.MovieSceneEvaluationTrackSegments.md)

#### Defined in

[ue/ue.d.ts:11157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11157)

___

### SourceTrack

• **SourceTrack**: [`MovieSceneTrack`](ue_ue.MovieSceneTrack.md)

#### Defined in

[ue/ue.d.ts:11158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11158)

___

### TrackTemplate

• **TrackTemplate**: [`MovieSceneTrackImplementationPtr`](ue_ue.MovieSceneTrackImplementationPtr.md)

#### Defined in

[ue/ue.d.ts:11161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11161)

___

### \_\_tid\_MovieSceneEvaluationTrack\_\_

• `Private` **\_\_tid\_MovieSceneEvaluationTrack\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:11171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11171)

___

### bEvaluateInPostroll

• **bEvaluateInPostroll**: `boolean`

#### Defined in

[ue/ue.d.ts:11164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11164)

___

### bEvaluateInPreroll

• **bEvaluateInPreroll**: `boolean`

#### Defined in

[ue/ue.d.ts:11163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11163)

___

### bTearDownPriority

• **bTearDownPriority**: `boolean`

#### Defined in

[ue/ue.d.ts:11165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11165)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:11169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11169)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:11170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11170)
