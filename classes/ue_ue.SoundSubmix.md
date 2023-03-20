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

#### Defined in

[ue/ue.d.ts:9605](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9605)

## Properties

### AmbisonicsPluginSettings

• **AmbisonicsPluginSettings**: [`AmbisonicsSubmixSettingsBase`](ue_ue.AmbisonicsSubmixSettingsBase.md)

#### Defined in

[ue/ue.d.ts:9611](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9611)

___

### ChannelFormat

• **ChannelFormat**: [`ESubmixChannelFormat`](../enums/ue_ue.ESubmixChannelFormat.md)

#### Defined in

[ue/ue.d.ts:9608](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9608)

___

### ChildSubmixes

• **ChildSubmixes**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSubmix`](ue_ue.SoundSubmix.md)\>

#### Defined in

[ue/ue.d.ts:9606](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9606)

___

### EnvelopeFollowerAttackTime

• **EnvelopeFollowerAttackTime**: `number`

#### Defined in

[ue/ue.d.ts:9612](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9612)

___

### EnvelopeFollowerReleaseTime

• **EnvelopeFollowerReleaseTime**: `number`

#### Defined in

[ue/ue.d.ts:9613](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9613)

___

### OnSubmixRecordedFileDone

• **OnSubmixRecordedFileDone**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`ResultingSoundWave`: [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundWave`](ue_ue.SoundWave.md)\>) => `void`\>

#### Defined in

[ue/ue.d.ts:9615](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9615)

___

### OutputVolume

• **OutputVolume**: `number`

#### Defined in

[ue/ue.d.ts:9614](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9614)

___

### ParentSubmix

• **ParentSubmix**: [`SoundSubmix`](ue_ue.SoundSubmix.md)

#### Defined in

[ue/ue.d.ts:9607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9607)

___

### SubmixEffectChain

• **SubmixEffectChain**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundEffectSubmixPreset`](ue_ue.SoundEffectSubmixPreset.md)\>

#### Defined in

[ue/ue.d.ts:9610](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9610)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SoundSubmix\_\_

• **\_\_tid\_SoundSubmix\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:9626](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9626)

___

### bMuteWhenBackgrounded

• **bMuteWhenBackgrounded**: `boolean`

#### Defined in

[ue/ue.d.ts:9609](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9609)

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

#### Defined in

[ue/ue.d.ts:9616](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9616)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:9617](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9617)

___

### StartEnvelopeFollowing

▸ **StartEnvelopeFollowing**(`WorldContextObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:9618](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9618)

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

#### Defined in

[ue/ue.d.ts:9619](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9619)

___

### StopEnvelopeFollowing

▸ **StopEnvelopeFollowing**(`WorldContextObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:9620](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9620)

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

#### Defined in

[ue/ue.d.ts:9621](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9621)

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

#### Defined in

[ue/ue.d.ts:9623](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9623)

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

#### Defined in

[ue/ue.d.ts:9624](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9624)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:9622](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L9622)
