[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / GameplayStatics

# Class: GameplayStatics

[ue/ue](../modules/ue_ue.md).GameplayStatics

## Hierarchy

- [`BlueprintFunctionLibrary`](ue_ue.BlueprintFunctionLibrary.md)

  ↳ **`GameplayStatics`**

## Table of contents

### Constructors

- [constructor](ue_ue.GameplayStatics.md#constructor)

### Properties

- [\_\_tid\_BlueprintFunctionLibrary\_\_](ue_ue.GameplayStatics.md#__tid_blueprintfunctionlibrary__)
- [\_\_tid\_GameplayStatics\_\_](ue_ue.GameplayStatics.md#__tid_gameplaystatics__)
- [\_\_tid\_Object\_\_](ue_ue.GameplayStatics.md#__tid_object__)

### Methods

- [CreateDefaultSubobject](ue_ue.GameplayStatics.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.GameplayStatics.md#executeubergraph)
- [GetClass](ue_ue.GameplayStatics.md#getclass)
- [GetName](ue_ue.GameplayStatics.md#getname)
- [GetOuter](ue_ue.GameplayStatics.md#getouter)
- [GetWorld](ue_ue.GameplayStatics.md#getworld)
- [ActivateReverbEffect](ue_ue.GameplayStatics.md#activatereverbeffect)
- [ApplyDamage](ue_ue.GameplayStatics.md#applydamage)
- [ApplyPointDamage](ue_ue.GameplayStatics.md#applypointdamage)
- [ApplyRadialDamage](ue_ue.GameplayStatics.md#applyradialdamage)
- [ApplyRadialDamageWithFalloff](ue_ue.GameplayStatics.md#applyradialdamagewithfalloff)
- [AreAnyListenersWithinRange](ue_ue.GameplayStatics.md#areanylistenerswithinrange)
- [AreSubtitlesEnabled](ue_ue.GameplayStatics.md#aresubtitlesenabled)
- [BeginDeferredActorSpawnFromClass](ue_ue.GameplayStatics.md#begindeferredactorspawnfromclass)
- [BeginSpawningActorFromBlueprint](ue_ue.GameplayStatics.md#beginspawningactorfromblueprint)
- [BeginSpawningActorFromClass](ue_ue.GameplayStatics.md#beginspawningactorfromclass)
- [BlueprintSuggestProjectileVelocity](ue_ue.GameplayStatics.md#blueprintsuggestprojectilevelocity)
- [Blueprint\_PredictProjectilePath\_Advanced](ue_ue.GameplayStatics.md#blueprint_predictprojectilepath_advanced)
- [Blueprint\_PredictProjectilePath\_ByObjectType](ue_ue.GameplayStatics.md#blueprint_predictprojectilepath_byobjecttype)
- [Blueprint\_PredictProjectilePath\_ByTraceChannel](ue_ue.GameplayStatics.md#blueprint_predictprojectilepath_bytracechannel)
- [BreakHitResult](ue_ue.GameplayStatics.md#breakhitresult)
- [CancelAsyncLoading](ue_ue.GameplayStatics.md#cancelasyncloading)
- [ClearSoundMixClassOverride](ue_ue.GameplayStatics.md#clearsoundmixclassoverride)
- [ClearSoundMixModifiers](ue_ue.GameplayStatics.md#clearsoundmixmodifiers)
- [CreatePlayer](ue_ue.GameplayStatics.md#createplayer)
- [CreateSaveGameObject](ue_ue.GameplayStatics.md#createsavegameobject)
- [CreateSound2D](ue_ue.GameplayStatics.md#createsound2d)
- [DeactivateReverbEffect](ue_ue.GameplayStatics.md#deactivatereverbeffect)
- [DeleteGameInSlot](ue_ue.GameplayStatics.md#deletegameinslot)
- [DeprojectScreenToWorld](ue_ue.GameplayStatics.md#deprojectscreentoworld)
- [DoesSaveGameExist](ue_ue.GameplayStatics.md#doessavegameexist)
- [EnableLiveStreaming](ue_ue.GameplayStatics.md#enablelivestreaming)
- [Find](ue_ue.GameplayStatics.md#find)
- [FindCollisionUV](ue_ue.GameplayStatics.md#findcollisionuv)
- [FinishSpawningActor](ue_ue.GameplayStatics.md#finishspawningactor)
- [FlushLevelStreaming](ue_ue.GameplayStatics.md#flushlevelstreaming)
- [GetAccurateRealTime](ue_ue.GameplayStatics.md#getaccuraterealtime)
- [GetActorArrayAverageLocation](ue_ue.GameplayStatics.md#getactorarrayaveragelocation)
- [GetActorArrayBounds](ue_ue.GameplayStatics.md#getactorarraybounds)
- [GetActorOfClass](ue_ue.GameplayStatics.md#getactorofclass)
- [GetAllActorsOfClass](ue_ue.GameplayStatics.md#getallactorsofclass)
- [GetAllActorsOfClassWithTag](ue_ue.GameplayStatics.md#getallactorsofclasswithtag)
- [GetAllActorsWithInterface](ue_ue.GameplayStatics.md#getallactorswithinterface)
- [GetAllActorsWithTag](ue_ue.GameplayStatics.md#getallactorswithtag)
- [GetAudioTimeSeconds](ue_ue.GameplayStatics.md#getaudiotimeseconds)
- [GetCurrentLevelName](ue_ue.GameplayStatics.md#getcurrentlevelname)
- [GetCurrentReverbEffect](ue_ue.GameplayStatics.md#getcurrentreverbeffect)
- [GetEnableWorldRendering](ue_ue.GameplayStatics.md#getenableworldrendering)
- [GetGameInstance](ue_ue.GameplayStatics.md#getgameinstance)
- [GetGameMode](ue_ue.GameplayStatics.md#getgamemode)
- [GetGameState](ue_ue.GameplayStatics.md#getgamestate)
- [GetGlobalTimeDilation](ue_ue.GameplayStatics.md#getglobaltimedilation)
- [GetIntOption](ue_ue.GameplayStatics.md#getintoption)
- [GetKeyValue](ue_ue.GameplayStatics.md#getkeyvalue)
- [GetMaxAudioChannelCount](ue_ue.GameplayStatics.md#getmaxaudiochannelcount)
- [GetObjectClass](ue_ue.GameplayStatics.md#getobjectclass)
- [GetPlatformName](ue_ue.GameplayStatics.md#getplatformname)
- [GetPlayerCameraManager](ue_ue.GameplayStatics.md#getplayercameramanager)
- [GetPlayerCharacter](ue_ue.GameplayStatics.md#getplayercharacter)
- [GetPlayerController](ue_ue.GameplayStatics.md#getplayercontroller)
- [GetPlayerControllerFromID](ue_ue.GameplayStatics.md#getplayercontrollerfromid)
- [GetPlayerControllerID](ue_ue.GameplayStatics.md#getplayercontrollerid)
- [GetPlayerPawn](ue_ue.GameplayStatics.md#getplayerpawn)
- [GetRealTimeSeconds](ue_ue.GameplayStatics.md#getrealtimeseconds)
- [GetStreamingLevel](ue_ue.GameplayStatics.md#getstreaminglevel)
- [GetSurfaceType](ue_ue.GameplayStatics.md#getsurfacetype)
- [GetTimeSeconds](ue_ue.GameplayStatics.md#gettimeseconds)
- [GetUnpausedTimeSeconds](ue_ue.GameplayStatics.md#getunpausedtimeseconds)
- [GetViewProjectionMatrix](ue_ue.GameplayStatics.md#getviewprojectionmatrix)
- [GetViewportMouseCaptureMode](ue_ue.GameplayStatics.md#getviewportmousecapturemode)
- [GetWorldDeltaSeconds](ue_ue.GameplayStatics.md#getworlddeltaseconds)
- [GetWorldOriginLocation](ue_ue.GameplayStatics.md#getworldoriginlocation)
- [GrassOverlappingSphereCount](ue_ue.GameplayStatics.md#grassoverlappingspherecount)
- [HasLaunchOption](ue_ue.GameplayStatics.md#haslaunchoption)
- [HasOption](ue_ue.GameplayStatics.md#hasoption)
- [IsGamePaused](ue_ue.GameplayStatics.md#isgamepaused)
- [IsSplitscreenForceDisabled](ue_ue.GameplayStatics.md#issplitscreenforcedisabled)
- [Load](ue_ue.GameplayStatics.md#load)
- [LoadGameFromSlot](ue_ue.GameplayStatics.md#loadgamefromslot)
- [LoadStreamLevel](ue_ue.GameplayStatics.md#loadstreamlevel)
- [MakeHitResult](ue_ue.GameplayStatics.md#makehitresult)
- [OpenLevel](ue_ue.GameplayStatics.md#openlevel)
- [ParseOption](ue_ue.GameplayStatics.md#parseoption)
- [PlayDialogue2D](ue_ue.GameplayStatics.md#playdialogue2d)
- [PlayDialogueAtLocation](ue_ue.GameplayStatics.md#playdialogueatlocation)
- [PlaySound2D](ue_ue.GameplayStatics.md#playsound2d)
- [PlaySoundAtLocation](ue_ue.GameplayStatics.md#playsoundatlocation)
- [PlayWorldCameraShake](ue_ue.GameplayStatics.md#playworldcamerashake)
- [PopSoundMixModifier](ue_ue.GameplayStatics.md#popsoundmixmodifier)
- [PrimeSound](ue_ue.GameplayStatics.md#primesound)
- [ProjectWorldToScreen](ue_ue.GameplayStatics.md#projectworldtoscreen)
- [PushSoundMixModifier](ue_ue.GameplayStatics.md#pushsoundmixmodifier)
- [RebaseLocalOriginOntoZero](ue_ue.GameplayStatics.md#rebaselocaloriginontozero)
- [RebaseZeroOriginOntoLocal](ue_ue.GameplayStatics.md#rebasezerooriginontolocal)
- [RemovePlayer](ue_ue.GameplayStatics.md#removeplayer)
- [SaveGameToSlot](ue_ue.GameplayStatics.md#savegametoslot)
- [SetBaseSoundMix](ue_ue.GameplayStatics.md#setbasesoundmix)
- [SetEnableWorldRendering](ue_ue.GameplayStatics.md#setenableworldrendering)
- [SetForceDisableSplitscreen](ue_ue.GameplayStatics.md#setforcedisablesplitscreen)
- [SetGamePaused](ue_ue.GameplayStatics.md#setgamepaused)
- [SetGlobalListenerFocusParameters](ue_ue.GameplayStatics.md#setgloballistenerfocusparameters)
- [SetGlobalPitchModulation](ue_ue.GameplayStatics.md#setglobalpitchmodulation)
- [SetGlobalTimeDilation](ue_ue.GameplayStatics.md#setglobaltimedilation)
- [SetMaxAudioChannelsScaled](ue_ue.GameplayStatics.md#setmaxaudiochannelsscaled)
- [SetPlayerControllerID](ue_ue.GameplayStatics.md#setplayercontrollerid)
- [SetSoundMixClassOverride](ue_ue.GameplayStatics.md#setsoundmixclassoverride)
- [SetSubtitlesEnabled](ue_ue.GameplayStatics.md#setsubtitlesenabled)
- [SetViewportMouseCaptureMode](ue_ue.GameplayStatics.md#setviewportmousecapturemode)
- [SetWorldOriginLocation](ue_ue.GameplayStatics.md#setworldoriginlocation)
- [SpawnDecalAtLocation](ue_ue.GameplayStatics.md#spawndecalatlocation)
- [SpawnDecalAttached](ue_ue.GameplayStatics.md#spawndecalattached)
- [SpawnDialogue2D](ue_ue.GameplayStatics.md#spawndialogue2d)
- [SpawnDialogueAtLocation](ue_ue.GameplayStatics.md#spawndialogueatlocation)
- [SpawnDialogueAttached](ue_ue.GameplayStatics.md#spawndialogueattached)
- [SpawnEmitterAtLocation](ue_ue.GameplayStatics.md#spawnemitteratlocation)
- [SpawnEmitterAttached](ue_ue.GameplayStatics.md#spawnemitterattached)
- [SpawnForceFeedbackAtLocation](ue_ue.GameplayStatics.md#spawnforcefeedbackatlocation)
- [SpawnForceFeedbackAttached](ue_ue.GameplayStatics.md#spawnforcefeedbackattached)
- [SpawnObject](ue_ue.GameplayStatics.md#spawnobject)
- [SpawnSound2D](ue_ue.GameplayStatics.md#spawnsound2d)
- [SpawnSoundAtLocation](ue_ue.GameplayStatics.md#spawnsoundatlocation)
- [SpawnSoundAttached](ue_ue.GameplayStatics.md#spawnsoundattached)
- [StaticClass](ue_ue.GameplayStatics.md#staticclass)
- [SuggestProjectileVelocity\_CustomArc](ue_ue.GameplayStatics.md#suggestprojectilevelocity_customarc)
- [UnloadStreamLevel](ue_ue.GameplayStatics.md#unloadstreamlevel)

## Constructors

### constructor

• **new GameplayStatics**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[constructor](ue_ue.BlueprintFunctionLibrary.md#constructor)

#### Defined in

[ue/ue.d.ts:36855](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36855)

## Properties

### \_\_tid\_BlueprintFunctionLibrary\_\_

• **\_\_tid\_BlueprintFunctionLibrary\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_BlueprintFunctionLibrary__](ue_ue.BlueprintFunctionLibrary.md#__tid_blueprintfunctionlibrary__)

#### Defined in

[ue/ue.d.ts:13418](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13418)

___

### \_\_tid\_GameplayStatics\_\_

• **\_\_tid\_GameplayStatics\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:36976](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36976)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[__tid_Object__](ue_ue.BlueprintFunctionLibrary.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

## Methods

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[CreateDefaultSubobject](ue_ue.BlueprintFunctionLibrary.md#createdefaultsubobject)

#### Defined in

[ue/ue.d.ts:11](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L11)

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

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[ExecuteUbergraph](ue_ue.BlueprintFunctionLibrary.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetClass](ue_ue.BlueprintFunctionLibrary.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetName](ue_ue.BlueprintFunctionLibrary.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetOuter](ue_ue.BlueprintFunctionLibrary.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[GetWorld](ue_ue.BlueprintFunctionLibrary.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### ActivateReverbEffect

▸ `Static` **ActivateReverbEffect**(`WorldContextObject`, `ReverbEffect`, `TagName`, `Priority?`, `Volume?`, `FadeTime?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ReverbEffect` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ReverbEffect`](ue_ue.ReverbEffect.md)\> |
| `TagName` | `string` |
| `Priority?` | `number` |
| `Volume?` | `number` |
| `FadeTime?` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36856](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36856)

___

### ApplyDamage

▸ `Static` **ApplyDamage**(`DamagedActor`, `BaseDamage`, `EventInstigator`, `DamageCauser`, `DamageTypeClass`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DamagedActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `BaseDamage` | `number` |
| `EventInstigator` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |
| `DamageCauser` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `DamageTypeClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:36857](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36857)

___

### ApplyPointDamage

▸ `Static` **ApplyPointDamage**(`DamagedActor`, `BaseDamage`, `HitFromDirection`, `HitInfo`, `EventInstigator`, `DamageCauser`, `DamageTypeClass`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DamagedActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `BaseDamage` | `number` |
| `HitFromDirection` | [`Vector`](ue_ue_s.Vector.md) |
| `HitInfo` | [`HitResult`](ue_ue.HitResult.md) |
| `EventInstigator` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Controller`](ue_ue.Controller.md)\> |
| `DamageCauser` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `DamageTypeClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:36858](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36858)

___

### ApplyRadialDamage

▸ `Static` **ApplyRadialDamage**(`WorldContextObject`, `BaseDamage`, `Origin`, `DamageRadius`, `DamageTypeClass`, `IgnoreActors`, `DamageCauser?`, `InstigatedByController?`, `bDoFullDamage?`, `DamagePreventionChannel?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `BaseDamage` | `number` |
| `Origin` | [`Vector`](ue_ue_s.Vector.md) |
| `DamageRadius` | `number` |
| `DamageTypeClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `IgnoreActors` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\> |
| `DamageCauser?` | [`Actor`](ue_ue.Actor.md) |
| `InstigatedByController?` | [`Controller`](ue_ue.Controller.md) |
| `bDoFullDamage?` | `boolean` |
| `DamagePreventionChannel?` | [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36859](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36859)

___

### ApplyRadialDamageWithFalloff

▸ `Static` **ApplyRadialDamageWithFalloff**(`WorldContextObject`, `BaseDamage`, `MinimumDamage`, `Origin`, `DamageInnerRadius`, `DamageOuterRadius`, `DamageFalloff`, `DamageTypeClass`, `IgnoreActors`, `DamageCauser?`, `InstigatedByController?`, `DamagePreventionChannel?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `BaseDamage` | `number` |
| `MinimumDamage` | `number` |
| `Origin` | [`Vector`](ue_ue_s.Vector.md) |
| `DamageInnerRadius` | `number` |
| `DamageOuterRadius` | `number` |
| `DamageFalloff` | `number` |
| `DamageTypeClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `IgnoreActors` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\> |
| `DamageCauser?` | [`Actor`](ue_ue.Actor.md) |
| `InstigatedByController?` | [`Controller`](ue_ue.Controller.md) |
| `DamagePreventionChannel?` | [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md) |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36860](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36860)

___

### AreAnyListenersWithinRange

▸ `Static` **AreAnyListenersWithinRange**(`WorldContextObject`, `Location`, `MaximumRange`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `MaximumRange` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36861](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36861)

___

### AreSubtitlesEnabled

▸ `Static` **AreSubtitlesEnabled**(): `boolean`

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36862](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36862)

___

### BeginDeferredActorSpawnFromClass

▸ `Static` **BeginDeferredActorSpawnFromClass**(`WorldContextObject`, `ActorClass`, `SpawnTransform`, `CollisionHandlingOverride?`, `Owner?`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ActorClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `SpawnTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `CollisionHandlingOverride?` | [`ESpawnActorCollisionHandlingMethod`](../enums/ue_ue.ESpawnActorCollisionHandlingMethod.md) |
| `Owner?` | [`Actor`](ue_ue.Actor.md) |

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:36863](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36863)

___

### BeginSpawningActorFromBlueprint

▸ `Static` **BeginSpawningActorFromBlueprint**(`WorldContextObject`, `Blueprint`, `SpawnTransform`, `bNoCollisionFail`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Blueprint` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Blueprint`](ue_ue.Blueprint.md)\> |
| `SpawnTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `bNoCollisionFail` | `boolean` |

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:36864](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36864)

___

### BeginSpawningActorFromClass

▸ `Static` **BeginSpawningActorFromClass**(`WorldContextObject`, `ActorClass`, `SpawnTransform`, `bNoCollisionFail?`, `Owner?`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ActorClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `SpawnTransform` | [`Transform`](ue_ue_s.Transform.md) |
| `bNoCollisionFail?` | `boolean` |
| `Owner?` | [`Actor`](ue_ue.Actor.md) |

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:36865](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36865)

___

### BlueprintSuggestProjectileVelocity

▸ `Static` **BlueprintSuggestProjectileVelocity**(`WorldContextObject`, `TossVelocity`, `StartLocation`, `EndLocation`, `LaunchSpeed`, `OverrideGravityZ`, `TraceOption`, `CollisionRadius`, `bFavorHighArc`, `bDrawDebug`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `TossVelocity` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `StartLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `EndLocation` | [`Vector`](ue_ue_s.Vector.md) |
| `LaunchSpeed` | `number` |
| `OverrideGravityZ` | `number` |
| `TraceOption` | [`ESuggestProjVelocityTraceOption`](../enums/ue_ue.ESuggestProjVelocityTraceOption.md) |
| `CollisionRadius` | `number` |
| `bFavorHighArc` | `boolean` |
| `bDrawDebug` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36869](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36869)

___

### Blueprint\_PredictProjectilePath\_Advanced

▸ `Static` **Blueprint_PredictProjectilePath_Advanced**(`WorldContextObject`, `PredictParams`, `PredictResult`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PredictParams` | [`PredictProjectilePathParams`](ue_ue.PredictProjectilePathParams.md) |
| `PredictResult` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PredictProjectilePathResult`](ue_ue.PredictProjectilePathResult.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36866](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36866)

___

### Blueprint\_PredictProjectilePath\_ByObjectType

▸ `Static` **Blueprint_PredictProjectilePath_ByObjectType**(`WorldContextObject`, `OutHit`, `OutPathPositions`, `OutLastTraceDestination`, `StartPos`, `LaunchVelocity`, `bTracePath`, `ProjectileRadius`, `ObjectTypes`, `bTraceComplex`, `ActorsToIgnore`, `DrawDebugType`, `DrawDebugTime`, `SimFrequency?`, `MaxSimTime?`, `OverrideGravityZ?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `OutHit` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `OutPathPositions` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |
| `OutLastTraceDestination` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `StartPos` | [`Vector`](ue_ue_s.Vector.md) |
| `LaunchVelocity` | [`Vector`](ue_ue_s.Vector.md) |
| `bTracePath` | `boolean` |
| `ProjectileRadius` | `number` |
| `ObjectTypes` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`EObjectTypeQuery`](../enums/ue_ue.EObjectTypeQuery.md)\> |
| `bTraceComplex` | `boolean` |
| `ActorsToIgnore` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\> |
| `DrawDebugType` | [`EDrawDebugTrace`](../enums/ue_ue.EDrawDebugTrace.md) |
| `DrawDebugTime` | `number` |
| `SimFrequency?` | `number` |
| `MaxSimTime?` | `number` |
| `OverrideGravityZ?` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36867](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36867)

___

### Blueprint\_PredictProjectilePath\_ByTraceChannel

▸ `Static` **Blueprint_PredictProjectilePath_ByTraceChannel**(`WorldContextObject`, `OutHit`, `OutPathPositions`, `OutLastTraceDestination`, `StartPos`, `LaunchVelocity`, `bTracePath`, `ProjectileRadius`, `TraceChannel`, `bTraceComplex`, `ActorsToIgnore`, `DrawDebugType`, `DrawDebugTime`, `SimFrequency?`, `MaxSimTime?`, `OverrideGravityZ?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `OutHit` | [`$Ref`](../interfaces/puerts._Ref.md)<[`HitResult`](ue_ue.HitResult.md)\> |
| `OutPathPositions` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Vector`](ue_ue_s.Vector.md)\>\> |
| `OutLastTraceDestination` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `StartPos` | [`Vector`](ue_ue_s.Vector.md) |
| `LaunchVelocity` | [`Vector`](ue_ue_s.Vector.md) |
| `bTracePath` | `boolean` |
| `ProjectileRadius` | `number` |
| `TraceChannel` | [`ECollisionChannel`](../enums/ue_ue.ECollisionChannel.md) |
| `bTraceComplex` | `boolean` |
| `ActorsToIgnore` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\> |
| `DrawDebugType` | [`EDrawDebugTrace`](../enums/ue_ue.EDrawDebugTrace.md) |
| `DrawDebugTime` | `number` |
| `SimFrequency?` | `number` |
| `MaxSimTime?` | `number` |
| `OverrideGravityZ?` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36868](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36868)

___

### BreakHitResult

▸ `Static` **BreakHitResult**(`Hit`, `bBlockingHit`, `bInitialOverlap`, `Time`, `Distance`, `Location`, `ImpactPoint`, `Normal`, `ImpactNormal`, `PhysMat`, `HitActor`, `HitComponent`, `HitBoneName`, `HitItem`, `FaceIndex`, `TraceStart`, `TraceEnd`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hit` | [`HitResult`](ue_ue.HitResult.md) |
| `bBlockingHit` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `bInitialOverlap` | [`$Ref`](../interfaces/puerts._Ref.md)<`boolean`\> |
| `Time` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `Distance` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `Location` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `ImpactPoint` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `Normal` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `ImpactNormal` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `PhysMat` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)\> |
| `HitActor` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Actor`](ue_ue.Actor.md)\> |
| `HitComponent` | [`$Ref`](../interfaces/puerts._Ref.md)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `HitBoneName` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `HitItem` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `FaceIndex` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `TraceStart` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `TraceEnd` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36870](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36870)

___

### CancelAsyncLoading

▸ `Static` **CancelAsyncLoading**(): `void`

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36871](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36871)

___

### ClearSoundMixClassOverride

▸ `Static` **ClearSoundMixClassOverride**(`WorldContextObject`, `InSoundMixModifier`, `InSoundClass`, `FadeOutTime?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `InSoundMixModifier` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundMix`](ue_ue.SoundMix.md)\> |
| `InSoundClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundClass`](ue_ue.SoundClass.md)\> |
| `FadeOutTime?` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36872](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36872)

___

### ClearSoundMixModifiers

▸ `Static` **ClearSoundMixModifiers**(`WorldContextObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36873](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36873)

___

### CreatePlayer

▸ `Static` **CreatePlayer**(`WorldContextObject`, `ControllerId?`, `bSpawnPlayerController?`): [`PlayerController`](ue_ue.PlayerController.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ControllerId?` | `number` |
| `bSpawnPlayerController?` | `boolean` |

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Defined in

[ue/ue.d.ts:36874](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36874)

___

### CreateSaveGameObject

▸ `Static` **CreateSaveGameObject**(`SaveGameClass`): [`SaveGame`](ue_ue.SaveGame.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SaveGameClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`SaveGame`](ue_ue.SaveGame.md)

#### Defined in

[ue/ue.d.ts:36875](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36875)

___

### CreateSound2D

▸ `Static` **CreateSound2D**(`WorldContextObject`, `Sound`, `VolumeMultiplier?`, `PitchMultiplier?`, `StartTime?`, `ConcurrencySettings?`, `bPersistAcrossLevelTransition?`, `bAutoDestroy?`): [`AudioComponent`](ue_ue.AudioComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Sound` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundBase`](ue_ue.SoundBase.md)\> |
| `VolumeMultiplier?` | `number` |
| `PitchMultiplier?` | `number` |
| `StartTime?` | `number` |
| `ConcurrencySettings?` | [`SoundConcurrency`](ue_ue.SoundConcurrency.md) |
| `bPersistAcrossLevelTransition?` | `boolean` |
| `bAutoDestroy?` | `boolean` |

#### Returns

[`AudioComponent`](ue_ue.AudioComponent.md)

#### Defined in

[ue/ue.d.ts:36876](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36876)

___

### DeactivateReverbEffect

▸ `Static` **DeactivateReverbEffect**(`WorldContextObject`, `TagName`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `TagName` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36877](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36877)

___

### DeleteGameInSlot

▸ `Static` **DeleteGameInSlot**(`SlotName`, `UserIndex`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SlotName` | `string` |
| `UserIndex` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36878](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36878)

___

### DeprojectScreenToWorld

▸ `Static` **DeprojectScreenToWorld**(`Player`, `ScreenPosition`, `WorldPosition`, `WorldDirection`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Player` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `ScreenPosition` | [`Vector2D`](ue_ue_s.Vector2D.md) |
| `WorldPosition` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `WorldDirection` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36879](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36879)

___

### DoesSaveGameExist

▸ `Static` **DoesSaveGameExist**(`SlotName`, `UserIndex`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SlotName` | `string` |
| `UserIndex` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36880](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36880)

___

### EnableLiveStreaming

▸ `Static` **EnableLiveStreaming**(`Enable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Enable` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36881](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36881)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`GameplayStatics`](ue_ue.GameplayStatics.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`GameplayStatics`](ue_ue.GameplayStatics.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Find](ue_ue.BlueprintFunctionLibrary.md#find)

#### Defined in

[ue/ue.d.ts:36973](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36973)

___

### FindCollisionUV

▸ `Static` **FindCollisionUV**(`Hit`, `UVChannel`, `UV`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hit` | [`HitResult`](ue_ue.HitResult.md) |
| `UVChannel` | `number` |
| `UV` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36882](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36882)

___

### FinishSpawningActor

▸ `Static` **FinishSpawningActor**(`Actor`, `SpawnTransform`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `SpawnTransform` | [`Transform`](ue_ue_s.Transform.md) |

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:36883](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36883)

___

### FlushLevelStreaming

▸ `Static` **FlushLevelStreaming**(`WorldContextObject`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36884](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36884)

___

### GetAccurateRealTime

▸ `Static` **GetAccurateRealTime**(`WorldContextObject`, `Seconds`, `PartialSeconds`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Seconds` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |
| `PartialSeconds` | [`$Ref`](../interfaces/puerts._Ref.md)<`number`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36885](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36885)

___

### GetActorArrayAverageLocation

▸ `Static` **GetActorArrayAverageLocation**(`Actors`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actors` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\> |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:36886](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36886)

___

### GetActorArrayBounds

▸ `Static` **GetActorArrayBounds**(`Actors`, `bOnlyCollidingComponents`, `Center`, `BoxExtent`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Actors` | [`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\> |
| `bOnlyCollidingComponents` | `boolean` |
| `Center` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `BoxExtent` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36887](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36887)

___

### GetActorOfClass

▸ `Static` **GetActorOfClass**(`WorldContextObject`, `ActorClass`): [`Actor`](ue_ue.Actor.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ActorClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

[`Actor`](ue_ue.Actor.md)

#### Defined in

[ue/ue.d.ts:36888](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36888)

___

### GetAllActorsOfClass

▸ `Static` **GetAllActorsOfClass**(`WorldContextObject`, `ActorClass`, `OutActors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ActorClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `OutActors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36889](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36889)

___

### GetAllActorsOfClassWithTag

▸ `Static` **GetAllActorsOfClassWithTag**(`WorldContextObject`, `ActorClass`, `Tag`, `OutActors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ActorClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `Tag` | `string` |
| `OutActors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36890](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36890)

___

### GetAllActorsWithInterface

▸ `Static` **GetAllActorsWithInterface**(`WorldContextObject`, `Interface`, `OutActors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Interface` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `OutActors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36891](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36891)

___

### GetAllActorsWithTag

▸ `Static` **GetAllActorsWithTag**(`WorldContextObject`, `Tag`, `OutActors`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Tag` | `string` |
| `OutActors` | [`$Ref`](../interfaces/puerts._Ref.md)<[`TArray`](../interfaces/ue_puerts.TArray.md)<[`Actor`](ue_ue.Actor.md)\>\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36892](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36892)

___

### GetAudioTimeSeconds

▸ `Static` **GetAudioTimeSeconds**(`WorldContextObject`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:36893](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36893)

___

### GetCurrentLevelName

▸ `Static` **GetCurrentLevelName**(`WorldContextObject`, `bRemovePrefixString?`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `bRemovePrefixString?` | `boolean` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:36894](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36894)

___

### GetCurrentReverbEffect

▸ `Static` **GetCurrentReverbEffect**(`WorldContextObject`): [`ReverbEffect`](ue_ue.ReverbEffect.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`ReverbEffect`](ue_ue.ReverbEffect.md)

#### Defined in

[ue/ue.d.ts:36895](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36895)

___

### GetEnableWorldRendering

▸ `Static` **GetEnableWorldRendering**(`WorldContextObject`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36896](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36896)

___

### GetGameInstance

▸ `Static` **GetGameInstance**(`WorldContextObject`): [`GameInstance`](ue_ue.GameInstance.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`GameInstance`](ue_ue.GameInstance.md)

#### Defined in

[ue/ue.d.ts:36897](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36897)

___

### GetGameMode

▸ `Static` **GetGameMode**(`WorldContextObject`): [`GameModeBase`](ue_ue.GameModeBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`GameModeBase`](ue_ue.GameModeBase.md)

#### Defined in

[ue/ue.d.ts:36898](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36898)

___

### GetGameState

▸ `Static` **GetGameState**(`WorldContextObject`): [`GameStateBase`](ue_ue.GameStateBase.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`GameStateBase`](ue_ue.GameStateBase.md)

#### Defined in

[ue/ue.d.ts:36899](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36899)

___

### GetGlobalTimeDilation

▸ `Static` **GetGlobalTimeDilation**(`WorldContextObject`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:36900](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36900)

___

### GetIntOption

▸ `Static` **GetIntOption**(`Options`, `Key`, `DefaultValue`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Options` | `string` |
| `Key` | `string` |
| `DefaultValue` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:36901](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36901)

___

### GetKeyValue

▸ `Static` **GetKeyValue**(`Pair`, `Key`, `Value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Pair` | `string` |
| `Key` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |
| `Value` | [`$Ref`](../interfaces/puerts._Ref.md)<`string`\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36902](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36902)

___

### GetMaxAudioChannelCount

▸ `Static` **GetMaxAudioChannelCount**(`WorldContextObject`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:36903](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36903)

___

### GetObjectClass

▸ `Static` **GetObjectClass**(`Object`): [`Class`](ue_ue.Class.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Object` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`Class`](ue_ue.Class.md)

#### Defined in

[ue/ue.d.ts:36904](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36904)

___

### GetPlatformName

▸ `Static` **GetPlatformName**(): `string`

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:36905](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36905)

___

### GetPlayerCameraManager

▸ `Static` **GetPlayerCameraManager**(`WorldContextObject`, `PlayerIndex`): [`PlayerCameraManager`](ue_ue.PlayerCameraManager.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PlayerIndex` | `number` |

#### Returns

[`PlayerCameraManager`](ue_ue.PlayerCameraManager.md)

#### Defined in

[ue/ue.d.ts:36906](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36906)

___

### GetPlayerCharacter

▸ `Static` **GetPlayerCharacter**(`WorldContextObject`, `PlayerIndex`): [`Character`](ue_ue.Character.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PlayerIndex` | `number` |

#### Returns

[`Character`](ue_ue.Character.md)

#### Defined in

[ue/ue.d.ts:36907](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36907)

___

### GetPlayerController

▸ `Static` **GetPlayerController**(`WorldContextObject`, `PlayerIndex`): [`PlayerController`](ue_ue.PlayerController.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PlayerIndex` | `number` |

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Defined in

[ue/ue.d.ts:36908](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36908)

___

### GetPlayerControllerFromID

▸ `Static` **GetPlayerControllerFromID**(`WorldContextObject`, `ControllerID`): [`PlayerController`](ue_ue.PlayerController.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ControllerID` | `number` |

#### Returns

[`PlayerController`](ue_ue.PlayerController.md)

#### Defined in

[ue/ue.d.ts:36909](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36909)

___

### GetPlayerControllerID

▸ `Static` **GetPlayerControllerID**(`Player`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Player` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:36910](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36910)

___

### GetPlayerPawn

▸ `Static` **GetPlayerPawn**(`WorldContextObject`, `PlayerIndex`): [`Pawn`](ue_ue.Pawn.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PlayerIndex` | `number` |

#### Returns

[`Pawn`](ue_ue.Pawn.md)

#### Defined in

[ue/ue.d.ts:36911](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36911)

___

### GetRealTimeSeconds

▸ `Static` **GetRealTimeSeconds**(`WorldContextObject`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:36912](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36912)

___

### GetStreamingLevel

▸ `Static` **GetStreamingLevel**(`WorldContextObject`, `PackageName`): [`LevelStreaming`](ue_ue.LevelStreaming.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PackageName` | `string` |

#### Returns

[`LevelStreaming`](ue_ue.LevelStreaming.md)

#### Defined in

[ue/ue.d.ts:36913](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36913)

___

### GetSurfaceType

▸ `Static` **GetSurfaceType**(`Hit`): [`EPhysicalSurface`](../enums/ue_ue.EPhysicalSurface.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Hit` | [`HitResult`](ue_ue.HitResult.md) |

#### Returns

[`EPhysicalSurface`](../enums/ue_ue.EPhysicalSurface.md)

#### Defined in

[ue/ue.d.ts:36914](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36914)

___

### GetTimeSeconds

▸ `Static` **GetTimeSeconds**(`WorldContextObject`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:36915](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36915)

___

### GetUnpausedTimeSeconds

▸ `Static` **GetUnpausedTimeSeconds**(`WorldContextObject`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:36916](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36916)

___

### GetViewProjectionMatrix

▸ `Static` **GetViewProjectionMatrix**(`DesiredView`, `ViewMatrix`, `ProjectionMatrix`, `ViewProjectionMatrix`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `DesiredView` | [`MinimalViewInfo`](ue_ue.MinimalViewInfo.md) |
| `ViewMatrix` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Matrix`](ue_ue.Matrix.md)\> |
| `ProjectionMatrix` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Matrix`](ue_ue.Matrix.md)\> |
| `ViewProjectionMatrix` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Matrix`](ue_ue.Matrix.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36918](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36918)

___

### GetViewportMouseCaptureMode

▸ `Static` **GetViewportMouseCaptureMode**(`WorldContextObject`): [`EMouseCaptureMode`](../enums/ue_ue.EMouseCaptureMode.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`EMouseCaptureMode`](../enums/ue_ue.EMouseCaptureMode.md)

#### Defined in

[ue/ue.d.ts:36917](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36917)

___

### GetWorldDeltaSeconds

▸ `Static` **GetWorldDeltaSeconds**(`WorldContextObject`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:36919](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36919)

___

### GetWorldOriginLocation

▸ `Static` **GetWorldOriginLocation**(`WorldContextObject`): [`IntVector`](ue_ue_s.IntVector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`IntVector`](ue_ue_s.IntVector.md)

#### Defined in

[ue/ue.d.ts:36920](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36920)

___

### GrassOverlappingSphereCount

▸ `Static` **GrassOverlappingSphereCount**(`WorldContextObject`, `StaticMesh`, `CenterPosition`, `Radius`): `number`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `StaticMesh` | [`$Nullable`](../modules/puerts.md#$nullable)<[`StaticMesh`](ue_ue.StaticMesh.md)\> |
| `CenterPosition` | [`Vector`](ue_ue_s.Vector.md) |
| `Radius` | `number` |

#### Returns

`number`

#### Defined in

[ue/ue.d.ts:36921](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36921)

___

### HasLaunchOption

▸ `Static` **HasLaunchOption**(`OptionToCheck`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `OptionToCheck` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36922](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36922)

___

### HasOption

▸ `Static` **HasOption**(`Options`, `InKey`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Options` | `string` |
| `InKey` | `string` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36923](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36923)

___

### IsGamePaused

▸ `Static` **IsGamePaused**(`WorldContextObject`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36924](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36924)

___

### IsSplitscreenForceDisabled

▸ `Static` **IsSplitscreenForceDisabled**(`WorldContextObject`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36925](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36925)

___

### Load

▸ `Static` **Load**(`InName`): [`GameplayStatics`](ue_ue.GameplayStatics.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`GameplayStatics`](ue_ue.GameplayStatics.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[Load](ue_ue.BlueprintFunctionLibrary.md#load)

#### Defined in

[ue/ue.d.ts:36974](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36974)

___

### LoadGameFromSlot

▸ `Static` **LoadGameFromSlot**(`SlotName`, `UserIndex`): [`SaveGame`](ue_ue.SaveGame.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `SlotName` | `string` |
| `UserIndex` | `number` |

#### Returns

[`SaveGame`](ue_ue.SaveGame.md)

#### Defined in

[ue/ue.d.ts:36926](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36926)

___

### LoadStreamLevel

▸ `Static` **LoadStreamLevel**(`WorldContextObject`, `LevelName`, `bMakeVisibleAfterLoad`, `bShouldBlockOnLoad`, `LatentInfo`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `LevelName` | `string` |
| `bMakeVisibleAfterLoad` | `boolean` |
| `bShouldBlockOnLoad` | `boolean` |
| `LatentInfo` | [`LatentActionInfo`](ue_ue.LatentActionInfo.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36927](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36927)

___

### MakeHitResult

▸ `Static` **MakeHitResult**(`bBlockingHit`, `bInitialOverlap`, `Time`, `Distance`, `Location`, `ImpactPoint`, `Normal`, `ImpactNormal`, `PhysMat`, `HitActor`, `HitComponent`, `HitBoneName`, `HitItem`, `FaceIndex`, `TraceStart`, `TraceEnd`): [`HitResult`](ue_ue.HitResult.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `bBlockingHit` | `boolean` |
| `bInitialOverlap` | `boolean` |
| `Time` | `number` |
| `Distance` | `number` |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `ImpactPoint` | [`Vector`](ue_ue_s.Vector.md) |
| `Normal` | [`Vector`](ue_ue_s.Vector.md) |
| `ImpactNormal` | [`Vector`](ue_ue_s.Vector.md) |
| `PhysMat` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PhysicalMaterial`](ue_ue.PhysicalMaterial.md)\> |
| `HitActor` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Actor`](ue_ue.Actor.md)\> |
| `HitComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PrimitiveComponent`](ue_ue.PrimitiveComponent.md)\> |
| `HitBoneName` | `string` |
| `HitItem` | `number` |
| `FaceIndex` | `number` |
| `TraceStart` | [`Vector`](ue_ue_s.Vector.md) |
| `TraceEnd` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`HitResult`](ue_ue.HitResult.md)

#### Defined in

[ue/ue.d.ts:36928](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36928)

___

### OpenLevel

▸ `Static` **OpenLevel**(`WorldContextObject`, `LevelName`, `bAbsolute?`, `Options?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `LevelName` | `string` |
| `bAbsolute?` | `boolean` |
| `Options?` | `string` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36929](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36929)

___

### ParseOption

▸ `Static` **ParseOption**(`Options`, `Key`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Options` | `string` |
| `Key` | `string` |

#### Returns

`string`

#### Defined in

[ue/ue.d.ts:36930](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36930)

___

### PlayDialogue2D

▸ `Static` **PlayDialogue2D**(`WorldContextObject`, `Dialogue`, `Context`, `VolumeMultiplier?`, `PitchMultiplier?`, `StartTime?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Dialogue` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DialogueWave`](ue_ue.DialogueWave.md)\> |
| `Context` | [`DialogueContext`](ue_ue.DialogueContext.md) |
| `VolumeMultiplier?` | `number` |
| `PitchMultiplier?` | `number` |
| `StartTime?` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36931](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36931)

___

### PlayDialogueAtLocation

▸ `Static` **PlayDialogueAtLocation**(`WorldContextObject`, `Dialogue`, `Context`, `Location`, `Rotation`, `VolumeMultiplier?`, `PitchMultiplier?`, `StartTime?`, `AttenuationSettings?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Dialogue` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DialogueWave`](ue_ue.DialogueWave.md)\> |
| `Context` | [`DialogueContext`](ue_ue.DialogueContext.md) |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `VolumeMultiplier?` | `number` |
| `PitchMultiplier?` | `number` |
| `StartTime?` | `number` |
| `AttenuationSettings?` | [`SoundAttenuation`](ue_ue.SoundAttenuation.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36932](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36932)

___

### PlaySound2D

▸ `Static` **PlaySound2D**(`WorldContextObject`, `Sound`, `VolumeMultiplier?`, `PitchMultiplier?`, `StartTime?`, `ConcurrencySettings?`, `OwningActor?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Sound` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundBase`](ue_ue.SoundBase.md)\> |
| `VolumeMultiplier?` | `number` |
| `PitchMultiplier?` | `number` |
| `StartTime?` | `number` |
| `ConcurrencySettings?` | [`SoundConcurrency`](ue_ue.SoundConcurrency.md) |
| `OwningActor?` | [`Actor`](ue_ue.Actor.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36933](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36933)

___

### PlaySoundAtLocation

▸ `Static` **PlaySoundAtLocation**(`WorldContextObject`, `Sound`, `Location`, `Rotation`, `VolumeMultiplier?`, `PitchMultiplier?`, `StartTime?`, `AttenuationSettings?`, `ConcurrencySettings?`, `OwningActor?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Sound` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundBase`](ue_ue.SoundBase.md)\> |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation` | [`Rotator`](ue_ue_s.Rotator.md) |
| `VolumeMultiplier?` | `number` |
| `PitchMultiplier?` | `number` |
| `StartTime?` | `number` |
| `AttenuationSettings?` | [`SoundAttenuation`](ue_ue.SoundAttenuation.md) |
| `ConcurrencySettings?` | [`SoundConcurrency`](ue_ue.SoundConcurrency.md) |
| `OwningActor?` | [`Actor`](ue_ue.Actor.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36934](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36934)

___

### PlayWorldCameraShake

▸ `Static` **PlayWorldCameraShake**(`WorldContextObject`, `Shake`, `Epicenter`, `InnerRadius`, `OuterRadius`, `Falloff?`, `bOrientShakeTowardsEpicenter?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Shake` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `Epicenter` | [`Vector`](ue_ue_s.Vector.md) |
| `InnerRadius` | `number` |
| `OuterRadius` | `number` |
| `Falloff?` | `number` |
| `bOrientShakeTowardsEpicenter?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36935](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36935)

___

### PopSoundMixModifier

▸ `Static` **PopSoundMixModifier**(`WorldContextObject`, `InSoundMixModifier`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `InSoundMixModifier` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundMix`](ue_ue.SoundMix.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36936](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36936)

___

### PrimeSound

▸ `Static` **PrimeSound**(`InSound`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `InSound` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundBase`](ue_ue.SoundBase.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36937](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36937)

___

### ProjectWorldToScreen

▸ `Static` **ProjectWorldToScreen**(`Player`, `WorldPosition`, `ScreenPosition`, `bPlayerViewportRelative?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Player` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `WorldPosition` | [`Vector`](ue_ue_s.Vector.md) |
| `ScreenPosition` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector2D`](ue_ue_s.Vector2D.md)\> |
| `bPlayerViewportRelative?` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36938](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36938)

___

### PushSoundMixModifier

▸ `Static` **PushSoundMixModifier**(`WorldContextObject`, `InSoundMixModifier`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `InSoundMixModifier` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundMix`](ue_ue.SoundMix.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36939](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36939)

___

### RebaseLocalOriginOntoZero

▸ `Static` **RebaseLocalOriginOntoZero**(`WorldContextObject`, `WorldLocation`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `WorldLocation` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:36940](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36940)

___

### RebaseZeroOriginOntoLocal

▸ `Static` **RebaseZeroOriginOntoLocal**(`WorldContextObject`, `WorldLocation`): [`Vector`](ue_ue_s.Vector.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `WorldLocation` | [`Vector`](ue_ue_s.Vector.md) |

#### Returns

[`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:36941](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36941)

___

### RemovePlayer

▸ `Static` **RemovePlayer**(`Player`, `bDestroyPawn`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Player` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `bDestroyPawn` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36942](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36942)

___

### SaveGameToSlot

▸ `Static` **SaveGameToSlot**(`SaveGameObject`, `SlotName`, `UserIndex`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `SaveGameObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SaveGame`](ue_ue.SaveGame.md)\> |
| `SlotName` | `string` |
| `UserIndex` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36943](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36943)

___

### SetBaseSoundMix

▸ `Static` **SetBaseSoundMix**(`WorldContextObject`, `InSoundMix`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `InSoundMix` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundMix`](ue_ue.SoundMix.md)\> |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36944](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36944)

___

### SetEnableWorldRendering

▸ `Static` **SetEnableWorldRendering**(`WorldContextObject`, `bEnable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `bEnable` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36945](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36945)

___

### SetForceDisableSplitscreen

▸ `Static` **SetForceDisableSplitscreen**(`WorldContextObject`, `bDisable`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `bDisable` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36946](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36946)

___

### SetGamePaused

▸ `Static` **SetGamePaused**(`WorldContextObject`, `bPaused`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `bPaused` | `boolean` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36947](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36947)

___

### SetGlobalListenerFocusParameters

▸ `Static` **SetGlobalListenerFocusParameters**(`WorldContextObject`, `FocusAzimuthScale?`, `NonFocusAzimuthScale?`, `FocusDistanceScale?`, `NonFocusDistanceScale?`, `FocusVolumeScale?`, `NonFocusVolumeScale?`, `FocusPriorityScale?`, `NonFocusPriorityScale?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `FocusAzimuthScale?` | `number` |
| `NonFocusAzimuthScale?` | `number` |
| `FocusDistanceScale?` | `number` |
| `NonFocusDistanceScale?` | `number` |
| `FocusVolumeScale?` | `number` |
| `NonFocusVolumeScale?` | `number` |
| `FocusPriorityScale?` | `number` |
| `NonFocusPriorityScale?` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36948](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36948)

___

### SetGlobalPitchModulation

▸ `Static` **SetGlobalPitchModulation**(`WorldContextObject`, `PitchModulation`, `TimeSec`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `PitchModulation` | `number` |
| `TimeSec` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36949](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36949)

___

### SetGlobalTimeDilation

▸ `Static` **SetGlobalTimeDilation**(`WorldContextObject`, `TimeDilation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `TimeDilation` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36950](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36950)

___

### SetMaxAudioChannelsScaled

▸ `Static` **SetMaxAudioChannelsScaled**(`WorldContextObject`, `MaxChannelCountScale`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `MaxChannelCountScale` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36951](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36951)

___

### SetPlayerControllerID

▸ `Static` **SetPlayerControllerID**(`Player`, `ControllerId`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `Player` | [`$Nullable`](../modules/puerts.md#$nullable)<[`PlayerController`](ue_ue.PlayerController.md)\> |
| `ControllerId` | `number` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36952](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36952)

___

### SetSoundMixClassOverride

▸ `Static` **SetSoundMixClassOverride**(`WorldContextObject`, `InSoundMixModifier`, `InSoundClass`, `Volume?`, `Pitch?`, `FadeInTime?`, `bApplyToChildren?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `InSoundMixModifier` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundMix`](ue_ue.SoundMix.md)\> |
| `InSoundClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundClass`](ue_ue.SoundClass.md)\> |
| `Volume?` | `number` |
| `Pitch?` | `number` |
| `FadeInTime?` | `number` |
| `bApplyToChildren?` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36953](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36953)

___

### SetSubtitlesEnabled

▸ `Static` **SetSubtitlesEnabled**(`bEnabled`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `bEnabled` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36954](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36954)

___

### SetViewportMouseCaptureMode

▸ `Static` **SetViewportMouseCaptureMode**(`WorldContextObject`, `MouseCaptureMode`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `MouseCaptureMode` | [`EMouseCaptureMode`](../enums/ue_ue.EMouseCaptureMode.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36955](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36955)

___

### SetWorldOriginLocation

▸ `Static` **SetWorldOriginLocation**(`WorldContextObject`, `NewLocation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `NewLocation` | [`IntVector`](ue_ue_s.IntVector.md) |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36956](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36956)

___

### SpawnDecalAtLocation

▸ `Static` **SpawnDecalAtLocation**(`WorldContextObject`, `DecalMaterial`, `DecalSize`, `Location`, `Rotation?`, `LifeSpan?`): [`DecalComponent`](ue_ue.DecalComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `DecalMaterial` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `DecalSize` | [`Vector`](ue_ue_s.Vector.md) |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation?` | [`Rotator`](ue_ue_s.Rotator.md) |
| `LifeSpan?` | `number` |

#### Returns

[`DecalComponent`](ue_ue.DecalComponent.md)

#### Defined in

[ue/ue.d.ts:36957](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36957)

___

### SpawnDecalAttached

▸ `Static` **SpawnDecalAttached**(`DecalMaterial`, `DecalSize`, `AttachToComponent`, `AttachPointName?`, `Location?`, `Rotation?`, `LocationType?`, `LifeSpan?`): [`DecalComponent`](ue_ue.DecalComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `DecalMaterial` | [`$Nullable`](../modules/puerts.md#$nullable)<[`MaterialInterface`](ue_ue.MaterialInterface.md)\> |
| `DecalSize` | [`Vector`](ue_ue_s.Vector.md) |
| `AttachToComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `AttachPointName?` | `string` |
| `Location?` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation?` | [`Rotator`](ue_ue_s.Rotator.md) |
| `LocationType?` | [`EAttachLocation`](../enums/ue_ue.EAttachLocation.md) |
| `LifeSpan?` | `number` |

#### Returns

[`DecalComponent`](ue_ue.DecalComponent.md)

#### Defined in

[ue/ue.d.ts:36958](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36958)

___

### SpawnDialogue2D

▸ `Static` **SpawnDialogue2D**(`WorldContextObject`, `Dialogue`, `Context`, `VolumeMultiplier?`, `PitchMultiplier?`, `StartTime?`, `bAutoDestroy?`): [`AudioComponent`](ue_ue.AudioComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Dialogue` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DialogueWave`](ue_ue.DialogueWave.md)\> |
| `Context` | [`DialogueContext`](ue_ue.DialogueContext.md) |
| `VolumeMultiplier?` | `number` |
| `PitchMultiplier?` | `number` |
| `StartTime?` | `number` |
| `bAutoDestroy?` | `boolean` |

#### Returns

[`AudioComponent`](ue_ue.AudioComponent.md)

#### Defined in

[ue/ue.d.ts:36959](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36959)

___

### SpawnDialogueAtLocation

▸ `Static` **SpawnDialogueAtLocation**(`WorldContextObject`, `Dialogue`, `Context`, `Location`, `Rotation?`, `VolumeMultiplier?`, `PitchMultiplier?`, `StartTime?`, `AttenuationSettings?`, `bAutoDestroy?`): [`AudioComponent`](ue_ue.AudioComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Dialogue` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DialogueWave`](ue_ue.DialogueWave.md)\> |
| `Context` | [`DialogueContext`](ue_ue.DialogueContext.md) |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation?` | [`Rotator`](ue_ue_s.Rotator.md) |
| `VolumeMultiplier?` | `number` |
| `PitchMultiplier?` | `number` |
| `StartTime?` | `number` |
| `AttenuationSettings?` | [`SoundAttenuation`](ue_ue.SoundAttenuation.md) |
| `bAutoDestroy?` | `boolean` |

#### Returns

[`AudioComponent`](ue_ue.AudioComponent.md)

#### Defined in

[ue/ue.d.ts:36960](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36960)

___

### SpawnDialogueAttached

▸ `Static` **SpawnDialogueAttached**(`Dialogue`, `Context`, `AttachToComponent`, `AttachPointName?`, `Location?`, `Rotation?`, `LocationType?`, `bStopWhenAttachedToDestroyed?`, `VolumeMultiplier?`, `PitchMultiplier?`, `StartTime?`, `AttenuationSettings?`, `bAutoDestroy?`): [`AudioComponent`](ue_ue.AudioComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Dialogue` | [`$Nullable`](../modules/puerts.md#$nullable)<[`DialogueWave`](ue_ue.DialogueWave.md)\> |
| `Context` | [`DialogueContext`](ue_ue.DialogueContext.md) |
| `AttachToComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `AttachPointName?` | `string` |
| `Location?` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation?` | [`Rotator`](ue_ue_s.Rotator.md) |
| `LocationType?` | [`EAttachLocation`](../enums/ue_ue.EAttachLocation.md) |
| `bStopWhenAttachedToDestroyed?` | `boolean` |
| `VolumeMultiplier?` | `number` |
| `PitchMultiplier?` | `number` |
| `StartTime?` | `number` |
| `AttenuationSettings?` | [`SoundAttenuation`](ue_ue.SoundAttenuation.md) |
| `bAutoDestroy?` | `boolean` |

#### Returns

[`AudioComponent`](ue_ue.AudioComponent.md)

#### Defined in

[ue/ue.d.ts:36961](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36961)

___

### SpawnEmitterAtLocation

▸ `Static` **SpawnEmitterAtLocation**(`WorldContextObject`, `EmitterTemplate`, `Location`, `Rotation?`, `Scale?`, `bAutoDestroy?`, `PoolingMethod?`, `bAutoActivateSystem?`): [`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `EmitterTemplate` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ParticleSystem`](ue_ue.ParticleSystem.md)\> |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation?` | [`Rotator`](ue_ue_s.Rotator.md) |
| `Scale?` | [`Vector`](ue_ue_s.Vector.md) |
| `bAutoDestroy?` | `boolean` |
| `PoolingMethod?` | [`EPSCPoolMethod`](../enums/ue_ue.EPSCPoolMethod.md) |
| `bAutoActivateSystem?` | `boolean` |

#### Returns

[`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)

#### Defined in

[ue/ue.d.ts:36962](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36962)

___

### SpawnEmitterAttached

▸ `Static` **SpawnEmitterAttached**(`EmitterTemplate`, `AttachToComponent`, `AttachPointName?`, `Location?`, `Rotation?`, `Scale?`, `LocationType?`, `bAutoDestroy?`, `PoolingMethod?`, `bAutoActivate?`): [`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `EmitterTemplate` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ParticleSystem`](ue_ue.ParticleSystem.md)\> |
| `AttachToComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `AttachPointName?` | `string` |
| `Location?` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation?` | [`Rotator`](ue_ue_s.Rotator.md) |
| `Scale?` | [`Vector`](ue_ue_s.Vector.md) |
| `LocationType?` | [`EAttachLocation`](../enums/ue_ue.EAttachLocation.md) |
| `bAutoDestroy?` | `boolean` |
| `PoolingMethod?` | [`EPSCPoolMethod`](../enums/ue_ue.EPSCPoolMethod.md) |
| `bAutoActivate?` | `boolean` |

#### Returns

[`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)

#### Defined in

[ue/ue.d.ts:36963](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36963)

___

### SpawnForceFeedbackAtLocation

▸ `Static` **SpawnForceFeedbackAtLocation**(`WorldContextObject`, `ForceFeedbackEffect`, `Location`, `Rotation?`, `bLooping?`, `IntensityMultiplier?`, `StartTime?`, `AttenuationSettings?`, `bAutoDestroy?`): [`ForceFeedbackComponent`](ue_ue.ForceFeedbackComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `ForceFeedbackEffect` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ForceFeedbackEffect`](ue_ue.ForceFeedbackEffect.md)\> |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation?` | [`Rotator`](ue_ue_s.Rotator.md) |
| `bLooping?` | `boolean` |
| `IntensityMultiplier?` | `number` |
| `StartTime?` | `number` |
| `AttenuationSettings?` | [`ForceFeedbackAttenuation`](ue_ue.ForceFeedbackAttenuation.md) |
| `bAutoDestroy?` | `boolean` |

#### Returns

[`ForceFeedbackComponent`](ue_ue.ForceFeedbackComponent.md)

#### Defined in

[ue/ue.d.ts:36964](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36964)

___

### SpawnForceFeedbackAttached

▸ `Static` **SpawnForceFeedbackAttached**(`ForceFeedbackEffect`, `AttachToComponent`, `AttachPointName?`, `Location?`, `Rotation?`, `LocationType?`, `bStopWhenAttachedToDestroyed?`, `bLooping?`, `IntensityMultiplier?`, `StartTime?`, `AttenuationSettings?`, `bAutoDestroy?`): [`ForceFeedbackComponent`](ue_ue.ForceFeedbackComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ForceFeedbackEffect` | [`$Nullable`](../modules/puerts.md#$nullable)<[`ForceFeedbackEffect`](ue_ue.ForceFeedbackEffect.md)\> |
| `AttachToComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `AttachPointName?` | `string` |
| `Location?` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation?` | [`Rotator`](ue_ue_s.Rotator.md) |
| `LocationType?` | [`EAttachLocation`](../enums/ue_ue.EAttachLocation.md) |
| `bStopWhenAttachedToDestroyed?` | `boolean` |
| `bLooping?` | `boolean` |
| `IntensityMultiplier?` | `number` |
| `StartTime?` | `number` |
| `AttenuationSettings?` | [`ForceFeedbackAttenuation`](ue_ue.ForceFeedbackAttenuation.md) |
| `bAutoDestroy?` | `boolean` |

#### Returns

[`ForceFeedbackComponent`](ue_ue.ForceFeedbackComponent.md)

#### Defined in

[ue/ue.d.ts:36965](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36965)

___

### SpawnObject

▸ `Static` **SpawnObject**(`ObjectClass`, `Outer`): [`Object`](ue_ue.Object.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `ObjectClass` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |
| `Outer` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |

#### Returns

[`Object`](ue_ue.Object.md)

#### Defined in

[ue/ue.d.ts:36966](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36966)

___

### SpawnSound2D

▸ `Static` **SpawnSound2D**(`WorldContextObject`, `Sound`, `VolumeMultiplier?`, `PitchMultiplier?`, `StartTime?`, `ConcurrencySettings?`, `bPersistAcrossLevelTransition?`, `bAutoDestroy?`): [`AudioComponent`](ue_ue.AudioComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Sound` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundBase`](ue_ue.SoundBase.md)\> |
| `VolumeMultiplier?` | `number` |
| `PitchMultiplier?` | `number` |
| `StartTime?` | `number` |
| `ConcurrencySettings?` | [`SoundConcurrency`](ue_ue.SoundConcurrency.md) |
| `bPersistAcrossLevelTransition?` | `boolean` |
| `bAutoDestroy?` | `boolean` |

#### Returns

[`AudioComponent`](ue_ue.AudioComponent.md)

#### Defined in

[ue/ue.d.ts:36967](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36967)

___

### SpawnSoundAtLocation

▸ `Static` **SpawnSoundAtLocation**(`WorldContextObject`, `Sound`, `Location`, `Rotation?`, `VolumeMultiplier?`, `PitchMultiplier?`, `StartTime?`, `AttenuationSettings?`, `ConcurrencySettings?`, `bAutoDestroy?`): [`AudioComponent`](ue_ue.AudioComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `Sound` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundBase`](ue_ue.SoundBase.md)\> |
| `Location` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation?` | [`Rotator`](ue_ue_s.Rotator.md) |
| `VolumeMultiplier?` | `number` |
| `PitchMultiplier?` | `number` |
| `StartTime?` | `number` |
| `AttenuationSettings?` | [`SoundAttenuation`](ue_ue.SoundAttenuation.md) |
| `ConcurrencySettings?` | [`SoundConcurrency`](ue_ue.SoundConcurrency.md) |
| `bAutoDestroy?` | `boolean` |

#### Returns

[`AudioComponent`](ue_ue.AudioComponent.md)

#### Defined in

[ue/ue.d.ts:36968](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36968)

___

### SpawnSoundAttached

▸ `Static` **SpawnSoundAttached**(`Sound`, `AttachToComponent`, `AttachPointName?`, `Location?`, `Rotation?`, `LocationType?`, `bStopWhenAttachedToDestroyed?`, `VolumeMultiplier?`, `PitchMultiplier?`, `StartTime?`, `AttenuationSettings?`, `ConcurrencySettings?`, `bAutoDestroy?`): [`AudioComponent`](ue_ue.AudioComponent.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Sound` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SoundBase`](ue_ue.SoundBase.md)\> |
| `AttachToComponent` | [`$Nullable`](../modules/puerts.md#$nullable)<[`SceneComponent`](ue_ue.SceneComponent.md)\> |
| `AttachPointName?` | `string` |
| `Location?` | [`Vector`](ue_ue_s.Vector.md) |
| `Rotation?` | [`Rotator`](ue_ue_s.Rotator.md) |
| `LocationType?` | [`EAttachLocation`](../enums/ue_ue.EAttachLocation.md) |
| `bStopWhenAttachedToDestroyed?` | `boolean` |
| `VolumeMultiplier?` | `number` |
| `PitchMultiplier?` | `number` |
| `StartTime?` | `number` |
| `AttenuationSettings?` | [`SoundAttenuation`](ue_ue.SoundAttenuation.md) |
| `ConcurrencySettings?` | [`SoundConcurrency`](ue_ue.SoundConcurrency.md) |
| `bAutoDestroy?` | `boolean` |

#### Returns

[`AudioComponent`](ue_ue.AudioComponent.md)

#### Defined in

[ue/ue.d.ts:36969](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36969)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[BlueprintFunctionLibrary](ue_ue.BlueprintFunctionLibrary.md).[StaticClass](ue_ue.BlueprintFunctionLibrary.md#staticclass)

#### Defined in

[ue/ue.d.ts:36972](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36972)

___

### SuggestProjectileVelocity\_CustomArc

▸ `Static` **SuggestProjectileVelocity_CustomArc**(`WorldContextObject`, `OutLaunchVelocity`, `StartPos`, `EndPos`, `OverrideGravityZ?`, `ArcParam?`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `OutLaunchVelocity` | [`$Ref`](../interfaces/puerts._Ref.md)<[`Vector`](ue_ue_s.Vector.md)\> |
| `StartPos` | [`Vector`](ue_ue_s.Vector.md) |
| `EndPos` | [`Vector`](ue_ue_s.Vector.md) |
| `OverrideGravityZ?` | `number` |
| `ArcParam?` | `number` |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:36970](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36970)

___

### UnloadStreamLevel

▸ `Static` **UnloadStreamLevel**(`WorldContextObject`, `LevelName`, `LatentInfo`, `bShouldBlockOnUnload`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `WorldContextObject` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Object`](ue_ue.Object.md)\> |
| `LevelName` | `string` |
| `LatentInfo` | [`LatentActionInfo`](ue_ue.LatentActionInfo.md) |
| `bShouldBlockOnUnload` | `boolean` |

#### Returns

`void`

#### Defined in

[ue/ue.d.ts:36971](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L36971)
