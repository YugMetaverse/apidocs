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

## Properties

### KeyToActionMap

• **KeyToActionMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Key`](ue_ue.Key.md), [`ViewportActionKeyInput`](ue_ue.ViewportActionKeyInput.md)\>

___

### OtherInteractor

• **OtherInteractor**: [`ViewportInteractor`](ue_ue.ViewportInteractor.md)

___

### WorldInteraction

• **WorldInteraction**: [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[Object](ue_ue.Object.md).[__tid_Object__](ue_ue.Object.md#__tid_object__)

___

### \_\_tid\_ViewportInteractor\_\_

• **\_\_tid\_ViewportInteractor\_\_**: `boolean`

## Methods

### CanCarry

▸ **CanCarry**(): `boolean`

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

### GetDraggingMode

▸ **GetDraggingMode**(): [`EViewportInteractionDraggingMode`](../enums/ue_ue.EViewportInteractionDraggingMode.md)

#### Returns

[`EViewportInteractionDraggingMode`](../enums/ue_ue.EViewportInteractionDraggingMode.md)

___

### GetHitResultGizmoFilterMode

▸ **GetHitResultGizmoFilterMode**(): [`EHitResultGizmoFilterMode`](../enums/ue_ue.EHitResultGizmoFilterMode.md)

#### Returns

[`EHitResultGizmoFilterMode`](../enums/ue_ue.EHitResultGizmoFilterMode.md)

___

### GetHoverLocation

▸ **GetHoverLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

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

___

### GetLastRoomSpaceTransform

▸ **GetLastRoomSpaceTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

___

### GetLastTransform

▸ **GetLastTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[Object](ue_ue.Object.md).[GetName](ue_ue.Object.md#getname)

___

### GetOtherInteractor

▸ **GetOtherInteractor**(): [`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Returns

[`ViewportInteractor`](ue_ue.ViewportInteractor.md)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetOuter](ue_ue.Object.md#getouter)

___

### GetRoomSpaceTransform

▸ **GetRoomSpaceTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

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

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[Object](ue_ue.Object.md).[GetWorld](ue_ue.Object.md#getworld)

___

### GetWorldInteraction

▸ **GetWorldInteraction**(): [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Returns

[`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

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

___

### IsHoveringOverGizmo

▸ **IsHoveringOverGizmo**(): `boolean`

#### Returns

`boolean`

___

### SetCanCarry

▸ **SetCanCarry**(`bInCanCarry`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInCanCarry` | `boolean` |

#### Returns

`void`

___

### SetDraggingMode

▸ **SetDraggingMode**(`NewDraggingMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewDraggingMode` | [`EViewportInteractionDraggingMode`](../enums/ue_ue.EViewportInteractionDraggingMode.md) |

#### Returns

`void`

___

### SetHitResultGizmoFilterMode

▸ **SetHitResultGizmoFilterMode**(`newFilter`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `newFilter` | [`EHitResultGizmoFilterMode`](../enums/ue_ue.EHitResultGizmoFilterMode.md) |

#### Returns

`void`

___

### Shutdown

▸ **Shutdown**(): `void`

#### Returns

`void`

___

### Tick

▸ **Tick**(`DeltaTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaTime` | `number` |

#### Returns

`void`

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[Object](ue_ue.Object.md).[StaticClass](ue_ue.Object.md#staticclass)
