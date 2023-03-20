[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AudioMixerBlueprintLibrary

# Class: AudioMixerBlueprintLibrary

[ue/ue](../modules/ue_ue.md).AudioMixerBlueprintLibrary

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`AudioMixerBlueprintLibrary`**

## Table of contents

### Constructors

- [constructor](ue_ue.AudioMixerBlueprintLibrary.md#constructor)

### Properties

- [\_\_tid\_AudioMixerBlueprintLibrary\_\_](ue_ue.AudioMixerBlueprintLibrary.md#__tid_audiomixerblueprintlibrary__)
- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.AudioMixerBlueprintLibrary.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_Object\_\_](ue_ue.AudioMixerBlueprintLibrary.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AudioMixerBlueprintLibrary.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AudioMixerBlueprintLibrary.md#executeubergraph)
- [GetClass](ue_ue.AudioMixerBlueprintLibrary.md#getclass)
- [GetName](ue_ue.AudioMixerBlueprintLibrary.md#getname)
- [GetOuter](ue_ue.AudioMixerBlueprintLibrary.md#getouter)
- [GetWorld](ue_ue.AudioMixerBlueprintLibrary.md#getworld)
- [AddMasterSubmixEffect](ue_ue.AudioMixerBlueprintLibrary.md#addmastersubmixeffect)
- [AddSourceEffectToPresetChain](ue_ue.AudioMixerBlueprintLibrary.md#addsourceeffecttopresetchain)
- [ClearMasterSubmixEffects](ue_ue.AudioMixerBlueprintLibrary.md#clearmastersubmixeffects)
- [Find](ue_ue.AudioMixerBlueprintLibrary.md#find)
- [GetMagnitudeForFrequencies](ue_ue.AudioMixerBlueprintLibrary.md#getmagnitudeforfrequencies)
- [GetNumberOfEntriesInSourceEffectChain](ue_ue.AudioMixerBlueprintLibrary.md#getnumberofentriesinsourceeffectchain)
- [GetPhaseForFrequencies](ue_ue.AudioMixerBlueprintLibrary.md#getphaseforfrequencies)
- [Load](ue_ue.AudioMixerBlueprintLibrary.md#load)
- [PauseRecordingOutput](ue_ue.AudioMixerBlueprintLibrary.md#pauserecordingoutput)
- [PrimeSoundCueForPlayback](ue_ue.AudioMixerBlueprintLibrary.md#primesoundcueforplayback)
- [PrimeSoundForPlayback](ue_ue.AudioMixerBlueprintLibrary.md#primesoundforplayback)
- [RemoveMasterSubmixEffect](ue_ue.AudioMixerBlueprintLibrary.md#removemastersubmixeffect)
- [RemoveSourceEffectFromPresetChain](ue_ue.AudioMixerBlueprintLibrary.md#removesourceeffectfrompresetchain)
- [ResumeRecordingOutput](ue_ue.AudioMixerBlueprintLibrary.md#resumerecordingoutput)
- [SetBypassSourceEffectChainEntry](ue_ue.AudioMixerBlueprintLibrary.md#setbypasssourceeffectchainentry)
- [StartAnalyzingOutput](ue_ue.AudioMixerBlueprintLibrary.md#startanalyzingoutput)
- [StartRecordingOutput](ue_ue.AudioMixerBlueprintLibrary.md#startrecordingoutput)
- [StaticClass](ue_ue.AudioMixerBlueprintLibrary.md#staticclass)
- [StopAnalyzingOutput](ue_ue.AudioMixerBlueprintLibrary.md#stopanalyzingoutput)
- [StopRecordingOutput](ue_ue.AudioMixerBlueprintLibrary.md#stoprecordingoutput)
- [TrimAudioCache](ue_ue.AudioMixerBlueprintLibrary.md#trimaudiocache)

## Constructors

### constructor

• **new AudioMixerBlueprintLibrary**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

## Properties

### \_\_tid\_AudioMixerBlueprintLibrary\_\_

• **\_\_tid\_AudioMixerBlueprintLibrary\_\_**: `boolean`

___

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

___

### AddMasterSubmixEffect

▸ `Static` **AddMasterSubmixEffect**(`WorldContextObject`, `SubmixEffectPreset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `SubmixEffectPreset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundEffectSubmixPreset`](ue_ue.SoundEffectSubmixPreset.md)\> |

#### Returns

`void`

___

### AddSourceEffectToPresetChain

▸ `Static` **AddSourceEffectToPresetChain**(`WorldContextObject`, `PresetChain`, `Entry`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PresetChain` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundEffectSourcePresetChain`](ue_ue.SoundEffectSourcePresetChain.md)\> |
| `Entry` | [`SourceEffectChainEntry`](ue_ue.SourceEffectChainEntry.md) |

#### Returns

`void`

___

### ClearMasterSubmixEffects

▸ `Static` **ClearMasterSubmixEffects**(`WorldContextObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AudioMixerBlueprintLibrary`](ue_ue.AudioMixerBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AudioMixerBlueprintLibrary`](ue_ue.AudioMixerBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

___

### GetMagnitudeForFrequencies

▸ `Static` **GetMagnitudeForFrequencies**(`WorldContextObject`, `Frequencies`, `Magnitudes`, `SubmixToAnalyze?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Frequencies` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `Magnitudes` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>\> |
| `SubmixToAnalyze?` | [`SoundSubmix`](ue_ue.SoundSubmix.md) |

#### Returns

`void`

___

### GetNumberOfEntriesInSourceEffectChain

▸ `Static` **GetNumberOfEntriesInSourceEffectChain**(`WorldContextObject`, `PresetChain`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PresetChain` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundEffectSourcePresetChain`](ue_ue.SoundEffectSourcePresetChain.md)\> |

#### Returns

`number`

___

### GetPhaseForFrequencies

▸ `Static` **GetPhaseForFrequencies**(`WorldContextObject`, `Frequencies`, `Phases`, `SubmixToAnalyze?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Frequencies` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `Phases` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>\> |
| `SubmixToAnalyze?` | [`SoundSubmix`](ue_ue.SoundSubmix.md) |

#### Returns

`void`

___

### Load

▸ `Static` **Load**(`InName`): [`AudioMixerBlueprintLibrary`](ue_ue.AudioMixerBlueprintLibrary.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AudioMixerBlueprintLibrary`](ue_ue.AudioMixerBlueprintLibrary.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

___

### PauseRecordingOutput

▸ `Static` **PauseRecordingOutput**(`WorldContextObject`, `SubmixToPause?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `SubmixToPause?` | [`SoundSubmix`](ue_ue.SoundSubmix.md) |

#### Returns

`void`

___

### PrimeSoundCueForPlayback

▸ `Static` **PrimeSoundCueForPlayback**(`SoundCue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SoundCue` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundCue`](ue_ue.SoundCue.md)\> |

#### Returns

`void`

___

### PrimeSoundForPlayback

▸ `Static` **PrimeSoundForPlayback**(`SoundWave`, `OnLoadCompletion`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SoundWave` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundWave`](ue_ue.SoundWave.md)\> |
| `OnLoadCompletion` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`LoadedSoundWave`: [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundWave`](ue_ue.SoundWave.md)\>, `WasCancelled`: `boolean`) => `void`\> |

#### Returns

`void`

___

### RemoveMasterSubmixEffect

▸ `Static` **RemoveMasterSubmixEffect**(`WorldContextObject`, `SubmixEffectPreset`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `SubmixEffectPreset` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundEffectSubmixPreset`](ue_ue.SoundEffectSubmixPreset.md)\> |

#### Returns

`void`

___

### RemoveSourceEffectFromPresetChain

▸ `Static` **RemoveSourceEffectFromPresetChain**(`WorldContextObject`, `PresetChain`, `EntryIndex`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PresetChain` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundEffectSourcePresetChain`](ue_ue.SoundEffectSourcePresetChain.md)\> |
| `EntryIndex` | `number` |

#### Returns

`void`

___

### ResumeRecordingOutput

▸ `Static` **ResumeRecordingOutput**(`WorldContextObject`, `SubmixToPause?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `SubmixToPause?` | [`SoundSubmix`](ue_ue.SoundSubmix.md) |

#### Returns

`void`

___

### SetBypassSourceEffectChainEntry

▸ `Static` **SetBypassSourceEffectChainEntry**(`WorldContextObject`, `PresetChain`, `EntryIndex`, `bBypassed`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PresetChain` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundEffectSourcePresetChain`](ue_ue.SoundEffectSourcePresetChain.md)\> |
| `EntryIndex` | `number` |
| `bBypassed` | `boolean` |

#### Returns

`void`

___

### StartAnalyzingOutput

▸ `Static` **StartAnalyzingOutput**(`WorldContextObject`, `SubmixToAnalyze?`, `FFTSize?`, `InterpolationMethod?`, `WindowType?`, `HopSize?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `SubmixToAnalyze?` | [`SoundSubmix`](ue_ue.SoundSubmix.md) |
| `FFTSize?` | [`EFFTSize`](../enums/ue_ue.EFFTSize.md) |
| `InterpolationMethod?` | [`EFFTPeakInterpolationMethod`](../enums/ue_ue.EFFTPeakInterpolationMethod.md) |
| `WindowType?` | [`EFFTWindowType`](../enums/ue_ue.EFFTWindowType.md) |
| `HopSize?` | `number` |

#### Returns

`void`

___

### StartRecordingOutput

▸ `Static` **StartRecordingOutput**(`WorldContextObject`, `ExpectedDuration`, `SubmixToRecord?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ExpectedDuration` | `number` |
| `SubmixToRecord?` | [`SoundSubmix`](ue_ue.SoundSubmix.md) |

#### Returns

`void`

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

___

### StopAnalyzingOutput

▸ `Static` **StopAnalyzingOutput**(`WorldContextObject`, `SubmixToStopAnalyzing?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `SubmixToStopAnalyzing?` | [`SoundSubmix`](ue_ue.SoundSubmix.md) |

#### Returns

`void`

___

### StopRecordingOutput

▸ `Static` **StopRecordingOutput**(`WorldContextObject`, `ExportType`, `Name`, `Path`, `SubmixToRecord?`, `ExistingSoundWaveToOverwrite?`): [`SoundWave`](ue_ue.SoundWave.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ExportType` | [`EAudioRecordingExportType`](../enums/ue_ue.EAudioRecordingExportType.md) |
| `Name` | `string` |
| `Path` | `string` |
| `SubmixToRecord?` | [`SoundSubmix`](ue_ue.SoundSubmix.md) |
| `ExistingSoundWaveToOverwrite?` | [`SoundWave`](ue_ue.SoundWave.md) |

#### Returns

[`SoundWave`](ue_ue.SoundWave.md)

___

### TrimAudioCache

▸ `Static` **TrimAudioCache**(`InMegabytesToFree`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InMegabytesToFree` | `number` |

#### Returns

`number`
