[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SkyLightComponent

# Class: SkyLightComponent

[ue/ue](../modules/ue_ue.md).SkyLightComponent

## Hierarchy

- [`LightComponentBase`](ue_ue.LightComponentBase.md)

  ↳ **`SkyLightComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.SkyLightComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.SkyLightComponent.md#assetuserdata)
- [AttachChildren](ue_ue.SkyLightComponent.md#attachchildren)
- [AttachParent](ue_ue.SkyLightComponent.md#attachparent)
- [AttachSocketName](ue_ue.SkyLightComponent.md#attachsocketname)
- [BlendDestinationCubemap](ue_ue.SkyLightComponent.md#blenddestinationcubemap)
- [Brightness](ue_ue.SkyLightComponent.md#brightness)
- [CastDynamicShadows](ue_ue.SkyLightComponent.md#castdynamicshadows)
- [CastShadows](ue_ue.SkyLightComponent.md#castshadows)
- [CastStaticShadows](ue_ue.SkyLightComponent.md#caststaticshadows)
- [ClientAttachedChildren](ue_ue.SkyLightComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.SkyLightComponent.md#componenttags)
- [ComponentVelocity](ue_ue.SkyLightComponent.md#componentvelocity)
- [Contrast](ue_ue.SkyLightComponent.md#contrast)
- [CreationMethod](ue_ue.SkyLightComponent.md#creationmethod)
- [Cubemap](ue_ue.SkyLightComponent.md#cubemap)
- [CubemapResolution](ue_ue.SkyLightComponent.md#cubemapresolution)
- [DetailMode](ue_ue.SkyLightComponent.md#detailmode)
- [DynamicEditorTexture](ue_ue.SkyLightComponent.md#dynamiceditortexture)
- [DynamicEditorTextureScale](ue_ue.SkyLightComponent.md#dynamiceditortexturescale)
- [IndirectLightingIntensity](ue_ue.SkyLightComponent.md#indirectlightingintensity)
- [Intensity](ue_ue.SkyLightComponent.md#intensity)
- [LightColor](ue_ue.SkyLightComponent.md#lightcolor)
- [LightGuid](ue_ue.SkyLightComponent.md#lightguid)
- [LowerHemisphereColor](ue_ue.SkyLightComponent.md#lowerhemispherecolor)
- [MinOcclusion](ue_ue.SkyLightComponent.md#minocclusion)
- [Mobility](ue_ue.SkyLightComponent.md#mobility)
- [OcclusionCombineMode](ue_ue.SkyLightComponent.md#occlusioncombinemode)
- [OcclusionExponent](ue_ue.SkyLightComponent.md#occlusionexponent)
- [OcclusionMaxDistance](ue_ue.SkyLightComponent.md#occlusionmaxdistance)
- [OcclusionTint](ue_ue.SkyLightComponent.md#occlusiontint)
- [OnComponentActivated](ue_ue.SkyLightComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.SkyLightComponent.md#oncomponentdeactivated)
- [PhysicsVolume](ue_ue.SkyLightComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.SkyLightComponent.md#physicsvolumechangeddelegate)
- [PrimaryComponentTick](ue_ue.SkyLightComponent.md#primarycomponenttick)
- [RelativeLocation](ue_ue.SkyLightComponent.md#relativelocation)
- [RelativeRotation](ue_ue.SkyLightComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.SkyLightComponent.md#relativescale3d)
- [SamplesPerPixel](ue_ue.SkyLightComponent.md#samplesperpixel)
- [SkyDistanceThreshold](ue_ue.SkyLightComponent.md#skydistancethreshold)
- [SourceCubemapAngle](ue_ue.SkyLightComponent.md#sourcecubemapangle)
- [SourceType](ue_ue.SkyLightComponent.md#sourcetype)
- [StaticEditorTexture](ue_ue.SkyLightComponent.md#staticeditortexture)
- [StaticEditorTextureScale](ue_ue.SkyLightComponent.md#staticeditortexturescale)
- [UCSModifiedProperties](ue_ue.SkyLightComponent.md#ucsmodifiedproperties)
- [VolumetricScatteringIntensity](ue_ue.SkyLightComponent.md#volumetricscatteringintensity)
- [\_\_tid\_ActorComponent\_\_](ue_ue.SkyLightComponent.md#__tid_actorcomponent__)
- [\_\_tid\_LightComponentBase\_\_](ue_ue.SkyLightComponent.md#__tid_lightcomponentbase__)
- [\_\_tid\_Object\_\_](ue_ue.SkyLightComponent.md#__tid_object__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.SkyLightComponent.md#__tid_scenecomponent__)
- [\_\_tid\_SkyLightComponent\_\_](ue_ue.SkyLightComponent.md#__tid_skylightcomponent__)
- [bAbsoluteLocation](ue_ue.SkyLightComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.SkyLightComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.SkyLightComponent.md#babsolutescale)
- [bAffectGlobalIllumination](ue_ue.SkyLightComponent.md#baffectglobalillumination)
- [bAffectReflection](ue_ue.SkyLightComponent.md#baffectreflection)
- [bAffectTranslucentLighting](ue_ue.SkyLightComponent.md#baffecttranslucentlighting)
- [bAffectsWorld](ue_ue.SkyLightComponent.md#baffectsworld)
- [bAutoActivate](ue_ue.SkyLightComponent.md#bautoactivate)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.SkyLightComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.SkyLightComponent.md#bcaneveraffectnavigation)
- [bCaptureEmissiveOnly](ue_ue.SkyLightComponent.md#bcaptureemissiveonly)
- [bCastDeepShadow](ue_ue.SkyLightComponent.md#bcastdeepshadow)
- [bCastRaytracedShadow](ue_ue.SkyLightComponent.md#bcastraytracedshadow)
- [bCastVolumetricShadow](ue_ue.SkyLightComponent.md#bcastvolumetricshadow)
- [bComponentToWorldUpdated](ue_ue.SkyLightComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.SkyLightComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.SkyLightComponent.md#beditablewheninherited)
- [bHiddenInGame](ue_ue.SkyLightComponent.md#bhiddeningame)
- [bInstanceComponent](ue_ue.SkyLightComponent.md#binstancecomponent)
- [bIsActive](ue_ue.SkyLightComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.SkyLightComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.SkyLightComponent.md#bisvisualizationcomponent)
- [bLowerHemisphereIsBlack](ue_ue.SkyLightComponent.md#blowerhemisphereisblack)
- [bNetAddressable](ue_ue.SkyLightComponent.md#bnetaddressable)
- [bReplicates](ue_ue.SkyLightComponent.md#breplicates)
- [bShouldBeAttached](ue_ue.SkyLightComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.SkyLightComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.SkyLightComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.SkyLightComponent.md#bshouldupdatephysicsvolume)
- [bTransmission](ue_ue.SkyLightComponent.md#btransmission)
- [bUseAttachParentBound](ue_ue.SkyLightComponent.md#buseattachparentbound)
- [bVisible](ue_ue.SkyLightComponent.md#bvisible)
- [bVisualizeComponent](ue_ue.SkyLightComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.SkyLightComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.SkyLightComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.SkyLightComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.SkyLightComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.SkyLightComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.SkyLightComponent.md#deactivate)
- [DetachFromParent](ue_ue.SkyLightComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.SkyLightComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.SkyLightComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.SkyLightComponent.md#getallsocketnames)
- [GetAttachParent](ue_ue.SkyLightComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.SkyLightComponent.md#getattachsocketname)
- [GetChildComponent](ue_ue.SkyLightComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.SkyLightComponent.md#getchildrencomponents)
- [GetClass](ue_ue.SkyLightComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.SkyLightComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.SkyLightComponent.md#getcomponentvelocity)
- [GetForwardVector](ue_ue.SkyLightComponent.md#getforwardvector)
- [GetLightColor](ue_ue.SkyLightComponent.md#getlightcolor)
- [GetName](ue_ue.SkyLightComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.SkyLightComponent.md#getnumchildrencomponents)
- [GetOuter](ue_ue.SkyLightComponent.md#getouter)
- [GetOwner](ue_ue.SkyLightComponent.md#getowner)
- [GetParentComponents](ue_ue.SkyLightComponent.md#getparentcomponents)
- [GetPhysicsVolume](ue_ue.SkyLightComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.SkyLightComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.SkyLightComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.SkyLightComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.SkyLightComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.SkyLightComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.SkyLightComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.SkyLightComponent.md#getsockettransform)
- [GetUpVector](ue_ue.SkyLightComponent.md#getupvector)
- [GetWorld](ue_ue.SkyLightComponent.md#getworld)
- [IsActive](ue_ue.SkyLightComponent.md#isactive)
- [IsAnySimulatingPhysics](ue_ue.SkyLightComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.SkyLightComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.SkyLightComponent.md#iscomponenttickenabled)
- [IsSimulatingPhysics](ue_ue.SkyLightComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.SkyLightComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.SkyLightComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.SkyLightComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.SkyLightComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.SkyLightComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.SkyLightComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.SkyLightComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.SkyLightComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.SkyLightComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.SkyLightComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.SkyLightComponent.md#k2_attachtocomponent)
- [K2\_DestroyComponent](ue_ue.SkyLightComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.SkyLightComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.SkyLightComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.SkyLightComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.SkyLightComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.SkyLightComponent.md#k2_getcomponenttoworld)
- [K2\_SetRelativeLocation](ue_ue.SkyLightComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.SkyLightComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.SkyLightComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.SkyLightComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.SkyLightComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.SkyLightComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.SkyLightComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.SkyLightComponent.md#k2_setworldtransform)
- [OnRep\_AttachChildren](ue_ue.SkyLightComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.SkyLightComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.SkyLightComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.SkyLightComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.SkyLightComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.SkyLightComponent.md#onrep_visibility)
- [RecaptureSky](ue_ue.SkyLightComponent.md#recapturesky)
- [ReceiveBeginPlay](ue_ue.SkyLightComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.SkyLightComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.SkyLightComponent.md#receivetick)
- [RegisterComponent](ue_ue.SkyLightComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.SkyLightComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.SkyLightComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.SkyLightComponent.md#resetrelativetransform)
- [SetAbsolute](ue_ue.SkyLightComponent.md#setabsolute)
- [SetActive](ue_ue.SkyLightComponent.md#setactive)
- [SetAffectGlobalIllumination](ue_ue.SkyLightComponent.md#setaffectglobalillumination)
- [SetAffectReflection](ue_ue.SkyLightComponent.md#setaffectreflection)
- [SetAutoActivate](ue_ue.SkyLightComponent.md#setautoactivate)
- [SetCastDeepShadow](ue_ue.SkyLightComponent.md#setcastdeepshadow)
- [SetCastRaytracedShadow](ue_ue.SkyLightComponent.md#setcastraytracedshadow)
- [SetCastShadows](ue_ue.SkyLightComponent.md#setcastshadows)
- [SetCastVolumetricShadow](ue_ue.SkyLightComponent.md#setcastvolumetricshadow)
- [SetComponentTickEnabled](ue_ue.SkyLightComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.SkyLightComponent.md#setcomponenttickinterval)
- [SetCubemap](ue_ue.SkyLightComponent.md#setcubemap)
- [SetCubemapBlend](ue_ue.SkyLightComponent.md#setcubemapblend)
- [SetHiddenInGame](ue_ue.SkyLightComponent.md#sethiddeningame)
- [SetIndirectLightingIntensity](ue_ue.SkyLightComponent.md#setindirectlightingintensity)
- [SetIntensity](ue_ue.SkyLightComponent.md#setintensity)
- [SetIsReplicated](ue_ue.SkyLightComponent.md#setisreplicated)
- [SetLightColor](ue_ue.SkyLightComponent.md#setlightcolor)
- [SetLowerHemisphereColor](ue_ue.SkyLightComponent.md#setlowerhemispherecolor)
- [SetMinOcclusion](ue_ue.SkyLightComponent.md#setminocclusion)
- [SetMobility](ue_ue.SkyLightComponent.md#setmobility)
- [SetOcclusionContrast](ue_ue.SkyLightComponent.md#setocclusioncontrast)
- [SetOcclusionExponent](ue_ue.SkyLightComponent.md#setocclusionexponent)
- [SetOcclusionTint](ue_ue.SkyLightComponent.md#setocclusiontint)
- [SetRelativeScale3D](ue_ue.SkyLightComponent.md#setrelativescale3d)
- [SetSamplesPerPixel](ue_ue.SkyLightComponent.md#setsamplesperpixel)
- [SetShouldUpdatePhysicsVolume](ue_ue.SkyLightComponent.md#setshouldupdatephysicsvolume)
- [SetTickGroup](ue_ue.SkyLightComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.SkyLightComponent.md#settickablewhenpaused)
- [SetVisibility](ue_ue.SkyLightComponent.md#setvisibility)
- [SetVolumetricScatteringIntensity](ue_ue.SkyLightComponent.md#setvolumetricscatteringintensity)
- [SetWorldScale3D](ue_ue.SkyLightComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.SkyLightComponent.md#setupattachment)
- [SnapTo](ue_ue.SkyLightComponent.md#snapto)
- [ToggleActive](ue_ue.SkyLightComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.SkyLightComponent.md#togglevisibility)
- [Find](ue_ue.SkyLightComponent.md#find)
- [Load](ue_ue.SkyLightComponent.md#load)
- [StaticClass](ue_ue.SkyLightComponent.md#staticclass)

## Constructors

### constructor

• **new SkyLightComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[LightComponentBase](ue_ue.LightComponentBase.md).[constructor](ue_ue.LightComponentBase.md#constructor)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[AssetUserData](ue_ue.LightComponentBase.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[AttachChildren](ue_ue.LightComponentBase.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[AttachParent](ue_ue.LightComponentBase.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[AttachSocketName](ue_ue.LightComponentBase.md#attachsocketname)

___

### BlendDestinationCubemap

• **BlendDestinationCubemap**: [`TextureCube`](ue_ue.TextureCube.md)

___

### Brightness

• **Brightness**: `number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[Brightness](ue_ue.LightComponentBase.md#brightness)

___

### CastDynamicShadows

• **CastDynamicShadows**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[CastDynamicShadows](ue_ue.LightComponentBase.md#castdynamicshadows)

___

### CastShadows

• **CastShadows**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[CastShadows](ue_ue.LightComponentBase.md#castshadows)

___

### CastStaticShadows

• **CastStaticShadows**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[CastStaticShadows](ue_ue.LightComponentBase.md#caststaticshadows)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[ClientAttachedChildren](ue_ue.LightComponentBase.md#clientattachedchildren)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[ComponentTags](ue_ue.LightComponentBase.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[ComponentVelocity](ue_ue.LightComponentBase.md#componentvelocity)

___

### Contrast

• **Contrast**: `number`

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[CreationMethod](ue_ue.LightComponentBase.md#creationmethod)

___

### Cubemap

• **Cubemap**: [`TextureCube`](ue_ue.TextureCube.md)

___

### CubemapResolution

• **CubemapResolution**: `number`

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[DetailMode](ue_ue.LightComponentBase.md#detailmode)

___

### DynamicEditorTexture

• **DynamicEditorTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[DynamicEditorTexture](ue_ue.LightComponentBase.md#dynamiceditortexture)

___

### DynamicEditorTextureScale

• **DynamicEditorTextureScale**: `number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[DynamicEditorTextureScale](ue_ue.LightComponentBase.md#dynamiceditortexturescale)

___

### IndirectLightingIntensity

• **IndirectLightingIntensity**: `number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[IndirectLightingIntensity](ue_ue.LightComponentBase.md#indirectlightingintensity)

___

### Intensity

• **Intensity**: `number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[Intensity](ue_ue.LightComponentBase.md#intensity)

___

### LightColor

• **LightColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[LightColor](ue_ue.LightComponentBase.md#lightcolor)

___

### LightGuid

• **LightGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[LightGuid](ue_ue.LightComponentBase.md#lightguid)

___

### LowerHemisphereColor

• **LowerHemisphereColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

___

### MinOcclusion

• **MinOcclusion**: `number`

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[Mobility](ue_ue.LightComponentBase.md#mobility)

___

### OcclusionCombineMode

• **OcclusionCombineMode**: [`EOcclusionCombineMode`](../enums/ue_ue.EOcclusionCombineMode.md)

___

### OcclusionExponent

• **OcclusionExponent**: `number`

___

### OcclusionMaxDistance

• **OcclusionMaxDistance**: `number`

___

### OcclusionTint

• **OcclusionTint**: [`Color`](ue_ue_s.Color.md)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[OnComponentActivated](ue_ue.LightComponentBase.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[OnComponentDeactivated](ue_ue.LightComponentBase.md#oncomponentdeactivated)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[PhysicsVolume](ue_ue.LightComponentBase.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[PhysicsVolumeChangedDelegate](ue_ue.LightComponentBase.md#physicsvolumechangeddelegate)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[PrimaryComponentTick](ue_ue.LightComponentBase.md#primarycomponenttick)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[RelativeLocation](ue_ue.LightComponentBase.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[RelativeRotation](ue_ue.LightComponentBase.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[RelativeScale3D](ue_ue.LightComponentBase.md#relativescale3d)

___

### SamplesPerPixel

• **SamplesPerPixel**: `number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[SamplesPerPixel](ue_ue.LightComponentBase.md#samplesperpixel)

___

### SkyDistanceThreshold

• **SkyDistanceThreshold**: `number`

___

### SourceCubemapAngle

• **SourceCubemapAngle**: `number`

___

### SourceType

• **SourceType**: [`ESkyLightSourceType`](../enums/ue_ue.ESkyLightSourceType.md)

___

### StaticEditorTexture

• **StaticEditorTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[StaticEditorTexture](ue_ue.LightComponentBase.md#staticeditortexture)

___

### StaticEditorTextureScale

• **StaticEditorTextureScale**: `number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[StaticEditorTextureScale](ue_ue.LightComponentBase.md#staticeditortexturescale)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[UCSModifiedProperties](ue_ue.LightComponentBase.md#ucsmodifiedproperties)

___

### VolumetricScatteringIntensity

• **VolumetricScatteringIntensity**: `number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[VolumetricScatteringIntensity](ue_ue.LightComponentBase.md#volumetricscatteringintensity)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[__tid_ActorComponent__](ue_ue.LightComponentBase.md#__tid_actorcomponent__)

___

### \_\_tid\_LightComponentBase\_\_

• **\_\_tid\_LightComponentBase\_\_**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[__tid_LightComponentBase__](ue_ue.LightComponentBase.md#__tid_lightcomponentbase__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[__tid_Object__](ue_ue.LightComponentBase.md#__tid_object__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[__tid_SceneComponent__](ue_ue.LightComponentBase.md#__tid_scenecomponent__)

___

### \_\_tid\_SkyLightComponent\_\_

• **\_\_tid\_SkyLightComponent\_\_**: `boolean`

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bAbsoluteLocation](ue_ue.LightComponentBase.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bAbsoluteRotation](ue_ue.LightComponentBase.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bAbsoluteScale](ue_ue.LightComponentBase.md#babsolutescale)

___

### bAffectGlobalIllumination

• **bAffectGlobalIllumination**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bAffectGlobalIllumination](ue_ue.LightComponentBase.md#baffectglobalillumination)

___

### bAffectReflection

• **bAffectReflection**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bAffectReflection](ue_ue.LightComponentBase.md#baffectreflection)

___

### bAffectTranslucentLighting

• **bAffectTranslucentLighting**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bAffectTranslucentLighting](ue_ue.LightComponentBase.md#baffecttranslucentlighting)

___

### bAffectsWorld

• **bAffectsWorld**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bAffectsWorld](ue_ue.LightComponentBase.md#baffectsworld)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bAutoActivate](ue_ue.LightComponentBase.md#bautoactivate)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.LightComponentBase.md#bboundschangetriggersstreamingdatarebuild)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bCanEverAffectNavigation](ue_ue.LightComponentBase.md#bcaneveraffectnavigation)

___

### bCaptureEmissiveOnly

• **bCaptureEmissiveOnly**: `boolean`

___

### bCastDeepShadow

• **bCastDeepShadow**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bCastDeepShadow](ue_ue.LightComponentBase.md#bcastdeepshadow)

___

### bCastRaytracedShadow

• **bCastRaytracedShadow**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bCastRaytracedShadow](ue_ue.LightComponentBase.md#bcastraytracedshadow)

___

### bCastVolumetricShadow

• **bCastVolumetricShadow**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bCastVolumetricShadow](ue_ue.LightComponentBase.md#bcastvolumetricshadow)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bComponentToWorldUpdated](ue_ue.LightComponentBase.md#bcomponenttoworldupdated)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bCreatedByConstructionScript](ue_ue.LightComponentBase.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bEditableWhenInherited](ue_ue.LightComponentBase.md#beditablewheninherited)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bHiddenInGame](ue_ue.LightComponentBase.md#bhiddeningame)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bInstanceComponent](ue_ue.LightComponentBase.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bIsActive](ue_ue.LightComponentBase.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bIsEditorOnly](ue_ue.LightComponentBase.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bIsVisualizationComponent](ue_ue.LightComponentBase.md#bisvisualizationcomponent)

___

### bLowerHemisphereIsBlack

• **bLowerHemisphereIsBlack**: `boolean`

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bNetAddressable](ue_ue.LightComponentBase.md#bnetaddressable)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bReplicates](ue_ue.LightComponentBase.md#breplicates)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bShouldBeAttached](ue_ue.LightComponentBase.md#bshouldbeattached)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bShouldSnapLocationWhenAttached](ue_ue.LightComponentBase.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bShouldSnapRotationWhenAttached](ue_ue.LightComponentBase.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bShouldUpdatePhysicsVolume](ue_ue.LightComponentBase.md#bshouldupdatephysicsvolume)

___

### bTransmission

• **bTransmission**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bTransmission](ue_ue.LightComponentBase.md#btransmission)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bUseAttachParentBound](ue_ue.LightComponentBase.md#buseattachparentbound)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bVisible](ue_ue.LightComponentBase.md#bvisible)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bVisualizeComponent](ue_ue.LightComponentBase.md#bvisualizecomponent)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[Activate](ue_ue.LightComponentBase.md#activate)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[AddTickPrerequisiteActor](ue_ue.LightComponentBase.md#addtickprerequisiteactor)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[AddTickPrerequisiteComponent](ue_ue.LightComponentBase.md#addtickprerequisitecomponent)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[ComponentHasTag](ue_ue.LightComponentBase.md#componenthastag)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[CreateDefaultSubobject](ue_ue.LightComponentBase.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[Deactivate](ue_ue.LightComponentBase.md#deactivate)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[DetachFromParent](ue_ue.LightComponentBase.md#detachfromparent)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[DoesSocketExist](ue_ue.LightComponentBase.md#doessocketexist)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[ExecuteUbergraph](ue_ue.LightComponentBase.md#executeubergraph)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetAllSocketNames](ue_ue.LightComponentBase.md#getallsocketnames)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetAttachParent](ue_ue.LightComponentBase.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetAttachSocketName](ue_ue.LightComponentBase.md#getattachsocketname)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[GetChildComponent](ue_ue.LightComponentBase.md#getchildcomponent)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[GetChildrenComponents](ue_ue.LightComponentBase.md#getchildrencomponents)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetClass](ue_ue.LightComponentBase.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetComponentTickInterval](ue_ue.LightComponentBase.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetComponentVelocity](ue_ue.LightComponentBase.md#getcomponentvelocity)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetForwardVector](ue_ue.LightComponentBase.md#getforwardvector)

___

### GetLightColor

▸ **GetLightColor**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetLightColor](ue_ue.LightComponentBase.md#getlightcolor)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetName](ue_ue.LightComponentBase.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetNumChildrenComponents](ue_ue.LightComponentBase.md#getnumchildrencomponents)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetOuter](ue_ue.LightComponentBase.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetOwner](ue_ue.LightComponentBase.md#getowner)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[GetParentComponents](ue_ue.LightComponentBase.md#getparentcomponents)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetPhysicsVolume](ue_ue.LightComponentBase.md#getphysicsvolume)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetRelativeTransform](ue_ue.LightComponentBase.md#getrelativetransform)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetRightVector](ue_ue.LightComponentBase.md#getrightvector)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetShouldUpdatePhysicsVolume](ue_ue.LightComponentBase.md#getshouldupdatephysicsvolume)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[GetSocketLocation](ue_ue.LightComponentBase.md#getsocketlocation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[GetSocketQuaternion](ue_ue.LightComponentBase.md#getsocketquaternion)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[GetSocketRotation](ue_ue.LightComponentBase.md#getsocketrotation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[GetSocketTransform](ue_ue.LightComponentBase.md#getsockettransform)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetUpVector](ue_ue.LightComponentBase.md#getupvector)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetWorld](ue_ue.LightComponentBase.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[IsActive](ue_ue.LightComponentBase.md#isactive)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[IsAnySimulatingPhysics](ue_ue.LightComponentBase.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[IsBeingDestroyed](ue_ue.LightComponentBase.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[IsComponentTickEnabled](ue_ue.LightComponentBase.md#iscomponenttickenabled)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[IsSimulatingPhysics](ue_ue.LightComponentBase.md#issimulatingphysics)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[IsVisible](ue_ue.LightComponentBase.md#isvisible)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AddLocalOffset](ue_ue.LightComponentBase.md#k2_addlocaloffset)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AddLocalRotation](ue_ue.LightComponentBase.md#k2_addlocalrotation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AddLocalTransform](ue_ue.LightComponentBase.md#k2_addlocaltransform)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AddRelativeLocation](ue_ue.LightComponentBase.md#k2_addrelativelocation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AddRelativeRotation](ue_ue.LightComponentBase.md#k2_addrelativerotation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AddWorldOffset](ue_ue.LightComponentBase.md#k2_addworldoffset)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AddWorldRotation](ue_ue.LightComponentBase.md#k2_addworldrotation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AddWorldTransform](ue_ue.LightComponentBase.md#k2_addworldtransform)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AttachTo](ue_ue.LightComponentBase.md#k2_attachto)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AttachToComponent](ue_ue.LightComponentBase.md#k2_attachtocomponent)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_DestroyComponent](ue_ue.LightComponentBase.md#k2_destroycomponent)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_DetachFromComponent](ue_ue.LightComponentBase.md#k2_detachfromcomponent)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_GetComponentLocation](ue_ue.LightComponentBase.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_GetComponentRotation](ue_ue.LightComponentBase.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_GetComponentScale](ue_ue.LightComponentBase.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_GetComponentToWorld](ue_ue.LightComponentBase.md#k2_getcomponenttoworld)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_SetRelativeLocation](ue_ue.LightComponentBase.md#k2_setrelativelocation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_SetRelativeLocationAndRotation](ue_ue.LightComponentBase.md#k2_setrelativelocationandrotation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_SetRelativeRotation](ue_ue.LightComponentBase.md#k2_setrelativerotation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_SetRelativeTransform](ue_ue.LightComponentBase.md#k2_setrelativetransform)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_SetWorldLocation](ue_ue.LightComponentBase.md#k2_setworldlocation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_SetWorldLocationAndRotation](ue_ue.LightComponentBase.md#k2_setworldlocationandrotation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_SetWorldRotation](ue_ue.LightComponentBase.md#k2_setworldrotation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_SetWorldTransform](ue_ue.LightComponentBase.md#k2_setworldtransform)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[OnRep_AttachChildren](ue_ue.LightComponentBase.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[OnRep_AttachParent](ue_ue.LightComponentBase.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[OnRep_AttachSocketName](ue_ue.LightComponentBase.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[OnRep_IsActive](ue_ue.LightComponentBase.md#onrep_isactive)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[OnRep_Transform](ue_ue.LightComponentBase.md#onrep_transform)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[OnRep_Visibility](ue_ue.LightComponentBase.md#onrep_visibility)

___

### RecaptureSky

▸ **RecaptureSky**(): `void`

#### Returns

`void`

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[ReceiveBeginPlay](ue_ue.LightComponentBase.md#receivebeginplay)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[ReceiveEndPlay](ue_ue.LightComponentBase.md#receiveendplay)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[ReceiveTick](ue_ue.LightComponentBase.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[RegisterComponent](ue_ue.LightComponentBase.md#registercomponent)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[RemoveTickPrerequisiteActor](ue_ue.LightComponentBase.md#removetickprerequisiteactor)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[RemoveTickPrerequisiteComponent](ue_ue.LightComponentBase.md#removetickprerequisitecomponent)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[ResetRelativeTransform](ue_ue.LightComponentBase.md#resetrelativetransform)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetAbsolute](ue_ue.LightComponentBase.md#setabsolute)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetActive](ue_ue.LightComponentBase.md#setactive)

___

### SetAffectGlobalIllumination

▸ **SetAffectGlobalIllumination**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[SetAffectGlobalIllumination](ue_ue.LightComponentBase.md#setaffectglobalillumination)

___

### SetAffectReflection

▸ **SetAffectReflection**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[SetAffectReflection](ue_ue.LightComponentBase.md#setaffectreflection)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetAutoActivate](ue_ue.LightComponentBase.md#setautoactivate)

___

### SetCastDeepShadow

▸ **SetCastDeepShadow**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[SetCastDeepShadow](ue_ue.LightComponentBase.md#setcastdeepshadow)

___

### SetCastRaytracedShadow

▸ **SetCastRaytracedShadow**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[SetCastRaytracedShadow](ue_ue.LightComponentBase.md#setcastraytracedshadow)

___

### SetCastShadows

▸ **SetCastShadows**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[SetCastShadows](ue_ue.LightComponentBase.md#setcastshadows)

___

### SetCastVolumetricShadow

▸ **SetCastVolumetricShadow**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[SetCastVolumetricShadow](ue_ue.LightComponentBase.md#setcastvolumetricshadow)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetComponentTickEnabled](ue_ue.LightComponentBase.md#setcomponenttickenabled)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetComponentTickInterval](ue_ue.LightComponentBase.md#setcomponenttickinterval)

___

### SetCubemap

▸ **SetCubemap**(`NewCubemap`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewCubemap` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureCube`](ue_ue.TextureCube.md)\> |

#### Returns

`void`

___

### SetCubemapBlend

▸ **SetCubemapBlend**(`SourceCubemap`, `DestinationCubemap`, `InBlendFraction`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SourceCubemap` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureCube`](ue_ue.TextureCube.md)\> |
| `DestinationCubemap` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureCube`](ue_ue.TextureCube.md)\> |
| `InBlendFraction` | `number` |

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetHiddenInGame](ue_ue.LightComponentBase.md#sethiddeningame)

___

### SetIndirectLightingIntensity

▸ **SetIndirectLightingIntensity**(`NewIntensity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewIntensity` | `number` |

#### Returns

`void`

___

### SetIntensity

▸ **SetIntensity**(`NewIntensity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewIntensity` | `number` |

#### Returns

`void`

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetIsReplicated](ue_ue.LightComponentBase.md#setisreplicated)

___

### SetLightColor

▸ **SetLightColor**(`NewLightColor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLightColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

___

### SetLowerHemisphereColor

▸ **SetLowerHemisphereColor**(`InLowerHemisphereColor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLowerHemisphereColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

___

### SetMinOcclusion

▸ **SetMinOcclusion**(`InMinOcclusion`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InMinOcclusion` | `number` |

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetMobility](ue_ue.LightComponentBase.md#setmobility)

___

### SetOcclusionContrast

▸ **SetOcclusionContrast**(`InOcclusionContrast`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InOcclusionContrast` | `number` |

#### Returns

`void`

___

### SetOcclusionExponent

▸ **SetOcclusionExponent**(`InOcclusionExponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InOcclusionExponent` | `number` |

#### Returns

`void`

___

### SetOcclusionTint

▸ **SetOcclusionTint**(`InTint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTint` | [`Color`](ue_ue_s.Color.md) |

#### Returns

`void`

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetRelativeScale3D](ue_ue.LightComponentBase.md#setrelativescale3d)

___

### SetSamplesPerPixel

▸ **SetSamplesPerPixel**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[SetSamplesPerPixel](ue_ue.LightComponentBase.md#setsamplesperpixel)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetShouldUpdatePhysicsVolume](ue_ue.LightComponentBase.md#setshouldupdatephysicsvolume)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetTickGroup](ue_ue.LightComponentBase.md#settickgroup)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetTickableWhenPaused](ue_ue.LightComponentBase.md#settickablewhenpaused)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetVisibility](ue_ue.LightComponentBase.md#setvisibility)

___

### SetVolumetricScatteringIntensity

▸ **SetVolumetricScatteringIntensity**(`NewIntensity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewIntensity` | `number` |

#### Returns

`void`

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetWorldScale3D](ue_ue.LightComponentBase.md#setworldscale3d)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetupAttachment](ue_ue.LightComponentBase.md#setupattachment)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SnapTo](ue_ue.LightComponentBase.md#snapto)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[ToggleActive](ue_ue.LightComponentBase.md#toggleactive)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[ToggleVisibility](ue_ue.LightComponentBase.md#togglevisibility)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SkyLightComponent`](ue_ue.SkyLightComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SkyLightComponent`](ue_ue.SkyLightComponent.md)

#### Overrides

[LightComponentBase](ue_ue.LightComponentBase.md).[Find](ue_ue.LightComponentBase.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`SkyLightComponent`](ue_ue.SkyLightComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SkyLightComponent`](ue_ue.SkyLightComponent.md)

#### Overrides

[LightComponentBase](ue_ue.LightComponentBase.md).[Load](ue_ue.LightComponentBase.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[LightComponentBase](ue_ue.LightComponentBase.md).[StaticClass](ue_ue.LightComponentBase.md#staticclass)
