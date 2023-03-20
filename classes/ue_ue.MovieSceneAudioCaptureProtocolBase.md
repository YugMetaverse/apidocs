[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneAudioCaptureProtocolBase

# Class: MovieSceneAudioCaptureProtocolBase

[ue/ue](../modules/ue_ue.md).MovieSceneAudioCaptureProtocolBase

## Hierarchy

- [`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

  ↳ **`MovieSceneAudioCaptureProtocolBase`**

  ↳↳ [`MasterAudioSubmixCaptureProtocol`](ue_ue.MasterAudioSubmixCaptureProtocol.md)

  ↳↳ [`NullAudioCaptureProtocol`](ue_ue.NullAudioCaptureProtocol.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneAudioCaptureProtocolBase.md#constructor)

### Properties

- [State](ue_ue.MovieSceneAudioCaptureProtocolBase.md#state)
- [\_\_tid\_MovieSceneAudioCaptureProtocolBase\_\_](ue_ue.MovieSceneAudioCaptureProtocolBase.md#__tid_moviesceneaudiocaptureprotocolbase__)
- [\_\_tid\_MovieSceneCaptureProtocolBase\_\_](ue_ue.MovieSceneAudioCaptureProtocolBase.md#__tid_moviescenecaptureprotocolbase__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneAudioCaptureProtocolBase.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneAudioCaptureProtocolBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneAudioCaptureProtocolBase.md#executeubergraph)
- [GetClass](ue_ue.MovieSceneAudioCaptureProtocolBase.md#getclass)
- [GetName](ue_ue.MovieSceneAudioCaptureProtocolBase.md#getname)
- [GetOuter](ue_ue.MovieSceneAudioCaptureProtocolBase.md#getouter)
- [GetState](ue_ue.MovieSceneAudioCaptureProtocolBase.md#getstate)
- [GetWorld](ue_ue.MovieSceneAudioCaptureProtocolBase.md#getworld)
- [IsCapturing](ue_ue.MovieSceneAudioCaptureProtocolBase.md#iscapturing)
- [Find](ue_ue.MovieSceneAudioCaptureProtocolBase.md#find)
- [Load](ue_ue.MovieSceneAudioCaptureProtocolBase.md#load)
- [StaticClass](ue_ue.MovieSceneAudioCaptureProtocolBase.md#staticclass)

## Constructors

### constructor

• **new MovieSceneAudioCaptureProtocolBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[constructor](ue_ue.MovieSceneCaptureProtocolBase.md#constructor)

## Properties

### State

• **State**: [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[State](ue_ue.MovieSceneCaptureProtocolBase.md#state)

___

### \_\_tid\_MovieSceneAudioCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneAudioCaptureProtocolBase\_\_**: `boolean`

___

### \_\_tid\_MovieSceneCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneCaptureProtocolBase\_\_**: `boolean`

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[__tid_MovieSceneCaptureProtocolBase__](ue_ue.MovieSceneCaptureProtocolBase.md#__tid_moviescenecaptureprotocolbase__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[__tid_Object__](ue_ue.MovieSceneCaptureProtocolBase.md#__tid_object__)

## Methods

### CreateDefaultSubobject

▸ **CreateDefaultSubobject**(`p0`, `p1`, `p2`, `p3`, `p4`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | `string` |
| `p1` | [`Class`](ue_ue.Class.md) |
| `p2` | [`Class`](ue_ue.Class.md) |
| `p3` | `boolean` |
| `p4` | `boolean` |

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[CreateDefaultSubobject](ue_ue.MovieSceneCaptureProtocolBase.md#createdefaultsubobject)

___

### ExecuteUbergraph

▸ **ExecuteUbergraph**(`EntryPoint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EntryPoint` | `number` |

#### Returns

`void`

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[ExecuteUbergraph](ue_ue.MovieSceneCaptureProtocolBase.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[GetClass](ue_ue.MovieSceneCaptureProtocolBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[GetName](ue_ue.MovieSceneCaptureProtocolBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[GetOuter](ue_ue.MovieSceneCaptureProtocolBase.md#getouter)

___

### GetState

▸ **GetState**(): [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Returns

[`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[GetState](ue_ue.MovieSceneCaptureProtocolBase.md#getstate)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[GetWorld](ue_ue.MovieSceneCaptureProtocolBase.md#getworld)

___

### IsCapturing

▸ **IsCapturing**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[IsCapturing](ue_ue.MovieSceneCaptureProtocolBase.md#iscapturing)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneAudioCaptureProtocolBase`](ue_ue.MovieSceneAudioCaptureProtocolBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneAudioCaptureProtocolBase`](ue_ue.MovieSceneAudioCaptureProtocolBase.md)

#### Overrides

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[Find](ue_ue.MovieSceneCaptureProtocolBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneAudioCaptureProtocolBase`](ue_ue.MovieSceneAudioCaptureProtocolBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneAudioCaptureProtocolBase`](ue_ue.MovieSceneAudioCaptureProtocolBase.md)

#### Overrides

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[Load](ue_ue.MovieSceneCaptureProtocolBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneCaptureProtocolBase](ue_ue.MovieSceneCaptureProtocolBase.md).[StaticClass](ue_ue.MovieSceneCaptureProtocolBase.md#staticclass)
