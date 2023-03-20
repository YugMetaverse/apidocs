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

#### Defined in

[ue/ue.d.ts:62737](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62737)

## Properties

### FrameDelay

• **FrameDelay**: `number`

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[FrameDelay](ue_ue.TimecodeProvider.md#framedelay)

#### Defined in

[ue/ue.d.ts:32608](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32608)

___

### FrameRate

• **FrameRate**: [`FrameRate`](ue_ue.FrameRate.md)

#### Defined in

[ue/ue.d.ts:62738](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62738)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[__tid_Object__](ue_ue.TimecodeProvider.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SystemTimeTimecodeProvider\_\_

• **\_\_tid\_SystemTimeTimecodeProvider\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:62744](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62744)

___

### \_\_tid\_TimecodeProvider\_\_

• **\_\_tid\_TimecodeProvider\_\_**: `boolean`

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[__tid_TimecodeProvider__](ue_ue.TimecodeProvider.md#__tid_timecodeprovider__)

#### Defined in

[ue/ue.d.ts:32617](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32617)

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

[TimecodeProvider](ue_ue.TimecodeProvider.md).[ExecuteUbergraph](ue_ue.TimecodeProvider.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[GetClass](ue_ue.TimecodeProvider.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetDelayedTimecode

▸ **GetDelayedTimecode**(): [`Timecode`](ue_ue.Timecode.md)

#### Returns

[`Timecode`](ue_ue.Timecode.md)

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[GetDelayedTimecode](ue_ue.TimecodeProvider.md#getdelayedtimecode)

#### Defined in

[ue/ue.d.ts:32609](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32609)

___

### GetFrameRate

▸ **GetFrameRate**(): [`FrameRate`](ue_ue.FrameRate.md)

#### Returns

[`FrameRate`](ue_ue.FrameRate.md)

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[GetFrameRate](ue_ue.TimecodeProvider.md#getframerate)

#### Defined in

[ue/ue.d.ts:32610](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32610)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[GetName](ue_ue.TimecodeProvider.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[GetOuter](ue_ue.TimecodeProvider.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetSynchronizationState

▸ **GetSynchronizationState**(): [`ETimecodeProviderSynchronizationState`](../enums/ue_ue.ETimecodeProviderSynchronizationState.md)

#### Returns

[`ETimecodeProviderSynchronizationState`](../enums/ue_ue.ETimecodeProviderSynchronizationState.md)

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[GetSynchronizationState](ue_ue.TimecodeProvider.md#getsynchronizationstate)

#### Defined in

[ue/ue.d.ts:32611](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32611)

___

### GetTimecode

▸ **GetTimecode**(): [`Timecode`](ue_ue.Timecode.md)

#### Returns

[`Timecode`](ue_ue.Timecode.md)

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[GetTimecode](ue_ue.TimecodeProvider.md#gettimecode)

#### Defined in

[ue/ue.d.ts:32612](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L32612)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[TimecodeProvider](ue_ue.TimecodeProvider.md).[GetWorld](ue_ue.TimecodeProvider.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### SetFrameRate

▸ **SetFrameRate**(`InFrameRate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFrameRate` | [`FrameRate`](ue_ue.FrameRate.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:62739](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62739)

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

#### Defined in

[ue/ue.d.ts:62741](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62741)

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

#### Defined in

[ue/ue.d.ts:62742](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62742)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[TimecodeProvider](ue_ue.TimecodeProvider.md).[StaticClass](ue_ue.TimecodeProvider.md#staticclass)

#### Defined in

[ue/ue.d.ts:62740](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L62740)
