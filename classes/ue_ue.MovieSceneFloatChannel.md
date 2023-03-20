[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneFloatChannel

# Class: MovieSceneFloatChannel

[ue/ue](../modules/ue_ue.md).MovieSceneFloatChannel

## Hierarchy

- [`MovieSceneChannel`](ue_ue.MovieSceneChannel.md)

  ↳ **`MovieSceneFloatChannel`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneFloatChannel.md#constructor)

### Properties

- [DefaultValue](ue_ue.MovieSceneFloatChannel.md#defaultvalue)
- [KeyHandles](ue_ue.MovieSceneFloatChannel.md#keyhandles)
- [PostInfinityExtrap](ue_ue.MovieSceneFloatChannel.md#postinfinityextrap)
- [PreInfinityExtrap](ue_ue.MovieSceneFloatChannel.md#preinfinityextrap)
- [TickResolution](ue_ue.MovieSceneFloatChannel.md#tickresolution)
- [Times](ue_ue.MovieSceneFloatChannel.md#times)
- [Values](ue_ue.MovieSceneFloatChannel.md#values)
- [\_\_tid\_MovieSceneFloatChannel\_\_](ue_ue.MovieSceneFloatChannel.md#__tid_moviescenefloatchannel__)
- [bHasDefaultValue](ue_ue.MovieSceneFloatChannel.md#bhasdefaultvalue)

### Methods

- [StaticClass](ue_ue.MovieSceneFloatChannel.md#staticclass)
- [StaticStruct](ue_ue.MovieSceneFloatChannel.md#staticstruct)

## Constructors

### constructor

• **new MovieSceneFloatChannel**()

#### Overrides

[MovieSceneChannel](ue_ue.MovieSceneChannel.md).[constructor](ue_ue.MovieSceneChannel.md#constructor)

#### Defined in

[ue/ue.d.ts:50964](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50964)

• **new MovieSceneFloatChannel**(`PreInfinityExtrap`, `PostInfinityExtrap`, `Times`, `Values`, `DefaultValue`, `bHasDefaultValue`, `KeyHandles`, `TickResolution`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `PreInfinityExtrap` | [`ERichCurveExtrapolation`](../enums/ue_ue.ERichCurveExtrapolation.md) |
| `PostInfinityExtrap` | [`ERichCurveExtrapolation`](../enums/ue_ue.ERichCurveExtrapolation.md) |
| `Times` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\> |
| `Values` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneFloatValue`](ue_ue.MovieSceneFloatValue.md)\> |
| `DefaultValue` | `number` |
| `bHasDefaultValue` | `boolean` |
| `KeyHandles` | [`MovieSceneKeyHandleMap`](ue_ue.MovieSceneKeyHandleMap.md) |
| `TickResolution` | [`FrameRate`](ue_ue.FrameRate.md) |

#### Overrides

UE.MovieSceneChannel.constructor

#### Defined in

[ue/ue.d.ts:50965](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50965)

## Properties

### DefaultValue

• **DefaultValue**: `number`

#### Defined in

[ue/ue.d.ts:50970](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50970)

___

### KeyHandles

• **KeyHandles**: [`MovieSceneKeyHandleMap`](ue_ue.MovieSceneKeyHandleMap.md)

#### Defined in

[ue/ue.d.ts:50972](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50972)

___

### PostInfinityExtrap

• **PostInfinityExtrap**: [`ERichCurveExtrapolation`](../enums/ue_ue.ERichCurveExtrapolation.md)

#### Defined in

[ue/ue.d.ts:50967](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50967)

___

### PreInfinityExtrap

• **PreInfinityExtrap**: [`ERichCurveExtrapolation`](../enums/ue_ue.ERichCurveExtrapolation.md)

#### Defined in

[ue/ue.d.ts:50966](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50966)

___

### TickResolution

• **TickResolution**: [`FrameRate`](ue_ue.FrameRate.md)

#### Defined in

[ue/ue.d.ts:50973](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50973)

___

### Times

• **Times**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`FrameNumber`](ue_ue.FrameNumber.md)\>

#### Defined in

[ue/ue.d.ts:50968](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50968)

___

### Values

• **Values**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MovieSceneFloatValue`](ue_ue.MovieSceneFloatValue.md)\>

#### Defined in

[ue/ue.d.ts:50969](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50969)

___

### \_\_tid\_MovieSceneFloatChannel\_\_

• `Private` **\_\_tid\_MovieSceneFloatChannel\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:50979](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50979)

___

### bHasDefaultValue

• **bHasDefaultValue**: `boolean`

#### Defined in

[ue/ue.d.ts:50971](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50971)

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

[ue/ue.d.ts:50977](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50977)

___

### StaticStruct

▸ `Static` **StaticStruct**(): [`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Returns

[`ScriptStruct`](ue_ue.ScriptStruct.md)

#### Overrides

[MovieSceneChannel](ue_ue.MovieSceneChannel.md).[StaticStruct](ue_ue.MovieSceneChannel.md#staticstruct)

#### Defined in

[ue/ue.d.ts:50978](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L50978)
