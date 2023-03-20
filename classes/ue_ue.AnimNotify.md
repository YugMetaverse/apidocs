[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNotify

# Class: AnimNotify

[ue/ue](../modules/ue_ue.md).AnimNotify

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AnimNotify`**

  ↳↳ [`AnimNotify_PauseClothingSimulation`](ue_ue.AnimNotify_PauseClothingSimulation.md)

  ↳↳ [`AnimNotify_PlayMontageNotify`](ue_ue.AnimNotify_PlayMontageNotify.md)

  ↳↳ [`AnimNotify_PlayParticleEffect`](ue_ue.AnimNotify_PlayParticleEffect.md)

  ↳↳ [`AnimNotify_PlaySound`](ue_ue.AnimNotify_PlaySound.md)

  ↳↳ [`AnimNotify_ResetClothingSimulation`](ue_ue.AnimNotify_ResetClothingSimulation.md)

  ↳↳ [`AnimNotify_ResetDynamics`](ue_ue.AnimNotify_ResetDynamics.md)

  ↳↳ [`AnimNotify_ResumeClothingSimulation`](ue_ue.AnimNotify_ResumeClothingSimulation.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNotify.md#constructor)

### Properties

- [NotifyColor](ue_ue.AnimNotify.md#notifycolor)
- [\_\_tid\_AnimNotify\_\_](ue_ue.AnimNotify.md#__tid_animnotify__)
- [\_\_tid\_Object\_\_](ue_ue.AnimNotify.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimNotify.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimNotify.md#executeubergraph)
- [GetClass](ue_ue.AnimNotify.md#getclass)
- [GetName](ue_ue.AnimNotify.md#getname)
- [GetNotifyName](ue_ue.AnimNotify.md#getnotifyname)
- [GetOuter](ue_ue.AnimNotify.md#getouter)
- [GetWorld](ue_ue.AnimNotify.md#getworld)
- [Received\_Notify](ue_ue.AnimNotify.md#received_notify)
- [Find](ue_ue.AnimNotify.md#find)
- [Load](ue_ue.AnimNotify.md#load)
- [StaticClass](ue_ue.AnimNotify.md#staticclass)

## Constructors

### constructor

• **new AnimNotify**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:3007](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3007)

## Properties

### NotifyColor

• **NotifyColor**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:3008](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3008)

___

### \_\_tid\_AnimNotify\_\_

• **\_\_tid\_AnimNotify\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:3015](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3015)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

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

### GetNotifyName

▸ **GetNotifyName**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:3009](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3009)

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

### Received\_Notify

▸ **Received_Notify**(`MeshComp`, `Animation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MeshComp` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)\> |
| `Animation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:3010](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3010)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimNotify`](ue_ue.AnimNotify.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimNotify`](ue_ue.AnimNotify.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:3012](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3012)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimNotify`](ue_ue.AnimNotify.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimNotify`](ue_ue.AnimNotify.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:3013](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3013)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:3011](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3011)
