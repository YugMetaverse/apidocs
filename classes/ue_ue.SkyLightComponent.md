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

#### Defined in

[ue/ue.d.ts:21396](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21396)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[AssetUserData](ue_ue.LightComponentBase.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L291)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[AttachChildren](ue_ue.LightComponentBase.md#attachchildren)

#### Defined in

[ue/ue.d.ts:12873](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12873)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[AttachParent](ue_ue.LightComponentBase.md#attachparent)

#### Defined in

[ue/ue.d.ts:12871](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12871)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[AttachSocketName](ue_ue.LightComponentBase.md#attachsocketname)

#### Defined in

[ue/ue.d.ts:12872](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12872)

___

### BlendDestinationCubemap

• **BlendDestinationCubemap**: [`TextureCube`](ue_ue.TextureCube.md)

#### Defined in

[ue/ue.d.ts:21411](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21411)

___

### Brightness

• **Brightness**: `number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[Brightness](ue_ue.LightComponentBase.md#brightness)

#### Defined in

[ue/ue.d.ts:21357](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21357)

___

### CastDynamicShadows

• **CastDynamicShadows**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[CastDynamicShadows](ue_ue.LightComponentBase.md#castdynamicshadows)

#### Defined in

[ue/ue.d.ts:21363](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21363)

___

### CastShadows

• **CastShadows**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[CastShadows](ue_ue.LightComponentBase.md#castshadows)

#### Defined in

[ue/ue.d.ts:21361](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21361)

___

### CastStaticShadows

• **CastStaticShadows**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[CastStaticShadows](ue_ue.LightComponentBase.md#caststaticshadows)

#### Defined in

[ue/ue.d.ts:21362](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21362)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[ClientAttachedChildren](ue_ue.LightComponentBase.md#clientattachedchildren)

#### Defined in

[ue/ue.d.ts:12874](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12874)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[ComponentTags](ue_ue.LightComponentBase.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L290)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[ComponentVelocity](ue_ue.LightComponentBase.md#componentvelocity)

#### Defined in

[ue/ue.d.ts:12878](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12878)

___

### Contrast

• **Contrast**: `number`

#### Defined in

[ue/ue.d.ts:21406](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21406)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[CreationMethod](ue_ue.LightComponentBase.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L302)

___

### Cubemap

• **Cubemap**: [`TextureCube`](ue_ue.TextureCube.md)

#### Defined in

[ue/ue.d.ts:21398](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21398)

___

### CubemapResolution

• **CubemapResolution**: `number`

#### Defined in

[ue/ue.d.ts:21400](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21400)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[DetailMode](ue_ue.LightComponentBase.md#detailmode)

#### Defined in

[ue/ue.d.ts:12893](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12893)

___

### DynamicEditorTexture

• **DynamicEditorTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[DynamicEditorTexture](ue_ue.LightComponentBase.md#dynamiceditortexture)

#### Defined in

[ue/ue.d.ts:21376](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21376)

___

### DynamicEditorTextureScale

• **DynamicEditorTextureScale**: `number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[DynamicEditorTextureScale](ue_ue.LightComponentBase.md#dynamiceditortexturescale)

#### Defined in

[ue/ue.d.ts:21377](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21377)

___

### IndirectLightingIntensity

• **IndirectLightingIntensity**: `number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[IndirectLightingIntensity](ue_ue.LightComponentBase.md#indirectlightingintensity)

#### Defined in

[ue/ue.d.ts:21371](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21371)

___

### Intensity

• **Intensity**: `number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[Intensity](ue_ue.LightComponentBase.md#intensity)

#### Defined in

[ue/ue.d.ts:21358](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21358)

___

### LightColor

• **LightColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[LightColor](ue_ue.LightComponentBase.md#lightcolor)

#### Defined in

[ue/ue.d.ts:21359](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21359)

___

### LightGuid

• **LightGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[LightGuid](ue_ue.LightComponentBase.md#lightguid)

#### Defined in

[ue/ue.d.ts:21356](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21356)

___

### LowerHemisphereColor

• **LowerHemisphereColor**: [`LinearColor`](ue_ue_s.LinearColor.md)

#### Defined in

[ue/ue.d.ts:21404](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21404)

___

### MinOcclusion

• **MinOcclusion**: `number`

#### Defined in

[ue/ue.d.ts:21408](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21408)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[Mobility](ue_ue.LightComponentBase.md#mobility)

#### Defined in

[ue/ue.d.ts:12892](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12892)

___

### OcclusionCombineMode

• **OcclusionCombineMode**: [`EOcclusionCombineMode`](../enums/ue_ue.EOcclusionCombineMode.md)

#### Defined in

[ue/ue.d.ts:21410](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21410)

___

### OcclusionExponent

• **OcclusionExponent**: `number`

#### Defined in

[ue/ue.d.ts:21407](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21407)

___

### OcclusionMaxDistance

• **OcclusionMaxDistance**: `number`

#### Defined in

[ue/ue.d.ts:21405](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21405)

___

### OcclusionTint

• **OcclusionTint**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:21409](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21409)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[OnComponentActivated](ue_ue.LightComponentBase.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[OnComponentDeactivated](ue_ue.LightComponentBase.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L304)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[PhysicsVolume](ue_ue.LightComponentBase.md#physicsvolume)

#### Defined in

[ue/ue.d.ts:12870](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12870)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[PhysicsVolumeChangedDelegate](ue_ue.LightComponentBase.md#physicsvolumechangeddelegate)

#### Defined in

[ue/ue.d.ts:12894](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12894)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[PrimaryComponentTick](ue_ue.LightComponentBase.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L289)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[RelativeLocation](ue_ue.LightComponentBase.md#relativelocation)

#### Defined in

[ue/ue.d.ts:12875](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12875)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[RelativeRotation](ue_ue.LightComponentBase.md#relativerotation)

#### Defined in

[ue/ue.d.ts:12876](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12876)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[RelativeScale3D](ue_ue.LightComponentBase.md#relativescale3d)

#### Defined in

[ue/ue.d.ts:12877](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12877)

___

### SamplesPerPixel

• **SamplesPerPixel**: `number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[SamplesPerPixel](ue_ue.LightComponentBase.md#samplesperpixel)

#### Defined in

[ue/ue.d.ts:21373](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21373)

___

### SkyDistanceThreshold

• **SkyDistanceThreshold**: `number`

#### Defined in

[ue/ue.d.ts:21401](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21401)

___

### SourceCubemapAngle

• **SourceCubemapAngle**: `number`

#### Defined in

[ue/ue.d.ts:21399](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21399)

___

### SourceType

• **SourceType**: [`ESkyLightSourceType`](../enums/ue_ue.ESkyLightSourceType.md)

#### Defined in

[ue/ue.d.ts:21397](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21397)

___

### StaticEditorTexture

• **StaticEditorTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[StaticEditorTexture](ue_ue.LightComponentBase.md#staticeditortexture)

#### Defined in

[ue/ue.d.ts:21374](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21374)

___

### StaticEditorTextureScale

• **StaticEditorTextureScale**: `number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[StaticEditorTextureScale](ue_ue.LightComponentBase.md#staticeditortexturescale)

#### Defined in

[ue/ue.d.ts:21375](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21375)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[UCSModifiedProperties](ue_ue.LightComponentBase.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L305)

___

### VolumetricScatteringIntensity

• **VolumetricScatteringIntensity**: `number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[VolumetricScatteringIntensity](ue_ue.LightComponentBase.md#volumetricscatteringintensity)

#### Defined in

[ue/ue.d.ts:21372](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21372)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[__tid_ActorComponent__](ue_ue.LightComponentBase.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L336)

___

### \_\_tid\_LightComponentBase\_\_

• **\_\_tid\_LightComponentBase\_\_**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[__tid_LightComponentBase__](ue_ue.LightComponentBase.md#__tid_lightcomponentbase__)

#### Defined in

[ue/ue.d.ts:21390](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21390)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[__tid_Object__](ue_ue.LightComponentBase.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[__tid_SceneComponent__](ue_ue.LightComponentBase.md#__tid_scenecomponent__)

#### Defined in

[ue/ue.d.ts:12961](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12961)

___

### \_\_tid\_SkyLightComponent\_\_

• **\_\_tid\_SkyLightComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:21428](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21428)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bAbsoluteLocation](ue_ue.LightComponentBase.md#babsolutelocation)

#### Defined in

[ue/ue.d.ts:12880](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12880)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bAbsoluteRotation](ue_ue.LightComponentBase.md#babsoluterotation)

#### Defined in

[ue/ue.d.ts:12881](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12881)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bAbsoluteScale](ue_ue.LightComponentBase.md#babsolutescale)

#### Defined in

[ue/ue.d.ts:12882](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12882)

___

### bAffectGlobalIllumination

• **bAffectGlobalIllumination**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bAffectGlobalIllumination](ue_ue.LightComponentBase.md#baffectglobalillumination)

#### Defined in

[ue/ue.d.ts:21370](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21370)

___

### bAffectReflection

• **bAffectReflection**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bAffectReflection](ue_ue.LightComponentBase.md#baffectreflection)

#### Defined in

[ue/ue.d.ts:21369](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21369)

___

### bAffectTranslucentLighting

• **bAffectTranslucentLighting**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bAffectTranslucentLighting](ue_ue.LightComponentBase.md#baffecttranslucentlighting)

#### Defined in

[ue/ue.d.ts:21364](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21364)

___

### bAffectsWorld

• **bAffectsWorld**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bAffectsWorld](ue_ue.LightComponentBase.md#baffectsworld)

#### Defined in

[ue/ue.d.ts:21360](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21360)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bAutoActivate](ue_ue.LightComponentBase.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L296)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.LightComponentBase.md#bboundschangetriggersstreamingdatarebuild)

#### Defined in

[ue/ue.d.ts:12889](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12889)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bCanEverAffectNavigation](ue_ue.LightComponentBase.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L299)

___

### bCaptureEmissiveOnly

• **bCaptureEmissiveOnly**: `boolean`

#### Defined in

[ue/ue.d.ts:21402](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21402)

___

### bCastDeepShadow

• **bCastDeepShadow**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bCastDeepShadow](ue_ue.LightComponentBase.md#bcastdeepshadow)

#### Defined in

[ue/ue.d.ts:21367](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21367)

___

### bCastRaytracedShadow

• **bCastRaytracedShadow**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bCastRaytracedShadow](ue_ue.LightComponentBase.md#bcastraytracedshadow)

#### Defined in

[ue/ue.d.ts:21368](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21368)

___

### bCastVolumetricShadow

• **bCastVolumetricShadow**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bCastVolumetricShadow](ue_ue.LightComponentBase.md#bcastvolumetricshadow)

#### Defined in

[ue/ue.d.ts:21366](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21366)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bComponentToWorldUpdated](ue_ue.LightComponentBase.md#bcomponenttoworldupdated)

#### Defined in

[ue/ue.d.ts:12879](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12879)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bCreatedByConstructionScript](ue_ue.LightComponentBase.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bEditableWhenInherited](ue_ue.LightComponentBase.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L298)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bHiddenInGame](ue_ue.LightComponentBase.md#bhiddeningame)

#### Defined in

[ue/ue.d.ts:12884](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12884)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bInstanceComponent](ue_ue.LightComponentBase.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bIsActive](ue_ue.LightComponentBase.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bIsEditorOnly](ue_ue.LightComponentBase.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bIsVisualizationComponent](ue_ue.LightComponentBase.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L301)

___

### bLowerHemisphereIsBlack

• **bLowerHemisphereIsBlack**: `boolean`

#### Defined in

[ue/ue.d.ts:21403](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21403)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bNetAddressable](ue_ue.LightComponentBase.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L293)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bReplicates](ue_ue.LightComponentBase.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L292)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bShouldBeAttached](ue_ue.LightComponentBase.md#bshouldbeattached)

#### Defined in

[ue/ue.d.ts:12885](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12885)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bShouldSnapLocationWhenAttached](ue_ue.LightComponentBase.md#bshouldsnaplocationwhenattached)

#### Defined in

[ue/ue.d.ts:12886](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12886)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bShouldSnapRotationWhenAttached](ue_ue.LightComponentBase.md#bshouldsnaprotationwhenattached)

#### Defined in

[ue/ue.d.ts:12887](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12887)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bShouldUpdatePhysicsVolume](ue_ue.LightComponentBase.md#bshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12888](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12888)

___

### bTransmission

• **bTransmission**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bTransmission](ue_ue.LightComponentBase.md#btransmission)

#### Defined in

[ue/ue.d.ts:21365](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21365)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bUseAttachParentBound](ue_ue.LightComponentBase.md#buseattachparentbound)

#### Defined in

[ue/ue.d.ts:12890](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12890)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bVisible](ue_ue.LightComponentBase.md#bvisible)

#### Defined in

[ue/ue.d.ts:12883](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12883)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[bVisualizeComponent](ue_ue.LightComponentBase.md#bvisualizecomponent)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[Activate](ue_ue.LightComponentBase.md#activate)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[AddTickPrerequisiteActor](ue_ue.LightComponentBase.md#addtickprerequisiteactor)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[AddTickPrerequisiteComponent](ue_ue.LightComponentBase.md#addtickprerequisitecomponent)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[ComponentHasTag](ue_ue.LightComponentBase.md#componenthastag)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[CreateDefaultSubobject](ue_ue.LightComponentBase.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[Deactivate](ue_ue.LightComponentBase.md#deactivate)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[DetachFromParent](ue_ue.LightComponentBase.md#detachfromparent)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[DoesSocketExist](ue_ue.LightComponentBase.md#doessocketexist)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[ExecuteUbergraph](ue_ue.LightComponentBase.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetAllSocketNames](ue_ue.LightComponentBase.md#getallsocketnames)

#### Defined in

[ue/ue.d.ts:12897](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12897)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetAttachParent](ue_ue.LightComponentBase.md#getattachparent)

#### Defined in

[ue/ue.d.ts:12898](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12898)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetAttachSocketName](ue_ue.LightComponentBase.md#getattachsocketname)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[GetChildComponent](ue_ue.LightComponentBase.md#getchildcomponent)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[GetChildrenComponents](ue_ue.LightComponentBase.md#getchildrencomponents)

#### Defined in

[ue/ue.d.ts:12901](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12901)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetClass](ue_ue.LightComponentBase.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetComponentTickInterval](ue_ue.LightComponentBase.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L311)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetComponentVelocity](ue_ue.LightComponentBase.md#getcomponentvelocity)

#### Defined in

[ue/ue.d.ts:12902](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12902)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetForwardVector](ue_ue.LightComponentBase.md#getforwardvector)

#### Defined in

[ue/ue.d.ts:12903](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12903)

___

### GetLightColor

▸ **GetLightColor**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetLightColor](ue_ue.LightComponentBase.md#getlightcolor)

#### Defined in

[ue/ue.d.ts:21378](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21378)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetName](ue_ue.LightComponentBase.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetNumChildrenComponents](ue_ue.LightComponentBase.md#getnumchildrencomponents)

#### Defined in

[ue/ue.d.ts:12904](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12904)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetOuter](ue_ue.LightComponentBase.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetOwner](ue_ue.LightComponentBase.md#getowner)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[GetParentComponents](ue_ue.LightComponentBase.md#getparentcomponents)

#### Defined in

[ue/ue.d.ts:12905](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12905)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetPhysicsVolume](ue_ue.LightComponentBase.md#getphysicsvolume)

#### Defined in

[ue/ue.d.ts:12906](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12906)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetRelativeTransform](ue_ue.LightComponentBase.md#getrelativetransform)

#### Defined in

[ue/ue.d.ts:12907](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12907)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetRightVector](ue_ue.LightComponentBase.md#getrightvector)

#### Defined in

[ue/ue.d.ts:12908](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12908)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetShouldUpdatePhysicsVolume](ue_ue.LightComponentBase.md#getshouldupdatephysicsvolume)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[GetSocketLocation](ue_ue.LightComponentBase.md#getsocketlocation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[GetSocketQuaternion](ue_ue.LightComponentBase.md#getsocketquaternion)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[GetSocketRotation](ue_ue.LightComponentBase.md#getsocketrotation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[GetSocketTransform](ue_ue.LightComponentBase.md#getsockettransform)

#### Defined in

[ue/ue.d.ts:12913](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12913)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetUpVector](ue_ue.LightComponentBase.md#getupvector)

#### Defined in

[ue/ue.d.ts:12914](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12914)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[GetWorld](ue_ue.LightComponentBase.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[IsActive](ue_ue.LightComponentBase.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L313)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[IsAnySimulatingPhysics](ue_ue.LightComponentBase.md#isanysimulatingphysics)

#### Defined in

[ue/ue.d.ts:12915](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12915)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[IsBeingDestroyed](ue_ue.LightComponentBase.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[IsComponentTickEnabled](ue_ue.LightComponentBase.md#iscomponenttickenabled)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[IsSimulatingPhysics](ue_ue.LightComponentBase.md#issimulatingphysics)

#### Defined in

[ue/ue.d.ts:12916](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12916)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[IsVisible](ue_ue.LightComponentBase.md#isvisible)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AddLocalOffset](ue_ue.LightComponentBase.md#k2_addlocaloffset)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AddLocalRotation](ue_ue.LightComponentBase.md#k2_addlocalrotation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AddLocalTransform](ue_ue.LightComponentBase.md#k2_addlocaltransform)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AddRelativeLocation](ue_ue.LightComponentBase.md#k2_addrelativelocation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AddRelativeRotation](ue_ue.LightComponentBase.md#k2_addrelativerotation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AddWorldOffset](ue_ue.LightComponentBase.md#k2_addworldoffset)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AddWorldRotation](ue_ue.LightComponentBase.md#k2_addworldrotation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AddWorldTransform](ue_ue.LightComponentBase.md#k2_addworldtransform)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AttachTo](ue_ue.LightComponentBase.md#k2_attachto)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_AttachToComponent](ue_ue.LightComponentBase.md#k2_attachtocomponent)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_DestroyComponent](ue_ue.LightComponentBase.md#k2_destroycomponent)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_DetachFromComponent](ue_ue.LightComponentBase.md#k2_detachfromcomponent)

#### Defined in

[ue/ue.d.ts:12928](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12928)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_GetComponentLocation](ue_ue.LightComponentBase.md#k2_getcomponentlocation)

#### Defined in

[ue/ue.d.ts:12929](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12929)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_GetComponentRotation](ue_ue.LightComponentBase.md#k2_getcomponentrotation)

#### Defined in

[ue/ue.d.ts:12930](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12930)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_GetComponentScale](ue_ue.LightComponentBase.md#k2_getcomponentscale)

#### Defined in

[ue/ue.d.ts:12931](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12931)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_GetComponentToWorld](ue_ue.LightComponentBase.md#k2_getcomponenttoworld)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_SetRelativeLocation](ue_ue.LightComponentBase.md#k2_setrelativelocation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_SetRelativeLocationAndRotation](ue_ue.LightComponentBase.md#k2_setrelativelocationandrotation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_SetRelativeRotation](ue_ue.LightComponentBase.md#k2_setrelativerotation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_SetRelativeTransform](ue_ue.LightComponentBase.md#k2_setrelativetransform)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_SetWorldLocation](ue_ue.LightComponentBase.md#k2_setworldlocation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_SetWorldLocationAndRotation](ue_ue.LightComponentBase.md#k2_setworldlocationandrotation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_SetWorldRotation](ue_ue.LightComponentBase.md#k2_setworldrotation)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[K2_SetWorldTransform](ue_ue.LightComponentBase.md#k2_setworldtransform)

#### Defined in

[ue/ue.d.ts:12940](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12940)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[OnRep_AttachChildren](ue_ue.LightComponentBase.md#onrep_attachchildren)

#### Defined in

[ue/ue.d.ts:12941](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12941)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[OnRep_AttachParent](ue_ue.LightComponentBase.md#onrep_attachparent)

#### Defined in

[ue/ue.d.ts:12942](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12942)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[OnRep_AttachSocketName](ue_ue.LightComponentBase.md#onrep_attachsocketname)

#### Defined in

[ue/ue.d.ts:12943](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12943)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[OnRep_IsActive](ue_ue.LightComponentBase.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L317)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[OnRep_Transform](ue_ue.LightComponentBase.md#onrep_transform)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[OnRep_Visibility](ue_ue.LightComponentBase.md#onrep_visibility)

#### Defined in

[ue/ue.d.ts:12945](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12945)

___

### RecaptureSky

▸ **RecaptureSky**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21412](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21412)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[ReceiveBeginPlay](ue_ue.LightComponentBase.md#receivebeginplay)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[ReceiveEndPlay](ue_ue.LightComponentBase.md#receiveendplay)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[ReceiveTick](ue_ue.LightComponentBase.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[RegisterComponent](ue_ue.LightComponentBase.md#registercomponent)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[RemoveTickPrerequisiteActor](ue_ue.LightComponentBase.md#removetickprerequisiteactor)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[RemoveTickPrerequisiteComponent](ue_ue.LightComponentBase.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L323)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[ResetRelativeTransform](ue_ue.LightComponentBase.md#resetrelativetransform)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetAbsolute](ue_ue.LightComponentBase.md#setabsolute)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetActive](ue_ue.LightComponentBase.md#setactive)

#### Defined in

[ue/ue.d.ts:324](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L324)

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

#### Defined in

[ue/ue.d.ts:21379](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21379)

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

#### Defined in

[ue/ue.d.ts:21380](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21380)

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

#### Defined in

[ue/ue.d.ts:325](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L325)

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

#### Defined in

[ue/ue.d.ts:21381](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21381)

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

#### Defined in

[ue/ue.d.ts:21382](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21382)

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

#### Defined in

[ue/ue.d.ts:21383](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21383)

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

#### Defined in

[ue/ue.d.ts:21384](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21384)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetComponentTickInterval](ue_ue.LightComponentBase.md#setcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L327)

___

### SetCubemap

▸ **SetCubemap**(`NewCubemap`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewCubemap` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureCube`](ue_ue.TextureCube.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21413](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21413)

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

#### Defined in

[ue/ue.d.ts:21414](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21414)

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

#### Defined in

[ue/ue.d.ts:12948](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12948)

___

### SetIndirectLightingIntensity

▸ **SetIndirectLightingIntensity**(`NewIntensity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewIntensity` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21415](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21415)

___

### SetIntensity

▸ **SetIntensity**(`NewIntensity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewIntensity` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21416](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21416)

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

#### Defined in

[ue/ue.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L328)

___

### SetLightColor

▸ **SetLightColor**(`NewLightColor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLightColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21417](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21417)

___

### SetLowerHemisphereColor

▸ **SetLowerHemisphereColor**(`InLowerHemisphereColor`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLowerHemisphereColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21418)

___

### SetMinOcclusion

▸ **SetMinOcclusion**(`InMinOcclusion`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InMinOcclusion` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21419](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21419)

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

#### Defined in

[ue/ue.d.ts:12949](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12949)

___

### SetOcclusionContrast

▸ **SetOcclusionContrast**(`InOcclusionContrast`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InOcclusionContrast` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21420](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21420)

___

### SetOcclusionExponent

▸ **SetOcclusionExponent**(`InOcclusionExponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InOcclusionExponent` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21421](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21421)

___

### SetOcclusionTint

▸ **SetOcclusionTint**(`InTint`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InTint` | [`Color`](ue_ue_s.Color.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21422](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21422)

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

#### Defined in

[ue/ue.d.ts:12950](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12950)

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

#### Defined in

[ue/ue.d.ts:21385](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21385)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetTickGroup](ue_ue.LightComponentBase.md#settickgroup)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetTickableWhenPaused](ue_ue.LightComponentBase.md#settickablewhenpaused)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetVisibility](ue_ue.LightComponentBase.md#setvisibility)

#### Defined in

[ue/ue.d.ts:12953](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12953)

___

### SetVolumetricScatteringIntensity

▸ **SetVolumetricScatteringIntensity**(`NewIntensity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewIntensity` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:21423](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21423)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SetupAttachment](ue_ue.LightComponentBase.md#setupattachment)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[SnapTo](ue_ue.LightComponentBase.md#snapto)

#### Defined in

[ue/ue.d.ts:12955](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12955)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponentBase](ue_ue.LightComponentBase.md).[ToggleActive](ue_ue.LightComponentBase.md#toggleactive)

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

[LightComponentBase](ue_ue.LightComponentBase.md).[ToggleVisibility](ue_ue.LightComponentBase.md#togglevisibility)

#### Defined in

[ue/ue.d.ts:12956](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12956)

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

#### Defined in

[ue/ue.d.ts:21425](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21425)

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

#### Defined in

[ue/ue.d.ts:21426](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21426)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[LightComponentBase](ue_ue.LightComponentBase.md).[StaticClass](ue_ue.LightComponentBase.md#staticclass)

#### Defined in

[ue/ue.d.ts:21424](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21424)
