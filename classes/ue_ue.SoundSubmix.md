[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundSubmix

# Class: SoundSubmix

[ue/ue](../modules/ue_ue.md).SoundSubmix

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SoundSubmix`**

## Table of contents

### Constructors

- [constructor](ue_ue.SoundSubmix.md#constructor)

### Properties

- [AmbisonicsPluginSettings](ue_ue.SoundSubmix.md#ambisonicspluginsettings)
- [ChannelFormat](ue_ue.SoundSubmix.md#channelformat)
- [ChildSubmixes](ue_ue.SoundSubmix.md#childsubmixes)
- [EnvelopeFollowerAttackTime](ue_ue.SoundSubmix.md#envelopefollowerattacktime)
- [EnvelopeFollowerReleaseTime](ue_ue.SoundSubmix.md#envelopefollowerreleasetime)
- [OnSubmixRecordedFileDone](ue_ue.SoundSubmix.md#onsubmixrecordedfiledone)
- [OutputVolume](ue_ue.SoundSubmix.md#outputvolume)
- [ParentSubmix](ue_ue.SoundSubmix.md#parentsubmix)
- [SubmixEffectChain](ue_ue.SoundSubmix.md#submixeffectchain)
- [\_\_tid\_Object\_\_](ue_ue.SoundSubmix.md#__tid_object__)
- [\_\_tid\_SoundSubmix\_\_](ue_ue.SoundSubmix.md#__tid_soundsubmix__)
- [bMuteWhenBackgrounded](ue_ue.SoundSubmix.md#bmutewhenbackgrounded)

### Methods

- [AddEnvelopeFollowerDelegate](ue_ue.SoundSubmix.md#addenvelopefollowerdelegate)
- [CreateDefaultSubobject](ue_ue.SoundSubmix.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundSubmix.md#executeubergraph)
- [GetClass](ue_ue.SoundSubmix.md#getclass)
- [GetName](ue_ue.SoundSubmix.md#getname)
- [GetOuter](ue_ue.SoundSubmix.md#getouter)
- [GetWorld](ue_ue.SoundSubmix.md#getworld)
- [SetSubmixOutputVolume](ue_ue.SoundSubmix.md#setsubmixoutputvolume)
- [StartEnvelopeFollowing](ue_ue.SoundSubmix.md#startenvelopefollowing)
- [StartRecordingOutput](ue_ue.SoundSubmix.md#startrecordingoutput)
- [StopEnvelopeFollowing](ue_ue.SoundSubmix.md#stopenvelopefollowing)
- [StopRecordingOutput](ue_ue.SoundSubmix.md#stoprecordingoutput)
- [Find](ue_ue.SoundSubmix.md#find)
- [Load](ue_ue.SoundSubmix.md#load)
- [StaticClass](ue_ue.SoundSubmix.md#staticclass)

## Constructors

### constructor

• **new SoundSubmix**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### AmbisonicsPluginSettings

• **AmbisonicsPluginSettings**: [`AmbisonicsSubmixSettingsBase`](ue_ue.AmbisonicsSubmixSettingsBase.md)

___

### ChannelFormat

• **ChannelFormat**: [`ESubmixChannelFormat`](../enums/ue_ue.ESubmixChannelFormat.md)

___

### ChildSubmixes

• **ChildSubmixes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSubmix`](ue_ue.SoundSubmix.md)\>

___

### EnvelopeFollowerAttackTime

• **EnvelopeFollowerAttackTime**: `number`

___

### EnvelopeFollowerReleaseTime

• **EnvelopeFollowerReleaseTime**: `number`

___

### OnSubmixRecordedFileDone

• **OnSubmixRecordedFileDone**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`ResultingSoundWave`: [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundWave`](ue_ue.SoundWave.md)\>) => `void`\>

___

### OutputVolume

• **OutputVolume**: `number`

___

### ParentSubmix

• **ParentSubmix**: [`SoundSubmix`](ue_ue.SoundSubmix.md)

___

### SubmixEffectChain

• **SubmixEffectChain**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundEffectSubmixPreset`](ue_ue.SoundEffectSubmixPreset.md)\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_SoundSubmix\_\_

• **\_\_tid\_SoundSubmix\_\_**: `boolean`

___

### bMuteWhenBackgrounded

• **bMuteWhenBackgrounded**: `boolean`

## Methods

### AddEnvelopeFollowerDelegate

▸ **AddEnvelopeFollowerDelegate**(`WorldContextObject`, `OnSubmixEnvelopeBP`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `OnSubmixEnvelopeBP` | [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`Envelope`: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>) => `void`\> |

#### Returns

`void`

___

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

### SetSubmixOutputVolume

▸ **SetSubmixOutputVolume**(`WorldContextObject`, `InOutputVolume`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `InOutputVolume` | `number` |

#### Returns

`void`

___

### StartEnvelopeFollowing

▸ **StartEnvelopeFollowing**(`WorldContextObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### StartRecordingOutput

▸ **StartRecordingOutput**(`WorldContextObject`, `ExpectedDuration`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ExpectedDuration` | `number` |

#### Returns

`void`

___

### StopEnvelopeFollowing

▸ **StopEnvelopeFollowing**(`WorldContextObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

___

### StopRecordingOutput

▸ **StopRecordingOutput**(`WorldContextObject`, `ExportType`, `Name`, `Path`, `ExistingSoundWaveToOverwrite?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ExportType` | [`EAudioRecordingExportType`](../enums/ue_ue.EAudioRecordingExportType.md) |
| `Name` | `string` |
| `Path` | `string` |
| `ExistingSoundWaveToOverwrite?` | [`SoundWave`](ue_ue.SoundWave.md) |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundSubmix`](ue_ue.SoundSubmix.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundSubmix`](ue_ue.SoundSubmix.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundSubmix`](ue_ue.SoundSubmix.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundSubmix`](ue_ue.SoundSubmix.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
