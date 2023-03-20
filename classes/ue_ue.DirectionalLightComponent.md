[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / DirectionalLightComponent

# Class: DirectionalLightComponent

[ue/ue](../modules/ue_ue.md).DirectionalLightComponent

## Hierarchy

- [`LightComponent`](ue_ue.LightComponent.md)

  ↳ **`DirectionalLightComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.DirectionalLightComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.DirectionalLightComponent.md#assetuserdata)
- [AtmosphereSunLightIndex](ue_ue.DirectionalLightComponent.md#atmospheresunlightindex)
- [AttachChildren](ue_ue.DirectionalLightComponent.md#attachchildren)
- [AttachParent](ue_ue.DirectionalLightComponent.md#attachparent)
- [AttachSocketName](ue_ue.DirectionalLightComponent.md#attachsocketname)
- [BloomMaxBrightness](ue_ue.DirectionalLightComponent.md#bloommaxbrightness)
- [BloomScale](ue_ue.DirectionalLightComponent.md#bloomscale)
- [BloomThreshold](ue_ue.DirectionalLightComponent.md#bloomthreshold)
- [BloomTint](ue_ue.DirectionalLightComponent.md#bloomtint)
- [Brightness](ue_ue.DirectionalLightComponent.md#brightness)
- [CascadeDistributionExponent](ue_ue.DirectionalLightComponent.md#cascadedistributionexponent)
- [CascadeTransitionFraction](ue_ue.DirectionalLightComponent.md#cascadetransitionfraction)
- [CastDynamicShadows](ue_ue.DirectionalLightComponent.md#castdynamicshadows)
- [CastShadows](ue_ue.DirectionalLightComponent.md#castshadows)
- [CastStaticShadows](ue_ue.DirectionalLightComponent.md#caststaticshadows)
- [CastTranslucentShadows](ue_ue.DirectionalLightComponent.md#casttranslucentshadows)
- [ClientAttachedChildren](ue_ue.DirectionalLightComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.DirectionalLightComponent.md#componenttags)
- [ComponentVelocity](ue_ue.DirectionalLightComponent.md#componentvelocity)
- [ContactShadowLength](ue_ue.DirectionalLightComponent.md#contactshadowlength)
- [ContactShadowLengthInWS](ue_ue.DirectionalLightComponent.md#contactshadowlengthinws)
- [CreationMethod](ue_ue.DirectionalLightComponent.md#creationmethod)
- [DetailMode](ue_ue.DirectionalLightComponent.md#detailmode)
- [DisabledBrightness](ue_ue.DirectionalLightComponent.md#disabledbrightness)
- [DistanceFieldShadowDistance](ue_ue.DirectionalLightComponent.md#distancefieldshadowdistance)
- [DynamicEditorTexture](ue_ue.DirectionalLightComponent.md#dynamiceditortexture)
- [DynamicEditorTextureScale](ue_ue.DirectionalLightComponent.md#dynamiceditortexturescale)
- [DynamicShadowCascades](ue_ue.DirectionalLightComponent.md#dynamicshadowcascades)
- [DynamicShadowDistanceMovableLight](ue_ue.DirectionalLightComponent.md#dynamicshadowdistancemovablelight)
- [DynamicShadowDistanceStationaryLight](ue_ue.DirectionalLightComponent.md#dynamicshadowdistancestationarylight)
- [FarShadowCascadeCount](ue_ue.DirectionalLightComponent.md#farshadowcascadecount)
- [FarShadowDistance](ue_ue.DirectionalLightComponent.md#farshadowdistance)
- [IESBrightnessScale](ue_ue.DirectionalLightComponent.md#iesbrightnessscale)
- [IESTexture](ue_ue.DirectionalLightComponent.md#iestexture)
- [IndirectLightingIntensity](ue_ue.DirectionalLightComponent.md#indirectlightingintensity)
- [Intensity](ue_ue.DirectionalLightComponent.md#intensity)
- [InverseSquaredFalloff](ue_ue.DirectionalLightComponent.md#inversesquaredfalloff)
- [LightColor](ue_ue.DirectionalLightComponent.md#lightcolor)
- [LightFunctionFadeDistance](ue_ue.DirectionalLightComponent.md#lightfunctionfadedistance)
- [LightFunctionMaterial](ue_ue.DirectionalLightComponent.md#lightfunctionmaterial)
- [LightFunctionScale](ue_ue.DirectionalLightComponent.md#lightfunctionscale)
- [LightGuid](ue_ue.DirectionalLightComponent.md#lightguid)
- [LightShaftOverrideDirection](ue_ue.DirectionalLightComponent.md#lightshaftoverridedirection)
- [LightSourceAngle](ue_ue.DirectionalLightComponent.md#lightsourceangle)
- [LightSourceSoftAngle](ue_ue.DirectionalLightComponent.md#lightsourcesoftangle)
- [LightingChannels](ue_ue.DirectionalLightComponent.md#lightingchannels)
- [LightmassSettings](ue_ue.DirectionalLightComponent.md#lightmasssettings)
- [MaxDistanceFadeRange](ue_ue.DirectionalLightComponent.md#maxdistancefaderange)
- [MaxDrawDistance](ue_ue.DirectionalLightComponent.md#maxdrawdistance)
- [MinRoughness](ue_ue.DirectionalLightComponent.md#minroughness)
- [Mobility](ue_ue.DirectionalLightComponent.md#mobility)
- [ModulatedShadowColor](ue_ue.DirectionalLightComponent.md#modulatedshadowcolor)
- [OcclusionDepthRange](ue_ue.DirectionalLightComponent.md#occlusiondepthrange)
- [OcclusionMaskDarkness](ue_ue.DirectionalLightComponent.md#occlusionmaskdarkness)
- [OnComponentActivated](ue_ue.DirectionalLightComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.DirectionalLightComponent.md#oncomponentdeactivated)
- [PhysicsVolume](ue_ue.DirectionalLightComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.DirectionalLightComponent.md#physicsvolumechangeddelegate)
- [PrimaryComponentTick](ue_ue.DirectionalLightComponent.md#primarycomponenttick)
- [RayStartOffsetDepthScale](ue_ue.DirectionalLightComponent.md#raystartoffsetdepthscale)
- [RelativeLocation](ue_ue.DirectionalLightComponent.md#relativelocation)
- [RelativeRotation](ue_ue.DirectionalLightComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.DirectionalLightComponent.md#relativescale3d)
- [SamplesPerPixel](ue_ue.DirectionalLightComponent.md#samplesperpixel)
- [ShadowAmount](ue_ue.DirectionalLightComponent.md#shadowamount)
- [ShadowBias](ue_ue.DirectionalLightComponent.md#shadowbias)
- [ShadowCascadeBiasDistribution](ue_ue.DirectionalLightComponent.md#shadowcascadebiasdistribution)
- [ShadowDistanceFadeoutFraction](ue_ue.DirectionalLightComponent.md#shadowdistancefadeoutfraction)
- [ShadowMapChannel](ue_ue.DirectionalLightComponent.md#shadowmapchannel)
- [ShadowResolutionScale](ue_ue.DirectionalLightComponent.md#shadowresolutionscale)
- [ShadowSharpen](ue_ue.DirectionalLightComponent.md#shadowsharpen)
- [ShadowSlopeBias](ue_ue.DirectionalLightComponent.md#shadowslopebias)
- [SpecularScale](ue_ue.DirectionalLightComponent.md#specularscale)
- [StaticEditorTexture](ue_ue.DirectionalLightComponent.md#staticeditortexture)
- [StaticEditorTextureScale](ue_ue.DirectionalLightComponent.md#staticeditortexturescale)
- [Temperature](ue_ue.DirectionalLightComponent.md#temperature)
- [TraceDistance](ue_ue.DirectionalLightComponent.md#tracedistance)
- [UCSModifiedProperties](ue_ue.DirectionalLightComponent.md#ucsmodifiedproperties)
- [VolumetricScatteringIntensity](ue_ue.DirectionalLightComponent.md#volumetricscatteringintensity)
- [WholeSceneDynamicShadowRadius](ue_ue.DirectionalLightComponent.md#wholescenedynamicshadowradius)
- [\_\_tid\_ActorComponent\_\_](ue_ue.DirectionalLightComponent.md#__tid_actorcomponent__)
- [\_\_tid\_DirectionalLightComponent\_\_](ue_ue.DirectionalLightComponent.md#__tid_directionallightcomponent__)
- [\_\_tid\_LightComponentBase\_\_](ue_ue.DirectionalLightComponent.md#__tid_lightcomponentbase__)
- [\_\_tid\_LightComponent\_\_](ue_ue.DirectionalLightComponent.md#__tid_lightcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.DirectionalLightComponent.md#__tid_object__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.DirectionalLightComponent.md#__tid_scenecomponent__)
- [bAbsoluteLocation](ue_ue.DirectionalLightComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.DirectionalLightComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.DirectionalLightComponent.md#babsolutescale)
- [bAffectDynamicIndirectLighting](ue_ue.DirectionalLightComponent.md#baffectdynamicindirectlighting)
- [bAffectGlobalIllumination](ue_ue.DirectionalLightComponent.md#baffectglobalillumination)
- [bAffectReflection](ue_ue.DirectionalLightComponent.md#baffectreflection)
- [bAffectTranslucentLighting](ue_ue.DirectionalLightComponent.md#baffecttranslucentlighting)
- [bAffectsWorld](ue_ue.DirectionalLightComponent.md#baffectsworld)
- [bAutoActivate](ue_ue.DirectionalLightComponent.md#bautoactivate)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.DirectionalLightComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.DirectionalLightComponent.md#bcaneveraffectnavigation)
- [bCastDeepShadow](ue_ue.DirectionalLightComponent.md#bcastdeepshadow)
- [bCastModulatedShadows](ue_ue.DirectionalLightComponent.md#bcastmodulatedshadows)
- [bCastRaytracedShadow](ue_ue.DirectionalLightComponent.md#bcastraytracedshadow)
- [bCastShadowsFromCinematicObjectsOnly](ue_ue.DirectionalLightComponent.md#bcastshadowsfromcinematicobjectsonly)
- [bCastVolumetricShadow](ue_ue.DirectionalLightComponent.md#bcastvolumetricshadow)
- [bComponentToWorldUpdated](ue_ue.DirectionalLightComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.DirectionalLightComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.DirectionalLightComponent.md#beditablewheninherited)
- [bEnableLightShaftBloom](ue_ue.DirectionalLightComponent.md#benablelightshaftbloom)
- [bEnableLightShaftOcclusion](ue_ue.DirectionalLightComponent.md#benablelightshaftocclusion)
- [bForceCachedShadowsForMovablePrimitives](ue_ue.DirectionalLightComponent.md#bforcecachedshadowsformovableprimitives)
- [bHiddenInGame](ue_ue.DirectionalLightComponent.md#bhiddeningame)
- [bInstanceComponent](ue_ue.DirectionalLightComponent.md#binstancecomponent)
- [bIsActive](ue_ue.DirectionalLightComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.DirectionalLightComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.DirectionalLightComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.DirectionalLightComponent.md#bnetaddressable)
- [bReplicates](ue_ue.DirectionalLightComponent.md#breplicates)
- [bShouldBeAttached](ue_ue.DirectionalLightComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.DirectionalLightComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.DirectionalLightComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.DirectionalLightComponent.md#bshouldupdatephysicsvolume)
- [bTransmission](ue_ue.DirectionalLightComponent.md#btransmission)
- [bUseAttachParentBound](ue_ue.DirectionalLightComponent.md#buseattachparentbound)
- [bUseIESBrightness](ue_ue.DirectionalLightComponent.md#buseiesbrightness)
- [bUseInsetShadowsForMovableObjects](ue_ue.DirectionalLightComponent.md#buseinsetshadowsformovableobjects)
- [bUseRayTracedDistanceFieldShadows](ue_ue.DirectionalLightComponent.md#buseraytraceddistancefieldshadows)
- [bUseTemperature](ue_ue.DirectionalLightComponent.md#busetemperature)
- [bUsedAsAtmosphereSunLight](ue_ue.DirectionalLightComponent.md#busedasatmospheresunlight)
- [bVisible](ue_ue.DirectionalLightComponent.md#bvisible)
- [bVisualizeComponent](ue_ue.DirectionalLightComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.DirectionalLightComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.DirectionalLightComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.DirectionalLightComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.DirectionalLightComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.DirectionalLightComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.DirectionalLightComponent.md#deactivate)
- [DetachFromParent](ue_ue.DirectionalLightComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.DirectionalLightComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.DirectionalLightComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.DirectionalLightComponent.md#getallsocketnames)
- [GetAttachParent](ue_ue.DirectionalLightComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.DirectionalLightComponent.md#getattachsocketname)
- [GetChildComponent](ue_ue.DirectionalLightComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.DirectionalLightComponent.md#getchildrencomponents)
- [GetClass](ue_ue.DirectionalLightComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.DirectionalLightComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.DirectionalLightComponent.md#getcomponentvelocity)
- [GetForwardVector](ue_ue.DirectionalLightComponent.md#getforwardvector)
- [GetLightColor](ue_ue.DirectionalLightComponent.md#getlightcolor)
- [GetName](ue_ue.DirectionalLightComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.DirectionalLightComponent.md#getnumchildrencomponents)
- [GetOuter](ue_ue.DirectionalLightComponent.md#getouter)
- [GetOwner](ue_ue.DirectionalLightComponent.md#getowner)
- [GetParentComponents](ue_ue.DirectionalLightComponent.md#getparentcomponents)
- [GetPhysicsVolume](ue_ue.DirectionalLightComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.DirectionalLightComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.DirectionalLightComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.DirectionalLightComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.DirectionalLightComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.DirectionalLightComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.DirectionalLightComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.DirectionalLightComponent.md#getsockettransform)
- [GetUpVector](ue_ue.DirectionalLightComponent.md#getupvector)
- [GetWorld](ue_ue.DirectionalLightComponent.md#getworld)
- [IsActive](ue_ue.DirectionalLightComponent.md#isactive)
- [IsAnySimulatingPhysics](ue_ue.DirectionalLightComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.DirectionalLightComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.DirectionalLightComponent.md#iscomponenttickenabled)
- [IsSimulatingPhysics](ue_ue.DirectionalLightComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.DirectionalLightComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.DirectionalLightComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.DirectionalLightComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.DirectionalLightComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.DirectionalLightComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.DirectionalLightComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.DirectionalLightComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.DirectionalLightComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.DirectionalLightComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.DirectionalLightComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.DirectionalLightComponent.md#k2_attachtocomponent)
- [K2\_DestroyComponent](ue_ue.DirectionalLightComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.DirectionalLightComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.DirectionalLightComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.DirectionalLightComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.DirectionalLightComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.DirectionalLightComponent.md#k2_getcomponenttoworld)
- [K2\_SetRelativeLocation](ue_ue.DirectionalLightComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.DirectionalLightComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.DirectionalLightComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.DirectionalLightComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.DirectionalLightComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.DirectionalLightComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.DirectionalLightComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.DirectionalLightComponent.md#k2_setworldtransform)
- [OnRep\_AttachChildren](ue_ue.DirectionalLightComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.DirectionalLightComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.DirectionalLightComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.DirectionalLightComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.DirectionalLightComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.DirectionalLightComponent.md#onrep_visibility)
- [ReceiveBeginPlay](ue_ue.DirectionalLightComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.DirectionalLightComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.DirectionalLightComponent.md#receivetick)
- [RegisterComponent](ue_ue.DirectionalLightComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.DirectionalLightComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.DirectionalLightComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.DirectionalLightComponent.md#resetrelativetransform)
- [SetAbsolute](ue_ue.DirectionalLightComponent.md#setabsolute)
- [SetActive](ue_ue.DirectionalLightComponent.md#setactive)
- [SetAffectDynamicIndirectLighting](ue_ue.DirectionalLightComponent.md#setaffectdynamicindirectlighting)
- [SetAffectGlobalIllumination](ue_ue.DirectionalLightComponent.md#setaffectglobalillumination)
- [SetAffectReflection](ue_ue.DirectionalLightComponent.md#setaffectreflection)
- [SetAffectTranslucentLighting](ue_ue.DirectionalLightComponent.md#setaffecttranslucentlighting)
- [SetAutoActivate](ue_ue.DirectionalLightComponent.md#setautoactivate)
- [SetBloomMaxBrightness](ue_ue.DirectionalLightComponent.md#setbloommaxbrightness)
- [SetBloomScale](ue_ue.DirectionalLightComponent.md#setbloomscale)
- [SetBloomThreshold](ue_ue.DirectionalLightComponent.md#setbloomthreshold)
- [SetBloomTint](ue_ue.DirectionalLightComponent.md#setbloomtint)
- [SetCascadeDistributionExponent](ue_ue.DirectionalLightComponent.md#setcascadedistributionexponent)
- [SetCascadeTransitionFraction](ue_ue.DirectionalLightComponent.md#setcascadetransitionfraction)
- [SetCastDeepShadow](ue_ue.DirectionalLightComponent.md#setcastdeepshadow)
- [SetCastRaytracedShadow](ue_ue.DirectionalLightComponent.md#setcastraytracedshadow)
- [SetCastShadows](ue_ue.DirectionalLightComponent.md#setcastshadows)
- [SetCastVolumetricShadow](ue_ue.DirectionalLightComponent.md#setcastvolumetricshadow)
- [SetComponentTickEnabled](ue_ue.DirectionalLightComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.DirectionalLightComponent.md#setcomponenttickinterval)
- [SetDynamicShadowCascades](ue_ue.DirectionalLightComponent.md#setdynamicshadowcascades)
- [SetDynamicShadowDistanceMovableLight](ue_ue.DirectionalLightComponent.md#setdynamicshadowdistancemovablelight)
- [SetDynamicShadowDistanceStationaryLight](ue_ue.DirectionalLightComponent.md#setdynamicshadowdistancestationarylight)
- [SetEnableLightShaftBloom](ue_ue.DirectionalLightComponent.md#setenablelightshaftbloom)
- [SetEnableLightShaftOcclusion](ue_ue.DirectionalLightComponent.md#setenablelightshaftocclusion)
- [SetForceCachedShadowsForMovablePrimitives](ue_ue.DirectionalLightComponent.md#setforcecachedshadowsformovableprimitives)
- [SetHiddenInGame](ue_ue.DirectionalLightComponent.md#sethiddeningame)
- [SetIESBrightnessScale](ue_ue.DirectionalLightComponent.md#setiesbrightnessscale)
- [SetIESTexture](ue_ue.DirectionalLightComponent.md#setiestexture)
- [SetIndirectLightingIntensity](ue_ue.DirectionalLightComponent.md#setindirectlightingintensity)
- [SetIntensity](ue_ue.DirectionalLightComponent.md#setintensity)
- [SetIsReplicated](ue_ue.DirectionalLightComponent.md#setisreplicated)
- [SetLightColor](ue_ue.DirectionalLightComponent.md#setlightcolor)
- [SetLightFunctionDisabledBrightness](ue_ue.DirectionalLightComponent.md#setlightfunctiondisabledbrightness)
- [SetLightFunctionFadeDistance](ue_ue.DirectionalLightComponent.md#setlightfunctionfadedistance)
- [SetLightFunctionMaterial](ue_ue.DirectionalLightComponent.md#setlightfunctionmaterial)
- [SetLightFunctionScale](ue_ue.DirectionalLightComponent.md#setlightfunctionscale)
- [SetLightShaftOverrideDirection](ue_ue.DirectionalLightComponent.md#setlightshaftoverridedirection)
- [SetMobility](ue_ue.DirectionalLightComponent.md#setmobility)
- [SetOcclusionMaskDarkness](ue_ue.DirectionalLightComponent.md#setocclusionmaskdarkness)
- [SetRelativeScale3D](ue_ue.DirectionalLightComponent.md#setrelativescale3d)
- [SetSamplesPerPixel](ue_ue.DirectionalLightComponent.md#setsamplesperpixel)
- [SetShadowAmount](ue_ue.DirectionalLightComponent.md#setshadowamount)
- [SetShadowBias](ue_ue.DirectionalLightComponent.md#setshadowbias)
- [SetShadowDistanceFadeoutFraction](ue_ue.DirectionalLightComponent.md#setshadowdistancefadeoutfraction)
- [SetShadowSlopeBias](ue_ue.DirectionalLightComponent.md#setshadowslopebias)
- [SetShouldUpdatePhysicsVolume](ue_ue.DirectionalLightComponent.md#setshouldupdatephysicsvolume)
- [SetSpecularScale](ue_ue.DirectionalLightComponent.md#setspecularscale)
- [SetTemperature](ue_ue.DirectionalLightComponent.md#settemperature)
- [SetTickGroup](ue_ue.DirectionalLightComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.DirectionalLightComponent.md#settickablewhenpaused)
- [SetTransmission](ue_ue.DirectionalLightComponent.md#settransmission)
- [SetUseIESBrightness](ue_ue.DirectionalLightComponent.md#setuseiesbrightness)
- [SetVisibility](ue_ue.DirectionalLightComponent.md#setvisibility)
- [SetVolumetricScatteringIntensity](ue_ue.DirectionalLightComponent.md#setvolumetricscatteringintensity)
- [SetWorldScale3D](ue_ue.DirectionalLightComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.DirectionalLightComponent.md#setupattachment)
- [SnapTo](ue_ue.DirectionalLightComponent.md#snapto)
- [ToggleActive](ue_ue.DirectionalLightComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.DirectionalLightComponent.md#togglevisibility)
- [Find](ue_ue.DirectionalLightComponent.md#find)
- [Load](ue_ue.DirectionalLightComponent.md#load)
- [StaticClass](ue_ue.DirectionalLightComponent.md#staticclass)

## Constructors

### constructor

• **new DirectionalLightComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[LightComponent](ue_ue.LightComponent.md).[constructor](ue_ue.LightComponent.md#constructor)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[AssetUserData](ue_ue.LightComponent.md#assetuserdata)

___

### AtmosphereSunLightIndex

• **AtmosphereSunLightIndex**: `number`

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[AttachChildren](ue_ue.LightComponent.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[AttachParent](ue_ue.LightComponent.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[AttachSocketName](ue_ue.LightComponent.md#attachsocketname)

___

### BloomMaxBrightness

• **BloomMaxBrightness**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[BloomMaxBrightness](ue_ue.LightComponent.md#bloommaxbrightness)

___

### BloomScale

• **BloomScale**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[BloomScale](ue_ue.LightComponent.md#bloomscale)

___

### BloomThreshold

• **BloomThreshold**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[BloomThreshold](ue_ue.LightComponent.md#bloomthreshold)

___

### BloomTint

• **BloomTint**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[BloomTint](ue_ue.LightComponent.md#bloomtint)

___

### Brightness

• **Brightness**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[Brightness](ue_ue.LightComponent.md#brightness)

___

### CascadeDistributionExponent

• **CascadeDistributionExponent**: `number`

___

### CascadeTransitionFraction

• **CascadeTransitionFraction**: `number`

___

### CastDynamicShadows

• **CastDynamicShadows**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[CastDynamicShadows](ue_ue.LightComponent.md#castdynamicshadows)

___

### CastShadows

• **CastShadows**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[CastShadows](ue_ue.LightComponent.md#castshadows)

___

### CastStaticShadows

• **CastStaticShadows**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[CastStaticShadows](ue_ue.LightComponent.md#caststaticshadows)

___

### CastTranslucentShadows

• **CastTranslucentShadows**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[CastTranslucentShadows](ue_ue.LightComponent.md#casttranslucentshadows)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[ClientAttachedChildren](ue_ue.LightComponent.md#clientattachedchildren)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[ComponentTags](ue_ue.LightComponent.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[ComponentVelocity](ue_ue.LightComponent.md#componentvelocity)

___

### ContactShadowLength

• **ContactShadowLength**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[ContactShadowLength](ue_ue.LightComponent.md#contactshadowlength)

___

### ContactShadowLengthInWS

• **ContactShadowLengthInWS**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[ContactShadowLengthInWS](ue_ue.LightComponent.md#contactshadowlengthinws)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[CreationMethod](ue_ue.LightComponent.md#creationmethod)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[DetailMode](ue_ue.LightComponent.md#detailmode)

___

### DisabledBrightness

• **DisabledBrightness**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[DisabledBrightness](ue_ue.LightComponent.md#disabledbrightness)

___

### DistanceFieldShadowDistance

• **DistanceFieldShadowDistance**: `number`

___

### DynamicEditorTexture

• **DynamicEditorTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[DynamicEditorTexture](ue_ue.LightComponent.md#dynamiceditortexture)

___

### DynamicEditorTextureScale

• **DynamicEditorTextureScale**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[DynamicEditorTextureScale](ue_ue.LightComponent.md#dynamiceditortexturescale)

___

### DynamicShadowCascades

• **DynamicShadowCascades**: `number`

___

### DynamicShadowDistanceMovableLight

• **DynamicShadowDistanceMovableLight**: `number`

___

### DynamicShadowDistanceStationaryLight

• **DynamicShadowDistanceStationaryLight**: `number`

___

### FarShadowCascadeCount

• **FarShadowCascadeCount**: `number`

___

### FarShadowDistance

• **FarShadowDistance**: `number`

___

### IESBrightnessScale

• **IESBrightnessScale**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[IESBrightnessScale](ue_ue.LightComponent.md#iesbrightnessscale)

___

### IESTexture

• **IESTexture**: [`TextureLightProfile`](ue_ue.TextureLightProfile.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[IESTexture](ue_ue.LightComponent.md#iestexture)

___

### IndirectLightingIntensity

• **IndirectLightingIntensity**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[IndirectLightingIntensity](ue_ue.LightComponent.md#indirectlightingintensity)

___

### Intensity

• **Intensity**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[Intensity](ue_ue.LightComponent.md#intensity)

___

### InverseSquaredFalloff

• **InverseSquaredFalloff**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[InverseSquaredFalloff](ue_ue.LightComponent.md#inversesquaredfalloff)

___

### LightColor

• **LightColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[LightColor](ue_ue.LightComponent.md#lightcolor)

___

### LightFunctionFadeDistance

• **LightFunctionFadeDistance**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[LightFunctionFadeDistance](ue_ue.LightComponent.md#lightfunctionfadedistance)

___

### LightFunctionMaterial

• **LightFunctionMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[LightFunctionMaterial](ue_ue.LightComponent.md#lightfunctionmaterial)

___

### LightFunctionScale

• **LightFunctionScale**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[LightFunctionScale](ue_ue.LightComponent.md#lightfunctionscale)

___

### LightGuid

• **LightGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[LightGuid](ue_ue.LightComponent.md#lightguid)

___

### LightShaftOverrideDirection

• **LightShaftOverrideDirection**: [`Vector`](ue_ue_s.Vector.md)

___

### LightSourceAngle

• **LightSourceAngle**: `number`

___

### LightSourceSoftAngle

• **LightSourceSoftAngle**: `number`

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[LightingChannels](ue_ue.LightComponent.md#lightingchannels)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassDirectionalLightSettings`](ue_ue.LightmassDirectionalLightSettings.md)

