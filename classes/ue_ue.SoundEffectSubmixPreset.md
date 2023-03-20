[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundEffectSubmixPreset

# Class: SoundEffectSubmixPreset

[ue/ue](../modules/ue_ue.md).SoundEffectSubmixPreset

## Hierarchy

- [`SoundEffectPreset`](ue_ue.SoundEffectPreset.md)

  ↳ **`SoundEffectSubmixPreset`**

  ↳↳ [`SubmixEffectDynamicsProcessorPreset`](ue_ue.SubmixEffectDynamicsProcessorPreset.md)

  ↳↳ [`SubmixEffectReverbFastPreset`](ue_ue.SubmixEffectReverbFastPreset.md)

  ↳↳ [`SubmixEffectReverbPreset`](ue_ue.SubmixEffectReverbPreset.md)

  ↳↳ [`SubmixEffectSubmixEQPreset`](ue_ue.SubmixEffectSubmixEQPreset.md)

## Table of contents

### Constructors

- [constructor](ue_ue.SoundEffectSubmixPreset.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.SoundEffectSubmixPreset.md#__tid_object__)
- [\_\_tid\_SoundEffectPreset\_\_](ue_ue.SoundEffectSubmixPreset.md#__tid_soundeffectpreset__)
- [\_\_tid\_SoundEffectSubmixPreset\_\_](ue_ue.SoundEffectSubmixPreset.md#__tid_soundeffectsubmixpreset__)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundEffectSubmixPreset.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundEffectSubmixPreset.md#executeubergraph)
- [GetClass](ue_ue.SoundEffectSubmixPreset.md#getclass)
- [GetName](ue_ue.SoundEffectSubmixPreset.md#getname)
- [GetOuter](ue_ue.SoundEffectSubmixPreset.md#getouter)
- [GetWorld](ue_ue.SoundEffectSubmixPreset.md#getworld)
- [Find](ue_ue.SoundEffectSubmixPreset.md#find)
- [Load](ue_ue.SoundEffectSubmixPreset.md#load)
- [StaticClass](ue_ue.SoundEffectSubmixPreset.md#staticclass)

## Constructors

### constructor

• **new SoundEffectSubmixPreset**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SoundEffectPreset](ue_ue.SoundEffectPreset.md).[constructor](ue_ue.SoundEffectPreset.md#constructor)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SoundEffectPreset](ue_ue.SoundEffectPreset.md).[__tid_Object__](ue_ue.SoundEffectPreset.md#__tid_object__)

___

### \_\_tid\_SoundEffectPreset\_\_

• **\_\_tid\_SoundEffectPreset\_\_**: `boolean`

#### Inherited from

[SoundEffectPreset](ue_ue.SoundEffectPreset.md).[__tid_SoundEffectPreset__](ue_ue.SoundEffectPreset.md#__tid_soundeffectpreset__)

___

### \_\_tid\_SoundEffectSubmixPreset\_\_

• **\_\_tid\_SoundEffectSubmixPreset\_\_**: `boolean`

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

[SoundEffectPreset](ue_ue.SoundEffectPreset.md).[CreateDefaultSubobject](ue_ue.SoundEffectPreset.md#createdefaultsubobject)

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

[SoundEffectPreset](ue_ue.SoundEffectPreset.md).[ExecuteUbergraph](ue_ue.SoundEffectPreset.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SoundEffectPreset](ue_ue.SoundEffectPreset.md).[GetClass](ue_ue.SoundEffectPreset.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SoundEffectPreset](ue_ue.SoundEffectPreset.md).[GetName](ue_ue.SoundEffectPreset.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SoundEffectPreset](ue_ue.SoundEffectPreset.md).[GetOuter](ue_ue.SoundEffectPreset.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SoundEffectPreset](ue_ue.SoundEffectPreset.md).[GetWorld](ue_ue.SoundEffectPreset.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundEffectSubmixPreset`](ue_ue.SoundEffectSubmixPreset.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundEffectSubmixPreset`](ue_ue.SoundEffectSubmixPreset.md)

#### Overrides

[SoundEffectPreset](ue_ue.SoundEffectPreset.md).[Find](ue_ue.SoundEffectPreset.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundEffectSubmixPreset`](ue_ue.SoundEffectSubmixPreset.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundEffectSubmixPreset`](ue_ue.SoundEffectSubmixPreset.md)

#### Overrides

[SoundEffectPreset](ue_ue.SoundEffectPreset.md).[Load](ue_ue.SoundEffectPreset.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SoundEffectPreset](ue_ue.SoundEffectPreset.md).[StaticClass](ue_ue.SoundEffectPreset.md#staticclass)
