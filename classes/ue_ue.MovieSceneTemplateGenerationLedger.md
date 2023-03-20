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

#### Defined in

[ue/ue.d.ts:11440](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11440)

• **new MovieSceneTemplateGenerationLedger**(`LastTrackIdentifier`, `TrackSignatureToTrackIdentifier`, `SubSectionRanges`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `LastTrackIdentifier` | [`MovieSceneTrackIdentifier`](ue_ue.MovieSceneTrackIdentifier.md) |
| `TrackSignatureToTrackIdentifier` | [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`MovieSceneTrackIdentifier`](ue_ue.MovieSceneTrackIdentifier.md)\> |
| `SubSectionRanges` | [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)\> |

#### Defined in

[ue/ue.d.ts:11441](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11441)

## Properties

### LastTrackIdentifier

• **LastTrackIdentifier**: [`MovieSceneTrackIdentifier`](ue_ue.MovieSceneTrackIdentifier.md)

#### Defined in

[ue/ue.d.ts:11442](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11442)

___

### SubSectionRanges

• **SubSectionRanges**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`MovieSceneFrameRange`](ue_ue.MovieSceneFrameRange.md)\>

#### Defined in

[ue/ue.d.ts:11444](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11444)

___

### TrackSignatureToTrackIdentifier

• **TrackSignatureToTrackIdentifier**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Guid`](ue_ue_s.Guid.md), [`MovieSceneTrackIdentifier`](ue_ue.MovieSceneTrackIdentifier.md)\>

#### Defined in

[ue/ue.d.ts:11443](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11443)

___

### \_\_tid\_MovieSceneTemplateGenerationLedger\_\_

• `Private` **\_\_tid\_MovieSceneTemplateGenerationLedger\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:11450](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11450)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:11448](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11448)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Defined in

[ue/ue.d.ts:11449](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11449)
