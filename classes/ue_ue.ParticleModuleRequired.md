[yug_typings](../README.md) / [Modules](../modules.md) / [ue/ue](../modules/ue_ue.md) / ParticleModuleRequired

# Class: ParticleModuleRequired

[ue/ue](../modules/ue_ue.md).ParticleModuleRequired

## Hierarchy

- [`ParticleModule`](ue_ue.ParticleModule.md)

  ↳ **`ParticleModuleRequired`**

## Table of contents

### Constructors

- [constructor](ue_ue.ParticleModuleRequired.md#constructor)

### Properties

- [AlphaThreshold](ue_ue.ParticleModuleRequired.md#alphathreshold)
- [BoundingMode](ue_ue.ParticleModuleRequired.md#boundingmode)
- [BurstList](ue_ue.ParticleModuleRequired.md#burstlist)
- [CutoutTexture](ue_ue.ParticleModuleRequired.md#cutouttexture)
- [EmitterDelay](ue_ue.ParticleModuleRequired.md#emitterdelay)
- [EmitterDelayLow](ue_ue.ParticleModuleRequired.md#emitterdelaylow)
- [EmitterDuration](ue_ue.ParticleModuleRequired.md#emitterduration)
- [EmitterDurationLow](ue_ue.ParticleModuleRequired.md#emitterdurationlow)
- [EmitterLoops](ue_ue.ParticleModuleRequired.md#emitterloops)
- [EmitterNormalsMode](ue_ue.ParticleModuleRequired.md#emitternormalsmode)
- [EmitterOrigin](ue_ue.ParticleModuleRequired.md#emitterorigin)
- [EmitterRotation](ue_ue.ParticleModuleRequired.md#emitterrotation)
- [InterpolationMethod](ue_ue.ParticleModuleRequired.md#interpolationmethod)
- [LODDuplicate](ue_ue.ParticleModuleRequired.md#lodduplicate)
- [LODValidity](ue_ue.ParticleModuleRequired.md#lodvalidity)
- [MacroUVPosition](ue_ue.ParticleModuleRequired.md#macrouvposition)
- [MacroUVRadius](ue_ue.ParticleModuleRequired.md#macrouvradius)
- [Material](ue_ue.ParticleModuleRequired.md#material)
- [MaxDrawCount](ue_ue.ParticleModuleRequired.md#maxdrawcount)
- [MaxFacingCameraBlendDistance](ue_ue.ParticleModuleRequired.md#maxfacingcamerablenddistance)
- [MinFacingCameraBlendDistance](ue_ue.ParticleModuleRequired.md#minfacingcamerablenddistance)
- [ModuleEditorColor](ue_ue.ParticleModuleRequired.md#moduleeditorcolor)
- [NamedMaterialOverrides](ue_ue.ParticleModuleRequired.md#namedmaterialoverrides)
- [NormalsCylinderDirection](ue_ue.ParticleModuleRequired.md#normalscylinderdirection)
- [NormalsSphereCenter](ue_ue.ParticleModuleRequired.md#normalsspherecenter)
- [OpacitySourceMode](ue_ue.ParticleModuleRequired.md#opacitysourcemode)
- [ParticleBurstMethod](ue_ue.ParticleModuleRequired.md#particleburstmethod)
- [RandomImageChanges](ue_ue.ParticleModuleRequired.md#randomimagechanges)
- [RandomImageTime](ue_ue.ParticleModuleRequired.md#randomimagetime)
- [ScreenAlignment](ue_ue.ParticleModuleRequired.md#screenalignment)
- [SortMode](ue_ue.ParticleModuleRequired.md#sortmode)
- [SpawnRate](ue_ue.ParticleModuleRequired.md#spawnrate)
- [SubImages\_Horizontal](ue_ue.ParticleModuleRequired.md#subimages_horizontal)
- [SubImages\_Vertical](ue_ue.ParticleModuleRequired.md#subimages_vertical)
- [UVFlippingMode](ue_ue.ParticleModuleRequired.md#uvflippingmode)
- [\_\_tid\_Object\_\_](ue_ue.ParticleModuleRequired.md#__tid_object__)
- [\_\_tid\_ParticleModuleRequired\_\_](ue_ue.ParticleModuleRequired.md#__tid_particlemodulerequired__)
- [\_\_tid\_ParticleModule\_\_](ue_ue.ParticleModuleRequired.md#__tid_particlemodule__)
- [b3DDrawMode](ue_ue.ParticleModuleRequired.md#b3ddrawmode)
- [bCurvesAsColor](ue_ue.ParticleModuleRequired.md#bcurvesascolor)
- [bDelayFirstLoopOnly](ue_ue.ParticleModuleRequired.md#bdelayfirstlooponly)
- [bDurationRecalcEachLoop](ue_ue.ParticleModuleRequired.md#bdurationrecalceachloop)
- [bEditable](ue_ue.ParticleModuleRequired.md#beditable)
- [bEmitterDelayUseRange](ue_ue.ParticleModuleRequired.md#bemitterdelayuserange)
- [bEmitterDurationUseRange](ue_ue.ParticleModuleRequired.md#bemitterdurationuserange)
- [bEnabled](ue_ue.ParticleModuleRequired.md#benabled)
- [bFinalUpdateModule](ue_ue.ParticleModuleRequired.md#bfinalupdatemodule)
- [bKillOnCompleted](ue_ue.ParticleModuleRequired.md#bkilloncompleted)
- [bKillOnDeactivate](ue_ue.ParticleModuleRequired.md#bkillondeactivate)
- [bOrbitModuleAffectsVelocityAlignment](ue_ue.ParticleModuleRequired.md#borbitmoduleaffectsvelocityalignment)
- [bOverrideSystemMacroUV](ue_ue.ParticleModuleRequired.md#boverridesystemmacrouv)
- [bRemoveHMDRoll](ue_ue.ParticleModuleRequired.md#bremovehmdroll)
- [bRequiresLoopingNotification](ue_ue.ParticleModuleRequired.md#brequiresloopingnotification)
- [bScaleUV](ue_ue.ParticleModuleRequired.md#bscaleuv)
- [bSpawnModule](ue_ue.ParticleModuleRequired.md#bspawnmodule)
- [bSupported3DDrawMode](ue_ue.ParticleModuleRequired.md#bsupported3ddrawmode)
- [bSupportsRandomSeed](ue_ue.ParticleModuleRequired.md#bsupportsrandomseed)
- [bUpdateForGPUEmitter](ue_ue.ParticleModuleRequired.md#bupdateforgpuemitter)
- [bUpdateModule](ue_ue.ParticleModuleRequired.md#bupdatemodule)
- [bUseLegacyEmitterTime](ue_ue.ParticleModuleRequired.md#buselegacyemittertime)
- [bUseLocalSpace](ue_ue.ParticleModuleRequired.md#buselocalspace)
- [bUseMaxDrawCount](ue_ue.ParticleModuleRequired.md#busemaxdrawcount)

### Methods

- [CreateDefaultSubobject](ue_ue.ParticleModuleRequired.md#createdefaultsubobject)
- [ExecuteUbergraph](ue_ue.ParticleModuleRequired.md#executeubergraph)
- [GetClass](ue_ue.ParticleModuleRequired.md#getclass)
- [GetName](ue_ue.ParticleModuleRequired.md#getname)
- [GetOuter](ue_ue.ParticleModuleRequired.md#getouter)
- [GetWorld](ue_ue.ParticleModuleRequired.md#getworld)
- [Find](ue_ue.ParticleModuleRequired.md#find)
- [Load](ue_ue.ParticleModuleRequired.md#load)
- [StaticClass](ue_ue.ParticleModuleRequired.md#staticclass)

## Constructors

### constructor

• **new ParticleModuleRequired**(`Outer?`, `Name?`, `ObjectFlags?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `Outer?` | [`Object`](ue_ue.Object.md) |
| `Name?` | `string` |
| `ObjectFlags?` | `number` |

#### Overrides

[ParticleModule](ue_ue.ParticleModule.md).[constructor](ue_ue.ParticleModule.md#constructor)

#### Defined in

[ue/ue.d.ts:6845](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6845)

## Properties

### AlphaThreshold

• **AlphaThreshold**: `number`

#### Defined in

[ue/ue.d.ts:6884](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6884)

___

### BoundingMode

• **BoundingMode**: [`ESubUVBoundingVertexCount`](../enums/ue_ue.ESubUVBoundingVertexCount.md)

#### Defined in

[ue/ue.d.ts:6881](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6881)

___

### BurstList

• **BurstList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleBurst`](ue_ue.ParticleBurst.md)\>

#### Defined in

[ue/ue.d.ts:6861](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6861)

___

### CutoutTexture

• **CutoutTexture**: [`Texture2D`](ue_ue.Texture2D.md)

#### Defined in

[ue/ue.d.ts:6886](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6886)

___

### EmitterDelay

• **EmitterDelay**: `number`

#### Defined in

[ue/ue.d.ts:6862](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6862)

___

### EmitterDelayLow

• **EmitterDelayLow**: `number`

#### Defined in

[ue/ue.d.ts:6863](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6863)

___

### EmitterDuration

• **EmitterDuration**: `number`

#### Defined in

[ue/ue.d.ts:6859](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6859)

___

### EmitterDurationLow

• **EmitterDurationLow**: `number`

#### Defined in

[ue/ue.d.ts:6888](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6888)

___

### EmitterLoops

• **EmitterLoops**: `number`

#### Defined in

[ue/ue.d.ts:6885](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6885)

___

### EmitterNormalsMode

• **EmitterNormalsMode**: [`EEmitterNormalsMode`](../enums/ue_ue.EEmitterNormalsMode.md)

#### Defined in

[ue/ue.d.ts:6872](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6872)

___

### EmitterOrigin

• **EmitterOrigin**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:6849](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6849)

___

### EmitterRotation

• **EmitterRotation**: [`Rotator`](ue_ue_s.Rotator.md)

#### Defined in

[ue/ue.d.ts:6850](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6850)

___

### InterpolationMethod

• **InterpolationMethod**: [`EParticleSubUVInterpMethod`](../enums/ue_ue.EParticleSubUVInterpMethod.md)

#### Defined in

[ue/ue.d.ts:6865](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6865)

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[LODDuplicate](ue_ue.ParticleModule.md#lodduplicate)

#### Defined in

[ue/ue.d.ts:6745](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6745)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[LODValidity](ue_ue.ParticleModule.md#lodvalidity)

#### Defined in

[ue/ue.d.ts:6748](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6748)

___

### MacroUVPosition

• **MacroUVPosition**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:6878](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6878)

___

### MacroUVRadius

• **MacroUVRadius**: `number`

#### Defined in

[ue/ue.d.ts:6879](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6879)

___

### Material

• **Material**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

#### Defined in

[ue/ue.d.ts:6846](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6846)

___

### MaxDrawCount

• **MaxDrawCount**: `number`

#### Defined in

[ue/ue.d.ts:6887](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6887)

___

### MaxFacingCameraBlendDistance

• **MaxFacingCameraBlendDistance**: `number`

#### Defined in

[ue/ue.d.ts:6848](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6848)

___

### MinFacingCameraBlendDistance

• **MinFacingCameraBlendDistance**: `number`

#### Defined in

[ue/ue.d.ts:6847](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6847)

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[ModuleEditorColor](ue_ue.ParticleModule.md#moduleeditorcolor)

#### Defined in

[ue/ue.d.ts:6749](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6749)

___

### NamedMaterialOverrides

• **NamedMaterialOverrides**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

#### Defined in

[ue/ue.d.ts:6890](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6890)

___

### NormalsCylinderDirection

• **NormalsCylinderDirection**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:6889](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6889)

___

### NormalsSphereCenter

• **NormalsSphereCenter**: [`Vector`](ue_ue_s.Vector.md)

#### Defined in

[ue/ue.d.ts:6883](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6883)

___

### OpacitySourceMode

• **OpacitySourceMode**: [`EOpacitySourceMode`](../enums/ue_ue.EOpacitySourceMode.md)

#### Defined in

[ue/ue.d.ts:6871](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6871)

___

### ParticleBurstMethod

• **ParticleBurstMethod**: [`EParticleBurstMethod`](../enums/ue_ue.EParticleBurstMethod.md)

#### Defined in

[ue/ue.d.ts:6868](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6868)

___

### RandomImageChanges

• **RandomImageChanges**: `number`

#### Defined in

[ue/ue.d.ts:6877](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6877)

___

### RandomImageTime

• **RandomImageTime**: `number`

#### Defined in

[ue/ue.d.ts:6876](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6876)

___

### ScreenAlignment

• **ScreenAlignment**: [`EParticleScreenAlignment`](../enums/ue_ue.EParticleScreenAlignment.md)

#### Defined in

[ue/ue.d.ts:6851](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6851)

___

### SortMode

• **SortMode**: [`EParticleSortMode`](../enums/ue_ue.EParticleSortMode.md)

#### Defined in

[ue/ue.d.ts:6855](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6855)

___

### SpawnRate

• **SpawnRate**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

#### Defined in

[ue/ue.d.ts:6860](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6860)

___

### SubImages\_Horizontal

• **SubImages\_Horizontal**: `number`

#### Defined in

[ue/ue.d.ts:6874](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6874)

___

### SubImages\_Vertical

• **SubImages\_Vertical**: `number`

#### Defined in

[ue/ue.d.ts:6875](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6875)

___

### UVFlippingMode

• **UVFlippingMode**: [`EParticleUVFlipMode`](../enums/ue_ue.EParticleUVFlipMode.md)

#### Defined in

[ue/ue.d.ts:6880](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6880)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[__tid_Object__](ue_ue.ParticleModule.md#__tid_object__)

#### Defined in

[ue/ue.d.ts:21](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L21)

___

### \_\_tid\_ParticleModuleRequired\_\_

• **\_\_tid\_ParticleModuleRequired\_\_**: `boolean`

#### Defined in

[ue/ue.d.ts:6895](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6895)

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[__tid_ParticleModule__](ue_ue.ParticleModule.md#__tid_particlemodule__)

#### Defined in

[ue/ue.d.ts:6754](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6754)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[b3DDrawMode](ue_ue.ParticleModule.md#b3ddrawmode)

#### Defined in

[ue/ue.d.ts:6741](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6741)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bCurvesAsColor](ue_ue.ParticleModule.md#bcurvesascolor)

#### Defined in

[ue/ue.d.ts:6740](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6740)

___

### bDelayFirstLoopOnly

• **bDelayFirstLoopOnly**: `boolean`

#### Defined in

[ue/ue.d.ts:6864](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6864)

___

### bDurationRecalcEachLoop

• **bDurationRecalcEachLoop**: `boolean`

#### Defined in

[ue/ue.d.ts:6882](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6882)

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bEditable](ue_ue.ParticleModule.md#beditable)

#### Defined in

[ue/ue.d.ts:6744](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6744)

___

### bEmitterDelayUseRange

• **bEmitterDelayUseRange**: `boolean`

#### Defined in

[ue/ue.d.ts:6867](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6867)

___

### bEmitterDurationUseRange

• **bEmitterDurationUseRange**: `boolean`

#### Defined in

[ue/ue.d.ts:6858](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6858)

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bEnabled](ue_ue.ParticleModule.md#benabled)

#### Defined in

[ue/ue.d.ts:6743](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6743)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bFinalUpdateModule](ue_ue.ParticleModule.md#bfinalupdatemodule)

#### Defined in

[ue/ue.d.ts:6738](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6738)

___

### bKillOnCompleted

• **bKillOnCompleted**: `boolean`

#### Defined in

[ue/ue.d.ts:6854](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6854)

___

### bKillOnDeactivate

• **bKillOnDeactivate**: `boolean`

#### Defined in

[ue/ue.d.ts:6853](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6853)

___

### bOrbitModuleAffectsVelocityAlignment

• **bOrbitModuleAffectsVelocityAlignment**: `boolean`

#### Defined in

[ue/ue.d.ts:6873](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6873)

___

### bOverrideSystemMacroUV

• **bOverrideSystemMacroUV**: `boolean`

#### Defined in

[ue/ue.d.ts:6869](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6869)

___

### bRemoveHMDRoll

• **bRemoveHMDRoll**: `boolean`

#### Defined in

[ue/ue.d.ts:6857](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6857)

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bRequiresLoopingNotification](ue_ue.ParticleModule.md#brequiresloopingnotification)

#### Defined in

[ue/ue.d.ts:6747](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6747)

___

### bScaleUV

• **bScaleUV**: `boolean`

#### Defined in

[ue/ue.d.ts:6866](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6866)

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bSpawnModule](ue_ue.ParticleModule.md#bspawnmodule)

#### Defined in

[ue/ue.d.ts:6736](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6736)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bSupported3DDrawMode](ue_ue.ParticleModule.md#bsupported3ddrawmode)

#### Defined in

[ue/ue.d.ts:6742](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6742)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bSupportsRandomSeed](ue_ue.ParticleModule.md#bsupportsrandomseed)

#### Defined in

[ue/ue.d.ts:6746](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6746)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bUpdateForGPUEmitter](ue_ue.ParticleModule.md#bupdateforgpuemitter)

#### Defined in

[ue/ue.d.ts:6739](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6739)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bUpdateModule](ue_ue.ParticleModule.md#bupdatemodule)

#### Defined in

[ue/ue.d.ts:6737](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6737)

___

### bUseLegacyEmitterTime

• **bUseLegacyEmitterTime**: `boolean`

#### Defined in

[ue/ue.d.ts:6856](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6856)

___

### bUseLocalSpace

• **bUseLocalSpace**: `boolean`

#### Defined in

[ue/ue.d.ts:6852](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6852)

___

### bUseMaxDrawCount

• **bUseMaxDrawCount**: `boolean`

#### Defined in

[ue/ue.d.ts:6870](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6870)

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

[ParticleModule](ue_ue.ParticleModule.md).[CreateDefaultSubobject](ue_ue.ParticleModule.md#createdefaultsubobject)

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

[ParticleModule](ue_ue.ParticleModule.md).[ExecuteUbergraph](ue_ue.ParticleModule.md#executeubergraph)

#### Defined in

[ue/ue.d.ts:12](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L12)

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[GetClass](ue_ue.ParticleModule.md#getclass)

#### Defined in

[ue/ue.d.ts:13](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L13)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[GetName](ue_ue.ParticleModule.md#getname)

#### Defined in

[ue/ue.d.ts:14](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L14)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[GetOuter](ue_ue.ParticleModule.md#getouter)

#### Defined in

[ue/ue.d.ts:15](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L15)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[GetWorld](ue_ue.ParticleModule.md#getworld)

#### Defined in

[ue/ue.d.ts:16](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L16)

___

### Find

▸ `Static` **Find**(`OrigInName`, `Outer?`): [`ParticleModuleRequired`](ue_ue.ParticleModuleRequired.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `OrigInName` | `string` |
| `Outer?` | [`Object`](ue_ue.Object.md) |

#### Returns

[`ParticleModuleRequired`](ue_ue.ParticleModuleRequired.md)

#### Overrides

[ParticleModule](ue_ue.ParticleModule.md).[Find](ue_ue.ParticleModule.md#find)

#### Defined in

[ue/ue.d.ts:6892](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6892)

___

### Load

▸ `Static` **Load**(`InName`): [`ParticleModuleRequired`](ue_ue.ParticleModuleRequired.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `InName` | `string` |

#### Returns

[`ParticleModuleRequired`](ue_ue.ParticleModuleRequired.md)

#### Overrides

[ParticleModule](ue_ue.ParticleModule.md).[Load](ue_ue.ParticleModule.md#load)

#### Defined in

[ue/ue.d.ts:6893](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6893)

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModule](ue_ue.ParticleModule.md).[StaticClass](ue_ue.ParticleModule.md#staticclass)

#### Defined in

[ue/ue.d.ts:6891](https://github.com/YugMetaverse/yug_typings/blob/25cad34/ue/ue.d.ts#L6891)
