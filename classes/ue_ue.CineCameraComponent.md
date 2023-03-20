[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / CineCameraComponent

# Class: CineCameraComponent

[ue/ue](../modules/ue_ue.md).CineCameraComponent

## Hierarchy

- [`CameraComponent`](ue_ue.CameraComponent.md)

  ↳ **`CineCameraComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.CineCameraComponent.md#constructor)

### Properties

- [AspectRatio](ue_ue.CineCameraComponent.md#aspectratio)
- [AssetUserData](ue_ue.CineCameraComponent.md#assetuserdata)
- [AttachChildren](ue_ue.CineCameraComponent.md#attachchildren)
- [AttachParent](ue_ue.CineCameraComponent.md#attachparent)
- [AttachSocketName](ue_ue.CineCameraComponent.md#attachsocketname)
- [CameraMesh](ue_ue.CineCameraComponent.md#cameramesh)
- [ClientAttachedChildren](ue_ue.CineCameraComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.CineCameraComponent.md#componenttags)
- [ComponentVelocity](ue_ue.CineCameraComponent.md#componentvelocity)
- [CreationMethod](ue_ue.CineCameraComponent.md#creationmethod)
- [CurrentAperture](ue_ue.CineCameraComponent.md#currentaperture)
- [CurrentFocalLength](ue_ue.CineCameraComponent.md#currentfocallength)
- [CurrentFocusDistance](ue_ue.CineCameraComponent.md#currentfocusdistance)
- [CurrentHorizontalFOV](ue_ue.CineCameraComponent.md#currenthorizontalfov)
- [DebugFocusPlaneComponent](ue_ue.CineCameraComponent.md#debugfocusplanecomponent)
- [DebugFocusPlaneMID](ue_ue.CineCameraComponent.md#debugfocusplanemid)
- [DefaultFilmbackPreset](ue_ue.CineCameraComponent.md#defaultfilmbackpreset)
- [DefaultFilmbackPresetName](ue_ue.CineCameraComponent.md#defaultfilmbackpresetname)
- [DefaultLensFStop](ue_ue.CineCameraComponent.md#defaultlensfstop)
- [DefaultLensFocalLength](ue_ue.CineCameraComponent.md#defaultlensfocallength)
- [DefaultLensPresetName](ue_ue.CineCameraComponent.md#defaultlenspresetname)
- [DetailMode](ue_ue.CineCameraComponent.md#detailmode)
- [FieldOfView](ue_ue.CineCameraComponent.md#fieldofview)
- [Filmback](ue_ue.CineCameraComponent.md#filmback)
- [FilmbackPresets](ue_ue.CineCameraComponent.md#filmbackpresets)
- [FilmbackSettings](ue_ue.CineCameraComponent.md#filmbacksettings)
- [FocusPlaneVisualizationMaterial](ue_ue.CineCameraComponent.md#focusplanevisualizationmaterial)
- [FocusPlaneVisualizationMesh](ue_ue.CineCameraComponent.md#focusplanevisualizationmesh)
- [FocusSettings](ue_ue.CineCameraComponent.md#focussettings)
- [LensPresets](ue_ue.CineCameraComponent.md#lenspresets)
- [LensSettings](ue_ue.CineCameraComponent.md#lenssettings)
- [Mobility](ue_ue.CineCameraComponent.md#mobility)
- [OnComponentActivated](ue_ue.CineCameraComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.CineCameraComponent.md#oncomponentdeactivated)
- [OrthoFarClipPlane](ue_ue.CineCameraComponent.md#orthofarclipplane)
- [OrthoNearClipPlane](ue_ue.CineCameraComponent.md#orthonearclipplane)
- [OrthoWidth](ue_ue.CineCameraComponent.md#orthowidth)
- [PhysicsVolume](ue_ue.CineCameraComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.CineCameraComponent.md#physicsvolumechangeddelegate)
- [PostProcessBlendWeight](ue_ue.CineCameraComponent.md#postprocessblendweight)
- [PostProcessSettings](ue_ue.CineCameraComponent.md#postprocesssettings)
- [PrimaryComponentTick](ue_ue.CineCameraComponent.md#primarycomponenttick)
- [ProjectionMode](ue_ue.CineCameraComponent.md#projectionmode)
- [RelativeLocation](ue_ue.CineCameraComponent.md#relativelocation)
- [RelativeRotation](ue_ue.CineCameraComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.CineCameraComponent.md#relativescale3d)
- [UCSModifiedProperties](ue_ue.CineCameraComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.CineCameraComponent.md#__tid_actorcomponent__)
- [\_\_tid\_CameraComponent\_\_](ue_ue.CineCameraComponent.md#__tid_cameracomponent__)
- [\_\_tid\_CineCameraComponent\_\_](ue_ue.CineCameraComponent.md#__tid_cinecameracomponent__)
- [\_\_tid\_Object\_\_](ue_ue.CineCameraComponent.md#__tid_object__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.CineCameraComponent.md#__tid_scenecomponent__)
- [bAbsoluteLocation](ue_ue.CineCameraComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.CineCameraComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.CineCameraComponent.md#babsolutescale)
- [bAutoActivate](ue_ue.CineCameraComponent.md#bautoactivate)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.CineCameraComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCameraMeshHiddenInGame](ue_ue.CineCameraComponent.md#bcamerameshhiddeningame)
- [bCanEverAffectNavigation](ue_ue.CineCameraComponent.md#bcaneveraffectnavigation)
- [bComponentToWorldUpdated](ue_ue.CineCameraComponent.md#bcomponenttoworldupdated)
- [bConstrainAspectRatio](ue_ue.CineCameraComponent.md#bconstrainaspectratio)
- [bCreatedByConstructionScript](ue_ue.CineCameraComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.CineCameraComponent.md#beditablewheninherited)
- [bHiddenInGame](ue_ue.CineCameraComponent.md#bhiddeningame)
- [bInstanceComponent](ue_ue.CineCameraComponent.md#binstancecomponent)
- [bIsActive](ue_ue.CineCameraComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.CineCameraComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.CineCameraComponent.md#bisvisualizationcomponent)
- [bLockToHmd](ue_ue.CineCameraComponent.md#blocktohmd)
- [bNetAddressable](ue_ue.CineCameraComponent.md#bnetaddressable)
- [bReplicates](ue_ue.CineCameraComponent.md#breplicates)
- [bShouldBeAttached](ue_ue.CineCameraComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.CineCameraComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.CineCameraComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.CineCameraComponent.md#bshouldupdatephysicsvolume)
- [bUseAttachParentBound](ue_ue.CineCameraComponent.md#buseattachparentbound)
- [bUseControllerViewRotation](ue_ue.CineCameraComponent.md#busecontrollerviewrotation)
- [bUseFieldOfViewForLOD](ue_ue.CineCameraComponent.md#busefieldofviewforlod)
- [bUsePawnControlRotation](ue_ue.CineCameraComponent.md#busepawncontrolrotation)
- [bVisible](ue_ue.CineCameraComponent.md#bvisible)
- [bVisualizeComponent](ue_ue.CineCameraComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.CineCameraComponent.md#activate)
- [AddOrUpdateBlendable](ue_ue.CineCameraComponent.md#addorupdateblendable)
- [AddTickPrerequisiteActor](ue_ue.CineCameraComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.CineCameraComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.CineCameraComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.CineCameraComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.CineCameraComponent.md#deactivate)
- [DetachFromParent](ue_ue.CineCameraComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.CineCameraComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.CineCameraComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.CineCameraComponent.md#getallsocketnames)
- [GetAttachParent](ue_ue.CineCameraComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.CineCameraComponent.md#getattachsocketname)
- [GetCameraView](ue_ue.CineCameraComponent.md#getcameraview)
- [GetChildComponent](ue_ue.CineCameraComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.CineCameraComponent.md#getchildrencomponents)
- [GetClass](ue_ue.CineCameraComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.CineCameraComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.CineCameraComponent.md#getcomponentvelocity)
- [GetDefaultFilmbackPresetName](ue_ue.CineCameraComponent.md#getdefaultfilmbackpresetname)
- [GetFilmbackPresetName](ue_ue.CineCameraComponent.md#getfilmbackpresetname)
- [GetFilmbackText](ue_ue.CineCameraComponent.md#getfilmbacktext)
- [GetForwardVector](ue_ue.CineCameraComponent.md#getforwardvector)
- [GetHorizontalFieldOfView](ue_ue.CineCameraComponent.md#gethorizontalfieldofview)
- [GetLensPresetName](ue_ue.CineCameraComponent.md#getlenspresetname)
- [GetName](ue_ue.CineCameraComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.CineCameraComponent.md#getnumchildrencomponents)
- [GetOuter](ue_ue.CineCameraComponent.md#getouter)
- [GetOwner](ue_ue.CineCameraComponent.md#getowner)
- [GetParentComponents](ue_ue.CineCameraComponent.md#getparentcomponents)
- [GetPhysicsVolume](ue_ue.CineCameraComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.CineCameraComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.CineCameraComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.CineCameraComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.CineCameraComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.CineCameraComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.CineCameraComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.CineCameraComponent.md#getsockettransform)
- [GetUpVector](ue_ue.CineCameraComponent.md#getupvector)
- [GetVerticalFieldOfView](ue_ue.CineCameraComponent.md#getverticalfieldofview)
- [GetWorld](ue_ue.CineCameraComponent.md#getworld)
- [IsActive](ue_ue.CineCameraComponent.md#isactive)
- [IsAnySimulatingPhysics](ue_ue.CineCameraComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.CineCameraComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.CineCameraComponent.md#iscomponenttickenabled)
- [IsSimulatingPhysics](ue_ue.CineCameraComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.CineCameraComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.CineCameraComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.CineCameraComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.CineCameraComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.CineCameraComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.CineCameraComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.CineCameraComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.CineCameraComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.CineCameraComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.CineCameraComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.CineCameraComponent.md#k2_attachtocomponent)
- [K2\_DestroyComponent](ue_ue.CineCameraComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.CineCameraComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.CineCameraComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.CineCameraComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.CineCameraComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.CineCameraComponent.md#k2_getcomponenttoworld)
- [K2\_SetRelativeLocation](ue_ue.CineCameraComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.CineCameraComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.CineCameraComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.CineCameraComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.CineCameraComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.CineCameraComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.CineCameraComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.CineCameraComponent.md#k2_setworldtransform)
- [OnCameraMeshHiddenChanged](ue_ue.CineCameraComponent.md#oncamerameshhiddenchanged)
- [OnRep\_AttachChildren](ue_ue.CineCameraComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.CineCameraComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.CineCameraComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.CineCameraComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.CineCameraComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.CineCameraComponent.md#onrep_visibility)
- [ReceiveBeginPlay](ue_ue.CineCameraComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.CineCameraComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.CineCameraComponent.md#receivetick)
- [RegisterComponent](ue_ue.CineCameraComponent.md#registercomponent)
- [RemoveBlendable](ue_ue.CineCameraComponent.md#removeblendable)
- [RemoveTickPrerequisiteActor](ue_ue.CineCameraComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.CineCameraComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.CineCameraComponent.md#resetrelativetransform)
- [SetAbsolute](ue_ue.CineCameraComponent.md#setabsolute)
- [SetActive](ue_ue.CineCameraComponent.md#setactive)
- [SetAspectRatio](ue_ue.CineCameraComponent.md#setaspectratio)
- [SetAutoActivate](ue_ue.CineCameraComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.CineCameraComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.CineCameraComponent.md#setcomponenttickinterval)
- [SetConstraintAspectRatio](ue_ue.CineCameraComponent.md#setconstraintaspectratio)
- [SetCurrentFocalLength](ue_ue.CineCameraComponent.md#setcurrentfocallength)
- [SetFieldOfView](ue_ue.CineCameraComponent.md#setfieldofview)
- [SetFilmbackPresetByName](ue_ue.CineCameraComponent.md#setfilmbackpresetbyname)
- [SetHiddenInGame](ue_ue.CineCameraComponent.md#sethiddeningame)
- [SetIsReplicated](ue_ue.CineCameraComponent.md#setisreplicated)
- [SetLensPresetByName](ue_ue.CineCameraComponent.md#setlenspresetbyname)
- [SetMobility](ue_ue.CineCameraComponent.md#setmobility)
- [SetOrthoFarClipPlane](ue_ue.CineCameraComponent.md#setorthofarclipplane)
- [SetOrthoNearClipPlane](ue_ue.CineCameraComponent.md#setorthonearclipplane)
- [SetOrthoWidth](ue_ue.CineCameraComponent.md#setorthowidth)
- [SetPostProcessBlendWeight](ue_ue.CineCameraComponent.md#setpostprocessblendweight)
- [SetProjectionMode](ue_ue.CineCameraComponent.md#setprojectionmode)
- [SetRelativeScale3D](ue_ue.CineCameraComponent.md#setrelativescale3d)
- [SetShouldUpdatePhysicsVolume](ue_ue.CineCameraComponent.md#setshouldupdatephysicsvolume)
- [SetTickGroup](ue_ue.CineCameraComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.CineCameraComponent.md#settickablewhenpaused)
- [SetUseFieldOfViewForLOD](ue_ue.CineCameraComponent.md#setusefieldofviewforlod)
- [SetVisibility](ue_ue.CineCameraComponent.md#setvisibility)
- [SetWorldScale3D](ue_ue.CineCameraComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.CineCameraComponent.md#setupattachment)
- [SnapTo](ue_ue.CineCameraComponent.md#snapto)
- [ToggleActive](ue_ue.CineCameraComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.CineCameraComponent.md#togglevisibility)
- [Find](ue_ue.CineCameraComponent.md#find)
- [GetLensPresetsCopy](ue_ue.CineCameraComponent.md#getlenspresetscopy)
- [Load](ue_ue.CineCameraComponent.md#load)
- [StaticClass](ue_ue.CineCameraComponent.md#staticclass)

## Constructors

### constructor

• **new CineCameraComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[CameraComponent](ue_ue.CameraComponent.md).[constructor](ue_ue.CameraComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:27332](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27332)

## Properties

### AspectRatio

• **AspectRatio**: `number`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[AspectRatio](ue_ue.CameraComponent.md#aspectratio)

#### Defined in

[ue/ue.d.ts:8160](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8160)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[AssetUserData](ue_ue.CameraComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L291)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[AttachChildren](ue_ue.CameraComponent.md#attachchildren)

#### Defined in

[ue/ue.d.ts:12873](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12873)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[AttachParent](ue_ue.CameraComponent.md#attachparent)

#### Defined in

[ue/ue.d.ts:12871](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12871)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[AttachSocketName](ue_ue.CameraComponent.md#attachsocketname)

#### Defined in

[ue/ue.d.ts:12872](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12872)

___

### CameraMesh

• **CameraMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[CameraMesh](ue_ue.CameraComponent.md#cameramesh)

#### Defined in

[ue/ue.d.ts:8167](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8167)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[ClientAttachedChildren](ue_ue.CameraComponent.md#clientattachedchildren)

#### Defined in

[ue/ue.d.ts:12874](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12874)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[ComponentTags](ue_ue.CameraComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L290)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[ComponentVelocity](ue_ue.CameraComponent.md#componentvelocity)

#### Defined in

[ue/ue.d.ts:12878](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12878)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[CreationMethod](ue_ue.CameraComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L302)

___

### CurrentAperture

• **CurrentAperture**: `number`

#### Defined in

[ue/ue.d.ts:27338](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27338)

___

### CurrentFocalLength

• **CurrentFocalLength**: `number`

#### Defined in

[ue/ue.d.ts:27337](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27337)

___

### CurrentFocusDistance

• **CurrentFocusDistance**: `number`

#### Defined in

[ue/ue.d.ts:27339](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27339)

___

### CurrentHorizontalFOV

• **CurrentHorizontalFOV**: `number`

#### Defined in

[ue/ue.d.ts:27340](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27340)

___

### DebugFocusPlaneComponent

• **DebugFocusPlaneComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

#### Defined in

[ue/ue.d.ts:27343](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27343)

___

### DebugFocusPlaneMID

• **DebugFocusPlaneMID**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

#### Defined in

[ue/ue.d.ts:27344](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27344)

___

### DefaultFilmbackPreset

• **DefaultFilmbackPreset**: `string`

#### Defined in

[ue/ue.d.ts:27348](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27348)

___

### DefaultFilmbackPresetName

• **DefaultFilmbackPresetName**: `string`

#### Defined in

[ue/ue.d.ts:27347](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27347)

___

### DefaultLensFStop

• **DefaultLensFStop**: `number`

#### Defined in

[ue/ue.d.ts:27351](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27351)

___

### DefaultLensFocalLength

• **DefaultLensFocalLength**: `number`

#### Defined in

[ue/ue.d.ts:27350](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27350)

___

### DefaultLensPresetName

• **DefaultLensPresetName**: `string`

#### Defined in

[ue/ue.d.ts:27349](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27349)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[DetailMode](ue_ue.CameraComponent.md#detailmode)

#### Defined in

[ue/ue.d.ts:12893](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12893)

___

### FieldOfView

• **FieldOfView**: `number`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[FieldOfView](ue_ue.CameraComponent.md#fieldofview)

#### Defined in

[ue/ue.d.ts:8156](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8156)

___

### Filmback

• **Filmback**: [`CameraFilmbackSettings`](ue_ue.CameraFilmbackSettings.md)

#### Defined in

[ue/ue.d.ts:27334](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27334)

___

### FilmbackPresets

• **FilmbackPresets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NamedFilmbackPreset`](ue_ue.NamedFilmbackPreset.md)\>

