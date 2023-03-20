[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / VREditorInteractor

# Class: VREditorInteractor

[ue/ue](../modules/ue_ue.md).VREditorInteractor

## Hierarchy

- [`ViewportInteractor`](ue_ue.ViewportInteractor.md)

  ↳ **`VREditorInteractor`**

  ↳↳ [`VRScoutingInteractor`](ue_ue.VRScoutingInteractor.md)

## Table of contents

### Constructors

- [constructor](ue_ue.VREditorInteractor.md#constructor)

### Properties

- [ControllerMotionSource](ue_ue.VREditorInteractor.md#controllermotionsource)
- [ControllerType](ue_ue.VREditorInteractor.md#controllertype)
- [HandMeshComponent](ue_ue.VREditorInteractor.md#handmeshcomponent)
- [HandMeshMID](ue_ue.VREditorInteractor.md#handmeshmid)
- [HoverMeshComponent](ue_ue.VREditorInteractor.md#hovermeshcomponent)
- [HoverPointLightComponent](ue_ue.VREditorInteractor.md#hoverpointlightcomponent)
- [KeyToActionMap](ue_ue.VREditorInteractor.md#keytoactionmap)
- [LaserPointerMID](ue_ue.VREditorInteractor.md#laserpointermid)
- [LaserSplineComponent](ue_ue.VREditorInteractor.md#lasersplinecomponent)
- [LaserSplineMeshComponents](ue_ue.VREditorInteractor.md#lasersplinemeshcomponents)
- [MotionControllerComponent](ue_ue.VREditorInteractor.md#motioncontrollercomponent)
- [OtherInteractor](ue_ue.VREditorInteractor.md#otherinteractor)
- [OverrideControllerType](ue_ue.VREditorInteractor.md#overridecontrollertype)
- [OwningAvatar](ue_ue.VREditorInteractor.md#owningavatar)
- [TranslucentLaserPointerMID](ue_ue.VREditorInteractor.md#translucentlaserpointermid)
- [VRMode](ue_ue.VREditorInteractor.md#vrmode)
- [WorldInteraction](ue_ue.VREditorInteractor.md#worldinteraction)
- [\_\_tid\_Object\_\_](ue_ue.VREditorInteractor.md#__tid_object__)
- [\_\_tid\_VREditorInteractor\_\_](ue_ue.VREditorInteractor.md#__tid_vreditorinteractor__)
- [\_\_tid\_ViewportInteractor\_\_](ue_ue.VREditorInteractor.md#__tid_viewportinteractor__)
- [bIsUndoRedoSwipeEnabled](ue_ue.VREditorInteractor.md#bisundoredoswipeenabled)

### Methods

- [CanCarry](ue_ue.VREditorInteractor.md#cancarry)
- [CreateDefaultSubobject](ue_ue.VREditorInteractor.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.VREditorInteractor.md#executeubergraph)
- [GetClass](ue_ue.VREditorInteractor.md#getclass)
- [GetControllerSide](ue_ue.VREditorInteractor.md#getcontrollerside)
- [GetControllerType](ue_ue.VREditorInteractor.md#getcontrollertype)
- [GetDraggingMode](ue_ue.VREditorInteractor.md#getdraggingmode)
- [GetHMDDeviceType](ue_ue.VREditorInteractor.md#gethmddevicetype)
- [GetHitResultGizmoFilterMode](ue_ue.VREditorInteractor.md#gethitresultgizmofiltermode)
- [GetHoverLocation](ue_ue.VREditorInteractor.md#gethoverlocation)
- [GetLaserEnd](ue_ue.VREditorInteractor.md#getlaserend)
- [GetLaserPointer](ue_ue.VREditorInteractor.md#getlaserpointer)
- [GetLaserStart](ue_ue.VREditorInteractor.md#getlaserstart)
- [GetLastRoomSpaceTransform](ue_ue.VREditorInteractor.md#getlastroomspacetransform)
- [GetLastTrackpadPosition](ue_ue.VREditorInteractor.md#getlasttrackpadposition)
- [GetLastTransform](ue_ue.VREditorInteractor.md#getlasttransform)
- [GetMotionControllerComponent](ue_ue.VREditorInteractor.md#getmotioncontrollercomponent)
- [GetName](ue_ue.VREditorInteractor.md#getname)
- [GetOtherInteractor](ue_ue.VREditorInteractor.md#getotherinteractor)
- [GetOuter](ue_ue.VREditorInteractor.md#getouter)
- [GetRoomSpaceTransform](ue_ue.VREditorInteractor.md#getroomspacetransform)
- [GetSelectAndMoveTriggerValue](ue_ue.VREditorInteractor.md#getselectandmovetriggervalue)
- [GetSlideDelta](ue_ue.VREditorInteractor.md#getslidedelta)
- [GetTeleportActor](ue_ue.VREditorInteractor.md#getteleportactor)
- [GetTrackpadPosition](ue_ue.VREditorInteractor.md#gettrackpadposition)
- [GetTransform](ue_ue.VREditorInteractor.md#gettransform)
- [GetTransformAndForwardVector](ue_ue.VREditorInteractor.md#gettransformandforwardvector)
- [GetWorld](ue_ue.VREditorInteractor.md#getworld)
- [GetWorldInteraction](ue_ue.VREditorInteractor.md#getworldinteraction)
- [HandleInputAxis\_BP](ue_ue.VREditorInteractor.md#handleinputaxis_bp)
- [HandleInputKey\_BP](ue_ue.VREditorInteractor.md#handleinputkey_bp)
- [Init](ue_ue.VREditorInteractor.md#init)
- [IsClickingOnUI](ue_ue.VREditorInteractor.md#isclickingonui)
- [IsHoveringOverGizmo](ue_ue.VREditorInteractor.md#ishoveringovergizmo)
- [IsHoveringOverUI](ue_ue.VREditorInteractor.md#ishoveringoverui)
- [IsTouchingTrackpad](ue_ue.VREditorInteractor.md#istouchingtrackpad)
- [ReplaceHandMeshComponent](ue_ue.VREditorInteractor.md#replacehandmeshcomponent)
- [SetCanCarry](ue_ue.VREditorInteractor.md#setcancarry)
- [SetControllerHandSide](ue_ue.VREditorInteractor.md#setcontrollerhandside)
- [SetControllerType](ue_ue.VREditorInteractor.md#setcontrollertype)
- [SetDraggingMode](ue_ue.VREditorInteractor.md#setdraggingmode)
- [SetForceLaserColor](ue_ue.VREditorInteractor.md#setforcelasercolor)
- [SetForceShowLaser](ue_ue.VREditorInteractor.md#setforceshowlaser)
- [SetHitResultGizmoFilterMode](ue_ue.VREditorInteractor.md#sethitresultgizmofiltermode)
- [SetupComponent](ue_ue.VREditorInteractor.md#setupcomponent)
- [Shutdown](ue_ue.VREditorInteractor.md#shutdown)
- [Tick](ue_ue.VREditorInteractor.md#tick)
- [TryOverrideControllerType](ue_ue.VREditorInteractor.md#tryoverridecontrollertype)
- [Find](ue_ue.VREditorInteractor.md#find)
- [Load](ue_ue.VREditorInteractor.md#load)
- [StaticClass](ue_ue.VREditorInteractor.md#staticclass)

## Constructors

### constructor

• **new VREditorInteractor**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ViewportInteractor](ue_ue.ViewportInteractor.md).[constructor](ue_ue.ViewportInteractor.md#constructor)

#### Defined in

[ue/ue.d.ts:65806](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65806)

## Properties

### ControllerMotionSource

• **ControllerMotionSource**: `string`

#### Defined in

[ue/ue.d.ts:65820](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65820)

___

### ControllerType

• **ControllerType**: [`EControllerType`](../enums/ue_ue.EControllerType.md)

#### Defined in

[ue/ue.d.ts:65818](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65818)

___

### HandMeshComponent

• **HandMeshComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

#### Defined in

[ue/ue.d.ts:65809](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65809)

___

### HandMeshMID

• **HandMeshMID**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:65816](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65816)

___

### HoverMeshComponent

• **HoverMeshComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

#### Defined in

[ue/ue.d.ts:65814](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65814)

___

### HoverPointLightComponent

• **HoverPointLightComponent**: [`PointLightComponent`](ue_ue.PointLightComponent.md)

#### Defined in

[ue/ue.d.ts:65815](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65815)

___

### KeyToActionMap

• **KeyToActionMap**: [`TMap`](../interfaces/ue_puerts.TMap.md)<[`Key`](ue_ue.Key.md), [`ViewportActionKeyInput`](ue_ue.ViewportActionKeyInput.md)\>

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[KeyToActionMap](ue_ue.ViewportInteractor.md#keytoactionmap)

#### Defined in

[ue/ue.d.ts:14350](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14350)

___

### LaserPointerMID

• **LaserPointerMID**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:65812](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65812)

___

### LaserSplineComponent

• **LaserSplineComponent**: [`SplineComponent`](ue_ue.SplineComponent.md)

#### Defined in

[ue/ue.d.ts:65810](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65810)

___

### LaserSplineMeshComponents

• **LaserSplineMeshComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SplineMeshComponent`](ue_ue.SplineMeshComponent.md)\>

#### Defined in

[ue/ue.d.ts:65811](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65811)

___

### MotionControllerComponent

• **MotionControllerComponent**: [`MotionControllerComponent`](ue_ue.MotionControllerComponent.md)

#### Defined in

[ue/ue.d.ts:65808](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65808)

___

### OtherInteractor

• **OtherInteractor**: [`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[OtherInteractor](ue_ue.ViewportInteractor.md#otherinteractor)

#### Defined in

[ue/ue.d.ts:14352](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14352)

___

### OverrideControllerType

• **OverrideControllerType**: [`EControllerType`](../enums/ue_ue.EControllerType.md)

#### Defined in

[ue/ue.d.ts:65819](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65819)

___

### OwningAvatar

• **OwningAvatar**: [`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:65817](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65817)

___

### TranslucentLaserPointerMID

• **TranslucentLaserPointerMID**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:65813](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65813)

___

### VRMode

• **VRMode**: [`VREditorMode`](ue_ue.VREditorMode.md)

#### Defined in

[ue/ue.d.ts:65821](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65821)

___

### WorldInteraction

• **WorldInteraction**: [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[WorldInteraction](ue_ue.ViewportInteractor.md#worldinteraction)

#### Defined in

[ue/ue.d.ts:14351](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14351)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[__tid_Object__](ue_ue.ViewportInteractor.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_VREditorInteractor\_\_

• **\_\_tid\_VREditorInteractor\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:65848](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65848)

___

### \_\_tid\_ViewportInteractor\_\_

• **\_\_tid\_ViewportInteractor\_\_**: `boolean`

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[__tid_ViewportInteractor__](ue_ue.ViewportInteractor.md#__tid_viewportinteractor__)

#### Defined in

[ue/ue.d.ts:14377](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14377)

___

### bIsUndoRedoSwipeEnabled

• **bIsUndoRedoSwipeEnabled**: `boolean`

#### Defined in

[ue/ue.d.ts:65807](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65807)

## Methods

### CanCarry

▸ **CanCarry**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[CanCarry](ue_ue.ViewportInteractor.md#cancarry)

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

[ViewportInteractor](ue_ue.ViewportInteractor.md).[CreateDefaultSubobject](ue_ue.ViewportInteractor.md#createdefaultsubobject)

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

[ViewportInteractor](ue_ue.ViewportInteractor.md).[ExecuteUbergraph](ue_ue.ViewportInteractor.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetClass](ue_ue.ViewportInteractor.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetControllerSide

▸ **GetControllerSide**(): [`EControllerHand`](../enums/ue_ue.EControllerHand.md)

#### Returns

[`EControllerHand`](../enums/ue_ue.EControllerHand.md)

#### Defined in

[ue/ue.d.ts:65822](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65822)

___

### GetControllerType

▸ **GetControllerType**(): [`EControllerType`](../enums/ue_ue.EControllerType.md)

#### Returns

[`EControllerType`](../enums/ue_ue.EControllerType.md)

#### Defined in

[ue/ue.d.ts:65823](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65823)

___

### GetDraggingMode

▸ **GetDraggingMode**(): [`EViewportInteractionDraggingMode`](../enums/ue_ue.EViewportInteractionDraggingMode.md)

#### Returns

[`EViewportInteractionDraggingMode`](../enums/ue_ue.EViewportInteractionDraggingMode.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetDraggingMode](ue_ue.ViewportInteractor.md#getdraggingmode)

#### Defined in

[ue/ue.d.ts:14354](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14354)

___

### GetHMDDeviceType

▸ **GetHMDDeviceType**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:65824](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65824)

___

### GetHitResultGizmoFilterMode

▸ **GetHitResultGizmoFilterMode**(): [`EHitResultGizmoFilterMode`](../enums/ue_ue.EHitResultGizmoFilterMode.md)

#### Returns

[`EHitResultGizmoFilterMode`](../enums/ue_ue.EHitResultGizmoFilterMode.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetHitResultGizmoFilterMode](ue_ue.ViewportInteractor.md#gethitresultgizmofiltermode)

#### Defined in

[ue/ue.d.ts:14355](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14355)

___

### GetHoverLocation

▸ **GetHoverLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetHoverLocation](ue_ue.ViewportInteractor.md#gethoverlocation)

#### Defined in

[ue/ue.d.ts:14356](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14356)

___

### GetLaserEnd

▸ **GetLaserEnd**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:65825](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65825)

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

#### Defined in

[ue/ue.d.ts:14357](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14357)

___

### GetLaserStart

▸ **GetLaserStart**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:65826](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65826)

___

### GetLastRoomSpaceTransform

▸ **GetLastRoomSpaceTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetLastRoomSpaceTransform](ue_ue.ViewportInteractor.md#getlastroomspacetransform)

#### Defined in

[ue/ue.d.ts:14358](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14358)

___

### GetLastTrackpadPosition

▸ **GetLastTrackpadPosition**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:65827](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65827)

___

### GetLastTransform

▸ **GetLastTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetLastTransform](ue_ue.ViewportInteractor.md#getlasttransform)

#### Defined in

[ue/ue.d.ts:14359](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14359)

___

### GetMotionControllerComponent

▸ **GetMotionControllerComponent**(): [`MotionControllerComponent`](ue_ue.MotionControllerComponent.md)

#### Returns

[`MotionControllerComponent`](ue_ue.MotionControllerComponent.md)

#### Defined in

[ue/ue.d.ts:65828](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65828)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetName](ue_ue.ViewportInteractor.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetOtherInteractor

▸ **GetOtherInteractor**(): [`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Returns

[`ViewportInteractor`](ue_ue.ViewportInteractor.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetOtherInteractor](ue_ue.ViewportInteractor.md#getotherinteractor)

#### Defined in

[ue/ue.d.ts:14360](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14360)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetOuter](ue_ue.ViewportInteractor.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetRoomSpaceTransform

▸ **GetRoomSpaceTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetRoomSpaceTransform](ue_ue.ViewportInteractor.md#getroomspacetransform)

#### Defined in

[ue/ue.d.ts:14361](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14361)

___

### GetSelectAndMoveTriggerValue

▸ **GetSelectAndMoveTriggerValue**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:65829](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65829)

___

### GetSlideDelta

▸ **GetSlideDelta**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:65830](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65830)

___

### GetTeleportActor

▸ **GetTeleportActor**(): [`VREditorTeleporter`](ue_ue.VREditorTeleporter.md)

#### Returns

[`VREditorTeleporter`](ue_ue.VREditorTeleporter.md)

#### Defined in

[ue/ue.d.ts:65831](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65831)

___

### GetTrackpadPosition

▸ **GetTrackpadPosition**(): [`Vector2D`](ue_ue_s.Vector2D.md)

#### Returns

[`Vector2D`](ue_ue_s.Vector2D.md)

#### Defined in

[ue/ue.d.ts:65832](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65832)

___

### GetTransform

▸ **GetTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetTransform](ue_ue.ViewportInteractor.md#gettransform)

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

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetTransformAndForwardVector](ue_ue.ViewportInteractor.md#gettransformandforwardvector)

#### Defined in

[ue/ue.d.ts:14363](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14363)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetWorld](ue_ue.ViewportInteractor.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### GetWorldInteraction

▸ **GetWorldInteraction**(): [`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Returns

[`ViewportWorldInteraction`](ue_ue.ViewportWorldInteraction.md)

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[GetWorldInteraction](ue_ue.ViewportInteractor.md#getworldinteraction)

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

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[HandleInputAxis_BP](ue_ue.ViewportInteractor.md#handleinputaxis_bp)

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

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[HandleInputKey_BP](ue_ue.ViewportInteractor.md#handleinputkey_bp)

#### Defined in

[ue/ue.d.ts:14366](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14366)

___

### Init

▸ **Init**(`InVRMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InVRMode` | [`$Nullable`](../modules/puerts.md#$nullable)<[`VREditorMode`](ue_ue.VREditorMode.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:65833](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65833)

___

### IsClickingOnUI

▸ **IsClickingOnUI**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:65834](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65834)

___

### IsHoveringOverGizmo

▸ **IsHoveringOverGizmo**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[IsHoveringOverGizmo](ue_ue.ViewportInteractor.md#ishoveringovergizmo)

#### Defined in

[ue/ue.d.ts:14367](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14367)

___

### IsHoveringOverUI

▸ **IsHoveringOverUI**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:65835](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65835)

___

### IsTouchingTrackpad

▸ **IsTouchingTrackpad**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:65836](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65836)

___

### ReplaceHandMeshComponent

▸ **ReplaceHandMeshComponent**(`NewMesh`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMesh` | [`$Nullable`](../modules/puerts.md#$nullable)<[`StaticMesh`](ue_ue.StaticMesh.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:65837](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65837)

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

#### Defined in

[ue/ue.d.ts:14368](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14368)

___

### SetControllerHandSide

▸ **SetControllerHandSide**(`InControllerHandSide`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InControllerHandSide` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:65838](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65838)

___

### SetControllerType

▸ **SetControllerType**(`InControllerType`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InControllerType` | [`EControllerType`](../enums/ue_ue.EControllerType.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:65839](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65839)

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

#### Defined in

[ue/ue.d.ts:14369](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14369)

___

### SetForceLaserColor

▸ **SetForceLaserColor**(`InColor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:65840](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65840)

___

### SetForceShowLaser

▸ **SetForceShowLaser**(`bInForceShow`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInForceShow` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:65841](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65841)

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

#### Defined in

[ue/ue.d.ts:14370](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14370)

___

### SetupComponent

▸ **SetupComponent**(`OwningActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OwningActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:65842](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65842)

___

### Shutdown

▸ **Shutdown**(): `void`

#### Returns

`void`

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[Shutdown](ue_ue.ViewportInteractor.md#shutdown)

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

#### Inherited from

[ViewportInteractor](ue_ue.ViewportInteractor.md).[Tick](ue_ue.ViewportInteractor.md#tick)

#### Defined in

[ue/ue.d.ts:14372](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14372)

___

### TryOverrideControllerType

▸ **TryOverrideControllerType**(`InControllerType`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InControllerType` | [`EControllerType`](../enums/ue_ue.EControllerType.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:65843](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65843)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`VREditorInteractor`](ue_ue.VREditorInteractor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`VREditorInteractor`](ue_ue.VREditorInteractor.md)

#### Overrides

[ViewportInteractor](ue_ue.ViewportInteractor.md).[Find](ue_ue.ViewportInteractor.md#find)

#### Defined in

[ue/ue.d.ts:65845](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65845)

___

### Load

▸ `Static` **Load**(`InName`): [`VREditorInteractor`](ue_ue.VREditorInteractor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`VREditorInteractor`](ue_ue.VREditorInteractor.md)

#### Overrides

[ViewportInteractor](ue_ue.ViewportInteractor.md).[Load](ue_ue.ViewportInteractor.md#load)

#### Defined in

[ue/ue.d.ts:65846](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65846)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ViewportInteractor](ue_ue.ViewportInteractor.md).[StaticClass](ue_ue.ViewportInteractor.md#staticclass)

#### Defined in

[ue/ue.d.ts:65844](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L65844)
