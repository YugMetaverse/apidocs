[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleSystem

# Class: ParticleSystem

[ue/ue](../modules/ue_ue.md).ParticleSystem

## Hierarchy

- [`FXSystemAsset`](ue_ue.FXSystemAsset.md)

  ↳ **`ParticleSystem`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleSystem.md#constructor)

### Properties

- [BackgroundColor](ue_ue.ParticleSystem.md#backgroundcolor)
- [CurveEdSetup](ue_ue.ParticleSystem.md#curveedsetup)
- [CustomOcclusionBounds](ue_ue.ParticleSystem.md#customocclusionbounds)
- [Delay](ue_ue.ParticleSystem.md#delay)
- [DelayLow](ue_ue.ParticleSystem.md#delaylow)
- [EditorLODSetting](ue_ue.ParticleSystem.md#editorlodsetting)
- [Emitters](ue_ue.ParticleSystem.md#emitters)
- [FixedRelativeBoundingBox](ue_ue.ParticleSystem.md#fixedrelativeboundingbox)
- [FloorMesh](ue_ue.ParticleSystem.md#floormesh)
- [FloorPosition](ue_ue.ParticleSystem.md#floorposition)
- [FloorRotation](ue_ue.ParticleSystem.md#floorrotation)
- [FloorScale](ue_ue.ParticleSystem.md#floorscale)
- [FloorScale3D](ue_ue.ParticleSystem.md#floorscale3d)
- [InsignificanceDelay](ue_ue.ParticleSystem.md#insignificancedelay)
- [InsignificantReaction](ue_ue.ParticleSystem.md#insignificantreaction)
- [LODDistanceCheckTime](ue_ue.ParticleSystem.md#loddistancechecktime)
- [LODDistances](ue_ue.ParticleSystem.md#loddistances)
- [LODMethod](ue_ue.ParticleSystem.md#lodmethod)
- [LODSettings](ue_ue.ParticleSystem.md#lodsettings)
- [MacroUVPosition](ue_ue.ParticleSystem.md#macrouvposition)
- [MacroUVRadius](ue_ue.ParticleSystem.md#macrouvradius)
- [MaxPoolSize](ue_ue.ParticleSystem.md#maxpoolsize)
- [MaxSignificanceLevel](ue_ue.ParticleSystem.md#maxsignificancelevel)
- [MinTimeBetweenTicks](ue_ue.ParticleSystem.md#mintimebetweenticks)
- [NamedMaterialSlots](ue_ue.ParticleSystem.md#namedmaterialslots)
- [OcclusionBoundsMethod](ue_ue.ParticleSystem.md#occlusionboundsmethod)
- [PreviewComponent](ue_ue.ParticleSystem.md#previewcomponent)
- [SecondsBeforeInactive](ue_ue.ParticleSystem.md#secondsbeforeinactive)
- [SoloTracking](ue_ue.ParticleSystem.md#solotracking)
- [SystemUpdateMode](ue_ue.ParticleSystem.md#systemupdatemode)
- [ThumbnailAngle](ue_ue.ParticleSystem.md#thumbnailangle)
- [ThumbnailDistance](ue_ue.ParticleSystem.md#thumbnaildistance)
- [ThumbnailImage](ue_ue.ParticleSystem.md#thumbnailimage)
- [ThumbnailImageOutOfDate](ue_ue.ParticleSystem.md#thumbnailimageoutofdate)
- [ThumbnailWarmup](ue_ue.ParticleSystem.md#thumbnailwarmup)
- [UpdateTime\_Delta](ue_ue.ParticleSystem.md#updatetime_delta)
- [UpdateTime\_FPS](ue_ue.ParticleSystem.md#updatetime_fps)
- [WarmupTickRate](ue_ue.ParticleSystem.md#warmuptickrate)
- [WarmupTime](ue_ue.ParticleSystem.md#warmuptime)
- [\_\_tid\_FXSystemAsset\_\_](ue_ue.ParticleSystem.md#__tid_fxsystemasset__)
- [\_\_tid\_Object\_\_](ue_ue.ParticleSystem.md#__tid_object__)
- [\_\_tid\_ParticleSystem\_\_](ue_ue.ParticleSystem.md#__tid_particlesystem__)
- [bAllowManagedTicking](ue_ue.ParticleSystem.md#ballowmanagedticking)
- [bAutoDeactivate](ue_ue.ParticleSystem.md#bautodeactivate)
- [bHasPhysics](ue_ue.ParticleSystem.md#bhasphysics)
- [bOrientZAxisTowardCamera](ue_ue.ParticleSystem.md#borientzaxistowardcamera)
- [bRegenerateLODDuplicate](ue_ue.ParticleSystem.md#bregeneratelodduplicate)
- [bShouldResetPeakCounts](ue_ue.ParticleSystem.md#bshouldresetpeakcounts)
- [bUseDelayRange](ue_ue.ParticleSystem.md#busedelayrange)
- [bUseFixedRelativeBoundingBox](ue_ue.ParticleSystem.md#busefixedrelativeboundingbox)
- [bUseRealtimeThumbnail](ue_ue.ParticleSystem.md#buserealtimethumbnail)

### Methods

- [ContainsEmitterType](ue_ue.ParticleSystem.md#containsemittertype)
- [CreateDefaultSubobject](ue_ue.ParticleSystem.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleSystem.md#executeubergraph)
- [GetClass](ue_ue.ParticleSystem.md#getclass)
- [GetName](ue_ue.ParticleSystem.md#getname)
- [GetOuter](ue_ue.ParticleSystem.md#getouter)
- [GetWorld](ue_ue.ParticleSystem.md#getworld)
- [Find](ue_ue.ParticleSystem.md#find)
- [Load](ue_ue.ParticleSystem.md#load)
- [StaticClass](ue_ue.ParticleSystem.md#staticclass)

## Constructors

### constructor

• **new ParticleSystem**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[FXSystemAsset](ue_ue.FXSystemAsset.md).[constructor](ue_ue.FXSystemAsset.md#constructor)

## Properties

### BackgroundColor

• **BackgroundColor**: [`Color`](ue_ue_s.Color.md)

___

### CurveEdSetup

• **CurveEdSetup**: [`InterpCurveEdSetup`](ue_ue.InterpCurveEdSetup.md)

___

### CustomOcclusionBounds

• **CustomOcclusionBounds**: [`Box`](ue_ue.Box.md)

___

### Delay

• **Delay**: `number`

___

### DelayLow

• **DelayLow**: `number`

___

### EditorLODSetting

• **EditorLODSetting**: `number`

___

### Emitters

• **Emitters**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleEmitter`](ue_ue.ParticleEmitter.md)\>

___

### FixedRelativeBoundingBox

• **FixedRelativeBoundingBox**: [`Box`](ue_ue.Box.md)

___

### FloorMesh

• **FloorMesh**: `string`

___

### FloorPosition

• **FloorPosition**: [`Vector`](ue_ue_s.Vector.md)

___

### FloorRotation

• **FloorRotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### FloorScale

• **FloorScale**: `number`

___

### FloorScale3D

• **FloorScale3D**: [`Vector`](ue_ue_s.Vector.md)

___

### InsignificanceDelay

• **InsignificanceDelay**: `number`

___

### InsignificantReaction

• **InsignificantReaction**: [`EParticleSystemInsignificanceReaction`](../enums/ue_ue.EParticleSystemInsignificanceReaction.md)

___

### LODDistanceCheckTime

• **LODDistanceCheckTime**: `number`

___

### LODDistances

• **LODDistances**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

___

### LODMethod

• **LODMethod**: [`ParticleSystemLODMethod`](../enums/ue_ue.ParticleSystemLODMethod.md)

___

### LODSettings

• **LODSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleSystemLOD`](ue_ue.ParticleSystemLOD.md)\>

___

### MacroUVPosition

• **MacroUVPosition**: [`Vector`](ue_ue_s.Vector.md)

___

### MacroUVRadius

• **MacroUVRadius**: `number`

___

### MaxPoolSize

• **MaxPoolSize**: `number`

#### Inherited from

[FXSystemAsset](ue_ue.FXSystemAsset.md).[MaxPoolSize](ue_ue.FXSystemAsset.md#maxpoolsize)

___

### MaxSignificanceLevel

• **MaxSignificanceLevel**: [`EParticleSignificanceLevel`](../enums/ue_ue.EParticleSignificanceLevel.md)

___

### MinTimeBetweenTicks

• **MinTimeBetweenTicks**: `number`

___

### NamedMaterialSlots

• **NamedMaterialSlots**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NamedEmitterMaterial`](ue_ue.NamedEmitterMaterial.md)\>

___

### OcclusionBoundsMethod

• **OcclusionBoundsMethod**: [`EParticleSystemOcclusionBoundsMethod`](../enums/ue_ue.EParticleSystemOcclusionBoundsMethod.md)

___

### PreviewComponent

• **PreviewComponent**: [`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)

___

### SecondsBeforeInactive

• **SecondsBeforeInactive**: `number`

___

### SoloTracking

• **SoloTracking**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LODSoloTrack`](ue_ue.LODSoloTrack.md)\>

___

### SystemUpdateMode

• **SystemUpdateMode**: [`EParticleSystemUpdateMode`](../enums/ue_ue.EParticleSystemUpdateMode.md)

___

### ThumbnailAngle

• **ThumbnailAngle**: [`Rotator`](ue_ue_s.Rotator.md)

___

### ThumbnailDistance

• **ThumbnailDistance**: `number`

___

### ThumbnailImage

• **ThumbnailImage**: [`Texture2D`](ue_ue.Texture2D.md)

___

### ThumbnailImageOutOfDate

• **ThumbnailImageOutOfDate**: `boolean`

___

### ThumbnailWarmup

• **ThumbnailWarmup**: `number`

___

### UpdateTime\_Delta

• **UpdateTime\_Delta**: `number`

___

### UpdateTime\_FPS

• **UpdateTime\_FPS**: `number`

___

### WarmupTickRate

• **WarmupTickRate**: `number`

___

### WarmupTime

• **WarmupTime**: `number`

___

### \_\_tid\_FXSystemAsset\_\_

• **\_\_tid\_FXSystemAsset\_\_**: `boolean`

#### Inherited from

[FXSystemAsset](ue_ue.FXSystemAsset.md).[__tid_FXSystemAsset__](ue_ue.FXSystemAsset.md#__tid_fxsystemasset__)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FXSystemAsset](ue_ue.FXSystemAsset.md).[__tid_Object__](ue_ue.FXSystemAsset.md#__tid_object__)

___

### \_\_tid\_ParticleSystem\_\_

• **\_\_tid\_ParticleSystem\_\_**: `boolean`

___

### bAllowManagedTicking

• **bAllowManagedTicking**: `boolean`

___

### bAutoDeactivate

• **bAutoDeactivate**: `boolean`

___

### bHasPhysics

• **bHasPhysics**: `boolean`

___

### bOrientZAxisTowardCamera

• **bOrientZAxisTowardCamera**: `boolean`

___

### bRegenerateLODDuplicate

• **bRegenerateLODDuplicate**: `boolean`

___

### bShouldResetPeakCounts

• **bShouldResetPeakCounts**: `boolean`

___

### bUseDelayRange

• **bUseDelayRange**: `boolean`

___

### bUseFixedRelativeBoundingBox

• **bUseFixedRelativeBoundingBox**: `boolean`

___

### bUseRealtimeThumbnail

• **bUseRealtimeThumbnail**: `boolean`

## Methods

### ContainsEmitterType

▸ **ContainsEmitterType**(`TypeData`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TypeData` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`boolean`

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

[FXSystemAsset](ue_ue.FXSystemAsset.md).[CreateDefaultSubobject](ue_ue.FXSystemAsset.md#createdefaultsubobject)

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

[FXSystemAsset](ue_ue.FXSystemAsset.md).[ExecuteUbergraph](ue_ue.FXSystemAsset.md#executeubergraph)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FXSystemAsset](ue_ue.FXSystemAsset.md).[GetClass](ue_ue.FXSystemAsset.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FXSystemAsset](ue_ue.FXSystemAsset.md).[GetName](ue_ue.FXSystemAsset.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FXSystemAsset](ue_ue.FXSystemAsset.md).[GetOuter](ue_ue.FXSystemAsset.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FXSystemAsset](ue_ue.FXSystemAsset.md).[GetWorld](ue_ue.FXSystemAsset.md#getworld)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleSystem`](ue_ue.ParticleSystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleSystem`](ue_ue.ParticleSystem.md)

#### Overrides

[FXSystemAsset](ue_ue.FXSystemAsset.md).[Find](ue_ue.FXSystemAsset.md#find)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleSystem`](ue_ue.ParticleSystem.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleSystem`](ue_ue.ParticleSystem.md)

#### Overrides

[FXSystemAsset](ue_ue.FXSystemAsset.md).[Load](ue_ue.FXSystemAsset.md#load)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FXSystemAsset](ue_ue.FXSystemAsset.md).[StaticClass](ue_ue.FXSystemAsset.md#staticclass)
