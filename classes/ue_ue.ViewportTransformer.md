[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ViewportTransformer

# Class: ViewportTransformer

[ue/ue](../modules/ue_ue.md).ViewportTransformer

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ViewportTransformer`**

  ↳↳ [`ActorTransformer`](ue_ue.ActorTransformer.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ViewportTransformer.md#constructor)

### Properties

- [ViewportWorldInteraction](ue_ue.ViewportTransformer.md#viewportworldinteraction)
- [\_\_tid\_Object\_\_](ue_ue.ViewportTransformer.md#__tid_object__)
- [\_\_tid\_ViewportTransformer\_\_](ue_ue.ViewportTransformer.md#__tid_viewporttransformer__)

### Methods

- [CanAlignToActors](ue_ue.ViewportTransformer.md#canaligntoactors)
- [CreateDefaultSubobject](ue_ue.ViewportTransformer.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ViewportTransformer.md#executeubergraph)
- [GetClass](ue_ue.ViewportTransformer.md#getclass)
- [GetName](ue_ue.ViewportTransformer.md#getname)
- [GetOuter](ue_ue.ViewportTransformer.md#getouter)
- [GetWorld](ue_ue.ViewportTransformer.md#getworld)
- [Init](ue_ue.ViewportTransformer.md#init)
- [OnStartDragging](ue_ue.ViewportTransformer.md#onstartdragging)
- [OnStopDragging](ue_ue.ViewportTransformer.md#onstopdragging)
- [ShouldCenterTransformGizmoPivot](ue_ue.ViewportTransformer.md#shouldcentertransformgizmopivot)
- [Shutdown](ue_ue.ViewportTransformer.md#shutdown)
- [Find](ue_ue.ViewportTransformer.md#find)
- [Load](ue_ue.ViewportTransformer.md#load)
- [StaticClass](ue_ue.ViewportTransformer.md#staticclass)

## Constructors

### constructor

• **new ViewportTransformer**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:14507](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14507)

## Properties

### ViewportWorldInteraction

• **ViewportWorldInteraction**: [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Defined in

[ue/ue.d.ts:14508](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14508)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ViewportTransformer\_\_

• **\_\_tid\_ViewportTransformer\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14519](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14519)

## Methods

### CanAlignToActors

▸ **CanAlignToActors**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:14509](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14509)

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

### Init

▸ **Init**(`InitViewportWorldInteraction`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InitViewportWorldInteraction` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14510](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14510)

___

### OnStartDragging

▸ **OnStartDragging**(`Interactor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Interactor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ViewportInteractor`](ue_ue.ViewportInteractor.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14511](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14511)

___

### OnStopDragging

▸ **OnStopDragging**(`Interactor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Interactor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ViewportInteractor`](ue_ue.ViewportInteractor.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14512](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14512)

___

### ShouldCenterTransformGizmoPivot

▸ **ShouldCenterTransformGizmoPivot**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:14513](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14513)

___

### Shutdown

▸ **Shutdown**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14514](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14514)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ViewportTransformer`](ue_ue.ViewportTransformer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ViewportTransformer`](ue_ue.ViewportTransformer.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:14516](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14516)

___

### Load

▸ `Static` **Load**(`InName`): [`ViewportTransformer`](ue_ue.ViewportTransformer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ViewportTransformer`](ue_ue.ViewportTransformer.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:14517](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14517)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:14515](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14515)
