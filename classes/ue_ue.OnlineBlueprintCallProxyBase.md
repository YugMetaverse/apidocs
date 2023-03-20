[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / OnlineBlueprintCallProxyBase

# Class: OnlineBlueprintCallProxyBase

[ue/ue](../modules/ue_ue.md).OnlineBlueprintCallProxyBase

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`OnlineBlueprintCallProxyBase`**

  ↳↳ [`AchievementQueryCallbackProxy`](ue_ue.AchievementQueryCallbackProxy.md)

  ↳↳ [`AchievementWriteCallbackProxy`](ue_ue.AchievementWriteCallbackProxy.md)

  ↳↳ [`ConnectionCallbackProxy`](ue_ue.ConnectionCallbackProxy.md)

  ↳↳ [`CreateSessionCallbackProxy`](ue_ue.CreateSessionCallbackProxy.md)

  ↳↳ [`DestroySessionCallbackProxy`](ue_ue.DestroySessionCallbackProxy.md)

  ↳↳ [`EndMatchCallbackProxy`](ue_ue.EndMatchCallbackProxy.md)

  ↳↳ [`EndTurnCallbackProxy`](ue_ue.EndTurnCallbackProxy.md)

  ↳↳ [`FindSessionsCallbackProxy`](ue_ue.FindSessionsCallbackProxy.md)

  ↳↳ [`FindTurnBasedMatchCallbackProxy`](ue_ue.FindTurnBasedMatchCallbackProxy.md)

  ↳↳ [`JoinSessionCallbackProxy`](ue_ue.JoinSessionCallbackProxy.md)

  ↳↳ [`QuitMatchCallbackProxy`](ue_ue.QuitMatchCallbackProxy.md)

## Table of contents

### Constructors

- [constructor](ue_ue.OnlineBlueprintCallProxyBase.md#constructor)

### Properties

- [\_\_tid\_Object\_\_](ue_ue.OnlineBlueprintCallProxyBase.md#__tid_object__)
- [\_\_tid\_OnlineBlueprintCallProxyBase\_\_](ue_ue.OnlineBlueprintCallProxyBase.md#__tid_onlineblueprintcallproxybase__)

### Methods

- [Activate](ue_ue.OnlineBlueprintCallProxyBase.md#activate)
- [CreateDefaultSubobject](ue_ue.OnlineBlueprintCallProxyBase.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.OnlineBlueprintCallProxyBase.md#executeubergraph)
- [GetClass](ue_ue.OnlineBlueprintCallProxyBase.md#getclass)
- [GetName](ue_ue.OnlineBlueprintCallProxyBase.md#getname)
- [GetOuter](ue_ue.OnlineBlueprintCallProxyBase.md#getouter)
- [GetWorld](ue_ue.OnlineBlueprintCallProxyBase.md#getworld)
- [Find](ue_ue.OnlineBlueprintCallProxyBase.md#find)
- [Load](ue_ue.OnlineBlueprintCallProxyBase.md#load)
- [StaticClass](ue_ue.OnlineBlueprintCallProxyBase.md#staticclass)

## Constructors

### constructor

• **new OnlineBlueprintCallProxyBase**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_OnlineBlueprintCallProxyBase\_\_

• **\_\_tid\_OnlineBlueprintCallProxyBase\_\_**: `boolean`

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

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

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`OnlineBlueprintCallProxyBase`](ue_ue.OnlineBlueprintCallProxyBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`OnlineBlueprintCallProxyBase`](ue_ue.OnlineBlueprintCallProxyBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`OnlineBlueprintCallProxyBase`](ue_ue.OnlineBlueprintCallProxyBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`OnlineBlueprintCallProxyBase`](ue_ue.OnlineBlueprintCallProxyBase.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
