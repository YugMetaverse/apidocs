[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MovieSceneCapture

# Class: MovieSceneCapture

[ue/ue](../modules/ue_ue.md).MovieSceneCapture

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`MovieSceneCapture`**

  ↳↳ [`AutomatedLevelSequenceCapture`](ue_ue.AutomatedLevelSequenceCapture.md)

  ↳↳ [`LevelCapture`](ue_ue.LevelCapture.md)

## Table of contents

### Constructors

- [constructor](ue_ue.MovieSceneCapture.md#constructor)

### Properties

- [AdditionalCommandLineArguments](ue_ue.MovieSceneCapture.md#additionalcommandlinearguments)
- [AudioCaptureProtocol](ue_ue.MovieSceneCapture.md#audiocaptureprotocol)
- [AudioCaptureProtocolType](ue_ue.MovieSceneCapture.md#audiocaptureprotocoltype)
- [ImageCaptureProtocol](ue_ue.MovieSceneCapture.md#imagecaptureprotocol)
- [ImageCaptureProtocolType](ue_ue.MovieSceneCapture.md#imagecaptureprotocoltype)
- [InheritedCommandLineArguments](ue_ue.MovieSceneCapture.md#inheritedcommandlinearguments)
- [Settings](ue_ue.MovieSceneCapture.md#settings)
- [\_\_tid\_MovieSceneCapture\_\_](ue_ue.MovieSceneCapture.md#__tid_moviescenecapture__)
- [\_\_tid\_Object\_\_](ue_ue.MovieSceneCapture.md#__tid_object__)
- [bCloseEditorWhenCaptureStarts](ue_ue.MovieSceneCapture.md#bcloseeditorwhencapturestarts)
- [bUseSeparateProcess](ue_ue.MovieSceneCapture.md#buseseparateprocess)

### Methods

- [CreateDefaultSubobject](ue_ue.MovieSceneCapture.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MovieSceneCapture.md#executeubergraph)
- [GetAudioCaptureProtocol](ue_ue.MovieSceneCapture.md#getaudiocaptureprotocol)
- [GetClass](ue_ue.MovieSceneCapture.md#getclass)
- [GetImageCaptureProtocol](ue_ue.MovieSceneCapture.md#getimagecaptureprotocol)
- [GetName](ue_ue.MovieSceneCapture.md#getname)
- [GetOuter](ue_ue.MovieSceneCapture.md#getouter)
- [GetWorld](ue_ue.MovieSceneCapture.md#getworld)
- [SetAudioCaptureProtocolType](ue_ue.MovieSceneCapture.md#setaudiocaptureprotocoltype)
- [SetImageCaptureProtocolType](ue_ue.MovieSceneCapture.md#setimagecaptureprotocoltype)
- [Find](ue_ue.MovieSceneCapture.md#find)
- [Load](ue_ue.MovieSceneCapture.md#load)
- [StaticClass](ue_ue.MovieSceneCapture.md#staticclass)

## Constructors

### constructor

• **new MovieSceneCapture**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AdditionalCommandLineArguments

• **AdditionalCommandLineArguments**: `string`

___

### AudioCaptureProtocol

• **AudioCaptureProtocol**: [`MovieSceneAudioCaptureProtocolBase`](ue_ue.MovieSceneAudioCaptureProtocolBase.md)

___

### AudioCaptureProtocolType

• **AudioCaptureProtocolType**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### ImageCaptureProtocol

• **ImageCaptureProtocol**: [`MovieSceneImageCaptureProtocolBase`](ue_ue.MovieSceneImageCaptureProtocolBase.md)

___

### ImageCaptureProtocolType

• **ImageCaptureProtocolType**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

___

### InheritedCommandLineArguments

• **InheritedCommandLineArguments**: `string`

___

### Settings

• **Settings**: [`MovieSceneCaptureSettings`](ue_ue.MovieSceneCaptureSettings.md)

___

### \_\_tid\_MovieSceneCapture\_\_

• **\_\_tid\_MovieSceneCapture\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### bCloseEditorWhenCaptureStarts

• **bCloseEditorWhenCaptureStarts**: `boolean`

___

### bUseSeparateProcess

• **bUseSeparateProcess**: `boolean`

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

### GetAudioCaptureProtocol

▸ **GetAudioCaptureProtocol**(): [`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

#### Returns

[`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetImageCaptureProtocol

▸ **GetImageCaptureProtocol**(): [`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

#### Returns

[`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

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

### SetAudioCaptureProtocolType

▸ **SetAudioCaptureProtocolType**(`ProtocolType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ProtocolType` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

___

### SetImageCaptureProtocolType

▸ **SetImageCaptureProtocolType**(`ProtocolType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ProtocolType` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MovieSceneCapture`](ue_ue.MovieSceneCapture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MovieSceneCapture`](ue_ue.MovieSceneCapture.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MovieSceneCapture`](ue_ue.MovieSceneCapture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MovieSceneCapture`](ue_ue.MovieSceneCapture.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
