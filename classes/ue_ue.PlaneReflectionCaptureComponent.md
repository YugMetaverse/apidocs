[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PlaneReflectionCaptureComponent

# Class: PlaneReflectionCaptureComponent

[ue/ue](../modules/ue_ue.md).PlaneReflectionCaptureComponent

## Hierarchy

- [`ReflectionCaptureComponent`](ue_ue.ReflectionCaptureComponent.md)

  ↳ **`PlaneReflectionCaptureComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.PlaneReflectionCaptureComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.PlaneReflectionCaptureComponent.md#assetuserdata)
- [AttachChildren](ue_ue.PlaneReflectionCaptureComponent.md#attachchildren)
- [AttachParent](ue_ue.PlaneReflectionCaptureComponent.md#attachparent)
- [AttachSocketName](ue_ue.PlaneReflectionCaptureComponent.md#attachsocketname)
- [Brightness](ue_ue.PlaneReflectionCaptureComponent.md#brightness)
- [CaptureOffset](ue_ue.PlaneReflectionCaptureComponent.md#captureoffset)
- [CaptureOffsetComponent](ue_ue.PlaneReflectionCaptureComponent.md#captureoffsetcomponent)
- [ClientAttachedChildren](ue_ue.PlaneReflectionCaptureComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.PlaneReflectionCaptureComponent.md#componenttags)
- [ComponentVelocity](ue_ue.PlaneReflectionCaptureComponent.md#componentvelocity)
- [CreationMethod](ue_ue.PlaneReflectionCaptureComponent.md#creationmethod)
- [Cubemap](ue_ue.PlaneReflectionCaptureComponent.md#cubemap)
- [DetailMode](ue_ue.PlaneReflectionCaptureComponent.md#detailmode)
- [InfluenceRadiusScale](ue_ue.PlaneReflectionCaptureComponent.md#influenceradiusscale)
- [MapBuildDataId](ue_ue.PlaneReflectionCaptureComponent.md#mapbuilddataid)
- [Mobility](ue_ue.PlaneReflectionCaptureComponent.md#mobility)
- [OnComponentActivated](ue_ue.PlaneReflectionCaptureComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.PlaneReflectionCaptureComponent.md#oncomponentdeactivated)
- [PhysicsVolume](ue_ue.PlaneReflectionCaptureComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.PlaneReflectionCaptureComponent.md#physicsvolumechangeddelegate)
- [PreviewCaptureBox](ue_ue.PlaneReflectionCaptureComponent.md#previewcapturebox)
- [PreviewInfluenceRadius](ue_ue.PlaneReflectionCaptureComponent.md#previewinfluenceradius)
- [PrimaryComponentTick](ue_ue.PlaneReflectionCaptureComponent.md#primarycomponenttick)
- [ReflectionSourceType](ue_ue.PlaneReflectionCaptureComponent.md#reflectionsourcetype)
- [RelativeLocation](ue_ue.PlaneReflectionCaptureComponent.md#relativelocation)
- [RelativeRotation](ue_ue.PlaneReflectionCaptureComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.PlaneReflectionCaptureComponent.md#relativescale3d)
- [SourceCubemapAngle](ue_ue.PlaneReflectionCaptureComponent.md#sourcecubemapangle)
- [UCSModifiedProperties](ue_ue.PlaneReflectionCaptureComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.PlaneReflectionCaptureComponent.md#__tid_actorcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.PlaneReflectionCaptureComponent.md#__tid_object__)
- [\_\_tid\_PlaneReflectionCaptureComponent\_\_](ue_ue.PlaneReflectionCaptureComponent.md#__tid_planereflectioncapturecomponent__)
- [\_\_tid\_ReflectionCaptureComponent\_\_](ue_ue.PlaneReflectionCaptureComponent.md#__tid_reflectioncapturecomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.PlaneReflectionCaptureComponent.md#__tid_scenecomponent__)
- [bAbsoluteLocation](ue_ue.PlaneReflectionCaptureComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.PlaneReflectionCaptureComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.PlaneReflectionCaptureComponent.md#babsolutescale)
- [bAutoActivate](ue_ue.PlaneReflectionCaptureComponent.md#bautoactivate)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.PlaneReflectionCaptureComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.PlaneReflectionCaptureComponent.md#bcaneveraffectnavigation)
- [bComponentToWorldUpdated](ue_ue.PlaneReflectionCaptureComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.PlaneReflectionCaptureComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.PlaneReflectionCaptureComponent.md#beditablewheninherited)
- [bHiddenInGame](ue_ue.PlaneReflectionCaptureComponent.md#bhiddeningame)
- [bInstanceComponent](ue_ue.PlaneReflectionCaptureComponent.md#binstancecomponent)
- [bIsActive](ue_ue.PlaneReflectionCaptureComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.PlaneReflectionCaptureComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.PlaneReflectionCaptureComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.PlaneReflectionCaptureComponent.md#bnetaddressable)
- [bReplicates](ue_ue.PlaneReflectionCaptureComponent.md#breplicates)
- [bShouldBeAttached](ue_ue.PlaneReflectionCaptureComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.PlaneReflectionCaptureComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.PlaneReflectionCaptureComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.PlaneReflectionCaptureComponent.md#bshouldupdatephysicsvolume)
- [bUseAttachParentBound](ue_ue.PlaneReflectionCaptureComponent.md#buseattachparentbound)
- [bVisible](ue_ue.PlaneReflectionCaptureComponent.md#bvisible)
- [bVisualizeComponent](ue_ue.PlaneReflectionCaptureComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.PlaneReflectionCaptureComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.PlaneReflectionCaptureComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PlaneReflectionCaptureComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.PlaneReflectionCaptureComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.PlaneReflectionCaptureComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.PlaneReflectionCaptureComponent.md#deactivate)
- [DetachFromParent](ue_ue.PlaneReflectionCaptureComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.PlaneReflectionCaptureComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.PlaneReflectionCaptureComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.PlaneReflectionCaptureComponent.md#getallsocketnames)
- [GetAttachParent](ue_ue.PlaneReflectionCaptureComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.PlaneReflectionCaptureComponent.md#getattachsocketname)
- [GetChildComponent](ue_ue.PlaneReflectionCaptureComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.PlaneReflectionCaptureComponent.md#getchildrencomponents)
- [GetClass](ue_ue.PlaneReflectionCaptureComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.PlaneReflectionCaptureComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.PlaneReflectionCaptureComponent.md#getcomponentvelocity)
- [GetForwardVector](ue_ue.PlaneReflectionCaptureComponent.md#getforwardvector)
- [GetName](ue_ue.PlaneReflectionCaptureComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.PlaneReflectionCaptureComponent.md#getnumchildrencomponents)
- [GetOuter](ue_ue.PlaneReflectionCaptureComponent.md#getouter)
- [GetOwner](ue_ue.PlaneReflectionCaptureComponent.md#getowner)
- [GetParentComponents](ue_ue.PlaneReflectionCaptureComponent.md#getparentcomponents)
- [GetPhysicsVolume](ue_ue.PlaneReflectionCaptureComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.PlaneReflectionCaptureComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.PlaneReflectionCaptureComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.PlaneReflectionCaptureComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.PlaneReflectionCaptureComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.PlaneReflectionCaptureComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.PlaneReflectionCaptureComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.PlaneReflectionCaptureComponent.md#getsockettransform)
- [GetUpVector](ue_ue.PlaneReflectionCaptureComponent.md#getupvector)
- [GetWorld](ue_ue.PlaneReflectionCaptureComponent.md#getworld)
- [IsActive](ue_ue.PlaneReflectionCaptureComponent.md#isactive)
- [IsAnySimulatingPhysics](ue_ue.PlaneReflectionCaptureComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.PlaneReflectionCaptureComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.PlaneReflectionCaptureComponent.md#iscomponenttickenabled)
- [IsSimulatingPhysics](ue_ue.PlaneReflectionCaptureComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.PlaneReflectionCaptureComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.PlaneReflectionCaptureComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.PlaneReflectionCaptureComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.PlaneReflectionCaptureComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.PlaneReflectionCaptureComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.PlaneReflectionCaptureComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.PlaneReflectionCaptureComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.PlaneReflectionCaptureComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.PlaneReflectionCaptureComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.PlaneReflectionCaptureComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.PlaneReflectionCaptureComponent.md#k2_attachtocomponent)
- [K2\_DestroyComponent](ue_ue.PlaneReflectionCaptureComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.PlaneReflectionCaptureComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.PlaneReflectionCaptureComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.PlaneReflectionCaptureComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.PlaneReflectionCaptureComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.PlaneReflectionCaptureComponent.md#k2_getcomponenttoworld)
- [K2\_SetRelativeLocation](ue_ue.PlaneReflectionCaptureComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.PlaneReflectionCaptureComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.PlaneReflectionCaptureComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.PlaneReflectionCaptureComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.PlaneReflectionCaptureComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.PlaneReflectionCaptureComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.PlaneReflectionCaptureComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.PlaneReflectionCaptureComponent.md#k2_setworldtransform)
- [OnRep\_AttachChildren](ue_ue.PlaneReflectionCaptureComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.PlaneReflectionCaptureComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.PlaneReflectionCaptureComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.PlaneReflectionCaptureComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.PlaneReflectionCaptureComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.PlaneReflectionCaptureComponent.md#onrep_visibility)
- [ReceiveBeginPlay](ue_ue.PlaneReflectionCaptureComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.PlaneReflectionCaptureComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.PlaneReflectionCaptureComponent.md#receivetick)
- [RegisterComponent](ue_ue.PlaneReflectionCaptureComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.PlaneReflectionCaptureComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PlaneReflectionCaptureComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.PlaneReflectionCaptureComponent.md#resetrelativetransform)
- [SetAbsolute](ue_ue.PlaneReflectionCaptureComponent.md#setabsolute)
- [SetActive](ue_ue.PlaneReflectionCaptureComponent.md#setactive)
- [SetAutoActivate](ue_ue.PlaneReflectionCaptureComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.PlaneReflectionCaptureComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.PlaneReflectionCaptureComponent.md#setcomponenttickinterval)
- [SetHiddenInGame](ue_ue.PlaneReflectionCaptureComponent.md#sethiddeningame)
- [SetIsReplicated](ue_ue.PlaneReflectionCaptureComponent.md#setisreplicated)
- [SetMobility](ue_ue.PlaneReflectionCaptureComponent.md#setmobility)
- [SetRelativeScale3D](ue_ue.PlaneReflectionCaptureComponent.md#setrelativescale3d)
- [SetShouldUpdatePhysicsVolume](ue_ue.PlaneReflectionCaptureComponent.md#setshouldupdatephysicsvolume)
- [SetTickGroup](ue_ue.PlaneReflectionCaptureComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PlaneReflectionCaptureComponent.md#settickablewhenpaused)
- [SetVisibility](ue_ue.PlaneReflectionCaptureComponent.md#setvisibility)
- [SetWorldScale3D](ue_ue.PlaneReflectionCaptureComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.PlaneReflectionCaptureComponent.md#setupattachment)
- [SnapTo](ue_ue.PlaneReflectionCaptureComponent.md#snapto)
- [ToggleActive](ue_ue.PlaneReflectionCaptureComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.PlaneReflectionCaptureComponent.md#togglevisibility)
- [Find](ue_ue.PlaneReflectionCaptureComponent.md#find)
- [Load](ue_ue.PlaneReflectionCaptureComponent.md#load)
- [StaticClass](ue_ue.PlaneReflectionCaptureComponent.md#staticclass)

## Constructors

### constructor

• **new PlaneReflectionCaptureComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[constructor](ue_ue.ReflectionCaptureComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:58001](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58001)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[AssetUserData](ue_ue.ReflectionCaptureComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L291)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[AttachChildren](ue_ue.ReflectionCaptureComponent.md#attachchildren)

#### Defined in

[ue/ue.d.ts:12873](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12873)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[AttachParent](ue_ue.ReflectionCaptureComponent.md#attachparent)

#### Defined in

[ue/ue.d.ts:12871](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12871)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[AttachSocketName](ue_ue.ReflectionCaptureComponent.md#attachsocketname)

#### Defined in

[ue/ue.d.ts:12872](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12872)

___

### Brightness

• **Brightness**: `number`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[Brightness](ue_ue.ReflectionCaptureComponent.md#brightness)

#### Defined in

[ue/ue.d.ts:24536](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24536)

___

### CaptureOffset

• **CaptureOffset**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[CaptureOffset](ue_ue.ReflectionCaptureComponent.md#captureoffset)

#### Defined in

[ue/ue.d.ts:24537](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24537)

___

### CaptureOffsetComponent

• **CaptureOffsetComponent**: [`BillboardComponent`](ue_ue.BillboardComponent.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[CaptureOffsetComponent](ue_ue.ReflectionCaptureComponent.md#captureoffsetcomponent)

#### Defined in

[ue/ue.d.ts:24532](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24532)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[ClientAttachedChildren](ue_ue.ReflectionCaptureComponent.md#clientattachedchildren)

#### Defined in

[ue/ue.d.ts:12874](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12874)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[ComponentTags](ue_ue.ReflectionCaptureComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L290)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[ComponentVelocity](ue_ue.ReflectionCaptureComponent.md#componentvelocity)

#### Defined in

[ue/ue.d.ts:12878](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12878)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[CreationMethod](ue_ue.ReflectionCaptureComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L302)

___

### Cubemap

• **Cubemap**: [`TextureCube`](ue_ue.TextureCube.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[Cubemap](ue_ue.ReflectionCaptureComponent.md#cubemap)

#### Defined in

[ue/ue.d.ts:24534](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24534)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[DetailMode](ue_ue.ReflectionCaptureComponent.md#detailmode)

#### Defined in

[ue/ue.d.ts:12893](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12893)

___

### InfluenceRadiusScale

• **InfluenceRadiusScale**: `number`

#### Defined in

[ue/ue.d.ts:58002](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58002)

___

### MapBuildDataId

• **MapBuildDataId**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[MapBuildDataId](ue_ue.ReflectionCaptureComponent.md#mapbuilddataid)

#### Defined in

[ue/ue.d.ts:24538](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24538)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[Mobility](ue_ue.ReflectionCaptureComponent.md#mobility)

#### Defined in

[ue/ue.d.ts:12892](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12892)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[OnComponentActivated](ue_ue.ReflectionCaptureComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[OnComponentDeactivated](ue_ue.ReflectionCaptureComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L304)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[PhysicsVolume](ue_ue.ReflectionCaptureComponent.md#physicsvolume)

#### Defined in

[ue/ue.d.ts:12870](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12870)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.ReflectionCaptureComponent.md#physicsvolumechangeddelegate)

#### Defined in

[ue/ue.d.ts:12894](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12894)

___

### PreviewCaptureBox

• **PreviewCaptureBox**: [`BoxComponent`](ue_ue.BoxComponent.md)

#### Defined in

[ue/ue.d.ts:58004](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58004)

___

### PreviewInfluenceRadius

• **PreviewInfluenceRadius**: [`DrawSphereComponent`](ue_ue.DrawSphereComponent.md)

#### Defined in

[ue/ue.d.ts:58003](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58003)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[PrimaryComponentTick](ue_ue.ReflectionCaptureComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L289)

___

### ReflectionSourceType

• **ReflectionSourceType**: [`EReflectionSourceType`](../enums/ue_ue.EReflectionSourceType.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[ReflectionSourceType](ue_ue.ReflectionCaptureComponent.md#reflectionsourcetype)

#### Defined in

[ue/ue.d.ts:24533](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24533)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[RelativeLocation](ue_ue.ReflectionCaptureComponent.md#relativelocation)

#### Defined in

[ue/ue.d.ts:12875](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12875)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[RelativeRotation](ue_ue.ReflectionCaptureComponent.md#relativerotation)

#### Defined in

[ue/ue.d.ts:12876](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12876)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[RelativeScale3D](ue_ue.ReflectionCaptureComponent.md#relativescale3d)

#### Defined in

[ue/ue.d.ts:12877](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12877)

___

### SourceCubemapAngle

• **SourceCubemapAngle**: `number`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[SourceCubemapAngle](ue_ue.ReflectionCaptureComponent.md#sourcecubemapangle)

#### Defined in

[ue/ue.d.ts:24535](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24535)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[UCSModifiedProperties](ue_ue.ReflectionCaptureComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L305)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[__tid_ActorComponent__](ue_ue.ReflectionCaptureComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L336)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[__tid_Object__](ue_ue.ReflectionCaptureComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_PlaneReflectionCaptureComponent\_\_

• **\_\_tid\_PlaneReflectionCaptureComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:58009](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58009)

___

### \_\_tid\_ReflectionCaptureComponent\_\_

• **\_\_tid\_ReflectionCaptureComponent\_\_**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[__tid_ReflectionCaptureComponent__](ue_ue.ReflectionCaptureComponent.md#__tid_reflectioncapturecomponent__)

#### Defined in

[ue/ue.d.ts:24543](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L24543)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[__tid_SceneComponent__](ue_ue.ReflectionCaptureComponent.md#__tid_scenecomponent__)

#### Defined in

[ue/ue.d.ts:12961](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12961)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bAbsoluteLocation](ue_ue.ReflectionCaptureComponent.md#babsolutelocation)

#### Defined in

[ue/ue.d.ts:12880](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12880)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bAbsoluteRotation](ue_ue.ReflectionCaptureComponent.md#babsoluterotation)

#### Defined in

[ue/ue.d.ts:12881](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12881)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bAbsoluteScale](ue_ue.ReflectionCaptureComponent.md#babsolutescale)

#### Defined in

[ue/ue.d.ts:12882](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12882)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bAutoActivate](ue_ue.ReflectionCaptureComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L296)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.ReflectionCaptureComponent.md#bboundschangetriggersstreamingdatarebuild)

#### Defined in

[ue/ue.d.ts:12889](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12889)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bCanEverAffectNavigation](ue_ue.ReflectionCaptureComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L299)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bComponentToWorldUpdated](ue_ue.ReflectionCaptureComponent.md#bcomponenttoworldupdated)

#### Defined in

[ue/ue.d.ts:12879](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12879)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bCreatedByConstructionScript](ue_ue.ReflectionCaptureComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bEditableWhenInherited](ue_ue.ReflectionCaptureComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L298)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bHiddenInGame](ue_ue.ReflectionCaptureComponent.md#bhiddeningame)

#### Defined in

[ue/ue.d.ts:12884](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12884)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bInstanceComponent](ue_ue.ReflectionCaptureComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bIsActive](ue_ue.ReflectionCaptureComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bIsEditorOnly](ue_ue.ReflectionCaptureComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bIsVisualizationComponent](ue_ue.ReflectionCaptureComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bNetAddressable](ue_ue.ReflectionCaptureComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L293)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bReplicates](ue_ue.ReflectionCaptureComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L292)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bShouldBeAttached](ue_ue.ReflectionCaptureComponent.md#bshouldbeattached)

#### Defined in

[ue/ue.d.ts:12885](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12885)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.ReflectionCaptureComponent.md#bshouldsnaplocationwhenattached)

#### Defined in

[ue/ue.d.ts:12886](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12886)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.ReflectionCaptureComponent.md#bshouldsnaprotationwhenattached)

#### Defined in

[ue/ue.d.ts:12887](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12887)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.ReflectionCaptureComponent.md#bshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12888](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12888)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bUseAttachParentBound](ue_ue.ReflectionCaptureComponent.md#buseattachparentbound)

#### Defined in

[ue/ue.d.ts:12890](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12890)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bVisible](ue_ue.ReflectionCaptureComponent.md#bvisible)

#### Defined in

[ue/ue.d.ts:12883](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12883)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[bVisualizeComponent](ue_ue.ReflectionCaptureComponent.md#bvisualizecomponent)

#### Defined in

[ue/ue.d.ts:12891](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12891)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[Activate](ue_ue.ReflectionCaptureComponent.md#activate)

#### Defined in

[ue/ue.d.ts:306](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L306)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[AddTickPrerequisiteActor](ue_ue.ReflectionCaptureComponent.md#addtickprerequisiteactor)

#### Defined in

[ue/ue.d.ts:307](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L307)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[AddTickPrerequisiteComponent](ue_ue.ReflectionCaptureComponent.md#addtickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:308](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L308)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[ComponentHasTag](ue_ue.ReflectionCaptureComponent.md#componenthastag)

#### Defined in

[ue/ue.d.ts:309](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L309)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[CreateDefaultSubobject](ue_ue.ReflectionCaptureComponent.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[Deactivate](ue_ue.ReflectionCaptureComponent.md#deactivate)

#### Defined in

[ue/ue.d.ts:310](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L310)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[DetachFromParent](ue_ue.ReflectionCaptureComponent.md#detachfromparent)

#### Defined in

[ue/ue.d.ts:12895](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12895)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[DoesSocketExist](ue_ue.ReflectionCaptureComponent.md#doessocketexist)

#### Defined in

[ue/ue.d.ts:12896](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12896)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[ExecuteUbergraph](ue_ue.ReflectionCaptureComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetAllSocketNames](ue_ue.ReflectionCaptureComponent.md#getallsocketnames)

#### Defined in

[ue/ue.d.ts:12897](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12897)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetAttachParent](ue_ue.ReflectionCaptureComponent.md#getattachparent)

#### Defined in

[ue/ue.d.ts:12898](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12898)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetAttachSocketName](ue_ue.ReflectionCaptureComponent.md#getattachsocketname)

#### Defined in

[ue/ue.d.ts:12899](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12899)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetChildComponent](ue_ue.ReflectionCaptureComponent.md#getchildcomponent)

#### Defined in

[ue/ue.d.ts:12900](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12900)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetChildrenComponents](ue_ue.ReflectionCaptureComponent.md#getchildrencomponents)

#### Defined in

[ue/ue.d.ts:12901](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12901)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetClass](ue_ue.ReflectionCaptureComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetComponentTickInterval](ue_ue.ReflectionCaptureComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L311)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetComponentVelocity](ue_ue.ReflectionCaptureComponent.md#getcomponentvelocity)

#### Defined in

[ue/ue.d.ts:12902](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12902)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetForwardVector](ue_ue.ReflectionCaptureComponent.md#getforwardvector)

#### Defined in

[ue/ue.d.ts:12903](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12903)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetName](ue_ue.ReflectionCaptureComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetNumChildrenComponents](ue_ue.ReflectionCaptureComponent.md#getnumchildrencomponents)

#### Defined in

[ue/ue.d.ts:12904](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12904)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetOuter](ue_ue.ReflectionCaptureComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetOwner](ue_ue.ReflectionCaptureComponent.md#getowner)

#### Defined in

[ue/ue.d.ts:312](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L312)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetParentComponents](ue_ue.ReflectionCaptureComponent.md#getparentcomponents)

#### Defined in

[ue/ue.d.ts:12905](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12905)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetPhysicsVolume](ue_ue.ReflectionCaptureComponent.md#getphysicsvolume)

#### Defined in

[ue/ue.d.ts:12906](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12906)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetRelativeTransform](ue_ue.ReflectionCaptureComponent.md#getrelativetransform)

#### Defined in

[ue/ue.d.ts:12907](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12907)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetRightVector](ue_ue.ReflectionCaptureComponent.md#getrightvector)

#### Defined in

[ue/ue.d.ts:12908](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12908)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.ReflectionCaptureComponent.md#getshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12909](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12909)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetSocketLocation](ue_ue.ReflectionCaptureComponent.md#getsocketlocation)

#### Defined in

[ue/ue.d.ts:12910](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12910)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetSocketQuaternion](ue_ue.ReflectionCaptureComponent.md#getsocketquaternion)

#### Defined in

[ue/ue.d.ts:12911](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12911)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetSocketRotation](ue_ue.ReflectionCaptureComponent.md#getsocketrotation)

#### Defined in

[ue/ue.d.ts:12912](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12912)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetSocketTransform](ue_ue.ReflectionCaptureComponent.md#getsockettransform)

#### Defined in

[ue/ue.d.ts:12913](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12913)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetUpVector](ue_ue.ReflectionCaptureComponent.md#getupvector)

#### Defined in

[ue/ue.d.ts:12914](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12914)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[GetWorld](ue_ue.ReflectionCaptureComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[IsActive](ue_ue.ReflectionCaptureComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L313)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[IsAnySimulatingPhysics](ue_ue.ReflectionCaptureComponent.md#isanysimulatingphysics)

#### Defined in

[ue/ue.d.ts:12915](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12915)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[IsBeingDestroyed](ue_ue.ReflectionCaptureComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[IsComponentTickEnabled](ue_ue.ReflectionCaptureComponent.md#iscomponenttickenabled)

#### Defined in

[ue/ue.d.ts:315](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L315)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[IsSimulatingPhysics](ue_ue.ReflectionCaptureComponent.md#issimulatingphysics)

#### Defined in

[ue/ue.d.ts:12916](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12916)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[IsVisible](ue_ue.ReflectionCaptureComponent.md#isvisible)

#### Defined in

[ue/ue.d.ts:12917](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12917)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_AddLocalOffset](ue_ue.ReflectionCaptureComponent.md#k2_addlocaloffset)

#### Defined in

[ue/ue.d.ts:12918](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12918)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_AddLocalRotation](ue_ue.ReflectionCaptureComponent.md#k2_addlocalrotation)

#### Defined in

[ue/ue.d.ts:12919](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12919)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_AddLocalTransform](ue_ue.ReflectionCaptureComponent.md#k2_addlocaltransform)

#### Defined in

[ue/ue.d.ts:12920](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12920)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_AddRelativeLocation](ue_ue.ReflectionCaptureComponent.md#k2_addrelativelocation)

#### Defined in

[ue/ue.d.ts:12921](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12921)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_AddRelativeRotation](ue_ue.ReflectionCaptureComponent.md#k2_addrelativerotation)

#### Defined in

[ue/ue.d.ts:12922](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12922)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_AddWorldOffset](ue_ue.ReflectionCaptureComponent.md#k2_addworldoffset)

#### Defined in

[ue/ue.d.ts:12923](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12923)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_AddWorldRotation](ue_ue.ReflectionCaptureComponent.md#k2_addworldrotation)

#### Defined in

[ue/ue.d.ts:12924](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12924)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_AddWorldTransform](ue_ue.ReflectionCaptureComponent.md#k2_addworldtransform)

#### Defined in

[ue/ue.d.ts:12925](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12925)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_AttachTo](ue_ue.ReflectionCaptureComponent.md#k2_attachto)

#### Defined in

[ue/ue.d.ts:12926](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12926)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_AttachToComponent](ue_ue.ReflectionCaptureComponent.md#k2_attachtocomponent)

#### Defined in

[ue/ue.d.ts:12927](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12927)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_DestroyComponent](ue_ue.ReflectionCaptureComponent.md#k2_destroycomponent)

#### Defined in

[ue/ue.d.ts:316](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L316)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_DetachFromComponent](ue_ue.ReflectionCaptureComponent.md#k2_detachfromcomponent)

#### Defined in

[ue/ue.d.ts:12928](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12928)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_GetComponentLocation](ue_ue.ReflectionCaptureComponent.md#k2_getcomponentlocation)

#### Defined in

[ue/ue.d.ts:12929](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12929)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_GetComponentRotation](ue_ue.ReflectionCaptureComponent.md#k2_getcomponentrotation)

#### Defined in

[ue/ue.d.ts:12930](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12930)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_GetComponentScale](ue_ue.ReflectionCaptureComponent.md#k2_getcomponentscale)

#### Defined in

[ue/ue.d.ts:12931](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12931)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_GetComponentToWorld](ue_ue.ReflectionCaptureComponent.md#k2_getcomponenttoworld)

#### Defined in

[ue/ue.d.ts:12932](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12932)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_SetRelativeLocation](ue_ue.ReflectionCaptureComponent.md#k2_setrelativelocation)

#### Defined in

[ue/ue.d.ts:12933](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12933)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.ReflectionCaptureComponent.md#k2_setrelativelocationandrotation)

#### Defined in

[ue/ue.d.ts:12934](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12934)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_SetRelativeRotation](ue_ue.ReflectionCaptureComponent.md#k2_setrelativerotation)

#### Defined in

[ue/ue.d.ts:12935](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12935)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_SetRelativeTransform](ue_ue.ReflectionCaptureComponent.md#k2_setrelativetransform)

#### Defined in

[ue/ue.d.ts:12936](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12936)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_SetWorldLocation](ue_ue.ReflectionCaptureComponent.md#k2_setworldlocation)

#### Defined in

[ue/ue.d.ts:12937](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12937)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.ReflectionCaptureComponent.md#k2_setworldlocationandrotation)

#### Defined in

[ue/ue.d.ts:12938](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12938)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_SetWorldRotation](ue_ue.ReflectionCaptureComponent.md#k2_setworldrotation)

#### Defined in

[ue/ue.d.ts:12939](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12939)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[K2_SetWorldTransform](ue_ue.ReflectionCaptureComponent.md#k2_setworldtransform)

#### Defined in

[ue/ue.d.ts:12940](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12940)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[OnRep_AttachChildren](ue_ue.ReflectionCaptureComponent.md#onrep_attachchildren)

#### Defined in

[ue/ue.d.ts:12941](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12941)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[OnRep_AttachParent](ue_ue.ReflectionCaptureComponent.md#onrep_attachparent)

#### Defined in

[ue/ue.d.ts:12942](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12942)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[OnRep_AttachSocketName](ue_ue.ReflectionCaptureComponent.md#onrep_attachsocketname)

#### Defined in

[ue/ue.d.ts:12943](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12943)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[OnRep_IsActive](ue_ue.ReflectionCaptureComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L317)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[OnRep_Transform](ue_ue.ReflectionCaptureComponent.md#onrep_transform)

#### Defined in

[ue/ue.d.ts:12944](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12944)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[OnRep_Visibility](ue_ue.ReflectionCaptureComponent.md#onrep_visibility)

#### Defined in

[ue/ue.d.ts:12945](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12945)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[ReceiveBeginPlay](ue_ue.ReflectionCaptureComponent.md#receivebeginplay)

#### Defined in

[ue/ue.d.ts:318](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L318)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[ReceiveEndPlay](ue_ue.ReflectionCaptureComponent.md#receiveendplay)

#### Defined in

[ue/ue.d.ts:319](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L319)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[ReceiveTick](ue_ue.ReflectionCaptureComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[RegisterComponent](ue_ue.ReflectionCaptureComponent.md#registercomponent)

#### Defined in

[ue/ue.d.ts:321](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L321)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[RemoveTickPrerequisiteActor](ue_ue.ReflectionCaptureComponent.md#removetickprerequisiteactor)

#### Defined in

[ue/ue.d.ts:322](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L322)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.ReflectionCaptureComponent.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L323)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[ResetRelativeTransform](ue_ue.ReflectionCaptureComponent.md#resetrelativetransform)

#### Defined in

[ue/ue.d.ts:12946](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12946)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[SetAbsolute](ue_ue.ReflectionCaptureComponent.md#setabsolute)

#### Defined in

[ue/ue.d.ts:12947](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12947)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[SetActive](ue_ue.ReflectionCaptureComponent.md#setactive)

#### Defined in

[ue/ue.d.ts:324](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L324)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[SetAutoActivate](ue_ue.ReflectionCaptureComponent.md#setautoactivate)

#### Defined in

[ue/ue.d.ts:325](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L325)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[SetComponentTickEnabled](ue_ue.ReflectionCaptureComponent.md#setcomponenttickenabled)

#### Defined in

[ue/ue.d.ts:326](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L326)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[SetComponentTickInterval](ue_ue.ReflectionCaptureComponent.md#setcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L327)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[SetHiddenInGame](ue_ue.ReflectionCaptureComponent.md#sethiddeningame)

#### Defined in

[ue/ue.d.ts:12948](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12948)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[SetIsReplicated](ue_ue.ReflectionCaptureComponent.md#setisreplicated)

#### Defined in

[ue/ue.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L328)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[SetMobility](ue_ue.ReflectionCaptureComponent.md#setmobility)

#### Defined in

[ue/ue.d.ts:12949](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12949)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[SetRelativeScale3D](ue_ue.ReflectionCaptureComponent.md#setrelativescale3d)

#### Defined in

[ue/ue.d.ts:12950](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12950)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.ReflectionCaptureComponent.md#setshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12951](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12951)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[SetTickGroup](ue_ue.ReflectionCaptureComponent.md#settickgroup)

#### Defined in

[ue/ue.d.ts:330](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L330)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[SetTickableWhenPaused](ue_ue.ReflectionCaptureComponent.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L329)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[SetVisibility](ue_ue.ReflectionCaptureComponent.md#setvisibility)

#### Defined in

[ue/ue.d.ts:12953](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12953)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[SetWorldScale3D](ue_ue.ReflectionCaptureComponent.md#setworldscale3d)

#### Defined in

[ue/ue.d.ts:12954](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12954)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[SetupAttachment](ue_ue.ReflectionCaptureComponent.md#setupattachment)

#### Defined in

[ue/ue.d.ts:12952](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12952)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[SnapTo](ue_ue.ReflectionCaptureComponent.md#snapto)

#### Defined in

[ue/ue.d.ts:12955](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12955)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[ToggleActive](ue_ue.ReflectionCaptureComponent.md#toggleactive)

#### Defined in

[ue/ue.d.ts:331](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L331)

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

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[ToggleVisibility](ue_ue.ReflectionCaptureComponent.md#togglevisibility)

#### Defined in

[ue/ue.d.ts:12956](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12956)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PlaneReflectionCaptureComponent`](ue_ue.PlaneReflectionCaptureComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PlaneReflectionCaptureComponent`](ue_ue.PlaneReflectionCaptureComponent.md)

#### Overrides

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[Find](ue_ue.ReflectionCaptureComponent.md#find)

#### Defined in

[ue/ue.d.ts:58006](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58006)

___

### Load

▸ `Static` **Load**(`InName`): [`PlaneReflectionCaptureComponent`](ue_ue.PlaneReflectionCaptureComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PlaneReflectionCaptureComponent`](ue_ue.PlaneReflectionCaptureComponent.md)

#### Overrides

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[Load](ue_ue.ReflectionCaptureComponent.md#load)

#### Defined in

[ue/ue.d.ts:58007](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58007)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ReflectionCaptureComponent](ue_ue.ReflectionCaptureComponent.md).[StaticClass](ue_ue.ReflectionCaptureComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:58005](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L58005)
