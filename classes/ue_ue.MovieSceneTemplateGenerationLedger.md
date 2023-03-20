[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneTemplateGenerationLedger

# Class: MovieSceneTemplateGenerationLedger

[ue/ue](../modules/ue_ue.md).MovieSceneTemplateGenerationLedger

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneTemplateGenerationLedger.md#constructor)

### Properties

- [LastTrackIdentifier](ue_ue.MovieSceneTemplateGenerationLedger.md#lasttrackidentifier)
- [SubSectionRanges](ue_ue.MovieSceneTemplateGenerationLedger.md#subsectionranges)
- [TrackSignatureToTrackIdentifier](ue_ue.MovieSceneTemplateGenerationLedger.md#tracksignaturetotrackidentifier)
- [\_\_tid\_MovieSceneTemplateGenerationLedger\_\_](ue_ue.MovieSceneTemplateGenerationLedger.md#__tid_moviescenetemplategenerationledger__)

### Methods

- [StaticClass](ue_ue.MovieSceneTemplateGenerationLedger.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneTemplateGenerationLedger.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneTemplateGenerationLedger**()

• **new MovieSceneTemplateGenerationLedger**(`LastTrackIdentifier`, `TrackSignatureToTrackIdentifier`, `SubSectionRanges`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `LastTrackIdentifier` | [`MovieSceneTrackIdentifier`](ue_ue.MovieSceneTrackIdentifier.md) |
| `TrackSignatureToTrackIdentifier` | [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`MovieSceneTrackIdentifier`](ue_ue.MovieSceneTrackIdentifier.md)\> |
| `SubSectionRanges` | [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)\> |

## Properties

### LastTrackIdentifier

• **LastTrackIdentifier**: [`MovieSceneTrackIdentifier`](ue_ue.MovieSceneTrackIdentifier.md)

___

### SubSectionRanges

• **SubSectionRanges**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)\>

___

### TrackSignatureToTrackIdentifier

• **TrackSignatureToTrackIdentifier**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`MovieSceneTrackIdentifier`](ue_ue.MovieSceneTrackIdentifier.md)\>

___

### \_\_tid\_MovieSceneTemplateGenerationLedger\_\_

• `Private` **\_\_tid\_MovieSceneTemplateGenerationLedger\_\_**: `boolean`

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
