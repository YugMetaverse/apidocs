[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNotifyState\_TimedParticleEffect

# Class: AnimNotifyState\_TimedParticleEffect

[ue/ue](../modules/ue_ue.md).AnimNotifyState_TimedParticleEffect

## Hierarchy

- [`AnimNotifyState`](ue_ue.AnimNotifyState.md)

  ↳ **`AnimNotifyState_TimedParticleEffect`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNotifyState_TimedParticleEffect.md#constructor)

### Properties

- [LocationOffset](ue_ue.AnimNotifyState_TimedParticleEffect.md#locationoffset)
- [NotifyColor](ue_ue.AnimNotifyState_TimedParticleEffect.md#notifycolor)
- [PSTemplate](ue_ue.AnimNotifyState_TimedParticleEffect.md#pstemplate)
- [PreviousPSTemplates](ue_ue.AnimNotifyState_TimedParticleEffect.md#previouspstemplates)
- [PreviousSocketNames](ue_ue.AnimNotifyState_TimedParticleEffect.md#previoussocketnames)
- [RotationOffset](ue_ue.AnimNotifyState_TimedParticleEffect.md#rotationoffset)
- [SocketName](ue_ue.AnimNotifyState_TimedParticleEffect.md#socketname)
- [\_\_tid\_AnimNotifyState\_TimedParticleEffect\_\_](ue_ue.AnimNotifyState_TimedParticleEffect.md#__tid_animnotifystate_timedparticleeffect__)
- [\_\_tid\_AnimNotifyState\_\_](ue_ue.AnimNotifyState_TimedParticleEffect.md#__tid_animnotifystate__)
- [\_\_tid\_Object\_\_](ue_ue.AnimNotifyState_TimedParticleEffect.md#__tid_object__)
- [bDestroyAtEnd](ue_ue.AnimNotifyState_TimedParticleEffect.md#bdestroyatend)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimNotifyState_TimedParticleEffect.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimNotifyState_TimedParticleEffect.md#executeubergraph)
- [GetClass](ue_ue.AnimNotifyState_TimedParticleEffect.md#getclass)
- [GetName](ue_ue.AnimNotifyState_TimedParticleEffect.md#getname)
- [GetNotifyName](ue_ue.AnimNotifyState_TimedParticleEffect.md#getnotifyname)
- [GetOuter](ue_ue.AnimNotifyState_TimedParticleEffect.md#getouter)
- [GetWorld](ue_ue.AnimNotifyState_TimedParticleEffect.md#getworld)
- [Received\_NotifyBegin](ue_ue.AnimNotifyState_TimedParticleEffect.md#received_notifybegin)
- [Received\_NotifyEnd](ue_ue.AnimNotifyState_TimedParticleEffect.md#received_notifyend)
- [Received\_NotifyTick](ue_ue.AnimNotifyState_TimedParticleEffect.md#received_notifytick)
- [Find](ue_ue.AnimNotifyState_TimedParticleEffect.md#find)
- [Load](ue_ue.AnimNotifyState_TimedParticleEffect.md#load)
- [StaticClass](ue_ue.AnimNotifyState_TimedParticleEffect.md#staticclass)

## Constructors

### constructor

• **new AnimNotifyState_TimedParticleEffect**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimNotifyState](ue_ue.AnimNotifyState.md).[constructor](ue_ue.AnimNotifyState.md#constructor)

## Properties

### LocationOffset

• **LocationOffset**: [`Vector`](ue_ue_s.Vector.md)

___

### NotifyColor

• **NotifyColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[AnimNotifyState](ue_ue.AnimNotifyState.md).[NotifyColor](ue_ue.AnimNotifyState.md#notifycolor)

___

### PSTemplate

• **PSTemplate**: [`ParticleSystem`](ue_ue.ParticleSystem.md)

___

### PreviousPSTemplates

• **PreviousPSTemplates**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleSystem`](ue_ue.ParticleSystem.md)\>

___

### PreviousSocketNames

• **PreviousSocketNames**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### RotationOffset

• **RotationOffset**: [`Rotator`](ue_ue_s.Rotator.md)

___

### SocketName

• **SocketName**: `string`

___

### \_\_tid\_AnimNotifyState\_TimedParticleEffect\_\_

• **\_\_tid\_AnimNotifyState\_TimedParticleEffect\_\_**: `boolean`

___

### \_\_tid\_AnimNotifyState\_\_

• **\_\_tid\_AnimNotifyState\_\_**: `boolean`

#### Inherited from

[AnimNotifyState](ue_ue.AnimNotifyState.md).[__tid_AnimNotifyState__](ue_ue.AnimNotifyState.md#__tid_animnotifystate__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimNotifyState](ue_ue.AnimNotifyState.md).[__tid_Object__](ue_ue.AnimNotifyState.md#__tid_object__)

___

### bDestroyAtEnd

• **bDestroyAtEnd**: `boolean`

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

[AnimNotifyState](ue_ue.AnimNotifyState.md).[CreateDefaultSubobject](ue_ue.AnimNotifyState.md#createdefaultsubobject)

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

[AnimNotifyState](ue_ue.AnimNotifyState.md).[ExecuteUbergraph](ue_ue.AnimNotifyState.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimNotifyState](ue_ue.AnimNotifyState.md).[GetClass](ue_ue.AnimNotifyState.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimNotifyState](ue_ue.AnimNotifyState.md).[GetName](ue_ue.AnimNotifyState.md#getname)

___

### GetNotifyName

▸ **GetNotifyName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimNotifyState](ue_ue.AnimNotifyState.md).[GetNotifyName](ue_ue.AnimNotifyState.md#getnotifyname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimNotifyState](ue_ue.AnimNotifyState.md).[GetOuter](ue_ue.AnimNotifyState.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimNotifyState](ue_ue.AnimNotifyState.md).[GetWorld](ue_ue.AnimNotifyState.md#getworld)

___

### Received\_NotifyBegin

▸ **Received_NotifyBegin**(`MeshComp`, `Animation`, `TotalDuration`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MeshComp` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)\> |
| `Animation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)\> |
| `TotalDuration` | `number` |

#### Returns

`boolean`

#### Inherited from

[AnimNotifyState](ue_ue.AnimNotifyState.md).[Received_NotifyBegin](ue_ue.AnimNotifyState.md#received_notifybegin)

___

### Received\_NotifyEnd

▸ **Received_NotifyEnd**(`MeshComp`, `Animation`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MeshComp` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)\> |
| `Animation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)\> |

#### Returns

`boolean`

#### Inherited from

[AnimNotifyState](ue_ue.AnimNotifyState.md).[Received_NotifyEnd](ue_ue.AnimNotifyState.md#received_notifyend)

___

### Received\_NotifyTick

▸ **Received_NotifyTick**(`MeshComp`, `Animation`, `FrameDeltaTime`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `MeshComp` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)\> |
| `Animation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimSequenceBase`](ue_ue.AnimSequenceBase.md)\> |
| `FrameDeltaTime` | `number` |

#### Returns

`boolean`

#### Inherited from

[AnimNotifyState](ue_ue.AnimNotifyState.md).[Received_NotifyTick](ue_ue.AnimNotifyState.md#received_notifytick)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimNotifyState_TimedParticleEffect`](ue_ue.AnimNotifyState_TimedParticleEffect.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimNotifyState_TimedParticleEffect`](ue_ue.AnimNotifyState_TimedParticleEffect.md)

#### Overrides

[AnimNotifyState](ue_ue.AnimNotifyState.md).[Find](ue_ue.AnimNotifyState.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimNotifyState_TimedParticleEffect`](ue_ue.AnimNotifyState_TimedParticleEffect.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimNotifyState_TimedParticleEffect`](ue_ue.AnimNotifyState_TimedParticleEffect.md)

#### Overrides

[AnimNotifyState](ue_ue.AnimNotifyState.md).[Load](ue_ue.AnimNotifyState.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimNotifyState](ue_ue.AnimNotifyState.md).[StaticClass](ue_ue.AnimNotifyState.md#staticclass)
