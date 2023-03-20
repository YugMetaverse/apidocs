[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / MediaSoundComponent

# Class: MediaSoundComponent

[ue/ue](../modules/ue_ue.md).MediaSoundComponent

## Hierarchy

- [`SynthComponent`](ue_ue.SynthComponent.md)

  ↳ **`MediaSoundComponent`**

## Table of contents

### Constructors

- [constructor](ue_ue.MediaSoundComponent.md#constructor)

### Properties

- [AssetUserData](ue_ue.MediaSoundComponent.md#assetuserdata)
- [AttachChildren](ue_ue.MediaSoundComponent.md#attachchildren)
- [AttachParent](ue_ue.MediaSoundComponent.md#attachparent)
- [AttachSocketName](ue_ue.MediaSoundComponent.md#attachsocketname)
- [AttenuationOverrides](ue_ue.MediaSoundComponent.md#attenuationoverrides)
- [AttenuationSettings](ue_ue.MediaSoundComponent.md#attenuationsettings)
- [AudioComponent](ue_ue.MediaSoundComponent.md#audiocomponent)
- [BusSends](ue_ue.MediaSoundComponent.md#bussends)
- [Channels](ue_ue.MediaSoundComponent.md#channels)
- [ClientAttachedChildren](ue_ue.MediaSoundComponent.md#clientattachedchildren)
- [ComponentTags](ue_ue.MediaSoundComponent.md#componenttags)
- [ComponentVelocity](ue_ue.MediaSoundComponent.md#componentvelocity)
- [ConcurrencySet](ue_ue.MediaSoundComponent.md#concurrencyset)
- [ConcurrencySettings](ue_ue.MediaSoundComponent.md#concurrencysettings)
- [CreationMethod](ue_ue.MediaSoundComponent.md#creationmethod)
- [DetailMode](ue_ue.MediaSoundComponent.md#detailmode)
- [DynamicRateAdjustment](ue_ue.MediaSoundComponent.md#dynamicrateadjustment)
- [EnvelopeFollowerAttackTime](ue_ue.MediaSoundComponent.md#envelopefollowerattacktime)
- [EnvelopeFollowerReleaseTime](ue_ue.MediaSoundComponent.md#envelopefollowerreleasetime)
- [MediaPlayer](ue_ue.MediaSoundComponent.md#mediaplayer)
- [Mobility](ue_ue.MediaSoundComponent.md#mobility)
- [Modulation](ue_ue.MediaSoundComponent.md#modulation)
- [OnAudioEnvelopeValue](ue_ue.MediaSoundComponent.md#onaudioenvelopevalue)
- [OnComponentActivated](ue_ue.MediaSoundComponent.md#oncomponentactivated)
- [OnComponentDeactivated](ue_ue.MediaSoundComponent.md#oncomponentdeactivated)
- [PhysicsVolume](ue_ue.MediaSoundComponent.md#physicsvolume)
- [PhysicsVolumeChangedDelegate](ue_ue.MediaSoundComponent.md#physicsvolumechangeddelegate)
- [PreEffectBusSends](ue_ue.MediaSoundComponent.md#preeffectbussends)
- [PrimaryComponentTick](ue_ue.MediaSoundComponent.md#primarycomponenttick)
- [RateAdjustmentFactor](ue_ue.MediaSoundComponent.md#rateadjustmentfactor)
- [RateAdjustmentRange](ue_ue.MediaSoundComponent.md#rateadjustmentrange)
- [RelativeLocation](ue_ue.MediaSoundComponent.md#relativelocation)
- [RelativeRotation](ue_ue.MediaSoundComponent.md#relativerotation)
- [RelativeScale3D](ue_ue.MediaSoundComponent.md#relativescale3d)
- [SoundClass](ue_ue.MediaSoundComponent.md#soundclass)
- [SoundSubmix](ue_ue.MediaSoundComponent.md#soundsubmix)
- [SoundSubmixSends](ue_ue.MediaSoundComponent.md#soundsubmixsends)
- [SourceEffectChain](ue_ue.MediaSoundComponent.md#sourceeffectchain)
- [Synth](ue_ue.MediaSoundComponent.md#synth)
- [UCSModifiedProperties](ue_ue.MediaSoundComponent.md#ucsmodifiedproperties)
- [\_\_tid\_ActorComponent\_\_](ue_ue.MediaSoundComponent.md#__tid_actorcomponent__)
- [\_\_tid\_MediaSoundComponent\_\_](ue_ue.MediaSoundComponent.md#__tid_mediasoundcomponent__)
- [\_\_tid\_Object\_\_](ue_ue.MediaSoundComponent.md#__tid_object__)
- [\_\_tid\_SceneComponent\_\_](ue_ue.MediaSoundComponent.md#__tid_scenecomponent__)
- [\_\_tid\_SynthComponent\_\_](ue_ue.MediaSoundComponent.md#__tid_synthcomponent__)
- [bAbsoluteLocation](ue_ue.MediaSoundComponent.md#babsolutelocation)
- [bAbsoluteRotation](ue_ue.MediaSoundComponent.md#babsoluterotation)
- [bAbsoluteScale](ue_ue.MediaSoundComponent.md#babsolutescale)
- [bAllowSpatialization](ue_ue.MediaSoundComponent.md#ballowspatialization)
- [bAutoActivate](ue_ue.MediaSoundComponent.md#bautoactivate)
- [bAutoDestroy](ue_ue.MediaSoundComponent.md#bautodestroy)
- [bBoundsChangeTriggersStreamingDataRebuild](ue_ue.MediaSoundComponent.md#bboundschangetriggersstreamingdatarebuild)
- [bCanEverAffectNavigation](ue_ue.MediaSoundComponent.md#bcaneveraffectnavigation)
- [bComponentToWorldUpdated](ue_ue.MediaSoundComponent.md#bcomponenttoworldupdated)
- [bCreatedByConstructionScript](ue_ue.MediaSoundComponent.md#bcreatedbyconstructionscript)
- [bEditableWhenInherited](ue_ue.MediaSoundComponent.md#beditablewheninherited)
- [bHiddenInGame](ue_ue.MediaSoundComponent.md#bhiddeningame)
- [bInstanceComponent](ue_ue.MediaSoundComponent.md#binstancecomponent)
- [bIsActive](ue_ue.MediaSoundComponent.md#bisactive)
- [bIsEditorOnly](ue_ue.MediaSoundComponent.md#biseditoronly)
- [bIsPreviewSound](ue_ue.MediaSoundComponent.md#bispreviewsound)
- [bIsUISound](ue_ue.MediaSoundComponent.md#bisuisound)
- [bIsVisualizationComponent](ue_ue.MediaSoundComponent.md#bisvisualizationcomponent)
- [bNetAddressable](ue_ue.MediaSoundComponent.md#bnetaddressable)
- [bOutputToBusOnly](ue_ue.MediaSoundComponent.md#boutputtobusonly)
- [bOverrideAttenuation](ue_ue.MediaSoundComponent.md#boverrideattenuation)
- [bReplicates](ue_ue.MediaSoundComponent.md#breplicates)
- [bShouldBeAttached](ue_ue.MediaSoundComponent.md#bshouldbeattached)
- [bShouldSnapLocationWhenAttached](ue_ue.MediaSoundComponent.md#bshouldsnaplocationwhenattached)
- [bShouldSnapRotationWhenAttached](ue_ue.MediaSoundComponent.md#bshouldsnaprotationwhenattached)
- [bShouldUpdatePhysicsVolume](ue_ue.MediaSoundComponent.md#bshouldupdatephysicsvolume)
- [bStopWhenOwnerDestroyed](ue_ue.MediaSoundComponent.md#bstopwhenownerdestroyed)
- [bUseAttachParentBound](ue_ue.MediaSoundComponent.md#buseattachparentbound)
- [bVisible](ue_ue.MediaSoundComponent.md#bvisible)
- [bVisualizeComponent](ue_ue.MediaSoundComponent.md#bvisualizecomponent)

### Methods

- [Activate](ue_ue.MediaSoundComponent.md#activate)
- [AddTickPrerequisiteActor](ue_ue.MediaSoundComponent.md#addtickprerequisiteactor)
- [AddTickPrerequisiteComponent](ue_ue.MediaSoundComponent.md#addtickprerequisitecomponent)
- [BP\_GetAttenuationSettingsToApply](ue_ue.MediaSoundComponent.md#bp_getattenuationsettingstoapply)
- [ComponentHasTag](ue_ue.MediaSoundComponent.md#componenthastag)
- [CreateDefaultSubobject](ue_ue.MediaSoundComponent.md#createdefaultsubobject)
- [Deactivate](ue_ue.MediaSoundComponent.md#deactivate)
- [DetachFromParent](ue_ue.MediaSoundComponent.md#detachfromparent)
- [DoesSocketExist](ue_ue.MediaSoundComponent.md#doessocketexist)
- [ExecuteUbergraph](ue_ue.MediaSoundComponent.md#executeubergraph)
- [GetAllSocketNames](ue_ue.MediaSoundComponent.md#getallsocketnames)
- [GetAttachParent](ue_ue.MediaSoundComponent.md#getattachparent)
- [GetAttachSocketName](ue_ue.MediaSoundComponent.md#getattachsocketname)
- [GetChildComponent](ue_ue.MediaSoundComponent.md#getchildcomponent)
- [GetChildrenComponents](ue_ue.MediaSoundComponent.md#getchildrencomponents)
- [GetClass](ue_ue.MediaSoundComponent.md#getclass)
- [GetComponentTickInterval](ue_ue.MediaSoundComponent.md#getcomponenttickinterval)
- [GetComponentVelocity](ue_ue.MediaSoundComponent.md#getcomponentvelocity)
- [GetEnvelopeValue](ue_ue.MediaSoundComponent.md#getenvelopevalue)
- [GetForwardVector](ue_ue.MediaSoundComponent.md#getforwardvector)
- [GetMediaPlayer](ue_ue.MediaSoundComponent.md#getmediaplayer)
- [GetName](ue_ue.MediaSoundComponent.md#getname)
- [GetNumChildrenComponents](ue_ue.MediaSoundComponent.md#getnumchildrencomponents)
- [GetOuter](ue_ue.MediaSoundComponent.md#getouter)
- [GetOwner](ue_ue.MediaSoundComponent.md#getowner)
- [GetParentComponents](ue_ue.MediaSoundComponent.md#getparentcomponents)
- [GetPhysicsVolume](ue_ue.MediaSoundComponent.md#getphysicsvolume)
- [GetRelativeTransform](ue_ue.MediaSoundComponent.md#getrelativetransform)
- [GetRightVector](ue_ue.MediaSoundComponent.md#getrightvector)
- [GetShouldUpdatePhysicsVolume](ue_ue.MediaSoundComponent.md#getshouldupdatephysicsvolume)
- [GetSocketLocation](ue_ue.MediaSoundComponent.md#getsocketlocation)
- [GetSocketQuaternion](ue_ue.MediaSoundComponent.md#getsocketquaternion)
- [GetSocketRotation](ue_ue.MediaSoundComponent.md#getsocketrotation)
- [GetSocketTransform](ue_ue.MediaSoundComponent.md#getsockettransform)
- [GetSpectralData](ue_ue.MediaSoundComponent.md#getspectraldata)
- [GetUpVector](ue_ue.MediaSoundComponent.md#getupvector)
- [GetWorld](ue_ue.MediaSoundComponent.md#getworld)
- [IsActive](ue_ue.MediaSoundComponent.md#isactive)
- [IsAnySimulatingPhysics](ue_ue.MediaSoundComponent.md#isanysimulatingphysics)
- [IsBeingDestroyed](ue_ue.MediaSoundComponent.md#isbeingdestroyed)
- [IsComponentTickEnabled](ue_ue.MediaSoundComponent.md#iscomponenttickenabled)
- [IsPlaying](ue_ue.MediaSoundComponent.md#isplaying)
- [IsSimulatingPhysics](ue_ue.MediaSoundComponent.md#issimulatingphysics)
- [IsVisible](ue_ue.MediaSoundComponent.md#isvisible)
- [K2\_AddLocalOffset](ue_ue.MediaSoundComponent.md#k2_addlocaloffset)
- [K2\_AddLocalRotation](ue_ue.MediaSoundComponent.md#k2_addlocalrotation)
- [K2\_AddLocalTransform](ue_ue.MediaSoundComponent.md#k2_addlocaltransform)
- [K2\_AddRelativeLocation](ue_ue.MediaSoundComponent.md#k2_addrelativelocation)
- [K2\_AddRelativeRotation](ue_ue.MediaSoundComponent.md#k2_addrelativerotation)
- [K2\_AddWorldOffset](ue_ue.MediaSoundComponent.md#k2_addworldoffset)
- [K2\_AddWorldRotation](ue_ue.MediaSoundComponent.md#k2_addworldrotation)
- [K2\_AddWorldTransform](ue_ue.MediaSoundComponent.md#k2_addworldtransform)
- [K2\_AttachTo](ue_ue.MediaSoundComponent.md#k2_attachto)
- [K2\_AttachToComponent](ue_ue.MediaSoundComponent.md#k2_attachtocomponent)
- [K2\_DestroyComponent](ue_ue.MediaSoundComponent.md#k2_destroycomponent)
- [K2\_DetachFromComponent](ue_ue.MediaSoundComponent.md#k2_detachfromcomponent)
- [K2\_GetComponentLocation](ue_ue.MediaSoundComponent.md#k2_getcomponentlocation)
- [K2\_GetComponentRotation](ue_ue.MediaSoundComponent.md#k2_getcomponentrotation)
- [K2\_GetComponentScale](ue_ue.MediaSoundComponent.md#k2_getcomponentscale)
- [K2\_GetComponentToWorld](ue_ue.MediaSoundComponent.md#k2_getcomponenttoworld)
- [K2\_SetRelativeLocation](ue_ue.MediaSoundComponent.md#k2_setrelativelocation)
- [K2\_SetRelativeLocationAndRotation](ue_ue.MediaSoundComponent.md#k2_setrelativelocationandrotation)
- [K2\_SetRelativeRotation](ue_ue.MediaSoundComponent.md#k2_setrelativerotation)
- [K2\_SetRelativeTransform](ue_ue.MediaSoundComponent.md#k2_setrelativetransform)
- [K2\_SetWorldLocation](ue_ue.MediaSoundComponent.md#k2_setworldlocation)
- [K2\_SetWorldLocationAndRotation](ue_ue.MediaSoundComponent.md#k2_setworldlocationandrotation)
- [K2\_SetWorldRotation](ue_ue.MediaSoundComponent.md#k2_setworldrotation)
- [K2\_SetWorldTransform](ue_ue.MediaSoundComponent.md#k2_setworldtransform)
- [OnRep\_AttachChildren](ue_ue.MediaSoundComponent.md#onrep_attachchildren)
- [OnRep\_AttachParent](ue_ue.MediaSoundComponent.md#onrep_attachparent)
- [OnRep\_AttachSocketName](ue_ue.MediaSoundComponent.md#onrep_attachsocketname)
- [OnRep\_IsActive](ue_ue.MediaSoundComponent.md#onrep_isactive)
- [OnRep\_Transform](ue_ue.MediaSoundComponent.md#onrep_transform)
- [OnRep\_Visibility](ue_ue.MediaSoundComponent.md#onrep_visibility)
- [ReceiveBeginPlay](ue_ue.MediaSoundComponent.md#receivebeginplay)
- [ReceiveEndPlay](ue_ue.MediaSoundComponent.md#receiveendplay)
- [ReceiveTick](ue_ue.MediaSoundComponent.md#receivetick)
- [RegisterComponent](ue_ue.MediaSoundComponent.md#registercomponent)
- [RemoveTickPrerequisiteActor](ue_ue.MediaSoundComponent.md#removetickprerequisiteactor)
- [RemoveTickPrerequisiteComponent](ue_ue.MediaSoundComponent.md#removetickprerequisitecomponent)
- [ResetRelativeTransform](ue_ue.MediaSoundComponent.md#resetrelativetransform)
- [SetAbsolute](ue_ue.MediaSoundComponent.md#setabsolute)
- [SetActive](ue_ue.MediaSoundComponent.md#setactive)
- [SetAutoActivate](ue_ue.MediaSoundComponent.md#setautoactivate)
- [SetComponentTickEnabled](ue_ue.MediaSoundComponent.md#setcomponenttickenabled)
- [SetComponentTickInterval](ue_ue.MediaSoundComponent.md#setcomponenttickinterval)
- [SetEnableEnvelopeFollowing](ue_ue.MediaSoundComponent.md#setenableenvelopefollowing)
- [SetEnableSpectralAnalysis](ue_ue.MediaSoundComponent.md#setenablespectralanalysis)
- [SetEnvelopeFollowingsettings](ue_ue.MediaSoundComponent.md#setenvelopefollowingsettings)
- [SetHiddenInGame](ue_ue.MediaSoundComponent.md#sethiddeningame)
- [SetIsReplicated](ue_ue.MediaSoundComponent.md#setisreplicated)
- [SetMediaPlayer](ue_ue.MediaSoundComponent.md#setmediaplayer)
- [SetMobility](ue_ue.MediaSoundComponent.md#setmobility)
- [SetRelativeScale3D](ue_ue.MediaSoundComponent.md#setrelativescale3d)
- [SetShouldUpdatePhysicsVolume](ue_ue.MediaSoundComponent.md#setshouldupdatephysicsvolume)
- [SetSpectralAnalysisSettings](ue_ue.MediaSoundComponent.md#setspectralanalysissettings)
- [SetSubmixSend](ue_ue.MediaSoundComponent.md#setsubmixsend)
- [SetTickGroup](ue_ue.MediaSoundComponent.md#settickgroup)
- [SetTickableWhenPaused](ue_ue.MediaSoundComponent.md#settickablewhenpaused)
- [SetVisibility](ue_ue.MediaSoundComponent.md#setvisibility)
- [SetVolumeMultiplier](ue_ue.MediaSoundComponent.md#setvolumemultiplier)
- [SetWorldScale3D](ue_ue.MediaSoundComponent.md#setworldscale3d)
- [SetupAttachment](ue_ue.MediaSoundComponent.md#setupattachment)
- [SnapTo](ue_ue.MediaSoundComponent.md#snapto)
- [Start](ue_ue.MediaSoundComponent.md#start)
- [Stop](ue_ue.MediaSoundComponent.md#stop)
- [ToggleActive](ue_ue.MediaSoundComponent.md#toggleactive)
- [ToggleVisibility](ue_ue.MediaSoundComponent.md#togglevisibility)
- [Find](ue_ue.MediaSoundComponent.md#find)
- [Load](ue_ue.MediaSoundComponent.md#load)
- [StaticClass](ue_ue.MediaSoundComponent.md#staticclass)

## Constructors

### constructor

• **new MediaSoundComponent**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[SynthComponent](ue_ue.SynthComponent.md).[constructor](ue_ue.SynthComponent.md#constructor)

## Properties

### AssetUserData

• **AssetUserData**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`AssetUserData`](ue_ue.AssetUserData.md)\>

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[AssetUserData](ue_ue.SynthComponent.md#assetuserdata)

___

### AttachChildren

• **AttachChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[AttachChildren](ue_ue.SynthComponent.md#attachchildren)

___

### AttachParent

• **AttachParent**: [`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[AttachParent](ue_ue.SynthComponent.md#attachparent)

___

### AttachSocketName

• **AttachSocketName**: `string`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[AttachSocketName](ue_ue.SynthComponent.md#attachsocketname)

___

### AttenuationOverrides

• **AttenuationOverrides**: [`SoundAttenuationSettings`](ue_ue.SoundAttenuationSettings.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[AttenuationOverrides](ue_ue.SynthComponent.md#attenuationoverrides)

___

### AttenuationSettings

• **AttenuationSettings**: [`SoundAttenuation`](ue_ue.SoundAttenuation.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[AttenuationSettings](ue_ue.SynthComponent.md#attenuationsettings)

___

### AudioComponent

• **AudioComponent**: [`AudioComponent`](ue_ue.AudioComponent.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[AudioComponent](ue_ue.SynthComponent.md#audiocomponent)

___

### BusSends

• **BusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[BusSends](ue_ue.SynthComponent.md#bussends)

___

### Channels

• **Channels**: [`EMediaSoundChannels`](../enums/ue_ue.EMediaSoundChannels.md)

___

### ClientAttachedChildren

• **ClientAttachedChildren**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SceneComponent`](ue_ue.SceneComponent.md)\>

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[ClientAttachedChildren](ue_ue.SynthComponent.md#clientattachedchildren)

___

### ComponentTags

• **ComponentTags**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[ComponentTags](ue_ue.SynthComponent.md#componenttags)

___

### ComponentVelocity

• **ComponentVelocity**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[ComponentVelocity](ue_ue.SynthComponent.md#componentvelocity)

___

### ConcurrencySet

• **ConcurrencySet**: [`TSet`](../interfaces/ue_puerts.TSet.md)<[`SoundConcurrency`](ue_ue.SoundConcurrency.md)\>

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[ConcurrencySet](ue_ue.SynthComponent.md#concurrencyset)

___

### ConcurrencySettings

• **ConcurrencySettings**: [`SoundConcurrency`](ue_ue.SoundConcurrency.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[ConcurrencySettings](ue_ue.SynthComponent.md#concurrencysettings)

___

### CreationMethod

• **CreationMethod**: [`EComponentCreationMethod`](../enums/ue_ue.EComponentCreationMethod.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[CreationMethod](ue_ue.SynthComponent.md#creationmethod)

___

### DetailMode

• **DetailMode**: [`EDetailMode`](../enums/ue_ue.EDetailMode.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[DetailMode](ue_ue.SynthComponent.md#detailmode)

___

### DynamicRateAdjustment

• **DynamicRateAdjustment**: `boolean`

___

### EnvelopeFollowerAttackTime

• **EnvelopeFollowerAttackTime**: `number`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[EnvelopeFollowerAttackTime](ue_ue.SynthComponent.md#envelopefollowerattacktime)

___

### EnvelopeFollowerReleaseTime

• **EnvelopeFollowerReleaseTime**: `number`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[EnvelopeFollowerReleaseTime](ue_ue.SynthComponent.md#envelopefollowerreleasetime)

___

### MediaPlayer

• **MediaPlayer**: [`MediaPlayer`](ue_ue.MediaPlayer.md)

___

### Mobility

• **Mobility**: [`EComponentMobility`](../enums/ue_ue.EComponentMobility.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[Mobility](ue_ue.SynthComponent.md#mobility)

___

### Modulation

• **Modulation**: [`SoundModulation`](ue_ue.SoundModulation.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[Modulation](ue_ue.SynthComponent.md#modulation)

___

### OnAudioEnvelopeValue

• **OnAudioEnvelopeValue**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`EnvelopeValue`: `number`) => `void`\>

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[OnAudioEnvelopeValue](ue_ue.SynthComponent.md#onaudioenvelopevalue)

___

### OnComponentActivated

• **OnComponentActivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>, `bReset`: `boolean`) => `void`\>

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[OnComponentActivated](ue_ue.SynthComponent.md#oncomponentactivated)

___

### OnComponentDeactivated

• **OnComponentDeactivated**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`Component`: [`$Nullable`](../modules/puerts.md#$nullable)<[`ActorComponent`](ue_ue.ActorComponent.md)\>) => `void`\>

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[OnComponentDeactivated](ue_ue.SynthComponent.md#oncomponentdeactivated)

___

### PhysicsVolume

• **PhysicsVolume**: [`TWeakObjectPtr`](../modules/ue_puerts.md#tweakobjectptr)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[PhysicsVolume](ue_ue.SynthComponent.md#physicsvolume)

___

### PhysicsVolumeChangedDelegate

• **PhysicsVolumeChangedDelegate**: [`$MulticastDelegate`](../interfaces/ue_puerts._MulticastDelegate.md)<(`NewVolume`: [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicsVolume`](ue_ue.PhysicsVolume.md)\>) => `void`\>

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[PhysicsVolumeChangedDelegate](ue_ue.SynthComponent.md#physicsvolumechangeddelegate)

___

### PreEffectBusSends

• **PreEffectBusSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSourceBusSendInfo`](ue_ue.SoundSourceBusSendInfo.md)\>

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[PreEffectBusSends](ue_ue.SynthComponent.md#preeffectbussends)

___

### PrimaryComponentTick

• **PrimaryComponentTick**: [`ActorComponentTickFunction`](ue_ue.ActorComponentTickFunction.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[PrimaryComponentTick](ue_ue.SynthComponent.md#primarycomponenttick)

___

### RateAdjustmentFactor

• **RateAdjustmentFactor**: `number`

___

### RateAdjustmentRange

• **RateAdjustmentRange**: [`FloatRange`](ue_ue.FloatRange.md)

___

### RelativeLocation

• **RelativeLocation**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[RelativeLocation](ue_ue.SynthComponent.md#relativelocation)

___

### RelativeRotation

• **RelativeRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[RelativeRotation](ue_ue.SynthComponent.md#relativerotation)

___

### RelativeScale3D

• **RelativeScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[RelativeScale3D](ue_ue.SynthComponent.md#relativescale3d)

___

### SoundClass

• **SoundClass**: [`SoundClass`](ue_ue.SoundClass.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[SoundClass](ue_ue.SynthComponent.md#soundclass)

___

### SoundSubmix

• **SoundSubmix**: [`SoundSubmix`](ue_ue.SoundSubmix.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[SoundSubmix](ue_ue.SynthComponent.md#soundsubmix)

___

### SoundSubmixSends

• **SoundSubmixSends**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SoundSubmixSendInfo`](ue_ue.SoundSubmixSendInfo.md)\>

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[SoundSubmixSends](ue_ue.SynthComponent.md#soundsubmixsends)

___

### SourceEffectChain

• **SourceEffectChain**: [`SoundEffectSourcePresetChain`](ue_ue.SoundEffectSourcePresetChain.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[SourceEffectChain](ue_ue.SynthComponent.md#sourceeffectchain)

___

### Synth

• **Synth**: [`SynthSound`](ue_ue.SynthSound.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[Synth](ue_ue.SynthComponent.md#synth)

___

### UCSModifiedProperties

• **UCSModifiedProperties**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`SimpleMemberReference`](ue_ue.SimpleMemberReference.md)\>

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[UCSModifiedProperties](ue_ue.SynthComponent.md#ucsmodifiedproperties)

___

### \_\_tid\_ActorComponent\_\_

• **\_\_tid\_ActorComponent\_\_**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[__tid_ActorComponent__](ue_ue.SynthComponent.md#__tid_actorcomponent__)

___

### \_\_tid\_MediaSoundComponent\_\_

• **\_\_tid\_MediaSoundComponent\_\_**: `boolean`

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[__tid_Object__](ue_ue.SynthComponent.md#__tid_object__)

___

### \_\_tid\_SceneComponent\_\_

• **\_\_tid\_SceneComponent\_\_**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[__tid_SceneComponent__](ue_ue.SynthComponent.md#__tid_scenecomponent__)

___

### \_\_tid\_SynthComponent\_\_

• **\_\_tid\_SynthComponent\_\_**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[__tid_SynthComponent__](ue_ue.SynthComponent.md#__tid_synthcomponent__)

___

### bAbsoluteLocation

• **bAbsoluteLocation**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bAbsoluteLocation](ue_ue.SynthComponent.md#babsolutelocation)

___

### bAbsoluteRotation

• **bAbsoluteRotation**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bAbsoluteRotation](ue_ue.SynthComponent.md#babsoluterotation)

___

### bAbsoluteScale

• **bAbsoluteScale**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bAbsoluteScale](ue_ue.SynthComponent.md#babsolutescale)

___

### bAllowSpatialization

• **bAllowSpatialization**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bAllowSpatialization](ue_ue.SynthComponent.md#ballowspatialization)

___

### bAutoActivate

• **bAutoActivate**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bAutoActivate](ue_ue.SynthComponent.md#bautoactivate)

___

### bAutoDestroy

• **bAutoDestroy**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bAutoDestroy](ue_ue.SynthComponent.md#bautodestroy)

___

### bBoundsChangeTriggersStreamingDataRebuild

• **bBoundsChangeTriggersStreamingDataRebuild**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bBoundsChangeTriggersStreamingDataRebuild](ue_ue.SynthComponent.md#bboundschangetriggersstreamingdatarebuild)

___

### bCanEverAffectNavigation

• **bCanEverAffectNavigation**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bCanEverAffectNavigation](ue_ue.SynthComponent.md#bcaneveraffectnavigation)

___

### bComponentToWorldUpdated

• **bComponentToWorldUpdated**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bComponentToWorldUpdated](ue_ue.SynthComponent.md#bcomponenttoworldupdated)

___

### bCreatedByConstructionScript

• **bCreatedByConstructionScript**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bCreatedByConstructionScript](ue_ue.SynthComponent.md#bcreatedbyconstructionscript)

___

### bEditableWhenInherited

• **bEditableWhenInherited**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bEditableWhenInherited](ue_ue.SynthComponent.md#beditablewheninherited)

___

### bHiddenInGame

• **bHiddenInGame**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bHiddenInGame](ue_ue.SynthComponent.md#bhiddeningame)

___

### bInstanceComponent

• **bInstanceComponent**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bInstanceComponent](ue_ue.SynthComponent.md#binstancecomponent)

___

### bIsActive

• **bIsActive**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bIsActive](ue_ue.SynthComponent.md#bisactive)

___

### bIsEditorOnly

• **bIsEditorOnly**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bIsEditorOnly](ue_ue.SynthComponent.md#biseditoronly)

___

### bIsPreviewSound

• **bIsPreviewSound**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bIsPreviewSound](ue_ue.SynthComponent.md#bispreviewsound)

___

### bIsUISound

• **bIsUISound**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bIsUISound](ue_ue.SynthComponent.md#bisuisound)

___

### bIsVisualizationComponent

• **bIsVisualizationComponent**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bIsVisualizationComponent](ue_ue.SynthComponent.md#bisvisualizationcomponent)

___

### bNetAddressable

• **bNetAddressable**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bNetAddressable](ue_ue.SynthComponent.md#bnetaddressable)

___

### bOutputToBusOnly

• **bOutputToBusOnly**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bOutputToBusOnly](ue_ue.SynthComponent.md#boutputtobusonly)

___

### bOverrideAttenuation

• **bOverrideAttenuation**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bOverrideAttenuation](ue_ue.SynthComponent.md#boverrideattenuation)

___

### bReplicates

• **bReplicates**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bReplicates](ue_ue.SynthComponent.md#breplicates)

___

### bShouldBeAttached

• **bShouldBeAttached**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bShouldBeAttached](ue_ue.SynthComponent.md#bshouldbeattached)

___

### bShouldSnapLocationWhenAttached

• **bShouldSnapLocationWhenAttached**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bShouldSnapLocationWhenAttached](ue_ue.SynthComponent.md#bshouldsnaplocationwhenattached)

___

### bShouldSnapRotationWhenAttached

• **bShouldSnapRotationWhenAttached**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bShouldSnapRotationWhenAttached](ue_ue.SynthComponent.md#bshouldsnaprotationwhenattached)

___

### bShouldUpdatePhysicsVolume

• **bShouldUpdatePhysicsVolume**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bShouldUpdatePhysicsVolume](ue_ue.SynthComponent.md#bshouldupdatephysicsvolume)

___

### bStopWhenOwnerDestroyed

• **bStopWhenOwnerDestroyed**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bStopWhenOwnerDestroyed](ue_ue.SynthComponent.md#bstopwhenownerdestroyed)

___

### bUseAttachParentBound

• **bUseAttachParentBound**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bUseAttachParentBound](ue_ue.SynthComponent.md#buseattachparentbound)

___

### bVisible

• **bVisible**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bVisible](ue_ue.SynthComponent.md#bvisible)

___

### bVisualizeComponent

• **bVisualizeComponent**: `boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[bVisualizeComponent](ue_ue.SynthComponent.md#bvisualizecomponent)

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

[SynthComponent](ue_ue.SynthComponent.md).[Activate](ue_ue.SynthComponent.md#activate)

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

[SynthComponent](ue_ue.SynthComponent.md).[AddTickPrerequisiteActor](ue_ue.SynthComponent.md#addtickprerequisiteactor)

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

[SynthComponent](ue_ue.SynthComponent.md).[AddTickPrerequisiteComponent](ue_ue.SynthComponent.md#addtickprerequisitecomponent)

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

[SynthComponent](ue_ue.SynthComponent.md).[ComponentHasTag](ue_ue.SynthComponent.md#componenthastag)

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

[SynthComponent](ue_ue.SynthComponent.md).[CreateDefaultSubobject](ue_ue.SynthComponent.md#createdefaultsubobject)

___

### Deactivate

▸ **Deactivate**(): `void`

#### Returns

`void`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[Deactivate](ue_ue.SynthComponent.md#deactivate)

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

[SynthComponent](ue_ue.SynthComponent.md).[DetachFromParent](ue_ue.SynthComponent.md#detachfromparent)

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

[SynthComponent](ue_ue.SynthComponent.md).[DoesSocketExist](ue_ue.SynthComponent.md#doessocketexist)

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

[SynthComponent](ue_ue.SynthComponent.md).[ExecuteUbergraph](ue_ue.SynthComponent.md#executeubergraph)

___

### GetAllSocketNames

▸ **GetAllSocketNames**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[GetAllSocketNames](ue_ue.SynthComponent.md#getallsocketnames)

___

### GetAttachParent

▸ **GetAttachParent**(): [`SceneComponent`](ue_ue.SceneComponent.md)

#### Returns

[`SceneComponent`](ue_ue.SceneComponent.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[GetAttachParent](ue_ue.SynthComponent.md#getattachparent)

___

### GetAttachSocketName

▸ **GetAttachSocketName**(): `string`

#### Returns

`string`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[GetAttachSocketName](ue_ue.SynthComponent.md#getattachsocketname)

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

[SynthComponent](ue_ue.SynthComponent.md).[GetChildComponent](ue_ue.SynthComponent.md#getchildcomponent)

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

[SynthComponent](ue_ue.SynthComponent.md).[GetChildrenComponents](ue_ue.SynthComponent.md#getchildrencomponents)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[GetClass](ue_ue.SynthComponent.md#getclass)

___

### GetComponentTickInterval

▸ **GetComponentTickInterval**(): `number`

#### Returns

`number`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[GetComponentTickInterval](ue_ue.SynthComponent.md#getcomponenttickinterval)

___

### GetComponentVelocity

▸ **GetComponentVelocity**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[GetComponentVelocity](ue_ue.SynthComponent.md#getcomponentvelocity)

___

### GetEnvelopeValue

▸ **GetEnvelopeValue**(): `number`

#### Returns

`number`

___

### GetForwardVector

▸ **GetForwardVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[GetForwardVector](ue_ue.SynthComponent.md#getforwardvector)

___

### GetMediaPlayer

▸ **GetMediaPlayer**(): [`MediaPlayer`](ue_ue.MediaPlayer.md)

#### Returns

[`MediaPlayer`](ue_ue.MediaPlayer.md)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[GetName](ue_ue.SynthComponent.md#getname)

___

### GetNumChildrenComponents

▸ **GetNumChildrenComponents**(): `number`

#### Returns

`number`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[GetNumChildrenComponents](ue_ue.SynthComponent.md#getnumchildrencomponents)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[GetOuter](ue_ue.SynthComponent.md#getouter)

___

### GetOwner

▸ **GetOwner**(): [`Actor`](ue_ue.Actor.md)

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[GetOwner](ue_ue.SynthComponent.md#getowner)

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

[SynthComponent](ue_ue.SynthComponent.md).[GetParentComponents](ue_ue.SynthComponent.md#getparentcomponents)

___

### GetPhysicsVolume

▸ **GetPhysicsVolume**(): [`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Returns

[`PhysicsVolume`](ue_ue.PhysicsVolume.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[GetPhysicsVolume](ue_ue.SynthComponent.md#getphysicsvolume)

___

### GetRelativeTransform

▸ **GetRelativeTransform**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[GetRelativeTransform](ue_ue.SynthComponent.md#getrelativetransform)

___

### GetRightVector

▸ **GetRightVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[GetRightVector](ue_ue.SynthComponent.md#getrightvector)

___

### GetShouldUpdatePhysicsVolume

▸ **GetShouldUpdatePhysicsVolume**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[GetShouldUpdatePhysicsVolume](ue_ue.SynthComponent.md#getshouldupdatephysicsvolume)

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

[SynthComponent](ue_ue.SynthComponent.md).[GetSocketLocation](ue_ue.SynthComponent.md#getsocketlocation)

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

[SynthComponent](ue_ue.SynthComponent.md).[GetSocketQuaternion](ue_ue.SynthComponent.md#getsocketquaternion)

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

[SynthComponent](ue_ue.SynthComponent.md).[GetSocketRotation](ue_ue.SynthComponent.md#getsocketrotation)

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

[SynthComponent](ue_ue.SynthComponent.md).[GetSocketTransform](ue_ue.SynthComponent.md#getsockettransform)

___

### GetSpectralData

▸ **GetSpectralData**(): [`TArray`](../interfaces/ue_puerts.TArray.md)<[`MediaSoundComponentSpectralData`](ue_ue.MediaSoundComponentSpectralData.md)\>

#### Returns

[`TArray`](../interfaces/ue_puerts.TArray.md)<[`MediaSoundComponentSpectralData`](ue_ue.MediaSoundComponentSpectralData.md)\>

___

### GetUpVector

▸ **GetUpVector**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[GetUpVector](ue_ue.SynthComponent.md#getupvector)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[GetWorld](ue_ue.SynthComponent.md#getworld)

___

### IsActive

▸ **IsActive**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[IsActive](ue_ue.SynthComponent.md#isactive)

___

### IsAnySimulatingPhysics

▸ **IsAnySimulatingPhysics**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[IsAnySimulatingPhysics](ue_ue.SynthComponent.md#isanysimulatingphysics)

___

### IsBeingDestroyed

▸ **IsBeingDestroyed**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[IsBeingDestroyed](ue_ue.SynthComponent.md#isbeingdestroyed)

___

### IsComponentTickEnabled

▸ **IsComponentTickEnabled**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[IsComponentTickEnabled](ue_ue.SynthComponent.md#iscomponenttickenabled)

___

### IsPlaying

▸ **IsPlaying**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[IsPlaying](ue_ue.SynthComponent.md#isplaying)

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

[SynthComponent](ue_ue.SynthComponent.md).[IsSimulatingPhysics](ue_ue.SynthComponent.md#issimulatingphysics)

___

### IsVisible

▸ **IsVisible**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[IsVisible](ue_ue.SynthComponent.md#isvisible)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_AddLocalOffset](ue_ue.SynthComponent.md#k2_addlocaloffset)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_AddLocalRotation](ue_ue.SynthComponent.md#k2_addlocalrotation)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_AddLocalTransform](ue_ue.SynthComponent.md#k2_addlocaltransform)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_AddRelativeLocation](ue_ue.SynthComponent.md#k2_addrelativelocation)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_AddRelativeRotation](ue_ue.SynthComponent.md#k2_addrelativerotation)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_AddWorldOffset](ue_ue.SynthComponent.md#k2_addworldoffset)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_AddWorldRotation](ue_ue.SynthComponent.md#k2_addworldrotation)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_AddWorldTransform](ue_ue.SynthComponent.md#k2_addworldtransform)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_AttachTo](ue_ue.SynthComponent.md#k2_attachto)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_AttachToComponent](ue_ue.SynthComponent.md#k2_attachtocomponent)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_DestroyComponent](ue_ue.SynthComponent.md#k2_destroycomponent)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_DetachFromComponent](ue_ue.SynthComponent.md#k2_detachfromcomponent)

___

### K2\_GetComponentLocation

▸ **K2_GetComponentLocation**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[K2_GetComponentLocation](ue_ue.SynthComponent.md#k2_getcomponentlocation)

___

### K2\_GetComponentRotation

▸ **K2_GetComponentRotation**(): [`Rotator`](ue_ue_s.Rotator.md)

#### Returns

[`Rotator`](ue_ue_s.Rotator.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[K2_GetComponentRotation](ue_ue.SynthComponent.md#k2_getcomponentrotation)

___

### K2\_GetComponentScale

▸ **K2_GetComponentScale**(): [`Vector`](ue_ue_s.Vector.md)

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[K2_GetComponentScale](ue_ue.SynthComponent.md#k2_getcomponentscale)

___

### K2\_GetComponentToWorld

▸ **K2_GetComponentToWorld**(): [`Transform`](ue_ue_s.Transform.md)

#### Returns

[`Transform`](ue_ue_s.Transform.md)

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[K2_GetComponentToWorld](ue_ue.SynthComponent.md#k2_getcomponenttoworld)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_SetRelativeLocation](ue_ue.SynthComponent.md#k2_setrelativelocation)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_SetRelativeLocationAndRotation](ue_ue.SynthComponent.md#k2_setrelativelocationandrotation)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_SetRelativeRotation](ue_ue.SynthComponent.md#k2_setrelativerotation)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_SetRelativeTransform](ue_ue.SynthComponent.md#k2_setrelativetransform)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_SetWorldLocation](ue_ue.SynthComponent.md#k2_setworldlocation)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_SetWorldLocationAndRotation](ue_ue.SynthComponent.md#k2_setworldlocationandrotation)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_SetWorldRotation](ue_ue.SynthComponent.md#k2_setworldrotation)

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

[SynthComponent](ue_ue.SynthComponent.md).[K2_SetWorldTransform](ue_ue.SynthComponent.md#k2_setworldtransform)

___

### OnRep\_AttachChildren

▸ **OnRep_AttachChildren**(): `void`

#### Returns

`void`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[OnRep_AttachChildren](ue_ue.SynthComponent.md#onrep_attachchildren)

___

### OnRep\_AttachParent

▸ **OnRep_AttachParent**(): `void`

#### Returns

`void`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[OnRep_AttachParent](ue_ue.SynthComponent.md#onrep_attachparent)

___

### OnRep\_AttachSocketName

▸ **OnRep_AttachSocketName**(): `void`

#### Returns

`void`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[OnRep_AttachSocketName](ue_ue.SynthComponent.md#onrep_attachsocketname)

___

### OnRep\_IsActive

▸ **OnRep_IsActive**(): `void`

#### Returns

`void`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[OnRep_IsActive](ue_ue.SynthComponent.md#onrep_isactive)

___

### OnRep\_Transform

▸ **OnRep_Transform**(): `void`

#### Returns

`void`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[OnRep_Transform](ue_ue.SynthComponent.md#onrep_transform)

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

[SynthComponent](ue_ue.SynthComponent.md).[OnRep_Visibility](ue_ue.SynthComponent.md#onrep_visibility)

___

### ReceiveBeginPlay

▸ **ReceiveBeginPlay**(): `void`

#### Returns

`void`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[ReceiveBeginPlay](ue_ue.SynthComponent.md#receivebeginplay)

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

[SynthComponent](ue_ue.SynthComponent.md).[ReceiveEndPlay](ue_ue.SynthComponent.md#receiveendplay)

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

[SynthComponent](ue_ue.SynthComponent.md).[ReceiveTick](ue_ue.SynthComponent.md#receivetick)

___

### RegisterComponent

▸ **RegisterComponent**(): `void`

#### Returns

`void`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[RegisterComponent](ue_ue.SynthComponent.md#registercomponent)

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

[SynthComponent](ue_ue.SynthComponent.md).[RemoveTickPrerequisiteActor](ue_ue.SynthComponent.md#removetickprerequisiteactor)

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

[SynthComponent](ue_ue.SynthComponent.md).[RemoveTickPrerequisiteComponent](ue_ue.SynthComponent.md#removetickprerequisitecomponent)

___

### ResetRelativeTransform

▸ **ResetRelativeTransform**(): `void`

#### Returns

`void`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[ResetRelativeTransform](ue_ue.SynthComponent.md#resetrelativetransform)

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

[SynthComponent](ue_ue.SynthComponent.md).[SetAbsolute](ue_ue.SynthComponent.md#setabsolute)

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

[SynthComponent](ue_ue.SynthComponent.md).[SetActive](ue_ue.SynthComponent.md#setactive)

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

[SynthComponent](ue_ue.SynthComponent.md).[SetAutoActivate](ue_ue.SynthComponent.md#setautoactivate)

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

[SynthComponent](ue_ue.SynthComponent.md).[SetComponentTickEnabled](ue_ue.SynthComponent.md#setcomponenttickenabled)

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

[SynthComponent](ue_ue.SynthComponent.md).[SetComponentTickInterval](ue_ue.SynthComponent.md#setcomponenttickinterval)

___

### SetEnableEnvelopeFollowing

▸ **SetEnableEnvelopeFollowing**(`bInEnvelopeFollowing`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInEnvelopeFollowing` | `boolean` |

#### Returns

`void`

___

### SetEnableSpectralAnalysis

▸ **SetEnableSpectralAnalysis**(`bInSpectralAnalysisEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bInSpectralAnalysisEnabled` | `boolean` |

#### Returns

`void`

___

### SetEnvelopeFollowingsettings

▸ **SetEnvelopeFollowingsettings**(`AttackTimeMsec`, `ReleaseTimeMsec`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `AttackTimeMsec` | `number` |
| `ReleaseTimeMsec` | `number` |

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

[SynthComponent](ue_ue.SynthComponent.md).[SetHiddenInGame](ue_ue.SynthComponent.md#sethiddeningame)

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

[SynthComponent](ue_ue.SynthComponent.md).[SetIsReplicated](ue_ue.SynthComponent.md#setisreplicated)

___

### SetMediaPlayer

▸ **SetMediaPlayer**(`NewMediaPlayer`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `NewMediaPlayer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MediaPlayer`](ue_ue.MediaPlayer.md)\> |

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

[SynthComponent](ue_ue.SynthComponent.md).[SetMobility](ue_ue.SynthComponent.md#setmobility)

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

[SynthComponent](ue_ue.SynthComponent.md).[SetRelativeScale3D](ue_ue.SynthComponent.md#setrelativescale3d)

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

[SynthComponent](ue_ue.SynthComponent.md).[SetShouldUpdatePhysicsVolume](ue_ue.SynthComponent.md#setshouldupdatephysicsvolume)

___

### SetSpectralAnalysisSettings

▸ **SetSpectralAnalysisSettings**(`InFrequenciesToAnalyze`, `InFFTSize?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InFrequenciesToAnalyze` | [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\> |
| `InFFTSize?` | [`EMediaSoundComponentFFTSize`](../enums/ue_ue.EMediaSoundComponentFFTSize.md) |

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

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[SetSubmixSend](ue_ue.SynthComponent.md#setsubmixsend)

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

[SynthComponent](ue_ue.SynthComponent.md).[SetTickGroup](ue_ue.SynthComponent.md#settickgroup)

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

[SynthComponent](ue_ue.SynthComponent.md).[SetTickableWhenPaused](ue_ue.SynthComponent.md#settickablewhenpaused)

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

[SynthComponent](ue_ue.SynthComponent.md).[SetVisibility](ue_ue.SynthComponent.md#setvisibility)

___

### SetVolumeMultiplier

▸ **SetVolumeMultiplier**(`VolumeMultiplier`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `VolumeMultiplier` | `number` |

#### Returns

`void`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[SetVolumeMultiplier](ue_ue.SynthComponent.md#setvolumemultiplier)

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

[SynthComponent](ue_ue.SynthComponent.md).[SetWorldScale3D](ue_ue.SynthComponent.md#setworldscale3d)

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

[SynthComponent](ue_ue.SynthComponent.md).[SetupAttachment](ue_ue.SynthComponent.md#setupattachment)

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

[SynthComponent](ue_ue.SynthComponent.md).[SnapTo](ue_ue.SynthComponent.md#snapto)

___

### Start

▸ **Start**(): `void`

#### Returns

`void`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[Start](ue_ue.SynthComponent.md#start)

___

### Stop

▸ **Stop**(): `void`

#### Returns

`void`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[Stop](ue_ue.SynthComponent.md#stop)

___

### ToggleActive

▸ **ToggleActive**(): `void`

#### Returns

`void`

#### Inherited from

[SynthComponent](ue_ue.SynthComponent.md).[ToggleActive](ue_ue.SynthComponent.md#toggleactive)

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

[SynthComponent](ue_ue.SynthComponent.md).[ToggleVisibility](ue_ue.SynthComponent.md#togglevisibility)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`MediaSoundComponent`](ue_ue.MediaSoundComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`MediaSoundComponent`](ue_ue.MediaSoundComponent.md)

#### Overrides

[SynthComponent](ue_ue.SynthComponent.md).[Find](ue_ue.SynthComponent.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`MediaSoundComponent`](ue_ue.MediaSoundComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`MediaSoundComponent`](ue_ue.MediaSoundComponent.md)

#### Overrides

[SynthComponent](ue_ue.SynthComponent.md).[Load](ue_ue.SynthComponent.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[SynthComponent](ue_ue.SynthComponent.md).[StaticClass](ue_ue.SynthComponent.md#staticclass)
