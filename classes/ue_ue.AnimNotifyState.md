[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNotifyState

# Class: AnimNotifyState

[ue/ue](../modules/ue_ue.md).AnimNotifyState

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`AnimNotifyState`**

  ↳↳ [`AnimNotify_PlayMontageNotifyWindow`](ue_ue.AnimNotify_PlayMontageNotifyWindow.md)

  ↳↳ [`AnimNotifyState_DisableRootMotion`](ue_ue.AnimNotifyState_DisableRootMotion.md)

  ↳↳ [`AnimNotifyState_TimedParticleEffect`](ue_ue.AnimNotifyState_TimedParticleEffect.md)

  ↳↳ [`AnimNotifyState_Trail`](ue_ue.AnimNotifyState_Trail.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNotifyState.md#constructor)

### Properties

- [NotifyColor](ue_ue.AnimNotifyState.md#notifycolor)
- [\_\_tid\_AnimNotifyState\_\_](ue_ue.AnimNotifyState.md#__tid_animnotifystate__)
- [\_\_tid\_Object\_\_](ue_ue.AnimNotifyState.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimNotifyState.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimNotifyState.md#executeubergraph)
- [GetClass](ue_ue.AnimNotifyState.md#getclass)
- [GetName](ue_ue.AnimNotifyState.md#getname)
- [GetNotifyName](ue_ue.AnimNotifyState.md#getnotifyname)
- [GetOuter](ue_ue.AnimNotifyState.md#getouter)
- [GetWorld](ue_ue.AnimNotifyState.md#getworld)
- [Received\_NotifyBegin](ue_ue.AnimNotifyState.md#received_notifybegin)
- [Received\_NotifyEnd](ue_ue.AnimNotifyState.md#received_notifyend)
- [Received\_NotifyTick](ue_ue.AnimNotifyState.md#received_notifytick)
- [Find](ue_ue.AnimNotifyState.md#find)
- [Load](ue_ue.AnimNotifyState.md#load)
- [StaticClass](ue_ue.AnimNotifyState.md#staticclass)

## Constructors

### constructor

• **new AnimNotifyState**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### NotifyColor

• **NotifyColor**: [`Color`](ue_ue_s.Color.md)

___

### \_\_tid\_AnimNotifyState\_\_

• **\_\_tid\_AnimNotifyState\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

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

### GetNotifyName

▸ **GetNotifyName**(): `string`

#### Returns

`string`

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

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimNotifyState`](ue_ue.AnimNotifyState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimNotifyState`](ue_ue.AnimNotifyState.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimNotifyState`](ue_ue.AnimNotifyState.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimNotifyState`](ue_ue.AnimNotifyState.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
