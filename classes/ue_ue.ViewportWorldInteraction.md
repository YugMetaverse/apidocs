[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ViewportWorldInteraction

# Class: ViewportWorldInteraction

[ue/ue](../modules/ue_ue.md).ViewportWorldInteraction

## Hierarchy

- [`EditorWorldExtension`](ue_ue.EditorWorldExtension.md)

  ↳ **`ViewportWorldInteraction`**

## Table of contents

### Constructors

- [constructor](ue_ue.ViewportWorldInteraction.md#constructor)

### Properties

- [ActorsToExcludeFromHitTest](ue_ue.ViewportWorldInteraction.md#actorstoexcludefromhittest)
- [AssetContainer](ue_ue.ViewportWorldInteraction.md#assetcontainer)
- [DefaultMouseCursorInteractor](ue_ue.ViewportWorldInteraction.md#defaultmousecursorinteractor)
- [ExtensionActors](ue_ue.ViewportWorldInteraction.md#extensionactors)
- [Interactors](ue_ue.ViewportWorldInteraction.md#interactors)
- [SnapGridActor](ue_ue.ViewportWorldInteraction.md#snapgridactor)
- [SnapGridMID](ue_ue.ViewportWorldInteraction.md#snapgridmid)
- [SnapGridMeshComponent](ue_ue.ViewportWorldInteraction.md#snapgridmeshcomponent)
- [TransformGizmoActor](ue_ue.ViewportWorldInteraction.md#transformgizmoactor)
- [ViewportTransformer](ue_ue.ViewportWorldInteraction.md#viewporttransformer)
- [\_\_tid\_EditorWorldExtension\_\_](ue_ue.ViewportWorldInteraction.md#__tid_editorworldextension__)
- [\_\_tid\_Object\_\_](ue_ue.ViewportWorldInteraction.md#__tid_object__)
- [\_\_tid\_ViewportWorldInteraction\_\_](ue_ue.ViewportWorldInteraction.md#__tid_viewportworldinteraction__)

### Methods

- [AddActorToExcludeFromHitTests](ue_ue.ViewportWorldInteraction.md#addactortoexcludefromhittests)
- [AddInteractor](ue_ue.ViewportWorldInteraction.md#addinteractor)
- [CreateDefaultSubobject](ue_ue.ViewportWorldInteraction.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ViewportWorldInteraction.md#executeubergraph)
- [GetClass](ue_ue.ViewportWorldInteraction.md#getclass)
- [GetHeadTransform](ue_ue.ViewportWorldInteraction.md#getheadtransform)
- [GetInteractors](ue_ue.ViewportWorldInteraction.md#getinteractors)
- [GetName](ue_ue.ViewportWorldInteraction.md#getname)
- [GetOuter](ue_ue.ViewportWorldInteraction.md#getouter)
- [GetRoomSpaceHeadTransform](ue_ue.ViewportWorldInteraction.md#getroomspaceheadtransform)
- [GetRoomTransform](ue_ue.ViewportWorldInteraction.md#getroomtransform)
- [GetTransformGizmoActor](ue_ue.ViewportWorldInteraction.md#gettransformgizmoactor)
- [GetWorld](ue_ue.ViewportWorldInteraction.md#getworld)
- [GetWorldScaleFactor](ue_ue.ViewportWorldInteraction.md#getworldscalefactor)
- [RemoveInteractor](ue_ue.ViewportWorldInteraction.md#removeinteractor)
- [SetHeadTransform](ue_ue.ViewportWorldInteraction.md#setheadtransform)
- [SetRoomTransformForNextFrame](ue_ue.ViewportWorldInteraction.md#setroomtransformfornextframe)
- [SetWorldToMetersScale](ue_ue.ViewportWorldInteraction.md#setworldtometersscale)
- [Find](ue_ue.ViewportWorldInteraction.md#find)
- [Load](ue_ue.ViewportWorldInteraction.md#load)
- [StaticClass](ue_ue.ViewportWorldInteraction.md#staticclass)

## Constructors

### constructor

• **new ViewportWorldInteraction**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[constructor](ue_ue.EditorWorldExtension.md#constructor)

#### Defined in

[ue/ue.d.ts:14477](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14477)

## Properties

### ActorsToExcludeFromHitTest

• **ActorsToExcludeFromHitTest**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`Actor`](ue_ue.Actor.md)\>\>

#### Defined in

[ue/ue.d.ts:14485](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14485)

___

### AssetContainer

• **AssetContainer**: [`ViewportInteractionAssetContainer`](ue_ue.ViewportInteractionAssetContainer.md)

#### Defined in

[ue/ue.d.ts:14486](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14486)

___

### DefaultMouseCursorInteractor

• **DefaultMouseCursorInteractor**: [`MouseCursorInteractor`](ue_ue.MouseCursorInteractor.md)

#### Defined in

[ue/ue.d.ts:14484](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14484)

___

### ExtensionActors

• **ExtensionActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EditorWorldExtensionActorData`](ue_ue.EditorWorldExtensionActorData.md)\>

#### Inherited from

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[ExtensionActors](ue_ue.EditorWorldExtension.md#extensionactors)

#### Defined in

[ue/ue.d.ts:14324](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14324)

___

### Interactors

• **Interactors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ViewportInteractor`](ue_ue.ViewportInteractor.md)\>

#### Defined in

[ue/ue.d.ts:14478](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14478)

___

### SnapGridActor

• **SnapGridActor**: [`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:14481](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14481)

___

### SnapGridMID

• **SnapGridMID**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:14483](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14483)

___

### SnapGridMeshComponent

• **SnapGridMeshComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

#### Defined in

[ue/ue.d.ts:14482](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14482)

___

### TransformGizmoActor

• **TransformGizmoActor**: [`BaseTransformGizmo`](ue_ue.BaseTransformGizmo.md)

#### Defined in

[ue/ue.d.ts:14480](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14480)

___

### ViewportTransformer

• **ViewportTransformer**: [`ViewportTransformer`](ue_ue.ViewportTransformer.md)

#### Defined in

[ue/ue.d.ts:14479](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14479)

___

### \_\_tid\_EditorWorldExtension\_\_

• **\_\_tid\_EditorWorldExtension\_\_**: `boolean`

#### Inherited from

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[__tid_EditorWorldExtension__](ue_ue.EditorWorldExtension.md#__tid_editorworldextension__)

#### Defined in

[ue/ue.d.ts:14329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14329)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[__tid_Object__](ue_ue.EditorWorldExtension.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_ViewportWorldInteraction\_\_

• **\_\_tid\_ViewportWorldInteraction\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14503](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14503)

## Methods

### AddActorToExcludeFromHitTests

▸ **AddActorToExcludeFromHitTests**(`ActorToExcludeFromHitTests`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ActorToExcludeFromHitTests` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14487](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14487)

___

### AddInteractor

▸ **AddInteractor**(`Interactor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Interactor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ViewportInteractor`](ue_ue.ViewportInteractor.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14488](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14488)

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

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[CreateDefaultSubobject](ue_ue.EditorWorldExtension.md#createdefaultsubobject)

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

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[ExecuteUbergraph](ue_ue.EditorWorldExtension.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[GetClass](ue_ue.EditorWorldExtension.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetHeadTransform

▸ **GetHeadTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:14489](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14489)

___

### GetInteractors

▸ **GetInteractors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ViewportInteractor`](ue_ue.ViewportInteractor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`ViewportInteractor`](ue_ue.ViewportInteractor.md)\>

#### Defined in

[ue/ue.d.ts:14490](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14490)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[GetName](ue_ue.EditorWorldExtension.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[GetOuter](ue_ue.EditorWorldExtension.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetRoomSpaceHeadTransform

▸ **GetRoomSpaceHeadTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:14491](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14491)

___

### GetRoomTransform

▸ **GetRoomTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:14492](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14492)

___

### GetTransformGizmoActor

▸ **GetTransformGizmoActor**(): [`BaseTransformGizmo`](ue_ue.BaseTransformGizmo.md)

#### Returns

[`BaseTransformGizmo`](ue_ue.BaseTransformGizmo.md)

#### Defined in

[ue/ue.d.ts:14493](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14493)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[GetWorld](ue_ue.EditorWorldExtension.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### GetWorldScaleFactor

▸ **GetWorldScaleFactor**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:14494](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14494)

___

### RemoveInteractor

▸ **RemoveInteractor**(`Interactor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Interactor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ViewportInteractor`](ue_ue.ViewportInteractor.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14495](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14495)

___

### SetHeadTransform

▸ **SetHeadTransform**(`NewHeadTransform`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewHeadTransform` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14496](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14496)

___

### SetRoomTransformForNextFrame

▸ **SetRoomTransformForNextFrame**(`NewRoomTransform`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRoomTransform` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14497](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14497)

___

### SetWorldToMetersScale

▸ **SetWorldToMetersScale**(`NewWorldToMetersScale`, `bCompensateRoomWorldScale?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewWorldToMetersScale` | `number` |
| `bCompensateRoomWorldScale?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14498](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14498)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Overrides

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[Find](ue_ue.EditorWorldExtension.md#find)

#### Defined in

[ue/ue.d.ts:14500](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14500)

___

### Load

▸ `Static` **Load**(`InName`): [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Overrides

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[Load](ue_ue.EditorWorldExtension.md#load)

#### Defined in

[ue/ue.d.ts:14501](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14501)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[EditorWorldExtension](ue_ue.EditorWorldExtension.md).[StaticClass](ue_ue.EditorWorldExtension.md#staticclass)

#### Defined in

[ue/ue.d.ts:14499](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14499)
