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

#### Defined in

[ue/ue.d.ts:58134](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58134)

## Properties

### OnBlendOut

• **OnBlendOut**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NotifyName`: `string`) => `void`\>

#### Defined in

[ue/ue.d.ts:58136](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58136)

___

### OnCompleted

• **OnCompleted**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NotifyName`: `string`) => `void`\>

#### Defined in

[ue/ue.d.ts:58135](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58135)

___

### OnInterrupted

• **OnInterrupted**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NotifyName`: `string`) => `void`\>

#### Defined in

[ue/ue.d.ts:58137](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58137)

___

### OnNotifyBegin

• **OnNotifyBegin**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NotifyName`: `string`) => `void`\>

#### Defined in

[ue/ue.d.ts:58138](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58138)

___

### OnNotifyEnd

• **OnNotifyEnd**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NotifyName`: `string`) => `void`\>

#### Defined in

[ue/ue.d.ts:58139](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58139)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PlayMontageCallbackProxy\_\_

• **\_\_tid\_PlayMontageCallbackProxy\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:58149](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58149)

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

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

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

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetClass](ue_ue.Object.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:58140](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58140)

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

#### Defined in

[ue/ue.d.ts:58141](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58141)

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

#### Defined in

[ue/ue.d.ts:58142](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58142)

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

#### Defined in

[ue/ue.d.ts:58143](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58143)

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

#### Defined in

[ue/ue.d.ts:58144](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58144)

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

#### Defined in

[ue/ue.d.ts:58146](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58146)

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

#### Defined in

[ue/ue.d.ts:58147](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58147)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:58145](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58145)
