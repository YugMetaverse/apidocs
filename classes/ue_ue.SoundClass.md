[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SoundClass

# Class: SoundClass

[ue/ue](../modules/ue_ue.md).SoundClass

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`SoundClass`**

## Table of contents

### Constructors

- [constructor](ue_ue.SoundClass.md#constructor)

### Properties

- [ChildClasses](ue_ue.SoundClass.md#childclasses)
- [Modulation](ue_ue.SoundClass.md#modulation)
- [ParentClass](ue_ue.SoundClass.md#parentclass)
- [PassiveSoundMixModifiers](ue_ue.SoundClass.md#passivesoundmixmodifiers)
- [Properties](ue_ue.SoundClass.md#properties)
- [\_\_tid\_Object\_\_](ue_ue.SoundClass.md#__tid_object__)
- [\_\_tid\_SoundClass\_\_](ue_ue.SoundClass.md#__tid_soundclass__)

### Methods

- [CreateDefaultSubobject](ue_ue.SoundClass.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.SoundClass.md#executeubergraph)
- [GetClass](ue_ue.SoundClass.md#getclass)
- [GetName](ue_ue.SoundClass.md#getname)
- [GetOuter](ue_ue.SoundClass.md#getouter)
- [GetWorld](ue_ue.SoundClass.md#getworld)
- [Find](ue_ue.SoundClass.md#find)
- [Load](ue_ue.SoundClass.md#load)
- [StaticClass](ue_ue.SoundClass.md#staticclass)

## Constructors

### constructor

• **new SoundClass**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:8914](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8914)

## Properties

### ChildClasses

• **ChildClasses**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundClass`](ue_ue.SoundClass.md)\>

#### Defined in

[ue/ue.d.ts:8916](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8916)

___

### Modulation

• **Modulation**: [`SoundModulation`](ue_ue.SoundModulation.md)

#### Defined in

[ue/ue.d.ts:8918](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8918)

___

### ParentClass

• **ParentClass**: [`SoundClass`](ue_ue.SoundClass.md)

#### Defined in

[ue/ue.d.ts:8919](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8919)

___

### PassiveSoundMixModifiers

• **PassiveSoundMixModifiers**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`PassiveSoundMixModifier`](ue_ue.PassiveSoundMixModifier.md)\>

#### Defined in

[ue/ue.d.ts:8917](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8917)

___

### Properties

• **Properties**: [`SoundClassProperties`](ue_ue.SoundClassProperties.md)

#### Defined in

[ue/ue.d.ts:8915](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8915)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_SoundClass\_\_

• **\_\_tid\_SoundClass\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:8924](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8924)

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SoundClass`](ue_ue.SoundClass.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SoundClass`](ue_ue.SoundClass.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:8921](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8921)

___

### Load

▸ `Static` **Load**(`InName`): [`SoundClass`](ue_ue.SoundClass.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SoundClass`](ue_ue.SoundClass.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:8922](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8922)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:8920](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L8920)
