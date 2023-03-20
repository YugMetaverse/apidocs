[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AnimNotify\_ResetDynamics

# Class: AnimNotify\_ResetDynamics

[ue/ue](../modules/ue_ue.md).AnimNotify_ResetDynamics

## Hierarchy

- [`AnimNotify`](ue_ue.AnimNotify.md)

  ↳ **`AnimNotify_ResetDynamics`**

## Table of contents

### Constructors

- [constructor](ue_ue.AnimNotify_ResetDynamics.md#constructor)

### Properties

- [NotifyColor](ue_ue.AnimNotify_ResetDynamics.md#notifycolor)
- [\_\_tid\_AnimNotify\_ResetDynamics\_\_](ue_ue.AnimNotify_ResetDynamics.md#__tid_animnotify_resetdynamics__)
- [\_\_tid\_AnimNotify\_\_](ue_ue.AnimNotify_ResetDynamics.md#__tid_animnotify__)
- [\_\_tid\_Object\_\_](ue_ue.AnimNotify_ResetDynamics.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.AnimNotify_ResetDynamics.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AnimNotify_ResetDynamics.md#executeubergraph)
- [GetClass](ue_ue.AnimNotify_ResetDynamics.md#getclass)
- [GetName](ue_ue.AnimNotify_ResetDynamics.md#getname)
- [GetNotifyName](ue_ue.AnimNotify_ResetDynamics.md#getnotifyname)
- [GetOuter](ue_ue.AnimNotify_ResetDynamics.md#getouter)
- [GetWorld](ue_ue.AnimNotify_ResetDynamics.md#getworld)
- [Received\_Notify](ue_ue.AnimNotify_ResetDynamics.md#received_notify)
- [Find](ue_ue.AnimNotify_ResetDynamics.md#find)
- [Load](ue_ue.AnimNotify_ResetDynamics.md#load)
- [StaticClass](ue_ue.AnimNotify_ResetDynamics.md#staticclass)

## Constructors

### constructor

• **new AnimNotify_ResetDynamics**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AnimNotify](ue_ue.AnimNotify.md).[constructor](ue_ue.AnimNotify.md#constructor)

## Properties

### NotifyColor

• **NotifyColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[AnimNotify](ue_ue.AnimNotify.md).[NotifyColor](ue_ue.AnimNotify.md#notifycolor)

___

### \_\_tid\_AnimNotify\_ResetDynamics\_\_

• **\_\_tid\_AnimNotify\_ResetDynamics\_\_**: `boolean`

___

### \_\_tid\_AnimNotify\_\_

• **\_\_tid\_AnimNotify\_\_**: `boolean`

#### Inherited from

[AnimNotify](ue_ue.AnimNotify.md).[__tid_AnimNotify__](ue_ue.AnimNotify.md#__tid_animnotify__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AnimNotify](ue_ue.AnimNotify.md).[__tid_Object__](ue_ue.AnimNotify.md#__tid_object__)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AnimNotify](ue_ue.AnimNotify.md).[GetClass](ue_ue.AnimNotify.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimNotify](ue_ue.AnimNotify.md).[GetName](ue_ue.AnimNotify.md#getname)

___

### GetNotifyName

▸ **GetNotifyName**(): `string`

#### Returns

`string`

#### Inherited from

[AnimNotify](ue_ue.AnimNotify.md).[GetNotifyName](ue_ue.AnimNotify.md#getnotifyname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AnimNotify](ue_ue.AnimNotify.md).[GetOuter](ue_ue.AnimNotify.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AnimNotify](ue_ue.AnimNotify.md).[GetWorld](ue_ue.AnimNotify.md#getworld)

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

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AnimNotify_ResetDynamics`](ue_ue.AnimNotify_ResetDynamics.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AnimNotify_ResetDynamics`](ue_ue.AnimNotify_ResetDynamics.md)

#### Overrides

[AnimNotify](ue_ue.AnimNotify.md).[Find](ue_ue.AnimNotify.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AnimNotify_ResetDynamics`](ue_ue.AnimNotify_ResetDynamics.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AnimNotify_ResetDynamics`](ue_ue.AnimNotify_ResetDynamics.md)

#### Overrides

[AnimNotify](ue_ue.AnimNotify.md).[Load](ue_ue.AnimNotify.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AnimNotify](ue_ue.AnimNotify.md).[StaticClass](ue_ue.AnimNotify.md#staticclass)
