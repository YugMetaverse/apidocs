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

#### Defined in

[ue/ue.d.ts:8945](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8945)

## Properties

### Duration

• **Duration**: `number`

#### Defined in

[ue/ue.d.ts:8952](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8952)

___

### EQPriority

• **EQPriority**: `number`

#### Defined in

[ue/ue.d.ts:8947](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8947)

___

### EQSettings

• **EQSettings**: [`AudioEQEffect`](ue_ue.AudioEQEffect.md)

#### Defined in

[ue/ue.d.ts:8948](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8948)

___

### FadeInTime

• **FadeInTime**: `number`

#### Defined in

[ue/ue.d.ts:8951](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8951)

___

### FadeOutTime

• **FadeOutTime**: `number`

#### Defined in

[ue/ue.d.ts:8953](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8953)

___

### InitialDelay

• **InitialDelay**: `number`

#### Defined in

[ue/ue.d.ts:8950](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8950)

___

### SoundClassEffects

• **SoundClassEffects**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundClassAdjuster`](ue_ue.SoundClassAdjuster.md)\>

#### Defined in

[ue/ue.d.ts:8949](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8949)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_SoundMix\_\_

• **\_\_tid\_SoundMix\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:8959](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8959)

___

### bApplyEQ

• **bApplyEQ**: `boolean`

#### Defined in

[ue/ue.d.ts:8946](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8946)

___

### bChanged

• **bChanged**: `boolean`

#### Defined in

[ue/ue.d.ts:8954](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8954)

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

[Object](ue_ue.Object.md).[ExecuteUbergraph](ue_ue.Object.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:8956](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8956)

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

#### Defined in

[ue/ue.d.ts:8957](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8957)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:8955](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8955)