___

### MaxDistanceFadeRange

• **MaxDistanceFadeRange**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[MaxDistanceFadeRange](ue_ue.LightComponent.md#maxdistancefaderange)

___

### MaxDrawDistance

• **MaxDrawDistance**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[MaxDrawDistance](ue_ue.LightComponent.md#maxdrawdistance)

___

### MinRoughness

• **MinRoughness**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[MinRoughness](ue_ue.LightComponent.md#minroughness)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[Mobility](ue_ue.LightComponent.md#mobility)

___

### ModulatedShadowColor

• **ModulatedShadowColor**: [`Color`](ue_ue_s.Color.md)

___

### OcclusionDepthRange

• **OcclusionDepthRange**: `number`

___

### OcclusionMaskDarkness

• **OcclusionMaskDarkness**: `number`

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[OnComponentActivated](ue_ue.LightComponent.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[OnComponentDeactivated](ue_ue.LightComponent.md#oncomponentdeactivated)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[PhysicsVolume](ue_ue.LightComponent.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.LightComponent.md#physicsvolumechangeddelegate)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[PrimaryComponentTick](ue_ue.LightComponent.md#primarycomponenttick)

___

### RayStartOffsetDepthScale

• **RayStartOffsetDepthScale**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[RayStartOffsetDepthScale](ue_ue.LightComponent.md#raystartoffsetdepthscale)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[RelativeLocation](ue_ue.LightComponent.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[RelativeRotation](ue_ue.LightComponent.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[RelativeScale3D](ue_ue.LightComponent.md#relativescale3d)

___

### SamplesPerPixel

• **SamplesPerPixel**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SamplesPerPixel](ue_ue.LightComponent.md#samplesperpixel)

___

### ShadowAmount

• **ShadowAmount**: `number`

___

### ShadowBias

• **ShadowBias**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[ShadowBias](ue_ue.LightComponent.md#shadowbias)

___

### ShadowCascadeBiasDistribution

• **ShadowCascadeBiasDistribution**: `number`

___

### ShadowDistanceFadeoutFraction

• **ShadowDistanceFadeoutFraction**: `number`

___

### ShadowMapChannel

• **ShadowMapChannel**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[ShadowMapChannel](ue_ue.LightComponent.md#shadowmapchannel)

___

### ShadowResolutionScale

• **ShadowResolutionScale**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[ShadowResolutionScale](ue_ue.LightComponent.md#shadowresolutionscale)

___

### ShadowSharpen

• **ShadowSharpen**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[ShadowSharpen](ue_ue.LightComponent.md#shadowsharpen)

___

### ShadowSlopeBias

• **ShadowSlopeBias**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[ShadowSlopeBias](ue_ue.LightComponent.md#shadowslopebias)

___

### SpecularScale

• **SpecularScale**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SpecularScale](ue_ue.LightComponent.md#specularscale)

___

### StaticEditorTexture

• **StaticEditorTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[StaticEditorTexture](ue_ue.LightComponent.md#staticeditortexture)

___

### StaticEditorTextureScale

• **StaticEditorTextureScale**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[StaticEditorTextureScale](ue_ue.LightComponent.md#staticeditortexturescale)

___

### Temperature

• **Temperature**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[Temperature](ue_ue.LightComponent.md#temperature)

___

### TraceDistance

• **TraceDistance**: `number`

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[UCSModifiedProperties](ue_ue.LightComponent.md#ucsmodifiedproperties)

___

### VolumetricScatteringIntensity

• **VolumetricScatteringIntensity**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[VolumetricScatteringIntensity](ue_ue.LightComponent.md#volumetricscatteringintensity)

___

### WholeSceneDynamicShadowRadius

• **WholeSceneDynamicShadowRadius**: `number`

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[__tid_ActorComponent__](ue_ue.LightComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_DirectionalLightComponent\_\_

• **\_\_tid\_DirectionalLightComponent\_\_**: `boolean`

___

### \_\_tid\_LightComponentBase\_\_

• **\_\_tid\_LightComponentBase\_\_**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[__tid_LightComponentBase__](ue_ue.LightComponent.md#__tid_lightcomponentbase__)

___

### \_\_tid\_LightComponent\_\_

• **\_\_tid\_LightComponent\_\_**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[__tid_LightComponent__](ue_ue.LightComponent.md#__tid_lightcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[__tid_Object__](ue_ue.LightComponent.md#__tid_object__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[__tid_SceneComponent__](ue_ue.LightComponent.md#__tid_scenecomponent__)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bAbsoluteLocation](ue_ue.LightComponent.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bAbsoluteRotation](ue_ue.LightComponent.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bAbsoluteScale](ue_ue.LightComponent.md#babsolutescale)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bAffectDynamicIndirectLighting](ue_ue.LightComponent.md#baffectdynamicindirectlighting)

___

### bAffectGlobalIllumination

• **bAffectGlobalIllumination**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bAffectGlobalIllumination](ue_ue.LightComponent.md#baffectglobalillumination)

___

### bAffectReflection

• **bAffectReflection**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bAffectReflection](ue_ue.LightComponent.md#baffectreflection)

___

### bAffectTranslucentLighting

• **bAffectTranslucentLighting**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bAffectTranslucentLighting](ue_ue.LightComponent.md#baffecttranslucentlighting)

___

### bAffectsWorld

• **bAffectsWorld**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bAffectsWorld](ue_ue.LightComponent.md#baffectsworld)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bAutoActivate](ue_ue.LightComponent.md#bautoactivate)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.LightComponent.md#bboundschangetriggersstreamingdatarebuild)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bCanEverAffectNavigation](ue_ue.LightComponent.md#bcaneveraffectnavigation)

___

### bCastDeepShadow

• **bCastDeepShadow**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bCastDeepShadow](ue_ue.LightComponent.md#bcastdeepshadow)

___

### bCastModulatedShadows

• **bCastModulatedShadows**: `boolean`

___

### bCastRaytracedShadow

• **bCastRaytracedShadow**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bCastRaytracedShadow](ue_ue.LightComponent.md#bcastraytracedshadow)

___

### bCastShadowsFromCinematicObjectsOnly

• **bCastShadowsFromCinematicObjectsOnly**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bCastShadowsFromCinematicObjectsOnly](ue_ue.LightComponent.md#bcastshadowsfromcinematicobjectsonly)

___

### bCastVolumetricShadow

• **bCastVolumetricShadow**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bCastVolumetricShadow](ue_ue.LightComponent.md#bcastvolumetricshadow)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bComponentToWorldUpdated](ue_ue.LightComponent.md#bcomponenttoworldupdated)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bCreatedByConstructionScript](ue_ue.LightComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bEditableWhenInherited](ue_ue.LightComponent.md#beditablewheninherited)

___

### bEnableLightShaftBloom

• **bEnableLightShaftBloom**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bEnableLightShaftBloom](ue_ue.LightComponent.md#benablelightshaftbloom)

___

### bEnableLightShaftOcclusion

• **bEnableLightShaftOcclusion**: `boolean`

___

### bForceCachedShadowsForMovablePrimitives

• **bForceCachedShadowsForMovablePrimitives**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bForceCachedShadowsForMovablePrimitives](ue_ue.LightComponent.md#bforcecachedshadowsformovableprimitives)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bHiddenInGame](ue_ue.LightComponent.md#bhiddeningame)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bInstanceComponent](ue_ue.LightComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bIsActive](ue_ue.LightComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bIsEditorOnly](ue_ue.LightComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bIsVisualizationComponent](ue_ue.LightComponent.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bNetAddressable](ue_ue.LightComponent.md#bnetaddressable)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bReplicates](ue_ue.LightComponent.md#breplicates)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bShouldBeAttached](ue_ue.LightComponent.md#bshouldbeattached)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.LightComponent.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.LightComponent.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.LightComponent.md#bshouldupdatephysicsvolume)

___

### bTransmission

• **bTransmission**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bTransmission](ue_ue.LightComponent.md#btransmission)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bUseAttachParentBound](ue_ue.LightComponent.md#buseattachparentbound)

___

### bUseIESBrightness

• **bUseIESBrightness**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bUseIESBrightness](ue_ue.LightComponent.md#buseiesbrightness)

___

### bUseInsetShadowsForMovableObjects

• **bUseInsetShadowsForMovableObjects**: `boolean`

___

### bUseRayTracedDistanceFieldShadows

• **bUseRayTracedDistanceFieldShadows**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bUseRayTracedDistanceFieldShadows](ue_ue.LightComponent.md#buseraytraceddistancefieldshadows)

___

### bUseTemperature

• **bUseTemperature**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bUseTemperature](ue_ue.LightComponent.md#busetemperature)

___

### bUsedAsAtmosphereSunLight

• **bUsedAsAtmosphereSunLight**: `boolean`

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bVisible](ue_ue.LightComponent.md#bvisible)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[bVisualizeComponent](ue_ue.LightComponent.md#bvisualizecomponent)

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

[LightComponent](ue_ue.LightComponent.md).[Activate](ue_ue.LightComponent.md#activate)

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

[LightComponent](ue_ue.LightComponent.md).[AddTickPrerequisiteActor](ue_ue.LightComponent.md#addtickprerequisiteactor)

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

[LightComponent](ue_ue.LightComponent.md).[AddTickPrerequisiteComponent](ue_ue.LightComponent.md#addtickprerequisitecomponent)

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

[LightComponent](ue_ue.LightComponent.md).[ComponentHasTag](ue_ue.LightComponent.md#componenthastag)

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

[LightComponent](ue_ue.LightComponent.md).[CreateDefaultSubobject](ue_ue.LightComponent.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[Deactivate](ue_ue.LightComponent.md#deactivate)

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

[LightComponent](ue_ue.LightComponent.md).[DetachFromParent](ue_ue.LightComponent.md#detachfromparent)

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

[LightComponent](ue_ue.LightComponent.md).[DoesSocketExist](ue_ue.LightComponent.md#doessocketexist)

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

[LightComponent](ue_ue.LightComponent.md).[ExecuteUbergraph](ue_ue.LightComponent.md#executeubergraph)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetAllSocketNames](ue_ue.LightComponent.md#getallsocketnames)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetAttachParent](ue_ue.LightComponent.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetAttachSocketName](ue_ue.LightComponent.md#getattachsocketname)

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

[LightComponent](ue_ue.LightComponent.md).[GetChildComponent](ue_ue.LightComponent.md#getchildcomponent)

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

[LightComponent](ue_ue.LightComponent.md).[GetChildrenComponents](ue_ue.LightComponent.md#getchildrencomponents)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetClass](ue_ue.LightComponent.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetComponentTickInterval](ue_ue.LightComponent.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetComponentVelocity](ue_ue.LightComponent.md#getcomponentvelocity)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetForwardVector](ue_ue.LightComponent.md#getforwardvector)

___

### GetLightColor

▸ **GetLightColor**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetLightColor](ue_ue.LightComponent.md#getlightcolor)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetName](ue_ue.LightComponent.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetNumChildrenComponents](ue_ue.LightComponent.md#getnumchildrencomponents)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetOuter](ue_ue.LightComponent.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetOwner](ue_ue.LightComponent.md#getowner)

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

[LightComponent](ue_ue.LightComponent.md).[GetParentComponents](ue_ue.LightComponent.md#getparentcomponents)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetPhysicsVolume](ue_ue.LightComponent.md#getphysicsvolume)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetRelativeTransform](ue_ue.LightComponent.md#getrelativetransform)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetRightVector](ue_ue.LightComponent.md#getrightvector)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.LightComponent.md#getshouldupdatephysicsvolume)

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

[LightComponent](ue_ue.LightComponent.md).[GetSocketLocation](ue_ue.LightComponent.md#getsocketlocation)

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

[LightComponent](ue_ue.LightComponent.md).[GetSocketQuaternion](ue_ue.LightComponent.md#getsocketquaternion)

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

[LightComponent](ue_ue.LightComponent.md).[GetSocketRotation](ue_ue.LightComponent.md#getsocketrotation)

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

[LightComponent](ue_ue.LightComponent.md).[GetSocketTransform](ue_ue.LightComponent.md#getsockettransform)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetUpVector](ue_ue.LightComponent.md#getupvector)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[GetWorld](ue_ue.LightComponent.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[IsActive](ue_ue.LightComponent.md#isactive)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[IsAnySimulatingPhysics](ue_ue.LightComponent.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[IsBeingDestroyed](ue_ue.LightComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[IsComponentTickEnabled](ue_ue.LightComponent.md#iscomponenttickenabled)

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

[LightComponent](ue_ue.LightComponent.md).[IsSimulatingPhysics](ue_ue.LightComponent.md#issimulatingphysics)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[IsVisible](ue_ue.LightComponent.md#isvisible)

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

[LightComponent](ue_ue.LightComponent.md).[K2_AddLocalOffset](ue_ue.LightComponent.md#k2_addlocaloffset)

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

[LightComponent](ue_ue.LightComponent.md).[K2_AddLocalRotation](ue_ue.LightComponent.md#k2_addlocalrotation)

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

[LightComponent](ue_ue.LightComponent.md).[K2_AddLocalTransform](ue_ue.LightComponent.md#k2_addlocaltransform)

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

[LightComponent](ue_ue.LightComponent.md).[K2_AddRelativeLocation](ue_ue.LightComponent.md#k2_addrelativelocation)

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

[LightComponent](ue_ue.LightComponent.md).[K2_AddRelativeRotation](ue_ue.LightComponent.md#k2_addrelativerotation)

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

[LightComponent](ue_ue.LightComponent.md).[K2_AddWorldOffset](ue_ue.LightComponent.md#k2_addworldoffset)

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

[LightComponent](ue_ue.LightComponent.md).[K2_AddWorldRotation](ue_ue.LightComponent.md#k2_addworldrotation)

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

[LightComponent](ue_ue.LightComponent.md).[K2_AddWorldTransform](ue_ue.LightComponent.md#k2_addworldtransform)

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

[LightComponent](ue_ue.LightComponent.md).[K2_AttachTo](ue_ue.LightComponent.md#k2_attachto)

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

[LightComponent](ue_ue.LightComponent.md).[K2_AttachToComponent](ue_ue.LightComponent.md#k2_attachtocomponent)

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

[LightComponent](ue_ue.LightComponent.md).[K2_DestroyComponent](ue_ue.LightComponent.md#k2_destroycomponent)

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

[LightComponent](ue_ue.LightComponent.md).[K2_DetachFromComponent](ue_ue.LightComponent.md#k2_detachfromcomponent)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[K2_GetComponentLocation](ue_ue.LightComponent.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[K2_GetComponentRotation](ue_ue.LightComponent.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[K2_GetComponentScale](ue_ue.LightComponent.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[K2_GetComponentToWorld](ue_ue.LightComponent.md#k2_getcomponenttoworld)

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

[LightComponent](ue_ue.LightComponent.md).[K2_SetRelativeLocation](ue_ue.LightComponent.md#k2_setrelativelocation)

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

[LightComponent](ue_ue.LightComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.LightComponent.md#k2_setrelativelocationandrotation)

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

[LightComponent](ue_ue.LightComponent.md).[K2_SetRelativeRotation](ue_ue.LightComponent.md#k2_setrelativerotation)

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

[LightComponent](ue_ue.LightComponent.md).[K2_SetRelativeTransform](ue_ue.LightComponent.md#k2_setrelativetransform)

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

[LightComponent](ue_ue.LightComponent.md).[K2_SetWorldLocation](ue_ue.LightComponent.md#k2_setworldlocation)

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

[LightComponent](ue_ue.LightComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.LightComponent.md#k2_setworldlocationandrotation)

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

[LightComponent](ue_ue.LightComponent.md).[K2_SetWorldRotation](ue_ue.LightComponent.md#k2_setworldrotation)

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

[LightComponent](ue_ue.LightComponent.md).[K2_SetWorldTransform](ue_ue.LightComponent.md#k2_setworldtransform)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[OnRep_AttachChildren](ue_ue.LightComponent.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[OnRep_AttachParent](ue_ue.LightComponent.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[OnRep_AttachSocketName](ue_ue.LightComponent.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[OnRep_IsActive](ue_ue.LightComponent.md#onrep_isactive)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[OnRep_Transform](ue_ue.LightComponent.md#onrep_transform)

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

[LightComponent](ue_ue.LightComponent.md).[OnRep_Visibility](ue_ue.LightComponent.md#onrep_visibility)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[ReceiveBeginPlay](ue_ue.LightComponent.md#receivebeginplay)

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

[LightComponent](ue_ue.LightComponent.md).[ReceiveEndPlay](ue_ue.LightComponent.md#receiveendplay)

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

[LightComponent](ue_ue.LightComponent.md).[ReceiveTick](ue_ue.LightComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[RegisterComponent](ue_ue.LightComponent.md#registercomponent)

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

[LightComponent](ue_ue.LightComponent.md).[RemoveTickPrerequisiteActor](ue_ue.LightComponent.md#removetickprerequisiteactor)

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

[LightComponent](ue_ue.LightComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.LightComponent.md#removetickprerequisitecomponent)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[ResetRelativeTransform](ue_ue.LightComponent.md#resetrelativetransform)

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

[LightComponent](ue_ue.LightComponent.md).[SetAbsolute](ue_ue.LightComponent.md#setabsolute)

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

[LightComponent](ue_ue.LightComponent.md).[SetActive](ue_ue.LightComponent.md#setactive)

___

### SetAffectDynamicIndirectLighting

▸ **SetAffectDynamicIndirectLighting**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetAffectDynamicIndirectLighting](ue_ue.LightComponent.md#setaffectdynamicindirectlighting)

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

[LightComponent](ue_ue.LightComponent.md).[SetAffectGlobalIllumination](ue_ue.LightComponent.md#setaffectglobalillumination)

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

[LightComponent](ue_ue.LightComponent.md).[SetAffectReflection](ue_ue.LightComponent.md#setaffectreflection)

___

### SetAffectTranslucentLighting

▸ **SetAffectTranslucentLighting**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetAffectTranslucentLighting](ue_ue.LightComponent.md#setaffecttranslucentlighting)

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

[LightComponent](ue_ue.LightComponent.md).[SetAutoActivate](ue_ue.LightComponent.md#setautoactivate)

___

### SetBloomMaxBrightness

▸ **SetBloomMaxBrightness**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetBloomMaxBrightness](ue_ue.LightComponent.md#setbloommaxbrightness)

___

### SetBloomScale

▸ **SetBloomScale**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetBloomScale](ue_ue.LightComponent.md#setbloomscale)

___

### SetBloomThreshold

▸ **SetBloomThreshold**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetBloomThreshold](ue_ue.LightComponent.md#setbloomthreshold)

___

### SetBloomTint

▸ **SetBloomTint**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | [`Color`](ue_ue_s.Color.md) |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetBloomTint](ue_ue.LightComponent.md#setbloomtint)

___

### SetCascadeDistributionExponent

▸ **SetCascadeDistributionExponent**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

___

### SetCascadeTransitionFraction

▸ **SetCascadeTransitionFraction**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

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

[LightComponent](ue_ue.LightComponent.md).[SetCastDeepShadow](ue_ue.LightComponent.md#setcastdeepshadow)

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

[LightComponent](ue_ue.LightComponent.md).[SetCastRaytracedShadow](ue_ue.LightComponent.md#setcastraytracedshadow)

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

[LightComponent](ue_ue.LightComponent.md).[SetCastShadows](ue_ue.LightComponent.md#setcastshadows)

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

[LightComponent](ue_ue.LightComponent.md).[SetCastVolumetricShadow](ue_ue.LightComponent.md#setcastvolumetricshadow)

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

[LightComponent](ue_ue.LightComponent.md).[SetComponentTickEnabled](ue_ue.LightComponent.md#setcomponenttickenabled)

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

[LightComponent](ue_ue.LightComponent.md).[SetComponentTickInterval](ue_ue.LightComponent.md#setcomponenttickinterval)

___

### SetDynamicShadowCascades

▸ **SetDynamicShadowCascades**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

___

### SetDynamicShadowDistanceMovableLight

▸ **SetDynamicShadowDistanceMovableLight**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

___

### SetDynamicShadowDistanceStationaryLight

▸ **SetDynamicShadowDistanceStationaryLight**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

___

### SetEnableLightShaftBloom

▸ **SetEnableLightShaftBloom**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetEnableLightShaftBloom](ue_ue.LightComponent.md#setenablelightshaftbloom)

___

### SetEnableLightShaftOcclusion

▸ **SetEnableLightShaftOcclusion**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `boolean` |

#### Returns

`void`

___

### SetForceCachedShadowsForMovablePrimitives

▸ **SetForceCachedShadowsForMovablePrimitives**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetForceCachedShadowsForMovablePrimitives](ue_ue.LightComponent.md#setforcecachedshadowsformovableprimitives)

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

[LightComponent](ue_ue.LightComponent.md).[SetHiddenInGame](ue_ue.LightComponent.md#sethiddeningame)

___

### SetIESBrightnessScale

▸ **SetIESBrightnessScale**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetIESBrightnessScale](ue_ue.LightComponent.md#setiesbrightnessscale)

___

### SetIESTexture

▸ **SetIESTexture**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | [`$Nullable`](../modules/puerts.md#$nullable)<[`TextureLightProfile`](ue_ue.TextureLightProfile.md)\> |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetIESTexture](ue_ue.LightComponent.md#setiestexture)

___

### SetIndirectLightingIntensity

▸ **SetIndirectLightingIntensity**(`NewIntensity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewIntensity` | `number` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetIndirectLightingIntensity](ue_ue.LightComponent.md#setindirectlightingintensity)

___

### SetIntensity

▸ **SetIntensity**(`NewIntensity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewIntensity` | `number` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetIntensity](ue_ue.LightComponent.md#setintensity)

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

[LightComponent](ue_ue.LightComponent.md).[SetIsReplicated](ue_ue.LightComponent.md#setisreplicated)

___

### SetLightColor

▸ **SetLightColor**(`NewLightColor`, `bSRGB?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLightColor` | [`LinearColor`](ue_ue_s.LinearColor.md) |
| `bSRGB?` | `boolean` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetLightColor](ue_ue.LightComponent.md#setlightcolor)

___

### SetLightFunctionDisabledBrightness

▸ **SetLightFunctionDisabledBrightness**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetLightFunctionDisabledBrightness](ue_ue.LightComponent.md#setlightfunctiondisabledbrightness)

___

### SetLightFunctionFadeDistance

▸ **SetLightFunctionFadeDistance**(`NewLightFunctionFadeDistance`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLightFunctionFadeDistance` | `number` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetLightFunctionFadeDistance](ue_ue.LightComponent.md#setlightfunctionfadedistance)

___

### SetLightFunctionMaterial

▸ **SetLightFunctionMaterial**(`NewLightFunctionMaterial`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLightFunctionMaterial` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetLightFunctionMaterial](ue_ue.LightComponent.md#setlightfunctionmaterial)

___

### SetLightFunctionScale

▸ **SetLightFunctionScale**(`NewLightFunctionScale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLightFunctionScale` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetLightFunctionScale](ue_ue.LightComponent.md#setlightfunctionscale)

___

### SetLightShaftOverrideDirection

▸ **SetLightShaftOverrideDirection**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | [`Vector`](ue_ue_s.Vector.md) |

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

[LightComponent](ue_ue.LightComponent.md).[SetMobility](ue_ue.LightComponent.md#setmobility)

___

### SetOcclusionMaskDarkness

▸ **SetOcclusionMaskDarkness**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

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

[LightComponent](ue_ue.LightComponent.md).[SetRelativeScale3D](ue_ue.LightComponent.md#setrelativescale3d)

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

[LightComponent](ue_ue.LightComponent.md).[SetSamplesPerPixel](ue_ue.LightComponent.md#setsamplesperpixel)

___

### SetShadowAmount

▸ **SetShadowAmount**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

___

### SetShadowBias

▸ **SetShadowBias**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetShadowBias](ue_ue.LightComponent.md#setshadowbias)

___

### SetShadowDistanceFadeoutFraction

▸ **SetShadowDistanceFadeoutFraction**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

___

### SetShadowSlopeBias

▸ **SetShadowSlopeBias**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetShadowSlopeBias](ue_ue.LightComponent.md#setshadowslopebias)

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

[LightComponent](ue_ue.LightComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.LightComponent.md#setshouldupdatephysicsvolume)

___

### SetSpecularScale

▸ **SetSpecularScale**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetSpecularScale](ue_ue.LightComponent.md#setspecularscale)

___

### SetTemperature

▸ **SetTemperature**(`NewTemperature`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewTemperature` | `number` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetTemperature](ue_ue.LightComponent.md#settemperature)

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

[LightComponent](ue_ue.LightComponent.md).[SetTickGroup](ue_ue.LightComponent.md#settickgroup)

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

[LightComponent](ue_ue.LightComponent.md).[SetTickableWhenPaused](ue_ue.LightComponent.md#settickablewhenpaused)

___

### SetTransmission

▸ **SetTransmission**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetTransmission](ue_ue.LightComponent.md#settransmission)

___

### SetUseIESBrightness

▸ **SetUseIESBrightness**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `boolean` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetUseIESBrightness](ue_ue.LightComponent.md#setuseiesbrightness)

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

[LightComponent](ue_ue.LightComponent.md).[SetVisibility](ue_ue.LightComponent.md#setvisibility)

___

### SetVolumetricScatteringIntensity

▸ **SetVolumetricScatteringIntensity**(`NewIntensity`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewIntensity` | `number` |

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[SetVolumetricScatteringIntensity](ue_ue.LightComponent.md#setvolumetricscatteringintensity)

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

[LightComponent](ue_ue.LightComponent.md).[SetWorldScale3D](ue_ue.LightComponent.md#setworldscale3d)

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

[LightComponent](ue_ue.LightComponent.md).[SetupAttachment](ue_ue.LightComponent.md#setupattachment)

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

[LightComponent](ue_ue.LightComponent.md).[SnapTo](ue_ue.LightComponent.md#snapto)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[ToggleActive](ue_ue.LightComponent.md#toggleactive)

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

[LightComponent](ue_ue.LightComponent.md).[ToggleVisibility](ue_ue.LightComponent.md#togglevisibility)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`DirectionalLightComponent`](ue_ue.DirectionalLightComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`DirectionalLightComponent`](ue_ue.DirectionalLightComponent.md)

#### Overrides

[LightComponent](ue_ue.LightComponent.md).[Find](ue_ue.LightComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`DirectionalLightComponent`](ue_ue.DirectionalLightComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`DirectionalLightComponent`](ue_ue.DirectionalLightComponent.md)

#### Overrides

[LightComponent](ue_ue.LightComponent.md).[Load](ue_ue.LightComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[LightComponent](ue_ue.LightComponent.md).[StaticClass](ue_ue.LightComponent.md#staticclass)
