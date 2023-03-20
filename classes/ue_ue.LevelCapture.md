[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LevelCapture

# Class: LevelCapture

[ue/ue](../modules/ue_ue.md).LevelCapture

## Hierarchy

- [`MovieSceneCapture`](ue_ue.MovieSceneCapture.md)

  ↳ **`LevelCapture`**

## Table of contents

### Constructors

- [constructor](ue_ue.LevelCapture.md#constructor)

### Properties

- [AdditionalCommandLineArguments](ue_ue.LevelCapture.md#additionalcommandlinearguments)
- [AudioCaptureProtocol](ue_ue.LevelCapture.md#audiocaptureprotocol)
- [AudioCaptureProtocolType](ue_ue.LevelCapture.md#audiocaptureprotocoltype)
- [ImageCaptureProtocol](ue_ue.LevelCapture.md#imagecaptureprotocol)
- [ImageCaptureProtocolType](ue_ue.LevelCapture.md#imagecaptureprotocoltype)
- [InheritedCommandLineArguments](ue_ue.LevelCapture.md#inheritedcommandlinearguments)
- [PrerequisiteActorId](ue_ue.LevelCapture.md#prerequisiteactorid)
- [Settings](ue_ue.LevelCapture.md#settings)
- [\_\_tid\_LevelCapture\_\_](ue_ue.LevelCapture.md#__tid_levelcapture__)
- [\_\_tid\_MovieSceneCapture\_\_](ue_ue.LevelCapture.md#__tid_moviescenecapture__)
- [\_\_tid\_Object\_\_](ue_ue.LevelCapture.md#__tid_object__)
- [bAutoStartCapture](ue_ue.LevelCapture.md#bautostartcapture)
- [bCloseEditorWhenCaptureStarts](ue_ue.LevelCapture.md#bcloseeditorwhencapturestarts)
- [bUseSeparateProcess](ue_ue.LevelCapture.md#buseseparateprocess)

### Methods

- [CreateDefaultSubobject](ue_ue.LevelCapture.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.LevelCapture.md#executeubergraph)
- [GetAudioCaptureProtocol](ue_ue.LevelCapture.md#getaudiocaptureprotocol)
- [GetClass](ue_ue.LevelCapture.md#getclass)
- [GetImageCaptureProtocol](ue_ue.LevelCapture.md#getimagecaptureprotocol)
- [GetName](ue_ue.LevelCapture.md#getname)
- [GetOuter](ue_ue.LevelCapture.md#getouter)
- [GetWorld](ue_ue.LevelCapture.md#getworld)
- [SetAudioCaptureProtocolType](ue_ue.LevelCapture.md#setaudiocaptureprotocoltype)
- [SetImageCaptureProtocolType](ue_ue.LevelCapture.md#setimagecaptureprotocoltype)
- [Find](ue_ue.LevelCapture.md#find)
- [Load](ue_ue.LevelCapture.md#load)
- [StaticClass](ue_ue.LevelCapture.md#staticclass)

## Constructors

### constructor

• **new LevelCapture**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[constructor](ue_ue.MovieSceneCapture.md#constructor)

#### Defined in

[ue/ue.d.ts:44760](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44760)

## Properties

### AdditionalCommandLineArguments

• **AdditionalCommandLineArguments**: `string`

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[AdditionalCommandLineArguments](ue_ue.MovieSceneCapture.md#additionalcommandlinearguments)

#### Defined in

[ue/ue.d.ts:22620](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22620)

___

### AudioCaptureProtocol

• **AudioCaptureProtocol**: [`MovieSceneAudioCaptureProtocolBase`](ue_ue.MovieSceneAudioCaptureProtocolBase.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[AudioCaptureProtocol](ue_ue.MovieSceneCapture.md#audiocaptureprotocol)

#### Defined in

[ue/ue.d.ts:22616](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22616)

___

### AudioCaptureProtocolType

• **AudioCaptureProtocolType**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[AudioCaptureProtocolType](ue_ue.MovieSceneCapture.md#audiocaptureprotocoltype)

#### Defined in

[ue/ue.d.ts:22614](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22614)

___

### ImageCaptureProtocol

• **ImageCaptureProtocol**: [`MovieSceneImageCaptureProtocolBase`](ue_ue.MovieSceneImageCaptureProtocolBase.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[ImageCaptureProtocol](ue_ue.MovieSceneCapture.md#imagecaptureprotocol)

#### Defined in

[ue/ue.d.ts:22615](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22615)

___

### ImageCaptureProtocolType

• **ImageCaptureProtocolType**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[ImageCaptureProtocolType](ue_ue.MovieSceneCapture.md#imagecaptureprotocoltype)

#### Defined in

[ue/ue.d.ts:22613](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22613)

___

### InheritedCommandLineArguments

• **InheritedCommandLineArguments**: `string`

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[InheritedCommandLineArguments](ue_ue.MovieSceneCapture.md#inheritedcommandlinearguments)

#### Defined in

[ue/ue.d.ts:22621](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22621)

___

### PrerequisiteActorId

• **PrerequisiteActorId**: [`Guid`](ue_ue_s.Guid.md)

#### Defined in

[ue/ue.d.ts:44762](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44762)

___

### Settings

• **Settings**: [`MovieSceneCaptureSettings`](ue_ue.MovieSceneCaptureSettings.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[Settings](ue_ue.MovieSceneCapture.md#settings)

#### Defined in

[ue/ue.d.ts:22617](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22617)

___

### \_\_tid\_LevelCapture\_\_

• **\_\_tid\_LevelCapture\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:44767](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44767)

___

### \_\_tid\_MovieSceneCapture\_\_

• **\_\_tid\_MovieSceneCapture\_\_**: `boolean`

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[__tid_MovieSceneCapture__](ue_ue.MovieSceneCapture.md#__tid_moviescenecapture__)

#### Defined in

[ue/ue.d.ts:22630](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22630)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[__tid_Object__](ue_ue.MovieSceneCapture.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### bAutoStartCapture

• **bAutoStartCapture**: `boolean`

#### Defined in

[ue/ue.d.ts:44761](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44761)

___

### bCloseEditorWhenCaptureStarts

• **bCloseEditorWhenCaptureStarts**: `boolean`

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[bCloseEditorWhenCaptureStarts](ue_ue.MovieSceneCapture.md#bcloseeditorwhencapturestarts)

#### Defined in

[ue/ue.d.ts:22619](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22619)

___

### bUseSeparateProcess

• **bUseSeparateProcess**: `boolean`

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[bUseSeparateProcess](ue_ue.MovieSceneCapture.md#buseseparateprocess)

#### Defined in

[ue/ue.d.ts:22618](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22618)

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

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[CreateDefaultSubobject](ue_ue.MovieSceneCapture.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[ExecuteUbergraph](ue_ue.MovieSceneCapture.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetAudioCaptureProtocol

▸ **GetAudioCaptureProtocol**(): [`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

#### Returns

[`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[GetAudioCaptureProtocol](ue_ue.MovieSceneCapture.md#getaudiocaptureprotocol)

#### Defined in

[ue/ue.d.ts:22622](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22622)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[GetClass](ue_ue.MovieSceneCapture.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetImageCaptureProtocol

▸ **GetImageCaptureProtocol**(): [`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

#### Returns

[`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[GetImageCaptureProtocol](ue_ue.MovieSceneCapture.md#getimagecaptureprotocol)

#### Defined in

[ue/ue.d.ts:22623](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22623)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[GetName](ue_ue.MovieSceneCapture.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[GetOuter](ue_ue.MovieSceneCapture.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[GetWorld](ue_ue.MovieSceneCapture.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### SetAudioCaptureProtocolType

▸ **SetAudioCaptureProtocolType**(`ProtocolType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ProtocolType` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[SetAudioCaptureProtocolType](ue_ue.MovieSceneCapture.md#setaudiocaptureprotocoltype)

#### Defined in

[ue/ue.d.ts:22624](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22624)

___

### SetImageCaptureProtocolType

▸ **SetImageCaptureProtocolType**(`ProtocolType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ProtocolType` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`void`

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[SetImageCaptureProtocolType](ue_ue.MovieSceneCapture.md#setimagecaptureprotocoltype)

#### Defined in

[ue/ue.d.ts:22625](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L22625)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LevelCapture`](ue_ue.LevelCapture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LevelCapture`](ue_ue.LevelCapture.md)

#### Overrides

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[Find](ue_ue.MovieSceneCapture.md#find)

#### Defined in

[ue/ue.d.ts:44764](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44764)

___

### Load

▸ `Static` **Load**(`InName`): [`LevelCapture`](ue_ue.LevelCapture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LevelCapture`](ue_ue.LevelCapture.md)

#### Overrides

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[Load](ue_ue.MovieSceneCapture.md#load)

#### Defined in

[ue/ue.d.ts:44765](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44765)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[StaticClass](ue_ue.MovieSceneCapture.md#staticclass)

#### Defined in

[ue/ue.d.ts:44763](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L44763)
