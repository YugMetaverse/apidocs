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

## Properties

### AspectRatio

• **AspectRatio**: `number`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[AspectRatio](ue_ue.CameraComponent.md#aspectratio)

___

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[AssetUserData](ue_ue.CameraComponent.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[AttachChildren](ue_ue.CameraComponent.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[AttachParent](ue_ue.CameraComponent.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[AttachSocketName](ue_ue.CameraComponent.md#attachsocketname)

___

### CameraMesh

• **CameraMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[CameraMesh](ue_ue.CameraComponent.md#cameramesh)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[ClientAttachedChildren](ue_ue.CameraComponent.md#clientattachedchildren)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[ComponentTags](ue_ue.CameraComponent.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[ComponentVelocity](ue_ue.CameraComponent.md#componentvelocity)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[CreationMethod](ue_ue.CameraComponent.md#creationmethod)

___

### CurrentAperture

• **CurrentAperture**: `number`

___

### CurrentFocalLength

• **CurrentFocalLength**: `number`

___

### CurrentFocusDistance

• **CurrentFocusDistance**: `number`

___

### CurrentHorizontalFOV

• **CurrentHorizontalFOV**: `number`

___

### DebugFocusPlaneComponent

• **DebugFocusPlaneComponent**: [`StaticMeshComponent`](ue_ue.StaticMeshComponent.md)

___

### DebugFocusPlaneMID

• **DebugFocusPlaneMID**: [`MaterialInstanceDynamic`](ue_ue.MaterialInstanceDynamic.md)

___

### DefaultFilmbackPreset

• **DefaultFilmbackPreset**: `string`

___

### DefaultFilmbackPresetName

• **DefaultFilmbackPresetName**: `string`

___

### DefaultLensFStop

• **DefaultLensFStop**: `number`

___

### DefaultLensFocalLength

• **DefaultLensFocalLength**: `number`

___

### DefaultLensPresetName

• **DefaultLensPresetName**: `string`

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[DetailMode](ue_ue.CameraComponent.md#detailmode)

___

### FieldOfView

• **FieldOfView**: `number`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[FieldOfView](ue_ue.CameraComponent.md#fieldofview)

___

### Filmback

• **Filmback**: [`CameraFilmbackSettings`](ue_ue.CameraFilmbackSettings.md)

___

### FilmbackPresets

• **FilmbackPresets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NamedFilmbackPreset`](ue_ue.NamedFilmbackPreset.md)\>

___

### FilmbackSettings

• **FilmbackSettings**: [`CameraFilmbackSettings`](ue_ue.CameraFilmbackSettings.md)

___

### FocusPlaneVisualizationMaterial

• **FocusPlaneVisualizationMaterial**: [`Material`](ue_ue.Material.md)

___

### FocusPlaneVisualizationMesh

• **FocusPlaneVisualizationMesh**: [`StaticMesh`](ue_ue.StaticMesh.md)

___

### FocusSettings

• **FocusSettings**: [`CameraFocusSettings`](ue_ue.CameraFocusSettings.md)

___

### LensPresets

• **LensPresets**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NamedLensPreset`](ue_ue.NamedLensPreset.md)\>

___

### LensSettings

• **LensSettings**: [`CameraLensSettings`](ue_ue.CameraLensSettings.md)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[Mobility](ue_ue.CameraComponent.md#mobility)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OnComponentActivated](ue_ue.CameraComponent.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OnComponentDeactivated](ue_ue.CameraComponent.md#oncomponentdeactivated)

___

### OrthoFarClipPlane

• **OrthoFarClipPlane**: `number`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OrthoFarClipPlane](ue_ue.CameraComponent.md#orthofarclipplane)

___

### OrthoNearClipPlane

• **OrthoNearClipPlane**: `number`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OrthoNearClipPlane](ue_ue.CameraComponent.md#orthonearclipplane)

___

### OrthoWidth

• **OrthoWidth**: `number`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OrthoWidth](ue_ue.CameraComponent.md#orthowidth)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[PhysicsVolume](ue_ue.CameraComponent.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.CameraComponent.md#physicsvolumechangeddelegate)

___

### PostProcessBlendWeight

• **PostProcessBlendWeight**: `number`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[PostProcessBlendWeight](ue_ue.CameraComponent.md#postprocessblendweight)

___

### PostProcessSettings

• **PostProcessSettings**: [`PostProcessSettings`](ue_ue.PostProcessSettings.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[PostProcessSettings](ue_ue.CameraComponent.md#postprocesssettings)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[PrimaryComponentTick](ue_ue.CameraComponent.md#primarycomponenttick)

___

### ProjectionMode

• **ProjectionMode**: [`ECameraProjectionMode`](../enums/ue_ue.ECameraProjectionMode.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[ProjectionMode](ue_ue.CameraComponent.md#projectionmode)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[RelativeLocation](ue_ue.CameraComponent.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[RelativeRotation](ue_ue.CameraComponent.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[RelativeScale3D](ue_ue.CameraComponent.md#relativescale3d)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[UCSModifiedProperties](ue_ue.CameraComponent.md#ucsmodifiedproperties)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[__tid_ActorComponent__](ue_ue.CameraComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_CameraComponent\_\_

• **\_\_tid\_CameraComponent\_\_**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[__tid_CameraComponent__](ue_ue.CameraComponent.md#__tid_cameracomponent__)

___

### \_\_tid\_CineCameraComponent\_\_

• **\_\_tid\_CineCameraComponent\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[__tid_Object__](ue_ue.CameraComponent.md#__tid_object__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[__tid_SceneComponent__](ue_ue.CameraComponent.md#__tid_scenecomponent__)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bAbsoluteLocation](ue_ue.CameraComponent.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bAbsoluteRotation](ue_ue.CameraComponent.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bAbsoluteScale](ue_ue.CameraComponent.md#babsolutescale)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bAutoActivate](ue_ue.CameraComponent.md#bautoactivate)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.CameraComponent.md#bboundschangetriggersstreamingdatarebuild)

___

### bCameraMeshHiddenInGame

• **bCameraMeshHiddenInGame**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bCameraMeshHiddenInGame](ue_ue.CameraComponent.md#bcamerameshhiddeningame)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bCanEverAffectNavigation](ue_ue.CameraComponent.md#bcaneveraffectnavigation)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bComponentToWorldUpdated](ue_ue.CameraComponent.md#bcomponenttoworldupdated)

___

### bConstrainAspectRatio

• **bConstrainAspectRatio**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bConstrainAspectRatio](ue_ue.CameraComponent.md#bconstrainaspectratio)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bCreatedByConstructionScript](ue_ue.CameraComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bEditableWhenInherited](ue_ue.CameraComponent.md#beditablewheninherited)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bHiddenInGame](ue_ue.CameraComponent.md#bhiddeningame)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bInstanceComponent](ue_ue.CameraComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bIsActive](ue_ue.CameraComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bIsEditorOnly](ue_ue.CameraComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bIsVisualizationComponent](ue_ue.CameraComponent.md#bisvisualizationcomponent)

___

### bLockToHmd

• **bLockToHmd**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bLockToHmd](ue_ue.CameraComponent.md#blocktohmd)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bNetAddressable](ue_ue.CameraComponent.md#bnetaddressable)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bReplicates](ue_ue.CameraComponent.md#breplicates)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bShouldBeAttached](ue_ue.CameraComponent.md#bshouldbeattached)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.CameraComponent.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.CameraComponent.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.CameraComponent.md#bshouldupdatephysicsvolume)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bUseAttachParentBound](ue_ue.CameraComponent.md#buseattachparentbound)

___

### bUseControllerViewRotation

• **bUseControllerViewRotation**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bUseControllerViewRotation](ue_ue.CameraComponent.md#busecontrollerviewrotation)

___

### bUseFieldOfViewForLOD

• **bUseFieldOfViewForLOD**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bUseFieldOfViewForLOD](ue_ue.CameraComponent.md#busefieldofviewforlod)

___

### bUsePawnControlRotation

• **bUsePawnControlRotation**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bUsePawnControlRotation](ue_ue.CameraComponent.md#busepawncontrolrotation)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bVisible](ue_ue.CameraComponent.md#bvisible)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[bVisualizeComponent](ue_ue.CameraComponent.md#bvisualizecomponent)

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

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[Deactivate](ue_ue.CameraComponent.md#deactivate)

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

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetAllSocketNames](ue_ue.CameraComponent.md#getallsocketnames)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetAttachParent](ue_ue.CameraComponent.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetAttachSocketName](ue_ue.CameraComponent.md#getattachsocketname)

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetClass](ue_ue.CameraComponent.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetComponentTickInterval](ue_ue.CameraComponent.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetComponentVelocity](ue_ue.CameraComponent.md#getcomponentvelocity)

___

### GetDefaultFilmbackPresetName

▸ **GetDefaultFilmbackPresetName**(): `string`

#### Returns

`string`

___

### GetFilmbackPresetName

▸ **GetFilmbackPresetName**(): `string`

#### Returns

`string`

___

### GetFilmbackText

▸ **GetFilmbackText**(): `string`

#### Returns

`string`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetFilmbackText](ue_ue.CameraComponent.md#getfilmbacktext)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetForwardVector](ue_ue.CameraComponent.md#getforwardvector)

___

### GetHorizontalFieldOfView

▸ **GetHorizontalFieldOfView**(): `number`

#### Returns

`number`

___

### GetLensPresetName

▸ **GetLensPresetName**(): `string`

#### Returns

`string`

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetName](ue_ue.CameraComponent.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetNumChildrenComponents](ue_ue.CameraComponent.md#getnumchildrencomponents)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetOuter](ue_ue.CameraComponent.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetOwner](ue_ue.CameraComponent.md#getowner)

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

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetPhysicsVolume](ue_ue.CameraComponent.md#getphysicsvolume)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetRelativeTransform](ue_ue.CameraComponent.md#getrelativetransform)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetRightVector](ue_ue.CameraComponent.md#getrightvector)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.CameraComponent.md#getshouldupdatephysicsvolume)

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

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetUpVector](ue_ue.CameraComponent.md#getupvector)

___

### GetVerticalFieldOfView

▸ **GetVerticalFieldOfView**(): `number`

#### Returns

`number`

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[GetWorld](ue_ue.CameraComponent.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[IsActive](ue_ue.CameraComponent.md#isactive)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[IsAnySimulatingPhysics](ue_ue.CameraComponent.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[IsBeingDestroyed](ue_ue.CameraComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[IsComponentTickEnabled](ue_ue.CameraComponent.md#iscomponenttickenabled)

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

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[IsVisible](ue_ue.CameraComponent.md#isvisible)

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

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[K2_GetComponentLocation](ue_ue.CameraComponent.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[K2_GetComponentRotation](ue_ue.CameraComponent.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[K2_GetComponentScale](ue_ue.CameraComponent.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[K2_GetComponentToWorld](ue_ue.CameraComponent.md#k2_getcomponenttoworld)

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

___

### OnCameraMeshHiddenChanged

▸ **OnCameraMeshHiddenChanged**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OnCameraMeshHiddenChanged](ue_ue.CameraComponent.md#oncamerameshhiddenchanged)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OnRep_AttachChildren](ue_ue.CameraComponent.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OnRep_AttachParent](ue_ue.CameraComponent.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OnRep_AttachSocketName](ue_ue.CameraComponent.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OnRep_IsActive](ue_ue.CameraComponent.md#onrep_isactive)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[OnRep_Transform](ue_ue.CameraComponent.md#onrep_transform)

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

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[ReceiveBeginPlay](ue_ue.CameraComponent.md#receivebeginplay)

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

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[RegisterComponent](ue_ue.CameraComponent.md#registercomponent)

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

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[ResetRelativeTransform](ue_ue.CameraComponent.md#resetrelativetransform)

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

___

### SetCurrentFocalLength

▸ **SetCurrentFocalLength**(`InFocalLength`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFocalLength` | `number` |

#### Returns

`void`

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

___

### SetFilmbackPresetByName

▸ **SetFilmbackPresetByName**(`InPresetName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPresetName` | `string` |

#### Returns

`void`

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

___

### SetLensPresetByName

▸ **SetLensPresetByName**(`InPresetName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InPresetName` | `string` |

#### Returns

`void`

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

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[CameraComponent](ue_ue.CameraComponent.md).[ToggleActive](ue_ue.CameraComponent.md#toggleactive)

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

___

### GetLensPresetsCopy

▸ `Static` **GetLensPresetsCopy**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NamedLensPreset`](ue_ue.NamedLensPreset.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`NamedLensPreset`](ue_ue.NamedLensPreset.md)\>

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[CameraComponent](ue_ue.CameraComponent.md).[StaticClass](ue_ue.CameraComponent.md#staticclass)
