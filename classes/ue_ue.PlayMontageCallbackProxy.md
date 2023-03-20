[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PlayMontageCallbackProxy

# Class: PlayMontageCallbackProxy

[ue/ue](../modules/ue_ue.md).PlayMontageCallbackProxy

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`PlayMontageCallbackProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.PlayMontageCallbackProxy.md#constructor)

### Properties

- [OnBlendOut](ue_ue.PlayMontageCallbackProxy.md#onblendout)
- [OnCompleted](ue_ue.PlayMontageCallbackProxy.md#oncompleted)
- [OnInterrupted](ue_ue.PlayMontageCallbackProxy.md#oninterrupted)
- [OnNotifyBegin](ue_ue.PlayMontageCallbackProxy.md#onnotifybegin)
- [OnNotifyEnd](ue_ue.PlayMontageCallbackProxy.md#onnotifyend)
- [\_\_tid\_Object\_\_](ue_ue.PlayMontageCallbackProxy.md#__tid_object__)
- [\_\_tid\_PlayMontageCallbackProxy\_\_](ue_ue.PlayMontageCallbackProxy.md#__tid_playmontagecallbackproxy__)

### Methods

- [CreateDefaultSubobject](ue_ue.PlayMontageCallbackProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.PlayMontageCallbackProxy.md#executeubergraph)
- [GetClass](ue_ue.PlayMontageCallbackProxy.md#getclass)
- [GetName](ue_ue.PlayMontageCallbackProxy.md#getname)
- [GetOuter](ue_ue.PlayMontageCallbackProxy.md#getouter)
- [GetWorld](ue_ue.PlayMontageCallbackProxy.md#getworld)
- [OnMontageBlendingOut](ue_ue.PlayMontageCallbackProxy.md#onmontageblendingout)
- [OnMontageEnded](ue_ue.PlayMontageCallbackProxy.md#onmontageended)
- [OnNotifyBeginReceived](ue_ue.PlayMontageCallbackProxy.md#onnotifybeginreceived)
- [OnNotifyEndReceived](ue_ue.PlayMontageCallbackProxy.md#onnotifyendreceived)
- [CreateProxyObjectForPlayMontage](ue_ue.PlayMontageCallbackProxy.md#createproxyobjectforplaymontage)
- [Find](ue_ue.PlayMontageCallbackProxy.md#find)
- [Load](ue_ue.PlayMontageCallbackProxy.md#load)
- [StaticClass](ue_ue.PlayMontageCallbackProxy.md#staticclass)

## Constructors

### constructor

• **new PlayMontageCallbackProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### OnBlendOut

• **OnBlendOut**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NotifyName`: `string`) => `void`\>

___

### OnCompleted

• **OnCompleted**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NotifyName`: `string`) => `void`\>

___

### OnInterrupted

• **OnInterrupted**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NotifyName`: `string`) => `void`\>

___

### OnNotifyBegin

• **OnNotifyBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NotifyName`: `string`) => `void`\>

___

### OnNotifyEnd

• **OnNotifyEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NotifyName`: `string`) => `void`\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_PlayMontageCallbackProxy\_\_

• **\_\_tid\_PlayMontageCallbackProxy\_\_**: `boolean`

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

### OnMontageBlendingOut

▸ **OnMontageBlendingOut**(`Montage`, `bInterrupted`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Montage` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\> |
| `bInterrupted` | `boolean` |

#### Returns

`void`

___

### OnMontageEnded

▸ **OnMontageEnded**(`Montage`, `bInterrupted`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Montage` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\> |
| `bInterrupted` | `boolean` |

#### Returns

`void`

___

### OnNotifyBeginReceived

▸ **OnNotifyBeginReceived**(`NotifyName`, `BranchingPointNotifyPayload`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NotifyName` | `string` |
| `BranchingPointNotifyPayload` | [`BranchingPointNotifyPayload`](ue_ue.BranchingPointNotifyPayload.md) |

#### Returns

`void`

___

### OnNotifyEndReceived

▸ **OnNotifyEndReceived**(`NotifyName`, `BranchingPointNotifyPayload`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NotifyName` | `string` |
| `BranchingPointNotifyPayload` | [`BranchingPointNotifyPayload`](ue_ue.BranchingPointNotifyPayload.md) |

#### Returns

`void`

___

### CreateProxyObjectForPlayMontage

▸ `Static` **CreateProxyObjectForPlayMontage**(`InSkeletalMeshComponent`, `MontageToPlay`, `PlayRate?`, `StartingPosition?`, `StartingSection?`): [`PlayMontageCallbackProxy`](ue_ue.PlayMontageCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSkeletalMeshComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SkeletalMeshComponent`](ue_ue.SkeletalMeshComponent.md)\> |
| `MontageToPlay` | [`$Nullable`](../modules/puerts.md#$nullable)<[`AnimMontage`](ue_ue.AnimMontage.md)\> |
| `PlayRate?` | `number` |
| `StartingPosition?` | `number` |
| `StartingSection?` | `string` |

#### Returns

[`PlayMontageCallbackProxy`](ue_ue.PlayMontageCallbackProxy.md)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PlayMontageCallbackProxy`](ue_ue.PlayMontageCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PlayMontageCallbackProxy`](ue_ue.PlayMontageCallbackProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PlayMontageCallbackProxy`](ue_ue.PlayMontageCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PlayMontageCallbackProxy`](ue_ue.PlayMontageCallbackProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
