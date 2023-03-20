[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneEditorData

# Class: MovieSceneEditorData

[ue/ue](../modules/ue_ue.md).MovieSceneEditorData

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneEditorData.md#constructor)

### Properties

- [ExpansionStates](ue_ue.MovieSceneEditorData.md#expansionstates)
- [MarkedFrames](ue_ue.MovieSceneEditorData.md#markedframes)
- [PinnedNodes](ue_ue.MovieSceneEditorData.md#pinnednodes)
- [ViewEnd](ue_ue.MovieSceneEditorData.md#viewend)
- [ViewRange](ue_ue.MovieSceneEditorData.md#viewrange)
- [ViewStart](ue_ue.MovieSceneEditorData.md#viewstart)
- [WorkEnd](ue_ue.MovieSceneEditorData.md#workend)
- [WorkStart](ue_ue.MovieSceneEditorData.md#workstart)
- [WorkingRange](ue_ue.MovieSceneEditorData.md#workingrange)
- [\_\_tid\_MovieSceneEditorData\_\_](ue_ue.MovieSceneEditorData.md#__tid_moviesceneeditordata__)

### Methods

- [StaticClass](ue_ue.MovieSceneEditorData.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneEditorData.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneEditorData**()

• **new MovieSceneEditorData**(`ExpansionStates`, `PinnedNodes`, `ViewStart`, `ViewEnd`, `WorkStart`, `WorkEnd`, `MarkedFrames`, `WorkingRange`, `ViewRange`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ExpansionStates` | [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`MovieSceneExpansionState`](ue_ue.MovieSceneExpansionState.md)\> |
| `PinnedNodes` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\> |
| `ViewStart` | `number` |
| `ViewEnd` | `number` |
| `WorkStart` | `number` |
| `WorkEnd` | `number` |
| `MarkedFrames` | [`TSet`](../interfaces/ue_puerts.TSet.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\> |
| `WorkingRange` | [`FloatRange`](ue_ue.FloatRange.md) |
| `ViewRange` | [`FloatRange`](ue_ue.FloatRange.md) |

## Properties

### ExpansionStates

• **ExpansionStates**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`MovieSceneExpansionState`](ue_ue.MovieSceneExpansionState.md)\>

___

### MarkedFrames

• **MarkedFrames**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\>

___

### PinnedNodes

• **PinnedNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### ViewEnd

• **ViewEnd**: `number`

___

### ViewRange

• **ViewRange**: [`FloatRange`](ue_ue.FloatRange.md)

___

### ViewStart

• **ViewStart**: `number`

___

### WorkEnd

• **WorkEnd**: `number`

___

### WorkStart

• **WorkStart**: `number`

___

### WorkingRange

• **WorkingRange**: [`FloatRange`](ue_ue.FloatRange.md)

___

### \_\_tid\_MovieSceneEditorData\_\_

• `Private` **\_\_tid\_MovieSceneEditorData\_\_**: `boolean`

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
