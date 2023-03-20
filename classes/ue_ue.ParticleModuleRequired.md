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

## Properties

### AlphaThreshold

• **AlphaThreshold**: `number`

___

### BoundingMode

• **BoundingMode**: [`ESubUVBoundingVertexCount`](../enums/ue_ue.ESubUVBoundingVertexCount.md)

___

### BurstList

• **BurstList**: [`TArray`](../interfaces/ue_puerts.TArray.md)<[`ParticleBurst`](ue_ue.ParticleBurst.md)\>

___

### CutoutTexture

• **CutoutTexture**: [`Texture2D`](ue_ue.Texture2D.md)

___

### EmitterDelay

• **EmitterDelay**: `number`

___

### EmitterDelayLow

• **EmitterDelayLow**: `number`

___

### EmitterDuration

• **EmitterDuration**: `number`

___

### EmitterDurationLow

• **EmitterDurationLow**: `number`

___

### EmitterLoops

• **EmitterLoops**: `number`

___

### EmitterNormalsMode

• **EmitterNormalsMode**: [`EEmitterNormalsMode`](../enums/ue_ue.EEmitterNormalsMode.md)

___

### EmitterOrigin

• **EmitterOrigin**: [`Vector`](ue_ue_s.Vector.md)

___

### EmitterRotation

• **EmitterRotation**: [`Rotator`](ue_ue_s.Rotator.md)

___

### InterpolationMethod

• **InterpolationMethod**: [`EParticleSubUVInterpMethod`](../enums/ue_ue.EParticleSubUVInterpMethod.md)

___

### LODDuplicate

