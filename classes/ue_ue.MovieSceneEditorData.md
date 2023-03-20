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

#### Defined in

[ue/ue.d.ts:11684](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11684)

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

#### Defined in

[ue/ue.d.ts:11685](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11685)

## Properties

### ExpansionStates

• **ExpansionStates**: [`TMap`](../interfaces/ue_puerts.TMap.md)<`string`, [`MovieSceneExpansionState`](ue_ue.MovieSceneExpansionState.md)\>

#### Defined in

[ue/ue.d.ts:11686](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11686)

___

### MarkedFrames

• **MarkedFrames**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\>

#### Defined in

[ue/ue.d.ts:11692](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11692)

___

### PinnedNodes

• **PinnedNodes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:11687](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11687)

___

### ViewEnd

• **ViewEnd**: `number`

#### Defined in

[ue/ue.d.ts:11689](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11689)

___

### ViewRange

• **ViewRange**: [`FloatRange`](ue_ue.FloatRange.md)

#### Defined in

[ue/ue.d.ts:11694](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11694)

___

### ViewStart

• **ViewStart**: `number`

#### Defined in

[ue/ue.d.ts:11688](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11688)

___

### WorkEnd

• **WorkEnd**: `number`

#### Defined in

[ue/ue.d.ts:11691](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11691)

___

### WorkStart

• **WorkStart**: `number`

#### Defined in

[ue/ue.d.ts:11690](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11690)

___

### WorkingRange

• **WorkingRange**: [`FloatRange`](ue_ue.FloatRange.md)

#### Defined in

[ue/ue.d.ts:11693](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11693)

___

### \_\_tid\_MovieSceneEditorData\_\_

• `Private` **\_\_tid\_MovieSceneEditorData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:11700](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11700)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:11698](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11698)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:11699](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11699)
