[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNotify\_PlayParticleEffect

# Class: AnimNotify\_PlayParticleEffect

[ue/ue](../modules/ue_ue.md).AnimNotify_PlayParticleEffect

## Hierarchy

- [`AnimNotify`](ue_ue.AnimNotify.md)

  ↳ **`AnimNotify_PlayParticleEffect`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNotify_PlayParticleEffect.md#constructor)

### Properties

- [Attached](ue_ue.AnimNotify_PlayParticleEffect.md#attached)
- [LocationOffset](ue_ue.AnimNotify_PlayParticleEffect.md#locationoffset)
- [NotifyColor](ue_ue.AnimNotify_PlayParticleEffect.md#notifycolor)
- [PSTemplate](ue_ue.AnimNotify_PlayParticleEffect.md#pstemplate)
- [RotationOffset](ue_ue.AnimNotify_PlayParticleEffect.md#rotationoffset)
- [Scale](ue_ue.AnimNotify_PlayParticleEffect.md#scale)
- [SocketName](ue_ue.AnimNotify_PlayParticleEffect.md#socketname)
- [\_\_tid\_AnimNotify\_PlayParticleEffect\_\_](ue_ue.AnimNotify_PlayParticleEffect.md#__tid_animnotify_playparticleeffect__)
- [\_\_tid\_AnimNotify\_\_](ue_ue.AnimNotify_PlayParticleEffect.md#__tid_animnotify__)
- [\_\_tid\_Object\_\_](ue_ue.AnimNotify_PlayParticleEffect.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimNotify_PlayParticleEffect.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimNotify_PlayParticleEffect.md#executeubergraph)
- [GetClass](ue_ue.AnimNotify_PlayParticleEffect.md#getclass)
- [GetName](ue_ue.AnimNotify_PlayParticleEffect.md#getname)
- [GetNotifyName](ue_ue.AnimNotify_PlayParticleEffect.md#getnotifyname)
- [GetOuter](ue_ue.AnimNotify_PlayParticleEffect.md#getouter)
- [GetWorld](ue_ue.AnimNotify_PlayParticleEffect.md#getworld)
- [Received\_Notify](ue_ue.AnimNotify_PlayParticleEffect.md#received_notify)
- [Find](ue_ue.AnimNotify_PlayParticleEffect.md#find)
- [Load](ue_ue.AnimNotify_PlayParticleEffect.md#load)
- [StaticClass](ue_ue.AnimNotify_PlayParticleEffect.md#staticclass)

## Constructors

### constructor

• **new AnimNotify_PlayParticleEffect**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimNotify](ue_ue.AnimNotify.md).[constructor](ue_ue.AnimNotify.md#constructor)

#### Defined in

[ue/ue.d.ts:20153](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20153)

## Properties

### Attached

• **Attached**: `boolean`

#### Defined in

[ue/ue.d.ts:20158](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20158)

___

### LocationOffset

• **LocationOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:20155](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20155)

___

### NotifyColor

• **NotifyColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[AnimNotify](ue_ue.AnimNotify.md).[NotifyColor](ue_ue.AnimNotify.md#notifycolor)

#### Defined in

[ue/ue.d.ts:3008](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3008)

___

### PSTemplate

• **PSTemplate**: [`ParticleSystem`](ue_ue.ParticleSystem.md)

#### Defined in

[ue/ue.d.ts:20154](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20154)

___

### RotationOffset

• **RotationOffset**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:20156](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20156)

___

### Scale

• **Scale**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:20157](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20157)

___

### SocketName

• **SocketName**: `string`

#### Defined in

[ue/ue.d.ts:20159](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20159)

___

### \_\_tid\_AnimNotify\_PlayParticleEffect\_\_

• **\_\_tid\_AnimNotify\_PlayParticleEffect\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:20164](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20164)

___

### \_\_tid\_AnimNotify\_\_

• **\_\_tid\_AnimNotify\_\_**: `boolean`

#### Inherited from

[AnimNotify](ue_ue.AnimNotify.md).[__tid_AnimNotify__](ue_ue.AnimNotify.md#__tid_animnotify__)

#### Defined in

[ue/ue.d.ts:3015](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3015)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimNotify](ue_ue.AnimNotify.md).[__tid_Object__](ue_ue.AnimNotify.md#__tid_object__)

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

[AnimNotify](ue_ue.AnimNotify.md).[CreateDefaultSubobject](ue_ue.AnimNotify.md#createdefaultsubobject)

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

[AnimNotify](ue_ue.AnimNotify.md).[ExecuteUbergraph](ue_ue.AnimNotify.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimNotify](ue_ue.AnimNotify.md).[GetClass](ue_ue.AnimNotify.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimNotify](ue_ue.AnimNotify.md).[GetName](ue_ue.AnimNotify.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetNotifyName

▸ **GetNotifyName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimNotify](ue_ue.AnimNotify.md).[GetNotifyName](ue_ue.AnimNotify.md#getnotifyname)

#### Defined in

[ue/ue.d.ts:3009](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3009)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimNotify](ue_ue.AnimNotify.md).[GetOuter](ue_ue.AnimNotify.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimNotify](ue_ue.AnimNotify.md).[GetWorld](ue_ue.AnimNotify.md#getworld)

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

#### Inherited from

[AnimNotify](ue_ue.AnimNotify.md).[Received_Notify](ue_ue.AnimNotify.md#received_notify)

#### Defined in

[ue/ue.d.ts:3010](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L3010)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimNotify_PlayParticleEffect`](ue_ue.AnimNotify_PlayParticleEffect.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimNotify_PlayParticleEffect`](ue_ue.AnimNotify_PlayParticleEffect.md)

#### Overrides

[AnimNotify](ue_ue.AnimNotify.md).[Find](ue_ue.AnimNotify.md#find)

#### Defined in

[ue/ue.d.ts:20161](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20161)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimNotify_PlayParticleEffect`](ue_ue.AnimNotify_PlayParticleEffect.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimNotify_PlayParticleEffect`](ue_ue.AnimNotify_PlayParticleEffect.md)

#### Overrides

[AnimNotify](ue_ue.AnimNotify.md).[Load](ue_ue.AnimNotify.md#load)

#### Defined in

[ue/ue.d.ts:20162](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20162)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimNotify](ue_ue.AnimNotify.md).[StaticClass](ue_ue.AnimNotify.md#staticclass)

#### Defined in

[ue/ue.d.ts:20160](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L20160)
