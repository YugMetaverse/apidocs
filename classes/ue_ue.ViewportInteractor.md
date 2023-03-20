[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ViewportInteractor

# Class: ViewportInteractor

[ue/ue](../modules/ue_ue.md).ViewportInteractor

## Hierarchy

- [`Object`](ue_ue.Object.md)

  ↳ **`ViewportInteractor`**

  ↳↳ [`MouseCursorInteractor`](ue_ue.MouseCursorInteractor.md)

  ↳↳ [`VREditorInteractor`](ue_ue.VREditorInteractor.md)

## Table of contents

### Constructors

- [constructor](ue_ue.ViewportInteractor.md#constructor)

### Properties

- [KeyToActionMap](ue_ue.ViewportInteractor.md#keytoactionmap)
- [OtherInteractor](ue_ue.ViewportInteractor.md#otherinteractor)
- [WorldInteraction](ue_ue.ViewportInteractor.md#worldinteraction)
- [\_\_tid\_Object\_\_](ue_ue.ViewportInteractor.md#__tid_object__)
- [\_\_tid\_ViewportInteractor\_\_](ue_ue.ViewportInteractor.md#__tid_viewportinteractor__)

### Methods

- [CanCarry](ue_ue.ViewportInteractor.md#cancarry)
- [CreateDefaultSubobject](ue_ue.ViewportInteractor.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ViewportInteractor.md#executeubergraph)
- [GetClass](ue_ue.ViewportInteractor.md#getclass)
- [GetDraggingMode](ue_ue.ViewportInteractor.md#getdraggingmode)
- [GetHitResultGizmoFilterMode](ue_ue.ViewportInteractor.md#gethitresultgizmofiltermode)
- [GetHoverLocation](ue_ue.ViewportInteractor.md#gethoverlocation)
- [GetLaserPointer](ue_ue.ViewportInteractor.md#getlaserpointer)
- [GetLastRoomSpaceTransform](ue_ue.ViewportInteractor.md#getlastroomspacetransform)
- [GetLastTransform](ue_ue.ViewportInteractor.md#getlasttransform)
- [GetName](ue_ue.ViewportInteractor.md#getname)
- [GetOtherInteractor](ue_ue.ViewportInteractor.md#getotherinteractor)
- [GetOuter](ue_ue.ViewportInteractor.md#getouter)
- [GetRoomSpaceTransform](ue_ue.ViewportInteractor.md#getroomspacetransform)
- [GetTransform](ue_ue.ViewportInteractor.md#gettransform)
- [GetTransformAndForwardVector](ue_ue.ViewportInteractor.md#gettransformandforwardvector)
- [GetWorld](ue_ue.ViewportInteractor.md#getworld)
- [GetWorldInteraction](ue_ue.ViewportInteractor.md#getworldinteraction)
- [HandleInputAxis\_BP](ue_ue.ViewportInteractor.md#handleinputaxis_bp)
- [HandleInputKey\_BP](ue_ue.ViewportInteractor.md#handleinputkey_bp)
- [IsHoveringOverGizmo](ue_ue.ViewportInteractor.md#ishoveringovergizmo)
- [SetCanCarry](ue_ue.ViewportInteractor.md#setcancarry)
- [SetDraggingMode](ue_ue.ViewportInteractor.md#setdraggingmode)
- [SetHitResultGizmoFilterMode](ue_ue.ViewportInteractor.md#sethitresultgizmofiltermode)
- [Shutdown](ue_ue.ViewportInteractor.md#shutdown)
- [Tick](ue_ue.ViewportInteractor.md#tick)
- [Find](ue_ue.ViewportInteractor.md#find)
- [Load](ue_ue.ViewportInteractor.md#load)
- [StaticClass](ue_ue.ViewportInteractor.md#staticclass)

## Constructors

### constructor

• **new ViewportInteractor**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[Object](ue_ue.Object.md).[constructor](ue_ue.Object.md#constructor)

#### Defined in

[ue/ue.d.ts:14349](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14349)

## Properties

### KeyToActionMap

• **KeyToActionMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Key`](ue_ue.Key.md), [`ViewportActionKeyInput`](ue_ue.ViewportActionKeyInput.md)\>

#### Defined in

[ue/ue.d.ts:14350](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14350)

___

### OtherInteractor

• **OtherInteractor**: [`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Defined in

[ue/ue.d.ts:14352](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14352)

___

### WorldInteraction

• **WorldInteraction**: [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Defined in

[ue/ue.d.ts:14351](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14351)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_ViewportInteractor\_\_

• **\_\_tid\_ViewportInteractor\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:14377](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14377)

## Methods

### CanCarry

▸ **CanCarry**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:14353](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14353)

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

### GetDraggingMode

▸ **GetDraggingMode**(): [`EViewportInteractionDraggingMode`](../enums/ue_ue.EViewportInteractionDraggingMode.md)

#### Returns

[`EViewportInteractionDraggingMode`](../enums/ue_ue.EViewportInteractionDraggingMode.md)

#### Defined in

[ue/ue.d.ts:14354](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14354)

___

### GetHitResultGizmoFilterMode

▸ **GetHitResultGizmoFilterMode**(): [`EHitResultGizmoFilterMode`](../enums/ue_ue.EHitResultGizmoFilterMode.md)

#### Returns

[`EHitResultGizmoFilterMode`](../enums/ue_ue.EHitResultGizmoFilterMode.md)

#### Defined in

[ue/ue.d.ts:14355](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14355)

___

### GetHoverLocation

▸ **GetHoverLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:14356](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14356)

___

### GetLaserPointer

▸ **GetLaserPointer**(`LaserPointerStart`, `LaserPointerEnd`, `bEvenIfBlocked?`, `LaserLengthOverride?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LaserPointerStart` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `LaserPointerEnd` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `bEvenIfBlocked?` | `boolean` |
| `LaserLengthOverride?` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:14357](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14357)

___

### GetLastRoomSpaceTransform

▸ **GetLastRoomSpaceTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:14358](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14358)

___

### GetLastTransform

▸ **GetLastTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:14359](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14359)

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

### GetOtherInteractor

▸ **GetOtherInteractor**(): [`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Returns

[`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Defined in

[ue/ue.d.ts:14360](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14360)

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

### GetRoomSpaceTransform

▸ **GetRoomSpaceTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:14361](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14361)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Defined in

[ue/ue.d.ts:14362](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14362)

___

### GetTransformAndForwardVector

▸ **GetTransformAndForwardVector**(`OutHandTransform`, `OutForwardVector`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutHandTransform` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Transform`](ue_ue_s.Transform.md)\> |
| `OutForwardVector` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:14363](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14363)

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

### GetWorldInteraction

▸ **GetWorldInteraction**(): [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Returns

[`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Defined in

[ue/ue.d.ts:14364](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14364)

___

### HandleInputAxis\_BP

▸ **HandleInputAxis_BP**(`Action`, `Key`, `Delta`, `DeltaTime`, `bOutWasHandled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Action` | [`ViewportActionKeyInput`](ue_ue.ViewportActionKeyInput.md) |
| `Key` | [`Key`](ue_ue.Key.md) |
| `Delta` | `number` |
| `DeltaTime` | `number` |
| `bOutWasHandled` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14365](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14365)

___

### HandleInputKey\_BP

▸ **HandleInputKey_BP**(`Action`, `Key`, `Event`, `bOutWasHandled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Action` | [`ViewportActionKeyInput`](ue_ue.ViewportActionKeyInput.md) |
| `Key` | [`Key`](ue_ue.Key.md) |
| `Event` | [`EInputEvent`](../enums/ue_ue.EInputEvent.md) |
| `bOutWasHandled` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14366](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14366)

___

### IsHoveringOverGizmo

▸ **IsHoveringOverGizmo**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:14367](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14367)

___

### SetCanCarry

▸ **SetCanCarry**(`bInCanCarry`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInCanCarry` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14368](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14368)

___

### SetDraggingMode

▸ **SetDraggingMode**(`NewDraggingMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewDraggingMode` | [`EViewportInteractionDraggingMode`](../enums/ue_ue.EViewportInteractionDraggingMode.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14369](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14369)

___

### SetHitResultGizmoFilterMode

▸ **SetHitResultGizmoFilterMode**(`newFilter`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `newFilter` | [`EHitResultGizmoFilterMode`](../enums/ue_ue.EHitResultGizmoFilterMode.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14370](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14370)

___

### Shutdown

▸ **Shutdown**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14371](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14371)

___

### Tick

▸ **Tick**(`DeltaTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaTime` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:14372](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14372)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Overrides

[Object](ue_ue.Object.md).[Find](ue_ue.Object.md#find)

#### Defined in

[ue/ue.d.ts:14374](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14374)

___

### Load

▸ `Static` **Load**(`InName`): [`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Overrides

[Object](ue_ue.Object.md).[Load](ue_ue.Object.md#load)

#### Defined in

[ue/ue.d.ts:14375](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14375)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)

#### Defined in

[ue/ue.d.ts:14373](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14373)
