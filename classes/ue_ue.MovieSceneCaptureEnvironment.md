[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneCaptureEnvironment

# Class: MovieSceneCaptureEnvironment

[ue/ue](../modules/ue_ue.md).MovieSceneCaptureEnvironment

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MovieSceneCaptureEnvironment`**

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneCaptureEnvironment.md#constructor)

### Properties

- [\_\_tid\_MovieSceneCaptureEnvironment\_\_](ue_ue.MovieSceneCaptureEnvironment.md#__tid_moviescenecaptureenvironment__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneCaptureEnvironment.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneCaptureEnvironment.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneCaptureEnvironment.md#executeubergraph)
- [GetClass](ue_ue.MovieSceneCaptureEnvironment.md#getclass)
- [GetName](ue_ue.MovieSceneCaptureEnvironment.md#getname)
- [GetOuter](ue_ue.MovieSceneCaptureEnvironment.md#getouter)
- [GetWorld](ue_ue.MovieSceneCaptureEnvironment.md#getworld)
- [Find](ue_ue.MovieSceneCaptureEnvironment.md#find)
- [FindAudioCaptureProtocol](ue_ue.MovieSceneCaptureEnvironment.md#findaudiocaptureprotocol)
- [FindImageCaptureProtocol](ue_ue.MovieSceneCaptureEnvironment.md#findimagecaptureprotocol)
- [GetCaptureElapsedTime](ue_ue.MovieSceneCaptureEnvironment.md#getcaptureelapsedtime)
- [GetCaptureFrameNumber](ue_ue.MovieSceneCaptureEnvironment.md#getcaptureframenumber)
- [IsCaptureInProgress](ue_ue.MovieSceneCaptureEnvironment.md#iscaptureinprogress)
- [Load](ue_ue.MovieSceneCaptureEnvironment.md#load)
- [StaticClass](ue_ue.MovieSceneCaptureEnvironment.md#staticclass)

## Constructors

### constructor

• **new MovieSceneCaptureEnvironment**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_MovieSceneCaptureEnvironment\_\_

• **\_\_tid\_MovieSceneCaptureEnvironment\_\_**: `boolean`

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

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneCaptureEnvironment`](ue_ue.MovieSceneCaptureEnvironment.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneCaptureEnvironment`](ue_ue.MovieSceneCaptureEnvironment.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### FindAudioCaptureProtocol

▸ `Static` **FindAudioCaptureProtocol**(): [`MovieSceneAudioCaptureProtocolBase`](ue_ue.MovieSceneAudioCaptureProtocolBase.md)

#### Returns

[`MovieSceneAudioCaptureProtocolBase`](ue_ue.MovieSceneAudioCaptureProtocolBase.md)

___

### FindImageCaptureProtocol

▸ `Static` **FindImageCaptureProtocol**(): [`MovieSceneImageCaptureProtocolBase`](ue_ue.MovieSceneImageCaptureProtocolBase.md)

#### Returns

[`MovieSceneImageCaptureProtocolBase`](ue_ue.MovieSceneImageCaptureProtocolBase.md)

___

### GetCaptureElapsedTime

▸ `Static` **GetCaptureElapsedTime**(): `number`

#### Returns

`number`

___

### GetCaptureFrameNumber

▸ `Static` **GetCaptureFrameNumber**(): `number`

#### Returns

`number`

___

### IsCaptureInProgress

▸ `Static` **IsCaptureInProgress**(): `boolean`

#### Returns

`boolean`

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneCaptureEnvironment`](ue_ue.MovieSceneCaptureEnvironment.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneCaptureEnvironment`](ue_ue.MovieSceneCaptureEnvironment.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
