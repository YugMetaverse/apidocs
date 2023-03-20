[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / AudioComponent

# Class: AudioComponent

[ue/ue](../modules/ue_ue.md).AudioComponent

## Hierarchy

- [`SceneComponent`](ue_ue.SceneComponent.md)

  ↳ **`AudioComponent`**

  ↳↳ [`AudioCurveSourceComponent`](ue_ue.AudioCurveSourceComponent.md)

## Table of contents

### Constructors

- [constructor](ue_ue.AudioComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.AudioComponent.md#assetuserdata)
- [AttachChildren](ue_ue.AudioComponent.md#attachchildren)
- [AttachParent](ue_ue.AudioComponent.md#attachparent)
- [AttachSocketName](ue_ue.AudioComponent.md#attachsocketname)
- [AttenuationOverrides](ue_ue.AudioComponent.md#attenuationoverrides)
- [AttenuationSettings](ue_ue.AudioComponent.md#attenuationsettings)
- [AudioComponentUserID](ue_ue.AudioComponent.md#audiocomponentuserid)
- [AutoAttachLocationRule](ue_ue.AudioComponent.md#autoattachlocationrule)
- [AutoAttachParent](ue_ue.AudioComponent.md#autoattachparent)
- [AutoAttachRotationRule](ue_ue.AudioComponent.md#autoattachrotationrule)
- [AutoAttachScaleRule](ue_ue.AudioComponent.md#autoattachscalerule)
- [AutoAttachSocketName](ue_ue.AudioComponent.md#autoattachsocketname)
- [ClientAttachedChildren](ue_ue.AudioComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.AudioComponent.md#componenttags)
- [ComponentVelocity](ue_ue.AudioComponent.md#componentvelocity)
- [ConcurrencySet](ue_ue.AudioComponent.md#concurrencyset)
- [ConcurrencySettings](ue_ue.AudioComponent.md#concurrencysettings)
- [CreationMethod](ue_ue.AudioComponent.md#creationmethod)
- [DetailMode](ue_ue.AudioComponent.md#detailmode)
- [EnvelopeFollowerAttackTime](ue_ue.AudioComponent.md#envelopefollowerattacktime)
- [EnvelopeFollowerReleaseTime](ue_ue.AudioComponent.md#envelopefollowerreleasetime)
- [HighFrequencyGainMultiplier](ue_ue.AudioComponent.md#highfrequencygainmultiplier)
- [InstanceParameters](ue_ue.AudioComponent.md#instanceparameters)
- [LowPassFilterFrequency](ue_ue.AudioComponent.md#lowpassfilterfrequency)
- [Mobility](ue_ue.AudioComponent.md#mobility)
- [Modulation](ue_ue.AudioComponent.md#modulation)
- [OnAudioFinished](ue_ue.AudioComponent.md#onaudiofinished)
- [OnAudioMultiEnvelopeValue](ue_ue.AudioComponent.md#onaudiomultienvelopevalue)
- [OnAudioPlaybackPercent](ue_ue.AudioComponent.md#onaudioplaybackpercent)
- [OnAudioSingleEnvelopeValue](ue_ue.AudioComponent.md#onaudiosingleenvelopevalue)
- [OnComponentActivated](ue_ue.AudioComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.AudioComponent.md#oncomponentdeactivated)
- [OnQueueSubtitles](ue_ue.AudioComponent.md#onqueuesubtitles)
- [PhysicsVolume](ue_ue.AudioComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.AudioComponent.md#physicsvolumechangeddelegate)
- [PitchModulationMax](ue_ue.AudioComponent.md#pitchmodulationmax)
- [PitchModulationMin](ue_ue.AudioComponent.md#pitchmodulationmin)
- [PitchMultiplier](ue_ue.AudioComponent.md#pitchmultiplier)
- [PrimaryComponentTick](ue_ue.AudioComponent.md#primarycomponenttick)
- [Priority](ue_ue.AudioComponent.md#priority)
- [RelativeLocation](ue_ue.AudioComponent.md#relativelocation)
- [RelativeRotation](ue_ue.AudioComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.AudioComponent.md#relativescale3d)
- [Sound](ue_ue.AudioComponent.md#sound)
- [SoundClassOverride](ue_ue.AudioComponent.md#soundclassoverride)
- [SourceEffectChain](ue_ue.AudioComponent.md#sourceeffectchain)
- [SubtitlePriority](ue_ue.AudioComponent.md#subtitlepriority)
- [UCSModifiedProperties](ue_ue.AudioComponent.md#ucsmodifiedproperties)
- [VolumeModulationMax](ue_ue.AudioComponent.md#volumemodulationmax)
- [VolumeModulationMin](ue_ue.AudioComponent.md#volumemodulationmin)
- [VolumeMultiplier](ue_ue.AudioComponent.md#volumemultiplier)
- [VolumeWeightedPriorityScale](ue_ue.AudioComponent.md#volumeweightedpriorityscale)
- [\_\_tid\_ActorComponent\_\_](ue_ue.AudioComponent.md#__tid_actorcomponent__)
- [\_\_tid\_AudioComponent\_\_](ue_ue.AudioComponent.md#__tid_audiocomponent__)
- [\_\_tid\_Object\_\_](ue_ue.AudioComponent.md#__tid_object__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.AudioComponent.md#__tid_scenecomponent__)
- [bAbsoluteLocation](ue_ue.AudioComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.AudioComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.AudioComponent.md#babsolutescale)
- [bAllowSpatialization](ue_ue.AudioComponent.md#ballowspatialization)
- [bAutoActivate](ue_ue.AudioComponent.md#bautoactivate)
- [bAutoDestroy](ue_ue.AudioComponent.md#bautodestroy)
- [bAutoManageAttachment](ue_ue.AudioComponent.md#bautomanageattachment)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.AudioComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.AudioComponent.md#bcaneveraffectnavigation)
- [bComponentToWorldUpdated](ue_ue.AudioComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.AudioComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.AudioComponent.md#beditablewheninherited)
- [bEnableLowPassFilter](ue_ue.AudioComponent.md#benablelowpassfilter)
- [bHiddenInGame](ue_ue.AudioComponent.md#bhiddeningame)
- [bInstanceComponent](ue_ue.AudioComponent.md#binstancecomponent)
- [bIsActive](ue_ue.AudioComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.AudioComponent.md#biseditoronly)
- [bIsUISound](ue_ue.AudioComponent.md#bisuisound)
- [bIsVisualizationComponent](ue_ue.AudioComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.AudioComponent.md#bnetaddressable)
- [bOverrideAttenuation](ue_ue.AudioComponent.md#boverrideattenuation)
- [bOverridePriority](ue_ue.AudioComponent.md#boverridepriority)
- [bOverrideSubtitlePriority](ue_ue.AudioComponent.md#boverridesubtitlepriority)
- [bReplicates](ue_ue.AudioComponent.md#breplicates)
- [bShouldBeAttached](ue_ue.AudioComponent.md#bshouldbeattached)
- [bShouldRemainActiveIfDropped](ue_ue.AudioComponent.md#bshouldremainactiveifdropped)
- [bShouldSnapLocationWhenAttached](ue_ue.AudioComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.AudioComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.AudioComponent.md#bshouldupdatephysicsvolume)
- [bStopWhenOwnerDestroyed](ue_ue.AudioComponent.md#bstopwhenownerdestroyed)
- [bSuppressSubtitles](ue_ue.AudioComponent.md#bsuppresssubtitles)
- [bUseAttachParentBound](ue_ue.AudioComponent.md#buseattachparentbound)
- [bVisible](ue_ue.AudioComponent.md#bvisible)
- [bVisualizeComponent](ue_ue.AudioComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.AudioComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.AudioComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.AudioComponent.md#addtickprerequisitecomponent)
- [AdjustAttenuation](ue_ue.AudioComponent.md#adjustattenuation)
- [AdjustVolume](ue_ue.AudioComponent.md#adjustvolume)
- [BP\_GetAttenuationSettingsToApply](ue_ue.AudioComponent.md#bp_getattenuationsettingstoapply)
- [ComponentHasTag](ue_ue.AudioComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.AudioComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.AudioComponent.md#deactivate)
- [DetachFromParent](ue_ue.AudioComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.AudioComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.AudioComponent.md#executeubergraph)
- [FadeIn](ue_ue.AudioComponent.md#fadein)
- [FadeOut](ue_ue.AudioComponent.md#fadeout)
- [GetAllSocketNames](ue_ue.AudioComponent.md#getallsocketnames)
- [GetAttachParent](ue_ue.AudioComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.AudioComponent.md#getattachsocketname)
- [GetChildComponent](ue_ue.AudioComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.AudioComponent.md#getchildrencomponents)
- [GetClass](ue_ue.AudioComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.AudioComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.AudioComponent.md#getcomponentvelocity)
- [GetCookedEnvelopeData](ue_ue.AudioComponent.md#getcookedenvelopedata)
- [GetCookedEnvelopeDataForAllPlayingSounds](ue_ue.AudioComponent.md#getcookedenvelopedataforallplayingsounds)
- [GetCookedFFTData](ue_ue.AudioComponent.md#getcookedfftdata)
- [GetCookedFFTDataForAllPlayingSounds](ue_ue.AudioComponent.md#getcookedfftdataforallplayingsounds)
- [GetForwardVector](ue_ue.AudioComponent.md#getforwardvector)
- [GetName](ue_ue.AudioComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.AudioComponent.md#getnumchildrencomponents)
- [GetOuter](ue_ue.AudioComponent.md#getouter)
- [GetOwner](ue_ue.AudioComponent.md#getowner)
- [GetParentComponents](ue_ue.AudioComponent.md#getparentcomponents)
- [GetPhysicsVolume](ue_ue.AudioComponent.md#getphysicsvolume)
- [GetPlayState](ue_ue.AudioComponent.md#getplaystate)
- [GetRelativeTransform](ue_ue.AudioComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.AudioComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.AudioComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.AudioComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.AudioComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.AudioComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.AudioComponent.md#getsockettransform)
- [GetUpVector](ue_ue.AudioComponent.md#getupvector)
- [GetWorld](ue_ue.AudioComponent.md#getworld)
- [HasCookedAmplitudeEnvelopeData](ue_ue.AudioComponent.md#hascookedamplitudeenvelopedata)
- [HasCookedFFTData](ue_ue.AudioComponent.md#hascookedfftdata)
- [IsActive](ue_ue.AudioComponent.md#isactive)
- [IsAnySimulatingPhysics](ue_ue.AudioComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.AudioComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.AudioComponent.md#iscomponenttickenabled)
- [IsPlaying](ue_ue.AudioComponent.md#isplaying)
- [IsSimulatingPhysics](ue_ue.AudioComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.AudioComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.AudioComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.AudioComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.AudioComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.AudioComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.AudioComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.AudioComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.AudioComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.AudioComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.AudioComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.AudioComponent.md#k2_attachtocomponent)
- [K2\_DestroyComponent](ue_ue.AudioComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.AudioComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.AudioComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.AudioComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.AudioComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.AudioComponent.md#k2_getcomponenttoworld)
- [K2\_SetRelativeLocation](ue_ue.AudioComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.AudioComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.AudioComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.AudioComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.AudioComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.AudioComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.AudioComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.AudioComponent.md#k2_setworldtransform)
- [OnRep\_AttachChildren](ue_ue.AudioComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.AudioComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.AudioComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.AudioComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.AudioComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.AudioComponent.md#onrep_visibility)
- [Play](ue_ue.AudioComponent.md#play)
- [ReceiveBeginPlay](ue_ue.AudioComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.AudioComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.AudioComponent.md#receivetick)
- [RegisterComponent](ue_ue.AudioComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.AudioComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.AudioComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.AudioComponent.md#resetrelativetransform)
- [SetAbsolute](ue_ue.AudioComponent.md#setabsolute)
- [SetActive](ue_ue.AudioComponent.md#setactive)
- [SetAutoActivate](ue_ue.AudioComponent.md#setautoactivate)
- [SetBoolParameter](ue_ue.AudioComponent.md#setboolparameter)
- [SetComponentTickEnabled](ue_ue.AudioComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.AudioComponent.md#setcomponenttickinterval)
- [SetFloatParameter](ue_ue.AudioComponent.md#setfloatparameter)
- [SetHiddenInGame](ue_ue.AudioComponent.md#sethiddeningame)
- [SetIntParameter](ue_ue.AudioComponent.md#setintparameter)
- [SetIsReplicated](ue_ue.AudioComponent.md#setisreplicated)
- [SetLowPassFilterEnabled](ue_ue.AudioComponent.md#setlowpassfilterenabled)
- [SetLowPassFilterFrequency](ue_ue.AudioComponent.md#setlowpassfilterfrequency)
- [SetMobility](ue_ue.AudioComponent.md#setmobility)
- [SetPaused](ue_ue.AudioComponent.md#setpaused)
- [SetPitchMultiplier](ue_ue.AudioComponent.md#setpitchmultiplier)
- [SetRelativeScale3D](ue_ue.AudioComponent.md#setrelativescale3d)
- [SetShouldUpdatePhysicsVolume](ue_ue.AudioComponent.md#setshouldupdatephysicsvolume)
- [SetSound](ue_ue.AudioComponent.md#setsound)
- [SetSourceBusSendPostEffect](ue_ue.AudioComponent.md#setsourcebussendposteffect)
- [SetSourceBusSendPreEffect](ue_ue.AudioComponent.md#setsourcebussendpreeffect)
- [SetSubmixSend](ue_ue.AudioComponent.md#setsubmixsend)
- [SetTickGroup](ue_ue.AudioComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.AudioComponent.md#settickablewhenpaused)
- [SetUISound](ue_ue.AudioComponent.md#setuisound)
- [SetVisibility](ue_ue.AudioComponent.md#setvisibility)
- [SetVolumeMultiplier](ue_ue.AudioComponent.md#setvolumemultiplier)
- [SetWaveParameter](ue_ue.AudioComponent.md#setwaveparameter)
- [SetWorldScale3D](ue_ue.AudioComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.AudioComponent.md#setupattachment)
- [SnapTo](ue_ue.AudioComponent.md#snapto)
- [Stop](ue_ue.AudioComponent.md#stop)
- [StopDelayed](ue_ue.AudioComponent.md#stopdelayed)
- [ToggleActive](ue_ue.AudioComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.AudioComponent.md#togglevisibility)
- [Find](ue_ue.AudioComponent.md#find)
- [Load](ue_ue.AudioComponent.md#load)
- [StaticClass](ue_ue.AudioComponent.md#staticclass)

## Constructors

### constructor

• **new AudioComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SceneComponent](ue_ue.SceneComponent.md).[constructor](ue_ue.SceneComponent.md#constructor)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[AssetUserData](ue_ue.SceneComponent.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[AttachChildren](ue_ue.SceneComponent.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[AttachParent](ue_ue.SceneComponent.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[AttachSocketName](ue_ue.SceneComponent.md#attachsocketname)

___

### AttenuationOverrides

• **AttenuationOverrides**: [`SoundAttenuationSettings`](ue_ue.SoundAttenuationSettings.md)

___

### AttenuationSettings

• **AttenuationSettings**: [`SoundAttenuation`](ue_ue.SoundAttenuation.md)

___

### AudioComponentUserID

• **AudioComponentUserID**: `string`

___

### AutoAttachLocationRule

• **AutoAttachLocationRule**: [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md)

___

### AutoAttachParent

• **AutoAttachParent**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

___

### AutoAttachRotationRule

• **AutoAttachRotationRule**: [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md)

___

### AutoAttachScaleRule

• **AutoAttachScaleRule**: [`EAttachmentRule`](../enums/ue_ue.EAttachmentRule.md)

___

### AutoAttachSocketName

• **AutoAttachSocketName**: `string`

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[ClientAttachedChildren](ue_ue.SceneComponent.md#clientattachedchildren)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[ComponentTags](ue_ue.SceneComponent.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[ComponentVelocity](ue_ue.SceneComponent.md#componentvelocity)

___

### ConcurrencySet

• **ConcurrencySet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`SoundConcurrency`](ue_ue.SoundConcurrency.md)\>

___

### ConcurrencySettings

• **ConcurrencySettings**: [`SoundConcurrency`](ue_ue.SoundConcurrency.md)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[CreationMethod](ue_ue.SceneComponent.md#creationmethod)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[DetailMode](ue_ue.SceneComponent.md#detailmode)

___

### EnvelopeFollowerAttackTime

• **EnvelopeFollowerAttackTime**: `number`

___

### EnvelopeFollowerReleaseTime

• **EnvelopeFollowerReleaseTime**: `number`

___

### HighFrequencyGainMultiplier

• **HighFrequencyGainMultiplier**: `number`

___

### InstanceParameters

• **InstanceParameters**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AudioComponentParam`](ue_ue.AudioComponentParam.md)\>

___

### LowPassFilterFrequency

• **LowPassFilterFrequency**: `number`

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[Mobility](ue_ue.SceneComponent.md#mobility)

___

### Modulation

• **Modulation**: [`SoundModulation`](ue_ue.SoundModulation.md)

___

### OnAudioFinished

• **OnAudioFinished**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<() => `void`\>

___

### OnAudioMultiEnvelopeValue

• **OnAudioMultiEnvelopeValue**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`AverageEnvelopeValue`: `number`, `MaxEnvelope`: `number`, `NumWaveInstances`: `number`) => `void`\>

___

### OnAudioPlaybackPercent

• **OnAudioPlaybackPercent**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`PlayingSoundWave`: [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundWave`](ue_ue.SoundWave.md)\>, `PlaybackPercent`: `number`) => `void`\>

___

### OnAudioSingleEnvelopeValue

• **OnAudioSingleEnvelopeValue**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`PlayingSoundWave`: [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundWave`](ue_ue.SoundWave.md)\>, `EnvelopeValue`: `number`) => `void`\>

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[OnComponentActivated](ue_ue.SceneComponent.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[OnComponentDeactivated](ue_ue.SceneComponent.md#oncomponentdeactivated)

___

### OnQueueSubtitles

• **OnQueueSubtitles**: [`$Delegate`](../interfaces/ue_puerts._Delegate.md)<(`Subtitles`: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SubtitleCue`](ue_ue.SubtitleCue.md)\>, `CueDuration`: `number`) => `void`\>

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[PhysicsVolume](ue_ue.SceneComponent.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.SceneComponent.md#physicsvolumechangeddelegate)

___

### PitchModulationMax

• **PitchModulationMax**: `number`

___

### PitchModulationMin

• **PitchModulationMin**: `number`

___

### PitchMultiplier

• **PitchMultiplier**: `number`

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[PrimaryComponentTick](ue_ue.SceneComponent.md#primarycomponenttick)

___

### Priority

• **Priority**: `number`

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[RelativeLocation](ue_ue.SceneComponent.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[RelativeRotation](ue_ue.SceneComponent.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[RelativeScale3D](ue_ue.SceneComponent.md#relativescale3d)

___

### Sound

• **Sound**: [`SoundBase`](ue_ue.SoundBase.md)

___

### SoundClassOverride

• **SoundClassOverride**: [`SoundClass`](ue_ue.SoundClass.md)

___

### SourceEffectChain

• **SourceEffectChain**: [`SoundEffectSourcePresetChain`](ue_ue.SoundEffectSourcePresetChain.md)

___

### SubtitlePriority

• **SubtitlePriority**: `number`

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[UCSModifiedProperties](ue_ue.SceneComponent.md#ucsmodifiedproperties)

___

### VolumeModulationMax

• **VolumeModulationMax**: `number`

___

### VolumeModulationMin

• **VolumeModulationMin**: `number`

___

### VolumeMultiplier

• **VolumeMultiplier**: `number`

___

### VolumeWeightedPriorityScale

• **VolumeWeightedPriorityScale**: `number`

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[__tid_ActorComponent__](ue_ue.SceneComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_AudioComponent\_\_

• **\_\_tid\_AudioComponent\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[__tid_Object__](ue_ue.SceneComponent.md#__tid_object__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[__tid_SceneComponent__](ue_ue.SceneComponent.md#__tid_scenecomponent__)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bAbsoluteLocation](ue_ue.SceneComponent.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bAbsoluteRotation](ue_ue.SceneComponent.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bAbsoluteScale](ue_ue.SceneComponent.md#babsolutescale)

___

### bAllowSpatialization

• **bAllowSpatialization**: `boolean`

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bAutoActivate](ue_ue.SceneComponent.md#bautoactivate)

___

### bAutoDestroy

• **bAutoDestroy**: `boolean`

___

### bAutoManageAttachment

• **bAutoManageAttachment**: `boolean`

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.SceneComponent.md#bboundschangetriggersstreamingdatarebuild)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bCanEverAffectNavigation](ue_ue.SceneComponent.md#bcaneveraffectnavigation)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bComponentToWorldUpdated](ue_ue.SceneComponent.md#bcomponenttoworldupdated)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bCreatedByConstructionScript](ue_ue.SceneComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bEditableWhenInherited](ue_ue.SceneComponent.md#beditablewheninherited)

___

### bEnableLowPassFilter

• **bEnableLowPassFilter**: `boolean`

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bHiddenInGame](ue_ue.SceneComponent.md#bhiddeningame)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bInstanceComponent](ue_ue.SceneComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bIsActive](ue_ue.SceneComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bIsEditorOnly](ue_ue.SceneComponent.md#biseditoronly)

___

### bIsUISound

• **bIsUISound**: `boolean`

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bIsVisualizationComponent](ue_ue.SceneComponent.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bNetAddressable](ue_ue.SceneComponent.md#bnetaddressable)

___

### bOverrideAttenuation

• **bOverrideAttenuation**: `boolean`

___

### bOverridePriority

• **bOverridePriority**: `boolean`

___

### bOverrideSubtitlePriority

• **bOverrideSubtitlePriority**: `boolean`

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bReplicates](ue_ue.SceneComponent.md#breplicates)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bShouldBeAttached](ue_ue.SceneComponent.md#bshouldbeattached)

___

### bShouldRemainActiveIfDropped

• **bShouldRemainActiveIfDropped**: `boolean`

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.SceneComponent.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.SceneComponent.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.SceneComponent.md#bshouldupdatephysicsvolume)

___

### bStopWhenOwnerDestroyed

• **bStopWhenOwnerDestroyed**: `boolean`

___

### bSuppressSubtitles

• **bSuppressSubtitles**: `boolean`

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bUseAttachParentBound](ue_ue.SceneComponent.md#buseattachparentbound)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bVisible](ue_ue.SceneComponent.md#bvisible)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[bVisualizeComponent](ue_ue.SceneComponent.md#bvisualizecomponent)

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

[SceneComponent](ue_ue.SceneComponent.md).[Activate](ue_ue.SceneComponent.md#activate)

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

[SceneComponent](ue_ue.SceneComponent.md).[AddTickPrerequisiteActor](ue_ue.SceneComponent.md#addtickprerequisiteactor)

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

[SceneComponent](ue_ue.SceneComponent.md).[AddTickPrerequisiteComponent](ue_ue.SceneComponent.md#addtickprerequisitecomponent)

___

### AdjustAttenuation

▸ **AdjustAttenuation**(`InAttenuationSettings`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InAttenuationSettings` | [`SoundAttenuationSettings`](ue_ue.SoundAttenuationSettings.md) |

#### Returns

`void`

___

### AdjustVolume

▸ **AdjustVolume**(`AdjustVolumeDuration`, `AdjustVolumeLevel`, `FadeCurve?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AdjustVolumeDuration` | `number` |
| `AdjustVolumeLevel` | `number` |
| `FadeCurve?` | [`EAudioFaderCurve`](../enums/ue_ue.EAudioFaderCurve.md) |

#### Returns

`void`

___

### BP\_GetAttenuationSettingsToApply

▸ **BP_GetAttenuationSettingsToApply**(`OutAttenuationSettings`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutAttenuationSettings` | [`$Ref`](../interfaces/puerts._Ref.md)<[`SoundAttenuationSettings`](ue_ue.SoundAttenuationSettings.md)\> |

#### Returns

`boolean`

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

[SceneComponent](ue_ue.SceneComponent.md).[ComponentHasTag](ue_ue.SceneComponent.md#componenthastag)

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

[SceneComponent](ue_ue.SceneComponent.md).[CreateDefaultSubobject](ue_ue.SceneComponent.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[Deactivate](ue_ue.SceneComponent.md#deactivate)

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

[SceneComponent](ue_ue.SceneComponent.md).[DetachFromParent](ue_ue.SceneComponent.md#detachfromparent)

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

[SceneComponent](ue_ue.SceneComponent.md).[DoesSocketExist](ue_ue.SceneComponent.md#doessocketexist)

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

[SceneComponent](ue_ue.SceneComponent.md).[ExecuteUbergraph](ue_ue.SceneComponent.md#executeubergraph)

___

### FadeIn

▸ **FadeIn**(`FadeInDuration`, `FadeVolumeLevel?`, `StartTime?`, `FadeCurve?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FadeInDuration` | `number` |
| `FadeVolumeLevel?` | `number` |
| `StartTime?` | `number` |
| `FadeCurve?` | [`EAudioFaderCurve`](../enums/ue_ue.EAudioFaderCurve.md) |

#### Returns

`void`

___

### FadeOut

▸ **FadeOut**(`FadeOutDuration`, `FadeVolumeLevel`, `FadeCurve?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FadeOutDuration` | `number` |
| `FadeVolumeLevel` | `number` |
| `FadeCurve?` | [`EAudioFaderCurve`](../enums/ue_ue.EAudioFaderCurve.md) |

#### Returns

`void`

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[GetAllSocketNames](ue_ue.SceneComponent.md#getallsocketnames)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[GetAttachParent](ue_ue.SceneComponent.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[GetAttachSocketName](ue_ue.SceneComponent.md#getattachsocketname)

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

[SceneComponent](ue_ue.SceneComponent.md).[GetChildComponent](ue_ue.SceneComponent.md#getchildcomponent)

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

[SceneComponent](ue_ue.SceneComponent.md).[GetChildrenComponents](ue_ue.SceneComponent.md#getchildrencomponents)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[GetClass](ue_ue.SceneComponent.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[GetComponentTickInterval](ue_ue.SceneComponent.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[GetComponentVelocity](ue_ue.SceneComponent.md#getcomponentvelocity)

___

### GetCookedEnvelopeData

▸ **GetCookedEnvelopeData**(`OutEnvelopeData`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutEnvelopeData` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`boolean`

___

### GetCookedEnvelopeDataForAllPlayingSounds

▸ **GetCookedEnvelopeDataForAllPlayingSounds**(`OutEnvelopeData`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutEnvelopeData` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundWaveEnvelopeDataPerSound`](ue_ue.SoundWaveEnvelopeDataPerSound.md)\>\> |

#### Returns

`boolean`

___

### GetCookedFFTData

▸ **GetCookedFFTData**(`FrequenciesToGet`, `OutSoundWaveSpectralData`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `FrequenciesToGet` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `OutSoundWaveSpectralData` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundWaveSpectralData`](ue_ue.SoundWaveSpectralData.md)\>\> |

#### Returns

`boolean`

___

### GetCookedFFTDataForAllPlayingSounds

▸ **GetCookedFFTDataForAllPlayingSounds**(`OutSoundWaveSpectralData`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OutSoundWaveSpectralData` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundWaveSpectralDataPerSound`](ue_ue.SoundWaveSpectralDataPerSound.md)\>\> |

#### Returns

`boolean`

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[GetForwardVector](ue_ue.SceneComponent.md#getforwardvector)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[GetName](ue_ue.SceneComponent.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[GetNumChildrenComponents](ue_ue.SceneComponent.md#getnumchildrencomponents)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[GetOuter](ue_ue.SceneComponent.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[GetOwner](ue_ue.SceneComponent.md#getowner)

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

[SceneComponent](ue_ue.SceneComponent.md).[GetParentComponents](ue_ue.SceneComponent.md#getparentcomponents)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[GetPhysicsVolume](ue_ue.SceneComponent.md#getphysicsvolume)

___

### GetPlayState

▸ **GetPlayState**(): [`EAudioComponentPlayState`](../enums/ue_ue.EAudioComponentPlayState.md)

#### Returns

[`EAudioComponentPlayState`](../enums/ue_ue.EAudioComponentPlayState.md)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[GetRelativeTransform](ue_ue.SceneComponent.md#getrelativetransform)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[GetRightVector](ue_ue.SceneComponent.md#getrightvector)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.SceneComponent.md#getshouldupdatephysicsvolume)

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

[SceneComponent](ue_ue.SceneComponent.md).[GetSocketLocation](ue_ue.SceneComponent.md#getsocketlocation)

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

[SceneComponent](ue_ue.SceneComponent.md).[GetSocketQuaternion](ue_ue.SceneComponent.md#getsocketquaternion)

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

[SceneComponent](ue_ue.SceneComponent.md).[GetSocketRotation](ue_ue.SceneComponent.md#getsocketrotation)

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

[SceneComponent](ue_ue.SceneComponent.md).[GetSocketTransform](ue_ue.SceneComponent.md#getsockettransform)

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[GetUpVector](ue_ue.SceneComponent.md#getupvector)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[GetWorld](ue_ue.SceneComponent.md#getworld)

___

### HasCookedAmplitudeEnvelopeData

▸ **HasCookedAmplitudeEnvelopeData**(): `boolean`

#### Returns

`boolean`

___

### HasCookedFFTData

▸ **HasCookedFFTData**(): `boolean`

#### Returns

`boolean`

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[IsActive](ue_ue.SceneComponent.md#isactive)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[IsAnySimulatingPhysics](ue_ue.SceneComponent.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[IsBeingDestroyed](ue_ue.SceneComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[IsComponentTickEnabled](ue_ue.SceneComponent.md#iscomponenttickenabled)

___

### IsPlaying

▸ **IsPlaying**(): `boolean`

#### Returns

`boolean`

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

[SceneComponent](ue_ue.SceneComponent.md).[IsSimulatingPhysics](ue_ue.SceneComponent.md#issimulatingphysics)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[IsVisible](ue_ue.SceneComponent.md#isvisible)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_AddLocalOffset](ue_ue.SceneComponent.md#k2_addlocaloffset)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_AddLocalRotation](ue_ue.SceneComponent.md#k2_addlocalrotation)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_AddLocalTransform](ue_ue.SceneComponent.md#k2_addlocaltransform)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_AddRelativeLocation](ue_ue.SceneComponent.md#k2_addrelativelocation)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_AddRelativeRotation](ue_ue.SceneComponent.md#k2_addrelativerotation)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_AddWorldOffset](ue_ue.SceneComponent.md#k2_addworldoffset)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_AddWorldRotation](ue_ue.SceneComponent.md#k2_addworldrotation)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_AddWorldTransform](ue_ue.SceneComponent.md#k2_addworldtransform)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_AttachTo](ue_ue.SceneComponent.md#k2_attachto)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_AttachToComponent](ue_ue.SceneComponent.md#k2_attachtocomponent)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_DestroyComponent](ue_ue.SceneComponent.md#k2_destroycomponent)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_DetachFromComponent](ue_ue.SceneComponent.md#k2_detachfromcomponent)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[K2_GetComponentLocation](ue_ue.SceneComponent.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[K2_GetComponentRotation](ue_ue.SceneComponent.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[K2_GetComponentScale](ue_ue.SceneComponent.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[K2_GetComponentToWorld](ue_ue.SceneComponent.md#k2_getcomponenttoworld)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_SetRelativeLocation](ue_ue.SceneComponent.md#k2_setrelativelocation)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.SceneComponent.md#k2_setrelativelocationandrotation)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_SetRelativeRotation](ue_ue.SceneComponent.md#k2_setrelativerotation)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_SetRelativeTransform](ue_ue.SceneComponent.md#k2_setrelativetransform)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_SetWorldLocation](ue_ue.SceneComponent.md#k2_setworldlocation)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.SceneComponent.md#k2_setworldlocationandrotation)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_SetWorldRotation](ue_ue.SceneComponent.md#k2_setworldrotation)

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

[SceneComponent](ue_ue.SceneComponent.md).[K2_SetWorldTransform](ue_ue.SceneComponent.md#k2_setworldtransform)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[OnRep_AttachChildren](ue_ue.SceneComponent.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[OnRep_AttachParent](ue_ue.SceneComponent.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[OnRep_AttachSocketName](ue_ue.SceneComponent.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[OnRep_IsActive](ue_ue.SceneComponent.md#onrep_isactive)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[OnRep_Transform](ue_ue.SceneComponent.md#onrep_transform)

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

[SceneComponent](ue_ue.SceneComponent.md).[OnRep_Visibility](ue_ue.SceneComponent.md#onrep_visibility)

___

### Play

▸ **Play**(`StartTime?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `StartTime?` | `number` |

#### Returns

`void`

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[ReceiveBeginPlay](ue_ue.SceneComponent.md#receivebeginplay)

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

[SceneComponent](ue_ue.SceneComponent.md).[ReceiveEndPlay](ue_ue.SceneComponent.md#receiveendplay)

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

[SceneComponent](ue_ue.SceneComponent.md).[ReceiveTick](ue_ue.SceneComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[RegisterComponent](ue_ue.SceneComponent.md#registercomponent)

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

[SceneComponent](ue_ue.SceneComponent.md).[RemoveTickPrerequisiteActor](ue_ue.SceneComponent.md#removetickprerequisiteactor)

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

[SceneComponent](ue_ue.SceneComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.SceneComponent.md#removetickprerequisitecomponent)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[ResetRelativeTransform](ue_ue.SceneComponent.md#resetrelativetransform)

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

[SceneComponent](ue_ue.SceneComponent.md).[SetAbsolute](ue_ue.SceneComponent.md#setabsolute)

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

[SceneComponent](ue_ue.SceneComponent.md).[SetActive](ue_ue.SceneComponent.md#setactive)

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

[SceneComponent](ue_ue.SceneComponent.md).[SetAutoActivate](ue_ue.SceneComponent.md#setautoactivate)

___

### SetBoolParameter

▸ **SetBoolParameter**(`InName`, `InBool`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |
| `InBool` | `boolean` |

#### Returns

`void`

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

[SceneComponent](ue_ue.SceneComponent.md).[SetComponentTickEnabled](ue_ue.SceneComponent.md#setcomponenttickenabled)

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

[SceneComponent](ue_ue.SceneComponent.md).[SetComponentTickInterval](ue_ue.SceneComponent.md#setcomponenttickinterval)

___

### SetFloatParameter

▸ **SetFloatParameter**(`InName`, `InFloat`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |
| `InFloat` | `number` |

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

[SceneComponent](ue_ue.SceneComponent.md).[SetHiddenInGame](ue_ue.SceneComponent.md#sethiddeningame)

___

### SetIntParameter

▸ **SetIntParameter**(`InName`, `InInt`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |
| `InInt` | `number` |

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

[SceneComponent](ue_ue.SceneComponent.md).[SetIsReplicated](ue_ue.SceneComponent.md#setisreplicated)

___

### SetLowPassFilterEnabled

▸ **SetLowPassFilterEnabled**(`InLowPassFilterEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLowPassFilterEnabled` | `boolean` |

#### Returns

`void`

___

### SetLowPassFilterFrequency

▸ **SetLowPassFilterFrequency**(`InLowPassFilterFrequency`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InLowPassFilterFrequency` | `number` |

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

[SceneComponent](ue_ue.SceneComponent.md).[SetMobility](ue_ue.SceneComponent.md#setmobility)

___

### SetPaused

▸ **SetPaused**(`bPause`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bPause` | `boolean` |

#### Returns

`void`

___

### SetPitchMultiplier

▸ **SetPitchMultiplier**(`NewPitchMultiplier`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewPitchMultiplier` | `number` |

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

[SceneComponent](ue_ue.SceneComponent.md).[SetRelativeScale3D](ue_ue.SceneComponent.md#setrelativescale3d)

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

[SceneComponent](ue_ue.SceneComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.SceneComponent.md#setshouldupdatephysicsvolume)

___

### SetSound

▸ **SetSound**(`NewSound`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewSound` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundBase`](ue_ue.SoundBase.md)\> |

#### Returns

`void`

___

### SetSourceBusSendPostEffect

▸ **SetSourceBusSendPostEffect**(`SoundSourceBus`, `SourceBusSendLevel`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SoundSourceBus` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundSourceBus`](ue_ue.SoundSourceBus.md)\> |
| `SourceBusSendLevel` | `number` |

#### Returns

`void`

___

### SetSourceBusSendPreEffect

▸ **SetSourceBusSendPreEffect**(`SoundSourceBus`, `SourceBusSendLevel`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SoundSourceBus` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundSourceBus`](ue_ue.SoundSourceBus.md)\> |
| `SourceBusSendLevel` | `number` |

#### Returns

`void`

___

### SetSubmixSend

▸ **SetSubmixSend**(`Submix`, `SendLevel`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Submix` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundSubmix`](ue_ue.SoundSubmix.md)\> |
| `SendLevel` | `number` |

#### Returns

`void`

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

[SceneComponent](ue_ue.SceneComponent.md).[SetTickGroup](ue_ue.SceneComponent.md#settickgroup)

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

[SceneComponent](ue_ue.SceneComponent.md).[SetTickableWhenPaused](ue_ue.SceneComponent.md#settickablewhenpaused)

___

### SetUISound

▸ **SetUISound**(`bInUISound`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInUISound` | `boolean` |

#### Returns

`void`

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

[SceneComponent](ue_ue.SceneComponent.md).[SetVisibility](ue_ue.SceneComponent.md#setvisibility)

___

### SetVolumeMultiplier

▸ **SetVolumeMultiplier**(`NewVolumeMultiplier`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewVolumeMultiplier` | `number` |

#### Returns

`void`

___

### SetWaveParameter

▸ **SetWaveParameter**(`InName`, `InWave`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |
| `InWave` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundWave`](ue_ue.SoundWave.md)\> |

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

[SceneComponent](ue_ue.SceneComponent.md).[SetWorldScale3D](ue_ue.SceneComponent.md#setworldscale3d)

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

[SceneComponent](ue_ue.SceneComponent.md).[SetupAttachment](ue_ue.SceneComponent.md#setupattachment)

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

[SceneComponent](ue_ue.SceneComponent.md).[SnapTo](ue_ue.SceneComponent.md#snapto)

___

### Stop

▸ **Stop**(): `void`

#### Returns

`void`

___

### StopDelayed

▸ **StopDelayed**(`DelayTime`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DelayTime` | `number` |

#### Returns

`void`

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[SceneComponent](ue_ue.SceneComponent.md).[ToggleActive](ue_ue.SceneComponent.md#toggleactive)

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

[SceneComponent](ue_ue.SceneComponent.md).[ToggleVisibility](ue_ue.SceneComponent.md#togglevisibility)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`AudioComponent`](ue_ue.AudioComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`AudioComponent`](ue_ue.AudioComponent.md)

#### Overrides

[SceneComponent](ue_ue.SceneComponent.md).[Find](ue_ue.SceneComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`AudioComponent`](ue_ue.AudioComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`AudioComponent`](ue_ue.AudioComponent.md)

#### Overrides

[SceneComponent](ue_ue.SceneComponent.md).[Load](ue_ue.SceneComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SceneComponent](ue_ue.SceneComponent.md).[StaticClass](ue_ue.SceneComponent.md#staticclass)