#### Defined in

[ue/ue.d.ts:27345](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27345)

___

### FilmbackSettings

• **FilmbackSettings**: [`CameraFilmbackSettings`](ue_ue.CameraFilmbackSettings.md)

#### Defined in

[ue/ue.d.ts:27333](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27333)

___

### FocusPlaneVisualizationMaterial

• **FocusPlaneVisualizationMaterial**: [`Material`](ue_ue.Material.md)

#### Defined in

[ue/ue.d.ts:27342](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27342)

___

### FocusPlaneVisualizationMesh

• **FocusPlaneVisualizationMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Defined in

[ue/ue.d.ts:27341](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27341)

___

### FocusSettings

• **FocusSettings**: [`CameraFocusSettings`](ue_ue.CameraFocusSettings.md)

#### Defined in

[ue/ue.d.ts:27336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27336)

___

### LensPresets

• **LensPresets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NamedLensPreset`](ue_ue.NamedLensPreset.md)\>

#### Defined in

[ue/ue.d.ts:27346](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27346)

___

### LensSettings

• **LensSettings**: [`CameraLensSettings`](ue_ue.CameraLensSettings.md)

#### Defined in

[ue/ue.d.ts:27335](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27335)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[Mobility](ue_ue.CameraComponent.md#mobility)

#### Defined in

[ue/ue.d.ts:12892](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12892)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OnComponentActivated](ue_ue.CameraComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OnComponentDeactivated](ue_ue.CameraComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L304)

___

### OrthoFarClipPlane

• **OrthoFarClipPlane**: `number`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OrthoFarClipPlane](ue_ue.CameraComponent.md#orthofarclipplane)

#### Defined in

[ue/ue.d.ts:8159](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8159)

___

### OrthoNearClipPlane

• **OrthoNearClipPlane**: `number`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OrthoNearClipPlane](ue_ue.CameraComponent.md#orthonearclipplane)

#### Defined in

[ue/ue.d.ts:8158](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8158)

___

### OrthoWidth

• **OrthoWidth**: `number`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OrthoWidth](ue_ue.CameraComponent.md#orthowidth)

#### Defined in

[ue/ue.d.ts:8157](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8157)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[PhysicsVolume](ue_ue.CameraComponent.md#physicsvolume)

#### Defined in

[ue/ue.d.ts:12870](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12870)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.CameraComponent.md#physicsvolumechangeddelegate)

#### Defined in

[ue/ue.d.ts:12894](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12894)

___

### PostProcessBlendWeight

• **PostProcessBlendWeight**: `number`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[PostProcessBlendWeight](ue_ue.CameraComponent.md#postprocessblendweight)

#### Defined in

[ue/ue.d.ts:8168](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8168)

___

### PostProcessSettings

• **PostProcessSettings**: [`PostProcessSettings`](ue_ue.PostProcessSettings.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[PostProcessSettings](ue_ue.CameraComponent.md#postprocesssettings)

#### Defined in

[ue/ue.d.ts:8169](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8169)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[PrimaryComponentTick](ue_ue.CameraComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L289)

___

### ProjectionMode

• **ProjectionMode**: [`ECameraProjectionMode`](../enums/ue_ue.ECameraProjectionMode.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[ProjectionMode](ue_ue.CameraComponent.md#projectionmode)

#### Defined in

[ue/ue.d.ts:8166](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8166)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[RelativeLocation](ue_ue.CameraComponent.md#relativelocation)

#### Defined in

[ue/ue.d.ts:12875](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12875)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[RelativeRotation](ue_ue.CameraComponent.md#relativerotation)

#### Defined in

[ue/ue.d.ts:12876](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12876)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[RelativeScale3D](ue_ue.CameraComponent.md#relativescale3d)

#### Defined in

[ue/ue.d.ts:12877](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12877)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[UCSModifiedProperties](ue_ue.CameraComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L305)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[__tid_ActorComponent__](ue_ue.CameraComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L336)

___

### \_\_tid\_CameraComponent\_\_

• **\_\_tid\_CameraComponent\_\_**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[__tid_CameraComponent__](ue_ue.CameraComponent.md#__tid_cameracomponent__)

#### Defined in

[ue/ue.d.ts:8189](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8189)

___

### \_\_tid\_CineCameraComponent\_\_

• **\_\_tid\_CineCameraComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:27365](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27365)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[__tid_Object__](ue_ue.CameraComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[__tid_SceneComponent__](ue_ue.CameraComponent.md#__tid_scenecomponent__)

#### Defined in

[ue/ue.d.ts:12961](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12961)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bAbsoluteLocation](ue_ue.CameraComponent.md#babsolutelocation)

#### Defined in

[ue/ue.d.ts:12880](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12880)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bAbsoluteRotation](ue_ue.CameraComponent.md#babsoluterotation)

#### Defined in

[ue/ue.d.ts:12881](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12881)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bAbsoluteScale](ue_ue.CameraComponent.md#babsolutescale)

#### Defined in

[ue/ue.d.ts:12882](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12882)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bAutoActivate](ue_ue.CameraComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L296)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.CameraComponent.md#bboundschangetriggersstreamingdatarebuild)

#### Defined in

[ue/ue.d.ts:12889](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12889)

___

### bCameraMeshHiddenInGame

• **bCameraMeshHiddenInGame**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bCameraMeshHiddenInGame](ue_ue.CameraComponent.md#bcamerameshhiddeningame)

#### Defined in

[ue/ue.d.ts:8163](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8163)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bCanEverAffectNavigation](ue_ue.CameraComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L299)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bComponentToWorldUpdated](ue_ue.CameraComponent.md#bcomponenttoworldupdated)

#### Defined in

[ue/ue.d.ts:12879](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12879)

___

### bConstrainAspectRatio

• **bConstrainAspectRatio**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bConstrainAspectRatio](ue_ue.CameraComponent.md#bconstrainaspectratio)

#### Defined in

[ue/ue.d.ts:8161](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8161)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bCreatedByConstructionScript](ue_ue.CameraComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bEditableWhenInherited](ue_ue.CameraComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L298)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bHiddenInGame](ue_ue.CameraComponent.md#bhiddeningame)

#### Defined in

[ue/ue.d.ts:12884](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12884)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bInstanceComponent](ue_ue.CameraComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bIsActive](ue_ue.CameraComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bIsEditorOnly](ue_ue.CameraComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bIsVisualizationComponent](ue_ue.CameraComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L301)

___

### bLockToHmd

• **bLockToHmd**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bLockToHmd](ue_ue.CameraComponent.md#blocktohmd)

#### Defined in

[ue/ue.d.ts:8164](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8164)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bNetAddressable](ue_ue.CameraComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L293)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bReplicates](ue_ue.CameraComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L292)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bShouldBeAttached](ue_ue.CameraComponent.md#bshouldbeattached)

#### Defined in

[ue/ue.d.ts:12885](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12885)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.CameraComponent.md#bshouldsnaplocationwhenattached)

#### Defined in

[ue/ue.d.ts:12886](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12886)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.CameraComponent.md#bshouldsnaprotationwhenattached)

#### Defined in

[ue/ue.d.ts:12887](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12887)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.CameraComponent.md#bshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12888](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12888)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bUseAttachParentBound](ue_ue.CameraComponent.md#buseattachparentbound)

#### Defined in

[ue/ue.d.ts:12890](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12890)

___

### bUseControllerViewRotation

• **bUseControllerViewRotation**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bUseControllerViewRotation](ue_ue.CameraComponent.md#busecontrollerviewrotation)

#### Defined in

[ue/ue.d.ts:8170](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8170)

___

### bUseFieldOfViewForLOD

• **bUseFieldOfViewForLOD**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bUseFieldOfViewForLOD](ue_ue.CameraComponent.md#busefieldofviewforlod)

#### Defined in

[ue/ue.d.ts:8162](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8162)

___

### bUsePawnControlRotation

• **bUsePawnControlRotation**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bUsePawnControlRotation](ue_ue.CameraComponent.md#busepawncontrolrotation)

#### Defined in

[ue/ue.d.ts:8165](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8165)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bVisible](ue_ue.CameraComponent.md#bvisible)

#### Defined in

[ue/ue.d.ts:12883](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12883)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bVisualizeComponent](ue_ue.CameraComponent.md#bvisualizecomponent)

#### Defined in

[ue/ue.d.ts:12891](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12891)

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

[CameraComponent](ue_ue.CameraComponent.md).[Activate](ue_ue.CameraComponent.md#activate)

#### Defined in

[ue/ue.d.ts:306](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L306)

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

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[AddOrUpdateBlendable](ue_ue.CameraComponent.md#addorupdateblendable)

#### Defined in

[ue/ue.d.ts:8171](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8171)

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

[CameraComponent](ue_ue.CameraComponent.md).[AddTickPrerequisiteActor](ue_ue.CameraComponent.md#addtickprerequisiteactor)

#### Defined in

[ue/ue.d.ts:307](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L307)

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

[CameraComponent](ue_ue.CameraComponent.md).[AddTickPrerequisiteComponent](ue_ue.CameraComponent.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:308](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L308)

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

[CameraComponent](ue_ue.CameraComponent.md).[ComponentHasTag](ue_ue.CameraComponent.md#componenthastag)

#### Defined in

[ue/ue.d.ts:309](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L309)

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

[CameraComponent](ue_ue.CameraComponent.md).[CreateDefaultSubobject](ue_ue.CameraComponent.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[Deactivate](ue_ue.CameraComponent.md#deactivate)

#### Defined in

[ue/ue.d.ts:310](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L310)

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

[CameraComponent](ue_ue.CameraComponent.md).[DetachFromParent](ue_ue.CameraComponent.md#detachfromparent)

#### Defined in

[ue/ue.d.ts:12895](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12895)

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

[CameraComponent](ue_ue.CameraComponent.md).[DoesSocketExist](ue_ue.CameraComponent.md#doessocketexist)

#### Defined in

[ue/ue.d.ts:12896](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12896)

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

[CameraComponent](ue_ue.CameraComponent.md).[ExecuteUbergraph](ue_ue.CameraComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetAllSocketNames](ue_ue.CameraComponent.md#getallsocketnames)

#### Defined in

[ue/ue.d.ts:12897](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12897)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetAttachParent](ue_ue.CameraComponent.md#getattachparent)

#### Defined in

[ue/ue.d.ts:12898](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12898)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetAttachSocketName](ue_ue.CameraComponent.md#getattachsocketname)

#### Defined in

[ue/ue.d.ts:12899](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12899)

___

### GetCameraView

▸ **GetCameraView**(`DeltaTime`, `DesiredView`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DeltaTime` | `number` |
| `DesiredView` | [`$Ref`](../interfaces/puerts._Ref.md)<[`MinimalViewInfo`](ue_ue.MinimalViewInfo.md)\> |

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetCameraView](ue_ue.CameraComponent.md#getcameraview)

#### Defined in

[ue/ue.d.ts:8172](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8172)

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

[CameraComponent](ue_ue.CameraComponent.md).[GetChildComponent](ue_ue.CameraComponent.md#getchildcomponent)

#### Defined in

[ue/ue.d.ts:12900](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12900)

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

[CameraComponent](ue_ue.CameraComponent.md).[GetChildrenComponents](ue_ue.CameraComponent.md#getchildrencomponents)

#### Defined in

[ue/ue.d.ts:12901](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12901)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetClass](ue_ue.CameraComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetComponentTickInterval](ue_ue.CameraComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L311)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetComponentVelocity](ue_ue.CameraComponent.md#getcomponentvelocity)

#### Defined in

[ue/ue.d.ts:12902](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12902)

___

### GetDefaultFilmbackPresetName

▸ **GetDefaultFilmbackPresetName**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:27352](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27352)

___

### GetFilmbackPresetName

▸ **GetFilmbackPresetName**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:27353](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27353)

