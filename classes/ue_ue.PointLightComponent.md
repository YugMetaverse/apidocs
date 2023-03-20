[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / PointLightComponent

# Class: PointLightComponent

[ue/ue](../modules/ue_ue.md).PointLightComponent

## Hierarchy

- [`LocalLightComponent`](ue_ue.LocalLightComponent.md)

  ↳ **`PointLightComponent`**

  ↳↳ [`SpotLightComponent`](ue_ue.SpotLightComponent.md)

## Table of contents

### Constructors

- [constructor](ue_ue.PointLightComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.PointLightComponent.md#assetuserdata)
- [AttachChildren](ue_ue.PointLightComponent.md#attachchildren)
- [AttachParent](ue_ue.PointLightComponent.md#attachparent)
- [AttachSocketName](ue_ue.PointLightComponent.md#attachsocketname)
- [AttenuationRadius](ue_ue.PointLightComponent.md#attenuationradius)
- [BloomMaxBrightness](ue_ue.PointLightComponent.md#bloommaxbrightness)
- [BloomScale](ue_ue.PointLightComponent.md#bloomscale)
- [BloomThreshold](ue_ue.PointLightComponent.md#bloomthreshold)
- [BloomTint](ue_ue.PointLightComponent.md#bloomtint)
- [Brightness](ue_ue.PointLightComponent.md#brightness)
- [CastDynamicShadows](ue_ue.PointLightComponent.md#castdynamicshadows)
- [CastShadows](ue_ue.PointLightComponent.md#castshadows)
- [CastStaticShadows](ue_ue.PointLightComponent.md#caststaticshadows)
- [CastTranslucentShadows](ue_ue.PointLightComponent.md#casttranslucentshadows)
- [ClientAttachedChildren](ue_ue.PointLightComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.PointLightComponent.md#componenttags)
- [ComponentVelocity](ue_ue.PointLightComponent.md#componentvelocity)
- [ContactShadowLength](ue_ue.PointLightComponent.md#contactshadowlength)
- [ContactShadowLengthInWS](ue_ue.PointLightComponent.md#contactshadowlengthinws)
- [CreationMethod](ue_ue.PointLightComponent.md#creationmethod)
- [DetailMode](ue_ue.PointLightComponent.md#detailmode)
- [DisabledBrightness](ue_ue.PointLightComponent.md#disabledbrightness)
- [DynamicEditorTexture](ue_ue.PointLightComponent.md#dynamiceditortexture)
- [DynamicEditorTextureScale](ue_ue.PointLightComponent.md#dynamiceditortexturescale)
- [IESBrightnessScale](ue_ue.PointLightComponent.md#iesbrightnessscale)
- [IESTexture](ue_ue.PointLightComponent.md#iestexture)
- [IndirectLightingIntensity](ue_ue.PointLightComponent.md#indirectlightingintensity)
- [Intensity](ue_ue.PointLightComponent.md#intensity)
- [IntensityUnits](ue_ue.PointLightComponent.md#intensityunits)
- [InverseSquaredFalloff](ue_ue.PointLightComponent.md#inversesquaredfalloff)
- [LightColor](ue_ue.PointLightComponent.md#lightcolor)
- [LightFalloffExponent](ue_ue.PointLightComponent.md#lightfalloffexponent)
- [LightFunctionFadeDistance](ue_ue.PointLightComponent.md#lightfunctionfadedistance)
- [LightFunctionMaterial](ue_ue.PointLightComponent.md#lightfunctionmaterial)
- [LightFunctionScale](ue_ue.PointLightComponent.md#lightfunctionscale)
- [LightGuid](ue_ue.PointLightComponent.md#lightguid)
- [LightingChannels](ue_ue.PointLightComponent.md#lightingchannels)
- [LightmassSettings](ue_ue.PointLightComponent.md#lightmasssettings)
- [MaxDistanceFadeRange](ue_ue.PointLightComponent.md#maxdistancefaderange)
- [MaxDrawDistance](ue_ue.PointLightComponent.md#maxdrawdistance)
- [MinRoughness](ue_ue.PointLightComponent.md#minroughness)
- [Mobility](ue_ue.PointLightComponent.md#mobility)
- [OnComponentActivated](ue_ue.PointLightComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.PointLightComponent.md#oncomponentdeactivated)
- [PhysicsVolume](ue_ue.PointLightComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.PointLightComponent.md#physicsvolumechangeddelegate)
- [PrimaryComponentTick](ue_ue.PointLightComponent.md#primarycomponenttick)
- [Radius](ue_ue.PointLightComponent.md#radius)
- [RayStartOffsetDepthScale](ue_ue.PointLightComponent.md#raystartoffsetdepthscale)
- [RelativeLocation](ue_ue.PointLightComponent.md#relativelocation)
- [RelativeRotation](ue_ue.PointLightComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.PointLightComponent.md#relativescale3d)
- [SamplesPerPixel](ue_ue.PointLightComponent.md#samplesperpixel)
- [ShadowBias](ue_ue.PointLightComponent.md#shadowbias)
- [ShadowMapChannel](ue_ue.PointLightComponent.md#shadowmapchannel)
- [ShadowResolutionScale](ue_ue.PointLightComponent.md#shadowresolutionscale)
- [ShadowSharpen](ue_ue.PointLightComponent.md#shadowsharpen)
- [ShadowSlopeBias](ue_ue.PointLightComponent.md#shadowslopebias)
- [SoftSourceRadius](ue_ue.PointLightComponent.md#softsourceradius)
- [SourceLength](ue_ue.PointLightComponent.md#sourcelength)
- [SourceRadius](ue_ue.PointLightComponent.md#sourceradius)
- [SpecularScale](ue_ue.PointLightComponent.md#specularscale)
- [StaticEditorTexture](ue_ue.PointLightComponent.md#staticeditortexture)
- [StaticEditorTextureScale](ue_ue.PointLightComponent.md#staticeditortexturescale)
- [Temperature](ue_ue.PointLightComponent.md#temperature)
- [UCSModifiedProperties](ue_ue.PointLightComponent.md#ucsmodifiedproperties)
- [VolumetricScatteringIntensity](ue_ue.PointLightComponent.md#volumetricscatteringintensity)
- [\_\_tid\_ActorComponent\_\_](ue_ue.PointLightComponent.md#__tid_actorcomponent__)
- [\_\_tid\_LightComponentBase\_\_](ue_ue.PointLightComponent.md#__tid_lightcomponentbase__)
- [\_\_tid\_LightComponent\_\_](ue_ue.PointLightComponent.md#__tid_lightcomponent__)
- [\_\_tid\_LocalLightComponent\_\_](ue_ue.PointLightComponent.md#__tid_locallightcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.PointLightComponent.md#__tid_object__)
- [\_\_tid\_PointLightComponent\_\_](ue_ue.PointLightComponent.md#__tid_pointlightcomponent__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.PointLightComponent.md#__tid_scenecomponent__)
- [bAbsoluteLocation](ue_ue.PointLightComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.PointLightComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.PointLightComponent.md#babsolutescale)
- [bAffectDynamicIndirectLighting](ue_ue.PointLightComponent.md#baffectdynamicindirectlighting)
- [bAffectGlobalIllumination](ue_ue.PointLightComponent.md#baffectglobalillumination)
- [bAffectReflection](ue_ue.PointLightComponent.md#baffectreflection)
- [bAffectTranslucentLighting](ue_ue.PointLightComponent.md#baffecttranslucentlighting)
- [bAffectsWorld](ue_ue.PointLightComponent.md#baffectsworld)
- [bAutoActivate](ue_ue.PointLightComponent.md#bautoactivate)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.PointLightComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.PointLightComponent.md#bcaneveraffectnavigation)
- [bCastDeepShadow](ue_ue.PointLightComponent.md#bcastdeepshadow)
- [bCastRaytracedShadow](ue_ue.PointLightComponent.md#bcastraytracedshadow)
- [bCastShadowsFromCinematicObjectsOnly](ue_ue.PointLightComponent.md#bcastshadowsfromcinematicobjectsonly)
- [bCastVolumetricShadow](ue_ue.PointLightComponent.md#bcastvolumetricshadow)
- [bComponentToWorldUpdated](ue_ue.PointLightComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.PointLightComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.PointLightComponent.md#beditablewheninherited)
- [bEnableLightShaftBloom](ue_ue.PointLightComponent.md#benablelightshaftbloom)
- [bForceCachedShadowsForMovablePrimitives](ue_ue.PointLightComponent.md#bforcecachedshadowsformovableprimitives)
- [bHiddenInGame](ue_ue.PointLightComponent.md#bhiddeningame)
- [bInstanceComponent](ue_ue.PointLightComponent.md#binstancecomponent)
- [bIsActive](ue_ue.PointLightComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.PointLightComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.PointLightComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.PointLightComponent.md#bnetaddressable)
- [bReplicates](ue_ue.PointLightComponent.md#breplicates)
- [bShouldBeAttached](ue_ue.PointLightComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.PointLightComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.PointLightComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.PointLightComponent.md#bshouldupdatephysicsvolume)
- [bTransmission](ue_ue.PointLightComponent.md#btransmission)
- [bUseAttachParentBound](ue_ue.PointLightComponent.md#buseattachparentbound)
- [bUseIESBrightness](ue_ue.PointLightComponent.md#buseiesbrightness)
- [bUseInverseSquaredFalloff](ue_ue.PointLightComponent.md#buseinversesquaredfalloff)
- [bUseRayTracedDistanceFieldShadows](ue_ue.PointLightComponent.md#buseraytraceddistancefieldshadows)
- [bUseTemperature](ue_ue.PointLightComponent.md#busetemperature)
- [bVisible](ue_ue.PointLightComponent.md#bvisible)
- [bVisualizeComponent](ue_ue.PointLightComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.PointLightComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.PointLightComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.PointLightComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.PointLightComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.PointLightComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.PointLightComponent.md#deactivate)
- [DetachFromParent](ue_ue.PointLightComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.PointLightComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.PointLightComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.PointLightComponent.md#getallsocketnames)
- [GetAttachParent](ue_ue.PointLightComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.PointLightComponent.md#getattachsocketname)
- [GetChildComponent](ue_ue.PointLightComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.PointLightComponent.md#getchildrencomponents)
- [GetClass](ue_ue.PointLightComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.PointLightComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.PointLightComponent.md#getcomponentvelocity)
- [GetForwardVector](ue_ue.PointLightComponent.md#getforwardvector)
- [GetLightColor](ue_ue.PointLightComponent.md#getlightcolor)
- [GetName](ue_ue.PointLightComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.PointLightComponent.md#getnumchildrencomponents)
- [GetOuter](ue_ue.PointLightComponent.md#getouter)
- [GetOwner](ue_ue.PointLightComponent.md#getowner)
- [GetParentComponents](ue_ue.PointLightComponent.md#getparentcomponents)
- [GetPhysicsVolume](ue_ue.PointLightComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.PointLightComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.PointLightComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.PointLightComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.PointLightComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.PointLightComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.PointLightComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.PointLightComponent.md#getsockettransform)
- [GetUpVector](ue_ue.PointLightComponent.md#getupvector)
- [GetWorld](ue_ue.PointLightComponent.md#getworld)
- [IsActive](ue_ue.PointLightComponent.md#isactive)
- [IsAnySimulatingPhysics](ue_ue.PointLightComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.PointLightComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.PointLightComponent.md#iscomponenttickenabled)
- [IsSimulatingPhysics](ue_ue.PointLightComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.PointLightComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.PointLightComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.PointLightComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.PointLightComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.PointLightComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.PointLightComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.PointLightComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.PointLightComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.PointLightComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.PointLightComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.PointLightComponent.md#k2_attachtocomponent)
- [K2\_DestroyComponent](ue_ue.PointLightComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.PointLightComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.PointLightComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.PointLightComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.PointLightComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.PointLightComponent.md#k2_getcomponenttoworld)
- [K2\_SetRelativeLocation](ue_ue.PointLightComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.PointLightComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.PointLightComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.PointLightComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.PointLightComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.PointLightComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.PointLightComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.PointLightComponent.md#k2_setworldtransform)
- [OnRep\_AttachChildren](ue_ue.PointLightComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.PointLightComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.PointLightComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.PointLightComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.PointLightComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.PointLightComponent.md#onrep_visibility)
- [ReceiveBeginPlay](ue_ue.PointLightComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.PointLightComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.PointLightComponent.md#receivetick)
- [RegisterComponent](ue_ue.PointLightComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.PointLightComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.PointLightComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.PointLightComponent.md#resetrelativetransform)
- [SetAbsolute](ue_ue.PointLightComponent.md#setabsolute)
- [SetActive](ue_ue.PointLightComponent.md#setactive)
- [SetAffectDynamicIndirectLighting](ue_ue.PointLightComponent.md#setaffectdynamicindirectlighting)
- [SetAffectGlobalIllumination](ue_ue.PointLightComponent.md#setaffectglobalillumination)
- [SetAffectReflection](ue_ue.PointLightComponent.md#setaffectreflection)
- [SetAffectTranslucentLighting](ue_ue.PointLightComponent.md#setaffecttranslucentlighting)
- [SetAttenuationRadius](ue_ue.PointLightComponent.md#setattenuationradius)
- [SetAutoActivate](ue_ue.PointLightComponent.md#setautoactivate)
- [SetBloomMaxBrightness](ue_ue.PointLightComponent.md#setbloommaxbrightness)
- [SetBloomScale](ue_ue.PointLightComponent.md#setbloomscale)
- [SetBloomThreshold](ue_ue.PointLightComponent.md#setbloomthreshold)
- [SetBloomTint](ue_ue.PointLightComponent.md#setbloomtint)
- [SetCastDeepShadow](ue_ue.PointLightComponent.md#setcastdeepshadow)
- [SetCastRaytracedShadow](ue_ue.PointLightComponent.md#setcastraytracedshadow)
- [SetCastShadows](ue_ue.PointLightComponent.md#setcastshadows)
- [SetCastVolumetricShadow](ue_ue.PointLightComponent.md#setcastvolumetricshadow)
- [SetComponentTickEnabled](ue_ue.PointLightComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.PointLightComponent.md#setcomponenttickinterval)
- [SetEnableLightShaftBloom](ue_ue.PointLightComponent.md#setenablelightshaftbloom)
- [SetForceCachedShadowsForMovablePrimitives](ue_ue.PointLightComponent.md#setforcecachedshadowsformovableprimitives)
- [SetHiddenInGame](ue_ue.PointLightComponent.md#sethiddeningame)
- [SetIESBrightnessScale](ue_ue.PointLightComponent.md#setiesbrightnessscale)
- [SetIESTexture](ue_ue.PointLightComponent.md#setiestexture)
- [SetIndirectLightingIntensity](ue_ue.PointLightComponent.md#setindirectlightingintensity)
- [SetIntensity](ue_ue.PointLightComponent.md#setintensity)
- [SetIntensityUnits](ue_ue.PointLightComponent.md#setintensityunits)
- [SetIsReplicated](ue_ue.PointLightComponent.md#setisreplicated)
- [SetLightColor](ue_ue.PointLightComponent.md#setlightcolor)
- [SetLightFalloffExponent](ue_ue.PointLightComponent.md#setlightfalloffexponent)
- [SetLightFunctionDisabledBrightness](ue_ue.PointLightComponent.md#setlightfunctiondisabledbrightness)
- [SetLightFunctionFadeDistance](ue_ue.PointLightComponent.md#setlightfunctionfadedistance)
- [SetLightFunctionMaterial](ue_ue.PointLightComponent.md#setlightfunctionmaterial)
- [SetLightFunctionScale](ue_ue.PointLightComponent.md#setlightfunctionscale)
- [SetMobility](ue_ue.PointLightComponent.md#setmobility)
- [SetRelativeScale3D](ue_ue.PointLightComponent.md#setrelativescale3d)
- [SetSamplesPerPixel](ue_ue.PointLightComponent.md#setsamplesperpixel)
- [SetShadowBias](ue_ue.PointLightComponent.md#setshadowbias)
- [SetShadowSlopeBias](ue_ue.PointLightComponent.md#setshadowslopebias)
- [SetShouldUpdatePhysicsVolume](ue_ue.PointLightComponent.md#setshouldupdatephysicsvolume)
- [SetSoftSourceRadius](ue_ue.PointLightComponent.md#setsoftsourceradius)
- [SetSourceLength](ue_ue.PointLightComponent.md#setsourcelength)
- [SetSourceRadius](ue_ue.PointLightComponent.md#setsourceradius)
- [SetSpecularScale](ue_ue.PointLightComponent.md#setspecularscale)
- [SetTemperature](ue_ue.PointLightComponent.md#settemperature)
- [SetTickGroup](ue_ue.PointLightComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.PointLightComponent.md#settickablewhenpaused)
- [SetTransmission](ue_ue.PointLightComponent.md#settransmission)
- [SetUseIESBrightness](ue_ue.PointLightComponent.md#setuseiesbrightness)
- [SetVisibility](ue_ue.PointLightComponent.md#setvisibility)
- [SetVolumetricScatteringIntensity](ue_ue.PointLightComponent.md#setvolumetricscatteringintensity)
- [SetWorldScale3D](ue_ue.PointLightComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.PointLightComponent.md#setupattachment)
- [SnapTo](ue_ue.PointLightComponent.md#snapto)
- [ToggleActive](ue_ue.PointLightComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.PointLightComponent.md#togglevisibility)
- [Find](ue_ue.PointLightComponent.md#find)
- [GetUnitsConversionFactor](ue_ue.PointLightComponent.md#getunitsconversionfactor)
- [Load](ue_ue.PointLightComponent.md#load)
- [StaticClass](ue_ue.PointLightComponent.md#staticclass)

## Constructors

### constructor

• **new PointLightComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[LocalLightComponent](ue_ue.LocalLightComponent.md).[constructor](ue_ue.LocalLightComponent.md#constructor)

#### Defined in

[ue/ue.d.ts:37446](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37446)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[AssetUserData](ue_ue.LocalLightComponent.md#assetuserdata)

#### Defined in

[ue/ue.d.ts:291](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L291)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[AttachChildren](ue_ue.LocalLightComponent.md#attachchildren)

#### Defined in

[ue/ue.d.ts:12873](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12873)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[AttachParent](ue_ue.LocalLightComponent.md#attachparent)

#### Defined in

[ue/ue.d.ts:12871](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12871)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[AttachSocketName](ue_ue.LocalLightComponent.md#attachsocketname)

#### Defined in

[ue/ue.d.ts:12872](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12872)

___

### AttenuationRadius

• **AttenuationRadius**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[AttenuationRadius](ue_ue.LocalLightComponent.md#attenuationradius)

#### Defined in

[ue/ue.d.ts:37433](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37433)

___

### BloomMaxBrightness

• **BloomMaxBrightness**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[BloomMaxBrightness](ue_ue.LocalLightComponent.md#bloommaxbrightness)

#### Defined in

[ue/ue.d.ts:24621](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24621)

___

### BloomScale

• **BloomScale**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[BloomScale](ue_ue.LocalLightComponent.md#bloomscale)

#### Defined in

[ue/ue.d.ts:24619](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24619)

___

### BloomThreshold

• **BloomThreshold**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[BloomThreshold](ue_ue.LocalLightComponent.md#bloomthreshold)

#### Defined in

[ue/ue.d.ts:24620](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24620)

___

### BloomTint

• **BloomTint**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[BloomTint](ue_ue.LocalLightComponent.md#bloomtint)

#### Defined in

[ue/ue.d.ts:24622](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24622)

___

### Brightness

• **Brightness**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[Brightness](ue_ue.LocalLightComponent.md#brightness)

#### Defined in

[ue/ue.d.ts:21357](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21357)

___

### CastDynamicShadows

• **CastDynamicShadows**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[CastDynamicShadows](ue_ue.LocalLightComponent.md#castdynamicshadows)

#### Defined in

[ue/ue.d.ts:21363](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21363)

___

### CastShadows

• **CastShadows**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[CastShadows](ue_ue.LocalLightComponent.md#castshadows)

#### Defined in

[ue/ue.d.ts:21361](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21361)

___

### CastStaticShadows

• **CastStaticShadows**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[CastStaticShadows](ue_ue.LocalLightComponent.md#caststaticshadows)

#### Defined in

[ue/ue.d.ts:21362](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21362)

___

### CastTranslucentShadows

• **CastTranslucentShadows**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[CastTranslucentShadows](ue_ue.LocalLightComponent.md#casttranslucentshadows)

#### Defined in

[ue/ue.d.ts:24606](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24606)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ClientAttachedChildren](ue_ue.LocalLightComponent.md#clientattachedchildren)

#### Defined in

[ue/ue.d.ts:12874](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12874)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ComponentTags](ue_ue.LocalLightComponent.md#componenttags)

#### Defined in

[ue/ue.d.ts:290](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L290)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ComponentVelocity](ue_ue.LocalLightComponent.md#componentvelocity)

#### Defined in

[ue/ue.d.ts:12878](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12878)

___

### ContactShadowLength

• **ContactShadowLength**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ContactShadowLength](ue_ue.LocalLightComponent.md#contactshadowlength)

#### Defined in

[ue/ue.d.ts:24603](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24603)

___

### ContactShadowLengthInWS

• **ContactShadowLengthInWS**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ContactShadowLengthInWS](ue_ue.LocalLightComponent.md#contactshadowlengthinws)

#### Defined in

[ue/ue.d.ts:24604](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24604)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[CreationMethod](ue_ue.LocalLightComponent.md#creationmethod)

#### Defined in

[ue/ue.d.ts:302](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L302)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[DetailMode](ue_ue.LocalLightComponent.md#detailmode)

#### Defined in

[ue/ue.d.ts:12893](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12893)

___

### DisabledBrightness

• **DisabledBrightness**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[DisabledBrightness](ue_ue.LocalLightComponent.md#disabledbrightness)

#### Defined in

[ue/ue.d.ts:24617](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24617)

___

### DynamicEditorTexture

• **DynamicEditorTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[DynamicEditorTexture](ue_ue.LocalLightComponent.md#dynamiceditortexture)

#### Defined in

[ue/ue.d.ts:21376](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21376)

___

### DynamicEditorTextureScale

• **DynamicEditorTextureScale**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[DynamicEditorTextureScale](ue_ue.LocalLightComponent.md#dynamiceditortexturescale)

#### Defined in

[ue/ue.d.ts:21377](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21377)

___

### IESBrightnessScale

• **IESBrightnessScale**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[IESBrightnessScale](ue_ue.LocalLightComponent.md#iesbrightnessscale)

#### Defined in

[ue/ue.d.ts:24615](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24615)

___

### IESTexture

• **IESTexture**: [`TextureLightProfile`](ue_ue.TextureLightProfile.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[IESTexture](ue_ue.LocalLightComponent.md#iestexture)

#### Defined in

[ue/ue.d.ts:24613](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24613)

___

### IndirectLightingIntensity

• **IndirectLightingIntensity**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[IndirectLightingIntensity](ue_ue.LocalLightComponent.md#indirectlightingintensity)

#### Defined in

[ue/ue.d.ts:21371](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21371)

___

### Intensity

• **Intensity**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[Intensity](ue_ue.LocalLightComponent.md#intensity)

#### Defined in

[ue/ue.d.ts:21358](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21358)

___

### IntensityUnits

• **IntensityUnits**: [`ELightUnits`](../enums/ue_ue.ELightUnits.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[IntensityUnits](ue_ue.LocalLightComponent.md#intensityunits)

#### Defined in

[ue/ue.d.ts:37431](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37431)

___

### InverseSquaredFalloff

• **InverseSquaredFalloff**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[InverseSquaredFalloff](ue_ue.LocalLightComponent.md#inversesquaredfalloff)

#### Defined in

[ue/ue.d.ts:24605](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24605)

___

### LightColor

• **LightColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[LightColor](ue_ue.LocalLightComponent.md#lightcolor)

#### Defined in

[ue/ue.d.ts:21359](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21359)

___

### LightFalloffExponent

• **LightFalloffExponent**: `number`

#### Defined in

[ue/ue.d.ts:37448](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37448)

___

### LightFunctionFadeDistance

• **LightFunctionFadeDistance**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[LightFunctionFadeDistance](ue_ue.LocalLightComponent.md#lightfunctionfadedistance)

#### Defined in

[ue/ue.d.ts:24616](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24616)

___

### LightFunctionMaterial

• **LightFunctionMaterial**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[LightFunctionMaterial](ue_ue.LocalLightComponent.md#lightfunctionmaterial)

#### Defined in

[ue/ue.d.ts:24611](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24611)

___

### LightFunctionScale

• **LightFunctionScale**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[LightFunctionScale](ue_ue.LocalLightComponent.md#lightfunctionscale)

#### Defined in

[ue/ue.d.ts:24612](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24612)

___

### LightGuid

• **LightGuid**: [`Guid`](ue_ue_s.Guid.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[LightGuid](ue_ue.LocalLightComponent.md#lightguid)

#### Defined in

[ue/ue.d.ts:21356](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21356)

___

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[LightingChannels](ue_ue.LocalLightComponent.md#lightingchannels)

#### Defined in

[ue/ue.d.ts:24610](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24610)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassPointLightSettings`](ue_ue.LightmassPointLightSettings.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[LightmassSettings](ue_ue.LocalLightComponent.md#lightmasssettings)

#### Defined in

[ue/ue.d.ts:37434](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37434)

___

### MaxDistanceFadeRange

• **MaxDistanceFadeRange**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[MaxDistanceFadeRange](ue_ue.LocalLightComponent.md#maxdistancefaderange)

#### Defined in

[ue/ue.d.ts:24594](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24594)

___

### MaxDrawDistance

• **MaxDrawDistance**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[MaxDrawDistance](ue_ue.LocalLightComponent.md#maxdrawdistance)

#### Defined in

[ue/ue.d.ts:24593](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24593)

___

### MinRoughness

• **MinRoughness**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[MinRoughness](ue_ue.LocalLightComponent.md#minroughness)

#### Defined in

[ue/ue.d.ts:24597](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24597)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[Mobility](ue_ue.LocalLightComponent.md#mobility)

#### Defined in

[ue/ue.d.ts:12892](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12892)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[OnComponentActivated](ue_ue.LocalLightComponent.md#oncomponentactivated)

#### Defined in

[ue/ue.d.ts:303](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L303)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[OnComponentDeactivated](ue_ue.LocalLightComponent.md#oncomponentdeactivated)

#### Defined in

[ue/ue.d.ts:304](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L304)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[PhysicsVolume](ue_ue.LocalLightComponent.md#physicsvolume)

#### Defined in

[ue/ue.d.ts:12870](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12870)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.LocalLightComponent.md#physicsvolumechangeddelegate)

#### Defined in

[ue/ue.d.ts:12894](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12894)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[PrimaryComponentTick](ue_ue.LocalLightComponent.md#primarycomponenttick)

#### Defined in

[ue/ue.d.ts:289](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L289)

___

### Radius

• **Radius**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[Radius](ue_ue.LocalLightComponent.md#radius)

#### Defined in

[ue/ue.d.ts:37432](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37432)

___

### RayStartOffsetDepthScale

• **RayStartOffsetDepthScale**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[RayStartOffsetDepthScale](ue_ue.LocalLightComponent.md#raystartoffsetdepthscale)

#### Defined in

[ue/ue.d.ts:24624](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24624)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[RelativeLocation](ue_ue.LocalLightComponent.md#relativelocation)

#### Defined in

[ue/ue.d.ts:12875](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12875)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[RelativeRotation](ue_ue.LocalLightComponent.md#relativerotation)

#### Defined in

[ue/ue.d.ts:12876](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12876)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[RelativeScale3D](ue_ue.LocalLightComponent.md#relativescale3d)

#### Defined in

[ue/ue.d.ts:12877](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12877)

___

### SamplesPerPixel

• **SamplesPerPixel**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SamplesPerPixel](ue_ue.LocalLightComponent.md#samplesperpixel)

#### Defined in

[ue/ue.d.ts:21373](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21373)

___

### ShadowBias

• **ShadowBias**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ShadowBias](ue_ue.LocalLightComponent.md#shadowbias)

#### Defined in

[ue/ue.d.ts:24600](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24600)

___

### ShadowMapChannel

• **ShadowMapChannel**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ShadowMapChannel](ue_ue.LocalLightComponent.md#shadowmapchannel)

#### Defined in

[ue/ue.d.ts:24596](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24596)

___

### ShadowResolutionScale

• **ShadowResolutionScale**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ShadowResolutionScale](ue_ue.LocalLightComponent.md#shadowresolutionscale)

#### Defined in

[ue/ue.d.ts:24599](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24599)

___

### ShadowSharpen

• **ShadowSharpen**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ShadowSharpen](ue_ue.LocalLightComponent.md#shadowsharpen)

#### Defined in

[ue/ue.d.ts:24602](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24602)

___

### ShadowSlopeBias

• **ShadowSlopeBias**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ShadowSlopeBias](ue_ue.LocalLightComponent.md#shadowslopebias)

#### Defined in

[ue/ue.d.ts:24601](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24601)

___

### SoftSourceRadius

• **SoftSourceRadius**: `number`

#### Defined in

[ue/ue.d.ts:37450](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37450)

___

### SourceLength

• **SourceLength**: `number`

#### Defined in

[ue/ue.d.ts:37451](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37451)

___

### SourceRadius

• **SourceRadius**: `number`

#### Defined in

[ue/ue.d.ts:37449](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37449)

___

### SpecularScale

• **SpecularScale**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SpecularScale](ue_ue.LocalLightComponent.md#specularscale)

#### Defined in

[ue/ue.d.ts:24598](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24598)

___

### StaticEditorTexture

• **StaticEditorTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[StaticEditorTexture](ue_ue.LocalLightComponent.md#staticeditortexture)

#### Defined in

[ue/ue.d.ts:21374](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21374)

___

### StaticEditorTextureScale

• **StaticEditorTextureScale**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[StaticEditorTextureScale](ue_ue.LocalLightComponent.md#staticeditortexturescale)

#### Defined in

[ue/ue.d.ts:21375](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21375)

___

### Temperature

• **Temperature**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[Temperature](ue_ue.LocalLightComponent.md#temperature)

#### Defined in

[ue/ue.d.ts:24592](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24592)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[UCSModifiedProperties](ue_ue.LocalLightComponent.md#ucsmodifiedproperties)

#### Defined in

[ue/ue.d.ts:305](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L305)

___

### VolumetricScatteringIntensity

• **VolumetricScatteringIntensity**: `number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[VolumetricScatteringIntensity](ue_ue.LocalLightComponent.md#volumetricscatteringintensity)

#### Defined in

[ue/ue.d.ts:21372](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21372)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[__tid_ActorComponent__](ue_ue.LocalLightComponent.md#__tid_actorcomponent__)

#### Defined in

[ue/ue.d.ts:336](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L336)

___

### \_\_tid\_LightComponentBase\_\_

• **\_\_tid\_LightComponentBase\_\_**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[__tid_LightComponentBase__](ue_ue.LocalLightComponent.md#__tid_lightcomponentbase__)

#### Defined in

[ue/ue.d.ts:21390](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21390)

___

### \_\_tid\_LightComponent\_\_

• **\_\_tid\_LightComponent\_\_**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[__tid_LightComponent__](ue_ue.LocalLightComponent.md#__tid_lightcomponent__)

#### Defined in

[ue/ue.d.ts:24653](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24653)

___

### \_\_tid\_LocalLightComponent\_\_

• **\_\_tid\_LocalLightComponent\_\_**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[__tid_LocalLightComponent__](ue_ue.LocalLightComponent.md#__tid_locallightcomponent__)

#### Defined in

[ue/ue.d.ts:37442](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37442)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[__tid_Object__](ue_ue.LocalLightComponent.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21)

___

### \_\_tid\_PointLightComponent\_\_

• **\_\_tid\_PointLightComponent\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:37460](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37460)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[__tid_SceneComponent__](ue_ue.LocalLightComponent.md#__tid_scenecomponent__)

#### Defined in

[ue/ue.d.ts:12961](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12961)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bAbsoluteLocation](ue_ue.LocalLightComponent.md#babsolutelocation)

#### Defined in

[ue/ue.d.ts:12880](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12880)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bAbsoluteRotation](ue_ue.LocalLightComponent.md#babsoluterotation)

#### Defined in

[ue/ue.d.ts:12881](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12881)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bAbsoluteScale](ue_ue.LocalLightComponent.md#babsolutescale)

#### Defined in

[ue/ue.d.ts:12882](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12882)

___

### bAffectDynamicIndirectLighting

• **bAffectDynamicIndirectLighting**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bAffectDynamicIndirectLighting](ue_ue.LocalLightComponent.md#baffectdynamicindirectlighting)

#### Defined in

[ue/ue.d.ts:24608](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24608)

___

### bAffectGlobalIllumination

• **bAffectGlobalIllumination**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bAffectGlobalIllumination](ue_ue.LocalLightComponent.md#baffectglobalillumination)

#### Defined in

[ue/ue.d.ts:21370](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21370)

___

### bAffectReflection

• **bAffectReflection**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bAffectReflection](ue_ue.LocalLightComponent.md#baffectreflection)

#### Defined in

[ue/ue.d.ts:21369](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21369)

___

### bAffectTranslucentLighting

• **bAffectTranslucentLighting**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bAffectTranslucentLighting](ue_ue.LocalLightComponent.md#baffecttranslucentlighting)

#### Defined in

[ue/ue.d.ts:21364](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21364)

___

### bAffectsWorld

• **bAffectsWorld**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bAffectsWorld](ue_ue.LocalLightComponent.md#baffectsworld)

#### Defined in

[ue/ue.d.ts:21360](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21360)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bAutoActivate](ue_ue.LocalLightComponent.md#bautoactivate)

#### Defined in

[ue/ue.d.ts:296](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L296)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.LocalLightComponent.md#bboundschangetriggersstreamingdatarebuild)

#### Defined in

[ue/ue.d.ts:12889](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12889)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bCanEverAffectNavigation](ue_ue.LocalLightComponent.md#bcaneveraffectnavigation)

#### Defined in

[ue/ue.d.ts:299](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L299)

___

### bCastDeepShadow

• **bCastDeepShadow**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bCastDeepShadow](ue_ue.LocalLightComponent.md#bcastdeepshadow)

#### Defined in

[ue/ue.d.ts:21367](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21367)

___

### bCastRaytracedShadow

• **bCastRaytracedShadow**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bCastRaytracedShadow](ue_ue.LocalLightComponent.md#bcastraytracedshadow)

#### Defined in

[ue/ue.d.ts:21368](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21368)

___

### bCastShadowsFromCinematicObjectsOnly

• **bCastShadowsFromCinematicObjectsOnly**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bCastShadowsFromCinematicObjectsOnly](ue_ue.LocalLightComponent.md#bcastshadowsfromcinematicobjectsonly)

#### Defined in

[ue/ue.d.ts:24607](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24607)

___

### bCastVolumetricShadow

• **bCastVolumetricShadow**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bCastVolumetricShadow](ue_ue.LocalLightComponent.md#bcastvolumetricshadow)

#### Defined in

[ue/ue.d.ts:21366](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21366)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bComponentToWorldUpdated](ue_ue.LocalLightComponent.md#bcomponenttoworldupdated)

#### Defined in

[ue/ue.d.ts:12879](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12879)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bCreatedByConstructionScript](ue_ue.LocalLightComponent.md#bcreatedbyconstructionscript)

#### Defined in

[ue/ue.d.ts:294](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L294)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bEditableWhenInherited](ue_ue.LocalLightComponent.md#beditablewheninherited)

#### Defined in

[ue/ue.d.ts:298](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L298)

___

### bEnableLightShaftBloom

• **bEnableLightShaftBloom**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bEnableLightShaftBloom](ue_ue.LocalLightComponent.md#benablelightshaftbloom)

#### Defined in

[ue/ue.d.ts:24618](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24618)

___

### bForceCachedShadowsForMovablePrimitives

• **bForceCachedShadowsForMovablePrimitives**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bForceCachedShadowsForMovablePrimitives](ue_ue.LocalLightComponent.md#bforcecachedshadowsformovableprimitives)

#### Defined in

[ue/ue.d.ts:24609](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24609)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bHiddenInGame](ue_ue.LocalLightComponent.md#bhiddeningame)

#### Defined in

[ue/ue.d.ts:12884](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12884)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bInstanceComponent](ue_ue.LocalLightComponent.md#binstancecomponent)

#### Defined in

[ue/ue.d.ts:295](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L295)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bIsActive](ue_ue.LocalLightComponent.md#bisactive)

#### Defined in

[ue/ue.d.ts:297](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L297)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bIsEditorOnly](ue_ue.LocalLightComponent.md#biseditoronly)

#### Defined in

[ue/ue.d.ts:300](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L300)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bIsVisualizationComponent](ue_ue.LocalLightComponent.md#bisvisualizationcomponent)

#### Defined in

[ue/ue.d.ts:301](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L301)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bNetAddressable](ue_ue.LocalLightComponent.md#bnetaddressable)

#### Defined in

[ue/ue.d.ts:293](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L293)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bReplicates](ue_ue.LocalLightComponent.md#breplicates)

#### Defined in

[ue/ue.d.ts:292](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L292)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bShouldBeAttached](ue_ue.LocalLightComponent.md#bshouldbeattached)

#### Defined in

[ue/ue.d.ts:12885](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12885)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.LocalLightComponent.md#bshouldsnaplocationwhenattached)

#### Defined in

[ue/ue.d.ts:12886](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12886)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.LocalLightComponent.md#bshouldsnaprotationwhenattached)

#### Defined in

[ue/ue.d.ts:12887](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12887)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.LocalLightComponent.md#bshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12888](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12888)

___

### bTransmission

• **bTransmission**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bTransmission](ue_ue.LocalLightComponent.md#btransmission)

#### Defined in

[ue/ue.d.ts:21365](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21365)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bUseAttachParentBound](ue_ue.LocalLightComponent.md#buseattachparentbound)

#### Defined in

[ue/ue.d.ts:12890](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12890)

___

### bUseIESBrightness

• **bUseIESBrightness**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bUseIESBrightness](ue_ue.LocalLightComponent.md#buseiesbrightness)

#### Defined in

[ue/ue.d.ts:24614](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24614)

___

### bUseInverseSquaredFalloff

• **bUseInverseSquaredFalloff**: `boolean`

#### Defined in

[ue/ue.d.ts:37447](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37447)

___

### bUseRayTracedDistanceFieldShadows

• **bUseRayTracedDistanceFieldShadows**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bUseRayTracedDistanceFieldShadows](ue_ue.LocalLightComponent.md#buseraytraceddistancefieldshadows)

#### Defined in

[ue/ue.d.ts:24623](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24623)

___

### bUseTemperature

• **bUseTemperature**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bUseTemperature](ue_ue.LocalLightComponent.md#busetemperature)

#### Defined in

[ue/ue.d.ts:24595](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24595)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bVisible](ue_ue.LocalLightComponent.md#bvisible)

#### Defined in

[ue/ue.d.ts:12883](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12883)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[bVisualizeComponent](ue_ue.LocalLightComponent.md#bvisualizecomponent)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[Activate](ue_ue.LocalLightComponent.md#activate)

#### Defined in

[ue/ue.d.ts:306](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L306)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[AddTickPrerequisiteActor](ue_ue.LocalLightComponent.md#addtickprerequisiteactor)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[AddTickPrerequisiteComponent](ue_ue.LocalLightComponent.md#addtickprerequisitecomponent)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ComponentHasTag](ue_ue.LocalLightComponent.md#componenthastag)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[CreateDefaultSubobject](ue_ue.LocalLightComponent.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L11)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[Deactivate](ue_ue.LocalLightComponent.md#deactivate)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[DetachFromParent](ue_ue.LocalLightComponent.md#detachfromparent)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[DoesSocketExist](ue_ue.LocalLightComponent.md#doessocketexist)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ExecuteUbergraph](ue_ue.LocalLightComponent.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetAllSocketNames](ue_ue.LocalLightComponent.md#getallsocketnames)

#### Defined in

[ue/ue.d.ts:12897](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12897)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetAttachParent](ue_ue.LocalLightComponent.md#getattachparent)

#### Defined in

[ue/ue.d.ts:12898](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12898)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetAttachSocketName](ue_ue.LocalLightComponent.md#getattachsocketname)

#### Defined in

[ue/ue.d.ts:12899](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12899)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetChildComponent](ue_ue.LocalLightComponent.md#getchildcomponent)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetChildrenComponents](ue_ue.LocalLightComponent.md#getchildrencomponents)

#### Defined in

[ue/ue.d.ts:12901](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12901)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetClass](ue_ue.LocalLightComponent.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L13)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetComponentTickInterval](ue_ue.LocalLightComponent.md#getcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:311](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L311)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetComponentVelocity](ue_ue.LocalLightComponent.md#getcomponentvelocity)

#### Defined in

[ue/ue.d.ts:12902](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12902)

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetForwardVector](ue_ue.LocalLightComponent.md#getforwardvector)

#### Defined in

[ue/ue.d.ts:12903](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12903)

___

### GetLightColor

▸ **GetLightColor**(): [`LinearColor`](ue_ue_s.LinearColor.md)

#### Returns

[`LinearColor`](ue_ue_s.LinearColor.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetLightColor](ue_ue.LocalLightComponent.md#getlightcolor)

#### Defined in

[ue/ue.d.ts:21378](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21378)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetName](ue_ue.LocalLightComponent.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L14)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetNumChildrenComponents](ue_ue.LocalLightComponent.md#getnumchildrencomponents)

#### Defined in

[ue/ue.d.ts:12904](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12904)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetOuter](ue_ue.LocalLightComponent.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L15)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetOwner](ue_ue.LocalLightComponent.md#getowner)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetParentComponents](ue_ue.LocalLightComponent.md#getparentcomponents)

#### Defined in

[ue/ue.d.ts:12905](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12905)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetPhysicsVolume](ue_ue.LocalLightComponent.md#getphysicsvolume)

#### Defined in

[ue/ue.d.ts:12906](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12906)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetRelativeTransform](ue_ue.LocalLightComponent.md#getrelativetransform)

#### Defined in

[ue/ue.d.ts:12907](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12907)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetRightVector](ue_ue.LocalLightComponent.md#getrightvector)

#### Defined in

[ue/ue.d.ts:12908](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12908)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.LocalLightComponent.md#getshouldupdatephysicsvolume)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetSocketLocation](ue_ue.LocalLightComponent.md#getsocketlocation)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetSocketQuaternion](ue_ue.LocalLightComponent.md#getsocketquaternion)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetSocketRotation](ue_ue.LocalLightComponent.md#getsocketrotation)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetSocketTransform](ue_ue.LocalLightComponent.md#getsockettransform)

#### Defined in

[ue/ue.d.ts:12913](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12913)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetUpVector](ue_ue.LocalLightComponent.md#getupvector)

#### Defined in

[ue/ue.d.ts:12914](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12914)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetWorld](ue_ue.LocalLightComponent.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L16)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[IsActive](ue_ue.LocalLightComponent.md#isactive)

#### Defined in

[ue/ue.d.ts:313](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L313)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[IsAnySimulatingPhysics](ue_ue.LocalLightComponent.md#isanysimulatingphysics)

#### Defined in

[ue/ue.d.ts:12915](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12915)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[IsBeingDestroyed](ue_ue.LocalLightComponent.md#isbeingdestroyed)

#### Defined in

[ue/ue.d.ts:314](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L314)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[IsComponentTickEnabled](ue_ue.LocalLightComponent.md#iscomponenttickenabled)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[IsSimulatingPhysics](ue_ue.LocalLightComponent.md#issimulatingphysics)

#### Defined in

[ue/ue.d.ts:12916](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12916)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[IsVisible](ue_ue.LocalLightComponent.md#isvisible)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_AddLocalOffset](ue_ue.LocalLightComponent.md#k2_addlocaloffset)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_AddLocalRotation](ue_ue.LocalLightComponent.md#k2_addlocalrotation)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_AddLocalTransform](ue_ue.LocalLightComponent.md#k2_addlocaltransform)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_AddRelativeLocation](ue_ue.LocalLightComponent.md#k2_addrelativelocation)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_AddRelativeRotation](ue_ue.LocalLightComponent.md#k2_addrelativerotation)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_AddWorldOffset](ue_ue.LocalLightComponent.md#k2_addworldoffset)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_AddWorldRotation](ue_ue.LocalLightComponent.md#k2_addworldrotation)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_AddWorldTransform](ue_ue.LocalLightComponent.md#k2_addworldtransform)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_AttachTo](ue_ue.LocalLightComponent.md#k2_attachto)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_AttachToComponent](ue_ue.LocalLightComponent.md#k2_attachtocomponent)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_DestroyComponent](ue_ue.LocalLightComponent.md#k2_destroycomponent)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_DetachFromComponent](ue_ue.LocalLightComponent.md#k2_detachfromcomponent)

#### Defined in

[ue/ue.d.ts:12928](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12928)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_GetComponentLocation](ue_ue.LocalLightComponent.md#k2_getcomponentlocation)

#### Defined in

[ue/ue.d.ts:12929](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12929)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_GetComponentRotation](ue_ue.LocalLightComponent.md#k2_getcomponentrotation)

#### Defined in

[ue/ue.d.ts:12930](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12930)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_GetComponentScale](ue_ue.LocalLightComponent.md#k2_getcomponentscale)

#### Defined in

[ue/ue.d.ts:12931](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12931)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_GetComponentToWorld](ue_ue.LocalLightComponent.md#k2_getcomponenttoworld)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_SetRelativeLocation](ue_ue.LocalLightComponent.md#k2_setrelativelocation)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.LocalLightComponent.md#k2_setrelativelocationandrotation)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_SetRelativeRotation](ue_ue.LocalLightComponent.md#k2_setrelativerotation)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_SetRelativeTransform](ue_ue.LocalLightComponent.md#k2_setrelativetransform)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_SetWorldLocation](ue_ue.LocalLightComponent.md#k2_setworldlocation)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.LocalLightComponent.md#k2_setworldlocationandrotation)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_SetWorldRotation](ue_ue.LocalLightComponent.md#k2_setworldrotation)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[K2_SetWorldTransform](ue_ue.LocalLightComponent.md#k2_setworldtransform)

#### Defined in

[ue/ue.d.ts:12940](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12940)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[OnRep_AttachChildren](ue_ue.LocalLightComponent.md#onrep_attachchildren)

#### Defined in

[ue/ue.d.ts:12941](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12941)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[OnRep_AttachParent](ue_ue.LocalLightComponent.md#onrep_attachparent)

#### Defined in

[ue/ue.d.ts:12942](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12942)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[OnRep_AttachSocketName](ue_ue.LocalLightComponent.md#onrep_attachsocketname)

#### Defined in

[ue/ue.d.ts:12943](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12943)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[OnRep_IsActive](ue_ue.LocalLightComponent.md#onrep_isactive)

#### Defined in

[ue/ue.d.ts:317](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L317)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[OnRep_Transform](ue_ue.LocalLightComponent.md#onrep_transform)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[OnRep_Visibility](ue_ue.LocalLightComponent.md#onrep_visibility)

#### Defined in

[ue/ue.d.ts:12945](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12945)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ReceiveBeginPlay](ue_ue.LocalLightComponent.md#receivebeginplay)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ReceiveEndPlay](ue_ue.LocalLightComponent.md#receiveendplay)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ReceiveTick](ue_ue.LocalLightComponent.md#receivetick)

#### Defined in

[ue/ue.d.ts:320](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L320)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[RegisterComponent](ue_ue.LocalLightComponent.md#registercomponent)

#### Defined in

[ue/ue.d.ts:321](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L321)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[RemoveTickPrerequisiteActor](ue_ue.LocalLightComponent.md#removetickprerequisiteactor)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.LocalLightComponent.md#removetickprerequisitecomponent)

#### Defined in

[ue/ue.d.ts:323](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L323)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ResetRelativeTransform](ue_ue.LocalLightComponent.md#resetrelativetransform)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetAbsolute](ue_ue.LocalLightComponent.md#setabsolute)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetActive](ue_ue.LocalLightComponent.md#setactive)

#### Defined in

[ue/ue.d.ts:324](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L324)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetAffectDynamicIndirectLighting](ue_ue.LocalLightComponent.md#setaffectdynamicindirectlighting)

#### Defined in

[ue/ue.d.ts:24625](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24625)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetAffectGlobalIllumination](ue_ue.LocalLightComponent.md#setaffectglobalillumination)

#### Defined in

[ue/ue.d.ts:21379](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21379)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetAffectReflection](ue_ue.LocalLightComponent.md#setaffectreflection)

#### Defined in

[ue/ue.d.ts:21380](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21380)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetAffectTranslucentLighting](ue_ue.LocalLightComponent.md#setaffecttranslucentlighting)

#### Defined in

[ue/ue.d.ts:24626](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24626)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetAttenuationRadius](ue_ue.LocalLightComponent.md#setattenuationradius)

#### Defined in

[ue/ue.d.ts:37435](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37435)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetAutoActivate](ue_ue.LocalLightComponent.md#setautoactivate)

#### Defined in

[ue/ue.d.ts:325](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L325)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetBloomMaxBrightness](ue_ue.LocalLightComponent.md#setbloommaxbrightness)

#### Defined in

[ue/ue.d.ts:24627](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24627)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetBloomScale](ue_ue.LocalLightComponent.md#setbloomscale)

#### Defined in

[ue/ue.d.ts:24628](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24628)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetBloomThreshold](ue_ue.LocalLightComponent.md#setbloomthreshold)

#### Defined in

[ue/ue.d.ts:24629](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24629)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetBloomTint](ue_ue.LocalLightComponent.md#setbloomtint)

#### Defined in

[ue/ue.d.ts:24630](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24630)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetCastDeepShadow](ue_ue.LocalLightComponent.md#setcastdeepshadow)

#### Defined in

[ue/ue.d.ts:21381](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21381)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetCastRaytracedShadow](ue_ue.LocalLightComponent.md#setcastraytracedshadow)

#### Defined in

[ue/ue.d.ts:21382](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21382)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetCastShadows](ue_ue.LocalLightComponent.md#setcastshadows)

#### Defined in

[ue/ue.d.ts:21383](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21383)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetCastVolumetricShadow](ue_ue.LocalLightComponent.md#setcastvolumetricshadow)

#### Defined in

[ue/ue.d.ts:21384](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21384)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetComponentTickEnabled](ue_ue.LocalLightComponent.md#setcomponenttickenabled)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetComponentTickInterval](ue_ue.LocalLightComponent.md#setcomponenttickinterval)

#### Defined in

[ue/ue.d.ts:327](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L327)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetEnableLightShaftBloom](ue_ue.LocalLightComponent.md#setenablelightshaftbloom)

#### Defined in

[ue/ue.d.ts:24631](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24631)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetForceCachedShadowsForMovablePrimitives](ue_ue.LocalLightComponent.md#setforcecachedshadowsformovableprimitives)

#### Defined in

[ue/ue.d.ts:24632](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24632)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetHiddenInGame](ue_ue.LocalLightComponent.md#sethiddeningame)

#### Defined in

[ue/ue.d.ts:12948](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12948)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetIESBrightnessScale](ue_ue.LocalLightComponent.md#setiesbrightnessscale)

#### Defined in

[ue/ue.d.ts:24633](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24633)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetIESTexture](ue_ue.LocalLightComponent.md#setiestexture)

#### Defined in

[ue/ue.d.ts:24634](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24634)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetIndirectLightingIntensity](ue_ue.LocalLightComponent.md#setindirectlightingintensity)

#### Defined in

[ue/ue.d.ts:24635](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24635)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetIntensity](ue_ue.LocalLightComponent.md#setintensity)

#### Defined in

[ue/ue.d.ts:24636](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24636)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetIntensityUnits](ue_ue.LocalLightComponent.md#setintensityunits)

#### Defined in

[ue/ue.d.ts:37436](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37436)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetIsReplicated](ue_ue.LocalLightComponent.md#setisreplicated)

#### Defined in

[ue/ue.d.ts:328](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L328)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetLightColor](ue_ue.LocalLightComponent.md#setlightcolor)

#### Defined in

[ue/ue.d.ts:24637](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24637)

___

### SetLightFalloffExponent

▸ **SetLightFalloffExponent**(`NewLightFalloffExponent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewLightFalloffExponent` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:37452](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37452)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetLightFunctionDisabledBrightness](ue_ue.LocalLightComponent.md#setlightfunctiondisabledbrightness)

#### Defined in

[ue/ue.d.ts:24638](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24638)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetLightFunctionFadeDistance](ue_ue.LocalLightComponent.md#setlightfunctionfadedistance)

#### Defined in

[ue/ue.d.ts:24639](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24639)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetLightFunctionMaterial](ue_ue.LocalLightComponent.md#setlightfunctionmaterial)

#### Defined in

[ue/ue.d.ts:24640](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24640)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetLightFunctionScale](ue_ue.LocalLightComponent.md#setlightfunctionscale)

#### Defined in

[ue/ue.d.ts:24641](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24641)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetMobility](ue_ue.LocalLightComponent.md#setmobility)

#### Defined in

[ue/ue.d.ts:12949](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12949)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetRelativeScale3D](ue_ue.LocalLightComponent.md#setrelativescale3d)

#### Defined in

[ue/ue.d.ts:12950](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12950)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetSamplesPerPixel](ue_ue.LocalLightComponent.md#setsamplesperpixel)

#### Defined in

[ue/ue.d.ts:21385](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L21385)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetShadowBias](ue_ue.LocalLightComponent.md#setshadowbias)

#### Defined in

[ue/ue.d.ts:24642](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24642)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetShadowSlopeBias](ue_ue.LocalLightComponent.md#setshadowslopebias)

#### Defined in

[ue/ue.d.ts:24643](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24643)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.LocalLightComponent.md#setshouldupdatephysicsvolume)

#### Defined in

[ue/ue.d.ts:12951](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12951)

___

### SetSoftSourceRadius

▸ **SetSoftSourceRadius**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:37453](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37453)

___

### SetSourceLength

▸ **SetSourceLength**(`NewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewValue` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:37454](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37454)

___

### SetSourceRadius

▸ **SetSourceRadius**(`bNewValue`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bNewValue` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:37455](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37455)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetSpecularScale](ue_ue.LocalLightComponent.md#setspecularscale)

#### Defined in

[ue/ue.d.ts:24644](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24644)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetTemperature](ue_ue.LocalLightComponent.md#settemperature)

#### Defined in

[ue/ue.d.ts:24645](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24645)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetTickGroup](ue_ue.LocalLightComponent.md#settickgroup)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetTickableWhenPaused](ue_ue.LocalLightComponent.md#settickablewhenpaused)

#### Defined in

[ue/ue.d.ts:329](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L329)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetTransmission](ue_ue.LocalLightComponent.md#settransmission)

#### Defined in

[ue/ue.d.ts:24646](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24646)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetUseIESBrightness](ue_ue.LocalLightComponent.md#setuseiesbrightness)

#### Defined in

[ue/ue.d.ts:24647](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24647)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetVisibility](ue_ue.LocalLightComponent.md#setvisibility)

#### Defined in

[ue/ue.d.ts:12953](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12953)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetVolumetricScatteringIntensity](ue_ue.LocalLightComponent.md#setvolumetricscatteringintensity)

#### Defined in

[ue/ue.d.ts:24648](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L24648)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetWorldScale3D](ue_ue.LocalLightComponent.md#setworldscale3d)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SetupAttachment](ue_ue.LocalLightComponent.md#setupattachment)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[SnapTo](ue_ue.LocalLightComponent.md#snapto)

#### Defined in

[ue/ue.d.ts:12955](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12955)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ToggleActive](ue_ue.LocalLightComponent.md#toggleactive)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[ToggleVisibility](ue_ue.LocalLightComponent.md#togglevisibility)

#### Defined in

[ue/ue.d.ts:12956](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L12956)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`PointLightComponent`](ue_ue.PointLightComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`PointLightComponent`](ue_ue.PointLightComponent.md)

#### Overrides

[LocalLightComponent](ue_ue.LocalLightComponent.md).[Find](ue_ue.LocalLightComponent.md#find)

#### Defined in

[ue/ue.d.ts:37457](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37457)

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

[LocalLightComponent](ue_ue.LocalLightComponent.md).[GetUnitsConversionFactor](ue_ue.LocalLightComponent.md#getunitsconversionfactor)

#### Defined in

[ue/ue.d.ts:37437](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37437)

___

### Load

▸ `Static` **Load**(`InName`): [`PointLightComponent`](ue_ue.PointLightComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`PointLightComponent`](ue_ue.PointLightComponent.md)

#### Overrides

[LocalLightComponent](ue_ue.LocalLightComponent.md).[Load](ue_ue.LocalLightComponent.md#load)

#### Defined in

[ue/ue.d.ts:37458](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37458)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[LocalLightComponent](ue_ue.LocalLightComponent.md).[StaticClass](ue_ue.LocalLightComponent.md#staticclass)

#### Defined in

[ue/ue.d.ts:37456](https://github.com/YugMetaverse/yug_typings/blob/b7d9b19/ue/ue.d.ts#L37456)
