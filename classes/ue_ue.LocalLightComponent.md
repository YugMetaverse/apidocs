[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / LocalLightComponent

# Class: LocalLightComponent

[ue/ue](../modules/ue_ue.md).LocalLightComponent

## Hierarchy

- [`LightComponent`](ue_ue.LightComponent.md)

  ↳ **`LocalLightComponent`**

  ↳↳ [`PointLightComponent`](ue_ue.PointLightComponent.md)

  ↳↳ [`RectLightComponent`](ue_ue.RectLightComponent.md)

## Table of contents

### Constructors

- [constructor](ue_ue.LocalLightComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.LocalLightComponent.md#assetuserdata)
- [AttachChildren](ue_ue.LocalLightComponent.md#attachchildren)
- [AttachParent](ue_ue.LocalLightComponent.md#attachparent)
- [AttachSocketName](ue_ue.LocalLightComponent.md#attachsocketname)
- [AttenuationRadius](ue_ue.LocalLightComponent.md#attenuationradius)
- [BloomMaxBrightness](ue_ue.LocalLightComponent.md#bloommaxbrightness)
- [BloomScale](ue_ue.LocalLightComponent.md#bloomscale)
- [BloomThreshold](ue_ue.LocalLightComponent.md#bloomthreshold)
- [BloomTint](ue_ue.LocalLightComponent.md#bloomtint)
- [Brightness](ue_ue.LocalLightComponent.md#brightness)
- [CastDynamicShadows](ue_ue.LocalLightComponent.md#castdynamicshadows)
- [CastShadows](ue_ue.LocalLightComponent.md#castshadows)
- [CastStaticShadows](ue_ue.LocalLightComponent.md#caststaticshadows)
- [CastTranslucentShadows](ue_ue.LocalLightComponent.md#casttranslucentshadows)
- [ClientAttachedChildren](ue_ue.LocalLightComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.LocalLightComponent.md#componenttags)
- [ComponentVelocity](ue_ue.LocalLightComponent.md#componentvelocity)
- [ContactShadowLength](ue_ue.LocalLightComponent.md#contactshadowlength)
- [ContactShadowLengthInWS](ue_ue.LocalLightComponent.md#contactshadowlengthinws)
- [CreationMethod](ue_ue.LocalLightComponent.md#creationmethod)
- [DetailMode](ue_ue.LocalLightComponent.md#detailmode)
- [DisabledBrightness](ue_ue.LocalLightComponent.md#disabledbrightness)
- [DynamicEditorTexture](ue_ue.LocalLightComponent.md#dynamiceditortexture)
- [DynamicEditorTextureScale](ue_ue.LocalLightComponent.md#dynamiceditortexturescale)
- [IESBrightnessScale](ue_ue.LocalLightComponent.md#iesbrightnessscale)
- [IESTexture](ue_ue.LocalLightComponent.md#iestexture)
- [IndirectLightingIntensity](ue_ue.LocalLightComponent.md#indirectlightingintensity)
- [Intensity](ue_ue.LocalLightComponent.md#intensity)
- [IntensityUnits](ue_ue.LocalLightComponent.md#intensityunits)
- [InverseSquaredFalloff](ue_ue.LocalLightComponent.md#inversesquaredfalloff)
- [LightColor](ue_ue.LocalLightComponent.md#lightcolor)
- [LightFunctionFadeDistance](ue_ue.LocalLightComponent.md#lightfunctionfadedistance)
- [LightFunctionMaterial](ue_ue.LocalLightComponent.md#lightfunctionmaterial)
- [LightFunctionScale](ue_ue.LocalLightComponent.md#lightfunctionscale)
- [LightGuid](ue_ue.LocalLightComponent.md#lightguid)
- [LightingChannels](ue_ue.LocalLightComponent.md#lightingchannels)
- [LightmassSettings](ue_ue.LocalLightComponent.md#lightmasssettings)
- [MaxDistanceFadeRange](ue_ue.LocalLightComponent.md#maxdistancefaderange)
- [MaxDrawDistance](ue_ue.LocalLightComponent.md#maxdrawdistance)
- [MinRoughness](ue_ue.LocalLightComponent.md#minroughness)
- [Mobility](ue_ue.LocalLightComponent.md#mobility)
- [OnComponentActivated](ue_ue.LocalLightComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.LocalLightComponent.md#oncomponentdeactivated)
- [PhysicsVolume](ue_ue.LocalLightComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.LocalLightComponent.md#physicsvolumechangeddelegate)
- [PrimaryComponentTick](ue_ue.LocalLightComponent.md#primarycomponenttick)
- [Radius](ue_ue.LocalLightComponent.md#radius)
- [RayStartOffsetDepthScale](ue_ue.LocalLightComponent.md#raystartoffsetdepthscale)
- [RelativeLocation](ue_ue.LocalLightComponent.md#relativelocation)
- [RelativeRotation](ue_ue.LocalLightComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.LocalLightComponent.md#relativescale3d)
- [SamplesPerPixel](ue_ue.LocalLightComponent.md#samplesperpixel)
- [ShadowBias](ue_ue.LocalLightComponent.md#shadowbias)
- [ShadowMapChannel](ue_ue.LocalLightComponent.md#shadowmapchannel)
- [ShadowResolutionScale](ue_ue.LocalLightComponent.md#shadowresolutionscale)
- [ShadowSharpen](ue_ue.LocalLightComponent.md#shadowsharpen)
- [ShadowSlopeBias](ue_ue.LocalLightComponent.md#shadowslopebias)
- [SpecularScale](ue_ue.LocalLightComponent.md#specularscale)
- [StaticEditorTexture](ue_ue.LocalLightComponent.md#staticeditortexture)
- [StaticEditorTextureScale](ue_ue.LocalLightComponent.md#staticeditortexturescale)
- [Temperature](ue_ue.LocalLightComponent.md#temperature)
- [UCSModifiedProperties](ue_ue.LocalLightComponent.md#ucsmodifiedproperties)
- [VolumetricScatteringIntensity](ue_ue.LocalLightComponent.md#volumetricscatteringintensity)
- [\_\_tid\_ActorComponent\_\_](ue_ue.LocalLightComponent.md#__tid_actorcomponent__)
- [\_\_tid\_LightComponentBase\_\_](ue_ue.LocalLightComponent.md#__tid_lightcomponentbase__)
- [\_\_tid\_LightComponent\_\_](ue_ue.LocalLightComponent.md#__tid_lightcomponent__)
- [\_\_tid\_LocalLightComponent\_\_](ue_ue.LocalLightComponent.md#__tid_locallightcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.LocalLightComponent.md#__tid_object__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.LocalLightComponent.md#__tid_scenecomponent__)
- [bAbsoluteLocation](ue_ue.LocalLightComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.LocalLightComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.LocalLightComponent.md#babsolutescale)
- [bAffectDynamicIndirectLighting](ue_ue.LocalLightComponent.md#baffectdynamicindirectlighting)
- [bAffectGlobalIllumination](ue_ue.LocalLightComponent.md#baffectglobalillumination)
- [bAffectReflection](ue_ue.LocalLightComponent.md#baffectreflection)
- [bAffectTranslucentLighting](ue_ue.LocalLightComponent.md#baffecttranslucentlighting)
- [bAffectsWorld](ue_ue.LocalLightComponent.md#baffectsworld)
- [bAutoActivate](ue_ue.LocalLightComponent.md#bautoactivate)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.LocalLightComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.LocalLightComponent.md#bcaneveraffectnavigation)
- [bCastDeepShadow](ue_ue.LocalLightComponent.md#bcastdeepshadow)
- [bCastRaytracedShadow](ue_ue.LocalLightComponent.md#bcastraytracedshadow)
- [bCastShadowsFromCinematicObjectsOnly](ue_ue.LocalLightComponent.md#bcastshadowsfromcinematicobjectsonly)
- [bCastVolumetricShadow](ue_ue.LocalLightComponent.md#bcastvolumetricshadow)
- [bComponentToWorldUpdated](ue_ue.LocalLightComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.LocalLightComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.LocalLightComponent.md#beditablewheninherited)
- [bEnableLightShaftBloom](ue_ue.LocalLightComponent.md#benablelightshaftbloom)
- [bForceCachedShadowsForMovablePrimitives](ue_ue.LocalLightComponent.md#bforcecachedshadowsformovableprimitives)
- [bHiddenInGame](ue_ue.LocalLightComponent.md#bhiddeningame)
- [bInstanceComponent](ue_ue.LocalLightComponent.md#binstancecomponent)
- [bIsActive](ue_ue.LocalLightComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.LocalLightComponent.md#biseditoronly)
- [bIsVisualizationComponent](ue_ue.LocalLightComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.LocalLightComponent.md#bnetaddressable)
- [bReplicates](ue_ue.LocalLightComponent.md#breplicates)
- [bShouldBeAttached](ue_ue.LocalLightComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.LocalLightComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.LocalLightComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.LocalLightComponent.md#bshouldupdatephysicsvolume)
- [bTransmission](ue_ue.LocalLightComponent.md#btransmission)
- [bUseAttachParentBound](ue_ue.LocalLightComponent.md#buseattachparentbound)
- [bUseIESBrightness](ue_ue.LocalLightComponent.md#buseiesbrightness)
- [bUseRayTracedDistanceFieldShadows](ue_ue.LocalLightComponent.md#buseraytraceddistancefieldshadows)
- [bUseTemperature](ue_ue.LocalLightComponent.md#busetemperature)
- [bVisible](ue_ue.LocalLightComponent.md#bvisible)
- [bVisualizeComponent](ue_ue.LocalLightComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.LocalLightComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.LocalLightComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.LocalLightComponent.md#addtickprerequisitecomponent)
- [ComponentHasTag](ue_ue.LocalLightComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.LocalLightComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.LocalLightComponent.md#deactivate)
- [DetachFromParent](ue_ue.LocalLightComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.LocalLightComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.LocalLightComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.LocalLightComponent.md#getallsocketnames)
- [GetAttachParent](ue_ue.LocalLightComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.LocalLightComponent.md#getattachsocketname)
- [GetChildComponent](ue_ue.LocalLightComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.LocalLightComponent.md#getchildrencomponents)
- [GetClass](ue_ue.LocalLightComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.LocalLightComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.LocalLightComponent.md#getcomponentvelocity)
- [GetForwardVector](ue_ue.LocalLightComponent.md#getforwardvector)
- [GetLightColor](ue_ue.LocalLightComponent.md#getlightcolor)
- [GetName](ue_ue.LocalLightComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.LocalLightComponent.md#getnumchildrencomponents)
- [GetOuter](ue_ue.LocalLightComponent.md#getouter)
- [GetOwner](ue_ue.LocalLightComponent.md#getowner)
- [GetParentComponents](ue_ue.LocalLightComponent.md#getparentcomponents)
- [GetPhysicsVolume](ue_ue.LocalLightComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.LocalLightComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.LocalLightComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.LocalLightComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.LocalLightComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.LocalLightComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.LocalLightComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.LocalLightComponent.md#getsockettransform)
- [GetUpVector](ue_ue.LocalLightComponent.md#getupvector)
- [GetWorld](ue_ue.LocalLightComponent.md#getworld)
- [IsActive](ue_ue.LocalLightComponent.md#isactive)
- [IsAnySimulatingPhysics](ue_ue.LocalLightComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.LocalLightComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.LocalLightComponent.md#iscomponenttickenabled)
- [IsSimulatingPhysics](ue_ue.LocalLightComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.LocalLightComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.LocalLightComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.LocalLightComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.LocalLightComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.LocalLightComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.LocalLightComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.LocalLightComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.LocalLightComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.LocalLightComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.LocalLightComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.LocalLightComponent.md#k2_attachtocomponent)
- [K2\_DestroyComponent](ue_ue.LocalLightComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.LocalLightComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.LocalLightComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.LocalLightComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.LocalLightComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.LocalLightComponent.md#k2_getcomponenttoworld)
- [K2\_SetRelativeLocation](ue_ue.LocalLightComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.LocalLightComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.LocalLightComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.LocalLightComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.LocalLightComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.LocalLightComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.LocalLightComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.LocalLightComponent.md#k2_setworldtransform)
- [OnRep\_AttachChildren](ue_ue.LocalLightComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.LocalLightComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.LocalLightComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.LocalLightComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.LocalLightComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.LocalLightComponent.md#onrep_visibility)
- [ReceiveBeginPlay](ue_ue.LocalLightComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.LocalLightComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.LocalLightComponent.md#receivetick)
- [RegisterComponent](ue_ue.LocalLightComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.LocalLightComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.LocalLightComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.LocalLightComponent.md#resetrelativetransform)
- [SetAbsolute](ue_ue.LocalLightComponent.md#setabsolute)
- [SetActive](ue_ue.LocalLightComponent.md#setactive)
- [SetAffectDynamicIndirectLighting](ue_ue.LocalLightComponent.md#setaffectdynamicindirectlighting)
- [SetAffectGlobalIllumination](ue_ue.LocalLightComponent.md#setaffectglobalillumination)
- [SetAffectReflection](ue_ue.LocalLightComponent.md#setaffectreflection)
- [SetAffectTranslucentLighting](ue_ue.LocalLightComponent.md#setaffecttranslucentlighting)
- [SetAttenuationRadius](ue_ue.LocalLightComponent.md#setattenuationradius)
- [SetAutoActivate](ue_ue.LocalLightComponent.md#setautoactivate)
- [SetBloomMaxBrightness](ue_ue.LocalLightComponent.md#setbloommaxbrightness)
- [SetBloomScale](ue_ue.LocalLightComponent.md#setbloomscale)
- [SetBloomThreshold](ue_ue.LocalLightComponent.md#setbloomthreshold)
- [SetBloomTint](ue_ue.LocalLightComponent.md#setbloomtint)
- [SetCastDeepShadow](ue_ue.LocalLightComponent.md#setcastdeepshadow)
- [SetCastRaytracedShadow](ue_ue.LocalLightComponent.md#setcastraytracedshadow)
- [SetCastShadows](ue_ue.LocalLightComponent.md#setcastshadows)
- [SetCastVolumetricShadow](ue_ue.LocalLightComponent.md#setcastvolumetricshadow)
- [SetComponentTickEnabled](ue_ue.LocalLightComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.LocalLightComponent.md#setcomponenttickinterval)
- [SetEnableLightShaftBloom](ue_ue.LocalLightComponent.md#setenablelightshaftbloom)
- [SetForceCachedShadowsForMovablePrimitives](ue_ue.LocalLightComponent.md#setforcecachedshadowsformovableprimitives)
- [SetHiddenInGame](ue_ue.LocalLightComponent.md#sethiddeningame)
- [SetIESBrightnessScale](ue_ue.LocalLightComponent.md#setiesbrightnessscale)
- [SetIESTexture](ue_ue.LocalLightComponent.md#setiestexture)
- [SetIndirectLightingIntensity](ue_ue.LocalLightComponent.md#setindirectlightingintensity)
- [SetIntensity](ue_ue.LocalLightComponent.md#setintensity)
- [SetIntensityUnits](ue_ue.LocalLightComponent.md#setintensityunits)
- [SetIsReplicated](ue_ue.LocalLightComponent.md#setisreplicated)
- [SetLightColor](ue_ue.LocalLightComponent.md#setlightcolor)
- [SetLightFunctionDisabledBrightness](ue_ue.LocalLightComponent.md#setlightfunctiondisabledbrightness)
- [SetLightFunctionFadeDistance](ue_ue.LocalLightComponent.md#setlightfunctionfadedistance)
- [SetLightFunctionMaterial](ue_ue.LocalLightComponent.md#setlightfunctionmaterial)
- [SetLightFunctionScale](ue_ue.LocalLightComponent.md#setlightfunctionscale)
- [SetMobility](ue_ue.LocalLightComponent.md#setmobility)
- [SetRelativeScale3D](ue_ue.LocalLightComponent.md#setrelativescale3d)
- [SetSamplesPerPixel](ue_ue.LocalLightComponent.md#setsamplesperpixel)
- [SetShadowBias](ue_ue.LocalLightComponent.md#setshadowbias)
- [SetShadowSlopeBias](ue_ue.LocalLightComponent.md#setshadowslopebias)
- [SetShouldUpdatePhysicsVolume](ue_ue.LocalLightComponent.md#setshouldupdatephysicsvolume)
- [SetSpecularScale](ue_ue.LocalLightComponent.md#setspecularscale)
- [SetTemperature](ue_ue.LocalLightComponent.md#settemperature)
- [SetTickGroup](ue_ue.LocalLightComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.LocalLightComponent.md#settickablewhenpaused)
- [SetTransmission](ue_ue.LocalLightComponent.md#settransmission)
- [SetUseIESBrightness](ue_ue.LocalLightComponent.md#setuseiesbrightness)
- [SetVisibility](ue_ue.LocalLightComponent.md#setvisibility)
- [SetVolumetricScatteringIntensity](ue_ue.LocalLightComponent.md#setvolumetricscatteringintensity)
- [SetWorldScale3D](ue_ue.LocalLightComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.LocalLightComponent.md#setupattachment)
- [SnapTo](ue_ue.LocalLightComponent.md#snapto)
- [ToggleActive](ue_ue.LocalLightComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.LocalLightComponent.md#togglevisibility)
- [Find](ue_ue.LocalLightComponent.md#find)
- [GetUnitsConversionFactor](ue_ue.LocalLightComponent.md#getunitsconversionfactor)
- [Load](ue_ue.LocalLightComponent.md#load)
- [StaticClass](ue_ue.LocalLightComponent.md#staticclass)

## Constructors

### constructor

• **new LocalLightComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

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

### AttenuationRadius

• **AttenuationRadius**: `number`

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

### IntensityUnits

• **IntensityUnits**: [`ELightUnits`](../enums/ue_ue.ELightUnits.md)

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

### LightingChannels

• **LightingChannels**: [`LightingChannels`](ue_ue.LightingChannels.md)

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[LightingChannels](ue_ue.LightComponent.md#lightingchannels)

___

### LightmassSettings

• **LightmassSettings**: [`LightmassPointLightSettings`](ue_ue.LightmassPointLightSettings.md)

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

### Radius

• **Radius**: `number`

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

### ShadowBias

• **ShadowBias**: `number`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[ShadowBias](ue_ue.LightComponent.md#shadowbias)

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

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[LightComponent](ue_ue.LightComponent.md).[__tid_ActorComponent__](ue_ue.LightComponent.md#__tid_actorcomponent__)

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

### \_\_tid\_LocalLightComponent\_\_

• **\_\_tid\_LocalLightComponent\_\_**: `boolean`

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

### SetAttenuationRadius

▸ **SetAttenuationRadius**(`NewRadius`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewRadius` | `number` |

#### Returns

`void`

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

### SetIntensityUnits

▸ **SetIntensityUnits**(`NewIntensityUnits`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewIntensityUnits` | [`ELightUnits`](../enums/ue_ue.ELightUnits.md) |

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

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`LocalLightComponent`](ue_ue.LocalLightComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`LocalLightComponent`](ue_ue.LocalLightComponent.md)

#### Overrides

[LightComponent](ue_ue.LightComponent.md).[Find](ue_ue.LightComponent.md#find)

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

___

### Load

▸ `Static` **Load**(`InName`): [`LocalLightComponent`](ue_ue.LocalLightComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`LocalLightComponent`](ue_ue.LocalLightComponent.md)

#### Overrides

[LightComponent](ue_ue.LightComponent.md).[Load](ue_ue.LightComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[LightComponent](ue_ue.LightComponent.md).[StaticClass](ue_ue.LightComponent.md#staticclass)
