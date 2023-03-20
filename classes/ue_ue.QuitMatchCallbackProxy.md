[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / QuitMatchCallbackProxy

# Class: QuitMatchCallbackProxy

[ue/ue](../modules/ue_ue.md).QuitMatchCallbackProxy

## Hierarchy

- [`OnlineBlueprintCallProxyBase`](ue_ue.OnlineBlueprintCallProxyBase.md)

  ↳ **`QuitMatchCallbackProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.QuitMatchCallbackProxy.md#constructor)

### Properties

- [OnFailure](ue_ue.QuitMatchCallbackProxy.md#onfailure)
- [OnSuccess](ue_ue.QuitMatchCallbackProxy.md#onsuccess)
- [\_\_tid\_Object\_\_](ue_ue.QuitMatchCallbackProxy.md#__tid_object__)
- [\_\_tid\_OnlineBlueprintCallProxyBase\_\_](ue_ue.QuitMatchCallbackProxy.md#__tid_onlineblueprintcallproxybase__)
- [\_\_tid\_QuitMatchCallbackProxy\_\_](ue_ue.QuitMatchCallbackProxy.md#__tid_quitmatchcallbackproxy__)

### Methods

- [Activate](ue_ue.QuitMatchCallbackProxy.md#activate)
- [CreateDefaultSubobject](ue_ue.QuitMatchCallbackProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.QuitMatchCallbackProxy.md#executeubergraph)
- [GetClass](ue_ue.QuitMatchCallbackProxy.md#getclass)
- [GetName](ue_ue.QuitMatchCallbackProxy.md#getname)
- [GetOuter](ue_ue.QuitMatchCallbackProxy.md#getouter)
- [GetWorld](ue_ue.QuitMatchCallbackProxy.md#getworld)
- [Find](ue_ue.QuitMatchCallbackProxy.md#find)
- [Load](ue_ue.QuitMatchCallbackProxy.md#load)
- [QuitMatch](ue_ue.QuitMatchCallbackProxy.md#quitmatch)
- [StaticClass](ue_ue.QuitMatchCallbackProxy.md#staticclass)

## Constructors

### constructor

• **new QuitMatchCallbackProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[constructor](ue_ue.OnlineBlueprintCallProxyBase.md#constructor)

#### Defined in

[ue/ue.d.ts:58981](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58981)

## Properties

### OnFailure

• **OnFailure**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:58983](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58983)

___

### OnSuccess

• **OnSuccess**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

#### Defined in

[ue/ue.d.ts:58982](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58982)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[__tid_Object__](ue_ue.OnlineBlueprintCallProxyBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_OnlineBlueprintCallProxyBase\_\_

• **\_\_tid\_OnlineBlueprintCallProxyBase\_\_**: `boolean`

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[__tid_OnlineBlueprintCallProxyBase__](ue_ue.OnlineBlueprintCallProxyBase.md#__tid_onlineblueprintcallproxybase__)

#### Defined in

[ue/ue.d.ts:13439](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13439)

___

### \_\_tid\_QuitMatchCallbackProxy\_\_

• **\_\_tid\_QuitMatchCallbackProxy\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:58989](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58989)

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[Activate](ue_ue.OnlineBlueprintCallProxyBase.md#activate)

#### Defined in

[ue/ue.d.ts:13434](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13434)

___

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

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[CreateDefaultSubobject](ue_ue.OnlineBlueprintCallProxyBase.md#createdefaultsubobject)

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

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[ExecuteUbergraph](ue_ue.OnlineBlueprintCallProxyBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[GetClass](ue_ue.OnlineBlueprintCallProxyBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[GetName](ue_ue.OnlineBlueprintCallProxyBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[GetOuter](ue_ue.OnlineBlueprintCallProxyBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[GetWorld](ue_ue.OnlineBlueprintCallProxyBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`QuitMatchCallbackProxy`](ue_ue.QuitMatchCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`QuitMatchCallbackProxy`](ue_ue.QuitMatchCallbackProxy.md)

#### Overrides

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[Find](ue_ue.OnlineBlueprintCallProxyBase.md#find)

#### Defined in

[ue/ue.d.ts:58986](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58986)

___

### Load

▸ `Static` **Load**(`InName`): [`QuitMatchCallbackProxy`](ue_ue.QuitMatchCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`QuitMatchCallbackProxy`](ue_ue.QuitMatchCallbackProxy.md)

#### Overrides

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[Load](ue_ue.OnlineBlueprintCallProxyBase.md#load)

#### Defined in

[ue/ue.d.ts:58987](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58987)

___

### QuitMatch

▸ `Static` **QuitMatch**(`WorldContextObject`, `PlayerController`, `MatchID`, `Outcome`, `TurnTimeoutInSeconds`): [`QuitMatchCallbackProxy`](ue_ue.QuitMatchCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `MatchID` | `string` |
| `Outcome` | [`EMPMatchOutcome`](../enums/ue_ue.EMPMatchOutcome.md) |
| `TurnTimeoutInSeconds` | `number` |

#### Returns

[`QuitMatchCallbackProxy`](ue_ue.QuitMatchCallbackProxy.md)

#### Defined in

[ue/ue.d.ts:58984](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58984)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[StaticClass](ue_ue.OnlineBlueprintCallProxyBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:58985](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L58985)
