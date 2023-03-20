[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SceneCaptureComponent2D

# Class: SceneCaptureComponent2D

[ue/ue](../modules/ue_ue.md).SceneCaptureComponent2D

## Hierarchy

- [`SceneCaptureComponent`](ue_ue.SceneCaptureComponent.md)

  ↳ **`SceneCaptureComponent2D`**

## Table of contents

### Constructors

- [constructor](ue_ue.SceneCaptureComponent2D.md#constructor)

### Properties

- [AssetUserData](ue_ue.SceneCaptureComponent2D.md#assetuserdata)
- [AttachChildren](ue_ue.SceneCaptureComponent2D.md#attachchildren)
- [AttachParent](ue_ue.SceneCaptureComponent2D.md#attachparent)
- [AttachSocketName](ue_ue.SceneCaptureComponent2D.md#attachsocketname)
- [CaptureMesh](ue_ue.SceneCaptureComponent2D.md#capturemesh)
- [CaptureSortPriority](ue_ue.SceneCaptureComponent2D.md#capturesortpriority)
- [CaptureSource](ue_ue.SceneCaptureComponent2D.md#capturesource)
- [ClientAttachedChildren](ue_ue.SceneCaptureComponent2D.md#clientattachedchildren)
- [ClipPlaneBase](ue_ue.SceneCaptureComponent2D.md#clipplanebase)
- [ClipPlaneNormal](ue_ue.SceneCaptureComponent2D.md#clipplanenormal)
- [ComponentTags](ue_ue.SceneCaptureComponent2D.md#componenttags)
- [ComponentVelocity](ue_ue.SceneCaptureComponent2D.md#componentvelocity)
- [CompositeMode](ue_ue.SceneCaptureComponent2D.md#compositemode)
- [CreationMethod](ue_ue.SceneCaptureComponent2D.md#creationmethod)
- [CustomNearClippingPlane](ue_ue.SceneCaptureComponent2D.md#customnearclippingplane)
- [CustomProjectionMatrix](ue_ue.SceneCaptureComponent2D.md#customprojectionmatrix)
- [DetailMode](ue_ue.SceneCaptureComponent2D.md#detailmode)
- [FOVAngle](ue_ue.SceneCaptureComponent2D.md#fovangle)
- [HiddenActors](ue_ue.SceneCaptureComponent2D.md#hiddenactors)
- [HiddenComponents](ue_ue.SceneCaptureComponent2D.md#hiddencomponents)
- [LODDistanceFactor](ue_ue.SceneCaptureComponent2D.md#loddistancefactor)
- [MaxViewDistanceOverride](ue_ue.SceneCaptureComponent2D.md#maxviewdistanceoverride)
- [Mobility](ue_ue.SceneCaptureComponent2D.md#mobility)
- [OnComponentActivated](ue_ue.SceneCaptureComponent2D.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.SceneCaptureComponent2D.md#oncomponentdeactivated)
- [OrthoWidth](ue_ue.SceneCaptureComponent2D.md#orthowidth)
- [PhysicsVolume](ue_ue.SceneCaptureComponent2D.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.SceneCaptureComponent2D.md#physicsvolumechangeddelegate)
- [PostProcessBlendWeight](ue_ue.SceneCaptureComponent2D.md#postprocessblendweight)
- [PostProcessSettings](ue_ue.SceneCaptureComponent2D.md#postprocesssettings)
- [PrimaryComponentTick](ue_ue.SceneCaptureComponent2D.md#primarycomponenttick)
- [PrimitiveRenderMode](ue_ue.SceneCaptureComponent2D.md#primitiverendermode)
- [ProfilingEventName](ue_ue.SceneCaptureComponent2D.md#profilingeventname)
- [ProjectionType](ue_ue.SceneCaptureComponent2D.md#projectiontype)
- [RelativeLocation](ue_ue.SceneCaptureComponent2D.md#relativelocation)
- [RelativeRotation](ue_ue.SceneCaptureComponent2D.md#relativerotation)
- [RelativeScale3D](ue_ue.SceneCaptureComponent2D.md#relativescale3d)
- [ShowFlagSettings](ue_ue.SceneCaptureComponent2D.md#showflagsettings)
- [ShowOnlyActors](ue_ue.SceneCaptureComponent2D.md#showonlyactors)
- [ShowOnlyComponents](ue_ue.SceneCaptureComponent2D.md#showonlycomponents)
- [TextureTarget](ue_ue.SceneCaptureComponent2D.md#texturetarget)
- [UCSModifiedProperties](ue_ue.SceneCaptureComponent2D.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.SceneCaptureComponent2D.md#__tid_actorcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.SceneCaptureComponent2D.md#__tid_object__)
- [\_\_tid\_SceneCaptureComponent2D\_\_](ue_ue.SceneCaptureComponent2D.md#__tid_scenecapturecomponent2d__)
- [\_\_tid\_SceneCaptureComponent\_\_](ue_ue.SceneCaptureComponent2D.md#__tid_scenecapturecomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.SceneCaptureComponent2D.md#__tid_scenecomponent__)
- [bAbsoluteLocation](ue_ue.SceneCaptureComponent2D.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.SceneCaptureComponent2D.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.SceneCaptureComponent2D.md#babsolutescale)
- [bAlwaysPersistRenderingState](ue_ue.SceneCaptureComponent2D.md#balwayspersistrenderingstate)
- [bAutoActivate](ue_ue.SceneCaptureComponent2D.md#bautoactivate)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.SceneCaptureComponent2D.md#bboundschangetriggersstreamingdatarebuild)
- [bCameraCutThisFrame](ue_ue.SceneCaptureComponent2D.md#bcameracutthisframe)
- [bCanEverAffectNavigation](ue_ue.SceneCaptureComponent2D.md#bcaneveraffectnavigation)
- [bCaptureEveryFrame](ue_ue.SceneCaptureComponent2D.md#bcaptureeveryframe)
- [bCaptureOnMovement](ue_ue.SceneCaptureComponent2D.md#bcaptureonmovement)
- [bComponentToWorldUpdated](ue_ue.SceneCaptureComponent2D.md#bcomponenttoworldupdated)
- [bConsiderUnrenderedOpaquePixelAsFullyTranslucent](ue_ue.SceneCaptureComponent2D.md#bconsiderunrenderedopaquepixelasfullytranslucent)
- [bCreatedByConstructionScript](ue_ue.SceneCaptureComponent2D.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.SceneCaptureComponent2D.md#beditablewheninherited)
- [bEnableClipPlane](ue_ue.SceneCaptureComponent2D.md#benableclipplane)
- [bHiddenInGame](ue_ue.SceneCaptureComponent2D.md#bhiddeningame)
- [bInstanceComponent](ue_ue.SceneCaptureComponent2D.md#binstancecomponent)
- [bIsActive](ue_ue.SceneCaptureComponent2D.md#bisactive)
- [bIsEditorOnly](ue_ue.SceneCaptureComponent2D.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.SceneCaptureComponent2D.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.SceneCaptureComponent2D.md#bnetaddressable)
- [bOverride\_CustomNearClippingPlane](ue_ue.SceneCaptureComponent2D.md#boverride_customnearclippingplane)
- [bReplicates](ue_ue.SceneCaptureComponent2D.md#breplicates)
- [bShouldBeAttached](ue_ue.SceneCaptureComponent2D.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.SceneCaptureComponent2D.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.SceneCaptureComponent2D.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.SceneCaptureComponent2D.md#bshouldupdatephysicsvolume)
- [bUseAttachParentBound](ue_ue.SceneCaptureComponent2D.md#buseattachparentbound)
- [bUseCustomProjectionMatrix](ue_ue.SceneCaptureComponent2D.md#busecustomprojectionmatrix)
- [bVisible](ue_ue.SceneCaptureComponent2D.md#bvisible)
- [bVisualizeComponent](ue_ue.SceneCaptureComponent2D.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.SceneCaptureComponent2D.md#activate)
- [AddOrUpdateBlendable](ue_ue.SceneCaptureComponent2D.md#addorupdateblendable)
- [AddTickPrerequisiteActor](ue_ue.SceneCaptureComponent2D.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.SceneCaptureComponent2D.md#addtickprerequisitecomponent)
- [CaptureScene](ue_ue.SceneCaptureComponent2D.md#capturescene)
- [ClearHiddenComponents](ue_ue.SceneCaptureComponent2D.md#clearhiddencomponents)
- [ClearShowOnlyComponents](ue_ue.SceneCaptureComponent2D.md#clearshowonlycomponents)
- [ComponentHasTag](ue_ue.SceneCaptureComponent2D.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.SceneCaptureComponent2D.md#createdefaultsubobject)
- [Deactivate](ue_ue.SceneCaptureComponent2D.md#deactivate)
- [DetachFromParent](ue_ue.SceneCaptureComponent2D.md#detachfromparent)
- [DoesSocketExist](ue_ue.SceneCaptureComponent2D.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.SceneCaptureComponent2D.md#executeubergraph)
- [GetAllSocketNames](ue_ue.SceneCaptureComponent2D.md#getallsocketnames)
- [GetAttachParent](ue_ue.SceneCaptureComponent2D.md#getattachparent)
- [GetAttachSocketName](ue_ue.SceneCaptureComponent2D.md#getattachsocketname)
- [GetChildComponent](ue_ue.SceneCaptureComponent2D.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.SceneCaptureComponent2D.md#getchildrencomponents)
- [GetClass](ue_ue.SceneCaptureComponent2D.md#getclass)
- [GetComponentTickInterval](ue_ue.SceneCaptureComponent2D.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.SceneCaptureComponent2D.md#getcomponentvelocity)
- [GetForwardVector](ue_ue.SceneCaptureComponent2D.md#getforwardvector)
- [GetName](ue_ue.SceneCaptureComponent2D.md#getname)
- [GetNumChildrenComponents](ue_ue.SceneCaptureComponent2D.md#getnumchildrencomponents)
- [GetOuter](ue_ue.SceneCaptureComponent2D.md#getouter)
- [GetOwner](ue_ue.SceneCaptureComponent2D.md#getowner)
- [GetParentComponents](ue_ue.SceneCaptureComponent2D.md#getparentcomponents)
- [GetPhysicsVolume](ue_ue.SceneCaptureComponent2D.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.SceneCaptureComponent2D.md#getrelativetransform)
- [GetRightVector](ue_ue.SceneCaptureComponent2D.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.SceneCaptureComponent2D.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.SceneCaptureComponent2D.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.SceneCaptureComponent2D.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.SceneCaptureComponent2D.md#getsocketrotation)
- [GetSocketTransform](ue_ue.SceneCaptureComponent2D.md#getsockettransform)
- [GetUpVector](ue_ue.SceneCaptureComponent2D.md#getupvector)
- [GetWorld](ue_ue.SceneCaptureComponent2D.md#getworld)
- [HideActorComponents](ue_ue.SceneCaptureComponent2D.md#hideactorcomponents)
- [HideComponent](ue_ue.SceneCaptureComponent2D.md#hidecomponent)
- [IsActive](ue_ue.SceneCaptureComponent2D.md#isactive)
- [IsAnySimulatingPhysics](ue_ue.SceneCaptureComponent2D.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.SceneCaptureComponent2D.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.SceneCaptureComponent2D.md#iscomponenttickenabled)
- [IsSimulatingPhysics](ue_ue.SceneCaptureComponent2D.md#issimulatingphysics)
- [IsVisible](ue_ue.SceneCaptureComponent2D.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.SceneCaptureComponent2D.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.SceneCaptureComponent2D.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.SceneCaptureComponent2D.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.SceneCaptureComponent2D.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.SceneCaptureComponent2D.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.SceneCaptureComponent2D.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.SceneCaptureComponent2D.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.SceneCaptureComponent2D.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.SceneCaptureComponent2D.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.SceneCaptureComponent2D.md#k2_attachtocomponent)
- [K2\_DestroyComponent](ue_ue.SceneCaptureComponent2D.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.SceneCaptureComponent2D.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.SceneCaptureComponent2D.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.SceneCaptureComponent2D.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.SceneCaptureComponent2D.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.SceneCaptureComponent2D.md#k2_getcomponenttoworld)
- [K2\_SetRelativeLocation](ue_ue.SceneCaptureComponent2D.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.SceneCaptureComponent2D.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.SceneCaptureComponent2D.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.SceneCaptureComponent2D.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.SceneCaptureComponent2D.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.SceneCaptureComponent2D.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.SceneCaptureComponent2D.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.SceneCaptureComponent2D.md#k2_setworldtransform)
- [OnRep\_AttachChildren](ue_ue.SceneCaptureComponent2D.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.SceneCaptureComponent2D.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.SceneCaptureComponent2D.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.SceneCaptureComponent2D.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.SceneCaptureComponent2D.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.SceneCaptureComponent2D.md#onrep_visibility)
- [ReceiveBeginPlay](ue_ue.SceneCaptureComponent2D.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.SceneCaptureComponent2D.md#receiveendplay)
- [ReceiveTick](ue_ue.SceneCaptureComponent2D.md#receivetick)
- [RegisterComponent](ue_ue.SceneCaptureComponent2D.md#registercomponent)
- [RemoveShowOnlyActorComponents](ue_ue.SceneCaptureComponent2D.md#removeshowonlyactorcomponents)
- [RemoveShowOnlyComponent](ue_ue.SceneCaptureComponent2D.md#removeshowonlycomponent)
- [RemoveTickPrerequisiteActor](ue_ue.SceneCaptureComponent2D.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.SceneCaptureComponent2D.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.SceneCaptureComponent2D.md#resetrelativetransform)
- [SetAbsolute](ue_ue.SceneCaptureComponent2D.md#setabsolute)
- [SetActive](ue_ue.SceneCaptureComponent2D.md#setactive)
- [SetAutoActivate](ue_ue.SceneCaptureComponent2D.md#setautoactivate)
- [SetCaptureSortPriority](ue_ue.SceneCaptureComponent2D.md#setcapturesortpriority)
- [SetComponentTickEnabled](ue_ue.SceneCaptureComponent2D.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.SceneCaptureComponent2D.md#setcomponenttickinterval)
- [SetHiddenInGame](ue_ue.SceneCaptureComponent2D.md#sethiddeningame)
- [SetIsReplicated](ue_ue.SceneCaptureComponent2D.md#setisreplicated)
- [SetMobility](ue_ue.SceneCaptureComponent2D.md#setmobility)
- [SetRelativeScale3D](ue_ue.SceneCaptureComponent2D.md#setrelativescale3d)
- [SetShouldUpdatePhysicsVolume](ue_ue.SceneCaptureComponent2D.md#setshouldupdatephysicsvolume)
- [SetTickGroup](ue_ue.SceneCaptureComponent2D.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.SceneCaptureComponent2D.md#settickablewhenpaused)
- [SetVisibility](ue_ue.SceneCaptureComponent2D.md#setvisibility)
- [SetWorldScale3D](ue_ue.SceneCaptureComponent2D.md#setworldscale3d)
- [SetupAttachment](ue_ue.SceneCaptureComponent2D.md#setupattachment)
- [ShowOnlyActorComponents](ue_ue.SceneCaptureComponent2D.md#showonlyactorcomponents)
- [ShowOnlyComponent](ue_ue.SceneCaptureComponent2D.md#showonlycomponent)
- [SnapTo](ue_ue.SceneCaptureComponent2D.md#snapto)
- [ToggleActive](ue_ue.SceneCaptureComponent2D.md#toggleactive)
- [ToggleVisibility](ue_ue.SceneCaptureComponent2D.md#togglevisibility)
- [Find](ue_ue.SceneCaptureComponent2D.md#find)
- [Load](ue_ue.SceneCaptureComponent2D.md#load)
- [StaticClass](ue_ue.SceneCaptureComponent2D.md#staticclass)

## Constructors

### constructor

• **new SceneCaptureComponent2D**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[constructor](ue_ue.SceneCaptureComponent.md#constructor)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[AssetUserData](ue_ue.SceneCaptureComponent.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[AttachChildren](ue_ue.SceneCaptureComponent.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[AttachParent](ue_ue.SceneCaptureComponent.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[AttachSocketName](ue_ue.SceneCaptureComponent.md#attachsocketname)

___

### CaptureMesh

• **CaptureMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[CaptureMesh](ue_ue.SceneCaptureComponent.md#capturemesh)

___

### CaptureSortPriority

• **CaptureSortPriority**: `number`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[CaptureSortPriority](ue_ue.SceneCaptureComponent.md#capturesortpriority)

___

### CaptureSource

• **CaptureSource**: [`ESceneCaptureSource`](../enums/ue_ue.ESceneCaptureSource.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[CaptureSource](ue_ue.SceneCaptureComponent.md#capturesource)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ClientAttachedChildren](ue_ue.SceneCaptureComponent.md#clientattachedchildren)

___

### ClipPlaneBase

• **ClipPlaneBase**: [`Vector`](ue_ue_s.Vector.md)

___

### ClipPlaneNormal

• **ClipPlaneNormal**: [`Vector`](ue_ue_s.Vector.md)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ComponentTags](ue_ue.SceneCaptureComponent.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ComponentVelocity](ue_ue.SceneCaptureComponent.md#componentvelocity)

___

### CompositeMode

• **CompositeMode**: [`ESceneCaptureCompositeMode`](../enums/ue_ue.ESceneCaptureCompositeMode.md)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[CreationMethod](ue_ue.SceneCaptureComponent.md#creationmethod)

___

### CustomNearClippingPlane

• **CustomNearClippingPlane**: `number`

___

### CustomProjectionMatrix

• **CustomProjectionMatrix**: [`Matrix`](ue_ue.Matrix.md)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[DetailMode](ue_ue.SceneCaptureComponent.md#detailmode)

___

### FOVAngle

• **FOVAngle**: `number`

___

### HiddenActors

• **HiddenActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[HiddenActors](ue_ue.SceneCaptureComponent.md#hiddenactors)

___

### HiddenComponents

• **HiddenComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>\>

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[HiddenComponents](ue_ue.SceneCaptureComponent.md#hiddencomponents)

___

### LODDistanceFactor

• **LODDistanceFactor**: `number`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[LODDistanceFactor](ue_ue.SceneCaptureComponent.md#loddistancefactor)

___

### MaxViewDistanceOverride

• **MaxViewDistanceOverride**: `number`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[MaxViewDistanceOverride](ue_ue.SceneCaptureComponent.md#maxviewdistanceoverride)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[Mobility](ue_ue.SceneCaptureComponent.md#mobility)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[OnComponentActivated](ue_ue.SceneCaptureComponent.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[OnComponentDeactivated](ue_ue.SceneCaptureComponent.md#oncomponentdeactivated)

___

### OrthoWidth

• **OrthoWidth**: `number`

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[PhysicsVolume](ue_ue.SceneCaptureComponent.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.SceneCaptureComponent.md#physicsvolumechangeddelegate)

___

### PostProcessBlendWeight

• **PostProcessBlendWeight**: `number`

___

### PostProcessSettings

• **PostProcessSettings**: [`PostProcessSettings`](ue_ue.PostProcessSettings.md)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[PrimaryComponentTick](ue_ue.SceneCaptureComponent.md#primarycomponenttick)

___

### PrimitiveRenderMode

• **PrimitiveRenderMode**: [`ESceneCapturePrimitiveRenderMode`](../enums/ue_ue.ESceneCapturePrimitiveRenderMode.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[PrimitiveRenderMode](ue_ue.SceneCaptureComponent.md#primitiverendermode)

___

### ProfilingEventName

• **ProfilingEventName**: `string`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ProfilingEventName](ue_ue.SceneCaptureComponent.md#profilingeventname)

___

### ProjectionType

• **ProjectionType**: [`ECameraProjectionMode`](../enums/ue_ue.ECameraProjectionMode.md)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[RelativeLocation](ue_ue.SceneCaptureComponent.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[RelativeRotation](ue_ue.SceneCaptureComponent.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[RelativeScale3D](ue_ue.SceneCaptureComponent.md#relativescale3d)

___

### ShowFlagSettings

• **ShowFlagSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EngineShowFlagsSetting`](ue_ue.EngineShowFlagsSetting.md)\>

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ShowFlagSettings](ue_ue.SceneCaptureComponent.md#showflagsettings)

___

### ShowOnlyActors

• **ShowOnlyActors**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ShowOnlyActors](ue_ue.SceneCaptureComponent.md#showonlyactors)

___

### ShowOnlyComponents

• **ShowOnlyComponents**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\>\>

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ShowOnlyComponents](ue_ue.SceneCaptureComponent.md#showonlycomponents)

___

### TextureTarget

• **TextureTarget**: [`TextureRenderTarget2D`](ue_ue.TextureRenderTarget2D.md)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[UCSModifiedProperties](ue_ue.SceneCaptureComponent.md#ucsmodifiedproperties)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[__tid_ActorComponent__](ue_ue.SceneCaptureComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[__tid_Object__](ue_ue.SceneCaptureComponent.md#__tid_object__)

___

### \_\_tid\_SceneCaptureComponent2D\_\_

• **\_\_tid\_SceneCaptureComponent2D\_\_**: `boolean`

___

### \_\_tid\_SceneCaptureComponent\_\_

• **\_\_tid\_SceneCaptureComponent\_\_**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[__tid_SceneCaptureComponent__](ue_ue.SceneCaptureComponent.md#__tid_scenecapturecomponent__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[__tid_SceneComponent__](ue_ue.SceneCaptureComponent.md#__tid_scenecomponent__)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bAbsoluteLocation](ue_ue.SceneCaptureComponent.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bAbsoluteRotation](ue_ue.SceneCaptureComponent.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bAbsoluteScale](ue_ue.SceneCaptureComponent.md#babsolutescale)

___

### bAlwaysPersistRenderingState

• **bAlwaysPersistRenderingState**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bAlwaysPersistRenderingState](ue_ue.SceneCaptureComponent.md#balwayspersistrenderingstate)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bAutoActivate](ue_ue.SceneCaptureComponent.md#bautoactivate)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.SceneCaptureComponent.md#bboundschangetriggersstreamingdatarebuild)

___

### bCameraCutThisFrame

• **bCameraCutThisFrame**: `boolean`

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bCanEverAffectNavigation](ue_ue.SceneCaptureComponent.md#bcaneveraffectnavigation)

___

### bCaptureEveryFrame

• **bCaptureEveryFrame**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bCaptureEveryFrame](ue_ue.SceneCaptureComponent.md#bcaptureeveryframe)

___

### bCaptureOnMovement

• **bCaptureOnMovement**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bCaptureOnMovement](ue_ue.SceneCaptureComponent.md#bcaptureonmovement)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bComponentToWorldUpdated](ue_ue.SceneCaptureComponent.md#bcomponenttoworldupdated)

___

### bConsiderUnrenderedOpaquePixelAsFullyTranslucent

• **bConsiderUnrenderedOpaquePixelAsFullyTranslucent**: `boolean`

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bCreatedByConstructionScript](ue_ue.SceneCaptureComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bEditableWhenInherited](ue_ue.SceneCaptureComponent.md#beditablewheninherited)

___

### bEnableClipPlane

• **bEnableClipPlane**: `boolean`

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bHiddenInGame](ue_ue.SceneCaptureComponent.md#bhiddeningame)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bInstanceComponent](ue_ue.SceneCaptureComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bIsActive](ue_ue.SceneCaptureComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bIsEditorOnly](ue_ue.SceneCaptureComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bIsVisualizationComponent](ue_ue.SceneCaptureComponent.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bNetAddressable](ue_ue.SceneCaptureComponent.md#bnetaddressable)

___

### bOverride\_CustomNearClippingPlane

• **bOverride\_CustomNearClippingPlane**: `boolean`

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bReplicates](ue_ue.SceneCaptureComponent.md#breplicates)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bShouldBeAttached](ue_ue.SceneCaptureComponent.md#bshouldbeattached)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.SceneCaptureComponent.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.SceneCaptureComponent.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.SceneCaptureComponent.md#bshouldupdatephysicsvolume)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bUseAttachParentBound](ue_ue.SceneCaptureComponent.md#buseattachparentbound)

___

### bUseCustomProjectionMatrix

• **bUseCustomProjectionMatrix**: `boolean`

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bVisible](ue_ue.SceneCaptureComponent.md#bvisible)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[bVisualizeComponent](ue_ue.SceneCaptureComponent.md#bvisualizecomponent)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[Activate](ue_ue.SceneCaptureComponent.md#activate)

___

### AddOrUpdateBlendable

▸ **AddOrUpdateBlendable**(`InBlendableObject`, `InWeight?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBlendableObject` | [`BlendableInterface`](ue_ue.BlendableInterface.md) |
| `InWeight?` | `number` |

#### Returns

`void`

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[AddTickPrerequisiteActor](ue_ue.SceneCaptureComponent.md#addtickprerequisiteactor)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[AddTickPrerequisiteComponent](ue_ue.SceneCaptureComponent.md#addtickprerequisitecomponent)

___

### CaptureScene

▸ **CaptureScene**(): `void`

#### Returns

`void`

___

### ClearHiddenComponents

▸ **ClearHiddenComponents**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ClearHiddenComponents](ue_ue.SceneCaptureComponent.md#clearhiddencomponents)

___

### ClearShowOnlyComponents

▸ **ClearShowOnlyComponents**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ClearShowOnlyComponents](ue_ue.SceneCaptureComponent.md#clearshowonlycomponents)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ComponentHasTag](ue_ue.SceneCaptureComponent.md#componenthastag)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[CreateDefaultSubobject](ue_ue.SceneCaptureComponent.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[Deactivate](ue_ue.SceneCaptureComponent.md#deactivate)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[DetachFromParent](ue_ue.SceneCaptureComponent.md#detachfromparent)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[DoesSocketExist](ue_ue.SceneCaptureComponent.md#doessocketexist)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ExecuteUbergraph](ue_ue.SceneCaptureComponent.md#executeubergraph)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetAllSocketNames](ue_ue.SceneCaptureComponent.md#getallsocketnames)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetAttachParent](ue_ue.SceneCaptureComponent.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetAttachSocketName](ue_ue.SceneCaptureComponent.md#getattachsocketname)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetChildComponent](ue_ue.SceneCaptureComponent.md#getchildcomponent)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetChildrenComponents](ue_ue.SceneCaptureComponent.md#getchildrencomponents)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetClass](ue_ue.SceneCaptureComponent.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetComponentTickInterval](ue_ue.SceneCaptureComponent.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetComponentVelocity](ue_ue.SceneCaptureComponent.md#getcomponentvelocity)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetForwardVector](ue_ue.SceneCaptureComponent.md#getforwardvector)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetName](ue_ue.SceneCaptureComponent.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetNumChildrenComponents](ue_ue.SceneCaptureComponent.md#getnumchildrencomponents)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetOuter](ue_ue.SceneCaptureComponent.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetOwner](ue_ue.SceneCaptureComponent.md#getowner)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetParentComponents](ue_ue.SceneCaptureComponent.md#getparentcomponents)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetPhysicsVolume](ue_ue.SceneCaptureComponent.md#getphysicsvolume)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetRelativeTransform](ue_ue.SceneCaptureComponent.md#getrelativetransform)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetRightVector](ue_ue.SceneCaptureComponent.md#getrightvector)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.SceneCaptureComponent.md#getshouldupdatephysicsvolume)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetSocketLocation](ue_ue.SceneCaptureComponent.md#getsocketlocation)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetSocketQuaternion](ue_ue.SceneCaptureComponent.md#getsocketquaternion)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetSocketRotation](ue_ue.SceneCaptureComponent.md#getsocketrotation)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetSocketTransform](ue_ue.SceneCaptureComponent.md#getsockettransform)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetUpVector](ue_ue.SceneCaptureComponent.md#getupvector)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[GetWorld](ue_ue.SceneCaptureComponent.md#getworld)

___

### HideActorComponents

▸ **HideActorComponents**(`InActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[HideActorComponents](ue_ue.SceneCaptureComponent.md#hideactorcomponents)

___

### HideComponent

▸ **HideComponent**(`InComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[HideComponent](ue_ue.SceneCaptureComponent.md#hidecomponent)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[IsActive](ue_ue.SceneCaptureComponent.md#isactive)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[IsAnySimulatingPhysics](ue_ue.SceneCaptureComponent.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[IsBeingDestroyed](ue_ue.SceneCaptureComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[IsComponentTickEnabled](ue_ue.SceneCaptureComponent.md#iscomponenttickenabled)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[IsSimulatingPhysics](ue_ue.SceneCaptureComponent.md#issimulatingphysics)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[IsVisible](ue_ue.SceneCaptureComponent.md#isvisible)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_AddLocalOffset](ue_ue.SceneCaptureComponent.md#k2_addlocaloffset)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_AddLocalRotation](ue_ue.SceneCaptureComponent.md#k2_addlocalrotation)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_AddLocalTransform](ue_ue.SceneCaptureComponent.md#k2_addlocaltransform)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_AddRelativeLocation](ue_ue.SceneCaptureComponent.md#k2_addrelativelocation)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_AddRelativeRotation](ue_ue.SceneCaptureComponent.md#k2_addrelativerotation)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_AddWorldOffset](ue_ue.SceneCaptureComponent.md#k2_addworldoffset)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_AddWorldRotation](ue_ue.SceneCaptureComponent.md#k2_addworldrotation)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_AddWorldTransform](ue_ue.SceneCaptureComponent.md#k2_addworldtransform)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_AttachTo](ue_ue.SceneCaptureComponent.md#k2_attachto)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_AttachToComponent](ue_ue.SceneCaptureComponent.md#k2_attachtocomponent)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_DestroyComponent](ue_ue.SceneCaptureComponent.md#k2_destroycomponent)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_DetachFromComponent](ue_ue.SceneCaptureComponent.md#k2_detachfromcomponent)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_GetComponentLocation](ue_ue.SceneCaptureComponent.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_GetComponentRotation](ue_ue.SceneCaptureComponent.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_GetComponentScale](ue_ue.SceneCaptureComponent.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_GetComponentToWorld](ue_ue.SceneCaptureComponent.md#k2_getcomponenttoworld)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_SetRelativeLocation](ue_ue.SceneCaptureComponent.md#k2_setrelativelocation)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.SceneCaptureComponent.md#k2_setrelativelocationandrotation)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_SetRelativeRotation](ue_ue.SceneCaptureComponent.md#k2_setrelativerotation)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_SetRelativeTransform](ue_ue.SceneCaptureComponent.md#k2_setrelativetransform)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_SetWorldLocation](ue_ue.SceneCaptureComponent.md#k2_setworldlocation)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.SceneCaptureComponent.md#k2_setworldlocationandrotation)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_SetWorldRotation](ue_ue.SceneCaptureComponent.md#k2_setworldrotation)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[K2_SetWorldTransform](ue_ue.SceneCaptureComponent.md#k2_setworldtransform)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[OnRep_AttachChildren](ue_ue.SceneCaptureComponent.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[OnRep_AttachParent](ue_ue.SceneCaptureComponent.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[OnRep_AttachSocketName](ue_ue.SceneCaptureComponent.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[OnRep_IsActive](ue_ue.SceneCaptureComponent.md#onrep_isactive)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[OnRep_Transform](ue_ue.SceneCaptureComponent.md#onrep_transform)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[OnRep_Visibility](ue_ue.SceneCaptureComponent.md#onrep_visibility)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ReceiveBeginPlay](ue_ue.SceneCaptureComponent.md#receivebeginplay)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ReceiveEndPlay](ue_ue.SceneCaptureComponent.md#receiveendplay)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ReceiveTick](ue_ue.SceneCaptureComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[RegisterComponent](ue_ue.SceneCaptureComponent.md#registercomponent)

___

### RemoveShowOnlyActorComponents

▸ **RemoveShowOnlyActorComponents**(`InActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[RemoveShowOnlyActorComponents](ue_ue.SceneCaptureComponent.md#removeshowonlyactorcomponents)

___

### RemoveShowOnlyComponent

▸ **RemoveShowOnlyComponent**(`InComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[RemoveShowOnlyComponent](ue_ue.SceneCaptureComponent.md#removeshowonlycomponent)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[RemoveTickPrerequisiteActor](ue_ue.SceneCaptureComponent.md#removetickprerequisiteactor)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.SceneCaptureComponent.md#removetickprerequisitecomponent)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ResetRelativeTransform](ue_ue.SceneCaptureComponent.md#resetrelativetransform)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[SetAbsolute](ue_ue.SceneCaptureComponent.md#setabsolute)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[SetActive](ue_ue.SceneCaptureComponent.md#setactive)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[SetAutoActivate](ue_ue.SceneCaptureComponent.md#setautoactivate)

___

### SetCaptureSortPriority

▸ **SetCaptureSortPriority**(`NewCaptureSortPriority`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewCaptureSortPriority` | `number` |

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[SetCaptureSortPriority](ue_ue.SceneCaptureComponent.md#setcapturesortpriority)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[SetComponentTickEnabled](ue_ue.SceneCaptureComponent.md#setcomponenttickenabled)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[SetComponentTickInterval](ue_ue.SceneCaptureComponent.md#setcomponenttickinterval)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[SetHiddenInGame](ue_ue.SceneCaptureComponent.md#sethiddeningame)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[SetIsReplicated](ue_ue.SceneCaptureComponent.md#setisreplicated)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[SetMobility](ue_ue.SceneCaptureComponent.md#setmobility)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[SetRelativeScale3D](ue_ue.SceneCaptureComponent.md#setrelativescale3d)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.SceneCaptureComponent.md#setshouldupdatephysicsvolume)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[SetTickGroup](ue_ue.SceneCaptureComponent.md#settickgroup)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[SetTickableWhenPaused](ue_ue.SceneCaptureComponent.md#settickablewhenpaused)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[SetVisibility](ue_ue.SceneCaptureComponent.md#setvisibility)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[SetWorldScale3D](ue_ue.SceneCaptureComponent.md#setworldscale3d)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[SetupAttachment](ue_ue.SceneCaptureComponent.md#setupattachment)

___

### ShowOnlyActorComponents

▸ **ShowOnlyActorComponents**(`InActor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ShowOnlyActorComponents](ue_ue.SceneCaptureComponent.md#showonlyactorcomponents)

___

### ShowOnlyComponent

▸ **ShowOnlyComponent**(`InComponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ShowOnlyComponent](ue_ue.SceneCaptureComponent.md#showonlycomponent)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[SnapTo](ue_ue.SceneCaptureComponent.md#snapto)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ToggleActive](ue_ue.SceneCaptureComponent.md#toggleactive)

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

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[ToggleVisibility](ue_ue.SceneCaptureComponent.md#togglevisibility)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SceneCaptureComponent2D`](ue_ue.SceneCaptureComponent2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SceneCaptureComponent2D`](ue_ue.SceneCaptureComponent2D.md)

#### Overrides

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[Find](ue_ue.SceneCaptureComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SceneCaptureComponent2D`](ue_ue.SceneCaptureComponent2D.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SceneCaptureComponent2D`](ue_ue.SceneCaptureComponent2D.md)

#### Overrides

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[Load](ue_ue.SceneCaptureComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SceneCaptureComponent](ue_ue.SceneCaptureComponent.md).[StaticClass](ue_ue.SceneCaptureComponent.md#staticclass)
