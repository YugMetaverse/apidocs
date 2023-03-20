[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SystemTimeTimecodeProvider

# Class: SystemTimeTimecodeProvider

[ue/ue](../modules/ue_ue.md).SystemTimeTimecodeProvider

## Hierarchy

- [`TimecodeProvider`](ue_ue.TimecodeProvider.md)

  ↳ **`SystemTimeTimecodeProvider`**

## Table of contents

### Constructors

- [constructor](ue_ue.SystemTimeTimecodeProvider.md#constructor)

### Properties

- [FrameDelay](ue_ue.SystemTimeTimecodeProvider.md#framedelay)
- [FrameRate](ue_ue.SystemTimeTimecodeProvider.md#framerate)
- [\_\_tid\_Object\_\_](ue_ue.SystemTimeTimecodeProvider.md#__tid_object__)
- [\_\_tid\_SystemTimeTimecodeProvider\_\_](ue_ue.SystemTimeTimecodeProvider.md#__tid_systemtimetimecodeprovider__)
- [\_\_tid\_TimecodeProvider\_\_](ue_ue.SystemTimeTimecodeProvider.md#__tid_timecodeprovider__)

### Methods

- [CreateDefaultSubobject](ue_ue.SystemTimeTimecodeProvider.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SystemTimeTimecodeProvider.md#executeubergraph)
- [GetClass](ue_ue.SystemTimeTimecodeProvider.md#getclass)
- [GetDelayedTimecode](ue_ue.SystemTimeTimecodeProvider.md#getdelayedtimecode)
- [GetFrameRate](ue_ue.SystemTimeTimecodeProvider.md#getframerate)
- [GetName](ue_ue.SystemTimeTimecodeProvider.md#getname)
- [GetOuter](ue_ue.SystemTimeTimecodeProvider.md#getouter)
- [GetSynchronizationState](ue_ue.SystemTimeTimecodeProvider.md#getsynchronizationstate)
- [GetTimecode](ue_ue.SystemTimeTimecodeProvider.md#gettimecode)
- [GetWorld](ue_ue.SystemTimeTimecodeProvider.md#getworld)
- [SetFrameRate](ue_ue.SystemTimeTimecodeProvider.md#setframerate)
- [Find](ue_ue.SystemTimeTimecodeProvider.md#find)
- [Load](ue_ue.SystemTimeTimecodeProvider.md#load)
- [StaticClass](ue_ue.SystemTimeTimecodeProvider.md#staticclass)

## Constructors

### constructor

• **new SystemTimeTimecodeProvider**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[TimecodeProvider](ue_ue.TimecodeProvider.md).[constructor](ue_ue.TimecodeProvider.md#constructor)

## Properties

### FrameDelay

• **FrameDelay**: `number`

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[FrameDelay](ue_ue.TimecodeProvider.md#framedelay)

___

### FrameRate

• **FrameRate**: [`FrameRate`](ue_ue.FrameRate.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[__tid_Object__](ue_ue.TimecodeProvider.md#__tid_object__)

___

### \_\_tid\_SystemTimeTimecodeProvider\_\_

• **\_\_tid\_SystemTimeTimecodeProvider\_\_**: `boolean`

___

### \_\_tid\_TimecodeProvider\_\_

• **\_\_tid\_TimecodeProvider\_\_**: `boolean`

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[__tid_TimecodeProvider__](ue_ue.TimecodeProvider.md#__tid_timecodeprovider__)

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

[TimecodeProvider](ue_ue.TimecodeProvider.md).[CreateDefaultSubobject](ue_ue.TimecodeProvider.md#createdefaultsubobject)

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

[TimecodeProvider](ue_ue.TimecodeProvider.md).[ExecuteUbergraph](ue_ue.TimecodeProvider.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[GetClass](ue_ue.TimecodeProvider.md#getclass)

___

### GetDelayedTimecode

▸ **GetDelayedTimecode**(): [`Timecode`](ue_ue.Timecode.md)

#### Returns

[`Timecode`](ue_ue.Timecode.md)

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[GetDelayedTimecode](ue_ue.TimecodeProvider.md#getdelayedtimecode)

___

### GetFrameRate

▸ **GetFrameRate**(): [`FrameRate`](ue_ue.FrameRate.md)

#### Returns

[`FrameRate`](ue_ue.FrameRate.md)

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[GetFrameRate](ue_ue.TimecodeProvider.md#getframerate)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[GetName](ue_ue.TimecodeProvider.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[GetOuter](ue_ue.TimecodeProvider.md#getouter)

___

### GetSynchronizationState

▸ **GetSynchronizationState**(): [`ETimecodeProviderSynchronizationState`](../enums/ue_ue.ETimecodeProviderSynchronizationState.md)

#### Returns

[`ETimecodeProviderSynchronizationState`](../enums/ue_ue.ETimecodeProviderSynchronizationState.md)

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[GetSynchronizationState](ue_ue.TimecodeProvider.md#getsynchronizationstate)

___

### GetTimecode

▸ **GetTimecode**(): [`Timecode`](ue_ue.Timecode.md)

#### Returns

[`Timecode`](ue_ue.Timecode.md)

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[GetTimecode](ue_ue.TimecodeProvider.md#gettimecode)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[GetWorld](ue_ue.TimecodeProvider.md#getworld)

___

### SetFrameRate

▸ **SetFrameRate**(`InFrameRate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFrameRate` | [`FrameRate`](ue_ue.FrameRate.md) |

#### Returns

`void`

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SystemTimeTimecodeProvider`](ue_ue.SystemTimeTimecodeProvider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SystemTimeTimecodeProvider`](ue_ue.SystemTimeTimecodeProvider.md)

#### Overrides

[TimecodeProvider](ue_ue.TimecodeProvider.md).[Find](ue_ue.TimecodeProvider.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SystemTimeTimecodeProvider`](ue_ue.SystemTimeTimecodeProvider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SystemTimeTimecodeProvider`](ue_ue.SystemTimeTimecodeProvider.md)

#### Overrides

[TimecodeProvider](ue_ue.TimecodeProvider.md).[Load](ue_ue.TimecodeProvider.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[TimecodeProvider](ue_ue.TimecodeProvider.md).[StaticClass](ue_ue.TimecodeProvider.md#staticclass)
