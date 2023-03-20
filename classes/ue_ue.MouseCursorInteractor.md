[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MouseCursorInteractor

# Class: MouseCursorInteractor

[ue/ue](../modules/ue_ue.md).MouseCursorInteractor

## Hierarchy

- [`ViewportInteractor`](ue_ue.ViewportInteractor.md)

  ↳ **`MouseCursorInteractor`**

## Table of contents

### Constructors

- [constructor](ue_ue.MouseCursorInteractor.md#constructor)

### Properties

- [KeyToActionMap](ue_ue.MouseCursorInteractor.md#keytoactionmap)
- [OtherInteractor](ue_ue.MouseCursorInteractor.md#otherinteractor)
- [WorldInteraction](ue_ue.MouseCursorInteractor.md#worldinteraction)
- [\_\_tid\_MouseCursorInteractor\_\_](ue_ue.MouseCursorInteractor.md#__tid_mousecursorinteractor__)
- [\_\_tid\_Object\_\_](ue_ue.MouseCursorInteractor.md#__tid_object__)
- [\_\_tid\_ViewportInteractor\_\_](ue_ue.MouseCursorInteractor.md#__tid_viewportinteractor__)

### Methods

- [CanCarry](ue_ue.MouseCursorInteractor.md#cancarry)
- [CreateDefaultSubobject](ue_ue.MouseCursorInteractor.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.MouseCursorInteractor.md#executeubergraph)
- [GetClass](ue_ue.MouseCursorInteractor.md#getclass)
- [GetDraggingMode](ue_ue.MouseCursorInteractor.md#getdraggingmode)
- [GetHitResultGizmoFilterMode](ue_ue.MouseCursorInteractor.md#gethitresultgizmofiltermode)
- [GetHoverLocation](ue_ue.MouseCursorInteractor.md#gethoverlocation)
- [GetLaserPointer](ue_ue.MouseCursorInteractor.md#getlaserpointer)
- [GetLastRoomSpaceTransform](ue_ue.MouseCursorInteractor.md#getlastroomspacetransform)
- [GetLastTransform](ue_ue.MouseCursorInteractor.md#getlasttransform)
- [GetName](ue_ue.MouseCursorInteractor.md#getname)
- [GetOtherInteractor](ue_ue.MouseCursorInteractor.md#getotherinteractor)
- [GetOuter](ue_ue.MouseCursorInteractor.md#getouter)
- [GetRoomSpaceTransform](ue_ue.MouseCursorInteractor.md#getroomspacetransform)
- [GetTransform](ue_ue.MouseCursorInteractor.md#gettransform)
- [GetTransformAndForwardVector](ue_ue.MouseCursorInteractor.md#gettransformandforwardvector)
- [GetWorld](ue_ue.MouseCursorInteractor.md#getworld)
- [GetWorldInteraction](ue_ue.MouseCursorInteractor.md#getworldinteraction)
- [HandleInputAxis\_BP](ue_ue.MouseCursorInteractor.md#handleinputaxis_bp)
- [HandleInputKey\_BP](ue_ue.MouseCursorInteractor.md#handleinputkey_bp)
- [IsHoveringOverGizmo](ue_ue.MouseCursorInteractor.md#ishoveringovergizmo)
- [SetCanCarry](ue_ue.MouseCursorInteractor.md#setcancarry)
- [SetDraggingMode](ue_ue.MouseCursorInteractor.md#setdraggingmode)
- [SetHitResultGizmoFilterMode](ue_ue.MouseCursorInteractor.md#sethitresultgizmofiltermode)
- [Shutdown](ue_ue.MouseCursorInteractor.md#shutdown)
- [Tick](ue_ue.MouseCursorInteractor.md#tick)
- [Find](ue_ue.MouseCursorInteractor.md#find)
- [Load](ue_ue.MouseCursorInteractor.md#load)
- [StaticClass](ue_ue.MouseCursorInteractor.md#staticclass)

## Constructors

### constructor

• **new MouseCursorInteractor**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ViewportInteractor](ue_ue.ViewportInteractor.md).[constructor](ue_ue.ViewportInteractor.md#constructor)

## Properties

### KeyToActionMap

• **KeyToActionMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Key`](ue_ue.Key.md), [`ViewportActionKeyInput`](ue_ue.ViewportActionKeyInput.md)\>

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[KeyToActionMap](ue_ue.ViewportInteractor.md#keytoactionmap)

___

### OtherInteractor

• **OtherInteractor**: [`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[OtherInteractor](ue_ue.ViewportInteractor.md#otherinteractor)

___

### WorldInteraction

• **WorldInteraction**: [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[WorldInteraction](ue_ue.ViewportInteractor.md#worldinteraction)

___

### \_\_tid\_MouseCursorInteractor\_\_

• **\_\_tid\_MouseCursorInteractor\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[__tid_Object__](ue_ue.ViewportInteractor.md#__tid_object__)

___

### \_\_tid\_ViewportInteractor\_\_

• **\_\_tid\_ViewportInteractor\_\_**: `boolean`

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[__tid_ViewportInteractor__](ue_ue.ViewportInteractor.md#__tid_viewportinteractor__)

## Methods

### CanCarry

▸ **CanCarry**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[CanCarry](ue_ue.ViewportInteractor.md#cancarry)

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

[ViewportInteractor](ue_ue.ViewportInteractor.md).[CreateDefaultSubobject](ue_ue.ViewportInteractor.md#createdefaultsubobject)

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

[ViewportInteractor](ue_ue.ViewportInteractor.md).[ExecuteUbergraph](ue_ue.ViewportInteractor.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetClass](ue_ue.ViewportInteractor.md#getclass)

___

### GetDraggingMode

▸ **GetDraggingMode**(): [`EViewportInteractionDraggingMode`](../enums/ue_ue.EViewportInteractionDraggingMode.md)

#### Returns

[`EViewportInteractionDraggingMode`](../enums/ue_ue.EViewportInteractionDraggingMode.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetDraggingMode](ue_ue.ViewportInteractor.md#getdraggingmode)

___

### GetHitResultGizmoFilterMode

▸ **GetHitResultGizmoFilterMode**(): [`EHitResultGizmoFilterMode`](../enums/ue_ue.EHitResultGizmoFilterMode.md)

#### Returns

[`EHitResultGizmoFilterMode`](../enums/ue_ue.EHitResultGizmoFilterMode.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetHitResultGizmoFilterMode](ue_ue.ViewportInteractor.md#gethitresultgizmofiltermode)

___

### GetHoverLocation

▸ **GetHoverLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetHoverLocation](ue_ue.ViewportInteractor.md#gethoverlocation)

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

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetLaserPointer](ue_ue.ViewportInteractor.md#getlaserpointer)

___

### GetLastRoomSpaceTransform

▸ **GetLastRoomSpaceTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetLastRoomSpaceTransform](ue_ue.ViewportInteractor.md#getlastroomspacetransform)

___

### GetLastTransform

▸ **GetLastTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetLastTransform](ue_ue.ViewportInteractor.md#getlasttransform)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetName](ue_ue.ViewportInteractor.md#getname)

___

### GetOtherInteractor

▸ **GetOtherInteractor**(): [`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Returns

[`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetOtherInteractor](ue_ue.ViewportInteractor.md#getotherinteractor)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetOuter](ue_ue.ViewportInteractor.md#getouter)

___

### GetRoomSpaceTransform

▸ **GetRoomSpaceTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetRoomSpaceTransform](ue_ue.ViewportInteractor.md#getroomspacetransform)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetTransform](ue_ue.ViewportInteractor.md#gettransform)

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

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetTransformAndForwardVector](ue_ue.ViewportInteractor.md#gettransformandforwardvector)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetWorld](ue_ue.ViewportInteractor.md#getworld)

___

### GetWorldInteraction

▸ **GetWorldInteraction**(): [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Returns

[`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetWorldInteraction](ue_ue.ViewportInteractor.md#getworldinteraction)

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

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[HandleInputAxis_BP](ue_ue.ViewportInteractor.md#handleinputaxis_bp)

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

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[HandleInputKey_BP](ue_ue.ViewportInteractor.md#handleinputkey_bp)

___

### IsHoveringOverGizmo

▸ **IsHoveringOverGizmo**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[IsHoveringOverGizmo](ue_ue.ViewportInteractor.md#ishoveringovergizmo)

___

### SetCanCarry

▸ **SetCanCarry**(`bInCanCarry`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInCanCarry` | `boolean` |

#### Returns

`void`

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[SetCanCarry](ue_ue.ViewportInteractor.md#setcancarry)

___

### SetDraggingMode

▸ **SetDraggingMode**(`NewDraggingMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewDraggingMode` | [`EViewportInteractionDraggingMode`](../enums/ue_ue.EViewportInteractionDraggingMode.md) |

#### Returns

`void`

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[SetDraggingMode](ue_ue.ViewportInteractor.md#setdraggingmode)

___

### SetHitResultGizmoFilterMode

▸ **SetHitResultGizmoFilterMode**(`newFilter`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `newFilter` | [`EHitResultGizmoFilterMode`](../enums/ue_ue.EHitResultGizmoFilterMode.md) |

#### Returns

`void`

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[SetHitResultGizmoFilterMode](ue_ue.ViewportInteractor.md#sethitresultgizmofiltermode)

___

### Shutdown

▸ **Shutdown**(): `void`

#### Returns

`void`

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[Shutdown](ue_ue.ViewportInteractor.md#shutdown)

___

### Tick

▸ **Tick**(`DeltaTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaTime` | `number` |

#### Returns

`void`

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[Tick](ue_ue.ViewportInteractor.md#tick)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MouseCursorInteractor`](ue_ue.MouseCursorInteractor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MouseCursorInteractor`](ue_ue.MouseCursorInteractor.md)

#### Overrides

[ViewportInteractor](ue_ue.ViewportInteractor.md).[Find](ue_ue.ViewportInteractor.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MouseCursorInteractor`](ue_ue.MouseCursorInteractor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MouseCursorInteractor`](ue_ue.MouseCursorInteractor.md)

#### Overrides

[ViewportInteractor](ue_ue.ViewportInteractor.md).[Load](ue_ue.ViewportInteractor.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ViewportInteractor](ue_ue.ViewportInteractor.md).[StaticClass](ue_ue.ViewportInteractor.md#staticclass)
