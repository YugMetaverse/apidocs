[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / SpotLightComponent

# Class: SpotLightComponent

[ue/ue](../modules/ue_ue.md).SpotLightComponent

## Hierarchy

- [`PointLightComponent`](ue_ue.PointLightComponent.md)

  ↳ **`SpotLightComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.SpotLightComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.SpotLightComponent.md#assetuserdata)
- [AttachChildren](ue_ue.SpotLightComponent.md#attachchildren)
- [AttachParent](ue_ue.SpotLightComponent.md#attachparent)
- [AttachSocketName](ue_ue.SpotLightComponent.md#attachsocketname)
- [AttenuationRadius](ue_ue.SpotLightComponent.md#attenuationradius)
- [BloomMaxBrightness](ue_ue.SpotLightComponent.md#bloommaxbrightness)
- [BloomScale](ue_ue.SpotLightComponent.md#bloomscale)
- [BloomThreshold](ue_ue.SpotLightComponent.md#bloomthreshold)
- [BloomTint](ue_ue.SpotLightComponent.md#bloomtint)
- [Brightness](ue_ue.SpotLightComponent.md#brightness)
- [CastDynamicShadows](ue_ue.SpotLightComponent.md#castdynamicshadows)
- [CastShadows](ue_ue.SpotLightComponent.md#castshadows)
- [CastStaticShadows](ue_ue.SpotLightComponent.md#caststaticshadows)
- [CastTranslucentShadows](ue_ue.SpotLightComponent.md#casttranslucentshadows)
- [ClientAttachedChildren](ue_ue.SpotLightComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.SpotLightComponent.md#componenttags)
- [ComponentVelocity](ue_ue.SpotLightComponent.md#componentvelocity)
- [ContactShadowLength](ue_ue.SpotLightComponent.md#contactshadowlength)
- [ContactShadowLengthInWS](ue_ue.SpotLightComponent.md#contactshadowlengthinws)
- [CreationMethod](ue_ue.SpotLightComponent.md#creationmethod)
- [DetailMode](ue_ue.SpotLightComponent.md#detailmode)
- [DisabledBrightness](ue_ue.SpotLightComponent.md#disabledbrightness)
- [DynamicEditorTexture](ue_ue.SpotLightComponent.md#dynamiceditortexture)
- [DynamicEditorTextureScale](ue_ue.SpotLightComponent.md#dynamiceditortexturescale)
- [IESBrightnessScale](ue_ue.SpotLightComponent.md#iesbrightnessscale)
- [IESTexture](ue_ue.SpotLightComponent.md#iestexture)
- [IndirectLightingIntensity](ue_ue.SpotLightComponent.md#indirectlightingintensity)
- [InnerConeAngle](ue_ue.SpotLightComponent.md#innerconeangle)
- [Intensity](ue_ue.SpotLightComponent.md#intensity)
- [IntensityUnits](ue_ue.SpotLightComponent.md#intensityunits)
- [InverseSquaredFalloff](ue_ue.SpotLightComponent.md#inversesquaredfalloff)
- [LightColor](ue_ue.SpotLightComponent.md#lightcolor)
- [LightFalloffExponent](ue_ue.SpotLightComponent.md#lightfalloffexponent)
- [LightFunctionFadeDistance](ue_ue.SpotLightComponent.md#lightfunctionfadedistance)
- [LightFunctionMaterial](ue_ue.SpotLightComponent.md#lightfunctionmaterial)
- [LightFunctionScale](ue_ue.SpotLightComponent.md#lightfunctionscale)
- [LightGuid](ue_ue.SpotLightComponent.md#lightguid)
- [LightShaftConeAngle](ue_ue.SpotLightComponent.md#lightshaftconeangle)
- [LightingChannels](ue_ue.SpotLightComponent.md#lightingchannels)
- [LightmassSettings](ue_ue.SpotLightComponent.md#lightmasssettings)
- [MaxDistanceFadeRange](ue_ue.SpotLightComponent.md#maxdistancefaderange)
- [MaxDrawDistance](ue_ue.SpotLightComponent.md#maxdrawdistance)
- [MinRoughness](ue_ue.SpotLightComponent.md#minroughness)
- [Mobility](ue_ue.SpotLightComponent.md#mobility)
- [OnComponentActivated](ue_ue.SpotLightComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.SpotLightComponent.md#oncomponentdeactivated)
- [OuterConeAngle](ue_ue.SpotLightComponent.md#outerconeangle)
- [PhysicsVolume](ue_ue.SpotLightComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.SpotLightComponent.md#physicsvolumechangeddelegate)
- [PrimaryComponentTick](ue_ue.SpotLightComponent.md#primarycomponenttick)
- [Radius](ue_ue.SpotLightComponent.md#radius)
- [RayStartOffsetDepthScale](ue_ue.SpotLightComponent.md#raystartoffsetdepthscale)
- [RelativeLocation](ue_ue.SpotLightComponent.md#relativelocation)
- [RelativeRotation](ue_ue.SpotLightComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.SpotLightComponent.md#relativescale3d)
- [SamplesPerPixel](ue_ue.SpotLightComponent.md#samplesperpixel)
- [ShadowBias](ue_ue.SpotLightComponent.md#shadowbias)
- [ShadowMapChannel](ue_ue.SpotLightComponent.md#shadowmapchannel)
- [ShadowResolutionScale](ue_ue.SpotLightComponent.md#shadowresolutionscale)
- [ShadowSharpen](ue_ue.SpotLightComponent.md#shadowsharpen)
- [ShadowSlopeBias](ue_ue.SpotLightComponent.md#shadowslopebias)
- [SoftSourceRadius](ue_ue.SpotLightComponent.md#softsourceradius)
- [SourceLength](ue_ue.SpotLightComponent.md#sourcelength)
- [SourceRadius](ue_ue.SpotLightComponent.md#sourceradius)
- [SpecularScale](ue_ue.SpotLightComponent.md#specularscale)
- [StaticEditorTexture](ue_ue.SpotLightComponent.md#staticeditortexture)
- [StaticEditorTextureScale](ue_ue.SpotLightComponent.md#staticeditortexturescale)
- [Temperature](ue_ue.SpotLightComponent.md#temperature)
- [UCSModifiedProperties](ue_ue.SpotLightComponent.md#ucsmodifiedproperties)
- [VolumetricScatteringIntensity](ue_ue.SpotLightComponent.md#volumetricscatteringintensity)
- [\_\_tid\_ActorComponent\_\_](ue_ue.SpotLightComponent.md#__tid_actorcomponent__)
- [\_\_tid\_LightComponentBase\_\_](ue_ue.SpotLightComponent.md#__tid_lightcomponentbase__)
- [\_\_tid\_LightComponent\_\_](ue_ue.SpotLightComponent.md#__tid_lightcomponent__)
- [\_\_tid\_LocalLightComponent\_\_](ue_ue.SpotLightComponent.md#__tid_locallightcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.SpotLightComponent.md#__tid_object__)
- [\_\_tid\_PointLightComponent\_\_](ue_ue.SpotLightComponent.md#__tid_pointlightcomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.SpotLightComponent.md#__tid_scenecomponent__)
- [\_\_tid\_SpotLightComponent\_\_](ue_ue.SpotLightComponent.md#__tid_spotlightcomponent__)
- [bAbsoluteLocation](ue_ue.SpotLightComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.SpotLightComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.SpotLightComponent.md#babsolutescale)
- [bAffectDynamicIndirectLighting](ue_ue.SpotLightComponent.md#baffectdynamicindirectlighting)
- [bAffectGlobalIllumination](ue_ue.SpotLightComponent.md#baffectglobalillumination)
- [bAffectReflection](ue_ue.SpotLightComponent.md#baffectreflection)
- [bAffectTranslucentLighting](ue_ue.SpotLightComponent.md#baffecttranslucentlighting)
- [bAffectsWorld](ue_ue.SpotLightComponent.md#baffectsworld)
- [bAutoActivate](ue_ue.SpotLightComponent.md#bautoactivate)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.SpotLightComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.SpotLightComponent.md#bcaneveraffectnavigation)
- [bCastDeepShadow](ue_ue.SpotLightComponent.md#bcastdeepshadow)
- [bCastRaytracedShadow](ue_ue.SpotLightComponent.md#bcastraytracedshadow)
- [bCastShadowsFromCinematicObjectsOnly](ue_ue.SpotLightComponent.md#bcastshadowsfromcinematicobjectsonly)
- [bCastVolumetricShadow](ue_ue.SpotLightComponent.md#bcastvolumetricshadow)
- [bComponentToWorldUpdated](ue_ue.SpotLightComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.SpotLightComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.SpotLightComponent.md#beditablewheninherited)
- [bEnableLightShaftBloom](ue_ue.SpotLightComponent.md#benablelightshaftbloom)
- [bForceCachedShadowsForMovablePrimitives](ue_ue.SpotLightComponent.md#bforcecachedshadowsformovableprimitives)
- [bHiddenInGame](ue_ue.SpotLightComponent.md#bhiddeningame)
- [bInstanceComponent](ue_ue.SpotLightComponent.md#binstancecomponent)
- [bIsActive](ue_ue.SpotLightComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.SpotLightComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.SpotLightComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.SpotLightComponent.md#bnetaddressable)
- [bReplicates](ue_ue.SpotLightComponent.md#breplicates)
- [bShouldBeAttached](ue_ue.SpotLightComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.SpotLightComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.SpotLightComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.SpotLightComponent.md#bshouldupdatephysicsvolume)
- [bTransmission](ue_ue.SpotLightComponent.md#btransmission)
- [bUseAttachParentBound](ue_ue.SpotLightComponent.md#buseattachparentbound)
- [bUseIESBrightness](ue_ue.SpotLightComponent.md#buseiesbrightness)
- [bUseInverseSquaredFalloff](ue_ue.SpotLightComponent.md#buseinversesquaredfalloff)
- [bUseRayTracedDistanceFieldShadows](ue_ue.SpotLightComponent.md#buseraytraceddistancefieldshadows)
- [bUseTemperature](ue_ue.SpotLightComponent.md#busetemperature)
- [bVisible](ue_ue.SpotLightComponent.md#bvisible)
- [bVisualizeComponent](ue_ue.SpotLightComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.SpotLightComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.SpotLightComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.SpotLightComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.SpotLightComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.SpotLightComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.SpotLightComponent.md#deactivate)
- [DetachFromParent](ue_ue.SpotLightComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.SpotLightComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.SpotLightComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.SpotLightComponent.md#getallsocketnames)
- [GetAttachParent](ue_ue.SpotLightComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.SpotLightComponent.md#getattachsocketname)
- [GetChildComponent](ue_ue.SpotLightComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.SpotLightComponent.md#getchildrencomponents)
- [GetClass](ue_ue.SpotLightComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.SpotLightComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.SpotLightComponent.md#getcomponentvelocity)
- [GetForwardVector](ue_ue.SpotLightComponent.md#getforwardvector)
- [GetLightColor](ue_ue.SpotLightComponent.md#getlightcolor)
- [GetName](ue_ue.SpotLightComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.SpotLightComponent.md#getnumchildrencomponents)
- [GetOuter](ue_ue.SpotLightComponent.md#getouter)
- [GetOwner](ue_ue.SpotLightComponent.md#getowner)
- [GetParentComponents](ue_ue.SpotLightComponent.md#getparentcomponents)
- [GetPhysicsVolume](ue_ue.SpotLightComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.SpotLightComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.SpotLightComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.SpotLightComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.SpotLightComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.SpotLightComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.SpotLightComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.SpotLightComponent.md#getsockettransform)
- [GetUpVector](ue_ue.SpotLightComponent.md#getupvector)
- [GetWorld](ue_ue.SpotLightComponent.md#getworld)
- [IsActive](ue_ue.SpotLightComponent.md#isactive)
- [IsAnySimulatingPhysics](ue_ue.SpotLightComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.SpotLightComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.SpotLightComponent.md#iscomponenttickenabled)
- [IsSimulatingPhysics](ue_ue.SpotLightComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.SpotLightComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.SpotLightComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.SpotLightComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.SpotLightComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.SpotLightComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.SpotLightComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.SpotLightComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.SpotLightComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.SpotLightComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.SpotLightComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.SpotLightComponent.md#k2_attachtocomponent)
- [K2\_DestroyComponent](ue_ue.SpotLightComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.SpotLightComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.SpotLightComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.SpotLightComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.SpotLightComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.SpotLightComponent.md#k2_getcomponenttoworld)
- [K2\_SetRelativeLocation](ue_ue.SpotLightComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.SpotLightComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.SpotLightComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.SpotLightComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.SpotLightComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.SpotLightComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.SpotLightComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.SpotLightComponent.md#k2_setworldtransform)
- [OnRep\_AttachChildren](ue_ue.SpotLightComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.SpotLightComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.SpotLightComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.SpotLightComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.SpotLightComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.SpotLightComponent.md#onrep_visibility)
- [ReceiveBeginPlay](ue_ue.SpotLightComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.SpotLightComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.SpotLightComponent.md#receivetick)
- [RegisterComponent](ue_ue.SpotLightComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.SpotLightComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.SpotLightComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.SpotLightComponent.md#resetrelativetransform)
- [SetAbsolute](ue_ue.SpotLightComponent.md#setabsolute)
- [SetActive](ue_ue.SpotLightComponent.md#setactive)
- [SetAffectDynamicIndirectLighting](ue_ue.SpotLightComponent.md#setaffectdynamicindirectlighting)
- [SetAffectGlobalIllumination](ue_ue.SpotLightComponent.md#setaffectglobalillumination)
- [SetAffectReflection](ue_ue.SpotLightComponent.md#setaffectreflection)
- [SetAffectTranslucentLighting](ue_ue.SpotLightComponent.md#setaffecttranslucentlighting)
- [SetAttenuationRadius](ue_ue.SpotLightComponent.md#setattenuationradius)
- [SetAutoActivate](ue_ue.SpotLightComponent.md#setautoactivate)
- [SetBloomMaxBrightness](ue_ue.SpotLightComponent.md#setbloommaxbrightness)
- [SetBloomScale](ue_ue.SpotLightComponent.md#setbloomscale)
- [SetBloomThreshold](ue_ue.SpotLightComponent.md#setbloomthreshold)
- [SetBloomTint](ue_ue.SpotLightComponent.md#setbloomtint)
- [SetCastDeepShadow](ue_ue.SpotLightComponent.md#setcastdeepshadow)
- [SetCastRaytracedShadow](ue_ue.SpotLightComponent.md#setcastraytracedshadow)
- [SetCastShadows](ue_ue.SpotLightComponent.md#setcastshadows)
- [SetCastVolumetricShadow](ue_ue.SpotLightComponent.md#setcastvolumetricshadow)
- [SetComponentTickEnabled](ue_ue.SpotLightComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.SpotLightComponent.md#setcomponenttickinterval)
- [SetEnableLightShaftBloom](ue_ue.SpotLightComponent.md#setenablelightshaftbloom)
- [SetForceCachedShadowsForMovablePrimitives](ue_ue.SpotLightComponent.md#setforcecachedshadowsformovableprimitives)
- [SetHiddenInGame](ue_ue.SpotLightComponent.md#sethiddeningame)
- [SetIESBrightnessScale](ue_ue.SpotLightComponent.md#setiesbrightnessscale)
- [SetIESTexture](ue_ue.SpotLightComponent.md#setiestexture)
- [SetIndirectLightingIntensity](ue_ue.SpotLightComponent.md#setindirectlightingintensity)
- [SetInnerConeAngle](ue_ue.SpotLightComponent.md#setinnerconeangle)
- [SetIntensity](ue_ue.SpotLightComponent.md#setintensity)
- [SetIntensityUnits](ue_ue.SpotLightComponent.md#setintensityunits)
- [SetIsReplicated](ue_ue.SpotLightComponent.md#setisreplicated)
- [SetLightColor](ue_ue.SpotLightComponent.md#setlightcolor)
- [SetLightFalloffExponent](ue_ue.SpotLightComponent.md#setlightfalloffexponent)
- [SetLightFunctionDisabledBrightness](ue_ue.SpotLightComponent.md#setlightfunctiondisabledbrightness)
- [SetLightFunctionFadeDistance](ue_ue.SpotLightComponent.md#setlightfunctionfadedistance)
- [SetLightFunctionMaterial](ue_ue.SpotLightComponent.md#setlightfunctionmaterial)
- [SetLightFunctionScale](ue_ue.SpotLightComponent.md#setlightfunctionscale)
- [SetMobility](ue_ue.SpotLightComponent.md#setmobility)
- [SetOuterConeAngle](ue_ue.SpotLightComponent.md#setouterconeangle)
- [SetRelativeScale3D](ue_ue.SpotLightComponent.md#setrelativescale3d)
- [SetSamplesPerPixel](ue_ue.SpotLightComponent.md#setsamplesperpixel)
- [SetShadowBias](ue_ue.SpotLightComponent.md#setshadowbias)
- [SetShadowSlopeBias](ue_ue.SpotLightComponent.md#setshadowslopebias)
- [SetShouldUpdatePhysicsVolume](ue_ue.SpotLightComponent.md#setshouldupdatephysicsvolume)
- [SetSoftSourceRadius](ue_ue.SpotLightComponent.md#setsoftsourceradius)
- [SetSourceLength](ue_ue.SpotLightComponent.md#setsourcelength)
- [SetSourceRadius](ue_ue.SpotLightComponent.md#setsourceradius)
- [SetSpecularScale](ue_ue.SpotLightComponent.md#setspecularscale)
- [SetTemperature](ue_ue.SpotLightComponent.md#settemperature)
- [SetTickGroup](ue_ue.SpotLightComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.SpotLightComponent.md#settickablewhenpaused)
- [SetTransmission](ue_ue.SpotLightComponent.md#settransmission)
- [SetUseIESBrightness](ue_ue.SpotLightComponent.md#setuseiesbrightness)
- [SetVisibility](ue_ue.SpotLightComponent.md#setvisibility)
- [SetVolumetricScatteringIntensity](ue_ue.SpotLightComponent.md#setvolumetricscatteringintensity)
- [SetWorldScale3D](ue_ue.SpotLightComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.SpotLightComponent.md#setupattachment)
- [SnapTo](ue_ue.SpotLightComponent.md#snapto)
- [ToggleActive](ue_ue.SpotLightComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.SpotLightComponent.md#togglevisibility)
- [Find](ue_ue.SpotLightComponent.md#find)
- [GetUnitsConversionFactor](ue_ue.SpotLightComponent.md#getunitsconversionfactor)
- [Load](ue_ue.SpotLightComponent.md#load)
- [StaticClass](ue_ue.SpotLightComponent.md#staticclass)

## Constructors

### constructor

• **new SpotLightComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[PointLightComponent](ue_ue.PointLightComponent.md).[constructor](ue_ue.PointLightComponent.md#constructor)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[AssetUserData](ue_ue.PointLightComponent.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[AttachChildren](ue_ue.PointLightComponent.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[AttachParent](ue_ue.PointLightComponent.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[AttachSocketName](ue_ue.PointLightComponent.md#attachsocketname)

___

### AttenuationRadius

• **AttenuationRadius**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[AttenuationRadius](ue_ue.PointLightComponent.md#attenuationradius)

___

### BloomMaxBrightness

• **BloomMaxBrightness**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[BloomMaxBrightness](ue_ue.PointLightComponent.md#bloommaxbrightness)

___

### BloomScale

• **BloomScale**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[BloomScale](ue_ue.PointLightComponent.md#bloomscale)

___

### BloomThreshold

• **BloomThreshold**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[BloomThreshold](ue_ue.PointLightComponent.md#bloomthreshold)

___

### BloomTint

• **BloomTint**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[BloomTint](ue_ue.PointLightComponent.md#bloomtint)

___

### Brightness

• **Brightness**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[Brightness](ue_ue.PointLightComponent.md#brightness)

___

### CastDynamicShadows

• **CastDynamicShadows**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[CastDynamicShadows](ue_ue.PointLightComponent.md#castdynamicshadows)

___

### CastShadows

• **CastShadows**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[CastShadows](ue_ue.PointLightComponent.md#castshadows)

___

### CastStaticShadows

• **CastStaticShadows**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[CastStaticShadows](ue_ue.PointLightComponent.md#caststaticshadows)

___

### CastTranslucentShadows

• **CastTranslucentShadows**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[CastTranslucentShadows](ue_ue.PointLightComponent.md#casttranslucentshadows)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[ClientAttachedChildren](ue_ue.PointLightComponent.md#clientattachedchildren)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[ComponentTags](ue_ue.PointLightComponent.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[ComponentVelocity](ue_ue.PointLightComponent.md#componentvelocity)

___

### ContactShadowLength

• **ContactShadowLength**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[ContactShadowLength](ue_ue.PointLightComponent.md#contactshadowlength)

___

### ContactShadowLengthInWS

• **ContactShadowLengthInWS**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[ContactShadowLengthInWS](ue_ue.PointLightComponent.md#contactshadowlengthinws)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[CreationMethod](ue_ue.PointLightComponent.md#creationmethod)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[DetailMode](ue_ue.PointLightComponent.md#detailmode)

___

### DisabledBrightness

• **DisabledBrightness**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[DisabledBrightness](ue_ue.PointLightComponent.md#disabledbrightness)

___

### DynamicEditorTexture

• **DynamicEditorTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[DynamicEditorTexture](ue_ue.PointLightComponent.md#dynamiceditortexture)

___

### DynamicEditorTextureScale

• **DynamicEditorTextureScale**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[DynamicEditorTextureScale](ue_ue.PointLightComponent.md#dynamiceditortexturescale)

___

### IESBrightnessScale

• **IESBrightnessScale**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[IESBrightnessScale](ue_ue.PointLightComponent.md#iesbrightnessscale)

___

### IESTexture

• **IESTexture**: [`TextureLightProfile`](ue_ue.TextureLightProfile.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[IESTexture](ue_ue.PointLightComponent.md#iestexture)

___

### IndirectLightingIntensity

• **IndirectLightingIntensity**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[IndirectLightingIntensity](ue_ue.PointLightComponent.md#indirectlightingintensity)

___

### InnerConeAngle

• **InnerConeAngle**: `number`

___

### Intensity

• **Intensity**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[Intensity](ue_ue.PointLightComponent.md#intensity)

___

### IntensityUnits

• **IntensityUnits**: [`ELightUnits`](../enums/ue_ue.ELightUnits.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[IntensityUnits](ue_ue.PointLightComponent.md#intensityunits)

___

### InverseSquaredFalloff

• **InverseSquaredFalloff**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[InverseSquaredFalloff](ue_ue.PointLightComponent.md#inversesquaredfalloff)

___

### LightColor

• **LightColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[LightColor](ue_ue.PointLightComponent.md#lightcolor)

___

### LightFalloffExponent

• **LightFalloffExponent**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[LightFalloffExponent](ue_ue.PointLightComponent.md#lightfalloffexponent)

___

### LightFunctionFadeDistance

• **LightFunctionFadeDistance**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[LightFunctionFadeDistance](ue_ue.PointLightComponent.md#lightfunctionfadedistance)

___

### LightFunctionMaterial

• **LightFunctionMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[LightFunctionMaterial](ue_ue.PointLightComponent.md#lightfunctionmaterial)

___

### LightFunctionScale

• **LightFunctionScale**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[LightFunctionScale](ue_ue.PointLightComponent.md#lightfunctionscale)

___

### LightGuid

• **LightGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[LightGuid](ue_ue.PointLightComponent.md#lightguid)

___

### LightShaftConeAngle

• **LightShaftConeAngle**: `number`

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[LightingChannels](ue_ue.PointLightComponent.md#lightingchannels)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassPointLightSettings`](ue_ue.LightmassPointLightSettings.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[LightmassSettings](ue_ue.PointLightComponent.md#lightmasssettings)

___

### MaxDistanceFadeRange

• **MaxDistanceFadeRange**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[MaxDistanceFadeRange](ue_ue.PointLightComponent.md#maxdistancefaderange)

___

### MaxDrawDistance

• **MaxDrawDistance**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[MaxDrawDistance](ue_ue.PointLightComponent.md#maxdrawdistance)

___

### MinRoughness

• **MinRoughness**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[MinRoughness](ue_ue.PointLightComponent.md#minroughness)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[Mobility](ue_ue.PointLightComponent.md#mobility)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[OnComponentActivated](ue_ue.PointLightComponent.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[OnComponentDeactivated](ue_ue.PointLightComponent.md#oncomponentdeactivated)

___

### OuterConeAngle

• **OuterConeAngle**: `number`

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[PhysicsVolume](ue_ue.PointLightComponent.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.PointLightComponent.md#physicsvolumechangeddelegate)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[PrimaryComponentTick](ue_ue.PointLightComponent.md#primarycomponenttick)

___

### Radius

• **Radius**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[Radius](ue_ue.PointLightComponent.md#radius)

___

### RayStartOffsetDepthScale

• **RayStartOffsetDepthScale**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[RayStartOffsetDepthScale](ue_ue.PointLightComponent.md#raystartoffsetdepthscale)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[RelativeLocation](ue_ue.PointLightComponent.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[RelativeRotation](ue_ue.PointLightComponent.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[RelativeScale3D](ue_ue.PointLightComponent.md#relativescale3d)

___

### SamplesPerPixel

• **SamplesPerPixel**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[SamplesPerPixel](ue_ue.PointLightComponent.md#samplesperpixel)

___

### ShadowBias

• **ShadowBias**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[ShadowBias](ue_ue.PointLightComponent.md#shadowbias)

___

### ShadowMapChannel

• **ShadowMapChannel**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[ShadowMapChannel](ue_ue.PointLightComponent.md#shadowmapchannel)

___

### ShadowResolutionScale

• **ShadowResolutionScale**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[ShadowResolutionScale](ue_ue.PointLightComponent.md#shadowresolutionscale)

___

### ShadowSharpen

• **ShadowSharpen**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[ShadowSharpen](ue_ue.PointLightComponent.md#shadowsharpen)

___

### ShadowSlopeBias

• **ShadowSlopeBias**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[ShadowSlopeBias](ue_ue.PointLightComponent.md#shadowslopebias)

___

### SoftSourceRadius

• **SoftSourceRadius**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[SoftSourceRadius](ue_ue.PointLightComponent.md#softsourceradius)

___

### SourceLength

• **SourceLength**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[SourceLength](ue_ue.PointLightComponent.md#sourcelength)

___

### SourceRadius

• **SourceRadius**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[SourceRadius](ue_ue.PointLightComponent.md#sourceradius)

___

### SpecularScale

• **SpecularScale**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[SpecularScale](ue_ue.PointLightComponent.md#specularscale)

___

### StaticEditorTexture

• **StaticEditorTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[StaticEditorTexture](ue_ue.PointLightComponent.md#staticeditortexture)

___

### StaticEditorTextureScale

• **StaticEditorTextureScale**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[StaticEditorTextureScale](ue_ue.PointLightComponent.md#staticeditortexturescale)

___

### Temperature

• **Temperature**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[Temperature](ue_ue.PointLightComponent.md#temperature)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[UCSModifiedProperties](ue_ue.PointLightComponent.md#ucsmodifiedproperties)

___

### VolumetricScatteringIntensity

• **VolumetricScatteringIntensity**: `number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[VolumetricScatteringIntensity](ue_ue.PointLightComponent.md#volumetricscatteringintensity)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[__tid_ActorComponent__](ue_ue.PointLightComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_LightComponentBase\_\_

• **\_\_tid\_LightComponentBase\_\_**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[__tid_LightComponentBase__](ue_ue.PointLightComponent.md#__tid_lightcomponentbase__)

___

### \_\_tid\_LightComponent\_\_

• **\_\_tid\_LightComponent\_\_**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[__tid_LightComponent__](ue_ue.PointLightComponent.md#__tid_lightcomponent__)

___

### \_\_tid\_LocalLightComponent\_\_

• **\_\_tid\_LocalLightComponent\_\_**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[__tid_LocalLightComponent__](ue_ue.PointLightComponent.md#__tid_locallightcomponent__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[__tid_Object__](ue_ue.PointLightComponent.md#__tid_object__)

___

### \_\_tid\_PointLightComponent\_\_

• **\_\_tid\_PointLightComponent\_\_**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[__tid_PointLightComponent__](ue_ue.PointLightComponent.md#__tid_pointlightcomponent__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[__tid_SceneComponent__](ue_ue.PointLightComponent.md#__tid_scenecomponent__)

___

### \_\_tid\_SpotLightComponent\_\_

• **\_\_tid\_SpotLightComponent\_\_**: `boolean`

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bAbsoluteLocation](ue_ue.PointLightComponent.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bAbsoluteRotation](ue_ue.PointLightComponent.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bAbsoluteScale](ue_ue.PointLightComponent.md#babsolutescale)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bAffectDynamicIndirectLighting](ue_ue.PointLightComponent.md#baffectdynamicindirectlighting)

___

### bAffectGlobalIllumination

• **bAffectGlobalIllumination**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bAffectGlobalIllumination](ue_ue.PointLightComponent.md#baffectglobalillumination)

___

### bAffectReflection

• **bAffectReflection**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bAffectReflection](ue_ue.PointLightComponent.md#baffectreflection)

___

### bAffectTranslucentLighting

• **bAffectTranslucentLighting**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bAffectTranslucentLighting](ue_ue.PointLightComponent.md#baffecttranslucentlighting)

___

### bAffectsWorld

• **bAffectsWorld**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bAffectsWorld](ue_ue.PointLightComponent.md#baffectsworld)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bAutoActivate](ue_ue.PointLightComponent.md#bautoactivate)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.PointLightComponent.md#bboundschangetriggersstreamingdatarebuild)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bCanEverAffectNavigation](ue_ue.PointLightComponent.md#bcaneveraffectnavigation)

___

### bCastDeepShadow

• **bCastDeepShadow**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bCastDeepShadow](ue_ue.PointLightComponent.md#bcastdeepshadow)

___

### bCastRaytracedShadow

• **bCastRaytracedShadow**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bCastRaytracedShadow](ue_ue.PointLightComponent.md#bcastraytracedshadow)

___

### bCastShadowsFromCinematicObjectsOnly

• **bCastShadowsFromCinematicObjectsOnly**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bCastShadowsFromCinematicObjectsOnly](ue_ue.PointLightComponent.md#bcastshadowsfromcinematicobjectsonly)

___

### bCastVolumetricShadow

• **bCastVolumetricShadow**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bCastVolumetricShadow](ue_ue.PointLightComponent.md#bcastvolumetricshadow)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bComponentToWorldUpdated](ue_ue.PointLightComponent.md#bcomponenttoworldupdated)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bCreatedByConstructionScript](ue_ue.PointLightComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bEditableWhenInherited](ue_ue.PointLightComponent.md#beditablewheninherited)

___

### bEnableLightShaftBloom

• **bEnableLightShaftBloom**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bEnableLightShaftBloom](ue_ue.PointLightComponent.md#benablelightshaftbloom)

___

### bForceCachedShadowsForMovablePrimitives

• **bForceCachedShadowsForMovablePrimitives**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bForceCachedShadowsForMovablePrimitives](ue_ue.PointLightComponent.md#bforcecachedshadowsformovableprimitives)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bHiddenInGame](ue_ue.PointLightComponent.md#bhiddeningame)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bInstanceComponent](ue_ue.PointLightComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bIsActive](ue_ue.PointLightComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bIsEditorOnly](ue_ue.PointLightComponent.md#biseditoronly)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bIsVisualizationComponent](ue_ue.PointLightComponent.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bNetAddressable](ue_ue.PointLightComponent.md#bnetaddressable)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bReplicates](ue_ue.PointLightComponent.md#breplicates)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bShouldBeAttached](ue_ue.PointLightComponent.md#bshouldbeattached)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.PointLightComponent.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.PointLightComponent.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.PointLightComponent.md#bshouldupdatephysicsvolume)

___

### bTransmission

• **bTransmission**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bTransmission](ue_ue.PointLightComponent.md#btransmission)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bUseAttachParentBound](ue_ue.PointLightComponent.md#buseattachparentbound)

___

### bUseIESBrightness

• **bUseIESBrightness**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bUseIESBrightness](ue_ue.PointLightComponent.md#buseiesbrightness)

___

### bUseInverseSquaredFalloff

• **bUseInverseSquaredFalloff**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bUseInverseSquaredFalloff](ue_ue.PointLightComponent.md#buseinversesquaredfalloff)

___

### bUseRayTracedDistanceFieldShadows

• **bUseRayTracedDistanceFieldShadows**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bUseRayTracedDistanceFieldShadows](ue_ue.PointLightComponent.md#buseraytraceddistancefieldshadows)

___

### bUseTemperature

• **bUseTemperature**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bUseTemperature](ue_ue.PointLightComponent.md#busetemperature)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bVisible](ue_ue.PointLightComponent.md#bvisible)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[bVisualizeComponent](ue_ue.PointLightComponent.md#bvisualizecomponent)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[Activate](ue_ue.PointLightComponent.md#activate)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[AddTickPrerequisiteActor](ue_ue.PointLightComponent.md#addtickprerequisiteactor)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[AddTickPrerequisiteComponent](ue_ue.PointLightComponent.md#addtickprerequisitecomponent)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[ComponentHasTag](ue_ue.PointLightComponent.md#componenthastag)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[CreateDefaultSubobject](ue_ue.PointLightComponent.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[Deactivate](ue_ue.PointLightComponent.md#deactivate)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[DetachFromParent](ue_ue.PointLightComponent.md#detachfromparent)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[DoesSocketExist](ue_ue.PointLightComponent.md#doessocketexist)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[ExecuteUbergraph](ue_ue.PointLightComponent.md#executeubergraph)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetAllSocketNames](ue_ue.PointLightComponent.md#getallsocketnames)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetAttachParent](ue_ue.PointLightComponent.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetAttachSocketName](ue_ue.PointLightComponent.md#getattachsocketname)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[GetChildComponent](ue_ue.PointLightComponent.md#getchildcomponent)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[GetChildrenComponents](ue_ue.PointLightComponent.md#getchildrencomponents)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetClass](ue_ue.PointLightComponent.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetComponentTickInterval](ue_ue.PointLightComponent.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetComponentVelocity](ue_ue.PointLightComponent.md#getcomponentvelocity)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetForwardVector](ue_ue.PointLightComponent.md#getforwardvector)

___

### GetLightColor

▸ **GetLightColor**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetLightColor](ue_ue.PointLightComponent.md#getlightcolor)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetName](ue_ue.PointLightComponent.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetNumChildrenComponents](ue_ue.PointLightComponent.md#getnumchildrencomponents)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetOuter](ue_ue.PointLightComponent.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetOwner](ue_ue.PointLightComponent.md#getowner)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[GetParentComponents](ue_ue.PointLightComponent.md#getparentcomponents)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetPhysicsVolume](ue_ue.PointLightComponent.md#getphysicsvolume)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetRelativeTransform](ue_ue.PointLightComponent.md#getrelativetransform)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetRightVector](ue_ue.PointLightComponent.md#getrightvector)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.PointLightComponent.md#getshouldupdatephysicsvolume)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[GetSocketLocation](ue_ue.PointLightComponent.md#getsocketlocation)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[GetSocketQuaternion](ue_ue.PointLightComponent.md#getsocketquaternion)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[GetSocketRotation](ue_ue.PointLightComponent.md#getsocketrotation)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[GetSocketTransform](ue_ue.PointLightComponent.md#getsockettransform)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetUpVector](ue_ue.PointLightComponent.md#getupvector)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetWorld](ue_ue.PointLightComponent.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[IsActive](ue_ue.PointLightComponent.md#isactive)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[IsAnySimulatingPhysics](ue_ue.PointLightComponent.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[IsBeingDestroyed](ue_ue.PointLightComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[IsComponentTickEnabled](ue_ue.PointLightComponent.md#iscomponenttickenabled)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[IsSimulatingPhysics](ue_ue.PointLightComponent.md#issimulatingphysics)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[IsVisible](ue_ue.PointLightComponent.md#isvisible)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_AddLocalOffset](ue_ue.PointLightComponent.md#k2_addlocaloffset)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_AddLocalRotation](ue_ue.PointLightComponent.md#k2_addlocalrotation)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_AddLocalTransform](ue_ue.PointLightComponent.md#k2_addlocaltransform)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_AddRelativeLocation](ue_ue.PointLightComponent.md#k2_addrelativelocation)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_AddRelativeRotation](ue_ue.PointLightComponent.md#k2_addrelativerotation)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_AddWorldOffset](ue_ue.PointLightComponent.md#k2_addworldoffset)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_AddWorldRotation](ue_ue.PointLightComponent.md#k2_addworldrotation)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_AddWorldTransform](ue_ue.PointLightComponent.md#k2_addworldtransform)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_AttachTo](ue_ue.PointLightComponent.md#k2_attachto)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_AttachToComponent](ue_ue.PointLightComponent.md#k2_attachtocomponent)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_DestroyComponent](ue_ue.PointLightComponent.md#k2_destroycomponent)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_DetachFromComponent](ue_ue.PointLightComponent.md#k2_detachfromcomponent)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_GetComponentLocation](ue_ue.PointLightComponent.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_GetComponentRotation](ue_ue.PointLightComponent.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_GetComponentScale](ue_ue.PointLightComponent.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_GetComponentToWorld](ue_ue.PointLightComponent.md#k2_getcomponenttoworld)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_SetRelativeLocation](ue_ue.PointLightComponent.md#k2_setrelativelocation)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.PointLightComponent.md#k2_setrelativelocationandrotation)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_SetRelativeRotation](ue_ue.PointLightComponent.md#k2_setrelativerotation)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_SetRelativeTransform](ue_ue.PointLightComponent.md#k2_setrelativetransform)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_SetWorldLocation](ue_ue.PointLightComponent.md#k2_setworldlocation)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.PointLightComponent.md#k2_setworldlocationandrotation)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_SetWorldRotation](ue_ue.PointLightComponent.md#k2_setworldrotation)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[K2_SetWorldTransform](ue_ue.PointLightComponent.md#k2_setworldtransform)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[OnRep_AttachChildren](ue_ue.PointLightComponent.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[OnRep_AttachParent](ue_ue.PointLightComponent.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[OnRep_AttachSocketName](ue_ue.PointLightComponent.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[OnRep_IsActive](ue_ue.PointLightComponent.md#onrep_isactive)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[OnRep_Transform](ue_ue.PointLightComponent.md#onrep_transform)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[OnRep_Visibility](ue_ue.PointLightComponent.md#onrep_visibility)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[ReceiveBeginPlay](ue_ue.PointLightComponent.md#receivebeginplay)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[ReceiveEndPlay](ue_ue.PointLightComponent.md#receiveendplay)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[ReceiveTick](ue_ue.PointLightComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[RegisterComponent](ue_ue.PointLightComponent.md#registercomponent)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[RemoveTickPrerequisiteActor](ue_ue.PointLightComponent.md#removetickprerequisiteactor)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.PointLightComponent.md#removetickprerequisitecomponent)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[ResetRelativeTransform](ue_ue.PointLightComponent.md#resetrelativetransform)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetAbsolute](ue_ue.PointLightComponent.md#setabsolute)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetActive](ue_ue.PointLightComponent.md#setactive)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetAffectDynamicIndirectLighting](ue_ue.PointLightComponent.md#setaffectdynamicindirectlighting)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetAffectGlobalIllumination](ue_ue.PointLightComponent.md#setaffectglobalillumination)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetAffectReflection](ue_ue.PointLightComponent.md#setaffectreflection)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetAffectTranslucentLighting](ue_ue.PointLightComponent.md#setaffecttranslucentlighting)

___

### SetAttenuationRadius

▸ **SetAttenuationRadius**(`NewRadius`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRadius` | `number` |

#### Returns

`void`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[SetAttenuationRadius](ue_ue.PointLightComponent.md#setattenuationradius)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetAutoActivate](ue_ue.PointLightComponent.md#setautoactivate)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetBloomMaxBrightness](ue_ue.PointLightComponent.md#setbloommaxbrightness)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetBloomScale](ue_ue.PointLightComponent.md#setbloomscale)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetBloomThreshold](ue_ue.PointLightComponent.md#setbloomthreshold)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetBloomTint](ue_ue.PointLightComponent.md#setbloomtint)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetCastDeepShadow](ue_ue.PointLightComponent.md#setcastdeepshadow)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetCastRaytracedShadow](ue_ue.PointLightComponent.md#setcastraytracedshadow)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetCastShadows](ue_ue.PointLightComponent.md#setcastshadows)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetCastVolumetricShadow](ue_ue.PointLightComponent.md#setcastvolumetricshadow)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetComponentTickEnabled](ue_ue.PointLightComponent.md#setcomponenttickenabled)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetComponentTickInterval](ue_ue.PointLightComponent.md#setcomponenttickinterval)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetEnableLightShaftBloom](ue_ue.PointLightComponent.md#setenablelightshaftbloom)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetForceCachedShadowsForMovablePrimitives](ue_ue.PointLightComponent.md#setforcecachedshadowsformovableprimitives)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetHiddenInGame](ue_ue.PointLightComponent.md#sethiddeningame)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetIESBrightnessScale](ue_ue.PointLightComponent.md#setiesbrightnessscale)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetIESTexture](ue_ue.PointLightComponent.md#setiestexture)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetIndirectLightingIntensity](ue_ue.PointLightComponent.md#setindirectlightingintensity)

___

### SetInnerConeAngle

▸ **SetInnerConeAngle**(`NewInnerConeAngle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewInnerConeAngle` | `number` |

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

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[SetIntensity](ue_ue.PointLightComponent.md#setintensity)

___

### SetIntensityUnits

▸ **SetIntensityUnits**(`NewIntensityUnits`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewIntensityUnits` | [`ELightUnits`](../enums/ue_ue.ELightUnits.md) |

#### Returns

`void`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[SetIntensityUnits](ue_ue.PointLightComponent.md#setintensityunits)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetIsReplicated](ue_ue.PointLightComponent.md#setisreplicated)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetLightColor](ue_ue.PointLightComponent.md#setlightcolor)

___

### SetLightFalloffExponent

▸ **SetLightFalloffExponent**(`NewLightFalloffExponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLightFalloffExponent` | `number` |

#### Returns

`void`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[SetLightFalloffExponent](ue_ue.PointLightComponent.md#setlightfalloffexponent)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetLightFunctionDisabledBrightness](ue_ue.PointLightComponent.md#setlightfunctiondisabledbrightness)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetLightFunctionFadeDistance](ue_ue.PointLightComponent.md#setlightfunctionfadedistance)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetLightFunctionMaterial](ue_ue.PointLightComponent.md#setlightfunctionmaterial)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetLightFunctionScale](ue_ue.PointLightComponent.md#setlightfunctionscale)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetMobility](ue_ue.PointLightComponent.md#setmobility)

___

### SetOuterConeAngle

▸ **SetOuterConeAngle**(`NewOuterConeAngle`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewOuterConeAngle` | `number` |

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetRelativeScale3D](ue_ue.PointLightComponent.md#setrelativescale3d)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetSamplesPerPixel](ue_ue.PointLightComponent.md#setsamplesperpixel)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetShadowBias](ue_ue.PointLightComponent.md#setshadowbias)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetShadowSlopeBias](ue_ue.PointLightComponent.md#setshadowslopebias)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.PointLightComponent.md#setshouldupdatephysicsvolume)

___

### SetSoftSourceRadius

▸ **SetSoftSourceRadius**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `number` |

#### Returns

`void`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[SetSoftSourceRadius](ue_ue.PointLightComponent.md#setsoftsourceradius)

___

### SetSourceLength

▸ **SetSourceLength**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[SetSourceLength](ue_ue.PointLightComponent.md#setsourcelength)

___

### SetSourceRadius

▸ **SetSourceRadius**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `number` |

#### Returns

`void`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[SetSourceRadius](ue_ue.PointLightComponent.md#setsourceradius)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetSpecularScale](ue_ue.PointLightComponent.md#setspecularscale)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetTemperature](ue_ue.PointLightComponent.md#settemperature)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetTickGroup](ue_ue.PointLightComponent.md#settickgroup)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetTickableWhenPaused](ue_ue.PointLightComponent.md#settickablewhenpaused)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetTransmission](ue_ue.PointLightComponent.md#settransmission)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetUseIESBrightness](ue_ue.PointLightComponent.md#setuseiesbrightness)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetVisibility](ue_ue.PointLightComponent.md#setvisibility)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetVolumetricScatteringIntensity](ue_ue.PointLightComponent.md#setvolumetricscatteringintensity)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetWorldScale3D](ue_ue.PointLightComponent.md#setworldscale3d)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SetupAttachment](ue_ue.PointLightComponent.md#setupattachment)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[SnapTo](ue_ue.PointLightComponent.md#snapto)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[ToggleActive](ue_ue.PointLightComponent.md#toggleactive)

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

[PointLightComponent](ue_ue.PointLightComponent.md).[ToggleVisibility](ue_ue.PointLightComponent.md#togglevisibility)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`SpotLightComponent`](ue_ue.SpotLightComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`SpotLightComponent`](ue_ue.SpotLightComponent.md)

#### Overrides

[PointLightComponent](ue_ue.PointLightComponent.md).[Find](ue_ue.PointLightComponent.md#find)

___

### GetUnitsConversionFactor

▸ `Static` **GetUnitsConversionFactor**(`SrcUnits`, `TargetUnits`, `CosHalfConeAngle?`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SrcUnits` | [`ELightUnits`](../enums/ue_ue.ELightUnits.md) |
| `TargetUnits` | [`ELightUnits`](../enums/ue_ue.ELightUnits.md) |
| `CosHalfConeAngle?` | `number` |

#### Returns

`number`

#### Inherited from

[PointLightComponent](ue_ue.PointLightComponent.md).[GetUnitsConversionFactor](ue_ue.PointLightComponent.md#getunitsconversionfactor)

___

### Load

▸ `Static` **Load**(`InName`): [`SpotLightComponent`](ue_ue.SpotLightComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`SpotLightComponent`](ue_ue.SpotLightComponent.md)

#### Overrides

[PointLightComponent](ue_ue.PointLightComponent.md).[Load](ue_ue.PointLightComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[PointLightComponent](ue_ue.PointLightComponent.md).[StaticClass](ue_ue.PointLightComponent.md#staticclass)
