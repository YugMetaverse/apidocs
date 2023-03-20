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

#### Defined in

[ue/ue.d.ts:7201](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7201)

## Properties

### BackgroundColor

• **BackgroundColor**: [`Color`](ue_ue_s.Color.md)

#### Defined in

[ue/ue.d.ts:7224](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7224)

___

### CurveEdSetup

• **CurveEdSetup**: [`InterpCurveEdSetup`](ue_ue.InterpCurveEdSetup.md)

#### Defined in

[ue/ue.d.ts:7211](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7211)

___

### CustomOcclusionBounds

• **CustomOcclusionBounds**: [`Box`](ue_ue.Box.md)

#### Defined in

[ue/ue.d.ts:7246](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7246)

___

### Delay

• **Delay**: `number`

#### Defined in

[ue/ue.d.ts:7225](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7225)

___

### DelayLow

• **DelayLow**: `number`

#### Defined in

[ue/ue.d.ts:7226](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7226)

___

### EditorLODSetting

• **EditorLODSetting**: `number`

#### Defined in

[ue/ue.d.ts:7215](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7215)

___

### Emitters

• **Emitters**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleEmitter`](ue_ue.ParticleEmitter.md)\>

#### Defined in

[ue/ue.d.ts:7206](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7206)

___

### FixedRelativeBoundingBox

• **FixedRelativeBoundingBox**: [`Box`](ue_ue.Box.md)

#### Defined in

[ue/ue.d.ts:7217](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7217)

___

### FloorMesh

• **FloorMesh**: `string`

#### Defined in

[ue/ue.d.ts:7219](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7219)

___

### FloorPosition

• **FloorPosition**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:7220](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7220)

___

### FloorRotation

• **FloorRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:7221](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7221)

___

### FloorScale

• **FloorScale**: `number`

#### Defined in

[ue/ue.d.ts:7222](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7222)

___

### FloorScale3D

• **FloorScale3D**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:7223](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7223)

___

### InsignificanceDelay

• **InsignificanceDelay**: `number`

#### Defined in

[ue/ue.d.ts:7244](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7244)

___

### InsignificantReaction

• **InsignificantReaction**: [`EParticleSystemInsignificanceReaction`](../enums/ue_ue.EParticleSystemInsignificanceReaction.md)

#### Defined in

[ue/ue.d.ts:7240](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7240)

___

### LODDistanceCheckTime

• **LODDistanceCheckTime**: `number`

#### Defined in

[ue/ue.d.ts:7212](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7212)

___

### LODDistances

• **LODDistances**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`number`\>

#### Defined in

[ue/ue.d.ts:7214](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7214)

___

### LODMethod

• **LODMethod**: [`ParticleSystemLODMethod`](../enums/ue_ue.ParticleSystemLODMethod.md)

#### Defined in

[ue/ue.d.ts:7239](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7239)

___

### LODSettings

• **LODSettings**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleSystemLOD`](ue_ue.ParticleSystemLOD.md)\>

#### Defined in

[ue/ue.d.ts:7216](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7216)

___

### MacroUVPosition

• **MacroUVPosition**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:7245](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7245)

___

### MacroUVRadius

• **MacroUVRadius**: `number`

#### Defined in

[ue/ue.d.ts:7213](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7213)

___

### MaxPoolSize

• **MaxPoolSize**: `number`

#### Inherited from

[FXSystemAsset](ue_ue.FXSystemAsset.md).[MaxPoolSize](ue_ue.FXSystemAsset.md#maxpoolsize)

#### Defined in

[ue/ue.d.ts:6705](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6705)

___

### MaxSignificanceLevel

• **MaxSignificanceLevel**: [`EParticleSignificanceLevel`](../enums/ue_ue.EParticleSignificanceLevel.md)

#### Defined in

[ue/ue.d.ts:7242](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7242)

___

### MinTimeBetweenTicks

• **MinTimeBetweenTicks**: `number`

#### Defined in

[ue/ue.d.ts:7243](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7243)

___

### NamedMaterialSlots

• **NamedMaterialSlots**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`NamedEmitterMaterial`](ue_ue.NamedEmitterMaterial.md)\>

#### Defined in

[ue/ue.d.ts:7248](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7248)

___

### OcclusionBoundsMethod

• **OcclusionBoundsMethod**: [`EParticleSystemOcclusionBoundsMethod`](../enums/ue_ue.EParticleSystemOcclusionBoundsMethod.md)

#### Defined in

[ue/ue.d.ts:7241](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7241)

___

### PreviewComponent

• **PreviewComponent**: [`ParticleSystemComponent`](ue_ue.ParticleSystemComponent.md)

#### Defined in

[ue/ue.d.ts:7207](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7207)

___

### SecondsBeforeInactive

• **SecondsBeforeInactive**: `number`

#### Defined in

[ue/ue.d.ts:7218](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7218)

___

### SoloTracking

• **SoloTracking**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`LODSoloTrack`](ue_ue.LODSoloTrack.md)\>

