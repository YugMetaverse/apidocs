[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneEventSectionData

# Class: MovieSceneEventSectionData

[ue/ue](../modules/ue_ue.md).MovieSceneEventSectionData

## Hierarchy

- [`MovieSceneChannel`](ue_ue.MovieSceneChannel.md)

  ↳ **`MovieSceneEventSectionData`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneEventSectionData.md#constructor)

### Properties

- [KeyTimes](ue_ue.MovieSceneEventSectionData.md#keytimes)
- [KeyValues](ue_ue.MovieSceneEventSectionData.md#keyvalues)
- [Times](ue_ue.MovieSceneEventSectionData.md#times)
- [\_\_tid\_MovieSceneEventSectionData\_\_](ue_ue.MovieSceneEventSectionData.md#__tid_moviesceneeventsectiondata__)

### Methods

- [StaticClass](ue_ue.MovieSceneEventSectionData.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneEventSectionData.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneEventSectionData**()

#### Overrides

[MovieSceneChannel](ue_ue.MovieSceneChannel.md).[constructor](ue_ue.MovieSceneChannel.md#constructor)

#### Defined in

[ue/ue.d.ts:51782](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51782)

• **new MovieSceneEventSectionData**(`Times`, `KeyValues`, `KeyTimes`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Times` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\> |
| `KeyValues` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EventPayload`](ue_ue.EventPayload.md)\> |
| `KeyTimes` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |

#### Overrides

UE.MovieSceneChannel.constructor

#### Defined in

[ue/ue.d.ts:51783](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51783)

## Properties

### KeyTimes

• **KeyTimes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:51786](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51786)

___

### KeyValues

• **KeyValues**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EventPayload`](ue_ue.EventPayload.md)\>

#### Defined in

[ue/ue.d.ts:51785](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51785)

___

### Times

• **Times**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\>

#### Defined in

[ue/ue.d.ts:51784](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51784)

___

### \_\_tid\_MovieSceneEventSectionData\_\_

• `Private` **\_\_tid\_MovieSceneEventSectionData\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:51792](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51792)

## Methods

### StaticClass

▸ `Static` **StaticClass**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

**`Deprecated`**

use StaticStruct instead.

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[MovieSceneChannel](ue_ue.MovieSceneChannel.md).[StaticClass](ue_ue.MovieSceneChannel.md#staticclass)

#### Defined in

[ue/ue.d.ts:51790](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51790)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[MovieSceneChannel](ue_ue.MovieSceneChannel.md).[StaticStruct](ue_ue.MovieSceneChannel.md#staticstruct)

#### Defined in

[ue/ue.d.ts:51791](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L51791)
