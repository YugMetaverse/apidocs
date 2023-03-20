[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AutomatedLevelSequenceCapture

# Class: AutomatedLevelSequenceCapture

[ue/ue](../modules/ue_ue.md).AutomatedLevelSequenceCapture

## Hierarchy

- [`MovieSceneCapture`](ue_ue.MovieSceneCapture.md)

  ↳ **`AutomatedLevelSequenceCapture`**

## Table of contents

### Constructors

- [constructor](ue_ue.AutomatedLevelSequenceCapture.md#constructor)

### Properties

- [AdditionalCommandLineArguments](ue_ue.AutomatedLevelSequenceCapture.md#additionalcommandlinearguments)
- [AudioCaptureProtocol](ue_ue.AutomatedLevelSequenceCapture.md#audiocaptureprotocol)
- [AudioCaptureProtocolType](ue_ue.AutomatedLevelSequenceCapture.md#audiocaptureprotocoltype)
- [BurnInOptions](ue_ue.AutomatedLevelSequenceCapture.md#burninoptions)
- [CustomEndFrame](ue_ue.AutomatedLevelSequenceCapture.md#customendframe)
- [CustomStartFrame](ue_ue.AutomatedLevelSequenceCapture.md#customstartframe)
- [DelayBeforeShotWarmUp](ue_ue.AutomatedLevelSequenceCapture.md#delaybeforeshotwarmup)
- [DelayBeforeWarmUp](ue_ue.AutomatedLevelSequenceCapture.md#delaybeforewarmup)
- [DelayEveryFrame](ue_ue.AutomatedLevelSequenceCapture.md#delayeveryframe)
- [ImageCaptureProtocol](ue_ue.AutomatedLevelSequenceCapture.md#imagecaptureprotocol)
- [ImageCaptureProtocolType](ue_ue.AutomatedLevelSequenceCapture.md#imagecaptureprotocoltype)
- [InheritedCommandLineArguments](ue_ue.AutomatedLevelSequenceCapture.md#inheritedcommandlinearguments)
- [LevelSequenceActor](ue_ue.AutomatedLevelSequenceCapture.md#levelsequenceactor)
- [LevelSequenceAsset](ue_ue.AutomatedLevelSequenceCapture.md#levelsequenceasset)
- [Settings](ue_ue.AutomatedLevelSequenceCapture.md#settings)
- [ShotName](ue_ue.AutomatedLevelSequenceCapture.md#shotname)
- [WarmUpFrameCount](ue_ue.AutomatedLevelSequenceCapture.md#warmupframecount)
- [\_\_tid\_AutomatedLevelSequenceCapture\_\_](ue_ue.AutomatedLevelSequenceCapture.md#__tid_automatedlevelsequencecapture__)
- [\_\_tid\_MovieSceneCapture\_\_](ue_ue.AutomatedLevelSequenceCapture.md#__tid_moviescenecapture__)
- [\_\_tid\_Object\_\_](ue_ue.AutomatedLevelSequenceCapture.md#__tid_object__)
- [bCloseEditorWhenCaptureStarts](ue_ue.AutomatedLevelSequenceCapture.md#bcloseeditorwhencapturestarts)
- [bUseCustomEndFrame](ue_ue.AutomatedLevelSequenceCapture.md#busecustomendframe)
- [bUseCustomStartFrame](ue_ue.AutomatedLevelSequenceCapture.md#busecustomstartframe)
- [bUseSeparateProcess](ue_ue.AutomatedLevelSequenceCapture.md#buseseparateprocess)
- [bWriteEditDecisionList](ue_ue.AutomatedLevelSequenceCapture.md#bwriteeditdecisionlist)
- [bWriteFinalCutProXML](ue_ue.AutomatedLevelSequenceCapture.md#bwritefinalcutproxml)

### Methods

- [CreateDefaultSubobject](ue_ue.AutomatedLevelSequenceCapture.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AutomatedLevelSequenceCapture.md#executeubergraph)
- [GetAudioCaptureProtocol](ue_ue.AutomatedLevelSequenceCapture.md#getaudiocaptureprotocol)
- [GetClass](ue_ue.AutomatedLevelSequenceCapture.md#getclass)
- [GetImageCaptureProtocol](ue_ue.AutomatedLevelSequenceCapture.md#getimagecaptureprotocol)
- [GetName](ue_ue.AutomatedLevelSequenceCapture.md#getname)
- [GetOuter](ue_ue.AutomatedLevelSequenceCapture.md#getouter)
- [GetWorld](ue_ue.AutomatedLevelSequenceCapture.md#getworld)
- [SetAudioCaptureProtocolType](ue_ue.AutomatedLevelSequenceCapture.md#setaudiocaptureprotocoltype)
- [SetImageCaptureProtocolType](ue_ue.AutomatedLevelSequenceCapture.md#setimagecaptureprotocoltype)
- [Find](ue_ue.AutomatedLevelSequenceCapture.md#find)
- [Load](ue_ue.AutomatedLevelSequenceCapture.md#load)
- [StaticClass](ue_ue.AutomatedLevelSequenceCapture.md#staticclass)

## Constructors

### constructor

• **new AutomatedLevelSequenceCapture**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[constructor](ue_ue.MovieSceneCapture.md#constructor)

## Properties

### AdditionalCommandLineArguments

• **AdditionalCommandLineArguments**: `string`

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[AdditionalCommandLineArguments](ue_ue.MovieSceneCapture.md#additionalcommandlinearguments)

___

### AudioCaptureProtocol

• **AudioCaptureProtocol**: [`MovieSceneAudioCaptureProtocolBase`](ue_ue.MovieSceneAudioCaptureProtocolBase.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[AudioCaptureProtocol](ue_ue.MovieSceneCapture.md#audiocaptureprotocol)

___

### AudioCaptureProtocolType

• **AudioCaptureProtocolType**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[AudioCaptureProtocolType](ue_ue.MovieSceneCapture.md#audiocaptureprotocoltype)

___

### BurnInOptions

• **BurnInOptions**: [`LevelSequenceBurnInOptions`](ue_ue.LevelSequenceBurnInOptions.md)

___

### CustomEndFrame

• **CustomEndFrame**: [`FrameNumber`](ue_ue.FrameNumber.md)

___

### CustomStartFrame

• **CustomStartFrame**: [`FrameNumber`](ue_ue.FrameNumber.md)

___

### DelayBeforeShotWarmUp

• **DelayBeforeShotWarmUp**: `number`

___

### DelayBeforeWarmUp

• **DelayBeforeWarmUp**: `number`

___

### DelayEveryFrame

• **DelayEveryFrame**: `number`

___

### ImageCaptureProtocol

• **ImageCaptureProtocol**: [`MovieSceneImageCaptureProtocolBase`](ue_ue.MovieSceneImageCaptureProtocolBase.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[ImageCaptureProtocol](ue_ue.MovieSceneCapture.md#imagecaptureprotocol)

___

### ImageCaptureProtocolType

• **ImageCaptureProtocolType**: [`SoftClassPath`](ue_ue.SoftClassPath.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[ImageCaptureProtocolType](ue_ue.MovieSceneCapture.md#imagecaptureprotocoltype)

___

### InheritedCommandLineArguments

• **InheritedCommandLineArguments**: `string`

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[InheritedCommandLineArguments](ue_ue.MovieSceneCapture.md#inheritedcommandlinearguments)

___

### LevelSequenceActor

• **LevelSequenceActor**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`LevelSequenceActor`](ue_ue.LevelSequenceActor.md)\>

___

### LevelSequenceAsset

• **LevelSequenceAsset**: [`SoftObjectPath`](ue_ue.SoftObjectPath.md)

___

### Settings

• **Settings**: [`MovieSceneCaptureSettings`](ue_ue.MovieSceneCaptureSettings.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[Settings](ue_ue.MovieSceneCapture.md#settings)

___

### ShotName

• **ShotName**: `string`

___

### WarmUpFrameCount

• **WarmUpFrameCount**: `number`

___

### \_\_tid\_AutomatedLevelSequenceCapture\_\_

• **\_\_tid\_AutomatedLevelSequenceCapture\_\_**: `boolean`

___

### \_\_tid\_MovieSceneCapture\_\_

• **\_\_tid\_MovieSceneCapture\_\_**: `boolean`

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[__tid_MovieSceneCapture__](ue_ue.MovieSceneCapture.md#__tid_moviescenecapture__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[__tid_Object__](ue_ue.MovieSceneCapture.md#__tid_object__)

___

### bCloseEditorWhenCaptureStarts

• **bCloseEditorWhenCaptureStarts**: `boolean`

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[bCloseEditorWhenCaptureStarts](ue_ue.MovieSceneCapture.md#bcloseeditorwhencapturestarts)

___

### bUseCustomEndFrame

• **bUseCustomEndFrame**: `boolean`

___

### bUseCustomStartFrame

• **bUseCustomStartFrame**: `boolean`

___

### bUseSeparateProcess

• **bUseSeparateProcess**: `boolean`

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[bUseSeparateProcess](ue_ue.MovieSceneCapture.md#buseseparateprocess)

___

### bWriteEditDecisionList

• **bWriteEditDecisionList**: `boolean`

___

### bWriteFinalCutProXML

• **bWriteFinalCutProXML**: `boolean`

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

___

### GetAudioCaptureProtocol

▸ **GetAudioCaptureProtocol**(): [`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

#### Returns

[`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[GetAudioCaptureProtocol](ue_ue.MovieSceneCapture.md#getaudiocaptureprotocol)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[GetClass](ue_ue.MovieSceneCapture.md#getclass)

___

### GetImageCaptureProtocol

▸ **GetImageCaptureProtocol**(): [`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

#### Returns

[`MovieSceneCaptureProtocolBase`](ue_ue.MovieSceneCaptureProtocolBase.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[GetImageCaptureProtocol](ue_ue.MovieSceneCapture.md#getimagecaptureprotocol)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[GetName](ue_ue.MovieSceneCapture.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[GetOuter](ue_ue.MovieSceneCapture.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[GetWorld](ue_ue.MovieSceneCapture.md#getworld)

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

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AutomatedLevelSequenceCapture`](ue_ue.AutomatedLevelSequenceCapture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AutomatedLevelSequenceCapture`](ue_ue.AutomatedLevelSequenceCapture.md)

#### Overrides

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[Find](ue_ue.MovieSceneCapture.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AutomatedLevelSequenceCapture`](ue_ue.AutomatedLevelSequenceCapture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AutomatedLevelSequenceCapture`](ue_ue.AutomatedLevelSequenceCapture.md)

#### Overrides

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[Load](ue_ue.MovieSceneCapture.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[MovieSceneCapture](ue_ue.MovieSceneCapture.md).[StaticClass](ue_ue.MovieSceneCapture.md#staticclass)
