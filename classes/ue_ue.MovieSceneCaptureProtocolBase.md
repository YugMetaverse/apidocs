[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneCaptureProtocolBase

# Class: MovieSceneCaptureProtocolBase

[ue/ue](../modules/ue_ue.md).MovieSceneCaptureProtocolBase

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MovieSceneCaptureProtocolBase`**

  ↳↳ [`MovieSceneImageCaptureProtocolBase`](ue_ue.MovieSceneImageCaptureProtocolBase.md)

  ↳↳ [`MovieSceneAudioCaptureProtocolBase`](ue_ue.MovieSceneAudioCaptureProtocolBase.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneCaptureProtocolBase.md#constructor)

### Properties

- [State](ue_ue.MovieSceneCaptureProtocolBase.md#state)
- [\_\_tid\_MovieSceneCaptureProtocolBase\_\_](ue_ue.MovieSceneCaptureProtocolBase.md#__tid_moviescenecaptureprotocolbase__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneCaptureProtocolBase.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneCaptureProtocolBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneCaptureProtocolBase.md#executeubergraph)
- [GetClass](ue_ue.MovieSceneCaptureProtocolBase.md#getclass)
- [GetName](ue_ue.MovieSceneCaptureProtocolBase.md#getname)
- [GetOuter](ue_ue.MovieSceneCaptureProtocolBase.md#getouter)
- [GetState](ue_ue.MovieSceneCaptureProtocolBase.md#getstate)
- [GetWorld](ue_ue.MovieSceneCaptureProtocolBase.md#getworld)
- [IsCapturing](ue_ue.MovieSceneCaptureProtocolBase.md#iscapturing)
- [Find](ue_ue.MovieSceneCaptureProtocolBase.md#find)
- [Load](ue_ue.MovieSceneCaptureProtocolBase.md#load)
- [StaticClass](ue_ue.MovieSceneCaptureProtocolBase.md#staticclass)

## Constructors

### constructor

• **new MovieSceneCaptureProtocolBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### State

• **State**: [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

___

### \_\_tid\_MovieSceneCaptureProtocolBase\_\_

• **\_\_tid\_MovieSceneCaptureProtocolBase\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

[Object](ue_ue.Object.md).[CreateDefaultSubobject](ue_ue.Object.md#createdefaultsubobject)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetState

▸ **GetState**(): [`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

#### Returns

[`EMovieSceneCaptureProtocolState`](../enums/ue_ue.EMovieSceneCaptureProtocolState.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### IsCapturing

▸ **IsCapturing**(): `boolean`

#### Returns

`boolean`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
