[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VRScoutingInteractor

# Class: VRScoutingInteractor

[ue/ue](../modules/ue_ue.md).VRScoutingInteractor

## Hierarchy

- [`VREditorInteractor`](ue_ue.VREditorInteractor.md)

  ↳ **`VRScoutingInteractor`**

## Table of contents

### Constructors

- [constructor](ue_ue.VRScoutingInteractor.md#constructor)

### Properties

- [ControllerMotionSource](ue_ue.VRScoutingInteractor.md#controllermotionsource)
- [ControllerType](ue_ue.VRScoutingInteractor.md#controllertype)
- [FlyingIndicatorComponent](ue_ue.VRScoutingInteractor.md#flyingindicatorcomponent)
- [HandMeshComponent](ue_ue.VRScoutingInteractor.md#handmeshcomponent)
- [HandMeshMID](ue_ue.VRScoutingInteractor.md#handmeshmid)
- [HoverMeshComponent](ue_ue.VRScoutingInteractor.md#hovermeshcomponent)
- [HoverPointLightComponent](ue_ue.VRScoutingInteractor.md#hoverpointlightcomponent)
- [KeyToActionMap](ue_ue.VRScoutingInteractor.md#keytoactionmap)
- [LaserPointerMID](ue_ue.VRScoutingInteractor.md#laserpointermid)
- [LaserSplineComponent](ue_ue.VRScoutingInteractor.md#lasersplinecomponent)
- [LaserSplineMeshComponents](ue_ue.VRScoutingInteractor.md#lasersplinemeshcomponents)
- [MotionControllerComponent](ue_ue.VRScoutingInteractor.md#motioncontrollercomponent)
- [OtherInteractor](ue_ue.VRScoutingInteractor.md#otherinteractor)
- [OverrideControllerType](ue_ue.VRScoutingInteractor.md#overridecontrollertype)
- [OwningAvatar](ue_ue.VRScoutingInteractor.md#owningavatar)
- [TranslucentLaserPointerMID](ue_ue.VRScoutingInteractor.md#translucentlaserpointermid)
- [VRMode](ue_ue.VRScoutingInteractor.md#vrmode)
- [WorldInteraction](ue_ue.VRScoutingInteractor.md#worldinteraction)
- [\_\_tid\_Object\_\_](ue_ue.VRScoutingInteractor.md#__tid_object__)
- [\_\_tid\_VREditorInteractor\_\_](ue_ue.VRScoutingInteractor.md#__tid_vreditorinteractor__)
- [\_\_tid\_VRScoutingInteractor\_\_](ue_ue.VRScoutingInteractor.md#__tid_vrscoutinginteractor__)
- [\_\_tid\_ViewportInteractor\_\_](ue_ue.VRScoutingInteractor.md#__tid_viewportinteractor__)
- [bIsUndoRedoSwipeEnabled](ue_ue.VRScoutingInteractor.md#bisundoredoswipeenabled)

### Methods

- [CanCarry](ue_ue.VRScoutingInteractor.md#cancarry)
- [CreateDefaultSubobject](ue_ue.VRScoutingInteractor.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.VRScoutingInteractor.md#executeubergraph)
- [GetClass](ue_ue.VRScoutingInteractor.md#getclass)
- [GetControllerSide](ue_ue.VRScoutingInteractor.md#getcontrollerside)
- [GetControllerType](ue_ue.VRScoutingInteractor.md#getcontrollertype)
- [GetDraggingMode](ue_ue.VRScoutingInteractor.md#getdraggingmode)
- [GetGizmoMode](ue_ue.VRScoutingInteractor.md#getgizmomode)
- [GetHMDDeviceType](ue_ue.VRScoutingInteractor.md#gethmddevicetype)
- [GetHitResultGizmoFilterMode](ue_ue.VRScoutingInteractor.md#gethitresultgizmofiltermode)
- [GetHoverLocation](ue_ue.VRScoutingInteractor.md#gethoverlocation)
- [GetLaserEnd](ue_ue.VRScoutingInteractor.md#getlaserend)
- [GetLaserPointer](ue_ue.VRScoutingInteractor.md#getlaserpointer)
- [GetLaserStart](ue_ue.VRScoutingInteractor.md#getlaserstart)
- [GetLastRoomSpaceTransform](ue_ue.VRScoutingInteractor.md#getlastroomspacetransform)
- [GetLastTrackpadPosition](ue_ue.VRScoutingInteractor.md#getlasttrackpadposition)
- [GetLastTransform](ue_ue.VRScoutingInteractor.md#getlasttransform)
- [GetMotionControllerComponent](ue_ue.VRScoutingInteractor.md#getmotioncontrollercomponent)
- [GetName](ue_ue.VRScoutingInteractor.md#getname)
- [GetOtherInteractor](ue_ue.VRScoutingInteractor.md#getotherinteractor)
- [GetOuter](ue_ue.VRScoutingInteractor.md#getouter)
- [GetRoomSpaceTransform](ue_ue.VRScoutingInteractor.md#getroomspacetransform)
- [GetSelectAndMoveTriggerValue](ue_ue.VRScoutingInteractor.md#getselectandmovetriggervalue)
- [GetSlideDelta](ue_ue.VRScoutingInteractor.md#getslidedelta)
- [GetTeleportActor](ue_ue.VRScoutingInteractor.md#getteleportactor)
- [GetTrackpadPosition](ue_ue.VRScoutingInteractor.md#gettrackpadposition)
- [GetTransform](ue_ue.VRScoutingInteractor.md#gettransform)
- [GetTransformAndForwardVector](ue_ue.VRScoutingInteractor.md#gettransformandforwardvector)
- [GetWorld](ue_ue.VRScoutingInteractor.md#getworld)
- [GetWorldInteraction](ue_ue.VRScoutingInteractor.md#getworldinteraction)
- [HandleInputAxis\_BP](ue_ue.VRScoutingInteractor.md#handleinputaxis_bp)
- [HandleInputKey\_BP](ue_ue.VRScoutingInteractor.md#handleinputkey_bp)
- [Init](ue_ue.VRScoutingInteractor.md#init)
- [IsClickingOnUI](ue_ue.VRScoutingInteractor.md#isclickingonui)
- [IsHoveringOverGizmo](ue_ue.VRScoutingInteractor.md#ishoveringovergizmo)
- [IsHoveringOverUI](ue_ue.VRScoutingInteractor.md#ishoveringoverui)
- [IsTouchingTrackpad](ue_ue.VRScoutingInteractor.md#istouchingtrackpad)
- [ReplaceHandMeshComponent](ue_ue.VRScoutingInteractor.md#replacehandmeshcomponent)
- [SetCanCarry](ue_ue.VRScoutingInteractor.md#setcancarry)
- [SetControllerHandSide](ue_ue.VRScoutingInteractor.md#setcontrollerhandside)
- [SetControllerType](ue_ue.VRScoutingInteractor.md#setcontrollertype)
- [SetDraggingMode](ue_ue.VRScoutingInteractor.md#setdraggingmode)
- [SetForceLaserColor](ue_ue.VRScoutingInteractor.md#setforcelasercolor)
- [SetForceShowLaser](ue_ue.VRScoutingInteractor.md#setforceshowlaser)
- [SetGizmoMode](ue_ue.VRScoutingInteractor.md#setgizmomode)
- [SetHitResultGizmoFilterMode](ue_ue.VRScoutingInteractor.md#sethitresultgizmofiltermode)
- [SetupComponent](ue_ue.VRScoutingInteractor.md#setupcomponent)
- [Shutdown](ue_ue.VRScoutingInteractor.md#shutdown)
- [Tick](ue_ue.VRScoutingInteractor.md#tick)
- [TryOverrideControllerType](ue_ue.VRScoutingInteractor.md#tryoverridecontrollertype)
- [Find](ue_ue.VRScoutingInteractor.md#find)
- [GetSelectedActors](ue_ue.VRScoutingInteractor.md#getselectedactors)
- [Load](ue_ue.VRScoutingInteractor.md#load)
- [StaticClass](ue_ue.VRScoutingInteractor.md#staticclass)

## Constructors

### constructor

• **new VRScoutingInteractor**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[VREditorInteractor](ue_ue.VREditorInteractor.md).[constructor](ue_ue.VREditorInteractor.md#constructor)

## Properties

### ControllerMotionSource

• **ControllerMotionSource**: `string`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[ControllerMotionSource](ue_ue.VREditorInteractor.md#controllermotionsource)

___

### ControllerType

• **ControllerType**: [`EControllerType`](../enums/ue_ue.EControllerType.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[ControllerType](ue_ue.VREditorInteractor.md#controllertype)

___

### FlyingIndicatorComponent

• **FlyingIndicatorComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

___

### HandMeshComponent

• **HandMeshComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[HandMeshComponent](ue_ue.VREditorInteractor.md#handmeshcomponent)

___

### HandMeshMID

• **HandMeshMID**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[HandMeshMID](ue_ue.VREditorInteractor.md#handmeshmid)

___

### HoverMeshComponent

• **HoverMeshComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[HoverMeshComponent](ue_ue.VREditorInteractor.md#hovermeshcomponent)

___

### HoverPointLightComponent

• **HoverPointLightComponent**: [`PointLightComponent`](ue_ue.PointLightComponent.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[HoverPointLightComponent](ue_ue.VREditorInteractor.md#hoverpointlightcomponent)

___

### KeyToActionMap

• **KeyToActionMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Key`](ue_ue.Key.md), [`ViewportActionKeyInput`](ue_ue.ViewportActionKeyInput.md)\>

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[KeyToActionMap](ue_ue.VREditorInteractor.md#keytoactionmap)

___

### LaserPointerMID

• **LaserPointerMID**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[LaserPointerMID](ue_ue.VREditorInteractor.md#laserpointermid)

___

### LaserSplineComponent

• **LaserSplineComponent**: [`SplineComponent`](ue_ue.SplineComponent.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[LaserSplineComponent](ue_ue.VREditorInteractor.md#lasersplinecomponent)

___

### LaserSplineMeshComponents

• **LaserSplineMeshComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SplineMeshComponent`](ue_ue.SplineMeshComponent.md)\>

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[LaserSplineMeshComponents](ue_ue.VREditorInteractor.md#lasersplinemeshcomponents)

___

### MotionControllerComponent

• **MotionControllerComponent**: [`MotionControllerComponent`](ue_ue.MotionControllerComponent.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[MotionControllerComponent](ue_ue.VREditorInteractor.md#motioncontrollercomponent)

___

### OtherInteractor

• **OtherInteractor**: [`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[OtherInteractor](ue_ue.VREditorInteractor.md#otherinteractor)

___

### OverrideControllerType

• **OverrideControllerType**: [`EControllerType`](../enums/ue_ue.EControllerType.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[OverrideControllerType](ue_ue.VREditorInteractor.md#overridecontrollertype)

___

### OwningAvatar

• **OwningAvatar**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[OwningAvatar](ue_ue.VREditorInteractor.md#owningavatar)

___

### TranslucentLaserPointerMID

• **TranslucentLaserPointerMID**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[TranslucentLaserPointerMID](ue_ue.VREditorInteractor.md#translucentlaserpointermid)

___

### VRMode

• **VRMode**: [`VREditorMode`](ue_ue.VREditorMode.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[VRMode](ue_ue.VREditorInteractor.md#vrmode)

___

### WorldInteraction

• **WorldInteraction**: [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[WorldInteraction](ue_ue.VREditorInteractor.md#worldinteraction)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[__tid_Object__](ue_ue.VREditorInteractor.md#__tid_object__)

___

### \_\_tid\_VREditorInteractor\_\_

• **\_\_tid\_VREditorInteractor\_\_**: `boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[__tid_VREditorInteractor__](ue_ue.VREditorInteractor.md#__tid_vreditorinteractor__)

___

### \_\_tid\_VRScoutingInteractor\_\_

• **\_\_tid\_VRScoutingInteractor\_\_**: `boolean`

___

### \_\_tid\_ViewportInteractor\_\_

• **\_\_tid\_ViewportInteractor\_\_**: `boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[__tid_ViewportInteractor__](ue_ue.VREditorInteractor.md#__tid_viewportinteractor__)

___

### bIsUndoRedoSwipeEnabled

• **bIsUndoRedoSwipeEnabled**: `boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[bIsUndoRedoSwipeEnabled](ue_ue.VREditorInteractor.md#bisundoredoswipeenabled)

## Methods

### CanCarry

▸ **CanCarry**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[CanCarry](ue_ue.VREditorInteractor.md#cancarry)

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

[VREditorInteractor](ue_ue.VREditorInteractor.md).[CreateDefaultSubobject](ue_ue.VREditorInteractor.md#createdefaultsubobject)

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

[VREditorInteractor](ue_ue.VREditorInteractor.md).[ExecuteUbergraph](ue_ue.VREditorInteractor.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetClass](ue_ue.VREditorInteractor.md#getclass)

___

### GetControllerSide

▸ **GetControllerSide**(): [`EControllerHand`](../enums/ue_ue.EControllerHand.md)

#### Returns

[`EControllerHand`](../enums/ue_ue.EControllerHand.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetControllerSide](ue_ue.VREditorInteractor.md#getcontrollerside)

___

### GetControllerType

▸ **GetControllerType**(): [`EControllerType`](../enums/ue_ue.EControllerType.md)

#### Returns

[`EControllerType`](../enums/ue_ue.EControllerType.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetControllerType](ue_ue.VREditorInteractor.md#getcontrollertype)

___

### GetDraggingMode

▸ **GetDraggingMode**(): [`EViewportInteractionDraggingMode`](../enums/ue_ue.EViewportInteractionDraggingMode.md)

#### Returns

[`EViewportInteractionDraggingMode`](../enums/ue_ue.EViewportInteractionDraggingMode.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetDraggingMode](ue_ue.VREditorInteractor.md#getdraggingmode)

___

### GetGizmoMode

▸ **GetGizmoMode**(): [`EGizmoHandleTypes`](../enums/ue_ue.EGizmoHandleTypes.md)

#### Returns

[`EGizmoHandleTypes`](../enums/ue_ue.EGizmoHandleTypes.md)

___

### GetHMDDeviceType

▸ **GetHMDDeviceType**(): `string`

#### Returns

`string`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetHMDDeviceType](ue_ue.VREditorInteractor.md#gethmddevicetype)

___

### GetHitResultGizmoFilterMode

▸ **GetHitResultGizmoFilterMode**(): [`EHitResultGizmoFilterMode`](../enums/ue_ue.EHitResultGizmoFilterMode.md)

#### Returns

[`EHitResultGizmoFilterMode`](../enums/ue_ue.EHitResultGizmoFilterMode.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetHitResultGizmoFilterMode](ue_ue.VREditorInteractor.md#gethitresultgizmofiltermode)

___

### GetHoverLocation

▸ **GetHoverLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetHoverLocation](ue_ue.VREditorInteractor.md#gethoverlocation)

___

### GetLaserEnd

▸ **GetLaserEnd**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetLaserEnd](ue_ue.VREditorInteractor.md#getlaserend)

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

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetLaserPointer](ue_ue.VREditorInteractor.md#getlaserpointer)

___

### GetLaserStart

▸ **GetLaserStart**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetLaserStart](ue_ue.VREditorInteractor.md#getlaserstart)

___

### GetLastRoomSpaceTransform

▸ **GetLastRoomSpaceTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetLastRoomSpaceTransform](ue_ue.VREditorInteractor.md#getlastroomspacetransform)

___

### GetLastTrackpadPosition

▸ **GetLastTrackpadPosition**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetLastTrackpadPosition](ue_ue.VREditorInteractor.md#getlasttrackpadposition)

___

### GetLastTransform

▸ **GetLastTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetLastTransform](ue_ue.VREditorInteractor.md#getlasttransform)

___

### GetMotionControllerComponent

▸ **GetMotionControllerComponent**(): [`MotionControllerComponent`](ue_ue.MotionControllerComponent.md)

#### Returns

[`MotionControllerComponent`](ue_ue.MotionControllerComponent.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetMotionControllerComponent](ue_ue.VREditorInteractor.md#getmotioncontrollercomponent)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetName](ue_ue.VREditorInteractor.md#getname)

___

### GetOtherInteractor

▸ **GetOtherInteractor**(): [`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Returns

[`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetOtherInteractor](ue_ue.VREditorInteractor.md#getotherinteractor)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetOuter](ue_ue.VREditorInteractor.md#getouter)

___

### GetRoomSpaceTransform

▸ **GetRoomSpaceTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetRoomSpaceTransform](ue_ue.VREditorInteractor.md#getroomspacetransform)

___

### GetSelectAndMoveTriggerValue

▸ **GetSelectAndMoveTriggerValue**(): `number`

#### Returns

`number`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetSelectAndMoveTriggerValue](ue_ue.VREditorInteractor.md#getselectandmovetriggervalue)

___

### GetSlideDelta

▸ **GetSlideDelta**(): `number`

#### Returns

`number`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetSlideDelta](ue_ue.VREditorInteractor.md#getslidedelta)

___

### GetTeleportActor

▸ **GetTeleportActor**(): [`VREditorTeleporter`](ue_ue.VREditorTeleporter.md)

#### Returns

[`VREditorTeleporter`](ue_ue.VREditorTeleporter.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetTeleportActor](ue_ue.VREditorInteractor.md#getteleportactor)

___

### GetTrackpadPosition

▸ **GetTrackpadPosition**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetTrackpadPosition](ue_ue.VREditorInteractor.md#gettrackpadposition)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetTransform](ue_ue.VREditorInteractor.md#gettransform)

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

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetTransformAndForwardVector](ue_ue.VREditorInteractor.md#gettransformandforwardvector)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetWorld](ue_ue.VREditorInteractor.md#getworld)

___

### GetWorldInteraction

▸ **GetWorldInteraction**(): [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Returns

[`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetWorldInteraction](ue_ue.VREditorInteractor.md#getworldinteraction)

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

[VREditorInteractor](ue_ue.VREditorInteractor.md).[HandleInputAxis_BP](ue_ue.VREditorInteractor.md#handleinputaxis_bp)

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

[VREditorInteractor](ue_ue.VREditorInteractor.md).[HandleInputKey_BP](ue_ue.VREditorInteractor.md#handleinputkey_bp)

___

### Init

▸ **Init**(`InVRMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVRMode` | [`$Nullable`](../modules/puerts.md#$nullable)<[`VREditorMode`](ue_ue.VREditorMode.md)\> |

#### Returns

`void`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[Init](ue_ue.VREditorInteractor.md#init)

___

### IsClickingOnUI

▸ **IsClickingOnUI**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[IsClickingOnUI](ue_ue.VREditorInteractor.md#isclickingonui)

___

### IsHoveringOverGizmo

▸ **IsHoveringOverGizmo**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[IsHoveringOverGizmo](ue_ue.VREditorInteractor.md#ishoveringovergizmo)

___

### IsHoveringOverUI

▸ **IsHoveringOverUI**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[IsHoveringOverUI](ue_ue.VREditorInteractor.md#ishoveringoverui)

___

### IsTouchingTrackpad

▸ **IsTouchingTrackpad**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[IsTouchingTrackpad](ue_ue.VREditorInteractor.md#istouchingtrackpad)

___

### ReplaceHandMeshComponent

▸ **ReplaceHandMeshComponent**(`NewMesh`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMesh` | [`$Nullable`](../modules/puerts.md#$nullable)<[`StaticMesh`](ue_ue.StaticMesh.md)\> |

#### Returns

`void`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[ReplaceHandMeshComponent](ue_ue.VREditorInteractor.md#replacehandmeshcomponent)

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

[VREditorInteractor](ue_ue.VREditorInteractor.md).[SetCanCarry](ue_ue.VREditorInteractor.md#setcancarry)

___

### SetControllerHandSide

▸ **SetControllerHandSide**(`InControllerHandSide`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InControllerHandSide` | `string` |

#### Returns

`void`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[SetControllerHandSide](ue_ue.VREditorInteractor.md#setcontrollerhandside)

___

### SetControllerType

▸ **SetControllerType**(`InControllerType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InControllerType` | [`EControllerType`](../enums/ue_ue.EControllerType.md) |

#### Returns

`void`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[SetControllerType](ue_ue.VREditorInteractor.md#setcontrollertype)

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

[VREditorInteractor](ue_ue.VREditorInteractor.md).[SetDraggingMode](ue_ue.VREditorInteractor.md#setdraggingmode)

___

### SetForceLaserColor

▸ **SetForceLaserColor**(`InColor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[SetForceLaserColor](ue_ue.VREditorInteractor.md#setforcelasercolor)

___

### SetForceShowLaser

▸ **SetForceShowLaser**(`bInForceShow`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInForceShow` | `boolean` |

#### Returns

`void`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[SetForceShowLaser](ue_ue.VREditorInteractor.md#setforceshowlaser)

___

### SetGizmoMode

▸ **SetGizmoMode**(`InGizmoMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InGizmoMode` | [`EGizmoHandleTypes`](../enums/ue_ue.EGizmoHandleTypes.md) |

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

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[SetHitResultGizmoFilterMode](ue_ue.VREditorInteractor.md#sethitresultgizmofiltermode)

___

### SetupComponent

▸ **SetupComponent**(`OwningActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwningActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[SetupComponent](ue_ue.VREditorInteractor.md#setupcomponent)

___

### Shutdown

▸ **Shutdown**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[Shutdown](ue_ue.VREditorInteractor.md#shutdown)

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

[VREditorInteractor](ue_ue.VREditorInteractor.md).[Tick](ue_ue.VREditorInteractor.md#tick)

___

### TryOverrideControllerType

▸ **TryOverrideControllerType**(`InControllerType`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InControllerType` | [`EControllerType`](../enums/ue_ue.EControllerType.md) |

#### Returns

`boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[TryOverrideControllerType](ue_ue.VREditorInteractor.md#tryoverridecontrollertype)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VRScoutingInteractor`](ue_ue.VRScoutingInteractor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VRScoutingInteractor`](ue_ue.VRScoutingInteractor.md)

#### Overrides

[VREditorInteractor](ue_ue.VREditorInteractor.md).[Find](ue_ue.VREditorInteractor.md#find)

___

### GetSelectedActors

▸ `Static` **GetSelectedActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

___

### Load

▸ `Static` **Load**(`InName`): [`VRScoutingInteractor`](ue_ue.VRScoutingInteractor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VRScoutingInteractor`](ue_ue.VRScoutingInteractor.md)

#### Overrides

[VREditorInteractor](ue_ue.VREditorInteractor.md).[Load](ue_ue.VREditorInteractor.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[VREditorInteractor](ue_ue.VREditorInteractor.md).[StaticClass](ue_ue.VREditorInteractor.md#staticclass)