• **LODDuplicate**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[LODDuplicate](ue_ue.ParticleModule.md#lodduplicate)

___

### LODValidity

• **LODValidity**: `number`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[LODValidity](ue_ue.ParticleModule.md#lodvalidity)

___

### MacroUVPosition

• **MacroUVPosition**: [`Vector`](ue_ue_s.Vector.md)

___

### MacroUVRadius

• **MacroUVRadius**: `number`

___

### Material

• **Material**: [`MaterialInterface`](ue_ue.MaterialInterface.md)

___

### MaxDrawCount

• **MaxDrawCount**: `number`

___

### MaxFacingCameraBlendDistance

• **MaxFacingCameraBlendDistance**: `number`

___

### MinFacingCameraBlendDistance

• **MinFacingCameraBlendDistance**: `number`

___

### ModuleEditorColor

• **ModuleEditorColor**: [`Color`](ue_ue_s.Color.md)

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[ModuleEditorColor](ue_ue.ParticleModule.md#moduleeditorcolor)

___

### NamedMaterialOverrides

• **NamedMaterialOverrides**: [`TArray`](../interfaces/ue_puerts.TArray.md)<`string`\>

___

### NormalsCylinderDirection

• **NormalsCylinderDirection**: [`Vector`](ue_ue_s.Vector.md)

___

### NormalsSphereCenter

• **NormalsSphereCenter**: [`Vector`](ue_ue_s.Vector.md)

___

### OpacitySourceMode

• **OpacitySourceMode**: [`EOpacitySourceMode`](../enums/ue_ue.EOpacitySourceMode.md)

___

### ParticleBurstMethod

• **ParticleBurstMethod**: [`EParticleBurstMethod`](../enums/ue_ue.EParticleBurstMethod.md)

___

### RandomImageChanges

• **RandomImageChanges**: `number`

___

### RandomImageTime

• **RandomImageTime**: `number`

___

### ScreenAlignment

• **ScreenAlignment**: [`EParticleScreenAlignment`](../enums/ue_ue.EParticleScreenAlignment.md)

___

### SortMode

• **SortMode**: [`EParticleSortMode`](../enums/ue_ue.EParticleSortMode.md)

___

### SpawnRate

• **SpawnRate**: [`RawDistributionFloat`](ue_ue.RawDistributionFloat.md)

___

### SubImages\_Horizontal

• **SubImages\_Horizontal**: `number`

___

### SubImages\_Vertical

• **SubImages\_Vertical**: `number`

___

### UVFlippingMode

• **UVFlippingMode**: [`EParticleUVFlipMode`](../enums/ue_ue.EParticleUVFlipMode.md)

___

### \_\_tid\_Object\_\_

• **\_\_tid\_Object\_\_**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[__tid_Object__](ue_ue.ParticleModule.md#__tid_object__)

___

### \_\_tid\_ParticleModuleRequired\_\_

• **\_\_tid\_ParticleModuleRequired\_\_**: `boolean`

___

### \_\_tid\_ParticleModule\_\_

• **\_\_tid\_ParticleModule\_\_**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[__tid_ParticleModule__](ue_ue.ParticleModule.md#__tid_particlemodule__)

___

### b3DDrawMode

• **b3DDrawMode**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[b3DDrawMode](ue_ue.ParticleModule.md#b3ddrawmode)

___

### bCurvesAsColor

• **bCurvesAsColor**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bCurvesAsColor](ue_ue.ParticleModule.md#bcurvesascolor)

___

### bDelayFirstLoopOnly

• **bDelayFirstLoopOnly**: `boolean`

___

### bDurationRecalcEachLoop

• **bDurationRecalcEachLoop**: `boolean`

___

### bEditable

• **bEditable**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bEditable](ue_ue.ParticleModule.md#beditable)

___

### bEmitterDelayUseRange

• **bEmitterDelayUseRange**: `boolean`

___

### bEmitterDurationUseRange

• **bEmitterDurationUseRange**: `boolean`

___

### bEnabled

• **bEnabled**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bEnabled](ue_ue.ParticleModule.md#benabled)

___

### bFinalUpdateModule

• **bFinalUpdateModule**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bFinalUpdateModule](ue_ue.ParticleModule.md#bfinalupdatemodule)

___

### bKillOnCompleted

• **bKillOnCompleted**: `boolean`

___

### bKillOnDeactivate

• **bKillOnDeactivate**: `boolean`

___

### bOrbitModuleAffectsVelocityAlignment

• **bOrbitModuleAffectsVelocityAlignment**: `boolean`

___

### bOverrideSystemMacroUV

• **bOverrideSystemMacroUV**: `boolean`

___

### bRemoveHMDRoll

• **bRemoveHMDRoll**: `boolean`

___

### bRequiresLoopingNotification

• **bRequiresLoopingNotification**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bRequiresLoopingNotification](ue_ue.ParticleModule.md#brequiresloopingnotification)

___

### bScaleUV

• **bScaleUV**: `boolean`

___

### bSpawnModule

• **bSpawnModule**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bSpawnModule](ue_ue.ParticleModule.md#bspawnmodule)

___

### bSupported3DDrawMode

• **bSupported3DDrawMode**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bSupported3DDrawMode](ue_ue.ParticleModule.md#bsupported3ddrawmode)

___

### bSupportsRandomSeed

• **bSupportsRandomSeed**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bSupportsRandomSeed](ue_ue.ParticleModule.md#bsupportsrandomseed)

___

### bUpdateForGPUEmitter

• **bUpdateForGPUEmitter**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bUpdateForGPUEmitter](ue_ue.ParticleModule.md#bupdateforgpuemitter)

___

### bUpdateModule

• **bUpdateModule**: `boolean`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[bUpdateModule](ue_ue.ParticleModule.md#bupdatemodule)

___

### bUseLegacyEmitterTime

• **bUseLegacyEmitterTime**: `boolean`

___

### bUseLocalSpace

• **bUseLocalSpace**: `boolean`

___

### bUseMaxDrawCount

• **bUseMaxDrawCount**: `boolean`

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

___

### GetClass

▸ **GetClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[GetClass](ue_ue.ParticleModule.md#getclass)

___

### GetName

▸ **GetName**(): `string`

#### Returns

`string`

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[GetName](ue_ue.ParticleModule.md#getname)

___

### GetOuter

▸ **GetOuter**(): [`Object`](ue_ue.Object.md)

#### Returns

[`Object`](ue_ue.Object.md)

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[GetOuter](ue_ue.ParticleModule.md#getouter)

___

### GetWorld

▸ **GetWorld**(): [`World`](ue_ue.World.md)

#### Returns

[`World`](ue_ue.World.md)

#### Inherited from

[ParticleModule](ue_ue.ParticleModule.md).[GetWorld](ue_ue.ParticleModule.md#getworld)

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

___

### StaticClass

▸ `Static` **StaticClass**(): [`Class`](ue_ue.Class.md)

#### Returns

[`Class`](ue_ue.Class.md)

#### Overrides

[ParticleModule](ue_ue.ParticleModule.md).[StaticClass](ue_ue.ParticleModule.md#staticclass)
