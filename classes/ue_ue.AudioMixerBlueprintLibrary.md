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

#### Defined in

[ue/ue.d.ts:22428](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22428)

## Properties

### \_\_tid\_AudioMixerBlueprintLibrary\_\_

• **\_\_tid\_AudioMixerBlueprintLibrary\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:22451](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22451)

___

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:22429](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22429)

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

#### Defined in

[ue/ue.d.ts:22430](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22430)

___

### ClearMasterSubmixEffects

▸ `Static` **ClearMasterSubmixEffects**(`WorldContextObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22431](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22431)

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

#### Defined in

[ue/ue.d.ts:22448](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22448)

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

#### Defined in

[ue/ue.d.ts:22432](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22432)

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

#### Defined in

[ue/ue.d.ts:22433](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22433)

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

#### Defined in

[ue/ue.d.ts:22434](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22434)

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

#### Defined in

[ue/ue.d.ts:22449](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22449)

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

#### Defined in

[ue/ue.d.ts:22435](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22435)

___

### PrimeSoundCueForPlayback

▸ `Static` **PrimeSoundCueForPlayback**(`SoundCue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SoundCue` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundCue`](ue_ue.SoundCue.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:22436](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22436)

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

#### Defined in

[ue/ue.d.ts:22437](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22437)

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

#### Defined in

[ue/ue.d.ts:22438](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22438)

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

#### Defined in

[ue/ue.d.ts:22439](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22439)

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

#### Defined in

[ue/ue.d.ts:22440](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22440)

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

#### Defined in

[ue/ue.d.ts:22441](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22441)

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

#### Defined in

[ue/ue.d.ts:22442](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22442)

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

#### Defined in

[ue/ue.d.ts:22443](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22443)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:22447](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22447)

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

#### Defined in

[ue/ue.d.ts:22444](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22444)

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

#### Defined in

[ue/ue.d.ts:22445](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22445)

___

### TrimAudioCache

▸ `Static` **TrimAudioCache**(`InMegabytesToFree`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InMegabytesToFree` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:22446](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L22446)
