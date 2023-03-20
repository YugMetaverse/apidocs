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

#### Defined in

[ue/ue.d.ts:65995](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65995)

## Properties

### ControllerMotionSource

• **ControllerMotionSource**: `string`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[ControllerMotionSource](ue_ue.VREditorInteractor.md#controllermotionsource)

#### Defined in

[ue/ue.d.ts:65820](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65820)

___

### ControllerType

• **ControllerType**: [`EControllerType`](../enums/ue_ue.EControllerType.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[ControllerType](ue_ue.VREditorInteractor.md#controllertype)

#### Defined in

[ue/ue.d.ts:65818](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65818)

___

### FlyingIndicatorComponent

• **FlyingIndicatorComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

#### Defined in

[ue/ue.d.ts:65996](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65996)

___

### HandMeshComponent

• **HandMeshComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[HandMeshComponent](ue_ue.VREditorInteractor.md#handmeshcomponent)

#### Defined in

[ue/ue.d.ts:65809](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65809)

___

### HandMeshMID

• **HandMeshMID**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[HandMeshMID](ue_ue.VREditorInteractor.md#handmeshmid)

#### Defined in

[ue/ue.d.ts:65816](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65816)

___

### HoverMeshComponent

• **HoverMeshComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[HoverMeshComponent](ue_ue.VREditorInteractor.md#hovermeshcomponent)

#### Defined in

[ue/ue.d.ts:65814](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65814)

___

### HoverPointLightComponent

• **HoverPointLightComponent**: [`PointLightComponent`](ue_ue.PointLightComponent.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[HoverPointLightComponent](ue_ue.VREditorInteractor.md#hoverpointlightcomponent)

#### Defined in

[ue/ue.d.ts:65815](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65815)

___

### KeyToActionMap

• **KeyToActionMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Key`](ue_ue.Key.md), [`ViewportActionKeyInput`](ue_ue.ViewportActionKeyInput.md)\>

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[KeyToActionMap](ue_ue.VREditorInteractor.md#keytoactionmap)

#### Defined in

[ue/ue.d.ts:14350](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14350)

___

### LaserPointerMID

• **LaserPointerMID**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[LaserPointerMID](ue_ue.VREditorInteractor.md#laserpointermid)

#### Defined in

[ue/ue.d.ts:65812](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65812)

___

### LaserSplineComponent

• **LaserSplineComponent**: [`SplineComponent`](ue_ue.SplineComponent.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[LaserSplineComponent](ue_ue.VREditorInteractor.md#lasersplinecomponent)

#### Defined in

[ue/ue.d.ts:65810](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65810)

___

### LaserSplineMeshComponents

• **LaserSplineMeshComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SplineMeshComponent`](ue_ue.SplineMeshComponent.md)\>

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[LaserSplineMeshComponents](ue_ue.VREditorInteractor.md#lasersplinemeshcomponents)

#### Defined in

[ue/ue.d.ts:65811](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65811)

___

### MotionControllerComponent

• **MotionControllerComponent**: [`MotionControllerComponent`](ue_ue.MotionControllerComponent.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[MotionControllerComponent](ue_ue.VREditorInteractor.md#motioncontrollercomponent)

#### Defined in

[ue/ue.d.ts:65808](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65808)

___

### OtherInteractor

• **OtherInteractor**: [`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[OtherInteractor](ue_ue.VREditorInteractor.md#otherinteractor)

#### Defined in

[ue/ue.d.ts:14352](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14352)

___

### OverrideControllerType

• **OverrideControllerType**: [`EControllerType`](../enums/ue_ue.EControllerType.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[OverrideControllerType](ue_ue.VREditorInteractor.md#overridecontrollertype)

#### Defined in

[ue/ue.d.ts:65819](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65819)

___

### OwningAvatar

• **OwningAvatar**: [`Actor`](ue_ue.Actor.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[OwningAvatar](ue_ue.VREditorInteractor.md#owningavatar)

#### Defined in

[ue/ue.d.ts:65817](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65817)

___

### TranslucentLaserPointerMID

• **TranslucentLaserPointerMID**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[TranslucentLaserPointerMID](ue_ue.VREditorInteractor.md#translucentlaserpointermid)

#### Defined in

[ue/ue.d.ts:65813](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65813)

___

### VRMode

• **VRMode**: [`VREditorMode`](ue_ue.VREditorMode.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[VRMode](ue_ue.VREditorInteractor.md#vrmode)

#### Defined in

[ue/ue.d.ts:65821](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65821)

___

### WorldInteraction

• **WorldInteraction**: [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[WorldInteraction](ue_ue.VREditorInteractor.md#worldinteraction)

#### Defined in

[ue/ue.d.ts:14351](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14351)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[__tid_Object__](ue_ue.VREditorInteractor.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_VREditorInteractor\_\_

• **\_\_tid\_VREditorInteractor\_\_**: `boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[__tid_VREditorInteractor__](ue_ue.VREditorInteractor.md#__tid_vreditorinteractor__)

#### Defined in

[ue/ue.d.ts:65848](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65848)

___

### \_\_tid\_VRScoutingInteractor\_\_

• **\_\_tid\_VRScoutingInteractor\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:66004](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66004)

___

### \_\_tid\_ViewportInteractor\_\_

• **\_\_tid\_ViewportInteractor\_\_**: `boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[__tid_ViewportInteractor__](ue_ue.VREditorInteractor.md#__tid_viewportinteractor__)

#### Defined in

[ue/ue.d.ts:14377](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14377)

___

### bIsUndoRedoSwipeEnabled

• **bIsUndoRedoSwipeEnabled**: `boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[bIsUndoRedoSwipeEnabled](ue_ue.VREditorInteractor.md#bisundoredoswipeenabled)

#### Defined in

[ue/ue.d.ts:65807](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65807)

## Methods

### CanCarry

▸ **CanCarry**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[CanCarry](ue_ue.VREditorInteractor.md#cancarry)

#### Defined in

[ue/ue.d.ts:14353](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14353)

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

[VREditorInteractor](ue_ue.VREditorInteractor.md).[ExecuteUbergraph](ue_ue.VREditorInteractor.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetClass](ue_ue.VREditorInteractor.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetControllerSide

▸ **GetControllerSide**(): [`EControllerHand`](../enums/ue_ue.EControllerHand.md)

#### Returns

[`EControllerHand`](../enums/ue_ue.EControllerHand.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetControllerSide](ue_ue.VREditorInteractor.md#getcontrollerside)

#### Defined in

[ue/ue.d.ts:65822](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65822)

___

### GetControllerType

▸ **GetControllerType**(): [`EControllerType`](../enums/ue_ue.EControllerType.md)

#### Returns

[`EControllerType`](../enums/ue_ue.EControllerType.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetControllerType](ue_ue.VREditorInteractor.md#getcontrollertype)

#### Defined in

[ue/ue.d.ts:65823](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65823)

___

### GetDraggingMode

▸ **GetDraggingMode**(): [`EViewportInteractionDraggingMode`](../enums/ue_ue.EViewportInteractionDraggingMode.md)

#### Returns

[`EViewportInteractionDraggingMode`](../enums/ue_ue.EViewportInteractionDraggingMode.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetDraggingMode](ue_ue.VREditorInteractor.md#getdraggingmode)

#### Defined in

[ue/ue.d.ts:14354](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14354)

___

### GetGizmoMode

▸ **GetGizmoMode**(): [`EGizmoHandleTypes`](../enums/ue_ue.EGizmoHandleTypes.md)

#### Returns

[`EGizmoHandleTypes`](../enums/ue_ue.EGizmoHandleTypes.md)

#### Defined in

[ue/ue.d.ts:65997](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65997)

___

### GetHMDDeviceType

▸ **GetHMDDeviceType**(): `string`

#### Returns

`string`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetHMDDeviceType](ue_ue.VREditorInteractor.md#gethmddevicetype)

#### Defined in

[ue/ue.d.ts:65824](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65824)

___

### GetHitResultGizmoFilterMode

▸ **GetHitResultGizmoFilterMode**(): [`EHitResultGizmoFilterMode`](../enums/ue_ue.EHitResultGizmoFilterMode.md)

#### Returns

[`EHitResultGizmoFilterMode`](../enums/ue_ue.EHitResultGizmoFilterMode.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetHitResultGizmoFilterMode](ue_ue.VREditorInteractor.md#gethitresultgizmofiltermode)

#### Defined in

[ue/ue.d.ts:14355](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14355)

___

### GetHoverLocation

▸ **GetHoverLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetHoverLocation](ue_ue.VREditorInteractor.md#gethoverlocation)

#### Defined in

[ue/ue.d.ts:14356](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14356)

___

### GetLaserEnd

▸ **GetLaserEnd**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetLaserEnd](ue_ue.VREditorInteractor.md#getlaserend)

#### Defined in

[ue/ue.d.ts:65825](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65825)

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

#### Defined in

[ue/ue.d.ts:14357](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14357)

___

### GetLaserStart

▸ **GetLaserStart**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetLaserStart](ue_ue.VREditorInteractor.md#getlaserstart)

#### Defined in

[ue/ue.d.ts:65826](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65826)

___

### GetLastRoomSpaceTransform

▸ **GetLastRoomSpaceTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetLastRoomSpaceTransform](ue_ue.VREditorInteractor.md#getlastroomspacetransform)

#### Defined in

[ue/ue.d.ts:14358](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14358)

___

### GetLastTrackpadPosition

▸ **GetLastTrackpadPosition**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetLastTrackpadPosition](ue_ue.VREditorInteractor.md#getlasttrackpadposition)

#### Defined in

[ue/ue.d.ts:65827](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65827)

___

### GetLastTransform

▸ **GetLastTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetLastTransform](ue_ue.VREditorInteractor.md#getlasttransform)

#### Defined in

[ue/ue.d.ts:14359](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14359)

___

### GetMotionControllerComponent

▸ **GetMotionControllerComponent**(): [`MotionControllerComponent`](ue_ue.MotionControllerComponent.md)

#### Returns

[`MotionControllerComponent`](ue_ue.MotionControllerComponent.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetMotionControllerComponent](ue_ue.VREditorInteractor.md#getmotioncontrollercomponent)

#### Defined in

[ue/ue.d.ts:65828](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65828)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetName](ue_ue.VREditorInteractor.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOtherInteractor

▸ **GetOtherInteractor**(): [`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Returns

[`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetOtherInteractor](ue_ue.VREditorInteractor.md#getotherinteractor)

#### Defined in

[ue/ue.d.ts:14360](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14360)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetOuter](ue_ue.VREditorInteractor.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetRoomSpaceTransform

▸ **GetRoomSpaceTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetRoomSpaceTransform](ue_ue.VREditorInteractor.md#getroomspacetransform)

#### Defined in

[ue/ue.d.ts:14361](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14361)

___

### GetSelectAndMoveTriggerValue

▸ **GetSelectAndMoveTriggerValue**(): `number`

#### Returns

`number`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetSelectAndMoveTriggerValue](ue_ue.VREditorInteractor.md#getselectandmovetriggervalue)

#### Defined in

[ue/ue.d.ts:65829](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65829)

___

### GetSlideDelta

▸ **GetSlideDelta**(): `number`

#### Returns

`number`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetSlideDelta](ue_ue.VREditorInteractor.md#getslidedelta)

#### Defined in

[ue/ue.d.ts:65830](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65830)

___

### GetTeleportActor

▸ **GetTeleportActor**(): [`VREditorTeleporter`](ue_ue.VREditorTeleporter.md)

#### Returns

[`VREditorTeleporter`](ue_ue.VREditorTeleporter.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetTeleportActor](ue_ue.VREditorInteractor.md#getteleportactor)

#### Defined in

[ue/ue.d.ts:65831](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65831)

___

### GetTrackpadPosition

▸ **GetTrackpadPosition**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetTrackpadPosition](ue_ue.VREditorInteractor.md#gettrackpadposition)

#### Defined in

[ue/ue.d.ts:65832](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65832)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetTransform](ue_ue.VREditorInteractor.md#gettransform)

#### Defined in

[ue/ue.d.ts:14362](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14362)

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

#### Defined in

[ue/ue.d.ts:14363](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14363)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetWorld](ue_ue.VREditorInteractor.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### GetWorldInteraction

▸ **GetWorldInteraction**(): [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Returns

[`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[GetWorldInteraction](ue_ue.VREditorInteractor.md#getworldinteraction)

#### Defined in

[ue/ue.d.ts:14364](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14364)

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

#### Defined in

[ue/ue.d.ts:14365](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14365)

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

#### Defined in

[ue/ue.d.ts:14366](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14366)

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

#### Defined in

[ue/ue.d.ts:65833](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65833)

___

### IsClickingOnUI

▸ **IsClickingOnUI**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[IsClickingOnUI](ue_ue.VREditorInteractor.md#isclickingonui)

#### Defined in

[ue/ue.d.ts:65834](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65834)

___

### IsHoveringOverGizmo

▸ **IsHoveringOverGizmo**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[IsHoveringOverGizmo](ue_ue.VREditorInteractor.md#ishoveringovergizmo)

#### Defined in

[ue/ue.d.ts:14367](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14367)

___

### IsHoveringOverUI

▸ **IsHoveringOverUI**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[IsHoveringOverUI](ue_ue.VREditorInteractor.md#ishoveringoverui)

#### Defined in

[ue/ue.d.ts:65835](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65835)

___

### IsTouchingTrackpad

▸ **IsTouchingTrackpad**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[IsTouchingTrackpad](ue_ue.VREditorInteractor.md#istouchingtrackpad)

#### Defined in

[ue/ue.d.ts:65836](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65836)

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

#### Defined in

[ue/ue.d.ts:65837](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65837)

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

#### Defined in

[ue/ue.d.ts:14368](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14368)

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

#### Defined in

[ue/ue.d.ts:65838](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65838)

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

#### Defined in

[ue/ue.d.ts:65839](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65839)

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

#### Defined in

[ue/ue.d.ts:14369](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14369)

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

#### Defined in

[ue/ue.d.ts:65840](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65840)

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

#### Defined in

[ue/ue.d.ts:65841](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65841)

___

### SetGizmoMode

▸ **SetGizmoMode**(`InGizmoMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InGizmoMode` | [`EGizmoHandleTypes`](../enums/ue_ue.EGizmoHandleTypes.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:65998](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65998)

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

#### Defined in

[ue/ue.d.ts:14370](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14370)

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

#### Defined in

[ue/ue.d.ts:65842](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65842)

___

### Shutdown

▸ **Shutdown**(): `void`

#### Returns

`void`

#### Inherited from

[VREditorInteractor](ue_ue.VREditorInteractor.md).[Shutdown](ue_ue.VREditorInteractor.md#shutdown)

#### Defined in

[ue/ue.d.ts:14371](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14371)

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

#### Defined in

[ue/ue.d.ts:14372](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14372)

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

#### Defined in

[ue/ue.d.ts:65843](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65843)

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

#### Defined in

[ue/ue.d.ts:66001](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66001)

___

### GetSelectedActors

▸ `Static` **GetSelectedActors**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Defined in

[ue/ue.d.ts:65999](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L65999)

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

#### Defined in

[ue/ue.d.ts:66002](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66002)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[VREditorInteractor](ue_ue.VREditorInteractor.md).[StaticClass](ue_ue.VREditorInteractor.md#staticclass)

#### Defined in

[ue/ue.d.ts:66000](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L66000)
