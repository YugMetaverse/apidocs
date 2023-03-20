[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AudioCapture

# Class: AudioCapture

[ue/ue](../modules/ue_ue.md).AudioCapture

## Hierarchy

- [`AudioGenerator`](ue_ue.AudioGenerator.md)

  ↳ **`AudioCapture`**

## Table of contents

### Constructors

- [constructor](ue_ue.AudioCapture.md#constructor)

### Properties

- [\_\_tid\_AudioCapture\_\_](ue_ue.AudioCapture.md#__tid_audiocapture__)
- [\_\_tid\_AudioGenerator\_\_](ue_ue.AudioCapture.md#__tid_audiogenerator__)
- [\_\_tid\_Object\_\_](ue_ue.AudioCapture.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AudioCapture.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AudioCapture.md#executeubergraph)
- [GetAudioCaptureDeviceInfo](ue_ue.AudioCapture.md#getaudiocapturedeviceinfo)
- [GetClass](ue_ue.AudioCapture.md#getclass)
- [GetName](ue_ue.AudioCapture.md#getname)
- [GetOuter](ue_ue.AudioCapture.md#getouter)
- [GetWorld](ue_ue.AudioCapture.md#getworld)
- [IsCapturingAudio](ue_ue.AudioCapture.md#iscapturingaudio)
- [StartCapturingAudio](ue_ue.AudioCapture.md#startcapturingaudio)
- [StopCapturingAudio](ue_ue.AudioCapture.md#stopcapturingaudio)
- [Find](ue_ue.AudioCapture.md#find)
- [Load](ue_ue.AudioCapture.md#load)
- [StaticClass](ue_ue.AudioCapture.md#staticclass)

## Constructors

### constructor

• **new AudioCapture**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AudioGenerator](ue_ue.AudioGenerator.md).[constructor](ue_ue.AudioGenerator.md#constructor)

## Properties

### \_\_tid\_AudioCapture\_\_

• **\_\_tid\_AudioCapture\_\_**: `boolean`

___

### \_\_tid\_AudioGenerator\_\_

• **\_\_tid\_AudioGenerator\_\_**: `boolean`

#### Inherited from

[AudioGenerator](ue_ue.AudioGenerator.md).[__tid_AudioGenerator__](ue_ue.AudioGenerator.md#__tid_audiogenerator__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AudioGenerator](ue_ue.AudioGenerator.md).[__tid_Object__](ue_ue.AudioGenerator.md#__tid_object__)

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

[AudioGenerator](ue_ue.AudioGenerator.md).[CreateDefaultSubobject](ue_ue.AudioGenerator.md#createdefaultsubobject)

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

[AudioGenerator](ue_ue.AudioGenerator.md).[ExecuteUbergraph](ue_ue.AudioGenerator.md#executeubergraph)

___

### GetAudioCaptureDeviceInfo

▸ **GetAudioCaptureDeviceInfo**(`OutInfo`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutInfo` | [`$Ref`](../interfaces/puerts._Ref.md)<[`AudioCaptureDeviceInfo`](ue_ue.AudioCaptureDeviceInfo.md)\> |

#### Returns

`boolean`

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AudioGenerator](ue_ue.AudioGenerator.md).[GetClass](ue_ue.AudioGenerator.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AudioGenerator](ue_ue.AudioGenerator.md).[GetName](ue_ue.AudioGenerator.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AudioGenerator](ue_ue.AudioGenerator.md).[GetOuter](ue_ue.AudioGenerator.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AudioGenerator](ue_ue.AudioGenerator.md).[GetWorld](ue_ue.AudioGenerator.md#getworld)

___

### IsCapturingAudio

▸ **IsCapturingAudio**(): `boolean`

#### Returns

`boolean`

___

### StartCapturingAudio

▸ **StartCapturingAudio**(): `void`

#### Returns

`void`

___

### StopCapturingAudio

▸ **StopCapturingAudio**(): `void`

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AudioCapture`](ue_ue.AudioCapture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AudioCapture`](ue_ue.AudioCapture.md)

#### Overrides

[AudioGenerator](ue_ue.AudioGenerator.md).[Find](ue_ue.AudioGenerator.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AudioCapture`](ue_ue.AudioCapture.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AudioCapture`](ue_ue.AudioCapture.md)

#### Overrides

[AudioGenerator](ue_ue.AudioGenerator.md).[Load](ue_ue.AudioGenerator.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AudioGenerator](ue_ue.AudioGenerator.md).[StaticClass](ue_ue.AudioGenerator.md#staticclass)
