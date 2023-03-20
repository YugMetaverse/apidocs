[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PivotTranslationGizmoHandleGroup

# Class: PivotTranslationGizmoHandleGroup

[ue/ue](../modules/ue_ue.md).PivotTranslationGizmoHandleGroup

## Hierarchy

- [`AxisGizmoHandleGroup`](ue_ue.AxisGizmoHandleGroup.md)

  ↳ **`PivotTranslationGizmoHandleGroup`**

## Table of contents

### Constructors

- [constructor](ue_ue.PivotTranslationGizmoHandleGroup.md#constructor)

### Properties

- [AssetUserData](ue_ue.PivotTranslationGizmoHandleGroup.md#assetuserdata)
- [AttachChildren](ue_ue.PivotTranslationGizmoHandleGroup.md#attachchildren)
- [AttachParent](ue_ue.PivotTranslationGizmoHandleGroup.md#attachparent)
- [AttachSocketName](ue_ue.PivotTranslationGizmoHandleGroup.md#attachsocketname)
- [ClientAttachedChildren](ue_ue.PivotTranslationGizmoHandleGroup.md#clientattachedchildren)
- [ComponentTags](ue_ue.PivotTranslationGizmoHandleGroup.md#componenttags)
- [ComponentVelocity](ue_ue.PivotTranslationGizmoHandleGroup.md#componentvelocity)
- [CreationMethod](ue_ue.PivotTranslationGizmoHandleGroup.md#creationmethod)
- [DetailMode](ue_ue.PivotTranslationGizmoHandleGroup.md#detailmode)
- [DragOperationComponent](ue_ue.PivotTranslationGizmoHandleGroup.md#dragoperationcomponent)
- [GizmoMaterial](ue_ue.PivotTranslationGizmoHandleGroup.md#gizmomaterial)
- [Handles](ue_ue.PivotTranslationGizmoHandleGroup.md#handles)
- [Mobility](ue_ue.PivotTranslationGizmoHandleGroup.md#mobility)
- [OnComponentActivated](ue_ue.PivotTranslationGizmoHandleGroup.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.PivotTranslationGizmoHandleGroup.md#oncomponentdeactivated)
- [OwningTransformGizmoActor](ue_ue.PivotTranslationGizmoHandleGroup.md#owningtransformgizmoactor)
- [PhysicsVolume](ue_ue.PivotTranslationGizmoHandleGroup.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.PivotTranslationGizmoHandleGroup.md#physicsvolumechangeddelegate)
- [PrimaryComponentTick](ue_ue.PivotTranslationGizmoHandleGroup.md#primarycomponenttick)
- [RelativeLocation](ue_ue.PivotTranslationGizmoHandleGroup.md#relativelocation)
- [RelativeRotation](ue_ue.PivotTranslationGizmoHandleGroup.md#relativerotation)
- [RelativeScale3D](ue_ue.PivotTranslationGizmoHandleGroup.md#relativescale3d)
- [TranslucentGizmoMaterial](ue_ue.PivotTranslationGizmoHandleGroup.md#translucentgizmomaterial)
- [UCSModifiedProperties](ue_ue.PivotTranslationGizmoHandleGroup.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.PivotTranslationGizmoHandleGroup.md#__tid_actorcomponent__)
- [\_\_tid\_AxisGizmoHandleGroup\_\_](ue_ue.PivotTranslationGizmoHandleGroup.md#__tid_axisgizmohandlegroup__)
- [\_\_tid\_GizmoHandleGroup\_\_](ue_ue.PivotTranslationGizmoHandleGroup.md#__tid_gizmohandlegroup__)
- [\_\_tid\_Object\_\_](ue_ue.PivotTranslationGizmoHandleGroup.md#__tid_object__)
- [\_\_tid\_PivotTranslationGizmoHandleGroup\_\_](ue_ue.PivotTranslationGizmoHandleGroup.md#__tid_pivottranslationgizmohandlegroup__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.PivotTranslationGizmoHandleGroup.md#__tid_scenecomponent__)
- [bAbsoluteLocation](ue_ue.PivotTranslationGizmoHandleGroup.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.PivotTranslationGizmoHandleGroup.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.PivotTranslationGizmoHandleGroup.md#babsolutescale)
- [bAutoActivate](ue_ue.PivotTranslationGizmoHandleGroup.md#bautoactivate)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.PivotTranslationGizmoHandleGroup.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.PivotTranslationGizmoHandleGroup.md#bcaneveraffectnavigation)
- [bComponentToWorldUpdated](ue_ue.PivotTranslationGizmoHandleGroup.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.PivotTranslationGizmoHandleGroup.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.PivotTranslationGizmoHandleGroup.md#beditablewheninherited)
- [bHiddenInGame](ue_ue.PivotTranslationGizmoHandleGroup.md#bhiddeningame)
- [bInstanceComponent](ue_ue.PivotTranslationGizmoHandleGroup.md#binstancecomponent)
- [bIsActive](ue_ue.PivotTranslationGizmoHandleGroup.md#bisactive)
- [bIsEditorOnly](ue_ue.PivotTranslationGizmoHandleGroup.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.PivotTranslationGizmoHandleGroup.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.PivotTranslationGizmoHandleGroup.md#bnetaddressable)
- [bReplicates](ue_ue.PivotTranslationGizmoHandleGroup.md#breplicates)
- [bShouldBeAttached](ue_ue.PivotTranslationGizmoHandleGroup.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.PivotTranslationGizmoHandleGroup.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.PivotTranslationGizmoHandleGroup.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.PivotTranslationGizmoHandleGroup.md#bshouldupdatephysicsvolume)
- [bUseAttachParentBound](ue_ue.PivotTranslationGizmoHandleGroup.md#buseattachparentbound)
- [bVisible](ue_ue.PivotTranslationGizmoHandleGroup.md#bvisible)
- [bVisualizeComponent](ue_ue.PivotTranslationGizmoHandleGroup.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.PivotTranslationGizmoHandleGroup.md#activate)
- [AddTickPrerequisiteActor](ue_ue.PivotTranslationGizmoHandleGroup.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PivotTranslationGizmoHandleGroup.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.PivotTranslationGizmoHandleGroup.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.PivotTranslationGizmoHandleGroup.md#createdefaultsubobject)
- [Deactivate](ue_ue.PivotTranslationGizmoHandleGroup.md#deactivate)
- [DetachFromParent](ue_ue.PivotTranslationGizmoHandleGroup.md#detachfromparent)
- [DoesSocketExist](ue_ue.PivotTranslationGizmoHandleGroup.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.PivotTranslationGizmoHandleGroup.md#executeubergraph)
- [GetAllSocketNames](ue_ue.PivotTranslationGizmoHandleGroup.md#getallsocketnames)
- [GetAttachParent](ue_ue.PivotTranslationGizmoHandleGroup.md#getattachparent)
- [GetAttachSocketName](ue_ue.PivotTranslationGizmoHandleGroup.md#getattachsocketname)
- [GetChildComponent](ue_ue.PivotTranslationGizmoHandleGroup.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.PivotTranslationGizmoHandleGroup.md#getchildrencomponents)
- [GetClass](ue_ue.PivotTranslationGizmoHandleGroup.md#getclass)
- [GetComponentTickInterval](ue_ue.PivotTranslationGizmoHandleGroup.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.PivotTranslationGizmoHandleGroup.md#getcomponentvelocity)
- [GetForwardVector](ue_ue.PivotTranslationGizmoHandleGroup.md#getforwardvector)
- [GetName](ue_ue.PivotTranslationGizmoHandleGroup.md#getname)
- [GetNumChildrenComponents](ue_ue.PivotTranslationGizmoHandleGroup.md#getnumchildrencomponents)
- [GetOuter](ue_ue.PivotTranslationGizmoHandleGroup.md#getouter)
- [GetOwner](ue_ue.PivotTranslationGizmoHandleGroup.md#getowner)
- [GetParentComponents](ue_ue.PivotTranslationGizmoHandleGroup.md#getparentcomponents)
- [GetPhysicsVolume](ue_ue.PivotTranslationGizmoHandleGroup.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.PivotTranslationGizmoHandleGroup.md#getrelativetransform)
- [GetRightVector](ue_ue.PivotTranslationGizmoHandleGroup.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.PivotTranslationGizmoHandleGroup.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.PivotTranslationGizmoHandleGroup.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.PivotTranslationGizmoHandleGroup.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.PivotTranslationGizmoHandleGroup.md#getsocketrotation)
- [GetSocketTransform](ue_ue.PivotTranslationGizmoHandleGroup.md#getsockettransform)
- [GetUpVector](ue_ue.PivotTranslationGizmoHandleGroup.md#getupvector)
- [GetWorld](ue_ue.PivotTranslationGizmoHandleGroup.md#getworld)
- [IsActive](ue_ue.PivotTranslationGizmoHandleGroup.md#isactive)
- [IsAnySimulatingPhysics](ue_ue.PivotTranslationGizmoHandleGroup.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.PivotTranslationGizmoHandleGroup.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.PivotTranslationGizmoHandleGroup.md#iscomponenttickenabled)
- [IsSimulatingPhysics](ue_ue.PivotTranslationGizmoHandleGroup.md#issimulatingphysics)
- [IsVisible](ue_ue.PivotTranslationGizmoHandleGroup.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_attachtocomponent)
- [K2\_DestroyComponent](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_getcomponenttoworld)
- [K2\_SetRelativeLocation](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.PivotTranslationGizmoHandleGroup.md#k2_setworldtransform)
- [OnRep\_AttachChildren](ue_ue.PivotTranslationGizmoHandleGroup.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.PivotTranslationGizmoHandleGroup.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.PivotTranslationGizmoHandleGroup.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.PivotTranslationGizmoHandleGroup.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.PivotTranslationGizmoHandleGroup.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.PivotTranslationGizmoHandleGroup.md#onrep_visibility)
- [ReceiveBeginPlay](ue_ue.PivotTranslationGizmoHandleGroup.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.PivotTranslationGizmoHandleGroup.md#receiveendplay)
- [ReceiveTick](ue_ue.PivotTranslationGizmoHandleGroup.md#receivetick)
- [RegisterComponent](ue_ue.PivotTranslationGizmoHandleGroup.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.PivotTranslationGizmoHandleGroup.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PivotTranslationGizmoHandleGroup.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.PivotTranslationGizmoHandleGroup.md#resetrelativetransform)
- [SetAbsolute](ue_ue.PivotTranslationGizmoHandleGroup.md#setabsolute)
- [SetActive](ue_ue.PivotTranslationGizmoHandleGroup.md#setactive)
- [SetAutoActivate](ue_ue.PivotTranslationGizmoHandleGroup.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.PivotTranslationGizmoHandleGroup.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.PivotTranslationGizmoHandleGroup.md#setcomponenttickinterval)
- [SetHiddenInGame](ue_ue.PivotTranslationGizmoHandleGroup.md#sethiddeningame)
- [SetIsReplicated](ue_ue.PivotTranslationGizmoHandleGroup.md#setisreplicated)
- [SetMobility](ue_ue.PivotTranslationGizmoHandleGroup.md#setmobility)
- [SetRelativeScale3D](ue_ue.PivotTranslationGizmoHandleGroup.md#setrelativescale3d)
- [SetShouldUpdatePhysicsVolume](ue_ue.PivotTranslationGizmoHandleGroup.md#setshouldupdatephysicsvolume)
- [SetTickGroup](ue_ue.PivotTranslationGizmoHandleGroup.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PivotTranslationGizmoHandleGroup.md#settickablewhenpaused)
- [SetVisibility](ue_ue.PivotTranslationGizmoHandleGroup.md#setvisibility)
- [SetWorldScale3D](ue_ue.PivotTranslationGizmoHandleGroup.md#setworldscale3d)
- [SetupAttachment](ue_ue.PivotTranslationGizmoHandleGroup.md#setupattachment)
- [SnapTo](ue_ue.PivotTranslationGizmoHandleGroup.md#snapto)
- [ToggleActive](ue_ue.PivotTranslationGizmoHandleGroup.md#toggleactive)
- [ToggleVisibility](ue_ue.PivotTranslationGizmoHandleGroup.md#togglevisibility)
- [Find](ue_ue.PivotTranslationGizmoHandleGroup.md#find)
- [Load](ue_ue.PivotTranslationGizmoHandleGroup.md#load)
- [StaticClass](ue_ue.PivotTranslationGizmoHandleGroup.md#staticclass)

## Constructors

### constructor

• **new PivotTranslationGizmoHandleGroup**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[constructor](ue_ue.AxisGizmoHandleGroup.md#constructor)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[AssetUserData](ue_ue.AxisGizmoHandleGroup.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[AttachChildren](ue_ue.AxisGizmoHandleGroup.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[AttachParent](ue_ue.AxisGizmoHandleGroup.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[AttachSocketName](ue_ue.AxisGizmoHandleGroup.md#attachsocketname)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[ClientAttachedChildren](ue_ue.AxisGizmoHandleGroup.md#clientattachedchildren)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[ComponentTags](ue_ue.AxisGizmoHandleGroup.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[ComponentVelocity](ue_ue.AxisGizmoHandleGroup.md#componentvelocity)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[CreationMethod](ue_ue.AxisGizmoHandleGroup.md#creationmethod)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[DetailMode](ue_ue.AxisGizmoHandleGroup.md#detailmode)

___

### DragOperationComponent

• **DragOperationComponent**: [`ViewportDragOperationComponent`](ue_ue.ViewportDragOperationComponent.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[DragOperationComponent](ue_ue.AxisGizmoHandleGroup.md#dragoperationcomponent)

___

### GizmoMaterial

• **GizmoMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GizmoMaterial](ue_ue.AxisGizmoHandleGroup.md#gizmomaterial)

___

### Handles

• **Handles**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`GizmoHandle`](ue_ue.GizmoHandle.md)\>

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[Handles](ue_ue.AxisGizmoHandleGroup.md#handles)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[Mobility](ue_ue.AxisGizmoHandleGroup.md#mobility)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[OnComponentActivated](ue_ue.AxisGizmoHandleGroup.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[OnComponentDeactivated](ue_ue.AxisGizmoHandleGroup.md#oncomponentdeactivated)

___

### OwningTransformGizmoActor

• **OwningTransformGizmoActor**: [`BaseTransformGizmo`](ue_ue.BaseTransformGizmo.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[OwningTransformGizmoActor](ue_ue.AxisGizmoHandleGroup.md#owningtransformgizmoactor)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[PhysicsVolume](ue_ue.AxisGizmoHandleGroup.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[PhysicsVolumeChangedDelegate](ue_ue.AxisGizmoHandleGroup.md#physicsvolumechangeddelegate)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[PrimaryComponentTick](ue_ue.AxisGizmoHandleGroup.md#primarycomponenttick)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[RelativeLocation](ue_ue.AxisGizmoHandleGroup.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[RelativeRotation](ue_ue.AxisGizmoHandleGroup.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[RelativeScale3D](ue_ue.AxisGizmoHandleGroup.md#relativescale3d)

___

### TranslucentGizmoMaterial

• **TranslucentGizmoMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[TranslucentGizmoMaterial](ue_ue.AxisGizmoHandleGroup.md#translucentgizmomaterial)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[UCSModifiedProperties](ue_ue.AxisGizmoHandleGroup.md#ucsmodifiedproperties)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[__tid_ActorComponent__](ue_ue.AxisGizmoHandleGroup.md#__tid_actorcomponent__)

___

### \_\_tid\_AxisGizmoHandleGroup\_\_

• **\_\_tid\_AxisGizmoHandleGroup\_\_**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[__tid_AxisGizmoHandleGroup__](ue_ue.AxisGizmoHandleGroup.md#__tid_axisgizmohandlegroup__)

___

### \_\_tid\_GizmoHandleGroup\_\_

• **\_\_tid\_GizmoHandleGroup\_\_**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[__tid_GizmoHandleGroup__](ue_ue.AxisGizmoHandleGroup.md#__tid_gizmohandlegroup__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[__tid_Object__](ue_ue.AxisGizmoHandleGroup.md#__tid_object__)

___

### \_\_tid\_PivotTranslationGizmoHandleGroup\_\_

• **\_\_tid\_PivotTranslationGizmoHandleGroup\_\_**: `boolean`

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[__tid_SceneComponent__](ue_ue.AxisGizmoHandleGroup.md#__tid_scenecomponent__)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bAbsoluteLocation](ue_ue.AxisGizmoHandleGroup.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bAbsoluteRotation](ue_ue.AxisGizmoHandleGroup.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bAbsoluteScale](ue_ue.AxisGizmoHandleGroup.md#babsolutescale)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bAutoActivate](ue_ue.AxisGizmoHandleGroup.md#bautoactivate)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.AxisGizmoHandleGroup.md#bboundschangetriggersstreamingdatarebuild)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bCanEverAffectNavigation](ue_ue.AxisGizmoHandleGroup.md#bcaneveraffectnavigation)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bComponentToWorldUpdated](ue_ue.AxisGizmoHandleGroup.md#bcomponenttoworldupdated)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bCreatedByConstructionScript](ue_ue.AxisGizmoHandleGroup.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bEditableWhenInherited](ue_ue.AxisGizmoHandleGroup.md#beditablewheninherited)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bHiddenInGame](ue_ue.AxisGizmoHandleGroup.md#bhiddeningame)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bInstanceComponent](ue_ue.AxisGizmoHandleGroup.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bIsActive](ue_ue.AxisGizmoHandleGroup.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bIsEditorOnly](ue_ue.AxisGizmoHandleGroup.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bIsVisualizationComponent](ue_ue.AxisGizmoHandleGroup.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bNetAddressable](ue_ue.AxisGizmoHandleGroup.md#bnetaddressable)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bReplicates](ue_ue.AxisGizmoHandleGroup.md#breplicates)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bShouldBeAttached](ue_ue.AxisGizmoHandleGroup.md#bshouldbeattached)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bShouldSnapLocationWhenAttached](ue_ue.AxisGizmoHandleGroup.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bShouldSnapRotationWhenAttached](ue_ue.AxisGizmoHandleGroup.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bShouldUpdatePhysicsVolume](ue_ue.AxisGizmoHandleGroup.md#bshouldupdatephysicsvolume)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bUseAttachParentBound](ue_ue.AxisGizmoHandleGroup.md#buseattachparentbound)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bVisible](ue_ue.AxisGizmoHandleGroup.md#bvisible)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[bVisualizeComponent](ue_ue.AxisGizmoHandleGroup.md#bvisualizecomponent)

## Methods

### Activate

▸ **Activate**(`bReset?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bReset?` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[Activate](ue_ue.AxisGizmoHandleGroup.md#activate)

___

### AddTickPrerequisiteActor

▸ **AddTickPrerequisiteActor**(`PrerequisiteActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[AddTickPrerequisiteActor](ue_ue.AxisGizmoHandleGroup.md#addtickprerequisiteactor)

___

### AddTickPrerequisiteComponent

▸ **AddTickPrerequisiteComponent**(`PrerequisiteComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\> |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[AddTickPrerequisiteComponent](ue_ue.AxisGizmoHandleGroup.md#addtickprerequisitecomponent)

___

### ComponentHasTag

▸ **ComponentHasTag**(`Tag`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Tag` | `string` |

#### Returns

`boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[ComponentHasTag](ue_ue.AxisGizmoHandleGroup.md#componenthastag)

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

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[CreateDefaultSubobject](ue_ue.AxisGizmoHandleGroup.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[Deactivate](ue_ue.AxisGizmoHandleGroup.md#deactivate)

___

### DetachFromParent

▸ **DetachFromParent**(`bMaintainWorldPosition?`, `bCallModify?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bMaintainWorldPosition?` | `boolean` |
| `bCallModify?` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[DetachFromParent](ue_ue.AxisGizmoHandleGroup.md#detachfromparent)

___

### DoesSocketExist

▸ **DoesSocketExist**(`InSocketName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSocketName` | `string` |

#### Returns

`boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[DoesSocketExist](ue_ue.AxisGizmoHandleGroup.md#doessocketexist)

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

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[ExecuteUbergraph](ue_ue.AxisGizmoHandleGroup.md#executeubergraph)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetAllSocketNames](ue_ue.AxisGizmoHandleGroup.md#getallsocketnames)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetAttachParent](ue_ue.AxisGizmoHandleGroup.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetAttachSocketName](ue_ue.AxisGizmoHandleGroup.md#getattachsocketname)

___

### GetChildComponent

▸ **GetChildComponent**(`ChildIndex`): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ChildIndex` | `number` |

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetChildComponent](ue_ue.AxisGizmoHandleGroup.md#getchildcomponent)

___

### GetChildrenComponents

▸ **GetChildrenComponents**(`bIncludeAllDescendants`, `Children`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bIncludeAllDescendants` | `boolean` |
| `Children` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>\> |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetChildrenComponents](ue_ue.AxisGizmoHandleGroup.md#getchildrencomponents)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetClass](ue_ue.AxisGizmoHandleGroup.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetComponentTickInterval](ue_ue.AxisGizmoHandleGroup.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetComponentVelocity](ue_ue.AxisGizmoHandleGroup.md#getcomponentvelocity)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetForwardVector](ue_ue.AxisGizmoHandleGroup.md#getforwardvector)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetName](ue_ue.AxisGizmoHandleGroup.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetNumChildrenComponents](ue_ue.AxisGizmoHandleGroup.md#getnumchildrencomponents)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetOuter](ue_ue.AxisGizmoHandleGroup.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetOwner](ue_ue.AxisGizmoHandleGroup.md#getowner)

___

### GetParentComponents

▸ **GetParentComponents**(`Parents`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Parents` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>\> |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetParentComponents](ue_ue.AxisGizmoHandleGroup.md#getparentcomponents)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetPhysicsVolume](ue_ue.AxisGizmoHandleGroup.md#getphysicsvolume)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetRelativeTransform](ue_ue.AxisGizmoHandleGroup.md#getrelativetransform)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetRightVector](ue_ue.AxisGizmoHandleGroup.md#getrightvector)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetShouldUpdatePhysicsVolume](ue_ue.AxisGizmoHandleGroup.md#getshouldupdatephysicsvolume)

___

### GetSocketLocation

▸ **GetSocketLocation**(`InSocketName`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSocketName` | `string` |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetSocketLocation](ue_ue.AxisGizmoHandleGroup.md#getsocketlocation)

___

### GetSocketQuaternion

▸ **GetSocketQuaternion**(`InSocketName`): [`Quat`](ue_ue_s.Quat.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSocketName` | `string` |

#### Returns

[`Quat`](ue_ue_s.Quat.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetSocketQuaternion](ue_ue.AxisGizmoHandleGroup.md#getsocketquaternion)

___

### GetSocketRotation

▸ **GetSocketRotation**(`InSocketName`): [`Rotator`](ue_ue_s.Rotator.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSocketName` | `string` |

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetSocketRotation](ue_ue.AxisGizmoHandleGroup.md#getsocketrotation)

___

### GetSocketTransform

▸ **GetSocketTransform**(`InSocketName`, `TransformSpace?`): [`Transform`](ue_ue_s.Transform.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSocketName` | `string` |
| `TransformSpace?` | [`ERelativeTransformSpace`](../enums/ue_ue.ERelativeTransformSpace.md) |

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetSocketTransform](ue_ue.AxisGizmoHandleGroup.md#getsockettransform)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetUpVector](ue_ue.AxisGizmoHandleGroup.md#getupvector)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[GetWorld](ue_ue.AxisGizmoHandleGroup.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[IsActive](ue_ue.AxisGizmoHandleGroup.md#isactive)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[IsAnySimulatingPhysics](ue_ue.AxisGizmoHandleGroup.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[IsBeingDestroyed](ue_ue.AxisGizmoHandleGroup.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[IsComponentTickEnabled](ue_ue.AxisGizmoHandleGroup.md#iscomponenttickenabled)

___

### IsSimulatingPhysics

▸ **IsSimulatingPhysics**(`BoneName?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `BoneName?` | `string` |

#### Returns

`boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[IsSimulatingPhysics](ue_ue.AxisGizmoHandleGroup.md#issimulatingphysics)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[IsVisible](ue_ue.AxisGizmoHandleGroup.md#isvisible)

___

### K2\_AddLocalOffset

▸ **K2_AddLocalOffset**(`DeltaLocation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_AddLocalOffset](ue_ue.AxisGizmoHandleGroup.md#k2_addlocaloffset)

___

### K2\_AddLocalRotation

▸ **K2_AddLocalRotation**(`DeltaRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_AddLocalRotation](ue_ue.AxisGizmoHandleGroup.md#k2_addlocalrotation)

___

### K2\_AddLocalTransform

▸ **K2_AddLocalTransform**(`DeltaTransform`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_AddLocalTransform](ue_ue.AxisGizmoHandleGroup.md#k2_addlocaltransform)

___

### K2\_AddRelativeLocation

▸ **K2_AddRelativeLocation**(`DeltaLocation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_AddRelativeLocation](ue_ue.AxisGizmoHandleGroup.md#k2_addrelativelocation)

___

### K2\_AddRelativeRotation

▸ **K2_AddRelativeRotation**(`DeltaRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_AddRelativeRotation](ue_ue.AxisGizmoHandleGroup.md#k2_addrelativerotation)

___

### K2\_AddWorldOffset

▸ **K2_AddWorldOffset**(`DeltaLocation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_AddWorldOffset](ue_ue.AxisGizmoHandleGroup.md#k2_addworldoffset)

___

### K2\_AddWorldRotation

▸ **K2_AddWorldRotation**(`DeltaRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_AddWorldRotation](ue_ue.AxisGizmoHandleGroup.md#k2_addworldrotation)

___

### K2\_AddWorldTransform

▸ **K2_AddWorldTransform**(`DeltaTransform`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_AddWorldTransform](ue_ue.AxisGizmoHandleGroup.md#k2_addworldtransform)

___

### K2\_AttachTo

▸ **K2_AttachTo**(`InParent`, `InSocketName?`, `AttachType?`, `bWeldSimulatedBodies?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InParent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `InSocketName?` | `string` |
| `AttachType?` | [`EAttachLocation`](../enums/ue_ue.EAttachLocation.md) |
| `bWeldSimulatedBodies?` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_AttachTo](ue_ue.AxisGizmoHandleGroup.md#k2_attachto)

___

### K2\_AttachToComponent

▸ **K2_AttachToComponent**(`Parent`, `SocketName`, `LocationRule`, `RotationRule`, `ScaleRule`, `bWeldSimulatedBodies`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Parent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `SocketName` | `string` |
| `LocationRule` | [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md) |
| `RotationRule` | [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md) |
| `ScaleRule` | [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md) |
| `bWeldSimulatedBodies` | `boolean` |

#### Returns

`boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_AttachToComponent](ue_ue.AxisGizmoHandleGroup.md#k2_attachtocomponent)

___

### K2\_DestroyComponent

▸ **K2_DestroyComponent**(`Object`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Object` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_DestroyComponent](ue_ue.AxisGizmoHandleGroup.md#k2_destroycomponent)

___

### K2\_DetachFromComponent

▸ **K2_DetachFromComponent**(`LocationRule?`, `RotationRule?`, `ScaleRule?`, `bCallModify?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `LocationRule?` | [`EDetachmentRule`](../enums/ue_ue.EDetachmentRule.md) |
| `RotationRule?` | [`EDetachmentRule`](../enums/ue_ue.EDetachmentRule.md) |
| `ScaleRule?` | [`EDetachmentRule`](../enums/ue_ue.EDetachmentRule.md) |
| `bCallModify?` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_DetachFromComponent](ue_ue.AxisGizmoHandleGroup.md#k2_detachfromcomponent)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_GetComponentLocation](ue_ue.AxisGizmoHandleGroup.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_GetComponentRotation](ue_ue.AxisGizmoHandleGroup.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_GetComponentScale](ue_ue.AxisGizmoHandleGroup.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_GetComponentToWorld](ue_ue.AxisGizmoHandleGroup.md#k2_getcomponenttoworld)

___

### K2\_SetRelativeLocation

▸ **K2_SetRelativeLocation**(`NewLocation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_SetRelativeLocation](ue_ue.AxisGizmoHandleGroup.md#k2_setrelativelocation)

___

### K2\_SetRelativeLocationAndRotation

▸ **K2_SetRelativeLocationAndRotation**(`NewLocation`, `NewRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_SetRelativeLocationAndRotation](ue_ue.AxisGizmoHandleGroup.md#k2_setrelativelocationandrotation)

___

### K2\_SetRelativeRotation

▸ **K2_SetRelativeRotation**(`NewRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_SetRelativeRotation](ue_ue.AxisGizmoHandleGroup.md#k2_setrelativerotation)

___

### K2\_SetRelativeTransform

▸ **K2_SetRelativeTransform**(`NewTransform`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_SetRelativeTransform](ue_ue.AxisGizmoHandleGroup.md#k2_setrelativetransform)

___

### K2\_SetWorldLocation

▸ **K2_SetWorldLocation**(`NewLocation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_SetWorldLocation](ue_ue.AxisGizmoHandleGroup.md#k2_setworldlocation)

___

### K2\_SetWorldLocationAndRotation

▸ **K2_SetWorldLocationAndRotation**(`NewLocation`, `NewRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_SetWorldLocationAndRotation](ue_ue.AxisGizmoHandleGroup.md#k2_setworldlocationandrotation)

___

### K2\_SetWorldRotation

▸ **K2_SetWorldRotation**(`NewRotation`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_SetWorldRotation](ue_ue.AxisGizmoHandleGroup.md#k2_setworldrotation)

___

### K2\_SetWorldTransform

▸ **K2_SetWorldTransform**(`NewTransform`, `bSweep`, `SweepHitResult`, `bTeleport`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `bSweep` | `boolean` |
| `SweepHitResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `bTeleport` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[K2_SetWorldTransform](ue_ue.AxisGizmoHandleGroup.md#k2_setworldtransform)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[OnRep_AttachChildren](ue_ue.AxisGizmoHandleGroup.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[OnRep_AttachParent](ue_ue.AxisGizmoHandleGroup.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[OnRep_AttachSocketName](ue_ue.AxisGizmoHandleGroup.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[OnRep_IsActive](ue_ue.AxisGizmoHandleGroup.md#onrep_isactive)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[OnRep_Transform](ue_ue.AxisGizmoHandleGroup.md#onrep_transform)

___

### OnRep\_Visibility

▸ **OnRep_Visibility**(`OldValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OldValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[OnRep_Visibility](ue_ue.AxisGizmoHandleGroup.md#onrep_visibility)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[ReceiveBeginPlay](ue_ue.AxisGizmoHandleGroup.md#receivebeginplay)

___

### ReceiveEndPlay

▸ **ReceiveEndPlay**(`EndPlayReason`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `EndPlayReason` | [`EEndPlayReason`](../enums/ue_ue.EEndPlayReason.md) |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[ReceiveEndPlay](ue_ue.AxisGizmoHandleGroup.md#receiveendplay)

___

### ReceiveTick

▸ **ReceiveTick**(`DeltaSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaSeconds` | `number` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[ReceiveTick](ue_ue.AxisGizmoHandleGroup.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[RegisterComponent](ue_ue.AxisGizmoHandleGroup.md#registercomponent)

___

### RemoveTickPrerequisiteActor

▸ **RemoveTickPrerequisiteActor**(`PrerequisiteActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[RemoveTickPrerequisiteActor](ue_ue.AxisGizmoHandleGroup.md#removetickprerequisiteactor)

___

### RemoveTickPrerequisiteComponent

▸ **RemoveTickPrerequisiteComponent**(`PrerequisiteComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `PrerequisiteComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\> |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[RemoveTickPrerequisiteComponent](ue_ue.AxisGizmoHandleGroup.md#removetickprerequisitecomponent)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[ResetRelativeTransform](ue_ue.AxisGizmoHandleGroup.md#resetrelativetransform)

___

### SetAbsolute

▸ **SetAbsolute**(`bNewAbsoluteLocation?`, `bNewAbsoluteRotation?`, `bNewAbsoluteScale?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewAbsoluteLocation?` | `boolean` |
| `bNewAbsoluteRotation?` | `boolean` |
| `bNewAbsoluteScale?` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[SetAbsolute](ue_ue.AxisGizmoHandleGroup.md#setabsolute)

___

### SetActive

▸ **SetActive**(`bNewActive`, `bReset?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewActive` | `boolean` |
| `bReset?` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[SetActive](ue_ue.AxisGizmoHandleGroup.md#setactive)

___

### SetAutoActivate

▸ **SetAutoActivate**(`bNewAutoActivate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewAutoActivate` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[SetAutoActivate](ue_ue.AxisGizmoHandleGroup.md#setautoactivate)

___

### SetComponentTickEnabled

▸ **SetComponentTickEnabled**(`bEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnabled` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[SetComponentTickEnabled](ue_ue.AxisGizmoHandleGroup.md#setcomponenttickenabled)

___

### SetComponentTickInterval

▸ **SetComponentTickInterval**(`TickInterval`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TickInterval` | `number` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[SetComponentTickInterval](ue_ue.AxisGizmoHandleGroup.md#setcomponenttickinterval)

___

### SetHiddenInGame

▸ **SetHiddenInGame**(`NewHidden`, `bPropagateToChildren?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewHidden` | `boolean` |
| `bPropagateToChildren?` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[SetHiddenInGame](ue_ue.AxisGizmoHandleGroup.md#sethiddeningame)

___

### SetIsReplicated

▸ **SetIsReplicated**(`ShouldReplicate`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ShouldReplicate` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[SetIsReplicated](ue_ue.AxisGizmoHandleGroup.md#setisreplicated)

___

### SetMobility

▸ **SetMobility**(`NewMobility`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMobility` | [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md) |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[SetMobility](ue_ue.AxisGizmoHandleGroup.md#setmobility)

___

### SetRelativeScale3D

▸ **SetRelativeScale3D**(`NewScale3D`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScale3D` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[SetRelativeScale3D](ue_ue.AxisGizmoHandleGroup.md#setrelativescale3d)

___

### SetShouldUpdatePhysicsVolume

▸ **SetShouldUpdatePhysicsVolume**(`bInShouldUpdatePhysicsVolume`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInShouldUpdatePhysicsVolume` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[SetShouldUpdatePhysicsVolume](ue_ue.AxisGizmoHandleGroup.md#setshouldupdatephysicsvolume)

___

### SetTickGroup

▸ **SetTickGroup**(`NewTickGroup`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTickGroup` | [`ETickingGroup`](../enums/ue_ue.ETickingGroup.md) |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[SetTickGroup](ue_ue.AxisGizmoHandleGroup.md#settickgroup)

___

### SetTickableWhenPaused

▸ **SetTickableWhenPaused**(`bTickableWhenPaused`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bTickableWhenPaused` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[SetTickableWhenPaused](ue_ue.AxisGizmoHandleGroup.md#settickablewhenpaused)

___

### SetVisibility

▸ **SetVisibility**(`bNewVisibility`, `bPropagateToChildren?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewVisibility` | `boolean` |
| `bPropagateToChildren?` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[SetVisibility](ue_ue.AxisGizmoHandleGroup.md#setvisibility)

___

### SetWorldScale3D

▸ **SetWorldScale3D**(`NewScale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewScale` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[SetWorldScale3D](ue_ue.AxisGizmoHandleGroup.md#setworldscale3d)

___

### SetupAttachment

▸ **SetupAttachment**(`p0`, `p1`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `p0` | [`SceneComponent`](ue_ue.SceneComponent.md) |
| `p1` | `string` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[SetupAttachment](ue_ue.AxisGizmoHandleGroup.md#setupattachment)

___

### SnapTo

▸ **SnapTo**(`InParent`, `InSocketName?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InParent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `InSocketName?` | `string` |

#### Returns

`boolean`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[SnapTo](ue_ue.AxisGizmoHandleGroup.md#snapto)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[ToggleActive](ue_ue.AxisGizmoHandleGroup.md#toggleactive)

___

### ToggleVisibility

▸ **ToggleVisibility**(`bPropagateToChildren?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bPropagateToChildren?` | `boolean` |

#### Returns

`void`

#### Inherited from

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[ToggleVisibility](ue_ue.AxisGizmoHandleGroup.md#togglevisibility)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PivotTranslationGizmoHandleGroup`](ue_ue.PivotTranslationGizmoHandleGroup.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PivotTranslationGizmoHandleGroup`](ue_ue.PivotTranslationGizmoHandleGroup.md)

#### Overrides

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[Find](ue_ue.AxisGizmoHandleGroup.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`PivotTranslationGizmoHandleGroup`](ue_ue.PivotTranslationGizmoHandleGroup.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PivotTranslationGizmoHandleGroup`](ue_ue.PivotTranslationGizmoHandleGroup.md)

#### Overrides

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[Load](ue_ue.AxisGizmoHandleGroup.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[AxisGizmoHandleGroup](ue_ue.AxisGizmoHandleGroup.md).[StaticClass](ue_ue.AxisGizmoHandleGroup.md#staticclass)
