[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundMix

# Class: SoundMix

[ue/ue](../modules/ue_ue.md).SoundMix

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SoundMix`**

## Table of contents

### Constructors

- [constructor](ue_ue.SoundMix.md#constructor)

### Properties

- [Duration](ue_ue.SoundMix.md#duration)
- [EQPriority](ue_ue.SoundMix.md#eqpriority)
- [EQSettings](ue_ue.SoundMix.md#eqsettings)
- [FadeInTime](ue_ue.SoundMix.md#fadeintime)
- [FadeOutTime](ue_ue.SoundMix.md#fadeouttime)
- [InitialDelay](ue_ue.SoundMix.md#initialdelay)
- [SoundClassEffects](ue_ue.SoundMix.md#soundclasseffects)
- [\_\_tid\_Object\_\_](ue_ue.SoundMix.md#__tid_object__)
- [\_\_tid\_SoundMix\_\_](ue_ue.SoundMix.md#__tid_soundmix__)
- [bApplyEQ](ue_ue.SoundMix.md#bapplyeq)
- [bChanged](ue_ue.SoundMix.md#bchanged)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundMix.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundMix.md#executeubergraph)
- [GetClass](ue_ue.SoundMix.md#getclass)
- [GetName](ue_ue.SoundMix.md#getname)
- [GetOuter](ue_ue.SoundMix.md#getouter)
- [GetWorld](ue_ue.SoundMix.md#getworld)
- [Find](ue_ue.SoundMix.md#find)
- [Load](ue_ue.SoundMix.md#load)
- [StaticClass](ue_ue.SoundMix.md#staticclass)

## Constructors

### constructor

• **new SoundMix**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Duration

• **Duration**: `number`

___

### EQPriority

• **EQPriority**: `number`

___

### EQSettings

• **EQSettings**: [`AudioEQEffect`](ue_ue.AudioEQEffect.md)

___

### FadeInTime

• **FadeInTime**: `number`

___

### FadeOutTime

• **FadeOutTime**: `number`

___

### InitialDelay

• **InitialDelay**: `number`

___

### SoundClassEffects

• **SoundClassEffects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundClassAdjuster`](ue_ue.SoundClassAdjuster.md)\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_SoundMix\_\_

• **\_\_tid\_SoundMix\_\_**: `boolean`

___

### bApplyEQ

• **bApplyEQ**: `boolean`

___

### bChanged

• **bChanged**: `boolean`

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundMix`](ue_ue.SoundMix.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundMix`](ue_ue.SoundMix.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundMix`](ue_ue.SoundMix.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundMix`](ue_ue.SoundMix.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
