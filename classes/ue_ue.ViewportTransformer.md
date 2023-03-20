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

## Properties

### ViewportWorldInteraction

• **ViewportWorldInteraction**: [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_ViewportTransformer\_\_

• **\_\_tid\_ViewportTransformer\_\_**: `boolean`

## Methods

### CanAlignToActors

▸ **CanAlignToActors**(): `boolean`

#### Returns

`boolean`

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

### Init

▸ **Init**(`InitViewportWorldInteraction`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InitViewportWorldInteraction` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)\> |

#### Returns

`void`

___

### OnStartDragging

▸ **OnStartDragging**(`Interactor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Interactor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ViewportInteractor`](ue_ue.ViewportInteractor.md)\> |

#### Returns

`void`

___

### OnStopDragging

▸ **OnStopDragging**(`Interactor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Interactor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ViewportInteractor`](ue_ue.ViewportInteractor.md)\> |

#### Returns

`void`

___

### ShouldCenterTransformGizmoPivot

▸ **ShouldCenterTransformGizmoPivot**(): `boolean`

#### Returns

`boolean`

___

### Shutdown

▸ **Shutdown**(): `void`

#### Returns

`void`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
