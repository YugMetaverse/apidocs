[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AchievementQueryCallbackProxy

# Class: AchievementQueryCallbackProxy

[ue/ue](../modules/ue_ue.md).AchievementQueryCallbackProxy

## Hierarchy

- [`OnlineBlueprintCallProxyBase`](ue_ue.OnlineBlueprintCallProxyBase.md)

  ↳ **`AchievementQueryCallbackProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.AchievementQueryCallbackProxy.md#constructor)

### Properties

- [OnFailure](ue_ue.AchievementQueryCallbackProxy.md#onfailure)
- [OnSuccess](ue_ue.AchievementQueryCallbackProxy.md#onsuccess)
- [\_\_tid\_AchievementQueryCallbackProxy\_\_](ue_ue.AchievementQueryCallbackProxy.md#__tid_achievementquerycallbackproxy__)
- [\_\_tid\_Object\_\_](ue_ue.AchievementQueryCallbackProxy.md#__tid_object__)
- [\_\_tid\_OnlineBlueprintCallProxyBase\_\_](ue_ue.AchievementQueryCallbackProxy.md#__tid_onlineblueprintcallproxybase__)

### Methods

- [Activate](ue_ue.AchievementQueryCallbackProxy.md#activate)
- [CreateDefaultSubobject](ue_ue.AchievementQueryCallbackProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.AchievementQueryCallbackProxy.md#executeubergraph)
- [GetClass](ue_ue.AchievementQueryCallbackProxy.md#getclass)
- [GetName](ue_ue.AchievementQueryCallbackProxy.md#getname)
- [GetOuter](ue_ue.AchievementQueryCallbackProxy.md#getouter)
- [GetWorld](ue_ue.AchievementQueryCallbackProxy.md#getworld)
- [CacheAchievementDescriptions](ue_ue.AchievementQueryCallbackProxy.md#cacheachievementdescriptions)
- [CacheAchievements](ue_ue.AchievementQueryCallbackProxy.md#cacheachievements)
- [Find](ue_ue.AchievementQueryCallbackProxy.md#find)
- [Load](ue_ue.AchievementQueryCallbackProxy.md#load)
- [StaticClass](ue_ue.AchievementQueryCallbackProxy.md#staticclass)

## Constructors

### constructor

• **new AchievementQueryCallbackProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[constructor](ue_ue.OnlineBlueprintCallProxyBase.md#constructor)

## Properties

### OnFailure

• **OnFailure**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnSuccess

• **OnSuccess**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### \_\_tid\_AchievementQueryCallbackProxy\_\_

• **\_\_tid\_AchievementQueryCallbackProxy\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[__tid_Object__](ue_ue.OnlineBlueprintCallProxyBase.md#__tid_object__)

___

### \_\_tid\_OnlineBlueprintCallProxyBase\_\_

• **\_\_tid\_OnlineBlueprintCallProxyBase\_\_**: `boolean`

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[__tid_OnlineBlueprintCallProxyBase__](ue_ue.OnlineBlueprintCallProxyBase.md#__tid_onlineblueprintcallproxybase__)

## Methods

### Activate

▸ **Activate**(): `void`

#### Returns

`void`

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[Activate](ue_ue.OnlineBlueprintCallProxyBase.md#activate)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[GetClass](ue_ue.OnlineBlueprintCallProxyBase.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[GetName](ue_ue.OnlineBlueprintCallProxyBase.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[GetOuter](ue_ue.OnlineBlueprintCallProxyBase.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[GetWorld](ue_ue.OnlineBlueprintCallProxyBase.md#getworld)

___

### CacheAchievementDescriptions

▸ `Static` **CacheAchievementDescriptions**(`WorldContextObject`, `PlayerController`): [`AchievementQueryCallbackProxy`](ue_ue.AchievementQueryCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

[`AchievementQueryCallbackProxy`](ue_ue.AchievementQueryCallbackProxy.md)

___

### CacheAchievements

▸ `Static` **CacheAchievements**(`WorldContextObject`, `PlayerController`): [`AchievementQueryCallbackProxy`](ue_ue.AchievementQueryCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PlayerController` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

[`AchievementQueryCallbackProxy`](ue_ue.AchievementQueryCallbackProxy.md)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AchievementQueryCallbackProxy`](ue_ue.AchievementQueryCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AchievementQueryCallbackProxy`](ue_ue.AchievementQueryCallbackProxy.md)

#### Overrides

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[Find](ue_ue.OnlineBlueprintCallProxyBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AchievementQueryCallbackProxy`](ue_ue.AchievementQueryCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AchievementQueryCallbackProxy`](ue_ue.AchievementQueryCallbackProxy.md)

#### Overrides

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[Load](ue_ue.OnlineBlueprintCallProxyBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[OnlineBlueprintCallProxyBase](ue_ue.OnlineBlueprintCallProxyBase.md).[StaticClass](ue_ue.OnlineBlueprintCallProxyBase.md#staticclass)
