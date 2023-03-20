[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ActorTransformer

# Class: ActorTransformer

[ue/ue](../modules/ue_ue.md).ActorTransformer

## Hierarchy

- [`ViewportTransformer`](ue_ue.ViewportTransformer.md)

  ↳ **`ActorTransformer`**

## Table of contents

### Constructors

- [constructor](ue_ue.ActorTransformer.md#constructor)

### Properties

- [ViewportWorldInteraction](ue_ue.ActorTransformer.md#viewportworldinteraction)
- [\_\_tid\_ActorTransformer\_\_](ue_ue.ActorTransformer.md#__tid_actortransformer__)
- [\_\_tid\_Object\_\_](ue_ue.ActorTransformer.md#__tid_object__)
- [\_\_tid\_ViewportTransformer\_\_](ue_ue.ActorTransformer.md#__tid_viewporttransformer__)

### Methods

- [CanAlignToActors](ue_ue.ActorTransformer.md#canaligntoactors)
- [CreateDefaultSubobject](ue_ue.ActorTransformer.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ActorTransformer.md#executeubergraph)
- [GetClass](ue_ue.ActorTransformer.md#getclass)
- [GetName](ue_ue.ActorTransformer.md#getname)
- [GetOuter](ue_ue.ActorTransformer.md#getouter)
- [GetWorld](ue_ue.ActorTransformer.md#getworld)
- [Init](ue_ue.ActorTransformer.md#init)
- [OnStartDragging](ue_ue.ActorTransformer.md#onstartdragging)
- [OnStopDragging](ue_ue.ActorTransformer.md#onstopdragging)
- [ShouldCenterTransformGizmoPivot](ue_ue.ActorTransformer.md#shouldcentertransformgizmopivot)
- [Shutdown](ue_ue.ActorTransformer.md#shutdown)
- [Find](ue_ue.ActorTransformer.md#find)
- [Load](ue_ue.ActorTransformer.md#load)
- [StaticClass](ue_ue.ActorTransformer.md#staticclass)

## Constructors

### constructor

• **new ActorTransformer**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ViewportTransformer](ue_ue.ViewportTransformer.md).[constructor](ue_ue.ViewportTransformer.md#constructor)

#### Defined in

[ue/ue.d.ts:14523](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14523)

## Properties

### ViewportWorldInteraction

• **ViewportWorldInteraction**: [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Inherited from

[ViewportTransformer](ue_ue.ViewportTransformer.md).[ViewportWorldInteraction](ue_ue.ViewportTransformer.md#viewportworldinteraction)

#### Defined in

[ue/ue.d.ts:14508](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14508)

___

### \_\_tid\_ActorTransformer\_\_

• **\_\_tid\_ActorTransformer\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14528](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14528)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ViewportTransformer](ue_ue.ViewportTransformer.md).[__tid_Object__](ue_ue.ViewportTransformer.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_ViewportTransformer\_\_

• **\_\_tid\_ViewportTransformer\_\_**: `boolean`

#### Inherited from

[ViewportTransformer](ue_ue.ViewportTransformer.md).[__tid_ViewportTransformer__](ue_ue.ViewportTransformer.md#__tid_viewporttransformer__)

#### Defined in

[ue/ue.d.ts:14519](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14519)

## Methods

### CanAlignToActors

▸ **CanAlignToActors**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ViewportTransformer](ue_ue.ViewportTransformer.md).[CanAlignToActors](ue_ue.ViewportTransformer.md#canaligntoactors)

#### Defined in

[ue/ue.d.ts:14509](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14509)

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

[ViewportTransformer](ue_ue.ViewportTransformer.md).[CreateDefaultSubobject](ue_ue.ViewportTransformer.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[ViewportTransformer](ue_ue.ViewportTransformer.md).[ExecuteUbergraph](ue_ue.ViewportTransformer.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ViewportTransformer](ue_ue.ViewportTransformer.md).[GetClass](ue_ue.ViewportTransformer.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ViewportTransformer](ue_ue.ViewportTransformer.md).[GetName](ue_ue.ViewportTransformer.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ViewportTransformer](ue_ue.ViewportTransformer.md).[GetOuter](ue_ue.ViewportTransformer.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ViewportTransformer](ue_ue.ViewportTransformer.md).[GetWorld](ue_ue.ViewportTransformer.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Init

▸ **Init**(`InitViewportWorldInteraction`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InitViewportWorldInteraction` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)\> |

#### Returns

`void`

#### Inherited from

[ViewportTransformer](ue_ue.ViewportTransformer.md).[Init](ue_ue.ViewportTransformer.md#init)

#### Defined in

[ue/ue.d.ts:14510](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14510)

___

### OnStartDragging

▸ **OnStartDragging**(`Interactor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Interactor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ViewportInteractor`](ue_ue.ViewportInteractor.md)\> |

#### Returns

`void`

#### Inherited from

[ViewportTransformer](ue_ue.ViewportTransformer.md).[OnStartDragging](ue_ue.ViewportTransformer.md#onstartdragging)

#### Defined in

[ue/ue.d.ts:14511](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14511)

___

### OnStopDragging

▸ **OnStopDragging**(`Interactor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Interactor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ViewportInteractor`](ue_ue.ViewportInteractor.md)\> |

#### Returns

`void`

#### Inherited from

[ViewportTransformer](ue_ue.ViewportTransformer.md).[OnStopDragging](ue_ue.ViewportTransformer.md#onstopdragging)

#### Defined in

[ue/ue.d.ts:14512](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14512)

___

### ShouldCenterTransformGizmoPivot

▸ **ShouldCenterTransformGizmoPivot**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ViewportTransformer](ue_ue.ViewportTransformer.md).[ShouldCenterTransformGizmoPivot](ue_ue.ViewportTransformer.md#shouldcentertransformgizmopivot)

#### Defined in

[ue/ue.d.ts:14513](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14513)

___

### Shutdown

▸ **Shutdown**(): `void`

#### Returns

`void`

#### Inherited from

[ViewportTransformer](ue_ue.ViewportTransformer.md).[Shutdown](ue_ue.ViewportTransformer.md#shutdown)

#### Defined in

[ue/ue.d.ts:14514](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14514)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ActorTransformer`](ue_ue.ActorTransformer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ActorTransformer`](ue_ue.ActorTransformer.md)

#### Overrides

[ViewportTransformer](ue_ue.ViewportTransformer.md).[Find](ue_ue.ViewportTransformer.md#find)

#### Defined in

[ue/ue.d.ts:14525](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14525)

___

### Load

▸ `Static` **Load**(`InName`): [`ActorTransformer`](ue_ue.ActorTransformer.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ActorTransformer`](ue_ue.ActorTransformer.md)

#### Overrides

[ViewportTransformer](ue_ue.ViewportTransformer.md).[Load](ue_ue.ViewportTransformer.md#load)

#### Defined in

[ue/ue.d.ts:14526](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14526)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ViewportTransformer](ue_ue.ViewportTransformer.md).[StaticClass](ue_ue.ViewportTransformer.md#staticclass)

#### Defined in

[ue/ue.d.ts:14524](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14524)