#### Defined in

[ue/ue.d.ts:7247](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7247)

___

### SystemUpdateMode

• **SystemUpdateMode**: [`EParticleSystemUpdateMode`](../enums/ue_ue.EParticleSystemUpdateMode.md)

#### Defined in

[ue/ue.d.ts:7238](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7238)

___

### ThumbnailAngle

• **ThumbnailAngle**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:7208](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7208)

___

### ThumbnailDistance

• **ThumbnailDistance**: `number`

#### Defined in

[ue/ue.d.ts:7209](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7209)

___

### ThumbnailImage

• **ThumbnailImage**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:7233](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7233)

___

### ThumbnailImageOutOfDate

• **ThumbnailImageOutOfDate**: `boolean`

#### Defined in

[ue/ue.d.ts:7232](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7232)

___

### ThumbnailWarmup

• **ThumbnailWarmup**: `number`

#### Defined in

[ue/ue.d.ts:7210](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7210)

___

### UpdateTime\_Delta

• **UpdateTime\_Delta**: `number`

#### Defined in

[ue/ue.d.ts:7203](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7203)

___

### UpdateTime\_FPS

• **UpdateTime\_FPS**: `number`

#### Defined in

[ue/ue.d.ts:7202](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7202)

___

### WarmupTickRate

• **WarmupTickRate**: `number`

#### Defined in

[ue/ue.d.ts:7205](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7205)

___

### WarmupTime

• **WarmupTime**: `number`

#### Defined in

[ue/ue.d.ts:7204](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7204)

___

### \_\_tid\_FXSystemAsset\_\_

• **\_\_tid\_FXSystemAsset\_\_**: `boolean`

#### Inherited from

[FXSystemAsset](ue_ue.FXSystemAsset.md).[__tid_FXSystemAsset__](ue_ue.FXSystemAsset.md#__tid_fxsystemasset__)

#### Defined in

[ue/ue.d.ts:6710](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6710)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[FXSystemAsset](ue_ue.FXSystemAsset.md).[__tid_Object__](ue_ue.FXSystemAsset.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_ParticleSystem\_\_

• **\_\_tid\_ParticleSystem\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:7254](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7254)

___

### bAllowManagedTicking

• **bAllowManagedTicking**: `boolean`

#### Defined in

[ue/ue.d.ts:7235](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7235)

___

### bAutoDeactivate

• **bAutoDeactivate**: `boolean`

#### Defined in

[ue/ue.d.ts:7236](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7236)

___

### bHasPhysics

• **bHasPhysics**: `boolean`

#### Defined in

[ue/ue.d.ts:7230](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7230)

___

### bOrientZAxisTowardCamera

• **bOrientZAxisTowardCamera**: `boolean`

#### Defined in

[ue/ue.d.ts:7227](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7227)

___

### bRegenerateLODDuplicate

• **bRegenerateLODDuplicate**: `boolean`

#### Defined in

[ue/ue.d.ts:7237](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7237)

___

### bShouldResetPeakCounts

• **bShouldResetPeakCounts**: `boolean`

#### Defined in

[ue/ue.d.ts:7229](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7229)

___

### bUseDelayRange

• **bUseDelayRange**: `boolean`

#### Defined in

[ue/ue.d.ts:7234](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7234)

___

### bUseFixedRelativeBoundingBox

• **bUseFixedRelativeBoundingBox**: `boolean`

#### Defined in

[ue/ue.d.ts:7228](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7228)

___

### bUseRealtimeThumbnail

• **bUseRealtimeThumbnail**: `boolean`

#### Defined in

[ue/ue.d.ts:7231](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7231)

## Methods

### ContainsEmitterType

▸ **ContainsEmitterType**(`TypeData`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `TypeData` | [`$Nullable`](../modules/puerts.md#$nullable)<[`Class`](ue_ue.Class.md)\> |

#### Returns

`boolean`

#### Defined in

[ue/ue.d.ts:7249](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7249)

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

[FXSystemAsset](ue_ue.FXSystemAsset.md).[ExecuteUbergraph](ue_ue.FXSystemAsset.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[FXSystemAsset](ue_ue.FXSystemAsset.md).[GetClass](ue_ue.FXSystemAsset.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[FXSystemAsset](ue_ue.FXSystemAsset.md).[GetName](ue_ue.FXSystemAsset.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[FXSystemAsset](ue_ue.FXSystemAsset.md).[GetOuter](ue_ue.FXSystemAsset.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[FXSystemAsset](ue_ue.FXSystemAsset.md).[GetWorld](ue_ue.FXSystemAsset.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

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

#### Defined in

[ue/ue.d.ts:7251](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7251)

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

#### Defined in

[ue/ue.d.ts:7252](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7252)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[FXSystemAsset](ue_ue.FXSystemAsset.md).[StaticClass](ue_ue.FXSystemAsset.md#staticclass)

#### Defined in

[ue/ue.d.ts:7250](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L7250)