___

### GetFilmbackText

▸ **GetFilmbackText**(): `string`

#### Returns

`string`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetFilmbackText](ue_ue.CameraComponent.md#getfilmbacktext)

#### Defined in

[ue/ue.d.ts:8173](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8173)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetForwardVector](ue_ue.CameraComponent.md#getforwardvector)

#### Defined in

[ue/ue.d.ts:12903](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12903)

___

### GetHorizontalFieldOfView

▸ **GetHorizontalFieldOfView**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:27354](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27354)

___

### GetLensPresetName

▸ **GetLensPresetName**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:27355](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27355)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetName](ue_ue.CameraComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetNumChildrenComponents](ue_ue.CameraComponent.md#getnumchildrencomponents)

#### Defined in

[ue/ue.d.ts:12904](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12904)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetOuter](ue_ue.CameraComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetOwner](ue_ue.CameraComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L312)

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

[CameraComponent](ue_ue.CameraComponent.md).[GetParentComponents](ue_ue.CameraComponent.md#getparentcomponents)

#### Defined in

[ue/ue.d.ts:12905](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12905)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetPhysicsVolume](ue_ue.CameraComponent.md#getphysicsvolume)

#### Defined in

[ue/ue.d.ts:12906](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12906)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetRelativeTransform](ue_ue.CameraComponent.md#getrelativetransform)

#### Defined in

[ue/ue.d.ts:12907](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12907)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetRightVector](ue_ue.CameraComponent.md#getrightvector)

#### Defined in

[ue/ue.d.ts:12908](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12908)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.CameraComponent.md#getshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12909](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12909)

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

[CameraComponent](ue_ue.CameraComponent.md).[GetSocketLocation](ue_ue.CameraComponent.md#getsocketlocation)

#### Defined in

[ue/ue.d.ts:12910](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12910)

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

[CameraComponent](ue_ue.CameraComponent.md).[GetSocketQuaternion](ue_ue.CameraComponent.md#getsocketquaternion)

#### Defined in

[ue/ue.d.ts:12911](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12911)

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

[CameraComponent](ue_ue.CameraComponent.md).[GetSocketRotation](ue_ue.CameraComponent.md#getsocketrotation)

#### Defined in

[ue/ue.d.ts:12912](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12912)

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

[CameraComponent](ue_ue.CameraComponent.md).[GetSocketTransform](ue_ue.CameraComponent.md#getsockettransform)

#### Defined in

[ue/ue.d.ts:12913](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12913)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetUpVector](ue_ue.CameraComponent.md#getupvector)

#### Defined in

[ue/ue.d.ts:12914](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12914)

___

### GetVerticalFieldOfView

▸ **GetVerticalFieldOfView**(): `number`

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:27356](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27356)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetWorld](ue_ue.CameraComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[IsActive](ue_ue.CameraComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L313)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[IsAnySimulatingPhysics](ue_ue.CameraComponent.md#isanysimulatingphysics)

#### Defined in

[ue/ue.d.ts:12915](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12915)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[IsBeingDestroyed](ue_ue.CameraComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[IsComponentTickEnabled](ue_ue.CameraComponent.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L315)

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

[CameraComponent](ue_ue.CameraComponent.md).[IsSimulatingPhysics](ue_ue.CameraComponent.md#issimulatingphysics)

#### Defined in

[ue/ue.d.ts:12916](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12916)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[IsVisible](ue_ue.CameraComponent.md#isvisible)

#### Defined in

[ue/ue.d.ts:12917](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12917)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_AddLocalOffset](ue_ue.CameraComponent.md#k2_addlocaloffset)

#### Defined in

[ue/ue.d.ts:12918](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12918)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_AddLocalRotation](ue_ue.CameraComponent.md#k2_addlocalrotation)

#### Defined in

[ue/ue.d.ts:12919](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12919)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_AddLocalTransform](ue_ue.CameraComponent.md#k2_addlocaltransform)

#### Defined in

[ue/ue.d.ts:12920](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12920)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_AddRelativeLocation](ue_ue.CameraComponent.md#k2_addrelativelocation)

#### Defined in

[ue/ue.d.ts:12921](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12921)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_AddRelativeRotation](ue_ue.CameraComponent.md#k2_addrelativerotation)

#### Defined in

[ue/ue.d.ts:12922](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12922)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_AddWorldOffset](ue_ue.CameraComponent.md#k2_addworldoffset)

#### Defined in

[ue/ue.d.ts:12923](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12923)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_AddWorldRotation](ue_ue.CameraComponent.md#k2_addworldrotation)

#### Defined in

[ue/ue.d.ts:12924](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12924)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_AddWorldTransform](ue_ue.CameraComponent.md#k2_addworldtransform)

#### Defined in

[ue/ue.d.ts:12925](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12925)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_AttachTo](ue_ue.CameraComponent.md#k2_attachto)

#### Defined in

[ue/ue.d.ts:12926](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12926)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_AttachToComponent](ue_ue.CameraComponent.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:12927](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12927)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_DestroyComponent](ue_ue.CameraComponent.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L316)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_DetachFromComponent](ue_ue.CameraComponent.md#k2_detachfromcomponent)

#### Defined in

[ue/ue.d.ts:12928](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12928)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[K2_GetComponentLocation](ue_ue.CameraComponent.md#k2_getcomponentlocation)

#### Defined in

[ue/ue.d.ts:12929](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12929)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[K2_GetComponentRotation](ue_ue.CameraComponent.md#k2_getcomponentrotation)

#### Defined in

[ue/ue.d.ts:12930](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12930)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[K2_GetComponentScale](ue_ue.CameraComponent.md#k2_getcomponentscale)

#### Defined in

[ue/ue.d.ts:12931](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12931)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[K2_GetComponentToWorld](ue_ue.CameraComponent.md#k2_getcomponenttoworld)

#### Defined in

[ue/ue.d.ts:12932](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12932)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_SetRelativeLocation](ue_ue.CameraComponent.md#k2_setrelativelocation)

#### Defined in

[ue/ue.d.ts:12933](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12933)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.CameraComponent.md#k2_setrelativelocationandrotation)

#### Defined in

[ue/ue.d.ts:12934](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12934)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_SetRelativeRotation](ue_ue.CameraComponent.md#k2_setrelativerotation)

#### Defined in

[ue/ue.d.ts:12935](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12935)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_SetRelativeTransform](ue_ue.CameraComponent.md#k2_setrelativetransform)

#### Defined in

[ue/ue.d.ts:12936](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12936)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_SetWorldLocation](ue_ue.CameraComponent.md#k2_setworldlocation)

#### Defined in

[ue/ue.d.ts:12937](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12937)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.CameraComponent.md#k2_setworldlocationandrotation)

#### Defined in

[ue/ue.d.ts:12938](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12938)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_SetWorldRotation](ue_ue.CameraComponent.md#k2_setworldrotation)

#### Defined in

[ue/ue.d.ts:12939](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12939)

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

[CameraComponent](ue_ue.CameraComponent.md).[K2_SetWorldTransform](ue_ue.CameraComponent.md#k2_setworldtransform)

#### Defined in

[ue/ue.d.ts:12940](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12940)

___

### OnCameraMeshHiddenChanged

▸ **OnCameraMeshHiddenChanged**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OnCameraMeshHiddenChanged](ue_ue.CameraComponent.md#oncamerameshhiddenchanged)

#### Defined in

[ue/ue.d.ts:8174](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8174)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OnRep_AttachChildren](ue_ue.CameraComponent.md#onrep_attachchildren)

#### Defined in

[ue/ue.d.ts:12941](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12941)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OnRep_AttachParent](ue_ue.CameraComponent.md#onrep_attachparent)

#### Defined in

[ue/ue.d.ts:12942](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12942)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OnRep_AttachSocketName](ue_ue.CameraComponent.md#onrep_attachsocketname)

#### Defined in

[ue/ue.d.ts:12943](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12943)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OnRep_IsActive](ue_ue.CameraComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L317)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OnRep_Transform](ue_ue.CameraComponent.md#onrep_transform)

#### Defined in

[ue/ue.d.ts:12944](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12944)

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

[CameraComponent](ue_ue.CameraComponent.md).[OnRep_Visibility](ue_ue.CameraComponent.md#onrep_visibility)

#### Defined in

[ue/ue.d.ts:12945](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12945)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[ReceiveBeginPlay](ue_ue.CameraComponent.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:318](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L318)

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

[CameraComponent](ue_ue.CameraComponent.md).[ReceiveEndPlay](ue_ue.CameraComponent.md#receiveendplay)

#### Defined in

[ue/ue.d.ts:319](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L319)

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

[CameraComponent](ue_ue.CameraComponent.md).[ReceiveTick](ue_ue.CameraComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[RegisterComponent](ue_ue.CameraComponent.md#registercomponent)

#### Defined in

[ue/ue.d.ts:321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L321)

___

### RemoveBlendable

▸ **RemoveBlendable**(`InBlendableObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InBlendableObject` | [`BlendableInterface`](ue_ue.BlendableInterface.md) |

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[RemoveBlendable](ue_ue.CameraComponent.md#removeblendable)

#### Defined in

[ue/ue.d.ts:8175](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8175)

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

[CameraComponent](ue_ue.CameraComponent.md).[RemoveTickPrerequisiteActor](ue_ue.CameraComponent.md#removetickprerequisiteactor)

#### Defined in

[ue/ue.d.ts:322](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L322)

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

[CameraComponent](ue_ue.CameraComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.CameraComponent.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L323)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[ResetRelativeTransform](ue_ue.CameraComponent.md#resetrelativetransform)

#### Defined in

[ue/ue.d.ts:12946](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12946)

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

[CameraComponent](ue_ue.CameraComponent.md).[SetAbsolute](ue_ue.CameraComponent.md#setabsolute)

#### Defined in

[ue/ue.d.ts:12947](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12947)

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

[CameraComponent](ue_ue.CameraComponent.md).[SetActive](ue_ue.CameraComponent.md#setactive)

#### Defined in

[ue/ue.d.ts:324](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L324)

___

### SetAspectRatio

▸ **SetAspectRatio**(`InAspectRatio`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAspectRatio` | `number` |

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[SetAspectRatio](ue_ue.CameraComponent.md#setaspectratio)

#### Defined in

[ue/ue.d.ts:8176](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8176)

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

[CameraComponent](ue_ue.CameraComponent.md).[SetAutoActivate](ue_ue.CameraComponent.md#setautoactivate)

#### Defined in

[ue/ue.d.ts:325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L325)

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

[CameraComponent](ue_ue.CameraComponent.md).[SetComponentTickEnabled](ue_ue.CameraComponent.md#setcomponenttickenabled)

#### Defined in

[ue/ue.d.ts:326](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L326)

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

[CameraComponent](ue_ue.CameraComponent.md).[SetComponentTickInterval](ue_ue.CameraComponent.md#setcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L327)

___

### SetConstraintAspectRatio

▸ **SetConstraintAspectRatio**(`bInConstrainAspectRatio`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInConstrainAspectRatio` | `boolean` |

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[SetConstraintAspectRatio](ue_ue.CameraComponent.md#setconstraintaspectratio)

#### Defined in

[ue/ue.d.ts:8177](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8177)

___

### SetCurrentFocalLength

▸ **SetCurrentFocalLength**(`InFocalLength`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFocalLength` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:27357](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27357)

___

### SetFieldOfView

▸ **SetFieldOfView**(`InFieldOfView`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFieldOfView` | `number` |

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[SetFieldOfView](ue_ue.CameraComponent.md#setfieldofview)

#### Defined in

[ue/ue.d.ts:8178](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8178)

___

### SetFilmbackPresetByName

▸ **SetFilmbackPresetByName**(`InPresetName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPresetName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:27358](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27358)

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

[CameraComponent](ue_ue.CameraComponent.md).[SetHiddenInGame](ue_ue.CameraComponent.md#sethiddeningame)

#### Defined in

[ue/ue.d.ts:12948](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12948)

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

[CameraComponent](ue_ue.CameraComponent.md).[SetIsReplicated](ue_ue.CameraComponent.md#setisreplicated)

#### Defined in

[ue/ue.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L328)

___

### SetLensPresetByName

▸ **SetLensPresetByName**(`InPresetName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPresetName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:27359](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27359)

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

[CameraComponent](ue_ue.CameraComponent.md).[SetMobility](ue_ue.CameraComponent.md#setmobility)

#### Defined in

[ue/ue.d.ts:12949](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12949)

___

### SetOrthoFarClipPlane

▸ **SetOrthoFarClipPlane**(`InOrthoFarClipPlane`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InOrthoFarClipPlane` | `number` |

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[SetOrthoFarClipPlane](ue_ue.CameraComponent.md#setorthofarclipplane)

#### Defined in

[ue/ue.d.ts:8179](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8179)

___

### SetOrthoNearClipPlane

▸ **SetOrthoNearClipPlane**(`InOrthoNearClipPlane`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InOrthoNearClipPlane` | `number` |

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[SetOrthoNearClipPlane](ue_ue.CameraComponent.md#setorthonearclipplane)

#### Defined in

[ue/ue.d.ts:8180](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8180)

___

### SetOrthoWidth

▸ **SetOrthoWidth**(`InOrthoWidth`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InOrthoWidth` | `number` |

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[SetOrthoWidth](ue_ue.CameraComponent.md#setorthowidth)

#### Defined in

[ue/ue.d.ts:8181](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8181)

___

### SetPostProcessBlendWeight

▸ **SetPostProcessBlendWeight**(`InPostProcessBlendWeight`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPostProcessBlendWeight` | `number` |

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[SetPostProcessBlendWeight](ue_ue.CameraComponent.md#setpostprocessblendweight)

#### Defined in

[ue/ue.d.ts:8182](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8182)

___

### SetProjectionMode

▸ **SetProjectionMode**(`InProjectionMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InProjectionMode` | [`ECameraProjectionMode`](../enums/ue_ue.ECameraProjectionMode.md) |

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[SetProjectionMode](ue_ue.CameraComponent.md#setprojectionmode)

#### Defined in

[ue/ue.d.ts:8183](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8183)

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

[CameraComponent](ue_ue.CameraComponent.md).[SetRelativeScale3D](ue_ue.CameraComponent.md#setrelativescale3d)

#### Defined in

[ue/ue.d.ts:12950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12950)

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

[CameraComponent](ue_ue.CameraComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.CameraComponent.md#setshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12951](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12951)

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

[CameraComponent](ue_ue.CameraComponent.md).[SetTickGroup](ue_ue.CameraComponent.md#settickgroup)

#### Defined in

[ue/ue.d.ts:330](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L330)

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

[CameraComponent](ue_ue.CameraComponent.md).[SetTickableWhenPaused](ue_ue.CameraComponent.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L329)

___

### SetUseFieldOfViewForLOD

▸ **SetUseFieldOfViewForLOD**(`bInUseFieldOfViewForLOD`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInUseFieldOfViewForLOD` | `boolean` |

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[SetUseFieldOfViewForLOD](ue_ue.CameraComponent.md#setusefieldofviewforlod)

#### Defined in

[ue/ue.d.ts:8184](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L8184)

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

[CameraComponent](ue_ue.CameraComponent.md).[SetVisibility](ue_ue.CameraComponent.md#setvisibility)

#### Defined in

[ue/ue.d.ts:12953](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12953)

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

[CameraComponent](ue_ue.CameraComponent.md).[SetWorldScale3D](ue_ue.CameraComponent.md#setworldscale3d)

#### Defined in

[ue/ue.d.ts:12954](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12954)

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

[CameraComponent](ue_ue.CameraComponent.md).[SetupAttachment](ue_ue.CameraComponent.md#setupattachment)

#### Defined in

[ue/ue.d.ts:12952](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12952)

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

[CameraComponent](ue_ue.CameraComponent.md).[SnapTo](ue_ue.CameraComponent.md#snapto)

#### Defined in

[ue/ue.d.ts:12955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12955)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[ToggleActive](ue_ue.CameraComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L331)

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

[CameraComponent](ue_ue.CameraComponent.md).[ToggleVisibility](ue_ue.CameraComponent.md#togglevisibility)

#### Defined in

[ue/ue.d.ts:12956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12956)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`CineCameraComponent`](ue_ue.CineCameraComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`CineCameraComponent`](ue_ue.CineCameraComponent.md)

#### Overrides

[CameraComponent](ue_ue.CameraComponent.md).[Find](ue_ue.CameraComponent.md#find)

#### Defined in

[ue/ue.d.ts:27362](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27362)

___

### GetLensPresetsCopy

▸ `Static` **GetLensPresetsCopy**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NamedLensPreset`](ue_ue.NamedLensPreset.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`NamedLensPreset`](ue_ue.NamedLensPreset.md)\>

#### Defined in

[ue/ue.d.ts:27360](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27360)

___

### Load

▸ `Static` **Load**(`InName`): [`CineCameraComponent`](ue_ue.CineCameraComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`CineCameraComponent`](ue_ue.CineCameraComponent.md)

#### Overrides

[CameraComponent](ue_ue.CameraComponent.md).[Load](ue_ue.CameraComponent.md#load)

#### Defined in

[ue/ue.d.ts:27363](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27363)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[CameraComponent](ue_ue.CameraComponent.md).[StaticClass](ue_ue.CameraComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:27361](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L27361)