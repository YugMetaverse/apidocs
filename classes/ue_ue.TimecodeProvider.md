[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / TimecodeProvider

# Class: TimecodeProvider

[ue/ue](../modules/ue_ue.md).TimecodeProvider

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`TimecodeProvider`**

  ↳↳ [`SystemTimeTimecodeProvider`](ue_ue.SystemTimeTimecodeProvider.md)

## Table of contents

### Constructors

- [constructor](ue_ue.TimecodeProvider.md#constructor)

### Properties

- [FrameDelay](ue_ue.TimecodeProvider.md#framedelay)
- [\_\_tid\_Object\_\_](ue_ue.TimecodeProvider.md#__tid_object__)
- [\_\_tid\_TimecodeProvider\_\_](ue_ue.TimecodeProvider.md#__tid_timecodeprovider__)

### Methods

- [CreateDefaultSubobject](ue_ue.TimecodeProvider.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.TimecodeProvider.md#executeubergraph)
- [GetClass](ue_ue.TimecodeProvider.md#getclass)
- [GetDelayedTimecode](ue_ue.TimecodeProvider.md#getdelayedtimecode)
- [GetFrameRate](ue_ue.TimecodeProvider.md#getframerate)
- [GetName](ue_ue.TimecodeProvider.md#getname)
- [GetOuter](ue_ue.TimecodeProvider.md#getouter)
- [GetSynchronizationState](ue_ue.TimecodeProvider.md#getsynchronizationstate)
- [GetTimecode](ue_ue.TimecodeProvider.md#gettimecode)
- [GetWorld](ue_ue.TimecodeProvider.md#getworld)
- [Find](ue_ue.TimecodeProvider.md#find)
- [Load](ue_ue.TimecodeProvider.md#load)
- [StaticClass](ue_ue.TimecodeProvider.md#staticclass)

## Constructors

### constructor

• **new TimecodeProvider**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### FrameDelay

• **FrameDelay**: `number`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_TimecodeProvider\_\_

• **\_\_tid\_TimecodeProvider\_\_**: `boolean`

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

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

___

### GetDelayedTimecode

▸ **GetDelayedTimecode**(): [`Timecode`](ue_ue.Timecode.md)

#### Returns

[`Timecode`](ue_ue.Timecode.md)

___

### GetFrameRate

▸ **GetFrameRate**(): [`FrameRate`](ue_ue.FrameRate.md)

#### Returns

[`FrameRate`](ue_ue.FrameRate.md)

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

### GetSynchronizationState

▸ **GetSynchronizationState**(): [`ETimecodeProviderSynchronizationState`](../enums/ue_ue.ETimecodeProviderSynchronizationState.md)

#### Returns

[`ETimecodeProviderSynchronizationState`](../enums/ue_ue.ETimecodeProviderSynchronizationState.md)

___

### GetTimecode

▸ **GetTimecode**(): [`Timecode`](ue_ue.Timecode.md)

#### Returns

[`Timecode`](ue_ue.Timecode.md)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`TimecodeProvider`](ue_ue.TimecodeProvider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`TimecodeProvider`](ue_ue.TimecodeProvider.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`TimecodeProvider`](ue_ue.TimecodeProvider.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`TimecodeProvider`](ue_ue.TimecodeProvider.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
