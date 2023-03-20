[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / WidgetAnimationPlayCallbackProxy

# Class: WidgetAnimationPlayCallbackProxy

[ue/ue](../modules/ue_ue.md).WidgetAnimationPlayCallbackProxy

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`WidgetAnimationPlayCallbackProxy`**

## Table of contents

### Constructors

- [constructor](ue_ue.WidgetAnimationPlayCallbackProxy.md#constructor)

### Properties

- [Finished](ue_ue.WidgetAnimationPlayCallbackProxy.md#finished)
- [\_\_tid\_Object\_\_](ue_ue.WidgetAnimationPlayCallbackProxy.md#__tid_object__)
- [\_\_tid\_WidgetAnimationPlayCallbackProxy\_\_](ue_ue.WidgetAnimationPlayCallbackProxy.md#__tid_widgetanimationplaycallbackproxy__)

### Methods

- [CreateDefaultSubobject](ue_ue.WidgetAnimationPlayCallbackProxy.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.WidgetAnimationPlayCallbackProxy.md#executeubergraph)
- [GetClass](ue_ue.WidgetAnimationPlayCallbackProxy.md#getclass)
- [GetName](ue_ue.WidgetAnimationPlayCallbackProxy.md#getname)
- [GetOuter](ue_ue.WidgetAnimationPlayCallbackProxy.md#getouter)
- [GetWorld](ue_ue.WidgetAnimationPlayCallbackProxy.md#getworld)
- [CreatePlayAnimationProxyObject](ue_ue.WidgetAnimationPlayCallbackProxy.md#createplayanimationproxyobject)
- [CreatePlayAnimationTimeRangeProxyObject](ue_ue.WidgetAnimationPlayCallbackProxy.md#createplayanimationtimerangeproxyobject)
- [Find](ue_ue.WidgetAnimationPlayCallbackProxy.md#find)
- [Load](ue_ue.WidgetAnimationPlayCallbackProxy.md#load)
- [StaticClass](ue_ue.WidgetAnimationPlayCallbackProxy.md#staticclass)

## Constructors

### constructor

• **new WidgetAnimationPlayCallbackProxy**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

## Properties

### Finished

• **Finished**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_WidgetAnimationPlayCallbackProxy\_\_

• **\_\_tid\_WidgetAnimationPlayCallbackProxy\_\_**: `boolean`

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

### CreatePlayAnimationProxyObject

▸ `Static` **CreatePlayAnimationProxyObject**(`Result`, `Widget`, `InAnimation`, `StartAtTime?`, `NumLoopsToPlay?`, `PlayMode?`, `PlaybackSpeed?`): [`WidgetAnimationPlayCallbackProxy`](ue_ue.WidgetAnimationPlayCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Result` | [`$Ref`](../interfaces/puerts._Ref.md)<[`UMGSequencePlayer`](ue_ue.UMGSequencePlayer.md)\> |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\> |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |
| `StartAtTime?` | `number` |
| `NumLoopsToPlay?` | `number` |
| `PlayMode?` | [`EUMGSequencePlayMode`](../enums/ue_ue.EUMGSequencePlayMode.md) |
| `PlaybackSpeed?` | `number` |

#### Returns

[`WidgetAnimationPlayCallbackProxy`](ue_ue.WidgetAnimationPlayCallbackProxy.md)

___

### CreatePlayAnimationTimeRangeProxyObject

▸ `Static` **CreatePlayAnimationTimeRangeProxyObject**(`Result`, `Widget`, `InAnimation`, `StartAtTime?`, `EndAtTime?`, `NumLoopsToPlay?`, `PlayMode?`, `PlaybackSpeed?`): [`WidgetAnimationPlayCallbackProxy`](ue_ue.WidgetAnimationPlayCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Result` | [`$Ref`](../interfaces/puerts._Ref.md)<[`UMGSequencePlayer`](ue_ue.UMGSequencePlayer.md)\> |
| `Widget` | [`$Nullable`](../modules/puerts.md#$nullable)<[`UserWidget`](ue_ue.UserWidget.md)\> |
| `InAnimation` | [`$Nullable`](../modules/puerts.md#$nullable)<[`WidgetAnimation`](ue_ue.WidgetAnimation.md)\> |
| `StartAtTime?` | `number` |
| `EndAtTime?` | `number` |
| `NumLoopsToPlay?` | `number` |
| `PlayMode?` | [`EUMGSequencePlayMode`](../enums/ue_ue.EUMGSequencePlayMode.md) |
| `PlaybackSpeed?` | `number` |

#### Returns

[`WidgetAnimationPlayCallbackProxy`](ue_ue.WidgetAnimationPlayCallbackProxy.md)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`WidgetAnimationPlayCallbackProxy`](ue_ue.WidgetAnimationPlayCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`WidgetAnimationPlayCallbackProxy`](ue_ue.WidgetAnimationPlayCallbackProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`WidgetAnimationPlayCallbackProxy`](ue_ue.WidgetAnimationPlayCallbackProxy.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`WidgetAnimationPlayCallbackProxy`](ue_ue.WidgetAnimationPlayCallbackProxy.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
